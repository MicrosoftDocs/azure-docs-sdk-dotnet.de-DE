<Type Name="IInputsOperations" FullName="Microsoft.Azure.Management.StreamAnalytics.IInputsOperations">
  <TypeSignature Language="C#" Value="public interface IInputsOperations" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IInputsOperations" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.StreamAnalytics.IInputsOperations" />
  <TypeSignature Language="VB.NET" Value="Public Interface IInputsOperations" />
  <TypeSignature Language="F#" Value="type IInputsOperations = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
    <AssemblyVersion>2.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="76a2d-101">InputsOperations-Vorgänge.</span><span class="sxs-lookup"><span data-stu-id="76a2d-101">InputsOperations operations.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="BeginTestWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.StreamAnalytics.Models.ResourceTestStatus&gt;&gt; BeginTestWithHttpMessagesAsync (string resourceGroupName, string jobName, string inputName, Microsoft.Azure.Management.StreamAnalytics.Models.Input input = null, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Management.StreamAnalytics.Models.ResourceTestStatus&gt;&gt; BeginTestWithHttpMessagesAsync(string resourceGroupName, string jobName, string inputName, class Microsoft.Azure.Management.StreamAnalytics.Models.Input input, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StreamAnalytics.IInputsOperations.BeginTestWithHttpMessagesAsync(System.String,System.String,System.String,Microsoft.Azure.Management.StreamAnalytics.Models.Input,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member BeginTestWithHttpMessagesAsync : string * string * string * Microsoft.Azure.Management.StreamAnalytics.Models.Input * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.StreamAnalytics.Models.ResourceTestStatus&gt;&gt;" Usage="iInputsOperations.BeginTestWithHttpMessagesAsync (resourceGroupName, jobName, inputName, input, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.StreamAnalytics.Models.ResourceTestStatus&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="jobName" Type="System.String" />
        <Parameter Name="inputName" Type="System.String" />
        <Parameter Name="input" Type="Microsoft.Azure.Management.StreamAnalytics.Models.Input" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="76a2d-102">Der Name der Ressourcengruppe, die die Ressource enthält.</span><span class="sxs-lookup"><span data-stu-id="76a2d-102">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="76a2d-103">Dieser Wert kann über die Azure-Ressourcen-Manager-API oder das Portal abgerufen werden.</span><span class="sxs-lookup"><span data-stu-id="76a2d-103">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="jobName">
            <span data-ttu-id="76a2d-104">Der Name des streamingauftrags.</span><span class="sxs-lookup"><span data-stu-id="76a2d-104">The name of the streaming job.</span></span>
            </param>
        <param name="inputName">
            <span data-ttu-id="76a2d-105">Der Name der Eingabe.</span><span class="sxs-lookup"><span data-stu-id="76a2d-105">The name of the input.</span></span>
            </param>
        <param name="input">
            <span data-ttu-id="76a2d-106">Wenn die angegebene Eingabe nicht bereits vorhanden ist, muss dieser Parameter die vollständige eingabedefinition getestet werden soll enthalten.</span><span class="sxs-lookup"><span data-stu-id="76a2d-106">If the input specified does not already exist, this parameter must contain the full input definition intended to be tested.</span></span> <span data-ttu-id="76a2d-107">Wenn die Eingabe, die bereits vorhanden ist, dieser Parameter kann null So testen Sie die vorhandene Eingabe unverändert gelassen werden oder wenn angegeben, überschreibt die angegebenen Eigenschaften der entsprechenden Eigenschaften in die vorhandene Eingabe (genau wie ein PATCH-Vorgang) und das resultierende Eingabe wird getestet werden.</span><span class="sxs-lookup"><span data-stu-id="76a2d-107">If the input specified already exists, this parameter can be left null to test the existing input as is or if specified, the properties specified will overwrite the corresponding properties in the existing input (exactly like a PATCH operation) and the resulting input will be tested.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="76a2d-108">Die Header, die hinzugefügt werden auf Anforderung.</span><span class="sxs-lookup"><span data-stu-id="76a2d-108">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="76a2d-109">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="76a2d-109">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="76a2d-110">Testet, ob eine Eingabe-Datenquelle erreichbar und von Azure Stream Analytics-Dienst verwendet werden kann.</span><span class="sxs-lookup"><span data-stu-id="76a2d-110">Tests whether an input’s datasource is reachable and usable by the Azure Stream Analytics service.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="76a2d-111">Wird ausgelöst, wenn der Vorgang einen ungültigen Statuscode zurückgegeben hat.</span><span class="sxs-lookup"><span data-stu-id="76a2d-111">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="76a2d-112">Wird ausgelöst, wenn nicht die Antwort zu deserialisieren.</span><span class="sxs-lookup"><span data-stu-id="76a2d-112">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="76a2d-113">Wird ausgelöst, wenn ein erforderlicher Parameter null ist.</span><span class="sxs-lookup"><span data-stu-id="76a2d-113">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="CreateOrReplaceWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.StreamAnalytics.Models.Input,Microsoft.Azure.Management.StreamAnalytics.Models.InputsCreateOrReplaceHeaders&gt;&gt; CreateOrReplaceWithHttpMessagesAsync (Microsoft.Azure.Management.StreamAnalytics.Models.Input input, string resourceGroupName, string jobName, string inputName, string ifMatch = null, string ifNoneMatch = null, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`2&lt;class Microsoft.Azure.Management.StreamAnalytics.Models.Input, class Microsoft.Azure.Management.StreamAnalytics.Models.InputsCreateOrReplaceHeaders&gt;&gt; CreateOrReplaceWithHttpMessagesAsync(class Microsoft.Azure.Management.StreamAnalytics.Models.Input input, string resourceGroupName, string jobName, string inputName, string ifMatch, string ifNoneMatch, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StreamAnalytics.IInputsOperations.CreateOrReplaceWithHttpMessagesAsync(Microsoft.Azure.Management.StreamAnalytics.Models.Input,System.String,System.String,System.String,System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member CreateOrReplaceWithHttpMessagesAsync : Microsoft.Azure.Management.StreamAnalytics.Models.Input * string * string * string * string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.StreamAnalytics.Models.Input, Microsoft.Azure.Management.StreamAnalytics.Models.InputsCreateOrReplaceHeaders&gt;&gt;" Usage="iInputsOperations.CreateOrReplaceWithHttpMessagesAsync (input, resourceGroupName, jobName, inputName, ifMatch, ifNoneMatch, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.StreamAnalytics.Models.Input,Microsoft.Azure.Management.StreamAnalytics.Models.InputsCreateOrReplaceHeaders&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="input" Type="Microsoft.Azure.Management.StreamAnalytics.Models.Input" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="jobName" Type="System.String" />
        <Parameter Name="inputName" Type="System.String" />
        <Parameter Name="ifMatch" Type="System.String" />
        <Parameter Name="ifNoneMatch" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="input">
            <span data-ttu-id="76a2d-114">Die Definition der Eingabe, die eine neue Eingabe erstellen oder Ersetzen von vorhandenen Knoten unter der streamingauftrag verwendet werden.</span><span class="sxs-lookup"><span data-stu-id="76a2d-114">The definition of the input that will be used to create a new input or replace the existing one under the streaming job.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="76a2d-115">Der Name der Ressourcengruppe, die die Ressource enthält.</span><span class="sxs-lookup"><span data-stu-id="76a2d-115">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="76a2d-116">Dieser Wert kann über die Azure-Ressourcen-Manager-API oder das Portal abgerufen werden.</span><span class="sxs-lookup"><span data-stu-id="76a2d-116">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="jobName">
            <span data-ttu-id="76a2d-117">Der Name des streamingauftrags.</span><span class="sxs-lookup"><span data-stu-id="76a2d-117">The name of the streaming job.</span></span>
            </param>
        <param name="inputName">
            <span data-ttu-id="76a2d-118">Der Name der Eingabe.</span><span class="sxs-lookup"><span data-stu-id="76a2d-118">The name of the input.</span></span>
            </param>
        <param name="ifMatch">
            <span data-ttu-id="76a2d-119">Das ETag der Eingabe.</span><span class="sxs-lookup"><span data-stu-id="76a2d-119">The ETag of the input.</span></span> <span data-ttu-id="76a2d-120">Lassen Sie diesen Wert, um die aktuelle Eingabe immer überschrieben.</span><span class="sxs-lookup"><span data-stu-id="76a2d-120">Omit this value to always overwrite the current input.</span></span> <span data-ttu-id="76a2d-121">Geben Sie die letzten gesehen ETag-Wert um versehentlich Overwritting gleichzeitige Änderungen zu verhindern.</span><span class="sxs-lookup"><span data-stu-id="76a2d-121">Specify the last-seen ETag value to prevent accidentally overwritting concurrent changes.</span></span>
            </param>
        <param name="ifNoneMatch">
            <span data-ttu-id="76a2d-122">Legen Sie auf "\*" um eine neue Eingabe erstellt werden, sondern um zu verhindern, aktualisieren eine vorhandene Eingabe zu ermöglichen.</span><span class="sxs-lookup"><span data-stu-id="76a2d-122">Set to '\*' to allow a new input to be created, but to prevent updating an existing input.</span></span> <span data-ttu-id="76a2d-123">Andere Werte führt 412 Antwort vor Bedingung fehlerhaft ist.</span><span class="sxs-lookup"><span data-stu-id="76a2d-123">Other values will result in a 412 Pre-condition Failed response.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="76a2d-124">Die Header, die hinzugefügt werden auf Anforderung.</span><span class="sxs-lookup"><span data-stu-id="76a2d-124">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="76a2d-125">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="76a2d-125">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="76a2d-126">Erstellt eine Eingabe, oder eine bereits vorhandene Eingabe unter einem vorhandenen streaming Auftrag ersetzt.</span><span class="sxs-lookup"><span data-stu-id="76a2d-126">Creates an input or replaces an already existing input under an existing streaming job.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="76a2d-127">Wird ausgelöst, wenn der Vorgang einen ungültigen Statuscode zurückgegeben hat.</span><span class="sxs-lookup"><span data-stu-id="76a2d-127">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="76a2d-128">Wird ausgelöst, wenn nicht die Antwort zu deserialisieren.</span><span class="sxs-lookup"><span data-stu-id="76a2d-128">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="76a2d-129">Wird ausgelöst, wenn ein erforderlicher Parameter null ist.</span><span class="sxs-lookup"><span data-stu-id="76a2d-129">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="DeleteWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt; DeleteWithHttpMessagesAsync (string resourceGroupName, string jobName, string inputName, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse&gt; DeleteWithHttpMessagesAsync(string resourceGroupName, string jobName, string inputName, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StreamAnalytics.IInputsOperations.DeleteWithHttpMessagesAsync(System.String,System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member DeleteWithHttpMessagesAsync : string * string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt;" Usage="iInputsOperations.DeleteWithHttpMessagesAsync (resourceGroupName, jobName, inputName, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="jobName" Type="System.String" />
        <Parameter Name="inputName" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="76a2d-130">Der Name der Ressourcengruppe, die die Ressource enthält.</span><span class="sxs-lookup"><span data-stu-id="76a2d-130">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="76a2d-131">Dieser Wert kann über die Azure-Ressourcen-Manager-API oder das Portal abgerufen werden.</span><span class="sxs-lookup"><span data-stu-id="76a2d-131">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="jobName">
            <span data-ttu-id="76a2d-132">Der Name des streamingauftrags.</span><span class="sxs-lookup"><span data-stu-id="76a2d-132">The name of the streaming job.</span></span>
            </param>
        <param name="inputName">
            <span data-ttu-id="76a2d-133">Der Name der Eingabe.</span><span class="sxs-lookup"><span data-stu-id="76a2d-133">The name of the input.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="76a2d-134">Die Header, die hinzugefügt werden auf Anforderung.</span><span class="sxs-lookup"><span data-stu-id="76a2d-134">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="76a2d-135">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="76a2d-135">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="76a2d-136">Löscht eine Eingabe aus der streaming-Auftrags an.</span><span class="sxs-lookup"><span data-stu-id="76a2d-136">Deletes an input from the streaming job.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="76a2d-137">Wird ausgelöst, wenn der Vorgang einen ungültigen Statuscode zurückgegeben hat.</span><span class="sxs-lookup"><span data-stu-id="76a2d-137">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="76a2d-138">Wird ausgelöst, wenn ein erforderlicher Parameter null ist.</span><span class="sxs-lookup"><span data-stu-id="76a2d-138">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="GetWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.StreamAnalytics.Models.Input,Microsoft.Azure.Management.StreamAnalytics.Models.InputsGetHeaders&gt;&gt; GetWithHttpMessagesAsync (string resourceGroupName, string jobName, string inputName, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`2&lt;class Microsoft.Azure.Management.StreamAnalytics.Models.Input, class Microsoft.Azure.Management.StreamAnalytics.Models.InputsGetHeaders&gt;&gt; GetWithHttpMessagesAsync(string resourceGroupName, string jobName, string inputName, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StreamAnalytics.IInputsOperations.GetWithHttpMessagesAsync(System.String,System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetWithHttpMessagesAsync : string * string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.StreamAnalytics.Models.Input, Microsoft.Azure.Management.StreamAnalytics.Models.InputsGetHeaders&gt;&gt;" Usage="iInputsOperations.GetWithHttpMessagesAsync (resourceGroupName, jobName, inputName, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.StreamAnalytics.Models.Input,Microsoft.Azure.Management.StreamAnalytics.Models.InputsGetHeaders&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="jobName" Type="System.String" />
        <Parameter Name="inputName" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="76a2d-139">Der Name der Ressourcengruppe, die die Ressource enthält.</span><span class="sxs-lookup"><span data-stu-id="76a2d-139">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="76a2d-140">Dieser Wert kann über die Azure-Ressourcen-Manager-API oder das Portal abgerufen werden.</span><span class="sxs-lookup"><span data-stu-id="76a2d-140">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="jobName">
            <span data-ttu-id="76a2d-141">Der Name des streamingauftrags.</span><span class="sxs-lookup"><span data-stu-id="76a2d-141">The name of the streaming job.</span></span>
            </param>
        <param name="inputName">
            <span data-ttu-id="76a2d-142">Der Name der Eingabe.</span><span class="sxs-lookup"><span data-stu-id="76a2d-142">The name of the input.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="76a2d-143">Die Header, die hinzugefügt werden auf Anforderung.</span><span class="sxs-lookup"><span data-stu-id="76a2d-143">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="76a2d-144">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="76a2d-144">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="76a2d-145">Ruft Details über die angegebene Eingabe ab.</span><span class="sxs-lookup"><span data-stu-id="76a2d-145">Gets details about the specified input.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="76a2d-146">Wird ausgelöst, wenn der Vorgang einen ungültigen Statuscode zurückgegeben hat.</span><span class="sxs-lookup"><span data-stu-id="76a2d-146">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="76a2d-147">Wird ausgelöst, wenn nicht die Antwort zu deserialisieren.</span><span class="sxs-lookup"><span data-stu-id="76a2d-147">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="76a2d-148">Wird ausgelöst, wenn ein erforderlicher Parameter null ist.</span><span class="sxs-lookup"><span data-stu-id="76a2d-148">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="ListByStreamingJobNextWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.StreamAnalytics.Models.Input&gt;&gt;&gt; ListByStreamingJobNextWithHttpMessagesAsync (string nextPageLink, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.StreamAnalytics.Models.Input&gt;&gt;&gt; ListByStreamingJobNextWithHttpMessagesAsync(string nextPageLink, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StreamAnalytics.IInputsOperations.ListByStreamingJobNextWithHttpMessagesAsync(System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListByStreamingJobNextWithHttpMessagesAsync : string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.StreamAnalytics.Models.Input&gt;&gt;&gt;" Usage="iInputsOperations.ListByStreamingJobNextWithHttpMessagesAsync (nextPageLink, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.StreamAnalytics.Models.Input&gt;&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="nextPageLink">
            <span data-ttu-id="76a2d-149">Die "NextLink" aus dem vorherigen erfolgreichen Aufruf List-Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="76a2d-149">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="76a2d-150">Die Header, die hinzugefügt werden auf Anforderung.</span><span class="sxs-lookup"><span data-stu-id="76a2d-150">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="76a2d-151">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="76a2d-151">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="76a2d-152">Zeigt eine Liste aller Eingaben unter dem angegebenen streaming-Auftrags.</span><span class="sxs-lookup"><span data-stu-id="76a2d-152">Lists all of the inputs under the specified streaming job.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="76a2d-153">Wird ausgelöst, wenn der Vorgang einen ungültigen Statuscode zurückgegeben hat.</span><span class="sxs-lookup"><span data-stu-id="76a2d-153">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="76a2d-154">Wird ausgelöst, wenn nicht die Antwort zu deserialisieren.</span><span class="sxs-lookup"><span data-stu-id="76a2d-154">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="76a2d-155">Wird ausgelöst, wenn ein erforderlicher Parameter null ist.</span><span class="sxs-lookup"><span data-stu-id="76a2d-155">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="ListByStreamingJobWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.StreamAnalytics.Models.Input&gt;&gt;&gt; ListByStreamingJobWithHttpMessagesAsync (string resourceGroupName, string jobName, string select = null, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.StreamAnalytics.Models.Input&gt;&gt;&gt; ListByStreamingJobWithHttpMessagesAsync(string resourceGroupName, string jobName, string select, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StreamAnalytics.IInputsOperations.ListByStreamingJobWithHttpMessagesAsync(System.String,System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListByStreamingJobWithHttpMessagesAsync : string * string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.StreamAnalytics.Models.Input&gt;&gt;&gt;" Usage="iInputsOperations.ListByStreamingJobWithHttpMessagesAsync (resourceGroupName, jobName, select, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.StreamAnalytics.Models.Input&gt;&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="jobName" Type="System.String" />
        <Parameter Name="select" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="76a2d-156">Der Name der Ressourcengruppe, die die Ressource enthält.</span><span class="sxs-lookup"><span data-stu-id="76a2d-156">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="76a2d-157">Dieser Wert kann über die Azure-Ressourcen-Manager-API oder das Portal abgerufen werden.</span><span class="sxs-lookup"><span data-stu-id="76a2d-157">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="jobName">
            <span data-ttu-id="76a2d-158">Der Name des streamingauftrags.</span><span class="sxs-lookup"><span data-stu-id="76a2d-158">The name of the streaming job.</span></span>
            </param>
        <param name="select">
            <span data-ttu-id="76a2d-159">Der $select OData-Abfrageparameter.</span><span class="sxs-lookup"><span data-stu-id="76a2d-159">The $select OData query parameter.</span></span> <span data-ttu-id="76a2d-160">Dies ist eine durch Trennzeichen getrennte Liste der strukturellen Eigenschaften in die Antwort eingeschlossen werden sollen oder "*" alle Eigenschaften eingeschlossen. Standardmäßig werden alle Eigenschaften außer Diagnose zurückgegeben. Derzeit sind nur Werte "*" als gültiger Wert.</span><span class="sxs-lookup"><span data-stu-id="76a2d-160">This is a comma-separated list of structural properties to include in the response, or “*” to include all properties. By default, all properties are returned except diagnostics. Currently only accepts '*' as a valid value.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="76a2d-161">Die Header, die hinzugefügt werden auf Anforderung.</span><span class="sxs-lookup"><span data-stu-id="76a2d-161">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="76a2d-162">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="76a2d-162">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="76a2d-163">Zeigt eine Liste aller Eingaben unter dem angegebenen streaming-Auftrags.</span><span class="sxs-lookup"><span data-stu-id="76a2d-163">Lists all of the inputs under the specified streaming job.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="76a2d-164">Wird ausgelöst, wenn der Vorgang einen ungültigen Statuscode zurückgegeben hat.</span><span class="sxs-lookup"><span data-stu-id="76a2d-164">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="76a2d-165">Wird ausgelöst, wenn nicht die Antwort zu deserialisieren.</span><span class="sxs-lookup"><span data-stu-id="76a2d-165">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="76a2d-166">Wird ausgelöst, wenn ein erforderlicher Parameter null ist.</span><span class="sxs-lookup"><span data-stu-id="76a2d-166">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="TestWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.StreamAnalytics.Models.ResourceTestStatus&gt;&gt; TestWithHttpMessagesAsync (string resourceGroupName, string jobName, string inputName, Microsoft.Azure.Management.StreamAnalytics.Models.Input input = null, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Management.StreamAnalytics.Models.ResourceTestStatus&gt;&gt; TestWithHttpMessagesAsync(string resourceGroupName, string jobName, string inputName, class Microsoft.Azure.Management.StreamAnalytics.Models.Input input, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StreamAnalytics.IInputsOperations.TestWithHttpMessagesAsync(System.String,System.String,System.String,Microsoft.Azure.Management.StreamAnalytics.Models.Input,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member TestWithHttpMessagesAsync : string * string * string * Microsoft.Azure.Management.StreamAnalytics.Models.Input * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.StreamAnalytics.Models.ResourceTestStatus&gt;&gt;" Usage="iInputsOperations.TestWithHttpMessagesAsync (resourceGroupName, jobName, inputName, input, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.StreamAnalytics.Models.ResourceTestStatus&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="jobName" Type="System.String" />
        <Parameter Name="inputName" Type="System.String" />
        <Parameter Name="input" Type="Microsoft.Azure.Management.StreamAnalytics.Models.Input" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="76a2d-167">Der Name der Ressourcengruppe, die die Ressource enthält.</span><span class="sxs-lookup"><span data-stu-id="76a2d-167">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="76a2d-168">Dieser Wert kann über die Azure-Ressourcen-Manager-API oder das Portal abgerufen werden.</span><span class="sxs-lookup"><span data-stu-id="76a2d-168">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="jobName">
            <span data-ttu-id="76a2d-169">Der Name des streamingauftrags.</span><span class="sxs-lookup"><span data-stu-id="76a2d-169">The name of the streaming job.</span></span>
            </param>
        <param name="inputName">
            <span data-ttu-id="76a2d-170">Der Name der Eingabe.</span><span class="sxs-lookup"><span data-stu-id="76a2d-170">The name of the input.</span></span>
            </param>
        <param name="input">
            <span data-ttu-id="76a2d-171">Wenn die angegebene Eingabe nicht bereits vorhanden ist, muss dieser Parameter die vollständige eingabedefinition getestet werden soll enthalten.</span><span class="sxs-lookup"><span data-stu-id="76a2d-171">If the input specified does not already exist, this parameter must contain the full input definition intended to be tested.</span></span> <span data-ttu-id="76a2d-172">Wenn die Eingabe, die bereits vorhanden ist, dieser Parameter kann null So testen Sie die vorhandene Eingabe unverändert gelassen werden oder wenn angegeben, überschreibt die angegebenen Eigenschaften der entsprechenden Eigenschaften in die vorhandene Eingabe (genau wie ein PATCH-Vorgang) und das resultierende Eingabe wird getestet werden.</span><span class="sxs-lookup"><span data-stu-id="76a2d-172">If the input specified already exists, this parameter can be left null to test the existing input as is or if specified, the properties specified will overwrite the corresponding properties in the existing input (exactly like a PATCH operation) and the resulting input will be tested.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="76a2d-173">Die Header, die hinzugefügt werden auf Anforderung.</span><span class="sxs-lookup"><span data-stu-id="76a2d-173">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="76a2d-174">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="76a2d-174">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="76a2d-175">Testet, ob eine Eingabe-Datenquelle erreichbar und von Azure Stream Analytics-Dienst verwendet werden kann.</span><span class="sxs-lookup"><span data-stu-id="76a2d-175">Tests whether an input’s datasource is reachable and usable by the Azure Stream Analytics service.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="76a2d-176">Wird ausgelöst, wenn der Vorgang einen ungültigen Statuscode zurückgegeben hat.</span><span class="sxs-lookup"><span data-stu-id="76a2d-176">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="76a2d-177">Wird ausgelöst, wenn nicht die Antwort zu deserialisieren.</span><span class="sxs-lookup"><span data-stu-id="76a2d-177">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="76a2d-178">Wird ausgelöst, wenn ein erforderlicher Parameter null ist.</span><span class="sxs-lookup"><span data-stu-id="76a2d-178">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="UpdateWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.StreamAnalytics.Models.Input,Microsoft.Azure.Management.StreamAnalytics.Models.InputsUpdateHeaders&gt;&gt; UpdateWithHttpMessagesAsync (Microsoft.Azure.Management.StreamAnalytics.Models.Input input, string resourceGroupName, string jobName, string inputName, string ifMatch = null, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`2&lt;class Microsoft.Azure.Management.StreamAnalytics.Models.Input, class Microsoft.Azure.Management.StreamAnalytics.Models.InputsUpdateHeaders&gt;&gt; UpdateWithHttpMessagesAsync(class Microsoft.Azure.Management.StreamAnalytics.Models.Input input, string resourceGroupName, string jobName, string inputName, string ifMatch, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StreamAnalytics.IInputsOperations.UpdateWithHttpMessagesAsync(Microsoft.Azure.Management.StreamAnalytics.Models.Input,System.String,System.String,System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member UpdateWithHttpMessagesAsync : Microsoft.Azure.Management.StreamAnalytics.Models.Input * string * string * string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.StreamAnalytics.Models.Input, Microsoft.Azure.Management.StreamAnalytics.Models.InputsUpdateHeaders&gt;&gt;" Usage="iInputsOperations.UpdateWithHttpMessagesAsync (input, resourceGroupName, jobName, inputName, ifMatch, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.StreamAnalytics.Models.Input,Microsoft.Azure.Management.StreamAnalytics.Models.InputsUpdateHeaders&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="input" Type="Microsoft.Azure.Management.StreamAnalytics.Models.Input" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="jobName" Type="System.String" />
        <Parameter Name="inputName" Type="System.String" />
        <Parameter Name="ifMatch" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="input">
            <span data-ttu-id="76a2d-179">Ein Input-Objekt.</span><span class="sxs-lookup"><span data-stu-id="76a2d-179">An Input object.</span></span> <span data-ttu-id="76a2d-180">Die Eigenschaften, die hier angegebene überschreibt die entsprechenden Eigenschaften in der vorhandenen Eingabe (d. h. Diese Eigenschaften werden aktualisiert).</span><span class="sxs-lookup"><span data-stu-id="76a2d-180">The properties specified here will overwrite the corresponding properties in the existing input (ie. Those properties will be updated).</span></span> <span data-ttu-id="76a2d-181">Alle Eigenschaften, die werden auf null festgelegt, hier bedeutet, dass die entsprechende Eigenschaft in der vorhandenen Eingabe identisch bleibt und nicht als Ergebnis dieser PATCH-Vorgang geändert.</span><span class="sxs-lookup"><span data-stu-id="76a2d-181">Any properties that are set to null here will mean that the corresponding property in the existing input will remain the same and not change as a result of this PATCH operation.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="76a2d-182">Der Name der Ressourcengruppe, die die Ressource enthält.</span><span class="sxs-lookup"><span data-stu-id="76a2d-182">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="76a2d-183">Dieser Wert kann über die Azure-Ressourcen-Manager-API oder das Portal abgerufen werden.</span><span class="sxs-lookup"><span data-stu-id="76a2d-183">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="jobName">
            <span data-ttu-id="76a2d-184">Der Name des streamingauftrags.</span><span class="sxs-lookup"><span data-stu-id="76a2d-184">The name of the streaming job.</span></span>
            </param>
        <param name="inputName">
            <span data-ttu-id="76a2d-185">Der Name der Eingabe.</span><span class="sxs-lookup"><span data-stu-id="76a2d-185">The name of the input.</span></span>
            </param>
        <param name="ifMatch">
            <span data-ttu-id="76a2d-186">Das ETag der Eingabe.</span><span class="sxs-lookup"><span data-stu-id="76a2d-186">The ETag of the input.</span></span> <span data-ttu-id="76a2d-187">Lassen Sie diesen Wert, um die aktuelle Eingabe immer überschrieben.</span><span class="sxs-lookup"><span data-stu-id="76a2d-187">Omit this value to always overwrite the current input.</span></span> <span data-ttu-id="76a2d-188">Geben Sie die letzten gesehen ETag-Wert um versehentlich Overwritting gleichzeitige Änderungen zu verhindern.</span><span class="sxs-lookup"><span data-stu-id="76a2d-188">Specify the last-seen ETag value to prevent accidentally overwritting concurrent changes.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="76a2d-189">Die Header, die hinzugefügt werden auf Anforderung.</span><span class="sxs-lookup"><span data-stu-id="76a2d-189">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="76a2d-190">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="76a2d-190">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="76a2d-191">Aktualisiert eine vorhandene Eingabe unter einem vorhandenen streaming-Auftrags an.</span><span class="sxs-lookup"><span data-stu-id="76a2d-191">Updates an existing input under an existing streaming job.</span></span> <span data-ttu-id="76a2d-192">Dies kann verwendet werden, aktualisieren Sie teilweise (d. h.</span><span class="sxs-lookup"><span data-stu-id="76a2d-192">This can be used to partially update (ie.</span></span> <span data-ttu-id="76a2d-193">Aktualisieren Sie eine oder zwei Eigenschaften) Eingabe ohne den Rest der Auftrag oder die Eingabe-Definition.</span><span class="sxs-lookup"><span data-stu-id="76a2d-193">update one or two properties) an input without affecting the rest the job or input definition.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="76a2d-194">Wird ausgelöst, wenn der Vorgang einen ungültigen Statuscode zurückgegeben hat.</span><span class="sxs-lookup"><span data-stu-id="76a2d-194">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="76a2d-195">Wird ausgelöst, wenn nicht die Antwort zu deserialisieren.</span><span class="sxs-lookup"><span data-stu-id="76a2d-195">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="76a2d-196">Wird ausgelöst, wenn ein erforderlicher Parameter null ist.</span><span class="sxs-lookup"><span data-stu-id="76a2d-196">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>