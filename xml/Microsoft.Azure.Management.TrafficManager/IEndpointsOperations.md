<Type Name="IEndpointsOperations" FullName="Microsoft.Azure.Management.TrafficManager.IEndpointsOperations">
  <TypeSignature Language="C#" Value="public interface IEndpointsOperations" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IEndpointsOperations" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.TrafficManager.IEndpointsOperations" />
  <TypeSignature Language="VB.NET" Value="Public Interface IEndpointsOperations" />
  <TypeSignature Language="F#" Value="type IEndpointsOperations = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.TrafficManager</AssemblyName>
    <AssemblyVersion>2.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="60a16-101">EndpointsOperations-Vorgänge.</span><span class="sxs-lookup"><span data-stu-id="60a16-101">EndpointsOperations operations.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="CreateOrUpdateWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.TrafficManager.Models.Endpoint&gt;&gt; CreateOrUpdateWithHttpMessagesAsync (string resourceGroupName, string profileName, string endpointType, string endpointName, Microsoft.Azure.Management.TrafficManager.Models.Endpoint parameters, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Management.TrafficManager.Models.Endpoint&gt;&gt; CreateOrUpdateWithHttpMessagesAsync(string resourceGroupName, string profileName, string endpointType, string endpointName, class Microsoft.Azure.Management.TrafficManager.Models.Endpoint parameters, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.TrafficManager.IEndpointsOperations.CreateOrUpdateWithHttpMessagesAsync(System.String,System.String,System.String,System.String,Microsoft.Azure.Management.TrafficManager.Models.Endpoint,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member CreateOrUpdateWithHttpMessagesAsync : string * string * string * string * Microsoft.Azure.Management.TrafficManager.Models.Endpoint * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.TrafficManager.Models.Endpoint&gt;&gt;" Usage="iEndpointsOperations.CreateOrUpdateWithHttpMessagesAsync (resourceGroupName, profileName, endpointType, endpointName, parameters, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.TrafficManager</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.TrafficManager.Models.Endpoint&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="profileName" Type="System.String" />
        <Parameter Name="endpointType" Type="System.String" />
        <Parameter Name="endpointName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.TrafficManager.Models.Endpoint" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="60a16-102">Der Name der Ressourcengruppe, enthält die Traffic Manager-Endpunkt erstellt oder aktualisiert werden.</span><span class="sxs-lookup"><span data-stu-id="60a16-102">The name of the resource group containing the Traffic Manager endpoint to be created or updated.</span></span>
            </param>
        <param name="profileName">
            <span data-ttu-id="60a16-103">Der Name des Traffic Manager-Profils.</span><span class="sxs-lookup"><span data-stu-id="60a16-103">The name of the Traffic Manager profile.</span></span>
            </param>
        <param name="endpointType">
            <span data-ttu-id="60a16-104">Der Typ des Traffic Manager-Endpunkt erstellt oder aktualisiert werden.</span><span class="sxs-lookup"><span data-stu-id="60a16-104">The type of the Traffic Manager endpoint to be created or updated.</span></span>
            </param>
        <param name="endpointName">
            <span data-ttu-id="60a16-105">Der Name des Traffic Manager-Endpunkt erstellt oder aktualisiert werden.</span><span class="sxs-lookup"><span data-stu-id="60a16-105">The name of the Traffic Manager endpoint to be created or updated.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="60a16-106">Die Traffic Manager Endpunktparameter für den Vorgang CreateOrUpdate bereitgestellte.</span><span class="sxs-lookup"><span data-stu-id="60a16-106">The Traffic Manager endpoint parameters supplied to the CreateOrUpdate operation.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="60a16-107">Die Header, die hinzugefügt werden auf Anforderung.</span><span class="sxs-lookup"><span data-stu-id="60a16-107">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="60a16-108">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="60a16-108">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="60a16-109">Erstellt oder aktualisiert einen Traffic Manager-Endpunkt.</span><span class="sxs-lookup"><span data-stu-id="60a16-109">Create or update a Traffic Manager endpoint.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="60a16-110">Wird ausgelöst, wenn der Vorgang einen ungültigen Statuscode zurückgegeben hat.</span><span class="sxs-lookup"><span data-stu-id="60a16-110">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="60a16-111">Wird ausgelöst, wenn nicht die Antwort zu deserialisieren.</span><span class="sxs-lookup"><span data-stu-id="60a16-111">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="60a16-112">Wird ausgelöst, wenn ein erforderlicher Parameter null ist.</span><span class="sxs-lookup"><span data-stu-id="60a16-112">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="DeleteWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.TrafficManager.Models.DeleteOperationResult&gt;&gt; DeleteWithHttpMessagesAsync (string resourceGroupName, string profileName, string endpointType, string endpointName, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Management.TrafficManager.Models.DeleteOperationResult&gt;&gt; DeleteWithHttpMessagesAsync(string resourceGroupName, string profileName, string endpointType, string endpointName, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.TrafficManager.IEndpointsOperations.DeleteWithHttpMessagesAsync(System.String,System.String,System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member DeleteWithHttpMessagesAsync : string * string * string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.TrafficManager.Models.DeleteOperationResult&gt;&gt;" Usage="iEndpointsOperations.DeleteWithHttpMessagesAsync (resourceGroupName, profileName, endpointType, endpointName, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.TrafficManager</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.TrafficManager.Models.DeleteOperationResult&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="profileName" Type="System.String" />
        <Parameter Name="endpointType" Type="System.String" />
        <Parameter Name="endpointName" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="60a16-113">Der Name der Ressourcengruppe, die Traffic Manager-Dienstendpunkt enthält, gelöscht werden soll.</span><span class="sxs-lookup"><span data-stu-id="60a16-113">The name of the resource group containing the Traffic Manager endpoint to be deleted.</span></span>
            </param>
        <param name="profileName">
            <span data-ttu-id="60a16-114">Der Name des Traffic Manager-Profils.</span><span class="sxs-lookup"><span data-stu-id="60a16-114">The name of the Traffic Manager profile.</span></span>
            </param>
        <param name="endpointType">
            <span data-ttu-id="60a16-115">Der Typ des Traffic Manager-Endpunkt gelöscht werden soll.</span><span class="sxs-lookup"><span data-stu-id="60a16-115">The type of the Traffic Manager endpoint to be deleted.</span></span>
            </param>
        <param name="endpointName">
            <span data-ttu-id="60a16-116">Der Name des Traffic Manager-Endpunkt gelöscht werden soll.</span><span class="sxs-lookup"><span data-stu-id="60a16-116">The name of the Traffic Manager endpoint to be deleted.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="60a16-117">Die Header, die hinzugefügt werden auf Anforderung.</span><span class="sxs-lookup"><span data-stu-id="60a16-117">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="60a16-118">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="60a16-118">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="60a16-119">Löscht einen Traffic Manager-Endpunkt an.</span><span class="sxs-lookup"><span data-stu-id="60a16-119">Deletes a Traffic Manager endpoint.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="60a16-120">Wird ausgelöst, wenn der Vorgang einen ungültigen Statuscode zurückgegeben hat.</span><span class="sxs-lookup"><span data-stu-id="60a16-120">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="60a16-121">Wird ausgelöst, wenn nicht die Antwort zu deserialisieren.</span><span class="sxs-lookup"><span data-stu-id="60a16-121">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="60a16-122">Wird ausgelöst, wenn ein erforderlicher Parameter null ist.</span><span class="sxs-lookup"><span data-stu-id="60a16-122">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="GetWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.TrafficManager.Models.Endpoint&gt;&gt; GetWithHttpMessagesAsync (string resourceGroupName, string profileName, string endpointType, string endpointName, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Management.TrafficManager.Models.Endpoint&gt;&gt; GetWithHttpMessagesAsync(string resourceGroupName, string profileName, string endpointType, string endpointName, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.TrafficManager.IEndpointsOperations.GetWithHttpMessagesAsync(System.String,System.String,System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetWithHttpMessagesAsync : string * string * string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.TrafficManager.Models.Endpoint&gt;&gt;" Usage="iEndpointsOperations.GetWithHttpMessagesAsync (resourceGroupName, profileName, endpointType, endpointName, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.TrafficManager</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.TrafficManager.Models.Endpoint&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="profileName" Type="System.String" />
        <Parameter Name="endpointType" Type="System.String" />
        <Parameter Name="endpointName" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="60a16-123">Der Name der Ressourcengruppe, die die Traffic Manager-Endpunkt enthält.</span><span class="sxs-lookup"><span data-stu-id="60a16-123">The name of the resource group containing the Traffic Manager endpoint.</span></span>
            </param>
        <param name="profileName">
            <span data-ttu-id="60a16-124">Der Name des Traffic Manager-Profils.</span><span class="sxs-lookup"><span data-stu-id="60a16-124">The name of the Traffic Manager profile.</span></span>
            </param>
        <param name="endpointType">
            <span data-ttu-id="60a16-125">Der Typ des Traffic Manager-Endpunkt.</span><span class="sxs-lookup"><span data-stu-id="60a16-125">The type of the Traffic Manager endpoint.</span></span>
            </param>
        <param name="endpointName">
            <span data-ttu-id="60a16-126">Der Name des Traffic Manager-Endpunkt.</span><span class="sxs-lookup"><span data-stu-id="60a16-126">The name of the Traffic Manager endpoint.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="60a16-127">Die Header, die hinzugefügt werden auf Anforderung.</span><span class="sxs-lookup"><span data-stu-id="60a16-127">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="60a16-128">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="60a16-128">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="60a16-129">Ruft eine Traffic Manager-Endpunkt ab.</span><span class="sxs-lookup"><span data-stu-id="60a16-129">Gets a Traffic Manager endpoint.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="60a16-130">Wird ausgelöst, wenn der Vorgang einen ungültigen Statuscode zurückgegeben hat.</span><span class="sxs-lookup"><span data-stu-id="60a16-130">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="60a16-131">Wird ausgelöst, wenn nicht die Antwort zu deserialisieren.</span><span class="sxs-lookup"><span data-stu-id="60a16-131">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="60a16-132">Wird ausgelöst, wenn ein erforderlicher Parameter null ist.</span><span class="sxs-lookup"><span data-stu-id="60a16-132">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="UpdateWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.TrafficManager.Models.Endpoint&gt;&gt; UpdateWithHttpMessagesAsync (string resourceGroupName, string profileName, string endpointType, string endpointName, Microsoft.Azure.Management.TrafficManager.Models.Endpoint parameters, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Management.TrafficManager.Models.Endpoint&gt;&gt; UpdateWithHttpMessagesAsync(string resourceGroupName, string profileName, string endpointType, string endpointName, class Microsoft.Azure.Management.TrafficManager.Models.Endpoint parameters, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.TrafficManager.IEndpointsOperations.UpdateWithHttpMessagesAsync(System.String,System.String,System.String,System.String,Microsoft.Azure.Management.TrafficManager.Models.Endpoint,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member UpdateWithHttpMessagesAsync : string * string * string * string * Microsoft.Azure.Management.TrafficManager.Models.Endpoint * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.TrafficManager.Models.Endpoint&gt;&gt;" Usage="iEndpointsOperations.UpdateWithHttpMessagesAsync (resourceGroupName, profileName, endpointType, endpointName, parameters, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.TrafficManager</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.TrafficManager.Models.Endpoint&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="profileName" Type="System.String" />
        <Parameter Name="endpointType" Type="System.String" />
        <Parameter Name="endpointName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.TrafficManager.Models.Endpoint" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="60a16-133">Der Name der Ressourcengruppe, die Traffic Manager-Dienstendpunkt enthält, aktualisiert werden.</span><span class="sxs-lookup"><span data-stu-id="60a16-133">The name of the resource group containing the Traffic Manager endpoint to be updated.</span></span>
            </param>
        <param name="profileName">
            <span data-ttu-id="60a16-134">Der Name des Traffic Manager-Profils.</span><span class="sxs-lookup"><span data-stu-id="60a16-134">The name of the Traffic Manager profile.</span></span>
            </param>
        <param name="endpointType">
            <span data-ttu-id="60a16-135">Der Typ des Endpunkts Traffic Manager aktualisiert werden.</span><span class="sxs-lookup"><span data-stu-id="60a16-135">The type of the Traffic Manager endpoint to be updated.</span></span>
            </param>
        <param name="endpointName">
            <span data-ttu-id="60a16-136">Der Name des Endpunkts Traffic Manager aktualisiert werden.</span><span class="sxs-lookup"><span data-stu-id="60a16-136">The name of the Traffic Manager endpoint to be updated.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="60a16-137">Die Traffic Manager Endpunktparameter auf den Updatevorgang angegeben.</span><span class="sxs-lookup"><span data-stu-id="60a16-137">The Traffic Manager endpoint parameters supplied to the Update operation.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="60a16-138">Die Header, die hinzugefügt werden auf Anforderung.</span><span class="sxs-lookup"><span data-stu-id="60a16-138">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="60a16-139">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="60a16-139">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="60a16-140">Aktualisieren Sie einen Traffic Manager-Endpunkt.</span><span class="sxs-lookup"><span data-stu-id="60a16-140">Update a Traffic Manager endpoint.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="60a16-141">Wird ausgelöst, wenn der Vorgang einen ungültigen Statuscode zurückgegeben hat.</span><span class="sxs-lookup"><span data-stu-id="60a16-141">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="60a16-142">Wird ausgelöst, wenn nicht die Antwort zu deserialisieren.</span><span class="sxs-lookup"><span data-stu-id="60a16-142">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="60a16-143">Wird ausgelöst, wenn ein erforderlicher Parameter null ist.</span><span class="sxs-lookup"><span data-stu-id="60a16-143">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>