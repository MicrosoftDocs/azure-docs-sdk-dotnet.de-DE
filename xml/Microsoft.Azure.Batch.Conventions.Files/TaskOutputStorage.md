<Type Name="TaskOutputStorage" FullName="Microsoft.Azure.Batch.Conventions.Files.TaskOutputStorage">
  <TypeSignature Language="C#" Value="public class TaskOutputStorage" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit TaskOutputStorage extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Batch.Conventions.Files.TaskOutputStorage" />
  <TypeSignature Language="VB.NET" Value="Public Class TaskOutputStorage" />
  <TypeSignature Language="F#" Value="type TaskOutputStorage = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Batch.Conventions.Files</AssemblyName>
    <AssemblyVersion>3.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="8f1db-101">Stellt permanenten Speicher für die Ausgaben eines Azure Batch-Vorgangs dar.</span><span class="sxs-lookup"><span data-stu-id="8f1db-101">Represents persistent storage for the outputs of an Azure Batch task.</span></span>
            </summary>
    <remarks>
            <span data-ttu-id="8f1db-102">Aufgabenausgaben finden Sie in Ausgabedaten logisch eine bestimmte Aufgabe, anstatt den Auftrag als Ganzes zugeordnet.</span><span class="sxs-lookup"><span data-stu-id="8f1db-102">Task outputs refer to output data logically associated with a specific task, rather than the job as a whole.</span></span> <span data-ttu-id="8f1db-103">Z. B. in einem Film-Rendering-Auftrag wäre wenn eine Aufgabe mit einen einzelnen Frame gerendert dieser Rahmen einer Aufgabenausgabe.</span><span class="sxs-lookup"><span data-stu-id="8f1db-103">For example, in a movie rendering job, if a task rendered a single frame, that frame would be a task output.</span></span>  <span data-ttu-id="8f1db-104">Protokolle und andere Diagnoseinformationen wie z. B. Zwischendateien möglicherweise auch beibehalten, wie taskausgaben (siehe <see cref="T:Microsoft.Azure.Batch.Conventions.Files.TaskOutputKind" /> für eine Möglichkeit, diese zu kategorisieren, sodass Clients die Hauptausgabe weitere Daten unterscheiden, können).</span><span class="sxs-lookup"><span data-stu-id="8f1db-104">Logs and other diagnostic information such as intermediate files may also be persisted as task outputs (see <see cref="T:Microsoft.Azure.Batch.Conventions.Files.TaskOutputKind" /> for a way to categorise these so that clients can distinguish between the main output and auxiliary data).</span></span>
            </remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public TaskOutputStorage (Uri jobOutputContainerUri, string taskId);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.Uri jobOutputContainerUri, string taskId) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Conventions.Files.TaskOutputStorage.#ctor(System.Uri,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (jobOutputContainerUri As Uri, taskId As String)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Batch.Conventions.Files.TaskOutputStorage : Uri * string -&gt; Microsoft.Azure.Batch.Conventions.Files.TaskOutputStorage" Usage="new Microsoft.Azure.Batch.Conventions.Files.TaskOutputStorage (jobOutputContainerUri, taskId)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch.Conventions.Files</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="jobOutputContainerUri" Type="System.Uri" />
        <Parameter Name="taskId" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="jobOutputContainerUri"><span data-ttu-id="8f1db-105">Die URL im Azure-Speicher des Blob-Containers für diesen Auftrag zugeordneten Ausgaben verwendet werden soll.</span><span class="sxs-lookup"><span data-stu-id="8f1db-105">The URL in Azure storage of the blob container to use for outputs associated with this job.</span></span> <span data-ttu-id="8f1db-106">Diese URL muss eine SAS (Shared Access Signature) mit dem Gewähren des Zugriffs auf den Container enthalten, oder der Container muss öffentlich sein.</span><span class="sxs-lookup"><span data-stu-id="8f1db-106">This URL must contain a SAS (Shared Access Signature) granting access to the container, or the container must be public.</span></span></param>
        <param name="taskId"><span data-ttu-id="8f1db-107">Die Id der Azure Batch-Aufgabe.</span><span class="sxs-lookup"><span data-stu-id="8f1db-107">The id of the Azure Batch task.</span></span></param>
        <summary>
            <span data-ttu-id="8f1db-108">Initialisiert eine neue Instanz der dem <see cref="T:Microsoft.Azure.Batch.Conventions.Files.JobOutputStorage" /> Klasse von einem Task-Id und eine URL, die der Auftrag Ausgabecontainer darstellt.</span><span class="sxs-lookup"><span data-stu-id="8f1db-108">Initializes a new instance of the <see cref="T:Microsoft.Azure.Batch.Conventions.Files.JobOutputStorage" /> class from a task id and a URL representing the job output container.</span></span>
            </summary>
        <remarks><span data-ttu-id="8f1db-109">Der Container muss bereits vorhanden sein; die Klasse TaskOutputStorage wird nicht für Sie erstellt.</span><span class="sxs-lookup"><span data-stu-id="8f1db-109">The container must already exist; the TaskOutputStorage class does not create it for you.</span></span></remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public TaskOutputStorage (Microsoft.WindowsAzure.Storage.CloudStorageAccount storageAccount, string jobId, string taskId);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class Microsoft.WindowsAzure.Storage.CloudStorageAccount storageAccount, string jobId, string taskId) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Conventions.Files.TaskOutputStorage.#ctor(Microsoft.WindowsAzure.Storage.CloudStorageAccount,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (storageAccount As CloudStorageAccount, jobId As String, taskId As String)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Batch.Conventions.Files.TaskOutputStorage : Microsoft.WindowsAzure.Storage.CloudStorageAccount * string * string -&gt; Microsoft.Azure.Batch.Conventions.Files.TaskOutputStorage" Usage="new Microsoft.Azure.Batch.Conventions.Files.TaskOutputStorage (storageAccount, jobId, taskId)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch.Conventions.Files</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="storageAccount" Type="Microsoft.WindowsAzure.Storage.CloudStorageAccount" />
        <Parameter Name="jobId" Type="System.String" />
        <Parameter Name="taskId" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="storageAccount"><span data-ttu-id="8f1db-110">Das Speicherkonto mit der Azure Batch-Konto verknüpft ist.</span><span class="sxs-lookup"><span data-stu-id="8f1db-110">The storage account linked to the Azure Batch account.</span></span></param>
        <param name="jobId"><span data-ttu-id="8f1db-111">Die Id des Azure Batch-Auftrags, der den Task enthält.</span><span class="sxs-lookup"><span data-stu-id="8f1db-111">The id of the Azure Batch job containing the task.</span></span></param>
        <param name="taskId"><span data-ttu-id="8f1db-112">Die Id der Azure Batch-Aufgabe.</span><span class="sxs-lookup"><span data-stu-id="8f1db-112">The id of the Azure Batch task.</span></span></param>
        <summary>
            <span data-ttu-id="8f1db-113">Initialisiert eine neue Instanz der dem <see cref="T:Microsoft.Azure.Batch.Conventions.Files.JobOutputStorage" /> Klasse aus einem Speicherkonto, die Auftrags-Id und die Task-Id.</span><span class="sxs-lookup"><span data-stu-id="8f1db-113">Initializes a new instance of the <see cref="T:Microsoft.Azure.Batch.Conventions.Files.JobOutputStorage" /> class from a storage account, job id, and task id.</span></span>
            </summary>
        <remarks><span data-ttu-id="8f1db-114">Der Auftrag Ausgabecontainer muss bereits vorhanden sein; die Klasse TaskOutputStorage wird nicht für Sie erstellt.</span><span class="sxs-lookup"><span data-stu-id="8f1db-114">The job output container must already exist; the TaskOutputStorage class does not create it for you.</span></span></remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public TaskOutputStorage (Uri jobOutputContainerUri, string taskId, Microsoft.WindowsAzure.Storage.RetryPolicies.IRetryPolicy storageRetryPolicy);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.Uri jobOutputContainerUri, string taskId, class Microsoft.WindowsAzure.Storage.RetryPolicies.IRetryPolicy storageRetryPolicy) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Conventions.Files.TaskOutputStorage.#ctor(System.Uri,System.String,Microsoft.WindowsAzure.Storage.RetryPolicies.IRetryPolicy)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (jobOutputContainerUri As Uri, taskId As String, storageRetryPolicy As IRetryPolicy)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Batch.Conventions.Files.TaskOutputStorage : Uri * string * Microsoft.WindowsAzure.Storage.RetryPolicies.IRetryPolicy -&gt; Microsoft.Azure.Batch.Conventions.Files.TaskOutputStorage" Usage="new Microsoft.Azure.Batch.Conventions.Files.TaskOutputStorage (jobOutputContainerUri, taskId, storageRetryPolicy)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch.Conventions.Files</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="jobOutputContainerUri" Type="System.Uri" />
        <Parameter Name="taskId" Type="System.String" />
        <Parameter Name="storageRetryPolicy" Type="Microsoft.WindowsAzure.Storage.RetryPolicies.IRetryPolicy" />
      </Parameters>
      <Docs>
        <param name="jobOutputContainerUri"><span data-ttu-id="8f1db-115">Die URL im Azure-Speicher des Blob-Containers für diesen Auftrag zugeordneten Ausgaben verwendet werden soll.</span><span class="sxs-lookup"><span data-stu-id="8f1db-115">The URL in Azure storage of the blob container to use for outputs associated with this job.</span></span> <span data-ttu-id="8f1db-116">Diese URL muss eine SAS (Shared Access Signature) mit dem Gewähren des Zugriffs auf den Container enthalten, oder der Container muss öffentlich sein.</span><span class="sxs-lookup"><span data-stu-id="8f1db-116">This URL must contain a SAS (Shared Access Signature) granting access to the container, or the container must be public.</span></span></param>
        <param name="taskId"><span data-ttu-id="8f1db-117">Die Id der Azure Batch-Aufgabe.</span><span class="sxs-lookup"><span data-stu-id="8f1db-117">The id of the Azure Batch task.</span></span></param>
        <param name="storageRetryPolicy"><span data-ttu-id="8f1db-118">Die wiederholungsrichtlinie für speicheranforderungen.</span><span class="sxs-lookup"><span data-stu-id="8f1db-118">The retry policy for storage requests.</span></span></param>
        <summary>
            <span data-ttu-id="8f1db-119">Initialisiert eine neue Instanz der dem <see cref="T:Microsoft.Azure.Batch.Conventions.Files.JobOutputStorage" /> Klasse von einem Task-Id und eine URL, die der Auftrag Ausgabecontainer darstellt.</span><span class="sxs-lookup"><span data-stu-id="8f1db-119">Initializes a new instance of the <see cref="T:Microsoft.Azure.Batch.Conventions.Files.JobOutputStorage" /> class from a task id and a URL representing the job output container.</span></span>
            </summary>
        <remarks><span data-ttu-id="8f1db-120">Der Container muss bereits vorhanden sein; die Klasse TaskOutputStorage wird nicht für Sie erstellt.</span><span class="sxs-lookup"><span data-stu-id="8f1db-120">The container must already exist; the TaskOutputStorage class does not create it for you.</span></span></remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public TaskOutputStorage (Microsoft.WindowsAzure.Storage.CloudStorageAccount storageAccount, string jobId, string taskId, Microsoft.WindowsAzure.Storage.RetryPolicies.IRetryPolicy storageRetryPolicy);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class Microsoft.WindowsAzure.Storage.CloudStorageAccount storageAccount, string jobId, string taskId, class Microsoft.WindowsAzure.Storage.RetryPolicies.IRetryPolicy storageRetryPolicy) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Conventions.Files.TaskOutputStorage.#ctor(Microsoft.WindowsAzure.Storage.CloudStorageAccount,System.String,System.String,Microsoft.WindowsAzure.Storage.RetryPolicies.IRetryPolicy)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (storageAccount As CloudStorageAccount, jobId As String, taskId As String, storageRetryPolicy As IRetryPolicy)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Batch.Conventions.Files.TaskOutputStorage : Microsoft.WindowsAzure.Storage.CloudStorageAccount * string * string * Microsoft.WindowsAzure.Storage.RetryPolicies.IRetryPolicy -&gt; Microsoft.Azure.Batch.Conventions.Files.TaskOutputStorage" Usage="new Microsoft.Azure.Batch.Conventions.Files.TaskOutputStorage (storageAccount, jobId, taskId, storageRetryPolicy)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch.Conventions.Files</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="storageAccount" Type="Microsoft.WindowsAzure.Storage.CloudStorageAccount" />
        <Parameter Name="jobId" Type="System.String" />
        <Parameter Name="taskId" Type="System.String" />
        <Parameter Name="storageRetryPolicy" Type="Microsoft.WindowsAzure.Storage.RetryPolicies.IRetryPolicy" />
      </Parameters>
      <Docs>
        <param name="storageAccount"><span data-ttu-id="8f1db-121">Das Speicherkonto mit der Azure Batch-Konto verknüpft ist.</span><span class="sxs-lookup"><span data-stu-id="8f1db-121">The storage account linked to the Azure Batch account.</span></span></param>
        <param name="jobId"><span data-ttu-id="8f1db-122">Die Id des Azure Batch-Auftrags, der den Task enthält.</span><span class="sxs-lookup"><span data-stu-id="8f1db-122">The id of the Azure Batch job containing the task.</span></span></param>
        <param name="taskId"><span data-ttu-id="8f1db-123">Die Id der Azure Batch-Aufgabe.</span><span class="sxs-lookup"><span data-stu-id="8f1db-123">The id of the Azure Batch task.</span></span></param>
        <param name="storageRetryPolicy"><span data-ttu-id="8f1db-124">Die wiederholungsrichtlinie für speicheranforderungen.</span><span class="sxs-lookup"><span data-stu-id="8f1db-124">The retry policy for storage requests.</span></span></param>
        <summary>
            <span data-ttu-id="8f1db-125">Initialisiert eine neue Instanz der dem <see cref="T:Microsoft.Azure.Batch.Conventions.Files.JobOutputStorage" /> Klasse aus einem Speicherkonto, die Auftrags-Id und die Task-Id.</span><span class="sxs-lookup"><span data-stu-id="8f1db-125">Initializes a new instance of the <see cref="T:Microsoft.Azure.Batch.Conventions.Files.JobOutputStorage" /> class from a storage account, job id, and task id.</span></span>
            </summary>
        <remarks><span data-ttu-id="8f1db-126">Der Auftrag Ausgabecontainer muss bereits vorhanden sein; die Klasse TaskOutputStorage wird nicht für Sie erstellt.</span><span class="sxs-lookup"><span data-stu-id="8f1db-126">The job output container must already exist; the TaskOutputStorage class does not create it for you.</span></span></remarks>
      </Docs>
    </Member>
    <Member MemberName="GetOutputAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Batch.Conventions.Files.OutputFileReference&gt; GetOutputAsync (Microsoft.Azure.Batch.Conventions.Files.TaskOutputKind kind, string filePath, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Batch.Conventions.Files.OutputFileReference&gt; GetOutputAsync(class Microsoft.Azure.Batch.Conventions.Files.TaskOutputKind kind, string filePath, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Conventions.Files.TaskOutputStorage.GetOutputAsync(Microsoft.Azure.Batch.Conventions.Files.TaskOutputKind,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.GetOutputAsync : Microsoft.Azure.Batch.Conventions.Files.TaskOutputKind * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Batch.Conventions.Files.OutputFileReference&gt;" Usage="taskOutputStorage.GetOutputAsync (kind, filePath, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch.Conventions.Files</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Batch.Conventions.Files.TaskOutputStorage/&lt;GetOutputAsync&gt;d__11))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Batch.Conventions.Files.OutputFileReference&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="kind" Type="Microsoft.Azure.Batch.Conventions.Files.TaskOutputKind" />
        <Parameter Name="filePath" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="kind"><span data-ttu-id="8f1db-127">Ein <see cref="T:Microsoft.Azure.Batch.Conventions.Files.TaskOutputKind" /> für die Kategorie der Ausgabe abrufen, z. B. <see cref="F:Microsoft.Azure.Batch.Conventions.Files.TaskOutputKind.TaskOutput" /> oder <see cref="F:Microsoft.Azure.Batch.Conventions.Files.TaskOutputKind.TaskLog" />.</span><span class="sxs-lookup"><span data-stu-id="8f1db-127">A <see cref="T:Microsoft.Azure.Batch.Conventions.Files.TaskOutputKind" /> representing the category of the output to retrieve, for example <see cref="F:Microsoft.Azure.Batch.Conventions.Files.TaskOutputKind.TaskOutput" /> or <see cref="F:Microsoft.Azure.Batch.Conventions.Files.TaskOutputKind.TaskLog" />.</span></span></param>
        <param name="filePath"><span data-ttu-id="8f1db-128">Der Pfad, unter dem die Ausgabe im Blob-Speicher beibehalten wurde.</span><span class="sxs-lookup"><span data-stu-id="8f1db-128">The path under which the output was persisted in blob storage.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="8f1db-129">Ein <see cref="T:System.Threading.CancellationToken" /> für die Steuerung der Lebensdauer eines asynchronen Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="8f1db-129">A <see cref="T:System.Threading.CancellationToken" /> for controlling the lifetime of the asynchronous operation.</span></span></param>
        <summary>
            <span data-ttu-id="8f1db-130">Ruft eine Aufgabenausgabe aus dem Azure-Blob-Speicher von der Art und den Pfad ab.</span><span class="sxs-lookup"><span data-stu-id="8f1db-130">Retrieves a task output from Azure blob storage by kind and path.</span></span>
            </summary>
        <returns><span data-ttu-id="8f1db-131">Ein Verweis auf die angeforderte Datei im Azure-Blob-Speicher.</span><span class="sxs-lookup"><span data-stu-id="8f1db-131">A reference to the requested file in Azure blob storage.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListOutputs">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.Conventions.Files.OutputFileReference&gt; ListOutputs (Microsoft.Azure.Batch.Conventions.Files.TaskOutputKind kind);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Batch.Conventions.Files.OutputFileReference&gt; ListOutputs(class Microsoft.Azure.Batch.Conventions.Files.TaskOutputKind kind) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Conventions.Files.TaskOutputStorage.ListOutputs(Microsoft.Azure.Batch.Conventions.Files.TaskOutputKind)" />
      <MemberSignature Language="VB.NET" Value="Public Function ListOutputs (kind As TaskOutputKind) As IEnumerable(Of OutputFileReference)" />
      <MemberSignature Language="F#" Value="member this.ListOutputs : Microsoft.Azure.Batch.Conventions.Files.TaskOutputKind -&gt; seq&lt;Microsoft.Azure.Batch.Conventions.Files.OutputFileReference&gt;" Usage="taskOutputStorage.ListOutputs kind" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch.Conventions.Files</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.Conventions.Files.OutputFileReference&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="kind" Type="Microsoft.Azure.Batch.Conventions.Files.TaskOutputKind" />
      </Parameters>
      <Docs>
        <param name="kind"><span data-ttu-id="8f1db-132">Ein <see cref="T:Microsoft.Azure.Batch.Conventions.Files.TaskOutputKind" /> für die Kategorie der Ausgaben auflisten, z. B. <see cref="F:Microsoft.Azure.Batch.Conventions.Files.TaskOutputKind.TaskOutput" /> oder <see cref="F:Microsoft.Azure.Batch.Conventions.Files.TaskOutputKind.TaskLog" />.</span><span class="sxs-lookup"><span data-stu-id="8f1db-132">A <see cref="T:Microsoft.Azure.Batch.Conventions.Files.TaskOutputKind" /> representing the category of outputs to list, for example <see cref="F:Microsoft.Azure.Batch.Conventions.Files.TaskOutputKind.TaskOutput" /> or <see cref="F:Microsoft.Azure.Batch.Conventions.Files.TaskOutputKind.TaskLog" />.</span></span></param>
        <summary>
            <span data-ttu-id="8f1db-133">Listet die Aufgabenausgaben der angegebenen Art an.</span><span class="sxs-lookup"><span data-stu-id="8f1db-133">Lists the task outputs of the specified kind.</span></span>
            </summary>
        <returns><span data-ttu-id="8f1db-134">Eine Liste der persistent gespeicherten Aufgabenausgaben der angegebenen Art.</span><span class="sxs-lookup"><span data-stu-id="8f1db-134">A list of persisted task outputs of the specified kind.</span></span></returns>
        <remarks><span data-ttu-id="8f1db-135">Die Liste wird aus dem Azure-Blob-Speicher verzögert abgerufen, wenn diese aufgelistet wird.</span><span class="sxs-lookup"><span data-stu-id="8f1db-135">The list is retrieved lazily from Azure blob storage when it is enumerated.</span></span></remarks>
      </Docs>
    </Member>
    <Member MemberName="SaveAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task SaveAsync (Microsoft.Azure.Batch.Conventions.Files.TaskOutputKind kind, string relativePath, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task SaveAsync(class Microsoft.Azure.Batch.Conventions.Files.TaskOutputKind kind, string relativePath, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Conventions.Files.TaskOutputStorage.SaveAsync(Microsoft.Azure.Batch.Conventions.Files.TaskOutputKind,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.SaveAsync : Microsoft.Azure.Batch.Conventions.Files.TaskOutputKind * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="taskOutputStorage.SaveAsync (kind, relativePath, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch.Conventions.Files</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Batch.Conventions.Files.TaskOutputStorage/&lt;SaveAsync&gt;d__6))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="kind" Type="Microsoft.Azure.Batch.Conventions.Files.TaskOutputKind" />
        <Parameter Name="relativePath" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="kind"><span data-ttu-id="8f1db-136">Ein <see cref="T:Microsoft.Azure.Batch.Conventions.Files.TaskOutputKind" /> für die Kategorie aus, unter dem diese Datei zu speichern, z. B. <see cref="F:Microsoft.Azure.Batch.Conventions.Files.TaskOutputKind.TaskOutput" /> oder <see cref="F:Microsoft.Azure.Batch.Conventions.Files.TaskOutputKind.TaskLog" />.</span><span class="sxs-lookup"><span data-stu-id="8f1db-136">A <see cref="T:Microsoft.Azure.Batch.Conventions.Files.TaskOutputKind" /> representing the category under which to store this file, for example <see cref="F:Microsoft.Azure.Batch.Conventions.Files.TaskOutputKind.TaskOutput" /> or <see cref="F:Microsoft.Azure.Batch.Conventions.Files.TaskOutputKind.TaskLog" />.</span></span></param>
        <param name="relativePath"><span data-ttu-id="8f1db-137">Der Pfad der Datei relativ zum aktuellen Verzeichnis zu speichern.</span><span class="sxs-lookup"><span data-stu-id="8f1db-137">The path of the file to save, relative to the current directory.</span></span>
            <span data-ttu-id="8f1db-138">Wenn die Datei in einem Unterverzeichnis des aktuellen Verzeichnisses ist, wird der relative Pfad im Blob-Speicher beibehalten.</span><span class="sxs-lookup"><span data-stu-id="8f1db-138">If the file is in a subdirectory of the current directory, the relative path will be preserved in blob storage.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="8f1db-139">Ein <see cref="T:System.Threading.CancellationToken" /> für die Steuerung der Lebensdauer eines asynchronen Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="8f1db-139">A <see cref="T:System.Threading.CancellationToken" /> for controlling the lifetime of the asynchronous operation.</span></span></param>
        <summary>
            <span data-ttu-id="8f1db-140">Speichert die angegebene Datei in den persistenten Speicher.</span><span class="sxs-lookup"><span data-stu-id="8f1db-140">Saves the specified file to persistent storage.</span></span>
            </summary>
        <returns><span data-ttu-id="8f1db-141">Ein <see cref="T:System.Threading.Tasks.Task" />-Element, das den asynchronen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="8f1db-141">A <see cref="T:System.Threading.Tasks.Task" /> that represents the asynchronous operation.</span></span></returns>
        <remarks><span data-ttu-id="8f1db-142">Wenn die Datei außerhalb des aktuellen Verzeichnisses ist, werden von links aus der Verzeichnisstruktur entfernt.</span><span class="sxs-lookup"><span data-stu-id="8f1db-142">If the file is outside the current directory, traversals up the directory tree are removed.</span></span>
            <span data-ttu-id="8f1db-143">Z. B. eine <paramref name="relativePath" /> der ".. \ProcessEnv.cmd"würde als"ProcessEnv.cmd"im Rahmen der Erstellen eines Blob-namens behandelt werden.</span><span class="sxs-lookup"><span data-stu-id="8f1db-143">For example, a <paramref name="relativePath" /> of "..\ProcessEnv.cmd" would be treated as "ProcessEnv.cmd" for the purposes of creating a blob name.</span></span></remarks>
        <exception cref="T:System.ArgumentNullException"><span data-ttu-id="8f1db-144">Die <paramref name="kind" /> oder <paramref name="relativePath" /> Argument ist null.</span><span class="sxs-lookup"><span data-stu-id="8f1db-144">The <paramref name="kind" /> or <paramref name="relativePath" /> argument is null.</span></span></exception>
        <exception cref="T:System.ArgumentException"><span data-ttu-id="8f1db-145">Die <paramref name="relativePath" /> Argument ist ein absoluter Pfad oder ist leer.</span><span class="sxs-lookup"><span data-stu-id="8f1db-145">The <paramref name="relativePath" /> argument is an absolute path, or is empty.</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName="SaveAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task SaveAsync (Microsoft.Azure.Batch.Conventions.Files.TaskOutputKind kind, string sourcePath, string destinationRelativePath, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task SaveAsync(class Microsoft.Azure.Batch.Conventions.Files.TaskOutputKind kind, string sourcePath, string destinationRelativePath, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Conventions.Files.TaskOutputStorage.SaveAsync(Microsoft.Azure.Batch.Conventions.Files.TaskOutputKind,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.SaveAsync : Microsoft.Azure.Batch.Conventions.Files.TaskOutputKind * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="taskOutputStorage.SaveAsync (kind, sourcePath, destinationRelativePath, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch.Conventions.Files</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Batch.Conventions.Files.TaskOutputStorage/&lt;SaveAsync&gt;d__8))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="kind" Type="Microsoft.Azure.Batch.Conventions.Files.TaskOutputKind" />
        <Parameter Name="sourcePath" Type="System.String" />
        <Parameter Name="destinationRelativePath" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="kind"><span data-ttu-id="8f1db-146">Ein <see cref="T:Microsoft.Azure.Batch.Conventions.Files.TaskOutputKind" /> für die Kategorie aus, unter dem diese Datei zu speichern, z. B. <see cref="F:Microsoft.Azure.Batch.Conventions.Files.TaskOutputKind.TaskOutput" /> oder <see cref="F:Microsoft.Azure.Batch.Conventions.Files.TaskOutputKind.TaskLog" />.</span><span class="sxs-lookup"><span data-stu-id="8f1db-146">A <see cref="T:Microsoft.Azure.Batch.Conventions.Files.TaskOutputKind" /> representing the category under which to store this file, for example <see cref="F:Microsoft.Azure.Batch.Conventions.Files.TaskOutputKind.TaskOutput" /> or <see cref="F:Microsoft.Azure.Batch.Conventions.Files.TaskOutputKind.TaskLog" />.</span></span></param>
        <param name="sourcePath"><span data-ttu-id="8f1db-147">Der Pfad der zu speichernden Datei.</span><span class="sxs-lookup"><span data-stu-id="8f1db-147">The path of the file to save.</span></span></param>
        <param name="destinationRelativePath"><span data-ttu-id="8f1db-148">Der Blob-Name, unter dem die Datei gespeichert werden soll.</span><span class="sxs-lookup"><span data-stu-id="8f1db-148">The blob name under which to save the file.</span></span> <span data-ttu-id="8f1db-149">Dies kann eine relative Komponente, wie z. B. "pointclouds/pointcloud_0001.txt" umfassen.</span><span class="sxs-lookup"><span data-stu-id="8f1db-149">This may include a relative component, such as "pointclouds/pointcloud_0001.txt".</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="8f1db-150">Ein <see cref="T:System.Threading.CancellationToken" /> für die Steuerung der Lebensdauer eines asynchronen Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="8f1db-150">A <see cref="T:System.Threading.CancellationToken" /> for controlling the lifetime of the asynchronous operation.</span></span></param>
        <summary>
            <span data-ttu-id="8f1db-151">Speichert die angegebene Datei in den persistenten Speicher.</span><span class="sxs-lookup"><span data-stu-id="8f1db-151">Saves the specified file to persistent storage.</span></span>
            </summary>
        <returns><span data-ttu-id="8f1db-152">Ein <see cref="T:System.Threading.Tasks.Task" />-Element, das den asynchronen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="8f1db-152">A <see cref="T:System.Threading.Tasks.Task" /> that represents the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentNullException"><span data-ttu-id="8f1db-153">Die <paramref name="kind" />, <paramref name="sourcePath" />, oder <paramref name="destinationRelativePath" /> Argument ist null.</span><span class="sxs-lookup"><span data-stu-id="8f1db-153">The <paramref name="kind" />, <paramref name="sourcePath" />, or <paramref name="destinationRelativePath" /> argument is null.</span></span></exception>
        <exception cref="T:System.ArgumentException"><span data-ttu-id="8f1db-154">Die <paramref name="sourcePath" /> oder <paramref name="destinationRelativePath" /> -Argument leer ist.</span><span class="sxs-lookup"><span data-stu-id="8f1db-154">The <paramref name="sourcePath" /> or <paramref name="destinationRelativePath" /> argument is empty.</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName="SaveTextAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task SaveTextAsync (Microsoft.Azure.Batch.Conventions.Files.TaskOutputKind kind, string text, string destinationRelativePath, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task SaveTextAsync(class Microsoft.Azure.Batch.Conventions.Files.TaskOutputKind kind, string text, string destinationRelativePath, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Conventions.Files.TaskOutputStorage.SaveTextAsync(Microsoft.Azure.Batch.Conventions.Files.TaskOutputKind,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.SaveTextAsync : Microsoft.Azure.Batch.Conventions.Files.TaskOutputKind * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="taskOutputStorage.SaveTextAsync (kind, text, destinationRelativePath, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch.Conventions.Files</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Batch.Conventions.Files.TaskOutputStorage/&lt;SaveTextAsync&gt;d__9))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="kind" Type="Microsoft.Azure.Batch.Conventions.Files.TaskOutputKind" />
        <Parameter Name="text" Type="System.String" />
        <Parameter Name="destinationRelativePath" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="kind"><span data-ttu-id="8f1db-155">Ein <see cref="T:Microsoft.Azure.Batch.Conventions.Files.TaskOutputKind" /> für die Kategorie aus, unter dem Speichern der Daten, z. B. <see cref="F:Microsoft.Azure.Batch.Conventions.Files.TaskOutputKind.TaskOutput" /> oder <see cref="F:Microsoft.Azure.Batch.Conventions.Files.TaskOutputKind.TaskLog" />.</span><span class="sxs-lookup"><span data-stu-id="8f1db-155">A <see cref="T:Microsoft.Azure.Batch.Conventions.Files.TaskOutputKind" /> representing the category under which to store this data, for example <see cref="F:Microsoft.Azure.Batch.Conventions.Files.TaskOutputKind.TaskOutput" /> or <see cref="F:Microsoft.Azure.Batch.Conventions.Files.TaskOutputKind.TaskLog" />.</span></span></param>
        <param name="text"><span data-ttu-id="8f1db-156">Der Text gespeichert.</span><span class="sxs-lookup"><span data-stu-id="8f1db-156">The text to save.</span></span></param>
        <param name="destinationRelativePath"><span data-ttu-id="8f1db-157">Der Blob-Name, unter dem den Text gespeichert werden soll.</span><span class="sxs-lookup"><span data-stu-id="8f1db-157">The blob name under which to save the text.</span></span> <span data-ttu-id="8f1db-158">Dies kann eine relative Komponente, wie z. B. "records/widget42.json" umfassen.</span><span class="sxs-lookup"><span data-stu-id="8f1db-158">This may include a relative component, such as "records/widget42.json".</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="8f1db-159">Ein <see cref="T:System.Threading.CancellationToken" /> für die Steuerung der Lebensdauer eines asynchronen Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="8f1db-159">A <see cref="T:System.Threading.CancellationToken" /> for controlling the lifetime of the asynchronous operation.</span></span></param>
        <summary>
            <span data-ttu-id="8f1db-160">Speichert den angegebenen Text in den permanenten Speicher, ohne dass Ihnen die Erstellung eine lokale Datei.</span><span class="sxs-lookup"><span data-stu-id="8f1db-160">Saves the specified text to persistent storage, without requiring you to create a local file.</span></span>
            </summary>
        <returns><span data-ttu-id="8f1db-161">Ein <see cref="T:System.Threading.Tasks.Task" />-Element, das den asynchronen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="8f1db-161">A <see cref="T:System.Threading.Tasks.Task" /> that represents the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentNullException"><span data-ttu-id="8f1db-162">Die <paramref name="kind" />, <paramref name="text" />, oder <paramref name="destinationRelativePath" /> Argument ist null.</span><span class="sxs-lookup"><span data-stu-id="8f1db-162">The <paramref name="kind" />, <paramref name="text" />, or <paramref name="destinationRelativePath" /> argument is null.</span></span></exception>
        <exception cref="T:System.ArgumentException"><span data-ttu-id="8f1db-163">Die <paramref name="destinationRelativePath" /> -Argument leer ist.</span><span class="sxs-lookup"><span data-stu-id="8f1db-163">The <paramref name="destinationRelativePath" /> argument is empty.</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName="SaveTrackedAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Batch.Conventions.Files.ITrackedSaveOperation&gt; SaveTrackedAsync (string relativePath);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Batch.Conventions.Files.ITrackedSaveOperation&gt; SaveTrackedAsync(string relativePath) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Conventions.Files.TaskOutputStorage.SaveTrackedAsync(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function SaveTrackedAsync (relativePath As String) As Task(Of ITrackedSaveOperation)" />
      <MemberSignature Language="F#" Value="member this.SaveTrackedAsync : string -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Batch.Conventions.Files.ITrackedSaveOperation&gt;" Usage="taskOutputStorage.SaveTrackedAsync relativePath" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch.Conventions.Files</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Batch.Conventions.Files.TaskOutputStorage/&lt;SaveTrackedAsync&gt;d__12))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Batch.Conventions.Files.ITrackedSaveOperation&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="relativePath" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="relativePath"><span data-ttu-id="8f1db-164">Der Pfad der Datei relativ zum aktuellen Verzeichnis zu speichern.</span><span class="sxs-lookup"><span data-stu-id="8f1db-164">The path of the file to save, relative to the current directory.</span></span>
            <span data-ttu-id="8f1db-165">Wenn die Datei in einem Unterverzeichnis des aktuellen Verzeichnisses ist, wird der relative Pfad im Blob-Speicher beibehalten.</span><span class="sxs-lookup"><span data-stu-id="8f1db-165">If the file is in a subdirectory of the current directory, the relative path will be preserved in blob storage.</span></span></param>
        <summary>
            <span data-ttu-id="8f1db-166">Speichert die angegebene Datei in den persistenten Speicher als eine <see cref="F:Microsoft.Azure.Batch.Conventions.Files.TaskOutputKind.TaskLog" />, und nachfolgende verfolgt fügt an die Datei und fügt sie an die persistente Kopie zu.</span><span class="sxs-lookup"><span data-stu-id="8f1db-166">Saves the specified file to persistent storage as a <see cref="F:Microsoft.Azure.Batch.Conventions.Files.TaskOutputKind.TaskLog" />, and tracks subsequent appends to the file and appends them to the persistent copy too.</span></span>
            </summary>
        <returns><span data-ttu-id="8f1db-167">Ein <see cref="T:Microsoft.Azure.Batch.Conventions.Files.ITrackedSaveOperation" /> die speichert einer Datei in Blob-Speicher und die Datei wird in regelmäßigen Abständen entleert fügt Sie in das Blob erst verworfen.</span><span class="sxs-lookup"><span data-stu-id="8f1db-167">An <see cref="T:Microsoft.Azure.Batch.Conventions.Files.ITrackedSaveOperation" /> which will save a file to blob storage and will periodically flush file appends to the blob until disposed.</span></span>  <span data-ttu-id="8f1db-168">Wenn freigegeben, fügt allen übrigen werden geleert, um blob-Speicher und weitere Track Datei fügt wird beendet.</span><span class="sxs-lookup"><span data-stu-id="8f1db-168">When disposed, all remaining appends are flushed to blob storage, and further tracking of file appends is stopped.</span></span></returns>
        <remarks>
          <para><span data-ttu-id="8f1db-169">Nachverfolgen von unterstützt nur angefügt.</span><span class="sxs-lookup"><span data-stu-id="8f1db-169">Tracking supports only appends.</span></span> <span data-ttu-id="8f1db-170">Während eine Datei nachverfolgt wird, werden am Ende hinzugefügten Daten im permanenten Speicher angefügt.</span><span class="sxs-lookup"><span data-stu-id="8f1db-170">That is, while a file is being tracked, any data added at the end is appended to the persistent storage.</span></span> <span data-ttu-id="8f1db-171">Änderungen an Daten, die bereits hochgeladen wurden, werden nicht im permanenten Speicher berücksichtigt.</span><span class="sxs-lookup"><span data-stu-id="8f1db-171">Changes to data that has already been uploaded will not be reflected to the persistent store.</span></span> <span data-ttu-id="8f1db-172">Diese Methode ist daher nur für Dateien, wie z. B. Protokolldateien (nicht drehen) für die Verwendung vorgesehen, in dem Daten nur am Ende der Datei hinzugefügt wird.</span><span class="sxs-lookup"><span data-stu-id="8f1db-172">This method is therefore intended for use only with files such as (non-rotating) log files where data is only added at the end of the file.</span></span>
            <span data-ttu-id="8f1db-173">Wenn Sie den gesamten Inhalt einer Datei ändern können, verwenden <see cref="M:Microsoft.Azure.Batch.Conventions.Files.TaskOutputStorage.SaveAsync(Microsoft.Azure.Batch.Conventions.Files.TaskOutputKind,System.String,System.Threading.CancellationToken)" /> und nennen Sie es in regelmäßigen Abständen oder nach jeder Änderung.</span><span class="sxs-lookup"><span data-stu-id="8f1db-173">If the entire contents of a file can change, use <see cref="M:Microsoft.Azure.Batch.Conventions.Files.TaskOutputStorage.SaveAsync(Microsoft.Azure.Batch.Conventions.Files.TaskOutputKind,System.String,System.Threading.CancellationToken)" /> and call it periodically or after each change.</span></span></para>
          <para><span data-ttu-id="8f1db-174">Wenn die Datei außerhalb des aktuellen Verzeichnisses ist, werden von links aus der Verzeichnisstruktur entfernt.</span><span class="sxs-lookup"><span data-stu-id="8f1db-174">If the file is outside the current directory, traversals up the directory tree are removed.</span></span>
            <span data-ttu-id="8f1db-175">Z. B. eine <paramref name="relativePath" /> der ".. \ProcessEnv.cmd"würde als"ProcessEnv.cmd"im Rahmen der Erstellen eines Blob-namens behandelt werden.</span><span class="sxs-lookup"><span data-stu-id="8f1db-175">For example, a <paramref name="relativePath" /> of "..\ProcessEnv.cmd" would be treated as "ProcessEnv.cmd" for the purposes of creating a blob name.</span></span></para>
        </remarks>
        <exception cref="T:System.ArgumentNullException"><span data-ttu-id="8f1db-176">Das <paramref name="relativePath" />-Argument ist null.</span><span class="sxs-lookup"><span data-stu-id="8f1db-176">The <paramref name="relativePath" /> argument is null.</span></span></exception>
        <exception cref="T:System.ArgumentException"><span data-ttu-id="8f1db-177">Die <paramref name="relativePath" /> Argument ist ein absoluter Pfad oder ist leer.</span><span class="sxs-lookup"><span data-stu-id="8f1db-177">The <paramref name="relativePath" /> argument is an absolute path, or is empty.</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName="SaveTrackedAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Batch.Conventions.Files.ITrackedSaveOperation&gt; SaveTrackedAsync (Microsoft.Azure.Batch.Conventions.Files.TaskOutputKind kind, string sourcePath, string destinationRelativePath, TimeSpan flushInterval);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Batch.Conventions.Files.ITrackedSaveOperation&gt; SaveTrackedAsync(class Microsoft.Azure.Batch.Conventions.Files.TaskOutputKind kind, string sourcePath, string destinationRelativePath, valuetype System.TimeSpan flushInterval) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Conventions.Files.TaskOutputStorage.SaveTrackedAsync(Microsoft.Azure.Batch.Conventions.Files.TaskOutputKind,System.String,System.String,System.TimeSpan)" />
      <MemberSignature Language="VB.NET" Value="Public Function SaveTrackedAsync (kind As TaskOutputKind, sourcePath As String, destinationRelativePath As String, flushInterval As TimeSpan) As Task(Of ITrackedSaveOperation)" />
      <MemberSignature Language="F#" Value="member this.SaveTrackedAsync : Microsoft.Azure.Batch.Conventions.Files.TaskOutputKind * string * string * TimeSpan -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Batch.Conventions.Files.ITrackedSaveOperation&gt;" Usage="taskOutputStorage.SaveTrackedAsync (kind, sourcePath, destinationRelativePath, flushInterval)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch.Conventions.Files</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Batch.Conventions.Files.TaskOutputStorage/&lt;SaveTrackedAsync&gt;d__13))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Batch.Conventions.Files.ITrackedSaveOperation&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="kind" Type="Microsoft.Azure.Batch.Conventions.Files.TaskOutputKind" />
        <Parameter Name="sourcePath" Type="System.String" />
        <Parameter Name="destinationRelativePath" Type="System.String" />
        <Parameter Name="flushInterval" Type="System.TimeSpan" />
      </Parameters>
      <Docs>
        <param name="kind"><span data-ttu-id="8f1db-178">Ein <see cref="T:Microsoft.Azure.Batch.Conventions.Files.TaskOutputKind" /> für die Kategorie aus, unter dem diese Datei zu speichern, z. B. <see cref="F:Microsoft.Azure.Batch.Conventions.Files.TaskOutputKind.TaskOutput" /> oder <see cref="F:Microsoft.Azure.Batch.Conventions.Files.TaskOutputKind.TaskLog" />.</span><span class="sxs-lookup"><span data-stu-id="8f1db-178">A <see cref="T:Microsoft.Azure.Batch.Conventions.Files.TaskOutputKind" /> representing the category under which to store this file, for example <see cref="F:Microsoft.Azure.Batch.Conventions.Files.TaskOutputKind.TaskOutput" /> or <see cref="F:Microsoft.Azure.Batch.Conventions.Files.TaskOutputKind.TaskLog" />.</span></span></param>
        <param name="sourcePath"><span data-ttu-id="8f1db-179">Der Pfad der zu speichernden Datei.</span><span class="sxs-lookup"><span data-stu-id="8f1db-179">The path of the file to save.</span></span></param>
        <param name="destinationRelativePath"><span data-ttu-id="8f1db-180">Der Blob-Name, unter dem die Datei gespeichert werden soll.</span><span class="sxs-lookup"><span data-stu-id="8f1db-180">The blob name under which to save the file.</span></span> <span data-ttu-id="8f1db-181">Dies kann eine relative Komponente, wie z. B. "pointclouds/pointcloud_0001.txt" umfassen.</span><span class="sxs-lookup"><span data-stu-id="8f1db-181">This may include a relative component, such as "pointclouds/pointcloud_0001.txt".</span></span></param>
        <param name="flushInterval"><span data-ttu-id="8f1db-182">Das Intervall, in dem leeren fügt in den persistenten Speicher.</span><span class="sxs-lookup"><span data-stu-id="8f1db-182">The interval at which to flush appends to persistent storage.</span></span></param>
        <summary>
            <span data-ttu-id="8f1db-183">Speichert die angegebene Datei permanenten Speicher und verfolgt nachfolgende fügt an die Datei und fügt sie die persistente Kopie zu.</span><span class="sxs-lookup"><span data-stu-id="8f1db-183">Saves the specified file to persistent storage, and tracks subsequent appends to the file and appends them to the persistent copy too.</span></span>
            </summary>
        <returns><span data-ttu-id="8f1db-184">Ein <see cref="T:Microsoft.Azure.Batch.Conventions.Files.ITrackedSaveOperation" /> die speichert einer Datei in Blob-Speicher und die Datei wird in regelmäßigen Abständen entleert fügt Sie in das Blob erst verworfen.</span><span class="sxs-lookup"><span data-stu-id="8f1db-184">An <see cref="T:Microsoft.Azure.Batch.Conventions.Files.ITrackedSaveOperation" /> which will save a file to blob storage and will periodically flush file appends to the blob until disposed.</span></span>  <span data-ttu-id="8f1db-185">Wenn freigegeben, fügt allen übrigen werden geleert, um blob-Speicher und weitere Track Datei fügt wird beendet.</span><span class="sxs-lookup"><span data-stu-id="8f1db-185">When disposed, all remaining appends are flushed to blob storage, and further tracking of file appends is stopped.</span></span></returns>
        <remarks>
          <para><span data-ttu-id="8f1db-186">Nachverfolgen von unterstützt nur angefügt.</span><span class="sxs-lookup"><span data-stu-id="8f1db-186">Tracking supports only appends.</span></span> <span data-ttu-id="8f1db-187">Während eine Datei nachverfolgt wird, werden am Ende hinzugefügten Daten im permanenten Speicher angefügt.</span><span class="sxs-lookup"><span data-stu-id="8f1db-187">That is, while a file is being tracked, any data added at the end is appended to the persistent storage.</span></span> <span data-ttu-id="8f1db-188">Änderungen an Daten, die bereits hochgeladen wurden, werden nicht im permanenten Speicher berücksichtigt.</span><span class="sxs-lookup"><span data-stu-id="8f1db-188">Changes to data that has already been uploaded will not be reflected to the persistent store.</span></span> <span data-ttu-id="8f1db-189">Diese Methode ist daher nur für Dateien, wie z. B. Protokolldateien (nicht drehen) für die Verwendung vorgesehen, in dem Daten nur am Ende der Datei hinzugefügt wird.</span><span class="sxs-lookup"><span data-stu-id="8f1db-189">This method is therefore intended for use only with files such as (non-rotating) log files where data is only added at the end of the file.</span></span>
            <span data-ttu-id="8f1db-190">Wenn Sie den gesamten Inhalt einer Datei ändern können, verwenden <see cref="M:Microsoft.Azure.Batch.Conventions.Files.TaskOutputStorage.SaveAsync(Microsoft.Azure.Batch.Conventions.Files.TaskOutputKind,System.String,System.String,System.Threading.CancellationToken)" /> und nennen Sie es in regelmäßigen Abständen oder nach jeder Änderung.</span><span class="sxs-lookup"><span data-stu-id="8f1db-190">If the entire contents of a file can change, use <see cref="M:Microsoft.Azure.Batch.Conventions.Files.TaskOutputStorage.SaveAsync(Microsoft.Azure.Batch.Conventions.Files.TaskOutputKind,System.String,System.String,System.Threading.CancellationToken)" /> and call it periodically or after each change.</span></span></para>
        </remarks>
        <exception cref="T:System.ArgumentNullException"><span data-ttu-id="8f1db-191">Die <paramref name="kind" />, <paramref name="sourcePath" />, oder <paramref name="destinationRelativePath" /> Argument ist null.</span><span class="sxs-lookup"><span data-stu-id="8f1db-191">The <paramref name="kind" />, <paramref name="sourcePath" />, or <paramref name="destinationRelativePath" /> argument is null.</span></span></exception>
        <exception cref="T:System.ArgumentException"><span data-ttu-id="8f1db-192">Die <paramref name="sourcePath" /> oder <paramref name="destinationRelativePath" /> -Argument leer ist.</span><span class="sxs-lookup"><span data-stu-id="8f1db-192">The <paramref name="sourcePath" /> or <paramref name="destinationRelativePath" /> argument is empty.</span></span></exception>
      </Docs>
    </Member>
  </Members>
</Type>