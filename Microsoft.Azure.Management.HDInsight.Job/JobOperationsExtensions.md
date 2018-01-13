<Type Name="JobOperationsExtensions" FullName="Microsoft.Azure.Management.HDInsight.Job.JobOperationsExtensions">
  <TypeSignature Language="C#" Value="public static class JobOperationsExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit JobOperationsExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.HDInsight.Job.JobOperationsExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module JobOperationsExtensions" />
  <TypeSignature Language="F#" Value="type JobOperationsExtensions = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.HDInsight.Job</AssemblyName>
    <AssemblyVersion>2.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="06f9a-101">Vorgänge zum Verwalten von Aufträgen für HDInsight-Cluster.</span><span class="sxs-lookup"><span data-stu-id="06f9a-101">Operations for managing jobs against HDInsight clusters.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="GetJob">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.HDInsight.Job.Models.JobGetResponse GetJob (this Microsoft.Azure.Management.HDInsight.Job.IJobOperations operations, string jobId);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.HDInsight.Job.Models.JobGetResponse GetJob(class Microsoft.Azure.Management.HDInsight.Job.IJobOperations operations, string jobId) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.HDInsight.Job.JobOperationsExtensions.GetJob(Microsoft.Azure.Management.HDInsight.Job.IJobOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function GetJob (operations As IJobOperations, jobId As String) As JobGetResponse" />
      <MemberSignature Language="F#" Value="static member GetJob : Microsoft.Azure.Management.HDInsight.Job.IJobOperations * string -&gt; Microsoft.Azure.Management.HDInsight.Job.Models.JobGetResponse" Usage="Microsoft.Azure.Management.HDInsight.Job.JobOperationsExtensions.GetJob (operations, jobId)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.HDInsight.Job</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.HDInsight.Job.Models.JobGetResponse</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.HDInsight.Job.IJobOperations" RefType="this" />
        <Parameter Name="jobId" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="06f9a-102">Verweis auf die Microsoft.Azure.Management.HDInsight.Job.IJobOperations.</span><span class="sxs-lookup"><span data-stu-id="06f9a-102">Reference to the Microsoft.Azure.Management.HDInsight.Job.IJobOperations.</span></span>
            </param>
        <param name="jobId">
            <span data-ttu-id="06f9a-103">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="06f9a-103">Required.</span></span> <span data-ttu-id="06f9a-104">Die Id des Auftrags.</span><span class="sxs-lookup"><span data-stu-id="06f9a-104">The id of the job.</span></span>
            </param>
        <summary>
            <span data-ttu-id="06f9a-105">Ruft die Auftragsdetails aus dem angegebenen HDInsight-Cluster ab.</span><span class="sxs-lookup"><span data-stu-id="06f9a-105">Gets job details from the specified HDInsight cluster.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="06f9a-106">Die Antwort für den Get Job-Vorgang.</span><span class="sxs-lookup"><span data-stu-id="06f9a-106">The Get Job operation response.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetJobAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.HDInsight.Job.Models.JobGetResponse&gt; GetJobAsync (this Microsoft.Azure.Management.HDInsight.Job.IJobOperations operations, string jobId);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.HDInsight.Job.Models.JobGetResponse&gt; GetJobAsync(class Microsoft.Azure.Management.HDInsight.Job.IJobOperations operations, string jobId) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.HDInsight.Job.JobOperationsExtensions.GetJobAsync(Microsoft.Azure.Management.HDInsight.Job.IJobOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function GetJobAsync (operations As IJobOperations, jobId As String) As Task(Of JobGetResponse)" />
      <MemberSignature Language="F#" Value="static member GetJobAsync : Microsoft.Azure.Management.HDInsight.Job.IJobOperations * string -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.HDInsight.Job.Models.JobGetResponse&gt;" Usage="Microsoft.Azure.Management.HDInsight.Job.JobOperationsExtensions.GetJobAsync (operations, jobId)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.HDInsight.Job</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.HDInsight.Job.Models.JobGetResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.HDInsight.Job.IJobOperations" RefType="this" />
        <Parameter Name="jobId" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="06f9a-107">Verweis auf die Microsoft.Azure.Management.HDInsight.Job.IJobOperations.</span><span class="sxs-lookup"><span data-stu-id="06f9a-107">Reference to the Microsoft.Azure.Management.HDInsight.Job.IJobOperations.</span></span>
            </param>
        <param name="jobId">
            <span data-ttu-id="06f9a-108">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="06f9a-108">Required.</span></span> <span data-ttu-id="06f9a-109">Die Id des Auftrags.</span><span class="sxs-lookup"><span data-stu-id="06f9a-109">The id of the job.</span></span>
            </param>
        <summary>
            <span data-ttu-id="06f9a-110">Ruft die Auftragsdetails aus dem angegebenen HDInsight-Cluster ab.</span><span class="sxs-lookup"><span data-stu-id="06f9a-110">Gets job details from the specified HDInsight cluster.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="06f9a-111">Die Antwort für den Get Job-Vorgang.</span><span class="sxs-lookup"><span data-stu-id="06f9a-111">The Get Job operation response.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetJobErrorLogs">
      <MemberSignature Language="C#" Value="public static System.IO.Stream GetJobErrorLogs (this Microsoft.Azure.Management.HDInsight.Job.IJobOperations operations, string jobId, Microsoft.Azure.Management.HDInsight.Job.Models.IStorageAccess storageAccess);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.IO.Stream GetJobErrorLogs(class Microsoft.Azure.Management.HDInsight.Job.IJobOperations operations, string jobId, class Microsoft.Azure.Management.HDInsight.Job.Models.IStorageAccess storageAccess) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.HDInsight.Job.JobOperationsExtensions.GetJobErrorLogs(Microsoft.Azure.Management.HDInsight.Job.IJobOperations,System.String,Microsoft.Azure.Management.HDInsight.Job.Models.IStorageAccess)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function GetJobErrorLogs (operations As IJobOperations, jobId As String, storageAccess As IStorageAccess) As Stream" />
      <MemberSignature Language="F#" Value="static member GetJobErrorLogs : Microsoft.Azure.Management.HDInsight.Job.IJobOperations * string * Microsoft.Azure.Management.HDInsight.Job.Models.IStorageAccess -&gt; System.IO.Stream" Usage="Microsoft.Azure.Management.HDInsight.Job.JobOperationsExtensions.GetJobErrorLogs (operations, jobId, storageAccess)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.HDInsight.Job</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.IO.Stream</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.HDInsight.Job.IJobOperations" RefType="this" />
        <Parameter Name="jobId" Type="System.String" />
        <Parameter Name="storageAccess" Type="Microsoft.Azure.Management.HDInsight.Job.Models.IStorageAccess" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="06f9a-112">Verweis auf die Microsoft.Azure.Management.HDInsight.Job.IJobOperations.</span><span class="sxs-lookup"><span data-stu-id="06f9a-112">Reference to the Microsoft.Azure.Management.HDInsight.Job.IJobOperations.</span></span>
            </param>
        <param name="jobId">
            <span data-ttu-id="06f9a-113">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="06f9a-113">Required.</span></span> <span data-ttu-id="06f9a-114">Die Id des Auftrags.</span><span class="sxs-lookup"><span data-stu-id="06f9a-114">The id of the job.</span></span>
            </param>
        <param name="storageAccess">
            <span data-ttu-id="06f9a-115">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="06f9a-115">Required.</span></span> <span data-ttu-id="06f9a-116">Das Konto Speicherobjekt des Typs IStorageAccess.</span><span class="sxs-lookup"><span data-stu-id="06f9a-116">The storage account object of type IStorageAccess.</span></span>
            </param>
        <summary>
            <span data-ttu-id="06f9a-117">Ruft die Fehlerprotokolle aus der Ausführung einer einzelnen JobDetails ab.</span><span class="sxs-lookup"><span data-stu-id="06f9a-117">Gets the error logs from the execution of an individual jobDetails.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="06f9a-118">Die Fehlerprotokolle von einer einzelnen JobDetails von "JobID"-Wert.</span><span class="sxs-lookup"><span data-stu-id="06f9a-118">The error logs of an individual jobDetails by jobId.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetJobErrorLogsAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;System.IO.Stream&gt; GetJobErrorLogsAsync (this Microsoft.Azure.Management.HDInsight.Job.IJobOperations operations, string jobId, Microsoft.Azure.Management.HDInsight.Job.Models.IStorageAccess storageAccess);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class System.IO.Stream&gt; GetJobErrorLogsAsync(class Microsoft.Azure.Management.HDInsight.Job.IJobOperations operations, string jobId, class Microsoft.Azure.Management.HDInsight.Job.Models.IStorageAccess storageAccess) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.HDInsight.Job.JobOperationsExtensions.GetJobErrorLogsAsync(Microsoft.Azure.Management.HDInsight.Job.IJobOperations,System.String,Microsoft.Azure.Management.HDInsight.Job.Models.IStorageAccess)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function GetJobErrorLogsAsync (operations As IJobOperations, jobId As String, storageAccess As IStorageAccess) As Task(Of Stream)" />
      <MemberSignature Language="F#" Value="static member GetJobErrorLogsAsync : Microsoft.Azure.Management.HDInsight.Job.IJobOperations * string * Microsoft.Azure.Management.HDInsight.Job.Models.IStorageAccess -&gt; System.Threading.Tasks.Task&lt;System.IO.Stream&gt;" Usage="Microsoft.Azure.Management.HDInsight.Job.JobOperationsExtensions.GetJobErrorLogsAsync (operations, jobId, storageAccess)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.HDInsight.Job</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.IO.Stream&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.HDInsight.Job.IJobOperations" RefType="this" />
        <Parameter Name="jobId" Type="System.String" />
        <Parameter Name="storageAccess" Type="Microsoft.Azure.Management.HDInsight.Job.Models.IStorageAccess" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="06f9a-119">Verweis auf die Microsoft.Azure.Management.HDInsight.Job.IJobOperations.</span><span class="sxs-lookup"><span data-stu-id="06f9a-119">Reference to the Microsoft.Azure.Management.HDInsight.Job.IJobOperations.</span></span>
            </param>
        <param name="jobId">
            <span data-ttu-id="06f9a-120">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="06f9a-120">Required.</span></span> <span data-ttu-id="06f9a-121">Die Id des Auftrags.</span><span class="sxs-lookup"><span data-stu-id="06f9a-121">The id of the job.</span></span>
            </param>
        <param name="storageAccess">
            <span data-ttu-id="06f9a-122">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="06f9a-122">Required.</span></span> <span data-ttu-id="06f9a-123">Das Konto Speicherobjekt des Typs IStorageAccess.</span><span class="sxs-lookup"><span data-stu-id="06f9a-123">The storage account object of type IStorageAccess.</span></span>
            </param>
        <summary>
            <span data-ttu-id="06f9a-124">Ruft die Fehlerprotokolle aus der Ausführung einer einzelnen JobDetails ab.</span><span class="sxs-lookup"><span data-stu-id="06f9a-124">Gets the error logs from the execution of an individual jobDetails.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="06f9a-125">Die Fehlerprotokolle von einer einzelnen JobDetails von "JobID"-Wert.</span><span class="sxs-lookup"><span data-stu-id="06f9a-125">The error logs of an individual jobDetails by jobId.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetJobOutput">
      <MemberSignature Language="C#" Value="public static System.IO.Stream GetJobOutput (this Microsoft.Azure.Management.HDInsight.Job.IJobOperations operations, string jobId, Microsoft.Azure.Management.HDInsight.Job.Models.IStorageAccess storageAccess);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.IO.Stream GetJobOutput(class Microsoft.Azure.Management.HDInsight.Job.IJobOperations operations, string jobId, class Microsoft.Azure.Management.HDInsight.Job.Models.IStorageAccess storageAccess) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.HDInsight.Job.JobOperationsExtensions.GetJobOutput(Microsoft.Azure.Management.HDInsight.Job.IJobOperations,System.String,Microsoft.Azure.Management.HDInsight.Job.Models.IStorageAccess)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function GetJobOutput (operations As IJobOperations, jobId As String, storageAccess As IStorageAccess) As Stream" />
      <MemberSignature Language="F#" Value="static member GetJobOutput : Microsoft.Azure.Management.HDInsight.Job.IJobOperations * string * Microsoft.Azure.Management.HDInsight.Job.Models.IStorageAccess -&gt; System.IO.Stream" Usage="Microsoft.Azure.Management.HDInsight.Job.JobOperationsExtensions.GetJobOutput (operations, jobId, storageAccess)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.HDInsight.Job</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.IO.Stream</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.HDInsight.Job.IJobOperations" RefType="this" />
        <Parameter Name="jobId" Type="System.String" />
        <Parameter Name="storageAccess" Type="Microsoft.Azure.Management.HDInsight.Job.Models.IStorageAccess" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="06f9a-126">Verweis auf die Microsoft.Azure.Management.HDInsight.Job.IJobOperations.</span><span class="sxs-lookup"><span data-stu-id="06f9a-126">Reference to the Microsoft.Azure.Management.HDInsight.Job.IJobOperations.</span></span>
            </param>
        <param name="jobId">
            <span data-ttu-id="06f9a-127">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="06f9a-127">Required.</span></span> <span data-ttu-id="06f9a-128">Die Id des Auftrags.</span><span class="sxs-lookup"><span data-stu-id="06f9a-128">The id of the job.</span></span>
            </param>
        <param name="storageAccess">
            <span data-ttu-id="06f9a-129">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="06f9a-129">Required.</span></span> <span data-ttu-id="06f9a-130">Das Konto Speicherobjekt des Typs IStorageAccess.</span><span class="sxs-lookup"><span data-stu-id="06f9a-130">The storage account object of type IStorageAccess.</span></span>
            </param>
        <summary>
            <span data-ttu-id="06f9a-131">Ruft die Ausgabe von der Ausführung einer einzelnen JobDetails ab.</span><span class="sxs-lookup"><span data-stu-id="06f9a-131">Gets the output from the execution of an individual jobDetails.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="06f9a-132">Die Ausgabe eine einzelne JobDetails durch "JobID"-Wert.</span><span class="sxs-lookup"><span data-stu-id="06f9a-132">The output of an individual jobDetails by jobId.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetJobOutputAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;System.IO.Stream&gt; GetJobOutputAsync (this Microsoft.Azure.Management.HDInsight.Job.IJobOperations operations, string jobId, Microsoft.Azure.Management.HDInsight.Job.Models.IStorageAccess storageAccess);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class System.IO.Stream&gt; GetJobOutputAsync(class Microsoft.Azure.Management.HDInsight.Job.IJobOperations operations, string jobId, class Microsoft.Azure.Management.HDInsight.Job.Models.IStorageAccess storageAccess) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.HDInsight.Job.JobOperationsExtensions.GetJobOutputAsync(Microsoft.Azure.Management.HDInsight.Job.IJobOperations,System.String,Microsoft.Azure.Management.HDInsight.Job.Models.IStorageAccess)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function GetJobOutputAsync (operations As IJobOperations, jobId As String, storageAccess As IStorageAccess) As Task(Of Stream)" />
      <MemberSignature Language="F#" Value="static member GetJobOutputAsync : Microsoft.Azure.Management.HDInsight.Job.IJobOperations * string * Microsoft.Azure.Management.HDInsight.Job.Models.IStorageAccess -&gt; System.Threading.Tasks.Task&lt;System.IO.Stream&gt;" Usage="Microsoft.Azure.Management.HDInsight.Job.JobOperationsExtensions.GetJobOutputAsync (operations, jobId, storageAccess)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.HDInsight.Job</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.IO.Stream&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.HDInsight.Job.IJobOperations" RefType="this" />
        <Parameter Name="jobId" Type="System.String" />
        <Parameter Name="storageAccess" Type="Microsoft.Azure.Management.HDInsight.Job.Models.IStorageAccess" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="06f9a-133">Verweis auf die Microsoft.Azure.Management.HDInsight.Job.IJobOperations.</span><span class="sxs-lookup"><span data-stu-id="06f9a-133">Reference to the Microsoft.Azure.Management.HDInsight.Job.IJobOperations.</span></span>
            </param>
        <param name="jobId">
            <span data-ttu-id="06f9a-134">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="06f9a-134">Required.</span></span> <span data-ttu-id="06f9a-135">Die Id des Auftrags.</span><span class="sxs-lookup"><span data-stu-id="06f9a-135">The id of the job.</span></span>
            </param>
        <param name="storageAccess">
            <span data-ttu-id="06f9a-136">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="06f9a-136">Required.</span></span> <span data-ttu-id="06f9a-137">Das Konto Speicherobjekt des Typs IStorageAccess.</span><span class="sxs-lookup"><span data-stu-id="06f9a-137">The storage account object of type IStorageAccess.</span></span>
            </param>
        <summary>
            <span data-ttu-id="06f9a-138">Ruft die Ausgabe von der Ausführung einer einzelnen JobDetails ab.</span><span class="sxs-lookup"><span data-stu-id="06f9a-138">Gets the output from the execution of an individual jobDetails.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="06f9a-139">Die Ausgabe eine einzelne JobDetails durch "JobID"-Wert.</span><span class="sxs-lookup"><span data-stu-id="06f9a-139">The output of an individual jobDetails by jobId.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="KillJob">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.HDInsight.Job.Models.JobGetResponse KillJob (this Microsoft.Azure.Management.HDInsight.Job.IJobOperations operations, string jobId);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.HDInsight.Job.Models.JobGetResponse KillJob(class Microsoft.Azure.Management.HDInsight.Job.IJobOperations operations, string jobId) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.HDInsight.Job.JobOperationsExtensions.KillJob(Microsoft.Azure.Management.HDInsight.Job.IJobOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function KillJob (operations As IJobOperations, jobId As String) As JobGetResponse" />
      <MemberSignature Language="F#" Value="static member KillJob : Microsoft.Azure.Management.HDInsight.Job.IJobOperations * string -&gt; Microsoft.Azure.Management.HDInsight.Job.Models.JobGetResponse" Usage="Microsoft.Azure.Management.HDInsight.Job.JobOperationsExtensions.KillJob (operations, jobId)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.HDInsight.Job</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.HDInsight.Job.Models.JobGetResponse</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.HDInsight.Job.IJobOperations" RefType="this" />
        <Parameter Name="jobId" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="06f9a-140">Verweis auf die Microsoft.Azure.Management.HDInsight.Job.IJobOperations.</span><span class="sxs-lookup"><span data-stu-id="06f9a-140">Reference to the Microsoft.Azure.Management.HDInsight.Job.IJobOperations.</span></span>
            </param>
        <param name="jobId">
            <span data-ttu-id="06f9a-141">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="06f9a-141">Required.</span></span> <span data-ttu-id="06f9a-142">Die Id des Auftrags.</span><span class="sxs-lookup"><span data-stu-id="06f9a-142">The id of the job.</span></span>
            </param>
        <summary>
            <span data-ttu-id="06f9a-143">Initiiert Abbrechen auf aktuell ausgeführten Auftrag in der angegebenen HDInsight-Cluster angegeben.</span><span class="sxs-lookup"><span data-stu-id="06f9a-143">Initiates cancel on given running job in the specified HDInsight cluster.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="06f9a-144">Die Antwort für den Get Job-Vorgang.</span><span class="sxs-lookup"><span data-stu-id="06f9a-144">The Get Job operation response.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="KillJobAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.HDInsight.Job.Models.JobGetResponse&gt; KillJobAsync (this Microsoft.Azure.Management.HDInsight.Job.IJobOperations operations, string jobId);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.HDInsight.Job.Models.JobGetResponse&gt; KillJobAsync(class Microsoft.Azure.Management.HDInsight.Job.IJobOperations operations, string jobId) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.HDInsight.Job.JobOperationsExtensions.KillJobAsync(Microsoft.Azure.Management.HDInsight.Job.IJobOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function KillJobAsync (operations As IJobOperations, jobId As String) As Task(Of JobGetResponse)" />
      <MemberSignature Language="F#" Value="static member KillJobAsync : Microsoft.Azure.Management.HDInsight.Job.IJobOperations * string -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.HDInsight.Job.Models.JobGetResponse&gt;" Usage="Microsoft.Azure.Management.HDInsight.Job.JobOperationsExtensions.KillJobAsync (operations, jobId)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.HDInsight.Job</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.HDInsight.Job.Models.JobGetResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.HDInsight.Job.IJobOperations" RefType="this" />
        <Parameter Name="jobId" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="06f9a-145">Verweis auf die Microsoft.Azure.Management.HDInsight.Job.IJobOperations.</span><span class="sxs-lookup"><span data-stu-id="06f9a-145">Reference to the Microsoft.Azure.Management.HDInsight.Job.IJobOperations.</span></span>
            </param>
        <param name="jobId">
            <span data-ttu-id="06f9a-146">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="06f9a-146">Required.</span></span> <span data-ttu-id="06f9a-147">Die Id des Auftrags.</span><span class="sxs-lookup"><span data-stu-id="06f9a-147">The id of the job.</span></span>
            </param>
        <summary>
            <span data-ttu-id="06f9a-148">Initiiert Abbrechen auf aktuell ausgeführten Auftrag in der angegebenen HDInsight-Cluster angegeben.</span><span class="sxs-lookup"><span data-stu-id="06f9a-148">Initiates cancel on given running job in the specified HDInsight cluster.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="06f9a-149">Die Antwort für den Get Job-Vorgang.</span><span class="sxs-lookup"><span data-stu-id="06f9a-149">The Get Job operation response.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListJobs">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.HDInsight.Job.Models.JobListResponse ListJobs (this Microsoft.Azure.Management.HDInsight.Job.IJobOperations operations);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.HDInsight.Job.Models.JobListResponse ListJobs(class Microsoft.Azure.Management.HDInsight.Job.IJobOperations operations) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.HDInsight.Job.JobOperationsExtensions.ListJobs(Microsoft.Azure.Management.HDInsight.Job.IJobOperations)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListJobs (operations As IJobOperations) As JobListResponse" />
      <MemberSignature Language="F#" Value="static member ListJobs : Microsoft.Azure.Management.HDInsight.Job.IJobOperations -&gt; Microsoft.Azure.Management.HDInsight.Job.Models.JobListResponse" Usage="Microsoft.Azure.Management.HDInsight.Job.JobOperationsExtensions.ListJobs operations" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.HDInsight.Job</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.HDInsight.Job.Models.JobListResponse</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.HDInsight.Job.IJobOperations" RefType="this" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="06f9a-150">Verweis auf die Microsoft.Azure.Management.HDInsight.Job.IJobOperations.</span><span class="sxs-lookup"><span data-stu-id="06f9a-150">Reference to the Microsoft.Azure.Management.HDInsight.Job.IJobOperations.</span></span>
            </param>
        <summary>
            <span data-ttu-id="06f9a-151">Ruft die Liste der Aufträge aus den angegebenen HDInsight-Cluster ab.</span><span class="sxs-lookup"><span data-stu-id="06f9a-151">Gets the list of jobs from the specified HDInsight cluster.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="06f9a-152">Die Liste Auftrag Operation-Antwort.</span><span class="sxs-lookup"><span data-stu-id="06f9a-152">The List Job operation response.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListJobsAfterJobId">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.HDInsight.Job.Models.JobListResponse ListJobsAfterJobId (this Microsoft.Azure.Management.HDInsight.Job.IJobOperations operations, string jobId, int numOfJobs);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.HDInsight.Job.Models.JobListResponse ListJobsAfterJobId(class Microsoft.Azure.Management.HDInsight.Job.IJobOperations operations, string jobId, int32 numOfJobs) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.HDInsight.Job.JobOperationsExtensions.ListJobsAfterJobId(Microsoft.Azure.Management.HDInsight.Job.IJobOperations,System.String,System.Int32)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListJobsAfterJobId (operations As IJobOperations, jobId As String, numOfJobs As Integer) As JobListResponse" />
      <MemberSignature Language="F#" Value="static member ListJobsAfterJobId : Microsoft.Azure.Management.HDInsight.Job.IJobOperations * string * int -&gt; Microsoft.Azure.Management.HDInsight.Job.Models.JobListResponse" Usage="Microsoft.Azure.Management.HDInsight.Job.JobOperationsExtensions.ListJobsAfterJobId (operations, jobId, numOfJobs)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.HDInsight.Job</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.HDInsight.Job.Models.JobListResponse</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.HDInsight.Job.IJobOperations" RefType="this" />
        <Parameter Name="jobId" Type="System.String" />
        <Parameter Name="numOfJobs" Type="System.Int32" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="06f9a-153">Verweis auf die Microsoft.Azure.Management.HDInsight.Job.IJobOperations.</span><span class="sxs-lookup"><span data-stu-id="06f9a-153">Reference to the Microsoft.Azure.Management.HDInsight.Job.IJobOperations.</span></span>
            </param>
        <param name="jobId">
            <span data-ttu-id="06f9a-154">Optional.</span><span class="sxs-lookup"><span data-stu-id="06f9a-154">Optional.</span></span> <span data-ttu-id="06f9a-155">"JobID"-Wert von wo Aufträge aufgelistet werden.</span><span class="sxs-lookup"><span data-stu-id="06f9a-155">jobId from where to list jobs.</span></span>
            </param>
        <param name="numOfJobs">
            <span data-ttu-id="06f9a-156">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="06f9a-156">Required.</span></span> <span data-ttu-id="06f9a-157">Anzahl der Aufträge abgerufen.</span><span class="sxs-lookup"><span data-stu-id="06f9a-157">Number of jobs to fetch.</span></span> <span data-ttu-id="06f9a-158">Verwenden Sie-1. um alle.</span><span class="sxs-lookup"><span data-stu-id="06f9a-158">Use -1 to get all.</span></span>
            </param>
        <summary>
            <span data-ttu-id="06f9a-159">Ruft NumOfJobs nach der "JobID"-Wert aus dem angegebenen HDInsight-Cluster ab.</span><span class="sxs-lookup"><span data-stu-id="06f9a-159">Gets numOfJobs after jobId from the specified HDInsight cluster.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="06f9a-160">Die Liste Auftrag Operation-Antwort.</span><span class="sxs-lookup"><span data-stu-id="06f9a-160">The List Job operation response.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListJobsAfterJobIdAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.HDInsight.Job.Models.JobListResponse&gt; ListJobsAfterJobIdAsync (this Microsoft.Azure.Management.HDInsight.Job.IJobOperations operations, string jobId, int numOfJobs);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.HDInsight.Job.Models.JobListResponse&gt; ListJobsAfterJobIdAsync(class Microsoft.Azure.Management.HDInsight.Job.IJobOperations operations, string jobId, int32 numOfJobs) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.HDInsight.Job.JobOperationsExtensions.ListJobsAfterJobIdAsync(Microsoft.Azure.Management.HDInsight.Job.IJobOperations,System.String,System.Int32)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListJobsAfterJobIdAsync (operations As IJobOperations, jobId As String, numOfJobs As Integer) As Task(Of JobListResponse)" />
      <MemberSignature Language="F#" Value="static member ListJobsAfterJobIdAsync : Microsoft.Azure.Management.HDInsight.Job.IJobOperations * string * int -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.HDInsight.Job.Models.JobListResponse&gt;" Usage="Microsoft.Azure.Management.HDInsight.Job.JobOperationsExtensions.ListJobsAfterJobIdAsync (operations, jobId, numOfJobs)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.HDInsight.Job</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.HDInsight.Job.Models.JobListResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.HDInsight.Job.IJobOperations" RefType="this" />
        <Parameter Name="jobId" Type="System.String" />
        <Parameter Name="numOfJobs" Type="System.Int32" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="06f9a-161">Verweis auf die Microsoft.Azure.Management.HDInsight.Job.IJobOperations.</span><span class="sxs-lookup"><span data-stu-id="06f9a-161">Reference to the Microsoft.Azure.Management.HDInsight.Job.IJobOperations.</span></span>
            </param>
        <param name="jobId">
            <span data-ttu-id="06f9a-162">Optional.</span><span class="sxs-lookup"><span data-stu-id="06f9a-162">Optional.</span></span> <span data-ttu-id="06f9a-163">"JobID"-Wert von wo Aufträge aufgelistet werden.</span><span class="sxs-lookup"><span data-stu-id="06f9a-163">jobId from where to list jobs.</span></span>
            </param>
        <param name="numOfJobs">
            <span data-ttu-id="06f9a-164">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="06f9a-164">Required.</span></span> <span data-ttu-id="06f9a-165">Anzahl der Aufträge abgerufen.</span><span class="sxs-lookup"><span data-stu-id="06f9a-165">Number of jobs to fetch.</span></span> <span data-ttu-id="06f9a-166">Verwenden Sie-1. um alle.</span><span class="sxs-lookup"><span data-stu-id="06f9a-166">Use -1 to get all.</span></span>
            </param>
        <summary>
            <span data-ttu-id="06f9a-167">Ruft NumOfJobs nach der "JobID"-Wert aus dem angegebenen HDInsight-Cluster ab.</span><span class="sxs-lookup"><span data-stu-id="06f9a-167">Gets numOfJobs after jobId from the specified HDInsight cluster.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="06f9a-168">Die Liste Auftrag Operation-Antwort.</span><span class="sxs-lookup"><span data-stu-id="06f9a-168">The List Job operation response.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListJobsAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.HDInsight.Job.Models.JobListResponse&gt; ListJobsAsync (this Microsoft.Azure.Management.HDInsight.Job.IJobOperations operations);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.HDInsight.Job.Models.JobListResponse&gt; ListJobsAsync(class Microsoft.Azure.Management.HDInsight.Job.IJobOperations operations) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.HDInsight.Job.JobOperationsExtensions.ListJobsAsync(Microsoft.Azure.Management.HDInsight.Job.IJobOperations)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListJobsAsync (operations As IJobOperations) As Task(Of JobListResponse)" />
      <MemberSignature Language="F#" Value="static member ListJobsAsync : Microsoft.Azure.Management.HDInsight.Job.IJobOperations -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.HDInsight.Job.Models.JobListResponse&gt;" Usage="Microsoft.Azure.Management.HDInsight.Job.JobOperationsExtensions.ListJobsAsync operations" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.HDInsight.Job</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.HDInsight.Job.Models.JobListResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.HDInsight.Job.IJobOperations" RefType="this" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="06f9a-169">Verweis auf die Microsoft.Azure.Management.HDInsight.Job.IJobOperations.</span><span class="sxs-lookup"><span data-stu-id="06f9a-169">Reference to the Microsoft.Azure.Management.HDInsight.Job.IJobOperations.</span></span>
            </param>
        <summary>
            <span data-ttu-id="06f9a-170">Ruft die Liste der Aufträge aus den angegebenen HDInsight-Cluster ab.</span><span class="sxs-lookup"><span data-stu-id="06f9a-170">Gets the list of jobs from the specified HDInsight cluster.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="06f9a-171">Die Liste Auftrag Operation-Antwort.</span><span class="sxs-lookup"><span data-stu-id="06f9a-171">The List Job operation response.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SubmitHiveJob">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.HDInsight.Job.Models.JobSubmissionResponse SubmitHiveJob (this Microsoft.Azure.Management.HDInsight.Job.IJobOperations operations, Microsoft.Azure.Management.HDInsight.Job.Models.HiveJobSubmissionParameters parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.HDInsight.Job.Models.JobSubmissionResponse SubmitHiveJob(class Microsoft.Azure.Management.HDInsight.Job.IJobOperations operations, class Microsoft.Azure.Management.HDInsight.Job.Models.HiveJobSubmissionParameters parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.HDInsight.Job.JobOperationsExtensions.SubmitHiveJob(Microsoft.Azure.Management.HDInsight.Job.IJobOperations,Microsoft.Azure.Management.HDInsight.Job.Models.HiveJobSubmissionParameters)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function SubmitHiveJob (operations As IJobOperations, parameters As HiveJobSubmissionParameters) As JobSubmissionResponse" />
      <MemberSignature Language="F#" Value="static member SubmitHiveJob : Microsoft.Azure.Management.HDInsight.Job.IJobOperations * Microsoft.Azure.Management.HDInsight.Job.Models.HiveJobSubmissionParameters -&gt; Microsoft.Azure.Management.HDInsight.Job.Models.JobSubmissionResponse" Usage="Microsoft.Azure.Management.HDInsight.Job.JobOperationsExtensions.SubmitHiveJob (operations, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.HDInsight.Job</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.HDInsight.Job.Models.JobSubmissionResponse</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.HDInsight.Job.IJobOperations" RefType="this" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.HDInsight.Job.Models.HiveJobSubmissionParameters" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="06f9a-172">Verweis auf die Microsoft.Azure.Management.HDInsight.Job.IJobOperations.</span><span class="sxs-lookup"><span data-stu-id="06f9a-172">Reference to the Microsoft.Azure.Management.HDInsight.Job.IJobOperations.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="06f9a-173">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="06f9a-173">Required.</span></span> <span data-ttu-id="06f9a-174">Hive Auftragsparameter.</span><span class="sxs-lookup"><span data-stu-id="06f9a-174">Hive job parameters.</span></span>
            </param>
        <summary>
            <span data-ttu-id="06f9a-175">Übermittelt Hive-Auftrag an einen HDInsight-Cluster an.</span><span class="sxs-lookup"><span data-stu-id="06f9a-175">Submits a Hive job to an HDInsight cluster.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="06f9a-176">Die Antwort für den Auftrag erstellen-Vorgang.</span><span class="sxs-lookup"><span data-stu-id="06f9a-176">The Create Job operation response.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SubmitHiveJob">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.HDInsight.Job.Models.JobSubmissionResponse SubmitHiveJob (this Microsoft.Azure.Management.HDInsight.Job.IJobOperations operations, Microsoft.Azure.Management.HDInsight.Job.Models.JobSubmissionParameters parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.HDInsight.Job.Models.JobSubmissionResponse SubmitHiveJob(class Microsoft.Azure.Management.HDInsight.Job.IJobOperations operations, class Microsoft.Azure.Management.HDInsight.Job.Models.JobSubmissionParameters parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.HDInsight.Job.JobOperationsExtensions.SubmitHiveJob(Microsoft.Azure.Management.HDInsight.Job.IJobOperations,Microsoft.Azure.Management.HDInsight.Job.Models.JobSubmissionParameters)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function SubmitHiveJob (operations As IJobOperations, parameters As JobSubmissionParameters) As JobSubmissionResponse" />
      <MemberSignature Language="F#" Value="static member SubmitHiveJob : Microsoft.Azure.Management.HDInsight.Job.IJobOperations * Microsoft.Azure.Management.HDInsight.Job.Models.JobSubmissionParameters -&gt; Microsoft.Azure.Management.HDInsight.Job.Models.JobSubmissionResponse" Usage="Microsoft.Azure.Management.HDInsight.Job.JobOperationsExtensions.SubmitHiveJob (operations, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.HDInsight.Job</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.HDInsight.Job.Models.JobSubmissionResponse</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.HDInsight.Job.IJobOperations" RefType="this" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.HDInsight.Job.Models.JobSubmissionParameters" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="06f9a-177">Verweis auf die Microsoft.Azure.Management.HDInsight.Job.IJobOperations.</span><span class="sxs-lookup"><span data-stu-id="06f9a-177">Reference to the Microsoft.Azure.Management.HDInsight.Job.IJobOperations.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="06f9a-178">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="06f9a-178">Required.</span></span> <span data-ttu-id="06f9a-179">Hive Auftragsparameter.</span><span class="sxs-lookup"><span data-stu-id="06f9a-179">Hive job parameters.</span></span>
            </param>
        <summary>
            <span data-ttu-id="06f9a-180">Übermittelt Hive-Auftrag an einen HDInsight-Cluster an.</span><span class="sxs-lookup"><span data-stu-id="06f9a-180">Submits a Hive job to an HDInsight cluster.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="06f9a-181">Die Antwort für den Auftrag erstellen-Vorgang.</span><span class="sxs-lookup"><span data-stu-id="06f9a-181">The Create Job operation response.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SubmitHiveJobAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.HDInsight.Job.Models.JobSubmissionResponse&gt; SubmitHiveJobAsync (this Microsoft.Azure.Management.HDInsight.Job.IJobOperations operations, Microsoft.Azure.Management.HDInsight.Job.Models.HiveJobSubmissionParameters parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.HDInsight.Job.Models.JobSubmissionResponse&gt; SubmitHiveJobAsync(class Microsoft.Azure.Management.HDInsight.Job.IJobOperations operations, class Microsoft.Azure.Management.HDInsight.Job.Models.HiveJobSubmissionParameters parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.HDInsight.Job.JobOperationsExtensions.SubmitHiveJobAsync(Microsoft.Azure.Management.HDInsight.Job.IJobOperations,Microsoft.Azure.Management.HDInsight.Job.Models.HiveJobSubmissionParameters)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function SubmitHiveJobAsync (operations As IJobOperations, parameters As HiveJobSubmissionParameters) As Task(Of JobSubmissionResponse)" />
      <MemberSignature Language="F#" Value="static member SubmitHiveJobAsync : Microsoft.Azure.Management.HDInsight.Job.IJobOperations * Microsoft.Azure.Management.HDInsight.Job.Models.HiveJobSubmissionParameters -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.HDInsight.Job.Models.JobSubmissionResponse&gt;" Usage="Microsoft.Azure.Management.HDInsight.Job.JobOperationsExtensions.SubmitHiveJobAsync (operations, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.HDInsight.Job</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.HDInsight.Job.Models.JobSubmissionResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.HDInsight.Job.IJobOperations" RefType="this" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.HDInsight.Job.Models.HiveJobSubmissionParameters" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="06f9a-182">Verweis auf die Microsoft.Azure.Management.HDInsight.Job.IJobOperations.</span><span class="sxs-lookup"><span data-stu-id="06f9a-182">Reference to the Microsoft.Azure.Management.HDInsight.Job.IJobOperations.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="06f9a-183">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="06f9a-183">Required.</span></span> <span data-ttu-id="06f9a-184">Hive Auftragsparameter.</span><span class="sxs-lookup"><span data-stu-id="06f9a-184">Hive job parameters.</span></span>
            </param>
        <summary>
            <span data-ttu-id="06f9a-185">Übermittelt Hive-Auftrag an einen HDInsight-Cluster an.</span><span class="sxs-lookup"><span data-stu-id="06f9a-185">Submits a Hive job to an HDInsight cluster.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="06f9a-186">Die Antwort für den Auftrag erstellen-Vorgang.</span><span class="sxs-lookup"><span data-stu-id="06f9a-186">The Create Job operation response.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SubmitHiveJobAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.HDInsight.Job.Models.JobSubmissionResponse&gt; SubmitHiveJobAsync (this Microsoft.Azure.Management.HDInsight.Job.IJobOperations operations, Microsoft.Azure.Management.HDInsight.Job.Models.JobSubmissionParameters parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.HDInsight.Job.Models.JobSubmissionResponse&gt; SubmitHiveJobAsync(class Microsoft.Azure.Management.HDInsight.Job.IJobOperations operations, class Microsoft.Azure.Management.HDInsight.Job.Models.JobSubmissionParameters parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.HDInsight.Job.JobOperationsExtensions.SubmitHiveJobAsync(Microsoft.Azure.Management.HDInsight.Job.IJobOperations,Microsoft.Azure.Management.HDInsight.Job.Models.JobSubmissionParameters)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function SubmitHiveJobAsync (operations As IJobOperations, parameters As JobSubmissionParameters) As Task(Of JobSubmissionResponse)" />
      <MemberSignature Language="F#" Value="static member SubmitHiveJobAsync : Microsoft.Azure.Management.HDInsight.Job.IJobOperations * Microsoft.Azure.Management.HDInsight.Job.Models.JobSubmissionParameters -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.HDInsight.Job.Models.JobSubmissionResponse&gt;" Usage="Microsoft.Azure.Management.HDInsight.Job.JobOperationsExtensions.SubmitHiveJobAsync (operations, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.HDInsight.Job</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.HDInsight.Job.Models.JobSubmissionResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.HDInsight.Job.IJobOperations" RefType="this" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.HDInsight.Job.Models.JobSubmissionParameters" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="06f9a-187">Verweis auf die Microsoft.Azure.Management.HDInsight.Job.IJobOperations.</span><span class="sxs-lookup"><span data-stu-id="06f9a-187">Reference to the Microsoft.Azure.Management.HDInsight.Job.IJobOperations.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="06f9a-188">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="06f9a-188">Required.</span></span> <span data-ttu-id="06f9a-189">Hive Auftragsparameter.</span><span class="sxs-lookup"><span data-stu-id="06f9a-189">Hive job parameters.</span></span>
            </param>
        <summary>
            <span data-ttu-id="06f9a-190">Übermittelt Hive-Auftrag an einen HDInsight-Cluster an.</span><span class="sxs-lookup"><span data-stu-id="06f9a-190">Submits a Hive job to an HDInsight cluster.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="06f9a-191">Die Antwort für den Auftrag erstellen-Vorgang.</span><span class="sxs-lookup"><span data-stu-id="06f9a-191">The Create Job operation response.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SubmitMapReduceJob">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.HDInsight.Job.Models.JobSubmissionResponse SubmitMapReduceJob (this Microsoft.Azure.Management.HDInsight.Job.IJobOperations operations, Microsoft.Azure.Management.HDInsight.Job.Models.JobSubmissionParameters parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.HDInsight.Job.Models.JobSubmissionResponse SubmitMapReduceJob(class Microsoft.Azure.Management.HDInsight.Job.IJobOperations operations, class Microsoft.Azure.Management.HDInsight.Job.Models.JobSubmissionParameters parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.HDInsight.Job.JobOperationsExtensions.SubmitMapReduceJob(Microsoft.Azure.Management.HDInsight.Job.IJobOperations,Microsoft.Azure.Management.HDInsight.Job.Models.JobSubmissionParameters)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function SubmitMapReduceJob (operations As IJobOperations, parameters As JobSubmissionParameters) As JobSubmissionResponse" />
      <MemberSignature Language="F#" Value="static member SubmitMapReduceJob : Microsoft.Azure.Management.HDInsight.Job.IJobOperations * Microsoft.Azure.Management.HDInsight.Job.Models.JobSubmissionParameters -&gt; Microsoft.Azure.Management.HDInsight.Job.Models.JobSubmissionResponse" Usage="Microsoft.Azure.Management.HDInsight.Job.JobOperationsExtensions.SubmitMapReduceJob (operations, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.HDInsight.Job</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.HDInsight.Job.Models.JobSubmissionResponse</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.HDInsight.Job.IJobOperations" RefType="this" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.HDInsight.Job.Models.JobSubmissionParameters" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="06f9a-192">Verweis auf die Microsoft.Azure.Management.HDInsight.Job.IJobOperations.</span><span class="sxs-lookup"><span data-stu-id="06f9a-192">Reference to the Microsoft.Azure.Management.HDInsight.Job.IJobOperations.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="06f9a-193">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="06f9a-193">Required.</span></span> <span data-ttu-id="06f9a-194">MapReduce-Auftrag-Parameter.</span><span class="sxs-lookup"><span data-stu-id="06f9a-194">MapReduce job parameters.</span></span>
            </param>
        <summary>
            <span data-ttu-id="06f9a-195">Übermittelt einen MapReduce-Auftrag mit einer HDInsight-Cluster.</span><span class="sxs-lookup"><span data-stu-id="06f9a-195">Submits a MapReduce job to an HDInsight cluster.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="06f9a-196">Die Antwort für den Auftrag erstellen-Vorgang.</span><span class="sxs-lookup"><span data-stu-id="06f9a-196">The Create Job operation response.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SubmitMapReduceJob">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.HDInsight.Job.Models.JobSubmissionResponse SubmitMapReduceJob (this Microsoft.Azure.Management.HDInsight.Job.IJobOperations operations, Microsoft.Azure.Management.HDInsight.Job.Models.MapReduceJobSubmissionParameters parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.HDInsight.Job.Models.JobSubmissionResponse SubmitMapReduceJob(class Microsoft.Azure.Management.HDInsight.Job.IJobOperations operations, class Microsoft.Azure.Management.HDInsight.Job.Models.MapReduceJobSubmissionParameters parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.HDInsight.Job.JobOperationsExtensions.SubmitMapReduceJob(Microsoft.Azure.Management.HDInsight.Job.IJobOperations,Microsoft.Azure.Management.HDInsight.Job.Models.MapReduceJobSubmissionParameters)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function SubmitMapReduceJob (operations As IJobOperations, parameters As MapReduceJobSubmissionParameters) As JobSubmissionResponse" />
      <MemberSignature Language="F#" Value="static member SubmitMapReduceJob : Microsoft.Azure.Management.HDInsight.Job.IJobOperations * Microsoft.Azure.Management.HDInsight.Job.Models.MapReduceJobSubmissionParameters -&gt; Microsoft.Azure.Management.HDInsight.Job.Models.JobSubmissionResponse" Usage="Microsoft.Azure.Management.HDInsight.Job.JobOperationsExtensions.SubmitMapReduceJob (operations, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.HDInsight.Job</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.HDInsight.Job.Models.JobSubmissionResponse</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.HDInsight.Job.IJobOperations" RefType="this" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.HDInsight.Job.Models.MapReduceJobSubmissionParameters" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="06f9a-197">Verweis auf die Microsoft.Azure.Management.HDInsight.Job.IJobOperations.</span><span class="sxs-lookup"><span data-stu-id="06f9a-197">Reference to the Microsoft.Azure.Management.HDInsight.Job.IJobOperations.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="06f9a-198">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="06f9a-198">Required.</span></span> <span data-ttu-id="06f9a-199">MapReduce-Auftrag-Parameter.</span><span class="sxs-lookup"><span data-stu-id="06f9a-199">MapReduce job parameters.</span></span>
            </param>
        <summary>
            <span data-ttu-id="06f9a-200">Übermittelt einen MapReduce-Auftrag mit einer HDInsight-Cluster.</span><span class="sxs-lookup"><span data-stu-id="06f9a-200">Submits a MapReduce job to an HDInsight cluster.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="06f9a-201">Die Antwort für den Auftrag erstellen-Vorgang.</span><span class="sxs-lookup"><span data-stu-id="06f9a-201">The Create Job operation response.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SubmitMapReduceJobAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.HDInsight.Job.Models.JobSubmissionResponse&gt; SubmitMapReduceJobAsync (this Microsoft.Azure.Management.HDInsight.Job.IJobOperations operations, Microsoft.Azure.Management.HDInsight.Job.Models.JobSubmissionParameters parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.HDInsight.Job.Models.JobSubmissionResponse&gt; SubmitMapReduceJobAsync(class Microsoft.Azure.Management.HDInsight.Job.IJobOperations operations, class Microsoft.Azure.Management.HDInsight.Job.Models.JobSubmissionParameters parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.HDInsight.Job.JobOperationsExtensions.SubmitMapReduceJobAsync(Microsoft.Azure.Management.HDInsight.Job.IJobOperations,Microsoft.Azure.Management.HDInsight.Job.Models.JobSubmissionParameters)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function SubmitMapReduceJobAsync (operations As IJobOperations, parameters As JobSubmissionParameters) As Task(Of JobSubmissionResponse)" />
      <MemberSignature Language="F#" Value="static member SubmitMapReduceJobAsync : Microsoft.Azure.Management.HDInsight.Job.IJobOperations * Microsoft.Azure.Management.HDInsight.Job.Models.JobSubmissionParameters -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.HDInsight.Job.Models.JobSubmissionResponse&gt;" Usage="Microsoft.Azure.Management.HDInsight.Job.JobOperationsExtensions.SubmitMapReduceJobAsync (operations, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.HDInsight.Job</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.HDInsight.Job.Models.JobSubmissionResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.HDInsight.Job.IJobOperations" RefType="this" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.HDInsight.Job.Models.JobSubmissionParameters" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="06f9a-202">Verweis auf die Microsoft.Azure.Management.HDInsight.Job.IJobOperations.</span><span class="sxs-lookup"><span data-stu-id="06f9a-202">Reference to the Microsoft.Azure.Management.HDInsight.Job.IJobOperations.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="06f9a-203">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="06f9a-203">Required.</span></span> <span data-ttu-id="06f9a-204">MapReduce-Auftrag-Parameter.</span><span class="sxs-lookup"><span data-stu-id="06f9a-204">MapReduce job parameters.</span></span>
            </param>
        <summary>
            <span data-ttu-id="06f9a-205">Übermittelt einen MapReduce-Auftrag mit einer HDInsight-Cluster.</span><span class="sxs-lookup"><span data-stu-id="06f9a-205">Submits a MapReduce job to an HDInsight cluster.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="06f9a-206">Die Antwort für den Auftrag erstellen-Vorgang.</span><span class="sxs-lookup"><span data-stu-id="06f9a-206">The Create Job operation response.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SubmitMapReduceJobAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.HDInsight.Job.Models.JobSubmissionResponse&gt; SubmitMapReduceJobAsync (this Microsoft.Azure.Management.HDInsight.Job.IJobOperations operations, Microsoft.Azure.Management.HDInsight.Job.Models.MapReduceJobSubmissionParameters parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.HDInsight.Job.Models.JobSubmissionResponse&gt; SubmitMapReduceJobAsync(class Microsoft.Azure.Management.HDInsight.Job.IJobOperations operations, class Microsoft.Azure.Management.HDInsight.Job.Models.MapReduceJobSubmissionParameters parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.HDInsight.Job.JobOperationsExtensions.SubmitMapReduceJobAsync(Microsoft.Azure.Management.HDInsight.Job.IJobOperations,Microsoft.Azure.Management.HDInsight.Job.Models.MapReduceJobSubmissionParameters)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function SubmitMapReduceJobAsync (operations As IJobOperations, parameters As MapReduceJobSubmissionParameters) As Task(Of JobSubmissionResponse)" />
      <MemberSignature Language="F#" Value="static member SubmitMapReduceJobAsync : Microsoft.Azure.Management.HDInsight.Job.IJobOperations * Microsoft.Azure.Management.HDInsight.Job.Models.MapReduceJobSubmissionParameters -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.HDInsight.Job.Models.JobSubmissionResponse&gt;" Usage="Microsoft.Azure.Management.HDInsight.Job.JobOperationsExtensions.SubmitMapReduceJobAsync (operations, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.HDInsight.Job</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.HDInsight.Job.Models.JobSubmissionResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.HDInsight.Job.IJobOperations" RefType="this" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.HDInsight.Job.Models.MapReduceJobSubmissionParameters" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="06f9a-207">Verweis auf die Microsoft.Azure.Management.HDInsight.Job.IJobOperations.</span><span class="sxs-lookup"><span data-stu-id="06f9a-207">Reference to the Microsoft.Azure.Management.HDInsight.Job.IJobOperations.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="06f9a-208">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="06f9a-208">Required.</span></span> <span data-ttu-id="06f9a-209">MapReduce-Auftrag-Parameter.</span><span class="sxs-lookup"><span data-stu-id="06f9a-209">MapReduce job parameters.</span></span>
            </param>
        <summary>
            <span data-ttu-id="06f9a-210">Übermittelt einen MapReduce-Auftrag mit einer HDInsight-Cluster.</span><span class="sxs-lookup"><span data-stu-id="06f9a-210">Submits a MapReduce job to an HDInsight cluster.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="06f9a-211">Die Antwort für den Auftrag erstellen-Vorgang.</span><span class="sxs-lookup"><span data-stu-id="06f9a-211">The Create Job operation response.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SubmitMapReduceStreamingJob">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.HDInsight.Job.Models.JobSubmissionResponse SubmitMapReduceStreamingJob (this Microsoft.Azure.Management.HDInsight.Job.IJobOperations operations, Microsoft.Azure.Management.HDInsight.Job.Models.JobSubmissionParameters parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.HDInsight.Job.Models.JobSubmissionResponse SubmitMapReduceStreamingJob(class Microsoft.Azure.Management.HDInsight.Job.IJobOperations operations, class Microsoft.Azure.Management.HDInsight.Job.Models.JobSubmissionParameters parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.HDInsight.Job.JobOperationsExtensions.SubmitMapReduceStreamingJob(Microsoft.Azure.Management.HDInsight.Job.IJobOperations,Microsoft.Azure.Management.HDInsight.Job.Models.JobSubmissionParameters)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function SubmitMapReduceStreamingJob (operations As IJobOperations, parameters As JobSubmissionParameters) As JobSubmissionResponse" />
      <MemberSignature Language="F#" Value="static member SubmitMapReduceStreamingJob : Microsoft.Azure.Management.HDInsight.Job.IJobOperations * Microsoft.Azure.Management.HDInsight.Job.Models.JobSubmissionParameters -&gt; Microsoft.Azure.Management.HDInsight.Job.Models.JobSubmissionResponse" Usage="Microsoft.Azure.Management.HDInsight.Job.JobOperationsExtensions.SubmitMapReduceStreamingJob (operations, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.HDInsight.Job</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.HDInsight.Job.Models.JobSubmissionResponse</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.HDInsight.Job.IJobOperations" RefType="this" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.HDInsight.Job.Models.JobSubmissionParameters" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="06f9a-212">Verweis auf die Microsoft.Azure.Management.HDInsight.Job.IJobOperations.</span><span class="sxs-lookup"><span data-stu-id="06f9a-212">Reference to the Microsoft.Azure.Management.HDInsight.Job.IJobOperations.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="06f9a-213">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="06f9a-213">Required.</span></span> <span data-ttu-id="06f9a-214">MapReduce-Auftrag-Parameter.</span><span class="sxs-lookup"><span data-stu-id="06f9a-214">MapReduce job parameters.</span></span>
            </param>
        <summary>
            <span data-ttu-id="06f9a-215">Übermittelt ein MapReduce-streamingauftrag mit einer HDInsight-Cluster an.</span><span class="sxs-lookup"><span data-stu-id="06f9a-215">Submits a MapReduce streaming job to an HDInsight cluster.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="06f9a-216">Die Antwort für den Auftrag erstellen-Vorgang.</span><span class="sxs-lookup"><span data-stu-id="06f9a-216">The Create Job operation response.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SubmitMapReduceStreamingJob">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.HDInsight.Job.Models.JobSubmissionResponse SubmitMapReduceStreamingJob (this Microsoft.Azure.Management.HDInsight.Job.IJobOperations operations, Microsoft.Azure.Management.HDInsight.Job.Models.MapReduceStreamingJobSubmissionParameters parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.HDInsight.Job.Models.JobSubmissionResponse SubmitMapReduceStreamingJob(class Microsoft.Azure.Management.HDInsight.Job.IJobOperations operations, class Microsoft.Azure.Management.HDInsight.Job.Models.MapReduceStreamingJobSubmissionParameters parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.HDInsight.Job.JobOperationsExtensions.SubmitMapReduceStreamingJob(Microsoft.Azure.Management.HDInsight.Job.IJobOperations,Microsoft.Azure.Management.HDInsight.Job.Models.MapReduceStreamingJobSubmissionParameters)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function SubmitMapReduceStreamingJob (operations As IJobOperations, parameters As MapReduceStreamingJobSubmissionParameters) As JobSubmissionResponse" />
      <MemberSignature Language="F#" Value="static member SubmitMapReduceStreamingJob : Microsoft.Azure.Management.HDInsight.Job.IJobOperations * Microsoft.Azure.Management.HDInsight.Job.Models.MapReduceStreamingJobSubmissionParameters -&gt; Microsoft.Azure.Management.HDInsight.Job.Models.JobSubmissionResponse" Usage="Microsoft.Azure.Management.HDInsight.Job.JobOperationsExtensions.SubmitMapReduceStreamingJob (operations, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.HDInsight.Job</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.HDInsight.Job.Models.JobSubmissionResponse</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.HDInsight.Job.IJobOperations" RefType="this" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.HDInsight.Job.Models.MapReduceStreamingJobSubmissionParameters" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="06f9a-217">Verweis auf die Microsoft.Azure.Management.HDInsight.Job.IJobOperations.</span><span class="sxs-lookup"><span data-stu-id="06f9a-217">Reference to the Microsoft.Azure.Management.HDInsight.Job.IJobOperations.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="06f9a-218">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="06f9a-218">Required.</span></span> <span data-ttu-id="06f9a-219">MapReduce-Auftrag-Parameter.</span><span class="sxs-lookup"><span data-stu-id="06f9a-219">MapReduce job parameters.</span></span>
            </param>
        <summary>
            <span data-ttu-id="06f9a-220">Übermittelt ein MapReduce-streamingauftrag mit einer HDInsight-Cluster an.</span><span class="sxs-lookup"><span data-stu-id="06f9a-220">Submits a MapReduce streaming job to an HDInsight cluster.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="06f9a-221">Die Antwort für den Auftrag erstellen-Vorgang.</span><span class="sxs-lookup"><span data-stu-id="06f9a-221">The Create Job operation response.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SubmitMapReduceStreamingJobAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.HDInsight.Job.Models.JobSubmissionResponse&gt; SubmitMapReduceStreamingJobAsync (this Microsoft.Azure.Management.HDInsight.Job.IJobOperations operations, Microsoft.Azure.Management.HDInsight.Job.Models.JobSubmissionParameters parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.HDInsight.Job.Models.JobSubmissionResponse&gt; SubmitMapReduceStreamingJobAsync(class Microsoft.Azure.Management.HDInsight.Job.IJobOperations operations, class Microsoft.Azure.Management.HDInsight.Job.Models.JobSubmissionParameters parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.HDInsight.Job.JobOperationsExtensions.SubmitMapReduceStreamingJobAsync(Microsoft.Azure.Management.HDInsight.Job.IJobOperations,Microsoft.Azure.Management.HDInsight.Job.Models.JobSubmissionParameters)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function SubmitMapReduceStreamingJobAsync (operations As IJobOperations, parameters As JobSubmissionParameters) As Task(Of JobSubmissionResponse)" />
      <MemberSignature Language="F#" Value="static member SubmitMapReduceStreamingJobAsync : Microsoft.Azure.Management.HDInsight.Job.IJobOperations * Microsoft.Azure.Management.HDInsight.Job.Models.JobSubmissionParameters -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.HDInsight.Job.Models.JobSubmissionResponse&gt;" Usage="Microsoft.Azure.Management.HDInsight.Job.JobOperationsExtensions.SubmitMapReduceStreamingJobAsync (operations, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.HDInsight.Job</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.HDInsight.Job.Models.JobSubmissionResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.HDInsight.Job.IJobOperations" RefType="this" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.HDInsight.Job.Models.JobSubmissionParameters" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="06f9a-222">Verweis auf die Microsoft.Azure.Management.HDInsight.Job.IJobOperations.</span><span class="sxs-lookup"><span data-stu-id="06f9a-222">Reference to the Microsoft.Azure.Management.HDInsight.Job.IJobOperations.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="06f9a-223">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="06f9a-223">Required.</span></span> <span data-ttu-id="06f9a-224">MapReduce-Auftrag-Parameter.</span><span class="sxs-lookup"><span data-stu-id="06f9a-224">MapReduce job parameters.</span></span>
            </param>
        <summary>
            <span data-ttu-id="06f9a-225">Übermittelt ein MapReduce-streamingauftrag mit einer HDInsight-Cluster an.</span><span class="sxs-lookup"><span data-stu-id="06f9a-225">Submits a MapReduce streaming job to an HDInsight cluster.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="06f9a-226">Die Antwort für den Auftrag erstellen-Vorgang.</span><span class="sxs-lookup"><span data-stu-id="06f9a-226">The Create Job operation response.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SubmitMapReduceStreamingJobAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.HDInsight.Job.Models.JobSubmissionResponse&gt; SubmitMapReduceStreamingJobAsync (this Microsoft.Azure.Management.HDInsight.Job.IJobOperations operations, Microsoft.Azure.Management.HDInsight.Job.Models.MapReduceStreamingJobSubmissionParameters parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.HDInsight.Job.Models.JobSubmissionResponse&gt; SubmitMapReduceStreamingJobAsync(class Microsoft.Azure.Management.HDInsight.Job.IJobOperations operations, class Microsoft.Azure.Management.HDInsight.Job.Models.MapReduceStreamingJobSubmissionParameters parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.HDInsight.Job.JobOperationsExtensions.SubmitMapReduceStreamingJobAsync(Microsoft.Azure.Management.HDInsight.Job.IJobOperations,Microsoft.Azure.Management.HDInsight.Job.Models.MapReduceStreamingJobSubmissionParameters)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function SubmitMapReduceStreamingJobAsync (operations As IJobOperations, parameters As MapReduceStreamingJobSubmissionParameters) As Task(Of JobSubmissionResponse)" />
      <MemberSignature Language="F#" Value="static member SubmitMapReduceStreamingJobAsync : Microsoft.Azure.Management.HDInsight.Job.IJobOperations * Microsoft.Azure.Management.HDInsight.Job.Models.MapReduceStreamingJobSubmissionParameters -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.HDInsight.Job.Models.JobSubmissionResponse&gt;" Usage="Microsoft.Azure.Management.HDInsight.Job.JobOperationsExtensions.SubmitMapReduceStreamingJobAsync (operations, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.HDInsight.Job</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.HDInsight.Job.Models.JobSubmissionResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.HDInsight.Job.IJobOperations" RefType="this" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.HDInsight.Job.Models.MapReduceStreamingJobSubmissionParameters" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="06f9a-227">Verweis auf die Microsoft.Azure.Management.HDInsight.Job.IJobOperations.</span><span class="sxs-lookup"><span data-stu-id="06f9a-227">Reference to the Microsoft.Azure.Management.HDInsight.Job.IJobOperations.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="06f9a-228">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="06f9a-228">Required.</span></span> <span data-ttu-id="06f9a-229">MapReduce-Auftrag-Parameter.</span><span class="sxs-lookup"><span data-stu-id="06f9a-229">MapReduce job parameters.</span></span>
            </param>
        <summary>
            <span data-ttu-id="06f9a-230">Übermittelt ein MapReduce-streamingauftrag mit einer HDInsight-Cluster an.</span><span class="sxs-lookup"><span data-stu-id="06f9a-230">Submits a MapReduce streaming job to an HDInsight cluster.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="06f9a-231">Die Antwort für den Auftrag erstellen-Vorgang.</span><span class="sxs-lookup"><span data-stu-id="06f9a-231">The Create Job operation response.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SubmitPigJob">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.HDInsight.Job.Models.JobSubmissionResponse SubmitPigJob (this Microsoft.Azure.Management.HDInsight.Job.IJobOperations operations, Microsoft.Azure.Management.HDInsight.Job.Models.JobSubmissionParameters parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.HDInsight.Job.Models.JobSubmissionResponse SubmitPigJob(class Microsoft.Azure.Management.HDInsight.Job.IJobOperations operations, class Microsoft.Azure.Management.HDInsight.Job.Models.JobSubmissionParameters parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.HDInsight.Job.JobOperationsExtensions.SubmitPigJob(Microsoft.Azure.Management.HDInsight.Job.IJobOperations,Microsoft.Azure.Management.HDInsight.Job.Models.JobSubmissionParameters)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function SubmitPigJob (operations As IJobOperations, parameters As JobSubmissionParameters) As JobSubmissionResponse" />
      <MemberSignature Language="F#" Value="static member SubmitPigJob : Microsoft.Azure.Management.HDInsight.Job.IJobOperations * Microsoft.Azure.Management.HDInsight.Job.Models.JobSubmissionParameters -&gt; Microsoft.Azure.Management.HDInsight.Job.Models.JobSubmissionResponse" Usage="Microsoft.Azure.Management.HDInsight.Job.JobOperationsExtensions.SubmitPigJob (operations, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.HDInsight.Job</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.HDInsight.Job.Models.JobSubmissionResponse</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.HDInsight.Job.IJobOperations" RefType="this" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.HDInsight.Job.Models.JobSubmissionParameters" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="06f9a-232">Verweis auf die Microsoft.Azure.Management.HDInsight.Job.IJobOperations.</span><span class="sxs-lookup"><span data-stu-id="06f9a-232">Reference to the Microsoft.Azure.Management.HDInsight.Job.IJobOperations.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="06f9a-233">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="06f9a-233">Required.</span></span> <span data-ttu-id="06f9a-234">Pig-Auftrag-Parameter.</span><span class="sxs-lookup"><span data-stu-id="06f9a-234">Pig job parameters.</span></span>
            </param>
        <summary>
            <span data-ttu-id="06f9a-235">Sendet einen Pig-Auftrag an einen HDInsight-Cluster an.</span><span class="sxs-lookup"><span data-stu-id="06f9a-235">Submits a Pig job to an HDInsight cluster.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="06f9a-236">Die Antwort für den Auftrag erstellen-Vorgang.</span><span class="sxs-lookup"><span data-stu-id="06f9a-236">The Create Job operation response.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SubmitPigJob">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.HDInsight.Job.Models.JobSubmissionResponse SubmitPigJob (this Microsoft.Azure.Management.HDInsight.Job.IJobOperations operations, Microsoft.Azure.Management.HDInsight.Job.Models.PigJobSubmissionParameters parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.HDInsight.Job.Models.JobSubmissionResponse SubmitPigJob(class Microsoft.Azure.Management.HDInsight.Job.IJobOperations operations, class Microsoft.Azure.Management.HDInsight.Job.Models.PigJobSubmissionParameters parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.HDInsight.Job.JobOperationsExtensions.SubmitPigJob(Microsoft.Azure.Management.HDInsight.Job.IJobOperations,Microsoft.Azure.Management.HDInsight.Job.Models.PigJobSubmissionParameters)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function SubmitPigJob (operations As IJobOperations, parameters As PigJobSubmissionParameters) As JobSubmissionResponse" />
      <MemberSignature Language="F#" Value="static member SubmitPigJob : Microsoft.Azure.Management.HDInsight.Job.IJobOperations * Microsoft.Azure.Management.HDInsight.Job.Models.PigJobSubmissionParameters -&gt; Microsoft.Azure.Management.HDInsight.Job.Models.JobSubmissionResponse" Usage="Microsoft.Azure.Management.HDInsight.Job.JobOperationsExtensions.SubmitPigJob (operations, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.HDInsight.Job</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.HDInsight.Job.Models.JobSubmissionResponse</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.HDInsight.Job.IJobOperations" RefType="this" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.HDInsight.Job.Models.PigJobSubmissionParameters" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="06f9a-237">Verweis auf die Microsoft.Azure.Management.HDInsight.Job.IJobOperations.</span><span class="sxs-lookup"><span data-stu-id="06f9a-237">Reference to the Microsoft.Azure.Management.HDInsight.Job.IJobOperations.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="06f9a-238">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="06f9a-238">Required.</span></span> <span data-ttu-id="06f9a-239">Pig-Auftrag-Parameter.</span><span class="sxs-lookup"><span data-stu-id="06f9a-239">Pig job parameters.</span></span>
            </param>
        <summary>
            <span data-ttu-id="06f9a-240">Sendet einen Pig-Auftrag an einen HDInsight-Cluster an.</span><span class="sxs-lookup"><span data-stu-id="06f9a-240">Submits a Pig job to an HDInsight cluster.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="06f9a-241">Die Antwort für den Auftrag erstellen-Vorgang.</span><span class="sxs-lookup"><span data-stu-id="06f9a-241">The Create Job operation response.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SubmitPigJobAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.HDInsight.Job.Models.JobSubmissionResponse&gt; SubmitPigJobAsync (this Microsoft.Azure.Management.HDInsight.Job.IJobOperations operations, Microsoft.Azure.Management.HDInsight.Job.Models.JobSubmissionParameters parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.HDInsight.Job.Models.JobSubmissionResponse&gt; SubmitPigJobAsync(class Microsoft.Azure.Management.HDInsight.Job.IJobOperations operations, class Microsoft.Azure.Management.HDInsight.Job.Models.JobSubmissionParameters parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.HDInsight.Job.JobOperationsExtensions.SubmitPigJobAsync(Microsoft.Azure.Management.HDInsight.Job.IJobOperations,Microsoft.Azure.Management.HDInsight.Job.Models.JobSubmissionParameters)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function SubmitPigJobAsync (operations As IJobOperations, parameters As JobSubmissionParameters) As Task(Of JobSubmissionResponse)" />
      <MemberSignature Language="F#" Value="static member SubmitPigJobAsync : Microsoft.Azure.Management.HDInsight.Job.IJobOperations * Microsoft.Azure.Management.HDInsight.Job.Models.JobSubmissionParameters -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.HDInsight.Job.Models.JobSubmissionResponse&gt;" Usage="Microsoft.Azure.Management.HDInsight.Job.JobOperationsExtensions.SubmitPigJobAsync (operations, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.HDInsight.Job</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.HDInsight.Job.Models.JobSubmissionResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.HDInsight.Job.IJobOperations" RefType="this" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.HDInsight.Job.Models.JobSubmissionParameters" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="06f9a-242">Verweis auf die Microsoft.Azure.Management.HDInsight.Job.IJobOperations.</span><span class="sxs-lookup"><span data-stu-id="06f9a-242">Reference to the Microsoft.Azure.Management.HDInsight.Job.IJobOperations.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="06f9a-243">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="06f9a-243">Required.</span></span> <span data-ttu-id="06f9a-244">Pig-Auftrag-Parameter.</span><span class="sxs-lookup"><span data-stu-id="06f9a-244">Pig job parameters.</span></span>
            </param>
        <summary>
            <span data-ttu-id="06f9a-245">Sendet einen Pig-Auftrag an einen HDInsight-Cluster an.</span><span class="sxs-lookup"><span data-stu-id="06f9a-245">Submits a Pig job to an HDInsight cluster.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="06f9a-246">Die Antwort für den Auftrag erstellen-Vorgang.</span><span class="sxs-lookup"><span data-stu-id="06f9a-246">The Create Job operation response.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SubmitPigJobAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.HDInsight.Job.Models.JobSubmissionResponse&gt; SubmitPigJobAsync (this Microsoft.Azure.Management.HDInsight.Job.IJobOperations operations, Microsoft.Azure.Management.HDInsight.Job.Models.PigJobSubmissionParameters parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.HDInsight.Job.Models.JobSubmissionResponse&gt; SubmitPigJobAsync(class Microsoft.Azure.Management.HDInsight.Job.IJobOperations operations, class Microsoft.Azure.Management.HDInsight.Job.Models.PigJobSubmissionParameters parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.HDInsight.Job.JobOperationsExtensions.SubmitPigJobAsync(Microsoft.Azure.Management.HDInsight.Job.IJobOperations,Microsoft.Azure.Management.HDInsight.Job.Models.PigJobSubmissionParameters)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function SubmitPigJobAsync (operations As IJobOperations, parameters As PigJobSubmissionParameters) As Task(Of JobSubmissionResponse)" />
      <MemberSignature Language="F#" Value="static member SubmitPigJobAsync : Microsoft.Azure.Management.HDInsight.Job.IJobOperations * Microsoft.Azure.Management.HDInsight.Job.Models.PigJobSubmissionParameters -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.HDInsight.Job.Models.JobSubmissionResponse&gt;" Usage="Microsoft.Azure.Management.HDInsight.Job.JobOperationsExtensions.SubmitPigJobAsync (operations, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.HDInsight.Job</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.HDInsight.Job.Models.JobSubmissionResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.HDInsight.Job.IJobOperations" RefType="this" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.HDInsight.Job.Models.PigJobSubmissionParameters" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="06f9a-247">Verweis auf die Microsoft.Azure.Management.HDInsight.Job.IJobOperations.</span><span class="sxs-lookup"><span data-stu-id="06f9a-247">Reference to the Microsoft.Azure.Management.HDInsight.Job.IJobOperations.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="06f9a-248">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="06f9a-248">Required.</span></span> <span data-ttu-id="06f9a-249">Pig-Auftrag-Parameter.</span><span class="sxs-lookup"><span data-stu-id="06f9a-249">Pig job parameters.</span></span>
            </param>
        <summary>
            <span data-ttu-id="06f9a-250">Sendet einen Pig-Auftrag an einen HDInsight-Cluster an.</span><span class="sxs-lookup"><span data-stu-id="06f9a-250">Submits a Pig job to an HDInsight cluster.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="06f9a-251">Die Antwort für den Auftrag erstellen-Vorgang.</span><span class="sxs-lookup"><span data-stu-id="06f9a-251">The Create Job operation response.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SubmitSqoopJob">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.HDInsight.Job.Models.JobSubmissionResponse SubmitSqoopJob (this Microsoft.Azure.Management.HDInsight.Job.IJobOperations operations, Microsoft.Azure.Management.HDInsight.Job.Models.JobSubmissionParameters parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.HDInsight.Job.Models.JobSubmissionResponse SubmitSqoopJob(class Microsoft.Azure.Management.HDInsight.Job.IJobOperations operations, class Microsoft.Azure.Management.HDInsight.Job.Models.JobSubmissionParameters parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.HDInsight.Job.JobOperationsExtensions.SubmitSqoopJob(Microsoft.Azure.Management.HDInsight.Job.IJobOperations,Microsoft.Azure.Management.HDInsight.Job.Models.JobSubmissionParameters)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function SubmitSqoopJob (operations As IJobOperations, parameters As JobSubmissionParameters) As JobSubmissionResponse" />
      <MemberSignature Language="F#" Value="static member SubmitSqoopJob : Microsoft.Azure.Management.HDInsight.Job.IJobOperations * Microsoft.Azure.Management.HDInsight.Job.Models.JobSubmissionParameters -&gt; Microsoft.Azure.Management.HDInsight.Job.Models.JobSubmissionResponse" Usage="Microsoft.Azure.Management.HDInsight.Job.JobOperationsExtensions.SubmitSqoopJob (operations, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.HDInsight.Job</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.HDInsight.Job.Models.JobSubmissionResponse</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.HDInsight.Job.IJobOperations" RefType="this" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.HDInsight.Job.Models.JobSubmissionParameters" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="06f9a-252">Verweis auf die Microsoft.Azure.Management.HDInsight.Job.IJobOperations.</span><span class="sxs-lookup"><span data-stu-id="06f9a-252">Reference to the Microsoft.Azure.Management.HDInsight.Job.IJobOperations.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="06f9a-253">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="06f9a-253">Required.</span></span> <span data-ttu-id="06f9a-254">Sqoop-Auftrag-Parameter.</span><span class="sxs-lookup"><span data-stu-id="06f9a-254">Sqoop job parameters.</span></span>
            </param>
        <summary>
            <span data-ttu-id="06f9a-255">Übermittelt einen Sqoop-Auftrag um einen HDInsight-Cluster.</span><span class="sxs-lookup"><span data-stu-id="06f9a-255">Submits a Sqoop job to an HDInsight cluster.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="06f9a-256">Die Antwort für den Auftrag erstellen-Vorgang.</span><span class="sxs-lookup"><span data-stu-id="06f9a-256">The Create Job operation response.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SubmitSqoopJob">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.HDInsight.Job.Models.JobSubmissionResponse SubmitSqoopJob (this Microsoft.Azure.Management.HDInsight.Job.IJobOperations operations, Microsoft.Azure.Management.HDInsight.Job.Models.SqoopJobSubmissionParameters parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.HDInsight.Job.Models.JobSubmissionResponse SubmitSqoopJob(class Microsoft.Azure.Management.HDInsight.Job.IJobOperations operations, class Microsoft.Azure.Management.HDInsight.Job.Models.SqoopJobSubmissionParameters parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.HDInsight.Job.JobOperationsExtensions.SubmitSqoopJob(Microsoft.Azure.Management.HDInsight.Job.IJobOperations,Microsoft.Azure.Management.HDInsight.Job.Models.SqoopJobSubmissionParameters)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function SubmitSqoopJob (operations As IJobOperations, parameters As SqoopJobSubmissionParameters) As JobSubmissionResponse" />
      <MemberSignature Language="F#" Value="static member SubmitSqoopJob : Microsoft.Azure.Management.HDInsight.Job.IJobOperations * Microsoft.Azure.Management.HDInsight.Job.Models.SqoopJobSubmissionParameters -&gt; Microsoft.Azure.Management.HDInsight.Job.Models.JobSubmissionResponse" Usage="Microsoft.Azure.Management.HDInsight.Job.JobOperationsExtensions.SubmitSqoopJob (operations, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.HDInsight.Job</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.HDInsight.Job.Models.JobSubmissionResponse</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.HDInsight.Job.IJobOperations" RefType="this" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.HDInsight.Job.Models.SqoopJobSubmissionParameters" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="06f9a-257">Verweis auf die Microsoft.Azure.Management.HDInsight.Job.IJobOperations.</span><span class="sxs-lookup"><span data-stu-id="06f9a-257">Reference to the Microsoft.Azure.Management.HDInsight.Job.IJobOperations.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="06f9a-258">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="06f9a-258">Required.</span></span> <span data-ttu-id="06f9a-259">Sqoop-Auftrag-Parameter.</span><span class="sxs-lookup"><span data-stu-id="06f9a-259">Sqoop job parameters.</span></span>
            </param>
        <summary>
            <span data-ttu-id="06f9a-260">Übermittelt einen Sqoop-Auftrag um einen HDInsight-Cluster.</span><span class="sxs-lookup"><span data-stu-id="06f9a-260">Submits a Sqoop job to an HDInsight cluster.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="06f9a-261">Die Antwort für den Auftrag erstellen-Vorgang.</span><span class="sxs-lookup"><span data-stu-id="06f9a-261">The Create Job operation response.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SubmitSqoopJobAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.HDInsight.Job.Models.JobSubmissionResponse&gt; SubmitSqoopJobAsync (this Microsoft.Azure.Management.HDInsight.Job.IJobOperations operations, Microsoft.Azure.Management.HDInsight.Job.Models.JobSubmissionParameters parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.HDInsight.Job.Models.JobSubmissionResponse&gt; SubmitSqoopJobAsync(class Microsoft.Azure.Management.HDInsight.Job.IJobOperations operations, class Microsoft.Azure.Management.HDInsight.Job.Models.JobSubmissionParameters parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.HDInsight.Job.JobOperationsExtensions.SubmitSqoopJobAsync(Microsoft.Azure.Management.HDInsight.Job.IJobOperations,Microsoft.Azure.Management.HDInsight.Job.Models.JobSubmissionParameters)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function SubmitSqoopJobAsync (operations As IJobOperations, parameters As JobSubmissionParameters) As Task(Of JobSubmissionResponse)" />
      <MemberSignature Language="F#" Value="static member SubmitSqoopJobAsync : Microsoft.Azure.Management.HDInsight.Job.IJobOperations * Microsoft.Azure.Management.HDInsight.Job.Models.JobSubmissionParameters -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.HDInsight.Job.Models.JobSubmissionResponse&gt;" Usage="Microsoft.Azure.Management.HDInsight.Job.JobOperationsExtensions.SubmitSqoopJobAsync (operations, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.HDInsight.Job</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.HDInsight.Job.Models.JobSubmissionResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.HDInsight.Job.IJobOperations" RefType="this" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.HDInsight.Job.Models.JobSubmissionParameters" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="06f9a-262">Verweis auf die Microsoft.Azure.Management.HDInsight.Job.IJobOperations.</span><span class="sxs-lookup"><span data-stu-id="06f9a-262">Reference to the Microsoft.Azure.Management.HDInsight.Job.IJobOperations.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="06f9a-263">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="06f9a-263">Required.</span></span> <span data-ttu-id="06f9a-264">Sqoop-Auftrag-Parameter.</span><span class="sxs-lookup"><span data-stu-id="06f9a-264">Sqoop job parameters.</span></span>
            </param>
        <summary>
            <span data-ttu-id="06f9a-265">Übermittelt einen Sqoop-Auftrag um einen HDInsight-Cluster.</span><span class="sxs-lookup"><span data-stu-id="06f9a-265">Submits a Sqoop job to an HDInsight cluster.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="06f9a-266">Die Antwort für den Auftrag erstellen-Vorgang.</span><span class="sxs-lookup"><span data-stu-id="06f9a-266">The Create Job operation response.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SubmitSqoopJobAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.HDInsight.Job.Models.JobSubmissionResponse&gt; SubmitSqoopJobAsync (this Microsoft.Azure.Management.HDInsight.Job.IJobOperations operations, Microsoft.Azure.Management.HDInsight.Job.Models.SqoopJobSubmissionParameters parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.HDInsight.Job.Models.JobSubmissionResponse&gt; SubmitSqoopJobAsync(class Microsoft.Azure.Management.HDInsight.Job.IJobOperations operations, class Microsoft.Azure.Management.HDInsight.Job.Models.SqoopJobSubmissionParameters parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.HDInsight.Job.JobOperationsExtensions.SubmitSqoopJobAsync(Microsoft.Azure.Management.HDInsight.Job.IJobOperations,Microsoft.Azure.Management.HDInsight.Job.Models.SqoopJobSubmissionParameters)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function SubmitSqoopJobAsync (operations As IJobOperations, parameters As SqoopJobSubmissionParameters) As Task(Of JobSubmissionResponse)" />
      <MemberSignature Language="F#" Value="static member SubmitSqoopJobAsync : Microsoft.Azure.Management.HDInsight.Job.IJobOperations * Microsoft.Azure.Management.HDInsight.Job.Models.SqoopJobSubmissionParameters -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.HDInsight.Job.Models.JobSubmissionResponse&gt;" Usage="Microsoft.Azure.Management.HDInsight.Job.JobOperationsExtensions.SubmitSqoopJobAsync (operations, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.HDInsight.Job</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.HDInsight.Job.Models.JobSubmissionResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.HDInsight.Job.IJobOperations" RefType="this" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.HDInsight.Job.Models.SqoopJobSubmissionParameters" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="06f9a-267">Verweis auf die Microsoft.Azure.Management.HDInsight.Job.IJobOperations.</span><span class="sxs-lookup"><span data-stu-id="06f9a-267">Reference to the Microsoft.Azure.Management.HDInsight.Job.IJobOperations.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="06f9a-268">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="06f9a-268">Required.</span></span> <span data-ttu-id="06f9a-269">Sqoop-Auftrag-Parameter.</span><span class="sxs-lookup"><span data-stu-id="06f9a-269">Sqoop job parameters.</span></span>
            </param>
        <summary>
            <span data-ttu-id="06f9a-270">Übermittelt einen Sqoop-Auftrag um einen HDInsight-Cluster.</span><span class="sxs-lookup"><span data-stu-id="06f9a-270">Submits a Sqoop job to an HDInsight cluster.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="06f9a-271">Die Antwort für den Auftrag erstellen-Vorgang.</span><span class="sxs-lookup"><span data-stu-id="06f9a-271">The Create Job operation response.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="WaitForJobCompletion">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.HDInsight.Job.Models.JobGetResponse WaitForJobCompletion (this Microsoft.Azure.Management.HDInsight.Job.IJobOperations operations, string jobId, Nullable&lt;TimeSpan&gt; duration = null, Nullable&lt;TimeSpan&gt; waitInterval = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.HDInsight.Job.Models.JobGetResponse WaitForJobCompletion(class Microsoft.Azure.Management.HDInsight.Job.IJobOperations operations, string jobId, valuetype System.Nullable`1&lt;valuetype System.TimeSpan&gt; duration, valuetype System.Nullable`1&lt;valuetype System.TimeSpan&gt; waitInterval) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.HDInsight.Job.JobOperationsExtensions.WaitForJobCompletion(Microsoft.Azure.Management.HDInsight.Job.IJobOperations,System.String,System.Nullable{System.TimeSpan},System.Nullable{System.TimeSpan})" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function WaitForJobCompletion (operations As IJobOperations, jobId As String, Optional duration As Nullable(Of TimeSpan) = null, Optional waitInterval As Nullable(Of TimeSpan) = null) As JobGetResponse" />
      <MemberSignature Language="F#" Value="static member WaitForJobCompletion : Microsoft.Azure.Management.HDInsight.Job.IJobOperations * string * Nullable&lt;TimeSpan&gt; * Nullable&lt;TimeSpan&gt; -&gt; Microsoft.Azure.Management.HDInsight.Job.Models.JobGetResponse" Usage="Microsoft.Azure.Management.HDInsight.Job.JobOperationsExtensions.WaitForJobCompletion (operations, jobId, duration, waitInterval)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.HDInsight.Job</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.HDInsight.Job.Models.JobGetResponse</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.HDInsight.Job.IJobOperations" RefType="this" />
        <Parameter Name="jobId" Type="System.String" />
        <Parameter Name="duration" Type="System.Nullable&lt;System.TimeSpan&gt;" />
        <Parameter Name="waitInterval" Type="System.Nullable&lt;System.TimeSpan&gt;" />
      </Parameters>
      <Docs>
        <param name="operations">To be added.</param>
        <param name="jobId">
            <span data-ttu-id="06f9a-272">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="06f9a-272">Required.</span></span> <span data-ttu-id="06f9a-273">Die Id des Auftrags.</span><span class="sxs-lookup"><span data-stu-id="06f9a-273">The id of the job.</span></span>
            </param>
        <param name="duration">
            <span data-ttu-id="06f9a-274">Optional.</span><span class="sxs-lookup"><span data-stu-id="06f9a-274">Optional.</span></span> <span data-ttu-id="06f9a-275">Die maximale Zeitspanne zum Abschluss des Auftrags vor der Rückgabe an den Client gewartet werden soll.</span><span class="sxs-lookup"><span data-stu-id="06f9a-275">The maximum duration to wait for completion of job before returning to client.</span></span> <span data-ttu-id="06f9a-276">Wenn Sie nicht warten Sie dann zu übergeben, bis der Auftrag abgeschlossen ist.</span><span class="sxs-lookup"><span data-stu-id="06f9a-276">If not passed then wait till job is completed.</span></span>
            </param>
        <param name="waitInterval">
            <span data-ttu-id="06f9a-277">Optional.</span><span class="sxs-lookup"><span data-stu-id="06f9a-277">Optional.</span></span> <span data-ttu-id="06f9a-278">Das Intervall, Auftragsstatus abzurufen.</span><span class="sxs-lookup"><span data-stu-id="06f9a-278">The interval to poll for job status.</span></span> <span data-ttu-id="06f9a-279">Der Standardwert wird aus der HDInsight-Auftrags Verwaltungsclient DefaultPollInterval-Eigenschaft festgelegt.</span><span class="sxs-lookup"><span data-stu-id="06f9a-279">The default value is set from DefaultPollInterval property of HDInsight job management client.</span></span>
            </param>
        <summary>
            <span data-ttu-id="06f9a-280">Warten Sie auf den Abschluss eines Auftrags.</span><span class="sxs-lookup"><span data-stu-id="06f9a-280">Wait for completion of a Job.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.TimeoutException">
            <span data-ttu-id="06f9a-281">Wird ausgelöst, wenn warten auf die Beendigung des Auftrags die maximale Dauer, angegeben durch Parameter Dauer überschreitet.</span><span class="sxs-lookup"><span data-stu-id="06f9a-281">Thrown when waiting for job completion exceeds the maximum duration specified by parameter duration.</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="WaitForJobCompletionAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.HDInsight.Job.Models.JobGetResponse&gt; WaitForJobCompletionAsync (this Microsoft.Azure.Management.HDInsight.Job.IJobOperations operations, string jobId, Nullable&lt;TimeSpan&gt; duration = null, Nullable&lt;TimeSpan&gt; waitInterval = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.HDInsight.Job.Models.JobGetResponse&gt; WaitForJobCompletionAsync(class Microsoft.Azure.Management.HDInsight.Job.IJobOperations operations, string jobId, valuetype System.Nullable`1&lt;valuetype System.TimeSpan&gt; duration, valuetype System.Nullable`1&lt;valuetype System.TimeSpan&gt; waitInterval) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.HDInsight.Job.JobOperationsExtensions.WaitForJobCompletionAsync(Microsoft.Azure.Management.HDInsight.Job.IJobOperations,System.String,System.Nullable{System.TimeSpan},System.Nullable{System.TimeSpan})" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function WaitForJobCompletionAsync (operations As IJobOperations, jobId As String, Optional duration As Nullable(Of TimeSpan) = null, Optional waitInterval As Nullable(Of TimeSpan) = null) As Task(Of JobGetResponse)" />
      <MemberSignature Language="F#" Value="static member WaitForJobCompletionAsync : Microsoft.Azure.Management.HDInsight.Job.IJobOperations * string * Nullable&lt;TimeSpan&gt; * Nullable&lt;TimeSpan&gt; -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.HDInsight.Job.Models.JobGetResponse&gt;" Usage="Microsoft.Azure.Management.HDInsight.Job.JobOperationsExtensions.WaitForJobCompletionAsync (operations, jobId, duration, waitInterval)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.HDInsight.Job</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.HDInsight.Job.Models.JobGetResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.HDInsight.Job.IJobOperations" RefType="this" />
        <Parameter Name="jobId" Type="System.String" />
        <Parameter Name="duration" Type="System.Nullable&lt;System.TimeSpan&gt;" />
        <Parameter Name="waitInterval" Type="System.Nullable&lt;System.TimeSpan&gt;" />
      </Parameters>
      <Docs>
        <param name="operations">To be added.</param>
        <param name="jobId">
            <span data-ttu-id="06f9a-282">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="06f9a-282">Required.</span></span> <span data-ttu-id="06f9a-283">Die Id des Auftrags.</span><span class="sxs-lookup"><span data-stu-id="06f9a-283">The id of the job.</span></span>
            </param>
        <param name="duration">
            <span data-ttu-id="06f9a-284">Optional.</span><span class="sxs-lookup"><span data-stu-id="06f9a-284">Optional.</span></span> <span data-ttu-id="06f9a-285">Die maximale Zeitspanne zum Abschluss des Auftrags vor der Rückgabe an den Client gewartet werden soll.</span><span class="sxs-lookup"><span data-stu-id="06f9a-285">The maximum duration to wait for completion of job before returning to client.</span></span> <span data-ttu-id="06f9a-286">Wenn Sie nicht warten Sie dann zu übergeben, bis der Auftrag abgeschlossen ist.</span><span class="sxs-lookup"><span data-stu-id="06f9a-286">If not passed then wait till job is completed.</span></span>
            </param>
        <param name="waitInterval">
            <span data-ttu-id="06f9a-287">Optional.</span><span class="sxs-lookup"><span data-stu-id="06f9a-287">Optional.</span></span> <span data-ttu-id="06f9a-288">Das Intervall, Auftragsstatus abzurufen.</span><span class="sxs-lookup"><span data-stu-id="06f9a-288">The interval to poll for job status.</span></span> <span data-ttu-id="06f9a-289">Der Standardwert wird aus der HDInsight-Auftrags Verwaltungsclient DefaultPollInterval-Eigenschaft festgelegt.</span><span class="sxs-lookup"><span data-stu-id="06f9a-289">The default value is set from DefaultPollInterval property of HDInsight job management client.</span></span>
            </param>
        <summary>
            <span data-ttu-id="06f9a-290">Warten Sie auf den Abschluss eines Auftrags.</span><span class="sxs-lookup"><span data-stu-id="06f9a-290">Wait for completion of a Job.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.TimeoutException">
            <span data-ttu-id="06f9a-291">Wird ausgelöst, wenn warten auf die Beendigung des Auftrags die maximale Dauer, angegeben durch Parameter Dauer überschreitet.</span><span class="sxs-lookup"><span data-stu-id="06f9a-291">Thrown when waiting for job completion exceeds the maximum duration specified by parameter duration.</span></span>
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>