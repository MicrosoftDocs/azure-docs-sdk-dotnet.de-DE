<Type Name="IFileOperations" FullName="Microsoft.Azure.Batch.Protocol.IFileOperations">
  <TypeSignature Language="C#" Value="public interface IFileOperations" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IFileOperations" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Batch.Protocol.IFileOperations" />
  <TypeSignature Language="VB.NET" Value="Public Interface IFileOperations" />
  <TypeSignature Language="F#" Value="type IFileOperations = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
    <AssemblyVersion>7.1.0.0</AssemblyVersion>
    <AssemblyVersion>8.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="c1c94-101">FileOperations-Vorgänge.</span><span class="sxs-lookup"><span data-stu-id="c1c94-101">FileOperations operations.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="DeleteFromComputeNodeWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationHeaderResponse&lt;Microsoft.Azure.Batch.Protocol.Models.FileDeleteFromComputeNodeHeaders&gt;&gt; DeleteFromComputeNodeWithHttpMessagesAsync (string poolId, string nodeId, string filePath, Nullable&lt;bool&gt; recursive = null, Microsoft.Azure.Batch.Protocol.Models.FileDeleteFromComputeNodeOptions fileDeleteFromComputeNodeOptions = null, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationHeaderResponse`1&lt;class Microsoft.Azure.Batch.Protocol.Models.FileDeleteFromComputeNodeHeaders&gt;&gt; DeleteFromComputeNodeWithHttpMessagesAsync(string poolId, string nodeId, string filePath, valuetype System.Nullable`1&lt;bool&gt; recursive, class Microsoft.Azure.Batch.Protocol.Models.FileDeleteFromComputeNodeOptions fileDeleteFromComputeNodeOptions, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.IFileOperations.DeleteFromComputeNodeWithHttpMessagesAsync(System.String,System.String,System.String,System.Nullable{System.Boolean},Microsoft.Azure.Batch.Protocol.Models.FileDeleteFromComputeNodeOptions,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member DeleteFromComputeNodeWithHttpMessagesAsync : string * string * string * Nullable&lt;bool&gt; * Microsoft.Azure.Batch.Protocol.Models.FileDeleteFromComputeNodeOptions * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationHeaderResponse&lt;Microsoft.Azure.Batch.Protocol.Models.FileDeleteFromComputeNodeHeaders&gt;&gt;" Usage="iFileOperations.DeleteFromComputeNodeWithHttpMessagesAsync (poolId, nodeId, filePath, recursive, fileDeleteFromComputeNodeOptions, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationHeaderResponse&lt;Microsoft.Azure.Batch.Protocol.Models.FileDeleteFromComputeNodeHeaders&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="poolId" Type="System.String" />
        <Parameter Name="nodeId" Type="System.String" />
        <Parameter Name="filePath" Type="System.String" />
        <Parameter Name="recursive" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="fileDeleteFromComputeNodeOptions" Type="Microsoft.Azure.Batch.Protocol.Models.FileDeleteFromComputeNodeOptions" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="poolId">
            <span data-ttu-id="c1c94-102">Die ID des Pools, den Compute-Knoten enthält.</span><span class="sxs-lookup"><span data-stu-id="c1c94-102">The ID of the pool that contains the compute node.</span></span>
            </param>
        <param name="nodeId">
            <span data-ttu-id="c1c94-103">Die ID der Compute-Knoten, von dem Sie die Datei löschen möchten.</span><span class="sxs-lookup"><span data-stu-id="c1c94-103">The ID of the compute node from which you want to delete the file.</span></span>
            </param>
        <param name="filePath">
            <span data-ttu-id="c1c94-104">Der Pfad zur Datei oder zum Verzeichnis, das Sie löschen möchten.</span><span class="sxs-lookup"><span data-stu-id="c1c94-104">The path to the file or directory that you want to delete.</span></span>
            </param>
        <param name="recursive">
            <span data-ttu-id="c1c94-105">Ob untergeordnete Elemente eines Verzeichnisses gelöscht.</span><span class="sxs-lookup"><span data-stu-id="c1c94-105">Whether to delete children of a directory.</span></span> <span data-ttu-id="c1c94-106">Wenn der Parameter "FilePath" ein Verzeichnis anstelle einer Datei darstellt, können Sie die rekursive auf "true" Löschen des Verzeichnisses und aller Dateien und Unterverzeichnisse darin festlegen.</span><span class="sxs-lookup"><span data-stu-id="c1c94-106">If the filePath parameter represents a directory instead of a file, you can set recursive to true to delete the directory and all of the files and subdirectories in it.</span></span> <span data-ttu-id="c1c94-107">Wenn rekursiv "false" ist das Verzeichnis muss leer sein, oder Löschvorgang fehl.</span><span class="sxs-lookup"><span data-stu-id="c1c94-107">If recursive is false then the directory must be empty or deletion will fail.</span></span>
            </param>
        <param name="fileDeleteFromComputeNodeOptions">
            <span data-ttu-id="c1c94-108">Zusätzliche Parameter für den Vorgang</span><span class="sxs-lookup"><span data-stu-id="c1c94-108">Additional parameters for the operation</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="c1c94-109">Die Header, die hinzugefügt werden auf Anforderung.</span><span class="sxs-lookup"><span data-stu-id="c1c94-109">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="c1c94-110">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="c1c94-110">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="c1c94-111">Löscht die angegebene Datei als der Serverknoten an.</span><span class="sxs-lookup"><span data-stu-id="c1c94-111">Deletes the specified file from the compute node.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Azure.Batch.Protocol.Models.BatchErrorException">
            <span data-ttu-id="c1c94-112">Wird ausgelöst, wenn der Vorgang einen ungültigen Statuscode zurückgegeben hat.</span><span class="sxs-lookup"><span data-stu-id="c1c94-112">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="c1c94-113">Wird ausgelöst, wenn ein erforderlicher Parameter null ist.</span><span class="sxs-lookup"><span data-stu-id="c1c94-113">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="DeleteFromTaskWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationHeaderResponse&lt;Microsoft.Azure.Batch.Protocol.Models.FileDeleteFromTaskHeaders&gt;&gt; DeleteFromTaskWithHttpMessagesAsync (string jobId, string taskId, string filePath, Nullable&lt;bool&gt; recursive = null, Microsoft.Azure.Batch.Protocol.Models.FileDeleteFromTaskOptions fileDeleteFromTaskOptions = null, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationHeaderResponse`1&lt;class Microsoft.Azure.Batch.Protocol.Models.FileDeleteFromTaskHeaders&gt;&gt; DeleteFromTaskWithHttpMessagesAsync(string jobId, string taskId, string filePath, valuetype System.Nullable`1&lt;bool&gt; recursive, class Microsoft.Azure.Batch.Protocol.Models.FileDeleteFromTaskOptions fileDeleteFromTaskOptions, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.IFileOperations.DeleteFromTaskWithHttpMessagesAsync(System.String,System.String,System.String,System.Nullable{System.Boolean},Microsoft.Azure.Batch.Protocol.Models.FileDeleteFromTaskOptions,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member DeleteFromTaskWithHttpMessagesAsync : string * string * string * Nullable&lt;bool&gt; * Microsoft.Azure.Batch.Protocol.Models.FileDeleteFromTaskOptions * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationHeaderResponse&lt;Microsoft.Azure.Batch.Protocol.Models.FileDeleteFromTaskHeaders&gt;&gt;" Usage="iFileOperations.DeleteFromTaskWithHttpMessagesAsync (jobId, taskId, filePath, recursive, fileDeleteFromTaskOptions, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationHeaderResponse&lt;Microsoft.Azure.Batch.Protocol.Models.FileDeleteFromTaskHeaders&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="jobId" Type="System.String" />
        <Parameter Name="taskId" Type="System.String" />
        <Parameter Name="filePath" Type="System.String" />
        <Parameter Name="recursive" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="fileDeleteFromTaskOptions" Type="Microsoft.Azure.Batch.Protocol.Models.FileDeleteFromTaskOptions" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="jobId">
            <span data-ttu-id="c1c94-114">Die ID des Auftrags, der den Task enthält.</span><span class="sxs-lookup"><span data-stu-id="c1c94-114">The ID of the job that contains the task.</span></span>
            </param>
        <param name="taskId">
            <span data-ttu-id="c1c94-115">Die ID der Aufgabe, deren Datei, die Sie löschen möchten.</span><span class="sxs-lookup"><span data-stu-id="c1c94-115">The ID of the task whose file you want to delete.</span></span>
            </param>
        <param name="filePath">
            <span data-ttu-id="c1c94-116">Der Pfad zu der Aufgabendatei oder das Verzeichnis, das Sie löschen möchten.</span><span class="sxs-lookup"><span data-stu-id="c1c94-116">The path to the task file or directory that you want to delete.</span></span>
            </param>
        <param name="recursive">
            <span data-ttu-id="c1c94-117">Ob untergeordnete Elemente eines Verzeichnisses gelöscht.</span><span class="sxs-lookup"><span data-stu-id="c1c94-117">Whether to delete children of a directory.</span></span> <span data-ttu-id="c1c94-118">Wenn der Parameter "FilePath" ein Verzeichnis anstelle einer Datei darstellt, können Sie die rekursive auf "true" Löschen des Verzeichnisses und aller Dateien und Unterverzeichnisse darin festlegen.</span><span class="sxs-lookup"><span data-stu-id="c1c94-118">If the filePath parameter represents a directory instead of a file, you can set recursive to true to delete the directory and all of the files and subdirectories in it.</span></span> <span data-ttu-id="c1c94-119">Wenn rekursiv "false" ist das Verzeichnis muss leer sein, oder Löschvorgang fehl.</span><span class="sxs-lookup"><span data-stu-id="c1c94-119">If recursive is false then the directory must be empty or deletion will fail.</span></span>
            </param>
        <param name="fileDeleteFromTaskOptions">
            <span data-ttu-id="c1c94-120">Zusätzliche Parameter für den Vorgang</span><span class="sxs-lookup"><span data-stu-id="c1c94-120">Additional parameters for the operation</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="c1c94-121">Die Header, die hinzugefügt werden auf Anforderung.</span><span class="sxs-lookup"><span data-stu-id="c1c94-121">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="c1c94-122">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="c1c94-122">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="c1c94-123">Löscht der angegebenen Aufgabendatei aus den Compute-Knoten, in dem die Aufgabe ausgeführt wurde.</span><span class="sxs-lookup"><span data-stu-id="c1c94-123">Deletes the specified task file from the compute node where the task ran.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Azure.Batch.Protocol.Models.BatchErrorException">
            <span data-ttu-id="c1c94-124">Wird ausgelöst, wenn der Vorgang einen ungültigen Statuscode zurückgegeben hat.</span><span class="sxs-lookup"><span data-stu-id="c1c94-124">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="c1c94-125">Wird ausgelöst, wenn ein erforderlicher Parameter null ist.</span><span class="sxs-lookup"><span data-stu-id="c1c94-125">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="GetFromComputeNodeWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;System.IO.Stream,Microsoft.Azure.Batch.Protocol.Models.FileGetFromComputeNodeHeaders&gt;&gt; GetFromComputeNodeWithHttpMessagesAsync (string poolId, string nodeId, string filePath, Microsoft.Azure.Batch.Protocol.Models.FileGetFromComputeNodeOptions fileGetFromComputeNodeOptions = null, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`2&lt;class System.IO.Stream, class Microsoft.Azure.Batch.Protocol.Models.FileGetFromComputeNodeHeaders&gt;&gt; GetFromComputeNodeWithHttpMessagesAsync(string poolId, string nodeId, string filePath, class Microsoft.Azure.Batch.Protocol.Models.FileGetFromComputeNodeOptions fileGetFromComputeNodeOptions, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.IFileOperations.GetFromComputeNodeWithHttpMessagesAsync(System.String,System.String,System.String,Microsoft.Azure.Batch.Protocol.Models.FileGetFromComputeNodeOptions,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetFromComputeNodeWithHttpMessagesAsync : string * string * string * Microsoft.Azure.Batch.Protocol.Models.FileGetFromComputeNodeOptions * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;System.IO.Stream, Microsoft.Azure.Batch.Protocol.Models.FileGetFromComputeNodeHeaders&gt;&gt;" Usage="iFileOperations.GetFromComputeNodeWithHttpMessagesAsync (poolId, nodeId, filePath, fileGetFromComputeNodeOptions, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;System.IO.Stream,Microsoft.Azure.Batch.Protocol.Models.FileGetFromComputeNodeHeaders&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="poolId" Type="System.String" />
        <Parameter Name="nodeId" Type="System.String" />
        <Parameter Name="filePath" Type="System.String" />
        <Parameter Name="fileGetFromComputeNodeOptions" Type="Microsoft.Azure.Batch.Protocol.Models.FileGetFromComputeNodeOptions" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="poolId">
            <span data-ttu-id="c1c94-126">Die ID des Pools, den Compute-Knoten enthält.</span><span class="sxs-lookup"><span data-stu-id="c1c94-126">The ID of the pool that contains the compute node.</span></span>
            </param>
        <param name="nodeId">
            <span data-ttu-id="c1c94-127">Die ID des Compute-Knotens, der die Datei enthält.</span><span class="sxs-lookup"><span data-stu-id="c1c94-127">The ID of the compute node that contains the file.</span></span>
            </param>
        <param name="filePath">
            <span data-ttu-id="c1c94-128">Der Pfad zu der Compute-Knoten-Datei, der den Inhalt abgerufen werden soll.</span><span class="sxs-lookup"><span data-stu-id="c1c94-128">The path to the compute node file that you want to get the content of.</span></span>
            </param>
        <param name="fileGetFromComputeNodeOptions">
            <span data-ttu-id="c1c94-129">Zusätzliche Parameter für den Vorgang</span><span class="sxs-lookup"><span data-stu-id="c1c94-129">Additional parameters for the operation</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="c1c94-130">Die Header, die hinzugefügt werden auf Anforderung.</span><span class="sxs-lookup"><span data-stu-id="c1c94-130">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="c1c94-131">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="c1c94-131">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="c1c94-132">Gibt den Inhalt der angegebenen Compute-Knoten-Datei zurück.</span><span class="sxs-lookup"><span data-stu-id="c1c94-132">Returns the content of the specified compute node file.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Azure.Batch.Protocol.Models.BatchErrorException">
            <span data-ttu-id="c1c94-133">Wird ausgelöst, wenn der Vorgang einen ungültigen Statuscode zurückgegeben hat.</span><span class="sxs-lookup"><span data-stu-id="c1c94-133">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="c1c94-134">Wird ausgelöst, wenn nicht die Antwort zu deserialisieren.</span><span class="sxs-lookup"><span data-stu-id="c1c94-134">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="c1c94-135">Wird ausgelöst, wenn ein erforderlicher Parameter null ist.</span><span class="sxs-lookup"><span data-stu-id="c1c94-135">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="GetFromTaskWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;System.IO.Stream,Microsoft.Azure.Batch.Protocol.Models.FileGetFromTaskHeaders&gt;&gt; GetFromTaskWithHttpMessagesAsync (string jobId, string taskId, string filePath, Microsoft.Azure.Batch.Protocol.Models.FileGetFromTaskOptions fileGetFromTaskOptions = null, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`2&lt;class System.IO.Stream, class Microsoft.Azure.Batch.Protocol.Models.FileGetFromTaskHeaders&gt;&gt; GetFromTaskWithHttpMessagesAsync(string jobId, string taskId, string filePath, class Microsoft.Azure.Batch.Protocol.Models.FileGetFromTaskOptions fileGetFromTaskOptions, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.IFileOperations.GetFromTaskWithHttpMessagesAsync(System.String,System.String,System.String,Microsoft.Azure.Batch.Protocol.Models.FileGetFromTaskOptions,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetFromTaskWithHttpMessagesAsync : string * string * string * Microsoft.Azure.Batch.Protocol.Models.FileGetFromTaskOptions * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;System.IO.Stream, Microsoft.Azure.Batch.Protocol.Models.FileGetFromTaskHeaders&gt;&gt;" Usage="iFileOperations.GetFromTaskWithHttpMessagesAsync (jobId, taskId, filePath, fileGetFromTaskOptions, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;System.IO.Stream,Microsoft.Azure.Batch.Protocol.Models.FileGetFromTaskHeaders&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="jobId" Type="System.String" />
        <Parameter Name="taskId" Type="System.String" />
        <Parameter Name="filePath" Type="System.String" />
        <Parameter Name="fileGetFromTaskOptions" Type="Microsoft.Azure.Batch.Protocol.Models.FileGetFromTaskOptions" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="jobId">
            <span data-ttu-id="c1c94-136">Die ID des Auftrags, der den Task enthält.</span><span class="sxs-lookup"><span data-stu-id="c1c94-136">The ID of the job that contains the task.</span></span>
            </param>
        <param name="taskId">
            <span data-ttu-id="c1c94-137">Die ID der Aufgabe, deren Datei, die Sie abrufen möchten.</span><span class="sxs-lookup"><span data-stu-id="c1c94-137">The ID of the task whose file you want to retrieve.</span></span>
            </param>
        <param name="filePath">
            <span data-ttu-id="c1c94-138">Der Pfad zu der Aufgabendatei, die den Inhalt abgerufen werden soll.</span><span class="sxs-lookup"><span data-stu-id="c1c94-138">The path to the task file that you want to get the content of.</span></span>
            </param>
        <param name="fileGetFromTaskOptions">
            <span data-ttu-id="c1c94-139">Zusätzliche Parameter für den Vorgang</span><span class="sxs-lookup"><span data-stu-id="c1c94-139">Additional parameters for the operation</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="c1c94-140">Die Header, die hinzugefügt werden auf Anforderung.</span><span class="sxs-lookup"><span data-stu-id="c1c94-140">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="c1c94-141">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="c1c94-141">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="c1c94-142">Gibt den Inhalt der angegebenen Aufgabendatei zurück.</span><span class="sxs-lookup"><span data-stu-id="c1c94-142">Returns the content of the specified task file.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Azure.Batch.Protocol.Models.BatchErrorException">
            <span data-ttu-id="c1c94-143">Wird ausgelöst, wenn der Vorgang einen ungültigen Statuscode zurückgegeben hat.</span><span class="sxs-lookup"><span data-stu-id="c1c94-143">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="c1c94-144">Wird ausgelöst, wenn nicht die Antwort zu deserialisieren.</span><span class="sxs-lookup"><span data-stu-id="c1c94-144">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="c1c94-145">Wird ausgelöst, wenn ein erforderlicher Parameter null ist.</span><span class="sxs-lookup"><span data-stu-id="c1c94-145">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="GetPropertiesFromComputeNodeWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationHeaderResponse&lt;Microsoft.Azure.Batch.Protocol.Models.FileGetPropertiesFromComputeNodeHeaders&gt;&gt; GetPropertiesFromComputeNodeWithHttpMessagesAsync (string poolId, string nodeId, string filePath, Microsoft.Azure.Batch.Protocol.Models.FileGetPropertiesFromComputeNodeOptions fileGetPropertiesFromComputeNodeOptions = null, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationHeaderResponse`1&lt;class Microsoft.Azure.Batch.Protocol.Models.FileGetPropertiesFromComputeNodeHeaders&gt;&gt; GetPropertiesFromComputeNodeWithHttpMessagesAsync(string poolId, string nodeId, string filePath, class Microsoft.Azure.Batch.Protocol.Models.FileGetPropertiesFromComputeNodeOptions fileGetPropertiesFromComputeNodeOptions, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.IFileOperations.GetPropertiesFromComputeNodeWithHttpMessagesAsync(System.String,System.String,System.String,Microsoft.Azure.Batch.Protocol.Models.FileGetPropertiesFromComputeNodeOptions,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetPropertiesFromComputeNodeWithHttpMessagesAsync : string * string * string * Microsoft.Azure.Batch.Protocol.Models.FileGetPropertiesFromComputeNodeOptions * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationHeaderResponse&lt;Microsoft.Azure.Batch.Protocol.Models.FileGetPropertiesFromComputeNodeHeaders&gt;&gt;" Usage="iFileOperations.GetPropertiesFromComputeNodeWithHttpMessagesAsync (poolId, nodeId, filePath, fileGetPropertiesFromComputeNodeOptions, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationHeaderResponse&lt;Microsoft.Azure.Batch.Protocol.Models.FileGetPropertiesFromComputeNodeHeaders&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="poolId" Type="System.String" />
        <Parameter Name="nodeId" Type="System.String" />
        <Parameter Name="filePath" Type="System.String" />
        <Parameter Name="fileGetPropertiesFromComputeNodeOptions" Type="Microsoft.Azure.Batch.Protocol.Models.FileGetPropertiesFromComputeNodeOptions" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="poolId">
            <span data-ttu-id="c1c94-146">Die ID des Pools, den Compute-Knoten enthält.</span><span class="sxs-lookup"><span data-stu-id="c1c94-146">The ID of the pool that contains the compute node.</span></span>
            </param>
        <param name="nodeId">
            <span data-ttu-id="c1c94-147">Die ID des Compute-Knotens, der die Datei enthält.</span><span class="sxs-lookup"><span data-stu-id="c1c94-147">The ID of the compute node that contains the file.</span></span>
            </param>
        <param name="filePath">
            <span data-ttu-id="c1c94-148">Der Pfad der Compute-Knoten-Datei, die die Eigenschaften abgerufen werden sollen.</span><span class="sxs-lookup"><span data-stu-id="c1c94-148">The path to the compute node file that you want to get the properties of.</span></span>
            </param>
        <param name="fileGetPropertiesFromComputeNodeOptions">
            <span data-ttu-id="c1c94-149">Zusätzliche Parameter für den Vorgang</span><span class="sxs-lookup"><span data-stu-id="c1c94-149">Additional parameters for the operation</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="c1c94-150">Die Header, die hinzugefügt werden auf Anforderung.</span><span class="sxs-lookup"><span data-stu-id="c1c94-150">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="c1c94-151">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="c1c94-151">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="c1c94-152">Ruft die Eigenschaften der angegebenen Compute-Knoten-Datei ab.</span><span class="sxs-lookup"><span data-stu-id="c1c94-152">Gets the properties of the specified compute node file.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Azure.Batch.Protocol.Models.BatchErrorException">
            <span data-ttu-id="c1c94-153">Wird ausgelöst, wenn der Vorgang einen ungültigen Statuscode zurückgegeben hat.</span><span class="sxs-lookup"><span data-stu-id="c1c94-153">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="c1c94-154">Wird ausgelöst, wenn ein erforderlicher Parameter null ist.</span><span class="sxs-lookup"><span data-stu-id="c1c94-154">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="GetPropertiesFromTaskWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationHeaderResponse&lt;Microsoft.Azure.Batch.Protocol.Models.FileGetPropertiesFromTaskHeaders&gt;&gt; GetPropertiesFromTaskWithHttpMessagesAsync (string jobId, string taskId, string filePath, Microsoft.Azure.Batch.Protocol.Models.FileGetPropertiesFromTaskOptions fileGetPropertiesFromTaskOptions = null, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationHeaderResponse`1&lt;class Microsoft.Azure.Batch.Protocol.Models.FileGetPropertiesFromTaskHeaders&gt;&gt; GetPropertiesFromTaskWithHttpMessagesAsync(string jobId, string taskId, string filePath, class Microsoft.Azure.Batch.Protocol.Models.FileGetPropertiesFromTaskOptions fileGetPropertiesFromTaskOptions, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.IFileOperations.GetPropertiesFromTaskWithHttpMessagesAsync(System.String,System.String,System.String,Microsoft.Azure.Batch.Protocol.Models.FileGetPropertiesFromTaskOptions,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetPropertiesFromTaskWithHttpMessagesAsync : string * string * string * Microsoft.Azure.Batch.Protocol.Models.FileGetPropertiesFromTaskOptions * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationHeaderResponse&lt;Microsoft.Azure.Batch.Protocol.Models.FileGetPropertiesFromTaskHeaders&gt;&gt;" Usage="iFileOperations.GetPropertiesFromTaskWithHttpMessagesAsync (jobId, taskId, filePath, fileGetPropertiesFromTaskOptions, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationHeaderResponse&lt;Microsoft.Azure.Batch.Protocol.Models.FileGetPropertiesFromTaskHeaders&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="jobId" Type="System.String" />
        <Parameter Name="taskId" Type="System.String" />
        <Parameter Name="filePath" Type="System.String" />
        <Parameter Name="fileGetPropertiesFromTaskOptions" Type="Microsoft.Azure.Batch.Protocol.Models.FileGetPropertiesFromTaskOptions" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="jobId">
            <span data-ttu-id="c1c94-155">Die ID des Auftrags, der den Task enthält.</span><span class="sxs-lookup"><span data-stu-id="c1c94-155">The ID of the job that contains the task.</span></span>
            </param>
        <param name="taskId">
            <span data-ttu-id="c1c94-156">Die ID der Aufgabe, deren Datei, die die Eigenschaften abgerufen werden sollen.</span><span class="sxs-lookup"><span data-stu-id="c1c94-156">The ID of the task whose file you want to get the properties of.</span></span>
            </param>
        <param name="filePath">
            <span data-ttu-id="c1c94-157">Der Pfad zu der Aufgabendatei, die die Eigenschaften abgerufen werden sollen.</span><span class="sxs-lookup"><span data-stu-id="c1c94-157">The path to the task file that you want to get the properties of.</span></span>
            </param>
        <param name="fileGetPropertiesFromTaskOptions">
            <span data-ttu-id="c1c94-158">Zusätzliche Parameter für den Vorgang</span><span class="sxs-lookup"><span data-stu-id="c1c94-158">Additional parameters for the operation</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="c1c94-159">Die Header, die hinzugefügt werden auf Anforderung.</span><span class="sxs-lookup"><span data-stu-id="c1c94-159">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="c1c94-160">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="c1c94-160">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="c1c94-161">Ruft die Eigenschaften der angegebenen Aufgabendatei ab.</span><span class="sxs-lookup"><span data-stu-id="c1c94-161">Gets the properties of the specified task file.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Azure.Batch.Protocol.Models.BatchErrorException">
            <span data-ttu-id="c1c94-162">Wird ausgelöst, wenn der Vorgang einen ungültigen Statuscode zurückgegeben hat.</span><span class="sxs-lookup"><span data-stu-id="c1c94-162">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="c1c94-163">Wird ausgelöst, wenn ein erforderlicher Parameter null ist.</span><span class="sxs-lookup"><span data-stu-id="c1c94-163">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="ListFromComputeNodeNextWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Batch.Protocol.Models.NodeFile&gt;,Microsoft.Azure.Batch.Protocol.Models.FileListFromComputeNodeHeaders&gt;&gt; ListFromComputeNodeNextWithHttpMessagesAsync (string nextPageLink, Microsoft.Azure.Batch.Protocol.Models.FileListFromComputeNodeNextOptions fileListFromComputeNodeNextOptions = null, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`2&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Batch.Protocol.Models.NodeFile&gt;, class Microsoft.Azure.Batch.Protocol.Models.FileListFromComputeNodeHeaders&gt;&gt; ListFromComputeNodeNextWithHttpMessagesAsync(string nextPageLink, class Microsoft.Azure.Batch.Protocol.Models.FileListFromComputeNodeNextOptions fileListFromComputeNodeNextOptions, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.IFileOperations.ListFromComputeNodeNextWithHttpMessagesAsync(System.String,Microsoft.Azure.Batch.Protocol.Models.FileListFromComputeNodeNextOptions,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListFromComputeNodeNextWithHttpMessagesAsync : string * Microsoft.Azure.Batch.Protocol.Models.FileListFromComputeNodeNextOptions * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Batch.Protocol.Models.NodeFile&gt;, Microsoft.Azure.Batch.Protocol.Models.FileListFromComputeNodeHeaders&gt;&gt;" Usage="iFileOperations.ListFromComputeNodeNextWithHttpMessagesAsync (nextPageLink, fileListFromComputeNodeNextOptions, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Batch.Protocol.Models.NodeFile&gt;,Microsoft.Azure.Batch.Protocol.Models.FileListFromComputeNodeHeaders&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="fileListFromComputeNodeNextOptions" Type="Microsoft.Azure.Batch.Protocol.Models.FileListFromComputeNodeNextOptions" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="nextPageLink">
            <span data-ttu-id="c1c94-164">Die "NextLink" aus dem vorherigen erfolgreichen Aufruf List-Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="c1c94-164">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="fileListFromComputeNodeNextOptions">
            <span data-ttu-id="c1c94-165">Zusätzliche Parameter für den Vorgang</span><span class="sxs-lookup"><span data-stu-id="c1c94-165">Additional parameters for the operation</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="c1c94-166">Die Header, die hinzugefügt werden auf Anforderung.</span><span class="sxs-lookup"><span data-stu-id="c1c94-166">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="c1c94-167">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="c1c94-167">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="c1c94-168">Zeigt eine Liste aller Dateien im Task-Verzeichnisse im angegebenen Serverknoten.</span><span class="sxs-lookup"><span data-stu-id="c1c94-168">Lists all of the files in task directories on the specified compute node.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Azure.Batch.Protocol.Models.BatchErrorException">
            <span data-ttu-id="c1c94-169">Wird ausgelöst, wenn der Vorgang einen ungültigen Statuscode zurückgegeben hat.</span><span class="sxs-lookup"><span data-stu-id="c1c94-169">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="c1c94-170">Wird ausgelöst, wenn nicht die Antwort zu deserialisieren.</span><span class="sxs-lookup"><span data-stu-id="c1c94-170">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="c1c94-171">Wird ausgelöst, wenn ein erforderlicher Parameter null ist.</span><span class="sxs-lookup"><span data-stu-id="c1c94-171">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="ListFromComputeNodeWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Batch.Protocol.Models.NodeFile&gt;,Microsoft.Azure.Batch.Protocol.Models.FileListFromComputeNodeHeaders&gt;&gt; ListFromComputeNodeWithHttpMessagesAsync (string poolId, string nodeId, Nullable&lt;bool&gt; recursive = null, Microsoft.Azure.Batch.Protocol.Models.FileListFromComputeNodeOptions fileListFromComputeNodeOptions = null, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`2&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Batch.Protocol.Models.NodeFile&gt;, class Microsoft.Azure.Batch.Protocol.Models.FileListFromComputeNodeHeaders&gt;&gt; ListFromComputeNodeWithHttpMessagesAsync(string poolId, string nodeId, valuetype System.Nullable`1&lt;bool&gt; recursive, class Microsoft.Azure.Batch.Protocol.Models.FileListFromComputeNodeOptions fileListFromComputeNodeOptions, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.IFileOperations.ListFromComputeNodeWithHttpMessagesAsync(System.String,System.String,System.Nullable{System.Boolean},Microsoft.Azure.Batch.Protocol.Models.FileListFromComputeNodeOptions,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListFromComputeNodeWithHttpMessagesAsync : string * string * Nullable&lt;bool&gt; * Microsoft.Azure.Batch.Protocol.Models.FileListFromComputeNodeOptions * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Batch.Protocol.Models.NodeFile&gt;, Microsoft.Azure.Batch.Protocol.Models.FileListFromComputeNodeHeaders&gt;&gt;" Usage="iFileOperations.ListFromComputeNodeWithHttpMessagesAsync (poolId, nodeId, recursive, fileListFromComputeNodeOptions, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Batch.Protocol.Models.NodeFile&gt;,Microsoft.Azure.Batch.Protocol.Models.FileListFromComputeNodeHeaders&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="poolId" Type="System.String" />
        <Parameter Name="nodeId" Type="System.String" />
        <Parameter Name="recursive" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="fileListFromComputeNodeOptions" Type="Microsoft.Azure.Batch.Protocol.Models.FileListFromComputeNodeOptions" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="poolId">
            <span data-ttu-id="c1c94-172">Die ID des Pools, den Compute-Knoten enthält.</span><span class="sxs-lookup"><span data-stu-id="c1c94-172">The ID of the pool that contains the compute node.</span></span>
            </param>
        <param name="nodeId">
            <span data-ttu-id="c1c94-173">Die ID des Serverknotens, deren Dateien, die Sie auflisten möchten.</span><span class="sxs-lookup"><span data-stu-id="c1c94-173">The ID of the compute node whose files you want to list.</span></span>
            </param>
        <param name="recursive">
            <span data-ttu-id="c1c94-174">Ob untergeordnete Elemente auflisten eines Verzeichnisses.</span><span class="sxs-lookup"><span data-stu-id="c1c94-174">Whether to list children of a directory.</span></span>
            </param>
        <param name="fileListFromComputeNodeOptions">
            <span data-ttu-id="c1c94-175">Zusätzliche Parameter für den Vorgang</span><span class="sxs-lookup"><span data-stu-id="c1c94-175">Additional parameters for the operation</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="c1c94-176">Die Header, die hinzugefügt werden auf Anforderung.</span><span class="sxs-lookup"><span data-stu-id="c1c94-176">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="c1c94-177">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="c1c94-177">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="c1c94-178">Zeigt eine Liste aller Dateien im Task-Verzeichnisse im angegebenen Serverknoten.</span><span class="sxs-lookup"><span data-stu-id="c1c94-178">Lists all of the files in task directories on the specified compute node.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Azure.Batch.Protocol.Models.BatchErrorException">
            <span data-ttu-id="c1c94-179">Wird ausgelöst, wenn der Vorgang einen ungültigen Statuscode zurückgegeben hat.</span><span class="sxs-lookup"><span data-stu-id="c1c94-179">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="c1c94-180">Wird ausgelöst, wenn nicht die Antwort zu deserialisieren.</span><span class="sxs-lookup"><span data-stu-id="c1c94-180">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="c1c94-181">Wird ausgelöst, wenn ein erforderlicher Parameter null ist.</span><span class="sxs-lookup"><span data-stu-id="c1c94-181">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="ListFromTaskNextWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Batch.Protocol.Models.NodeFile&gt;,Microsoft.Azure.Batch.Protocol.Models.FileListFromTaskHeaders&gt;&gt; ListFromTaskNextWithHttpMessagesAsync (string nextPageLink, Microsoft.Azure.Batch.Protocol.Models.FileListFromTaskNextOptions fileListFromTaskNextOptions = null, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`2&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Batch.Protocol.Models.NodeFile&gt;, class Microsoft.Azure.Batch.Protocol.Models.FileListFromTaskHeaders&gt;&gt; ListFromTaskNextWithHttpMessagesAsync(string nextPageLink, class Microsoft.Azure.Batch.Protocol.Models.FileListFromTaskNextOptions fileListFromTaskNextOptions, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.IFileOperations.ListFromTaskNextWithHttpMessagesAsync(System.String,Microsoft.Azure.Batch.Protocol.Models.FileListFromTaskNextOptions,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListFromTaskNextWithHttpMessagesAsync : string * Microsoft.Azure.Batch.Protocol.Models.FileListFromTaskNextOptions * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Batch.Protocol.Models.NodeFile&gt;, Microsoft.Azure.Batch.Protocol.Models.FileListFromTaskHeaders&gt;&gt;" Usage="iFileOperations.ListFromTaskNextWithHttpMessagesAsync (nextPageLink, fileListFromTaskNextOptions, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Batch.Protocol.Models.NodeFile&gt;,Microsoft.Azure.Batch.Protocol.Models.FileListFromTaskHeaders&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="fileListFromTaskNextOptions" Type="Microsoft.Azure.Batch.Protocol.Models.FileListFromTaskNextOptions" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="nextPageLink">
            <span data-ttu-id="c1c94-182">Die "NextLink" aus dem vorherigen erfolgreichen Aufruf List-Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="c1c94-182">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="fileListFromTaskNextOptions">
            <span data-ttu-id="c1c94-183">Zusätzliche Parameter für den Vorgang</span><span class="sxs-lookup"><span data-stu-id="c1c94-183">Additional parameters for the operation</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="c1c94-184">Die Header, die hinzugefügt werden auf Anforderung.</span><span class="sxs-lookup"><span data-stu-id="c1c94-184">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="c1c94-185">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="c1c94-185">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="c1c94-186">Listet die Dateien im Verzeichnis für eine Aufgabe auf seine Computeknoten.</span><span class="sxs-lookup"><span data-stu-id="c1c94-186">Lists the files in a task's directory on its compute node.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Azure.Batch.Protocol.Models.BatchErrorException">
            <span data-ttu-id="c1c94-187">Wird ausgelöst, wenn der Vorgang einen ungültigen Statuscode zurückgegeben hat.</span><span class="sxs-lookup"><span data-stu-id="c1c94-187">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="c1c94-188">Wird ausgelöst, wenn nicht die Antwort zu deserialisieren.</span><span class="sxs-lookup"><span data-stu-id="c1c94-188">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="c1c94-189">Wird ausgelöst, wenn ein erforderlicher Parameter null ist.</span><span class="sxs-lookup"><span data-stu-id="c1c94-189">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="ListFromTaskWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Batch.Protocol.Models.NodeFile&gt;,Microsoft.Azure.Batch.Protocol.Models.FileListFromTaskHeaders&gt;&gt; ListFromTaskWithHttpMessagesAsync (string jobId, string taskId, Nullable&lt;bool&gt; recursive = null, Microsoft.Azure.Batch.Protocol.Models.FileListFromTaskOptions fileListFromTaskOptions = null, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`2&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Batch.Protocol.Models.NodeFile&gt;, class Microsoft.Azure.Batch.Protocol.Models.FileListFromTaskHeaders&gt;&gt; ListFromTaskWithHttpMessagesAsync(string jobId, string taskId, valuetype System.Nullable`1&lt;bool&gt; recursive, class Microsoft.Azure.Batch.Protocol.Models.FileListFromTaskOptions fileListFromTaskOptions, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.IFileOperations.ListFromTaskWithHttpMessagesAsync(System.String,System.String,System.Nullable{System.Boolean},Microsoft.Azure.Batch.Protocol.Models.FileListFromTaskOptions,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListFromTaskWithHttpMessagesAsync : string * string * Nullable&lt;bool&gt; * Microsoft.Azure.Batch.Protocol.Models.FileListFromTaskOptions * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Batch.Protocol.Models.NodeFile&gt;, Microsoft.Azure.Batch.Protocol.Models.FileListFromTaskHeaders&gt;&gt;" Usage="iFileOperations.ListFromTaskWithHttpMessagesAsync (jobId, taskId, recursive, fileListFromTaskOptions, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Batch.Protocol.Models.NodeFile&gt;,Microsoft.Azure.Batch.Protocol.Models.FileListFromTaskHeaders&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="jobId" Type="System.String" />
        <Parameter Name="taskId" Type="System.String" />
        <Parameter Name="recursive" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="fileListFromTaskOptions" Type="Microsoft.Azure.Batch.Protocol.Models.FileListFromTaskOptions" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="jobId">
            <span data-ttu-id="c1c94-190">Die ID des Auftrags, der den Task enthält.</span><span class="sxs-lookup"><span data-stu-id="c1c94-190">The ID of the job that contains the task.</span></span>
            </param>
        <param name="taskId">
            <span data-ttu-id="c1c94-191">Die ID der Aufgabe, deren Dateien, die Sie auflisten möchten.</span><span class="sxs-lookup"><span data-stu-id="c1c94-191">The ID of the task whose files you want to list.</span></span>
            </param>
        <param name="recursive">
            <span data-ttu-id="c1c94-192">Ob untergeordnete Elemente auflisten des Verzeichnisses Aufgabe.</span><span class="sxs-lookup"><span data-stu-id="c1c94-192">Whether to list children of the task directory.</span></span> <span data-ttu-id="c1c94-193">Dieser Parameter kann in Kombination mit dem Filterparameter, um die Liste bestimmte Typen von Dateien verwendet werden.</span><span class="sxs-lookup"><span data-stu-id="c1c94-193">This parameter can be used in combination with the filter parameter to list specific type of files.</span></span>
            </param>
        <param name="fileListFromTaskOptions">
            <span data-ttu-id="c1c94-194">Zusätzliche Parameter für den Vorgang</span><span class="sxs-lookup"><span data-stu-id="c1c94-194">Additional parameters for the operation</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="c1c94-195">Die Header, die hinzugefügt werden auf Anforderung.</span><span class="sxs-lookup"><span data-stu-id="c1c94-195">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="c1c94-196">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="c1c94-196">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="c1c94-197">Listet die Dateien im Verzeichnis für eine Aufgabe auf seine Computeknoten.</span><span class="sxs-lookup"><span data-stu-id="c1c94-197">Lists the files in a task's directory on its compute node.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Azure.Batch.Protocol.Models.BatchErrorException">
            <span data-ttu-id="c1c94-198">Wird ausgelöst, wenn der Vorgang einen ungültigen Statuscode zurückgegeben hat.</span><span class="sxs-lookup"><span data-stu-id="c1c94-198">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="c1c94-199">Wird ausgelöst, wenn nicht die Antwort zu deserialisieren.</span><span class="sxs-lookup"><span data-stu-id="c1c94-199">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="c1c94-200">Wird ausgelöst, wenn ein erforderlicher Parameter null ist.</span><span class="sxs-lookup"><span data-stu-id="c1c94-200">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>