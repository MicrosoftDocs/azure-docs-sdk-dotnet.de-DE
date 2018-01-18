<Type Name="JobOperationsExtensions" FullName="Microsoft.Azure.Batch.Protocol.JobOperationsExtensions">
  <TypeSignature Language="C#" Value="public static class JobOperationsExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit JobOperationsExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Batch.Protocol.JobOperationsExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module JobOperationsExtensions" />
  <TypeSignature Language="F#" Value="type JobOperationsExtensions = class" />
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
            <span data-ttu-id="b12dc-101">Erweiterungsmethoden für JobOperations.</span><span class="sxs-lookup"><span data-stu-id="b12dc-101">Extension methods for JobOperations.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="Add">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Batch.Protocol.Models.JobAddHeaders Add (this Microsoft.Azure.Batch.Protocol.IJobOperations operations, Microsoft.Azure.Batch.Protocol.Models.JobAddParameter job, Microsoft.Azure.Batch.Protocol.Models.JobAddOptions jobAddOptions = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Batch.Protocol.Models.JobAddHeaders Add(class Microsoft.Azure.Batch.Protocol.IJobOperations operations, class Microsoft.Azure.Batch.Protocol.Models.JobAddParameter job, class Microsoft.Azure.Batch.Protocol.Models.JobAddOptions jobAddOptions) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.JobOperationsExtensions.Add(Microsoft.Azure.Batch.Protocol.IJobOperations,Microsoft.Azure.Batch.Protocol.Models.JobAddParameter,Microsoft.Azure.Batch.Protocol.Models.JobAddOptions)" />
      <MemberSignature Language="F#" Value="static member Add : Microsoft.Azure.Batch.Protocol.IJobOperations * Microsoft.Azure.Batch.Protocol.Models.JobAddParameter * Microsoft.Azure.Batch.Protocol.Models.JobAddOptions -&gt; Microsoft.Azure.Batch.Protocol.Models.JobAddHeaders" Usage="Microsoft.Azure.Batch.Protocol.JobOperationsExtensions.Add (operations, job, jobAddOptions)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.Protocol.Models.JobAddHeaders</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Batch.Protocol.IJobOperations" RefType="this" />
        <Parameter Name="job" Type="Microsoft.Azure.Batch.Protocol.Models.JobAddParameter" />
        <Parameter Name="jobAddOptions" Type="Microsoft.Azure.Batch.Protocol.Models.JobAddOptions" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="b12dc-102">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="b12dc-102">The operations group for this extension method.</span></span>
            </param>
        <param name="job">
            <span data-ttu-id="b12dc-103">Der Auftrag hinzugefügt werden.</span><span class="sxs-lookup"><span data-stu-id="b12dc-103">The job to be added.</span></span>
            </param>
        <param name="jobAddOptions">
            <span data-ttu-id="b12dc-104">Zusätzliche Parameter für den Vorgang</span><span class="sxs-lookup"><span data-stu-id="b12dc-104">Additional parameters for the operation</span></span>
            </param>
        <summary>
            <span data-ttu-id="b12dc-105">Das angegebene Konto hinzugefügt einen Auftrag.</span><span class="sxs-lookup"><span data-stu-id="b12dc-105">Adds a job to the specified account.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="b12dc-106">Der Batch-Dienst unterstützt zwei Möglichkeiten, die Arbeit, die im Rahmen eines Auftrags zu steuern.</span><span class="sxs-lookup"><span data-stu-id="b12dc-106">The Batch service supports two ways to control the work done as part of a job.</span></span> <span data-ttu-id="b12dc-107">In der ersten Methode gibt der Benutzer eine Auftrags-Manager-Aufgabe.</span><span class="sxs-lookup"><span data-stu-id="b12dc-107">In the first approach, the user specifies a Job Manager task.</span></span> <span data-ttu-id="b12dc-108">Der Batch-Dienst startet diese Aufgabe aus, wenn er beim Starten des Auftrags bereit ist.</span><span class="sxs-lookup"><span data-stu-id="b12dc-108">The Batch service launches this task when it is ready to start the job.</span></span> <span data-ttu-id="b12dc-109">Die Auftrags-Manager-Aufgabe steuert alle anderen Aufgaben, die unter dieser Auftrag ausgeführt wird, über die Task-APIs.</span><span class="sxs-lookup"><span data-stu-id="b12dc-109">The Job Manager task controls all other tasks that run under this job, by using the Task APIs.</span></span> <span data-ttu-id="b12dc-110">Bei der zweiten Methode steuert der Benutzer die Ausführung von Aufgaben unter einem aktiven Auftrag direkt über die Task-APIs.</span><span class="sxs-lookup"><span data-stu-id="b12dc-110">In the second approach, the user directly controls the execution of tasks under an active job, by using the Task APIs.</span></span> <span data-ttu-id="b12dc-111">Beachten Sie außerdem: beim Benennen von Aufträgen zu vermeiden, darunter vertrauliche Daten wie Benutzernamen oder für den geheimen Projektnamen.</span><span class="sxs-lookup"><span data-stu-id="b12dc-111">Also note: when naming jobs, avoid including sensitive information such as user names or secret project names.</span></span> <span data-ttu-id="b12dc-112">Diese Informationen erscheinen im Telemetrie-Protokolle an Microsoft Support-Mitarbeiter zugegriffen werden kann.</span><span class="sxs-lookup"><span data-stu-id="b12dc-112">This information may appear in telemetry logs accessible to Microsoft Support engineers.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="AddAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Batch.Protocol.Models.JobAddHeaders&gt; AddAsync (this Microsoft.Azure.Batch.Protocol.IJobOperations operations, Microsoft.Azure.Batch.Protocol.Models.JobAddParameter job, Microsoft.Azure.Batch.Protocol.Models.JobAddOptions jobAddOptions = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Batch.Protocol.Models.JobAddHeaders&gt; AddAsync(class Microsoft.Azure.Batch.Protocol.IJobOperations operations, class Microsoft.Azure.Batch.Protocol.Models.JobAddParameter job, class Microsoft.Azure.Batch.Protocol.Models.JobAddOptions jobAddOptions, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.JobOperationsExtensions.AddAsync(Microsoft.Azure.Batch.Protocol.IJobOperations,Microsoft.Azure.Batch.Protocol.Models.JobAddParameter,Microsoft.Azure.Batch.Protocol.Models.JobAddOptions,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member AddAsync : Microsoft.Azure.Batch.Protocol.IJobOperations * Microsoft.Azure.Batch.Protocol.Models.JobAddParameter * Microsoft.Azure.Batch.Protocol.Models.JobAddOptions * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Batch.Protocol.Models.JobAddHeaders&gt;" Usage="Microsoft.Azure.Batch.Protocol.JobOperationsExtensions.AddAsync (operations, job, jobAddOptions, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Batch.Protocol.JobOperationsExtensions/&lt;AddAsync&gt;d__17))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Batch.Protocol.Models.JobAddHeaders&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Batch.Protocol.IJobOperations" RefType="this" />
        <Parameter Name="job" Type="Microsoft.Azure.Batch.Protocol.Models.JobAddParameter" />
        <Parameter Name="jobAddOptions" Type="Microsoft.Azure.Batch.Protocol.Models.JobAddOptions" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="b12dc-113">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="b12dc-113">The operations group for this extension method.</span></span>
            </param>
        <param name="job">
            <span data-ttu-id="b12dc-114">Der Auftrag hinzugefügt werden.</span><span class="sxs-lookup"><span data-stu-id="b12dc-114">The job to be added.</span></span>
            </param>
        <param name="jobAddOptions">
            <span data-ttu-id="b12dc-115">Zusätzliche Parameter für den Vorgang</span><span class="sxs-lookup"><span data-stu-id="b12dc-115">Additional parameters for the operation</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="b12dc-116">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="b12dc-116">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="b12dc-117">Das angegebene Konto hinzugefügt einen Auftrag.</span><span class="sxs-lookup"><span data-stu-id="b12dc-117">Adds a job to the specified account.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="b12dc-118">Der Batch-Dienst unterstützt zwei Möglichkeiten, die Arbeit, die im Rahmen eines Auftrags zu steuern.</span><span class="sxs-lookup"><span data-stu-id="b12dc-118">The Batch service supports two ways to control the work done as part of a job.</span></span> <span data-ttu-id="b12dc-119">In der ersten Methode gibt der Benutzer eine Auftrags-Manager-Aufgabe.</span><span class="sxs-lookup"><span data-stu-id="b12dc-119">In the first approach, the user specifies a Job Manager task.</span></span> <span data-ttu-id="b12dc-120">Der Batch-Dienst startet diese Aufgabe aus, wenn er beim Starten des Auftrags bereit ist.</span><span class="sxs-lookup"><span data-stu-id="b12dc-120">The Batch service launches this task when it is ready to start the job.</span></span> <span data-ttu-id="b12dc-121">Die Auftrags-Manager-Aufgabe steuert alle anderen Aufgaben, die unter dieser Auftrag ausgeführt wird, über die Task-APIs.</span><span class="sxs-lookup"><span data-stu-id="b12dc-121">The Job Manager task controls all other tasks that run under this job, by using the Task APIs.</span></span> <span data-ttu-id="b12dc-122">Bei der zweiten Methode steuert der Benutzer die Ausführung von Aufgaben unter einem aktiven Auftrag direkt über die Task-APIs.</span><span class="sxs-lookup"><span data-stu-id="b12dc-122">In the second approach, the user directly controls the execution of tasks under an active job, by using the Task APIs.</span></span> <span data-ttu-id="b12dc-123">Beachten Sie außerdem: beim Benennen von Aufträgen zu vermeiden, darunter vertrauliche Daten wie Benutzernamen oder für den geheimen Projektnamen.</span><span class="sxs-lookup"><span data-stu-id="b12dc-123">Also note: when naming jobs, avoid including sensitive information such as user names or secret project names.</span></span> <span data-ttu-id="b12dc-124">Diese Informationen erscheinen im Telemetrie-Protokolle an Microsoft Support-Mitarbeiter zugegriffen werden kann.</span><span class="sxs-lookup"><span data-stu-id="b12dc-124">This information may appear in telemetry logs accessible to Microsoft Support engineers.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="Delete">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Batch.Protocol.Models.JobDeleteHeaders Delete (this Microsoft.Azure.Batch.Protocol.IJobOperations operations, string jobId, Microsoft.Azure.Batch.Protocol.Models.JobDeleteOptions jobDeleteOptions = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Batch.Protocol.Models.JobDeleteHeaders Delete(class Microsoft.Azure.Batch.Protocol.IJobOperations operations, string jobId, class Microsoft.Azure.Batch.Protocol.Models.JobDeleteOptions jobDeleteOptions) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.JobOperationsExtensions.Delete(Microsoft.Azure.Batch.Protocol.IJobOperations,System.String,Microsoft.Azure.Batch.Protocol.Models.JobDeleteOptions)" />
      <MemberSignature Language="F#" Value="static member Delete : Microsoft.Azure.Batch.Protocol.IJobOperations * string * Microsoft.Azure.Batch.Protocol.Models.JobDeleteOptions -&gt; Microsoft.Azure.Batch.Protocol.Models.JobDeleteHeaders" Usage="Microsoft.Azure.Batch.Protocol.JobOperationsExtensions.Delete (operations, jobId, jobDeleteOptions)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.Protocol.Models.JobDeleteHeaders</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Batch.Protocol.IJobOperations" RefType="this" />
        <Parameter Name="jobId" Type="System.String" />
        <Parameter Name="jobDeleteOptions" Type="Microsoft.Azure.Batch.Protocol.Models.JobDeleteOptions" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="b12dc-125">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="b12dc-125">The operations group for this extension method.</span></span>
            </param>
        <param name="jobId">
            <span data-ttu-id="b12dc-126">Die ID des Auftrags zu löschen.</span><span class="sxs-lookup"><span data-stu-id="b12dc-126">The ID of the job to delete.</span></span>
            </param>
        <param name="jobDeleteOptions">
            <span data-ttu-id="b12dc-127">Zusätzliche Parameter für den Vorgang</span><span class="sxs-lookup"><span data-stu-id="b12dc-127">Additional parameters for the operation</span></span>
            </param>
        <summary>
            <span data-ttu-id="b12dc-128">Löscht einen Auftrag.</span><span class="sxs-lookup"><span data-stu-id="b12dc-128">Deletes a job.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="b12dc-129">Löschen eines Auftrags werden auch alle Aufgaben, die Teil von diesem Auftrag sind, und alle Auftragsstatistik gelöscht.</span><span class="sxs-lookup"><span data-stu-id="b12dc-129">Deleting a job also deletes all tasks that are part of that job, and all job statistics.</span></span> <span data-ttu-id="b12dc-130">Dies wird auch die Beibehaltungsdauer für Aufgabendaten; d. h., wenn der Auftrag Aufgaben enthält, der weiterhin auf Serverknoten beibehalten werden, Batch-Dienste löscht Arbeitsverzeichnisse für diese Vorgänge und alle ihre Inhalte.</span><span class="sxs-lookup"><span data-stu-id="b12dc-130">This also overrides the retention period for task data; that is, if the job contains tasks which are still retained on compute nodes, the Batch services deletes those tasks' working directories and all their contents.</span></span>  <span data-ttu-id="b12dc-131">Wenn eine Auftrag löschen-Anforderung empfangen wird, wird der Batch-Dienst der Auftrag zum Löschen von Status an.</span><span class="sxs-lookup"><span data-stu-id="b12dc-131">When a Delete Job request is received, the Batch service sets the job to the deleting state.</span></span> <span data-ttu-id="b12dc-132">Alle Update-Vorgänge für einen Auftrag, der gelöscht wird, schlagen mit Statuscode 409 (Konflikt) mit zusätzlichen Informationen, der angibt, dass der Auftrag gelöscht wird.</span><span class="sxs-lookup"><span data-stu-id="b12dc-132">All update operations on a job that is in deleting state will fail with status code 409 (Conflict), with additional information indicating that the job is being deleted.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Batch.Protocol.Models.JobDeleteHeaders&gt; DeleteAsync (this Microsoft.Azure.Batch.Protocol.IJobOperations operations, string jobId, Microsoft.Azure.Batch.Protocol.Models.JobDeleteOptions jobDeleteOptions = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Batch.Protocol.Models.JobDeleteHeaders&gt; DeleteAsync(class Microsoft.Azure.Batch.Protocol.IJobOperations operations, string jobId, class Microsoft.Azure.Batch.Protocol.Models.JobDeleteOptions jobDeleteOptions, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.JobOperationsExtensions.DeleteAsync(Microsoft.Azure.Batch.Protocol.IJobOperations,System.String,Microsoft.Azure.Batch.Protocol.Models.JobDeleteOptions,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member DeleteAsync : Microsoft.Azure.Batch.Protocol.IJobOperations * string * Microsoft.Azure.Batch.Protocol.Models.JobDeleteOptions * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Batch.Protocol.Models.JobDeleteHeaders&gt;" Usage="Microsoft.Azure.Batch.Protocol.JobOperationsExtensions.DeleteAsync (operations, jobId, jobDeleteOptions, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Batch.Protocol.JobOperationsExtensions/&lt;DeleteAsync&gt;d__3))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Batch.Protocol.Models.JobDeleteHeaders&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Batch.Protocol.IJobOperations" RefType="this" />
        <Parameter Name="jobId" Type="System.String" />
        <Parameter Name="jobDeleteOptions" Type="Microsoft.Azure.Batch.Protocol.Models.JobDeleteOptions" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="b12dc-133">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="b12dc-133">The operations group for this extension method.</span></span>
            </param>
        <param name="jobId">
            <span data-ttu-id="b12dc-134">Die ID des Auftrags zu löschen.</span><span class="sxs-lookup"><span data-stu-id="b12dc-134">The ID of the job to delete.</span></span>
            </param>
        <param name="jobDeleteOptions">
            <span data-ttu-id="b12dc-135">Zusätzliche Parameter für den Vorgang</span><span class="sxs-lookup"><span data-stu-id="b12dc-135">Additional parameters for the operation</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="b12dc-136">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="b12dc-136">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="b12dc-137">Löscht einen Auftrag.</span><span class="sxs-lookup"><span data-stu-id="b12dc-137">Deletes a job.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="b12dc-138">Löschen eines Auftrags werden auch alle Aufgaben, die Teil von diesem Auftrag sind, und alle Auftragsstatistik gelöscht.</span><span class="sxs-lookup"><span data-stu-id="b12dc-138">Deleting a job also deletes all tasks that are part of that job, and all job statistics.</span></span> <span data-ttu-id="b12dc-139">Dies wird auch die Beibehaltungsdauer für Aufgabendaten; d. h., wenn der Auftrag Aufgaben enthält, der weiterhin auf Serverknoten beibehalten werden, Batch-Dienste löscht Arbeitsverzeichnisse für diese Vorgänge und alle ihre Inhalte.</span><span class="sxs-lookup"><span data-stu-id="b12dc-139">This also overrides the retention period for task data; that is, if the job contains tasks which are still retained on compute nodes, the Batch services deletes those tasks' working directories and all their contents.</span></span>  <span data-ttu-id="b12dc-140">Wenn eine Auftrag löschen-Anforderung empfangen wird, wird der Batch-Dienst der Auftrag zum Löschen von Status an.</span><span class="sxs-lookup"><span data-stu-id="b12dc-140">When a Delete Job request is received, the Batch service sets the job to the deleting state.</span></span> <span data-ttu-id="b12dc-141">Alle Update-Vorgänge für einen Auftrag, der gelöscht wird, schlagen mit Statuscode 409 (Konflikt) mit zusätzlichen Informationen, der angibt, dass der Auftrag gelöscht wird.</span><span class="sxs-lookup"><span data-stu-id="b12dc-141">All update operations on a job that is in deleting state will fail with status code 409 (Conflict), with additional information indicating that the job is being deleted.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="Disable">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Batch.Protocol.Models.JobDisableHeaders Disable (this Microsoft.Azure.Batch.Protocol.IJobOperations operations, string jobId, Microsoft.Azure.Batch.Protocol.Models.DisableJobOption disableTasks, Microsoft.Azure.Batch.Protocol.Models.JobDisableOptions jobDisableOptions = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Batch.Protocol.Models.JobDisableHeaders Disable(class Microsoft.Azure.Batch.Protocol.IJobOperations operations, string jobId, valuetype Microsoft.Azure.Batch.Protocol.Models.DisableJobOption disableTasks, class Microsoft.Azure.Batch.Protocol.Models.JobDisableOptions jobDisableOptions) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.JobOperationsExtensions.Disable(Microsoft.Azure.Batch.Protocol.IJobOperations,System.String,Microsoft.Azure.Batch.Protocol.Models.DisableJobOption,Microsoft.Azure.Batch.Protocol.Models.JobDisableOptions)" />
      <MemberSignature Language="F#" Value="static member Disable : Microsoft.Azure.Batch.Protocol.IJobOperations * string * Microsoft.Azure.Batch.Protocol.Models.DisableJobOption * Microsoft.Azure.Batch.Protocol.Models.JobDisableOptions -&gt; Microsoft.Azure.Batch.Protocol.Models.JobDisableHeaders" Usage="Microsoft.Azure.Batch.Protocol.JobOperationsExtensions.Disable (operations, jobId, disableTasks, jobDisableOptions)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.Protocol.Models.JobDisableHeaders</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Batch.Protocol.IJobOperations" RefType="this" />
        <Parameter Name="jobId" Type="System.String" />
        <Parameter Name="disableTasks" Type="Microsoft.Azure.Batch.Protocol.Models.DisableJobOption" />
        <Parameter Name="jobDisableOptions" Type="Microsoft.Azure.Batch.Protocol.Models.JobDisableOptions" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="b12dc-142">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="b12dc-142">The operations group for this extension method.</span></span>
            </param>
        <param name="jobId">
            <span data-ttu-id="b12dc-143">Die ID des Auftrags zu deaktivieren.</span><span class="sxs-lookup"><span data-stu-id="b12dc-143">The ID of the job to disable.</span></span>
            </param>
        <param name="disableTasks">
            <span data-ttu-id="b12dc-144">Vorgehensweise mit aktiven Aufgaben, die dem Auftrag zugeordnet.</span><span class="sxs-lookup"><span data-stu-id="b12dc-144">What to do with active tasks associated with the job.</span></span> <span data-ttu-id="b12dc-145">Folgende Werte sind möglich: "wieder in Warteschlange", "Beenden", "Warten"</span><span class="sxs-lookup"><span data-stu-id="b12dc-145">Possible values include: 'requeue', 'terminate', 'wait'</span></span>
            </param>
        <param name="jobDisableOptions">
            <span data-ttu-id="b12dc-146">Zusätzliche Parameter für den Vorgang</span><span class="sxs-lookup"><span data-stu-id="b12dc-146">Additional parameters for the operation</span></span>
            </param>
        <summary>
            <span data-ttu-id="b12dc-147">Deaktiviert den angegebenen Auftrag, der verhindert, dass neue Vorgänge ausgeführt wird.</span><span class="sxs-lookup"><span data-stu-id="b12dc-147">Disables the specified job, preventing new tasks from running.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="b12dc-148">Der Batch-Dienst verschiebt den Auftrag sofort in den Zustand deaktiviert.</span><span class="sxs-lookup"><span data-stu-id="b12dc-148">The Batch Service immediately moves the job to the disabling state.</span></span> <span data-ttu-id="b12dc-149">Batch verwendet dann den DisableTasks-Parameter, welche mit der aktuell ausgeführten Tasks des Auftrags zu tun.</span><span class="sxs-lookup"><span data-stu-id="b12dc-149">Batch then uses the disableTasks parameter to determine what to do with the currently running tasks of the job.</span></span> <span data-ttu-id="b12dc-150">Der Auftrag verbleibt im Status "deaktiviert", bis der Deaktivierungsvorgang abgeschlossen ist und alle Aufgaben wurde gemäß der Option DisableTasks damit haben; der Auftrag wird an den deaktivierten Zustand.</span><span class="sxs-lookup"><span data-stu-id="b12dc-150">The job remains in the disabling state until the disable operation is completed and all tasks have been dealt with according to the disableTasks option; the job then moves to the disabled state.</span></span> <span data-ttu-id="b12dc-151">Keine neuen Tasks werden unter dem Auftrag gestartet, bis er wieder zum Zustand "aktiv" wechselt.</span><span class="sxs-lookup"><span data-stu-id="b12dc-151">No new tasks are started under the job until it moves back to active state.</span></span> <span data-ttu-id="b12dc-152">Wenn Sie versuchen, einen Auftrag zu deaktivieren, der in einem beliebigen Zustand als aktiv ist, deaktivieren oder deaktiviert ist, schlägt die Anforderung fehl mit Statuscode 409.</span><span class="sxs-lookup"><span data-stu-id="b12dc-152">If you try to disable a job that is in any state other than active, disabling, or disabled, the request fails with status code 409.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="DisableAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Batch.Protocol.Models.JobDisableHeaders&gt; DisableAsync (this Microsoft.Azure.Batch.Protocol.IJobOperations operations, string jobId, Microsoft.Azure.Batch.Protocol.Models.DisableJobOption disableTasks, Microsoft.Azure.Batch.Protocol.Models.JobDisableOptions jobDisableOptions = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Batch.Protocol.Models.JobDisableHeaders&gt; DisableAsync(class Microsoft.Azure.Batch.Protocol.IJobOperations operations, string jobId, valuetype Microsoft.Azure.Batch.Protocol.Models.DisableJobOption disableTasks, class Microsoft.Azure.Batch.Protocol.Models.JobDisableOptions jobDisableOptions, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.JobOperationsExtensions.DisableAsync(Microsoft.Azure.Batch.Protocol.IJobOperations,System.String,Microsoft.Azure.Batch.Protocol.Models.DisableJobOption,Microsoft.Azure.Batch.Protocol.Models.JobDisableOptions,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member DisableAsync : Microsoft.Azure.Batch.Protocol.IJobOperations * string * Microsoft.Azure.Batch.Protocol.Models.DisableJobOption * Microsoft.Azure.Batch.Protocol.Models.JobDisableOptions * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Batch.Protocol.Models.JobDisableHeaders&gt;" Usage="Microsoft.Azure.Batch.Protocol.JobOperationsExtensions.DisableAsync (operations, jobId, disableTasks, jobDisableOptions, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Batch.Protocol.JobOperationsExtensions/&lt;DisableAsync&gt;d__11))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Batch.Protocol.Models.JobDisableHeaders&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Batch.Protocol.IJobOperations" RefType="this" />
        <Parameter Name="jobId" Type="System.String" />
        <Parameter Name="disableTasks" Type="Microsoft.Azure.Batch.Protocol.Models.DisableJobOption" />
        <Parameter Name="jobDisableOptions" Type="Microsoft.Azure.Batch.Protocol.Models.JobDisableOptions" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="b12dc-153">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="b12dc-153">The operations group for this extension method.</span></span>
            </param>
        <param name="jobId">
            <span data-ttu-id="b12dc-154">Die ID des Auftrags zu deaktivieren.</span><span class="sxs-lookup"><span data-stu-id="b12dc-154">The ID of the job to disable.</span></span>
            </param>
        <param name="disableTasks">
            <span data-ttu-id="b12dc-155">Vorgehensweise mit aktiven Aufgaben, die dem Auftrag zugeordnet.</span><span class="sxs-lookup"><span data-stu-id="b12dc-155">What to do with active tasks associated with the job.</span></span> <span data-ttu-id="b12dc-156">Folgende Werte sind möglich: "wieder in Warteschlange", "Beenden", "Warten"</span><span class="sxs-lookup"><span data-stu-id="b12dc-156">Possible values include: 'requeue', 'terminate', 'wait'</span></span>
            </param>
        <param name="jobDisableOptions">
            <span data-ttu-id="b12dc-157">Zusätzliche Parameter für den Vorgang</span><span class="sxs-lookup"><span data-stu-id="b12dc-157">Additional parameters for the operation</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="b12dc-158">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="b12dc-158">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="b12dc-159">Deaktiviert den angegebenen Auftrag, der verhindert, dass neue Vorgänge ausgeführt wird.</span><span class="sxs-lookup"><span data-stu-id="b12dc-159">Disables the specified job, preventing new tasks from running.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="b12dc-160">Der Batch-Dienst verschiebt den Auftrag sofort in den Zustand deaktiviert.</span><span class="sxs-lookup"><span data-stu-id="b12dc-160">The Batch Service immediately moves the job to the disabling state.</span></span> <span data-ttu-id="b12dc-161">Batch verwendet dann den DisableTasks-Parameter, welche mit der aktuell ausgeführten Tasks des Auftrags zu tun.</span><span class="sxs-lookup"><span data-stu-id="b12dc-161">Batch then uses the disableTasks parameter to determine what to do with the currently running tasks of the job.</span></span> <span data-ttu-id="b12dc-162">Der Auftrag verbleibt im Status "deaktiviert", bis der Deaktivierungsvorgang abgeschlossen ist und alle Aufgaben wurde gemäß der Option DisableTasks damit haben; der Auftrag wird an den deaktivierten Zustand.</span><span class="sxs-lookup"><span data-stu-id="b12dc-162">The job remains in the disabling state until the disable operation is completed and all tasks have been dealt with according to the disableTasks option; the job then moves to the disabled state.</span></span> <span data-ttu-id="b12dc-163">Keine neuen Tasks werden unter dem Auftrag gestartet, bis er wieder zum Zustand "aktiv" wechselt.</span><span class="sxs-lookup"><span data-stu-id="b12dc-163">No new tasks are started under the job until it moves back to active state.</span></span> <span data-ttu-id="b12dc-164">Wenn Sie versuchen, einen Auftrag zu deaktivieren, der in einem beliebigen Zustand als aktiv ist, deaktivieren oder deaktiviert ist, schlägt die Anforderung fehl mit Statuscode 409.</span><span class="sxs-lookup"><span data-stu-id="b12dc-164">If you try to disable a job that is in any state other than active, disabling, or disabled, the request fails with status code 409.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="Enable">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Batch.Protocol.Models.JobEnableHeaders Enable (this Microsoft.Azure.Batch.Protocol.IJobOperations operations, string jobId, Microsoft.Azure.Batch.Protocol.Models.JobEnableOptions jobEnableOptions = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Batch.Protocol.Models.JobEnableHeaders Enable(class Microsoft.Azure.Batch.Protocol.IJobOperations operations, string jobId, class Microsoft.Azure.Batch.Protocol.Models.JobEnableOptions jobEnableOptions) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.JobOperationsExtensions.Enable(Microsoft.Azure.Batch.Protocol.IJobOperations,System.String,Microsoft.Azure.Batch.Protocol.Models.JobEnableOptions)" />
      <MemberSignature Language="F#" Value="static member Enable : Microsoft.Azure.Batch.Protocol.IJobOperations * string * Microsoft.Azure.Batch.Protocol.Models.JobEnableOptions -&gt; Microsoft.Azure.Batch.Protocol.Models.JobEnableHeaders" Usage="Microsoft.Azure.Batch.Protocol.JobOperationsExtensions.Enable (operations, jobId, jobEnableOptions)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.Protocol.Models.JobEnableHeaders</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Batch.Protocol.IJobOperations" RefType="this" />
        <Parameter Name="jobId" Type="System.String" />
        <Parameter Name="jobEnableOptions" Type="Microsoft.Azure.Batch.Protocol.Models.JobEnableOptions" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="b12dc-165">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="b12dc-165">The operations group for this extension method.</span></span>
            </param>
        <param name="jobId">
            <span data-ttu-id="b12dc-166">Die ID des Auftrags zu aktivieren.</span><span class="sxs-lookup"><span data-stu-id="b12dc-166">The ID of the job to enable.</span></span>
            </param>
        <param name="jobEnableOptions">
            <span data-ttu-id="b12dc-167">Zusätzliche Parameter für den Vorgang</span><span class="sxs-lookup"><span data-stu-id="b12dc-167">Additional parameters for the operation</span></span>
            </param>
        <summary>
            <span data-ttu-id="b12dc-168">Aktiviert den angegebenen Auftrag, neue Aufgaben ausführen.</span><span class="sxs-lookup"><span data-stu-id="b12dc-168">Enables the specified job, allowing new tasks to run.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="b12dc-169">Wenn Sie diese API aufrufen, legt der Batch-Dienst ein deaktiviertes Auftrags auf ausschöpfen Zustand fest.</span><span class="sxs-lookup"><span data-stu-id="b12dc-169">When you call this API, the Batch service sets a disabled job to the enabling state.</span></span> <span data-ttu-id="b12dc-170">Nachdem dieser Vorgang abgeschlossen ist, geht der Auftrag in den aktiven Status und die Planung neuer Aufgaben unter der Auftrag fortgesetzt wird.</span><span class="sxs-lookup"><span data-stu-id="b12dc-170">After the this operation is completed, the job moves to the active state, and scheduling of new tasks under the job resumes.</span></span> <span data-ttu-id="b12dc-171">Der Batch-Dienst lässt sich nicht auf eine Aufgabe im Zustand "active" mehr als sieben Tage lang verbleiben aus.</span><span class="sxs-lookup"><span data-stu-id="b12dc-171">The Batch service does not allow a task to remain in the active state for more than 7 days.</span></span> <span data-ttu-id="b12dc-172">Wenn Sie ein Auftrags mit aktiven Aufgaben, die mehr als 7 Tage zurückliegen hinzugefügt wurden aktivieren, werden diese Aufgaben deshalb nicht ausgeführt.</span><span class="sxs-lookup"><span data-stu-id="b12dc-172">Therefore, if you enable a job containing active tasks which were added more than 7 days ago, those tasks will not run.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="EnableAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Batch.Protocol.Models.JobEnableHeaders&gt; EnableAsync (this Microsoft.Azure.Batch.Protocol.IJobOperations operations, string jobId, Microsoft.Azure.Batch.Protocol.Models.JobEnableOptions jobEnableOptions = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Batch.Protocol.Models.JobEnableHeaders&gt; EnableAsync(class Microsoft.Azure.Batch.Protocol.IJobOperations operations, string jobId, class Microsoft.Azure.Batch.Protocol.Models.JobEnableOptions jobEnableOptions, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.JobOperationsExtensions.EnableAsync(Microsoft.Azure.Batch.Protocol.IJobOperations,System.String,Microsoft.Azure.Batch.Protocol.Models.JobEnableOptions,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member EnableAsync : Microsoft.Azure.Batch.Protocol.IJobOperations * string * Microsoft.Azure.Batch.Protocol.Models.JobEnableOptions * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Batch.Protocol.Models.JobEnableHeaders&gt;" Usage="Microsoft.Azure.Batch.Protocol.JobOperationsExtensions.EnableAsync (operations, jobId, jobEnableOptions, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Batch.Protocol.JobOperationsExtensions/&lt;EnableAsync&gt;d__13))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Batch.Protocol.Models.JobEnableHeaders&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Batch.Protocol.IJobOperations" RefType="this" />
        <Parameter Name="jobId" Type="System.String" />
        <Parameter Name="jobEnableOptions" Type="Microsoft.Azure.Batch.Protocol.Models.JobEnableOptions" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="b12dc-173">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="b12dc-173">The operations group for this extension method.</span></span>
            </param>
        <param name="jobId">
            <span data-ttu-id="b12dc-174">Die ID des Auftrags zu aktivieren.</span><span class="sxs-lookup"><span data-stu-id="b12dc-174">The ID of the job to enable.</span></span>
            </param>
        <param name="jobEnableOptions">
            <span data-ttu-id="b12dc-175">Zusätzliche Parameter für den Vorgang</span><span class="sxs-lookup"><span data-stu-id="b12dc-175">Additional parameters for the operation</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="b12dc-176">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="b12dc-176">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="b12dc-177">Aktiviert den angegebenen Auftrag, neue Aufgaben ausführen.</span><span class="sxs-lookup"><span data-stu-id="b12dc-177">Enables the specified job, allowing new tasks to run.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="b12dc-178">Wenn Sie diese API aufrufen, legt der Batch-Dienst ein deaktiviertes Auftrags auf ausschöpfen Zustand fest.</span><span class="sxs-lookup"><span data-stu-id="b12dc-178">When you call this API, the Batch service sets a disabled job to the enabling state.</span></span> <span data-ttu-id="b12dc-179">Nachdem dieser Vorgang abgeschlossen ist, geht der Auftrag in den aktiven Status und die Planung neuer Aufgaben unter der Auftrag fortgesetzt wird.</span><span class="sxs-lookup"><span data-stu-id="b12dc-179">After the this operation is completed, the job moves to the active state, and scheduling of new tasks under the job resumes.</span></span> <span data-ttu-id="b12dc-180">Der Batch-Dienst lässt sich nicht auf eine Aufgabe im Zustand "active" mehr als sieben Tage lang verbleiben aus.</span><span class="sxs-lookup"><span data-stu-id="b12dc-180">The Batch service does not allow a task to remain in the active state for more than 7 days.</span></span> <span data-ttu-id="b12dc-181">Wenn Sie ein Auftrags mit aktiven Aufgaben, die mehr als 7 Tage zurückliegen hinzugefügt wurden aktivieren, werden diese Aufgaben deshalb nicht ausgeführt.</span><span class="sxs-lookup"><span data-stu-id="b12dc-181">Therefore, if you enable a job containing active tasks which were added more than 7 days ago, those tasks will not run.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="Get">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Batch.Protocol.Models.CloudJob Get (this Microsoft.Azure.Batch.Protocol.IJobOperations operations, string jobId, Microsoft.Azure.Batch.Protocol.Models.JobGetOptions jobGetOptions = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Batch.Protocol.Models.CloudJob Get(class Microsoft.Azure.Batch.Protocol.IJobOperations operations, string jobId, class Microsoft.Azure.Batch.Protocol.Models.JobGetOptions jobGetOptions) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.JobOperationsExtensions.Get(Microsoft.Azure.Batch.Protocol.IJobOperations,System.String,Microsoft.Azure.Batch.Protocol.Models.JobGetOptions)" />
      <MemberSignature Language="F#" Value="static member Get : Microsoft.Azure.Batch.Protocol.IJobOperations * string * Microsoft.Azure.Batch.Protocol.Models.JobGetOptions -&gt; Microsoft.Azure.Batch.Protocol.Models.CloudJob" Usage="Microsoft.Azure.Batch.Protocol.JobOperationsExtensions.Get (operations, jobId, jobGetOptions)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.Protocol.Models.CloudJob</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Batch.Protocol.IJobOperations" RefType="this" />
        <Parameter Name="jobId" Type="System.String" />
        <Parameter Name="jobGetOptions" Type="Microsoft.Azure.Batch.Protocol.Models.JobGetOptions" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="b12dc-182">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="b12dc-182">The operations group for this extension method.</span></span>
            </param>
        <param name="jobId">
            <span data-ttu-id="b12dc-183">Die ID des Auftrags.</span><span class="sxs-lookup"><span data-stu-id="b12dc-183">The ID of the job.</span></span>
            </param>
        <param name="jobGetOptions">
            <span data-ttu-id="b12dc-184">Zusätzliche Parameter für den Vorgang</span><span class="sxs-lookup"><span data-stu-id="b12dc-184">Additional parameters for the operation</span></span>
            </param>
        <summary>
            <span data-ttu-id="b12dc-185">Ruft Informationen über den angegebenen Auftrag ab.</span><span class="sxs-lookup"><span data-stu-id="b12dc-185">Gets information about the specified job.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAllLifetimeStatistics">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Batch.Protocol.Models.JobStatistics GetAllLifetimeStatistics (this Microsoft.Azure.Batch.Protocol.IJobOperations operations, Microsoft.Azure.Batch.Protocol.Models.JobGetAllLifetimeStatisticsOptions jobGetAllLifetimeStatisticsOptions = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Batch.Protocol.Models.JobStatistics GetAllLifetimeStatistics(class Microsoft.Azure.Batch.Protocol.IJobOperations operations, class Microsoft.Azure.Batch.Protocol.Models.JobGetAllLifetimeStatisticsOptions jobGetAllLifetimeStatisticsOptions) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.JobOperationsExtensions.GetAllLifetimeStatistics(Microsoft.Azure.Batch.Protocol.IJobOperations,Microsoft.Azure.Batch.Protocol.Models.JobGetAllLifetimeStatisticsOptions)" />
      <MemberSignature Language="F#" Value="static member GetAllLifetimeStatistics : Microsoft.Azure.Batch.Protocol.IJobOperations * Microsoft.Azure.Batch.Protocol.Models.JobGetAllLifetimeStatisticsOptions -&gt; Microsoft.Azure.Batch.Protocol.Models.JobStatistics" Usage="Microsoft.Azure.Batch.Protocol.JobOperationsExtensions.GetAllLifetimeStatistics (operations, jobGetAllLifetimeStatisticsOptions)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.Protocol.Models.JobStatistics</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Batch.Protocol.IJobOperations" RefType="this" />
        <Parameter Name="jobGetAllLifetimeStatisticsOptions" Type="Microsoft.Azure.Batch.Protocol.Models.JobGetAllLifetimeStatisticsOptions" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="b12dc-186">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="b12dc-186">The operations group for this extension method.</span></span>
            </param>
        <param name="jobGetAllLifetimeStatisticsOptions">
            <span data-ttu-id="b12dc-187">Zusätzliche Parameter für den Vorgang</span><span class="sxs-lookup"><span data-stu-id="b12dc-187">Additional parameters for the operation</span></span>
            </param>
        <summary>
            <span data-ttu-id="b12dc-188">Zusammenfassung lebensdauerstatistiken für alle Aufträge in das angegebene Konto abgerufen.</span><span class="sxs-lookup"><span data-stu-id="b12dc-188">Gets lifetime summary statistics for all of the jobs in the specified account.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="b12dc-189">Statistiken werden für alle Aufträge aggregiert, die jemals im Konto, von der kontoerstellung bis zum letzten Zeitpunkt des Updates der Statistik vorhanden waren.</span><span class="sxs-lookup"><span data-stu-id="b12dc-189">Statistics are aggregated across all jobs that have ever existed in the account, from account creation to the last update time of the statistics.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAllLifetimeStatisticsAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Batch.Protocol.Models.JobStatistics&gt; GetAllLifetimeStatisticsAsync (this Microsoft.Azure.Batch.Protocol.IJobOperations operations, Microsoft.Azure.Batch.Protocol.Models.JobGetAllLifetimeStatisticsOptions jobGetAllLifetimeStatisticsOptions = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Batch.Protocol.Models.JobStatistics&gt; GetAllLifetimeStatisticsAsync(class Microsoft.Azure.Batch.Protocol.IJobOperations operations, class Microsoft.Azure.Batch.Protocol.Models.JobGetAllLifetimeStatisticsOptions jobGetAllLifetimeStatisticsOptions, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.JobOperationsExtensions.GetAllLifetimeStatisticsAsync(Microsoft.Azure.Batch.Protocol.IJobOperations,Microsoft.Azure.Batch.Protocol.Models.JobGetAllLifetimeStatisticsOptions,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetAllLifetimeStatisticsAsync : Microsoft.Azure.Batch.Protocol.IJobOperations * Microsoft.Azure.Batch.Protocol.Models.JobGetAllLifetimeStatisticsOptions * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Batch.Protocol.Models.JobStatistics&gt;" Usage="Microsoft.Azure.Batch.Protocol.JobOperationsExtensions.GetAllLifetimeStatisticsAsync (operations, jobGetAllLifetimeStatisticsOptions, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Batch.Protocol.JobOperationsExtensions/&lt;GetAllLifetimeStatisticsAsync&gt;d__1))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Batch.Protocol.Models.JobStatistics&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Batch.Protocol.IJobOperations" RefType="this" />
        <Parameter Name="jobGetAllLifetimeStatisticsOptions" Type="Microsoft.Azure.Batch.Protocol.Models.JobGetAllLifetimeStatisticsOptions" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="b12dc-190">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="b12dc-190">The operations group for this extension method.</span></span>
            </param>
        <param name="jobGetAllLifetimeStatisticsOptions">
            <span data-ttu-id="b12dc-191">Zusätzliche Parameter für den Vorgang</span><span class="sxs-lookup"><span data-stu-id="b12dc-191">Additional parameters for the operation</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="b12dc-192">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="b12dc-192">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="b12dc-193">Zusammenfassung lebensdauerstatistiken für alle Aufträge in das angegebene Konto abgerufen.</span><span class="sxs-lookup"><span data-stu-id="b12dc-193">Gets lifetime summary statistics for all of the jobs in the specified account.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="b12dc-194">Statistiken werden für alle Aufträge aggregiert, die jemals im Konto, von der kontoerstellung bis zum letzten Zeitpunkt des Updates der Statistik vorhanden waren.</span><span class="sxs-lookup"><span data-stu-id="b12dc-194">Statistics are aggregated across all jobs that have ever existed in the account, from account creation to the last update time of the statistics.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Batch.Protocol.Models.CloudJob&gt; GetAsync (this Microsoft.Azure.Batch.Protocol.IJobOperations operations, string jobId, Microsoft.Azure.Batch.Protocol.Models.JobGetOptions jobGetOptions = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Batch.Protocol.Models.CloudJob&gt; GetAsync(class Microsoft.Azure.Batch.Protocol.IJobOperations operations, string jobId, class Microsoft.Azure.Batch.Protocol.Models.JobGetOptions jobGetOptions, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.JobOperationsExtensions.GetAsync(Microsoft.Azure.Batch.Protocol.IJobOperations,System.String,Microsoft.Azure.Batch.Protocol.Models.JobGetOptions,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetAsync : Microsoft.Azure.Batch.Protocol.IJobOperations * string * Microsoft.Azure.Batch.Protocol.Models.JobGetOptions * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Batch.Protocol.Models.CloudJob&gt;" Usage="Microsoft.Azure.Batch.Protocol.JobOperationsExtensions.GetAsync (operations, jobId, jobGetOptions, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Batch.Protocol.JobOperationsExtensions/&lt;GetAsync&gt;d__5))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Batch.Protocol.Models.CloudJob&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Batch.Protocol.IJobOperations" RefType="this" />
        <Parameter Name="jobId" Type="System.String" />
        <Parameter Name="jobGetOptions" Type="Microsoft.Azure.Batch.Protocol.Models.JobGetOptions" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="b12dc-195">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="b12dc-195">The operations group for this extension method.</span></span>
            </param>
        <param name="jobId">
            <span data-ttu-id="b12dc-196">Die ID des Auftrags.</span><span class="sxs-lookup"><span data-stu-id="b12dc-196">The ID of the job.</span></span>
            </param>
        <param name="jobGetOptions">
            <span data-ttu-id="b12dc-197">Zusätzliche Parameter für den Vorgang</span><span class="sxs-lookup"><span data-stu-id="b12dc-197">Additional parameters for the operation</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="b12dc-198">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="b12dc-198">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="b12dc-199">Ruft Informationen über den angegebenen Auftrag ab.</span><span class="sxs-lookup"><span data-stu-id="b12dc-199">Gets information about the specified job.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetTaskCounts">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Batch.Protocol.Models.TaskCounts GetTaskCounts (this Microsoft.Azure.Batch.Protocol.IJobOperations operations, string jobId, Microsoft.Azure.Batch.Protocol.Models.JobGetTaskCountsOptions jobGetTaskCountsOptions = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Batch.Protocol.Models.TaskCounts GetTaskCounts(class Microsoft.Azure.Batch.Protocol.IJobOperations operations, string jobId, class Microsoft.Azure.Batch.Protocol.Models.JobGetTaskCountsOptions jobGetTaskCountsOptions) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.JobOperationsExtensions.GetTaskCounts(Microsoft.Azure.Batch.Protocol.IJobOperations,System.String,Microsoft.Azure.Batch.Protocol.Models.JobGetTaskCountsOptions)" />
      <MemberSignature Language="F#" Value="static member GetTaskCounts : Microsoft.Azure.Batch.Protocol.IJobOperations * string * Microsoft.Azure.Batch.Protocol.Models.JobGetTaskCountsOptions -&gt; Microsoft.Azure.Batch.Protocol.Models.TaskCounts" Usage="Microsoft.Azure.Batch.Protocol.JobOperationsExtensions.GetTaskCounts (operations, jobId, jobGetTaskCountsOptions)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.Protocol.Models.TaskCounts</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Batch.Protocol.IJobOperations" RefType="this" />
        <Parameter Name="jobId" Type="System.String" />
        <Parameter Name="jobGetTaskCountsOptions" Type="Microsoft.Azure.Batch.Protocol.Models.JobGetTaskCountsOptions" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="b12dc-200">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="b12dc-200">The operations group for this extension method.</span></span>
            </param>
        <param name="jobId">
            <span data-ttu-id="b12dc-201">Die ID des Auftrags.</span><span class="sxs-lookup"><span data-stu-id="b12dc-201">The ID of the job.</span></span>
            </param>
        <param name="jobGetTaskCountsOptions">
            <span data-ttu-id="b12dc-202">Zusätzliche Parameter für den Vorgang</span><span class="sxs-lookup"><span data-stu-id="b12dc-202">Additional parameters for the operation</span></span>
            </param>
        <summary>
            <span data-ttu-id="b12dc-203">Ruft die Anzahl der Task für den angegebenen Auftrag.</span><span class="sxs-lookup"><span data-stu-id="b12dc-203">Gets the task counts for the specified job.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="b12dc-204">Aufgabe Anzahlen bieten eine Anzahl der Aufgaben nach dem Zustand Aktiv, laufenden oder abgeschlossenen Aufgabe sowie die Anzahl der Aufgaben, die erfolgreich war oder nicht.</span><span class="sxs-lookup"><span data-stu-id="b12dc-204">Task counts provide a count of the tasks by active, running or completed task state, and a count of tasks which succeeded or failed.</span></span> <span data-ttu-id="b12dc-205">Aufgaben im Status "vorbereitet" werden als Ausführung gezählt.</span><span class="sxs-lookup"><span data-stu-id="b12dc-205">Tasks in the preparing state are counted as running.</span></span> <span data-ttu-id="b12dc-206">Wenn die ValidationStatus nicht überprüfte ist, klicken Sie dann wurde der Batch-Dienst nicht zum Überprüfen, dass für die Task-Status in der Liste Aufgaben-API gemeldeten Status zählt können.</span><span class="sxs-lookup"><span data-stu-id="b12dc-206">If the validationStatus is unvalidated, then the Batch service has not been able to check state counts against the task states as reported in the List Tasks API.</span></span> <span data-ttu-id="b12dc-207">Die ValidationStatus möglicherweise nicht überprüfte sein, wenn der Auftrag über 200.000 Aufgaben enthält.</span><span class="sxs-lookup"><span data-stu-id="b12dc-207">The validationStatus may be unvalidated if the job contains more than 200,000 tasks.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="GetTaskCountsAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Batch.Protocol.Models.TaskCounts&gt; GetTaskCountsAsync (this Microsoft.Azure.Batch.Protocol.IJobOperations operations, string jobId, Microsoft.Azure.Batch.Protocol.Models.JobGetTaskCountsOptions jobGetTaskCountsOptions = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Batch.Protocol.Models.TaskCounts&gt; GetTaskCountsAsync(class Microsoft.Azure.Batch.Protocol.IJobOperations operations, string jobId, class Microsoft.Azure.Batch.Protocol.Models.JobGetTaskCountsOptions jobGetTaskCountsOptions, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.JobOperationsExtensions.GetTaskCountsAsync(Microsoft.Azure.Batch.Protocol.IJobOperations,System.String,Microsoft.Azure.Batch.Protocol.Models.JobGetTaskCountsOptions,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetTaskCountsAsync : Microsoft.Azure.Batch.Protocol.IJobOperations * string * Microsoft.Azure.Batch.Protocol.Models.JobGetTaskCountsOptions * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Batch.Protocol.Models.TaskCounts&gt;" Usage="Microsoft.Azure.Batch.Protocol.JobOperationsExtensions.GetTaskCountsAsync (operations, jobId, jobGetTaskCountsOptions, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Batch.Protocol.JobOperationsExtensions/&lt;GetTaskCountsAsync&gt;d__25))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Batch.Protocol.Models.TaskCounts&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Batch.Protocol.IJobOperations" RefType="this" />
        <Parameter Name="jobId" Type="System.String" />
        <Parameter Name="jobGetTaskCountsOptions" Type="Microsoft.Azure.Batch.Protocol.Models.JobGetTaskCountsOptions" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="b12dc-208">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="b12dc-208">The operations group for this extension method.</span></span>
            </param>
        <param name="jobId">
            <span data-ttu-id="b12dc-209">Die ID des Auftrags.</span><span class="sxs-lookup"><span data-stu-id="b12dc-209">The ID of the job.</span></span>
            </param>
        <param name="jobGetTaskCountsOptions">
            <span data-ttu-id="b12dc-210">Zusätzliche Parameter für den Vorgang</span><span class="sxs-lookup"><span data-stu-id="b12dc-210">Additional parameters for the operation</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="b12dc-211">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="b12dc-211">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="b12dc-212">Ruft die Anzahl der Task für den angegebenen Auftrag.</span><span class="sxs-lookup"><span data-stu-id="b12dc-212">Gets the task counts for the specified job.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="b12dc-213">Aufgabe Anzahlen bieten eine Anzahl der Aufgaben nach dem Zustand Aktiv, laufenden oder abgeschlossenen Aufgabe sowie die Anzahl der Aufgaben, die erfolgreich war oder nicht.</span><span class="sxs-lookup"><span data-stu-id="b12dc-213">Task counts provide a count of the tasks by active, running or completed task state, and a count of tasks which succeeded or failed.</span></span> <span data-ttu-id="b12dc-214">Aufgaben im Status "vorbereitet" werden als Ausführung gezählt.</span><span class="sxs-lookup"><span data-stu-id="b12dc-214">Tasks in the preparing state are counted as running.</span></span> <span data-ttu-id="b12dc-215">Wenn die ValidationStatus nicht überprüfte ist, klicken Sie dann wurde der Batch-Dienst nicht zum Überprüfen, dass für die Task-Status in der Liste Aufgaben-API gemeldeten Status zählt können.</span><span class="sxs-lookup"><span data-stu-id="b12dc-215">If the validationStatus is unvalidated, then the Batch service has not been able to check state counts against the task states as reported in the List Tasks API.</span></span> <span data-ttu-id="b12dc-216">Die ValidationStatus möglicherweise nicht überprüfte sein, wenn der Auftrag über 200.000 Aufgaben enthält.</span><span class="sxs-lookup"><span data-stu-id="b12dc-216">The validationStatus may be unvalidated if the job contains more than 200,000 tasks.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="List">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Batch.Protocol.Models.CloudJob&gt; List (this Microsoft.Azure.Batch.Protocol.IJobOperations operations, Microsoft.Azure.Batch.Protocol.Models.JobListOptions jobListOptions = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Batch.Protocol.Models.CloudJob&gt; List(class Microsoft.Azure.Batch.Protocol.IJobOperations operations, class Microsoft.Azure.Batch.Protocol.Models.JobListOptions jobListOptions) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.JobOperationsExtensions.List(Microsoft.Azure.Batch.Protocol.IJobOperations,Microsoft.Azure.Batch.Protocol.Models.JobListOptions)" />
      <MemberSignature Language="F#" Value="static member List : Microsoft.Azure.Batch.Protocol.IJobOperations * Microsoft.Azure.Batch.Protocol.Models.JobListOptions -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Batch.Protocol.Models.CloudJob&gt;" Usage="Microsoft.Azure.Batch.Protocol.JobOperationsExtensions.List (operations, jobListOptions)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Batch.Protocol.Models.CloudJob&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Batch.Protocol.IJobOperations" RefType="this" />
        <Parameter Name="jobListOptions" Type="Microsoft.Azure.Batch.Protocol.Models.JobListOptions" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="b12dc-217">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="b12dc-217">The operations group for this extension method.</span></span>
            </param>
        <param name="jobListOptions">
            <span data-ttu-id="b12dc-218">Zusätzliche Parameter für den Vorgang</span><span class="sxs-lookup"><span data-stu-id="b12dc-218">Additional parameters for the operation</span></span>
            </param>
        <summary>
            <span data-ttu-id="b12dc-219">Zeigt eine Liste aller Aufträge in das angegebene Konto.</span><span class="sxs-lookup"><span data-stu-id="b12dc-219">Lists all of the jobs in the specified account.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Batch.Protocol.Models.CloudJob&gt;&gt; ListAsync (this Microsoft.Azure.Batch.Protocol.IJobOperations operations, Microsoft.Azure.Batch.Protocol.Models.JobListOptions jobListOptions = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Batch.Protocol.Models.CloudJob&gt;&gt; ListAsync(class Microsoft.Azure.Batch.Protocol.IJobOperations operations, class Microsoft.Azure.Batch.Protocol.Models.JobListOptions jobListOptions, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.JobOperationsExtensions.ListAsync(Microsoft.Azure.Batch.Protocol.IJobOperations,Microsoft.Azure.Batch.Protocol.Models.JobListOptions,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListAsync : Microsoft.Azure.Batch.Protocol.IJobOperations * Microsoft.Azure.Batch.Protocol.Models.JobListOptions * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Batch.Protocol.Models.CloudJob&gt;&gt;" Usage="Microsoft.Azure.Batch.Protocol.JobOperationsExtensions.ListAsync (operations, jobListOptions, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Batch.Protocol.JobOperationsExtensions/&lt;ListAsync&gt;d__19))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Batch.Protocol.Models.CloudJob&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Batch.Protocol.IJobOperations" RefType="this" />
        <Parameter Name="jobListOptions" Type="Microsoft.Azure.Batch.Protocol.Models.JobListOptions" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="b12dc-220">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="b12dc-220">The operations group for this extension method.</span></span>
            </param>
        <param name="jobListOptions">
            <span data-ttu-id="b12dc-221">Zusätzliche Parameter für den Vorgang</span><span class="sxs-lookup"><span data-stu-id="b12dc-221">Additional parameters for the operation</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="b12dc-222">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="b12dc-222">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="b12dc-223">Zeigt eine Liste aller Aufträge in das angegebene Konto.</span><span class="sxs-lookup"><span data-stu-id="b12dc-223">Lists all of the jobs in the specified account.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListFromJobSchedule">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Batch.Protocol.Models.CloudJob&gt; ListFromJobSchedule (this Microsoft.Azure.Batch.Protocol.IJobOperations operations, string jobScheduleId, Microsoft.Azure.Batch.Protocol.Models.JobListFromJobScheduleOptions jobListFromJobScheduleOptions = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Batch.Protocol.Models.CloudJob&gt; ListFromJobSchedule(class Microsoft.Azure.Batch.Protocol.IJobOperations operations, string jobScheduleId, class Microsoft.Azure.Batch.Protocol.Models.JobListFromJobScheduleOptions jobListFromJobScheduleOptions) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.JobOperationsExtensions.ListFromJobSchedule(Microsoft.Azure.Batch.Protocol.IJobOperations,System.String,Microsoft.Azure.Batch.Protocol.Models.JobListFromJobScheduleOptions)" />
      <MemberSignature Language="F#" Value="static member ListFromJobSchedule : Microsoft.Azure.Batch.Protocol.IJobOperations * string * Microsoft.Azure.Batch.Protocol.Models.JobListFromJobScheduleOptions -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Batch.Protocol.Models.CloudJob&gt;" Usage="Microsoft.Azure.Batch.Protocol.JobOperationsExtensions.ListFromJobSchedule (operations, jobScheduleId, jobListFromJobScheduleOptions)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Batch.Protocol.Models.CloudJob&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Batch.Protocol.IJobOperations" RefType="this" />
        <Parameter Name="jobScheduleId" Type="System.String" />
        <Parameter Name="jobListFromJobScheduleOptions" Type="Microsoft.Azure.Batch.Protocol.Models.JobListFromJobScheduleOptions" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="b12dc-224">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="b12dc-224">The operations group for this extension method.</span></span>
            </param>
        <param name="jobScheduleId">
            <span data-ttu-id="b12dc-225">Die ID des Auftragszeitplans, von dem Sie eine Liste der Aufträge abrufen möchten.</span><span class="sxs-lookup"><span data-stu-id="b12dc-225">The ID of the job schedule from which you want to get a list of jobs.</span></span>
            </param>
        <param name="jobListFromJobScheduleOptions">
            <span data-ttu-id="b12dc-226">Zusätzliche Parameter für den Vorgang</span><span class="sxs-lookup"><span data-stu-id="b12dc-226">Additional parameters for the operation</span></span>
            </param>
        <summary>
            <span data-ttu-id="b12dc-227">Listet die Aufträge, die unter der angegebenen Auftragszeitplan erstellt wurden.</span><span class="sxs-lookup"><span data-stu-id="b12dc-227">Lists the jobs that have been created under the specified job schedule.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListFromJobScheduleAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Batch.Protocol.Models.CloudJob&gt;&gt; ListFromJobScheduleAsync (this Microsoft.Azure.Batch.Protocol.IJobOperations operations, string jobScheduleId, Microsoft.Azure.Batch.Protocol.Models.JobListFromJobScheduleOptions jobListFromJobScheduleOptions = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Batch.Protocol.Models.CloudJob&gt;&gt; ListFromJobScheduleAsync(class Microsoft.Azure.Batch.Protocol.IJobOperations operations, string jobScheduleId, class Microsoft.Azure.Batch.Protocol.Models.JobListFromJobScheduleOptions jobListFromJobScheduleOptions, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.JobOperationsExtensions.ListFromJobScheduleAsync(Microsoft.Azure.Batch.Protocol.IJobOperations,System.String,Microsoft.Azure.Batch.Protocol.Models.JobListFromJobScheduleOptions,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListFromJobScheduleAsync : Microsoft.Azure.Batch.Protocol.IJobOperations * string * Microsoft.Azure.Batch.Protocol.Models.JobListFromJobScheduleOptions * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Batch.Protocol.Models.CloudJob&gt;&gt;" Usage="Microsoft.Azure.Batch.Protocol.JobOperationsExtensions.ListFromJobScheduleAsync (operations, jobScheduleId, jobListFromJobScheduleOptions, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Batch.Protocol.JobOperationsExtensions/&lt;ListFromJobScheduleAsync&gt;d__21))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Batch.Protocol.Models.CloudJob&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Batch.Protocol.IJobOperations" RefType="this" />
        <Parameter Name="jobScheduleId" Type="System.String" />
        <Parameter Name="jobListFromJobScheduleOptions" Type="Microsoft.Azure.Batch.Protocol.Models.JobListFromJobScheduleOptions" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="b12dc-228">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="b12dc-228">The operations group for this extension method.</span></span>
            </param>
        <param name="jobScheduleId">
            <span data-ttu-id="b12dc-229">Die ID des Auftragszeitplans, von dem Sie eine Liste der Aufträge abrufen möchten.</span><span class="sxs-lookup"><span data-stu-id="b12dc-229">The ID of the job schedule from which you want to get a list of jobs.</span></span>
            </param>
        <param name="jobListFromJobScheduleOptions">
            <span data-ttu-id="b12dc-230">Zusätzliche Parameter für den Vorgang</span><span class="sxs-lookup"><span data-stu-id="b12dc-230">Additional parameters for the operation</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="b12dc-231">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="b12dc-231">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="b12dc-232">Listet die Aufträge, die unter der angegebenen Auftragszeitplan erstellt wurden.</span><span class="sxs-lookup"><span data-stu-id="b12dc-232">Lists the jobs that have been created under the specified job schedule.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListFromJobScheduleNext">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Batch.Protocol.Models.CloudJob&gt; ListFromJobScheduleNext (this Microsoft.Azure.Batch.Protocol.IJobOperations operations, string nextPageLink, Microsoft.Azure.Batch.Protocol.Models.JobListFromJobScheduleNextOptions jobListFromJobScheduleNextOptions = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Batch.Protocol.Models.CloudJob&gt; ListFromJobScheduleNext(class Microsoft.Azure.Batch.Protocol.IJobOperations operations, string nextPageLink, class Microsoft.Azure.Batch.Protocol.Models.JobListFromJobScheduleNextOptions jobListFromJobScheduleNextOptions) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.JobOperationsExtensions.ListFromJobScheduleNext(Microsoft.Azure.Batch.Protocol.IJobOperations,System.String,Microsoft.Azure.Batch.Protocol.Models.JobListFromJobScheduleNextOptions)" />
      <MemberSignature Language="F#" Value="static member ListFromJobScheduleNext : Microsoft.Azure.Batch.Protocol.IJobOperations * string * Microsoft.Azure.Batch.Protocol.Models.JobListFromJobScheduleNextOptions -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Batch.Protocol.Models.CloudJob&gt;" Usage="Microsoft.Azure.Batch.Protocol.JobOperationsExtensions.ListFromJobScheduleNext (operations, nextPageLink, jobListFromJobScheduleNextOptions)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Batch.Protocol.Models.CloudJob&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Batch.Protocol.IJobOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="jobListFromJobScheduleNextOptions" Type="Microsoft.Azure.Batch.Protocol.Models.JobListFromJobScheduleNextOptions" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="b12dc-233">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="b12dc-233">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="b12dc-234">Die "NextLink" aus dem vorherigen erfolgreichen Aufruf List-Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="b12dc-234">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="jobListFromJobScheduleNextOptions">
            <span data-ttu-id="b12dc-235">Zusätzliche Parameter für den Vorgang</span><span class="sxs-lookup"><span data-stu-id="b12dc-235">Additional parameters for the operation</span></span>
            </param>
        <summary>
            <span data-ttu-id="b12dc-236">Listet die Aufträge, die unter der angegebenen Auftragszeitplan erstellt wurden.</span><span class="sxs-lookup"><span data-stu-id="b12dc-236">Lists the jobs that have been created under the specified job schedule.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListFromJobScheduleNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Batch.Protocol.Models.CloudJob&gt;&gt; ListFromJobScheduleNextAsync (this Microsoft.Azure.Batch.Protocol.IJobOperations operations, string nextPageLink, Microsoft.Azure.Batch.Protocol.Models.JobListFromJobScheduleNextOptions jobListFromJobScheduleNextOptions = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Batch.Protocol.Models.CloudJob&gt;&gt; ListFromJobScheduleNextAsync(class Microsoft.Azure.Batch.Protocol.IJobOperations operations, string nextPageLink, class Microsoft.Azure.Batch.Protocol.Models.JobListFromJobScheduleNextOptions jobListFromJobScheduleNextOptions, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.JobOperationsExtensions.ListFromJobScheduleNextAsync(Microsoft.Azure.Batch.Protocol.IJobOperations,System.String,Microsoft.Azure.Batch.Protocol.Models.JobListFromJobScheduleNextOptions,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListFromJobScheduleNextAsync : Microsoft.Azure.Batch.Protocol.IJobOperations * string * Microsoft.Azure.Batch.Protocol.Models.JobListFromJobScheduleNextOptions * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Batch.Protocol.Models.CloudJob&gt;&gt;" Usage="Microsoft.Azure.Batch.Protocol.JobOperationsExtensions.ListFromJobScheduleNextAsync (operations, nextPageLink, jobListFromJobScheduleNextOptions, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Batch.Protocol.JobOperationsExtensions/&lt;ListFromJobScheduleNextAsync&gt;d__29))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Batch.Protocol.Models.CloudJob&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Batch.Protocol.IJobOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="jobListFromJobScheduleNextOptions" Type="Microsoft.Azure.Batch.Protocol.Models.JobListFromJobScheduleNextOptions" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="b12dc-237">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="b12dc-237">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="b12dc-238">Die "NextLink" aus dem vorherigen erfolgreichen Aufruf List-Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="b12dc-238">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="jobListFromJobScheduleNextOptions">
            <span data-ttu-id="b12dc-239">Zusätzliche Parameter für den Vorgang</span><span class="sxs-lookup"><span data-stu-id="b12dc-239">Additional parameters for the operation</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="b12dc-240">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="b12dc-240">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="b12dc-241">Listet die Aufträge, die unter der angegebenen Auftragszeitplan erstellt wurden.</span><span class="sxs-lookup"><span data-stu-id="b12dc-241">Lists the jobs that have been created under the specified job schedule.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListNext">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Batch.Protocol.Models.CloudJob&gt; ListNext (this Microsoft.Azure.Batch.Protocol.IJobOperations operations, string nextPageLink, Microsoft.Azure.Batch.Protocol.Models.JobListNextOptions jobListNextOptions = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Batch.Protocol.Models.CloudJob&gt; ListNext(class Microsoft.Azure.Batch.Protocol.IJobOperations operations, string nextPageLink, class Microsoft.Azure.Batch.Protocol.Models.JobListNextOptions jobListNextOptions) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.JobOperationsExtensions.ListNext(Microsoft.Azure.Batch.Protocol.IJobOperations,System.String,Microsoft.Azure.Batch.Protocol.Models.JobListNextOptions)" />
      <MemberSignature Language="F#" Value="static member ListNext : Microsoft.Azure.Batch.Protocol.IJobOperations * string * Microsoft.Azure.Batch.Protocol.Models.JobListNextOptions -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Batch.Protocol.Models.CloudJob&gt;" Usage="Microsoft.Azure.Batch.Protocol.JobOperationsExtensions.ListNext (operations, nextPageLink, jobListNextOptions)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Batch.Protocol.Models.CloudJob&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Batch.Protocol.IJobOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="jobListNextOptions" Type="Microsoft.Azure.Batch.Protocol.Models.JobListNextOptions" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="b12dc-242">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="b12dc-242">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="b12dc-243">Die "NextLink" aus dem vorherigen erfolgreichen Aufruf List-Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="b12dc-243">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="jobListNextOptions">
            <span data-ttu-id="b12dc-244">Zusätzliche Parameter für den Vorgang</span><span class="sxs-lookup"><span data-stu-id="b12dc-244">Additional parameters for the operation</span></span>
            </param>
        <summary>
            <span data-ttu-id="b12dc-245">Zeigt eine Liste aller Aufträge in das angegebene Konto.</span><span class="sxs-lookup"><span data-stu-id="b12dc-245">Lists all of the jobs in the specified account.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Batch.Protocol.Models.CloudJob&gt;&gt; ListNextAsync (this Microsoft.Azure.Batch.Protocol.IJobOperations operations, string nextPageLink, Microsoft.Azure.Batch.Protocol.Models.JobListNextOptions jobListNextOptions = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Batch.Protocol.Models.CloudJob&gt;&gt; ListNextAsync(class Microsoft.Azure.Batch.Protocol.IJobOperations operations, string nextPageLink, class Microsoft.Azure.Batch.Protocol.Models.JobListNextOptions jobListNextOptions, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.JobOperationsExtensions.ListNextAsync(Microsoft.Azure.Batch.Protocol.IJobOperations,System.String,Microsoft.Azure.Batch.Protocol.Models.JobListNextOptions,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListNextAsync : Microsoft.Azure.Batch.Protocol.IJobOperations * string * Microsoft.Azure.Batch.Protocol.Models.JobListNextOptions * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Batch.Protocol.Models.CloudJob&gt;&gt;" Usage="Microsoft.Azure.Batch.Protocol.JobOperationsExtensions.ListNextAsync (operations, nextPageLink, jobListNextOptions, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Batch.Protocol.JobOperationsExtensions/&lt;ListNextAsync&gt;d__27))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Batch.Protocol.Models.CloudJob&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Batch.Protocol.IJobOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="jobListNextOptions" Type="Microsoft.Azure.Batch.Protocol.Models.JobListNextOptions" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="b12dc-246">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="b12dc-246">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="b12dc-247">Die "NextLink" aus dem vorherigen erfolgreichen Aufruf List-Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="b12dc-247">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="jobListNextOptions">
            <span data-ttu-id="b12dc-248">Zusätzliche Parameter für den Vorgang</span><span class="sxs-lookup"><span data-stu-id="b12dc-248">Additional parameters for the operation</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="b12dc-249">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="b12dc-249">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="b12dc-250">Zeigt eine Liste aller Aufträge in das angegebene Konto.</span><span class="sxs-lookup"><span data-stu-id="b12dc-250">Lists all of the jobs in the specified account.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListPreparationAndReleaseTaskStatus">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Batch.Protocol.Models.JobPreparationAndReleaseTaskExecutionInformation&gt; ListPreparationAndReleaseTaskStatus (this Microsoft.Azure.Batch.Protocol.IJobOperations operations, string jobId, Microsoft.Azure.Batch.Protocol.Models.JobListPreparationAndReleaseTaskStatusOptions jobListPreparationAndReleaseTaskStatusOptions = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Batch.Protocol.Models.JobPreparationAndReleaseTaskExecutionInformation&gt; ListPreparationAndReleaseTaskStatus(class Microsoft.Azure.Batch.Protocol.IJobOperations operations, string jobId, class Microsoft.Azure.Batch.Protocol.Models.JobListPreparationAndReleaseTaskStatusOptions jobListPreparationAndReleaseTaskStatusOptions) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.JobOperationsExtensions.ListPreparationAndReleaseTaskStatus(Microsoft.Azure.Batch.Protocol.IJobOperations,System.String,Microsoft.Azure.Batch.Protocol.Models.JobListPreparationAndReleaseTaskStatusOptions)" />
      <MemberSignature Language="F#" Value="static member ListPreparationAndReleaseTaskStatus : Microsoft.Azure.Batch.Protocol.IJobOperations * string * Microsoft.Azure.Batch.Protocol.Models.JobListPreparationAndReleaseTaskStatusOptions -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Batch.Protocol.Models.JobPreparationAndReleaseTaskExecutionInformation&gt;" Usage="Microsoft.Azure.Batch.Protocol.JobOperationsExtensions.ListPreparationAndReleaseTaskStatus (operations, jobId, jobListPreparationAndReleaseTaskStatusOptions)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Batch.Protocol.Models.JobPreparationAndReleaseTaskExecutionInformation&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Batch.Protocol.IJobOperations" RefType="this" />
        <Parameter Name="jobId" Type="System.String" />
        <Parameter Name="jobListPreparationAndReleaseTaskStatusOptions" Type="Microsoft.Azure.Batch.Protocol.Models.JobListPreparationAndReleaseTaskStatusOptions" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="b12dc-251">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="b12dc-251">The operations group for this extension method.</span></span>
            </param>
        <param name="jobId">
            <span data-ttu-id="b12dc-252">Die ID des Auftrags.</span><span class="sxs-lookup"><span data-stu-id="b12dc-252">The ID of the job.</span></span>
            </param>
        <param name="jobListPreparationAndReleaseTaskStatusOptions">
            <span data-ttu-id="b12dc-253">Zusätzliche Parameter für den Vorgang</span><span class="sxs-lookup"><span data-stu-id="b12dc-253">Additional parameters for the operation</span></span>
            </param>
        <summary>
            <span data-ttu-id="b12dc-254">Listet den Ausführungsstatus des Tasks Auftrag Vorbereitung und Version der Auftrag für den angegebenen Auftrag über den Compute-Knoten, auf denen der Auftrag ausgeführt wurde.</span><span class="sxs-lookup"><span data-stu-id="b12dc-254">Lists the execution status of the Job Preparation and Job Release task for the specified job across the compute nodes where the job has run.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="b12dc-255">Diese API gibt des Aufgabenstatus Auftrag Vorbereitung und Version des Auftrags auf allen Serverknoten, die die Auftrag zur Vorbereitung oder Auftrag Release Aufgabe ausgeführt haben.</span><span class="sxs-lookup"><span data-stu-id="b12dc-255">This API returns the Job Preparation and Job Release task status on all compute nodes that have run the Job Preparation or Job Release task.</span></span> <span data-ttu-id="b12dc-256">Dies schließt die Knoten, die zwischenzeitlich aus dem Pool entfernt wurden.</span><span class="sxs-lookup"><span data-stu-id="b12dc-256">This includes nodes which have since been removed from the pool.</span></span> <span data-ttu-id="b12dc-257">Wenn diese API in einem Auftrag besitzt kein Auftrag Vorbereitung oder Auftrag Release Task aufgerufen wird, gibt der Batch-Dienst HTTP-Statuscode 409 (Konflikt) mit einem Fehlercode von JobPreparationTaskNotSpecified zurück.</span><span class="sxs-lookup"><span data-stu-id="b12dc-257">If this API is invoked on a job which has no Job Preparation or Job Release task, the Batch service returns HTTP status code 409 (Conflict) with an error code of JobPreparationTaskNotSpecified.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ListPreparationAndReleaseTaskStatusAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Batch.Protocol.Models.JobPreparationAndReleaseTaskExecutionInformation&gt;&gt; ListPreparationAndReleaseTaskStatusAsync (this Microsoft.Azure.Batch.Protocol.IJobOperations operations, string jobId, Microsoft.Azure.Batch.Protocol.Models.JobListPreparationAndReleaseTaskStatusOptions jobListPreparationAndReleaseTaskStatusOptions = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Batch.Protocol.Models.JobPreparationAndReleaseTaskExecutionInformation&gt;&gt; ListPreparationAndReleaseTaskStatusAsync(class Microsoft.Azure.Batch.Protocol.IJobOperations operations, string jobId, class Microsoft.Azure.Batch.Protocol.Models.JobListPreparationAndReleaseTaskStatusOptions jobListPreparationAndReleaseTaskStatusOptions, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.JobOperationsExtensions.ListPreparationAndReleaseTaskStatusAsync(Microsoft.Azure.Batch.Protocol.IJobOperations,System.String,Microsoft.Azure.Batch.Protocol.Models.JobListPreparationAndReleaseTaskStatusOptions,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListPreparationAndReleaseTaskStatusAsync : Microsoft.Azure.Batch.Protocol.IJobOperations * string * Microsoft.Azure.Batch.Protocol.Models.JobListPreparationAndReleaseTaskStatusOptions * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Batch.Protocol.Models.JobPreparationAndReleaseTaskExecutionInformation&gt;&gt;" Usage="Microsoft.Azure.Batch.Protocol.JobOperationsExtensions.ListPreparationAndReleaseTaskStatusAsync (operations, jobId, jobListPreparationAndReleaseTaskStatusOptions, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Batch.Protocol.JobOperationsExtensions/&lt;ListPreparationAndReleaseTaskStatusAsync&gt;d__23))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Batch.Protocol.Models.JobPreparationAndReleaseTaskExecutionInformation&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Batch.Protocol.IJobOperations" RefType="this" />
        <Parameter Name="jobId" Type="System.String" />
        <Parameter Name="jobListPreparationAndReleaseTaskStatusOptions" Type="Microsoft.Azure.Batch.Protocol.Models.JobListPreparationAndReleaseTaskStatusOptions" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="b12dc-258">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="b12dc-258">The operations group for this extension method.</span></span>
            </param>
        <param name="jobId">
            <span data-ttu-id="b12dc-259">Die ID des Auftrags.</span><span class="sxs-lookup"><span data-stu-id="b12dc-259">The ID of the job.</span></span>
            </param>
        <param name="jobListPreparationAndReleaseTaskStatusOptions">
            <span data-ttu-id="b12dc-260">Zusätzliche Parameter für den Vorgang</span><span class="sxs-lookup"><span data-stu-id="b12dc-260">Additional parameters for the operation</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="b12dc-261">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="b12dc-261">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="b12dc-262">Listet den Ausführungsstatus des Tasks Auftrag Vorbereitung und Version der Auftrag für den angegebenen Auftrag über den Compute-Knoten, auf denen der Auftrag ausgeführt wurde.</span><span class="sxs-lookup"><span data-stu-id="b12dc-262">Lists the execution status of the Job Preparation and Job Release task for the specified job across the compute nodes where the job has run.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="b12dc-263">Diese API gibt des Aufgabenstatus Auftrag Vorbereitung und Version des Auftrags auf allen Serverknoten, die die Auftrag zur Vorbereitung oder Auftrag Release Aufgabe ausgeführt haben.</span><span class="sxs-lookup"><span data-stu-id="b12dc-263">This API returns the Job Preparation and Job Release task status on all compute nodes that have run the Job Preparation or Job Release task.</span></span> <span data-ttu-id="b12dc-264">Dies schließt die Knoten, die zwischenzeitlich aus dem Pool entfernt wurden.</span><span class="sxs-lookup"><span data-stu-id="b12dc-264">This includes nodes which have since been removed from the pool.</span></span> <span data-ttu-id="b12dc-265">Wenn diese API in einem Auftrag besitzt kein Auftrag Vorbereitung oder Auftrag Release Task aufgerufen wird, gibt der Batch-Dienst HTTP-Statuscode 409 (Konflikt) mit einem Fehlercode von JobPreparationTaskNotSpecified zurück.</span><span class="sxs-lookup"><span data-stu-id="b12dc-265">If this API is invoked on a job which has no Job Preparation or Job Release task, the Batch service returns HTTP status code 409 (Conflict) with an error code of JobPreparationTaskNotSpecified.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ListPreparationAndReleaseTaskStatusNext">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Batch.Protocol.Models.JobPreparationAndReleaseTaskExecutionInformation&gt; ListPreparationAndReleaseTaskStatusNext (this Microsoft.Azure.Batch.Protocol.IJobOperations operations, string nextPageLink, Microsoft.Azure.Batch.Protocol.Models.JobListPreparationAndReleaseTaskStatusNextOptions jobListPreparationAndReleaseTaskStatusNextOptions = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Batch.Protocol.Models.JobPreparationAndReleaseTaskExecutionInformation&gt; ListPreparationAndReleaseTaskStatusNext(class Microsoft.Azure.Batch.Protocol.IJobOperations operations, string nextPageLink, class Microsoft.Azure.Batch.Protocol.Models.JobListPreparationAndReleaseTaskStatusNextOptions jobListPreparationAndReleaseTaskStatusNextOptions) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.JobOperationsExtensions.ListPreparationAndReleaseTaskStatusNext(Microsoft.Azure.Batch.Protocol.IJobOperations,System.String,Microsoft.Azure.Batch.Protocol.Models.JobListPreparationAndReleaseTaskStatusNextOptions)" />
      <MemberSignature Language="F#" Value="static member ListPreparationAndReleaseTaskStatusNext : Microsoft.Azure.Batch.Protocol.IJobOperations * string * Microsoft.Azure.Batch.Protocol.Models.JobListPreparationAndReleaseTaskStatusNextOptions -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Batch.Protocol.Models.JobPreparationAndReleaseTaskExecutionInformation&gt;" Usage="Microsoft.Azure.Batch.Protocol.JobOperationsExtensions.ListPreparationAndReleaseTaskStatusNext (operations, nextPageLink, jobListPreparationAndReleaseTaskStatusNextOptions)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Batch.Protocol.Models.JobPreparationAndReleaseTaskExecutionInformation&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Batch.Protocol.IJobOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="jobListPreparationAndReleaseTaskStatusNextOptions" Type="Microsoft.Azure.Batch.Protocol.Models.JobListPreparationAndReleaseTaskStatusNextOptions" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="b12dc-266">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="b12dc-266">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="b12dc-267">Die "NextLink" aus dem vorherigen erfolgreichen Aufruf List-Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="b12dc-267">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="jobListPreparationAndReleaseTaskStatusNextOptions">
            <span data-ttu-id="b12dc-268">Zusätzliche Parameter für den Vorgang</span><span class="sxs-lookup"><span data-stu-id="b12dc-268">Additional parameters for the operation</span></span>
            </param>
        <summary>
            <span data-ttu-id="b12dc-269">Listet den Ausführungsstatus des Tasks Auftrag Vorbereitung und Version der Auftrag für den angegebenen Auftrag über den Compute-Knoten, auf denen der Auftrag ausgeführt wurde.</span><span class="sxs-lookup"><span data-stu-id="b12dc-269">Lists the execution status of the Job Preparation and Job Release task for the specified job across the compute nodes where the job has run.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="b12dc-270">Diese API gibt des Aufgabenstatus Auftrag Vorbereitung und Version des Auftrags auf allen Serverknoten, die die Auftrag zur Vorbereitung oder Auftrag Release Aufgabe ausgeführt haben.</span><span class="sxs-lookup"><span data-stu-id="b12dc-270">This API returns the Job Preparation and Job Release task status on all compute nodes that have run the Job Preparation or Job Release task.</span></span> <span data-ttu-id="b12dc-271">Dies schließt die Knoten, die zwischenzeitlich aus dem Pool entfernt wurden.</span><span class="sxs-lookup"><span data-stu-id="b12dc-271">This includes nodes which have since been removed from the pool.</span></span> <span data-ttu-id="b12dc-272">Wenn diese API in einem Auftrag besitzt kein Auftrag Vorbereitung oder Auftrag Release Task aufgerufen wird, gibt der Batch-Dienst HTTP-Statuscode 409 (Konflikt) mit einem Fehlercode von JobPreparationTaskNotSpecified zurück.</span><span class="sxs-lookup"><span data-stu-id="b12dc-272">If this API is invoked on a job which has no Job Preparation or Job Release task, the Batch service returns HTTP status code 409 (Conflict) with an error code of JobPreparationTaskNotSpecified.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ListPreparationAndReleaseTaskStatusNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Batch.Protocol.Models.JobPreparationAndReleaseTaskExecutionInformation&gt;&gt; ListPreparationAndReleaseTaskStatusNextAsync (this Microsoft.Azure.Batch.Protocol.IJobOperations operations, string nextPageLink, Microsoft.Azure.Batch.Protocol.Models.JobListPreparationAndReleaseTaskStatusNextOptions jobListPreparationAndReleaseTaskStatusNextOptions = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Batch.Protocol.Models.JobPreparationAndReleaseTaskExecutionInformation&gt;&gt; ListPreparationAndReleaseTaskStatusNextAsync(class Microsoft.Azure.Batch.Protocol.IJobOperations operations, string nextPageLink, class Microsoft.Azure.Batch.Protocol.Models.JobListPreparationAndReleaseTaskStatusNextOptions jobListPreparationAndReleaseTaskStatusNextOptions, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.JobOperationsExtensions.ListPreparationAndReleaseTaskStatusNextAsync(Microsoft.Azure.Batch.Protocol.IJobOperations,System.String,Microsoft.Azure.Batch.Protocol.Models.JobListPreparationAndReleaseTaskStatusNextOptions,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListPreparationAndReleaseTaskStatusNextAsync : Microsoft.Azure.Batch.Protocol.IJobOperations * string * Microsoft.Azure.Batch.Protocol.Models.JobListPreparationAndReleaseTaskStatusNextOptions * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Batch.Protocol.Models.JobPreparationAndReleaseTaskExecutionInformation&gt;&gt;" Usage="Microsoft.Azure.Batch.Protocol.JobOperationsExtensions.ListPreparationAndReleaseTaskStatusNextAsync (operations, nextPageLink, jobListPreparationAndReleaseTaskStatusNextOptions, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Batch.Protocol.JobOperationsExtensions/&lt;ListPreparationAndReleaseTaskStatusNextAsync&gt;d__31))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Batch.Protocol.Models.JobPreparationAndReleaseTaskExecutionInformation&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Batch.Protocol.IJobOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="jobListPreparationAndReleaseTaskStatusNextOptions" Type="Microsoft.Azure.Batch.Protocol.Models.JobListPreparationAndReleaseTaskStatusNextOptions" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="b12dc-273">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="b12dc-273">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="b12dc-274">Die "NextLink" aus dem vorherigen erfolgreichen Aufruf List-Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="b12dc-274">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="jobListPreparationAndReleaseTaskStatusNextOptions">
            <span data-ttu-id="b12dc-275">Zusätzliche Parameter für den Vorgang</span><span class="sxs-lookup"><span data-stu-id="b12dc-275">Additional parameters for the operation</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="b12dc-276">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="b12dc-276">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="b12dc-277">Listet den Ausführungsstatus des Tasks Auftrag Vorbereitung und Version der Auftrag für den angegebenen Auftrag über den Compute-Knoten, auf denen der Auftrag ausgeführt wurde.</span><span class="sxs-lookup"><span data-stu-id="b12dc-277">Lists the execution status of the Job Preparation and Job Release task for the specified job across the compute nodes where the job has run.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="b12dc-278">Diese API gibt des Aufgabenstatus Auftrag Vorbereitung und Version des Auftrags auf allen Serverknoten, die die Auftrag zur Vorbereitung oder Auftrag Release Aufgabe ausgeführt haben.</span><span class="sxs-lookup"><span data-stu-id="b12dc-278">This API returns the Job Preparation and Job Release task status on all compute nodes that have run the Job Preparation or Job Release task.</span></span> <span data-ttu-id="b12dc-279">Dies schließt die Knoten, die zwischenzeitlich aus dem Pool entfernt wurden.</span><span class="sxs-lookup"><span data-stu-id="b12dc-279">This includes nodes which have since been removed from the pool.</span></span> <span data-ttu-id="b12dc-280">Wenn diese API in einem Auftrag besitzt kein Auftrag Vorbereitung oder Auftrag Release Task aufgerufen wird, gibt der Batch-Dienst HTTP-Statuscode 409 (Konflikt) mit einem Fehlercode von JobPreparationTaskNotSpecified zurück.</span><span class="sxs-lookup"><span data-stu-id="b12dc-280">If this API is invoked on a job which has no Job Preparation or Job Release task, the Batch service returns HTTP status code 409 (Conflict) with an error code of JobPreparationTaskNotSpecified.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="Patch">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Batch.Protocol.Models.JobPatchHeaders Patch (this Microsoft.Azure.Batch.Protocol.IJobOperations operations, string jobId, Microsoft.Azure.Batch.Protocol.Models.JobPatchParameter jobPatchParameter, Microsoft.Azure.Batch.Protocol.Models.JobPatchOptions jobPatchOptions = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Batch.Protocol.Models.JobPatchHeaders Patch(class Microsoft.Azure.Batch.Protocol.IJobOperations operations, string jobId, class Microsoft.Azure.Batch.Protocol.Models.JobPatchParameter jobPatchParameter, class Microsoft.Azure.Batch.Protocol.Models.JobPatchOptions jobPatchOptions) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.JobOperationsExtensions.Patch(Microsoft.Azure.Batch.Protocol.IJobOperations,System.String,Microsoft.Azure.Batch.Protocol.Models.JobPatchParameter,Microsoft.Azure.Batch.Protocol.Models.JobPatchOptions)" />
      <MemberSignature Language="F#" Value="static member Patch : Microsoft.Azure.Batch.Protocol.IJobOperations * string * Microsoft.Azure.Batch.Protocol.Models.JobPatchParameter * Microsoft.Azure.Batch.Protocol.Models.JobPatchOptions -&gt; Microsoft.Azure.Batch.Protocol.Models.JobPatchHeaders" Usage="Microsoft.Azure.Batch.Protocol.JobOperationsExtensions.Patch (operations, jobId, jobPatchParameter, jobPatchOptions)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.Protocol.Models.JobPatchHeaders</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Batch.Protocol.IJobOperations" RefType="this" />
        <Parameter Name="jobId" Type="System.String" />
        <Parameter Name="jobPatchParameter" Type="Microsoft.Azure.Batch.Protocol.Models.JobPatchParameter" />
        <Parameter Name="jobPatchOptions" Type="Microsoft.Azure.Batch.Protocol.Models.JobPatchOptions" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="b12dc-281">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="b12dc-281">The operations group for this extension method.</span></span>
            </param>
        <param name="jobId">
            <span data-ttu-id="b12dc-282">Die ID des Auftrags, dessen Eigenschaften Sie aktualisieren möchten.</span><span class="sxs-lookup"><span data-stu-id="b12dc-282">The ID of the job whose properties you want to update.</span></span>
            </param>
        <param name="jobPatchParameter">
            <span data-ttu-id="b12dc-283">Die Parameter für die Anforderung.</span><span class="sxs-lookup"><span data-stu-id="b12dc-283">The parameters for the request.</span></span>
            </param>
        <param name="jobPatchOptions">
            <span data-ttu-id="b12dc-284">Zusätzliche Parameter für den Vorgang</span><span class="sxs-lookup"><span data-stu-id="b12dc-284">Additional parameters for the operation</span></span>
            </param>
        <summary>
            <span data-ttu-id="b12dc-285">Aktualisiert die Eigenschaften des angegebenen Auftrags.</span><span class="sxs-lookup"><span data-stu-id="b12dc-285">Updates the properties of the specified job.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="b12dc-286">Dies ersetzt die Auftragseigenschaften in der Anforderung angegeben.</span><span class="sxs-lookup"><span data-stu-id="b12dc-286">This replaces only the job properties specified in the request.</span></span> <span data-ttu-id="b12dc-287">Beispielsweise behält Wenn weist Einschränkungen auf der Auftrag und eine Anforderung keine Einschränkungen-Element gibt, klicken Sie dann der Auftrag die vorhandenen Einschränkungen.</span><span class="sxs-lookup"><span data-stu-id="b12dc-287">For example, if the job has constraints, and a request does not specify the constraints element, then the job keeps the existing constraints.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="PatchAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Batch.Protocol.Models.JobPatchHeaders&gt; PatchAsync (this Microsoft.Azure.Batch.Protocol.IJobOperations operations, string jobId, Microsoft.Azure.Batch.Protocol.Models.JobPatchParameter jobPatchParameter, Microsoft.Azure.Batch.Protocol.Models.JobPatchOptions jobPatchOptions = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Batch.Protocol.Models.JobPatchHeaders&gt; PatchAsync(class Microsoft.Azure.Batch.Protocol.IJobOperations operations, string jobId, class Microsoft.Azure.Batch.Protocol.Models.JobPatchParameter jobPatchParameter, class Microsoft.Azure.Batch.Protocol.Models.JobPatchOptions jobPatchOptions, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.JobOperationsExtensions.PatchAsync(Microsoft.Azure.Batch.Protocol.IJobOperations,System.String,Microsoft.Azure.Batch.Protocol.Models.JobPatchParameter,Microsoft.Azure.Batch.Protocol.Models.JobPatchOptions,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member PatchAsync : Microsoft.Azure.Batch.Protocol.IJobOperations * string * Microsoft.Azure.Batch.Protocol.Models.JobPatchParameter * Microsoft.Azure.Batch.Protocol.Models.JobPatchOptions * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Batch.Protocol.Models.JobPatchHeaders&gt;" Usage="Microsoft.Azure.Batch.Protocol.JobOperationsExtensions.PatchAsync (operations, jobId, jobPatchParameter, jobPatchOptions, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Batch.Protocol.JobOperationsExtensions/&lt;PatchAsync&gt;d__7))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Batch.Protocol.Models.JobPatchHeaders&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Batch.Protocol.IJobOperations" RefType="this" />
        <Parameter Name="jobId" Type="System.String" />
        <Parameter Name="jobPatchParameter" Type="Microsoft.Azure.Batch.Protocol.Models.JobPatchParameter" />
        <Parameter Name="jobPatchOptions" Type="Microsoft.Azure.Batch.Protocol.Models.JobPatchOptions" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="b12dc-288">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="b12dc-288">The operations group for this extension method.</span></span>
            </param>
        <param name="jobId">
            <span data-ttu-id="b12dc-289">Die ID des Auftrags, dessen Eigenschaften Sie aktualisieren möchten.</span><span class="sxs-lookup"><span data-stu-id="b12dc-289">The ID of the job whose properties you want to update.</span></span>
            </param>
        <param name="jobPatchParameter">
            <span data-ttu-id="b12dc-290">Die Parameter für die Anforderung.</span><span class="sxs-lookup"><span data-stu-id="b12dc-290">The parameters for the request.</span></span>
            </param>
        <param name="jobPatchOptions">
            <span data-ttu-id="b12dc-291">Zusätzliche Parameter für den Vorgang</span><span class="sxs-lookup"><span data-stu-id="b12dc-291">Additional parameters for the operation</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="b12dc-292">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="b12dc-292">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="b12dc-293">Aktualisiert die Eigenschaften des angegebenen Auftrags.</span><span class="sxs-lookup"><span data-stu-id="b12dc-293">Updates the properties of the specified job.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="b12dc-294">Dies ersetzt die Auftragseigenschaften in der Anforderung angegeben.</span><span class="sxs-lookup"><span data-stu-id="b12dc-294">This replaces only the job properties specified in the request.</span></span> <span data-ttu-id="b12dc-295">Beispielsweise behält Wenn weist Einschränkungen auf der Auftrag und eine Anforderung keine Einschränkungen-Element gibt, klicken Sie dann der Auftrag die vorhandenen Einschränkungen.</span><span class="sxs-lookup"><span data-stu-id="b12dc-295">For example, if the job has constraints, and a request does not specify the constraints element, then the job keeps the existing constraints.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="Terminate">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Batch.Protocol.Models.JobTerminateHeaders Terminate (this Microsoft.Azure.Batch.Protocol.IJobOperations operations, string jobId, string terminateReason = null, Microsoft.Azure.Batch.Protocol.Models.JobTerminateOptions jobTerminateOptions = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Batch.Protocol.Models.JobTerminateHeaders Terminate(class Microsoft.Azure.Batch.Protocol.IJobOperations operations, string jobId, string terminateReason, class Microsoft.Azure.Batch.Protocol.Models.JobTerminateOptions jobTerminateOptions) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.JobOperationsExtensions.Terminate(Microsoft.Azure.Batch.Protocol.IJobOperations,System.String,System.String,Microsoft.Azure.Batch.Protocol.Models.JobTerminateOptions)" />
      <MemberSignature Language="F#" Value="static member Terminate : Microsoft.Azure.Batch.Protocol.IJobOperations * string * string * Microsoft.Azure.Batch.Protocol.Models.JobTerminateOptions -&gt; Microsoft.Azure.Batch.Protocol.Models.JobTerminateHeaders" Usage="Microsoft.Azure.Batch.Protocol.JobOperationsExtensions.Terminate (operations, jobId, terminateReason, jobTerminateOptions)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.Protocol.Models.JobTerminateHeaders</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Batch.Protocol.IJobOperations" RefType="this" />
        <Parameter Name="jobId" Type="System.String" />
        <Parameter Name="terminateReason" Type="System.String" />
        <Parameter Name="jobTerminateOptions" Type="Microsoft.Azure.Batch.Protocol.Models.JobTerminateOptions" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="b12dc-296">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="b12dc-296">The operations group for this extension method.</span></span>
            </param>
        <param name="jobId">
            <span data-ttu-id="b12dc-297">Die ID des Auftrags beendet werden soll.</span><span class="sxs-lookup"><span data-stu-id="b12dc-297">The ID of the job to terminate.</span></span>
            </param>
        <param name="terminateReason">
            <span data-ttu-id="b12dc-298">Der Text, der als TerminateReason für den Auftrag angezeigt werden sollen.</span><span class="sxs-lookup"><span data-stu-id="b12dc-298">The text you want to appear as the job's TerminateReason.</span></span> <span data-ttu-id="b12dc-299">Der Standardwert ist "UserTerminate".</span><span class="sxs-lookup"><span data-stu-id="b12dc-299">The default is 'UserTerminate'.</span></span>
            </param>
        <param name="jobTerminateOptions">
            <span data-ttu-id="b12dc-300">Zusätzliche Parameter für den Vorgang</span><span class="sxs-lookup"><span data-stu-id="b12dc-300">Additional parameters for the operation</span></span>
            </param>
        <summary>
            <span data-ttu-id="b12dc-301">Beendet den angegebenen Auftrag als abgeschlossen gekennzeichnet.</span><span class="sxs-lookup"><span data-stu-id="b12dc-301">Terminates the specified job, marking it as completed.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="b12dc-302">Wenn eine Auftrag beenden-Anforderung empfangen wird, wird der Batch-Dienst der Auftrag in den abschließenden Zustand.</span><span class="sxs-lookup"><span data-stu-id="b12dc-302">When a Terminate Job request is received, the Batch service sets the job to the terminating state.</span></span> <span data-ttu-id="b12dc-303">Der Batch-Dienst aktiven oder ausgeführten Aufgaben im Zusammenhang mit der Auftrag beendet und führt alle erforderlichen Aufgaben für die Version des Auftrags.</span><span class="sxs-lookup"><span data-stu-id="b12dc-303">The Batch service then terminates any active or running tasks associated with the job, and runs any required Job Release tasks.</span></span> <span data-ttu-id="b12dc-304">Der Auftrag wird in den abgeschlossenen Zustand versetzt.</span><span class="sxs-lookup"><span data-stu-id="b12dc-304">The job then moves into the completed state.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="TerminateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Batch.Protocol.Models.JobTerminateHeaders&gt; TerminateAsync (this Microsoft.Azure.Batch.Protocol.IJobOperations operations, string jobId, string terminateReason = null, Microsoft.Azure.Batch.Protocol.Models.JobTerminateOptions jobTerminateOptions = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Batch.Protocol.Models.JobTerminateHeaders&gt; TerminateAsync(class Microsoft.Azure.Batch.Protocol.IJobOperations operations, string jobId, string terminateReason, class Microsoft.Azure.Batch.Protocol.Models.JobTerminateOptions jobTerminateOptions, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.JobOperationsExtensions.TerminateAsync(Microsoft.Azure.Batch.Protocol.IJobOperations,System.String,System.String,Microsoft.Azure.Batch.Protocol.Models.JobTerminateOptions,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member TerminateAsync : Microsoft.Azure.Batch.Protocol.IJobOperations * string * string * Microsoft.Azure.Batch.Protocol.Models.JobTerminateOptions * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Batch.Protocol.Models.JobTerminateHeaders&gt;" Usage="Microsoft.Azure.Batch.Protocol.JobOperationsExtensions.TerminateAsync (operations, jobId, terminateReason, jobTerminateOptions, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Batch.Protocol.JobOperationsExtensions/&lt;TerminateAsync&gt;d__15))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Batch.Protocol.Models.JobTerminateHeaders&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Batch.Protocol.IJobOperations" RefType="this" />
        <Parameter Name="jobId" Type="System.String" />
        <Parameter Name="terminateReason" Type="System.String" />
        <Parameter Name="jobTerminateOptions" Type="Microsoft.Azure.Batch.Protocol.Models.JobTerminateOptions" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="b12dc-305">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="b12dc-305">The operations group for this extension method.</span></span>
            </param>
        <param name="jobId">
            <span data-ttu-id="b12dc-306">Die ID des Auftrags beendet werden soll.</span><span class="sxs-lookup"><span data-stu-id="b12dc-306">The ID of the job to terminate.</span></span>
            </param>
        <param name="terminateReason">
            <span data-ttu-id="b12dc-307">Der Text, der als TerminateReason für den Auftrag angezeigt werden sollen.</span><span class="sxs-lookup"><span data-stu-id="b12dc-307">The text you want to appear as the job's TerminateReason.</span></span> <span data-ttu-id="b12dc-308">Der Standardwert ist "UserTerminate".</span><span class="sxs-lookup"><span data-stu-id="b12dc-308">The default is 'UserTerminate'.</span></span>
            </param>
        <param name="jobTerminateOptions">
            <span data-ttu-id="b12dc-309">Zusätzliche Parameter für den Vorgang</span><span class="sxs-lookup"><span data-stu-id="b12dc-309">Additional parameters for the operation</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="b12dc-310">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="b12dc-310">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="b12dc-311">Beendet den angegebenen Auftrag als abgeschlossen gekennzeichnet.</span><span class="sxs-lookup"><span data-stu-id="b12dc-311">Terminates the specified job, marking it as completed.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="b12dc-312">Wenn eine Auftrag beenden-Anforderung empfangen wird, wird der Batch-Dienst der Auftrag in den abschließenden Zustand.</span><span class="sxs-lookup"><span data-stu-id="b12dc-312">When a Terminate Job request is received, the Batch service sets the job to the terminating state.</span></span> <span data-ttu-id="b12dc-313">Der Batch-Dienst aktiven oder ausgeführten Aufgaben im Zusammenhang mit der Auftrag beendet und führt alle erforderlichen Aufgaben für die Version des Auftrags.</span><span class="sxs-lookup"><span data-stu-id="b12dc-313">The Batch service then terminates any active or running tasks associated with the job, and runs any required Job Release tasks.</span></span> <span data-ttu-id="b12dc-314">Der Auftrag wird in den abgeschlossenen Zustand versetzt.</span><span class="sxs-lookup"><span data-stu-id="b12dc-314">The job then moves into the completed state.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="Update">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Batch.Protocol.Models.JobUpdateHeaders Update (this Microsoft.Azure.Batch.Protocol.IJobOperations operations, string jobId, Microsoft.Azure.Batch.Protocol.Models.JobUpdateParameter jobUpdateParameter, Microsoft.Azure.Batch.Protocol.Models.JobUpdateOptions jobUpdateOptions = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Batch.Protocol.Models.JobUpdateHeaders Update(class Microsoft.Azure.Batch.Protocol.IJobOperations operations, string jobId, class Microsoft.Azure.Batch.Protocol.Models.JobUpdateParameter jobUpdateParameter, class Microsoft.Azure.Batch.Protocol.Models.JobUpdateOptions jobUpdateOptions) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.JobOperationsExtensions.Update(Microsoft.Azure.Batch.Protocol.IJobOperations,System.String,Microsoft.Azure.Batch.Protocol.Models.JobUpdateParameter,Microsoft.Azure.Batch.Protocol.Models.JobUpdateOptions)" />
      <MemberSignature Language="F#" Value="static member Update : Microsoft.Azure.Batch.Protocol.IJobOperations * string * Microsoft.Azure.Batch.Protocol.Models.JobUpdateParameter * Microsoft.Azure.Batch.Protocol.Models.JobUpdateOptions -&gt; Microsoft.Azure.Batch.Protocol.Models.JobUpdateHeaders" Usage="Microsoft.Azure.Batch.Protocol.JobOperationsExtensions.Update (operations, jobId, jobUpdateParameter, jobUpdateOptions)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.Protocol.Models.JobUpdateHeaders</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Batch.Protocol.IJobOperations" RefType="this" />
        <Parameter Name="jobId" Type="System.String" />
        <Parameter Name="jobUpdateParameter" Type="Microsoft.Azure.Batch.Protocol.Models.JobUpdateParameter" />
        <Parameter Name="jobUpdateOptions" Type="Microsoft.Azure.Batch.Protocol.Models.JobUpdateOptions" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="b12dc-315">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="b12dc-315">The operations group for this extension method.</span></span>
            </param>
        <param name="jobId">
            <span data-ttu-id="b12dc-316">Die ID des Auftrags, dessen Eigenschaften Sie aktualisieren möchten.</span><span class="sxs-lookup"><span data-stu-id="b12dc-316">The ID of the job whose properties you want to update.</span></span>
            </param>
        <param name="jobUpdateParameter">
            <span data-ttu-id="b12dc-317">Die Parameter für die Anforderung.</span><span class="sxs-lookup"><span data-stu-id="b12dc-317">The parameters for the request.</span></span>
            </param>
        <param name="jobUpdateOptions">
            <span data-ttu-id="b12dc-318">Zusätzliche Parameter für den Vorgang</span><span class="sxs-lookup"><span data-stu-id="b12dc-318">Additional parameters for the operation</span></span>
            </param>
        <summary>
            <span data-ttu-id="b12dc-319">Aktualisiert die Eigenschaften des angegebenen Auftrags.</span><span class="sxs-lookup"><span data-stu-id="b12dc-319">Updates the properties of the specified job.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="b12dc-320">Vollständig ersetzt alle aktualisierbaren Eigenschaften des Auftrags.</span><span class="sxs-lookup"><span data-stu-id="b12dc-320">This fully replaces all the updateable properties of the job.</span></span> <span data-ttu-id="b12dc-321">Beispielsweise entfernt verfügt der Auftrag zugeordnete Einschränkungen und Einschränkungen bei dieser Anforderung nicht angegeben ist, klicken Sie dann der Batch-Dienst die vorhandenen Einschränkungen.</span><span class="sxs-lookup"><span data-stu-id="b12dc-321">For example, if the job has constraints associated with it and if constraints is not specified with this request, then the Batch service will remove the existing constraints.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="UpdateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Batch.Protocol.Models.JobUpdateHeaders&gt; UpdateAsync (this Microsoft.Azure.Batch.Protocol.IJobOperations operations, string jobId, Microsoft.Azure.Batch.Protocol.Models.JobUpdateParameter jobUpdateParameter, Microsoft.Azure.Batch.Protocol.Models.JobUpdateOptions jobUpdateOptions = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Batch.Protocol.Models.JobUpdateHeaders&gt; UpdateAsync(class Microsoft.Azure.Batch.Protocol.IJobOperations operations, string jobId, class Microsoft.Azure.Batch.Protocol.Models.JobUpdateParameter jobUpdateParameter, class Microsoft.Azure.Batch.Protocol.Models.JobUpdateOptions jobUpdateOptions, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.JobOperationsExtensions.UpdateAsync(Microsoft.Azure.Batch.Protocol.IJobOperations,System.String,Microsoft.Azure.Batch.Protocol.Models.JobUpdateParameter,Microsoft.Azure.Batch.Protocol.Models.JobUpdateOptions,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member UpdateAsync : Microsoft.Azure.Batch.Protocol.IJobOperations * string * Microsoft.Azure.Batch.Protocol.Models.JobUpdateParameter * Microsoft.Azure.Batch.Protocol.Models.JobUpdateOptions * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Batch.Protocol.Models.JobUpdateHeaders&gt;" Usage="Microsoft.Azure.Batch.Protocol.JobOperationsExtensions.UpdateAsync (operations, jobId, jobUpdateParameter, jobUpdateOptions, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Batch.Protocol.JobOperationsExtensions/&lt;UpdateAsync&gt;d__9))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Batch.Protocol.Models.JobUpdateHeaders&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Batch.Protocol.IJobOperations" RefType="this" />
        <Parameter Name="jobId" Type="System.String" />
        <Parameter Name="jobUpdateParameter" Type="Microsoft.Azure.Batch.Protocol.Models.JobUpdateParameter" />
        <Parameter Name="jobUpdateOptions" Type="Microsoft.Azure.Batch.Protocol.Models.JobUpdateOptions" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="b12dc-322">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="b12dc-322">The operations group for this extension method.</span></span>
            </param>
        <param name="jobId">
            <span data-ttu-id="b12dc-323">Die ID des Auftrags, dessen Eigenschaften Sie aktualisieren möchten.</span><span class="sxs-lookup"><span data-stu-id="b12dc-323">The ID of the job whose properties you want to update.</span></span>
            </param>
        <param name="jobUpdateParameter">
            <span data-ttu-id="b12dc-324">Die Parameter für die Anforderung.</span><span class="sxs-lookup"><span data-stu-id="b12dc-324">The parameters for the request.</span></span>
            </param>
        <param name="jobUpdateOptions">
            <span data-ttu-id="b12dc-325">Zusätzliche Parameter für den Vorgang</span><span class="sxs-lookup"><span data-stu-id="b12dc-325">Additional parameters for the operation</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="b12dc-326">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="b12dc-326">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="b12dc-327">Aktualisiert die Eigenschaften des angegebenen Auftrags.</span><span class="sxs-lookup"><span data-stu-id="b12dc-327">Updates the properties of the specified job.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="b12dc-328">Vollständig ersetzt alle aktualisierbaren Eigenschaften des Auftrags.</span><span class="sxs-lookup"><span data-stu-id="b12dc-328">This fully replaces all the updateable properties of the job.</span></span> <span data-ttu-id="b12dc-329">Beispielsweise entfernt verfügt der Auftrag zugeordnete Einschränkungen und Einschränkungen bei dieser Anforderung nicht angegeben ist, klicken Sie dann der Batch-Dienst die vorhandenen Einschränkungen.</span><span class="sxs-lookup"><span data-stu-id="b12dc-329">For example, if the job has constraints associated with it and if constraints is not specified with this request, then the Batch service will remove the existing constraints.</span></span>
            </remarks>
      </Docs>
    </Member>
  </Members>
</Type>