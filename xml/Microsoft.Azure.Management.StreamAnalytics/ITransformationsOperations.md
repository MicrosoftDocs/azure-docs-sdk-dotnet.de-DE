<Type Name="ITransformationsOperations" FullName="Microsoft.Azure.Management.StreamAnalytics.ITransformationsOperations">
  <TypeSignature Language="C#" Value="public interface ITransformationsOperations" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract ITransformationsOperations" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.StreamAnalytics.ITransformationsOperations" />
  <TypeSignature Language="VB.NET" Value="Public Interface ITransformationsOperations" />
  <TypeSignature Language="F#" Value="type ITransformationsOperations = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
    <AssemblyVersion>2.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="8caea-101">TransformationsOperations-Vorgänge.</span><span class="sxs-lookup"><span data-stu-id="8caea-101">TransformationsOperations operations.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="CreateOrReplaceWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.StreamAnalytics.Models.Transformation,Microsoft.Azure.Management.StreamAnalytics.Models.TransformationsCreateOrReplaceHeaders&gt;&gt; CreateOrReplaceWithHttpMessagesAsync (Microsoft.Azure.Management.StreamAnalytics.Models.Transformation transformation, string resourceGroupName, string jobName, string transformationName, string ifMatch = null, string ifNoneMatch = null, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`2&lt;class Microsoft.Azure.Management.StreamAnalytics.Models.Transformation, class Microsoft.Azure.Management.StreamAnalytics.Models.TransformationsCreateOrReplaceHeaders&gt;&gt; CreateOrReplaceWithHttpMessagesAsync(class Microsoft.Azure.Management.StreamAnalytics.Models.Transformation transformation, string resourceGroupName, string jobName, string transformationName, string ifMatch, string ifNoneMatch, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StreamAnalytics.ITransformationsOperations.CreateOrReplaceWithHttpMessagesAsync(Microsoft.Azure.Management.StreamAnalytics.Models.Transformation,System.String,System.String,System.String,System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member CreateOrReplaceWithHttpMessagesAsync : Microsoft.Azure.Management.StreamAnalytics.Models.Transformation * string * string * string * string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.StreamAnalytics.Models.Transformation, Microsoft.Azure.Management.StreamAnalytics.Models.TransformationsCreateOrReplaceHeaders&gt;&gt;" Usage="iTransformationsOperations.CreateOrReplaceWithHttpMessagesAsync (transformation, resourceGroupName, jobName, transformationName, ifMatch, ifNoneMatch, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.StreamAnalytics.Models.Transformation,Microsoft.Azure.Management.StreamAnalytics.Models.TransformationsCreateOrReplaceHeaders&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="transformation" Type="Microsoft.Azure.Management.StreamAnalytics.Models.Transformation" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="jobName" Type="System.String" />
        <Parameter Name="transformationName" Type="System.String" />
        <Parameter Name="ifMatch" Type="System.String" />
        <Parameter Name="ifNoneMatch" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="transformation">
            <span data-ttu-id="8caea-102">Die Definition der Transformation, die zum Erstellen Sie eine neue Transformation oder Ersetzen von vorhandenen Knoten unter der streamingauftrag verwendet werden.</span><span class="sxs-lookup"><span data-stu-id="8caea-102">The definition of the transformation that will be used to create a new transformation or replace the existing one under the streaming job.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="8caea-103">Der Name der Ressourcengruppe, die die Ressource enthält.</span><span class="sxs-lookup"><span data-stu-id="8caea-103">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="8caea-104">Dieser Wert kann über die Azure-Ressourcen-Manager-API oder das Portal abgerufen werden.</span><span class="sxs-lookup"><span data-stu-id="8caea-104">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="jobName">
            <span data-ttu-id="8caea-105">Der Name des streamingauftrags.</span><span class="sxs-lookup"><span data-stu-id="8caea-105">The name of the streaming job.</span></span>
            </param>
        <param name="transformationName">
            <span data-ttu-id="8caea-106">Der Name der Transformation.</span><span class="sxs-lookup"><span data-stu-id="8caea-106">The name of the transformation.</span></span>
            </param>
        <param name="ifMatch">
            <span data-ttu-id="8caea-107">Das ETag der Transformation.</span><span class="sxs-lookup"><span data-stu-id="8caea-107">The ETag of the transformation.</span></span> <span data-ttu-id="8caea-108">Lassen Sie diesen Wert, um die aktuelle Transformation immer überschrieben.</span><span class="sxs-lookup"><span data-stu-id="8caea-108">Omit this value to always overwrite the current transformation.</span></span> <span data-ttu-id="8caea-109">Geben Sie die letzten gesehen ETag-Wert um versehentlich Overwritting gleichzeitige Änderungen zu verhindern.</span><span class="sxs-lookup"><span data-stu-id="8caea-109">Specify the last-seen ETag value to prevent accidentally overwritting concurrent changes.</span></span>
            </param>
        <param name="ifNoneMatch">
            <span data-ttu-id="8caea-110">Legen Sie auf "\*" um eine neue Transformation erstellt werden, sondern um zu verhindern, aktualisieren eine vorhandene Transformation zu ermöglichen.</span><span class="sxs-lookup"><span data-stu-id="8caea-110">Set to '\*' to allow a new transformation to be created, but to prevent updating an existing transformation.</span></span> <span data-ttu-id="8caea-111">Andere Werte führt 412 Antwort vor Bedingung fehlerhaft ist.</span><span class="sxs-lookup"><span data-stu-id="8caea-111">Other values will result in a 412 Pre-condition Failed response.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="8caea-112">Die Header, die hinzugefügt werden auf Anforderung.</span><span class="sxs-lookup"><span data-stu-id="8caea-112">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="8caea-113">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="8caea-113">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="8caea-114">Erstellt eine Transformation oder eine bereits vorhandene Transformation unter einem vorhandenen streaming Auftrag ersetzt.</span><span class="sxs-lookup"><span data-stu-id="8caea-114">Creates a transformation or replaces an already existing transformation under an existing streaming job.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="8caea-115">Wird ausgelöst, wenn der Vorgang einen ungültigen Statuscode zurückgegeben hat.</span><span class="sxs-lookup"><span data-stu-id="8caea-115">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="8caea-116">Wird ausgelöst, wenn nicht die Antwort zu deserialisieren.</span><span class="sxs-lookup"><span data-stu-id="8caea-116">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="8caea-117">Wird ausgelöst, wenn ein erforderlicher Parameter null ist.</span><span class="sxs-lookup"><span data-stu-id="8caea-117">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="GetWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.StreamAnalytics.Models.Transformation,Microsoft.Azure.Management.StreamAnalytics.Models.TransformationsGetHeaders&gt;&gt; GetWithHttpMessagesAsync (string resourceGroupName, string jobName, string transformationName, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`2&lt;class Microsoft.Azure.Management.StreamAnalytics.Models.Transformation, class Microsoft.Azure.Management.StreamAnalytics.Models.TransformationsGetHeaders&gt;&gt; GetWithHttpMessagesAsync(string resourceGroupName, string jobName, string transformationName, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StreamAnalytics.ITransformationsOperations.GetWithHttpMessagesAsync(System.String,System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetWithHttpMessagesAsync : string * string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.StreamAnalytics.Models.Transformation, Microsoft.Azure.Management.StreamAnalytics.Models.TransformationsGetHeaders&gt;&gt;" Usage="iTransformationsOperations.GetWithHttpMessagesAsync (resourceGroupName, jobName, transformationName, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.StreamAnalytics.Models.Transformation,Microsoft.Azure.Management.StreamAnalytics.Models.TransformationsGetHeaders&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="jobName" Type="System.String" />
        <Parameter Name="transformationName" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="8caea-118">Der Name der Ressourcengruppe, die die Ressource enthält.</span><span class="sxs-lookup"><span data-stu-id="8caea-118">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="8caea-119">Dieser Wert kann über die Azure-Ressourcen-Manager-API oder das Portal abgerufen werden.</span><span class="sxs-lookup"><span data-stu-id="8caea-119">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="jobName">
            <span data-ttu-id="8caea-120">Der Name des streamingauftrags.</span><span class="sxs-lookup"><span data-stu-id="8caea-120">The name of the streaming job.</span></span>
            </param>
        <param name="transformationName">
            <span data-ttu-id="8caea-121">Der Name der Transformation.</span><span class="sxs-lookup"><span data-stu-id="8caea-121">The name of the transformation.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="8caea-122">Die Header, die hinzugefügt werden auf Anforderung.</span><span class="sxs-lookup"><span data-stu-id="8caea-122">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="8caea-123">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="8caea-123">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="8caea-124">Ruft Details zu der angegebenen Transformation ab.</span><span class="sxs-lookup"><span data-stu-id="8caea-124">Gets details about the specified transformation.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="8caea-125">Wird ausgelöst, wenn der Vorgang einen ungültigen Statuscode zurückgegeben hat.</span><span class="sxs-lookup"><span data-stu-id="8caea-125">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="8caea-126">Wird ausgelöst, wenn nicht die Antwort zu deserialisieren.</span><span class="sxs-lookup"><span data-stu-id="8caea-126">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="8caea-127">Wird ausgelöst, wenn ein erforderlicher Parameter null ist.</span><span class="sxs-lookup"><span data-stu-id="8caea-127">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="UpdateWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.StreamAnalytics.Models.Transformation,Microsoft.Azure.Management.StreamAnalytics.Models.TransformationsUpdateHeaders&gt;&gt; UpdateWithHttpMessagesAsync (Microsoft.Azure.Management.StreamAnalytics.Models.Transformation transformation, string resourceGroupName, string jobName, string transformationName, string ifMatch = null, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`2&lt;class Microsoft.Azure.Management.StreamAnalytics.Models.Transformation, class Microsoft.Azure.Management.StreamAnalytics.Models.TransformationsUpdateHeaders&gt;&gt; UpdateWithHttpMessagesAsync(class Microsoft.Azure.Management.StreamAnalytics.Models.Transformation transformation, string resourceGroupName, string jobName, string transformationName, string ifMatch, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StreamAnalytics.ITransformationsOperations.UpdateWithHttpMessagesAsync(Microsoft.Azure.Management.StreamAnalytics.Models.Transformation,System.String,System.String,System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member UpdateWithHttpMessagesAsync : Microsoft.Azure.Management.StreamAnalytics.Models.Transformation * string * string * string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.StreamAnalytics.Models.Transformation, Microsoft.Azure.Management.StreamAnalytics.Models.TransformationsUpdateHeaders&gt;&gt;" Usage="iTransformationsOperations.UpdateWithHttpMessagesAsync (transformation, resourceGroupName, jobName, transformationName, ifMatch, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.StreamAnalytics.Models.Transformation,Microsoft.Azure.Management.StreamAnalytics.Models.TransformationsUpdateHeaders&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="transformation" Type="Microsoft.Azure.Management.StreamAnalytics.Models.Transformation" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="jobName" Type="System.String" />
        <Parameter Name="transformationName" Type="System.String" />
        <Parameter Name="ifMatch" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="transformation">
            <span data-ttu-id="8caea-128">Eine Transformationsobjekt.</span><span class="sxs-lookup"><span data-stu-id="8caea-128">A Transformation object.</span></span> <span data-ttu-id="8caea-129">Die Eigenschaften, die hier angegebene überschreibt die entsprechenden Eigenschaften in die vorhandene Transformation (d. h. Diese Eigenschaften werden aktualisiert).</span><span class="sxs-lookup"><span data-stu-id="8caea-129">The properties specified here will overwrite the corresponding properties in the existing transformation (ie. Those properties will be updated).</span></span> <span data-ttu-id="8caea-130">Alle Eigenschaften, die werden auf null festgelegt, hier bedeutet, dass die entsprechende Eigenschaft in der vorhandenen Transformation identisch bleibt und als Ergebnis dieser PATCH-Vorgang nicht geändert werden.</span><span class="sxs-lookup"><span data-stu-id="8caea-130">Any properties that are set to null here will mean that the corresponding property in the existing transformation will remain the same and not change as a result of this PATCH operation.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="8caea-131">Der Name der Ressourcengruppe, die die Ressource enthält.</span><span class="sxs-lookup"><span data-stu-id="8caea-131">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="8caea-132">Dieser Wert kann über die Azure-Ressourcen-Manager-API oder das Portal abgerufen werden.</span><span class="sxs-lookup"><span data-stu-id="8caea-132">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="jobName">
            <span data-ttu-id="8caea-133">Der Name des streamingauftrags.</span><span class="sxs-lookup"><span data-stu-id="8caea-133">The name of the streaming job.</span></span>
            </param>
        <param name="transformationName">
            <span data-ttu-id="8caea-134">Der Name der Transformation.</span><span class="sxs-lookup"><span data-stu-id="8caea-134">The name of the transformation.</span></span>
            </param>
        <param name="ifMatch">
            <span data-ttu-id="8caea-135">Das ETag der Transformation.</span><span class="sxs-lookup"><span data-stu-id="8caea-135">The ETag of the transformation.</span></span> <span data-ttu-id="8caea-136">Lassen Sie diesen Wert, um die aktuelle Transformation immer überschrieben.</span><span class="sxs-lookup"><span data-stu-id="8caea-136">Omit this value to always overwrite the current transformation.</span></span> <span data-ttu-id="8caea-137">Geben Sie die letzten gesehen ETag-Wert um versehentlich Overwritting gleichzeitige Änderungen zu verhindern.</span><span class="sxs-lookup"><span data-stu-id="8caea-137">Specify the last-seen ETag value to prevent accidentally overwritting concurrent changes.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="8caea-138">Die Header, die hinzugefügt werden auf Anforderung.</span><span class="sxs-lookup"><span data-stu-id="8caea-138">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="8caea-139">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="8caea-139">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="8caea-140">Aktualisiert eine vorhandene Transformation unter einem vorhandenen streaming-Auftrags an.</span><span class="sxs-lookup"><span data-stu-id="8caea-140">Updates an existing transformation under an existing streaming job.</span></span>
            <span data-ttu-id="8caea-141">Dies kann verwendet werden, aktualisieren Sie teilweise (d. h.</span><span class="sxs-lookup"><span data-stu-id="8caea-141">This can be used to partially update (ie.</span></span> <span data-ttu-id="8caea-142">Aktualisieren Sie eine oder zwei Eigenschaften) eine Transformation ohne den Rest der Definition der Auftrag oder Transformation.</span><span class="sxs-lookup"><span data-stu-id="8caea-142">update one or two properties) a transformation without affecting the rest the job or transformation definition.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="8caea-143">Wird ausgelöst, wenn der Vorgang einen ungültigen Statuscode zurückgegeben hat.</span><span class="sxs-lookup"><span data-stu-id="8caea-143">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="8caea-144">Wird ausgelöst, wenn nicht die Antwort zu deserialisieren.</span><span class="sxs-lookup"><span data-stu-id="8caea-144">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="8caea-145">Wird ausgelöst, wenn ein erforderlicher Parameter null ist.</span><span class="sxs-lookup"><span data-stu-id="8caea-145">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>