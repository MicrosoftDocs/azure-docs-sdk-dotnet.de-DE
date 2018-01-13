<Type Name="ITaskOperations" FullName="Microsoft.Azure.Batch.Protocol.ITaskOperations">
  <TypeSignature Language="C#" Value="public interface ITaskOperations" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract ITaskOperations" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Batch.Protocol.ITaskOperations" />
  <TypeSignature Language="VB.NET" Value="Public Interface ITaskOperations" />
  <TypeSignature Language="F#" Value="type ITaskOperations = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
    <AssemblyVersion>7.1.0.0</AssemblyVersion>
    <AssemblyVersion>8.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="4cb42-101">TaskOperations-Vorgänge.</span><span class="sxs-lookup"><span data-stu-id="4cb42-101">TaskOperations operations.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="AddCollectionWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Batch.Protocol.Models.TaskAddCollectionResult,Microsoft.Azure.Batch.Protocol.Models.TaskAddCollectionHeaders&gt;&gt; AddCollectionWithHttpMessagesAsync (string jobId, System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.TaskAddParameter&gt; value, Microsoft.Azure.Batch.Protocol.Models.TaskAddCollectionOptions taskAddCollectionOptions = null, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`2&lt;class Microsoft.Azure.Batch.Protocol.Models.TaskAddCollectionResult, class Microsoft.Azure.Batch.Protocol.Models.TaskAddCollectionHeaders&gt;&gt; AddCollectionWithHttpMessagesAsync(string jobId, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Batch.Protocol.Models.TaskAddParameter&gt; value, class Microsoft.Azure.Batch.Protocol.Models.TaskAddCollectionOptions taskAddCollectionOptions, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.ITaskOperations.AddCollectionWithHttpMessagesAsync(System.String,System.Collections.Generic.IList{Microsoft.Azure.Batch.Protocol.Models.TaskAddParameter},Microsoft.Azure.Batch.Protocol.Models.TaskAddCollectionOptions,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member AddCollectionWithHttpMessagesAsync : string * System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.TaskAddParameter&gt; * Microsoft.Azure.Batch.Protocol.Models.TaskAddCollectionOptions * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Batch.Protocol.Models.TaskAddCollectionResult, Microsoft.Azure.Batch.Protocol.Models.TaskAddCollectionHeaders&gt;&gt;" Usage="iTaskOperations.AddCollectionWithHttpMessagesAsync (jobId, value, taskAddCollectionOptions, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Batch.Protocol.Models.TaskAddCollectionResult,Microsoft.Azure.Batch.Protocol.Models.TaskAddCollectionHeaders&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="jobId" Type="System.String" />
        <Parameter Name="value" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.TaskAddParameter&gt;" />
        <Parameter Name="taskAddCollectionOptions" Type="Microsoft.Azure.Batch.Protocol.Models.TaskAddCollectionOptions" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="jobId">
            <span data-ttu-id="4cb42-102">Die ID des Auftrags, der die Auflistung der ist, hinzugefügt werden.</span><span class="sxs-lookup"><span data-stu-id="4cb42-102">The ID of the job to which the task collection is to be added.</span></span>
            </param>
        <param name="value">
            <span data-ttu-id="4cb42-103">Die Auflistung von Aufgaben hinzufügen.</span><span class="sxs-lookup"><span data-stu-id="4cb42-103">The collection of tasks to add.</span></span> <span data-ttu-id="4cb42-104">Die serialisierte Gesamtgröße dieser Auflistung muss kleiner als 4 MB sein.</span><span class="sxs-lookup"><span data-stu-id="4cb42-104">The total serialized size of this collection must be less than 4MB.</span></span> <span data-ttu-id="4cb42-105">Ist er größer als 4MB (z. B., wenn jede Aufgabe 100 Ressourcendateien oder Umgebungsvariablen verfügt), wird die Anforderung schlägt fehl mit Code "RequestBodyTooLarge" und mit weniger Vorgänge erneut wiederholt werden sollen.</span><span class="sxs-lookup"><span data-stu-id="4cb42-105">If it is greater than 4MB (for example if each task has 100's of resource files or environment variables), the request will fail with code 'RequestBodyTooLarge' and should be retried again with fewer tasks.</span></span>
            </param>
        <param name="taskAddCollectionOptions">
            <span data-ttu-id="4cb42-106">Zusätzliche Parameter für den Vorgang</span><span class="sxs-lookup"><span data-stu-id="4cb42-106">Additional parameters for the operation</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="4cb42-107">Die Header, die hinzugefügt werden auf Anforderung.</span><span class="sxs-lookup"><span data-stu-id="4cb42-107">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="4cb42-108">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="4cb42-108">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="4cb42-109">Fügt eine Auflistung von Aufgaben an den angegebenen Auftrag.</span><span class="sxs-lookup"><span data-stu-id="4cb42-109">Adds a collection of tasks to the specified job.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="4cb42-110">Beachten Sie, dass jede Aufgabe eine eindeutige ID aufweisen muss</span><span class="sxs-lookup"><span data-stu-id="4cb42-110">Note that each task must have a unique ID.</span></span> <span data-ttu-id="4cb42-111">Der Batch-Dienst möglicherweise nicht die Ergebnisse für jede Aufgabe in der gleichen Reihenfolge zurück, die die Aufgaben in dieser Anforderung gesendet wurden.</span><span class="sxs-lookup"><span data-stu-id="4cb42-111">The Batch service may not return the results for each task in the same order the tasks were submitted in this request.</span></span> <span data-ttu-id="4cb42-112">Wenn der Server ein Timeout eintritt, oder die Verbindung, während der Anforderung geschlossen wird, die Anforderung teilweise oder vollständig verarbeitet war möglicherweise oder überhaupt nicht.</span><span class="sxs-lookup"><span data-stu-id="4cb42-112">If the server times out or the connection is closed during the request, the request may have been partially or fully processed, or not at all.</span></span> <span data-ttu-id="4cb42-113">In solchen Fällen sollte der Benutzer die Anforderung erneut senden.</span><span class="sxs-lookup"><span data-stu-id="4cb42-113">In such cases, the user should re-issue the request.</span></span> <span data-ttu-id="4cb42-114">Beachten Sie, dass es bis zu dem Benutzer, Fehler richtig zu behandeln, wenn eine Anforderung erneut gesendet wird.</span><span class="sxs-lookup"><span data-stu-id="4cb42-114">Note that it is up to the user to correctly handle failures when re-issuing a request.</span></span> <span data-ttu-id="4cb42-115">Beispielsweise sollten Sie die gleichen Aufgaben-IDs bei einer Wiederholung verwenden, damit, dass wenn der vorherige Vorgang erfolgreich war, die Wiederholung nicht unerwartet zusätzliche Aufgaben erstellt wird.</span><span class="sxs-lookup"><span data-stu-id="4cb42-115">For example, you should use the same task IDs during a retry so that if the prior operation succeeded, the retry will not create extra tasks unexpectedly.</span></span> <span data-ttu-id="4cb42-116">Wenn die Antwort alle Aufgaben, die Fehler beim Hinzufügen enthält, kann ein Client die Anforderung erneut ausführen.</span><span class="sxs-lookup"><span data-stu-id="4cb42-116">If the response contains any tasks which failed to add, a client can retry the request.</span></span> <span data-ttu-id="4cb42-117">In einer Wiederholung ist es am effizientesten, nur Vorgänge, die nicht hinzufügen, und klicken Sie, um Aufgaben zu unterdrücken, die beim ersten Versuch erfolgreich hinzugefügt wurden, erneut zu senden.</span><span class="sxs-lookup"><span data-stu-id="4cb42-117">In a retry, it is most efficient to resubmit only tasks that failed to add, and to omit tasks that were successfully added on the first attempt.</span></span> <span data-ttu-id="4cb42-118">Die maximale Lebensdauer einer Aufgabe vom hinzufügen bis zum Abschluss beträgt 7 Tage.</span><span class="sxs-lookup"><span data-stu-id="4cb42-118">The maximum lifetime of a task from addition to completion is 7 days.</span></span>
            <span data-ttu-id="4cb42-119">Wenn eine Aufgabe nicht abgeschlossen wurde, innerhalb von 7 Tagen hinzugefügt wird, dass durch die Batch-Dienst und der linken Seite beendet werden, wurde in unabhängig von Ihrem Status er zu diesem Zeitpunkt.</span><span class="sxs-lookup"><span data-stu-id="4cb42-119">If a task has not completed within 7 days of being added it will be terminated by the Batch service and left in whatever state it was in at that time.</span></span>
            </remarks>
        <exception cref="T:Microsoft.Azure.Batch.Protocol.Models.BatchErrorException">
            <span data-ttu-id="4cb42-120">Wird ausgelöst, wenn der Vorgang einen ungültigen Statuscode zurückgegeben hat.</span><span class="sxs-lookup"><span data-stu-id="4cb42-120">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="4cb42-121">Wird ausgelöst, wenn nicht die Antwort zu deserialisieren.</span><span class="sxs-lookup"><span data-stu-id="4cb42-121">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="4cb42-122">Wird ausgelöst, wenn ein erforderlicher Parameter null ist.</span><span class="sxs-lookup"><span data-stu-id="4cb42-122">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="AddWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationHeaderResponse&lt;Microsoft.Azure.Batch.Protocol.Models.TaskAddHeaders&gt;&gt; AddWithHttpMessagesAsync (string jobId, Microsoft.Azure.Batch.Protocol.Models.TaskAddParameter task, Microsoft.Azure.Batch.Protocol.Models.TaskAddOptions taskAddOptions = null, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationHeaderResponse`1&lt;class Microsoft.Azure.Batch.Protocol.Models.TaskAddHeaders&gt;&gt; AddWithHttpMessagesAsync(string jobId, class Microsoft.Azure.Batch.Protocol.Models.TaskAddParameter task, class Microsoft.Azure.Batch.Protocol.Models.TaskAddOptions taskAddOptions, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.ITaskOperations.AddWithHttpMessagesAsync(System.String,Microsoft.Azure.Batch.Protocol.Models.TaskAddParameter,Microsoft.Azure.Batch.Protocol.Models.TaskAddOptions,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member AddWithHttpMessagesAsync : string * Microsoft.Azure.Batch.Protocol.Models.TaskAddParameter * Microsoft.Azure.Batch.Protocol.Models.TaskAddOptions * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationHeaderResponse&lt;Microsoft.Azure.Batch.Protocol.Models.TaskAddHeaders&gt;&gt;" Usage="iTaskOperations.AddWithHttpMessagesAsync (jobId, task, taskAddOptions, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationHeaderResponse&lt;Microsoft.Azure.Batch.Protocol.Models.TaskAddHeaders&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="jobId" Type="System.String" />
        <Parameter Name="task" Type="Microsoft.Azure.Batch.Protocol.Models.TaskAddParameter" />
        <Parameter Name="taskAddOptions" Type="Microsoft.Azure.Batch.Protocol.Models.TaskAddOptions" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="jobId">
            <span data-ttu-id="4cb42-123">Die ID des Auftrags, zu dem die Aufgabe ist, hinzugefügt werden.</span><span class="sxs-lookup"><span data-stu-id="4cb42-123">The ID of the job to which the task is to be added.</span></span>
            </param>
        <param name="task">
            <span data-ttu-id="4cb42-124">Die Aufgabe hinzugefügt werden.</span><span class="sxs-lookup"><span data-stu-id="4cb42-124">The task to be added.</span></span>
            </param>
        <param name="taskAddOptions">
            <span data-ttu-id="4cb42-125">Zusätzliche Parameter für den Vorgang</span><span class="sxs-lookup"><span data-stu-id="4cb42-125">Additional parameters for the operation</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="4cb42-126">Die Header, die hinzugefügt werden auf Anforderung.</span><span class="sxs-lookup"><span data-stu-id="4cb42-126">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="4cb42-127">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="4cb42-127">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="4cb42-128">Fügt eine Aufgabe zum angegebenen Auftrag.</span><span class="sxs-lookup"><span data-stu-id="4cb42-128">Adds a task to the specified job.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="4cb42-129">Die maximale Lebensdauer einer Aufgabe vom hinzufügen bis zum Abschluss beträgt 7 Tage.</span><span class="sxs-lookup"><span data-stu-id="4cb42-129">The maximum lifetime of a task from addition to completion is 7 days.</span></span> <span data-ttu-id="4cb42-130">Wenn eine Aufgabe nicht abgeschlossen wurde, innerhalb von 7 Tagen hinzugefügt wird, dass durch die Batch-Dienst und der linken Seite beendet werden, wurde in unabhängig von Ihrem Status er zu diesem Zeitpunkt.</span><span class="sxs-lookup"><span data-stu-id="4cb42-130">If a task has not completed within 7 days of being added it will be terminated by the Batch service and left in whatever state it was in at that time.</span></span>
            </remarks>
        <exception cref="T:Microsoft.Azure.Batch.Protocol.Models.BatchErrorException">
            <span data-ttu-id="4cb42-131">Wird ausgelöst, wenn der Vorgang einen ungültigen Statuscode zurückgegeben hat.</span><span class="sxs-lookup"><span data-stu-id="4cb42-131">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="4cb42-132">Wird ausgelöst, wenn ein erforderlicher Parameter null ist.</span><span class="sxs-lookup"><span data-stu-id="4cb42-132">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="DeleteWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationHeaderResponse&lt;Microsoft.Azure.Batch.Protocol.Models.TaskDeleteHeaders&gt;&gt; DeleteWithHttpMessagesAsync (string jobId, string taskId, Microsoft.Azure.Batch.Protocol.Models.TaskDeleteOptions taskDeleteOptions = null, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationHeaderResponse`1&lt;class Microsoft.Azure.Batch.Protocol.Models.TaskDeleteHeaders&gt;&gt; DeleteWithHttpMessagesAsync(string jobId, string taskId, class Microsoft.Azure.Batch.Protocol.Models.TaskDeleteOptions taskDeleteOptions, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.ITaskOperations.DeleteWithHttpMessagesAsync(System.String,System.String,Microsoft.Azure.Batch.Protocol.Models.TaskDeleteOptions,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member DeleteWithHttpMessagesAsync : string * string * Microsoft.Azure.Batch.Protocol.Models.TaskDeleteOptions * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationHeaderResponse&lt;Microsoft.Azure.Batch.Protocol.Models.TaskDeleteHeaders&gt;&gt;" Usage="iTaskOperations.DeleteWithHttpMessagesAsync (jobId, taskId, taskDeleteOptions, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationHeaderResponse&lt;Microsoft.Azure.Batch.Protocol.Models.TaskDeleteHeaders&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="jobId" Type="System.String" />
        <Parameter Name="taskId" Type="System.String" />
        <Parameter Name="taskDeleteOptions" Type="Microsoft.Azure.Batch.Protocol.Models.TaskDeleteOptions" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="jobId">
            <span data-ttu-id="4cb42-133">Die ID des Auftrags, aus dem die Aufgabe zu löschen.</span><span class="sxs-lookup"><span data-stu-id="4cb42-133">The ID of the job from which to delete the task.</span></span>
            </param>
        <param name="taskId">
            <span data-ttu-id="4cb42-134">Die ID des Vorgangs zu löschen.</span><span class="sxs-lookup"><span data-stu-id="4cb42-134">The ID of the task to delete.</span></span>
            </param>
        <param name="taskDeleteOptions">
            <span data-ttu-id="4cb42-135">Zusätzliche Parameter für den Vorgang</span><span class="sxs-lookup"><span data-stu-id="4cb42-135">Additional parameters for the operation</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="4cb42-136">Die Header, die hinzugefügt werden auf Anforderung.</span><span class="sxs-lookup"><span data-stu-id="4cb42-136">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="4cb42-137">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="4cb42-137">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="4cb42-138">Löscht eine Aufgabe aus dem angegebenen Auftrag.</span><span class="sxs-lookup"><span data-stu-id="4cb42-138">Deletes a task from the specified job.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="4cb42-139">Wenn eine Aufgabe gelöscht wird, werden alle Dateien im Verzeichnis auf den Computeknoten, in dem es ausgeführt wurde (unabhängig von der Aufbewahrungsdauer) ebenfalls gelöscht.</span><span class="sxs-lookup"><span data-stu-id="4cb42-139">When a task is deleted, all of the files in its directory on the compute node where it ran are also deleted (regardless of the retention time).</span></span> <span data-ttu-id="4cb42-140">Für Vorgänge mit mehreren Instanzen gilt der Löschvorgang für den Task synchron an die primäre Aufgabe; Unteraufgaben und die Dateien werden asynchron im Hintergrund gelöscht.</span><span class="sxs-lookup"><span data-stu-id="4cb42-140">For multi-instance tasks, the delete task operation applies synchronously to the primary task; subtasks and their files are then deleted asynchronously in the background.</span></span>
            </remarks>
        <exception cref="T:Microsoft.Azure.Batch.Protocol.Models.BatchErrorException">
            <span data-ttu-id="4cb42-141">Wird ausgelöst, wenn der Vorgang einen ungültigen Statuscode zurückgegeben hat.</span><span class="sxs-lookup"><span data-stu-id="4cb42-141">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="4cb42-142">Wird ausgelöst, wenn ein erforderlicher Parameter null ist.</span><span class="sxs-lookup"><span data-stu-id="4cb42-142">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="GetWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Batch.Protocol.Models.CloudTask,Microsoft.Azure.Batch.Protocol.Models.TaskGetHeaders&gt;&gt; GetWithHttpMessagesAsync (string jobId, string taskId, Microsoft.Azure.Batch.Protocol.Models.TaskGetOptions taskGetOptions = null, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`2&lt;class Microsoft.Azure.Batch.Protocol.Models.CloudTask, class Microsoft.Azure.Batch.Protocol.Models.TaskGetHeaders&gt;&gt; GetWithHttpMessagesAsync(string jobId, string taskId, class Microsoft.Azure.Batch.Protocol.Models.TaskGetOptions taskGetOptions, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.ITaskOperations.GetWithHttpMessagesAsync(System.String,System.String,Microsoft.Azure.Batch.Protocol.Models.TaskGetOptions,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetWithHttpMessagesAsync : string * string * Microsoft.Azure.Batch.Protocol.Models.TaskGetOptions * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Batch.Protocol.Models.CloudTask, Microsoft.Azure.Batch.Protocol.Models.TaskGetHeaders&gt;&gt;" Usage="iTaskOperations.GetWithHttpMessagesAsync (jobId, taskId, taskGetOptions, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Batch.Protocol.Models.CloudTask,Microsoft.Azure.Batch.Protocol.Models.TaskGetHeaders&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="jobId" Type="System.String" />
        <Parameter Name="taskId" Type="System.String" />
        <Parameter Name="taskGetOptions" Type="Microsoft.Azure.Batch.Protocol.Models.TaskGetOptions" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="jobId">
            <span data-ttu-id="4cb42-143">Die ID des Auftrags, der den Task enthält.</span><span class="sxs-lookup"><span data-stu-id="4cb42-143">The ID of the job that contains the task.</span></span>
            </param>
        <param name="taskId">
            <span data-ttu-id="4cb42-144">Die ID des Tasks, zu dem Informationen abgerufen werden sollen.</span><span class="sxs-lookup"><span data-stu-id="4cb42-144">The ID of the task to get information about.</span></span>
            </param>
        <param name="taskGetOptions">
            <span data-ttu-id="4cb42-145">Zusätzliche Parameter für den Vorgang</span><span class="sxs-lookup"><span data-stu-id="4cb42-145">Additional parameters for the operation</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="4cb42-146">Die Header, die hinzugefügt werden auf Anforderung.</span><span class="sxs-lookup"><span data-stu-id="4cb42-146">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="4cb42-147">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="4cb42-147">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="4cb42-148">Ruft Informationen über den angegebenen Vorgang ab.</span><span class="sxs-lookup"><span data-stu-id="4cb42-148">Gets information about the specified task.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="4cb42-149">Für Vorgänge mit mehreren Instanzen Informationen wie z. B. Affinitäts-ID, finden und Sie ExecutionInfo NodeInfo in die primäre Aufgabe.</span><span class="sxs-lookup"><span data-stu-id="4cb42-149">For multi-instance tasks, information such as affinityId, executionInfo and nodeInfo refer to the primary task.</span></span> <span data-ttu-id="4cb42-150">Verwenden Sie die Liste Unteraufgaben API zum Abrufen von Informationen über Teilvorgänge an.</span><span class="sxs-lookup"><span data-stu-id="4cb42-150">Use the list subtasks API to retrieve information about subtasks.</span></span>
            </remarks>
        <exception cref="T:Microsoft.Azure.Batch.Protocol.Models.BatchErrorException">
            <span data-ttu-id="4cb42-151">Wird ausgelöst, wenn der Vorgang einen ungültigen Statuscode zurückgegeben hat.</span><span class="sxs-lookup"><span data-stu-id="4cb42-151">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="4cb42-152">Wird ausgelöst, wenn nicht die Antwort zu deserialisieren.</span><span class="sxs-lookup"><span data-stu-id="4cb42-152">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="4cb42-153">Wird ausgelöst, wenn ein erforderlicher Parameter null ist.</span><span class="sxs-lookup"><span data-stu-id="4cb42-153">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="ListNextWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Batch.Protocol.Models.CloudTask&gt;,Microsoft.Azure.Batch.Protocol.Models.TaskListHeaders&gt;&gt; ListNextWithHttpMessagesAsync (string nextPageLink, Microsoft.Azure.Batch.Protocol.Models.TaskListNextOptions taskListNextOptions = null, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`2&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Batch.Protocol.Models.CloudTask&gt;, class Microsoft.Azure.Batch.Protocol.Models.TaskListHeaders&gt;&gt; ListNextWithHttpMessagesAsync(string nextPageLink, class Microsoft.Azure.Batch.Protocol.Models.TaskListNextOptions taskListNextOptions, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.ITaskOperations.ListNextWithHttpMessagesAsync(System.String,Microsoft.Azure.Batch.Protocol.Models.TaskListNextOptions,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListNextWithHttpMessagesAsync : string * Microsoft.Azure.Batch.Protocol.Models.TaskListNextOptions * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Batch.Protocol.Models.CloudTask&gt;, Microsoft.Azure.Batch.Protocol.Models.TaskListHeaders&gt;&gt;" Usage="iTaskOperations.ListNextWithHttpMessagesAsync (nextPageLink, taskListNextOptions, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Batch.Protocol.Models.CloudTask&gt;,Microsoft.Azure.Batch.Protocol.Models.TaskListHeaders&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="taskListNextOptions" Type="Microsoft.Azure.Batch.Protocol.Models.TaskListNextOptions" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="nextPageLink">
            <span data-ttu-id="4cb42-154">Die "NextLink" aus dem vorherigen erfolgreichen Aufruf List-Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="4cb42-154">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="taskListNextOptions">
            <span data-ttu-id="4cb42-155">Zusätzliche Parameter für den Vorgang</span><span class="sxs-lookup"><span data-stu-id="4cb42-155">Additional parameters for the operation</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="4cb42-156">Die Header, die hinzugefügt werden auf Anforderung.</span><span class="sxs-lookup"><span data-stu-id="4cb42-156">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="4cb42-157">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="4cb42-157">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="4cb42-158">Zeigt eine Liste aller Aufgaben, die dem angegebenen Auftrag zugeordnet sind.</span><span class="sxs-lookup"><span data-stu-id="4cb42-158">Lists all of the tasks that are associated with the specified job.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="4cb42-159">Für Vorgänge mit mehreren Instanzen Informationen wie z. B. Affinitäts-ID, finden und Sie ExecutionInfo NodeInfo in die primäre Aufgabe.</span><span class="sxs-lookup"><span data-stu-id="4cb42-159">For multi-instance tasks, information such as affinityId, executionInfo and nodeInfo refer to the primary task.</span></span> <span data-ttu-id="4cb42-160">Verwenden Sie die Liste Unteraufgaben API zum Abrufen von Informationen über Teilvorgänge an.</span><span class="sxs-lookup"><span data-stu-id="4cb42-160">Use the list subtasks API to retrieve information about subtasks.</span></span>
            </remarks>
        <exception cref="T:Microsoft.Azure.Batch.Protocol.Models.BatchErrorException">
            <span data-ttu-id="4cb42-161">Wird ausgelöst, wenn der Vorgang einen ungültigen Statuscode zurückgegeben hat.</span><span class="sxs-lookup"><span data-stu-id="4cb42-161">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="4cb42-162">Wird ausgelöst, wenn nicht die Antwort zu deserialisieren.</span><span class="sxs-lookup"><span data-stu-id="4cb42-162">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="4cb42-163">Wird ausgelöst, wenn ein erforderlicher Parameter null ist.</span><span class="sxs-lookup"><span data-stu-id="4cb42-163">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="ListSubtasksWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Batch.Protocol.Models.CloudTaskListSubtasksResult,Microsoft.Azure.Batch.Protocol.Models.TaskListSubtasksHeaders&gt;&gt; ListSubtasksWithHttpMessagesAsync (string jobId, string taskId, Microsoft.Azure.Batch.Protocol.Models.TaskListSubtasksOptions taskListSubtasksOptions = null, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`2&lt;class Microsoft.Azure.Batch.Protocol.Models.CloudTaskListSubtasksResult, class Microsoft.Azure.Batch.Protocol.Models.TaskListSubtasksHeaders&gt;&gt; ListSubtasksWithHttpMessagesAsync(string jobId, string taskId, class Microsoft.Azure.Batch.Protocol.Models.TaskListSubtasksOptions taskListSubtasksOptions, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.ITaskOperations.ListSubtasksWithHttpMessagesAsync(System.String,System.String,Microsoft.Azure.Batch.Protocol.Models.TaskListSubtasksOptions,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListSubtasksWithHttpMessagesAsync : string * string * Microsoft.Azure.Batch.Protocol.Models.TaskListSubtasksOptions * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Batch.Protocol.Models.CloudTaskListSubtasksResult, Microsoft.Azure.Batch.Protocol.Models.TaskListSubtasksHeaders&gt;&gt;" Usage="iTaskOperations.ListSubtasksWithHttpMessagesAsync (jobId, taskId, taskListSubtasksOptions, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Batch.Protocol.Models.CloudTaskListSubtasksResult,Microsoft.Azure.Batch.Protocol.Models.TaskListSubtasksHeaders&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="jobId" Type="System.String" />
        <Parameter Name="taskId" Type="System.String" />
        <Parameter Name="taskListSubtasksOptions" Type="Microsoft.Azure.Batch.Protocol.Models.TaskListSubtasksOptions" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="jobId">
            <span data-ttu-id="4cb42-164">Die ID des Auftrags.</span><span class="sxs-lookup"><span data-stu-id="4cb42-164">The ID of the job.</span></span>
            </param>
        <param name="taskId">
            <span data-ttu-id="4cb42-165">Die ID des Tasks.</span><span class="sxs-lookup"><span data-stu-id="4cb42-165">The ID of the task.</span></span>
            </param>
        <param name="taskListSubtasksOptions">
            <span data-ttu-id="4cb42-166">Zusätzliche Parameter für den Vorgang</span><span class="sxs-lookup"><span data-stu-id="4cb42-166">Additional parameters for the operation</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="4cb42-167">Die Header, die hinzugefügt werden auf Anforderung.</span><span class="sxs-lookup"><span data-stu-id="4cb42-167">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="4cb42-168">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="4cb42-168">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="4cb42-169">Zeigt eine Liste aller die Unteraufgaben an, die der Aufgabe angegebenen mit mehreren Instanzen zugeordnet sind.</span><span class="sxs-lookup"><span data-stu-id="4cb42-169">Lists all of the subtasks that are associated with the specified multi-instance task.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="4cb42-170">Wenn der Vorgang nicht um eine Aufgabe mit mehreren Instanzen ist zurück dies eine leere Auflistung.</span><span class="sxs-lookup"><span data-stu-id="4cb42-170">If the task is not a multi-instance task then this returns an empty collection.</span></span>
            </remarks>
        <exception cref="T:Microsoft.Azure.Batch.Protocol.Models.BatchErrorException">
            <span data-ttu-id="4cb42-171">Wird ausgelöst, wenn der Vorgang einen ungültigen Statuscode zurückgegeben hat.</span><span class="sxs-lookup"><span data-stu-id="4cb42-171">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="4cb42-172">Wird ausgelöst, wenn nicht die Antwort zu deserialisieren.</span><span class="sxs-lookup"><span data-stu-id="4cb42-172">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="4cb42-173">Wird ausgelöst, wenn ein erforderlicher Parameter null ist.</span><span class="sxs-lookup"><span data-stu-id="4cb42-173">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="ListWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Batch.Protocol.Models.CloudTask&gt;,Microsoft.Azure.Batch.Protocol.Models.TaskListHeaders&gt;&gt; ListWithHttpMessagesAsync (string jobId, Microsoft.Azure.Batch.Protocol.Models.TaskListOptions taskListOptions = null, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`2&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Batch.Protocol.Models.CloudTask&gt;, class Microsoft.Azure.Batch.Protocol.Models.TaskListHeaders&gt;&gt; ListWithHttpMessagesAsync(string jobId, class Microsoft.Azure.Batch.Protocol.Models.TaskListOptions taskListOptions, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.ITaskOperations.ListWithHttpMessagesAsync(System.String,Microsoft.Azure.Batch.Protocol.Models.TaskListOptions,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListWithHttpMessagesAsync : string * Microsoft.Azure.Batch.Protocol.Models.TaskListOptions * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Batch.Protocol.Models.CloudTask&gt;, Microsoft.Azure.Batch.Protocol.Models.TaskListHeaders&gt;&gt;" Usage="iTaskOperations.ListWithHttpMessagesAsync (jobId, taskListOptions, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Batch.Protocol.Models.CloudTask&gt;,Microsoft.Azure.Batch.Protocol.Models.TaskListHeaders&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="jobId" Type="System.String" />
        <Parameter Name="taskListOptions" Type="Microsoft.Azure.Batch.Protocol.Models.TaskListOptions" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="jobId">
            <span data-ttu-id="4cb42-174">Die ID des Auftrags.</span><span class="sxs-lookup"><span data-stu-id="4cb42-174">The ID of the job.</span></span>
            </param>
        <param name="taskListOptions">
            <span data-ttu-id="4cb42-175">Zusätzliche Parameter für den Vorgang</span><span class="sxs-lookup"><span data-stu-id="4cb42-175">Additional parameters for the operation</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="4cb42-176">Die Header, die hinzugefügt werden auf Anforderung.</span><span class="sxs-lookup"><span data-stu-id="4cb42-176">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="4cb42-177">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="4cb42-177">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="4cb42-178">Zeigt eine Liste aller Aufgaben, die dem angegebenen Auftrag zugeordnet sind.</span><span class="sxs-lookup"><span data-stu-id="4cb42-178">Lists all of the tasks that are associated with the specified job.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="4cb42-179">Für Vorgänge mit mehreren Instanzen Informationen wie z. B. Affinitäts-ID, finden und Sie ExecutionInfo NodeInfo in die primäre Aufgabe.</span><span class="sxs-lookup"><span data-stu-id="4cb42-179">For multi-instance tasks, information such as affinityId, executionInfo and nodeInfo refer to the primary task.</span></span> <span data-ttu-id="4cb42-180">Verwenden Sie die Liste Unteraufgaben API zum Abrufen von Informationen über Teilvorgänge an.</span><span class="sxs-lookup"><span data-stu-id="4cb42-180">Use the list subtasks API to retrieve information about subtasks.</span></span>
            </remarks>
        <exception cref="T:Microsoft.Azure.Batch.Protocol.Models.BatchErrorException">
            <span data-ttu-id="4cb42-181">Wird ausgelöst, wenn der Vorgang einen ungültigen Statuscode zurückgegeben hat.</span><span class="sxs-lookup"><span data-stu-id="4cb42-181">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="4cb42-182">Wird ausgelöst, wenn nicht die Antwort zu deserialisieren.</span><span class="sxs-lookup"><span data-stu-id="4cb42-182">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="4cb42-183">Wird ausgelöst, wenn ein erforderlicher Parameter null ist.</span><span class="sxs-lookup"><span data-stu-id="4cb42-183">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="ReactivateWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationHeaderResponse&lt;Microsoft.Azure.Batch.Protocol.Models.TaskReactivateHeaders&gt;&gt; ReactivateWithHttpMessagesAsync (string jobId, string taskId, Microsoft.Azure.Batch.Protocol.Models.TaskReactivateOptions taskReactivateOptions = null, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationHeaderResponse`1&lt;class Microsoft.Azure.Batch.Protocol.Models.TaskReactivateHeaders&gt;&gt; ReactivateWithHttpMessagesAsync(string jobId, string taskId, class Microsoft.Azure.Batch.Protocol.Models.TaskReactivateOptions taskReactivateOptions, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.ITaskOperations.ReactivateWithHttpMessagesAsync(System.String,System.String,Microsoft.Azure.Batch.Protocol.Models.TaskReactivateOptions,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ReactivateWithHttpMessagesAsync : string * string * Microsoft.Azure.Batch.Protocol.Models.TaskReactivateOptions * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationHeaderResponse&lt;Microsoft.Azure.Batch.Protocol.Models.TaskReactivateHeaders&gt;&gt;" Usage="iTaskOperations.ReactivateWithHttpMessagesAsync (jobId, taskId, taskReactivateOptions, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationHeaderResponse&lt;Microsoft.Azure.Batch.Protocol.Models.TaskReactivateHeaders&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="jobId" Type="System.String" />
        <Parameter Name="taskId" Type="System.String" />
        <Parameter Name="taskReactivateOptions" Type="Microsoft.Azure.Batch.Protocol.Models.TaskReactivateOptions" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="jobId">
            <span data-ttu-id="4cb42-184">Die ID des Auftrags, der den Task enthält.</span><span class="sxs-lookup"><span data-stu-id="4cb42-184">The ID of the job containing the task.</span></span>
            </param>
        <param name="taskId">
            <span data-ttu-id="4cb42-185">Die ID des Tasks zu reaktivieren.</span><span class="sxs-lookup"><span data-stu-id="4cb42-185">The ID of the task to reactivate.</span></span>
            </param>
        <param name="taskReactivateOptions">
            <span data-ttu-id="4cb42-186">Zusätzliche Parameter für den Vorgang</span><span class="sxs-lookup"><span data-stu-id="4cb42-186">Additional parameters for the operation</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="4cb42-187">Die Header, die hinzugefügt werden auf Anforderung.</span><span class="sxs-lookup"><span data-stu-id="4cb42-187">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="4cb42-188">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="4cb42-188">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="4cb42-189">Reaktiviert eine Aufgabe, sodass es erneut ausführen, auch wenn die Anzahl der Wiederholungsversuche ausgeschöpft ist.</span><span class="sxs-lookup"><span data-stu-id="4cb42-189">Reactivates a task, allowing it to run again even if its retry count has been exhausted.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="4cb42-190">Reaktivierung wird eine Aufgabe berechtigt ist, bis die maximale Anzahl von Wiederholungsversuchen zum Vorgang wiederholt werden.</span><span class="sxs-lookup"><span data-stu-id="4cb42-190">Reactivation makes a task eligible to be retried again up to its maximum retry count.</span></span> <span data-ttu-id="4cb42-191">Der Status der Aufgabe wird in aktiv geändert.</span><span class="sxs-lookup"><span data-stu-id="4cb42-191">The task's state is changed to active.</span></span> <span data-ttu-id="4cb42-192">Wie die Aufgabe nicht mehr in den Zustand abgeschlossen ist, ist keine vorherigen beenden Code oder das Fehlschlagen der Informationen nach der Reaktivierung nicht mehr verfügbar.</span><span class="sxs-lookup"><span data-stu-id="4cb42-192">As the task is no longer in the completed state, any previous exit code or failure information is no longer available after reactivation.</span></span> <span data-ttu-id="4cb42-193">Jedes Mal, wenn eine Aufgabe erneut aktiviert wird, wird die Wiederholungsanzahl auf 0 zurückgesetzt.</span><span class="sxs-lookup"><span data-stu-id="4cb42-193">Each time a task is reactivated, its retry count is reset to 0.</span></span>
            <span data-ttu-id="4cb42-194">Reaktivierung fehl für Aufgaben, die nicht abgeschlossen oder zuvor erfolgreich (mit Exitcode 0) abgeschlossen.</span><span class="sxs-lookup"><span data-stu-id="4cb42-194">Reactivation will fail for tasks that are not completed or that previously completed successfully (with an exit code of 0).</span></span>
            <span data-ttu-id="4cb42-195">Darüber hinaus schlägt er fehl, wenn der Auftrag abgeschlossen wurde (oder beenden oder löschen).</span><span class="sxs-lookup"><span data-stu-id="4cb42-195">Additionally, it will fail if the job has completed (or is terminating or deleting).</span></span>
            </remarks>
        <exception cref="T:Microsoft.Azure.Batch.Protocol.Models.BatchErrorException">
            <span data-ttu-id="4cb42-196">Wird ausgelöst, wenn der Vorgang einen ungültigen Statuscode zurückgegeben hat.</span><span class="sxs-lookup"><span data-stu-id="4cb42-196">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="4cb42-197">Wird ausgelöst, wenn ein erforderlicher Parameter null ist.</span><span class="sxs-lookup"><span data-stu-id="4cb42-197">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="TerminateWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationHeaderResponse&lt;Microsoft.Azure.Batch.Protocol.Models.TaskTerminateHeaders&gt;&gt; TerminateWithHttpMessagesAsync (string jobId, string taskId, Microsoft.Azure.Batch.Protocol.Models.TaskTerminateOptions taskTerminateOptions = null, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationHeaderResponse`1&lt;class Microsoft.Azure.Batch.Protocol.Models.TaskTerminateHeaders&gt;&gt; TerminateWithHttpMessagesAsync(string jobId, string taskId, class Microsoft.Azure.Batch.Protocol.Models.TaskTerminateOptions taskTerminateOptions, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.ITaskOperations.TerminateWithHttpMessagesAsync(System.String,System.String,Microsoft.Azure.Batch.Protocol.Models.TaskTerminateOptions,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member TerminateWithHttpMessagesAsync : string * string * Microsoft.Azure.Batch.Protocol.Models.TaskTerminateOptions * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationHeaderResponse&lt;Microsoft.Azure.Batch.Protocol.Models.TaskTerminateHeaders&gt;&gt;" Usage="iTaskOperations.TerminateWithHttpMessagesAsync (jobId, taskId, taskTerminateOptions, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationHeaderResponse&lt;Microsoft.Azure.Batch.Protocol.Models.TaskTerminateHeaders&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="jobId" Type="System.String" />
        <Parameter Name="taskId" Type="System.String" />
        <Parameter Name="taskTerminateOptions" Type="Microsoft.Azure.Batch.Protocol.Models.TaskTerminateOptions" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="jobId">
            <span data-ttu-id="4cb42-198">Die ID des Auftrags, der den Task enthält.</span><span class="sxs-lookup"><span data-stu-id="4cb42-198">The ID of the job containing the task.</span></span>
            </param>
        <param name="taskId">
            <span data-ttu-id="4cb42-199">Die ID des Tasks beendet werden soll.</span><span class="sxs-lookup"><span data-stu-id="4cb42-199">The ID of the task to terminate.</span></span>
            </param>
        <param name="taskTerminateOptions">
            <span data-ttu-id="4cb42-200">Zusätzliche Parameter für den Vorgang</span><span class="sxs-lookup"><span data-stu-id="4cb42-200">Additional parameters for the operation</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="4cb42-201">Die Header, die hinzugefügt werden auf Anforderung.</span><span class="sxs-lookup"><span data-stu-id="4cb42-201">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="4cb42-202">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="4cb42-202">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="4cb42-203">Beendet die angegebene Aufgabe an.</span><span class="sxs-lookup"><span data-stu-id="4cb42-203">Terminates the specified task.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="4cb42-204">Wenn die Aufgabe beendet wurde, wird in den abgeschlossenen Zustand verschoben.</span><span class="sxs-lookup"><span data-stu-id="4cb42-204">When the task has been terminated, it moves to the completed state.</span></span>
            <span data-ttu-id="4cb42-205">Für Vorgänge mit mehreren Instanzen gilt der Vorgang "Beenden" Task synchron an die primäre Aufgabe. Unteraufgaben werden dann asynchron im Hintergrund beendet.</span><span class="sxs-lookup"><span data-stu-id="4cb42-205">For multi-instance tasks, the terminate task operation applies synchronously to the primary task; subtasks are then terminated asynchronously in the background.</span></span>
            </remarks>
        <exception cref="T:Microsoft.Azure.Batch.Protocol.Models.BatchErrorException">
            <span data-ttu-id="4cb42-206">Wird ausgelöst, wenn der Vorgang einen ungültigen Statuscode zurückgegeben hat.</span><span class="sxs-lookup"><span data-stu-id="4cb42-206">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="4cb42-207">Wird ausgelöst, wenn ein erforderlicher Parameter null ist.</span><span class="sxs-lookup"><span data-stu-id="4cb42-207">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="UpdateWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationHeaderResponse&lt;Microsoft.Azure.Batch.Protocol.Models.TaskUpdateHeaders&gt;&gt; UpdateWithHttpMessagesAsync (string jobId, string taskId, Microsoft.Azure.Batch.Protocol.Models.TaskConstraints constraints = null, Microsoft.Azure.Batch.Protocol.Models.TaskUpdateOptions taskUpdateOptions = null, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationHeaderResponse`1&lt;class Microsoft.Azure.Batch.Protocol.Models.TaskUpdateHeaders&gt;&gt; UpdateWithHttpMessagesAsync(string jobId, string taskId, class Microsoft.Azure.Batch.Protocol.Models.TaskConstraints constraints, class Microsoft.Azure.Batch.Protocol.Models.TaskUpdateOptions taskUpdateOptions, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.ITaskOperations.UpdateWithHttpMessagesAsync(System.String,System.String,Microsoft.Azure.Batch.Protocol.Models.TaskConstraints,Microsoft.Azure.Batch.Protocol.Models.TaskUpdateOptions,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member UpdateWithHttpMessagesAsync : string * string * Microsoft.Azure.Batch.Protocol.Models.TaskConstraints * Microsoft.Azure.Batch.Protocol.Models.TaskUpdateOptions * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationHeaderResponse&lt;Microsoft.Azure.Batch.Protocol.Models.TaskUpdateHeaders&gt;&gt;" Usage="iTaskOperations.UpdateWithHttpMessagesAsync (jobId, taskId, constraints, taskUpdateOptions, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationHeaderResponse&lt;Microsoft.Azure.Batch.Protocol.Models.TaskUpdateHeaders&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="jobId" Type="System.String" />
        <Parameter Name="taskId" Type="System.String" />
        <Parameter Name="constraints" Type="Microsoft.Azure.Batch.Protocol.Models.TaskConstraints" />
        <Parameter Name="taskUpdateOptions" Type="Microsoft.Azure.Batch.Protocol.Models.TaskUpdateOptions" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="jobId">
            <span data-ttu-id="4cb42-208">Die ID des Auftrags, der den Task enthält.</span><span class="sxs-lookup"><span data-stu-id="4cb42-208">The ID of the job containing the task.</span></span>
            </param>
        <param name="taskId">
            <span data-ttu-id="4cb42-209">Die ID des Tasks aktualisiert.</span><span class="sxs-lookup"><span data-stu-id="4cb42-209">The ID of the task to update.</span></span>
            </param>
        <param name="constraints">
            <span data-ttu-id="4cb42-210">Einschränkungen, die für diese Aufgabe gelten.</span><span class="sxs-lookup"><span data-stu-id="4cb42-210">Constraints that apply to this task.</span></span> <span data-ttu-id="4cb42-211">Wenn nicht angegeben, wird die Aufgabe das Default-Einschränkungen angegeben.</span><span class="sxs-lookup"><span data-stu-id="4cb42-211">If omitted, the task is given the default constraints.</span></span> <span data-ttu-id="4cb42-212">Für Vorgänge mit mehreren Instanzen aktualisieren die Aufbewahrungsdauer gilt nur für die primäre Aufgabe und Teilvorgänge nicht.</span><span class="sxs-lookup"><span data-stu-id="4cb42-212">For multi-instance tasks, updating the retention time applies only to the primary task and not subtasks.</span></span>
            </param>
        <param name="taskUpdateOptions">
            <span data-ttu-id="4cb42-213">Zusätzliche Parameter für den Vorgang</span><span class="sxs-lookup"><span data-stu-id="4cb42-213">Additional parameters for the operation</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="4cb42-214">Die Header, die hinzugefügt werden auf Anforderung.</span><span class="sxs-lookup"><span data-stu-id="4cb42-214">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="4cb42-215">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="4cb42-215">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="4cb42-216">Aktualisiert die Eigenschaften der angegebenen Aufgabe.</span><span class="sxs-lookup"><span data-stu-id="4cb42-216">Updates the properties of the specified task.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Azure.Batch.Protocol.Models.BatchErrorException">
            <span data-ttu-id="4cb42-217">Wird ausgelöst, wenn der Vorgang einen ungültigen Statuscode zurückgegeben hat.</span><span class="sxs-lookup"><span data-stu-id="4cb42-217">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="4cb42-218">Wird ausgelöst, wenn ein erforderlicher Parameter null ist.</span><span class="sxs-lookup"><span data-stu-id="4cb42-218">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>