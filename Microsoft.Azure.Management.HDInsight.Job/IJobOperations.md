<Type Name="IJobOperations" FullName="Microsoft.Azure.Management.HDInsight.Job.IJobOperations">
  <TypeSignature Language="C#" Value="public interface IJobOperations" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IJobOperations" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.HDInsight.Job.IJobOperations" />
  <TypeSignature Language="VB.NET" Value="Public Interface IJobOperations" />
  <TypeSignature Language="F#" Value="type IJobOperations = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.HDInsight.Job</AssemblyName>
    <AssemblyVersion>2.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="f42d6-101">Vorgänge zum Verwalten von Aufträgen für HDInsight-Cluster.</span><span class="sxs-lookup"><span data-stu-id="f42d6-101">Operations for managing jobs against HDInsight clusters.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="GetJobAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.HDInsight.Job.Models.JobGetResponse&gt; GetJobAsync (string jobId, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.HDInsight.Job.Models.JobGetResponse&gt; GetJobAsync(string jobId, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.HDInsight.Job.IJobOperations.GetJobAsync(System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetJobAsync : string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.HDInsight.Job.Models.JobGetResponse&gt;" Usage="iJobOperations.GetJobAsync (jobId, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.HDInsight.Job</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.HDInsight.Job.Models.JobGetResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="jobId" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="jobId">
            <span data-ttu-id="f42d6-102">Die Id des Auftrags.</span><span class="sxs-lookup"><span data-stu-id="f42d6-102">The id of the job.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="f42d6-103">Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="f42d6-103">Cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="f42d6-104">Ruft die Auftragsdetails aus dem angegebenen HDInsight-Cluster ab.</span><span class="sxs-lookup"><span data-stu-id="f42d6-104">Gets job details from the specified HDInsight cluster.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="f42d6-105">Die Antwort für den Get Job-Vorgang.</span><span class="sxs-lookup"><span data-stu-id="f42d6-105">The Get Job operation response.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetJobErrorLogsAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.IO.Stream&gt; GetJobErrorLogsAsync (string jobId, Microsoft.Azure.Management.HDInsight.Job.Models.IStorageAccess storageAccess, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class System.IO.Stream&gt; GetJobErrorLogsAsync(string jobId, class Microsoft.Azure.Management.HDInsight.Job.Models.IStorageAccess storageAccess, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.HDInsight.Job.IJobOperations.GetJobErrorLogsAsync(System.String,Microsoft.Azure.Management.HDInsight.Job.Models.IStorageAccess,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetJobErrorLogsAsync : string * Microsoft.Azure.Management.HDInsight.Job.Models.IStorageAccess * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.IO.Stream&gt;" Usage="iJobOperations.GetJobErrorLogsAsync (jobId, storageAccess, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.HDInsight.Job</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.IO.Stream&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="jobId" Type="System.String" />
        <Parameter Name="storageAccess" Type="Microsoft.Azure.Management.HDInsight.Job.Models.IStorageAccess" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="jobId">
            <span data-ttu-id="f42d6-106">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="f42d6-106">Required.</span></span> <span data-ttu-id="f42d6-107">Die Id des Auftrags.</span><span class="sxs-lookup"><span data-stu-id="f42d6-107">The id of the job.</span></span>
            </param>
        <param name="storageAccess">
            <span data-ttu-id="f42d6-108">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="f42d6-108">Required.</span></span> <span data-ttu-id="f42d6-109">Das Konto Speicherobjekt des Typs IStorageAccess.</span><span class="sxs-lookup"><span data-stu-id="f42d6-109">The storage account object of type IStorageAccess.</span></span>
            </param>
        <param name="cancellationToken"></param>
        <summary>
            <span data-ttu-id="f42d6-110">Ruft die Fehlerprotokolle aus der Ausführung einer einzelnen JobDetails ab.</span><span class="sxs-lookup"><span data-stu-id="f42d6-110">Gets the error logs from the execution of an individual jobDetails.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="f42d6-111">Die Fehlerprotokolle von einer einzelnen JobDetails von "JobID"-Wert.</span><span class="sxs-lookup"><span data-stu-id="f42d6-111">The error logs of an individual jobDetails by jobId.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetJobOutputAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.IO.Stream&gt; GetJobOutputAsync (string jobId, Microsoft.Azure.Management.HDInsight.Job.Models.IStorageAccess storageAccess, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class System.IO.Stream&gt; GetJobOutputAsync(string jobId, class Microsoft.Azure.Management.HDInsight.Job.Models.IStorageAccess storageAccess, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.HDInsight.Job.IJobOperations.GetJobOutputAsync(System.String,Microsoft.Azure.Management.HDInsight.Job.Models.IStorageAccess,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetJobOutputAsync : string * Microsoft.Azure.Management.HDInsight.Job.Models.IStorageAccess * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.IO.Stream&gt;" Usage="iJobOperations.GetJobOutputAsync (jobId, storageAccess, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.HDInsight.Job</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.IO.Stream&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="jobId" Type="System.String" />
        <Parameter Name="storageAccess" Type="Microsoft.Azure.Management.HDInsight.Job.Models.IStorageAccess" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="jobId">
            <span data-ttu-id="f42d6-112">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="f42d6-112">Required.</span></span> <span data-ttu-id="f42d6-113">Die Id des Auftrags.</span><span class="sxs-lookup"><span data-stu-id="f42d6-113">The id of the job.</span></span>
            </param>
        <param name="storageAccess">
            <span data-ttu-id="f42d6-114">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="f42d6-114">Required.</span></span> <span data-ttu-id="f42d6-115">Das Konto Speicherobjekt des Typs IStorageAccess.</span><span class="sxs-lookup"><span data-stu-id="f42d6-115">The storage account object of type IStorageAccess.</span></span>
            </param>
        <param name="cancellationToken"></param>
        <summary>
            <span data-ttu-id="f42d6-116">Ruft die Ausgabe von der Ausführung einer einzelnen JobDetails ab.</span><span class="sxs-lookup"><span data-stu-id="f42d6-116">Gets the output from the execution of an individual jobDetails.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="f42d6-117">Die Ausgabe eine einzelne JobDetails durch "JobID"-Wert.</span><span class="sxs-lookup"><span data-stu-id="f42d6-117">The output of an individual jobDetails by jobId.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="KillJobAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.HDInsight.Job.Models.JobGetResponse&gt; KillJobAsync (string jobId, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.HDInsight.Job.Models.JobGetResponse&gt; KillJobAsync(string jobId, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.HDInsight.Job.IJobOperations.KillJobAsync(System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member KillJobAsync : string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.HDInsight.Job.Models.JobGetResponse&gt;" Usage="iJobOperations.KillJobAsync (jobId, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.HDInsight.Job</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.HDInsight.Job.Models.JobGetResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="jobId" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="jobId">
            <span data-ttu-id="f42d6-118">Die Id des Auftrags.</span><span class="sxs-lookup"><span data-stu-id="f42d6-118">The id of the job.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="f42d6-119">Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="f42d6-119">Cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="f42d6-120">Initiiert Abbrechen auf aktuell ausgeführten Auftrag in der angegebenen HDInsight-Cluster angegeben.</span><span class="sxs-lookup"><span data-stu-id="f42d6-120">Initiates cancel on given running job in the specified HDInsight cluster.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="f42d6-121">Die Antwort für den Get Job-Vorgang.</span><span class="sxs-lookup"><span data-stu-id="f42d6-121">The Get Job operation response.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListJobsAfterJobIdAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.HDInsight.Job.Models.JobListResponse&gt; ListJobsAfterJobIdAsync (string jobId, int numOfJobs, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.HDInsight.Job.Models.JobListResponse&gt; ListJobsAfterJobIdAsync(string jobId, int32 numOfJobs, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.HDInsight.Job.IJobOperations.ListJobsAfterJobIdAsync(System.String,System.Int32,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListJobsAfterJobIdAsync : string * int * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.HDInsight.Job.Models.JobListResponse&gt;" Usage="iJobOperations.ListJobsAfterJobIdAsync (jobId, numOfJobs, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.HDInsight.Job</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.HDInsight.Job.Models.JobListResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="jobId" Type="System.String" />
        <Parameter Name="numOfJobs" Type="System.Int32" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="jobId">
            <span data-ttu-id="f42d6-122">"JobID"-Wert von wo Aufträge aufgelistet werden.</span><span class="sxs-lookup"><span data-stu-id="f42d6-122">jobId from where to list jobs.</span></span>
            </param>
        <param name="numOfJobs">
            <span data-ttu-id="f42d6-123">Anzahl der Aufträge abgerufen.</span><span class="sxs-lookup"><span data-stu-id="f42d6-123">Number of jobs to fetch.</span></span> <span data-ttu-id="f42d6-124">Verwenden Sie-1. um alle.</span><span class="sxs-lookup"><span data-stu-id="f42d6-124">Use -1 to get all.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="f42d6-125">Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="f42d6-125">Cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="f42d6-126">Ruft NumOfJobs nach der "JobID"-Wert aus dem angegebenen HDInsight-Cluster ab.</span><span class="sxs-lookup"><span data-stu-id="f42d6-126">Gets numOfJobs after jobId from the specified HDInsight cluster.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="f42d6-127">Die Liste Auftrag Operation-Antwort.</span><span class="sxs-lookup"><span data-stu-id="f42d6-127">The List Job operation response.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListJobsAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.HDInsight.Job.Models.JobListResponse&gt; ListJobsAsync (System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.HDInsight.Job.Models.JobListResponse&gt; ListJobsAsync(valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.HDInsight.Job.IJobOperations.ListJobsAsync(System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListJobsAsync : System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.HDInsight.Job.Models.JobListResponse&gt;" Usage="iJobOperations.ListJobsAsync cancellationToken" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.HDInsight.Job</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.HDInsight.Job.Models.JobListResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="cancellationToken">
            <span data-ttu-id="f42d6-128">Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="f42d6-128">Cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="f42d6-129">Ruft die Liste der Aufträge aus den angegebenen HDInsight-Cluster ab.</span><span class="sxs-lookup"><span data-stu-id="f42d6-129">Gets the list of jobs from the specified HDInsight cluster.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="f42d6-130">Die Liste Auftrag Operation-Antwort.</span><span class="sxs-lookup"><span data-stu-id="f42d6-130">The List Job operation response.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SubmitHiveJobAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.HDInsight.Job.Models.JobSubmissionResponse&gt; SubmitHiveJobAsync (Microsoft.Azure.Management.HDInsight.Job.Models.HiveJobSubmissionParameters parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.HDInsight.Job.Models.JobSubmissionResponse&gt; SubmitHiveJobAsync(class Microsoft.Azure.Management.HDInsight.Job.Models.HiveJobSubmissionParameters parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.HDInsight.Job.IJobOperations.SubmitHiveJobAsync(Microsoft.Azure.Management.HDInsight.Job.Models.HiveJobSubmissionParameters)" />
      <MemberSignature Language="VB.NET" Value="Public Function SubmitHiveJobAsync (parameters As HiveJobSubmissionParameters) As Task(Of JobSubmissionResponse)" />
      <MemberSignature Language="F#" Value="abstract member SubmitHiveJobAsync : Microsoft.Azure.Management.HDInsight.Job.Models.HiveJobSubmissionParameters -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.HDInsight.Job.Models.JobSubmissionResponse&gt;" Usage="iJobOperations.SubmitHiveJobAsync parameters" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.HDInsight.Job</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.HDInsight.Job.Models.JobSubmissionResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.HDInsight.Job.Models.HiveJobSubmissionParameters" />
      </Parameters>
      <Docs>
        <param name="parameters">
            <span data-ttu-id="f42d6-131">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="f42d6-131">Required.</span></span> <span data-ttu-id="f42d6-132">Hive Auftragsparameter.</span><span class="sxs-lookup"><span data-stu-id="f42d6-132">Hive job parameters.</span></span>
            </param>
        <summary>
            <span data-ttu-id="f42d6-133">Übermittelt Hive-Auftrag an einen HDInsight-Cluster an.</span><span class="sxs-lookup"><span data-stu-id="f42d6-133">Submits a Hive job to an HDInsight cluster.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="f42d6-134">Die Antwort für den Auftrag erstellen-Vorgang.</span><span class="sxs-lookup"><span data-stu-id="f42d6-134">The Create Job operation response.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SubmitHiveJobAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.HDInsight.Job.Models.JobSubmissionResponse&gt; SubmitHiveJobAsync (Microsoft.Azure.Management.HDInsight.Job.Models.JobSubmissionParameters parameters, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.HDInsight.Job.Models.JobSubmissionResponse&gt; SubmitHiveJobAsync(class Microsoft.Azure.Management.HDInsight.Job.Models.JobSubmissionParameters parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.HDInsight.Job.IJobOperations.SubmitHiveJobAsync(Microsoft.Azure.Management.HDInsight.Job.Models.JobSubmissionParameters,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member SubmitHiveJobAsync : Microsoft.Azure.Management.HDInsight.Job.Models.JobSubmissionParameters * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.HDInsight.Job.Models.JobSubmissionResponse&gt;" Usage="iJobOperations.SubmitHiveJobAsync (parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.HDInsight.Job</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.HDInsight.Job.Models.JobSubmissionResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.HDInsight.Job.Models.JobSubmissionParameters" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="parameters">
            <span data-ttu-id="f42d6-135">Hive Auftragsparameter.</span><span class="sxs-lookup"><span data-stu-id="f42d6-135">Hive job parameters.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="f42d6-136">Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="f42d6-136">Cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="f42d6-137">Übermittelt Hive-Auftrag an einen HDInsight-Cluster an.</span><span class="sxs-lookup"><span data-stu-id="f42d6-137">Submits a Hive job to an HDInsight cluster.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="f42d6-138">Die Antwort für den Auftrag erstellen-Vorgang.</span><span class="sxs-lookup"><span data-stu-id="f42d6-138">The Create Job operation response.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SubmitMapReduceJobAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.HDInsight.Job.Models.JobSubmissionResponse&gt; SubmitMapReduceJobAsync (Microsoft.Azure.Management.HDInsight.Job.Models.MapReduceJobSubmissionParameters parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.HDInsight.Job.Models.JobSubmissionResponse&gt; SubmitMapReduceJobAsync(class Microsoft.Azure.Management.HDInsight.Job.Models.MapReduceJobSubmissionParameters parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.HDInsight.Job.IJobOperations.SubmitMapReduceJobAsync(Microsoft.Azure.Management.HDInsight.Job.Models.MapReduceJobSubmissionParameters)" />
      <MemberSignature Language="VB.NET" Value="Public Function SubmitMapReduceJobAsync (parameters As MapReduceJobSubmissionParameters) As Task(Of JobSubmissionResponse)" />
      <MemberSignature Language="F#" Value="abstract member SubmitMapReduceJobAsync : Microsoft.Azure.Management.HDInsight.Job.Models.MapReduceJobSubmissionParameters -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.HDInsight.Job.Models.JobSubmissionResponse&gt;" Usage="iJobOperations.SubmitMapReduceJobAsync parameters" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.HDInsight.Job</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.HDInsight.Job.Models.JobSubmissionResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.HDInsight.Job.Models.MapReduceJobSubmissionParameters" />
      </Parameters>
      <Docs>
        <param name="parameters">
            <span data-ttu-id="f42d6-139">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="f42d6-139">Required.</span></span> <span data-ttu-id="f42d6-140">MapReduce-Auftrag-Parameter.</span><span class="sxs-lookup"><span data-stu-id="f42d6-140">MapReduce job parameters.</span></span>
            </param>
        <summary>
            <span data-ttu-id="f42d6-141">Übermittelt einen MapReduce-Auftrag mit einer HDInsight-Cluster.</span><span class="sxs-lookup"><span data-stu-id="f42d6-141">Submits a MapReduce job to an HDInsight cluster.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="f42d6-142">Die Antwort für den Auftrag erstellen-Vorgang.</span><span class="sxs-lookup"><span data-stu-id="f42d6-142">The Create Job operation response.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SubmitMapReduceJobAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.HDInsight.Job.Models.JobSubmissionResponse&gt; SubmitMapReduceJobAsync (Microsoft.Azure.Management.HDInsight.Job.Models.JobSubmissionParameters parameters, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.HDInsight.Job.Models.JobSubmissionResponse&gt; SubmitMapReduceJobAsync(class Microsoft.Azure.Management.HDInsight.Job.Models.JobSubmissionParameters parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.HDInsight.Job.IJobOperations.SubmitMapReduceJobAsync(Microsoft.Azure.Management.HDInsight.Job.Models.JobSubmissionParameters,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member SubmitMapReduceJobAsync : Microsoft.Azure.Management.HDInsight.Job.Models.JobSubmissionParameters * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.HDInsight.Job.Models.JobSubmissionResponse&gt;" Usage="iJobOperations.SubmitMapReduceJobAsync (parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.HDInsight.Job</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.HDInsight.Job.Models.JobSubmissionResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.HDInsight.Job.Models.JobSubmissionParameters" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="parameters">
            <span data-ttu-id="f42d6-143">MapReduce-Auftrag-Parameter.</span><span class="sxs-lookup"><span data-stu-id="f42d6-143">MapReduce job parameters.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="f42d6-144">Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="f42d6-144">Cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="f42d6-145">Übermittelt einen MapReduce-Auftrag mit einer HDInsight-Cluster.</span><span class="sxs-lookup"><span data-stu-id="f42d6-145">Submits a MapReduce job to an HDInsight cluster.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="f42d6-146">Die Antwort für den Auftrag erstellen-Vorgang.</span><span class="sxs-lookup"><span data-stu-id="f42d6-146">The Create Job operation response.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SubmitMapReduceStreamingJobAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.HDInsight.Job.Models.JobSubmissionResponse&gt; SubmitMapReduceStreamingJobAsync (Microsoft.Azure.Management.HDInsight.Job.Models.MapReduceStreamingJobSubmissionParameters parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.HDInsight.Job.Models.JobSubmissionResponse&gt; SubmitMapReduceStreamingJobAsync(class Microsoft.Azure.Management.HDInsight.Job.Models.MapReduceStreamingJobSubmissionParameters parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.HDInsight.Job.IJobOperations.SubmitMapReduceStreamingJobAsync(Microsoft.Azure.Management.HDInsight.Job.Models.MapReduceStreamingJobSubmissionParameters)" />
      <MemberSignature Language="VB.NET" Value="Public Function SubmitMapReduceStreamingJobAsync (parameters As MapReduceStreamingJobSubmissionParameters) As Task(Of JobSubmissionResponse)" />
      <MemberSignature Language="F#" Value="abstract member SubmitMapReduceStreamingJobAsync : Microsoft.Azure.Management.HDInsight.Job.Models.MapReduceStreamingJobSubmissionParameters -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.HDInsight.Job.Models.JobSubmissionResponse&gt;" Usage="iJobOperations.SubmitMapReduceStreamingJobAsync parameters" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.HDInsight.Job</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.HDInsight.Job.Models.JobSubmissionResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.HDInsight.Job.Models.MapReduceStreamingJobSubmissionParameters" />
      </Parameters>
      <Docs>
        <param name="parameters">
            <span data-ttu-id="f42d6-147">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="f42d6-147">Required.</span></span> <span data-ttu-id="f42d6-148">MapReduce-Auftrag-Parameter.</span><span class="sxs-lookup"><span data-stu-id="f42d6-148">MapReduce job parameters.</span></span>
            </param>
        <summary>
            <span data-ttu-id="f42d6-149">Übermittelt ein MapReduce-streamingauftrag mit einer HDInsight-Cluster an.</span><span class="sxs-lookup"><span data-stu-id="f42d6-149">Submits a MapReduce streaming job to an HDInsight cluster.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="f42d6-150">Die Antwort für den Auftrag erstellen-Vorgang.</span><span class="sxs-lookup"><span data-stu-id="f42d6-150">The Create Job operation response.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SubmitMapReduceStreamingJobAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.HDInsight.Job.Models.JobSubmissionResponse&gt; SubmitMapReduceStreamingJobAsync (Microsoft.Azure.Management.HDInsight.Job.Models.JobSubmissionParameters parameters, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.HDInsight.Job.Models.JobSubmissionResponse&gt; SubmitMapReduceStreamingJobAsync(class Microsoft.Azure.Management.HDInsight.Job.Models.JobSubmissionParameters parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.HDInsight.Job.IJobOperations.SubmitMapReduceStreamingJobAsync(Microsoft.Azure.Management.HDInsight.Job.Models.JobSubmissionParameters,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member SubmitMapReduceStreamingJobAsync : Microsoft.Azure.Management.HDInsight.Job.Models.JobSubmissionParameters * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.HDInsight.Job.Models.JobSubmissionResponse&gt;" Usage="iJobOperations.SubmitMapReduceStreamingJobAsync (parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.HDInsight.Job</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.HDInsight.Job.Models.JobSubmissionResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.HDInsight.Job.Models.JobSubmissionParameters" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="parameters">
            <span data-ttu-id="f42d6-151">MapReduce-Auftrag-Parameter.</span><span class="sxs-lookup"><span data-stu-id="f42d6-151">MapReduce job parameters.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="f42d6-152">Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="f42d6-152">Cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="f42d6-153">Übermittelt ein MapReduce-streamingauftrag mit einer HDInsight-Cluster an.</span><span class="sxs-lookup"><span data-stu-id="f42d6-153">Submits a MapReduce streaming job to an HDInsight cluster.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="f42d6-154">Die Antwort für den Auftrag erstellen-Vorgang.</span><span class="sxs-lookup"><span data-stu-id="f42d6-154">The Create Job operation response.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SubmitPigJobAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.HDInsight.Job.Models.JobSubmissionResponse&gt; SubmitPigJobAsync (Microsoft.Azure.Management.HDInsight.Job.Models.PigJobSubmissionParameters parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.HDInsight.Job.Models.JobSubmissionResponse&gt; SubmitPigJobAsync(class Microsoft.Azure.Management.HDInsight.Job.Models.PigJobSubmissionParameters parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.HDInsight.Job.IJobOperations.SubmitPigJobAsync(Microsoft.Azure.Management.HDInsight.Job.Models.PigJobSubmissionParameters)" />
      <MemberSignature Language="VB.NET" Value="Public Function SubmitPigJobAsync (parameters As PigJobSubmissionParameters) As Task(Of JobSubmissionResponse)" />
      <MemberSignature Language="F#" Value="abstract member SubmitPigJobAsync : Microsoft.Azure.Management.HDInsight.Job.Models.PigJobSubmissionParameters -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.HDInsight.Job.Models.JobSubmissionResponse&gt;" Usage="iJobOperations.SubmitPigJobAsync parameters" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.HDInsight.Job</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.HDInsight.Job.Models.JobSubmissionResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.HDInsight.Job.Models.PigJobSubmissionParameters" />
      </Parameters>
      <Docs>
        <param name="parameters">
            <span data-ttu-id="f42d6-155">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="f42d6-155">Required.</span></span> <span data-ttu-id="f42d6-156">Pig-Auftrag-Parameter.</span><span class="sxs-lookup"><span data-stu-id="f42d6-156">Pig job parameters.</span></span>
            </param>
        <summary>
            <span data-ttu-id="f42d6-157">Sendet einen Pig-Auftrag an einen HDInsight-Cluster an.</span><span class="sxs-lookup"><span data-stu-id="f42d6-157">Submits a Pig job to an HDInsight cluster.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="f42d6-158">Die Antwort für den Auftrag erstellen-Vorgang.</span><span class="sxs-lookup"><span data-stu-id="f42d6-158">The Create Job operation response.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SubmitPigJobAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.HDInsight.Job.Models.JobSubmissionResponse&gt; SubmitPigJobAsync (Microsoft.Azure.Management.HDInsight.Job.Models.JobSubmissionParameters parameters, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.HDInsight.Job.Models.JobSubmissionResponse&gt; SubmitPigJobAsync(class Microsoft.Azure.Management.HDInsight.Job.Models.JobSubmissionParameters parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.HDInsight.Job.IJobOperations.SubmitPigJobAsync(Microsoft.Azure.Management.HDInsight.Job.Models.JobSubmissionParameters,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member SubmitPigJobAsync : Microsoft.Azure.Management.HDInsight.Job.Models.JobSubmissionParameters * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.HDInsight.Job.Models.JobSubmissionResponse&gt;" Usage="iJobOperations.SubmitPigJobAsync (parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.HDInsight.Job</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.HDInsight.Job.Models.JobSubmissionResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.HDInsight.Job.Models.JobSubmissionParameters" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="parameters">
            <span data-ttu-id="f42d6-159">Pig-Auftrag-Parameter.</span><span class="sxs-lookup"><span data-stu-id="f42d6-159">Pig job parameters.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="f42d6-160">Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="f42d6-160">Cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="f42d6-161">Sendet einen Pig-Auftrag an einen HDInsight-Cluster an.</span><span class="sxs-lookup"><span data-stu-id="f42d6-161">Submits a Pig job to an HDInsight cluster.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="f42d6-162">Die Antwort für den Auftrag erstellen-Vorgang.</span><span class="sxs-lookup"><span data-stu-id="f42d6-162">The Create Job operation response.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SubmitSqoopJobAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.HDInsight.Job.Models.JobSubmissionResponse&gt; SubmitSqoopJobAsync (Microsoft.Azure.Management.HDInsight.Job.Models.SqoopJobSubmissionParameters parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.HDInsight.Job.Models.JobSubmissionResponse&gt; SubmitSqoopJobAsync(class Microsoft.Azure.Management.HDInsight.Job.Models.SqoopJobSubmissionParameters parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.HDInsight.Job.IJobOperations.SubmitSqoopJobAsync(Microsoft.Azure.Management.HDInsight.Job.Models.SqoopJobSubmissionParameters)" />
      <MemberSignature Language="VB.NET" Value="Public Function SubmitSqoopJobAsync (parameters As SqoopJobSubmissionParameters) As Task(Of JobSubmissionResponse)" />
      <MemberSignature Language="F#" Value="abstract member SubmitSqoopJobAsync : Microsoft.Azure.Management.HDInsight.Job.Models.SqoopJobSubmissionParameters -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.HDInsight.Job.Models.JobSubmissionResponse&gt;" Usage="iJobOperations.SubmitSqoopJobAsync parameters" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.HDInsight.Job</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.HDInsight.Job.Models.JobSubmissionResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.HDInsight.Job.Models.SqoopJobSubmissionParameters" />
      </Parameters>
      <Docs>
        <param name="parameters">
            <span data-ttu-id="f42d6-163">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="f42d6-163">Required.</span></span> <span data-ttu-id="f42d6-164">Sqoop-Auftrag-Parameter.</span><span class="sxs-lookup"><span data-stu-id="f42d6-164">Sqoop job parameters.</span></span>
            </param>
        <summary>
            <span data-ttu-id="f42d6-165">Übermittelt einen Sqoop-Auftrag um einen HDInsight-Cluster.</span><span class="sxs-lookup"><span data-stu-id="f42d6-165">Submits a Sqoop job to an HDInsight cluster.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="f42d6-166">Die Antwort für den Auftrag erstellen-Vorgang.</span><span class="sxs-lookup"><span data-stu-id="f42d6-166">The Create Job operation response.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SubmitSqoopJobAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.HDInsight.Job.Models.JobSubmissionResponse&gt; SubmitSqoopJobAsync (Microsoft.Azure.Management.HDInsight.Job.Models.JobSubmissionParameters parameters, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.HDInsight.Job.Models.JobSubmissionResponse&gt; SubmitSqoopJobAsync(class Microsoft.Azure.Management.HDInsight.Job.Models.JobSubmissionParameters parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.HDInsight.Job.IJobOperations.SubmitSqoopJobAsync(Microsoft.Azure.Management.HDInsight.Job.Models.JobSubmissionParameters,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member SubmitSqoopJobAsync : Microsoft.Azure.Management.HDInsight.Job.Models.JobSubmissionParameters * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.HDInsight.Job.Models.JobSubmissionResponse&gt;" Usage="iJobOperations.SubmitSqoopJobAsync (parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.HDInsight.Job</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.HDInsight.Job.Models.JobSubmissionResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.HDInsight.Job.Models.JobSubmissionParameters" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="parameters">
            <span data-ttu-id="f42d6-167">Sqoop-Auftrag-Parameter.</span><span class="sxs-lookup"><span data-stu-id="f42d6-167">Sqoop job parameters.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="f42d6-168">Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="f42d6-168">Cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="f42d6-169">Übermittelt einen Sqoop-Auftrag um einen HDInsight-Cluster.</span><span class="sxs-lookup"><span data-stu-id="f42d6-169">Submits a Sqoop job to an HDInsight cluster.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="f42d6-170">Die Antwort für den Auftrag erstellen-Vorgang.</span><span class="sxs-lookup"><span data-stu-id="f42d6-170">The Create Job operation response.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="WaitForJobCompletionAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.HDInsight.Job.Models.JobGetResponse&gt; WaitForJobCompletionAsync (string jobId, Nullable&lt;TimeSpan&gt; duration, Nullable&lt;TimeSpan&gt; waitInterval);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.HDInsight.Job.Models.JobGetResponse&gt; WaitForJobCompletionAsync(string jobId, valuetype System.Nullable`1&lt;valuetype System.TimeSpan&gt; duration, valuetype System.Nullable`1&lt;valuetype System.TimeSpan&gt; waitInterval) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.HDInsight.Job.IJobOperations.WaitForJobCompletionAsync(System.String,System.Nullable{System.TimeSpan},System.Nullable{System.TimeSpan})" />
      <MemberSignature Language="VB.NET" Value="Public Function WaitForJobCompletionAsync (jobId As String, duration As Nullable(Of TimeSpan), waitInterval As Nullable(Of TimeSpan)) As Task(Of JobGetResponse)" />
      <MemberSignature Language="F#" Value="abstract member WaitForJobCompletionAsync : string * Nullable&lt;TimeSpan&gt; * Nullable&lt;TimeSpan&gt; -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.HDInsight.Job.Models.JobGetResponse&gt;" Usage="iJobOperations.WaitForJobCompletionAsync (jobId, duration, waitInterval)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.HDInsight.Job</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.HDInsight.Job.Models.JobGetResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="jobId" Type="System.String" />
        <Parameter Name="duration" Type="System.Nullable&lt;System.TimeSpan&gt;" />
        <Parameter Name="waitInterval" Type="System.Nullable&lt;System.TimeSpan&gt;" />
      </Parameters>
      <Docs>
        <param name="jobId">
            <span data-ttu-id="f42d6-171">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="f42d6-171">Required.</span></span> <span data-ttu-id="f42d6-172">Die Id des Auftrags.</span><span class="sxs-lookup"><span data-stu-id="f42d6-172">The id of the job.</span></span>
            </param>
        <param name="duration">
            <span data-ttu-id="f42d6-173">Optional.</span><span class="sxs-lookup"><span data-stu-id="f42d6-173">Optional.</span></span> <span data-ttu-id="f42d6-174">Die maximale Zeitspanne zum Abschluss des Auftrags vor der Rückgabe an den Client gewartet werden soll.</span><span class="sxs-lookup"><span data-stu-id="f42d6-174">The maximum duration to wait for completion of job before returning to client.</span></span> <span data-ttu-id="f42d6-175">Wenn Sie nicht warten Sie dann zu übergeben, bis der Auftrag abgeschlossen ist.</span><span class="sxs-lookup"><span data-stu-id="f42d6-175">If not passed then wait till job is completed.</span></span>
            </param>
        <param name="waitInterval">
            <span data-ttu-id="f42d6-176">Optional.</span><span class="sxs-lookup"><span data-stu-id="f42d6-176">Optional.</span></span> <span data-ttu-id="f42d6-177">Das Intervall, Auftragsstatus abzurufen.</span><span class="sxs-lookup"><span data-stu-id="f42d6-177">The interval to poll for job status.</span></span> <span data-ttu-id="f42d6-178">Der Standardwert wird aus der HDInsight-Auftrags Verwaltungsclient DefaultPollInterval-Eigenschaft festgelegt.</span><span class="sxs-lookup"><span data-stu-id="f42d6-178">The default value is set from DefaultPollInterval property of HDInsight job management client.</span></span>
            </param>
        <summary>
            <span data-ttu-id="f42d6-179">Warten Sie auf den Abschluss eines Auftrags.</span><span class="sxs-lookup"><span data-stu-id="f42d6-179">Wait for completion of a Job.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.TimeoutException">
            <span data-ttu-id="f42d6-180">Wird ausgelöst, wenn warten auf die Beendigung des Auftrags die maximale Dauer, angegeben durch Parameter Dauer überschreitet.</span><span class="sxs-lookup"><span data-stu-id="f42d6-180">Thrown when waiting for job completion exceeds the maximum duration specified by parameter duration.</span></span>
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>