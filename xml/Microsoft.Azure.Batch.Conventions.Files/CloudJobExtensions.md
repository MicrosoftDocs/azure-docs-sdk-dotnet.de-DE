<Type Name="CloudJobExtensions" FullName="Microsoft.Azure.Batch.Conventions.Files.CloudJobExtensions">
  <TypeSignature Language="C#" Value="public static class CloudJobExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit CloudJobExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Batch.Conventions.Files.CloudJobExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module CloudJobExtensions" />
  <TypeSignature Language="F#" Value="type CloudJobExtensions = class" />
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
            <span data-ttu-id="f8618-101">Stellt Methoden zum Arbeiten mit Ausgaben von einem <see cref="T:Microsoft.Azure.Batch.CloudJob" />.</span><span class="sxs-lookup"><span data-stu-id="f8618-101">Provides methods for working with the outputs of a <see cref="T:Microsoft.Azure.Batch.CloudJob" />.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="GetOutputStorageContainerUrl">
      <MemberSignature Language="C#" Value="public static string GetOutputStorageContainerUrl (this Microsoft.Azure.Batch.CloudJob job, Microsoft.WindowsAzure.Storage.CloudStorageAccount storageAccount);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig string GetOutputStorageContainerUrl(class Microsoft.Azure.Batch.CloudJob job, class Microsoft.WindowsAzure.Storage.CloudStorageAccount storageAccount) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Conventions.Files.CloudJobExtensions.GetOutputStorageContainerUrl(Microsoft.Azure.Batch.CloudJob,Microsoft.WindowsAzure.Storage.CloudStorageAccount)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function GetOutputStorageContainerUrl (job As CloudJob, storageAccount As CloudStorageAccount) As String" />
      <MemberSignature Language="F#" Value="static member GetOutputStorageContainerUrl : Microsoft.Azure.Batch.CloudJob * Microsoft.WindowsAzure.Storage.CloudStorageAccount -&gt; string" Usage="Microsoft.Azure.Batch.Conventions.Files.CloudJobExtensions.GetOutputStorageContainerUrl (job, storageAccount)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch.Conventions.Files</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="job" Type="Microsoft.Azure.Batch.CloudJob" RefType="this" />
        <Parameter Name="storageAccount" Type="Microsoft.WindowsAzure.Storage.CloudStorageAccount" />
      </Parameters>
      <Docs>
        <param name="job"><span data-ttu-id="f8618-102">Der Auftrag für die zum Erstellen des Containers.</span><span class="sxs-lookup"><span data-stu-id="f8618-102">The job for which to create the container.</span></span></param>
        <param name="storageAccount"><span data-ttu-id="f8618-103">Das Speicherkonto mit der Azure Batch-Konto verknüpft ist.</span><span class="sxs-lookup"><span data-stu-id="f8618-103">The storage account linked to the Azure Batch account.</span></span></param>
        <summary>
            <span data-ttu-id="f8618-104">Ruft die URL, einschließlich einer Shared Access Signature (SAS), die schreiben, für den Auftrag Ausgabe Speichercontainer in Azure Blob-Speicher ermöglicht.</span><span class="sxs-lookup"><span data-stu-id="f8618-104">Gets the URL, including a Shared Access Signature (SAS) that permits writing, for the job's output storage container in Azure blob storage.</span></span> <span data-ttu-id="f8618-105">Diese URL eignet sich für die Übergabe an Aufgaben, damit diese verwenden, können die <see cref="M:Microsoft.Azure.Batch.Conventions.Files.JobOutputStorage.#ctor(System.Uri)" /> oder <see cref="M:Microsoft.Azure.Batch.Conventions.Files.TaskOutputStorage.#ctor(System.Uri,System.String)" /> Konstruktoren, die eine <see cref="T:System.Uri" />.</span><span class="sxs-lookup"><span data-stu-id="f8618-105">This URL is suitable for passing to tasks so they can use the <see cref="M:Microsoft.Azure.Batch.Conventions.Files.JobOutputStorage.#ctor(System.Uri)" /> or <see cref="M:Microsoft.Azure.Batch.Conventions.Files.TaskOutputStorage.#ctor(System.Uri,System.String)" /> constructors that take a <see cref="T:System.Uri" />.</span></span>
            </summary>
        <returns><span data-ttu-id="f8618-106">Die URL, einschließlich SAS, der der Auftrag Ausgabecontainer.</span><span class="sxs-lookup"><span data-stu-id="f8618-106">The URL, including SAS, of the job output container.</span></span></returns>
        <remarks><span data-ttu-id="f8618-107">Die SAS läuft nach 7 Tagen ab.</span><span class="sxs-lookup"><span data-stu-id="f8618-107">The SAS expires after 7 days.</span></span> <span data-ttu-id="f8618-108">Diese Standardeinstellung wird ausgewählt, um die maximale Zeit entsprechen, die Aufgaben aktiv bleiben können.</span><span class="sxs-lookup"><span data-stu-id="f8618-108">This default is chosen to match the maximum time that tasks can remain active.</span></span></remarks>
      </Docs>
    </Member>
    <Member MemberName="GetOutputStorageContainerUrl">
      <MemberSignature Language="C#" Value="public static string GetOutputStorageContainerUrl (this Microsoft.Azure.Batch.CloudJob job, Microsoft.WindowsAzure.Storage.CloudStorageAccount storageAccount, TimeSpan expiryTime);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig string GetOutputStorageContainerUrl(class Microsoft.Azure.Batch.CloudJob job, class Microsoft.WindowsAzure.Storage.CloudStorageAccount storageAccount, valuetype System.TimeSpan expiryTime) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Conventions.Files.CloudJobExtensions.GetOutputStorageContainerUrl(Microsoft.Azure.Batch.CloudJob,Microsoft.WindowsAzure.Storage.CloudStorageAccount,System.TimeSpan)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function GetOutputStorageContainerUrl (job As CloudJob, storageAccount As CloudStorageAccount, expiryTime As TimeSpan) As String" />
      <MemberSignature Language="F#" Value="static member GetOutputStorageContainerUrl : Microsoft.Azure.Batch.CloudJob * Microsoft.WindowsAzure.Storage.CloudStorageAccount * TimeSpan -&gt; string" Usage="Microsoft.Azure.Batch.Conventions.Files.CloudJobExtensions.GetOutputStorageContainerUrl (job, storageAccount, expiryTime)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch.Conventions.Files</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="job" Type="Microsoft.Azure.Batch.CloudJob" RefType="this" />
        <Parameter Name="storageAccount" Type="Microsoft.WindowsAzure.Storage.CloudStorageAccount" />
        <Parameter Name="expiryTime" Type="System.TimeSpan" />
      </Parameters>
      <Docs>
        <param name="job"><span data-ttu-id="f8618-109">Der Auftrag für die zum Erstellen des Containers.</span><span class="sxs-lookup"><span data-stu-id="f8618-109">The job for which to create the container.</span></span></param>
        <param name="storageAccount"><span data-ttu-id="f8618-110">Das Speicherkonto mit der Azure Batch-Konto verknüpft ist.</span><span class="sxs-lookup"><span data-stu-id="f8618-110">The storage account linked to the Azure Batch account.</span></span></param>
        <param name="expiryTime"><span data-ttu-id="f8618-111">Die Dauer, für die die SAS gültig ist.</span><span class="sxs-lookup"><span data-stu-id="f8618-111">The duration for which the SAS is valid.</span></span>  <span data-ttu-id="f8618-112">Dies dürfte lang genug, um alle Aufgaben des Auftrags erstellt und werden vollständig, einschließlich Spielraum für Fehler und führt die Wiederholung ausgeführt werden können.</span><span class="sxs-lookup"><span data-stu-id="f8618-112">This should be long enough to allow all tasks of the job to be created and run to completion, including leeway for errors and retries.</span></span></param>
        <summary>
            <span data-ttu-id="f8618-113">Ruft die URL, einschließlich einer Shared Access Signature (SAS), die schreiben, für den Auftrag Ausgabe Speichercontainer in Azure Blob-Speicher ermöglicht.</span><span class="sxs-lookup"><span data-stu-id="f8618-113">Gets the URL, including a Shared Access Signature (SAS) that permits writing, for the job's output storage container in Azure blob storage.</span></span> <span data-ttu-id="f8618-114">Diese URL eignet sich für die Übergabe an Aufgaben, damit diese verwenden, können die <see cref="M:Microsoft.Azure.Batch.Conventions.Files.JobOutputStorage.#ctor(System.Uri)" /> oder <see cref="M:Microsoft.Azure.Batch.Conventions.Files.TaskOutputStorage.#ctor(System.Uri,System.String)" /> Konstruktoren, die eine <see cref="T:System.Uri" />.</span><span class="sxs-lookup"><span data-stu-id="f8618-114">This URL is suitable for passing to tasks so they can use the <see cref="M:Microsoft.Azure.Batch.Conventions.Files.JobOutputStorage.#ctor(System.Uri)" /> or <see cref="M:Microsoft.Azure.Batch.Conventions.Files.TaskOutputStorage.#ctor(System.Uri,System.String)" /> constructors that take a <see cref="T:System.Uri" />.</span></span>
            </summary>
        <returns><span data-ttu-id="f8618-115">Die URL, einschließlich SAS, der der Auftrag Ausgabecontainer.</span><span class="sxs-lookup"><span data-stu-id="f8618-115">The URL, including SAS, of the job output container.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OutputStorage">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Batch.Conventions.Files.JobOutputStorage OutputStorage (this Microsoft.Azure.Batch.CloudJob job, Microsoft.WindowsAzure.Storage.CloudStorageAccount storageAccount);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Batch.Conventions.Files.JobOutputStorage OutputStorage(class Microsoft.Azure.Batch.CloudJob job, class Microsoft.WindowsAzure.Storage.CloudStorageAccount storageAccount) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Conventions.Files.CloudJobExtensions.OutputStorage(Microsoft.Azure.Batch.CloudJob,Microsoft.WindowsAzure.Storage.CloudStorageAccount)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function OutputStorage (job As CloudJob, storageAccount As CloudStorageAccount) As JobOutputStorage" />
      <MemberSignature Language="F#" Value="static member OutputStorage : Microsoft.Azure.Batch.CloudJob * Microsoft.WindowsAzure.Storage.CloudStorageAccount -&gt; Microsoft.Azure.Batch.Conventions.Files.JobOutputStorage" Usage="Microsoft.Azure.Batch.Conventions.Files.CloudJobExtensions.OutputStorage (job, storageAccount)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch.Conventions.Files</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.Conventions.Files.JobOutputStorage</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="job" Type="Microsoft.Azure.Batch.CloudJob" RefType="this" />
        <Parameter Name="storageAccount" Type="Microsoft.WindowsAzure.Storage.CloudStorageAccount" />
      </Parameters>
      <Docs>
        <param name="job"><span data-ttu-id="f8618-116">Der Auftrag für die Ausgabe-Speicher abgerufen werden soll.</span><span class="sxs-lookup"><span data-stu-id="f8618-116">The job for which to get output storage.</span></span></param>
        <param name="storageAccount"><span data-ttu-id="f8618-117">Das Speicherkonto mit der Azure Batch-Konto verknüpft ist.</span><span class="sxs-lookup"><span data-stu-id="f8618-117">The storage account linked to the Azure Batch account.</span></span></param>
        <summary>
            <span data-ttu-id="f8618-118">Ruft die <see cref="T:Microsoft.Azure.Batch.Conventions.Files.JobOutputStorage" /> für einen angegebenen <see cref="T:Microsoft.Azure.Batch.CloudJob" />.</span><span class="sxs-lookup"><span data-stu-id="f8618-118">Gets the <see cref="T:Microsoft.Azure.Batch.Conventions.Files.JobOutputStorage" /> for a specified <see cref="T:Microsoft.Azure.Batch.CloudJob" />.</span></span>
            </summary>
        <returns><span data-ttu-id="f8618-119">Eine JobOutputStorage für den angegebenen Auftrag.</span><span class="sxs-lookup"><span data-stu-id="f8618-119">A JobOutputStorage for the specified job.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OutputStorageContainerName">
      <MemberSignature Language="C#" Value="public static string OutputStorageContainerName (this Microsoft.Azure.Batch.CloudJob job);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig string OutputStorageContainerName(class Microsoft.Azure.Batch.CloudJob job) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Conventions.Files.CloudJobExtensions.OutputStorageContainerName(Microsoft.Azure.Batch.CloudJob)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function OutputStorageContainerName (job As CloudJob) As String" />
      <MemberSignature Language="F#" Value="static member OutputStorageContainerName : Microsoft.Azure.Batch.CloudJob -&gt; string" Usage="Microsoft.Azure.Batch.Conventions.Files.CloudJobExtensions.OutputStorageContainerName job" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch.Conventions.Files</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="job" Type="Microsoft.Azure.Batch.CloudJob" RefType="this" />
      </Parameters>
      <Docs>
        <param name="job"><span data-ttu-id="f8618-120">Der Auftrag für das Abrufen des Namens des Entitätencontainers.</span><span class="sxs-lookup"><span data-stu-id="f8618-120">The job for which to get the container name.</span></span></param>
        <summary>
            <span data-ttu-id="f8618-121">Ruft den Namen des Azure-Blob-Speichercontainer für die Ausgaben von einem <see cref="T:Microsoft.Azure.Batch.CloudJob" />.</span><span class="sxs-lookup"><span data-stu-id="f8618-121">Gets the name of the Azure blob storage container for the outputs of a <see cref="T:Microsoft.Azure.Batch.CloudJob" />.</span></span>
            </summary>
        <returns><span data-ttu-id="f8618-122">Der Name des Containers zum Speichern der Ausgaben des Auftrags.</span><span class="sxs-lookup"><span data-stu-id="f8618-122">The name of the container in which to save the outputs of this job.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PrepareOutputStorageAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task PrepareOutputStorageAsync (this Microsoft.Azure.Batch.CloudJob job, Microsoft.WindowsAzure.Storage.CloudStorageAccount storageAccount, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task PrepareOutputStorageAsync(class Microsoft.Azure.Batch.CloudJob job, class Microsoft.WindowsAzure.Storage.CloudStorageAccount storageAccount, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Conventions.Files.CloudJobExtensions.PrepareOutputStorageAsync(Microsoft.Azure.Batch.CloudJob,Microsoft.WindowsAzure.Storage.CloudStorageAccount,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member PrepareOutputStorageAsync : Microsoft.Azure.Batch.CloudJob * Microsoft.WindowsAzure.Storage.CloudStorageAccount * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Batch.Conventions.Files.CloudJobExtensions.PrepareOutputStorageAsync (job, storageAccount, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch.Conventions.Files</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Batch.Conventions.Files.CloudJobExtensions/&lt;PrepareOutputStorageAsync&gt;d__2))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="job" Type="Microsoft.Azure.Batch.CloudJob" RefType="this" />
        <Parameter Name="storageAccount" Type="Microsoft.WindowsAzure.Storage.CloudStorageAccount" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="job"><span data-ttu-id="f8618-123">Der Auftrag für die zum Erstellen des Containers.</span><span class="sxs-lookup"><span data-stu-id="f8618-123">The job for which to create the container.</span></span></param>
        <param name="storageAccount"><span data-ttu-id="f8618-124">Das Speicherkonto mit der Azure Batch-Konto verknüpft ist.</span><span class="sxs-lookup"><span data-stu-id="f8618-124">The storage account linked to the Azure Batch account.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="f8618-125">Ein <see cref="T:System.Threading.CancellationToken" /> für die Steuerung der Lebensdauer eines asynchronen Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="f8618-125">A <see cref="T:System.Threading.CancellationToken" /> for controlling the lifetime of the asynchronous operation.</span></span></param>
        <summary>
            <span data-ttu-id="f8618-126">Erstellt einen Azure-Blob-Speichercontainer für die Ausgaben von einem <see cref="T:Microsoft.Azure.Batch.CloudJob" />.</span><span class="sxs-lookup"><span data-stu-id="f8618-126">Creates an Azure blob storage container for the outputs of a <see cref="T:Microsoft.Azure.Batch.CloudJob" />.</span></span>
            </summary>
        <returns><span data-ttu-id="f8618-127">Ein <see cref="T:System.Threading.Tasks.Task" />-Element, das den asynchronen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="f8618-127">A <see cref="T:System.Threading.Tasks.Task" /> that represents the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>