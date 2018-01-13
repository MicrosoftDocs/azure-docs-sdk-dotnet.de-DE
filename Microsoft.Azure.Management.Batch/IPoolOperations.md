<Type Name="IPoolOperations" FullName="Microsoft.Azure.Management.Batch.IPoolOperations">
  <TypeSignature Language="C#" Value="public interface IPoolOperations" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IPoolOperations" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Batch.IPoolOperations" />
  <TypeSignature Language="VB.NET" Value="Public Interface IPoolOperations" />
  <TypeSignature Language="F#" Value="type IPoolOperations = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="697c5-101">PoolOperations-Vorgänge.</span><span class="sxs-lookup"><span data-stu-id="697c5-101">PoolOperations operations.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="BeginCreateWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Batch.Models.Pool,Microsoft.Azure.Management.Batch.Models.PoolCreateHeaders&gt;&gt; BeginCreateWithHttpMessagesAsync (string resourceGroupName, string accountName, string poolName, Microsoft.Azure.Management.Batch.Models.Pool parameters, string ifMatch = null, string ifNoneMatch = null, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`2&lt;class Microsoft.Azure.Management.Batch.Models.Pool, class Microsoft.Azure.Management.Batch.Models.PoolCreateHeaders&gt;&gt; BeginCreateWithHttpMessagesAsync(string resourceGroupName, string accountName, string poolName, class Microsoft.Azure.Management.Batch.Models.Pool parameters, string ifMatch, string ifNoneMatch, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Batch.IPoolOperations.BeginCreateWithHttpMessagesAsync(System.String,System.String,System.String,Microsoft.Azure.Management.Batch.Models.Pool,System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member BeginCreateWithHttpMessagesAsync : string * string * string * Microsoft.Azure.Management.Batch.Models.Pool * string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Batch.Models.Pool, Microsoft.Azure.Management.Batch.Models.PoolCreateHeaders&gt;&gt;" Usage="iPoolOperations.BeginCreateWithHttpMessagesAsync (resourceGroupName, accountName, poolName, parameters, ifMatch, ifNoneMatch, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Batch.Models.Pool,Microsoft.Azure.Management.Batch.Models.PoolCreateHeaders&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="poolName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Batch.Models.Pool" />
        <Parameter Name="ifMatch" Type="System.String" />
        <Parameter Name="ifNoneMatch" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="697c5-102">Der Name der Ressourcengruppe, die das Batch-Konto enthält.</span><span class="sxs-lookup"><span data-stu-id="697c5-102">The name of the resource group that contains the Batch account.</span></span>
            </param>
        <param name="accountName">
            <span data-ttu-id="697c5-103">Der Name des Batch-Konto.</span><span class="sxs-lookup"><span data-stu-id="697c5-103">The name of the Batch account.</span></span>
            </param>
        <param name="poolName">
            <span data-ttu-id="697c5-104">Der Name des Pools.</span><span class="sxs-lookup"><span data-stu-id="697c5-104">The pool name.</span></span> <span data-ttu-id="697c5-105">Dies muss im Konto eindeutig sein.</span><span class="sxs-lookup"><span data-stu-id="697c5-105">This must be unique within the account.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="697c5-106">Zusätzliche Parameter für die Erstellung von Pools.</span><span class="sxs-lookup"><span data-stu-id="697c5-106">Additional parameters for pool creation.</span></span>
            </param>
        <param name="ifMatch">
            <span data-ttu-id="697c5-107">Die entitätszustandsversion (ETag) Pool zu aktualisieren.</span><span class="sxs-lookup"><span data-stu-id="697c5-107">The entity state (ETag) version of the pool to update.</span></span> <span data-ttu-id="697c5-108">Der Wert "\*" können verwendet werden, um die Operation angewendet werden, wenn der Pool bereits vorhanden ist.</span><span class="sxs-lookup"><span data-stu-id="697c5-108">A value of "\*" can be used to apply the operation only if the pool already exists.</span></span> <span data-ttu-id="697c5-109">Wenn nicht angegeben, wird dieser Vorgang immer angewendet werden.</span><span class="sxs-lookup"><span data-stu-id="697c5-109">If omitted, this operation will always be applied.</span></span>
            </param>
        <param name="ifNoneMatch">
            <span data-ttu-id="697c5-110">Legen Sie auf "\*" um einen neuen Pool erstellt werden, sondern um zu verhindern, aktualisieren einen vorhandenen Pool zu ermöglichen.</span><span class="sxs-lookup"><span data-stu-id="697c5-110">Set to '\*' to allow a new pool to be created, but to prevent updating an existing pool.</span></span> <span data-ttu-id="697c5-111">Andere Werte werden ignoriert.</span><span class="sxs-lookup"><span data-stu-id="697c5-111">Other values will be ignored.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="697c5-112">Die Header, die hinzugefügt werden auf Anforderung.</span><span class="sxs-lookup"><span data-stu-id="697c5-112">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="697c5-113">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="697c5-113">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="697c5-114">Erstellt einen neuen Pool in das angegebene Konto.</span><span class="sxs-lookup"><span data-stu-id="697c5-114">Creates a new pool inside the specified account.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="697c5-115">Wird ausgelöst, wenn der Vorgang einen ungültigen Statuscode zurückgegeben hat.</span><span class="sxs-lookup"><span data-stu-id="697c5-115">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="697c5-116">Wird ausgelöst, wenn nicht die Antwort zu deserialisieren.</span><span class="sxs-lookup"><span data-stu-id="697c5-116">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="697c5-117">Wird ausgelöst, wenn ein erforderlicher Parameter null ist.</span><span class="sxs-lookup"><span data-stu-id="697c5-117">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="BeginDeleteWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationHeaderResponse&lt;Microsoft.Azure.Management.Batch.Models.PoolDeleteHeaders&gt;&gt; BeginDeleteWithHttpMessagesAsync (string resourceGroupName, string accountName, string poolName, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationHeaderResponse`1&lt;class Microsoft.Azure.Management.Batch.Models.PoolDeleteHeaders&gt;&gt; BeginDeleteWithHttpMessagesAsync(string resourceGroupName, string accountName, string poolName, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Batch.IPoolOperations.BeginDeleteWithHttpMessagesAsync(System.String,System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member BeginDeleteWithHttpMessagesAsync : string * string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationHeaderResponse&lt;Microsoft.Azure.Management.Batch.Models.PoolDeleteHeaders&gt;&gt;" Usage="iPoolOperations.BeginDeleteWithHttpMessagesAsync (resourceGroupName, accountName, poolName, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationHeaderResponse&lt;Microsoft.Azure.Management.Batch.Models.PoolDeleteHeaders&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="poolName" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="697c5-118">Der Name der Ressourcengruppe, die das Batch-Konto enthält.</span><span class="sxs-lookup"><span data-stu-id="697c5-118">The name of the resource group that contains the Batch account.</span></span>
            </param>
        <param name="accountName">
            <span data-ttu-id="697c5-119">Der Name des Batch-Konto.</span><span class="sxs-lookup"><span data-stu-id="697c5-119">The name of the Batch account.</span></span>
            </param>
        <param name="poolName">
            <span data-ttu-id="697c5-120">Der Name des Pools.</span><span class="sxs-lookup"><span data-stu-id="697c5-120">The pool name.</span></span> <span data-ttu-id="697c5-121">Dies muss im Konto eindeutig sein.</span><span class="sxs-lookup"><span data-stu-id="697c5-121">This must be unique within the account.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="697c5-122">Die Header, die hinzugefügt werden auf Anforderung.</span><span class="sxs-lookup"><span data-stu-id="697c5-122">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="697c5-123">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="697c5-123">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="697c5-124">Löscht den angegebenen Pool.</span><span class="sxs-lookup"><span data-stu-id="697c5-124">Deletes the specified pool.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="697c5-125">Wird ausgelöst, wenn der Vorgang einen ungültigen Statuscode zurückgegeben hat.</span><span class="sxs-lookup"><span data-stu-id="697c5-125">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="697c5-126">Wird ausgelöst, wenn ein erforderlicher Parameter null ist.</span><span class="sxs-lookup"><span data-stu-id="697c5-126">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="CreateWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Batch.Models.Pool,Microsoft.Azure.Management.Batch.Models.PoolCreateHeaders&gt;&gt; CreateWithHttpMessagesAsync (string resourceGroupName, string accountName, string poolName, Microsoft.Azure.Management.Batch.Models.Pool parameters, string ifMatch = null, string ifNoneMatch = null, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`2&lt;class Microsoft.Azure.Management.Batch.Models.Pool, class Microsoft.Azure.Management.Batch.Models.PoolCreateHeaders&gt;&gt; CreateWithHttpMessagesAsync(string resourceGroupName, string accountName, string poolName, class Microsoft.Azure.Management.Batch.Models.Pool parameters, string ifMatch, string ifNoneMatch, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Batch.IPoolOperations.CreateWithHttpMessagesAsync(System.String,System.String,System.String,Microsoft.Azure.Management.Batch.Models.Pool,System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member CreateWithHttpMessagesAsync : string * string * string * Microsoft.Azure.Management.Batch.Models.Pool * string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Batch.Models.Pool, Microsoft.Azure.Management.Batch.Models.PoolCreateHeaders&gt;&gt;" Usage="iPoolOperations.CreateWithHttpMessagesAsync (resourceGroupName, accountName, poolName, parameters, ifMatch, ifNoneMatch, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Batch.Models.Pool,Microsoft.Azure.Management.Batch.Models.PoolCreateHeaders&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="poolName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Batch.Models.Pool" />
        <Parameter Name="ifMatch" Type="System.String" />
        <Parameter Name="ifNoneMatch" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="697c5-127">Der Name der Ressourcengruppe, die das Batch-Konto enthält.</span><span class="sxs-lookup"><span data-stu-id="697c5-127">The name of the resource group that contains the Batch account.</span></span>
            </param>
        <param name="accountName">
            <span data-ttu-id="697c5-128">Der Name des Batch-Konto.</span><span class="sxs-lookup"><span data-stu-id="697c5-128">The name of the Batch account.</span></span>
            </param>
        <param name="poolName">
            <span data-ttu-id="697c5-129">Der Name des Pools.</span><span class="sxs-lookup"><span data-stu-id="697c5-129">The pool name.</span></span> <span data-ttu-id="697c5-130">Dies muss im Konto eindeutig sein.</span><span class="sxs-lookup"><span data-stu-id="697c5-130">This must be unique within the account.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="697c5-131">Zusätzliche Parameter für die Erstellung von Pools.</span><span class="sxs-lookup"><span data-stu-id="697c5-131">Additional parameters for pool creation.</span></span>
            </param>
        <param name="ifMatch">
            <span data-ttu-id="697c5-132">Die entitätszustandsversion (ETag) Pool zu aktualisieren.</span><span class="sxs-lookup"><span data-stu-id="697c5-132">The entity state (ETag) version of the pool to update.</span></span> <span data-ttu-id="697c5-133">Der Wert "\*" können verwendet werden, um die Operation angewendet werden, wenn der Pool bereits vorhanden ist.</span><span class="sxs-lookup"><span data-stu-id="697c5-133">A value of "\*" can be used to apply the operation only if the pool already exists.</span></span> <span data-ttu-id="697c5-134">Wenn nicht angegeben, wird dieser Vorgang immer angewendet werden.</span><span class="sxs-lookup"><span data-stu-id="697c5-134">If omitted, this operation will always be applied.</span></span>
            </param>
        <param name="ifNoneMatch">
            <span data-ttu-id="697c5-135">Legen Sie auf "\*" um einen neuen Pool erstellt werden, sondern um zu verhindern, aktualisieren einen vorhandenen Pool zu ermöglichen.</span><span class="sxs-lookup"><span data-stu-id="697c5-135">Set to '\*' to allow a new pool to be created, but to prevent updating an existing pool.</span></span> <span data-ttu-id="697c5-136">Andere Werte werden ignoriert.</span><span class="sxs-lookup"><span data-stu-id="697c5-136">Other values will be ignored.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="697c5-137">Die Header, die hinzugefügt werden auf Anforderung.</span><span class="sxs-lookup"><span data-stu-id="697c5-137">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="697c5-138">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="697c5-138">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="697c5-139">Erstellt einen neuen Pool in das angegebene Konto.</span><span class="sxs-lookup"><span data-stu-id="697c5-139">Creates a new pool inside the specified account.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="697c5-140">Wird ausgelöst, wenn der Vorgang einen ungültigen Statuscode zurückgegeben hat.</span><span class="sxs-lookup"><span data-stu-id="697c5-140">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="697c5-141">Wird ausgelöst, wenn nicht die Antwort zu deserialisieren.</span><span class="sxs-lookup"><span data-stu-id="697c5-141">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="697c5-142">Wird ausgelöst, wenn ein erforderlicher Parameter null ist.</span><span class="sxs-lookup"><span data-stu-id="697c5-142">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="DeleteWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationHeaderResponse&lt;Microsoft.Azure.Management.Batch.Models.PoolDeleteHeaders&gt;&gt; DeleteWithHttpMessagesAsync (string resourceGroupName, string accountName, string poolName, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationHeaderResponse`1&lt;class Microsoft.Azure.Management.Batch.Models.PoolDeleteHeaders&gt;&gt; DeleteWithHttpMessagesAsync(string resourceGroupName, string accountName, string poolName, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Batch.IPoolOperations.DeleteWithHttpMessagesAsync(System.String,System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member DeleteWithHttpMessagesAsync : string * string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationHeaderResponse&lt;Microsoft.Azure.Management.Batch.Models.PoolDeleteHeaders&gt;&gt;" Usage="iPoolOperations.DeleteWithHttpMessagesAsync (resourceGroupName, accountName, poolName, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationHeaderResponse&lt;Microsoft.Azure.Management.Batch.Models.PoolDeleteHeaders&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="poolName" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="697c5-143">Der Name der Ressourcengruppe, die das Batch-Konto enthält.</span><span class="sxs-lookup"><span data-stu-id="697c5-143">The name of the resource group that contains the Batch account.</span></span>
            </param>
        <param name="accountName">
            <span data-ttu-id="697c5-144">Der Name des Batch-Konto.</span><span class="sxs-lookup"><span data-stu-id="697c5-144">The name of the Batch account.</span></span>
            </param>
        <param name="poolName">
            <span data-ttu-id="697c5-145">Der Name des Pools.</span><span class="sxs-lookup"><span data-stu-id="697c5-145">The pool name.</span></span> <span data-ttu-id="697c5-146">Dies muss im Konto eindeutig sein.</span><span class="sxs-lookup"><span data-stu-id="697c5-146">This must be unique within the account.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="697c5-147">Die Header, die hinzugefügt werden auf Anforderung.</span><span class="sxs-lookup"><span data-stu-id="697c5-147">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="697c5-148">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="697c5-148">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="697c5-149">Löscht den angegebenen Pool.</span><span class="sxs-lookup"><span data-stu-id="697c5-149">Deletes the specified pool.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="697c5-150">Wird ausgelöst, wenn der Vorgang einen ungültigen Statuscode zurückgegeben hat.</span><span class="sxs-lookup"><span data-stu-id="697c5-150">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="697c5-151">Wird ausgelöst, wenn ein erforderlicher Parameter null ist.</span><span class="sxs-lookup"><span data-stu-id="697c5-151">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="DisableAutoScaleWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Batch.Models.Pool,Microsoft.Azure.Management.Batch.Models.PoolDisableAutoScaleHeaders&gt;&gt; DisableAutoScaleWithHttpMessagesAsync (string resourceGroupName, string accountName, string poolName, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`2&lt;class Microsoft.Azure.Management.Batch.Models.Pool, class Microsoft.Azure.Management.Batch.Models.PoolDisableAutoScaleHeaders&gt;&gt; DisableAutoScaleWithHttpMessagesAsync(string resourceGroupName, string accountName, string poolName, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Batch.IPoolOperations.DisableAutoScaleWithHttpMessagesAsync(System.String,System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member DisableAutoScaleWithHttpMessagesAsync : string * string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Batch.Models.Pool, Microsoft.Azure.Management.Batch.Models.PoolDisableAutoScaleHeaders&gt;&gt;" Usage="iPoolOperations.DisableAutoScaleWithHttpMessagesAsync (resourceGroupName, accountName, poolName, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Batch.Models.Pool,Microsoft.Azure.Management.Batch.Models.PoolDisableAutoScaleHeaders&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="poolName" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="697c5-152">Der Name der Ressourcengruppe, die das Batch-Konto enthält.</span><span class="sxs-lookup"><span data-stu-id="697c5-152">The name of the resource group that contains the Batch account.</span></span>
            </param>
        <param name="accountName">
            <span data-ttu-id="697c5-153">Der Name des Batch-Konto.</span><span class="sxs-lookup"><span data-stu-id="697c5-153">The name of the Batch account.</span></span>
            </param>
        <param name="poolName">
            <span data-ttu-id="697c5-154">Der Name des Pools.</span><span class="sxs-lookup"><span data-stu-id="697c5-154">The pool name.</span></span> <span data-ttu-id="697c5-155">Dies muss im Konto eindeutig sein.</span><span class="sxs-lookup"><span data-stu-id="697c5-155">This must be unique within the account.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="697c5-156">Die Header, die hinzugefügt werden auf Anforderung.</span><span class="sxs-lookup"><span data-stu-id="697c5-156">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="697c5-157">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="697c5-157">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="697c5-158">Deaktiviert die automatische Skalierung für einen Pool.</span><span class="sxs-lookup"><span data-stu-id="697c5-158">Disables automatic scaling for a pool.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="697c5-159">Wird ausgelöst, wenn der Vorgang einen ungültigen Statuscode zurückgegeben hat.</span><span class="sxs-lookup"><span data-stu-id="697c5-159">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="697c5-160">Wird ausgelöst, wenn nicht die Antwort zu deserialisieren.</span><span class="sxs-lookup"><span data-stu-id="697c5-160">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="697c5-161">Wird ausgelöst, wenn ein erforderlicher Parameter null ist.</span><span class="sxs-lookup"><span data-stu-id="697c5-161">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="GetWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Batch.Models.Pool,Microsoft.Azure.Management.Batch.Models.PoolGetHeaders&gt;&gt; GetWithHttpMessagesAsync (string resourceGroupName, string accountName, string poolName, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`2&lt;class Microsoft.Azure.Management.Batch.Models.Pool, class Microsoft.Azure.Management.Batch.Models.PoolGetHeaders&gt;&gt; GetWithHttpMessagesAsync(string resourceGroupName, string accountName, string poolName, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Batch.IPoolOperations.GetWithHttpMessagesAsync(System.String,System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetWithHttpMessagesAsync : string * string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Batch.Models.Pool, Microsoft.Azure.Management.Batch.Models.PoolGetHeaders&gt;&gt;" Usage="iPoolOperations.GetWithHttpMessagesAsync (resourceGroupName, accountName, poolName, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Batch.Models.Pool,Microsoft.Azure.Management.Batch.Models.PoolGetHeaders&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="poolName" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="697c5-162">Der Name der Ressourcengruppe, die das Batch-Konto enthält.</span><span class="sxs-lookup"><span data-stu-id="697c5-162">The name of the resource group that contains the Batch account.</span></span>
            </param>
        <param name="accountName">
            <span data-ttu-id="697c5-163">Der Name des Batch-Konto.</span><span class="sxs-lookup"><span data-stu-id="697c5-163">The name of the Batch account.</span></span>
            </param>
        <param name="poolName">
            <span data-ttu-id="697c5-164">Der Name des Pools.</span><span class="sxs-lookup"><span data-stu-id="697c5-164">The pool name.</span></span> <span data-ttu-id="697c5-165">Dies muss im Konto eindeutig sein.</span><span class="sxs-lookup"><span data-stu-id="697c5-165">This must be unique within the account.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="697c5-166">Die Header, die hinzugefügt werden auf Anforderung.</span><span class="sxs-lookup"><span data-stu-id="697c5-166">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="697c5-167">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="697c5-167">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="697c5-168">Ruft Informationen über den angegebenen Pool ab.</span><span class="sxs-lookup"><span data-stu-id="697c5-168">Gets information about the specified pool.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="697c5-169">Wird ausgelöst, wenn der Vorgang einen ungültigen Statuscode zurückgegeben hat.</span><span class="sxs-lookup"><span data-stu-id="697c5-169">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="697c5-170">Wird ausgelöst, wenn nicht die Antwort zu deserialisieren.</span><span class="sxs-lookup"><span data-stu-id="697c5-170">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="697c5-171">Wird ausgelöst, wenn ein erforderlicher Parameter null ist.</span><span class="sxs-lookup"><span data-stu-id="697c5-171">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="ListByBatchAccountNextWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Batch.Models.Pool&gt;&gt;&gt; ListByBatchAccountNextWithHttpMessagesAsync (string nextPageLink, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Batch.Models.Pool&gt;&gt;&gt; ListByBatchAccountNextWithHttpMessagesAsync(string nextPageLink, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Batch.IPoolOperations.ListByBatchAccountNextWithHttpMessagesAsync(System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListByBatchAccountNextWithHttpMessagesAsync : string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Batch.Models.Pool&gt;&gt;&gt;" Usage="iPoolOperations.ListByBatchAccountNextWithHttpMessagesAsync (nextPageLink, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Batch.Models.Pool&gt;&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="nextPageLink">
            <span data-ttu-id="697c5-172">Die "NextLink" aus dem vorherigen erfolgreichen Aufruf List-Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="697c5-172">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="697c5-173">Die Header, die hinzugefügt werden auf Anforderung.</span><span class="sxs-lookup"><span data-stu-id="697c5-173">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="697c5-174">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="697c5-174">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="697c5-175">Listet alle Pools im angegebenen Konto.</span><span class="sxs-lookup"><span data-stu-id="697c5-175">Lists all of the pools in the specified account.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="697c5-176">Wird ausgelöst, wenn der Vorgang einen ungültigen Statuscode zurückgegeben hat.</span><span class="sxs-lookup"><span data-stu-id="697c5-176">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="697c5-177">Wird ausgelöst, wenn nicht die Antwort zu deserialisieren.</span><span class="sxs-lookup"><span data-stu-id="697c5-177">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="697c5-178">Wird ausgelöst, wenn ein erforderlicher Parameter null ist.</span><span class="sxs-lookup"><span data-stu-id="697c5-178">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="ListByBatchAccountWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Batch.Models.Pool&gt;&gt;&gt; ListByBatchAccountWithHttpMessagesAsync (string resourceGroupName, string accountName, Nullable&lt;int&gt; maxresults = null, string select = null, string filter = null, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Batch.Models.Pool&gt;&gt;&gt; ListByBatchAccountWithHttpMessagesAsync(string resourceGroupName, string accountName, valuetype System.Nullable`1&lt;int32&gt; maxresults, string select, string filter, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Batch.IPoolOperations.ListByBatchAccountWithHttpMessagesAsync(System.String,System.String,System.Nullable{System.Int32},System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListByBatchAccountWithHttpMessagesAsync : string * string * Nullable&lt;int&gt; * string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Batch.Models.Pool&gt;&gt;&gt;" Usage="iPoolOperations.ListByBatchAccountWithHttpMessagesAsync (resourceGroupName, accountName, maxresults, select, filter, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Batch.Models.Pool&gt;&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="maxresults" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="select" Type="System.String" />
        <Parameter Name="filter" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
             <span data-ttu-id="697c5-179">Der Name der Ressourcengruppe, die das Batch-Konto enthält.</span><span class="sxs-lookup"><span data-stu-id="697c5-179">The name of the resource group that contains the Batch account.</span></span>
             </param>
        <param name="accountName">
             <span data-ttu-id="697c5-180">Der Name des Batch-Konto.</span><span class="sxs-lookup"><span data-stu-id="697c5-180">The name of the Batch account.</span></span>
             </param>
        <param name="maxresults">
             <span data-ttu-id="697c5-181">Die maximale Anzahl von Elementen, die in der Antwort zurückgegeben.</span><span class="sxs-lookup"><span data-stu-id="697c5-181">The maximum number of items to return in the response.</span></span>
             </param>
        <param name="select">
             <span data-ttu-id="697c5-182">Durch Trennzeichen getrennte Liste von Eigenschaften, die zurückgegeben werden sollen.</span><span class="sxs-lookup"><span data-stu-id="697c5-182">Comma separated list of properties that should be returned.</span></span> <span data-ttu-id="697c5-183">z. B. "Eigenschaften/ProvisioningState".</span><span class="sxs-lookup"><span data-stu-id="697c5-183">e.g. "properties/provisioningState".</span></span> <span data-ttu-id="697c5-184">Nur die ersten Ebene unter Eigenschaften Eigenschaften / zur Auswahl gültig sind.</span><span class="sxs-lookup"><span data-stu-id="697c5-184">Only top level properties under properties/ are valid for selection.</span></span>
             </param>
        <param name="filter">
             <span data-ttu-id="697c5-185">OData-Filterausdruck.</span><span class="sxs-lookup"><span data-stu-id="697c5-185">OData filter expression.</span></span> <span data-ttu-id="697c5-186">Gültige Eigenschaften für das Filtern lauten:</span><span class="sxs-lookup"><span data-stu-id="697c5-186">Valid properties for filtering are:</span></span>
            
             <span data-ttu-id="697c5-187">Benennen von Eigenschaften/AllocationState Eigenschaften/AllocationStateTransitionTime Eigenschaften/CreationTime-Eigenschaften/ProvisioningState-Eigenschaften/ProvisioningStateTransitionTime Eigenschaften/LastModified-Eigenschaften/VmSize Eigenschaften / InterNodeCommunication Eigenschaften/ScaleSettings/automatische Skalierung Eigenschaften/ScaleSettings/fixedScale</span><span class="sxs-lookup"><span data-stu-id="697c5-187">name properties/allocationState properties/allocationStateTransitionTime properties/creationTime properties/provisioningState properties/provisioningStateTransitionTime properties/lastModified properties/vmSize properties/interNodeCommunication properties/scaleSettings/autoScale properties/scaleSettings/fixedScale</span></span>
             </param>
        <param name="customHeaders">
             <span data-ttu-id="697c5-188">Die Header, die hinzugefügt werden auf Anforderung.</span><span class="sxs-lookup"><span data-stu-id="697c5-188">The headers that will be added to request.</span></span>
             </param>
        <param name="cancellationToken">
             <span data-ttu-id="697c5-189">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="697c5-189">The cancellation token.</span></span>
             </param>
        <summary>
             <span data-ttu-id="697c5-190">Listet alle Pools im angegebenen Konto.</span><span class="sxs-lookup"><span data-stu-id="697c5-190">Lists all of the pools in the specified account.</span></span>
             </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
             <span data-ttu-id="697c5-191">Wird ausgelöst, wenn der Vorgang einen ungültigen Statuscode zurückgegeben hat.</span><span class="sxs-lookup"><span data-stu-id="697c5-191">Thrown when the operation returned an invalid status code</span></span>
             </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
             <span data-ttu-id="697c5-192">Wird ausgelöst, wenn nicht die Antwort zu deserialisieren.</span><span class="sxs-lookup"><span data-stu-id="697c5-192">Thrown when unable to deserialize the response</span></span>
             </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
             <span data-ttu-id="697c5-193">Wird ausgelöst, wenn ein erforderlicher Parameter null ist.</span><span class="sxs-lookup"><span data-stu-id="697c5-193">Thrown when a required parameter is null</span></span>
             </exception>
      </Docs>
    </Member>
    <Member MemberName="StopResizeWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Batch.Models.Pool,Microsoft.Azure.Management.Batch.Models.PoolStopResizeHeaders&gt;&gt; StopResizeWithHttpMessagesAsync (string resourceGroupName, string accountName, string poolName, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`2&lt;class Microsoft.Azure.Management.Batch.Models.Pool, class Microsoft.Azure.Management.Batch.Models.PoolStopResizeHeaders&gt;&gt; StopResizeWithHttpMessagesAsync(string resourceGroupName, string accountName, string poolName, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Batch.IPoolOperations.StopResizeWithHttpMessagesAsync(System.String,System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member StopResizeWithHttpMessagesAsync : string * string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Batch.Models.Pool, Microsoft.Azure.Management.Batch.Models.PoolStopResizeHeaders&gt;&gt;" Usage="iPoolOperations.StopResizeWithHttpMessagesAsync (resourceGroupName, accountName, poolName, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Batch.Models.Pool,Microsoft.Azure.Management.Batch.Models.PoolStopResizeHeaders&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="poolName" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="697c5-194">Der Name der Ressourcengruppe, die das Batch-Konto enthält.</span><span class="sxs-lookup"><span data-stu-id="697c5-194">The name of the resource group that contains the Batch account.</span></span>
            </param>
        <param name="accountName">
            <span data-ttu-id="697c5-195">Der Name des Batch-Konto.</span><span class="sxs-lookup"><span data-stu-id="697c5-195">The name of the Batch account.</span></span>
            </param>
        <param name="poolName">
            <span data-ttu-id="697c5-196">Der Name des Pools.</span><span class="sxs-lookup"><span data-stu-id="697c5-196">The pool name.</span></span> <span data-ttu-id="697c5-197">Dies muss im Konto eindeutig sein.</span><span class="sxs-lookup"><span data-stu-id="697c5-197">This must be unique within the account.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="697c5-198">Die Header, die hinzugefügt werden auf Anforderung.</span><span class="sxs-lookup"><span data-stu-id="697c5-198">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="697c5-199">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="697c5-199">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="697c5-200">Beendet einen aktiven größenänderungsvorgang für den Pool an.</span><span class="sxs-lookup"><span data-stu-id="697c5-200">Stops an ongoing resize operation on the pool.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="697c5-201">Dies wird den Pool nicht auf den ursprünglichen Zustand vor der Größenänderung wiederhergestellt: nur beendet wird, keine weiteren Änderungen vorgenommen werden, und der Pool behält den aktuellen Zustand.</span><span class="sxs-lookup"><span data-stu-id="697c5-201">This does not restore the pool to its previous state before the resize operation: it only stops any further changes being made, and the pool maintains its current state.</span></span> <span data-ttu-id="697c5-202">Nach dem Beenden stabilisiert der Pool an die Anzahl der Knoten, den sie an, wenn der Beendigungsvorgang abgeschlossen wurde.</span><span class="sxs-lookup"><span data-stu-id="697c5-202">After stopping, the pool stabilizes at the number of nodes it was at when the stop operation was done.</span></span> <span data-ttu-id="697c5-203">Während des Beendigungsvorgangs ändert den Zuordnungsstatus des Pools zunächst zu beenden und dann zu gleichmäßig.</span><span class="sxs-lookup"><span data-stu-id="697c5-203">During the stop operation, the pool allocation state changes first to stopping and then to steady.</span></span> <span data-ttu-id="697c5-204">Ein größenänderungsvorgang muss eine explizite Resize Pool-Anfrage nicht. Diese API kann auch verwendet werden, auf die anfängliche Größe des Pools anhalten, wenn es erstellt wird.</span><span class="sxs-lookup"><span data-stu-id="697c5-204">A resize operation need not be an explicit resize pool request; this API can also be used to halt the initial sizing of the pool when it is created.</span></span>
            </remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="697c5-205">Wird ausgelöst, wenn der Vorgang einen ungültigen Statuscode zurückgegeben hat.</span><span class="sxs-lookup"><span data-stu-id="697c5-205">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="697c5-206">Wird ausgelöst, wenn nicht die Antwort zu deserialisieren.</span><span class="sxs-lookup"><span data-stu-id="697c5-206">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="697c5-207">Wird ausgelöst, wenn ein erforderlicher Parameter null ist.</span><span class="sxs-lookup"><span data-stu-id="697c5-207">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="UpdateWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Batch.Models.Pool,Microsoft.Azure.Management.Batch.Models.PoolUpdateHeaders&gt;&gt; UpdateWithHttpMessagesAsync (string resourceGroupName, string accountName, string poolName, Microsoft.Azure.Management.Batch.Models.Pool parameters, string ifMatch = null, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`2&lt;class Microsoft.Azure.Management.Batch.Models.Pool, class Microsoft.Azure.Management.Batch.Models.PoolUpdateHeaders&gt;&gt; UpdateWithHttpMessagesAsync(string resourceGroupName, string accountName, string poolName, class Microsoft.Azure.Management.Batch.Models.Pool parameters, string ifMatch, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Batch.IPoolOperations.UpdateWithHttpMessagesAsync(System.String,System.String,System.String,Microsoft.Azure.Management.Batch.Models.Pool,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member UpdateWithHttpMessagesAsync : string * string * string * Microsoft.Azure.Management.Batch.Models.Pool * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Batch.Models.Pool, Microsoft.Azure.Management.Batch.Models.PoolUpdateHeaders&gt;&gt;" Usage="iPoolOperations.UpdateWithHttpMessagesAsync (resourceGroupName, accountName, poolName, parameters, ifMatch, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Batch.Models.Pool,Microsoft.Azure.Management.Batch.Models.PoolUpdateHeaders&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="poolName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Batch.Models.Pool" />
        <Parameter Name="ifMatch" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="697c5-208">Der Name der Ressourcengruppe, die das Batch-Konto enthält.</span><span class="sxs-lookup"><span data-stu-id="697c5-208">The name of the resource group that contains the Batch account.</span></span>
            </param>
        <param name="accountName">
            <span data-ttu-id="697c5-209">Der Name des Batch-Konto.</span><span class="sxs-lookup"><span data-stu-id="697c5-209">The name of the Batch account.</span></span>
            </param>
        <param name="poolName">
            <span data-ttu-id="697c5-210">Der Name des Pools.</span><span class="sxs-lookup"><span data-stu-id="697c5-210">The pool name.</span></span> <span data-ttu-id="697c5-211">Dies muss im Konto eindeutig sein.</span><span class="sxs-lookup"><span data-stu-id="697c5-211">This must be unique within the account.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="697c5-212">Pooleigenschaften, die aktualisiert werden sollen.</span><span class="sxs-lookup"><span data-stu-id="697c5-212">Pool properties that should be updated.</span></span> <span data-ttu-id="697c5-213">Eigenschaften, die bereitgestellt werden aktualisiert werden, eine Eigenschaft nicht angegeben wird nicht geändert werden.</span><span class="sxs-lookup"><span data-stu-id="697c5-213">Properties that are supplied will be updated, any property not supplied will be unchanged.</span></span>
            </param>
        <param name="ifMatch">
            <span data-ttu-id="697c5-214">Die entitätszustandsversion (ETag) Pool zu aktualisieren.</span><span class="sxs-lookup"><span data-stu-id="697c5-214">The entity state (ETag) version of the pool to update.</span></span> <span data-ttu-id="697c5-215">Dieser Wert ausgelassen oder auf festgelegt werden kann "\*" um den Vorgang ohne Bedingung anzuwenden.</span><span class="sxs-lookup"><span data-stu-id="697c5-215">This value can be omitted or set to "\*" to apply the operation unconditionally.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="697c5-216">Die Header, die hinzugefügt werden auf Anforderung.</span><span class="sxs-lookup"><span data-stu-id="697c5-216">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="697c5-217">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="697c5-217">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="697c5-218">Aktualisiert die Eigenschaften eines vorhandenen Pools.</span><span class="sxs-lookup"><span data-stu-id="697c5-218">Updates the properties of an existing pool.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="697c5-219">Wird ausgelöst, wenn der Vorgang einen ungültigen Statuscode zurückgegeben hat.</span><span class="sxs-lookup"><span data-stu-id="697c5-219">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="697c5-220">Wird ausgelöst, wenn nicht die Antwort zu deserialisieren.</span><span class="sxs-lookup"><span data-stu-id="697c5-220">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="697c5-221">Wird ausgelöst, wenn ein erforderlicher Parameter null ist.</span><span class="sxs-lookup"><span data-stu-id="697c5-221">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>