<Type Name="IIotHubResourceOperations" FullName="Microsoft.Azure.Management.IotHub.IIotHubResourceOperations">
  <TypeSignature Language="C#" Value="public interface IIotHubResourceOperations" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IIotHubResourceOperations" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.IotHub.IIotHubResourceOperations" />
  <TypeSignature Language="VB.NET" Value="Public Interface IIotHubResourceOperations" />
  <TypeSignature Language="F#" Value="type IIotHubResourceOperations = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.IotHub</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="283fa-101">IotHubResourceOperations-Vorgänge.</span><span class="sxs-lookup"><span data-stu-id="283fa-101">IotHubResourceOperations operations.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="BeginCreateOrUpdateWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.IotHub.Models.IotHubDescription&gt;&gt; BeginCreateOrUpdateWithHttpMessagesAsync (string resourceGroupName, string resourceName, Microsoft.Azure.Management.IotHub.Models.IotHubDescription iotHubDescription, string ifMatch = null, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Management.IotHub.Models.IotHubDescription&gt;&gt; BeginCreateOrUpdateWithHttpMessagesAsync(string resourceGroupName, string resourceName, class Microsoft.Azure.Management.IotHub.Models.IotHubDescription iotHubDescription, string ifMatch, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.IotHub.IIotHubResourceOperations.BeginCreateOrUpdateWithHttpMessagesAsync(System.String,System.String,Microsoft.Azure.Management.IotHub.Models.IotHubDescription,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member BeginCreateOrUpdateWithHttpMessagesAsync : string * string * Microsoft.Azure.Management.IotHub.Models.IotHubDescription * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.IotHub.Models.IotHubDescription&gt;&gt;" Usage="iIotHubResourceOperations.BeginCreateOrUpdateWithHttpMessagesAsync (resourceGroupName, resourceName, iotHubDescription, ifMatch, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.IotHub</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.IotHub.Models.IotHubDescription&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="resourceName" Type="System.String" />
        <Parameter Name="iotHubDescription" Type="Microsoft.Azure.Management.IotHub.Models.IotHubDescription" />
        <Parameter Name="ifMatch" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="283fa-102">Der Name der Ressourcengruppe, die den IoT Hub enthält.</span><span class="sxs-lookup"><span data-stu-id="283fa-102">The name of the resource group that contains the IoT hub.</span></span>
            </param>
        <param name="resourceName">
            <span data-ttu-id="283fa-103">Der Name der IoT Hub.</span><span class="sxs-lookup"><span data-stu-id="283fa-103">The name of the IoT hub.</span></span>
            </param>
        <param name="iotHubDescription">
            <span data-ttu-id="283fa-104">Der IoT Hub-Metadaten und Sicherheitsmetadaten.</span><span class="sxs-lookup"><span data-stu-id="283fa-104">The IoT hub metadata and security metadata.</span></span>
            </param>
        <param name="ifMatch">
            <span data-ttu-id="283fa-105">ETag der IoT Hub.</span><span class="sxs-lookup"><span data-stu-id="283fa-105">ETag of the IoT Hub.</span></span> <span data-ttu-id="283fa-106">Geben Sie zum Erstellen einer neuen IoT Hub.</span><span class="sxs-lookup"><span data-stu-id="283fa-106">Do not specify for creating a brand new IoT Hub.</span></span> <span data-ttu-id="283fa-107">Zum Aktualisieren eines vorhandenen IoT Hub erforderlich.</span><span class="sxs-lookup"><span data-stu-id="283fa-107">Required to update an existing IoT Hub.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="283fa-108">Die Header, die hinzugefügt werden auf Anforderung.</span><span class="sxs-lookup"><span data-stu-id="283fa-108">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="283fa-109">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="283fa-109">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="283fa-110">Erstellen Sie oder aktualisieren Sie die Metadaten eines IoT Hubs.</span><span class="sxs-lookup"><span data-stu-id="283fa-110">Create or update the metadata of an IoT hub.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="283fa-111">Erstellen Sie oder aktualisieren Sie die Metadaten eines Iot Hubs.</span><span class="sxs-lookup"><span data-stu-id="283fa-111">Create or update the metadata of an Iot hub.</span></span> <span data-ttu-id="283fa-112">Zum Ändern einer Eigenschaft das übliche Muster ist die IoT Hub-Metadaten und Sicherheitsmetadaten abzurufen, und kombinieren sie Sie dann die geänderte Werte in einen neuen Text IoT Hub zu aktualisieren.</span><span class="sxs-lookup"><span data-stu-id="283fa-112">The usual pattern to modify a property is to retrieve the IoT hub metadata and security metadata, and then combine them with the modified values in a new body to update the IoT hub.</span></span>
            </remarks>
        <exception cref="T:Microsoft.Azure.Management.IotHub.Models.ErrorDetailsException">
            <span data-ttu-id="283fa-113">Wird ausgelöst, wenn der Vorgang einen ungültigen Statuscode zurückgegeben hat.</span><span class="sxs-lookup"><span data-stu-id="283fa-113">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="283fa-114">Wird ausgelöst, wenn nicht die Antwort zu deserialisieren.</span><span class="sxs-lookup"><span data-stu-id="283fa-114">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="283fa-115">Wird ausgelöst, wenn ein erforderlicher Parameter null ist.</span><span class="sxs-lookup"><span data-stu-id="283fa-115">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="BeginDeleteWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;object&gt;&gt; BeginDeleteWithHttpMessagesAsync (string resourceGroupName, string resourceName, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;object&gt;&gt; BeginDeleteWithHttpMessagesAsync(string resourceGroupName, string resourceName, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.IotHub.IIotHubResourceOperations.BeginDeleteWithHttpMessagesAsync(System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member BeginDeleteWithHttpMessagesAsync : string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;obj&gt;&gt;" Usage="iIotHubResourceOperations.BeginDeleteWithHttpMessagesAsync (resourceGroupName, resourceName, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.IotHub</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;System.Object&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="resourceName" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="283fa-116">Der Name der Ressourcengruppe, die den IoT Hub enthält.</span><span class="sxs-lookup"><span data-stu-id="283fa-116">The name of the resource group that contains the IoT hub.</span></span>
            </param>
        <param name="resourceName">
            <span data-ttu-id="283fa-117">Der Name der IoT Hub.</span><span class="sxs-lookup"><span data-stu-id="283fa-117">The name of the IoT hub.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="283fa-118">Die Header, die hinzugefügt werden auf Anforderung.</span><span class="sxs-lookup"><span data-stu-id="283fa-118">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="283fa-119">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="283fa-119">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="283fa-120">Löschen Sie einen IoT Hub.</span><span class="sxs-lookup"><span data-stu-id="283fa-120">Delete an IoT hub.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="283fa-121">Löschen Sie einen IoT Hub.</span><span class="sxs-lookup"><span data-stu-id="283fa-121">Delete an IoT hub.</span></span>
            </remarks>
        <exception cref="T:Microsoft.Azure.Management.IotHub.Models.ErrorDetailsException">
            <span data-ttu-id="283fa-122">Wird ausgelöst, wenn der Vorgang einen ungültigen Statuscode zurückgegeben hat.</span><span class="sxs-lookup"><span data-stu-id="283fa-122">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="283fa-123">Wird ausgelöst, wenn nicht die Antwort zu deserialisieren.</span><span class="sxs-lookup"><span data-stu-id="283fa-123">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="283fa-124">Wird ausgelöst, wenn ein erforderlicher Parameter null ist.</span><span class="sxs-lookup"><span data-stu-id="283fa-124">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="CheckNameAvailabilityWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.IotHub.Models.IotHubNameAvailabilityInfo&gt;&gt; CheckNameAvailabilityWithHttpMessagesAsync (Microsoft.Azure.Management.IotHub.Models.OperationInputs operationInputs, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Management.IotHub.Models.IotHubNameAvailabilityInfo&gt;&gt; CheckNameAvailabilityWithHttpMessagesAsync(class Microsoft.Azure.Management.IotHub.Models.OperationInputs operationInputs, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.IotHub.IIotHubResourceOperations.CheckNameAvailabilityWithHttpMessagesAsync(Microsoft.Azure.Management.IotHub.Models.OperationInputs,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member CheckNameAvailabilityWithHttpMessagesAsync : Microsoft.Azure.Management.IotHub.Models.OperationInputs * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.IotHub.Models.IotHubNameAvailabilityInfo&gt;&gt;" Usage="iIotHubResourceOperations.CheckNameAvailabilityWithHttpMessagesAsync (operationInputs, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.IotHub</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.IotHub.Models.IotHubNameAvailabilityInfo&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operationInputs" Type="Microsoft.Azure.Management.IotHub.Models.OperationInputs" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operationInputs">
            <span data-ttu-id="283fa-125">Legen Sie den Namensparameter in der Struktur OperationInputs auf den Namen des IoT Hub zu überprüfen.</span><span class="sxs-lookup"><span data-stu-id="283fa-125">Set the name parameter in the OperationInputs structure to the name of the IoT hub to check.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="283fa-126">Die Header, die hinzugefügt werden auf Anforderung.</span><span class="sxs-lookup"><span data-stu-id="283fa-126">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="283fa-127">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="283fa-127">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="283fa-128">Überprüfen Sie, ob ein IoT Hub-Name verfügbar ist.</span><span class="sxs-lookup"><span data-stu-id="283fa-128">Check if an IoT hub name is available.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="283fa-129">Überprüfen Sie, ob ein IoT Hub-Name verfügbar ist.</span><span class="sxs-lookup"><span data-stu-id="283fa-129">Check if an IoT hub name is available.</span></span>
            </remarks>
        <exception cref="T:Microsoft.Azure.Management.IotHub.Models.ErrorDetailsException">
            <span data-ttu-id="283fa-130">Wird ausgelöst, wenn der Vorgang einen ungültigen Statuscode zurückgegeben hat.</span><span class="sxs-lookup"><span data-stu-id="283fa-130">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="283fa-131">Wird ausgelöst, wenn nicht die Antwort zu deserialisieren.</span><span class="sxs-lookup"><span data-stu-id="283fa-131">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="283fa-132">Wird ausgelöst, wenn ein erforderlicher Parameter null ist.</span><span class="sxs-lookup"><span data-stu-id="283fa-132">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="CreateEventHubConsumerGroupWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.IotHub.Models.EventHubConsumerGroupInfo&gt;&gt; CreateEventHubConsumerGroupWithHttpMessagesAsync (string resourceGroupName, string resourceName, string eventHubEndpointName, string name, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Management.IotHub.Models.EventHubConsumerGroupInfo&gt;&gt; CreateEventHubConsumerGroupWithHttpMessagesAsync(string resourceGroupName, string resourceName, string eventHubEndpointName, string name, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.IotHub.IIotHubResourceOperations.CreateEventHubConsumerGroupWithHttpMessagesAsync(System.String,System.String,System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member CreateEventHubConsumerGroupWithHttpMessagesAsync : string * string * string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.IotHub.Models.EventHubConsumerGroupInfo&gt;&gt;" Usage="iIotHubResourceOperations.CreateEventHubConsumerGroupWithHttpMessagesAsync (resourceGroupName, resourceName, eventHubEndpointName, name, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.IotHub</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.IotHub.Models.EventHubConsumerGroupInfo&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="resourceName" Type="System.String" />
        <Parameter Name="eventHubEndpointName" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="283fa-133">Der Name der Ressourcengruppe, die den IoT Hub enthält.</span><span class="sxs-lookup"><span data-stu-id="283fa-133">The name of the resource group that contains the IoT hub.</span></span>
            </param>
        <param name="resourceName">
            <span data-ttu-id="283fa-134">Der Name der IoT Hub.</span><span class="sxs-lookup"><span data-stu-id="283fa-134">The name of the IoT hub.</span></span>
            </param>
        <param name="eventHubEndpointName">
            <span data-ttu-id="283fa-135">Der Name des Endpunkts Event Hub-kompatiblen IoT Hub.</span><span class="sxs-lookup"><span data-stu-id="283fa-135">The name of the Event Hub-compatible endpoint in the IoT hub.</span></span>
            </param>
        <param name="name">
            <span data-ttu-id="283fa-136">Der Name der Gruppe "Consumer" hinzufügen.</span><span class="sxs-lookup"><span data-stu-id="283fa-136">The name of the consumer group to add.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="283fa-137">Die Header, die hinzugefügt werden auf Anforderung.</span><span class="sxs-lookup"><span data-stu-id="283fa-137">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="283fa-138">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="283fa-138">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="283fa-139">Hinzufügen einer consumergruppe an einen Event Hub-kompatiblen Endpunkt in einem IoT Hub.</span><span class="sxs-lookup"><span data-stu-id="283fa-139">Add a consumer group to an Event Hub-compatible endpoint in an IoT hub.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="283fa-140">Hinzufügen einer consumergruppe an einen Event Hub-kompatiblen Endpunkt in einem IoT Hub.</span><span class="sxs-lookup"><span data-stu-id="283fa-140">Add a consumer group to an Event Hub-compatible endpoint in an IoT hub.</span></span>
            </remarks>
        <exception cref="T:Microsoft.Azure.Management.IotHub.Models.ErrorDetailsException">
            <span data-ttu-id="283fa-141">Wird ausgelöst, wenn der Vorgang einen ungültigen Statuscode zurückgegeben hat.</span><span class="sxs-lookup"><span data-stu-id="283fa-141">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="283fa-142">Wird ausgelöst, wenn nicht die Antwort zu deserialisieren.</span><span class="sxs-lookup"><span data-stu-id="283fa-142">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="283fa-143">Wird ausgelöst, wenn ein erforderlicher Parameter null ist.</span><span class="sxs-lookup"><span data-stu-id="283fa-143">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="CreateOrUpdateWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.IotHub.Models.IotHubDescription&gt;&gt; CreateOrUpdateWithHttpMessagesAsync (string resourceGroupName, string resourceName, Microsoft.Azure.Management.IotHub.Models.IotHubDescription iotHubDescription, string ifMatch = null, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Management.IotHub.Models.IotHubDescription&gt;&gt; CreateOrUpdateWithHttpMessagesAsync(string resourceGroupName, string resourceName, class Microsoft.Azure.Management.IotHub.Models.IotHubDescription iotHubDescription, string ifMatch, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.IotHub.IIotHubResourceOperations.CreateOrUpdateWithHttpMessagesAsync(System.String,System.String,Microsoft.Azure.Management.IotHub.Models.IotHubDescription,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member CreateOrUpdateWithHttpMessagesAsync : string * string * Microsoft.Azure.Management.IotHub.Models.IotHubDescription * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.IotHub.Models.IotHubDescription&gt;&gt;" Usage="iIotHubResourceOperations.CreateOrUpdateWithHttpMessagesAsync (resourceGroupName, resourceName, iotHubDescription, ifMatch, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.IotHub</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.IotHub.Models.IotHubDescription&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="resourceName" Type="System.String" />
        <Parameter Name="iotHubDescription" Type="Microsoft.Azure.Management.IotHub.Models.IotHubDescription" />
        <Parameter Name="ifMatch" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="283fa-144">Der Name der Ressourcengruppe, die den IoT Hub enthält.</span><span class="sxs-lookup"><span data-stu-id="283fa-144">The name of the resource group that contains the IoT hub.</span></span>
            </param>
        <param name="resourceName">
            <span data-ttu-id="283fa-145">Der Name der IoT Hub.</span><span class="sxs-lookup"><span data-stu-id="283fa-145">The name of the IoT hub.</span></span>
            </param>
        <param name="iotHubDescription">
            <span data-ttu-id="283fa-146">Der IoT Hub-Metadaten und Sicherheitsmetadaten.</span><span class="sxs-lookup"><span data-stu-id="283fa-146">The IoT hub metadata and security metadata.</span></span>
            </param>
        <param name="ifMatch">
            <span data-ttu-id="283fa-147">ETag der IoT Hub.</span><span class="sxs-lookup"><span data-stu-id="283fa-147">ETag of the IoT Hub.</span></span> <span data-ttu-id="283fa-148">Geben Sie zum Erstellen einer neuen IoT Hub.</span><span class="sxs-lookup"><span data-stu-id="283fa-148">Do not specify for creating a brand new IoT Hub.</span></span> <span data-ttu-id="283fa-149">Zum Aktualisieren eines vorhandenen IoT Hub erforderlich.</span><span class="sxs-lookup"><span data-stu-id="283fa-149">Required to update an existing IoT Hub.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="283fa-150">Die Header, die hinzugefügt werden auf Anforderung.</span><span class="sxs-lookup"><span data-stu-id="283fa-150">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="283fa-151">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="283fa-151">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="283fa-152">Erstellen Sie oder aktualisieren Sie die Metadaten eines IoT Hubs.</span><span class="sxs-lookup"><span data-stu-id="283fa-152">Create or update the metadata of an IoT hub.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="283fa-153">Erstellen Sie oder aktualisieren Sie die Metadaten eines Iot Hubs.</span><span class="sxs-lookup"><span data-stu-id="283fa-153">Create or update the metadata of an Iot hub.</span></span> <span data-ttu-id="283fa-154">Zum Ändern einer Eigenschaft das übliche Muster ist die IoT Hub-Metadaten und Sicherheitsmetadaten abzurufen, und kombinieren sie Sie dann die geänderte Werte in einen neuen Text IoT Hub zu aktualisieren.</span><span class="sxs-lookup"><span data-stu-id="283fa-154">The usual pattern to modify a property is to retrieve the IoT hub metadata and security metadata, and then combine them with the modified values in a new body to update the IoT hub.</span></span>
            </remarks>
        <exception cref="T:Microsoft.Azure.Management.IotHub.Models.ErrorDetailsException">
            <span data-ttu-id="283fa-155">Wird ausgelöst, wenn der Vorgang einen ungültigen Statuscode zurückgegeben hat.</span><span class="sxs-lookup"><span data-stu-id="283fa-155">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="283fa-156">Wird ausgelöst, wenn nicht die Antwort zu deserialisieren.</span><span class="sxs-lookup"><span data-stu-id="283fa-156">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="283fa-157">Wird ausgelöst, wenn ein erforderlicher Parameter null ist.</span><span class="sxs-lookup"><span data-stu-id="283fa-157">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="DeleteEventHubConsumerGroupWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt; DeleteEventHubConsumerGroupWithHttpMessagesAsync (string resourceGroupName, string resourceName, string eventHubEndpointName, string name, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse&gt; DeleteEventHubConsumerGroupWithHttpMessagesAsync(string resourceGroupName, string resourceName, string eventHubEndpointName, string name, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.IotHub.IIotHubResourceOperations.DeleteEventHubConsumerGroupWithHttpMessagesAsync(System.String,System.String,System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member DeleteEventHubConsumerGroupWithHttpMessagesAsync : string * string * string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt;" Usage="iIotHubResourceOperations.DeleteEventHubConsumerGroupWithHttpMessagesAsync (resourceGroupName, resourceName, eventHubEndpointName, name, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.IotHub</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="resourceName" Type="System.String" />
        <Parameter Name="eventHubEndpointName" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="283fa-158">Der Name der Ressourcengruppe, die den IoT Hub enthält.</span><span class="sxs-lookup"><span data-stu-id="283fa-158">The name of the resource group that contains the IoT hub.</span></span>
            </param>
        <param name="resourceName">
            <span data-ttu-id="283fa-159">Der Name der IoT Hub.</span><span class="sxs-lookup"><span data-stu-id="283fa-159">The name of the IoT hub.</span></span>
            </param>
        <param name="eventHubEndpointName">
            <span data-ttu-id="283fa-160">Der Name des Endpunkts Event Hub-kompatiblen IoT Hub.</span><span class="sxs-lookup"><span data-stu-id="283fa-160">The name of the Event Hub-compatible endpoint in the IoT hub.</span></span>
            </param>
        <param name="name">
            <span data-ttu-id="283fa-161">Der Name des zu löschenden consumergruppe.</span><span class="sxs-lookup"><span data-stu-id="283fa-161">The name of the consumer group to delete.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="283fa-162">Die Header, die hinzugefügt werden auf Anforderung.</span><span class="sxs-lookup"><span data-stu-id="283fa-162">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="283fa-163">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="283fa-163">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="283fa-164">Löschen einer consumergruppe von einem Event Hub-kompatiblen Endpunkt in einem IoT Hub.</span><span class="sxs-lookup"><span data-stu-id="283fa-164">Delete a consumer group from an Event Hub-compatible endpoint in an IoT hub.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="283fa-165">Löschen einer consumergruppe von einem Event Hub-kompatiblen Endpunkt in einem IoT Hub.</span><span class="sxs-lookup"><span data-stu-id="283fa-165">Delete a consumer group from an Event Hub-compatible endpoint in an IoT hub.</span></span>
            </remarks>
        <exception cref="T:Microsoft.Azure.Management.IotHub.Models.ErrorDetailsException">
            <span data-ttu-id="283fa-166">Wird ausgelöst, wenn der Vorgang einen ungültigen Statuscode zurückgegeben hat.</span><span class="sxs-lookup"><span data-stu-id="283fa-166">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="283fa-167">Wird ausgelöst, wenn ein erforderlicher Parameter null ist.</span><span class="sxs-lookup"><span data-stu-id="283fa-167">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="DeleteWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;object&gt;&gt; DeleteWithHttpMessagesAsync (string resourceGroupName, string resourceName, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;object&gt;&gt; DeleteWithHttpMessagesAsync(string resourceGroupName, string resourceName, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.IotHub.IIotHubResourceOperations.DeleteWithHttpMessagesAsync(System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member DeleteWithHttpMessagesAsync : string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;obj&gt;&gt;" Usage="iIotHubResourceOperations.DeleteWithHttpMessagesAsync (resourceGroupName, resourceName, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.IotHub</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;System.Object&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="resourceName" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="283fa-168">Der Name der Ressourcengruppe, die den IoT Hub enthält.</span><span class="sxs-lookup"><span data-stu-id="283fa-168">The name of the resource group that contains the IoT hub.</span></span>
            </param>
        <param name="resourceName">
            <span data-ttu-id="283fa-169">Der Name der IoT Hub.</span><span class="sxs-lookup"><span data-stu-id="283fa-169">The name of the IoT hub.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="283fa-170">Die Header, die hinzugefügt werden auf Anforderung.</span><span class="sxs-lookup"><span data-stu-id="283fa-170">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="283fa-171">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="283fa-171">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="283fa-172">Löschen Sie einen IoT Hub.</span><span class="sxs-lookup"><span data-stu-id="283fa-172">Delete an IoT hub.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="283fa-173">Löschen Sie einen IoT Hub.</span><span class="sxs-lookup"><span data-stu-id="283fa-173">Delete an IoT hub.</span></span>
            </remarks>
        <exception cref="T:Microsoft.Azure.Management.IotHub.Models.ErrorDetailsException">
            <span data-ttu-id="283fa-174">Wird ausgelöst, wenn der Vorgang einen ungültigen Statuscode zurückgegeben hat.</span><span class="sxs-lookup"><span data-stu-id="283fa-174">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="283fa-175">Wird ausgelöst, wenn nicht die Antwort zu deserialisieren.</span><span class="sxs-lookup"><span data-stu-id="283fa-175">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="283fa-176">Wird ausgelöst, wenn ein erforderlicher Parameter null ist.</span><span class="sxs-lookup"><span data-stu-id="283fa-176">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="ExportDevicesWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.IotHub.Models.JobResponse&gt;&gt; ExportDevicesWithHttpMessagesAsync (string resourceGroupName, string resourceName, Microsoft.Azure.Management.IotHub.Models.ExportDevicesRequest exportDevicesParameters, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Management.IotHub.Models.JobResponse&gt;&gt; ExportDevicesWithHttpMessagesAsync(string resourceGroupName, string resourceName, class Microsoft.Azure.Management.IotHub.Models.ExportDevicesRequest exportDevicesParameters, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.IotHub.IIotHubResourceOperations.ExportDevicesWithHttpMessagesAsync(System.String,System.String,Microsoft.Azure.Management.IotHub.Models.ExportDevicesRequest,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ExportDevicesWithHttpMessagesAsync : string * string * Microsoft.Azure.Management.IotHub.Models.ExportDevicesRequest * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.IotHub.Models.JobResponse&gt;&gt;" Usage="iIotHubResourceOperations.ExportDevicesWithHttpMessagesAsync (resourceGroupName, resourceName, exportDevicesParameters, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.IotHub</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.IotHub.Models.JobResponse&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="resourceName" Type="System.String" />
        <Parameter Name="exportDevicesParameters" Type="Microsoft.Azure.Management.IotHub.Models.ExportDevicesRequest" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="283fa-177">Der Name der Ressourcengruppe, die den IoT Hub enthält.</span><span class="sxs-lookup"><span data-stu-id="283fa-177">The name of the resource group that contains the IoT hub.</span></span>
            </param>
        <param name="resourceName">
            <span data-ttu-id="283fa-178">Der Name der IoT Hub.</span><span class="sxs-lookup"><span data-stu-id="283fa-178">The name of the IoT hub.</span></span>
            </param>
        <param name="exportDevicesParameters">
            <span data-ttu-id="283fa-179">Die Parameter, mit die den Exportvorgang für Geräte angegeben.</span><span class="sxs-lookup"><span data-stu-id="283fa-179">The parameters that specify the export devices operation.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="283fa-180">Die Header, die hinzugefügt werden auf Anforderung.</span><span class="sxs-lookup"><span data-stu-id="283fa-180">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="283fa-181">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="283fa-181">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="283fa-182">Exportiert alle geräteidentitäten in der IoT Hub-Identity-Registrierung in einer Azure-Speicher-Blob-Container.</span><span class="sxs-lookup"><span data-stu-id="283fa-182">Exports all the device identities in the IoT hub identity registry to an Azure Storage blob container.</span></span> <span data-ttu-id="283fa-183">Weitere Informationen finden Sie unter: https://docs.microsoft.com/azure/iot-hub/iot-hub-devguide-identity-registry#import-and-export-device-identities.</span><span class="sxs-lookup"><span data-stu-id="283fa-183">For more information, see: https://docs.microsoft.com/azure/iot-hub/iot-hub-devguide-identity-registry#import-and-export-device-identities.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="283fa-184">Exportiert alle geräteidentitäten in der IoT Hub-Identity-Registrierung in einer Azure-Speicher-Blob-Container.</span><span class="sxs-lookup"><span data-stu-id="283fa-184">Exports all the device identities in the IoT hub identity registry to an Azure Storage blob container.</span></span> <span data-ttu-id="283fa-185">Weitere Informationen finden Sie unter: https://docs.microsoft.com/azure/iot-hub/iot-hub-devguide-identity-registry#import-and-export-device-identities.</span><span class="sxs-lookup"><span data-stu-id="283fa-185">For more information, see: https://docs.microsoft.com/azure/iot-hub/iot-hub-devguide-identity-registry#import-and-export-device-identities.</span></span>
            </remarks>
        <exception cref="T:Microsoft.Azure.Management.IotHub.Models.ErrorDetailsException">
            <span data-ttu-id="283fa-186">Wird ausgelöst, wenn der Vorgang einen ungültigen Statuscode zurückgegeben hat.</span><span class="sxs-lookup"><span data-stu-id="283fa-186">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="283fa-187">Wird ausgelöst, wenn nicht die Antwort zu deserialisieren.</span><span class="sxs-lookup"><span data-stu-id="283fa-187">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="283fa-188">Wird ausgelöst, wenn ein erforderlicher Parameter null ist.</span><span class="sxs-lookup"><span data-stu-id="283fa-188">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="GetEventHubConsumerGroupWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.IotHub.Models.EventHubConsumerGroupInfo&gt;&gt; GetEventHubConsumerGroupWithHttpMessagesAsync (string resourceGroupName, string resourceName, string eventHubEndpointName, string name, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Management.IotHub.Models.EventHubConsumerGroupInfo&gt;&gt; GetEventHubConsumerGroupWithHttpMessagesAsync(string resourceGroupName, string resourceName, string eventHubEndpointName, string name, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.IotHub.IIotHubResourceOperations.GetEventHubConsumerGroupWithHttpMessagesAsync(System.String,System.String,System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetEventHubConsumerGroupWithHttpMessagesAsync : string * string * string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.IotHub.Models.EventHubConsumerGroupInfo&gt;&gt;" Usage="iIotHubResourceOperations.GetEventHubConsumerGroupWithHttpMessagesAsync (resourceGroupName, resourceName, eventHubEndpointName, name, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.IotHub</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.IotHub.Models.EventHubConsumerGroupInfo&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="resourceName" Type="System.String" />
        <Parameter Name="eventHubEndpointName" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="283fa-189">Der Name der Ressourcengruppe, die den IoT Hub enthält.</span><span class="sxs-lookup"><span data-stu-id="283fa-189">The name of the resource group that contains the IoT hub.</span></span>
            </param>
        <param name="resourceName">
            <span data-ttu-id="283fa-190">Der Name der IoT Hub.</span><span class="sxs-lookup"><span data-stu-id="283fa-190">The name of the IoT hub.</span></span>
            </param>
        <param name="eventHubEndpointName">
            <span data-ttu-id="283fa-191">Der Name des Endpunkts Event Hub-kompatiblen IoT Hub.</span><span class="sxs-lookup"><span data-stu-id="283fa-191">The name of the Event Hub-compatible endpoint in the IoT hub.</span></span>
            </param>
        <param name="name">
            <span data-ttu-id="283fa-192">Der Name des abzurufenden consumergruppe.</span><span class="sxs-lookup"><span data-stu-id="283fa-192">The name of the consumer group to retrieve.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="283fa-193">Die Header, die hinzugefügt werden auf Anforderung.</span><span class="sxs-lookup"><span data-stu-id="283fa-193">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="283fa-194">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="283fa-194">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="283fa-195">Ruft eine consumergruppe vom Event Hub-kompatibles Gerät-zu-Cloud-Endpunkt für einen IoT Hub ab.</span><span class="sxs-lookup"><span data-stu-id="283fa-195">Get a consumer group from the Event Hub-compatible device-to-cloud endpoint for an IoT hub.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="283fa-196">Ruft eine consumergruppe vom Event Hub-kompatibles Gerät-zu-Cloud-Endpunkt für einen IoT Hub ab.</span><span class="sxs-lookup"><span data-stu-id="283fa-196">Get a consumer group from the Event Hub-compatible device-to-cloud endpoint for an IoT hub.</span></span>
            </remarks>
        <exception cref="T:Microsoft.Azure.Management.IotHub.Models.ErrorDetailsException">
            <span data-ttu-id="283fa-197">Wird ausgelöst, wenn der Vorgang einen ungültigen Statuscode zurückgegeben hat.</span><span class="sxs-lookup"><span data-stu-id="283fa-197">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="283fa-198">Wird ausgelöst, wenn nicht die Antwort zu deserialisieren.</span><span class="sxs-lookup"><span data-stu-id="283fa-198">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="283fa-199">Wird ausgelöst, wenn ein erforderlicher Parameter null ist.</span><span class="sxs-lookup"><span data-stu-id="283fa-199">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="GetJobWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.IotHub.Models.JobResponse&gt;&gt; GetJobWithHttpMessagesAsync (string resourceGroupName, string resourceName, string jobId, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Management.IotHub.Models.JobResponse&gt;&gt; GetJobWithHttpMessagesAsync(string resourceGroupName, string resourceName, string jobId, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.IotHub.IIotHubResourceOperations.GetJobWithHttpMessagesAsync(System.String,System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetJobWithHttpMessagesAsync : string * string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.IotHub.Models.JobResponse&gt;&gt;" Usage="iIotHubResourceOperations.GetJobWithHttpMessagesAsync (resourceGroupName, resourceName, jobId, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.IotHub</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.IotHub.Models.JobResponse&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="resourceName" Type="System.String" />
        <Parameter Name="jobId" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="283fa-200">Der Name der Ressourcengruppe, die den IoT Hub enthält.</span><span class="sxs-lookup"><span data-stu-id="283fa-200">The name of the resource group that contains the IoT hub.</span></span>
            </param>
        <param name="resourceName">
            <span data-ttu-id="283fa-201">Der Name der IoT Hub.</span><span class="sxs-lookup"><span data-stu-id="283fa-201">The name of the IoT hub.</span></span>
            </param>
        <param name="jobId">
            <span data-ttu-id="283fa-202">Der Auftragsbezeichner.</span><span class="sxs-lookup"><span data-stu-id="283fa-202">The job identifier.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="283fa-203">Die Header, die hinzugefügt werden auf Anforderung.</span><span class="sxs-lookup"><span data-stu-id="283fa-203">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="283fa-204">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="283fa-204">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="283fa-205">Abrufen von Details eines Auftrags von einem IoT Hub.</span><span class="sxs-lookup"><span data-stu-id="283fa-205">Get the details of a job from an IoT hub.</span></span> <span data-ttu-id="283fa-206">Weitere Informationen finden Sie unter: https://docs.microsoft.com/azure/iot-hub/iot-hub-devguide-identity-registry.</span><span class="sxs-lookup"><span data-stu-id="283fa-206">For more information, see: https://docs.microsoft.com/azure/iot-hub/iot-hub-devguide-identity-registry.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="283fa-207">Abrufen von Details eines Auftrags von einem IoT Hub.</span><span class="sxs-lookup"><span data-stu-id="283fa-207">Get the details of a job from an IoT hub.</span></span> <span data-ttu-id="283fa-208">Weitere Informationen finden Sie unter: https://docs.microsoft.com/azure/iot-hub/iot-hub-devguide-identity-registry.</span><span class="sxs-lookup"><span data-stu-id="283fa-208">For more information, see: https://docs.microsoft.com/azure/iot-hub/iot-hub-devguide-identity-registry.</span></span>
            </remarks>
        <exception cref="T:Microsoft.Azure.Management.IotHub.Models.ErrorDetailsException">
            <span data-ttu-id="283fa-209">Wird ausgelöst, wenn der Vorgang einen ungültigen Statuscode zurückgegeben hat.</span><span class="sxs-lookup"><span data-stu-id="283fa-209">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="283fa-210">Wird ausgelöst, wenn nicht die Antwort zu deserialisieren.</span><span class="sxs-lookup"><span data-stu-id="283fa-210">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="283fa-211">Wird ausgelöst, wenn ein erforderlicher Parameter null ist.</span><span class="sxs-lookup"><span data-stu-id="283fa-211">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="GetKeysForKeyNameWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.IotHub.Models.SharedAccessSignatureAuthorizationRule&gt;&gt; GetKeysForKeyNameWithHttpMessagesAsync (string resourceGroupName, string resourceName, string keyName, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Management.IotHub.Models.SharedAccessSignatureAuthorizationRule&gt;&gt; GetKeysForKeyNameWithHttpMessagesAsync(string resourceGroupName, string resourceName, string keyName, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.IotHub.IIotHubResourceOperations.GetKeysForKeyNameWithHttpMessagesAsync(System.String,System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetKeysForKeyNameWithHttpMessagesAsync : string * string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.IotHub.Models.SharedAccessSignatureAuthorizationRule&gt;&gt;" Usage="iIotHubResourceOperations.GetKeysForKeyNameWithHttpMessagesAsync (resourceGroupName, resourceName, keyName, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.IotHub</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.IotHub.Models.SharedAccessSignatureAuthorizationRule&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="resourceName" Type="System.String" />
        <Parameter Name="keyName" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="283fa-212">Der Name der Ressourcengruppe, die den IoT Hub enthält.</span><span class="sxs-lookup"><span data-stu-id="283fa-212">The name of the resource group that contains the IoT hub.</span></span>
            </param>
        <param name="resourceName">
            <span data-ttu-id="283fa-213">Der Name der IoT Hub.</span><span class="sxs-lookup"><span data-stu-id="283fa-213">The name of the IoT hub.</span></span>
            </param>
        <param name="keyName">
            <span data-ttu-id="283fa-214">Der Name der Richtlinie für freigegebenen Zugriff.</span><span class="sxs-lookup"><span data-stu-id="283fa-214">The name of the shared access policy.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="283fa-215">Die Header, die hinzugefügt werden auf Anforderung.</span><span class="sxs-lookup"><span data-stu-id="283fa-215">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="283fa-216">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="283fa-216">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="283fa-217">Abrufen einer SAS-Richtlinie nach Namen von einem IoT Hub.</span><span class="sxs-lookup"><span data-stu-id="283fa-217">Get a shared access policy by name from an IoT hub.</span></span> <span data-ttu-id="283fa-218">Weitere Informationen finden Sie unter: https://docs.microsoft.com/azure/iot-hub/iot-hub-devguide-security.</span><span class="sxs-lookup"><span data-stu-id="283fa-218">For more information, see: https://docs.microsoft.com/azure/iot-hub/iot-hub-devguide-security.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="283fa-219">Abrufen einer SAS-Richtlinie nach Namen von einem IoT Hub.</span><span class="sxs-lookup"><span data-stu-id="283fa-219">Get a shared access policy by name from an IoT hub.</span></span> <span data-ttu-id="283fa-220">Weitere Informationen finden Sie unter: https://docs.microsoft.com/azure/iot-hub/iot-hub-devguide-security.</span><span class="sxs-lookup"><span data-stu-id="283fa-220">For more information, see: https://docs.microsoft.com/azure/iot-hub/iot-hub-devguide-security.</span></span>
            </remarks>
        <exception cref="T:Microsoft.Azure.Management.IotHub.Models.ErrorDetailsException">
            <span data-ttu-id="283fa-221">Wird ausgelöst, wenn der Vorgang einen ungültigen Statuscode zurückgegeben hat.</span><span class="sxs-lookup"><span data-stu-id="283fa-221">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="283fa-222">Wird ausgelöst, wenn nicht die Antwort zu deserialisieren.</span><span class="sxs-lookup"><span data-stu-id="283fa-222">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="283fa-223">Wird ausgelöst, wenn ein erforderlicher Parameter null ist.</span><span class="sxs-lookup"><span data-stu-id="283fa-223">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="GetQuotaMetricsNextWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.IotHub.Models.IotHubQuotaMetricInfo&gt;&gt;&gt; GetQuotaMetricsNextWithHttpMessagesAsync (string nextPageLink, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.IotHub.Models.IotHubQuotaMetricInfo&gt;&gt;&gt; GetQuotaMetricsNextWithHttpMessagesAsync(string nextPageLink, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.IotHub.IIotHubResourceOperations.GetQuotaMetricsNextWithHttpMessagesAsync(System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetQuotaMetricsNextWithHttpMessagesAsync : string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.IotHub.Models.IotHubQuotaMetricInfo&gt;&gt;&gt;" Usage="iIotHubResourceOperations.GetQuotaMetricsNextWithHttpMessagesAsync (nextPageLink, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.IotHub</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.IotHub.Models.IotHubQuotaMetricInfo&gt;&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="nextPageLink">
            <span data-ttu-id="283fa-224">Die "NextLink" aus dem vorherigen erfolgreichen Aufruf List-Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="283fa-224">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="283fa-225">Die Header, die hinzugefügt werden auf Anforderung.</span><span class="sxs-lookup"><span data-stu-id="283fa-225">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="283fa-226">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="283fa-226">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="283fa-227">Ruft die Metriken Kontingent für einen IoT Hub ab.</span><span class="sxs-lookup"><span data-stu-id="283fa-227">Get the quota metrics for an IoT hub.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="283fa-228">Ruft die Metriken Kontingent für einen IoT Hub ab.</span><span class="sxs-lookup"><span data-stu-id="283fa-228">Get the quota metrics for an IoT hub.</span></span>
            </remarks>
        <exception cref="T:Microsoft.Azure.Management.IotHub.Models.ErrorDetailsException">
            <span data-ttu-id="283fa-229">Wird ausgelöst, wenn der Vorgang einen ungültigen Statuscode zurückgegeben hat.</span><span class="sxs-lookup"><span data-stu-id="283fa-229">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="283fa-230">Wird ausgelöst, wenn nicht die Antwort zu deserialisieren.</span><span class="sxs-lookup"><span data-stu-id="283fa-230">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="283fa-231">Wird ausgelöst, wenn ein erforderlicher Parameter null ist.</span><span class="sxs-lookup"><span data-stu-id="283fa-231">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="GetQuotaMetricsWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.IotHub.Models.IotHubQuotaMetricInfo&gt;&gt;&gt; GetQuotaMetricsWithHttpMessagesAsync (string resourceGroupName, string resourceName, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.IotHub.Models.IotHubQuotaMetricInfo&gt;&gt;&gt; GetQuotaMetricsWithHttpMessagesAsync(string resourceGroupName, string resourceName, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.IotHub.IIotHubResourceOperations.GetQuotaMetricsWithHttpMessagesAsync(System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetQuotaMetricsWithHttpMessagesAsync : string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.IotHub.Models.IotHubQuotaMetricInfo&gt;&gt;&gt;" Usage="iIotHubResourceOperations.GetQuotaMetricsWithHttpMessagesAsync (resourceGroupName, resourceName, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.IotHub</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.IotHub.Models.IotHubQuotaMetricInfo&gt;&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="resourceName" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="283fa-232">Der Name der Ressourcengruppe, die den IoT Hub enthält.</span><span class="sxs-lookup"><span data-stu-id="283fa-232">The name of the resource group that contains the IoT hub.</span></span>
            </param>
        <param name="resourceName">
            <span data-ttu-id="283fa-233">Der Name der IoT Hub.</span><span class="sxs-lookup"><span data-stu-id="283fa-233">The name of the IoT hub.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="283fa-234">Die Header, die hinzugefügt werden auf Anforderung.</span><span class="sxs-lookup"><span data-stu-id="283fa-234">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="283fa-235">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="283fa-235">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="283fa-236">Ruft die Metriken Kontingent für einen IoT Hub ab.</span><span class="sxs-lookup"><span data-stu-id="283fa-236">Get the quota metrics for an IoT hub.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="283fa-237">Ruft die Metriken Kontingent für einen IoT Hub ab.</span><span class="sxs-lookup"><span data-stu-id="283fa-237">Get the quota metrics for an IoT hub.</span></span>
            </remarks>
        <exception cref="T:Microsoft.Azure.Management.IotHub.Models.ErrorDetailsException">
            <span data-ttu-id="283fa-238">Wird ausgelöst, wenn der Vorgang einen ungültigen Statuscode zurückgegeben hat.</span><span class="sxs-lookup"><span data-stu-id="283fa-238">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="283fa-239">Wird ausgelöst, wenn nicht die Antwort zu deserialisieren.</span><span class="sxs-lookup"><span data-stu-id="283fa-239">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="283fa-240">Wird ausgelöst, wenn ein erforderlicher Parameter null ist.</span><span class="sxs-lookup"><span data-stu-id="283fa-240">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="GetStatsWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.IotHub.Models.RegistryStatistics&gt;&gt; GetStatsWithHttpMessagesAsync (string resourceGroupName, string resourceName, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Management.IotHub.Models.RegistryStatistics&gt;&gt; GetStatsWithHttpMessagesAsync(string resourceGroupName, string resourceName, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.IotHub.IIotHubResourceOperations.GetStatsWithHttpMessagesAsync(System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetStatsWithHttpMessagesAsync : string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.IotHub.Models.RegistryStatistics&gt;&gt;" Usage="iIotHubResourceOperations.GetStatsWithHttpMessagesAsync (resourceGroupName, resourceName, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.IotHub</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.IotHub.Models.RegistryStatistics&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="resourceName" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="283fa-241">Der Name der Ressourcengruppe, die den IoT Hub enthält.</span><span class="sxs-lookup"><span data-stu-id="283fa-241">The name of the resource group that contains the IoT hub.</span></span>
            </param>
        <param name="resourceName">
            <span data-ttu-id="283fa-242">Der Name der IoT Hub.</span><span class="sxs-lookup"><span data-stu-id="283fa-242">The name of the IoT hub.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="283fa-243">Die Header, die hinzugefügt werden auf Anforderung.</span><span class="sxs-lookup"><span data-stu-id="283fa-243">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="283fa-244">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="283fa-244">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="283fa-245">Die Statistik von einem IoT Hub abrufen.</span><span class="sxs-lookup"><span data-stu-id="283fa-245">Get the statistics from an IoT hub.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="283fa-246">Die Statistik von einem IoT Hub abrufen.</span><span class="sxs-lookup"><span data-stu-id="283fa-246">Get the statistics from an IoT hub.</span></span>
            </remarks>
        <exception cref="T:Microsoft.Azure.Management.IotHub.Models.ErrorDetailsException">
            <span data-ttu-id="283fa-247">Wird ausgelöst, wenn der Vorgang einen ungültigen Statuscode zurückgegeben hat.</span><span class="sxs-lookup"><span data-stu-id="283fa-247">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="283fa-248">Wird ausgelöst, wenn nicht die Antwort zu deserialisieren.</span><span class="sxs-lookup"><span data-stu-id="283fa-248">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="283fa-249">Wird ausgelöst, wenn ein erforderlicher Parameter null ist.</span><span class="sxs-lookup"><span data-stu-id="283fa-249">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="GetValidSkusNextWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.IotHub.Models.IotHubSkuDescription&gt;&gt;&gt; GetValidSkusNextWithHttpMessagesAsync (string nextPageLink, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.IotHub.Models.IotHubSkuDescription&gt;&gt;&gt; GetValidSkusNextWithHttpMessagesAsync(string nextPageLink, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.IotHub.IIotHubResourceOperations.GetValidSkusNextWithHttpMessagesAsync(System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetValidSkusNextWithHttpMessagesAsync : string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.IotHub.Models.IotHubSkuDescription&gt;&gt;&gt;" Usage="iIotHubResourceOperations.GetValidSkusNextWithHttpMessagesAsync (nextPageLink, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.IotHub</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.IotHub.Models.IotHubSkuDescription&gt;&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="nextPageLink">
            <span data-ttu-id="283fa-250">Die "NextLink" aus dem vorherigen erfolgreichen Aufruf List-Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="283fa-250">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="283fa-251">Die Header, die hinzugefügt werden auf Anforderung.</span><span class="sxs-lookup"><span data-stu-id="283fa-251">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="283fa-252">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="283fa-252">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="283fa-253">Ruft die Liste der gültigen SKUs für einen IoT Hub ab.</span><span class="sxs-lookup"><span data-stu-id="283fa-253">Get the list of valid SKUs for an IoT hub.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="283fa-254">Ruft die Liste der gültigen SKUs für einen IoT Hub ab.</span><span class="sxs-lookup"><span data-stu-id="283fa-254">Get the list of valid SKUs for an IoT hub.</span></span>
            </remarks>
        <exception cref="T:Microsoft.Azure.Management.IotHub.Models.ErrorDetailsException">
            <span data-ttu-id="283fa-255">Wird ausgelöst, wenn der Vorgang einen ungültigen Statuscode zurückgegeben hat.</span><span class="sxs-lookup"><span data-stu-id="283fa-255">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="283fa-256">Wird ausgelöst, wenn nicht die Antwort zu deserialisieren.</span><span class="sxs-lookup"><span data-stu-id="283fa-256">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="283fa-257">Wird ausgelöst, wenn ein erforderlicher Parameter null ist.</span><span class="sxs-lookup"><span data-stu-id="283fa-257">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="GetValidSkusWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.IotHub.Models.IotHubSkuDescription&gt;&gt;&gt; GetValidSkusWithHttpMessagesAsync (string resourceGroupName, string resourceName, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.IotHub.Models.IotHubSkuDescription&gt;&gt;&gt; GetValidSkusWithHttpMessagesAsync(string resourceGroupName, string resourceName, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.IotHub.IIotHubResourceOperations.GetValidSkusWithHttpMessagesAsync(System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetValidSkusWithHttpMessagesAsync : string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.IotHub.Models.IotHubSkuDescription&gt;&gt;&gt;" Usage="iIotHubResourceOperations.GetValidSkusWithHttpMessagesAsync (resourceGroupName, resourceName, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.IotHub</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.IotHub.Models.IotHubSkuDescription&gt;&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="resourceName" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="283fa-258">Der Name der Ressourcengruppe, die den IoT Hub enthält.</span><span class="sxs-lookup"><span data-stu-id="283fa-258">The name of the resource group that contains the IoT hub.</span></span>
            </param>
        <param name="resourceName">
            <span data-ttu-id="283fa-259">Der Name der IoT Hub.</span><span class="sxs-lookup"><span data-stu-id="283fa-259">The name of the IoT hub.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="283fa-260">Die Header, die hinzugefügt werden auf Anforderung.</span><span class="sxs-lookup"><span data-stu-id="283fa-260">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="283fa-261">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="283fa-261">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="283fa-262">Ruft die Liste der gültigen SKUs für einen IoT Hub ab.</span><span class="sxs-lookup"><span data-stu-id="283fa-262">Get the list of valid SKUs for an IoT hub.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="283fa-263">Ruft die Liste der gültigen SKUs für einen IoT Hub ab.</span><span class="sxs-lookup"><span data-stu-id="283fa-263">Get the list of valid SKUs for an IoT hub.</span></span>
            </remarks>
        <exception cref="T:Microsoft.Azure.Management.IotHub.Models.ErrorDetailsException">
            <span data-ttu-id="283fa-264">Wird ausgelöst, wenn der Vorgang einen ungültigen Statuscode zurückgegeben hat.</span><span class="sxs-lookup"><span data-stu-id="283fa-264">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="283fa-265">Wird ausgelöst, wenn nicht die Antwort zu deserialisieren.</span><span class="sxs-lookup"><span data-stu-id="283fa-265">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="283fa-266">Wird ausgelöst, wenn ein erforderlicher Parameter null ist.</span><span class="sxs-lookup"><span data-stu-id="283fa-266">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="GetWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.IotHub.Models.IotHubDescription&gt;&gt; GetWithHttpMessagesAsync (string resourceGroupName, string resourceName, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Management.IotHub.Models.IotHubDescription&gt;&gt; GetWithHttpMessagesAsync(string resourceGroupName, string resourceName, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.IotHub.IIotHubResourceOperations.GetWithHttpMessagesAsync(System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetWithHttpMessagesAsync : string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.IotHub.Models.IotHubDescription&gt;&gt;" Usage="iIotHubResourceOperations.GetWithHttpMessagesAsync (resourceGroupName, resourceName, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.IotHub</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.IotHub.Models.IotHubDescription&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="resourceName" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="283fa-267">Der Name der Ressourcengruppe, die den IoT Hub enthält.</span><span class="sxs-lookup"><span data-stu-id="283fa-267">The name of the resource group that contains the IoT hub.</span></span>
            </param>
        <param name="resourceName">
            <span data-ttu-id="283fa-268">Der Name der IoT Hub.</span><span class="sxs-lookup"><span data-stu-id="283fa-268">The name of the IoT hub.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="283fa-269">Die Header, die hinzugefügt werden auf Anforderung.</span><span class="sxs-lookup"><span data-stu-id="283fa-269">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="283fa-270">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="283fa-270">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="283fa-271">Abrufen der zugehörigen nicht sicherheitsrelevantes Metadaten eines IoT Hubs.</span><span class="sxs-lookup"><span data-stu-id="283fa-271">Get the non-security related metadata of an IoT hub.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="283fa-272">Abrufen der zugehörigen nicht sicherheitsrelevantes Metadaten eines IoT Hubs.</span><span class="sxs-lookup"><span data-stu-id="283fa-272">Get the non-security related metadata of an IoT hub.</span></span>
            </remarks>
        <exception cref="T:Microsoft.Azure.Management.IotHub.Models.ErrorDetailsException">
            <span data-ttu-id="283fa-273">Wird ausgelöst, wenn der Vorgang einen ungültigen Statuscode zurückgegeben hat.</span><span class="sxs-lookup"><span data-stu-id="283fa-273">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="283fa-274">Wird ausgelöst, wenn nicht die Antwort zu deserialisieren.</span><span class="sxs-lookup"><span data-stu-id="283fa-274">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="283fa-275">Wird ausgelöst, wenn ein erforderlicher Parameter null ist.</span><span class="sxs-lookup"><span data-stu-id="283fa-275">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="ImportDevicesWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.IotHub.Models.JobResponse&gt;&gt; ImportDevicesWithHttpMessagesAsync (string resourceGroupName, string resourceName, Microsoft.Azure.Management.IotHub.Models.ImportDevicesRequest importDevicesParameters, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Management.IotHub.Models.JobResponse&gt;&gt; ImportDevicesWithHttpMessagesAsync(string resourceGroupName, string resourceName, class Microsoft.Azure.Management.IotHub.Models.ImportDevicesRequest importDevicesParameters, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.IotHub.IIotHubResourceOperations.ImportDevicesWithHttpMessagesAsync(System.String,System.String,Microsoft.Azure.Management.IotHub.Models.ImportDevicesRequest,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ImportDevicesWithHttpMessagesAsync : string * string * Microsoft.Azure.Management.IotHub.Models.ImportDevicesRequest * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.IotHub.Models.JobResponse&gt;&gt;" Usage="iIotHubResourceOperations.ImportDevicesWithHttpMessagesAsync (resourceGroupName, resourceName, importDevicesParameters, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.IotHub</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.IotHub.Models.JobResponse&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="resourceName" Type="System.String" />
        <Parameter Name="importDevicesParameters" Type="Microsoft.Azure.Management.IotHub.Models.ImportDevicesRequest" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="283fa-276">Der Name der Ressourcengruppe, die den IoT Hub enthält.</span><span class="sxs-lookup"><span data-stu-id="283fa-276">The name of the resource group that contains the IoT hub.</span></span>
            </param>
        <param name="resourceName">
            <span data-ttu-id="283fa-277">Der Name der IoT Hub.</span><span class="sxs-lookup"><span data-stu-id="283fa-277">The name of the IoT hub.</span></span>
            </param>
        <param name="importDevicesParameters">
            <span data-ttu-id="283fa-278">Die Parameter, die den Importvorgang für die Geräte angeben.</span><span class="sxs-lookup"><span data-stu-id="283fa-278">The parameters that specify the import devices operation.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="283fa-279">Die Header, die hinzugefügt werden auf Anforderung.</span><span class="sxs-lookup"><span data-stu-id="283fa-279">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="283fa-280">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="283fa-280">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="283fa-281">Importieren, aktualisieren oder Löschen von geräteidentitäten in der IoT Hub-Identity-Registrierung aus einem Blob.</span><span class="sxs-lookup"><span data-stu-id="283fa-281">Import, update, or delete device identities in the IoT hub identity registry from a blob.</span></span> <span data-ttu-id="283fa-282">Weitere Informationen finden Sie unter: https://docs.microsoft.com/azure/iot-hub/iot-hub-devguide-identity-registry#import-and-export-device-identities.</span><span class="sxs-lookup"><span data-stu-id="283fa-282">For more information, see: https://docs.microsoft.com/azure/iot-hub/iot-hub-devguide-identity-registry#import-and-export-device-identities.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="283fa-283">Importieren, aktualisieren oder Löschen von geräteidentitäten in der IoT Hub-Identity-Registrierung aus einem Blob.</span><span class="sxs-lookup"><span data-stu-id="283fa-283">Import, update, or delete device identities in the IoT hub identity registry from a blob.</span></span> <span data-ttu-id="283fa-284">Weitere Informationen finden Sie unter: https://docs.microsoft.com/azure/iot-hub/iot-hub-devguide-identity-registry#import-and-export-device-identities.</span><span class="sxs-lookup"><span data-stu-id="283fa-284">For more information, see: https://docs.microsoft.com/azure/iot-hub/iot-hub-devguide-identity-registry#import-and-export-device-identities.</span></span>
            </remarks>
        <exception cref="T:Microsoft.Azure.Management.IotHub.Models.ErrorDetailsException">
            <span data-ttu-id="283fa-285">Wird ausgelöst, wenn der Vorgang einen ungültigen Statuscode zurückgegeben hat.</span><span class="sxs-lookup"><span data-stu-id="283fa-285">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="283fa-286">Wird ausgelöst, wenn nicht die Antwort zu deserialisieren.</span><span class="sxs-lookup"><span data-stu-id="283fa-286">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="283fa-287">Wird ausgelöst, wenn ein erforderlicher Parameter null ist.</span><span class="sxs-lookup"><span data-stu-id="283fa-287">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="ListByResourceGroupNextWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.IotHub.Models.IotHubDescription&gt;&gt;&gt; ListByResourceGroupNextWithHttpMessagesAsync (string nextPageLink, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.IotHub.Models.IotHubDescription&gt;&gt;&gt; ListByResourceGroupNextWithHttpMessagesAsync(string nextPageLink, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.IotHub.IIotHubResourceOperations.ListByResourceGroupNextWithHttpMessagesAsync(System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListByResourceGroupNextWithHttpMessagesAsync : string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.IotHub.Models.IotHubDescription&gt;&gt;&gt;" Usage="iIotHubResourceOperations.ListByResourceGroupNextWithHttpMessagesAsync (nextPageLink, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.IotHub</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.IotHub.Models.IotHubDescription&gt;&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="nextPageLink">
            <span data-ttu-id="283fa-288">Die "NextLink" aus dem vorherigen erfolgreichen Aufruf List-Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="283fa-288">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="283fa-289">Die Header, die hinzugefügt werden auf Anforderung.</span><span class="sxs-lookup"><span data-stu-id="283fa-289">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="283fa-290">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="283fa-290">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="283fa-291">Ruft alle IoT Hubs in einer Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="283fa-291">Get all the IoT hubs in a resource group.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="283fa-292">Ruft alle IoT Hubs in einer Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="283fa-292">Get all the IoT hubs in a resource group.</span></span>
            </remarks>
        <exception cref="T:Microsoft.Azure.Management.IotHub.Models.ErrorDetailsException">
            <span data-ttu-id="283fa-293">Wird ausgelöst, wenn der Vorgang einen ungültigen Statuscode zurückgegeben hat.</span><span class="sxs-lookup"><span data-stu-id="283fa-293">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="283fa-294">Wird ausgelöst, wenn nicht die Antwort zu deserialisieren.</span><span class="sxs-lookup"><span data-stu-id="283fa-294">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="283fa-295">Wird ausgelöst, wenn ein erforderlicher Parameter null ist.</span><span class="sxs-lookup"><span data-stu-id="283fa-295">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="ListByResourceGroupWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.IotHub.Models.IotHubDescription&gt;&gt;&gt; ListByResourceGroupWithHttpMessagesAsync (string resourceGroupName, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.IotHub.Models.IotHubDescription&gt;&gt;&gt; ListByResourceGroupWithHttpMessagesAsync(string resourceGroupName, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.IotHub.IIotHubResourceOperations.ListByResourceGroupWithHttpMessagesAsync(System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListByResourceGroupWithHttpMessagesAsync : string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.IotHub.Models.IotHubDescription&gt;&gt;&gt;" Usage="iIotHubResourceOperations.ListByResourceGroupWithHttpMessagesAsync (resourceGroupName, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.IotHub</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.IotHub.Models.IotHubDescription&gt;&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="283fa-296">Der Name der Ressourcengruppe, die den IoT Hub enthält.</span><span class="sxs-lookup"><span data-stu-id="283fa-296">The name of the resource group that contains the IoT hub.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="283fa-297">Die Header, die hinzugefügt werden auf Anforderung.</span><span class="sxs-lookup"><span data-stu-id="283fa-297">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="283fa-298">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="283fa-298">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="283fa-299">Ruft alle IoT Hubs in einer Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="283fa-299">Get all the IoT hubs in a resource group.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="283fa-300">Ruft alle IoT Hubs in einer Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="283fa-300">Get all the IoT hubs in a resource group.</span></span>
            </remarks>
        <exception cref="T:Microsoft.Azure.Management.IotHub.Models.ErrorDetailsException">
            <span data-ttu-id="283fa-301">Wird ausgelöst, wenn der Vorgang einen ungültigen Statuscode zurückgegeben hat.</span><span class="sxs-lookup"><span data-stu-id="283fa-301">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="283fa-302">Wird ausgelöst, wenn nicht die Antwort zu deserialisieren.</span><span class="sxs-lookup"><span data-stu-id="283fa-302">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="283fa-303">Wird ausgelöst, wenn ein erforderlicher Parameter null ist.</span><span class="sxs-lookup"><span data-stu-id="283fa-303">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="ListBySubscriptionNextWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.IotHub.Models.IotHubDescription&gt;&gt;&gt; ListBySubscriptionNextWithHttpMessagesAsync (string nextPageLink, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.IotHub.Models.IotHubDescription&gt;&gt;&gt; ListBySubscriptionNextWithHttpMessagesAsync(string nextPageLink, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.IotHub.IIotHubResourceOperations.ListBySubscriptionNextWithHttpMessagesAsync(System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListBySubscriptionNextWithHttpMessagesAsync : string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.IotHub.Models.IotHubDescription&gt;&gt;&gt;" Usage="iIotHubResourceOperations.ListBySubscriptionNextWithHttpMessagesAsync (nextPageLink, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.IotHub</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.IotHub.Models.IotHubDescription&gt;&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="nextPageLink">
            <span data-ttu-id="283fa-304">Die "NextLink" aus dem vorherigen erfolgreichen Aufruf List-Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="283fa-304">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="283fa-305">Die Header, die hinzugefügt werden auf Anforderung.</span><span class="sxs-lookup"><span data-stu-id="283fa-305">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="283fa-306">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="283fa-306">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="283fa-307">Ruft alle IoT Hubs in einem Abonnement an.</span><span class="sxs-lookup"><span data-stu-id="283fa-307">Get all the IoT hubs in a subscription.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="283fa-308">Ruft alle IoT Hubs in einem Abonnement an.</span><span class="sxs-lookup"><span data-stu-id="283fa-308">Get all the IoT hubs in a subscription.</span></span>
            </remarks>
        <exception cref="T:Microsoft.Azure.Management.IotHub.Models.ErrorDetailsException">
            <span data-ttu-id="283fa-309">Wird ausgelöst, wenn der Vorgang einen ungültigen Statuscode zurückgegeben hat.</span><span class="sxs-lookup"><span data-stu-id="283fa-309">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="283fa-310">Wird ausgelöst, wenn nicht die Antwort zu deserialisieren.</span><span class="sxs-lookup"><span data-stu-id="283fa-310">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="283fa-311">Wird ausgelöst, wenn ein erforderlicher Parameter null ist.</span><span class="sxs-lookup"><span data-stu-id="283fa-311">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="ListBySubscriptionWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.IotHub.Models.IotHubDescription&gt;&gt;&gt; ListBySubscriptionWithHttpMessagesAsync (System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.IotHub.Models.IotHubDescription&gt;&gt;&gt; ListBySubscriptionWithHttpMessagesAsync(class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.IotHub.IIotHubResourceOperations.ListBySubscriptionWithHttpMessagesAsync(System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListBySubscriptionWithHttpMessagesAsync : System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.IotHub.Models.IotHubDescription&gt;&gt;&gt;" Usage="iIotHubResourceOperations.ListBySubscriptionWithHttpMessagesAsync (customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.IotHub</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.IotHub.Models.IotHubDescription&gt;&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="customHeaders">
            <span data-ttu-id="283fa-312">Die Header, die hinzugefügt werden auf Anforderung.</span><span class="sxs-lookup"><span data-stu-id="283fa-312">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="283fa-313">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="283fa-313">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="283fa-314">Ruft alle IoT Hubs in einem Abonnement an.</span><span class="sxs-lookup"><span data-stu-id="283fa-314">Get all the IoT hubs in a subscription.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="283fa-315">Ruft alle IoT Hubs in einem Abonnement an.</span><span class="sxs-lookup"><span data-stu-id="283fa-315">Get all the IoT hubs in a subscription.</span></span>
            </remarks>
        <exception cref="T:Microsoft.Azure.Management.IotHub.Models.ErrorDetailsException">
            <span data-ttu-id="283fa-316">Wird ausgelöst, wenn der Vorgang einen ungültigen Statuscode zurückgegeben hat.</span><span class="sxs-lookup"><span data-stu-id="283fa-316">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="283fa-317">Wird ausgelöst, wenn nicht die Antwort zu deserialisieren.</span><span class="sxs-lookup"><span data-stu-id="283fa-317">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="283fa-318">Wird ausgelöst, wenn ein erforderlicher Parameter null ist.</span><span class="sxs-lookup"><span data-stu-id="283fa-318">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="ListEventHubConsumerGroupsNextWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;string&gt;&gt;&gt; ListEventHubConsumerGroupsNextWithHttpMessagesAsync (string nextPageLink, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;string&gt;&gt;&gt; ListEventHubConsumerGroupsNextWithHttpMessagesAsync(string nextPageLink, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.IotHub.IIotHubResourceOperations.ListEventHubConsumerGroupsNextWithHttpMessagesAsync(System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListEventHubConsumerGroupsNextWithHttpMessagesAsync : string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;string&gt;&gt;&gt;" Usage="iIotHubResourceOperations.ListEventHubConsumerGroupsNextWithHttpMessagesAsync (nextPageLink, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.IotHub</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;System.String&gt;&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="nextPageLink">
            <span data-ttu-id="283fa-319">Die "NextLink" aus dem vorherigen erfolgreichen Aufruf List-Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="283fa-319">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="283fa-320">Die Header, die hinzugefügt werden auf Anforderung.</span><span class="sxs-lookup"><span data-stu-id="283fa-320">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="283fa-321">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="283fa-321">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="283fa-322">Abrufen einer Liste der consumergruppen im Event Hub-kompatibles Gerät-zu-Cloud-Endpunkt in einem IoT Hub.</span><span class="sxs-lookup"><span data-stu-id="283fa-322">Get a list of the consumer groups in the Event Hub-compatible device-to-cloud endpoint in an IoT hub.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="283fa-323">Abrufen einer Liste der consumergruppen im Event Hub-kompatibles Gerät-zu-Cloud-Endpunkt in einem IoT Hub.</span><span class="sxs-lookup"><span data-stu-id="283fa-323">Get a list of the consumer groups in the Event Hub-compatible device-to-cloud endpoint in an IoT hub.</span></span>
            </remarks>
        <exception cref="T:Microsoft.Azure.Management.IotHub.Models.ErrorDetailsException">
            <span data-ttu-id="283fa-324">Wird ausgelöst, wenn der Vorgang einen ungültigen Statuscode zurückgegeben hat.</span><span class="sxs-lookup"><span data-stu-id="283fa-324">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="283fa-325">Wird ausgelöst, wenn nicht die Antwort zu deserialisieren.</span><span class="sxs-lookup"><span data-stu-id="283fa-325">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="283fa-326">Wird ausgelöst, wenn ein erforderlicher Parameter null ist.</span><span class="sxs-lookup"><span data-stu-id="283fa-326">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="ListEventHubConsumerGroupsWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;string&gt;&gt;&gt; ListEventHubConsumerGroupsWithHttpMessagesAsync (string resourceGroupName, string resourceName, string eventHubEndpointName, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;string&gt;&gt;&gt; ListEventHubConsumerGroupsWithHttpMessagesAsync(string resourceGroupName, string resourceName, string eventHubEndpointName, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.IotHub.IIotHubResourceOperations.ListEventHubConsumerGroupsWithHttpMessagesAsync(System.String,System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListEventHubConsumerGroupsWithHttpMessagesAsync : string * string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;string&gt;&gt;&gt;" Usage="iIotHubResourceOperations.ListEventHubConsumerGroupsWithHttpMessagesAsync (resourceGroupName, resourceName, eventHubEndpointName, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.IotHub</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;System.String&gt;&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="resourceName" Type="System.String" />
        <Parameter Name="eventHubEndpointName" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="283fa-327">Der Name der Ressourcengruppe, die den IoT Hub enthält.</span><span class="sxs-lookup"><span data-stu-id="283fa-327">The name of the resource group that contains the IoT hub.</span></span>
            </param>
        <param name="resourceName">
            <span data-ttu-id="283fa-328">Der Name der IoT Hub.</span><span class="sxs-lookup"><span data-stu-id="283fa-328">The name of the IoT hub.</span></span>
            </param>
        <param name="eventHubEndpointName">
            <span data-ttu-id="283fa-329">Der Name des Endpunkts Event Hub-kompatibel.</span><span class="sxs-lookup"><span data-stu-id="283fa-329">The name of the Event Hub-compatible endpoint.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="283fa-330">Die Header, die hinzugefügt werden auf Anforderung.</span><span class="sxs-lookup"><span data-stu-id="283fa-330">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="283fa-331">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="283fa-331">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="283fa-332">Abrufen einer Liste der consumergruppen im Event Hub-kompatibles Gerät-zu-Cloud-Endpunkt in einem IoT Hub.</span><span class="sxs-lookup"><span data-stu-id="283fa-332">Get a list of the consumer groups in the Event Hub-compatible device-to-cloud endpoint in an IoT hub.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="283fa-333">Abrufen einer Liste der consumergruppen im Event Hub-kompatibles Gerät-zu-Cloud-Endpunkt in einem IoT Hub.</span><span class="sxs-lookup"><span data-stu-id="283fa-333">Get a list of the consumer groups in the Event Hub-compatible device-to-cloud endpoint in an IoT hub.</span></span>
            </remarks>
        <exception cref="T:Microsoft.Azure.Management.IotHub.Models.ErrorDetailsException">
            <span data-ttu-id="283fa-334">Wird ausgelöst, wenn der Vorgang einen ungültigen Statuscode zurückgegeben hat.</span><span class="sxs-lookup"><span data-stu-id="283fa-334">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="283fa-335">Wird ausgelöst, wenn nicht die Antwort zu deserialisieren.</span><span class="sxs-lookup"><span data-stu-id="283fa-335">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="283fa-336">Wird ausgelöst, wenn ein erforderlicher Parameter null ist.</span><span class="sxs-lookup"><span data-stu-id="283fa-336">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="ListJobsNextWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.IotHub.Models.JobResponse&gt;&gt;&gt; ListJobsNextWithHttpMessagesAsync (string nextPageLink, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.IotHub.Models.JobResponse&gt;&gt;&gt; ListJobsNextWithHttpMessagesAsync(string nextPageLink, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.IotHub.IIotHubResourceOperations.ListJobsNextWithHttpMessagesAsync(System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListJobsNextWithHttpMessagesAsync : string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.IotHub.Models.JobResponse&gt;&gt;&gt;" Usage="iIotHubResourceOperations.ListJobsNextWithHttpMessagesAsync (nextPageLink, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.IotHub</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.IotHub.Models.JobResponse&gt;&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="nextPageLink">
            <span data-ttu-id="283fa-337">Die "NextLink" aus dem vorherigen erfolgreichen Aufruf List-Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="283fa-337">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="283fa-338">Die Header, die hinzugefügt werden auf Anforderung.</span><span class="sxs-lookup"><span data-stu-id="283fa-338">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="283fa-339">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="283fa-339">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="283fa-340">Abrufen einer Liste aller Aufträge in einem IoT Hub.</span><span class="sxs-lookup"><span data-stu-id="283fa-340">Get a list of all the jobs in an IoT hub.</span></span> <span data-ttu-id="283fa-341">Weitere Informationen finden Sie unter: https://docs.microsoft.com/azure/iot-hub/iot-hub-devguide-identity-registry.</span><span class="sxs-lookup"><span data-stu-id="283fa-341">For more information, see: https://docs.microsoft.com/azure/iot-hub/iot-hub-devguide-identity-registry.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="283fa-342">Abrufen einer Liste aller Aufträge in einem IoT Hub.</span><span class="sxs-lookup"><span data-stu-id="283fa-342">Get a list of all the jobs in an IoT hub.</span></span> <span data-ttu-id="283fa-343">Weitere Informationen finden Sie unter: https://docs.microsoft.com/azure/iot-hub/iot-hub-devguide-identity-registry.</span><span class="sxs-lookup"><span data-stu-id="283fa-343">For more information, see: https://docs.microsoft.com/azure/iot-hub/iot-hub-devguide-identity-registry.</span></span>
            </remarks>
        <exception cref="T:Microsoft.Azure.Management.IotHub.Models.ErrorDetailsException">
            <span data-ttu-id="283fa-344">Wird ausgelöst, wenn der Vorgang einen ungültigen Statuscode zurückgegeben hat.</span><span class="sxs-lookup"><span data-stu-id="283fa-344">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="283fa-345">Wird ausgelöst, wenn nicht die Antwort zu deserialisieren.</span><span class="sxs-lookup"><span data-stu-id="283fa-345">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="283fa-346">Wird ausgelöst, wenn ein erforderlicher Parameter null ist.</span><span class="sxs-lookup"><span data-stu-id="283fa-346">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="ListJobsWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.IotHub.Models.JobResponse&gt;&gt;&gt; ListJobsWithHttpMessagesAsync (string resourceGroupName, string resourceName, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.IotHub.Models.JobResponse&gt;&gt;&gt; ListJobsWithHttpMessagesAsync(string resourceGroupName, string resourceName, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.IotHub.IIotHubResourceOperations.ListJobsWithHttpMessagesAsync(System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListJobsWithHttpMessagesAsync : string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.IotHub.Models.JobResponse&gt;&gt;&gt;" Usage="iIotHubResourceOperations.ListJobsWithHttpMessagesAsync (resourceGroupName, resourceName, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.IotHub</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.IotHub.Models.JobResponse&gt;&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="resourceName" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="283fa-347">Der Name der Ressourcengruppe, die den IoT Hub enthält.</span><span class="sxs-lookup"><span data-stu-id="283fa-347">The name of the resource group that contains the IoT hub.</span></span>
            </param>
        <param name="resourceName">
            <span data-ttu-id="283fa-348">Der Name der IoT Hub.</span><span class="sxs-lookup"><span data-stu-id="283fa-348">The name of the IoT hub.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="283fa-349">Die Header, die hinzugefügt werden auf Anforderung.</span><span class="sxs-lookup"><span data-stu-id="283fa-349">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="283fa-350">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="283fa-350">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="283fa-351">Abrufen einer Liste aller Aufträge in einem IoT Hub.</span><span class="sxs-lookup"><span data-stu-id="283fa-351">Get a list of all the jobs in an IoT hub.</span></span> <span data-ttu-id="283fa-352">Weitere Informationen finden Sie unter: https://docs.microsoft.com/azure/iot-hub/iot-hub-devguide-identity-registry.</span><span class="sxs-lookup"><span data-stu-id="283fa-352">For more information, see: https://docs.microsoft.com/azure/iot-hub/iot-hub-devguide-identity-registry.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="283fa-353">Abrufen einer Liste aller Aufträge in einem IoT Hub.</span><span class="sxs-lookup"><span data-stu-id="283fa-353">Get a list of all the jobs in an IoT hub.</span></span> <span data-ttu-id="283fa-354">Weitere Informationen finden Sie unter: https://docs.microsoft.com/azure/iot-hub/iot-hub-devguide-identity-registry.</span><span class="sxs-lookup"><span data-stu-id="283fa-354">For more information, see: https://docs.microsoft.com/azure/iot-hub/iot-hub-devguide-identity-registry.</span></span>
            </remarks>
        <exception cref="T:Microsoft.Azure.Management.IotHub.Models.ErrorDetailsException">
            <span data-ttu-id="283fa-355">Wird ausgelöst, wenn der Vorgang einen ungültigen Statuscode zurückgegeben hat.</span><span class="sxs-lookup"><span data-stu-id="283fa-355">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="283fa-356">Wird ausgelöst, wenn nicht die Antwort zu deserialisieren.</span><span class="sxs-lookup"><span data-stu-id="283fa-356">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="283fa-357">Wird ausgelöst, wenn ein erforderlicher Parameter null ist.</span><span class="sxs-lookup"><span data-stu-id="283fa-357">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="ListKeysNextWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.IotHub.Models.SharedAccessSignatureAuthorizationRule&gt;&gt;&gt; ListKeysNextWithHttpMessagesAsync (string nextPageLink, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.IotHub.Models.SharedAccessSignatureAuthorizationRule&gt;&gt;&gt; ListKeysNextWithHttpMessagesAsync(string nextPageLink, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.IotHub.IIotHubResourceOperations.ListKeysNextWithHttpMessagesAsync(System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListKeysNextWithHttpMessagesAsync : string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.IotHub.Models.SharedAccessSignatureAuthorizationRule&gt;&gt;&gt;" Usage="iIotHubResourceOperations.ListKeysNextWithHttpMessagesAsync (nextPageLink, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.IotHub</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.IotHub.Models.SharedAccessSignatureAuthorizationRule&gt;&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="nextPageLink">
            <span data-ttu-id="283fa-358">Die "NextLink" aus dem vorherigen erfolgreichen Aufruf List-Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="283fa-358">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="283fa-359">Die Header, die hinzugefügt werden auf Anforderung.</span><span class="sxs-lookup"><span data-stu-id="283fa-359">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="283fa-360">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="283fa-360">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="283fa-361">Ruft die Sicherheits-Metadaten für einen IoT Hub ab.</span><span class="sxs-lookup"><span data-stu-id="283fa-361">Get the security metadata for an IoT hub.</span></span> <span data-ttu-id="283fa-362">Weitere Informationen finden Sie unter: https://docs.microsoft.com/azure/iot-hub/iot-hub-devguide-security.</span><span class="sxs-lookup"><span data-stu-id="283fa-362">For more information, see: https://docs.microsoft.com/azure/iot-hub/iot-hub-devguide-security.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="283fa-363">Ruft die Sicherheits-Metadaten für einen IoT Hub ab.</span><span class="sxs-lookup"><span data-stu-id="283fa-363">Get the security metadata for an IoT hub.</span></span> <span data-ttu-id="283fa-364">Weitere Informationen finden Sie unter: https://docs.microsoft.com/azure/iot-hub/iot-hub-devguide-security.</span><span class="sxs-lookup"><span data-stu-id="283fa-364">For more information, see: https://docs.microsoft.com/azure/iot-hub/iot-hub-devguide-security.</span></span>
            </remarks>
        <exception cref="T:Microsoft.Azure.Management.IotHub.Models.ErrorDetailsException">
            <span data-ttu-id="283fa-365">Wird ausgelöst, wenn der Vorgang einen ungültigen Statuscode zurückgegeben hat.</span><span class="sxs-lookup"><span data-stu-id="283fa-365">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="283fa-366">Wird ausgelöst, wenn nicht die Antwort zu deserialisieren.</span><span class="sxs-lookup"><span data-stu-id="283fa-366">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="283fa-367">Wird ausgelöst, wenn ein erforderlicher Parameter null ist.</span><span class="sxs-lookup"><span data-stu-id="283fa-367">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="ListKeysWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.IotHub.Models.SharedAccessSignatureAuthorizationRule&gt;&gt;&gt; ListKeysWithHttpMessagesAsync (string resourceGroupName, string resourceName, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.IotHub.Models.SharedAccessSignatureAuthorizationRule&gt;&gt;&gt; ListKeysWithHttpMessagesAsync(string resourceGroupName, string resourceName, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.IotHub.IIotHubResourceOperations.ListKeysWithHttpMessagesAsync(System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListKeysWithHttpMessagesAsync : string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.IotHub.Models.SharedAccessSignatureAuthorizationRule&gt;&gt;&gt;" Usage="iIotHubResourceOperations.ListKeysWithHttpMessagesAsync (resourceGroupName, resourceName, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.IotHub</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.IotHub.Models.SharedAccessSignatureAuthorizationRule&gt;&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="resourceName" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="283fa-368">Der Name der Ressourcengruppe, die den IoT Hub enthält.</span><span class="sxs-lookup"><span data-stu-id="283fa-368">The name of the resource group that contains the IoT hub.</span></span>
            </param>
        <param name="resourceName">
            <span data-ttu-id="283fa-369">Der Name der IoT Hub.</span><span class="sxs-lookup"><span data-stu-id="283fa-369">The name of the IoT hub.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="283fa-370">Die Header, die hinzugefügt werden auf Anforderung.</span><span class="sxs-lookup"><span data-stu-id="283fa-370">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="283fa-371">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="283fa-371">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="283fa-372">Ruft die Sicherheits-Metadaten für einen IoT Hub ab.</span><span class="sxs-lookup"><span data-stu-id="283fa-372">Get the security metadata for an IoT hub.</span></span> <span data-ttu-id="283fa-373">Weitere Informationen finden Sie unter: https://docs.microsoft.com/azure/iot-hub/iot-hub-devguide-security.</span><span class="sxs-lookup"><span data-stu-id="283fa-373">For more information, see: https://docs.microsoft.com/azure/iot-hub/iot-hub-devguide-security.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="283fa-374">Ruft die Sicherheits-Metadaten für einen IoT Hub ab.</span><span class="sxs-lookup"><span data-stu-id="283fa-374">Get the security metadata for an IoT hub.</span></span> <span data-ttu-id="283fa-375">Weitere Informationen finden Sie unter: https://docs.microsoft.com/azure/iot-hub/iot-hub-devguide-security.</span><span class="sxs-lookup"><span data-stu-id="283fa-375">For more information, see: https://docs.microsoft.com/azure/iot-hub/iot-hub-devguide-security.</span></span>
            </remarks>
        <exception cref="T:Microsoft.Azure.Management.IotHub.Models.ErrorDetailsException">
            <span data-ttu-id="283fa-376">Wird ausgelöst, wenn der Vorgang einen ungültigen Statuscode zurückgegeben hat.</span><span class="sxs-lookup"><span data-stu-id="283fa-376">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="283fa-377">Wird ausgelöst, wenn nicht die Antwort zu deserialisieren.</span><span class="sxs-lookup"><span data-stu-id="283fa-377">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="283fa-378">Wird ausgelöst, wenn ein erforderlicher Parameter null ist.</span><span class="sxs-lookup"><span data-stu-id="283fa-378">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>