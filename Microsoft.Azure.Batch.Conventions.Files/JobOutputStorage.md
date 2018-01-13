<Type Name="JobOutputStorage" FullName="Microsoft.Azure.Batch.Conventions.Files.JobOutputStorage">
  <TypeSignature Language="C#" Value="public class JobOutputStorage" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit JobOutputStorage extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Batch.Conventions.Files.JobOutputStorage" />
  <TypeSignature Language="VB.NET" Value="Public Class JobOutputStorage" />
  <TypeSignature Language="F#" Value="type JobOutputStorage = class" />
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
            <span data-ttu-id="08fc4-101">Stellt permanenten Speicher für die Ausgaben von einem Azure Batch-Auftrag dar.</span><span class="sxs-lookup"><span data-stu-id="08fc4-101">Represents persistent storage for the outputs of an Azure Batch job.</span></span>
            </summary>
    <remarks>
            <span data-ttu-id="08fc4-102">Auftragsausgaben finden Sie in Ausgabedaten, die logisch mit einer bestimmten Aufgabe, anstatt das gesamte Projekt verknüpft ist.</span><span class="sxs-lookup"><span data-stu-id="08fc4-102">Job outputs refer to output data logically associated with the entire job, rather than a particular task.</span></span> <span data-ttu-id="08fc4-103">Z. B. in einem Film-Rendering-Auftrag, wenn eine Aufgabe in einen Film alle Frames kombiniert, die logisch eine Auftragsausgabe wäre.</span><span class="sxs-lookup"><span data-stu-id="08fc4-103">For example, in a movie rendering job, if a task combined all the frames into a movie, that would logically be a job output.</span></span> <span data-ttu-id="08fc4-104">Der Zweck der categorising einer Ausgabe wie "Auftragsausgabe" ist, um den Client zu speichern, müssen Sie wissen, welche Aufgabe erzeugt es wurde.</span><span class="sxs-lookup"><span data-stu-id="08fc4-104">The purpose of categorising an output as a 'job' output is to save the client from having to know which task produced it.</span></span>
            </remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public JobOutputStorage (Uri jobOutputContainerUri);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.Uri jobOutputContainerUri) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Conventions.Files.JobOutputStorage.#ctor(System.Uri)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (jobOutputContainerUri As Uri)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Batch.Conventions.Files.JobOutputStorage : Uri -&gt; Microsoft.Azure.Batch.Conventions.Files.JobOutputStorage" Usage="new Microsoft.Azure.Batch.Conventions.Files.JobOutputStorage jobOutputContainerUri" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch.Conventions.Files</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="jobOutputContainerUri" Type="System.Uri" />
      </Parameters>
      <Docs>
        <param name="jobOutputContainerUri"><span data-ttu-id="08fc4-105">Gibt die URL im Azure-Speicher des Blob-Containers für den Auftrag aus.</span><span class="sxs-lookup"><span data-stu-id="08fc4-105">The URL in Azure storage of the blob container to use for job outputs.</span></span> <span data-ttu-id="08fc4-106">Diese URL muss eine SAS (Shared Access Signature) mit dem Gewähren des Zugriffs auf den Container enthalten, oder der Container muss öffentlich sein.</span><span class="sxs-lookup"><span data-stu-id="08fc4-106">This URL must contain a SAS (Shared Access Signature) granting access to the container, or the container must be public.</span></span></param>
        <summary>
            <span data-ttu-id="08fc4-107">Initialisiert eine neue Instanz der dem <see cref="T:Microsoft.Azure.Batch.Conventions.Files.JobOutputStorage" /> Klasse von einer URL, die der Auftrag Ausgabecontainer darstellt.</span><span class="sxs-lookup"><span data-stu-id="08fc4-107">Initializes a new instance of the <see cref="T:Microsoft.Azure.Batch.Conventions.Files.JobOutputStorage" /> class from a URL representing the job output container.</span></span>
            </summary>
        <remarks><span data-ttu-id="08fc4-108">Der Container muss bereits vorhanden sein; die Klasse JobOutputStorage wird nicht für Sie erstellt.</span><span class="sxs-lookup"><span data-stu-id="08fc4-108">The container must already exist; the JobOutputStorage class does not create it for you.</span></span></remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public JobOutputStorage (Microsoft.WindowsAzure.Storage.CloudStorageAccount storageAccount, string jobId);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class Microsoft.WindowsAzure.Storage.CloudStorageAccount storageAccount, string jobId) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Conventions.Files.JobOutputStorage.#ctor(Microsoft.WindowsAzure.Storage.CloudStorageAccount,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (storageAccount As CloudStorageAccount, jobId As String)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Batch.Conventions.Files.JobOutputStorage : Microsoft.WindowsAzure.Storage.CloudStorageAccount * string -&gt; Microsoft.Azure.Batch.Conventions.Files.JobOutputStorage" Usage="new Microsoft.Azure.Batch.Conventions.Files.JobOutputStorage (storageAccount, jobId)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch.Conventions.Files</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="storageAccount" Type="Microsoft.WindowsAzure.Storage.CloudStorageAccount" />
        <Parameter Name="jobId" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="storageAccount"><span data-ttu-id="08fc4-109">Das Speicherkonto mit der Azure Batch-Konto verknüpft ist.</span><span class="sxs-lookup"><span data-stu-id="08fc4-109">The storage account linked to the Azure Batch account.</span></span></param>
        <param name="jobId"><span data-ttu-id="08fc4-110">Die Id des Azure Batch-Auftrags.</span><span class="sxs-lookup"><span data-stu-id="08fc4-110">The id of the Azure Batch job.</span></span></param>
        <summary>
            <span data-ttu-id="08fc4-111">Initialisiert eine neue Instanz der dem <see cref="T:Microsoft.Azure.Batch.Conventions.Files.JobOutputStorage" /> Klasse über eine Speicher-Konto und die Auftrags-Id.</span><span class="sxs-lookup"><span data-stu-id="08fc4-111">Initializes a new instance of the <see cref="T:Microsoft.Azure.Batch.Conventions.Files.JobOutputStorage" /> class from a storage account and job id.</span></span>
            </summary>
        <remarks><span data-ttu-id="08fc4-112">Der Auftrag Ausgabecontainer muss bereits vorhanden sein; die Klasse JobOutputStorage wird nicht für Sie erstellt.</span><span class="sxs-lookup"><span data-stu-id="08fc4-112">The job output container must already exist; the JobOutputStorage class does not create it for you.</span></span></remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public JobOutputStorage (Uri jobOutputContainerUri, Microsoft.WindowsAzure.Storage.RetryPolicies.IRetryPolicy storageRetryPolicy);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.Uri jobOutputContainerUri, class Microsoft.WindowsAzure.Storage.RetryPolicies.IRetryPolicy storageRetryPolicy) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Conventions.Files.JobOutputStorage.#ctor(System.Uri,Microsoft.WindowsAzure.Storage.RetryPolicies.IRetryPolicy)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (jobOutputContainerUri As Uri, storageRetryPolicy As IRetryPolicy)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Batch.Conventions.Files.JobOutputStorage : Uri * Microsoft.WindowsAzure.Storage.RetryPolicies.IRetryPolicy -&gt; Microsoft.Azure.Batch.Conventions.Files.JobOutputStorage" Usage="new Microsoft.Azure.Batch.Conventions.Files.JobOutputStorage (jobOutputContainerUri, storageRetryPolicy)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch.Conventions.Files</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="jobOutputContainerUri" Type="System.Uri" />
        <Parameter Name="storageRetryPolicy" Type="Microsoft.WindowsAzure.Storage.RetryPolicies.IRetryPolicy" />
      </Parameters>
      <Docs>
        <param name="jobOutputContainerUri"><span data-ttu-id="08fc4-113">Gibt die URL im Azure-Speicher des Blob-Containers für den Auftrag aus.</span><span class="sxs-lookup"><span data-stu-id="08fc4-113">The URL in Azure storage of the blob container to use for job outputs.</span></span> <span data-ttu-id="08fc4-114">Diese URL muss eine SAS (Shared Access Signature) mit dem Gewähren des Zugriffs auf den Container enthalten, oder der Container muss öffentlich sein.</span><span class="sxs-lookup"><span data-stu-id="08fc4-114">This URL must contain a SAS (Shared Access Signature) granting access to the container, or the container must be public.</span></span></param>
        <param name="storageRetryPolicy"><span data-ttu-id="08fc4-115">Die wiederholungsrichtlinie für speicheranforderungen.</span><span class="sxs-lookup"><span data-stu-id="08fc4-115">The retry policy for storage requests.</span></span></param>
        <summary>
            <span data-ttu-id="08fc4-116">Initialisiert eine neue Instanz der dem <see cref="T:Microsoft.Azure.Batch.Conventions.Files.JobOutputStorage" /> Klasse von einer URL, die der Auftrag Ausgabecontainer darstellt.</span><span class="sxs-lookup"><span data-stu-id="08fc4-116">Initializes a new instance of the <see cref="T:Microsoft.Azure.Batch.Conventions.Files.JobOutputStorage" /> class from a URL representing the job output container.</span></span>
            </summary>
        <remarks><span data-ttu-id="08fc4-117">Der Container muss bereits vorhanden sein; die Klasse JobOutputStorage wird nicht für Sie erstellt.</span><span class="sxs-lookup"><span data-stu-id="08fc4-117">The container must already exist; the JobOutputStorage class does not create it for you.</span></span></remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public JobOutputStorage (Microsoft.WindowsAzure.Storage.CloudStorageAccount storageAccount, string jobId, Microsoft.WindowsAzure.Storage.RetryPolicies.IRetryPolicy storageRetryPolicy);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class Microsoft.WindowsAzure.Storage.CloudStorageAccount storageAccount, string jobId, class Microsoft.WindowsAzure.Storage.RetryPolicies.IRetryPolicy storageRetryPolicy) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Conventions.Files.JobOutputStorage.#ctor(Microsoft.WindowsAzure.Storage.CloudStorageAccount,System.String,Microsoft.WindowsAzure.Storage.RetryPolicies.IRetryPolicy)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (storageAccount As CloudStorageAccount, jobId As String, storageRetryPolicy As IRetryPolicy)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Batch.Conventions.Files.JobOutputStorage : Microsoft.WindowsAzure.Storage.CloudStorageAccount * string * Microsoft.WindowsAzure.Storage.RetryPolicies.IRetryPolicy -&gt; Microsoft.Azure.Batch.Conventions.Files.JobOutputStorage" Usage="new Microsoft.Azure.Batch.Conventions.Files.JobOutputStorage (storageAccount, jobId, storageRetryPolicy)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch.Conventions.Files</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="storageAccount" Type="Microsoft.WindowsAzure.Storage.CloudStorageAccount" />
        <Parameter Name="jobId" Type="System.String" />
        <Parameter Name="storageRetryPolicy" Type="Microsoft.WindowsAzure.Storage.RetryPolicies.IRetryPolicy" />
      </Parameters>
      <Docs>
        <param name="storageAccount"><span data-ttu-id="08fc4-118">Das Speicherkonto mit der Azure Batch-Konto verknüpft ist.</span><span class="sxs-lookup"><span data-stu-id="08fc4-118">The storage account linked to the Azure Batch account.</span></span></param>
        <param name="jobId"><span data-ttu-id="08fc4-119">Die Id des Azure Batch-Auftrags.</span><span class="sxs-lookup"><span data-stu-id="08fc4-119">The id of the Azure Batch job.</span></span></param>
        <param name="storageRetryPolicy"><span data-ttu-id="08fc4-120">Die wiederholungsrichtlinie für speicheranforderungen.</span><span class="sxs-lookup"><span data-stu-id="08fc4-120">The retry policy for storage requests.</span></span></param>
        <summary>
            <span data-ttu-id="08fc4-121">Initialisiert eine neue Instanz der dem <see cref="T:Microsoft.Azure.Batch.Conventions.Files.JobOutputStorage" /> Klasse über eine Speicher-Konto und die Auftrags-Id.</span><span class="sxs-lookup"><span data-stu-id="08fc4-121">Initializes a new instance of the <see cref="T:Microsoft.Azure.Batch.Conventions.Files.JobOutputStorage" /> class from a storage account and job id.</span></span>
            </summary>
        <remarks><span data-ttu-id="08fc4-122">Der Auftrag Ausgabecontainer muss bereits vorhanden sein; die Klasse JobOutputStorage wird nicht für Sie erstellt.</span><span class="sxs-lookup"><span data-stu-id="08fc4-122">The job output container must already exist; the JobOutputStorage class does not create it for you.</span></span></remarks>
      </Docs>
    </Member>
    <Member MemberName="GetOutputAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Batch.Conventions.Files.OutputFileReference&gt; GetOutputAsync (Microsoft.Azure.Batch.Conventions.Files.JobOutputKind kind, string filePath, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Batch.Conventions.Files.OutputFileReference&gt; GetOutputAsync(class Microsoft.Azure.Batch.Conventions.Files.JobOutputKind kind, string filePath, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Conventions.Files.JobOutputStorage.GetOutputAsync(Microsoft.Azure.Batch.Conventions.Files.JobOutputKind,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.GetOutputAsync : Microsoft.Azure.Batch.Conventions.Files.JobOutputKind * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Batch.Conventions.Files.OutputFileReference&gt;" Usage="jobOutputStorage.GetOutputAsync (kind, filePath, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch.Conventions.Files</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Batch.Conventions.Files.JobOutputStorage/&lt;GetOutputAsync&gt;d__10))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Batch.Conventions.Files.OutputFileReference&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="kind" Type="Microsoft.Azure.Batch.Conventions.Files.JobOutputKind" />
        <Parameter Name="filePath" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="kind"><span data-ttu-id="08fc4-123">Ein <see cref="T:Microsoft.Azure.Batch.Conventions.Files.JobOutputKind" /> für die Kategorie der Ausgabe abrufen, z. B. <see cref="F:Microsoft.Azure.Batch.Conventions.Files.JobOutputKind.JobOutput" /> oder <see cref="F:Microsoft.Azure.Batch.Conventions.Files.JobOutputKind.JobPreview" />.</span><span class="sxs-lookup"><span data-stu-id="08fc4-123">A <see cref="T:Microsoft.Azure.Batch.Conventions.Files.JobOutputKind" /> representing the category of the output to retrieve, for example <see cref="F:Microsoft.Azure.Batch.Conventions.Files.JobOutputKind.JobOutput" /> or <see cref="F:Microsoft.Azure.Batch.Conventions.Files.JobOutputKind.JobPreview" />.</span></span></param>
        <param name="filePath"><span data-ttu-id="08fc4-124">Der Pfad, unter dem die Ausgabe im Blob-Speicher beibehalten wurde.</span><span class="sxs-lookup"><span data-stu-id="08fc4-124">The path under which the output was persisted in blob storage.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="08fc4-125">Ein <see cref="T:System.Threading.CancellationToken" /> für die Steuerung der Lebensdauer eines asynchronen Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="08fc4-125">A <see cref="T:System.Threading.CancellationToken" /> for controlling the lifetime of the asynchronous operation.</span></span></param>
        <summary>
            <span data-ttu-id="08fc4-126">Ruft eine Auftragsausgabe aus dem Azure-Blob-Speicher von der Art und den Pfad ab.</span><span class="sxs-lookup"><span data-stu-id="08fc4-126">Retrieves a job output from Azure blob storage by kind and path.</span></span>
            </summary>
        <returns><span data-ttu-id="08fc4-127">Ein Verweis auf die angeforderte Datei im Azure-Blob-Speicher.</span><span class="sxs-lookup"><span data-stu-id="08fc4-127">A reference to the requested file in Azure blob storage.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListOutputs">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.Conventions.Files.OutputFileReference&gt; ListOutputs (Microsoft.Azure.Batch.Conventions.Files.JobOutputKind kind);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Batch.Conventions.Files.OutputFileReference&gt; ListOutputs(class Microsoft.Azure.Batch.Conventions.Files.JobOutputKind kind) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Conventions.Files.JobOutputStorage.ListOutputs(Microsoft.Azure.Batch.Conventions.Files.JobOutputKind)" />
      <MemberSignature Language="VB.NET" Value="Public Function ListOutputs (kind As JobOutputKind) As IEnumerable(Of OutputFileReference)" />
      <MemberSignature Language="F#" Value="member this.ListOutputs : Microsoft.Azure.Batch.Conventions.Files.JobOutputKind -&gt; seq&lt;Microsoft.Azure.Batch.Conventions.Files.OutputFileReference&gt;" Usage="jobOutputStorage.ListOutputs kind" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch.Conventions.Files</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.Conventions.Files.OutputFileReference&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="kind" Type="Microsoft.Azure.Batch.Conventions.Files.JobOutputKind" />
      </Parameters>
      <Docs>
        <param name="kind"><span data-ttu-id="08fc4-128">Ein <see cref="T:Microsoft.Azure.Batch.Conventions.Files.JobOutputKind" /> für die Kategorie der Ausgaben auflisten, z. B. <see cref="F:Microsoft.Azure.Batch.Conventions.Files.JobOutputKind.JobOutput" /> oder <see cref="F:Microsoft.Azure.Batch.Conventions.Files.JobOutputKind.JobPreview" />.</span><span class="sxs-lookup"><span data-stu-id="08fc4-128">A <see cref="T:Microsoft.Azure.Batch.Conventions.Files.JobOutputKind" /> representing the category of outputs to list, for example <see cref="F:Microsoft.Azure.Batch.Conventions.Files.JobOutputKind.JobOutput" /> or <see cref="F:Microsoft.Azure.Batch.Conventions.Files.JobOutputKind.JobPreview" />.</span></span></param>
        <summary>
            <span data-ttu-id="08fc4-129">Listet die auftragsausgaben der angegebenen Art an.</span><span class="sxs-lookup"><span data-stu-id="08fc4-129">Lists the job outputs of the specified kind.</span></span>
            </summary>
        <returns><span data-ttu-id="08fc4-130">Eine Liste der persistenten auftragsausgaben der angegebenen Art.</span><span class="sxs-lookup"><span data-stu-id="08fc4-130">A list of persisted job outputs of the specified kind.</span></span></returns>
        <remarks><span data-ttu-id="08fc4-131">Die Liste wird aus dem Azure-Blob-Speicher verzögert abgerufen, wenn diese aufgelistet wird.</span><span class="sxs-lookup"><span data-stu-id="08fc4-131">The list is retrieved lazily from Azure blob storage when it is enumerated.</span></span></remarks>
      </Docs>
    </Member>
    <Member MemberName="SaveAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task SaveAsync (Microsoft.Azure.Batch.Conventions.Files.JobOutputKind kind, string relativePath, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task SaveAsync(class Microsoft.Azure.Batch.Conventions.Files.JobOutputKind kind, string relativePath, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Conventions.Files.JobOutputStorage.SaveAsync(Microsoft.Azure.Batch.Conventions.Files.JobOutputKind,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.SaveAsync : Microsoft.Azure.Batch.Conventions.Files.JobOutputKind * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="jobOutputStorage.SaveAsync (kind, relativePath, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch.Conventions.Files</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Batch.Conventions.Files.JobOutputStorage/&lt;SaveAsync&gt;d__6))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="kind" Type="Microsoft.Azure.Batch.Conventions.Files.JobOutputKind" />
        <Parameter Name="relativePath" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="kind"><span data-ttu-id="08fc4-132">Ein <see cref="T:Microsoft.Azure.Batch.Conventions.Files.JobOutputKind" /> für die Kategorie aus, unter dem diese Datei zu speichern, z. B. <see cref="F:Microsoft.Azure.Batch.Conventions.Files.JobOutputKind.JobOutput" /> oder <see cref="F:Microsoft.Azure.Batch.Conventions.Files.JobOutputKind.JobPreview" />.</span><span class="sxs-lookup"><span data-stu-id="08fc4-132">A <see cref="T:Microsoft.Azure.Batch.Conventions.Files.JobOutputKind" /> representing the category under which to store this file, for example <see cref="F:Microsoft.Azure.Batch.Conventions.Files.JobOutputKind.JobOutput" /> or <see cref="F:Microsoft.Azure.Batch.Conventions.Files.JobOutputKind.JobPreview" />.</span></span></param>
        <param name="relativePath"><span data-ttu-id="08fc4-133">Der Pfad der Datei relativ zum aktuellen Verzeichnis zu speichern.</span><span class="sxs-lookup"><span data-stu-id="08fc4-133">The path of the file to save, relative to the current directory.</span></span>
            <span data-ttu-id="08fc4-134">Wenn die Datei in einem Unterverzeichnis des aktuellen Verzeichnisses ist, wird der relative Pfad im Blob-Speicher beibehalten.</span><span class="sxs-lookup"><span data-stu-id="08fc4-134">If the file is in a subdirectory of the current directory, the relative path will be preserved in blob storage.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="08fc4-135">Ein <see cref="T:System.Threading.CancellationToken" /> für die Steuerung der Lebensdauer eines asynchronen Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="08fc4-135">A <see cref="T:System.Threading.CancellationToken" /> for controlling the lifetime of the asynchronous operation.</span></span></param>
        <summary>
            <span data-ttu-id="08fc4-136">Speichert die angegebene Datei in den persistenten Speicher.</span><span class="sxs-lookup"><span data-stu-id="08fc4-136">Saves the specified file to persistent storage.</span></span>
            </summary>
        <returns><span data-ttu-id="08fc4-137">Ein <see cref="T:System.Threading.Tasks.Task" />-Element, das den asynchronen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="08fc4-137">A <see cref="T:System.Threading.Tasks.Task" /> that represents the asynchronous operation.</span></span></returns>
        <remarks><span data-ttu-id="08fc4-138">Wenn die Datei außerhalb des aktuellen Verzeichnisses ist, werden von links aus der Verzeichnisstruktur entfernt.</span><span class="sxs-lookup"><span data-stu-id="08fc4-138">If the file is outside the current directory, traversals up the directory tree are removed.</span></span>
            <span data-ttu-id="08fc4-139">Z. B. eine <paramref name="relativePath" /> der ".. \ProcessEnv.cmd"würde als"ProcessEnv.cmd"im Rahmen der Erstellen eines Blob-namens behandelt werden.</span><span class="sxs-lookup"><span data-stu-id="08fc4-139">For example, a <paramref name="relativePath" /> of "..\ProcessEnv.cmd" would be treated as "ProcessEnv.cmd" for the purposes of creating a blob name.</span></span></remarks>
        <exception cref="T:System.ArgumentNullException"><span data-ttu-id="08fc4-140">Die <paramref name="kind" /> oder <paramref name="relativePath" /> Argument ist null.</span><span class="sxs-lookup"><span data-stu-id="08fc4-140">The <paramref name="kind" /> or <paramref name="relativePath" /> argument is null.</span></span></exception>
        <exception cref="T:System.ArgumentException"><span data-ttu-id="08fc4-141">Die <paramref name="relativePath" /> Argument ist ein absoluter Pfad oder ist leer.</span><span class="sxs-lookup"><span data-stu-id="08fc4-141">The <paramref name="relativePath" /> argument is an absolute path, or is empty.</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName="SaveAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task SaveAsync (Microsoft.Azure.Batch.Conventions.Files.JobOutputKind kind, string sourcePath, string destinationRelativePath, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task SaveAsync(class Microsoft.Azure.Batch.Conventions.Files.JobOutputKind kind, string sourcePath, string destinationRelativePath, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Conventions.Files.JobOutputStorage.SaveAsync(Microsoft.Azure.Batch.Conventions.Files.JobOutputKind,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.SaveAsync : Microsoft.Azure.Batch.Conventions.Files.JobOutputKind * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="jobOutputStorage.SaveAsync (kind, sourcePath, destinationRelativePath, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch.Conventions.Files</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Batch.Conventions.Files.JobOutputStorage/&lt;SaveAsync&gt;d__8))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="kind" Type="Microsoft.Azure.Batch.Conventions.Files.JobOutputKind" />
        <Parameter Name="sourcePath" Type="System.String" />
        <Parameter Name="destinationRelativePath" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="kind"><span data-ttu-id="08fc4-142">Ein <see cref="T:Microsoft.Azure.Batch.Conventions.Files.JobOutputKind" /> für die Kategorie aus, unter dem diese Datei zu speichern, z. B. <see cref="F:Microsoft.Azure.Batch.Conventions.Files.JobOutputKind.JobOutput" /> oder <see cref="F:Microsoft.Azure.Batch.Conventions.Files.JobOutputKind.JobPreview" />.</span><span class="sxs-lookup"><span data-stu-id="08fc4-142">A <see cref="T:Microsoft.Azure.Batch.Conventions.Files.JobOutputKind" /> representing the category under which to store this file, for example <see cref="F:Microsoft.Azure.Batch.Conventions.Files.JobOutputKind.JobOutput" /> or <see cref="F:Microsoft.Azure.Batch.Conventions.Files.JobOutputKind.JobPreview" />.</span></span></param>
        <param name="sourcePath"><span data-ttu-id="08fc4-143">Der Pfad der zu speichernden Datei.</span><span class="sxs-lookup"><span data-stu-id="08fc4-143">The path of the file to save.</span></span></param>
        <param name="destinationRelativePath"><span data-ttu-id="08fc4-144">Der Blob-Name, unter dem die Datei gespeichert werden soll.</span><span class="sxs-lookup"><span data-stu-id="08fc4-144">The blob name under which to save the file.</span></span> <span data-ttu-id="08fc4-145">Dies kann eine relative Komponente, wie z. B. "pointclouds/pointcloud_0001.txt" umfassen.</span><span class="sxs-lookup"><span data-stu-id="08fc4-145">This may include a relative component, such as "pointclouds/pointcloud_0001.txt".</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="08fc4-146">Ein <see cref="T:System.Threading.CancellationToken" /> für die Steuerung der Lebensdauer eines asynchronen Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="08fc4-146">A <see cref="T:System.Threading.CancellationToken" /> for controlling the lifetime of the asynchronous operation.</span></span></param>
        <summary>
            <span data-ttu-id="08fc4-147">Speichert die angegebene Datei in den persistenten Speicher.</span><span class="sxs-lookup"><span data-stu-id="08fc4-147">Saves the specified file to persistent storage.</span></span>
            </summary>
        <returns><span data-ttu-id="08fc4-148">Ein <see cref="T:System.Threading.Tasks.Task" />-Element, das den asynchronen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="08fc4-148">A <see cref="T:System.Threading.Tasks.Task" /> that represents the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentNullException"><span data-ttu-id="08fc4-149">Die <paramref name="kind" />, <paramref name="sourcePath" />, oder <paramref name="destinationRelativePath" /> Argument ist null.</span><span class="sxs-lookup"><span data-stu-id="08fc4-149">The <paramref name="kind" />, <paramref name="sourcePath" />, or <paramref name="destinationRelativePath" /> argument is null.</span></span></exception>
        <exception cref="T:System.ArgumentException"><span data-ttu-id="08fc4-150">Die <paramref name="sourcePath" /> oder <paramref name="destinationRelativePath" /> -Argument leer ist.</span><span class="sxs-lookup"><span data-stu-id="08fc4-150">The <paramref name="sourcePath" /> or <paramref name="destinationRelativePath" /> argument is empty.</span></span></exception>
      </Docs>
    </Member>
  </Members>
</Type>