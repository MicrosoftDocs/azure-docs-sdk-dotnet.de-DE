<Type Name="IIntegrationRuntimesOperations" FullName="Microsoft.Azure.Management.DataFactory.IIntegrationRuntimesOperations">
  <TypeSignature Language="C#" Value="public interface IIntegrationRuntimesOperations" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IIntegrationRuntimesOperations" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.DataFactory.IIntegrationRuntimesOperations" />
  <TypeSignature Language="VB.NET" Value="Public Interface IIntegrationRuntimesOperations" />
  <TypeSignature Language="F#" Value="type IIntegrationRuntimesOperations = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
    <AssemblyVersion>0.2.0.0</AssemblyVersion>
    <AssemblyVersion>0.3.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="e65a8-101">IntegrationRuntimesOperations-Vorgänge.</span><span class="sxs-lookup"><span data-stu-id="e65a8-101">IntegrationRuntimesOperations operations.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="BeginStartWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.DataFactory.Models.IntegrationRuntimeStatusResponse&gt;&gt; BeginStartWithHttpMessagesAsync (string resourceGroupName, string factoryName, string integrationRuntimeName, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Management.DataFactory.Models.IntegrationRuntimeStatusResponse&gt;&gt; BeginStartWithHttpMessagesAsync(string resourceGroupName, string factoryName, string integrationRuntimeName, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.IIntegrationRuntimesOperations.BeginStartWithHttpMessagesAsync(System.String,System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member BeginStartWithHttpMessagesAsync : string * string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.DataFactory.Models.IntegrationRuntimeStatusResponse&gt;&gt;" Usage="iIntegrationRuntimesOperations.BeginStartWithHttpMessagesAsync (resourceGroupName, factoryName, integrationRuntimeName, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.DataFactory.Models.IntegrationRuntimeStatusResponse&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="factoryName" Type="System.String" />
        <Parameter Name="integrationRuntimeName" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="e65a8-102">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="e65a8-102">The resource group name.</span></span>
            </param>
        <param name="factoryName">
            <span data-ttu-id="e65a8-103">Die Factory-Namen.</span><span class="sxs-lookup"><span data-stu-id="e65a8-103">The factory name.</span></span>
            </param>
        <param name="integrationRuntimeName">
            <span data-ttu-id="e65a8-104">Die Integration Laufzeitklasse-Namen.</span><span class="sxs-lookup"><span data-stu-id="e65a8-104">The integration runtime name.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="e65a8-105">Die Header, die hinzugefügt werden auf Anforderung.</span><span class="sxs-lookup"><span data-stu-id="e65a8-105">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="e65a8-106">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="e65a8-106">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="e65a8-107">Startet eine ManagedReserved Typ integrationslaufzeit an.</span><span class="sxs-lookup"><span data-stu-id="e65a8-107">Starts a ManagedReserved type integration runtime.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Azure.Management.DataFactory.Models.ErrorResponseException">
            <span data-ttu-id="e65a8-108">Wird ausgelöst, wenn der Vorgang einen ungültigen Statuscode zurückgegeben hat.</span><span class="sxs-lookup"><span data-stu-id="e65a8-108">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="e65a8-109">Wird ausgelöst, wenn nicht die Antwort zu deserialisieren.</span><span class="sxs-lookup"><span data-stu-id="e65a8-109">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="e65a8-110">Wird ausgelöst, wenn ein erforderlicher Parameter null ist.</span><span class="sxs-lookup"><span data-stu-id="e65a8-110">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="BeginStopWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt; BeginStopWithHttpMessagesAsync (string resourceGroupName, string factoryName, string integrationRuntimeName, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse&gt; BeginStopWithHttpMessagesAsync(string resourceGroupName, string factoryName, string integrationRuntimeName, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.IIntegrationRuntimesOperations.BeginStopWithHttpMessagesAsync(System.String,System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member BeginStopWithHttpMessagesAsync : string * string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt;" Usage="iIntegrationRuntimesOperations.BeginStopWithHttpMessagesAsync (resourceGroupName, factoryName, integrationRuntimeName, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="factoryName" Type="System.String" />
        <Parameter Name="integrationRuntimeName" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="e65a8-111">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="e65a8-111">The resource group name.</span></span>
            </param>
        <param name="factoryName">
            <span data-ttu-id="e65a8-112">Die Factory-Namen.</span><span class="sxs-lookup"><span data-stu-id="e65a8-112">The factory name.</span></span>
            </param>
        <param name="integrationRuntimeName">
            <span data-ttu-id="e65a8-113">Die Integration Laufzeitklasse-Namen.</span><span class="sxs-lookup"><span data-stu-id="e65a8-113">The integration runtime name.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="e65a8-114">Die Header, die hinzugefügt werden auf Anforderung.</span><span class="sxs-lookup"><span data-stu-id="e65a8-114">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="e65a8-115">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="e65a8-115">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="e65a8-116">Beendet eine ManagedReserved Typ integrationslaufzeit an.</span><span class="sxs-lookup"><span data-stu-id="e65a8-116">Stops a ManagedReserved type integration runtime.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Azure.Management.DataFactory.Models.ErrorResponseException">
            <span data-ttu-id="e65a8-117">Wird ausgelöst, wenn der Vorgang einen ungültigen Statuscode zurückgegeben hat.</span><span class="sxs-lookup"><span data-stu-id="e65a8-117">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="e65a8-118">Wird ausgelöst, wenn ein erforderlicher Parameter null ist.</span><span class="sxs-lookup"><span data-stu-id="e65a8-118">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="CreateOrUpdateWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.DataFactory.Models.IntegrationRuntimeResource&gt;&gt; CreateOrUpdateWithHttpMessagesAsync (string resourceGroupName, string factoryName, string integrationRuntimeName, Microsoft.Azure.Management.DataFactory.Models.IntegrationRuntimeResource integrationRuntime, string ifMatch = null, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Management.DataFactory.Models.IntegrationRuntimeResource&gt;&gt; CreateOrUpdateWithHttpMessagesAsync(string resourceGroupName, string factoryName, string integrationRuntimeName, class Microsoft.Azure.Management.DataFactory.Models.IntegrationRuntimeResource integrationRuntime, string ifMatch, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.IIntegrationRuntimesOperations.CreateOrUpdateWithHttpMessagesAsync(System.String,System.String,System.String,Microsoft.Azure.Management.DataFactory.Models.IntegrationRuntimeResource,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member CreateOrUpdateWithHttpMessagesAsync : string * string * string * Microsoft.Azure.Management.DataFactory.Models.IntegrationRuntimeResource * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.DataFactory.Models.IntegrationRuntimeResource&gt;&gt;" Usage="iIntegrationRuntimesOperations.CreateOrUpdateWithHttpMessagesAsync (resourceGroupName, factoryName, integrationRuntimeName, integrationRuntime, ifMatch, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.DataFactory.Models.IntegrationRuntimeResource&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="factoryName" Type="System.String" />
        <Parameter Name="integrationRuntimeName" Type="System.String" />
        <Parameter Name="integrationRuntime" Type="Microsoft.Azure.Management.DataFactory.Models.IntegrationRuntimeResource" />
        <Parameter Name="ifMatch" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="e65a8-119">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="e65a8-119">The resource group name.</span></span>
            </param>
        <param name="factoryName">
            <span data-ttu-id="e65a8-120">Die Factory-Namen.</span><span class="sxs-lookup"><span data-stu-id="e65a8-120">The factory name.</span></span>
            </param>
        <param name="integrationRuntimeName">
            <span data-ttu-id="e65a8-121">Die Integration Laufzeitklasse-Namen.</span><span class="sxs-lookup"><span data-stu-id="e65a8-121">The integration runtime name.</span></span>
            </param>
        <param name="integrationRuntime">
            <span data-ttu-id="e65a8-122">Integration in Common Language Runtime der Ressourcendefinition.</span><span class="sxs-lookup"><span data-stu-id="e65a8-122">Integration runtime resource definition.</span></span>
            </param>
        <param name="ifMatch">
            <span data-ttu-id="e65a8-123">ETag der Entität der Laufzeit von der Integration.</span><span class="sxs-lookup"><span data-stu-id="e65a8-123">ETag of the integration runtime entity.</span></span> <span data-ttu-id="e65a8-124">Sollte nur angegeben werden, für das Update, für die vorhandene Entität übereinstimmen oder können werden \* für unbedingtes Update.</span><span class="sxs-lookup"><span data-stu-id="e65a8-124">Should only be specified for update, for which it should match existing entity or can be \* for unconditional update.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="e65a8-125">Die Header, die hinzugefügt werden auf Anforderung.</span><span class="sxs-lookup"><span data-stu-id="e65a8-125">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="e65a8-126">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="e65a8-126">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="e65a8-127">Erstellt oder aktualisiert eine integrationslaufzeit.</span><span class="sxs-lookup"><span data-stu-id="e65a8-127">Creates or updates an integration runtime.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Azure.Management.DataFactory.Models.ErrorResponseException">
            <span data-ttu-id="e65a8-128">Wird ausgelöst, wenn der Vorgang einen ungültigen Statuscode zurückgegeben hat.</span><span class="sxs-lookup"><span data-stu-id="e65a8-128">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="e65a8-129">Wird ausgelöst, wenn nicht die Antwort zu deserialisieren.</span><span class="sxs-lookup"><span data-stu-id="e65a8-129">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="e65a8-130">Wird ausgelöst, wenn ein erforderlicher Parameter null ist.</span><span class="sxs-lookup"><span data-stu-id="e65a8-130">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="DeleteWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt; DeleteWithHttpMessagesAsync (string resourceGroupName, string factoryName, string integrationRuntimeName, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse&gt; DeleteWithHttpMessagesAsync(string resourceGroupName, string factoryName, string integrationRuntimeName, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.IIntegrationRuntimesOperations.DeleteWithHttpMessagesAsync(System.String,System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member DeleteWithHttpMessagesAsync : string * string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt;" Usage="iIntegrationRuntimesOperations.DeleteWithHttpMessagesAsync (resourceGroupName, factoryName, integrationRuntimeName, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="factoryName" Type="System.String" />
        <Parameter Name="integrationRuntimeName" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="e65a8-131">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="e65a8-131">The resource group name.</span></span>
            </param>
        <param name="factoryName">
            <span data-ttu-id="e65a8-132">Die Factory-Namen.</span><span class="sxs-lookup"><span data-stu-id="e65a8-132">The factory name.</span></span>
            </param>
        <param name="integrationRuntimeName">
            <span data-ttu-id="e65a8-133">Die Integration Laufzeitklasse-Namen.</span><span class="sxs-lookup"><span data-stu-id="e65a8-133">The integration runtime name.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="e65a8-134">Die Header, die hinzugefügt werden auf Anforderung.</span><span class="sxs-lookup"><span data-stu-id="e65a8-134">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="e65a8-135">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="e65a8-135">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="e65a8-136">Löscht eine integrationslaufzeit an.</span><span class="sxs-lookup"><span data-stu-id="e65a8-136">Deletes an integration runtime.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Azure.Management.DataFactory.Models.ErrorResponseException">
            <span data-ttu-id="e65a8-137">Wird ausgelöst, wenn der Vorgang einen ungültigen Statuscode zurückgegeben hat.</span><span class="sxs-lookup"><span data-stu-id="e65a8-137">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="e65a8-138">Wird ausgelöst, wenn ein erforderlicher Parameter null ist.</span><span class="sxs-lookup"><span data-stu-id="e65a8-138">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="GetConnectionInfoWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.DataFactory.Models.IntegrationRuntimeConnectionInfo&gt;&gt; GetConnectionInfoWithHttpMessagesAsync (string resourceGroupName, string factoryName, string integrationRuntimeName, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Management.DataFactory.Models.IntegrationRuntimeConnectionInfo&gt;&gt; GetConnectionInfoWithHttpMessagesAsync(string resourceGroupName, string factoryName, string integrationRuntimeName, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.IIntegrationRuntimesOperations.GetConnectionInfoWithHttpMessagesAsync(System.String,System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetConnectionInfoWithHttpMessagesAsync : string * string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.DataFactory.Models.IntegrationRuntimeConnectionInfo&gt;&gt;" Usage="iIntegrationRuntimesOperations.GetConnectionInfoWithHttpMessagesAsync (resourceGroupName, factoryName, integrationRuntimeName, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.DataFactory.Models.IntegrationRuntimeConnectionInfo&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="factoryName" Type="System.String" />
        <Parameter Name="integrationRuntimeName" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="e65a8-139">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="e65a8-139">The resource group name.</span></span>
            </param>
        <param name="factoryName">
            <span data-ttu-id="e65a8-140">Die Factory-Namen.</span><span class="sxs-lookup"><span data-stu-id="e65a8-140">The factory name.</span></span>
            </param>
        <param name="integrationRuntimeName">
            <span data-ttu-id="e65a8-141">Die Integration Laufzeitklasse-Namen.</span><span class="sxs-lookup"><span data-stu-id="e65a8-141">The integration runtime name.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="e65a8-142">Die Header, die hinzugefügt werden auf Anforderung.</span><span class="sxs-lookup"><span data-stu-id="e65a8-142">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="e65a8-143">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="e65a8-143">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="e65a8-144">Ruft das lokale Integration Common Language Runtime-Verbindungsinformationen für die Verschlüsselung von lokalen Datenquellen-Anmeldeinformationen ab.</span><span class="sxs-lookup"><span data-stu-id="e65a8-144">Gets the on-premises integration runtime connection information for encrypting the on-premises data source credentials.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Azure.Management.DataFactory.Models.ErrorResponseException">
            <span data-ttu-id="e65a8-145">Wird ausgelöst, wenn der Vorgang einen ungültigen Statuscode zurückgegeben hat.</span><span class="sxs-lookup"><span data-stu-id="e65a8-145">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="e65a8-146">Wird ausgelöst, wenn nicht die Antwort zu deserialisieren.</span><span class="sxs-lookup"><span data-stu-id="e65a8-146">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="e65a8-147">Wird ausgelöst, wenn ein erforderlicher Parameter null ist.</span><span class="sxs-lookup"><span data-stu-id="e65a8-147">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="GetMonitoringDataWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.DataFactory.Models.IntegrationRuntimeMonitoringData&gt;&gt; GetMonitoringDataWithHttpMessagesAsync (string resourceGroupName, string factoryName, string integrationRuntimeName, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Management.DataFactory.Models.IntegrationRuntimeMonitoringData&gt;&gt; GetMonitoringDataWithHttpMessagesAsync(string resourceGroupName, string factoryName, string integrationRuntimeName, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.IIntegrationRuntimesOperations.GetMonitoringDataWithHttpMessagesAsync(System.String,System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetMonitoringDataWithHttpMessagesAsync : string * string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.DataFactory.Models.IntegrationRuntimeMonitoringData&gt;&gt;" Usage="iIntegrationRuntimesOperations.GetMonitoringDataWithHttpMessagesAsync (resourceGroupName, factoryName, integrationRuntimeName, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.DataFactory.Models.IntegrationRuntimeMonitoringData&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="factoryName" Type="System.String" />
        <Parameter Name="integrationRuntimeName" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="e65a8-148">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="e65a8-148">The resource group name.</span></span>
            </param>
        <param name="factoryName">
            <span data-ttu-id="e65a8-149">Die Factory-Namen.</span><span class="sxs-lookup"><span data-stu-id="e65a8-149">The factory name.</span></span>
            </param>
        <param name="integrationRuntimeName">
            <span data-ttu-id="e65a8-150">Die Integration Laufzeitklasse-Namen.</span><span class="sxs-lookup"><span data-stu-id="e65a8-150">The integration runtime name.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="e65a8-151">Die Header, die hinzugefügt werden auf Anforderung.</span><span class="sxs-lookup"><span data-stu-id="e65a8-151">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="e65a8-152">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="e65a8-152">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="e65a8-153">Rufen Sie die Überwachungsdaten, darunter die Überwachungsdaten für alle Knoten unter dieser integrationslaufzeit integrationslaufzeit.</span><span class="sxs-lookup"><span data-stu-id="e65a8-153">Get the integration runtime monitoring data, which includes the monitor data for all the nodes under this integration runtime.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Azure.Management.DataFactory.Models.ErrorResponseException">
            <span data-ttu-id="e65a8-154">Wird ausgelöst, wenn der Vorgang einen ungültigen Statuscode zurückgegeben hat.</span><span class="sxs-lookup"><span data-stu-id="e65a8-154">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="e65a8-155">Wird ausgelöst, wenn nicht die Antwort zu deserialisieren.</span><span class="sxs-lookup"><span data-stu-id="e65a8-155">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="e65a8-156">Wird ausgelöst, wenn ein erforderlicher Parameter null ist.</span><span class="sxs-lookup"><span data-stu-id="e65a8-156">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="GetStatusWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.DataFactory.Models.IntegrationRuntimeStatusResponse&gt;&gt; GetStatusWithHttpMessagesAsync (string resourceGroupName, string factoryName, string integrationRuntimeName, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Management.DataFactory.Models.IntegrationRuntimeStatusResponse&gt;&gt; GetStatusWithHttpMessagesAsync(string resourceGroupName, string factoryName, string integrationRuntimeName, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.IIntegrationRuntimesOperations.GetStatusWithHttpMessagesAsync(System.String,System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetStatusWithHttpMessagesAsync : string * string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.DataFactory.Models.IntegrationRuntimeStatusResponse&gt;&gt;" Usage="iIntegrationRuntimesOperations.GetStatusWithHttpMessagesAsync (resourceGroupName, factoryName, integrationRuntimeName, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.DataFactory.Models.IntegrationRuntimeStatusResponse&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="factoryName" Type="System.String" />
        <Parameter Name="integrationRuntimeName" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="e65a8-157">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="e65a8-157">The resource group name.</span></span>
            </param>
        <param name="factoryName">
            <span data-ttu-id="e65a8-158">Die Factory-Namen.</span><span class="sxs-lookup"><span data-stu-id="e65a8-158">The factory name.</span></span>
            </param>
        <param name="integrationRuntimeName">
            <span data-ttu-id="e65a8-159">Die Integration Laufzeitklasse-Namen.</span><span class="sxs-lookup"><span data-stu-id="e65a8-159">The integration runtime name.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="e65a8-160">Die Header, die hinzugefügt werden auf Anforderung.</span><span class="sxs-lookup"><span data-stu-id="e65a8-160">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="e65a8-161">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="e65a8-161">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="e65a8-162">Ruft ausführliche Statusinformationen für eine integrationslaufzeit.</span><span class="sxs-lookup"><span data-stu-id="e65a8-162">Gets detailed status information for an integration runtime.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Azure.Management.DataFactory.Models.ErrorResponseException">
            <span data-ttu-id="e65a8-163">Wird ausgelöst, wenn der Vorgang einen ungültigen Statuscode zurückgegeben hat.</span><span class="sxs-lookup"><span data-stu-id="e65a8-163">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="e65a8-164">Wird ausgelöst, wenn nicht die Antwort zu deserialisieren.</span><span class="sxs-lookup"><span data-stu-id="e65a8-164">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="e65a8-165">Wird ausgelöst, wenn ein erforderlicher Parameter null ist.</span><span class="sxs-lookup"><span data-stu-id="e65a8-165">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="GetWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.DataFactory.Models.IntegrationRuntimeResource&gt;&gt; GetWithHttpMessagesAsync (string resourceGroupName, string factoryName, string integrationRuntimeName, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Management.DataFactory.Models.IntegrationRuntimeResource&gt;&gt; GetWithHttpMessagesAsync(string resourceGroupName, string factoryName, string integrationRuntimeName, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.IIntegrationRuntimesOperations.GetWithHttpMessagesAsync(System.String,System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetWithHttpMessagesAsync : string * string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.DataFactory.Models.IntegrationRuntimeResource&gt;&gt;" Usage="iIntegrationRuntimesOperations.GetWithHttpMessagesAsync (resourceGroupName, factoryName, integrationRuntimeName, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.DataFactory.Models.IntegrationRuntimeResource&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="factoryName" Type="System.String" />
        <Parameter Name="integrationRuntimeName" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="e65a8-166">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="e65a8-166">The resource group name.</span></span>
            </param>
        <param name="factoryName">
            <span data-ttu-id="e65a8-167">Die Factory-Namen.</span><span class="sxs-lookup"><span data-stu-id="e65a8-167">The factory name.</span></span>
            </param>
        <param name="integrationRuntimeName">
            <span data-ttu-id="e65a8-168">Die Integration Laufzeitklasse-Namen.</span><span class="sxs-lookup"><span data-stu-id="e65a8-168">The integration runtime name.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="e65a8-169">Die Header, die hinzugefügt werden auf Anforderung.</span><span class="sxs-lookup"><span data-stu-id="e65a8-169">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="e65a8-170">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="e65a8-170">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="e65a8-171">Ruft eine integrationslaufzeit ab.</span><span class="sxs-lookup"><span data-stu-id="e65a8-171">Gets an integration runtime.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Azure.Management.DataFactory.Models.ErrorResponseException">
            <span data-ttu-id="e65a8-172">Wird ausgelöst, wenn der Vorgang einen ungültigen Statuscode zurückgegeben hat.</span><span class="sxs-lookup"><span data-stu-id="e65a8-172">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="e65a8-173">Wird ausgelöst, wenn nicht die Antwort zu deserialisieren.</span><span class="sxs-lookup"><span data-stu-id="e65a8-173">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="e65a8-174">Wird ausgelöst, wenn ein erforderlicher Parameter null ist.</span><span class="sxs-lookup"><span data-stu-id="e65a8-174">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="ListAuthKeysWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.DataFactory.Models.IntegrationRuntimeAuthKeys&gt;&gt; ListAuthKeysWithHttpMessagesAsync (string resourceGroupName, string factoryName, string integrationRuntimeName, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Management.DataFactory.Models.IntegrationRuntimeAuthKeys&gt;&gt; ListAuthKeysWithHttpMessagesAsync(string resourceGroupName, string factoryName, string integrationRuntimeName, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.IIntegrationRuntimesOperations.ListAuthKeysWithHttpMessagesAsync(System.String,System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListAuthKeysWithHttpMessagesAsync : string * string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.DataFactory.Models.IntegrationRuntimeAuthKeys&gt;&gt;" Usage="iIntegrationRuntimesOperations.ListAuthKeysWithHttpMessagesAsync (resourceGroupName, factoryName, integrationRuntimeName, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.DataFactory.Models.IntegrationRuntimeAuthKeys&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="factoryName" Type="System.String" />
        <Parameter Name="integrationRuntimeName" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="e65a8-175">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="e65a8-175">The resource group name.</span></span>
            </param>
        <param name="factoryName">
            <span data-ttu-id="e65a8-176">Die Factory-Namen.</span><span class="sxs-lookup"><span data-stu-id="e65a8-176">The factory name.</span></span>
            </param>
        <param name="integrationRuntimeName">
            <span data-ttu-id="e65a8-177">Die Integration Laufzeitklasse-Namen.</span><span class="sxs-lookup"><span data-stu-id="e65a8-177">The integration runtime name.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="e65a8-178">Die Header, die hinzugefügt werden auf Anforderung.</span><span class="sxs-lookup"><span data-stu-id="e65a8-178">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="e65a8-179">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="e65a8-179">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="e65a8-180">Ruft den Authentifizierungsschlüssel von Akamai für eine integrationslaufzeit ab.</span><span class="sxs-lookup"><span data-stu-id="e65a8-180">Retrieves the authentication keys for an integration runtime.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Azure.Management.DataFactory.Models.ErrorResponseException">
            <span data-ttu-id="e65a8-181">Wird ausgelöst, wenn der Vorgang einen ungültigen Statuscode zurückgegeben hat.</span><span class="sxs-lookup"><span data-stu-id="e65a8-181">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="e65a8-182">Wird ausgelöst, wenn nicht die Antwort zu deserialisieren.</span><span class="sxs-lookup"><span data-stu-id="e65a8-182">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="e65a8-183">Wird ausgelöst, wenn ein erforderlicher Parameter null ist.</span><span class="sxs-lookup"><span data-stu-id="e65a8-183">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="ListByFactoryNextWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataFactory.Models.IntegrationRuntimeResource&gt;&gt;&gt; ListByFactoryNextWithHttpMessagesAsync (string nextPageLink, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.DataFactory.Models.IntegrationRuntimeResource&gt;&gt;&gt; ListByFactoryNextWithHttpMessagesAsync(string nextPageLink, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.IIntegrationRuntimesOperations.ListByFactoryNextWithHttpMessagesAsync(System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListByFactoryNextWithHttpMessagesAsync : string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataFactory.Models.IntegrationRuntimeResource&gt;&gt;&gt;" Usage="iIntegrationRuntimesOperations.ListByFactoryNextWithHttpMessagesAsync (nextPageLink, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataFactory.Models.IntegrationRuntimeResource&gt;&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="nextPageLink">
            <span data-ttu-id="e65a8-184">Die "NextLink" aus dem vorherigen erfolgreichen Aufruf List-Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="e65a8-184">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="e65a8-185">Die Header, die hinzugefügt werden auf Anforderung.</span><span class="sxs-lookup"><span data-stu-id="e65a8-185">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="e65a8-186">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="e65a8-186">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="e65a8-187">Listet Integration Laufzeiten.</span><span class="sxs-lookup"><span data-stu-id="e65a8-187">Lists integration runtimes.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Azure.Management.DataFactory.Models.ErrorResponseException">
            <span data-ttu-id="e65a8-188">Wird ausgelöst, wenn der Vorgang einen ungültigen Statuscode zurückgegeben hat.</span><span class="sxs-lookup"><span data-stu-id="e65a8-188">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="e65a8-189">Wird ausgelöst, wenn nicht die Antwort zu deserialisieren.</span><span class="sxs-lookup"><span data-stu-id="e65a8-189">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="e65a8-190">Wird ausgelöst, wenn ein erforderlicher Parameter null ist.</span><span class="sxs-lookup"><span data-stu-id="e65a8-190">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="ListByFactoryWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataFactory.Models.IntegrationRuntimeResource&gt;&gt;&gt; ListByFactoryWithHttpMessagesAsync (string resourceGroupName, string factoryName, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.DataFactory.Models.IntegrationRuntimeResource&gt;&gt;&gt; ListByFactoryWithHttpMessagesAsync(string resourceGroupName, string factoryName, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.IIntegrationRuntimesOperations.ListByFactoryWithHttpMessagesAsync(System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListByFactoryWithHttpMessagesAsync : string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataFactory.Models.IntegrationRuntimeResource&gt;&gt;&gt;" Usage="iIntegrationRuntimesOperations.ListByFactoryWithHttpMessagesAsync (resourceGroupName, factoryName, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataFactory.Models.IntegrationRuntimeResource&gt;&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="factoryName" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="e65a8-191">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="e65a8-191">The resource group name.</span></span>
            </param>
        <param name="factoryName">
            <span data-ttu-id="e65a8-192">Die Factory-Namen.</span><span class="sxs-lookup"><span data-stu-id="e65a8-192">The factory name.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="e65a8-193">Die Header, die hinzugefügt werden auf Anforderung.</span><span class="sxs-lookup"><span data-stu-id="e65a8-193">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="e65a8-194">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="e65a8-194">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="e65a8-195">Listet Integration Laufzeiten.</span><span class="sxs-lookup"><span data-stu-id="e65a8-195">Lists integration runtimes.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Azure.Management.DataFactory.Models.ErrorResponseException">
            <span data-ttu-id="e65a8-196">Wird ausgelöst, wenn der Vorgang einen ungültigen Statuscode zurückgegeben hat.</span><span class="sxs-lookup"><span data-stu-id="e65a8-196">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="e65a8-197">Wird ausgelöst, wenn nicht die Antwort zu deserialisieren.</span><span class="sxs-lookup"><span data-stu-id="e65a8-197">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="e65a8-198">Wird ausgelöst, wenn ein erforderlicher Parameter null ist.</span><span class="sxs-lookup"><span data-stu-id="e65a8-198">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="RegenerateAuthKeyWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.DataFactory.Models.IntegrationRuntimeAuthKeys&gt;&gt; RegenerateAuthKeyWithHttpMessagesAsync (string resourceGroupName, string factoryName, string integrationRuntimeName, Microsoft.Azure.Management.DataFactory.Models.IntegrationRuntimeRegenerateKeyParameters regenerateKeyParameters, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Management.DataFactory.Models.IntegrationRuntimeAuthKeys&gt;&gt; RegenerateAuthKeyWithHttpMessagesAsync(string resourceGroupName, string factoryName, string integrationRuntimeName, class Microsoft.Azure.Management.DataFactory.Models.IntegrationRuntimeRegenerateKeyParameters regenerateKeyParameters, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.IIntegrationRuntimesOperations.RegenerateAuthKeyWithHttpMessagesAsync(System.String,System.String,System.String,Microsoft.Azure.Management.DataFactory.Models.IntegrationRuntimeRegenerateKeyParameters,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member RegenerateAuthKeyWithHttpMessagesAsync : string * string * string * Microsoft.Azure.Management.DataFactory.Models.IntegrationRuntimeRegenerateKeyParameters * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.DataFactory.Models.IntegrationRuntimeAuthKeys&gt;&gt;" Usage="iIntegrationRuntimesOperations.RegenerateAuthKeyWithHttpMessagesAsync (resourceGroupName, factoryName, integrationRuntimeName, regenerateKeyParameters, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.DataFactory.Models.IntegrationRuntimeAuthKeys&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="factoryName" Type="System.String" />
        <Parameter Name="integrationRuntimeName" Type="System.String" />
        <Parameter Name="regenerateKeyParameters" Type="Microsoft.Azure.Management.DataFactory.Models.IntegrationRuntimeRegenerateKeyParameters" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="e65a8-199">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="e65a8-199">The resource group name.</span></span>
            </param>
        <param name="factoryName">
            <span data-ttu-id="e65a8-200">Die Factory-Namen.</span><span class="sxs-lookup"><span data-stu-id="e65a8-200">The factory name.</span></span>
            </param>
        <param name="integrationRuntimeName">
            <span data-ttu-id="e65a8-201">Die Integration Laufzeitklasse-Namen.</span><span class="sxs-lookup"><span data-stu-id="e65a8-201">The integration runtime name.</span></span>
            </param>
        <param name="regenerateKeyParameters">
            <span data-ttu-id="e65a8-202">Die Parameter für die erneute Generierung Integration Common Language Runtime-Authentifizierungsschlüssel.</span><span class="sxs-lookup"><span data-stu-id="e65a8-202">The parameters for regenerating integration runtime authentication key.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="e65a8-203">Die Header, die hinzugefügt werden auf Anforderung.</span><span class="sxs-lookup"><span data-stu-id="e65a8-203">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="e65a8-204">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="e65a8-204">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="e65a8-205">Generiert einen neuen Authentifizierungsschlüssel für eine integrationslaufzeit.</span><span class="sxs-lookup"><span data-stu-id="e65a8-205">Regenerates the authentication key for an integration runtime.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Azure.Management.DataFactory.Models.ErrorResponseException">
            <span data-ttu-id="e65a8-206">Wird ausgelöst, wenn der Vorgang einen ungültigen Statuscode zurückgegeben hat.</span><span class="sxs-lookup"><span data-stu-id="e65a8-206">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="e65a8-207">Wird ausgelöst, wenn nicht die Antwort zu deserialisieren.</span><span class="sxs-lookup"><span data-stu-id="e65a8-207">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="e65a8-208">Wird ausgelöst, wenn ein erforderlicher Parameter null ist.</span><span class="sxs-lookup"><span data-stu-id="e65a8-208">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="RemoveNodeWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt; RemoveNodeWithHttpMessagesAsync (string resourceGroupName, string factoryName, string integrationRuntimeName, Microsoft.Azure.Management.DataFactory.Models.IntegrationRuntimeRemoveNodeRequest removeNodeParameters, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse&gt; RemoveNodeWithHttpMessagesAsync(string resourceGroupName, string factoryName, string integrationRuntimeName, class Microsoft.Azure.Management.DataFactory.Models.IntegrationRuntimeRemoveNodeRequest removeNodeParameters, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.IIntegrationRuntimesOperations.RemoveNodeWithHttpMessagesAsync(System.String,System.String,System.String,Microsoft.Azure.Management.DataFactory.Models.IntegrationRuntimeRemoveNodeRequest,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member RemoveNodeWithHttpMessagesAsync : string * string * string * Microsoft.Azure.Management.DataFactory.Models.IntegrationRuntimeRemoveNodeRequest * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt;" Usage="iIntegrationRuntimesOperations.RemoveNodeWithHttpMessagesAsync (resourceGroupName, factoryName, integrationRuntimeName, removeNodeParameters, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="factoryName" Type="System.String" />
        <Parameter Name="integrationRuntimeName" Type="System.String" />
        <Parameter Name="removeNodeParameters" Type="Microsoft.Azure.Management.DataFactory.Models.IntegrationRuntimeRemoveNodeRequest" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="e65a8-209">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="e65a8-209">The resource group name.</span></span>
            </param>
        <param name="factoryName">
            <span data-ttu-id="e65a8-210">Die Factory-Namen.</span><span class="sxs-lookup"><span data-stu-id="e65a8-210">The factory name.</span></span>
            </param>
        <param name="integrationRuntimeName">
            <span data-ttu-id="e65a8-211">Die Integration Laufzeitklasse-Namen.</span><span class="sxs-lookup"><span data-stu-id="e65a8-211">The integration runtime name.</span></span>
            </param>
        <param name="removeNodeParameters">
            <span data-ttu-id="e65a8-212">Der Name des Knotens aus einem integrationslaufzeit entfernt werden soll.</span><span class="sxs-lookup"><span data-stu-id="e65a8-212">The name of the node to be removed from an integration runtime.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="e65a8-213">Die Header, die hinzugefügt werden auf Anforderung.</span><span class="sxs-lookup"><span data-stu-id="e65a8-213">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="e65a8-214">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="e65a8-214">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="e65a8-215">Entfernen eines Knotens aus integrationslaufzeit an.</span><span class="sxs-lookup"><span data-stu-id="e65a8-215">Remove a node from integration runtime.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Azure.Management.DataFactory.Models.ErrorResponseException">
            <span data-ttu-id="e65a8-216">Wird ausgelöst, wenn der Vorgang einen ungültigen Statuscode zurückgegeben hat.</span><span class="sxs-lookup"><span data-stu-id="e65a8-216">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="e65a8-217">Wird ausgelöst, wenn ein erforderlicher Parameter null ist.</span><span class="sxs-lookup"><span data-stu-id="e65a8-217">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="StartWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.DataFactory.Models.IntegrationRuntimeStatusResponse&gt;&gt; StartWithHttpMessagesAsync (string resourceGroupName, string factoryName, string integrationRuntimeName, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Management.DataFactory.Models.IntegrationRuntimeStatusResponse&gt;&gt; StartWithHttpMessagesAsync(string resourceGroupName, string factoryName, string integrationRuntimeName, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.IIntegrationRuntimesOperations.StartWithHttpMessagesAsync(System.String,System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member StartWithHttpMessagesAsync : string * string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.DataFactory.Models.IntegrationRuntimeStatusResponse&gt;&gt;" Usage="iIntegrationRuntimesOperations.StartWithHttpMessagesAsync (resourceGroupName, factoryName, integrationRuntimeName, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.DataFactory.Models.IntegrationRuntimeStatusResponse&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="factoryName" Type="System.String" />
        <Parameter Name="integrationRuntimeName" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="e65a8-218">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="e65a8-218">The resource group name.</span></span>
            </param>
        <param name="factoryName">
            <span data-ttu-id="e65a8-219">Die Factory-Namen.</span><span class="sxs-lookup"><span data-stu-id="e65a8-219">The factory name.</span></span>
            </param>
        <param name="integrationRuntimeName">
            <span data-ttu-id="e65a8-220">Die Integration Laufzeitklasse-Namen.</span><span class="sxs-lookup"><span data-stu-id="e65a8-220">The integration runtime name.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="e65a8-221">Die Header, die hinzugefügt werden auf Anforderung.</span><span class="sxs-lookup"><span data-stu-id="e65a8-221">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="e65a8-222">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="e65a8-222">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="e65a8-223">Startet eine ManagedReserved Typ integrationslaufzeit an.</span><span class="sxs-lookup"><span data-stu-id="e65a8-223">Starts a ManagedReserved type integration runtime.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Azure.Management.DataFactory.Models.ErrorResponseException">
            <span data-ttu-id="e65a8-224">Wird ausgelöst, wenn der Vorgang einen ungültigen Statuscode zurückgegeben hat.</span><span class="sxs-lookup"><span data-stu-id="e65a8-224">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="e65a8-225">Wird ausgelöst, wenn nicht die Antwort zu deserialisieren.</span><span class="sxs-lookup"><span data-stu-id="e65a8-225">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="e65a8-226">Wird ausgelöst, wenn ein erforderlicher Parameter null ist.</span><span class="sxs-lookup"><span data-stu-id="e65a8-226">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="StopWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt; StopWithHttpMessagesAsync (string resourceGroupName, string factoryName, string integrationRuntimeName, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse&gt; StopWithHttpMessagesAsync(string resourceGroupName, string factoryName, string integrationRuntimeName, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.IIntegrationRuntimesOperations.StopWithHttpMessagesAsync(System.String,System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member StopWithHttpMessagesAsync : string * string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt;" Usage="iIntegrationRuntimesOperations.StopWithHttpMessagesAsync (resourceGroupName, factoryName, integrationRuntimeName, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="factoryName" Type="System.String" />
        <Parameter Name="integrationRuntimeName" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="e65a8-227">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="e65a8-227">The resource group name.</span></span>
            </param>
        <param name="factoryName">
            <span data-ttu-id="e65a8-228">Die Factory-Namen.</span><span class="sxs-lookup"><span data-stu-id="e65a8-228">The factory name.</span></span>
            </param>
        <param name="integrationRuntimeName">
            <span data-ttu-id="e65a8-229">Die Integration Laufzeitklasse-Namen.</span><span class="sxs-lookup"><span data-stu-id="e65a8-229">The integration runtime name.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="e65a8-230">Die Header, die hinzugefügt werden auf Anforderung.</span><span class="sxs-lookup"><span data-stu-id="e65a8-230">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="e65a8-231">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="e65a8-231">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="e65a8-232">Beendet eine ManagedReserved Typ integrationslaufzeit an.</span><span class="sxs-lookup"><span data-stu-id="e65a8-232">Stops a ManagedReserved type integration runtime.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Azure.Management.DataFactory.Models.ErrorResponseException">
            <span data-ttu-id="e65a8-233">Wird ausgelöst, wenn der Vorgang einen ungültigen Statuscode zurückgegeben hat.</span><span class="sxs-lookup"><span data-stu-id="e65a8-233">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="e65a8-234">Wird ausgelöst, wenn ein erforderlicher Parameter null ist.</span><span class="sxs-lookup"><span data-stu-id="e65a8-234">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="SyncCredentialsWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt; SyncCredentialsWithHttpMessagesAsync (string resourceGroupName, string factoryName, string integrationRuntimeName, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse&gt; SyncCredentialsWithHttpMessagesAsync(string resourceGroupName, string factoryName, string integrationRuntimeName, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.IIntegrationRuntimesOperations.SyncCredentialsWithHttpMessagesAsync(System.String,System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member SyncCredentialsWithHttpMessagesAsync : string * string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt;" Usage="iIntegrationRuntimesOperations.SyncCredentialsWithHttpMessagesAsync (resourceGroupName, factoryName, integrationRuntimeName, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="factoryName" Type="System.String" />
        <Parameter Name="integrationRuntimeName" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="e65a8-235">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="e65a8-235">The resource group name.</span></span>
            </param>
        <param name="factoryName">
            <span data-ttu-id="e65a8-236">Die Factory-Namen.</span><span class="sxs-lookup"><span data-stu-id="e65a8-236">The factory name.</span></span>
            </param>
        <param name="integrationRuntimeName">
            <span data-ttu-id="e65a8-237">Die Integration Laufzeitklasse-Namen.</span><span class="sxs-lookup"><span data-stu-id="e65a8-237">The integration runtime name.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="e65a8-238">Die Header, die hinzugefügt werden auf Anforderung.</span><span class="sxs-lookup"><span data-stu-id="e65a8-238">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="e65a8-239">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="e65a8-239">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="e65a8-240">Erzwingen von der integrationslaufzeit Anmeldeinformationen knotenübergreifend Runtime Integration synchronisiert, und dadurch werden die Anmeldeinformationen für alle workerknoten, mit denen auf dem Verteiler Knoten überschrieben.</span><span class="sxs-lookup"><span data-stu-id="e65a8-240">Force the integration runtime to synchronize credentials across integration runtime nodes, and this will override the credentials across all worker nodes with those available on the dispatcher node.</span></span> <span data-ttu-id="e65a8-241">Wenn Sie bereits über die aktuellen Anmeldeinformationen Sicherungsdatei verfügen, sollten Sie es (bevorzugt) manuell auf einem selbst gehosteten Integration Common Language Runtime-Knoten als direkt mit dieser API importieren.</span><span class="sxs-lookup"><span data-stu-id="e65a8-241">If you already have the latest credential backup file, you should manually import it (preferred) on any self-hosted integration runtime node than using this API directly.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Azure.Management.DataFactory.Models.ErrorResponseException">
            <span data-ttu-id="e65a8-242">Wird ausgelöst, wenn der Vorgang einen ungültigen Statuscode zurückgegeben hat.</span><span class="sxs-lookup"><span data-stu-id="e65a8-242">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="e65a8-243">Wird ausgelöst, wenn ein erforderlicher Parameter null ist.</span><span class="sxs-lookup"><span data-stu-id="e65a8-243">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="UpdateWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.DataFactory.Models.IntegrationRuntimeStatusResponse&gt;&gt; UpdateWithHttpMessagesAsync (string resourceGroupName, string factoryName, string integrationRuntimeName, Microsoft.Azure.Management.DataFactory.Models.UpdateIntegrationRuntimeRequest updateIntegrationRuntimeRequest, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Management.DataFactory.Models.IntegrationRuntimeStatusResponse&gt;&gt; UpdateWithHttpMessagesAsync(string resourceGroupName, string factoryName, string integrationRuntimeName, class Microsoft.Azure.Management.DataFactory.Models.UpdateIntegrationRuntimeRequest updateIntegrationRuntimeRequest, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.IIntegrationRuntimesOperations.UpdateWithHttpMessagesAsync(System.String,System.String,System.String,Microsoft.Azure.Management.DataFactory.Models.UpdateIntegrationRuntimeRequest,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member UpdateWithHttpMessagesAsync : string * string * string * Microsoft.Azure.Management.DataFactory.Models.UpdateIntegrationRuntimeRequest * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.DataFactory.Models.IntegrationRuntimeStatusResponse&gt;&gt;" Usage="iIntegrationRuntimesOperations.UpdateWithHttpMessagesAsync (resourceGroupName, factoryName, integrationRuntimeName, updateIntegrationRuntimeRequest, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.DataFactory.Models.IntegrationRuntimeStatusResponse&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="factoryName" Type="System.String" />
        <Parameter Name="integrationRuntimeName" Type="System.String" />
        <Parameter Name="updateIntegrationRuntimeRequest" Type="Microsoft.Azure.Management.DataFactory.Models.UpdateIntegrationRuntimeRequest" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="e65a8-244">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="e65a8-244">The resource group name.</span></span>
            </param>
        <param name="factoryName">
            <span data-ttu-id="e65a8-245">Die Factory-Namen.</span><span class="sxs-lookup"><span data-stu-id="e65a8-245">The factory name.</span></span>
            </param>
        <param name="integrationRuntimeName">
            <span data-ttu-id="e65a8-246">Die Integration Laufzeitklasse-Namen.</span><span class="sxs-lookup"><span data-stu-id="e65a8-246">The integration runtime name.</span></span>
            </param>
        <param name="updateIntegrationRuntimeRequest">
            <span data-ttu-id="e65a8-247">Die Parameter für ein integrationslaufzeit aktualisieren.</span><span class="sxs-lookup"><span data-stu-id="e65a8-247">The parameters for updating an integration runtime.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="e65a8-248">Die Header, die hinzugefügt werden auf Anforderung.</span><span class="sxs-lookup"><span data-stu-id="e65a8-248">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="e65a8-249">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="e65a8-249">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="e65a8-250">Aktualisiert eine integrationslaufzeit an.</span><span class="sxs-lookup"><span data-stu-id="e65a8-250">Updates an integration runtime.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Azure.Management.DataFactory.Models.ErrorResponseException">
            <span data-ttu-id="e65a8-251">Wird ausgelöst, wenn der Vorgang einen ungültigen Statuscode zurückgegeben hat.</span><span class="sxs-lookup"><span data-stu-id="e65a8-251">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="e65a8-252">Wird ausgelöst, wenn nicht die Antwort zu deserialisieren.</span><span class="sxs-lookup"><span data-stu-id="e65a8-252">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="e65a8-253">Wird ausgelöst, wenn ein erforderlicher Parameter null ist.</span><span class="sxs-lookup"><span data-stu-id="e65a8-253">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="UpgradeWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt; UpgradeWithHttpMessagesAsync (string resourceGroupName, string factoryName, string integrationRuntimeName, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse&gt; UpgradeWithHttpMessagesAsync(string resourceGroupName, string factoryName, string integrationRuntimeName, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.IIntegrationRuntimesOperations.UpgradeWithHttpMessagesAsync(System.String,System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member UpgradeWithHttpMessagesAsync : string * string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt;" Usage="iIntegrationRuntimesOperations.UpgradeWithHttpMessagesAsync (resourceGroupName, factoryName, integrationRuntimeName, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="factoryName" Type="System.String" />
        <Parameter Name="integrationRuntimeName" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="e65a8-254">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="e65a8-254">The resource group name.</span></span>
            </param>
        <param name="factoryName">
            <span data-ttu-id="e65a8-255">Die Factory-Namen.</span><span class="sxs-lookup"><span data-stu-id="e65a8-255">The factory name.</span></span>
            </param>
        <param name="integrationRuntimeName">
            <span data-ttu-id="e65a8-256">Die Integration Laufzeitklasse-Namen.</span><span class="sxs-lookup"><span data-stu-id="e65a8-256">The integration runtime name.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="e65a8-257">Die Header, die hinzugefügt werden auf Anforderung.</span><span class="sxs-lookup"><span data-stu-id="e65a8-257">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="e65a8-258">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="e65a8-258">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="e65a8-259">Aktualisieren Sie selbst gehostete integrationslaufzeit auf neueste Version, wenn transparentes.</span><span class="sxs-lookup"><span data-stu-id="e65a8-259">Upgrade self-hosted integration runtime to latest version if availably.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Azure.Management.DataFactory.Models.ErrorResponseException">
            <span data-ttu-id="e65a8-260">Wird ausgelöst, wenn der Vorgang einen ungültigen Statuscode zurückgegeben hat.</span><span class="sxs-lookup"><span data-stu-id="e65a8-260">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="e65a8-261">Wird ausgelöst, wenn ein erforderlicher Parameter null ist.</span><span class="sxs-lookup"><span data-stu-id="e65a8-261">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>