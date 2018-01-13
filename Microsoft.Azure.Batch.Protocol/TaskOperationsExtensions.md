<Type Name="TaskOperationsExtensions" FullName="Microsoft.Azure.Batch.Protocol.TaskOperationsExtensions">
  <TypeSignature Language="C#" Value="public static class TaskOperationsExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit TaskOperationsExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Batch.Protocol.TaskOperationsExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module TaskOperationsExtensions" />
  <TypeSignature Language="F#" Value="type TaskOperationsExtensions = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
    <AssemblyVersion>7.1.0.0</AssemblyVersion>
    <AssemblyVersion>8.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="0060f-101">Erweiterungsmethoden für TaskOperations.</span><span class="sxs-lookup"><span data-stu-id="0060f-101">Extension methods for TaskOperations.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="Add">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Batch.Protocol.Models.TaskAddHeaders Add (this Microsoft.Azure.Batch.Protocol.ITaskOperations operations, string jobId, Microsoft.Azure.Batch.Protocol.Models.TaskAddParameter task, Microsoft.Azure.Batch.Protocol.Models.TaskAddOptions taskAddOptions = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Batch.Protocol.Models.TaskAddHeaders Add(class Microsoft.Azure.Batch.Protocol.ITaskOperations operations, string jobId, class Microsoft.Azure.Batch.Protocol.Models.TaskAddParameter task, class Microsoft.Azure.Batch.Protocol.Models.TaskAddOptions taskAddOptions) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.TaskOperationsExtensions.Add(Microsoft.Azure.Batch.Protocol.ITaskOperations,System.String,Microsoft.Azure.Batch.Protocol.Models.TaskAddParameter,Microsoft.Azure.Batch.Protocol.Models.TaskAddOptions)" />
      <MemberSignature Language="F#" Value="static member Add : Microsoft.Azure.Batch.Protocol.ITaskOperations * string * Microsoft.Azure.Batch.Protocol.Models.TaskAddParameter * Microsoft.Azure.Batch.Protocol.Models.TaskAddOptions -&gt; Microsoft.Azure.Batch.Protocol.Models.TaskAddHeaders" Usage="Microsoft.Azure.Batch.Protocol.TaskOperationsExtensions.Add (operations, jobId, task, taskAddOptions)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.Protocol.Models.TaskAddHeaders</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Batch.Protocol.ITaskOperations" RefType="this" />
        <Parameter Name="jobId" Type="System.String" />
        <Parameter Name="task" Type="Microsoft.Azure.Batch.Protocol.Models.TaskAddParameter" />
        <Parameter Name="taskAddOptions" Type="Microsoft.Azure.Batch.Protocol.Models.TaskAddOptions" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="0060f-102">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="0060f-102">The operations group for this extension method.</span></span>
            </param>
        <param name="jobId">
            <span data-ttu-id="0060f-103">Die ID des Auftrags, zu dem die Aufgabe ist, hinzugefügt werden.</span><span class="sxs-lookup"><span data-stu-id="0060f-103">The ID of the job to which the task is to be added.</span></span>
            </param>
        <param name="task">
            <span data-ttu-id="0060f-104">Die Aufgabe hinzugefügt werden.</span><span class="sxs-lookup"><span data-stu-id="0060f-104">The task to be added.</span></span>
            </param>
        <param name="taskAddOptions">
            <span data-ttu-id="0060f-105">Zusätzliche Parameter für den Vorgang</span><span class="sxs-lookup"><span data-stu-id="0060f-105">Additional parameters for the operation</span></span>
            </param>
        <summary>
            <span data-ttu-id="0060f-106">Fügt eine Aufgabe zum angegebenen Auftrag.</span><span class="sxs-lookup"><span data-stu-id="0060f-106">Adds a task to the specified job.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="0060f-107">Die maximale Lebensdauer einer Aufgabe vom hinzufügen bis zum Abschluss beträgt 7 Tage.</span><span class="sxs-lookup"><span data-stu-id="0060f-107">The maximum lifetime of a task from addition to completion is 7 days.</span></span> <span data-ttu-id="0060f-108">Wenn eine Aufgabe nicht abgeschlossen wurde, innerhalb von 7 Tagen hinzugefügt wird, dass durch die Batch-Dienst und der linken Seite beendet werden, wurde in unabhängig von Ihrem Status er zu diesem Zeitpunkt.</span><span class="sxs-lookup"><span data-stu-id="0060f-108">If a task has not completed within 7 days of being added it will be terminated by the Batch service and left in whatever state it was in at that time.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="AddAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Batch.Protocol.Models.TaskAddHeaders&gt; AddAsync (this Microsoft.Azure.Batch.Protocol.ITaskOperations operations, string jobId, Microsoft.Azure.Batch.Protocol.Models.TaskAddParameter task, Microsoft.Azure.Batch.Protocol.Models.TaskAddOptions taskAddOptions = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Batch.Protocol.Models.TaskAddHeaders&gt; AddAsync(class Microsoft.Azure.Batch.Protocol.ITaskOperations operations, string jobId, class Microsoft.Azure.Batch.Protocol.Models.TaskAddParameter task, class Microsoft.Azure.Batch.Protocol.Models.TaskAddOptions taskAddOptions, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.TaskOperationsExtensions.AddAsync(Microsoft.Azure.Batch.Protocol.ITaskOperations,System.String,Microsoft.Azure.Batch.Protocol.Models.TaskAddParameter,Microsoft.Azure.Batch.Protocol.Models.TaskAddOptions,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member AddAsync : Microsoft.Azure.Batch.Protocol.ITaskOperations * string * Microsoft.Azure.Batch.Protocol.Models.TaskAddParameter * Microsoft.Azure.Batch.Protocol.Models.TaskAddOptions * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Batch.Protocol.Models.TaskAddHeaders&gt;" Usage="Microsoft.Azure.Batch.Protocol.TaskOperationsExtensions.AddAsync (operations, jobId, task, taskAddOptions, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Batch.Protocol.TaskOperationsExtensions/&lt;AddAsync&gt;d__1))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Batch.Protocol.Models.TaskAddHeaders&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Batch.Protocol.ITaskOperations" RefType="this" />
        <Parameter Name="jobId" Type="System.String" />
        <Parameter Name="task" Type="Microsoft.Azure.Batch.Protocol.Models.TaskAddParameter" />
        <Parameter Name="taskAddOptions" Type="Microsoft.Azure.Batch.Protocol.Models.TaskAddOptions" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="0060f-109">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="0060f-109">The operations group for this extension method.</span></span>
            </param>
        <param name="jobId">
            <span data-ttu-id="0060f-110">Die ID des Auftrags, zu dem die Aufgabe ist, hinzugefügt werden.</span><span class="sxs-lookup"><span data-stu-id="0060f-110">The ID of the job to which the task is to be added.</span></span>
            </param>
        <param name="task">
            <span data-ttu-id="0060f-111">Die Aufgabe hinzugefügt werden.</span><span class="sxs-lookup"><span data-stu-id="0060f-111">The task to be added.</span></span>
            </param>
        <param name="taskAddOptions">
            <span data-ttu-id="0060f-112">Zusätzliche Parameter für den Vorgang</span><span class="sxs-lookup"><span data-stu-id="0060f-112">Additional parameters for the operation</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="0060f-113">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="0060f-113">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="0060f-114">Fügt eine Aufgabe zum angegebenen Auftrag.</span><span class="sxs-lookup"><span data-stu-id="0060f-114">Adds a task to the specified job.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="0060f-115">Die maximale Lebensdauer einer Aufgabe vom hinzufügen bis zum Abschluss beträgt 7 Tage.</span><span class="sxs-lookup"><span data-stu-id="0060f-115">The maximum lifetime of a task from addition to completion is 7 days.</span></span> <span data-ttu-id="0060f-116">Wenn eine Aufgabe nicht abgeschlossen wurde, innerhalb von 7 Tagen hinzugefügt wird, dass durch die Batch-Dienst und der linken Seite beendet werden, wurde in unabhängig von Ihrem Status er zu diesem Zeitpunkt.</span><span class="sxs-lookup"><span data-stu-id="0060f-116">If a task has not completed within 7 days of being added it will be terminated by the Batch service and left in whatever state it was in at that time.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="AddCollection">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Batch.Protocol.Models.TaskAddCollectionResult AddCollection (this Microsoft.Azure.Batch.Protocol.ITaskOperations operations, string jobId, System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.TaskAddParameter&gt; value, Microsoft.Azure.Batch.Protocol.Models.TaskAddCollectionOptions taskAddCollectionOptions = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Batch.Protocol.Models.TaskAddCollectionResult AddCollection(class Microsoft.Azure.Batch.Protocol.ITaskOperations operations, string jobId, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Batch.Protocol.Models.TaskAddParameter&gt; value, class Microsoft.Azure.Batch.Protocol.Models.TaskAddCollectionOptions taskAddCollectionOptions) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.TaskOperationsExtensions.AddCollection(Microsoft.Azure.Batch.Protocol.ITaskOperations,System.String,System.Collections.Generic.IList{Microsoft.Azure.Batch.Protocol.Models.TaskAddParameter},Microsoft.Azure.Batch.Protocol.Models.TaskAddCollectionOptions)" />
      <MemberSignature Language="F#" Value="static member AddCollection : Microsoft.Azure.Batch.Protocol.ITaskOperations * string * System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.TaskAddParameter&gt; * Microsoft.Azure.Batch.Protocol.Models.TaskAddCollectionOptions -&gt; Microsoft.Azure.Batch.Protocol.Models.TaskAddCollectionResult" Usage="Microsoft.Azure.Batch.Protocol.TaskOperationsExtensions.AddCollection (operations, jobId, value, taskAddCollectionOptions)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.Protocol.Models.TaskAddCollectionResult</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Batch.Protocol.ITaskOperations" RefType="this" />
        <Parameter Name="jobId" Type="System.String" />
        <Parameter Name="value" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.TaskAddParameter&gt;" />
        <Parameter Name="taskAddCollectionOptions" Type="Microsoft.Azure.Batch.Protocol.Models.TaskAddCollectionOptions" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="0060f-117">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="0060f-117">The operations group for this extension method.</span></span>
            </param>
        <param name="jobId">
            <span data-ttu-id="0060f-118">Die ID des Auftrags, der die Auflistung der ist, hinzugefügt werden.</span><span class="sxs-lookup"><span data-stu-id="0060f-118">The ID of the job to which the task collection is to be added.</span></span>
            </param>
        <param name="value">
            <span data-ttu-id="0060f-119">Die Auflistung von Aufgaben hinzufügen.</span><span class="sxs-lookup"><span data-stu-id="0060f-119">The collection of tasks to add.</span></span> <span data-ttu-id="0060f-120">Die serialisierte Gesamtgröße dieser Auflistung muss kleiner als 4 MB sein.</span><span class="sxs-lookup"><span data-stu-id="0060f-120">The total serialized size of this collection must be less than 4MB.</span></span> <span data-ttu-id="0060f-121">Ist er größer als 4MB (z. B., wenn jede Aufgabe 100 Ressourcendateien oder Umgebungsvariablen verfügt), wird die Anforderung schlägt fehl mit Code "RequestBodyTooLarge" und mit weniger Vorgänge erneut wiederholt werden sollen.</span><span class="sxs-lookup"><span data-stu-id="0060f-121">If it is greater than 4MB (for example if each task has 100's of resource files or environment variables), the request will fail with code 'RequestBodyTooLarge' and should be retried again with fewer tasks.</span></span>
            </param>
        <param name="taskAddCollectionOptions">
            <span data-ttu-id="0060f-122">Zusätzliche Parameter für den Vorgang</span><span class="sxs-lookup"><span data-stu-id="0060f-122">Additional parameters for the operation</span></span>
            </param>
        <summary>
            <span data-ttu-id="0060f-123">Fügt eine Auflistung von Aufgaben an den angegebenen Auftrag.</span><span class="sxs-lookup"><span data-stu-id="0060f-123">Adds a collection of tasks to the specified job.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="0060f-124">Beachten Sie, dass jede Aufgabe eine eindeutige ID aufweisen muss</span><span class="sxs-lookup"><span data-stu-id="0060f-124">Note that each task must have a unique ID.</span></span> <span data-ttu-id="0060f-125">Der Batch-Dienst möglicherweise nicht die Ergebnisse für jede Aufgabe in der gleichen Reihenfolge zurück, die die Aufgaben in dieser Anforderung gesendet wurden.</span><span class="sxs-lookup"><span data-stu-id="0060f-125">The Batch service may not return the results for each task in the same order the tasks were submitted in this request.</span></span> <span data-ttu-id="0060f-126">Wenn der Server ein Timeout eintritt, oder die Verbindung, während der Anforderung geschlossen wird, die Anforderung teilweise oder vollständig verarbeitet war möglicherweise oder überhaupt nicht.</span><span class="sxs-lookup"><span data-stu-id="0060f-126">If the server times out or the connection is closed during the request, the request may have been partially or fully processed, or not at all.</span></span> <span data-ttu-id="0060f-127">In solchen Fällen sollte der Benutzer die Anforderung erneut senden.</span><span class="sxs-lookup"><span data-stu-id="0060f-127">In such cases, the user should re-issue the request.</span></span> <span data-ttu-id="0060f-128">Beachten Sie, dass es bis zu dem Benutzer, Fehler richtig zu behandeln, wenn eine Anforderung erneut gesendet wird.</span><span class="sxs-lookup"><span data-stu-id="0060f-128">Note that it is up to the user to correctly handle failures when re-issuing a request.</span></span>
            <span data-ttu-id="0060f-129">Beispielsweise sollten Sie die gleichen Aufgaben-IDs bei einer Wiederholung verwenden, damit, dass wenn der vorherige Vorgang erfolgreich war, die Wiederholung nicht unerwartet zusätzliche Aufgaben erstellt wird.</span><span class="sxs-lookup"><span data-stu-id="0060f-129">For example, you should use the same task IDs during a retry so that if the prior operation succeeded, the retry will not create extra tasks unexpectedly.</span></span> <span data-ttu-id="0060f-130">Wenn die Antwort alle Aufgaben, die Fehler beim Hinzufügen enthält, kann ein Client die Anforderung erneut ausführen.</span><span class="sxs-lookup"><span data-stu-id="0060f-130">If the response contains any tasks which failed to add, a client can retry the request.</span></span> <span data-ttu-id="0060f-131">In einer Wiederholung ist es am effizientesten, nur Vorgänge, die nicht hinzufügen, und klicken Sie, um Aufgaben zu unterdrücken, die beim ersten Versuch erfolgreich hinzugefügt wurden, erneut zu senden.</span><span class="sxs-lookup"><span data-stu-id="0060f-131">In a retry, it is most efficient to resubmit only tasks that failed to add, and to omit tasks that were successfully added on the first attempt.</span></span> <span data-ttu-id="0060f-132">Die maximale Lebensdauer einer Aufgabe vom hinzufügen bis zum Abschluss beträgt 7 Tage.</span><span class="sxs-lookup"><span data-stu-id="0060f-132">The maximum lifetime of a task from addition to completion is 7 days.</span></span> <span data-ttu-id="0060f-133">Wenn eine Aufgabe nicht abgeschlossen wurde, innerhalb von 7 Tagen hinzugefügt wird, dass durch die Batch-Dienst und der linken Seite beendet werden, wurde in unabhängig von Ihrem Status er zu diesem Zeitpunkt.</span><span class="sxs-lookup"><span data-stu-id="0060f-133">If a task has not completed within 7 days of being added it will be terminated by the Batch service and left in whatever state it was in at that time.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="AddCollectionAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Batch.Protocol.Models.TaskAddCollectionResult&gt; AddCollectionAsync (this Microsoft.Azure.Batch.Protocol.ITaskOperations operations, string jobId, System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.TaskAddParameter&gt; value, Microsoft.Azure.Batch.Protocol.Models.TaskAddCollectionOptions taskAddCollectionOptions = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Batch.Protocol.Models.TaskAddCollectionResult&gt; AddCollectionAsync(class Microsoft.Azure.Batch.Protocol.ITaskOperations operations, string jobId, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Batch.Protocol.Models.TaskAddParameter&gt; value, class Microsoft.Azure.Batch.Protocol.Models.TaskAddCollectionOptions taskAddCollectionOptions, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.TaskOperationsExtensions.AddCollectionAsync(Microsoft.Azure.Batch.Protocol.ITaskOperations,System.String,System.Collections.Generic.IList{Microsoft.Azure.Batch.Protocol.Models.TaskAddParameter},Microsoft.Azure.Batch.Protocol.Models.TaskAddCollectionOptions,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member AddCollectionAsync : Microsoft.Azure.Batch.Protocol.ITaskOperations * string * System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.TaskAddParameter&gt; * Microsoft.Azure.Batch.Protocol.Models.TaskAddCollectionOptions * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Batch.Protocol.Models.TaskAddCollectionResult&gt;" Usage="Microsoft.Azure.Batch.Protocol.TaskOperationsExtensions.AddCollectionAsync (operations, jobId, value, taskAddCollectionOptions, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Batch.Protocol.TaskOperationsExtensions/&lt;AddCollectionAsync&gt;d__5))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Batch.Protocol.Models.TaskAddCollectionResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Batch.Protocol.ITaskOperations" RefType="this" />
        <Parameter Name="jobId" Type="System.String" />
        <Parameter Name="value" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.TaskAddParameter&gt;" />
        <Parameter Name="taskAddCollectionOptions" Type="Microsoft.Azure.Batch.Protocol.Models.TaskAddCollectionOptions" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="0060f-134">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="0060f-134">The operations group for this extension method.</span></span>
            </param>
        <param name="jobId">
            <span data-ttu-id="0060f-135">Die ID des Auftrags, der die Auflistung der ist, hinzugefügt werden.</span><span class="sxs-lookup"><span data-stu-id="0060f-135">The ID of the job to which the task collection is to be added.</span></span>
            </param>
        <param name="value">
            <span data-ttu-id="0060f-136">Die Auflistung von Aufgaben hinzufügen.</span><span class="sxs-lookup"><span data-stu-id="0060f-136">The collection of tasks to add.</span></span> <span data-ttu-id="0060f-137">Die serialisierte Gesamtgröße dieser Auflistung muss kleiner als 4 MB sein.</span><span class="sxs-lookup"><span data-stu-id="0060f-137">The total serialized size of this collection must be less than 4MB.</span></span> <span data-ttu-id="0060f-138">Ist er größer als 4MB (z. B., wenn jede Aufgabe 100 Ressourcendateien oder Umgebungsvariablen verfügt), wird die Anforderung schlägt fehl mit Code "RequestBodyTooLarge" und mit weniger Vorgänge erneut wiederholt werden sollen.</span><span class="sxs-lookup"><span data-stu-id="0060f-138">If it is greater than 4MB (for example if each task has 100's of resource files or environment variables), the request will fail with code 'RequestBodyTooLarge' and should be retried again with fewer tasks.</span></span>
            </param>
        <param name="taskAddCollectionOptions">
            <span data-ttu-id="0060f-139">Zusätzliche Parameter für den Vorgang</span><span class="sxs-lookup"><span data-stu-id="0060f-139">Additional parameters for the operation</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="0060f-140">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="0060f-140">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="0060f-141">Fügt eine Auflistung von Aufgaben an den angegebenen Auftrag.</span><span class="sxs-lookup"><span data-stu-id="0060f-141">Adds a collection of tasks to the specified job.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="0060f-142">Beachten Sie, dass jede Aufgabe eine eindeutige ID aufweisen muss</span><span class="sxs-lookup"><span data-stu-id="0060f-142">Note that each task must have a unique ID.</span></span> <span data-ttu-id="0060f-143">Der Batch-Dienst möglicherweise nicht die Ergebnisse für jede Aufgabe in der gleichen Reihenfolge zurück, die die Aufgaben in dieser Anforderung gesendet wurden.</span><span class="sxs-lookup"><span data-stu-id="0060f-143">The Batch service may not return the results for each task in the same order the tasks were submitted in this request.</span></span> <span data-ttu-id="0060f-144">Wenn der Server ein Timeout eintritt, oder die Verbindung, während der Anforderung geschlossen wird, die Anforderung teilweise oder vollständig verarbeitet war möglicherweise oder überhaupt nicht.</span><span class="sxs-lookup"><span data-stu-id="0060f-144">If the server times out or the connection is closed during the request, the request may have been partially or fully processed, or not at all.</span></span> <span data-ttu-id="0060f-145">In solchen Fällen sollte der Benutzer die Anforderung erneut senden.</span><span class="sxs-lookup"><span data-stu-id="0060f-145">In such cases, the user should re-issue the request.</span></span> <span data-ttu-id="0060f-146">Beachten Sie, dass es bis zu dem Benutzer, Fehler richtig zu behandeln, wenn eine Anforderung erneut gesendet wird.</span><span class="sxs-lookup"><span data-stu-id="0060f-146">Note that it is up to the user to correctly handle failures when re-issuing a request.</span></span>
            <span data-ttu-id="0060f-147">Beispielsweise sollten Sie die gleichen Aufgaben-IDs bei einer Wiederholung verwenden, damit, dass wenn der vorherige Vorgang erfolgreich war, die Wiederholung nicht unerwartet zusätzliche Aufgaben erstellt wird.</span><span class="sxs-lookup"><span data-stu-id="0060f-147">For example, you should use the same task IDs during a retry so that if the prior operation succeeded, the retry will not create extra tasks unexpectedly.</span></span> <span data-ttu-id="0060f-148">Wenn die Antwort alle Aufgaben, die Fehler beim Hinzufügen enthält, kann ein Client die Anforderung erneut ausführen.</span><span class="sxs-lookup"><span data-stu-id="0060f-148">If the response contains any tasks which failed to add, a client can retry the request.</span></span> <span data-ttu-id="0060f-149">In einer Wiederholung ist es am effizientesten, nur Vorgänge, die nicht hinzufügen, und klicken Sie, um Aufgaben zu unterdrücken, die beim ersten Versuch erfolgreich hinzugefügt wurden, erneut zu senden.</span><span class="sxs-lookup"><span data-stu-id="0060f-149">In a retry, it is most efficient to resubmit only tasks that failed to add, and to omit tasks that were successfully added on the first attempt.</span></span> <span data-ttu-id="0060f-150">Die maximale Lebensdauer einer Aufgabe vom hinzufügen bis zum Abschluss beträgt 7 Tage.</span><span class="sxs-lookup"><span data-stu-id="0060f-150">The maximum lifetime of a task from addition to completion is 7 days.</span></span> <span data-ttu-id="0060f-151">Wenn eine Aufgabe nicht abgeschlossen wurde, innerhalb von 7 Tagen hinzugefügt wird, dass durch die Batch-Dienst und der linken Seite beendet werden, wurde in unabhängig von Ihrem Status er zu diesem Zeitpunkt.</span><span class="sxs-lookup"><span data-stu-id="0060f-151">If a task has not completed within 7 days of being added it will be terminated by the Batch service and left in whatever state it was in at that time.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="Delete">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Batch.Protocol.Models.TaskDeleteHeaders Delete (this Microsoft.Azure.Batch.Protocol.ITaskOperations operations, string jobId, string taskId, Microsoft.Azure.Batch.Protocol.Models.TaskDeleteOptions taskDeleteOptions = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Batch.Protocol.Models.TaskDeleteHeaders Delete(class Microsoft.Azure.Batch.Protocol.ITaskOperations operations, string jobId, string taskId, class Microsoft.Azure.Batch.Protocol.Models.TaskDeleteOptions taskDeleteOptions) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.TaskOperationsExtensions.Delete(Microsoft.Azure.Batch.Protocol.ITaskOperations,System.String,System.String,Microsoft.Azure.Batch.Protocol.Models.TaskDeleteOptions)" />
      <MemberSignature Language="F#" Value="static member Delete : Microsoft.Azure.Batch.Protocol.ITaskOperations * string * string * Microsoft.Azure.Batch.Protocol.Models.TaskDeleteOptions -&gt; Microsoft.Azure.Batch.Protocol.Models.TaskDeleteHeaders" Usage="Microsoft.Azure.Batch.Protocol.TaskOperationsExtensions.Delete (operations, jobId, taskId, taskDeleteOptions)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.Protocol.Models.TaskDeleteHeaders</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Batch.Protocol.ITaskOperations" RefType="this" />
        <Parameter Name="jobId" Type="System.String" />
        <Parameter Name="taskId" Type="System.String" />
        <Parameter Name="taskDeleteOptions" Type="Microsoft.Azure.Batch.Protocol.Models.TaskDeleteOptions" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="0060f-152">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="0060f-152">The operations group for this extension method.</span></span>
            </param>
        <param name="jobId">
            <span data-ttu-id="0060f-153">Die ID des Auftrags, aus dem die Aufgabe zu löschen.</span><span class="sxs-lookup"><span data-stu-id="0060f-153">The ID of the job from which to delete the task.</span></span>
            </param>
        <param name="taskId">
            <span data-ttu-id="0060f-154">Die ID des Vorgangs zu löschen.</span><span class="sxs-lookup"><span data-stu-id="0060f-154">The ID of the task to delete.</span></span>
            </param>
        <param name="taskDeleteOptions">
            <span data-ttu-id="0060f-155">Zusätzliche Parameter für den Vorgang</span><span class="sxs-lookup"><span data-stu-id="0060f-155">Additional parameters for the operation</span></span>
            </param>
        <summary>
            <span data-ttu-id="0060f-156">Löscht eine Aufgabe aus dem angegebenen Auftrag.</span><span class="sxs-lookup"><span data-stu-id="0060f-156">Deletes a task from the specified job.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="0060f-157">Wenn eine Aufgabe gelöscht wird, werden alle Dateien im Verzeichnis auf den Computeknoten, in dem es ausgeführt wurde (unabhängig von der Aufbewahrungsdauer) ebenfalls gelöscht.</span><span class="sxs-lookup"><span data-stu-id="0060f-157">When a task is deleted, all of the files in its directory on the compute node where it ran are also deleted (regardless of the retention time).</span></span> <span data-ttu-id="0060f-158">Für Vorgänge mit mehreren Instanzen gilt der Löschvorgang für den Task synchron an die primäre Aufgabe; Unteraufgaben und die Dateien werden asynchron im Hintergrund gelöscht.</span><span class="sxs-lookup"><span data-stu-id="0060f-158">For multi-instance tasks, the delete task operation applies synchronously to the primary task; subtasks and their files are then deleted asynchronously in the background.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Batch.Protocol.Models.TaskDeleteHeaders&gt; DeleteAsync (this Microsoft.Azure.Batch.Protocol.ITaskOperations operations, string jobId, string taskId, Microsoft.Azure.Batch.Protocol.Models.TaskDeleteOptions taskDeleteOptions = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Batch.Protocol.Models.TaskDeleteHeaders&gt; DeleteAsync(class Microsoft.Azure.Batch.Protocol.ITaskOperations operations, string jobId, string taskId, class Microsoft.Azure.Batch.Protocol.Models.TaskDeleteOptions taskDeleteOptions, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.TaskOperationsExtensions.DeleteAsync(Microsoft.Azure.Batch.Protocol.ITaskOperations,System.String,System.String,Microsoft.Azure.Batch.Protocol.Models.TaskDeleteOptions,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member DeleteAsync : Microsoft.Azure.Batch.Protocol.ITaskOperations * string * string * Microsoft.Azure.Batch.Protocol.Models.TaskDeleteOptions * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Batch.Protocol.Models.TaskDeleteHeaders&gt;" Usage="Microsoft.Azure.Batch.Protocol.TaskOperationsExtensions.DeleteAsync (operations, jobId, taskId, taskDeleteOptions, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Batch.Protocol.TaskOperationsExtensions/&lt;DeleteAsync&gt;d__7))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Batch.Protocol.Models.TaskDeleteHeaders&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Batch.Protocol.ITaskOperations" RefType="this" />
        <Parameter Name="jobId" Type="System.String" />
        <Parameter Name="taskId" Type="System.String" />
        <Parameter Name="taskDeleteOptions" Type="Microsoft.Azure.Batch.Protocol.Models.TaskDeleteOptions" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="0060f-159">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="0060f-159">The operations group for this extension method.</span></span>
            </param>
        <param name="jobId">
            <span data-ttu-id="0060f-160">Die ID des Auftrags, aus dem die Aufgabe zu löschen.</span><span class="sxs-lookup"><span data-stu-id="0060f-160">The ID of the job from which to delete the task.</span></span>
            </param>
        <param name="taskId">
            <span data-ttu-id="0060f-161">Die ID des Vorgangs zu löschen.</span><span class="sxs-lookup"><span data-stu-id="0060f-161">The ID of the task to delete.</span></span>
            </param>
        <param name="taskDeleteOptions">
            <span data-ttu-id="0060f-162">Zusätzliche Parameter für den Vorgang</span><span class="sxs-lookup"><span data-stu-id="0060f-162">Additional parameters for the operation</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="0060f-163">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="0060f-163">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="0060f-164">Löscht eine Aufgabe aus dem angegebenen Auftrag.</span><span class="sxs-lookup"><span data-stu-id="0060f-164">Deletes a task from the specified job.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="0060f-165">Wenn eine Aufgabe gelöscht wird, werden alle Dateien im Verzeichnis auf den Computeknoten, in dem es ausgeführt wurde (unabhängig von der Aufbewahrungsdauer) ebenfalls gelöscht.</span><span class="sxs-lookup"><span data-stu-id="0060f-165">When a task is deleted, all of the files in its directory on the compute node where it ran are also deleted (regardless of the retention time).</span></span> <span data-ttu-id="0060f-166">Für Vorgänge mit mehreren Instanzen gilt der Löschvorgang für den Task synchron an die primäre Aufgabe; Unteraufgaben und die Dateien werden asynchron im Hintergrund gelöscht.</span><span class="sxs-lookup"><span data-stu-id="0060f-166">For multi-instance tasks, the delete task operation applies synchronously to the primary task; subtasks and their files are then deleted asynchronously in the background.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="Get">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Batch.Protocol.Models.CloudTask Get (this Microsoft.Azure.Batch.Protocol.ITaskOperations operations, string jobId, string taskId, Microsoft.Azure.Batch.Protocol.Models.TaskGetOptions taskGetOptions = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Batch.Protocol.Models.CloudTask Get(class Microsoft.Azure.Batch.Protocol.ITaskOperations operations, string jobId, string taskId, class Microsoft.Azure.Batch.Protocol.Models.TaskGetOptions taskGetOptions) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.TaskOperationsExtensions.Get(Microsoft.Azure.Batch.Protocol.ITaskOperations,System.String,System.String,Microsoft.Azure.Batch.Protocol.Models.TaskGetOptions)" />
      <MemberSignature Language="F#" Value="static member Get : Microsoft.Azure.Batch.Protocol.ITaskOperations * string * string * Microsoft.Azure.Batch.Protocol.Models.TaskGetOptions -&gt; Microsoft.Azure.Batch.Protocol.Models.CloudTask" Usage="Microsoft.Azure.Batch.Protocol.TaskOperationsExtensions.Get (operations, jobId, taskId, taskGetOptions)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.Protocol.Models.CloudTask</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Batch.Protocol.ITaskOperations" RefType="this" />
        <Parameter Name="jobId" Type="System.String" />
        <Parameter Name="taskId" Type="System.String" />
        <Parameter Name="taskGetOptions" Type="Microsoft.Azure.Batch.Protocol.Models.TaskGetOptions" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="0060f-167">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="0060f-167">The operations group for this extension method.</span></span>
            </param>
        <param name="jobId">
            <span data-ttu-id="0060f-168">Die ID des Auftrags, der den Task enthält.</span><span class="sxs-lookup"><span data-stu-id="0060f-168">The ID of the job that contains the task.</span></span>
            </param>
        <param name="taskId">
            <span data-ttu-id="0060f-169">Die ID des Tasks, zu dem Informationen abgerufen werden sollen.</span><span class="sxs-lookup"><span data-stu-id="0060f-169">The ID of the task to get information about.</span></span>
            </param>
        <param name="taskGetOptions">
            <span data-ttu-id="0060f-170">Zusätzliche Parameter für den Vorgang</span><span class="sxs-lookup"><span data-stu-id="0060f-170">Additional parameters for the operation</span></span>
            </param>
        <summary>
            <span data-ttu-id="0060f-171">Ruft Informationen über den angegebenen Vorgang ab.</span><span class="sxs-lookup"><span data-stu-id="0060f-171">Gets information about the specified task.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="0060f-172">Für Vorgänge mit mehreren Instanzen Informationen wie z. B. Affinitäts-ID, finden und Sie ExecutionInfo NodeInfo in die primäre Aufgabe.</span><span class="sxs-lookup"><span data-stu-id="0060f-172">For multi-instance tasks, information such as affinityId, executionInfo and nodeInfo refer to the primary task.</span></span> <span data-ttu-id="0060f-173">Verwenden Sie die Liste Unteraufgaben API zum Abrufen von Informationen über Teilvorgänge an.</span><span class="sxs-lookup"><span data-stu-id="0060f-173">Use the list subtasks API to retrieve information about subtasks.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Batch.Protocol.Models.CloudTask&gt; GetAsync (this Microsoft.Azure.Batch.Protocol.ITaskOperations operations, string jobId, string taskId, Microsoft.Azure.Batch.Protocol.Models.TaskGetOptions taskGetOptions = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Batch.Protocol.Models.CloudTask&gt; GetAsync(class Microsoft.Azure.Batch.Protocol.ITaskOperations operations, string jobId, string taskId, class Microsoft.Azure.Batch.Protocol.Models.TaskGetOptions taskGetOptions, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.TaskOperationsExtensions.GetAsync(Microsoft.Azure.Batch.Protocol.ITaskOperations,System.String,System.String,Microsoft.Azure.Batch.Protocol.Models.TaskGetOptions,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetAsync : Microsoft.Azure.Batch.Protocol.ITaskOperations * string * string * Microsoft.Azure.Batch.Protocol.Models.TaskGetOptions * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Batch.Protocol.Models.CloudTask&gt;" Usage="Microsoft.Azure.Batch.Protocol.TaskOperationsExtensions.GetAsync (operations, jobId, taskId, taskGetOptions, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Batch.Protocol.TaskOperationsExtensions/&lt;GetAsync&gt;d__9))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Batch.Protocol.Models.CloudTask&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Batch.Protocol.ITaskOperations" RefType="this" />
        <Parameter Name="jobId" Type="System.String" />
        <Parameter Name="taskId" Type="System.String" />
        <Parameter Name="taskGetOptions" Type="Microsoft.Azure.Batch.Protocol.Models.TaskGetOptions" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="0060f-174">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="0060f-174">The operations group for this extension method.</span></span>
            </param>
        <param name="jobId">
            <span data-ttu-id="0060f-175">Die ID des Auftrags, der den Task enthält.</span><span class="sxs-lookup"><span data-stu-id="0060f-175">The ID of the job that contains the task.</span></span>
            </param>
        <param name="taskId">
            <span data-ttu-id="0060f-176">Die ID des Tasks, zu dem Informationen abgerufen werden sollen.</span><span class="sxs-lookup"><span data-stu-id="0060f-176">The ID of the task to get information about.</span></span>
            </param>
        <param name="taskGetOptions">
            <span data-ttu-id="0060f-177">Zusätzliche Parameter für den Vorgang</span><span class="sxs-lookup"><span data-stu-id="0060f-177">Additional parameters for the operation</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="0060f-178">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="0060f-178">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="0060f-179">Ruft Informationen über den angegebenen Vorgang ab.</span><span class="sxs-lookup"><span data-stu-id="0060f-179">Gets information about the specified task.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="0060f-180">Für Vorgänge mit mehreren Instanzen Informationen wie z. B. Affinitäts-ID, finden und Sie ExecutionInfo NodeInfo in die primäre Aufgabe.</span><span class="sxs-lookup"><span data-stu-id="0060f-180">For multi-instance tasks, information such as affinityId, executionInfo and nodeInfo refer to the primary task.</span></span> <span data-ttu-id="0060f-181">Verwenden Sie die Liste Unteraufgaben API zum Abrufen von Informationen über Teilvorgänge an.</span><span class="sxs-lookup"><span data-stu-id="0060f-181">Use the list subtasks API to retrieve information about subtasks.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="List">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Batch.Protocol.Models.CloudTask&gt; List (this Microsoft.Azure.Batch.Protocol.ITaskOperations operations, string jobId, Microsoft.Azure.Batch.Protocol.Models.TaskListOptions taskListOptions = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Batch.Protocol.Models.CloudTask&gt; List(class Microsoft.Azure.Batch.Protocol.ITaskOperations operations, string jobId, class Microsoft.Azure.Batch.Protocol.Models.TaskListOptions taskListOptions) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.TaskOperationsExtensions.List(Microsoft.Azure.Batch.Protocol.ITaskOperations,System.String,Microsoft.Azure.Batch.Protocol.Models.TaskListOptions)" />
      <MemberSignature Language="F#" Value="static member List : Microsoft.Azure.Batch.Protocol.ITaskOperations * string * Microsoft.Azure.Batch.Protocol.Models.TaskListOptions -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Batch.Protocol.Models.CloudTask&gt;" Usage="Microsoft.Azure.Batch.Protocol.TaskOperationsExtensions.List (operations, jobId, taskListOptions)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Batch.Protocol.Models.CloudTask&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Batch.Protocol.ITaskOperations" RefType="this" />
        <Parameter Name="jobId" Type="System.String" />
        <Parameter Name="taskListOptions" Type="Microsoft.Azure.Batch.Protocol.Models.TaskListOptions" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="0060f-182">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="0060f-182">The operations group for this extension method.</span></span>
            </param>
        <param name="jobId">
            <span data-ttu-id="0060f-183">Die ID des Auftrags.</span><span class="sxs-lookup"><span data-stu-id="0060f-183">The ID of the job.</span></span>
            </param>
        <param name="taskListOptions">
            <span data-ttu-id="0060f-184">Zusätzliche Parameter für den Vorgang</span><span class="sxs-lookup"><span data-stu-id="0060f-184">Additional parameters for the operation</span></span>
            </param>
        <summary>
            <span data-ttu-id="0060f-185">Zeigt eine Liste aller Aufgaben, die dem angegebenen Auftrag zugeordnet sind.</span><span class="sxs-lookup"><span data-stu-id="0060f-185">Lists all of the tasks that are associated with the specified job.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="0060f-186">Für Vorgänge mit mehreren Instanzen Informationen wie z. B. Affinitäts-ID, finden und Sie ExecutionInfo NodeInfo in die primäre Aufgabe.</span><span class="sxs-lookup"><span data-stu-id="0060f-186">For multi-instance tasks, information such as affinityId, executionInfo and nodeInfo refer to the primary task.</span></span> <span data-ttu-id="0060f-187">Verwenden Sie die Liste Unteraufgaben API zum Abrufen von Informationen über Teilvorgänge an.</span><span class="sxs-lookup"><span data-stu-id="0060f-187">Use the list subtasks API to retrieve information about subtasks.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Batch.Protocol.Models.CloudTask&gt;&gt; ListAsync (this Microsoft.Azure.Batch.Protocol.ITaskOperations operations, string jobId, Microsoft.Azure.Batch.Protocol.Models.TaskListOptions taskListOptions = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Batch.Protocol.Models.CloudTask&gt;&gt; ListAsync(class Microsoft.Azure.Batch.Protocol.ITaskOperations operations, string jobId, class Microsoft.Azure.Batch.Protocol.Models.TaskListOptions taskListOptions, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.TaskOperationsExtensions.ListAsync(Microsoft.Azure.Batch.Protocol.ITaskOperations,System.String,Microsoft.Azure.Batch.Protocol.Models.TaskListOptions,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListAsync : Microsoft.Azure.Batch.Protocol.ITaskOperations * string * Microsoft.Azure.Batch.Protocol.Models.TaskListOptions * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Batch.Protocol.Models.CloudTask&gt;&gt;" Usage="Microsoft.Azure.Batch.Protocol.TaskOperationsExtensions.ListAsync (operations, jobId, taskListOptions, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Batch.Protocol.TaskOperationsExtensions/&lt;ListAsync&gt;d__3))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Batch.Protocol.Models.CloudTask&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Batch.Protocol.ITaskOperations" RefType="this" />
        <Parameter Name="jobId" Type="System.String" />
        <Parameter Name="taskListOptions" Type="Microsoft.Azure.Batch.Protocol.Models.TaskListOptions" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="0060f-188">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="0060f-188">The operations group for this extension method.</span></span>
            </param>
        <param name="jobId">
            <span data-ttu-id="0060f-189">Die ID des Auftrags.</span><span class="sxs-lookup"><span data-stu-id="0060f-189">The ID of the job.</span></span>
            </param>
        <param name="taskListOptions">
            <span data-ttu-id="0060f-190">Zusätzliche Parameter für den Vorgang</span><span class="sxs-lookup"><span data-stu-id="0060f-190">Additional parameters for the operation</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="0060f-191">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="0060f-191">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="0060f-192">Zeigt eine Liste aller Aufgaben, die dem angegebenen Auftrag zugeordnet sind.</span><span class="sxs-lookup"><span data-stu-id="0060f-192">Lists all of the tasks that are associated with the specified job.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="0060f-193">Für Vorgänge mit mehreren Instanzen Informationen wie z. B. Affinitäts-ID, finden und Sie ExecutionInfo NodeInfo in die primäre Aufgabe.</span><span class="sxs-lookup"><span data-stu-id="0060f-193">For multi-instance tasks, information such as affinityId, executionInfo and nodeInfo refer to the primary task.</span></span> <span data-ttu-id="0060f-194">Verwenden Sie die Liste Unteraufgaben API zum Abrufen von Informationen über Teilvorgänge an.</span><span class="sxs-lookup"><span data-stu-id="0060f-194">Use the list subtasks API to retrieve information about subtasks.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ListNext">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Batch.Protocol.Models.CloudTask&gt; ListNext (this Microsoft.Azure.Batch.Protocol.ITaskOperations operations, string nextPageLink, Microsoft.Azure.Batch.Protocol.Models.TaskListNextOptions taskListNextOptions = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Batch.Protocol.Models.CloudTask&gt; ListNext(class Microsoft.Azure.Batch.Protocol.ITaskOperations operations, string nextPageLink, class Microsoft.Azure.Batch.Protocol.Models.TaskListNextOptions taskListNextOptions) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.TaskOperationsExtensions.ListNext(Microsoft.Azure.Batch.Protocol.ITaskOperations,System.String,Microsoft.Azure.Batch.Protocol.Models.TaskListNextOptions)" />
      <MemberSignature Language="F#" Value="static member ListNext : Microsoft.Azure.Batch.Protocol.ITaskOperations * string * Microsoft.Azure.Batch.Protocol.Models.TaskListNextOptions -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Batch.Protocol.Models.CloudTask&gt;" Usage="Microsoft.Azure.Batch.Protocol.TaskOperationsExtensions.ListNext (operations, nextPageLink, taskListNextOptions)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Batch.Protocol.Models.CloudTask&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Batch.Protocol.ITaskOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="taskListNextOptions" Type="Microsoft.Azure.Batch.Protocol.Models.TaskListNextOptions" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="0060f-195">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="0060f-195">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="0060f-196">Die "NextLink" aus dem vorherigen erfolgreichen Aufruf List-Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="0060f-196">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="taskListNextOptions">
            <span data-ttu-id="0060f-197">Zusätzliche Parameter für den Vorgang</span><span class="sxs-lookup"><span data-stu-id="0060f-197">Additional parameters for the operation</span></span>
            </param>
        <summary>
            <span data-ttu-id="0060f-198">Zeigt eine Liste aller Aufgaben, die dem angegebenen Auftrag zugeordnet sind.</span><span class="sxs-lookup"><span data-stu-id="0060f-198">Lists all of the tasks that are associated with the specified job.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="0060f-199">Für Vorgänge mit mehreren Instanzen Informationen wie z. B. Affinitäts-ID, finden und Sie ExecutionInfo NodeInfo in die primäre Aufgabe.</span><span class="sxs-lookup"><span data-stu-id="0060f-199">For multi-instance tasks, information such as affinityId, executionInfo and nodeInfo refer to the primary task.</span></span> <span data-ttu-id="0060f-200">Verwenden Sie die Liste Unteraufgaben API zum Abrufen von Informationen über Teilvorgänge an.</span><span class="sxs-lookup"><span data-stu-id="0060f-200">Use the list subtasks API to retrieve information about subtasks.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ListNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Batch.Protocol.Models.CloudTask&gt;&gt; ListNextAsync (this Microsoft.Azure.Batch.Protocol.ITaskOperations operations, string nextPageLink, Microsoft.Azure.Batch.Protocol.Models.TaskListNextOptions taskListNextOptions = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Batch.Protocol.Models.CloudTask&gt;&gt; ListNextAsync(class Microsoft.Azure.Batch.Protocol.ITaskOperations operations, string nextPageLink, class Microsoft.Azure.Batch.Protocol.Models.TaskListNextOptions taskListNextOptions, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.TaskOperationsExtensions.ListNextAsync(Microsoft.Azure.Batch.Protocol.ITaskOperations,System.String,Microsoft.Azure.Batch.Protocol.Models.TaskListNextOptions,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListNextAsync : Microsoft.Azure.Batch.Protocol.ITaskOperations * string * Microsoft.Azure.Batch.Protocol.Models.TaskListNextOptions * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Batch.Protocol.Models.CloudTask&gt;&gt;" Usage="Microsoft.Azure.Batch.Protocol.TaskOperationsExtensions.ListNextAsync (operations, nextPageLink, taskListNextOptions, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Batch.Protocol.TaskOperationsExtensions/&lt;ListNextAsync&gt;d__19))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Batch.Protocol.Models.CloudTask&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Batch.Protocol.ITaskOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="taskListNextOptions" Type="Microsoft.Azure.Batch.Protocol.Models.TaskListNextOptions" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="0060f-201">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="0060f-201">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="0060f-202">Die "NextLink" aus dem vorherigen erfolgreichen Aufruf List-Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="0060f-202">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="taskListNextOptions">
            <span data-ttu-id="0060f-203">Zusätzliche Parameter für den Vorgang</span><span class="sxs-lookup"><span data-stu-id="0060f-203">Additional parameters for the operation</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="0060f-204">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="0060f-204">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="0060f-205">Zeigt eine Liste aller Aufgaben, die dem angegebenen Auftrag zugeordnet sind.</span><span class="sxs-lookup"><span data-stu-id="0060f-205">Lists all of the tasks that are associated with the specified job.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="0060f-206">Für Vorgänge mit mehreren Instanzen Informationen wie z. B. Affinitäts-ID, finden und Sie ExecutionInfo NodeInfo in die primäre Aufgabe.</span><span class="sxs-lookup"><span data-stu-id="0060f-206">For multi-instance tasks, information such as affinityId, executionInfo and nodeInfo refer to the primary task.</span></span> <span data-ttu-id="0060f-207">Verwenden Sie die Liste Unteraufgaben API zum Abrufen von Informationen über Teilvorgänge an.</span><span class="sxs-lookup"><span data-stu-id="0060f-207">Use the list subtasks API to retrieve information about subtasks.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ListSubtasks">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Batch.Protocol.Models.CloudTaskListSubtasksResult ListSubtasks (this Microsoft.Azure.Batch.Protocol.ITaskOperations operations, string jobId, string taskId, Microsoft.Azure.Batch.Protocol.Models.TaskListSubtasksOptions taskListSubtasksOptions = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Batch.Protocol.Models.CloudTaskListSubtasksResult ListSubtasks(class Microsoft.Azure.Batch.Protocol.ITaskOperations operations, string jobId, string taskId, class Microsoft.Azure.Batch.Protocol.Models.TaskListSubtasksOptions taskListSubtasksOptions) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.TaskOperationsExtensions.ListSubtasks(Microsoft.Azure.Batch.Protocol.ITaskOperations,System.String,System.String,Microsoft.Azure.Batch.Protocol.Models.TaskListSubtasksOptions)" />
      <MemberSignature Language="F#" Value="static member ListSubtasks : Microsoft.Azure.Batch.Protocol.ITaskOperations * string * string * Microsoft.Azure.Batch.Protocol.Models.TaskListSubtasksOptions -&gt; Microsoft.Azure.Batch.Protocol.Models.CloudTaskListSubtasksResult" Usage="Microsoft.Azure.Batch.Protocol.TaskOperationsExtensions.ListSubtasks (operations, jobId, taskId, taskListSubtasksOptions)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.Protocol.Models.CloudTaskListSubtasksResult</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Batch.Protocol.ITaskOperations" RefType="this" />
        <Parameter Name="jobId" Type="System.String" />
        <Parameter Name="taskId" Type="System.String" />
        <Parameter Name="taskListSubtasksOptions" Type="Microsoft.Azure.Batch.Protocol.Models.TaskListSubtasksOptions" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="0060f-208">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="0060f-208">The operations group for this extension method.</span></span>
            </param>
        <param name="jobId">
            <span data-ttu-id="0060f-209">Die ID des Auftrags.</span><span class="sxs-lookup"><span data-stu-id="0060f-209">The ID of the job.</span></span>
            </param>
        <param name="taskId">
            <span data-ttu-id="0060f-210">Die ID des Tasks.</span><span class="sxs-lookup"><span data-stu-id="0060f-210">The ID of the task.</span></span>
            </param>
        <param name="taskListSubtasksOptions">
            <span data-ttu-id="0060f-211">Zusätzliche Parameter für den Vorgang</span><span class="sxs-lookup"><span data-stu-id="0060f-211">Additional parameters for the operation</span></span>
            </param>
        <summary>
            <span data-ttu-id="0060f-212">Zeigt eine Liste aller die Unteraufgaben an, die der Aufgabe angegebenen mit mehreren Instanzen zugeordnet sind.</span><span class="sxs-lookup"><span data-stu-id="0060f-212">Lists all of the subtasks that are associated with the specified multi-instance task.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="0060f-213">Wenn der Vorgang nicht um eine Aufgabe mit mehreren Instanzen ist zurück dies eine leere Auflistung.</span><span class="sxs-lookup"><span data-stu-id="0060f-213">If the task is not a multi-instance task then this returns an empty collection.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ListSubtasksAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Batch.Protocol.Models.CloudTaskListSubtasksResult&gt; ListSubtasksAsync (this Microsoft.Azure.Batch.Protocol.ITaskOperations operations, string jobId, string taskId, Microsoft.Azure.Batch.Protocol.Models.TaskListSubtasksOptions taskListSubtasksOptions = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Batch.Protocol.Models.CloudTaskListSubtasksResult&gt; ListSubtasksAsync(class Microsoft.Azure.Batch.Protocol.ITaskOperations operations, string jobId, string taskId, class Microsoft.Azure.Batch.Protocol.Models.TaskListSubtasksOptions taskListSubtasksOptions, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.TaskOperationsExtensions.ListSubtasksAsync(Microsoft.Azure.Batch.Protocol.ITaskOperations,System.String,System.String,Microsoft.Azure.Batch.Protocol.Models.TaskListSubtasksOptions,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListSubtasksAsync : Microsoft.Azure.Batch.Protocol.ITaskOperations * string * string * Microsoft.Azure.Batch.Protocol.Models.TaskListSubtasksOptions * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Batch.Protocol.Models.CloudTaskListSubtasksResult&gt;" Usage="Microsoft.Azure.Batch.Protocol.TaskOperationsExtensions.ListSubtasksAsync (operations, jobId, taskId, taskListSubtasksOptions, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Batch.Protocol.TaskOperationsExtensions/&lt;ListSubtasksAsync&gt;d__13))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Batch.Protocol.Models.CloudTaskListSubtasksResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Batch.Protocol.ITaskOperations" RefType="this" />
        <Parameter Name="jobId" Type="System.String" />
        <Parameter Name="taskId" Type="System.String" />
        <Parameter Name="taskListSubtasksOptions" Type="Microsoft.Azure.Batch.Protocol.Models.TaskListSubtasksOptions" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="0060f-214">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="0060f-214">The operations group for this extension method.</span></span>
            </param>
        <param name="jobId">
            <span data-ttu-id="0060f-215">Die ID des Auftrags.</span><span class="sxs-lookup"><span data-stu-id="0060f-215">The ID of the job.</span></span>
            </param>
        <param name="taskId">
            <span data-ttu-id="0060f-216">Die ID des Tasks.</span><span class="sxs-lookup"><span data-stu-id="0060f-216">The ID of the task.</span></span>
            </param>
        <param name="taskListSubtasksOptions">
            <span data-ttu-id="0060f-217">Zusätzliche Parameter für den Vorgang</span><span class="sxs-lookup"><span data-stu-id="0060f-217">Additional parameters for the operation</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="0060f-218">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="0060f-218">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="0060f-219">Zeigt eine Liste aller die Unteraufgaben an, die der Aufgabe angegebenen mit mehreren Instanzen zugeordnet sind.</span><span class="sxs-lookup"><span data-stu-id="0060f-219">Lists all of the subtasks that are associated with the specified multi-instance task.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="0060f-220">Wenn der Vorgang nicht um eine Aufgabe mit mehreren Instanzen ist zurück dies eine leere Auflistung.</span><span class="sxs-lookup"><span data-stu-id="0060f-220">If the task is not a multi-instance task then this returns an empty collection.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="Reactivate">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Batch.Protocol.Models.TaskReactivateHeaders Reactivate (this Microsoft.Azure.Batch.Protocol.ITaskOperations operations, string jobId, string taskId, Microsoft.Azure.Batch.Protocol.Models.TaskReactivateOptions taskReactivateOptions = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Batch.Protocol.Models.TaskReactivateHeaders Reactivate(class Microsoft.Azure.Batch.Protocol.ITaskOperations operations, string jobId, string taskId, class Microsoft.Azure.Batch.Protocol.Models.TaskReactivateOptions taskReactivateOptions) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.TaskOperationsExtensions.Reactivate(Microsoft.Azure.Batch.Protocol.ITaskOperations,System.String,System.String,Microsoft.Azure.Batch.Protocol.Models.TaskReactivateOptions)" />
      <MemberSignature Language="F#" Value="static member Reactivate : Microsoft.Azure.Batch.Protocol.ITaskOperations * string * string * Microsoft.Azure.Batch.Protocol.Models.TaskReactivateOptions -&gt; Microsoft.Azure.Batch.Protocol.Models.TaskReactivateHeaders" Usage="Microsoft.Azure.Batch.Protocol.TaskOperationsExtensions.Reactivate (operations, jobId, taskId, taskReactivateOptions)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.Protocol.Models.TaskReactivateHeaders</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Batch.Protocol.ITaskOperations" RefType="this" />
        <Parameter Name="jobId" Type="System.String" />
        <Parameter Name="taskId" Type="System.String" />
        <Parameter Name="taskReactivateOptions" Type="Microsoft.Azure.Batch.Protocol.Models.TaskReactivateOptions" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="0060f-221">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="0060f-221">The operations group for this extension method.</span></span>
            </param>
        <param name="jobId">
            <span data-ttu-id="0060f-222">Die ID des Auftrags, der den Task enthält.</span><span class="sxs-lookup"><span data-stu-id="0060f-222">The ID of the job containing the task.</span></span>
            </param>
        <param name="taskId">
            <span data-ttu-id="0060f-223">Die ID des Tasks zu reaktivieren.</span><span class="sxs-lookup"><span data-stu-id="0060f-223">The ID of the task to reactivate.</span></span>
            </param>
        <param name="taskReactivateOptions">
            <span data-ttu-id="0060f-224">Zusätzliche Parameter für den Vorgang</span><span class="sxs-lookup"><span data-stu-id="0060f-224">Additional parameters for the operation</span></span>
            </param>
        <summary>
            <span data-ttu-id="0060f-225">Reaktiviert eine Aufgabe, sodass es erneut ausführen, auch wenn die Anzahl der Wiederholungsversuche ausgeschöpft ist.</span><span class="sxs-lookup"><span data-stu-id="0060f-225">Reactivates a task, allowing it to run again even if its retry count has been exhausted.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="0060f-226">Reaktivierung wird eine Aufgabe berechtigt ist, bis die maximale Anzahl von Wiederholungsversuchen zum Vorgang wiederholt werden.</span><span class="sxs-lookup"><span data-stu-id="0060f-226">Reactivation makes a task eligible to be retried again up to its maximum retry count.</span></span> <span data-ttu-id="0060f-227">Der Status der Aufgabe wird in aktiv geändert.</span><span class="sxs-lookup"><span data-stu-id="0060f-227">The task's state is changed to active.</span></span> <span data-ttu-id="0060f-228">Wie die Aufgabe nicht mehr in den Zustand abgeschlossen ist, ist keine vorherigen beenden Code oder das Fehlschlagen der Informationen nach der Reaktivierung nicht mehr verfügbar.</span><span class="sxs-lookup"><span data-stu-id="0060f-228">As the task is no longer in the completed state, any previous exit code or failure information is no longer available after reactivation.</span></span> <span data-ttu-id="0060f-229">Jedes Mal, wenn eine Aufgabe erneut aktiviert wird, wird die Wiederholungsanzahl auf 0 zurückgesetzt.</span><span class="sxs-lookup"><span data-stu-id="0060f-229">Each time a task is reactivated, its retry count is reset to 0.</span></span> <span data-ttu-id="0060f-230">Reaktivierung fehl für Aufgaben, die nicht abgeschlossen oder zuvor erfolgreich (mit Exitcode 0) abgeschlossen.</span><span class="sxs-lookup"><span data-stu-id="0060f-230">Reactivation will fail for tasks that are not completed or that previously completed successfully (with an exit code of 0).</span></span> <span data-ttu-id="0060f-231">Darüber hinaus schlägt er fehl, wenn der Auftrag abgeschlossen wurde (oder beenden oder löschen).</span><span class="sxs-lookup"><span data-stu-id="0060f-231">Additionally, it will fail if the job has completed (or is terminating or deleting).</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ReactivateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Batch.Protocol.Models.TaskReactivateHeaders&gt; ReactivateAsync (this Microsoft.Azure.Batch.Protocol.ITaskOperations operations, string jobId, string taskId, Microsoft.Azure.Batch.Protocol.Models.TaskReactivateOptions taskReactivateOptions = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Batch.Protocol.Models.TaskReactivateHeaders&gt; ReactivateAsync(class Microsoft.Azure.Batch.Protocol.ITaskOperations operations, string jobId, string taskId, class Microsoft.Azure.Batch.Protocol.Models.TaskReactivateOptions taskReactivateOptions, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.TaskOperationsExtensions.ReactivateAsync(Microsoft.Azure.Batch.Protocol.ITaskOperations,System.String,System.String,Microsoft.Azure.Batch.Protocol.Models.TaskReactivateOptions,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ReactivateAsync : Microsoft.Azure.Batch.Protocol.ITaskOperations * string * string * Microsoft.Azure.Batch.Protocol.Models.TaskReactivateOptions * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Batch.Protocol.Models.TaskReactivateHeaders&gt;" Usage="Microsoft.Azure.Batch.Protocol.TaskOperationsExtensions.ReactivateAsync (operations, jobId, taskId, taskReactivateOptions, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Batch.Protocol.TaskOperationsExtensions/&lt;ReactivateAsync&gt;d__17))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Batch.Protocol.Models.TaskReactivateHeaders&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Batch.Protocol.ITaskOperations" RefType="this" />
        <Parameter Name="jobId" Type="System.String" />
        <Parameter Name="taskId" Type="System.String" />
        <Parameter Name="taskReactivateOptions" Type="Microsoft.Azure.Batch.Protocol.Models.TaskReactivateOptions" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="0060f-232">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="0060f-232">The operations group for this extension method.</span></span>
            </param>
        <param name="jobId">
            <span data-ttu-id="0060f-233">Die ID des Auftrags, der den Task enthält.</span><span class="sxs-lookup"><span data-stu-id="0060f-233">The ID of the job containing the task.</span></span>
            </param>
        <param name="taskId">
            <span data-ttu-id="0060f-234">Die ID des Tasks zu reaktivieren.</span><span class="sxs-lookup"><span data-stu-id="0060f-234">The ID of the task to reactivate.</span></span>
            </param>
        <param name="taskReactivateOptions">
            <span data-ttu-id="0060f-235">Zusätzliche Parameter für den Vorgang</span><span class="sxs-lookup"><span data-stu-id="0060f-235">Additional parameters for the operation</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="0060f-236">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="0060f-236">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="0060f-237">Reaktiviert eine Aufgabe, sodass es erneut ausführen, auch wenn die Anzahl der Wiederholungsversuche ausgeschöpft ist.</span><span class="sxs-lookup"><span data-stu-id="0060f-237">Reactivates a task, allowing it to run again even if its retry count has been exhausted.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="0060f-238">Reaktivierung wird eine Aufgabe berechtigt ist, bis die maximale Anzahl von Wiederholungsversuchen zum Vorgang wiederholt werden.</span><span class="sxs-lookup"><span data-stu-id="0060f-238">Reactivation makes a task eligible to be retried again up to its maximum retry count.</span></span> <span data-ttu-id="0060f-239">Der Status der Aufgabe wird in aktiv geändert.</span><span class="sxs-lookup"><span data-stu-id="0060f-239">The task's state is changed to active.</span></span> <span data-ttu-id="0060f-240">Wie die Aufgabe nicht mehr in den Zustand abgeschlossen ist, ist keine vorherigen beenden Code oder das Fehlschlagen der Informationen nach der Reaktivierung nicht mehr verfügbar.</span><span class="sxs-lookup"><span data-stu-id="0060f-240">As the task is no longer in the completed state, any previous exit code or failure information is no longer available after reactivation.</span></span> <span data-ttu-id="0060f-241">Jedes Mal, wenn eine Aufgabe erneut aktiviert wird, wird die Wiederholungsanzahl auf 0 zurückgesetzt.</span><span class="sxs-lookup"><span data-stu-id="0060f-241">Each time a task is reactivated, its retry count is reset to 0.</span></span> <span data-ttu-id="0060f-242">Reaktivierung fehl für Aufgaben, die nicht abgeschlossen oder zuvor erfolgreich (mit Exitcode 0) abgeschlossen.</span><span class="sxs-lookup"><span data-stu-id="0060f-242">Reactivation will fail for tasks that are not completed or that previously completed successfully (with an exit code of 0).</span></span> <span data-ttu-id="0060f-243">Darüber hinaus schlägt er fehl, wenn der Auftrag abgeschlossen wurde (oder beenden oder löschen).</span><span class="sxs-lookup"><span data-stu-id="0060f-243">Additionally, it will fail if the job has completed (or is terminating or deleting).</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="Terminate">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Batch.Protocol.Models.TaskTerminateHeaders Terminate (this Microsoft.Azure.Batch.Protocol.ITaskOperations operations, string jobId, string taskId, Microsoft.Azure.Batch.Protocol.Models.TaskTerminateOptions taskTerminateOptions = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Batch.Protocol.Models.TaskTerminateHeaders Terminate(class Microsoft.Azure.Batch.Protocol.ITaskOperations operations, string jobId, string taskId, class Microsoft.Azure.Batch.Protocol.Models.TaskTerminateOptions taskTerminateOptions) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.TaskOperationsExtensions.Terminate(Microsoft.Azure.Batch.Protocol.ITaskOperations,System.String,System.String,Microsoft.Azure.Batch.Protocol.Models.TaskTerminateOptions)" />
      <MemberSignature Language="F#" Value="static member Terminate : Microsoft.Azure.Batch.Protocol.ITaskOperations * string * string * Microsoft.Azure.Batch.Protocol.Models.TaskTerminateOptions -&gt; Microsoft.Azure.Batch.Protocol.Models.TaskTerminateHeaders" Usage="Microsoft.Azure.Batch.Protocol.TaskOperationsExtensions.Terminate (operations, jobId, taskId, taskTerminateOptions)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.Protocol.Models.TaskTerminateHeaders</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Batch.Protocol.ITaskOperations" RefType="this" />
        <Parameter Name="jobId" Type="System.String" />
        <Parameter Name="taskId" Type="System.String" />
        <Parameter Name="taskTerminateOptions" Type="Microsoft.Azure.Batch.Protocol.Models.TaskTerminateOptions" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="0060f-244">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="0060f-244">The operations group for this extension method.</span></span>
            </param>
        <param name="jobId">
            <span data-ttu-id="0060f-245">Die ID des Auftrags, der den Task enthält.</span><span class="sxs-lookup"><span data-stu-id="0060f-245">The ID of the job containing the task.</span></span>
            </param>
        <param name="taskId">
            <span data-ttu-id="0060f-246">Die ID des Tasks beendet werden soll.</span><span class="sxs-lookup"><span data-stu-id="0060f-246">The ID of the task to terminate.</span></span>
            </param>
        <param name="taskTerminateOptions">
            <span data-ttu-id="0060f-247">Zusätzliche Parameter für den Vorgang</span><span class="sxs-lookup"><span data-stu-id="0060f-247">Additional parameters for the operation</span></span>
            </param>
        <summary>
            <span data-ttu-id="0060f-248">Beendet die angegebene Aufgabe an.</span><span class="sxs-lookup"><span data-stu-id="0060f-248">Terminates the specified task.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="0060f-249">Wenn die Aufgabe beendet wurde, wird in den abgeschlossenen Zustand verschoben.</span><span class="sxs-lookup"><span data-stu-id="0060f-249">When the task has been terminated, it moves to the completed state.</span></span> <span data-ttu-id="0060f-250">Für Vorgänge mit mehreren Instanzen gilt der Vorgang "Beenden" Task synchron an die primäre Aufgabe. Unteraufgaben werden dann asynchron im Hintergrund beendet.</span><span class="sxs-lookup"><span data-stu-id="0060f-250">For multi-instance tasks, the terminate task operation applies synchronously to the primary task; subtasks are then terminated asynchronously in the background.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="TerminateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Batch.Protocol.Models.TaskTerminateHeaders&gt; TerminateAsync (this Microsoft.Azure.Batch.Protocol.ITaskOperations operations, string jobId, string taskId, Microsoft.Azure.Batch.Protocol.Models.TaskTerminateOptions taskTerminateOptions = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Batch.Protocol.Models.TaskTerminateHeaders&gt; TerminateAsync(class Microsoft.Azure.Batch.Protocol.ITaskOperations operations, string jobId, string taskId, class Microsoft.Azure.Batch.Protocol.Models.TaskTerminateOptions taskTerminateOptions, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.TaskOperationsExtensions.TerminateAsync(Microsoft.Azure.Batch.Protocol.ITaskOperations,System.String,System.String,Microsoft.Azure.Batch.Protocol.Models.TaskTerminateOptions,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member TerminateAsync : Microsoft.Azure.Batch.Protocol.ITaskOperations * string * string * Microsoft.Azure.Batch.Protocol.Models.TaskTerminateOptions * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Batch.Protocol.Models.TaskTerminateHeaders&gt;" Usage="Microsoft.Azure.Batch.Protocol.TaskOperationsExtensions.TerminateAsync (operations, jobId, taskId, taskTerminateOptions, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Batch.Protocol.TaskOperationsExtensions/&lt;TerminateAsync&gt;d__15))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Batch.Protocol.Models.TaskTerminateHeaders&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Batch.Protocol.ITaskOperations" RefType="this" />
        <Parameter Name="jobId" Type="System.String" />
        <Parameter Name="taskId" Type="System.String" />
        <Parameter Name="taskTerminateOptions" Type="Microsoft.Azure.Batch.Protocol.Models.TaskTerminateOptions" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="0060f-251">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="0060f-251">The operations group for this extension method.</span></span>
            </param>
        <param name="jobId">
            <span data-ttu-id="0060f-252">Die ID des Auftrags, der den Task enthält.</span><span class="sxs-lookup"><span data-stu-id="0060f-252">The ID of the job containing the task.</span></span>
            </param>
        <param name="taskId">
            <span data-ttu-id="0060f-253">Die ID des Tasks beendet werden soll.</span><span class="sxs-lookup"><span data-stu-id="0060f-253">The ID of the task to terminate.</span></span>
            </param>
        <param name="taskTerminateOptions">
            <span data-ttu-id="0060f-254">Zusätzliche Parameter für den Vorgang</span><span class="sxs-lookup"><span data-stu-id="0060f-254">Additional parameters for the operation</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="0060f-255">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="0060f-255">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="0060f-256">Beendet die angegebene Aufgabe an.</span><span class="sxs-lookup"><span data-stu-id="0060f-256">Terminates the specified task.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="0060f-257">Wenn die Aufgabe beendet wurde, wird in den abgeschlossenen Zustand verschoben.</span><span class="sxs-lookup"><span data-stu-id="0060f-257">When the task has been terminated, it moves to the completed state.</span></span> <span data-ttu-id="0060f-258">Für Vorgänge mit mehreren Instanzen gilt der Vorgang "Beenden" Task synchron an die primäre Aufgabe. Unteraufgaben werden dann asynchron im Hintergrund beendet.</span><span class="sxs-lookup"><span data-stu-id="0060f-258">For multi-instance tasks, the terminate task operation applies synchronously to the primary task; subtasks are then terminated asynchronously in the background.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="Update">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Batch.Protocol.Models.TaskUpdateHeaders Update (this Microsoft.Azure.Batch.Protocol.ITaskOperations operations, string jobId, string taskId, Microsoft.Azure.Batch.Protocol.Models.TaskConstraints constraints = null, Microsoft.Azure.Batch.Protocol.Models.TaskUpdateOptions taskUpdateOptions = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Batch.Protocol.Models.TaskUpdateHeaders Update(class Microsoft.Azure.Batch.Protocol.ITaskOperations operations, string jobId, string taskId, class Microsoft.Azure.Batch.Protocol.Models.TaskConstraints constraints, class Microsoft.Azure.Batch.Protocol.Models.TaskUpdateOptions taskUpdateOptions) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.TaskOperationsExtensions.Update(Microsoft.Azure.Batch.Protocol.ITaskOperations,System.String,System.String,Microsoft.Azure.Batch.Protocol.Models.TaskConstraints,Microsoft.Azure.Batch.Protocol.Models.TaskUpdateOptions)" />
      <MemberSignature Language="F#" Value="static member Update : Microsoft.Azure.Batch.Protocol.ITaskOperations * string * string * Microsoft.Azure.Batch.Protocol.Models.TaskConstraints * Microsoft.Azure.Batch.Protocol.Models.TaskUpdateOptions -&gt; Microsoft.Azure.Batch.Protocol.Models.TaskUpdateHeaders" Usage="Microsoft.Azure.Batch.Protocol.TaskOperationsExtensions.Update (operations, jobId, taskId, constraints, taskUpdateOptions)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.Protocol.Models.TaskUpdateHeaders</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Batch.Protocol.ITaskOperations" RefType="this" />
        <Parameter Name="jobId" Type="System.String" />
        <Parameter Name="taskId" Type="System.String" />
        <Parameter Name="constraints" Type="Microsoft.Azure.Batch.Protocol.Models.TaskConstraints" />
        <Parameter Name="taskUpdateOptions" Type="Microsoft.Azure.Batch.Protocol.Models.TaskUpdateOptions" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="0060f-259">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="0060f-259">The operations group for this extension method.</span></span>
            </param>
        <param name="jobId">
            <span data-ttu-id="0060f-260">Die ID des Auftrags, der den Task enthält.</span><span class="sxs-lookup"><span data-stu-id="0060f-260">The ID of the job containing the task.</span></span>
            </param>
        <param name="taskId">
            <span data-ttu-id="0060f-261">Die ID des Tasks aktualisiert.</span><span class="sxs-lookup"><span data-stu-id="0060f-261">The ID of the task to update.</span></span>
            </param>
        <param name="constraints">
            <span data-ttu-id="0060f-262">Einschränkungen, die für diese Aufgabe gelten.</span><span class="sxs-lookup"><span data-stu-id="0060f-262">Constraints that apply to this task.</span></span> <span data-ttu-id="0060f-263">Wenn nicht angegeben, wird die Aufgabe das Default-Einschränkungen angegeben.</span><span class="sxs-lookup"><span data-stu-id="0060f-263">If omitted, the task is given the default constraints.</span></span> <span data-ttu-id="0060f-264">Für Vorgänge mit mehreren Instanzen aktualisieren die Aufbewahrungsdauer gilt nur für die primäre Aufgabe und Teilvorgänge nicht.</span><span class="sxs-lookup"><span data-stu-id="0060f-264">For multi-instance tasks, updating the retention time applies only to the primary task and not subtasks.</span></span>
            </param>
        <param name="taskUpdateOptions">
            <span data-ttu-id="0060f-265">Zusätzliche Parameter für den Vorgang</span><span class="sxs-lookup"><span data-stu-id="0060f-265">Additional parameters for the operation</span></span>
            </param>
        <summary>
            <span data-ttu-id="0060f-266">Aktualisiert die Eigenschaften der angegebenen Aufgabe.</span><span class="sxs-lookup"><span data-stu-id="0060f-266">Updates the properties of the specified task.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UpdateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Batch.Protocol.Models.TaskUpdateHeaders&gt; UpdateAsync (this Microsoft.Azure.Batch.Protocol.ITaskOperations operations, string jobId, string taskId, Microsoft.Azure.Batch.Protocol.Models.TaskConstraints constraints = null, Microsoft.Azure.Batch.Protocol.Models.TaskUpdateOptions taskUpdateOptions = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Batch.Protocol.Models.TaskUpdateHeaders&gt; UpdateAsync(class Microsoft.Azure.Batch.Protocol.ITaskOperations operations, string jobId, string taskId, class Microsoft.Azure.Batch.Protocol.Models.TaskConstraints constraints, class Microsoft.Azure.Batch.Protocol.Models.TaskUpdateOptions taskUpdateOptions, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.TaskOperationsExtensions.UpdateAsync(Microsoft.Azure.Batch.Protocol.ITaskOperations,System.String,System.String,Microsoft.Azure.Batch.Protocol.Models.TaskConstraints,Microsoft.Azure.Batch.Protocol.Models.TaskUpdateOptions,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member UpdateAsync : Microsoft.Azure.Batch.Protocol.ITaskOperations * string * string * Microsoft.Azure.Batch.Protocol.Models.TaskConstraints * Microsoft.Azure.Batch.Protocol.Models.TaskUpdateOptions * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Batch.Protocol.Models.TaskUpdateHeaders&gt;" Usage="Microsoft.Azure.Batch.Protocol.TaskOperationsExtensions.UpdateAsync (operations, jobId, taskId, constraints, taskUpdateOptions, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Batch.Protocol.TaskOperationsExtensions/&lt;UpdateAsync&gt;d__11))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Batch.Protocol.Models.TaskUpdateHeaders&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Batch.Protocol.ITaskOperations" RefType="this" />
        <Parameter Name="jobId" Type="System.String" />
        <Parameter Name="taskId" Type="System.String" />
        <Parameter Name="constraints" Type="Microsoft.Azure.Batch.Protocol.Models.TaskConstraints" />
        <Parameter Name="taskUpdateOptions" Type="Microsoft.Azure.Batch.Protocol.Models.TaskUpdateOptions" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="0060f-267">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="0060f-267">The operations group for this extension method.</span></span>
            </param>
        <param name="jobId">
            <span data-ttu-id="0060f-268">Die ID des Auftrags, der den Task enthält.</span><span class="sxs-lookup"><span data-stu-id="0060f-268">The ID of the job containing the task.</span></span>
            </param>
        <param name="taskId">
            <span data-ttu-id="0060f-269">Die ID des Tasks aktualisiert.</span><span class="sxs-lookup"><span data-stu-id="0060f-269">The ID of the task to update.</span></span>
            </param>
        <param name="constraints">
            <span data-ttu-id="0060f-270">Einschränkungen, die für diese Aufgabe gelten.</span><span class="sxs-lookup"><span data-stu-id="0060f-270">Constraints that apply to this task.</span></span> <span data-ttu-id="0060f-271">Wenn nicht angegeben, wird die Aufgabe das Default-Einschränkungen angegeben.</span><span class="sxs-lookup"><span data-stu-id="0060f-271">If omitted, the task is given the default constraints.</span></span> <span data-ttu-id="0060f-272">Für Vorgänge mit mehreren Instanzen aktualisieren die Aufbewahrungsdauer gilt nur für die primäre Aufgabe und Teilvorgänge nicht.</span><span class="sxs-lookup"><span data-stu-id="0060f-272">For multi-instance tasks, updating the retention time applies only to the primary task and not subtasks.</span></span>
            </param>
        <param name="taskUpdateOptions">
            <span data-ttu-id="0060f-273">Zusätzliche Parameter für den Vorgang</span><span class="sxs-lookup"><span data-stu-id="0060f-273">Additional parameters for the operation</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="0060f-274">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="0060f-274">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="0060f-275">Aktualisiert die Eigenschaften der angegebenen Aufgabe.</span><span class="sxs-lookup"><span data-stu-id="0060f-275">Updates the properties of the specified task.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>