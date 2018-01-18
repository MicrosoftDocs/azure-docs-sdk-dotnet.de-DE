<Type Name="CloudJob" FullName="Microsoft.Azure.Batch.CloudJob">
  <TypeSignature Language="C#" Value="public class CloudJob : Microsoft.Azure.Batch.IInheritedBehaviors, Microsoft.Azure.Batch.IRefreshable" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit CloudJob extends System.Object implements class Microsoft.Azure.Batch.IInheritedBehaviors, class Microsoft.Azure.Batch.IRefreshable" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Batch.CloudJob" />
  <TypeSignature Language="VB.NET" Value="Public Class CloudJob&#xA;Implements IInheritedBehaviors, IRefreshable" />
  <TypeSignature Language="F#" Value="type CloudJob = class&#xA;    interface IRefreshable&#xA;    interface ITransportObjectProvider&lt;JobAddParameter&gt;&#xA;    interface IInheritedBehaviors&#xA;    interface IPropertyMetadata&#xA;    interface IModifiable&#xA;    interface IReadOnly" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
    <AssemblyVersion>7.1.0.0</AssemblyVersion>
    <AssemblyVersion>8.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces>
    <Interface>
      <InterfaceName>Microsoft.Azure.Batch.IInheritedBehaviors</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.Azure.Batch.IRefreshable</InterfaceName>
    </Interface>
  </Interfaces>
  <Docs>
    <summary>
            <span data-ttu-id="36eb1-101">Ein Azure Batch-Auftrag.</span><span class="sxs-lookup"><span data-stu-id="36eb1-101">An Azure Batch job.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="AddTask">
      <MemberSignature Language="C#" Value="public System.Collections.Concurrent.ConcurrentDictionary&lt;Type,Microsoft.Azure.Batch.IFileStagingArtifact&gt; AddTask (Microsoft.Azure.Batch.CloudTask taskToAdd, System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Collections.Concurrent.ConcurrentDictionary`2&lt;class System.Type, class Microsoft.Azure.Batch.IFileStagingArtifact&gt; AddTask(class Microsoft.Azure.Batch.CloudTask taskToAdd, class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.CloudJob.AddTask(Microsoft.Azure.Batch.CloudTask,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior})" />
      <MemberSignature Language="VB.NET" Value="Public Function AddTask (taskToAdd As CloudTask, Optional additionalBehaviors As IEnumerable(Of BatchClientBehavior) = null) As ConcurrentDictionary(Of Type, IFileStagingArtifact)" />
      <MemberSignature Language="F#" Value="member this.AddTask : Microsoft.Azure.Batch.CloudTask * seq&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; -&gt; System.Collections.Concurrent.ConcurrentDictionary&lt;Type, Microsoft.Azure.Batch.IFileStagingArtifact&gt;" Usage="cloudJob.AddTask (taskToAdd, additionalBehaviors)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Concurrent.ConcurrentDictionary&lt;System.Type,Microsoft.Azure.Batch.IFileStagingArtifact&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="taskToAdd" Type="Microsoft.Azure.Batch.CloudTask" />
        <Parameter Name="additionalBehaviors" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt;" />
      </Parameters>
      <Docs>
        <param name="taskToAdd"><span data-ttu-id="36eb1-102">Das hinzuzufügende <see cref="T:Microsoft.Azure.Batch.CloudTask" />.</span><span class="sxs-lookup"><span data-stu-id="36eb1-102">The <see cref="T:Microsoft.Azure.Batch.CloudTask" /> to add.</span></span></param>
        <param name="additionalBehaviors"><span data-ttu-id="36eb1-103">Eine Auflistung von <see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" /> Instanzen, die für die Batchanforderung-Dienst nach gelten die <see cref="P:Microsoft.Azure.Batch.CloudJob.CustomBehaviors" />.</span><span class="sxs-lookup"><span data-stu-id="36eb1-103">A collection of <see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" /> instances that are applied to the Batch service request after the <see cref="P:Microsoft.Azure.Batch.CloudJob.CustomBehaviors" />.</span></span></param>
        <summary>
            <span data-ttu-id="36eb1-104">Fügt eine einzelne Aufgabe dieser <see cref="T:Microsoft.Azure.Batch.CloudJob" />.</span><span class="sxs-lookup"><span data-stu-id="36eb1-104">Adds a single task to this <see cref="T:Microsoft.Azure.Batch.CloudJob" />.</span></span>  <span data-ttu-id="36eb1-105">Verwenden Sie zum Hinzufügen von mehreren Aufgaben <see cref="M:Microsoft.Azure.Batch.JobOperations.AddTask(System.String,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.CloudTask},Microsoft.Azure.Batch.BatchClientParallelOptions,System.Collections.Concurrent.ConcurrentBag{System.Collections.Concurrent.ConcurrentDictionary{System.Type,Microsoft.Azure.Batch.IFileStagingArtifact}},System.Nullable{System.TimeSpan},System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior})">JobOperations.AddTaskAsync</see>.</span><span class="sxs-lookup"><span data-stu-id="36eb1-105">To add multiple tasks, use <see cref="M:Microsoft.Azure.Batch.JobOperations.AddTask(System.String,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.CloudTask},Microsoft.Azure.Batch.BatchClientParallelOptions,System.Collections.Concurrent.ConcurrentBag{System.Collections.Concurrent.ConcurrentDictionary{System.Type,Microsoft.Azure.Batch.IFileStagingArtifact}},System.Nullable{System.TimeSpan},System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior})">JobOperations.AddTaskAsync</see>.</span></span>
            </summary>
        <returns><span data-ttu-id="36eb1-106">Eine Auflistung von Informationen über die Datei mit dem Stagingprozess (siehe <see cref="P:Microsoft.Azure.Batch.CloudTask.FilesToStage" />).</span><span class="sxs-lookup"><span data-stu-id="36eb1-106">A collection of information about the file staging process (see <see cref="P:Microsoft.Azure.Batch.CloudTask.FilesToStage" />).</span></span>
            <span data-ttu-id="36eb1-107">Weitere Informationen finden Sie unter <see cref="T:Microsoft.Azure.Batch.IFileStagingArtifact" />.</span><span class="sxs-lookup"><span data-stu-id="36eb1-107">For more information see <see cref="T:Microsoft.Azure.Batch.IFileStagingArtifact" />.</span></span></returns>
        <remarks>
          <para>
            <span data-ttu-id="36eb1-108">Jeder Aufruf dieser Methode verursacht eine Anforderung an den Batch-Dienst.</span><span class="sxs-lookup"><span data-stu-id="36eb1-108">Each call to this method incurs a request to the Batch service.</span></span> <span data-ttu-id="36eb1-109">Aus diesem Grund verwenden diese Methode zum Hinzufügen von mehreren Aufgaben ist weniger effizient als die Verwendung einer Bulk add-Methode, und HTTP-Verbindung Einschränkungen verursachen können.</span><span class="sxs-lookup"><span data-stu-id="36eb1-109">Therefore, using this method to add multiple tasks is less efficient than using a bulk add method, and can incur HTTP connection restrictions.</span></span>
            <span data-ttu-id="36eb1-110">Wenn Sie viele dieser Vorgänge parallel ausgeführt werden und clientseitigen Timeouts angezeigt werden (eine <see cref="T:System.Threading.Tasks.TaskCanceledException" />), finden Sie unter http://msdn.microsoft.com/en-us/library/system.net.servicepointmanager.defaultconnectionlimit%28v=vs.110%29.aspx, oder verwenden <see cref="M:Microsoft.Azure.Batch.JobOperations.AddTask(System.String,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.CloudTask},Microsoft.Azure.Batch.BatchClientParallelOptions,System.Collections.Concurrent.ConcurrentBag{System.Collections.Concurrent.ConcurrentDictionary{System.Type,Microsoft.Azure.Batch.IFileStagingArtifact}},System.Nullable{System.TimeSpan},System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior})" />.</span><span class="sxs-lookup"><span data-stu-id="36eb1-110">If you are performing many of these operations in parallel and are seeing client side timeouts (a <see cref="T:System.Threading.Tasks.TaskCanceledException" />), please see http://msdn.microsoft.com/en-us/library/system.net.servicepointmanager.defaultconnectionlimit%28v=vs.110%29.aspx or use <see cref="M:Microsoft.Azure.Batch.JobOperations.AddTask(System.String,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.CloudTask},Microsoft.Azure.Batch.BatchClientParallelOptions,System.Collections.Concurrent.ConcurrentBag{System.Collections.Concurrent.ConcurrentDictionary{System.Type,Microsoft.Azure.Batch.IFileStagingArtifact}},System.Nullable{System.TimeSpan},System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior})" />.</span></span>
            </para>
          <para><span data-ttu-id="36eb1-111">Dies ist ein blockierender Vorgang.</span><span class="sxs-lookup"><span data-stu-id="36eb1-111">This is a blocking operation.</span></span> <span data-ttu-id="36eb1-112">Eine nicht blockierende Entsprechung, finden Sie unter <see cref="M:Microsoft.Azure.Batch.CloudJob.AddTaskAsync(Microsoft.Azure.Batch.CloudTask,System.Collections.Concurrent.ConcurrentDictionary{System.Type,Microsoft.Azure.Batch.IFileStagingArtifact},System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior},System.Threading.CancellationToken)" />.</span><span class="sxs-lookup"><span data-stu-id="36eb1-112">For a non-blocking equivalent, see <see cref="M:Microsoft.Azure.Batch.CloudJob.AddTaskAsync(Microsoft.Azure.Batch.CloudTask,System.Collections.Concurrent.ConcurrentDictionary{System.Type,Microsoft.Azure.Batch.IFileStagingArtifact},System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior},System.Threading.CancellationToken)" />.</span></span></para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="AddTask">
      <MemberSignature Language="C#" Value="public void AddTask (System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.CloudTask&gt; tasksToAdd, Microsoft.Azure.Batch.BatchClientParallelOptions parallelOptions = null, System.Collections.Concurrent.ConcurrentBag&lt;System.Collections.Concurrent.ConcurrentDictionary&lt;Type,Microsoft.Azure.Batch.IFileStagingArtifact&gt;&gt; fileStagingArtifacts = null, Nullable&lt;TimeSpan&gt; timeout = null, System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance void AddTask(class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Batch.CloudTask&gt; tasksToAdd, class Microsoft.Azure.Batch.BatchClientParallelOptions parallelOptions, class System.Collections.Concurrent.ConcurrentBag`1&lt;class System.Collections.Concurrent.ConcurrentDictionary`2&lt;class System.Type, class Microsoft.Azure.Batch.IFileStagingArtifact&gt;&gt; fileStagingArtifacts, valuetype System.Nullable`1&lt;valuetype System.TimeSpan&gt; timeout, class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.CloudJob.AddTask(System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.CloudTask},Microsoft.Azure.Batch.BatchClientParallelOptions,System.Collections.Concurrent.ConcurrentBag{System.Collections.Concurrent.ConcurrentDictionary{System.Type,Microsoft.Azure.Batch.IFileStagingArtifact}},System.Nullable{System.TimeSpan},System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior})" />
      <MemberSignature Language="VB.NET" Value="Public Sub AddTask (tasksToAdd As IEnumerable(Of CloudTask), Optional parallelOptions As BatchClientParallelOptions = null, Optional fileStagingArtifacts As ConcurrentBag(Of ConcurrentDictionary(Of Type, IFileStagingArtifact)) = null, Optional timeout As Nullable(Of TimeSpan) = null, Optional additionalBehaviors As IEnumerable(Of BatchClientBehavior) = null)" />
      <MemberSignature Language="F#" Value="member this.AddTask : seq&lt;Microsoft.Azure.Batch.CloudTask&gt; * Microsoft.Azure.Batch.BatchClientParallelOptions * System.Collections.Concurrent.ConcurrentBag&lt;System.Collections.Concurrent.ConcurrentDictionary&lt;Type, Microsoft.Azure.Batch.IFileStagingArtifact&gt;&gt; * Nullable&lt;TimeSpan&gt; * seq&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; -&gt; unit" Usage="cloudJob.AddTask (tasksToAdd, parallelOptions, fileStagingArtifacts, timeout, additionalBehaviors)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="tasksToAdd" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.CloudTask&gt;" />
        <Parameter Name="parallelOptions" Type="Microsoft.Azure.Batch.BatchClientParallelOptions" />
        <Parameter Name="fileStagingArtifacts" Type="System.Collections.Concurrent.ConcurrentBag&lt;System.Collections.Concurrent.ConcurrentDictionary&lt;System.Type,Microsoft.Azure.Batch.IFileStagingArtifact&gt;&gt;" />
        <Parameter Name="timeout" Type="System.Nullable&lt;System.TimeSpan&gt;" />
        <Parameter Name="additionalBehaviors" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt;" />
      </Parameters>
      <Docs>
        <param name="tasksToAdd"><span data-ttu-id="36eb1-113">Die <see cref="T:Microsoft.Azure.Batch.CloudTask" />s hinzufügen.</span><span class="sxs-lookup"><span data-stu-id="36eb1-113">The <see cref="T:Microsoft.Azure.Batch.CloudTask" />s to add.</span></span></param>
        <param name="parallelOptions">
            <span data-ttu-id="36eb1-114">Steuert die Anzahl gleichzeitiger parallele AddTaskCollection-Anforderungen an die Batch-Dienst ausgegeben.</span><span class="sxs-lookup"><span data-stu-id="36eb1-114">Controls the number of simultaneous parallel AddTaskCollection requests issued to the Batch service.</span></span>  <span data-ttu-id="36eb1-115">Jede Anforderung AddTaskCollection enthält höchstens <see cref="F:Microsoft.Azure.Batch.Constants.MaxTasksInSingleAddTaskCollectionRequest" /> Aufgaben darin.</span><span class="sxs-lookup"><span data-stu-id="36eb1-115">Each AddTaskCollection request contains at most <see cref="F:Microsoft.Azure.Batch.Constants.MaxTasksInSingleAddTaskCollectionRequest" /> tasks in it.</span></span>
            <span data-ttu-id="36eb1-116">Steuert auch das Abbruchtoken, das für den Vorgang.</span><span class="sxs-lookup"><span data-stu-id="36eb1-116">Also controls the cancellation token for the operation.</span></span>
            <span data-ttu-id="36eb1-117">Bei Auslassung wird die Standardeinstellung verwendet (siehe <see cref="T:Microsoft.Azure.Batch.BatchClientParallelOptions" />.)</span><span class="sxs-lookup"><span data-stu-id="36eb1-117">If omitted, the default is used (see <see cref="T:Microsoft.Azure.Batch.BatchClientParallelOptions" />.)</span></span>
            </param>
        <param name="fileStagingArtifacts"><span data-ttu-id="36eb1-118">Eine optionale Auflistung zum Empfangen von Informationen über die Datei mit dem Stagingprozess (siehe <see cref="P:Microsoft.Azure.Batch.CloudTask.FilesToStage" />).</span><span class="sxs-lookup"><span data-stu-id="36eb1-118">An optional collection to receive information about the file staging process (see <see cref="P:Microsoft.Azure.Batch.CloudTask.FilesToStage" />).</span></span>
            <span data-ttu-id="36eb1-119">Wird ein Eintrag hinzugefügt, um die <see cref="T:System.Collections.Concurrent.ConcurrentBag`1" /> für jeden Satz von Aufgaben, die für die Übermittlung an den Batch-Dienst gruppiert.</span><span class="sxs-lookup"><span data-stu-id="36eb1-119">An entry is added to the <see cref="T:System.Collections.Concurrent.ConcurrentBag`1" /> for each set of tasks grouped for submission to the Batch service.</span></span>
            <span data-ttu-id="36eb1-120">Im Gegensatz zu einzelnen Aufgabe hinzufügt, Sie können nicht diesen Parameter verwenden, um die Datei mit dem Stagingprozess anzupassen.</span><span class="sxs-lookup"><span data-stu-id="36eb1-120">Unlike single-task adds, you cannot use this parameter to customize the file staging process.</span></span>
            <span data-ttu-id="36eb1-121">Weitere Informationen zum Format von jeder Eintrag finden Sie unter <see cref="T:Microsoft.Azure.Batch.IFileStagingArtifact" />.</span><span class="sxs-lookup"><span data-stu-id="36eb1-121">For more information about the format of each entry, see <see cref="T:Microsoft.Azure.Batch.IFileStagingArtifact" />.</span></span></param>
        <param name="timeout"><span data-ttu-id="36eb1-122">Die Zeitspanne, nach dem Timeout des Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="36eb1-122">The amount of time after which the operation times out.</span></span></param>
        <param name="additionalBehaviors"><span data-ttu-id="36eb1-123">Eine Auflistung von <see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" /> Instanzen, die für die Batchanforderung-Dienst nach gelten die <see cref="P:Microsoft.Azure.Batch.CloudJob.CustomBehaviors" />.</span><span class="sxs-lookup"><span data-stu-id="36eb1-123">A collection of <see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" /> instances that are applied to the Batch service request after the <see cref="P:Microsoft.Azure.Batch.CloudJob.CustomBehaviors" />.</span></span></param>
        <summary>
            <span data-ttu-id="36eb1-124">Tasks hinzugefügt zu einem Auftrag.</span><span class="sxs-lookup"><span data-stu-id="36eb1-124">Adds tasks to a job.</span></span>
            </summary>
        <remarks>
          <para><span data-ttu-id="36eb1-125">Dies ist ein Blockierungsvorgang; eine nicht blockierende Entsprechung, finden Sie unter <see cref="M:Microsoft.Azure.Batch.CloudJob.AddTaskAsync(System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.CloudTask},Microsoft.Azure.Batch.BatchClientParallelOptions,System.Collections.Concurrent.ConcurrentBag{System.Collections.Concurrent.ConcurrentDictionary{System.Type,Microsoft.Azure.Batch.IFileStagingArtifact}},System.Nullable{System.TimeSpan},System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior})" />.</span><span class="sxs-lookup"><span data-stu-id="36eb1-125">This is a blocking operation; for a non-blocking equivalent, see <see cref="M:Microsoft.Azure.Batch.CloudJob.AddTaskAsync(System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.CloudTask},Microsoft.Azure.Batch.BatchClientParallelOptions,System.Collections.Concurrent.ConcurrentBag{System.Collections.Concurrent.ConcurrentDictionary{System.Type,Microsoft.Azure.Batch.IFileStagingArtifact}},System.Nullable{System.TimeSpan},System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior})" />.</span></span></para>
          <para><span data-ttu-id="36eb1-126">Diese Methode ist nicht atomaren; Es ist also möglich, dass die Methode zum Hinzufügen von Aufgaben starten und schlagen dann fehl.</span><span class="sxs-lookup"><span data-stu-id="36eb1-126">This method is not atomic; that is, it is possible for the method to start adding tasks and then fail.</span></span> <span data-ttu-id="36eb1-127">Die Auflistung von Aufgaben hinzuzufügende ist unterteilt in Blöcke unterteilt, Größe darf höchstens <see cref="F:Microsoft.Azure.Batch.Constants.MaxTasksInSingleAddTaskCollectionRequest" />, und eine Anforderung AddTaskCollection für jedes Blocks ausgegeben.</span><span class="sxs-lookup"><span data-stu-id="36eb1-127">The collection of tasks to add is broken down into chunks of size at most <see cref="F:Microsoft.Azure.Batch.Constants.MaxTasksInSingleAddTaskCollectionRequest" />, and an AddTaskCollection request is issued for each chunk.</span></span>  <span data-ttu-id="36eb1-128">Anforderungen können ausgegeben werden, parallel gemäß der <paramref name="parallelOptions" />.</span><span class="sxs-lookup"><span data-stu-id="36eb1-128">Requests may be issued in parallel according to the <paramref name="parallelOptions" />.</span></span></para>
          <para><span data-ttu-id="36eb1-129">Ausstellen von eine große Anzahl gleichzeitiger Anforderungen für die Batch-Dienst kann die HTTP-Verbindung Einschränkungen entstehen.</span><span class="sxs-lookup"><span data-stu-id="36eb1-129">Issuing a large number of simultaneous requests to the Batch service can incur HTTP connection restrictions.</span></span>
            <span data-ttu-id="36eb1-130">Wenn Sie viele dieser Vorgänge parallel ausgeführt werden (oder eine große MaxDegreeOfParallelism in ParallelOptions angegeben haben) und clientseitigen Timeouts angezeigt werden (eine <see cref="T:System.Threading.Tasks.TaskCanceledException" />), finden Sie unter http://msdn.microsoft.com/en-us/library/ System.NET.ServicePointManager.DefaultConnectionLimit%28v=VS.110%29.aspx.</span><span class="sxs-lookup"><span data-stu-id="36eb1-130">If you are performing many of these operations in parallel (or have specified a large MaxDegreeOfParallelism in the parallelOptions) and are seeing client side timeouts (a <see cref="T:System.Threading.Tasks.TaskCanceledException" />), please see http://msdn.microsoft.com/en-us/library/system.net.servicepointmanager.defaultconnectionlimit%28v=vs.110%29.aspx .</span></span></para>
          <para><span data-ttu-id="36eb1-131">Der Status des Vorgangs bei Fehlern richtet sich nach <see cref="T:Microsoft.Azure.Batch.AddTaskCollectionResultHandler" /> Verhalten.</span><span class="sxs-lookup"><span data-stu-id="36eb1-131">The progress of the operation in the face of errors is determined by <see cref="T:Microsoft.Azure.Batch.AddTaskCollectionResultHandler" /> behavior.</span></span>
            <span data-ttu-id="36eb1-132">Normalerweise ist es nicht müssen an dieses Verhalten als Batch Client den Standardwert verwendet, die unter normalen Umständen funktioniert.</span><span class="sxs-lookup"><span data-stu-id="36eb1-132">You do not normally need to specify this behavior, as the Batch client uses a default which works in normal circumstances.</span></span>
            <span data-ttu-id="36eb1-133">Wenn Sie dieses Verhalten anpassen möchten, geben Sie eine AddTaskCollectionResultHandler in der <see cref="P:Microsoft.Azure.Batch.CloudJob.CustomBehaviors" /> oder <paramref name="additionalBehaviors" /> Sammlungen.</span><span class="sxs-lookup"><span data-stu-id="36eb1-133">If you do want to customize this behavior, specify an AddTaskCollectionResultHandler in the <see cref="P:Microsoft.Azure.Batch.CloudJob.CustomBehaviors" /> or <paramref name="additionalBehaviors" /> collections.</span></span></para>
        </remarks>
        <exception cref="T:Microsoft.Azure.Batch.ParallelOperationsException"><span data-ttu-id="36eb1-134">Wird ausgelöst, wenn eine oder mehrere Anforderungen an die Batch-Dienst ein Fehler auftritt.</span><span class="sxs-lookup"><span data-stu-id="36eb1-134">Thrown if one or more requests to the Batch service fail.</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName="AddTaskAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task AddTaskAsync (Microsoft.Azure.Batch.CloudTask taskToAdd, System.Collections.Concurrent.ConcurrentDictionary&lt;Type,Microsoft.Azure.Batch.IFileStagingArtifact&gt; allFileStagingArtifacts = null, System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task AddTaskAsync(class Microsoft.Azure.Batch.CloudTask taskToAdd, class System.Collections.Concurrent.ConcurrentDictionary`2&lt;class System.Type, class Microsoft.Azure.Batch.IFileStagingArtifact&gt; allFileStagingArtifacts, class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.CloudJob.AddTaskAsync(Microsoft.Azure.Batch.CloudTask,System.Collections.Concurrent.ConcurrentDictionary{System.Type,Microsoft.Azure.Batch.IFileStagingArtifact},System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.AddTaskAsync : Microsoft.Azure.Batch.CloudTask * System.Collections.Concurrent.ConcurrentDictionary&lt;Type, Microsoft.Azure.Batch.IFileStagingArtifact&gt; * seq&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="cloudJob.AddTaskAsync (taskToAdd, allFileStagingArtifacts, additionalBehaviors, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Batch.CloudJob/&lt;AddTaskAsync&gt;d__4))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="taskToAdd" Type="Microsoft.Azure.Batch.CloudTask" />
        <Parameter Name="allFileStagingArtifacts" Type="System.Collections.Concurrent.ConcurrentDictionary&lt;System.Type,Microsoft.Azure.Batch.IFileStagingArtifact&gt;" />
        <Parameter Name="additionalBehaviors" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="taskToAdd"><span data-ttu-id="36eb1-135">Das hinzuzufügende <see cref="T:Microsoft.Azure.Batch.CloudTask" />.</span><span class="sxs-lookup"><span data-stu-id="36eb1-135">The <see cref="T:Microsoft.Azure.Batch.CloudTask" /> to add.</span></span></param>
        <param name="allFileStagingArtifacts"><span data-ttu-id="36eb1-136">Eine optionale Auflistung zum Anpassen und Empfangen von Informationen über die Datei mit dem Stagingprozess (siehe <see cref="P:Microsoft.Azure.Batch.CloudTask.FilesToStage" />).</span><span class="sxs-lookup"><span data-stu-id="36eb1-136">An optional collection to customize and receive information about the file staging process (see <see cref="P:Microsoft.Azure.Batch.CloudTask.FilesToStage" />).</span></span>
            <span data-ttu-id="36eb1-137">Weitere Informationen finden Sie unter <see cref="T:Microsoft.Azure.Batch.IFileStagingArtifact" />.</span><span class="sxs-lookup"><span data-stu-id="36eb1-137">For more information see <see cref="T:Microsoft.Azure.Batch.IFileStagingArtifact" />.</span></span></param>
        <param name="additionalBehaviors"><span data-ttu-id="36eb1-138">Eine Auflistung von <see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" /> Instanzen, die für die Batchanforderung-Dienst nach gelten die <see cref="P:Microsoft.Azure.Batch.CloudJob.CustomBehaviors" />.</span><span class="sxs-lookup"><span data-stu-id="36eb1-138">A collection of <see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" /> instances that are applied to the Batch service request after the <see cref="P:Microsoft.Azure.Batch.CloudJob.CustomBehaviors" />.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="36eb1-139">Ein <see cref="T:System.Threading.CancellationToken" /> für die Steuerung der Lebensdauer eines asynchronen Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="36eb1-139">A <see cref="T:System.Threading.CancellationToken" /> for controlling the lifetime of the asynchronous operation.</span></span></param>
        <summary>
            <span data-ttu-id="36eb1-140">Fügt eine einzelne Aufgabe dieser <see cref="T:Microsoft.Azure.Batch.CloudJob" />.</span><span class="sxs-lookup"><span data-stu-id="36eb1-140">Adds a single task to this <see cref="T:Microsoft.Azure.Batch.CloudJob" />.</span></span>  <span data-ttu-id="36eb1-141">Verwenden Sie zum Hinzufügen von mehreren Aufgaben <see cref="M:Microsoft.Azure.Batch.JobOperations.AddTaskAsync(System.String,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.CloudTask},Microsoft.Azure.Batch.BatchClientParallelOptions,System.Collections.Concurrent.ConcurrentBag{System.Collections.Concurrent.ConcurrentDictionary{System.Type,Microsoft.Azure.Batch.IFileStagingArtifact}},System.Nullable{System.TimeSpan},System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior})">JobOperations.AddTaskAsync</see>.</span><span class="sxs-lookup"><span data-stu-id="36eb1-141">To add multiple tasks, use <see cref="M:Microsoft.Azure.Batch.JobOperations.AddTaskAsync(System.String,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.CloudTask},Microsoft.Azure.Batch.BatchClientParallelOptions,System.Collections.Concurrent.ConcurrentBag{System.Collections.Concurrent.ConcurrentDictionary{System.Type,Microsoft.Azure.Batch.IFileStagingArtifact}},System.Nullable{System.TimeSpan},System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior})">JobOperations.AddTaskAsync</see>.</span></span>
            </summary>
        <returns><span data-ttu-id="36eb1-142">Ein <see cref="T:System.Threading.Tasks.Task" />-Element, das den asynchronen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="36eb1-142">A <see cref="T:System.Threading.Tasks.Task" /> that represents the asynchronous operation.</span></span></returns>
        <remarks>
          <para>
            <span data-ttu-id="36eb1-143">Jeder Aufruf dieser Methode verursacht eine Anforderung an den Batch-Dienst.</span><span class="sxs-lookup"><span data-stu-id="36eb1-143">Each call to this method incurs a request to the Batch service.</span></span> <span data-ttu-id="36eb1-144">Aus diesem Grund verwenden diese Methode zum Hinzufügen von mehreren Aufgaben ist weniger effizient als die Verwendung einer Bulk add-Methode, und HTTP-Verbindung Einschränkungen verursachen können.</span><span class="sxs-lookup"><span data-stu-id="36eb1-144">Therefore, using this method to add multiple tasks is less efficient than using a bulk add method, and can incur HTTP connection restrictions.</span></span>
            <span data-ttu-id="36eb1-145">Wenn Sie viele dieser Vorgänge parallel ausgeführt werden und clientseitigen Timeouts angezeigt werden (eine <see cref="T:System.Threading.Tasks.TaskCanceledException" />), finden Sie unter http://msdn.microsoft.com/en-us/library/system.net.servicepointmanager.defaultconnectionlimit%28v=vs.110%29.aspx, oder verwenden <see cref="M:Microsoft.Azure.Batch.JobOperations.AddTaskAsync(System.String,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.CloudTask},Microsoft.Azure.Batch.BatchClientParallelOptions,System.Collections.Concurrent.ConcurrentBag{System.Collections.Concurrent.ConcurrentDictionary{System.Type,Microsoft.Azure.Batch.IFileStagingArtifact}},System.Nullable{System.TimeSpan},System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior})" />.</span><span class="sxs-lookup"><span data-stu-id="36eb1-145">If you are performing many of these operations in parallel and are seeing client side timeouts (a <see cref="T:System.Threading.Tasks.TaskCanceledException" />), please see http://msdn.microsoft.com/en-us/library/system.net.servicepointmanager.defaultconnectionlimit%28v=vs.110%29.aspx or use <see cref="M:Microsoft.Azure.Batch.JobOperations.AddTaskAsync(System.String,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.CloudTask},Microsoft.Azure.Batch.BatchClientParallelOptions,System.Collections.Concurrent.ConcurrentBag{System.Collections.Concurrent.ConcurrentDictionary{System.Type,Microsoft.Azure.Batch.IFileStagingArtifact}},System.Nullable{System.TimeSpan},System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior})" />.</span></span>
            </para>
          <para><span data-ttu-id="36eb1-146">Der Vorgang des Agentverwaltungstasks hinzufügen wird asynchron ausgeführt.</span><span class="sxs-lookup"><span data-stu-id="36eb1-146">The add task operation runs asynchronously.</span></span></para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="AddTaskAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task AddTaskAsync (System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.CloudTask&gt; tasksToAdd, Microsoft.Azure.Batch.BatchClientParallelOptions parallelOptions = null, System.Collections.Concurrent.ConcurrentBag&lt;System.Collections.Concurrent.ConcurrentDictionary&lt;Type,Microsoft.Azure.Batch.IFileStagingArtifact&gt;&gt; fileStagingArtifacts = null, Nullable&lt;TimeSpan&gt; timeout = null, System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task AddTaskAsync(class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Batch.CloudTask&gt; tasksToAdd, class Microsoft.Azure.Batch.BatchClientParallelOptions parallelOptions, class System.Collections.Concurrent.ConcurrentBag`1&lt;class System.Collections.Concurrent.ConcurrentDictionary`2&lt;class System.Type, class Microsoft.Azure.Batch.IFileStagingArtifact&gt;&gt; fileStagingArtifacts, valuetype System.Nullable`1&lt;valuetype System.TimeSpan&gt; timeout, class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.CloudJob.AddTaskAsync(System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.CloudTask},Microsoft.Azure.Batch.BatchClientParallelOptions,System.Collections.Concurrent.ConcurrentBag{System.Collections.Concurrent.ConcurrentDictionary{System.Type,Microsoft.Azure.Batch.IFileStagingArtifact}},System.Nullable{System.TimeSpan},System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior})" />
      <MemberSignature Language="VB.NET" Value="Public Function AddTaskAsync (tasksToAdd As IEnumerable(Of CloudTask), Optional parallelOptions As BatchClientParallelOptions = null, Optional fileStagingArtifacts As ConcurrentBag(Of ConcurrentDictionary(Of Type, IFileStagingArtifact)) = null, Optional timeout As Nullable(Of TimeSpan) = null, Optional additionalBehaviors As IEnumerable(Of BatchClientBehavior) = null) As Task" />
      <MemberSignature Language="F#" Value="member this.AddTaskAsync : seq&lt;Microsoft.Azure.Batch.CloudTask&gt; * Microsoft.Azure.Batch.BatchClientParallelOptions * System.Collections.Concurrent.ConcurrentBag&lt;System.Collections.Concurrent.ConcurrentDictionary&lt;Type, Microsoft.Azure.Batch.IFileStagingArtifact&gt;&gt; * Nullable&lt;TimeSpan&gt; * seq&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; -&gt; System.Threading.Tasks.Task" Usage="cloudJob.AddTaskAsync (tasksToAdd, parallelOptions, fileStagingArtifacts, timeout, additionalBehaviors)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Batch.CloudJob/&lt;AddTaskAsync&gt;d__6))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="tasksToAdd" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.CloudTask&gt;" />
        <Parameter Name="parallelOptions" Type="Microsoft.Azure.Batch.BatchClientParallelOptions" />
        <Parameter Name="fileStagingArtifacts" Type="System.Collections.Concurrent.ConcurrentBag&lt;System.Collections.Concurrent.ConcurrentDictionary&lt;System.Type,Microsoft.Azure.Batch.IFileStagingArtifact&gt;&gt;" />
        <Parameter Name="timeout" Type="System.Nullable&lt;System.TimeSpan&gt;" />
        <Parameter Name="additionalBehaviors" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt;" />
      </Parameters>
      <Docs>
        <param name="tasksToAdd"><span data-ttu-id="36eb1-147">Die <see cref="T:Microsoft.Azure.Batch.CloudTask" />s hinzufügen.</span><span class="sxs-lookup"><span data-stu-id="36eb1-147">The <see cref="T:Microsoft.Azure.Batch.CloudTask" />s to add.</span></span></param>
        <param name="parallelOptions">
            <span data-ttu-id="36eb1-148">Steuert die Anzahl gleichzeitiger parallele AddTaskCollection-Anforderungen an die Batch-Dienst ausgegeben.</span><span class="sxs-lookup"><span data-stu-id="36eb1-148">Controls the number of simultaneous parallel AddTaskCollection requests issued to the Batch service.</span></span>  <span data-ttu-id="36eb1-149">Jede Anforderung AddTaskCollection enthält höchstens <see cref="F:Microsoft.Azure.Batch.Constants.MaxTasksInSingleAddTaskCollectionRequest" /> Aufgaben darin.</span><span class="sxs-lookup"><span data-stu-id="36eb1-149">Each AddTaskCollection request contains at most <see cref="F:Microsoft.Azure.Batch.Constants.MaxTasksInSingleAddTaskCollectionRequest" /> tasks in it.</span></span>
            <span data-ttu-id="36eb1-150">Steuert auch das Abbruchtoken, das für den Vorgang.</span><span class="sxs-lookup"><span data-stu-id="36eb1-150">Also controls the cancellation token for the operation.</span></span>
            <span data-ttu-id="36eb1-151">Bei Auslassung wird die Standardeinstellung verwendet (siehe <see cref="T:Microsoft.Azure.Batch.BatchClientParallelOptions" />.)</span><span class="sxs-lookup"><span data-stu-id="36eb1-151">If omitted, the default is used (see <see cref="T:Microsoft.Azure.Batch.BatchClientParallelOptions" />.)</span></span>
            </param>
        <param name="fileStagingArtifacts"><span data-ttu-id="36eb1-152">Eine optionale Auflistung zum Empfangen von Informationen über die Datei mit dem Stagingprozess (siehe <see cref="P:Microsoft.Azure.Batch.CloudTask.FilesToStage" />).</span><span class="sxs-lookup"><span data-stu-id="36eb1-152">An optional collection to receive information about the file staging process (see <see cref="P:Microsoft.Azure.Batch.CloudTask.FilesToStage" />).</span></span>
            <span data-ttu-id="36eb1-153">Wird ein Eintrag hinzugefügt, um die <see cref="T:System.Collections.Concurrent.ConcurrentBag`1" /> für jeden Satz von Aufgaben, die für die Übermittlung an den Batch-Dienst gruppiert.</span><span class="sxs-lookup"><span data-stu-id="36eb1-153">An entry is added to the <see cref="T:System.Collections.Concurrent.ConcurrentBag`1" /> for each set of tasks grouped for submission to the Batch service.</span></span>
            <span data-ttu-id="36eb1-154">Im Gegensatz zu einzelnen Aufgabe hinzufügt, Sie können nicht diesen Parameter verwenden, um die Datei mit dem Stagingprozess anzupassen.</span><span class="sxs-lookup"><span data-stu-id="36eb1-154">Unlike single-task adds, you cannot use this parameter to customize the file staging process.</span></span>
            <span data-ttu-id="36eb1-155">Weitere Informationen zum Format von jeder Eintrag finden Sie unter <see cref="T:Microsoft.Azure.Batch.IFileStagingArtifact" />.</span><span class="sxs-lookup"><span data-stu-id="36eb1-155">For more information about the format of each entry, see <see cref="T:Microsoft.Azure.Batch.IFileStagingArtifact" />.</span></span></param>
        <param name="timeout"><span data-ttu-id="36eb1-156">Die Zeitspanne, nach dem Timeout des Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="36eb1-156">The amount of time after which the operation times out.</span></span></param>
        <param name="additionalBehaviors"><span data-ttu-id="36eb1-157">Eine Auflistung von <see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" /> Instanzen, die für die Batchanforderung-Dienst nach gelten die <see cref="P:Microsoft.Azure.Batch.CloudJob.CustomBehaviors" />.</span><span class="sxs-lookup"><span data-stu-id="36eb1-157">A collection of <see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" /> instances that are applied to the Batch service request after the <see cref="P:Microsoft.Azure.Batch.CloudJob.CustomBehaviors" />.</span></span></param>
        <summary>
            <span data-ttu-id="36eb1-158">Tasks hinzugefügt zu einem Auftrag.</span><span class="sxs-lookup"><span data-stu-id="36eb1-158">Adds tasks to a job.</span></span>
            </summary>
        <returns><span data-ttu-id="36eb1-159">Ein <see cref="T:System.Threading.Tasks.Task" />-Objekt, das den asynchronen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="36eb1-159">A <see cref="T:System.Threading.Tasks.Task" /> object that represents the asynchronous operation.</span></span></returns>
        <remarks>
          <para><span data-ttu-id="36eb1-160">Der Vorgang des Agentverwaltungstasks hinzufügen wird asynchron ausgeführt.</span><span class="sxs-lookup"><span data-stu-id="36eb1-160">The add task operation runs asynchronously.</span></span></para>
          <para><span data-ttu-id="36eb1-161">Diese Methode ist nicht atomaren; Es ist also möglich, dass die Methode zum Hinzufügen von Aufgaben starten und schlagen dann fehl.</span><span class="sxs-lookup"><span data-stu-id="36eb1-161">This method is not atomic; that is, it is possible for the method to start adding tasks and then fail.</span></span> <span data-ttu-id="36eb1-162">Die Auflistung von Aufgaben hinzuzufügende ist unterteilt in Blöcke unterteilt, Größe darf höchstens <see cref="F:Microsoft.Azure.Batch.Constants.MaxTasksInSingleAddTaskCollectionRequest" />, und eine Anforderung AddTaskCollection für jedes Blocks ausgegeben.</span><span class="sxs-lookup"><span data-stu-id="36eb1-162">The collection of tasks to add is broken down into chunks of size at most <see cref="F:Microsoft.Azure.Batch.Constants.MaxTasksInSingleAddTaskCollectionRequest" />, and an AddTaskCollection request is issued for each chunk.</span></span>  <span data-ttu-id="36eb1-163">Anforderungen können ausgegeben werden, parallel gemäß der <paramref name="parallelOptions" />.</span><span class="sxs-lookup"><span data-stu-id="36eb1-163">Requests may be issued in parallel according to the <paramref name="parallelOptions" />.</span></span></para>
          <para><span data-ttu-id="36eb1-164">Ausstellen von eine große Anzahl gleichzeitiger Anforderungen für die Batch-Dienst kann die HTTP-Verbindung Einschränkungen entstehen.</span><span class="sxs-lookup"><span data-stu-id="36eb1-164">Issuing a large number of simultaneous requests to the Batch service can incur HTTP connection restrictions.</span></span>
            <span data-ttu-id="36eb1-165">Wenn Sie viele dieser Vorgänge parallel ausgeführt werden (oder eine große MaxDegreeOfParallelism in ParallelOptions angegeben haben) und clientseitigen Timeouts angezeigt werden (eine <see cref="T:System.Threading.Tasks.TaskCanceledException" />), finden Sie unter http://msdn.microsoft.com/en-us/library/ System.NET.ServicePointManager.DefaultConnectionLimit%28v=VS.110%29.aspx.</span><span class="sxs-lookup"><span data-stu-id="36eb1-165">If you are performing many of these operations in parallel (or have specified a large MaxDegreeOfParallelism in the parallelOptions) and are seeing client side timeouts (a <see cref="T:System.Threading.Tasks.TaskCanceledException" />), please see http://msdn.microsoft.com/en-us/library/system.net.servicepointmanager.defaultconnectionlimit%28v=vs.110%29.aspx .</span></span></para>
          <para><span data-ttu-id="36eb1-166">Der Status des Vorgangs bei Fehlern richtet sich nach <see cref="T:Microsoft.Azure.Batch.AddTaskCollectionResultHandler" /> Verhalten.</span><span class="sxs-lookup"><span data-stu-id="36eb1-166">The progress of the operation in the face of errors is determined by <see cref="T:Microsoft.Azure.Batch.AddTaskCollectionResultHandler" /> behavior.</span></span>
            <span data-ttu-id="36eb1-167">Normalerweise ist es nicht müssen an dieses Verhalten als Batch Client den Standardwert verwendet, die unter normalen Umständen funktioniert.</span><span class="sxs-lookup"><span data-stu-id="36eb1-167">You do not normally need to specify this behavior, as the Batch client uses a default which works in normal circumstances.</span></span>
            <span data-ttu-id="36eb1-168">Wenn Sie dieses Verhalten anpassen möchten, geben Sie eine AddTaskCollectionResultHandler in der <see cref="P:Microsoft.Azure.Batch.CloudJob.CustomBehaviors" /> oder <paramref name="additionalBehaviors" /> Sammlungen.</span><span class="sxs-lookup"><span data-stu-id="36eb1-168">If you do want to customize this behavior, specify an AddTaskCollectionResultHandler in the <see cref="P:Microsoft.Azure.Batch.CloudJob.CustomBehaviors" /> or <paramref name="additionalBehaviors" /> collections.</span></span></para>
        </remarks>
        <exception cref="T:Microsoft.Azure.Batch.ParallelOperationsException"><span data-ttu-id="36eb1-169">Wird ausgelöst, wenn eine oder mehrere Anforderungen an die Batch-Dienst ein Fehler auftritt.</span><span class="sxs-lookup"><span data-stu-id="36eb1-169">Thrown if one or more requests to the Batch service fail.</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName="Commit">
      <MemberSignature Language="C#" Value="public void Commit (System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance void Commit(class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.CloudJob.Commit(System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior})" />
      <MemberSignature Language="VB.NET" Value="Public Sub Commit (Optional additionalBehaviors As IEnumerable(Of BatchClientBehavior) = null)" />
      <MemberSignature Language="F#" Value="member this.Commit : seq&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; -&gt; unit" Usage="cloudJob.Commit additionalBehaviors" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="additionalBehaviors" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt;" />
      </Parameters>
      <Docs>
        <param name="additionalBehaviors"><span data-ttu-id="36eb1-170">Eine Auflistung von <see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" /> Instanzen, die für die Batchanforderung-Dienst nach gelten die <see cref="P:Microsoft.Azure.Batch.CloudJob.CustomBehaviors" />.</span><span class="sxs-lookup"><span data-stu-id="36eb1-170">A collection of <see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" /> instances that are applied to the Batch service request after the <see cref="P:Microsoft.Azure.Batch.CloudJob.CustomBehaviors" />.</span></span></param>
        <summary>
            <span data-ttu-id="36eb1-171">Führt einen Commit für diese <see cref="T:Microsoft.Azure.Batch.CloudJob" /> an den Azure Batch-Dienst.</span><span class="sxs-lookup"><span data-stu-id="36eb1-171">Commits this <see cref="T:Microsoft.Azure.Batch.CloudJob" /> to the Azure Batch service.</span></span>
            </summary>
        <remarks>
          <para><span data-ttu-id="36eb1-172">Wenn die <see cref="T:Microsoft.Azure.Batch.CloudJob" /> bereits auf der Batch-Dienst, dessen Eigenschaften ersetzt werden, durch die Eigenschaften dieses <see cref="T:Microsoft.Azure.Batch.CloudJob" />.</span><span class="sxs-lookup"><span data-stu-id="36eb1-172">If the <see cref="T:Microsoft.Azure.Batch.CloudJob" /> already exists on the Batch service, its properties are replaced by the properties of this <see cref="T:Microsoft.Azure.Batch.CloudJob" />.</span></span></para>
          <para><span data-ttu-id="36eb1-173">Dies ist ein blockierender Vorgang.</span><span class="sxs-lookup"><span data-stu-id="36eb1-173">This is a blocking operation.</span></span> <span data-ttu-id="36eb1-174">Eine nicht blockierende Entsprechung, finden Sie unter <see cref="M:Microsoft.Azure.Batch.CloudJob.CommitAsync(System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior},System.Threading.CancellationToken)" />.</span><span class="sxs-lookup"><span data-stu-id="36eb1-174">For a non-blocking equivalent, see <see cref="M:Microsoft.Azure.Batch.CloudJob.CommitAsync(System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior},System.Threading.CancellationToken)" />.</span></span></para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="CommitAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task CommitAsync (System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task CommitAsync(class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.CloudJob.CommitAsync(System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.CommitAsync : seq&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="cloudJob.CommitAsync (additionalBehaviors, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Batch.CloudJob/&lt;CommitAsync&gt;d__0))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="additionalBehaviors" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="additionalBehaviors"><span data-ttu-id="36eb1-175">Eine Auflistung von <see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" /> Instanzen, die für die Batchanforderung-Dienst nach gelten die <see cref="P:Microsoft.Azure.Batch.CloudJob.CustomBehaviors" />.</span><span class="sxs-lookup"><span data-stu-id="36eb1-175">A collection of <see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" /> instances that are applied to the Batch service request after the <see cref="P:Microsoft.Azure.Batch.CloudJob.CustomBehaviors" />.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="36eb1-176">Ein <see cref="T:System.Threading.CancellationToken" /> für die Steuerung der Lebensdauer eines asynchronen Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="36eb1-176">A <see cref="T:System.Threading.CancellationToken" /> for controlling the lifetime of the asynchronous operation.</span></span></param>
        <summary>
            <span data-ttu-id="36eb1-177">Führt einen Commit für diese <see cref="T:Microsoft.Azure.Batch.CloudJob" /> an den Azure Batch-Dienst.</span><span class="sxs-lookup"><span data-stu-id="36eb1-177">Commits this <see cref="T:Microsoft.Azure.Batch.CloudJob" /> to the Azure Batch service.</span></span>
            </summary>
        <returns><span data-ttu-id="36eb1-178">Ein <see cref="T:System.Threading.Tasks.Task" />-Element, das den asynchronen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="36eb1-178">A <see cref="T:System.Threading.Tasks.Task" /> that represents the asynchronous operation.</span></span></returns>
        <remarks>
          <para><span data-ttu-id="36eb1-179">Wenn die <see cref="T:Microsoft.Azure.Batch.CloudJob" /> bereits auf der Batch-Dienst, dessen Eigenschaften ersetzt werden, durch die Eigenschaften dieses <see cref="T:Microsoft.Azure.Batch.CloudJob" />.</span><span class="sxs-lookup"><span data-stu-id="36eb1-179">If the <see cref="T:Microsoft.Azure.Batch.CloudJob" /> already exists on the Batch service, its properties are replaced by the properties of this <see cref="T:Microsoft.Azure.Batch.CloudJob" />.</span></span></para>
          <para><span data-ttu-id="36eb1-180">Der Commitvorgang wird asynchron ausgeführt.</span><span class="sxs-lookup"><span data-stu-id="36eb1-180">The commit operation runs asynchronously.</span></span></para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="CommitChanges">
      <MemberSignature Language="C#" Value="public void CommitChanges (System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance void CommitChanges(class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.CloudJob.CommitChanges(System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior})" />
      <MemberSignature Language="VB.NET" Value="Public Sub CommitChanges (Optional additionalBehaviors As IEnumerable(Of BatchClientBehavior) = null)" />
      <MemberSignature Language="F#" Value="member this.CommitChanges : seq&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; -&gt; unit" Usage="cloudJob.CommitChanges additionalBehaviors" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="additionalBehaviors" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt;" />
      </Parameters>
      <Docs>
        <param name="additionalBehaviors"><span data-ttu-id="36eb1-181">Eine Auflistung von <see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" /> Instanzen, die für die Batchanforderung-Dienst nach gelten die <see cref="P:Microsoft.Azure.Batch.CloudJob.CustomBehaviors" />.</span><span class="sxs-lookup"><span data-stu-id="36eb1-181">A collection of <see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" /> instances that are applied to the Batch service request after the <see cref="P:Microsoft.Azure.Batch.CloudJob.CustomBehaviors" />.</span></span></param>
        <summary>
            <span data-ttu-id="36eb1-182">Führt einen Commit für alle ausstehenden Änderungen dieser <see cref="T:Microsoft.Azure.Batch.CloudJob" /> an den Azure Batch-Dienst.</span><span class="sxs-lookup"><span data-stu-id="36eb1-182">Commits all pending changes to this <see cref="T:Microsoft.Azure.Batch.CloudJob" /> to the Azure Batch service.</span></span>
            </summary>
        <remarks>
          <para>
            <span data-ttu-id="36eb1-183">Aktualisiert ein vorhandenes <see cref="T:Microsoft.Azure.Batch.CloudJob" /> auf der Batch-Dienst, indem Sie seine Eigenschaften mit den Eigenschaften dieser ersetzen <see cref="T:Microsoft.Azure.Batch.CloudJob" /> die geändert wurden.</span><span class="sxs-lookup"><span data-stu-id="36eb1-183">Updates an existing <see cref="T:Microsoft.Azure.Batch.CloudJob" /> on the Batch service by replacing its properties with the properties of this <see cref="T:Microsoft.Azure.Batch.CloudJob" /> which have been changed.</span></span>
            <span data-ttu-id="36eb1-184">Unveränderte Eigenschaften werden ignoriert.</span><span class="sxs-lookup"><span data-stu-id="36eb1-184">Unchanged properties are ignored.</span></span>
            <span data-ttu-id="36eb1-185">Alle Änderungen seit der letzten Ausführung dieser Entität aus der Batch-Dienst abgerufen wurde (entweder über <see cref="M:Microsoft.Azure.Batch.CloudJob.Refresh(Microsoft.Azure.Batch.DetailLevel,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior})" />, <see cref="M:Microsoft.Azure.Batch.JobOperations.GetJob(System.String,Microsoft.Azure.Batch.DetailLevel,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior})" />, oder <see cref="M:Microsoft.Azure.Batch.JobOperations.ListJobs(Microsoft.Azure.Batch.DetailLevel,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior})" />) angewendet werden.</span><span class="sxs-lookup"><span data-stu-id="36eb1-185">All changes since the last time this entity was retrieved from the Batch service (either via <see cref="M:Microsoft.Azure.Batch.CloudJob.Refresh(Microsoft.Azure.Batch.DetailLevel,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior})" />, <see cref="M:Microsoft.Azure.Batch.JobOperations.GetJob(System.String,Microsoft.Azure.Batch.DetailLevel,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior})" />, or <see cref="M:Microsoft.Azure.Batch.JobOperations.ListJobs(Microsoft.Azure.Batch.DetailLevel,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior})" />) are applied.</span></span>
            <span data-ttu-id="36eb1-186">Eigenschaften, die auf null wird explizit festgelegt sind, wird eine Ausnahme ausgelöst, da der Batch-Dienst nicht teilweise Updates unterstützt, die eine Eigenschaft auf null festgelegt.</span><span class="sxs-lookup"><span data-stu-id="36eb1-186">Properties which are explicitly set to null will cause an exception because the Batch service does not support partial updates which set a property to null.</span></span>
            <span data-ttu-id="36eb1-187">Wenn Sie eine Eigenschaft auf null festzulegen, verwenden <see cref="M:Microsoft.Azure.Batch.CloudJob.Commit(System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior})" />.</span><span class="sxs-lookup"><span data-stu-id="36eb1-187">If you need to set a property to null, use <see cref="M:Microsoft.Azure.Batch.CloudJob.Commit(System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior})" />.</span></span>
            </para>
          <para><span data-ttu-id="36eb1-188">Dies ist ein blockierender Vorgang.</span><span class="sxs-lookup"><span data-stu-id="36eb1-188">This is a blocking operation.</span></span> <span data-ttu-id="36eb1-189">Eine nicht blockierende Entsprechung, finden Sie unter <see cref="M:Microsoft.Azure.Batch.CloudJob.CommitChangesAsync(System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior},System.Threading.CancellationToken)" />.</span><span class="sxs-lookup"><span data-stu-id="36eb1-189">For a non-blocking equivalent, see <see cref="M:Microsoft.Azure.Batch.CloudJob.CommitChangesAsync(System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior},System.Threading.CancellationToken)" />.</span></span></para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="CommitChangesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task CommitChangesAsync (System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task CommitChangesAsync(class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.CloudJob.CommitChangesAsync(System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.CommitChangesAsync : seq&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="cloudJob.CommitChangesAsync (additionalBehaviors, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Batch.CloudJob/&lt;CommitChangesAsync&gt;d__2))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="additionalBehaviors" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="additionalBehaviors"><span data-ttu-id="36eb1-190">Eine Auflistung von <see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" /> Instanzen, die für die Batchanforderung-Dienst nach gelten die <see cref="P:Microsoft.Azure.Batch.CloudJob.CustomBehaviors" />.</span><span class="sxs-lookup"><span data-stu-id="36eb1-190">A collection of <see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" /> instances that are applied to the Batch service request after the <see cref="P:Microsoft.Azure.Batch.CloudJob.CustomBehaviors" />.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="36eb1-191">Ein <see cref="T:System.Threading.CancellationToken" /> für die Steuerung der Lebensdauer eines asynchronen Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="36eb1-191">A <see cref="T:System.Threading.CancellationToken" /> for controlling the lifetime of the asynchronous operation.</span></span></param>
        <summary>
            <span data-ttu-id="36eb1-192">Führt einen Commit für alle ausstehenden Änderungen dieser <see cref="T:Microsoft.Azure.Batch.CloudJob" /> an den Azure Batch-Dienst.</span><span class="sxs-lookup"><span data-stu-id="36eb1-192">Commits all pending changes to this <see cref="T:Microsoft.Azure.Batch.CloudJob" /> to the Azure Batch service.</span></span>
            </summary>
        <returns><span data-ttu-id="36eb1-193">Ein <see cref="T:System.Threading.Tasks.Task" />-Element, das den asynchronen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="36eb1-193">A <see cref="T:System.Threading.Tasks.Task" /> that represents the asynchronous operation.</span></span></returns>
        <remarks>
          <para>
            <span data-ttu-id="36eb1-194">Aktualisiert ein vorhandenes <see cref="T:Microsoft.Azure.Batch.CloudJob" /> auf der Batch-Dienst, indem Sie seine Eigenschaften mit den Eigenschaften dieser ersetzen <see cref="T:Microsoft.Azure.Batch.CloudJob" /> die geändert wurden.</span><span class="sxs-lookup"><span data-stu-id="36eb1-194">Updates an existing <see cref="T:Microsoft.Azure.Batch.CloudJob" /> on the Batch service by replacing its properties with the properties of this <see cref="T:Microsoft.Azure.Batch.CloudJob" /> which have been changed.</span></span>
            <span data-ttu-id="36eb1-195">Unveränderte Eigenschaften werden ignoriert.</span><span class="sxs-lookup"><span data-stu-id="36eb1-195">Unchanged properties are ignored.</span></span>
            <span data-ttu-id="36eb1-196">Alle Änderungen seit der letzten Ausführung dieser Entität aus der Batch-Dienst abgerufen wurde (entweder über <see cref="M:Microsoft.Azure.Batch.CloudJob.Refresh(Microsoft.Azure.Batch.DetailLevel,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior})" />, <see cref="M:Microsoft.Azure.Batch.JobOperations.GetJob(System.String,Microsoft.Azure.Batch.DetailLevel,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior})" />, oder <see cref="M:Microsoft.Azure.Batch.JobOperations.ListJobs(Microsoft.Azure.Batch.DetailLevel,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior})" />) angewendet werden.</span><span class="sxs-lookup"><span data-stu-id="36eb1-196">All changes since the last time this entity was retrieved from the Batch service (either via <see cref="M:Microsoft.Azure.Batch.CloudJob.Refresh(Microsoft.Azure.Batch.DetailLevel,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior})" />, <see cref="M:Microsoft.Azure.Batch.JobOperations.GetJob(System.String,Microsoft.Azure.Batch.DetailLevel,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior})" />, or <see cref="M:Microsoft.Azure.Batch.JobOperations.ListJobs(Microsoft.Azure.Batch.DetailLevel,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior})" />) are applied.</span></span>
            <span data-ttu-id="36eb1-197">Eigenschaften, die auf null wird explizit festgelegt sind, wird eine Ausnahme ausgelöst, da der Batch-Dienst nicht teilweise Updates unterstützt, die eine Eigenschaft auf null festgelegt.</span><span class="sxs-lookup"><span data-stu-id="36eb1-197">Properties which are explicitly set to null will cause an exception because the Batch service does not support partial updates which set a property to null.</span></span>
            <span data-ttu-id="36eb1-198">Wenn Sie eine Eigenschaft auf null festzulegen, verwenden <see cref="M:Microsoft.Azure.Batch.CloudJob.Commit(System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior})" />.</span><span class="sxs-lookup"><span data-stu-id="36eb1-198">If you need to set a property to null, use <see cref="M:Microsoft.Azure.Batch.CloudJob.Commit(System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior})" />.</span></span>
            </para>
          <para><span data-ttu-id="36eb1-199">Dieser Vorgang wird asynchron ausgeführt.</span><span class="sxs-lookup"><span data-stu-id="36eb1-199">This operation runs asynchronously.</span></span></para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="CommonEnvironmentSettings">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.EnvironmentSetting&gt; CommonEnvironmentSettings { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Batch.EnvironmentSetting&gt; CommonEnvironmentSettings" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.CloudJob.CommonEnvironmentSettings" />
      <MemberSignature Language="VB.NET" Value="Public Property CommonEnvironmentSettings As IList(Of EnvironmentSetting)" />
      <MemberSignature Language="F#" Value="member this.CommonEnvironmentSettings : System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.EnvironmentSetting&gt; with get, set" Usage="Microsoft.Azure.Batch.CloudJob.CommonEnvironmentSettings" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.EnvironmentSetting&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="36eb1-200">Ruft ab oder legt eine Liste der allgemeinen umgebungsvariableneinstellungen.</span><span class="sxs-lookup"><span data-stu-id="36eb1-200">Gets or sets a list of common environment variable settings.</span></span> <span data-ttu-id="36eb1-201">Diese Umgebungsvariablen festgelegt sind, für alle Aufgaben in dieser <see cref="T:Microsoft.Azure.Batch.CloudJob" /> (einschließlich der Auftrags-Manager, Auftrag zur Vorbereitung und Auftrag Version).</span><span class="sxs-lookup"><span data-stu-id="36eb1-201">These environment variables are set for all tasks in this <see cref="T:Microsoft.Azure.Batch.CloudJob" /> (including the Job Manager, Job Preparation and Job Release tasks).</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Constraints">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Batch.JobConstraints Constraints { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Batch.JobConstraints Constraints" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.CloudJob.Constraints" />
      <MemberSignature Language="VB.NET" Value="Public Property Constraints As JobConstraints" />
      <MemberSignature Language="F#" Value="member this.Constraints : Microsoft.Azure.Batch.JobConstraints with get, set" Usage="Microsoft.Azure.Batch.CloudJob.Constraints" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.JobConstraints</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="36eb1-202">Ruft ab oder legt die ausführungseinschränkungen für den Auftrag.</span><span class="sxs-lookup"><span data-stu-id="36eb1-202">Gets or sets the execution constraints for the job.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreationTime">
      <MemberSignature Language="C#" Value="public Nullable&lt;DateTime&gt; CreationTime { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; CreationTime" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.CloudJob.CreationTime" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property CreationTime As Nullable(Of DateTime)" />
      <MemberSignature Language="F#" Value="member this.CreationTime : Nullable&lt;DateTime&gt;" Usage="Microsoft.Azure.Batch.CloudJob.CreationTime" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.DateTime&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="36eb1-203">Ruft den Zeitpunkt der Erstellung des Auftrags ab.</span><span class="sxs-lookup"><span data-stu-id="36eb1-203">Gets the creation time of the job.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CustomBehaviors">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; CustomBehaviors { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Batch.BatchClientBehavior&gt; CustomBehaviors" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.CloudJob.CustomBehaviors" />
      <MemberSignature Language="VB.NET" Value="Public Property CustomBehaviors As IList(Of BatchClientBehavior)" />
      <MemberSignature Language="F#" Value="member this.CustomBehaviors : System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; with get, set" Usage="Microsoft.Azure.Batch.CloudJob.CustomBehaviors" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:Microsoft.Azure.Batch.IInheritedBehaviors.CustomBehaviors</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="36eb1-204">Ruft ab oder legt eine Liste der Verhaltensweisen, die ändern oder Anpassen von Anforderungen an den Batch-Dienst, die über dieses <see cref="T:Microsoft.Azure.Batch.CloudJob" />.</span><span class="sxs-lookup"><span data-stu-id="36eb1-204">Gets or sets a list of behaviors that modify or customize requests to the Batch service made via this <see cref="T:Microsoft.Azure.Batch.CloudJob" />.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
          <para><span data-ttu-id="36eb1-205">Diese Verhaltensweisen werden von untergeordneten Objekten geerbt.</span><span class="sxs-lookup"><span data-stu-id="36eb1-205">These behaviors are inherited by child objects.</span></span></para>
          <para><span data-ttu-id="36eb1-206">Änderungen werden in der Reihenfolge der Auflistung angewendet.</span><span class="sxs-lookup"><span data-stu-id="36eb1-206">Modifications are applied in the order of the collection.</span></span> <span data-ttu-id="36eb1-207">Der letzte write Wins.</span><span class="sxs-lookup"><span data-stu-id="36eb1-207">The last write wins.</span></span></para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="Delete">
      <MemberSignature Language="C#" Value="public void Delete (System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance void Delete(class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.CloudJob.Delete(System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior})" />
      <MemberSignature Language="VB.NET" Value="Public Sub Delete (Optional additionalBehaviors As IEnumerable(Of BatchClientBehavior) = null)" />
      <MemberSignature Language="F#" Value="member this.Delete : seq&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; -&gt; unit" Usage="cloudJob.Delete additionalBehaviors" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="additionalBehaviors" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt;" />
      </Parameters>
      <Docs>
        <param name="additionalBehaviors"><span data-ttu-id="36eb1-208">Eine Auflistung von <see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" /> Instanzen, die für die Batchanforderung-Dienst nach gelten die <see cref="P:Microsoft.Azure.Batch.CloudJob.CustomBehaviors" />.</span><span class="sxs-lookup"><span data-stu-id="36eb1-208">A collection of <see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" /> instances that are applied to the Batch service request after the <see cref="P:Microsoft.Azure.Batch.CloudJob.CustomBehaviors" />.</span></span></param>
        <summary>
            <span data-ttu-id="36eb1-209">Löscht dieses <see cref="T:Microsoft.Azure.Batch.CloudJob" />.</span><span class="sxs-lookup"><span data-stu-id="36eb1-209">Deletes this <see cref="T:Microsoft.Azure.Batch.CloudJob" />.</span></span>
            </summary>
        <remarks>
          <para><span data-ttu-id="36eb1-210">Der Löschvorgang fordert, dass der Auftrag gelöscht werden.</span><span class="sxs-lookup"><span data-stu-id="36eb1-210">The delete operation requests that the job be deleted.</span></span>  <span data-ttu-id="36eb1-211">Die Anforderung setzt den Auftrag in der <see cref="F:Microsoft.Azure.Batch.Common.JobState.Deleting" /> Zustand.</span><span class="sxs-lookup"><span data-stu-id="36eb1-211">The request puts the job in the <see cref="F:Microsoft.Azure.Batch.Common.JobState.Deleting" /> state.</span></span>
            <span data-ttu-id="36eb1-212">Der Batch-Dienst beendet alle ausgeführten Aufgaben und das tatsächliche Auftrag löschen, ohne weitere Clientaktion ausführen.</span><span class="sxs-lookup"><span data-stu-id="36eb1-212">The Batch service will stop any running tasks and perform the actual job deletion without any further client action.</span></span></para>
          <para><span data-ttu-id="36eb1-213">Dies ist ein blockierender Vorgang.</span><span class="sxs-lookup"><span data-stu-id="36eb1-213">This is a blocking operation.</span></span> <span data-ttu-id="36eb1-214">Eine nicht blockierende Entsprechung, finden Sie unter <see cref="M:Microsoft.Azure.Batch.CloudJob.DeleteAsync(System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior},System.Threading.CancellationToken)" />.</span><span class="sxs-lookup"><span data-stu-id="36eb1-214">For a non-blocking equivalent, see <see cref="M:Microsoft.Azure.Batch.CloudJob.DeleteAsync(System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior},System.Threading.CancellationToken)" />.</span></span></para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task DeleteAsync (System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task DeleteAsync(class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.CloudJob.DeleteAsync(System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.DeleteAsync : seq&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="cloudJob.DeleteAsync (additionalBehaviors, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="additionalBehaviors" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="additionalBehaviors"><span data-ttu-id="36eb1-215">Eine Auflistung von <see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" /> Instanzen, die für die Batchanforderung-Dienst nach gelten die <see cref="P:Microsoft.Azure.Batch.CloudJob.CustomBehaviors" />.</span><span class="sxs-lookup"><span data-stu-id="36eb1-215">A collection of <see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" /> instances that are applied to the Batch service request after the <see cref="P:Microsoft.Azure.Batch.CloudJob.CustomBehaviors" />.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="36eb1-216">Ein <see cref="T:System.Threading.CancellationToken" /> für die Steuerung der Lebensdauer eines asynchronen Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="36eb1-216">A <see cref="T:System.Threading.CancellationToken" /> for controlling the lifetime of the asynchronous operation.</span></span></param>
        <summary>
            <span data-ttu-id="36eb1-217">Löscht dieses <see cref="T:Microsoft.Azure.Batch.CloudJob" />.</span><span class="sxs-lookup"><span data-stu-id="36eb1-217">Deletes this <see cref="T:Microsoft.Azure.Batch.CloudJob" />.</span></span>
            </summary>
        <returns><span data-ttu-id="36eb1-218">Ein <see cref="T:System.Threading.Tasks.Task" />-Element, das den asynchronen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="36eb1-218">A <see cref="T:System.Threading.Tasks.Task" /> that represents the asynchronous operation.</span></span></returns>
        <remarks>
          <para><span data-ttu-id="36eb1-219">Der Löschvorgang fordert, dass der Auftrag gelöscht werden.</span><span class="sxs-lookup"><span data-stu-id="36eb1-219">The delete operation requests that the job be deleted.</span></span>  <span data-ttu-id="36eb1-220">Die Anforderung setzt den Auftrag in der <see cref="F:Microsoft.Azure.Batch.Common.JobState.Deleting" /> Zustand.</span><span class="sxs-lookup"><span data-stu-id="36eb1-220">The request puts the job in the <see cref="F:Microsoft.Azure.Batch.Common.JobState.Deleting" /> state.</span></span>
            <span data-ttu-id="36eb1-221">Der Batch-Dienst beendet alle ausgeführten Aufgaben und das tatsächliche Auftrag löschen, ohne weitere Clientaktion ausführen.</span><span class="sxs-lookup"><span data-stu-id="36eb1-221">The Batch service will stop any running tasks and perform the actual job deletion without any further client action.</span></span></para>
          <para><span data-ttu-id="36eb1-222">Der Löschvorgang wird asynchron ausgeführt.</span><span class="sxs-lookup"><span data-stu-id="36eb1-222">The delete operation runs asynchronously.</span></span></para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="Disable">
      <MemberSignature Language="C#" Value="public void Disable (Microsoft.Azure.Batch.Common.DisableJobOption disableJobOption, System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance void Disable(valuetype Microsoft.Azure.Batch.Common.DisableJobOption disableJobOption, class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.CloudJob.Disable(Microsoft.Azure.Batch.Common.DisableJobOption,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior})" />
      <MemberSignature Language="F#" Value="member this.Disable : Microsoft.Azure.Batch.Common.DisableJobOption * seq&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; -&gt; unit" Usage="cloudJob.Disable (disableJobOption, additionalBehaviors)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="disableJobOption" Type="Microsoft.Azure.Batch.Common.DisableJobOption" />
        <Parameter Name="additionalBehaviors" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt;" />
      </Parameters>
      <Docs>
        <param name="disableJobOption"><span data-ttu-id="36eb1-223">Gibt an, was mit aktiven Aufgaben, die dem Auftrag zugeordnet sind.</span><span class="sxs-lookup"><span data-stu-id="36eb1-223">Specifies what to do with active tasks associated with the job.</span></span></param>
        <param name="additionalBehaviors"><span data-ttu-id="36eb1-224">Eine Auflistung von <see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" /> Instanzen, die für die Batchanforderung-Dienst nach gelten die <see cref="P:Microsoft.Azure.Batch.CloudJob.CustomBehaviors" />.</span><span class="sxs-lookup"><span data-stu-id="36eb1-224">A collection of <see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" /> instances that are applied to the Batch service request after the <see cref="P:Microsoft.Azure.Batch.CloudJob.CustomBehaviors" />.</span></span></param>
        <summary>
            <span data-ttu-id="36eb1-225">Deaktiviert diese <see cref="T:Microsoft.Azure.Batch.CloudJob" />.</span><span class="sxs-lookup"><span data-stu-id="36eb1-225">Disables this <see cref="T:Microsoft.Azure.Batch.CloudJob" />.</span></span>  <span data-ttu-id="36eb1-226">Deaktivierte Aufträge neue Aufgaben nicht ausführen, aber möglicherweise erneut aktiviert werden weiter unten.</span><span class="sxs-lookup"><span data-stu-id="36eb1-226">Disabled jobs do not run new tasks, but may be re-enabled later.</span></span>
            </summary>
        <remarks><span data-ttu-id="36eb1-227">Dies ist ein blockierender Vorgang.</span><span class="sxs-lookup"><span data-stu-id="36eb1-227">This is a blocking operation.</span></span> <span data-ttu-id="36eb1-228">Eine nicht blockierende Entsprechung, finden Sie unter <see cref="M:Microsoft.Azure.Batch.CloudJob.DisableAsync(Microsoft.Azure.Batch.Common.DisableJobOption,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior},System.Threading.CancellationToken)" />.</span><span class="sxs-lookup"><span data-stu-id="36eb1-228">For a non-blocking equivalent, see <see cref="M:Microsoft.Azure.Batch.CloudJob.DisableAsync(Microsoft.Azure.Batch.Common.DisableJobOption,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior},System.Threading.CancellationToken)" />.</span></span></remarks>
      </Docs>
    </Member>
    <Member MemberName="DisableAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task DisableAsync (Microsoft.Azure.Batch.Common.DisableJobOption disableJobOption, System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task DisableAsync(valuetype Microsoft.Azure.Batch.Common.DisableJobOption disableJobOption, class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.CloudJob.DisableAsync(Microsoft.Azure.Batch.Common.DisableJobOption,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.DisableAsync : Microsoft.Azure.Batch.Common.DisableJobOption * seq&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="cloudJob.DisableAsync (disableJobOption, additionalBehaviors, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="disableJobOption" Type="Microsoft.Azure.Batch.Common.DisableJobOption" />
        <Parameter Name="additionalBehaviors" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="disableJobOption"><span data-ttu-id="36eb1-229">Gibt an, was mit aktiven Aufgaben, die dem Auftrag zugeordnet sind.</span><span class="sxs-lookup"><span data-stu-id="36eb1-229">Specifies what to do with active tasks associated with the job.</span></span></param>
        <param name="additionalBehaviors"><span data-ttu-id="36eb1-230">Eine Auflistung von <see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" /> Instanzen, die für die Batchanforderung-Dienst nach gelten die <see cref="P:Microsoft.Azure.Batch.CloudJob.CustomBehaviors" />.</span><span class="sxs-lookup"><span data-stu-id="36eb1-230">A collection of <see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" /> instances that are applied to the Batch service request after the <see cref="P:Microsoft.Azure.Batch.CloudJob.CustomBehaviors" />.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="36eb1-231">Ein <see cref="T:System.Threading.CancellationToken" /> für die Steuerung der Lebensdauer eines asynchronen Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="36eb1-231">A <see cref="T:System.Threading.CancellationToken" /> for controlling the lifetime of the asynchronous operation.</span></span></param>
        <summary>
            <span data-ttu-id="36eb1-232">Deaktiviert diese <see cref="T:Microsoft.Azure.Batch.CloudJob" />.</span><span class="sxs-lookup"><span data-stu-id="36eb1-232">Disables this <see cref="T:Microsoft.Azure.Batch.CloudJob" />.</span></span>  <span data-ttu-id="36eb1-233">Deaktivierte Aufträge neue Aufgaben nicht ausführen, aber möglicherweise erneut aktiviert werden weiter unten.</span><span class="sxs-lookup"><span data-stu-id="36eb1-233">Disabled jobs do not run new tasks, but may be re-enabled later.</span></span>
            </summary>
        <returns><span data-ttu-id="36eb1-234">Ein <see cref="T:System.Threading.Tasks.Task" />-Element, das den asynchronen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="36eb1-234">A <see cref="T:System.Threading.Tasks.Task" /> that represents the asynchronous operation.</span></span></returns>
        <remarks><span data-ttu-id="36eb1-235">Der Deaktivierungsvorgang wird asynchron ausgeführt.</span><span class="sxs-lookup"><span data-stu-id="36eb1-235">The disable operation runs asynchronously.</span></span></remarks>
      </Docs>
    </Member>
    <Member MemberName="DisplayName">
      <MemberSignature Language="C#" Value="public string DisplayName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string DisplayName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.CloudJob.DisplayName" />
      <MemberSignature Language="VB.NET" Value="Public Property DisplayName As String" />
      <MemberSignature Language="F#" Value="member this.DisplayName : string with get, set" Usage="Microsoft.Azure.Batch.CloudJob.DisplayName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="36eb1-236">Ruft ab oder legt den Anzeigenamen des Auftrags.</span><span class="sxs-lookup"><span data-stu-id="36eb1-236">Gets or sets the display name of the job.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Enable">
      <MemberSignature Language="C#" Value="public void Enable (System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance void Enable(class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.CloudJob.Enable(System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior})" />
      <MemberSignature Language="VB.NET" Value="Public Sub Enable (Optional additionalBehaviors As IEnumerable(Of BatchClientBehavior) = null)" />
      <MemberSignature Language="F#" Value="member this.Enable : seq&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; -&gt; unit" Usage="cloudJob.Enable additionalBehaviors" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="additionalBehaviors" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt;" />
      </Parameters>
      <Docs>
        <param name="additionalBehaviors"><span data-ttu-id="36eb1-237">Eine Auflistung von <see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" /> Instanzen, die für die Batchanforderung-Dienst nach gelten die <see cref="P:Microsoft.Azure.Batch.CloudJob.CustomBehaviors" />.</span><span class="sxs-lookup"><span data-stu-id="36eb1-237">A collection of <see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" /> instances that are applied to the Batch service request after the <see cref="P:Microsoft.Azure.Batch.CloudJob.CustomBehaviors" />.</span></span></param>
        <summary>
            <span data-ttu-id="36eb1-238">Dies ermöglicht <see cref="T:Microsoft.Azure.Batch.CloudJob" />, neue Aufgaben ausführen.</span><span class="sxs-lookup"><span data-stu-id="36eb1-238">Enables this <see cref="T:Microsoft.Azure.Batch.CloudJob" />, allowing new tasks to run.</span></span>
            </summary>
        <remarks><span data-ttu-id="36eb1-239">Dies ist ein blockierender Vorgang.</span><span class="sxs-lookup"><span data-stu-id="36eb1-239">This is a blocking operation.</span></span> <span data-ttu-id="36eb1-240">Eine nicht blockierende Entsprechung, finden Sie unter <see cref="M:Microsoft.Azure.Batch.CloudJob.EnableAsync(System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior},System.Threading.CancellationToken)" />.</span><span class="sxs-lookup"><span data-stu-id="36eb1-240">For a non-blocking equivalent, see <see cref="M:Microsoft.Azure.Batch.CloudJob.EnableAsync(System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior},System.Threading.CancellationToken)" />.</span></span></remarks>
      </Docs>
    </Member>
    <Member MemberName="EnableAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task EnableAsync (System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task EnableAsync(class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.CloudJob.EnableAsync(System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.EnableAsync : seq&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="cloudJob.EnableAsync (additionalBehaviors, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="additionalBehaviors" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="additionalBehaviors"><span data-ttu-id="36eb1-241">Eine Auflistung von <see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" /> Instanzen, die für die Batchanforderung-Dienst nach gelten die <see cref="P:Microsoft.Azure.Batch.CloudJob.CustomBehaviors" />.</span><span class="sxs-lookup"><span data-stu-id="36eb1-241">A collection of <see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" /> instances that are applied to the Batch service request after the <see cref="P:Microsoft.Azure.Batch.CloudJob.CustomBehaviors" />.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="36eb1-242">Ein <see cref="T:System.Threading.CancellationToken" /> für die Steuerung der Lebensdauer eines asynchronen Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="36eb1-242">A <see cref="T:System.Threading.CancellationToken" /> for controlling the lifetime of the asynchronous operation.</span></span></param>
        <summary>
            <span data-ttu-id="36eb1-243">Dies ermöglicht <see cref="T:Microsoft.Azure.Batch.CloudJob" />, neue Aufgaben ausführen.</span><span class="sxs-lookup"><span data-stu-id="36eb1-243">Enables this <see cref="T:Microsoft.Azure.Batch.CloudJob" />, allowing new tasks to run.</span></span>
            </summary>
        <returns><span data-ttu-id="36eb1-244">Ein <see cref="T:System.Threading.Tasks.Task" />-Element, das den asynchronen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="36eb1-244">A <see cref="T:System.Threading.Tasks.Task" /> that represents the asynchronous operation.</span></span></returns>
        <remarks><span data-ttu-id="36eb1-245">Der Aktivierungsvorgang wird asynchron ausgeführt.</span><span class="sxs-lookup"><span data-stu-id="36eb1-245">The enable operation runs asynchronously.</span></span></remarks>
      </Docs>
    </Member>
    <Member MemberName="ETag">
      <MemberSignature Language="C#" Value="public string ETag { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ETag" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.CloudJob.ETag" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ETag As String" />
      <MemberSignature Language="F#" Value="member this.ETag : string" Usage="Microsoft.Azure.Batch.CloudJob.ETag" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="36eb1-246">Ruft das ETag für den Auftrag ab.</span><span class="sxs-lookup"><span data-stu-id="36eb1-246">Gets the ETag for the job.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ExecutionInformation">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Batch.JobExecutionInformation ExecutionInformation { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Batch.JobExecutionInformation ExecutionInformation" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.CloudJob.ExecutionInformation" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ExecutionInformation As JobExecutionInformation" />
      <MemberSignature Language="F#" Value="member this.ExecutionInformation : Microsoft.Azure.Batch.JobExecutionInformation" Usage="Microsoft.Azure.Batch.CloudJob.ExecutionInformation" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.JobExecutionInformation</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="36eb1-247">Ruft die Ausführungsinformationen für den Auftrag ab.</span><span class="sxs-lookup"><span data-stu-id="36eb1-247">Gets the execution information for the job.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetTask">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Batch.CloudTask GetTask (string taskId, Microsoft.Azure.Batch.DetailLevel detailLevel = null, System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class Microsoft.Azure.Batch.CloudTask GetTask(string taskId, class Microsoft.Azure.Batch.DetailLevel detailLevel, class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.CloudJob.GetTask(System.String,Microsoft.Azure.Batch.DetailLevel,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior})" />
      <MemberSignature Language="F#" Value="member this.GetTask : string * Microsoft.Azure.Batch.DetailLevel * seq&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; -&gt; Microsoft.Azure.Batch.CloudTask" Usage="cloudJob.GetTask (taskId, detailLevel, additionalBehaviors)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.CloudTask</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="taskId" Type="System.String" />
        <Parameter Name="detailLevel" Type="Microsoft.Azure.Batch.DetailLevel" />
        <Parameter Name="additionalBehaviors" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt;" />
      </Parameters>
      <Docs>
        <param name="taskId"><span data-ttu-id="36eb1-248">Die Id des Tasks abgerufen werden soll.</span><span class="sxs-lookup"><span data-stu-id="36eb1-248">The id of the task to get.</span></span></param>
        <param name="detailLevel"><span data-ttu-id="36eb1-249">Ein <see cref="T:Microsoft.Azure.Batch.DetailLevel" /> gesteuert, welche Eigenschaften aus dem Dienst abgerufen werden.</span><span class="sxs-lookup"><span data-stu-id="36eb1-249">A <see cref="T:Microsoft.Azure.Batch.DetailLevel" /> used for controlling which properties are retrieved from the service.</span></span></param>
        <param name="additionalBehaviors"><span data-ttu-id="36eb1-250">Eine Auflistung von <see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" /> Instanzen, die für die Batchanforderung-Dienst nach gelten die <see cref="P:Microsoft.Azure.Batch.CloudJob.CustomBehaviors" /> und <paramref name="detailLevel" />.</span><span class="sxs-lookup"><span data-stu-id="36eb1-250">A collection of <see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" /> instances that are applied to the Batch service request after the <see cref="P:Microsoft.Azure.Batch.CloudJob.CustomBehaviors" /> and <paramref name="detailLevel" />.</span></span></param>
        <summary>
            <span data-ttu-id="36eb1-251">Ruft den angegebenen <see cref="T:Microsoft.Azure.Batch.CloudTask" /> ab.</span><span class="sxs-lookup"><span data-stu-id="36eb1-251">Gets the specified <see cref="T:Microsoft.Azure.Batch.CloudTask" />.</span></span>
            </summary>
        <returns><span data-ttu-id="36eb1-252">Ein <see cref="T:Microsoft.Azure.Batch.CloudTask" /> mit Informationen über die angegebene Azure Batch-Aufgabe.</span><span class="sxs-lookup"><span data-stu-id="36eb1-252">A <see cref="T:Microsoft.Azure.Batch.CloudTask" /> containing information about the specified Azure Batch task.</span></span></returns>
        <remarks><span data-ttu-id="36eb1-253">Dies ist ein blockierender Vorgang.</span><span class="sxs-lookup"><span data-stu-id="36eb1-253">This is a blocking operation.</span></span> <span data-ttu-id="36eb1-254">Eine nicht blockierende Entsprechung, finden Sie unter <see cref="M:Microsoft.Azure.Batch.CloudJob.GetTaskAsync(System.String,Microsoft.Azure.Batch.DetailLevel,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior},System.Threading.CancellationToken)" />.</span><span class="sxs-lookup"><span data-stu-id="36eb1-254">For a non-blocking equivalent, see <see cref="M:Microsoft.Azure.Batch.CloudJob.GetTaskAsync(System.String,Microsoft.Azure.Batch.DetailLevel,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior},System.Threading.CancellationToken)" />.</span></span></remarks>
      </Docs>
    </Member>
    <Member MemberName="GetTaskAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Batch.CloudTask&gt; GetTaskAsync (string taskId, Microsoft.Azure.Batch.DetailLevel detailLevel = null, System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Batch.CloudTask&gt; GetTaskAsync(string taskId, class Microsoft.Azure.Batch.DetailLevel detailLevel, class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.CloudJob.GetTaskAsync(System.String,Microsoft.Azure.Batch.DetailLevel,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.GetTaskAsync : string * Microsoft.Azure.Batch.DetailLevel * seq&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Batch.CloudTask&gt;" Usage="cloudJob.GetTaskAsync (taskId, detailLevel, additionalBehaviors, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Batch.CloudJob/&lt;GetTaskAsync&gt;d__9))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Batch.CloudTask&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="taskId" Type="System.String" />
        <Parameter Name="detailLevel" Type="Microsoft.Azure.Batch.DetailLevel" />
        <Parameter Name="additionalBehaviors" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="taskId"><span data-ttu-id="36eb1-255">Die Id des Tasks abgerufen werden soll.</span><span class="sxs-lookup"><span data-stu-id="36eb1-255">The id of the task to get.</span></span></param>
        <param name="detailLevel"><span data-ttu-id="36eb1-256">Ein <see cref="T:Microsoft.Azure.Batch.DetailLevel" /> gesteuert, welche Eigenschaften aus dem Dienst abgerufen werden.</span><span class="sxs-lookup"><span data-stu-id="36eb1-256">A <see cref="T:Microsoft.Azure.Batch.DetailLevel" /> used for controlling which properties are retrieved from the service.</span></span></param>
        <param name="additionalBehaviors"><span data-ttu-id="36eb1-257">Eine Auflistung von <see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" /> Instanzen, die für die Batchanforderung-Dienst nach gelten die <see cref="P:Microsoft.Azure.Batch.CloudJob.CustomBehaviors" /> und <paramref name="detailLevel" />.</span><span class="sxs-lookup"><span data-stu-id="36eb1-257">A collection of <see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" /> instances that are applied to the Batch service request after the <see cref="P:Microsoft.Azure.Batch.CloudJob.CustomBehaviors" /> and <paramref name="detailLevel" />.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="36eb1-258">Ein <see cref="T:System.Threading.CancellationToken" /> für die Steuerung der Lebensdauer eines asynchronen Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="36eb1-258">A <see cref="T:System.Threading.CancellationToken" /> for controlling the lifetime of the asynchronous operation.</span></span></param>
        <summary>
            <span data-ttu-id="36eb1-259">Ruft den angegebenen <see cref="T:Microsoft.Azure.Batch.CloudTask" /> ab.</span><span class="sxs-lookup"><span data-stu-id="36eb1-259">Gets the specified <see cref="T:Microsoft.Azure.Batch.CloudTask" />.</span></span>
            </summary>
        <returns><span data-ttu-id="36eb1-260">Ein <see cref="T:Microsoft.Azure.Batch.CloudTask" /> mit Informationen über die angegebene Azure Batch-Aufgabe.</span><span class="sxs-lookup"><span data-stu-id="36eb1-260">A <see cref="T:Microsoft.Azure.Batch.CloudTask" /> containing information about the specified Azure Batch task.</span></span></returns>
        <remarks><span data-ttu-id="36eb1-261">Der Abrufvorgang für die Aufgabe wird asynchron ausgeführt.</span><span class="sxs-lookup"><span data-stu-id="36eb1-261">The get task operation runs asynchronously.</span></span></remarks>
      </Docs>
    </Member>
    <Member MemberName="GetTaskCounts">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Batch.TaskCounts GetTaskCounts (System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class Microsoft.Azure.Batch.TaskCounts GetTaskCounts(class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.CloudJob.GetTaskCounts(System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior})" />
      <MemberSignature Language="VB.NET" Value="Public Function GetTaskCounts (Optional additionalBehaviors As IEnumerable(Of BatchClientBehavior) = null) As TaskCounts" />
      <MemberSignature Language="F#" Value="member this.GetTaskCounts : seq&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; -&gt; Microsoft.Azure.Batch.TaskCounts" Usage="cloudJob.GetTaskCounts additionalBehaviors" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.TaskCounts</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="additionalBehaviors" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt;" />
      </Parameters>
      <Docs>
        <param name="additionalBehaviors"><span data-ttu-id="36eb1-262">Eine Auflistung von <see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" /> Instanzen, die für die Batchanforderung-Dienst nach gelten die <see cref="P:Microsoft.Azure.Batch.CloudJob.CustomBehaviors" />.</span><span class="sxs-lookup"><span data-stu-id="36eb1-262">A collection of <see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" /> instances that are applied to the Batch service request after the <see cref="P:Microsoft.Azure.Batch.CloudJob.CustomBehaviors" />.</span></span></param>
        <summary>
            <span data-ttu-id="36eb1-263">Ruft die Anzahl der Task für den Auftrag ab.</span><span class="sxs-lookup"><span data-stu-id="36eb1-263">Gets the task counts for the job.</span></span>
            </summary>
        <returns><span data-ttu-id="36eb1-264">Ein <see cref="T:Microsoft.Azure.Batch.TaskCounts" /> Objekt mit dem Task für den Auftrag zählt</span><span class="sxs-lookup"><span data-stu-id="36eb1-264">A <see cref="T:Microsoft.Azure.Batch.TaskCounts" /> object containing the task counts for the job</span></span></returns>
        <remarks><span data-ttu-id="36eb1-265">Dies ist ein blockierender Vorgang.</span><span class="sxs-lookup"><span data-stu-id="36eb1-265">This is a blocking operation.</span></span> <span data-ttu-id="36eb1-266">Eine nicht blockierende Entsprechung, finden Sie unter <see cref="M:Microsoft.Azure.Batch.CloudJob.GetTaskCountsAsync(System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior},System.Threading.CancellationToken)" />.</span><span class="sxs-lookup"><span data-stu-id="36eb1-266">For a non-blocking equivalent, see <see cref="M:Microsoft.Azure.Batch.CloudJob.GetTaskCountsAsync(System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior},System.Threading.CancellationToken)" />.</span></span></remarks>
      </Docs>
    </Member>
    <Member MemberName="GetTaskCountsAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Batch.TaskCounts&gt; GetTaskCountsAsync (System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Batch.TaskCounts&gt; GetTaskCountsAsync(class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.CloudJob.GetTaskCountsAsync(System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.GetTaskCountsAsync : seq&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Batch.TaskCounts&gt;" Usage="cloudJob.GetTaskCountsAsync (additionalBehaviors, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Batch.CloudJob/&lt;GetTaskCountsAsync&gt;d__21))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Batch.TaskCounts&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="additionalBehaviors" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="additionalBehaviors"><span data-ttu-id="36eb1-267">Eine Auflistung von <see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" /> Instanzen, die für die Batchanforderung-Dienst nach gelten die <see cref="P:Microsoft.Azure.Batch.CloudJob.CustomBehaviors" />.</span><span class="sxs-lookup"><span data-stu-id="36eb1-267">A collection of <see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" /> instances that are applied to the Batch service request after the <see cref="P:Microsoft.Azure.Batch.CloudJob.CustomBehaviors" />.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="36eb1-268">Ein <see cref="T:System.Threading.CancellationToken" /> für die Steuerung der Lebensdauer eines asynchronen Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="36eb1-268">A <see cref="T:System.Threading.CancellationToken" /> for controlling the lifetime of the asynchronous operation.</span></span></param>
        <summary>
            <span data-ttu-id="36eb1-269">Ruft die Anzahl der Task für den Auftrag ab.</span><span class="sxs-lookup"><span data-stu-id="36eb1-269">Gets the task counts for the job.</span></span>
            </summary>
        <returns><span data-ttu-id="36eb1-270">Ein <see cref="T:Microsoft.Azure.Batch.TaskCounts" /> Objekt mit dem Task für den Auftrag zählt.</span><span class="sxs-lookup"><span data-stu-id="36eb1-270">A <see cref="T:Microsoft.Azure.Batch.TaskCounts" /> object containing the task counts for the job.</span></span></returns>
        <remarks><span data-ttu-id="36eb1-271">Die Get-Auftragstasks zählt Vorgang ausgeführt wird asynchron aus.</span><span class="sxs-lookup"><span data-stu-id="36eb1-271">The get job task counts operation runs asynchronously.</span></span></remarks>
      </Docs>
    </Member>
    <Member MemberName="Id">
      <MemberSignature Language="C#" Value="public string Id { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Id" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.CloudJob.Id" />
      <MemberSignature Language="VB.NET" Value="Public Property Id As String" />
      <MemberSignature Language="F#" Value="member this.Id : string with get, set" Usage="Microsoft.Azure.Batch.CloudJob.Id" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="36eb1-272">Ruft ab oder legt die Id des Auftrags.</span><span class="sxs-lookup"><span data-stu-id="36eb1-272">Gets or sets the id of the job.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="JobManagerTask">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Batch.JobManagerTask JobManagerTask { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Batch.JobManagerTask JobManagerTask" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.CloudJob.JobManagerTask" />
      <MemberSignature Language="VB.NET" Value="Public Property JobManagerTask As JobManagerTask" />
      <MemberSignature Language="F#" Value="member this.JobManagerTask : Microsoft.Azure.Batch.JobManagerTask with get, set" Usage="Microsoft.Azure.Batch.CloudJob.JobManagerTask" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.JobManagerTask</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="36eb1-273">Ruft ab oder legt die Auftrags-Manager-Aufgabe.</span><span class="sxs-lookup"><span data-stu-id="36eb1-273">Gets or sets the Job Manager task.</span></span> <span data-ttu-id="36eb1-274">Die Auftrags-Manager-Aufgabe wird gestartet, wenn der <see cref="T:Microsoft.Azure.Batch.CloudJob" /> gestartet wird.</span><span class="sxs-lookup"><span data-stu-id="36eb1-274">The Job Manager task is launched when the <see cref="T:Microsoft.Azure.Batch.CloudJob" /> is started.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="JobPreparationTask">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Batch.JobPreparationTask JobPreparationTask { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Batch.JobPreparationTask JobPreparationTask" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.CloudJob.JobPreparationTask" />
      <MemberSignature Language="VB.NET" Value="Public Property JobPreparationTask As JobPreparationTask" />
      <MemberSignature Language="F#" Value="member this.JobPreparationTask : Microsoft.Azure.Batch.JobPreparationTask with get, set" Usage="Microsoft.Azure.Batch.CloudJob.JobPreparationTask" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.JobPreparationTask</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="36eb1-275">Übernimmt oder bestimmt die Vorbereitung des Auftrags-Aufgabe.</span><span class="sxs-lookup"><span data-stu-id="36eb1-275">Gets or sets the Job Preparation task.</span></span> <span data-ttu-id="36eb1-276">Der Batch-Dienst wird die Auftrag zur Vorbereitung Aufgabe vor dem Starten alle Aufgaben dieses Auftrags auf diesem Computeknoten auf einem Serverknoten ausgeführt.</span><span class="sxs-lookup"><span data-stu-id="36eb1-276">The Batch service will run the Job Preparation task on a compute node before starting any tasks of that job on that compute node.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="JobReleaseTask">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Batch.JobReleaseTask JobReleaseTask { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Batch.JobReleaseTask JobReleaseTask" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.CloudJob.JobReleaseTask" />
      <MemberSignature Language="VB.NET" Value="Public Property JobReleaseTask As JobReleaseTask" />
      <MemberSignature Language="F#" Value="member this.JobReleaseTask : Microsoft.Azure.Batch.JobReleaseTask with get, set" Usage="Microsoft.Azure.Batch.CloudJob.JobReleaseTask" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.JobReleaseTask</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="36eb1-277">Ruft ab oder legt die Version des Auftrags fest.</span><span class="sxs-lookup"><span data-stu-id="36eb1-277">Gets or sets the Job Release task.</span></span> <span data-ttu-id="36eb1-278">Der Batch-Dienst führt den Auftrag Version Task aus, wenn der Auftrag beendet, in dem jede Aufgabe des Auftrags ausgeführt wurde, auf jedem Computeknoten.</span><span class="sxs-lookup"><span data-stu-id="36eb1-278">The Batch service runs the Job Release task when the job ends, on each compute node where any task of the job has run.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="LastModified">
      <MemberSignature Language="C#" Value="public Nullable&lt;DateTime&gt; LastModified { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; LastModified" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.CloudJob.LastModified" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property LastModified As Nullable(Of DateTime)" />
      <MemberSignature Language="F#" Value="member this.LastModified : Nullable&lt;DateTime&gt;" Usage="Microsoft.Azure.Batch.CloudJob.LastModified" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.DateTime&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="36eb1-279">Ruft den Zeitpunkt der letzten Änderung des Auftrags ab.</span><span class="sxs-lookup"><span data-stu-id="36eb1-279">Gets the last modified time of the job.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListTasks">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Batch.IPagedEnumerable&lt;Microsoft.Azure.Batch.CloudTask&gt; ListTasks (Microsoft.Azure.Batch.DetailLevel detailLevel = null, System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class Microsoft.Azure.Batch.IPagedEnumerable`1&lt;class Microsoft.Azure.Batch.CloudTask&gt; ListTasks(class Microsoft.Azure.Batch.DetailLevel detailLevel, class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.CloudJob.ListTasks(Microsoft.Azure.Batch.DetailLevel,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior})" />
      <MemberSignature Language="F#" Value="member this.ListTasks : Microsoft.Azure.Batch.DetailLevel * seq&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; -&gt; Microsoft.Azure.Batch.IPagedEnumerable&lt;Microsoft.Azure.Batch.CloudTask&gt;" Usage="cloudJob.ListTasks (detailLevel, additionalBehaviors)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.IPagedEnumerable&lt;Microsoft.Azure.Batch.CloudTask&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="detailLevel" Type="Microsoft.Azure.Batch.DetailLevel" />
        <Parameter Name="additionalBehaviors" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt;" />
      </Parameters>
      <Docs>
        <param name="detailLevel"><span data-ttu-id="36eb1-280">Ein <see cref="T:Microsoft.Azure.Batch.DetailLevel" /> verwendet, der zum Filtern der Liste und zum Steuern, welche Eigenschaften aus dem Dienst abgerufen werden.</span><span class="sxs-lookup"><span data-stu-id="36eb1-280">A <see cref="T:Microsoft.Azure.Batch.DetailLevel" /> used for filtering the list and for controlling which properties are retrieved from the service.</span></span></param>
        <param name="additionalBehaviors"><span data-ttu-id="36eb1-281">Eine Auflistung von <see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" /> Instanzen, die für die Batchanforderung-Dienst nach gelten die <see cref="P:Microsoft.Azure.Batch.CloudJob.CustomBehaviors" /> und <paramref name="detailLevel" />.</span><span class="sxs-lookup"><span data-stu-id="36eb1-281">A collection of <see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" /> instances that are applied to the Batch service request after the <see cref="P:Microsoft.Azure.Batch.CloudJob.CustomBehaviors" /> and <paramref name="detailLevel" />.</span></span></param>
        <summary>
            <span data-ttu-id="36eb1-282">Listet die <see cref="T:Microsoft.Azure.Batch.CloudTask">Aufgaben</see> dieses <see cref="T:Microsoft.Azure.Batch.CloudJob" />.</span><span class="sxs-lookup"><span data-stu-id="36eb1-282">Enumerates the <see cref="T:Microsoft.Azure.Batch.CloudTask">tasks</see> of this <see cref="T:Microsoft.Azure.Batch.CloudJob" />.</span></span>
            </summary>
        <returns><span data-ttu-id="36eb1-283">Eine <see cref="T:Microsoft.Azure.Batch.IPagedEnumerable`1" /> , die Aufgaben auflisten, synchron oder asynchron verwendet werden kann.</span><span class="sxs-lookup"><span data-stu-id="36eb1-283">An <see cref="T:Microsoft.Azure.Batch.IPagedEnumerable`1" /> that can be used to enumerate tasks asynchronously or synchronously.</span></span></returns>
        <remarks><span data-ttu-id="36eb1-284">Diese Methode gibt sofort zurück. nur, wenn die Auflistung aufgezählt wird, werden die Aufgaben aus dem Batch-Dienst abgerufen.</span><span class="sxs-lookup"><span data-stu-id="36eb1-284">This method returns immediately; the tasks are retrieved from the Batch service only when the collection is enumerated.</span></span>
            <span data-ttu-id="36eb1-285">Datenabruf ist nicht atomaren; Aufgaben werden in Seiten während der Enumeration der Auflistung abgerufen.</span><span class="sxs-lookup"><span data-stu-id="36eb1-285">Retrieval is non-atomic; tasks are retrieved in pages during enumeration of the collection.</span></span></remarks>
      </Docs>
    </Member>
    <Member MemberName="Metadata">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.MetadataItem&gt; Metadata { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Batch.MetadataItem&gt; Metadata" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.CloudJob.Metadata" />
      <MemberSignature Language="VB.NET" Value="Public Property Metadata As IList(Of MetadataItem)" />
      <MemberSignature Language="F#" Value="member this.Metadata : System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.MetadataItem&gt; with get, set" Usage="Microsoft.Azure.Batch.CloudJob.Metadata" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.MetadataItem&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="36eb1-286">Ruft ab oder legt eine Liste von Name / Wert-Paaren, die dem Auftrag als Metadaten zugeordnet.</span><span class="sxs-lookup"><span data-stu-id="36eb1-286">Gets or sets a list of name-value pairs associated with the job as metadata.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnAllTasksComplete">
      <MemberSignature Language="C#" Value="public Nullable&lt;Microsoft.Azure.Batch.Common.OnAllTasksComplete&gt; OnAllTasksComplete { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Batch.Common.OnAllTasksComplete&gt; OnAllTasksComplete" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.CloudJob.OnAllTasksComplete" />
      <MemberSignature Language="VB.NET" Value="Public Property OnAllTasksComplete As Nullable(Of OnAllTasksComplete)" />
      <MemberSignature Language="F#" Value="member this.OnAllTasksComplete : Nullable&lt;Microsoft.Azure.Batch.Common.OnAllTasksComplete&gt; with get, set" Usage="Microsoft.Azure.Batch.CloudJob.OnAllTasksComplete" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;Microsoft.Azure.Batch.Common.OnAllTasksComplete&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="36eb1-287">Ruft ab oder legt fest, die Aktion den Batch, der Dienst abwartet, wenn alle Aufgaben im Auftrag in sind die <see cref="F:Microsoft.Azure.Batch.Common.JobState.Completed" /> Zustand.</span><span class="sxs-lookup"><span data-stu-id="36eb1-287">Gets or sets the action the Batch service should take when all tasks in the job are in the <see cref="F:Microsoft.Azure.Batch.Common.JobState.Completed" /> state.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnTaskFailure">
      <MemberSignature Language="C#" Value="public Nullable&lt;Microsoft.Azure.Batch.Common.OnTaskFailure&gt; OnTaskFailure { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Batch.Common.OnTaskFailure&gt; OnTaskFailure" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.CloudJob.OnTaskFailure" />
      <MemberSignature Language="VB.NET" Value="Public Property OnTaskFailure As Nullable(Of OnTaskFailure)" />
      <MemberSignature Language="F#" Value="member this.OnTaskFailure : Nullable&lt;Microsoft.Azure.Batch.Common.OnTaskFailure&gt; with get, set" Usage="Microsoft.Azure.Batch.CloudJob.OnTaskFailure" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;Microsoft.Azure.Batch.Common.OnTaskFailure&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="36eb1-288">Ruft ab oder legt fest, die Aktion, die der Batch-Dienst ausführen sollten, wenn jede Aufgabe im Auftrag ein Fehler auftritt.</span><span class="sxs-lookup"><span data-stu-id="36eb1-288">Gets or sets the action the Batch service should take when any task in the job fails.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="36eb1-289">Eine Aufgabe gilt als fehlgeschlagen betrachtet, wenn es mit einem Exitcode ungleich 0 (null) abgeschlossen, und die Wiederholungsanzahl verbraucht hat oder ein Planungsfehler wäre.</span><span class="sxs-lookup"><span data-stu-id="36eb1-289">A task is considered to have failed if it completes with a non-zero exit code and has exhausted its retry count, or if it had a scheduling error.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="PoolInformation">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Batch.PoolInformation PoolInformation { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Batch.PoolInformation PoolInformation" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.CloudJob.PoolInformation" />
      <MemberSignature Language="VB.NET" Value="Public Property PoolInformation As PoolInformation" />
      <MemberSignature Language="F#" Value="member this.PoolInformation : Microsoft.Azure.Batch.PoolInformation with get, set" Usage="Microsoft.Azure.Batch.CloudJob.PoolInformation" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.PoolInformation</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="36eb1-290">Abrufen oder festlegen den Pool, auf dem der Batch-Dienst den Auftrag Aufgaben ausgeführt wird.</span><span class="sxs-lookup"><span data-stu-id="36eb1-290">Gets or sets the pool on which the Batch service runs the job's tasks.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PreviousState">
      <MemberSignature Language="C#" Value="public Nullable&lt;Microsoft.Azure.Batch.Common.JobState&gt; PreviousState { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Batch.Common.JobState&gt; PreviousState" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.CloudJob.PreviousState" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property PreviousState As Nullable(Of JobState)" />
      <MemberSignature Language="F#" Value="member this.PreviousState : Nullable&lt;Microsoft.Azure.Batch.Common.JobState&gt;" Usage="Microsoft.Azure.Batch.CloudJob.PreviousState" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;Microsoft.Azure.Batch.Common.JobState&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="36eb1-291">Ruft den vorherigen Status des Auftrags ab.</span><span class="sxs-lookup"><span data-stu-id="36eb1-291">Gets the previous state of the job.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="36eb1-292">Wenn der Auftrag befindet sich in die erste <see cref="F:Microsoft.Azure.Batch.Common.JobState.Active" /> Zustand befindet, wird die PreviousState-Eigenschaft ist nicht definiert.</span><span class="sxs-lookup"><span data-stu-id="36eb1-292">If the job is in its initial <see cref="F:Microsoft.Azure.Batch.Common.JobState.Active" /> state, the PreviousState property is not defined.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="PreviousStateTransitionTime">
      <MemberSignature Language="C#" Value="public Nullable&lt;DateTime&gt; PreviousStateTransitionTime { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; PreviousStateTransitionTime" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.CloudJob.PreviousStateTransitionTime" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property PreviousStateTransitionTime As Nullable(Of DateTime)" />
      <MemberSignature Language="F#" Value="member this.PreviousStateTransitionTime : Nullable&lt;DateTime&gt;" Usage="Microsoft.Azure.Batch.CloudJob.PreviousStateTransitionTime" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.DateTime&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="36eb1-293">Ruft den Zeitpunkt, an dem der Auftrag den vorherigen Zustand angenommen hat.</span><span class="sxs-lookup"><span data-stu-id="36eb1-293">Gets the time at which the job entered its previous state.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="36eb1-294">Wenn der Auftrag befindet sich in die erste <see cref="F:Microsoft.Azure.Batch.Common.JobState.Active" /> Zustand befindet, wird die PreviousStateTransitionTime-Eigenschaft ist nicht definiert.</span><span class="sxs-lookup"><span data-stu-id="36eb1-294">If the job is in its initial <see cref="F:Microsoft.Azure.Batch.Common.JobState.Active" /> state, the PreviousStateTransitionTime property is not defined.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="Priority">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; Priority { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; Priority" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.CloudJob.Priority" />
      <MemberSignature Language="VB.NET" Value="Public Property Priority As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.Priority : Nullable&lt;int&gt; with get, set" Usage="Microsoft.Azure.Batch.CloudJob.Priority" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="36eb1-295">Ruft ab oder legt die Priorität des Auftrags.</span><span class="sxs-lookup"><span data-stu-id="36eb1-295">Gets or sets the priority of the job.</span></span> <span data-ttu-id="36eb1-296">Priority-Werte reichen von-1000 bis 1000,-1000 wird die niedrigste Priorität und 1000 die höchste Priorität.</span><span class="sxs-lookup"><span data-stu-id="36eb1-296">Priority values can range from -1000 to 1000, with -1000 being the lowest priority and 1000 being the highest priority.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="36eb1-297">Der Standardwert ist 0.</span><span class="sxs-lookup"><span data-stu-id="36eb1-297">The default value is 0.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="Refresh">
      <MemberSignature Language="C#" Value="public void Refresh (Microsoft.Azure.Batch.DetailLevel detailLevel = null, System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Refresh(class Microsoft.Azure.Batch.DetailLevel detailLevel, class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.CloudJob.Refresh(Microsoft.Azure.Batch.DetailLevel,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior})" />
      <MemberSignature Language="F#" Value="abstract member Refresh : Microsoft.Azure.Batch.DetailLevel * seq&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; -&gt; unit&#xA;override this.Refresh : Microsoft.Azure.Batch.DetailLevel * seq&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; -&gt; unit" Usage="cloudJob.Refresh (detailLevel, additionalBehaviors)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.Azure.Batch.IRefreshable.Refresh(Microsoft.Azure.Batch.DetailLevel,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior})</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="detailLevel" Type="Microsoft.Azure.Batch.DetailLevel" />
        <Parameter Name="additionalBehaviors" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt;" />
      </Parameters>
      <Docs>
        <param name="detailLevel"><span data-ttu-id="36eb1-298">Die Detailstufe für die Aktualisierung.</span><span class="sxs-lookup"><span data-stu-id="36eb1-298">The detail level for the refresh.</span></span>  <span data-ttu-id="36eb1-299">Wenn einer der weglässt Detailebene der <see cref="P:Microsoft.Azure.Batch.CloudJob.Id" /> -Eigenschaft angegeben ist, scheitert die Aktualisierung.</span><span class="sxs-lookup"><span data-stu-id="36eb1-299">If a detail level which omits the <see cref="P:Microsoft.Azure.Batch.CloudJob.Id" /> property is specified, refresh will fail.</span></span></param>
        <param name="additionalBehaviors"><span data-ttu-id="36eb1-300">Eine Auflistung von <see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" /> Instanzen, die für die Batchanforderung-Dienst nach gelten die <see cref="P:Microsoft.Azure.Batch.CloudJob.CustomBehaviors" />.</span><span class="sxs-lookup"><span data-stu-id="36eb1-300">A collection of <see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" /> instances that are applied to the Batch service request after the <see cref="P:Microsoft.Azure.Batch.CloudJob.CustomBehaviors" />.</span></span></param>
        <summary>
            <span data-ttu-id="36eb1-301">Aktualisiert das aktuelle <see cref="T:Microsoft.Azure.Batch.CloudJob" />.</span><span class="sxs-lookup"><span data-stu-id="36eb1-301">Refreshes the current <see cref="T:Microsoft.Azure.Batch.CloudJob" />.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RefreshAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task RefreshAsync (Microsoft.Azure.Batch.DetailLevel detailLevel = null, System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task RefreshAsync(class Microsoft.Azure.Batch.DetailLevel detailLevel, class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.CloudJob.RefreshAsync(Microsoft.Azure.Batch.DetailLevel,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member RefreshAsync : Microsoft.Azure.Batch.DetailLevel * seq&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&#xA;override this.RefreshAsync : Microsoft.Azure.Batch.DetailLevel * seq&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="cloudJob.RefreshAsync (detailLevel, additionalBehaviors, cancellationToken)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.Azure.Batch.IRefreshable.RefreshAsync(Microsoft.Azure.Batch.DetailLevel,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior},System.Threading.CancellationToken)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Batch.CloudJob/&lt;RefreshAsync&gt;d__19))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="detailLevel" Type="Microsoft.Azure.Batch.DetailLevel" />
        <Parameter Name="additionalBehaviors" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="detailLevel"><span data-ttu-id="36eb1-302">Die Detailstufe für die Aktualisierung.</span><span class="sxs-lookup"><span data-stu-id="36eb1-302">The detail level for the refresh.</span></span>  <span data-ttu-id="36eb1-303">Wenn einer der weglässt Detailebene der <see cref="P:Microsoft.Azure.Batch.CloudJob.Id" /> -Eigenschaft angegeben ist, scheitert die Aktualisierung.</span><span class="sxs-lookup"><span data-stu-id="36eb1-303">If a detail level which omits the <see cref="P:Microsoft.Azure.Batch.CloudJob.Id" /> property is specified, refresh will fail.</span></span></param>
        <param name="additionalBehaviors"><span data-ttu-id="36eb1-304">Eine Auflistung von <see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" /> Instanzen, die für die Batchanforderung-Dienst nach gelten die <see cref="P:Microsoft.Azure.Batch.CloudJob.CustomBehaviors" />.</span><span class="sxs-lookup"><span data-stu-id="36eb1-304">A collection of <see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" /> instances that are applied to the Batch service request after the <see cref="P:Microsoft.Azure.Batch.CloudJob.CustomBehaviors" />.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="36eb1-305">Ein <see cref="T:System.Threading.CancellationToken" /> für die Steuerung der Lebensdauer eines asynchronen Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="36eb1-305">A <see cref="T:System.Threading.CancellationToken" /> for controlling the lifetime of the asynchronous operation.</span></span></param>
        <summary>
            <span data-ttu-id="36eb1-306">Aktualisiert das aktuelle <see cref="T:Microsoft.Azure.Batch.CloudJob" />.</span><span class="sxs-lookup"><span data-stu-id="36eb1-306">Refreshes the current <see cref="T:Microsoft.Azure.Batch.CloudJob" />.</span></span>
            </summary>
        <returns><span data-ttu-id="36eb1-307">Ein <see cref="T:System.Threading.Tasks.Task" /> , das den asynchronen Aktualisierungsvorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="36eb1-307">A <see cref="T:System.Threading.Tasks.Task" /> representing the asynchronous refresh operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="State">
      <MemberSignature Language="C#" Value="public Nullable&lt;Microsoft.Azure.Batch.Common.JobState&gt; State { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Batch.Common.JobState&gt; State" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.CloudJob.State" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property State As Nullable(Of JobState)" />
      <MemberSignature Language="F#" Value="member this.State : Nullable&lt;Microsoft.Azure.Batch.Common.JobState&gt;" Usage="Microsoft.Azure.Batch.CloudJob.State" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;Microsoft.Azure.Batch.Common.JobState&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="36eb1-308">Ruft den aktuellen Status des Auftrags ab.</span><span class="sxs-lookup"><span data-stu-id="36eb1-308">Gets the current state of the job.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="StateTransitionTime">
      <MemberSignature Language="C#" Value="public Nullable&lt;DateTime&gt; StateTransitionTime { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; StateTransitionTime" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.CloudJob.StateTransitionTime" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property StateTransitionTime As Nullable(Of DateTime)" />
      <MemberSignature Language="F#" Value="member this.StateTransitionTime : Nullable&lt;DateTime&gt;" Usage="Microsoft.Azure.Batch.CloudJob.StateTransitionTime" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.DateTime&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="36eb1-309">Ruft den Zeitpunkt, zu dem der Auftrag seinem aktuellen Status erlangt hat.</span><span class="sxs-lookup"><span data-stu-id="36eb1-309">Gets the time at which the job entered its current state.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Statistics">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Batch.JobStatistics Statistics { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Batch.JobStatistics Statistics" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.CloudJob.Statistics" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Statistics As JobStatistics" />
      <MemberSignature Language="F#" Value="member this.Statistics : Microsoft.Azure.Batch.JobStatistics" Usage="Microsoft.Azure.Batch.CloudJob.Statistics" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.JobStatistics</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="36eb1-310">Ruft den ressourcenauslastungsstatistiken für die gesamte Lebensdauer des Auftrags ab.</span><span class="sxs-lookup"><span data-stu-id="36eb1-310">Gets resource usage statistics for the entire lifetime of the job.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="36eb1-311">Diese Eigenschaft wird nur aufgefüllt, wenn die <see cref="T:Microsoft.Azure.Batch.CloudJob" /> abgerufen wurde, mit einem <see cref="P:Microsoft.Azure.Batch.ODATADetailLevel.ExpandClause" /> einschließlich das 'Statistiken für Ressourcenpools'-Attribut; andernfalls ist null.</span><span class="sxs-lookup"><span data-stu-id="36eb1-311">This property is populated only if the <see cref="T:Microsoft.Azure.Batch.CloudJob" /> was retrieved with an <see cref="P:Microsoft.Azure.Batch.ODATADetailLevel.ExpandClause" /> including the 'stats' attribute; otherwise it is null.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="Terminate">
      <MemberSignature Language="C#" Value="public void Terminate (string terminateReason = null, System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance void Terminate(string terminateReason, class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.CloudJob.Terminate(System.String,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior})" />
      <MemberSignature Language="VB.NET" Value="Public Sub Terminate (Optional terminateReason As String = null, Optional additionalBehaviors As IEnumerable(Of BatchClientBehavior) = null)" />
      <MemberSignature Language="F#" Value="member this.Terminate : string * seq&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; -&gt; unit" Usage="cloudJob.Terminate (terminateReason, additionalBehaviors)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="terminateReason" Type="System.String" />
        <Parameter Name="additionalBehaviors" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt;" />
      </Parameters>
      <Docs>
        <param name="terminateReason"><span data-ttu-id="36eb1-312">Der Text, der als des Auftrags angezeigt werden sollen <see cref="P:Microsoft.Azure.Batch.JobExecutionInformation.TerminateReason" />.</span><span class="sxs-lookup"><span data-stu-id="36eb1-312">The text you want to appear as the job's <see cref="P:Microsoft.Azure.Batch.JobExecutionInformation.TerminateReason" />.</span></span></param>
        <param name="additionalBehaviors"><span data-ttu-id="36eb1-313">Eine Auflistung von <see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" /> Instanzen, die für die Batchanforderung-Dienst nach gelten die <see cref="P:Microsoft.Azure.Batch.CloudJob.CustomBehaviors" />.</span><span class="sxs-lookup"><span data-stu-id="36eb1-313">A collection of <see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" /> instances that are applied to the Batch service request after the <see cref="P:Microsoft.Azure.Batch.CloudJob.CustomBehaviors" />.</span></span></param>
        <summary>
            <span data-ttu-id="36eb1-314">Dies beendet <see cref="T:Microsoft.Azure.Batch.CloudJob" />, als abgeschlossen gekennzeichnet.</span><span class="sxs-lookup"><span data-stu-id="36eb1-314">Terminates this <see cref="T:Microsoft.Azure.Batch.CloudJob" />, marking it as completed.</span></span>
            </summary>
        <remarks><span data-ttu-id="36eb1-315">Dies ist ein blockierender Vorgang.</span><span class="sxs-lookup"><span data-stu-id="36eb1-315">This is a blocking operation.</span></span> <span data-ttu-id="36eb1-316">Eine nicht blockierende Entsprechung, finden Sie unter <see cref="M:Microsoft.Azure.Batch.CloudJob.TerminateAsync(System.String,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior},System.Threading.CancellationToken)" />.</span><span class="sxs-lookup"><span data-stu-id="36eb1-316">For a non-blocking equivalent, see <see cref="M:Microsoft.Azure.Batch.CloudJob.TerminateAsync(System.String,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior},System.Threading.CancellationToken)" />.</span></span></remarks>
      </Docs>
    </Member>
    <Member MemberName="TerminateAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task TerminateAsync (string terminateReason = null, System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task TerminateAsync(string terminateReason, class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.CloudJob.TerminateAsync(System.String,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.TerminateAsync : string * seq&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="cloudJob.TerminateAsync (terminateReason, additionalBehaviors, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="terminateReason" Type="System.String" />
        <Parameter Name="additionalBehaviors" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="terminateReason"><span data-ttu-id="36eb1-317">Der Text, der als des Auftrags angezeigt werden sollen <see cref="P:Microsoft.Azure.Batch.JobExecutionInformation.TerminateReason" />.</span><span class="sxs-lookup"><span data-stu-id="36eb1-317">The text you want to appear as the job's <see cref="P:Microsoft.Azure.Batch.JobExecutionInformation.TerminateReason" />.</span></span></param>
        <param name="additionalBehaviors"><span data-ttu-id="36eb1-318">Eine Auflistung von <see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" /> Instanzen, die für die Batchanforderung-Dienst nach gelten die <see cref="P:Microsoft.Azure.Batch.CloudJob.CustomBehaviors" />.</span><span class="sxs-lookup"><span data-stu-id="36eb1-318">A collection of <see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" /> instances that are applied to the Batch service request after the <see cref="P:Microsoft.Azure.Batch.CloudJob.CustomBehaviors" />.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="36eb1-319">Ein <see cref="T:System.Threading.CancellationToken" /> für die Steuerung der Lebensdauer eines asynchronen Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="36eb1-319">A <see cref="T:System.Threading.CancellationToken" /> for controlling the lifetime of the asynchronous operation.</span></span></param>
        <summary>
            <span data-ttu-id="36eb1-320">Dies beendet <see cref="T:Microsoft.Azure.Batch.CloudJob" />, als abgeschlossen gekennzeichnet.</span><span class="sxs-lookup"><span data-stu-id="36eb1-320">Terminates this <see cref="T:Microsoft.Azure.Batch.CloudJob" />, marking it as completed.</span></span>
            </summary>
        <returns><span data-ttu-id="36eb1-321">Ein <see cref="T:System.Threading.Tasks.Task" />-Objekt, das den asynchronen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="36eb1-321">A <see cref="T:System.Threading.Tasks.Task" /> object that represents the asynchronous operation.</span></span></returns>
        <remarks><span data-ttu-id="36eb1-322">Der Vorgang "Beenden" wird asynchron ausgeführt.</span><span class="sxs-lookup"><span data-stu-id="36eb1-322">The terminate operation runs asynchronously.</span></span></remarks>
      </Docs>
    </Member>
    <Member MemberName="Url">
      <MemberSignature Language="C#" Value="public string Url { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Url" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.CloudJob.Url" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Url As String" />
      <MemberSignature Language="F#" Value="member this.Url : string" Usage="Microsoft.Azure.Batch.CloudJob.Url" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="36eb1-323">Ruft die URL des Auftrags ab.</span><span class="sxs-lookup"><span data-stu-id="36eb1-323">Gets the URL of the job.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UsesTaskDependencies">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; UsesTaskDependencies { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; UsesTaskDependencies" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.CloudJob.UsesTaskDependencies" />
      <MemberSignature Language="VB.NET" Value="Public Property UsesTaskDependencies As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.UsesTaskDependencies : Nullable&lt;bool&gt; with get, set" Usage="Microsoft.Azure.Batch.CloudJob.UsesTaskDependencies" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="36eb1-324">Ruft ab oder legt fest, ob die Aufgaben im Auftrag Abhängigkeiten untereinander definieren können.</span><span class="sxs-lookup"><span data-stu-id="36eb1-324">Gets or sets whether tasks in the job can define dependencies on each other.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="36eb1-325">Der Standardwert ist „false“.</span><span class="sxs-lookup"><span data-stu-id="36eb1-325">The default value is false.</span></span>
            </remarks>
      </Docs>
    </Member>
  </Members>
</Type>