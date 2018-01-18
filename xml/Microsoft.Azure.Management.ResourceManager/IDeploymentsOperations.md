<Type Name="IDeploymentsOperations" FullName="Microsoft.Azure.Management.ResourceManager.IDeploymentsOperations">
  <TypeSignature Language="C#" Value="public interface IDeploymentsOperations" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IDeploymentsOperations" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.ResourceManager.IDeploymentsOperations" />
  <TypeSignature Language="VB.NET" Value="Public Interface IDeploymentsOperations" />
  <TypeSignature Language="F#" Value="type IDeploymentsOperations = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="5439e-101">DeploymentsOperations-Vorgänge.</span><span class="sxs-lookup"><span data-stu-id="5439e-101">DeploymentsOperations operations.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="BeginCreateOrUpdateWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.ResourceManager.Models.DeploymentExtended&gt;&gt; BeginCreateOrUpdateWithHttpMessagesAsync (string resourceGroupName, string deploymentName, Microsoft.Azure.Management.ResourceManager.Models.Deployment parameters, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Management.ResourceManager.Models.DeploymentExtended&gt;&gt; BeginCreateOrUpdateWithHttpMessagesAsync(string resourceGroupName, string deploymentName, class Microsoft.Azure.Management.ResourceManager.Models.Deployment parameters, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.IDeploymentsOperations.BeginCreateOrUpdateWithHttpMessagesAsync(System.String,System.String,Microsoft.Azure.Management.ResourceManager.Models.Deployment,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member BeginCreateOrUpdateWithHttpMessagesAsync : string * string * Microsoft.Azure.Management.ResourceManager.Models.Deployment * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.ResourceManager.Models.DeploymentExtended&gt;&gt;" Usage="iDeploymentsOperations.BeginCreateOrUpdateWithHttpMessagesAsync (resourceGroupName, deploymentName, parameters, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.ResourceManager.Models.DeploymentExtended&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="deploymentName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.ResourceManager.Models.Deployment" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="5439e-102">Der Name der Ressourcengruppe an die Ressourcen bereitstellen.</span><span class="sxs-lookup"><span data-stu-id="5439e-102">The name of the resource group to deploy the resources to.</span></span> <span data-ttu-id="5439e-103">Der Name wird Groß-/Kleinschreibung nicht beachtet.</span><span class="sxs-lookup"><span data-stu-id="5439e-103">The name is case insensitive.</span></span> <span data-ttu-id="5439e-104">Die Ressourcengruppe muss bereits vorhanden sein.</span><span class="sxs-lookup"><span data-stu-id="5439e-104">The resource group must already exist.</span></span>
            </param>
        <param name="deploymentName">
            <span data-ttu-id="5439e-105">Der Name der Bereitstellung</span><span class="sxs-lookup"><span data-stu-id="5439e-105">The name of the deployment.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="5439e-106">Zusätzliche Parameter für den Vorgang bereitgestellte.</span><span class="sxs-lookup"><span data-stu-id="5439e-106">Additional parameters supplied to the operation.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="5439e-107">Die Header, die hinzugefügt werden auf Anforderung.</span><span class="sxs-lookup"><span data-stu-id="5439e-107">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="5439e-108">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="5439e-108">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="5439e-109">Stellt Ressourcen in einer Ressourcengruppe bereit.</span><span class="sxs-lookup"><span data-stu-id="5439e-109">Deploys resources to a resource group.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="5439e-110">Sie können die Vorlage und die Parameter direkt in der Anforderung oder den Link, um JSON-Dateien bereitstellen.</span><span class="sxs-lookup"><span data-stu-id="5439e-110">You can provide the template and parameters directly in the request or link to JSON files.</span></span>
            </remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="5439e-111">Wird ausgelöst, wenn der Vorgang einen ungültigen Statuscode zurückgegeben hat.</span><span class="sxs-lookup"><span data-stu-id="5439e-111">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="5439e-112">Wird ausgelöst, wenn nicht die Antwort zu deserialisieren.</span><span class="sxs-lookup"><span data-stu-id="5439e-112">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="5439e-113">Wird ausgelöst, wenn ein erforderlicher Parameter null ist.</span><span class="sxs-lookup"><span data-stu-id="5439e-113">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="BeginDeleteWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt; BeginDeleteWithHttpMessagesAsync (string resourceGroupName, string deploymentName, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse&gt; BeginDeleteWithHttpMessagesAsync(string resourceGroupName, string deploymentName, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.IDeploymentsOperations.BeginDeleteWithHttpMessagesAsync(System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member BeginDeleteWithHttpMessagesAsync : string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt;" Usage="iDeploymentsOperations.BeginDeleteWithHttpMessagesAsync (resourceGroupName, deploymentName, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="deploymentName" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="5439e-114">Der Name der Ressourcengruppe mit der Bereitstellung gelöscht.</span><span class="sxs-lookup"><span data-stu-id="5439e-114">The name of the resource group with the deployment to delete.</span></span> <span data-ttu-id="5439e-115">Der Name wird Groß-/Kleinschreibung nicht beachtet.</span><span class="sxs-lookup"><span data-stu-id="5439e-115">The name is case insensitive.</span></span>
            </param>
        <param name="deploymentName">
            <span data-ttu-id="5439e-116">Der Name der Bereitstellung gelöscht.</span><span class="sxs-lookup"><span data-stu-id="5439e-116">The name of the deployment to delete.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="5439e-117">Die Header, die hinzugefügt werden auf Anforderung.</span><span class="sxs-lookup"><span data-stu-id="5439e-117">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="5439e-118">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="5439e-118">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="5439e-119">Löscht eine Bereitstellung aus dem Bereitstellungsverlauf an.</span><span class="sxs-lookup"><span data-stu-id="5439e-119">Deletes a deployment from the deployment history.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="5439e-120">Eine vorlagenbereitstellung, die zurzeit ausgeführt wird, kann nicht gelöscht werden.</span><span class="sxs-lookup"><span data-stu-id="5439e-120">A template deployment that is currently running cannot be deleted.</span></span>
            <span data-ttu-id="5439e-121">Das Löschen einer vorlagenbereitstellung werden die zugehörigen Bereitstellungsvorgänge entfernt.</span><span class="sxs-lookup"><span data-stu-id="5439e-121">Deleting a template deployment removes the associated deployment operations.</span></span> <span data-ttu-id="5439e-122">Das Löschen einer vorlagenbereitstellung wirkt sich nicht auf den Status der Ressourcengruppe aus.</span><span class="sxs-lookup"><span data-stu-id="5439e-122">Deleting a template deployment does not affect the state of the resource group.</span></span> <span data-ttu-id="5439e-123">Dies ist ein asynchroner Vorgang, der den Status 202 zurückgibt, bis die vorlagenbereitstellung erfolgreich gelöscht wurde.</span><span class="sxs-lookup"><span data-stu-id="5439e-123">This is an asynchronous operation that returns a status of 202 until the template deployment is successfully deleted.</span></span> <span data-ttu-id="5439e-124">Antwortheaders der Adresse enthält den URI, der verwendet wird, um den Status des Prozesses zu erhalten.</span><span class="sxs-lookup"><span data-stu-id="5439e-124">The Location response header contains the URI that is used to obtain the status of the process.</span></span> <span data-ttu-id="5439e-125">Während der Prozess ausgeführt wird, gibt ein Aufruf des URIS im Location-Header den Status 202 zurück.</span><span class="sxs-lookup"><span data-stu-id="5439e-125">While the process is running, a call to the URI in the Location header returns a status of 202.</span></span> <span data-ttu-id="5439e-126">Wenn der Prozess abgeschlossen wurde, gibt der URI im Location-Header Status 204 bei Erfolg zurück.</span><span class="sxs-lookup"><span data-stu-id="5439e-126">When the process finishes, the URI in the Location header returns a status of 204 on success.</span></span> <span data-ttu-id="5439e-127">Wenn die asynchrone Anforderung fehlgeschlagen ist, gibt der URI im Location-Header einen Fehlerstufen-Statuscode zurück.</span><span class="sxs-lookup"><span data-stu-id="5439e-127">If the asynchronous request failed, the URI in the Location header returns an error-level status code.</span></span>
            </remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="5439e-128">Wird ausgelöst, wenn der Vorgang einen ungültigen Statuscode zurückgegeben hat.</span><span class="sxs-lookup"><span data-stu-id="5439e-128">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="5439e-129">Wird ausgelöst, wenn ein erforderlicher Parameter null ist.</span><span class="sxs-lookup"><span data-stu-id="5439e-129">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="CancelWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt; CancelWithHttpMessagesAsync (string resourceGroupName, string deploymentName, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse&gt; CancelWithHttpMessagesAsync(string resourceGroupName, string deploymentName, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.IDeploymentsOperations.CancelWithHttpMessagesAsync(System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member CancelWithHttpMessagesAsync : string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt;" Usage="iDeploymentsOperations.CancelWithHttpMessagesAsync (resourceGroupName, deploymentName, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="deploymentName" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="5439e-130">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="5439e-130">The name of the resource group.</span></span> <span data-ttu-id="5439e-131">Der Name wird Groß-/Kleinschreibung nicht beachtet.</span><span class="sxs-lookup"><span data-stu-id="5439e-131">The name is case insensitive.</span></span>
            </param>
        <param name="deploymentName">
            <span data-ttu-id="5439e-132">Der Name der Bereitstellung auf "Abbrechen".</span><span class="sxs-lookup"><span data-stu-id="5439e-132">The name of the deployment to cancel.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="5439e-133">Die Header, die hinzugefügt werden auf Anforderung.</span><span class="sxs-lookup"><span data-stu-id="5439e-133">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="5439e-134">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="5439e-134">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="5439e-135">Bricht einen derzeit ausgeführten vorlagenbereitstellung ab.</span><span class="sxs-lookup"><span data-stu-id="5439e-135">Cancels a currently running template deployment.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="5439e-136">Sie können eine Bereitstellung "Abbrechen", nur dann, wenn der ProvisioningState akzeptiert oder ausgeführt wird.</span><span class="sxs-lookup"><span data-stu-id="5439e-136">You can cancel a deployment only if the provisioningState is Accepted or Running.</span></span> <span data-ttu-id="5439e-137">Nachdem die Bereitstellung abgebrochen wird, wird der ProvisioningState auf Canceled festgelegt.</span><span class="sxs-lookup"><span data-stu-id="5439e-137">After the deployment is canceled, the provisioningState is set to Canceled.</span></span> <span data-ttu-id="5439e-138">Abbrechen einer vorlagenbereitstellung wird die aktuell ausgeführte vorlagenbereitstellung beendet und verlässt Ressourcengruppe teilweise bereitgestellt.</span><span class="sxs-lookup"><span data-stu-id="5439e-138">Canceling a template deployment stops the currently running template deployment and leaves the resource group partially deployed.</span></span>
            </remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="5439e-139">Wird ausgelöst, wenn der Vorgang einen ungültigen Statuscode zurückgegeben hat.</span><span class="sxs-lookup"><span data-stu-id="5439e-139">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="5439e-140">Wird ausgelöst, wenn ein erforderlicher Parameter null ist.</span><span class="sxs-lookup"><span data-stu-id="5439e-140">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="CheckExistenceWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;bool&gt;&gt; CheckExistenceWithHttpMessagesAsync (string resourceGroupName, string deploymentName, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;bool&gt;&gt; CheckExistenceWithHttpMessagesAsync(string resourceGroupName, string deploymentName, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.IDeploymentsOperations.CheckExistenceWithHttpMessagesAsync(System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member CheckExistenceWithHttpMessagesAsync : string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;bool&gt;&gt;" Usage="iDeploymentsOperations.CheckExistenceWithHttpMessagesAsync (resourceGroupName, deploymentName, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;System.Boolean&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="deploymentName" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="5439e-141">Der Name der mit der Bereitstellung zu überprüfenden Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="5439e-141">The name of the resource group with the deployment to check.</span></span> <span data-ttu-id="5439e-142">Der Name wird Groß-/Kleinschreibung nicht beachtet.</span><span class="sxs-lookup"><span data-stu-id="5439e-142">The name is case insensitive.</span></span>
            </param>
        <param name="deploymentName">
            <span data-ttu-id="5439e-143">Der Name der Bereitstellung zu überprüfen.</span><span class="sxs-lookup"><span data-stu-id="5439e-143">The name of the deployment to check.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="5439e-144">Die Header, die hinzugefügt werden auf Anforderung.</span><span class="sxs-lookup"><span data-stu-id="5439e-144">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="5439e-145">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="5439e-145">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="5439e-146">Überprüft, ob die Bereitstellung vorhanden ist.</span><span class="sxs-lookup"><span data-stu-id="5439e-146">Checks whether the deployment exists.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="5439e-147">Wird ausgelöst, wenn der Vorgang einen ungültigen Statuscode zurückgegeben hat.</span><span class="sxs-lookup"><span data-stu-id="5439e-147">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="5439e-148">Wird ausgelöst, wenn ein erforderlicher Parameter null ist.</span><span class="sxs-lookup"><span data-stu-id="5439e-148">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="CreateOrUpdateWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.ResourceManager.Models.DeploymentExtended&gt;&gt; CreateOrUpdateWithHttpMessagesAsync (string resourceGroupName, string deploymentName, Microsoft.Azure.Management.ResourceManager.Models.Deployment parameters, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Management.ResourceManager.Models.DeploymentExtended&gt;&gt; CreateOrUpdateWithHttpMessagesAsync(string resourceGroupName, string deploymentName, class Microsoft.Azure.Management.ResourceManager.Models.Deployment parameters, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.IDeploymentsOperations.CreateOrUpdateWithHttpMessagesAsync(System.String,System.String,Microsoft.Azure.Management.ResourceManager.Models.Deployment,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member CreateOrUpdateWithHttpMessagesAsync : string * string * Microsoft.Azure.Management.ResourceManager.Models.Deployment * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.ResourceManager.Models.DeploymentExtended&gt;&gt;" Usage="iDeploymentsOperations.CreateOrUpdateWithHttpMessagesAsync (resourceGroupName, deploymentName, parameters, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.ResourceManager.Models.DeploymentExtended&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="deploymentName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.ResourceManager.Models.Deployment" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="5439e-149">Der Name der Ressourcengruppe an die Ressourcen bereitstellen.</span><span class="sxs-lookup"><span data-stu-id="5439e-149">The name of the resource group to deploy the resources to.</span></span> <span data-ttu-id="5439e-150">Der Name wird Groß-/Kleinschreibung nicht beachtet.</span><span class="sxs-lookup"><span data-stu-id="5439e-150">The name is case insensitive.</span></span> <span data-ttu-id="5439e-151">Die Ressourcengruppe muss bereits vorhanden sein.</span><span class="sxs-lookup"><span data-stu-id="5439e-151">The resource group must already exist.</span></span>
            </param>
        <param name="deploymentName">
            <span data-ttu-id="5439e-152">Der Name der Bereitstellung</span><span class="sxs-lookup"><span data-stu-id="5439e-152">The name of the deployment.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="5439e-153">Zusätzliche Parameter für den Vorgang bereitgestellte.</span><span class="sxs-lookup"><span data-stu-id="5439e-153">Additional parameters supplied to the operation.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="5439e-154">Die Header, die hinzugefügt werden auf Anforderung.</span><span class="sxs-lookup"><span data-stu-id="5439e-154">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="5439e-155">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="5439e-155">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="5439e-156">Stellt Ressourcen in einer Ressourcengruppe bereit.</span><span class="sxs-lookup"><span data-stu-id="5439e-156">Deploys resources to a resource group.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="5439e-157">Sie können die Vorlage und die Parameter direkt in der Anforderung oder den Link, um JSON-Dateien bereitstellen.</span><span class="sxs-lookup"><span data-stu-id="5439e-157">You can provide the template and parameters directly in the request or link to JSON files.</span></span>
            </remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="5439e-158">Wird ausgelöst, wenn der Vorgang einen ungültigen Statuscode zurückgegeben hat.</span><span class="sxs-lookup"><span data-stu-id="5439e-158">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="5439e-159">Wird ausgelöst, wenn nicht die Antwort zu deserialisieren.</span><span class="sxs-lookup"><span data-stu-id="5439e-159">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="5439e-160">Wird ausgelöst, wenn ein erforderlicher Parameter null ist.</span><span class="sxs-lookup"><span data-stu-id="5439e-160">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="DeleteWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt; DeleteWithHttpMessagesAsync (string resourceGroupName, string deploymentName, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse&gt; DeleteWithHttpMessagesAsync(string resourceGroupName, string deploymentName, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.IDeploymentsOperations.DeleteWithHttpMessagesAsync(System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member DeleteWithHttpMessagesAsync : string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt;" Usage="iDeploymentsOperations.DeleteWithHttpMessagesAsync (resourceGroupName, deploymentName, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="deploymentName" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="5439e-161">Der Name der Ressourcengruppe mit der Bereitstellung gelöscht.</span><span class="sxs-lookup"><span data-stu-id="5439e-161">The name of the resource group with the deployment to delete.</span></span> <span data-ttu-id="5439e-162">Der Name wird Groß-/Kleinschreibung nicht beachtet.</span><span class="sxs-lookup"><span data-stu-id="5439e-162">The name is case insensitive.</span></span>
            </param>
        <param name="deploymentName">
            <span data-ttu-id="5439e-163">Der Name der Bereitstellung gelöscht.</span><span class="sxs-lookup"><span data-stu-id="5439e-163">The name of the deployment to delete.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="5439e-164">Die Header, die hinzugefügt werden auf Anforderung.</span><span class="sxs-lookup"><span data-stu-id="5439e-164">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="5439e-165">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="5439e-165">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="5439e-166">Löscht eine Bereitstellung aus dem Bereitstellungsverlauf an.</span><span class="sxs-lookup"><span data-stu-id="5439e-166">Deletes a deployment from the deployment history.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="5439e-167">Eine vorlagenbereitstellung, die zurzeit ausgeführt wird, kann nicht gelöscht werden.</span><span class="sxs-lookup"><span data-stu-id="5439e-167">A template deployment that is currently running cannot be deleted.</span></span>
            <span data-ttu-id="5439e-168">Das Löschen einer vorlagenbereitstellung werden die zugehörigen Bereitstellungsvorgänge entfernt.</span><span class="sxs-lookup"><span data-stu-id="5439e-168">Deleting a template deployment removes the associated deployment operations.</span></span> <span data-ttu-id="5439e-169">Das Löschen einer vorlagenbereitstellung wirkt sich nicht auf den Status der Ressourcengruppe aus.</span><span class="sxs-lookup"><span data-stu-id="5439e-169">Deleting a template deployment does not affect the state of the resource group.</span></span> <span data-ttu-id="5439e-170">Dies ist ein asynchroner Vorgang, der den Status 202 zurückgibt, bis die vorlagenbereitstellung erfolgreich gelöscht wurde.</span><span class="sxs-lookup"><span data-stu-id="5439e-170">This is an asynchronous operation that returns a status of 202 until the template deployment is successfully deleted.</span></span> <span data-ttu-id="5439e-171">Antwortheaders der Adresse enthält den URI, der verwendet wird, um den Status des Prozesses zu erhalten.</span><span class="sxs-lookup"><span data-stu-id="5439e-171">The Location response header contains the URI that is used to obtain the status of the process.</span></span> <span data-ttu-id="5439e-172">Während der Prozess ausgeführt wird, gibt ein Aufruf des URIS im Location-Header den Status 202 zurück.</span><span class="sxs-lookup"><span data-stu-id="5439e-172">While the process is running, a call to the URI in the Location header returns a status of 202.</span></span> <span data-ttu-id="5439e-173">Wenn der Prozess abgeschlossen wurde, gibt der URI im Location-Header Status 204 bei Erfolg zurück.</span><span class="sxs-lookup"><span data-stu-id="5439e-173">When the process finishes, the URI in the Location header returns a status of 204 on success.</span></span> <span data-ttu-id="5439e-174">Wenn die asynchrone Anforderung fehlgeschlagen ist, gibt der URI im Location-Header einen Fehlerstufen-Statuscode zurück.</span><span class="sxs-lookup"><span data-stu-id="5439e-174">If the asynchronous request failed, the URI in the Location header returns an error-level status code.</span></span>
            </remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="5439e-175">Wird ausgelöst, wenn der Vorgang einen ungültigen Statuscode zurückgegeben hat.</span><span class="sxs-lookup"><span data-stu-id="5439e-175">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="5439e-176">Wird ausgelöst, wenn ein erforderlicher Parameter null ist.</span><span class="sxs-lookup"><span data-stu-id="5439e-176">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="ExportTemplateWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.ResourceManager.Models.DeploymentExportResult&gt;&gt; ExportTemplateWithHttpMessagesAsync (string resourceGroupName, string deploymentName, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Management.ResourceManager.Models.DeploymentExportResult&gt;&gt; ExportTemplateWithHttpMessagesAsync(string resourceGroupName, string deploymentName, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.IDeploymentsOperations.ExportTemplateWithHttpMessagesAsync(System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ExportTemplateWithHttpMessagesAsync : string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.ResourceManager.Models.DeploymentExportResult&gt;&gt;" Usage="iDeploymentsOperations.ExportTemplateWithHttpMessagesAsync (resourceGroupName, deploymentName, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.ResourceManager.Models.DeploymentExportResult&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="deploymentName" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="5439e-177">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="5439e-177">The name of the resource group.</span></span> <span data-ttu-id="5439e-178">Der Name wird Groß-/Kleinschreibung nicht beachtet.</span><span class="sxs-lookup"><span data-stu-id="5439e-178">The name is case insensitive.</span></span>
            </param>
        <param name="deploymentName">
            <span data-ttu-id="5439e-179">Der Name der Bereitstellung von dem die Vorlage abgerufen werden soll.</span><span class="sxs-lookup"><span data-stu-id="5439e-179">The name of the deployment from which to get the template.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="5439e-180">Die Header, die hinzugefügt werden auf Anforderung.</span><span class="sxs-lookup"><span data-stu-id="5439e-180">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="5439e-181">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="5439e-181">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="5439e-182">Exportiert die Vorlage für eine angegebene Bereitstellung.</span><span class="sxs-lookup"><span data-stu-id="5439e-182">Exports the template used for specified deployment.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="5439e-183">Wird ausgelöst, wenn der Vorgang einen ungültigen Statuscode zurückgegeben hat.</span><span class="sxs-lookup"><span data-stu-id="5439e-183">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="5439e-184">Wird ausgelöst, wenn nicht die Antwort zu deserialisieren.</span><span class="sxs-lookup"><span data-stu-id="5439e-184">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="5439e-185">Wird ausgelöst, wenn ein erforderlicher Parameter null ist.</span><span class="sxs-lookup"><span data-stu-id="5439e-185">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="GetWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.ResourceManager.Models.DeploymentExtended&gt;&gt; GetWithHttpMessagesAsync (string resourceGroupName, string deploymentName, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Management.ResourceManager.Models.DeploymentExtended&gt;&gt; GetWithHttpMessagesAsync(string resourceGroupName, string deploymentName, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.IDeploymentsOperations.GetWithHttpMessagesAsync(System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetWithHttpMessagesAsync : string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.ResourceManager.Models.DeploymentExtended&gt;&gt;" Usage="iDeploymentsOperations.GetWithHttpMessagesAsync (resourceGroupName, deploymentName, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.ResourceManager.Models.DeploymentExtended&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="deploymentName" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="5439e-186">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="5439e-186">The name of the resource group.</span></span> <span data-ttu-id="5439e-187">Der Name wird Groß-/Kleinschreibung nicht beachtet.</span><span class="sxs-lookup"><span data-stu-id="5439e-187">The name is case insensitive.</span></span>
            </param>
        <param name="deploymentName">
            <span data-ttu-id="5439e-188">Der Name der Bereitstellung abgerufen werden soll.</span><span class="sxs-lookup"><span data-stu-id="5439e-188">The name of the deployment to get.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="5439e-189">Die Header, die hinzugefügt werden auf Anforderung.</span><span class="sxs-lookup"><span data-stu-id="5439e-189">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="5439e-190">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="5439e-190">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="5439e-191">Ruft eine Bereitstellung ab.</span><span class="sxs-lookup"><span data-stu-id="5439e-191">Gets a deployment.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="5439e-192">Wird ausgelöst, wenn der Vorgang einen ungültigen Statuscode zurückgegeben hat.</span><span class="sxs-lookup"><span data-stu-id="5439e-192">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="5439e-193">Wird ausgelöst, wenn nicht die Antwort zu deserialisieren.</span><span class="sxs-lookup"><span data-stu-id="5439e-193">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="5439e-194">Wird ausgelöst, wenn ein erforderlicher Parameter null ist.</span><span class="sxs-lookup"><span data-stu-id="5439e-194">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="ListByResourceGroupNextWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ResourceManager.Models.DeploymentExtended&gt;&gt;&gt; ListByResourceGroupNextWithHttpMessagesAsync (string nextPageLink, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.ResourceManager.Models.DeploymentExtended&gt;&gt;&gt; ListByResourceGroupNextWithHttpMessagesAsync(string nextPageLink, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.IDeploymentsOperations.ListByResourceGroupNextWithHttpMessagesAsync(System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListByResourceGroupNextWithHttpMessagesAsync : string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ResourceManager.Models.DeploymentExtended&gt;&gt;&gt;" Usage="iDeploymentsOperations.ListByResourceGroupNextWithHttpMessagesAsync (nextPageLink, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ResourceManager.Models.DeploymentExtended&gt;&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="nextPageLink">
            <span data-ttu-id="5439e-195">Die "NextLink" aus dem vorherigen erfolgreichen Aufruf List-Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="5439e-195">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="5439e-196">Die Header, die hinzugefügt werden auf Anforderung.</span><span class="sxs-lookup"><span data-stu-id="5439e-196">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="5439e-197">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="5439e-197">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="5439e-198">Rufen Sie alle Bereitstellungen für eine Ressourcengruppe ein.</span><span class="sxs-lookup"><span data-stu-id="5439e-198">Get all the deployments for a resource group.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="5439e-199">Wird ausgelöst, wenn der Vorgang einen ungültigen Statuscode zurückgegeben hat.</span><span class="sxs-lookup"><span data-stu-id="5439e-199">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="5439e-200">Wird ausgelöst, wenn nicht die Antwort zu deserialisieren.</span><span class="sxs-lookup"><span data-stu-id="5439e-200">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="5439e-201">Wird ausgelöst, wenn ein erforderlicher Parameter null ist.</span><span class="sxs-lookup"><span data-stu-id="5439e-201">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="ListByResourceGroupWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ResourceManager.Models.DeploymentExtended&gt;&gt;&gt; ListByResourceGroupWithHttpMessagesAsync (string resourceGroupName, Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.ResourceManager.Models.DeploymentExtendedFilter&gt; odataQuery = null, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.ResourceManager.Models.DeploymentExtended&gt;&gt;&gt; ListByResourceGroupWithHttpMessagesAsync(string resourceGroupName, class Microsoft.Rest.Azure.OData.ODataQuery`1&lt;class Microsoft.Azure.Management.ResourceManager.Models.DeploymentExtendedFilter&gt; odataQuery, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.IDeploymentsOperations.ListByResourceGroupWithHttpMessagesAsync(System.String,Microsoft.Rest.Azure.OData.ODataQuery{Microsoft.Azure.Management.ResourceManager.Models.DeploymentExtendedFilter},System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListByResourceGroupWithHttpMessagesAsync : string * Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.ResourceManager.Models.DeploymentExtendedFilter&gt; * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ResourceManager.Models.DeploymentExtended&gt;&gt;&gt;" Usage="iDeploymentsOperations.ListByResourceGroupWithHttpMessagesAsync (resourceGroupName, odataQuery, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ResourceManager.Models.DeploymentExtended&gt;&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="odataQuery" Type="Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.ResourceManager.Models.DeploymentExtendedFilter&gt;" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="5439e-202">Der Name der Ressourcengruppe mit dem Bereitstellungen abgerufen werden soll.</span><span class="sxs-lookup"><span data-stu-id="5439e-202">The name of the resource group with the deployments to get.</span></span> <span data-ttu-id="5439e-203">Der Name wird Groß-/Kleinschreibung nicht beachtet.</span><span class="sxs-lookup"><span data-stu-id="5439e-203">The name is case insensitive.</span></span>
            </param>
        <param name="odataQuery">
            <span data-ttu-id="5439e-204">OData-Parameter des Vorgangs angewendet.</span><span class="sxs-lookup"><span data-stu-id="5439e-204">OData parameters to apply to the operation.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="5439e-205">Die Header, die hinzugefügt werden auf Anforderung.</span><span class="sxs-lookup"><span data-stu-id="5439e-205">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="5439e-206">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="5439e-206">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="5439e-207">Rufen Sie alle Bereitstellungen für eine Ressourcengruppe ein.</span><span class="sxs-lookup"><span data-stu-id="5439e-207">Get all the deployments for a resource group.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="5439e-208">Wird ausgelöst, wenn der Vorgang einen ungültigen Statuscode zurückgegeben hat.</span><span class="sxs-lookup"><span data-stu-id="5439e-208">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="5439e-209">Wird ausgelöst, wenn nicht die Antwort zu deserialisieren.</span><span class="sxs-lookup"><span data-stu-id="5439e-209">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="5439e-210">Wird ausgelöst, wenn ein erforderlicher Parameter null ist.</span><span class="sxs-lookup"><span data-stu-id="5439e-210">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="ValidateWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.ResourceManager.Models.DeploymentValidateResult&gt;&gt; ValidateWithHttpMessagesAsync (string resourceGroupName, string deploymentName, Microsoft.Azure.Management.ResourceManager.Models.Deployment parameters, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Management.ResourceManager.Models.DeploymentValidateResult&gt;&gt; ValidateWithHttpMessagesAsync(string resourceGroupName, string deploymentName, class Microsoft.Azure.Management.ResourceManager.Models.Deployment parameters, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.IDeploymentsOperations.ValidateWithHttpMessagesAsync(System.String,System.String,Microsoft.Azure.Management.ResourceManager.Models.Deployment,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ValidateWithHttpMessagesAsync : string * string * Microsoft.Azure.Management.ResourceManager.Models.Deployment * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.ResourceManager.Models.DeploymentValidateResult&gt;&gt;" Usage="iDeploymentsOperations.ValidateWithHttpMessagesAsync (resourceGroupName, deploymentName, parameters, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.ResourceManager.Models.DeploymentValidateResult&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="deploymentName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.ResourceManager.Models.Deployment" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="5439e-211">Der Name der Ressourcengruppe wird in die Vorlage bereitgestellt werden.</span><span class="sxs-lookup"><span data-stu-id="5439e-211">The name of the resource group the template will be deployed to.</span></span>
            <span data-ttu-id="5439e-212">Der Name wird Groß-/Kleinschreibung nicht beachtet.</span><span class="sxs-lookup"><span data-stu-id="5439e-212">The name is case insensitive.</span></span>
            </param>
        <param name="deploymentName">
            <span data-ttu-id="5439e-213">Der Name der Bereitstellung</span><span class="sxs-lookup"><span data-stu-id="5439e-213">The name of the deployment.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="5439e-214">Parameter, um zu überprüfen.</span><span class="sxs-lookup"><span data-stu-id="5439e-214">Parameters to validate.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="5439e-215">Die Header, die hinzugefügt werden auf Anforderung.</span><span class="sxs-lookup"><span data-stu-id="5439e-215">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="5439e-216">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="5439e-216">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="5439e-217">Überprüft, ob die angegebene Vorlage syntaktisch richtig ist und werden von Azure Resource Manager akzeptiert...</span><span class="sxs-lookup"><span data-stu-id="5439e-217">Validates whether the specified template is syntactically correct and will be accepted by Azure Resource Manager..</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="5439e-218">Wird ausgelöst, wenn der Vorgang einen ungültigen Statuscode zurückgegeben hat.</span><span class="sxs-lookup"><span data-stu-id="5439e-218">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="5439e-219">Wird ausgelöst, wenn nicht die Antwort zu deserialisieren.</span><span class="sxs-lookup"><span data-stu-id="5439e-219">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="5439e-220">Wird ausgelöst, wenn ein erforderlicher Parameter null ist.</span><span class="sxs-lookup"><span data-stu-id="5439e-220">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>