<Type Name="TransferManager" FullName="Microsoft.WindowsAzure.Storage.DataMovement.TransferManager">
  <TypeSignature Language="C#" Value="public static class TransferManager" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed TransferManager extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.WindowsAzure.Storage.DataMovement.TransferManager" />
  <TypeSignature Language="VB.NET" Value="Public Class TransferManager" />
  <TypeSignature Language="F#" Value="type TransferManager = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.WindowsAzure.Storage.DataMovement</AssemblyName>
    <AssemblyVersion>0.5.3.0</AssemblyVersion>
    <AssemblyVersion>0.7.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="75481-101">TransferManager-Klasse</span><span class="sxs-lookup"><span data-stu-id="75481-101">TransferManager class</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="Configurations">
      <MemberSignature Language="C#" Value="public static Microsoft.WindowsAzure.Storage.DataMovement.TransferConfigurations Configurations { get; }" />
      <MemberSignature Language="ILAsm" Value=".property class Microsoft.WindowsAzure.Storage.DataMovement.TransferConfigurations Configurations" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.DataMovement.TransferManager.Configurations" />
      <MemberSignature Language="VB.NET" Value="Public Shared ReadOnly Property Configurations As TransferConfigurations" />
      <MemberSignature Language="F#" Value="member this.Configurations : Microsoft.WindowsAzure.Storage.DataMovement.TransferConfigurations" Usage="Microsoft.WindowsAzure.Storage.DataMovement.TransferManager.Configurations" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage.DataMovement</AssemblyName>
        <AssemblyVersion>0.5.3.0</AssemblyVersion>
        <AssemblyVersion>0.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Storage.DataMovement.TransferConfigurations</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="75481-102">Ruft ab oder legt die Übertragung der paketübertragungs-Manager zugeordnete Konfigurationen</span><span class="sxs-lookup"><span data-stu-id="75481-102">Gets or sets the transfer configurations associated with the transfer manager</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CopyAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task CopyAsync (Microsoft.WindowsAzure.Storage.Blob.CloudBlob sourceBlob, Microsoft.WindowsAzure.Storage.Blob.CloudBlob destBlob, bool isServiceCopy);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task CopyAsync(class Microsoft.WindowsAzure.Storage.Blob.CloudBlob sourceBlob, class Microsoft.WindowsAzure.Storage.Blob.CloudBlob destBlob, bool isServiceCopy) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.DataMovement.TransferManager.CopyAsync(Microsoft.WindowsAzure.Storage.Blob.CloudBlob,Microsoft.WindowsAzure.Storage.Blob.CloudBlob,System.Boolean)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function CopyAsync (sourceBlob As CloudBlob, destBlob As CloudBlob, isServiceCopy As Boolean) As Task" />
      <MemberSignature Language="F#" Value="static member CopyAsync : Microsoft.WindowsAzure.Storage.Blob.CloudBlob * Microsoft.WindowsAzure.Storage.Blob.CloudBlob * bool -&gt; System.Threading.Tasks.Task" Usage="Microsoft.WindowsAzure.Storage.DataMovement.TransferManager.CopyAsync (sourceBlob, destBlob, isServiceCopy)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage.DataMovement</AssemblyName>
        <AssemblyVersion>0.5.3.0</AssemblyVersion>
        <AssemblyVersion>0.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="sourceBlob" Type="Microsoft.WindowsAzure.Storage.Blob.CloudBlob" />
        <Parameter Name="destBlob" Type="Microsoft.WindowsAzure.Storage.Blob.CloudBlob" />
        <Parameter Name="isServiceCopy" Type="System.Boolean" />
      </Parameters>
      <Docs>
        <param name="sourceBlob"><span data-ttu-id="75481-103">Die <see cref="T:Microsoft.WindowsAzure.Storage.Blob.CloudBlob" /> , der die Quelle Azure-Blob.</span><span class="sxs-lookup"><span data-stu-id="75481-103">The <see cref="T:Microsoft.WindowsAzure.Storage.Blob.CloudBlob" /> that is the source Azure blob.</span></span></param>
        <param name="destBlob"><span data-ttu-id="75481-104">Die <see cref="T:Microsoft.WindowsAzure.Storage.Blob.CloudBlob" /> , die das Ziel Azure-Blob.</span><span class="sxs-lookup"><span data-stu-id="75481-104">The <see cref="T:Microsoft.WindowsAzure.Storage.Blob.CloudBlob" /> that is the destination Azure blob.</span></span></param>
        <param name="isServiceCopy"><span data-ttu-id="75481-105">Ein Flag, das angibt, ob die Kopie aufseiten des Dienstes asynchrone Kopie oder nicht ist.</span><span class="sxs-lookup"><span data-stu-id="75481-105">A flag indicating whether the copy is service-side asynchronous copy or not.</span></span>
            <span data-ttu-id="75481-106">Wenn dieses Flag, auf "true" werden aufseiten des Dienstes asychronen Kopie festgelegt ist wird verwendet. Wenn dieses Flag auf "false" festgelegt ist, wird Datei zuerst von der Quelle heruntergeladen und anschließend auf Ziel hochgeladen.</span><span class="sxs-lookup"><span data-stu-id="75481-106">If this flag is set to true, service-side asychronous copy will be used; if this flag is set to false, file is downloaded from source first, then uploaded to destination.</span></span></param>
        <summary>
            <span data-ttu-id="75481-107">Kopieren von Inhalten, Eigenschaften und Metadaten von einem Azure-blob in einen anderen.</span><span class="sxs-lookup"><span data-stu-id="75481-107">Copy content, properties and metadata of one Azure blob to another.</span></span>
            </summary>
        <returns><span data-ttu-id="75481-108">Ein <see cref="T:System.Threading.Tasks.Task" />-Objekt, das den asynchronen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="75481-108">A <see cref="T:System.Threading.Tasks.Task" /> object that represents the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CopyAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task CopyAsync (Microsoft.WindowsAzure.Storage.Blob.CloudBlob sourceBlob, Microsoft.WindowsAzure.Storage.File.CloudFile destFile, bool isServiceCopy);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task CopyAsync(class Microsoft.WindowsAzure.Storage.Blob.CloudBlob sourceBlob, class Microsoft.WindowsAzure.Storage.File.CloudFile destFile, bool isServiceCopy) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.DataMovement.TransferManager.CopyAsync(Microsoft.WindowsAzure.Storage.Blob.CloudBlob,Microsoft.WindowsAzure.Storage.File.CloudFile,System.Boolean)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function CopyAsync (sourceBlob As CloudBlob, destFile As CloudFile, isServiceCopy As Boolean) As Task" />
      <MemberSignature Language="F#" Value="static member CopyAsync : Microsoft.WindowsAzure.Storage.Blob.CloudBlob * Microsoft.WindowsAzure.Storage.File.CloudFile * bool -&gt; System.Threading.Tasks.Task" Usage="Microsoft.WindowsAzure.Storage.DataMovement.TransferManager.CopyAsync (sourceBlob, destFile, isServiceCopy)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage.DataMovement</AssemblyName>
        <AssemblyVersion>0.5.3.0</AssemblyVersion>
        <AssemblyVersion>0.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="sourceBlob" Type="Microsoft.WindowsAzure.Storage.Blob.CloudBlob" />
        <Parameter Name="destFile" Type="Microsoft.WindowsAzure.Storage.File.CloudFile" />
        <Parameter Name="isServiceCopy" Type="System.Boolean" />
      </Parameters>
      <Docs>
        <param name="sourceBlob"><span data-ttu-id="75481-109">Die <see cref="T:Microsoft.WindowsAzure.Storage.Blob.CloudBlob" /> , der die Quelle Azure-Blob.</span><span class="sxs-lookup"><span data-stu-id="75481-109">The <see cref="T:Microsoft.WindowsAzure.Storage.Blob.CloudBlob" /> that is the source Azure blob.</span></span></param>
        <param name="destFile"><span data-ttu-id="75481-110">Die <see cref="T:Microsoft.WindowsAzure.Storage.File.CloudFile" /> , die das Ziel Azure-Datei.</span><span class="sxs-lookup"><span data-stu-id="75481-110">The <see cref="T:Microsoft.WindowsAzure.Storage.File.CloudFile" /> that is the destination Azure file.</span></span></param>
        <param name="isServiceCopy"><span data-ttu-id="75481-111">Ein Flag, das angibt, ob die Kopie aufseiten des Dienstes asynchrone Kopie oder nicht ist.</span><span class="sxs-lookup"><span data-stu-id="75481-111">A flag indicating whether the copy is service-side asynchronous copy or not.</span></span>
            <span data-ttu-id="75481-112">Wenn dieses Flag, auf "true" werden aufseiten des Dienstes asychronen Kopie festgelegt ist wird verwendet. Wenn dieses Flag auf "false" festgelegt ist, wird Datei zuerst von der Quelle heruntergeladen und anschließend auf Ziel hochgeladen.</span><span class="sxs-lookup"><span data-stu-id="75481-112">If this flag is set to true, service-side asychronous copy will be used; if this flag is set to false, file is downloaded from source first, then uploaded to destination.</span></span></param>
        <summary>
            <span data-ttu-id="75481-113">Kopieren von Inhalten, Eigenschaften und Metadaten von einem Azure-blob in einer Azure-Datei.</span><span class="sxs-lookup"><span data-stu-id="75481-113">Copy content, properties and metadata of an Azure blob to an Azure file.</span></span>
            </summary>
        <returns><span data-ttu-id="75481-114">Ein <see cref="T:System.Threading.Tasks.Task" />-Objekt, das den asynchronen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="75481-114">A <see cref="T:System.Threading.Tasks.Task" /> object that represents the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CopyAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task CopyAsync (Microsoft.WindowsAzure.Storage.File.CloudFile sourceFile, Microsoft.WindowsAzure.Storage.Blob.CloudBlob destBlob, bool isServiceCopy);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task CopyAsync(class Microsoft.WindowsAzure.Storage.File.CloudFile sourceFile, class Microsoft.WindowsAzure.Storage.Blob.CloudBlob destBlob, bool isServiceCopy) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.DataMovement.TransferManager.CopyAsync(Microsoft.WindowsAzure.Storage.File.CloudFile,Microsoft.WindowsAzure.Storage.Blob.CloudBlob,System.Boolean)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function CopyAsync (sourceFile As CloudFile, destBlob As CloudBlob, isServiceCopy As Boolean) As Task" />
      <MemberSignature Language="F#" Value="static member CopyAsync : Microsoft.WindowsAzure.Storage.File.CloudFile * Microsoft.WindowsAzure.Storage.Blob.CloudBlob * bool -&gt; System.Threading.Tasks.Task" Usage="Microsoft.WindowsAzure.Storage.DataMovement.TransferManager.CopyAsync (sourceFile, destBlob, isServiceCopy)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage.DataMovement</AssemblyName>
        <AssemblyVersion>0.5.3.0</AssemblyVersion>
        <AssemblyVersion>0.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="sourceFile" Type="Microsoft.WindowsAzure.Storage.File.CloudFile" />
        <Parameter Name="destBlob" Type="Microsoft.WindowsAzure.Storage.Blob.CloudBlob" />
        <Parameter Name="isServiceCopy" Type="System.Boolean" />
      </Parameters>
      <Docs>
        <param name="sourceFile"><span data-ttu-id="75481-115">Die <see cref="T:Microsoft.WindowsAzure.Storage.File.CloudFile" /> , der die Quelle Azure-Datei.</span><span class="sxs-lookup"><span data-stu-id="75481-115">The <see cref="T:Microsoft.WindowsAzure.Storage.File.CloudFile" /> that is the source Azure file.</span></span></param>
        <param name="destBlob"><span data-ttu-id="75481-116">Die <see cref="T:Microsoft.WindowsAzure.Storage.Blob.CloudBlob" /> , die das Ziel Azure-Blob.</span><span class="sxs-lookup"><span data-stu-id="75481-116">The <see cref="T:Microsoft.WindowsAzure.Storage.Blob.CloudBlob" /> that is the destination Azure blob.</span></span></param>
        <param name="isServiceCopy"><span data-ttu-id="75481-117">Ein Flag, das angibt, ob die Kopie aufseiten des Dienstes asynchrone Kopie oder nicht ist.</span><span class="sxs-lookup"><span data-stu-id="75481-117">A flag indicating whether the copy is service-side asynchronous copy or not.</span></span>
            <span data-ttu-id="75481-118">Wenn dieses Flag, auf "true" werden aufseiten des Dienstes asychronen Kopie festgelegt ist wird verwendet. Wenn dieses Flag auf "false" festgelegt ist, wird Datei zuerst von der Quelle heruntergeladen und anschließend auf Ziel hochgeladen.</span><span class="sxs-lookup"><span data-stu-id="75481-118">If this flag is set to true, service-side asychronous copy will be used; if this flag is set to false, file is downloaded from source first, then uploaded to destination.</span></span></param>
        <summary>
            <span data-ttu-id="75481-119">Kopieren Sie die Inhalte, Eigenschaften und Metadaten einer Azure-Datei in ein Azure-Blob.</span><span class="sxs-lookup"><span data-stu-id="75481-119">Copy content, properties and metadata of an Azure file to an Azure blob.</span></span>
            </summary>
        <returns><span data-ttu-id="75481-120">Ein <see cref="T:System.Threading.Tasks.Task" />-Objekt, das den asynchronen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="75481-120">A <see cref="T:System.Threading.Tasks.Task" /> object that represents the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CopyAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task CopyAsync (Microsoft.WindowsAzure.Storage.File.CloudFile sourceFile, Microsoft.WindowsAzure.Storage.File.CloudFile destFile, bool isServiceCopy);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task CopyAsync(class Microsoft.WindowsAzure.Storage.File.CloudFile sourceFile, class Microsoft.WindowsAzure.Storage.File.CloudFile destFile, bool isServiceCopy) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.DataMovement.TransferManager.CopyAsync(Microsoft.WindowsAzure.Storage.File.CloudFile,Microsoft.WindowsAzure.Storage.File.CloudFile,System.Boolean)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function CopyAsync (sourceFile As CloudFile, destFile As CloudFile, isServiceCopy As Boolean) As Task" />
      <MemberSignature Language="F#" Value="static member CopyAsync : Microsoft.WindowsAzure.Storage.File.CloudFile * Microsoft.WindowsAzure.Storage.File.CloudFile * bool -&gt; System.Threading.Tasks.Task" Usage="Microsoft.WindowsAzure.Storage.DataMovement.TransferManager.CopyAsync (sourceFile, destFile, isServiceCopy)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage.DataMovement</AssemblyName>
        <AssemblyVersion>0.5.3.0</AssemblyVersion>
        <AssemblyVersion>0.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="sourceFile" Type="Microsoft.WindowsAzure.Storage.File.CloudFile" />
        <Parameter Name="destFile" Type="Microsoft.WindowsAzure.Storage.File.CloudFile" />
        <Parameter Name="isServiceCopy" Type="System.Boolean" />
      </Parameters>
      <Docs>
        <param name="sourceFile"><span data-ttu-id="75481-121">Die <see cref="T:Microsoft.WindowsAzure.Storage.File.CloudFile" /> , der die Quelle Azure-Datei.</span><span class="sxs-lookup"><span data-stu-id="75481-121">The <see cref="T:Microsoft.WindowsAzure.Storage.File.CloudFile" /> that is the source Azure file.</span></span></param>
        <param name="destFile"><span data-ttu-id="75481-122">Die <see cref="T:Microsoft.WindowsAzure.Storage.File.CloudFile" /> , die das Ziel Azure-Datei.</span><span class="sxs-lookup"><span data-stu-id="75481-122">The <see cref="T:Microsoft.WindowsAzure.Storage.File.CloudFile" /> that is the destination Azure file.</span></span></param>
        <param name="isServiceCopy"><span data-ttu-id="75481-123">Ein Flag, das angibt, ob die Kopie aufseiten des Dienstes asynchrone Kopie oder nicht ist.</span><span class="sxs-lookup"><span data-stu-id="75481-123">A flag indicating whether the copy is service-side asynchronous copy or not.</span></span>
            <span data-ttu-id="75481-124">Wenn dieses Flag, auf "true" werden aufseiten des Dienstes asychronen Kopie festgelegt ist wird verwendet. Wenn dieses Flag auf "false" festgelegt ist, wird Datei zuerst von der Quelle heruntergeladen und anschließend auf Ziel hochgeladen.</span><span class="sxs-lookup"><span data-stu-id="75481-124">If this flag is set to true, service-side asychronous copy will be used; if this flag is set to false, file is downloaded from source first, then uploaded to destination.</span></span></param>
        <summary>
            <span data-ttu-id="75481-125">Kopieren von Inhalten, Eigenschaften und Metadaten einer Azure-Datei in eine andere.</span><span class="sxs-lookup"><span data-stu-id="75481-125">Copy content, properties and metadata of an Azure file to another.</span></span>
            </summary>
        <returns><span data-ttu-id="75481-126">Ein <see cref="T:System.Threading.Tasks.Task" />-Objekt, das den asynchronen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="75481-126">A <see cref="T:System.Threading.Tasks.Task" /> object that represents the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CopyAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task CopyAsync (Uri sourceUri, Microsoft.WindowsAzure.Storage.Blob.CloudBlob destBlob, bool isServiceCopy);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task CopyAsync(class System.Uri sourceUri, class Microsoft.WindowsAzure.Storage.Blob.CloudBlob destBlob, bool isServiceCopy) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.DataMovement.TransferManager.CopyAsync(System.Uri,Microsoft.WindowsAzure.Storage.Blob.CloudBlob,System.Boolean)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function CopyAsync (sourceUri As Uri, destBlob As CloudBlob, isServiceCopy As Boolean) As Task" />
      <MemberSignature Language="F#" Value="static member CopyAsync : Uri * Microsoft.WindowsAzure.Storage.Blob.CloudBlob * bool -&gt; System.Threading.Tasks.Task" Usage="Microsoft.WindowsAzure.Storage.DataMovement.TransferManager.CopyAsync (sourceUri, destBlob, isServiceCopy)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage.DataMovement</AssemblyName>
        <AssemblyVersion>0.5.3.0</AssemblyVersion>
        <AssemblyVersion>0.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="sourceUri" Type="System.Uri" />
        <Parameter Name="destBlob" Type="Microsoft.WindowsAzure.Storage.Blob.CloudBlob" />
        <Parameter Name="isServiceCopy" Type="System.Boolean" />
      </Parameters>
      <Docs>
        <param name="sourceUri"><span data-ttu-id="75481-127">Die <see cref="T:System.Uri" /> der Quelldatei.</span><span class="sxs-lookup"><span data-stu-id="75481-127">The <see cref="T:System.Uri" /> of the source file.</span></span></param>
        <param name="destBlob"><span data-ttu-id="75481-128">Die <see cref="T:Microsoft.WindowsAzure.Storage.Blob.CloudBlob" /> , die das Ziel Azure-Blob.</span><span class="sxs-lookup"><span data-stu-id="75481-128">The <see cref="T:Microsoft.WindowsAzure.Storage.Blob.CloudBlob" /> that is the destination Azure blob.</span></span></param>
        <param name="isServiceCopy"><span data-ttu-id="75481-129">Ein Flag, das angibt, ob die Kopie aufseiten des Dienstes asynchrone Kopie oder nicht ist.</span><span class="sxs-lookup"><span data-stu-id="75481-129">A flag indicating whether the copy is service-side asynchronous copy or not.</span></span>
            <span data-ttu-id="75481-130">Wenn dieses Flag, auf "true" werden aufseiten des Dienstes asychronen Kopie festgelegt ist wird verwendet. Wenn dieses Flag auf "false" festgelegt ist, wird Datei zuerst von der Quelle heruntergeladen und anschließend auf Ziel hochgeladen.</span><span class="sxs-lookup"><span data-stu-id="75481-130">If this flag is set to true, service-side asychronous copy will be used; if this flag is set to false, file is downloaded from source first, then uploaded to destination.</span></span></param>
        <summary>
            <span data-ttu-id="75481-131">Kopieren der Datei aus einem angegebenen URI auf einen Azure-Blob.</span><span class="sxs-lookup"><span data-stu-id="75481-131">Copy file from an specified URI to an Azure blob.</span></span>
            </summary>
        <returns><span data-ttu-id="75481-132">Ein <see cref="T:System.Threading.Tasks.Task" />-Objekt, das den asynchronen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="75481-132">A <see cref="T:System.Threading.Tasks.Task" /> object that represents the asynchronous operation.</span></span></returns>
        <remarks><span data-ttu-id="75481-133">Kopieren von einem URI auf Azure-Blob synchron wird nicht unterstützt.</span><span class="sxs-lookup"><span data-stu-id="75481-133">Copying from an URI to Azure blob synchronously is not supported yet.</span></span></remarks>
      </Docs>
    </Member>
    <Member MemberName="CopyAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task CopyAsync (Uri sourceUri, Microsoft.WindowsAzure.Storage.File.CloudFile destFile, bool isServiceCopy);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task CopyAsync(class System.Uri sourceUri, class Microsoft.WindowsAzure.Storage.File.CloudFile destFile, bool isServiceCopy) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.DataMovement.TransferManager.CopyAsync(System.Uri,Microsoft.WindowsAzure.Storage.File.CloudFile,System.Boolean)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function CopyAsync (sourceUri As Uri, destFile As CloudFile, isServiceCopy As Boolean) As Task" />
      <MemberSignature Language="F#" Value="static member CopyAsync : Uri * Microsoft.WindowsAzure.Storage.File.CloudFile * bool -&gt; System.Threading.Tasks.Task" Usage="Microsoft.WindowsAzure.Storage.DataMovement.TransferManager.CopyAsync (sourceUri, destFile, isServiceCopy)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage.DataMovement</AssemblyName>
        <AssemblyVersion>0.5.3.0</AssemblyVersion>
        <AssemblyVersion>0.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="sourceUri" Type="System.Uri" />
        <Parameter Name="destFile" Type="Microsoft.WindowsAzure.Storage.File.CloudFile" />
        <Parameter Name="isServiceCopy" Type="System.Boolean" />
      </Parameters>
      <Docs>
        <param name="sourceUri"><span data-ttu-id="75481-134">Die <see cref="T:System.Uri" /> der Quelldatei.</span><span class="sxs-lookup"><span data-stu-id="75481-134">The <see cref="T:System.Uri" /> of the source file.</span></span></param>
        <param name="destFile"><span data-ttu-id="75481-135">Die <see cref="T:Microsoft.WindowsAzure.Storage.File.CloudFile" /> , die das Ziel Azure-Datei.</span><span class="sxs-lookup"><span data-stu-id="75481-135">The <see cref="T:Microsoft.WindowsAzure.Storage.File.CloudFile" /> that is the destination Azure file.</span></span></param>
        <param name="isServiceCopy"><span data-ttu-id="75481-136">Ein Flag, das angibt, ob die Kopie aufseiten des Dienstes asynchrone Kopie oder nicht ist.</span><span class="sxs-lookup"><span data-stu-id="75481-136">A flag indicating whether the copy is service-side asynchronous copy or not.</span></span>
            <span data-ttu-id="75481-137">Wenn dieses Flag, auf "true" werden aufseiten des Dienstes asychronen Kopie festgelegt ist wird verwendet. Wenn dieses Flag auf "false" festgelegt ist, wird Datei zuerst von der Quelle heruntergeladen und anschließend auf Ziel hochgeladen.</span><span class="sxs-lookup"><span data-stu-id="75481-137">If this flag is set to true, service-side asychronous copy will be used; if this flag is set to false, file is downloaded from source first, then uploaded to destination.</span></span></param>
        <summary>
            <span data-ttu-id="75481-138">Kopieren der Datei aus einem angegebenen URI auf eine Azure-Datei.</span><span class="sxs-lookup"><span data-stu-id="75481-138">Copy file from an specified URI to an Azure file.</span></span>
            </summary>
        <returns><span data-ttu-id="75481-139">Ein <see cref="T:System.Threading.Tasks.Task" />-Objekt, das den asynchronen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="75481-139">A <see cref="T:System.Threading.Tasks.Task" /> object that represents the asynchronous operation.</span></span></returns>
        <remarks><span data-ttu-id="75481-140">Kopieren von einem URI auf Azure-Datei synchron ist noch nicht unterstützt.</span><span class="sxs-lookup"><span data-stu-id="75481-140">Copying from an URI to Azure file synchronously is not supported yet.</span></span></remarks>
      </Docs>
    </Member>
    <Member MemberName="CopyAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task CopyAsync (Microsoft.WindowsAzure.Storage.Blob.CloudBlob sourceBlob, Microsoft.WindowsAzure.Storage.Blob.CloudBlob destBlob, bool isServiceCopy, Microsoft.WindowsAzure.Storage.DataMovement.CopyOptions options, Microsoft.WindowsAzure.Storage.DataMovement.SingleTransferContext context);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task CopyAsync(class Microsoft.WindowsAzure.Storage.Blob.CloudBlob sourceBlob, class Microsoft.WindowsAzure.Storage.Blob.CloudBlob destBlob, bool isServiceCopy, class Microsoft.WindowsAzure.Storage.DataMovement.CopyOptions options, class Microsoft.WindowsAzure.Storage.DataMovement.SingleTransferContext context) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.DataMovement.TransferManager.CopyAsync(Microsoft.WindowsAzure.Storage.Blob.CloudBlob,Microsoft.WindowsAzure.Storage.Blob.CloudBlob,System.Boolean,Microsoft.WindowsAzure.Storage.DataMovement.CopyOptions,Microsoft.WindowsAzure.Storage.DataMovement.SingleTransferContext)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function CopyAsync (sourceBlob As CloudBlob, destBlob As CloudBlob, isServiceCopy As Boolean, options As CopyOptions, context As SingleTransferContext) As Task" />
      <MemberSignature Language="F#" Value="static member CopyAsync : Microsoft.WindowsAzure.Storage.Blob.CloudBlob * Microsoft.WindowsAzure.Storage.Blob.CloudBlob * bool * Microsoft.WindowsAzure.Storage.DataMovement.CopyOptions * Microsoft.WindowsAzure.Storage.DataMovement.SingleTransferContext -&gt; System.Threading.Tasks.Task" Usage="Microsoft.WindowsAzure.Storage.DataMovement.TransferManager.CopyAsync (sourceBlob, destBlob, isServiceCopy, options, context)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage.DataMovement</AssemblyName>
        <AssemblyVersion>0.5.3.0</AssemblyVersion>
        <AssemblyVersion>0.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="sourceBlob" Type="Microsoft.WindowsAzure.Storage.Blob.CloudBlob" />
        <Parameter Name="destBlob" Type="Microsoft.WindowsAzure.Storage.Blob.CloudBlob" />
        <Parameter Name="isServiceCopy" Type="System.Boolean" />
        <Parameter Name="options" Type="Microsoft.WindowsAzure.Storage.DataMovement.CopyOptions" />
        <Parameter Name="context" Type="Microsoft.WindowsAzure.Storage.DataMovement.SingleTransferContext" />
      </Parameters>
      <Docs>
        <param name="sourceBlob"><span data-ttu-id="75481-141">Die <see cref="T:Microsoft.WindowsAzure.Storage.Blob.CloudBlob" /> , der die Quelle Azure-Blob.</span><span class="sxs-lookup"><span data-stu-id="75481-141">The <see cref="T:Microsoft.WindowsAzure.Storage.Blob.CloudBlob" /> that is the source Azure blob.</span></span></param>
        <param name="destBlob"><span data-ttu-id="75481-142">Die <see cref="T:Microsoft.WindowsAzure.Storage.Blob.CloudBlob" /> , die das Ziel Azure-Blob.</span><span class="sxs-lookup"><span data-stu-id="75481-142">The <see cref="T:Microsoft.WindowsAzure.Storage.Blob.CloudBlob" /> that is the destination Azure blob.</span></span></param>
        <param name="isServiceCopy"><span data-ttu-id="75481-143">Ein Flag, das angibt, ob die Kopie aufseiten des Dienstes asynchrone Kopie oder nicht ist.</span><span class="sxs-lookup"><span data-stu-id="75481-143">A flag indicating whether the copy is service-side asynchronous copy or not.</span></span>
            <span data-ttu-id="75481-144">Wenn dieses Flag, auf "true" werden aufseiten des Dienstes asychronen Kopie festgelegt ist wird verwendet. Wenn dieses Flag auf "false" festgelegt ist, wird Datei zuerst von der Quelle heruntergeladen und anschließend auf Ziel hochgeladen.</span><span class="sxs-lookup"><span data-stu-id="75481-144">If this flag is set to true, service-side asychronous copy will be used; if this flag is set to false, file is downloaded from source first, then uploaded to destination.</span></span></param>
        <param name="options"><span data-ttu-id="75481-145">Ein <see cref="T:Microsoft.WindowsAzure.Storage.DataMovement.CopyOptions" /> -Objekt, das zusätzliche Optionen für den Vorgang angibt.</span><span class="sxs-lookup"><span data-stu-id="75481-145">A <see cref="T:Microsoft.WindowsAzure.Storage.DataMovement.CopyOptions" /> object that specifies additional options for the operation.</span></span></param>
        <param name="context"><span data-ttu-id="75481-146">Ein <see cref="T:Microsoft.WindowsAzure.Storage.DataMovement.SingleTransferContext" /> -Objekt, das den Kontext für den aktuellen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="75481-146">A <see cref="T:Microsoft.WindowsAzure.Storage.DataMovement.SingleTransferContext" /> object that represents the context for the current operation.</span></span></param>
        <summary>
            <span data-ttu-id="75481-147">Kopieren von Inhalten, Eigenschaften und Metadaten von einem Azure-blob in einen anderen.</span><span class="sxs-lookup"><span data-stu-id="75481-147">Copy content, properties and metadata of one Azure blob to another.</span></span>
            </summary>
        <returns><span data-ttu-id="75481-148">Ein <see cref="T:System.Threading.Tasks.Task" />-Objekt, das den asynchronen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="75481-148">A <see cref="T:System.Threading.Tasks.Task" /> object that represents the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CopyAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task CopyAsync (Microsoft.WindowsAzure.Storage.Blob.CloudBlob sourceBlob, Microsoft.WindowsAzure.Storage.File.CloudFile destFile, bool isServiceCopy, Microsoft.WindowsAzure.Storage.DataMovement.CopyOptions options, Microsoft.WindowsAzure.Storage.DataMovement.SingleTransferContext context);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task CopyAsync(class Microsoft.WindowsAzure.Storage.Blob.CloudBlob sourceBlob, class Microsoft.WindowsAzure.Storage.File.CloudFile destFile, bool isServiceCopy, class Microsoft.WindowsAzure.Storage.DataMovement.CopyOptions options, class Microsoft.WindowsAzure.Storage.DataMovement.SingleTransferContext context) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.DataMovement.TransferManager.CopyAsync(Microsoft.WindowsAzure.Storage.Blob.CloudBlob,Microsoft.WindowsAzure.Storage.File.CloudFile,System.Boolean,Microsoft.WindowsAzure.Storage.DataMovement.CopyOptions,Microsoft.WindowsAzure.Storage.DataMovement.SingleTransferContext)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function CopyAsync (sourceBlob As CloudBlob, destFile As CloudFile, isServiceCopy As Boolean, options As CopyOptions, context As SingleTransferContext) As Task" />
      <MemberSignature Language="F#" Value="static member CopyAsync : Microsoft.WindowsAzure.Storage.Blob.CloudBlob * Microsoft.WindowsAzure.Storage.File.CloudFile * bool * Microsoft.WindowsAzure.Storage.DataMovement.CopyOptions * Microsoft.WindowsAzure.Storage.DataMovement.SingleTransferContext -&gt; System.Threading.Tasks.Task" Usage="Microsoft.WindowsAzure.Storage.DataMovement.TransferManager.CopyAsync (sourceBlob, destFile, isServiceCopy, options, context)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage.DataMovement</AssemblyName>
        <AssemblyVersion>0.5.3.0</AssemblyVersion>
        <AssemblyVersion>0.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="sourceBlob" Type="Microsoft.WindowsAzure.Storage.Blob.CloudBlob" />
        <Parameter Name="destFile" Type="Microsoft.WindowsAzure.Storage.File.CloudFile" />
        <Parameter Name="isServiceCopy" Type="System.Boolean" />
        <Parameter Name="options" Type="Microsoft.WindowsAzure.Storage.DataMovement.CopyOptions" />
        <Parameter Name="context" Type="Microsoft.WindowsAzure.Storage.DataMovement.SingleTransferContext" />
      </Parameters>
      <Docs>
        <param name="sourceBlob"><span data-ttu-id="75481-149">Die <see cref="T:Microsoft.WindowsAzure.Storage.Blob.CloudBlob" /> , der die Quelle Azure-Blob.</span><span class="sxs-lookup"><span data-stu-id="75481-149">The <see cref="T:Microsoft.WindowsAzure.Storage.Blob.CloudBlob" /> that is the source Azure blob.</span></span></param>
        <param name="destFile"><span data-ttu-id="75481-150">Die <see cref="T:Microsoft.WindowsAzure.Storage.File.CloudFile" /> , die das Ziel Azure-Datei.</span><span class="sxs-lookup"><span data-stu-id="75481-150">The <see cref="T:Microsoft.WindowsAzure.Storage.File.CloudFile" /> that is the destination Azure file.</span></span></param>
        <param name="isServiceCopy"><span data-ttu-id="75481-151">Ein Flag, das angibt, ob die Kopie aufseiten des Dienstes asynchrone Kopie oder nicht ist.</span><span class="sxs-lookup"><span data-stu-id="75481-151">A flag indicating whether the copy is service-side asynchronous copy or not.</span></span>
            <span data-ttu-id="75481-152">Wenn dieses Flag, auf "true" werden aufseiten des Dienstes asychronen Kopie festgelegt ist wird verwendet. Wenn dieses Flag auf "false" festgelegt ist, wird Datei zuerst von der Quelle heruntergeladen und anschließend auf Ziel hochgeladen.</span><span class="sxs-lookup"><span data-stu-id="75481-152">If this flag is set to true, service-side asychronous copy will be used; if this flag is set to false, file is downloaded from source first, then uploaded to destination.</span></span></param>
        <param name="options"><span data-ttu-id="75481-153">Ein <see cref="T:Microsoft.WindowsAzure.Storage.DataMovement.CopyOptions" /> -Objekt, das zusätzliche Optionen für den Vorgang angibt.</span><span class="sxs-lookup"><span data-stu-id="75481-153">A <see cref="T:Microsoft.WindowsAzure.Storage.DataMovement.CopyOptions" /> object that specifies additional options for the operation.</span></span></param>
        <param name="context"><span data-ttu-id="75481-154">Ein <see cref="T:Microsoft.WindowsAzure.Storage.DataMovement.TransferContext" /> -Objekt, das den Kontext für den aktuellen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="75481-154">A <see cref="T:Microsoft.WindowsAzure.Storage.DataMovement.TransferContext" /> object that represents the context for the current operation.</span></span></param>
        <summary>
            <span data-ttu-id="75481-155">Kopieren von Inhalten, Eigenschaften und Metadaten von einem Azure-blob in einer Azure-Datei.</span><span class="sxs-lookup"><span data-stu-id="75481-155">Copy content, properties and metadata of an Azure blob to an Azure file.</span></span>
            </summary>
        <returns><span data-ttu-id="75481-156">Ein <see cref="T:System.Threading.Tasks.Task" />-Objekt, das den asynchronen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="75481-156">A <see cref="T:System.Threading.Tasks.Task" /> object that represents the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CopyAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task CopyAsync (Microsoft.WindowsAzure.Storage.File.CloudFile sourceFile, Microsoft.WindowsAzure.Storage.Blob.CloudBlob destBlob, bool isServiceCopy, Microsoft.WindowsAzure.Storage.DataMovement.CopyOptions options, Microsoft.WindowsAzure.Storage.DataMovement.SingleTransferContext context);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task CopyAsync(class Microsoft.WindowsAzure.Storage.File.CloudFile sourceFile, class Microsoft.WindowsAzure.Storage.Blob.CloudBlob destBlob, bool isServiceCopy, class Microsoft.WindowsAzure.Storage.DataMovement.CopyOptions options, class Microsoft.WindowsAzure.Storage.DataMovement.SingleTransferContext context) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.DataMovement.TransferManager.CopyAsync(Microsoft.WindowsAzure.Storage.File.CloudFile,Microsoft.WindowsAzure.Storage.Blob.CloudBlob,System.Boolean,Microsoft.WindowsAzure.Storage.DataMovement.CopyOptions,Microsoft.WindowsAzure.Storage.DataMovement.SingleTransferContext)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function CopyAsync (sourceFile As CloudFile, destBlob As CloudBlob, isServiceCopy As Boolean, options As CopyOptions, context As SingleTransferContext) As Task" />
      <MemberSignature Language="F#" Value="static member CopyAsync : Microsoft.WindowsAzure.Storage.File.CloudFile * Microsoft.WindowsAzure.Storage.Blob.CloudBlob * bool * Microsoft.WindowsAzure.Storage.DataMovement.CopyOptions * Microsoft.WindowsAzure.Storage.DataMovement.SingleTransferContext -&gt; System.Threading.Tasks.Task" Usage="Microsoft.WindowsAzure.Storage.DataMovement.TransferManager.CopyAsync (sourceFile, destBlob, isServiceCopy, options, context)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage.DataMovement</AssemblyName>
        <AssemblyVersion>0.5.3.0</AssemblyVersion>
        <AssemblyVersion>0.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="sourceFile" Type="Microsoft.WindowsAzure.Storage.File.CloudFile" />
        <Parameter Name="destBlob" Type="Microsoft.WindowsAzure.Storage.Blob.CloudBlob" />
        <Parameter Name="isServiceCopy" Type="System.Boolean" />
        <Parameter Name="options" Type="Microsoft.WindowsAzure.Storage.DataMovement.CopyOptions" />
        <Parameter Name="context" Type="Microsoft.WindowsAzure.Storage.DataMovement.SingleTransferContext" />
      </Parameters>
      <Docs>
        <param name="sourceFile"><span data-ttu-id="75481-157">Die <see cref="T:Microsoft.WindowsAzure.Storage.File.CloudFile" /> , der die Quelle Azure-Datei.</span><span class="sxs-lookup"><span data-stu-id="75481-157">The <see cref="T:Microsoft.WindowsAzure.Storage.File.CloudFile" /> that is the source Azure file.</span></span></param>
        <param name="destBlob"><span data-ttu-id="75481-158">Die <see cref="T:Microsoft.WindowsAzure.Storage.Blob.CloudBlob" /> , die das Ziel Azure-Blob.</span><span class="sxs-lookup"><span data-stu-id="75481-158">The <see cref="T:Microsoft.WindowsAzure.Storage.Blob.CloudBlob" /> that is the destination Azure blob.</span></span></param>
        <param name="isServiceCopy"><span data-ttu-id="75481-159">Ein Flag, das angibt, ob die Kopie aufseiten des Dienstes asynchrone Kopie oder nicht ist.</span><span class="sxs-lookup"><span data-stu-id="75481-159">A flag indicating whether the copy is service-side asynchronous copy or not.</span></span>
            <span data-ttu-id="75481-160">Wenn dieses Flag, auf "true" werden aufseiten des Dienstes asychronen Kopie festgelegt ist wird verwendet. Wenn dieses Flag auf "false" festgelegt ist, wird Datei zuerst von der Quelle heruntergeladen und anschließend auf Ziel hochgeladen.</span><span class="sxs-lookup"><span data-stu-id="75481-160">If this flag is set to true, service-side asychronous copy will be used; if this flag is set to false, file is downloaded from source first, then uploaded to destination.</span></span></param>
        <param name="options"><span data-ttu-id="75481-161">Ein <see cref="T:Microsoft.WindowsAzure.Storage.DataMovement.CopyOptions" /> -Objekt, das zusätzliche Optionen für den Vorgang angibt.</span><span class="sxs-lookup"><span data-stu-id="75481-161">A <see cref="T:Microsoft.WindowsAzure.Storage.DataMovement.CopyOptions" /> object that specifies additional options for the operation.</span></span></param>
        <param name="context"><span data-ttu-id="75481-162">Ein <see cref="T:Microsoft.WindowsAzure.Storage.DataMovement.SingleTransferContext" /> -Objekt, das den Kontext für den aktuellen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="75481-162">A <see cref="T:Microsoft.WindowsAzure.Storage.DataMovement.SingleTransferContext" /> object that represents the context for the current operation.</span></span></param>
        <summary>
            <span data-ttu-id="75481-163">Kopieren Sie die Inhalte, Eigenschaften und Metadaten einer Azure-Datei in ein Azure-Blob.</span><span class="sxs-lookup"><span data-stu-id="75481-163">Copy content, properties and metadata of an Azure file to an Azure blob.</span></span>
            </summary>
        <returns><span data-ttu-id="75481-164">Ein <see cref="T:System.Threading.Tasks.Task" />-Objekt, das den asynchronen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="75481-164">A <see cref="T:System.Threading.Tasks.Task" /> object that represents the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CopyAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task CopyAsync (Microsoft.WindowsAzure.Storage.File.CloudFile sourceFile, Microsoft.WindowsAzure.Storage.File.CloudFile destFile, bool isServiceCopy, Microsoft.WindowsAzure.Storage.DataMovement.CopyOptions options, Microsoft.WindowsAzure.Storage.DataMovement.SingleTransferContext context);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task CopyAsync(class Microsoft.WindowsAzure.Storage.File.CloudFile sourceFile, class Microsoft.WindowsAzure.Storage.File.CloudFile destFile, bool isServiceCopy, class Microsoft.WindowsAzure.Storage.DataMovement.CopyOptions options, class Microsoft.WindowsAzure.Storage.DataMovement.SingleTransferContext context) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.DataMovement.TransferManager.CopyAsync(Microsoft.WindowsAzure.Storage.File.CloudFile,Microsoft.WindowsAzure.Storage.File.CloudFile,System.Boolean,Microsoft.WindowsAzure.Storage.DataMovement.CopyOptions,Microsoft.WindowsAzure.Storage.DataMovement.SingleTransferContext)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function CopyAsync (sourceFile As CloudFile, destFile As CloudFile, isServiceCopy As Boolean, options As CopyOptions, context As SingleTransferContext) As Task" />
      <MemberSignature Language="F#" Value="static member CopyAsync : Microsoft.WindowsAzure.Storage.File.CloudFile * Microsoft.WindowsAzure.Storage.File.CloudFile * bool * Microsoft.WindowsAzure.Storage.DataMovement.CopyOptions * Microsoft.WindowsAzure.Storage.DataMovement.SingleTransferContext -&gt; System.Threading.Tasks.Task" Usage="Microsoft.WindowsAzure.Storage.DataMovement.TransferManager.CopyAsync (sourceFile, destFile, isServiceCopy, options, context)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage.DataMovement</AssemblyName>
        <AssemblyVersion>0.5.3.0</AssemblyVersion>
        <AssemblyVersion>0.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="sourceFile" Type="Microsoft.WindowsAzure.Storage.File.CloudFile" />
        <Parameter Name="destFile" Type="Microsoft.WindowsAzure.Storage.File.CloudFile" />
        <Parameter Name="isServiceCopy" Type="System.Boolean" />
        <Parameter Name="options" Type="Microsoft.WindowsAzure.Storage.DataMovement.CopyOptions" />
        <Parameter Name="context" Type="Microsoft.WindowsAzure.Storage.DataMovement.SingleTransferContext" />
      </Parameters>
      <Docs>
        <param name="sourceFile"><span data-ttu-id="75481-165">Die <see cref="T:Microsoft.WindowsAzure.Storage.File.CloudFile" /> , der die Quelle Azure-Datei.</span><span class="sxs-lookup"><span data-stu-id="75481-165">The <see cref="T:Microsoft.WindowsAzure.Storage.File.CloudFile" /> that is the source Azure file.</span></span></param>
        <param name="destFile"><span data-ttu-id="75481-166">Die <see cref="T:Microsoft.WindowsAzure.Storage.File.CloudFile" /> , die das Ziel Azure-Datei.</span><span class="sxs-lookup"><span data-stu-id="75481-166">The <see cref="T:Microsoft.WindowsAzure.Storage.File.CloudFile" /> that is the destination Azure file.</span></span></param>
        <param name="isServiceCopy"><span data-ttu-id="75481-167">Ein Flag, das angibt, ob die Kopie aufseiten des Dienstes asynchrone Kopie oder nicht ist.</span><span class="sxs-lookup"><span data-stu-id="75481-167">A flag indicating whether the copy is service-side asynchronous copy or not.</span></span>
            <span data-ttu-id="75481-168">Wenn dieses Flag, auf "true" werden aufseiten des Dienstes asychronen Kopie festgelegt ist wird verwendet. Wenn dieses Flag auf "false" festgelegt ist, wird Datei zuerst von der Quelle heruntergeladen und anschließend auf Ziel hochgeladen.</span><span class="sxs-lookup"><span data-stu-id="75481-168">If this flag is set to true, service-side asychronous copy will be used; if this flag is set to false, file is downloaded from source first, then uploaded to destination.</span></span></param>
        <param name="options"><span data-ttu-id="75481-169">Ein <see cref="T:Microsoft.WindowsAzure.Storage.DataMovement.CopyOptions" /> -Objekt, das zusätzliche Optionen für den Vorgang angibt.</span><span class="sxs-lookup"><span data-stu-id="75481-169">A <see cref="T:Microsoft.WindowsAzure.Storage.DataMovement.CopyOptions" /> object that specifies additional options for the operation.</span></span></param>
        <param name="context"><span data-ttu-id="75481-170">Ein <see cref="T:Microsoft.WindowsAzure.Storage.DataMovement.SingleTransferContext" /> -Objekt, das den Kontext für den aktuellen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="75481-170">A <see cref="T:Microsoft.WindowsAzure.Storage.DataMovement.SingleTransferContext" /> object that represents the context for the current operation.</span></span></param>
        <summary>
            <span data-ttu-id="75481-171">Kopieren von Inhalten, Eigenschaften und Metadaten einer Azure-Datei in eine andere.</span><span class="sxs-lookup"><span data-stu-id="75481-171">Copy content, properties and metadata of an Azure file to another.</span></span>
            </summary>
        <returns><span data-ttu-id="75481-172">Ein <see cref="T:System.Threading.Tasks.Task" />-Objekt, das den asynchronen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="75481-172">A <see cref="T:System.Threading.Tasks.Task" /> object that represents the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CopyAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task CopyAsync (Uri sourceUri, Microsoft.WindowsAzure.Storage.Blob.CloudBlob destBlob, bool isServiceCopy, Microsoft.WindowsAzure.Storage.DataMovement.CopyOptions options, Microsoft.WindowsAzure.Storage.DataMovement.SingleTransferContext context);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task CopyAsync(class System.Uri sourceUri, class Microsoft.WindowsAzure.Storage.Blob.CloudBlob destBlob, bool isServiceCopy, class Microsoft.WindowsAzure.Storage.DataMovement.CopyOptions options, class Microsoft.WindowsAzure.Storage.DataMovement.SingleTransferContext context) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.DataMovement.TransferManager.CopyAsync(System.Uri,Microsoft.WindowsAzure.Storage.Blob.CloudBlob,System.Boolean,Microsoft.WindowsAzure.Storage.DataMovement.CopyOptions,Microsoft.WindowsAzure.Storage.DataMovement.SingleTransferContext)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function CopyAsync (sourceUri As Uri, destBlob As CloudBlob, isServiceCopy As Boolean, options As CopyOptions, context As SingleTransferContext) As Task" />
      <MemberSignature Language="F#" Value="static member CopyAsync : Uri * Microsoft.WindowsAzure.Storage.Blob.CloudBlob * bool * Microsoft.WindowsAzure.Storage.DataMovement.CopyOptions * Microsoft.WindowsAzure.Storage.DataMovement.SingleTransferContext -&gt; System.Threading.Tasks.Task" Usage="Microsoft.WindowsAzure.Storage.DataMovement.TransferManager.CopyAsync (sourceUri, destBlob, isServiceCopy, options, context)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage.DataMovement</AssemblyName>
        <AssemblyVersion>0.5.3.0</AssemblyVersion>
        <AssemblyVersion>0.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="sourceUri" Type="System.Uri" />
        <Parameter Name="destBlob" Type="Microsoft.WindowsAzure.Storage.Blob.CloudBlob" />
        <Parameter Name="isServiceCopy" Type="System.Boolean" />
        <Parameter Name="options" Type="Microsoft.WindowsAzure.Storage.DataMovement.CopyOptions" />
        <Parameter Name="context" Type="Microsoft.WindowsAzure.Storage.DataMovement.SingleTransferContext" />
      </Parameters>
      <Docs>
        <param name="sourceUri"><span data-ttu-id="75481-173">Die <see cref="T:System.Uri" /> der Quelldatei.</span><span class="sxs-lookup"><span data-stu-id="75481-173">The <see cref="T:System.Uri" /> of the source file.</span></span></param>
        <param name="destBlob"><span data-ttu-id="75481-174">Die <see cref="T:Microsoft.WindowsAzure.Storage.Blob.CloudBlob" /> , die das Ziel Azure-Blob.</span><span class="sxs-lookup"><span data-stu-id="75481-174">The <see cref="T:Microsoft.WindowsAzure.Storage.Blob.CloudBlob" /> that is the destination Azure blob.</span></span></param>
        <param name="isServiceCopy"><span data-ttu-id="75481-175">Ein Flag, das angibt, ob die Kopie aufseiten des Dienstes asynchrone Kopie oder nicht ist.</span><span class="sxs-lookup"><span data-stu-id="75481-175">A flag indicating whether the copy is service-side asynchronous copy or not.</span></span>
            <span data-ttu-id="75481-176">Wenn dieses Flag, auf "true" werden aufseiten des Dienstes asychronen Kopie festgelegt ist wird verwendet. Wenn dieses Flag auf "false" festgelegt ist, wird Datei zuerst von der Quelle heruntergeladen und anschließend auf Ziel hochgeladen.</span><span class="sxs-lookup"><span data-stu-id="75481-176">If this flag is set to true, service-side asychronous copy will be used; if this flag is set to false, file is downloaded from source first, then uploaded to destination.</span></span></param>
        <param name="options"><span data-ttu-id="75481-177">Ein <see cref="T:Microsoft.WindowsAzure.Storage.DataMovement.CopyOptions" /> -Objekt, das zusätzliche Optionen für den Vorgang angibt.</span><span class="sxs-lookup"><span data-stu-id="75481-177">A <see cref="T:Microsoft.WindowsAzure.Storage.DataMovement.CopyOptions" /> object that specifies additional options for the operation.</span></span></param>
        <param name="context"><span data-ttu-id="75481-178">Ein <see cref="T:Microsoft.WindowsAzure.Storage.DataMovement.SingleTransferContext" /> -Objekt, das den Kontext für den aktuellen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="75481-178">A <see cref="T:Microsoft.WindowsAzure.Storage.DataMovement.SingleTransferContext" /> object that represents the context for the current operation.</span></span></param>
        <summary>
            <span data-ttu-id="75481-179">Kopieren der Datei aus einem angegebenen URI auf einen Azure-Blob.</span><span class="sxs-lookup"><span data-stu-id="75481-179">Copy file from an specified URI to an Azure blob.</span></span>
            </summary>
        <returns><span data-ttu-id="75481-180">Ein <see cref="T:System.Threading.Tasks.Task" />-Objekt, das den asynchronen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="75481-180">A <see cref="T:System.Threading.Tasks.Task" /> object that represents the asynchronous operation.</span></span></returns>
        <remarks><span data-ttu-id="75481-181">Kopieren von einem URI auf Azure-Blob synchron wird nicht unterstützt.</span><span class="sxs-lookup"><span data-stu-id="75481-181">Copying from an URI to Azure blob synchronously is not supported yet.</span></span></remarks>
      </Docs>
    </Member>
    <Member MemberName="CopyAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task CopyAsync (Uri sourceUri, Microsoft.WindowsAzure.Storage.File.CloudFile destFile, bool isServiceCopy, Microsoft.WindowsAzure.Storage.DataMovement.CopyOptions options, Microsoft.WindowsAzure.Storage.DataMovement.SingleTransferContext context);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task CopyAsync(class System.Uri sourceUri, class Microsoft.WindowsAzure.Storage.File.CloudFile destFile, bool isServiceCopy, class Microsoft.WindowsAzure.Storage.DataMovement.CopyOptions options, class Microsoft.WindowsAzure.Storage.DataMovement.SingleTransferContext context) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.DataMovement.TransferManager.CopyAsync(System.Uri,Microsoft.WindowsAzure.Storage.File.CloudFile,System.Boolean,Microsoft.WindowsAzure.Storage.DataMovement.CopyOptions,Microsoft.WindowsAzure.Storage.DataMovement.SingleTransferContext)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function CopyAsync (sourceUri As Uri, destFile As CloudFile, isServiceCopy As Boolean, options As CopyOptions, context As SingleTransferContext) As Task" />
      <MemberSignature Language="F#" Value="static member CopyAsync : Uri * Microsoft.WindowsAzure.Storage.File.CloudFile * bool * Microsoft.WindowsAzure.Storage.DataMovement.CopyOptions * Microsoft.WindowsAzure.Storage.DataMovement.SingleTransferContext -&gt; System.Threading.Tasks.Task" Usage="Microsoft.WindowsAzure.Storage.DataMovement.TransferManager.CopyAsync (sourceUri, destFile, isServiceCopy, options, context)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage.DataMovement</AssemblyName>
        <AssemblyVersion>0.5.3.0</AssemblyVersion>
        <AssemblyVersion>0.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="sourceUri" Type="System.Uri" />
        <Parameter Name="destFile" Type="Microsoft.WindowsAzure.Storage.File.CloudFile" />
        <Parameter Name="isServiceCopy" Type="System.Boolean" />
        <Parameter Name="options" Type="Microsoft.WindowsAzure.Storage.DataMovement.CopyOptions" />
        <Parameter Name="context" Type="Microsoft.WindowsAzure.Storage.DataMovement.SingleTransferContext" />
      </Parameters>
      <Docs>
        <param name="sourceUri"><span data-ttu-id="75481-182">Die <see cref="T:System.Uri" /> der Quelldatei.</span><span class="sxs-lookup"><span data-stu-id="75481-182">The <see cref="T:System.Uri" /> of the source file.</span></span></param>
        <param name="destFile"><span data-ttu-id="75481-183">Die <see cref="T:Microsoft.WindowsAzure.Storage.File.CloudFile" /> , die das Ziel Azure-Datei.</span><span class="sxs-lookup"><span data-stu-id="75481-183">The <see cref="T:Microsoft.WindowsAzure.Storage.File.CloudFile" /> that is the destination Azure file.</span></span></param>
        <param name="isServiceCopy"><span data-ttu-id="75481-184">Ein Flag, das angibt, ob die Kopie aufseiten des Dienstes asynchrone Kopie oder nicht ist.</span><span class="sxs-lookup"><span data-stu-id="75481-184">A flag indicating whether the copy is service-side asynchronous copy or not.</span></span>
            <span data-ttu-id="75481-185">Wenn dieses Flag, auf "true" werden aufseiten des Dienstes asychronen Kopie festgelegt ist wird verwendet. Wenn dieses Flag auf "false" festgelegt ist, wird Datei zuerst von der Quelle heruntergeladen und anschließend auf Ziel hochgeladen.</span><span class="sxs-lookup"><span data-stu-id="75481-185">If this flag is set to true, service-side asychronous copy will be used; if this flag is set to false, file is downloaded from source first, then uploaded to destination.</span></span></param>
        <param name="options"><span data-ttu-id="75481-186">Ein <see cref="T:Microsoft.WindowsAzure.Storage.DataMovement.CopyOptions" /> -Objekt, das zusätzliche Optionen für den Vorgang angibt.</span><span class="sxs-lookup"><span data-stu-id="75481-186">A <see cref="T:Microsoft.WindowsAzure.Storage.DataMovement.CopyOptions" /> object that specifies additional options for the operation.</span></span></param>
        <param name="context"><span data-ttu-id="75481-187">Ein <see cref="T:Microsoft.WindowsAzure.Storage.DataMovement.SingleTransferContext" /> -Objekt, das den Kontext für den aktuellen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="75481-187">A <see cref="T:Microsoft.WindowsAzure.Storage.DataMovement.SingleTransferContext" /> object that represents the context for the current operation.</span></span></param>
        <summary>
            <span data-ttu-id="75481-188">Kopieren der Datei aus einem angegebenen URI auf eine Azure-Datei.</span><span class="sxs-lookup"><span data-stu-id="75481-188">Copy file from an specified URI to an Azure file.</span></span>
            </summary>
        <returns><span data-ttu-id="75481-189">Ein <see cref="T:System.Threading.Tasks.Task" />-Objekt, das den asynchronen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="75481-189">A <see cref="T:System.Threading.Tasks.Task" /> object that represents the asynchronous operation.</span></span></returns>
        <remarks><span data-ttu-id="75481-190">Kopieren von einem URI auf Azure-Datei synchron ist noch nicht unterstützt.</span><span class="sxs-lookup"><span data-stu-id="75481-190">Copying from an URI to Azure file synchronously is not supported yet.</span></span></remarks>
      </Docs>
    </Member>
    <Member MemberName="CopyAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task CopyAsync (Microsoft.WindowsAzure.Storage.Blob.CloudBlob sourceBlob, Microsoft.WindowsAzure.Storage.Blob.CloudBlob destBlob, bool isServiceCopy, Microsoft.WindowsAzure.Storage.DataMovement.CopyOptions options, Microsoft.WindowsAzure.Storage.DataMovement.SingleTransferContext context, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task CopyAsync(class Microsoft.WindowsAzure.Storage.Blob.CloudBlob sourceBlob, class Microsoft.WindowsAzure.Storage.Blob.CloudBlob destBlob, bool isServiceCopy, class Microsoft.WindowsAzure.Storage.DataMovement.CopyOptions options, class Microsoft.WindowsAzure.Storage.DataMovement.SingleTransferContext context, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.DataMovement.TransferManager.CopyAsync(Microsoft.WindowsAzure.Storage.Blob.CloudBlob,Microsoft.WindowsAzure.Storage.Blob.CloudBlob,System.Boolean,Microsoft.WindowsAzure.Storage.DataMovement.CopyOptions,Microsoft.WindowsAzure.Storage.DataMovement.SingleTransferContext,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member CopyAsync : Microsoft.WindowsAzure.Storage.Blob.CloudBlob * Microsoft.WindowsAzure.Storage.Blob.CloudBlob * bool * Microsoft.WindowsAzure.Storage.DataMovement.CopyOptions * Microsoft.WindowsAzure.Storage.DataMovement.SingleTransferContext * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.WindowsAzure.Storage.DataMovement.TransferManager.CopyAsync (sourceBlob, destBlob, isServiceCopy, options, context, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage.DataMovement</AssemblyName>
        <AssemblyVersion>0.5.3.0</AssemblyVersion>
        <AssemblyVersion>0.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Diagnostics.CodeAnalysis.SuppressMessage("Microsoft.Design", "CA1011:ConsiderPassingBaseTypesAsParameters", Justification="With TransferContext, it also accepts DirectoryTransferContext. Here forbid this behavior.")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="sourceBlob" Type="Microsoft.WindowsAzure.Storage.Blob.CloudBlob" />
        <Parameter Name="destBlob" Type="Microsoft.WindowsAzure.Storage.Blob.CloudBlob" />
        <Parameter Name="isServiceCopy" Type="System.Boolean" />
        <Parameter Name="options" Type="Microsoft.WindowsAzure.Storage.DataMovement.CopyOptions" />
        <Parameter Name="context" Type="Microsoft.WindowsAzure.Storage.DataMovement.SingleTransferContext" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="sourceBlob"><span data-ttu-id="75481-191">Die <see cref="T:Microsoft.WindowsAzure.Storage.Blob.CloudBlob" /> , der die Quelle Azure-Blob.</span><span class="sxs-lookup"><span data-stu-id="75481-191">The <see cref="T:Microsoft.WindowsAzure.Storage.Blob.CloudBlob" /> that is the source Azure blob.</span></span></param>
        <param name="destBlob"><span data-ttu-id="75481-192">Die <see cref="T:Microsoft.WindowsAzure.Storage.Blob.CloudBlob" /> , die das Ziel Azure-Blob.</span><span class="sxs-lookup"><span data-stu-id="75481-192">The <see cref="T:Microsoft.WindowsAzure.Storage.Blob.CloudBlob" /> that is the destination Azure blob.</span></span></param>
        <param name="isServiceCopy"><span data-ttu-id="75481-193">Ein Flag, das angibt, ob die Kopie aufseiten des Dienstes asynchrone Kopie oder nicht ist.</span><span class="sxs-lookup"><span data-stu-id="75481-193">A flag indicating whether the copy is service-side asynchronous copy or not.</span></span>
            <span data-ttu-id="75481-194">Wenn dieses Flag, auf "true" werden aufseiten des Dienstes asychronen Kopie festgelegt ist wird verwendet. Wenn dieses Flag auf "false" festgelegt ist, wird Datei zuerst von der Quelle heruntergeladen und anschließend auf Ziel hochgeladen.</span><span class="sxs-lookup"><span data-stu-id="75481-194">If this flag is set to true, service-side asychronous copy will be used; if this flag is set to false, file is downloaded from source first, then uploaded to destination.</span></span></param>
        <param name="options"><span data-ttu-id="75481-195">Ein <see cref="T:Microsoft.WindowsAzure.Storage.DataMovement.CopyOptions" /> -Objekt, das zusätzliche Optionen für den Vorgang angibt.</span><span class="sxs-lookup"><span data-stu-id="75481-195">A <see cref="T:Microsoft.WindowsAzure.Storage.DataMovement.CopyOptions" /> object that specifies additional options for the operation.</span></span></param>
        <param name="context"><span data-ttu-id="75481-196">Ein <see cref="T:Microsoft.WindowsAzure.Storage.DataMovement.SingleTransferContext" /> -Objekt, das den Kontext für den aktuellen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="75481-196">A <see cref="T:Microsoft.WindowsAzure.Storage.DataMovement.SingleTransferContext" /> object that represents the context for the current operation.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="75481-197">Ein <see cref="T:System.Threading.CancellationToken" /> Objekt, das beim Warten auf Abschluss einer Aufgabe überwacht werden.</span><span class="sxs-lookup"><span data-stu-id="75481-197">A <see cref="T:System.Threading.CancellationToken" /> object to observe while waiting for a task to complete.</span></span></param>
        <summary>
            <span data-ttu-id="75481-198">Kopieren von Inhalten, Eigenschaften und Metadaten von einem Azure-blob in einen anderen.</span><span class="sxs-lookup"><span data-stu-id="75481-198">Copy content, properties and metadata of one Azure blob to another.</span></span>
            </summary>
        <returns><span data-ttu-id="75481-199">Ein <see cref="T:System.Threading.Tasks.Task" />-Objekt, das den asynchronen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="75481-199">A <see cref="T:System.Threading.Tasks.Task" /> object that represents the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CopyAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task CopyAsync (Microsoft.WindowsAzure.Storage.Blob.CloudBlob sourceBlob, Microsoft.WindowsAzure.Storage.File.CloudFile destFile, bool isServiceCopy, Microsoft.WindowsAzure.Storage.DataMovement.CopyOptions options, Microsoft.WindowsAzure.Storage.DataMovement.SingleTransferContext context, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task CopyAsync(class Microsoft.WindowsAzure.Storage.Blob.CloudBlob sourceBlob, class Microsoft.WindowsAzure.Storage.File.CloudFile destFile, bool isServiceCopy, class Microsoft.WindowsAzure.Storage.DataMovement.CopyOptions options, class Microsoft.WindowsAzure.Storage.DataMovement.SingleTransferContext context, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.DataMovement.TransferManager.CopyAsync(Microsoft.WindowsAzure.Storage.Blob.CloudBlob,Microsoft.WindowsAzure.Storage.File.CloudFile,System.Boolean,Microsoft.WindowsAzure.Storage.DataMovement.CopyOptions,Microsoft.WindowsAzure.Storage.DataMovement.SingleTransferContext,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member CopyAsync : Microsoft.WindowsAzure.Storage.Blob.CloudBlob * Microsoft.WindowsAzure.Storage.File.CloudFile * bool * Microsoft.WindowsAzure.Storage.DataMovement.CopyOptions * Microsoft.WindowsAzure.Storage.DataMovement.SingleTransferContext * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.WindowsAzure.Storage.DataMovement.TransferManager.CopyAsync (sourceBlob, destFile, isServiceCopy, options, context, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage.DataMovement</AssemblyName>
        <AssemblyVersion>0.5.3.0</AssemblyVersion>
        <AssemblyVersion>0.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Diagnostics.CodeAnalysis.SuppressMessage("Microsoft.Design", "CA1011:ConsiderPassingBaseTypesAsParameters", Justification="With TransferContext, it also accepts DirectoryTransferContext. Here forbid this behavior.")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="sourceBlob" Type="Microsoft.WindowsAzure.Storage.Blob.CloudBlob" />
        <Parameter Name="destFile" Type="Microsoft.WindowsAzure.Storage.File.CloudFile" />
        <Parameter Name="isServiceCopy" Type="System.Boolean" />
        <Parameter Name="options" Type="Microsoft.WindowsAzure.Storage.DataMovement.CopyOptions" />
        <Parameter Name="context" Type="Microsoft.WindowsAzure.Storage.DataMovement.SingleTransferContext" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="sourceBlob"><span data-ttu-id="75481-200">Die <see cref="T:Microsoft.WindowsAzure.Storage.Blob.CloudBlob" /> , der die Quelle Azure-Blob.</span><span class="sxs-lookup"><span data-stu-id="75481-200">The <see cref="T:Microsoft.WindowsAzure.Storage.Blob.CloudBlob" /> that is the source Azure blob.</span></span></param>
        <param name="destFile"><span data-ttu-id="75481-201">Die <see cref="T:Microsoft.WindowsAzure.Storage.File.CloudFile" /> , die das Ziel Azure-Datei.</span><span class="sxs-lookup"><span data-stu-id="75481-201">The <see cref="T:Microsoft.WindowsAzure.Storage.File.CloudFile" /> that is the destination Azure file.</span></span></param>
        <param name="isServiceCopy"><span data-ttu-id="75481-202">Ein Flag, das angibt, ob die Kopie aufseiten des Dienstes asynchrone Kopie oder nicht ist.</span><span class="sxs-lookup"><span data-stu-id="75481-202">A flag indicating whether the copy is service-side asynchronous copy or not.</span></span>
            <span data-ttu-id="75481-203">Wenn dieses Flag, auf "true" werden aufseiten des Dienstes asychronen Kopie festgelegt ist wird verwendet. Wenn dieses Flag auf "false" festgelegt ist, wird Datei zuerst von der Quelle heruntergeladen und anschließend auf Ziel hochgeladen.</span><span class="sxs-lookup"><span data-stu-id="75481-203">If this flag is set to true, service-side asychronous copy will be used; if this flag is set to false, file is downloaded from source first, then uploaded to destination.</span></span></param>
        <param name="options"><span data-ttu-id="75481-204">Ein <see cref="T:Microsoft.WindowsAzure.Storage.DataMovement.CopyOptions" /> -Objekt, das zusätzliche Optionen für den Vorgang angibt.</span><span class="sxs-lookup"><span data-stu-id="75481-204">A <see cref="T:Microsoft.WindowsAzure.Storage.DataMovement.CopyOptions" /> object that specifies additional options for the operation.</span></span></param>
        <param name="context"><span data-ttu-id="75481-205">Ein <see cref="T:Microsoft.WindowsAzure.Storage.DataMovement.SingleTransferContext" /> -Objekt, das den Kontext für den aktuellen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="75481-205">A <see cref="T:Microsoft.WindowsAzure.Storage.DataMovement.SingleTransferContext" /> object that represents the context for the current operation.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="75481-206">Ein <see cref="T:System.Threading.CancellationToken" /> Objekt, das beim Warten auf Abschluss einer Aufgabe überwacht werden.</span><span class="sxs-lookup"><span data-stu-id="75481-206">A <see cref="T:System.Threading.CancellationToken" /> object to observe while waiting for a task to complete.</span></span></param>
        <summary>
            <span data-ttu-id="75481-207">Kopieren von Inhalten, Eigenschaften und Metadaten von einem Azure-blob in einer Azure-Datei.</span><span class="sxs-lookup"><span data-stu-id="75481-207">Copy content, properties and metadata of an Azure blob to an Azure file.</span></span>
            </summary>
        <returns><span data-ttu-id="75481-208">Ein <see cref="T:System.Threading.Tasks.Task" />-Objekt, das den asynchronen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="75481-208">A <see cref="T:System.Threading.Tasks.Task" /> object that represents the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CopyAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task CopyAsync (Microsoft.WindowsAzure.Storage.File.CloudFile sourceFile, Microsoft.WindowsAzure.Storage.Blob.CloudBlob destBlob, bool isServiceCopy, Microsoft.WindowsAzure.Storage.DataMovement.CopyOptions options, Microsoft.WindowsAzure.Storage.DataMovement.SingleTransferContext context, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task CopyAsync(class Microsoft.WindowsAzure.Storage.File.CloudFile sourceFile, class Microsoft.WindowsAzure.Storage.Blob.CloudBlob destBlob, bool isServiceCopy, class Microsoft.WindowsAzure.Storage.DataMovement.CopyOptions options, class Microsoft.WindowsAzure.Storage.DataMovement.SingleTransferContext context, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.DataMovement.TransferManager.CopyAsync(Microsoft.WindowsAzure.Storage.File.CloudFile,Microsoft.WindowsAzure.Storage.Blob.CloudBlob,System.Boolean,Microsoft.WindowsAzure.Storage.DataMovement.CopyOptions,Microsoft.WindowsAzure.Storage.DataMovement.SingleTransferContext,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member CopyAsync : Microsoft.WindowsAzure.Storage.File.CloudFile * Microsoft.WindowsAzure.Storage.Blob.CloudBlob * bool * Microsoft.WindowsAzure.Storage.DataMovement.CopyOptions * Microsoft.WindowsAzure.Storage.DataMovement.SingleTransferContext * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.WindowsAzure.Storage.DataMovement.TransferManager.CopyAsync (sourceFile, destBlob, isServiceCopy, options, context, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage.DataMovement</AssemblyName>
        <AssemblyVersion>0.5.3.0</AssemblyVersion>
        <AssemblyVersion>0.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Diagnostics.CodeAnalysis.SuppressMessage("Microsoft.Design", "CA1011:ConsiderPassingBaseTypesAsParameters", Justification="With TransferContext, it also accepts DirectoryTransferContext. Here forbid this behavior.")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="sourceFile" Type="Microsoft.WindowsAzure.Storage.File.CloudFile" />
        <Parameter Name="destBlob" Type="Microsoft.WindowsAzure.Storage.Blob.CloudBlob" />
        <Parameter Name="isServiceCopy" Type="System.Boolean" />
        <Parameter Name="options" Type="Microsoft.WindowsAzure.Storage.DataMovement.CopyOptions" />
        <Parameter Name="context" Type="Microsoft.WindowsAzure.Storage.DataMovement.SingleTransferContext" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="sourceFile"><span data-ttu-id="75481-209">Die <see cref="T:Microsoft.WindowsAzure.Storage.File.CloudFile" /> , der die Quelle Azure-Datei.</span><span class="sxs-lookup"><span data-stu-id="75481-209">The <see cref="T:Microsoft.WindowsAzure.Storage.File.CloudFile" /> that is the source Azure file.</span></span></param>
        <param name="destBlob"><span data-ttu-id="75481-210">Die <see cref="T:Microsoft.WindowsAzure.Storage.Blob.CloudBlob" /> , die das Ziel Azure-Blob.</span><span class="sxs-lookup"><span data-stu-id="75481-210">The <see cref="T:Microsoft.WindowsAzure.Storage.Blob.CloudBlob" /> that is the destination Azure blob.</span></span></param>
        <param name="isServiceCopy"><span data-ttu-id="75481-211">Ein Flag, das angibt, ob die Kopie aufseiten des Dienstes asynchrone Kopie oder nicht ist.</span><span class="sxs-lookup"><span data-stu-id="75481-211">A flag indicating whether the copy is service-side asynchronous copy or not.</span></span>
            <span data-ttu-id="75481-212">Wenn dieses Flag, auf "true" werden aufseiten des Dienstes asychronen Kopie festgelegt ist wird verwendet. Wenn dieses Flag auf "false" festgelegt ist, wird Datei zuerst von der Quelle heruntergeladen und anschließend auf Ziel hochgeladen.</span><span class="sxs-lookup"><span data-stu-id="75481-212">If this flag is set to true, service-side asychronous copy will be used; if this flag is set to false, file is downloaded from source first, then uploaded to destination.</span></span></param>
        <param name="options"><span data-ttu-id="75481-213">Ein <see cref="T:Microsoft.WindowsAzure.Storage.DataMovement.CopyOptions" /> -Objekt, das zusätzliche Optionen für den Vorgang angibt.</span><span class="sxs-lookup"><span data-stu-id="75481-213">A <see cref="T:Microsoft.WindowsAzure.Storage.DataMovement.CopyOptions" /> object that specifies additional options for the operation.</span></span></param>
        <param name="context"><span data-ttu-id="75481-214">Ein <see cref="T:Microsoft.WindowsAzure.Storage.DataMovement.SingleTransferContext" /> -Objekt, das den Kontext für den aktuellen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="75481-214">A <see cref="T:Microsoft.WindowsAzure.Storage.DataMovement.SingleTransferContext" /> object that represents the context for the current operation.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="75481-215">Ein <see cref="T:System.Threading.CancellationToken" /> Objekt, das beim Warten auf Abschluss einer Aufgabe überwacht werden.</span><span class="sxs-lookup"><span data-stu-id="75481-215">A <see cref="T:System.Threading.CancellationToken" /> object to observe while waiting for a task to complete.</span></span></param>
        <summary>
            <span data-ttu-id="75481-216">Kopieren Sie die Inhalte, Eigenschaften und Metadaten einer Azure-Datei in ein Azure-Blob.</span><span class="sxs-lookup"><span data-stu-id="75481-216">Copy content, properties and metadata of an Azure file to an Azure blob.</span></span>
            </summary>
        <returns><span data-ttu-id="75481-217">Ein <see cref="T:System.Threading.Tasks.Task" />-Objekt, das den asynchronen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="75481-217">A <see cref="T:System.Threading.Tasks.Task" /> object that represents the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CopyAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task CopyAsync (Microsoft.WindowsAzure.Storage.File.CloudFile sourceFile, Microsoft.WindowsAzure.Storage.File.CloudFile destFile, bool isServiceCopy, Microsoft.WindowsAzure.Storage.DataMovement.CopyOptions options, Microsoft.WindowsAzure.Storage.DataMovement.SingleTransferContext context, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task CopyAsync(class Microsoft.WindowsAzure.Storage.File.CloudFile sourceFile, class Microsoft.WindowsAzure.Storage.File.CloudFile destFile, bool isServiceCopy, class Microsoft.WindowsAzure.Storage.DataMovement.CopyOptions options, class Microsoft.WindowsAzure.Storage.DataMovement.SingleTransferContext context, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.DataMovement.TransferManager.CopyAsync(Microsoft.WindowsAzure.Storage.File.CloudFile,Microsoft.WindowsAzure.Storage.File.CloudFile,System.Boolean,Microsoft.WindowsAzure.Storage.DataMovement.CopyOptions,Microsoft.WindowsAzure.Storage.DataMovement.SingleTransferContext,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member CopyAsync : Microsoft.WindowsAzure.Storage.File.CloudFile * Microsoft.WindowsAzure.Storage.File.CloudFile * bool * Microsoft.WindowsAzure.Storage.DataMovement.CopyOptions * Microsoft.WindowsAzure.Storage.DataMovement.SingleTransferContext * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.WindowsAzure.Storage.DataMovement.TransferManager.CopyAsync (sourceFile, destFile, isServiceCopy, options, context, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage.DataMovement</AssemblyName>
        <AssemblyVersion>0.5.3.0</AssemblyVersion>
        <AssemblyVersion>0.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Diagnostics.CodeAnalysis.SuppressMessage("Microsoft.Design", "CA1011:ConsiderPassingBaseTypesAsParameters", Justification="With TransferContext, it also accepts DirectoryTransferContext. Here forbid this behavior.")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="sourceFile" Type="Microsoft.WindowsAzure.Storage.File.CloudFile" />
        <Parameter Name="destFile" Type="Microsoft.WindowsAzure.Storage.File.CloudFile" />
        <Parameter Name="isServiceCopy" Type="System.Boolean" />
        <Parameter Name="options" Type="Microsoft.WindowsAzure.Storage.DataMovement.CopyOptions" />
        <Parameter Name="context" Type="Microsoft.WindowsAzure.Storage.DataMovement.SingleTransferContext" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="sourceFile"><span data-ttu-id="75481-218">Die <see cref="T:Microsoft.WindowsAzure.Storage.File.CloudFile" /> , der die Quelle Azure-Datei.</span><span class="sxs-lookup"><span data-stu-id="75481-218">The <see cref="T:Microsoft.WindowsAzure.Storage.File.CloudFile" /> that is the source Azure file.</span></span></param>
        <param name="destFile"><span data-ttu-id="75481-219">Die <see cref="T:Microsoft.WindowsAzure.Storage.File.CloudFile" /> , die das Ziel Azure-Datei.</span><span class="sxs-lookup"><span data-stu-id="75481-219">The <see cref="T:Microsoft.WindowsAzure.Storage.File.CloudFile" /> that is the destination Azure file.</span></span></param>
        <param name="isServiceCopy"><span data-ttu-id="75481-220">Ein Flag, das angibt, ob die Kopie aufseiten des Dienstes asynchrone Kopie oder nicht ist.</span><span class="sxs-lookup"><span data-stu-id="75481-220">A flag indicating whether the copy is service-side asynchronous copy or not.</span></span>
            <span data-ttu-id="75481-221">Wenn dieses Flag, auf "true" werden aufseiten des Dienstes asychronen Kopie festgelegt ist wird verwendet. Wenn dieses Flag auf "false" festgelegt ist, wird Datei zuerst von der Quelle heruntergeladen und anschließend auf Ziel hochgeladen.</span><span class="sxs-lookup"><span data-stu-id="75481-221">If this flag is set to true, service-side asychronous copy will be used; if this flag is set to false, file is downloaded from source first, then uploaded to destination.</span></span></param>
        <param name="options"><span data-ttu-id="75481-222">Ein <see cref="T:Microsoft.WindowsAzure.Storage.DataMovement.CopyOptions" /> -Objekt, das zusätzliche Optionen für den Vorgang angibt.</span><span class="sxs-lookup"><span data-stu-id="75481-222">A <see cref="T:Microsoft.WindowsAzure.Storage.DataMovement.CopyOptions" /> object that specifies additional options for the operation.</span></span></param>
        <param name="context"><span data-ttu-id="75481-223">Ein <see cref="T:Microsoft.WindowsAzure.Storage.DataMovement.SingleTransferContext" /> -Objekt, das den Kontext für den aktuellen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="75481-223">A <see cref="T:Microsoft.WindowsAzure.Storage.DataMovement.SingleTransferContext" /> object that represents the context for the current operation.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="75481-224">Ein <see cref="T:System.Threading.CancellationToken" /> Objekt, das beim Warten auf Abschluss einer Aufgabe überwacht werden.</span><span class="sxs-lookup"><span data-stu-id="75481-224">A <see cref="T:System.Threading.CancellationToken" /> object to observe while waiting for a task to complete.</span></span></param>
        <summary>
            <span data-ttu-id="75481-225">Kopieren von Inhalten, Eigenschaften und Metadaten einer Azure-Datei in eine andere.</span><span class="sxs-lookup"><span data-stu-id="75481-225">Copy content, properties and metadata of an Azure file to another.</span></span>
            </summary>
        <returns><span data-ttu-id="75481-226">Ein <see cref="T:System.Threading.Tasks.Task" />-Objekt, das den asynchronen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="75481-226">A <see cref="T:System.Threading.Tasks.Task" /> object that represents the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CopyAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task CopyAsync (Uri sourceUri, Microsoft.WindowsAzure.Storage.Blob.CloudBlob destBlob, bool isServiceCopy, Microsoft.WindowsAzure.Storage.DataMovement.CopyOptions options, Microsoft.WindowsAzure.Storage.DataMovement.SingleTransferContext context, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task CopyAsync(class System.Uri sourceUri, class Microsoft.WindowsAzure.Storage.Blob.CloudBlob destBlob, bool isServiceCopy, class Microsoft.WindowsAzure.Storage.DataMovement.CopyOptions options, class Microsoft.WindowsAzure.Storage.DataMovement.SingleTransferContext context, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.DataMovement.TransferManager.CopyAsync(System.Uri,Microsoft.WindowsAzure.Storage.Blob.CloudBlob,System.Boolean,Microsoft.WindowsAzure.Storage.DataMovement.CopyOptions,Microsoft.WindowsAzure.Storage.DataMovement.SingleTransferContext,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member CopyAsync : Uri * Microsoft.WindowsAzure.Storage.Blob.CloudBlob * bool * Microsoft.WindowsAzure.Storage.DataMovement.CopyOptions * Microsoft.WindowsAzure.Storage.DataMovement.SingleTransferContext * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.WindowsAzure.Storage.DataMovement.TransferManager.CopyAsync (sourceUri, destBlob, isServiceCopy, options, context, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage.DataMovement</AssemblyName>
        <AssemblyVersion>0.5.3.0</AssemblyVersion>
        <AssemblyVersion>0.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Diagnostics.CodeAnalysis.SuppressMessage("Microsoft.Design", "CA1011:ConsiderPassingBaseTypesAsParameters", Justification="With TransferContext, it also accepts DirectoryTransferContext. Here forbid this behavior.")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="sourceUri" Type="System.Uri" />
        <Parameter Name="destBlob" Type="Microsoft.WindowsAzure.Storage.Blob.CloudBlob" />
        <Parameter Name="isServiceCopy" Type="System.Boolean" />
        <Parameter Name="options" Type="Microsoft.WindowsAzure.Storage.DataMovement.CopyOptions" />
        <Parameter Name="context" Type="Microsoft.WindowsAzure.Storage.DataMovement.SingleTransferContext" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="sourceUri"><span data-ttu-id="75481-227">Die <see cref="T:System.Uri" /> der Quelldatei.</span><span class="sxs-lookup"><span data-stu-id="75481-227">The <see cref="T:System.Uri" /> of the source file.</span></span></param>
        <param name="destBlob"><span data-ttu-id="75481-228">Die <see cref="T:Microsoft.WindowsAzure.Storage.Blob.CloudBlob" /> , die das Ziel Azure-Blob.</span><span class="sxs-lookup"><span data-stu-id="75481-228">The <see cref="T:Microsoft.WindowsAzure.Storage.Blob.CloudBlob" /> that is the destination Azure blob.</span></span></param>
        <param name="isServiceCopy"><span data-ttu-id="75481-229">Ein Flag, das angibt, ob die Kopie aufseiten des Dienstes asynchrone Kopie oder nicht ist.</span><span class="sxs-lookup"><span data-stu-id="75481-229">A flag indicating whether the copy is service-side asynchronous copy or not.</span></span>
            <span data-ttu-id="75481-230">Wenn dieses Flag, auf "true" werden aufseiten des Dienstes asychronen Kopie festgelegt ist wird verwendet. Wenn dieses Flag auf "false" festgelegt ist, wird Datei zuerst von der Quelle heruntergeladen und anschließend auf Ziel hochgeladen.</span><span class="sxs-lookup"><span data-stu-id="75481-230">If this flag is set to true, service-side asychronous copy will be used; if this flag is set to false, file is downloaded from source first, then uploaded to destination.</span></span></param>
        <param name="options"><span data-ttu-id="75481-231">Ein <see cref="T:Microsoft.WindowsAzure.Storage.DataMovement.CopyOptions" /> -Objekt, das zusätzliche Optionen für den Vorgang angibt.</span><span class="sxs-lookup"><span data-stu-id="75481-231">A <see cref="T:Microsoft.WindowsAzure.Storage.DataMovement.CopyOptions" /> object that specifies additional options for the operation.</span></span></param>
        <param name="context"><span data-ttu-id="75481-232">Ein <see cref="T:Microsoft.WindowsAzure.Storage.DataMovement.SingleTransferContext" /> -Objekt, das den Kontext für den aktuellen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="75481-232">A <see cref="T:Microsoft.WindowsAzure.Storage.DataMovement.SingleTransferContext" /> object that represents the context for the current operation.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="75481-233">Ein <see cref="T:System.Threading.CancellationToken" /> Objekt, das beim Warten auf Abschluss einer Aufgabe überwacht werden.</span><span class="sxs-lookup"><span data-stu-id="75481-233">A <see cref="T:System.Threading.CancellationToken" /> object to observe while waiting for a task to complete.</span></span></param>
        <summary>
            <span data-ttu-id="75481-234">Kopieren der Datei aus einem angegebenen URI auf einen Azure-Blob.</span><span class="sxs-lookup"><span data-stu-id="75481-234">Copy file from an specified URI to an Azure blob.</span></span>
            </summary>
        <returns><span data-ttu-id="75481-235">Ein <see cref="T:System.Threading.Tasks.Task" />-Objekt, das den asynchronen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="75481-235">A <see cref="T:System.Threading.Tasks.Task" /> object that represents the asynchronous operation.</span></span></returns>
        <remarks><span data-ttu-id="75481-236">Kopieren von einem URI auf Azure-Blob synchron wird nicht unterstützt.</span><span class="sxs-lookup"><span data-stu-id="75481-236">Copying from an URI to Azure blob synchronously is not supported yet.</span></span></remarks>
      </Docs>
    </Member>
    <Member MemberName="CopyAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task CopyAsync (Uri sourceUri, Microsoft.WindowsAzure.Storage.File.CloudFile destFile, bool isServiceCopy, Microsoft.WindowsAzure.Storage.DataMovement.CopyOptions options, Microsoft.WindowsAzure.Storage.DataMovement.SingleTransferContext context, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task CopyAsync(class System.Uri sourceUri, class Microsoft.WindowsAzure.Storage.File.CloudFile destFile, bool isServiceCopy, class Microsoft.WindowsAzure.Storage.DataMovement.CopyOptions options, class Microsoft.WindowsAzure.Storage.DataMovement.SingleTransferContext context, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.DataMovement.TransferManager.CopyAsync(System.Uri,Microsoft.WindowsAzure.Storage.File.CloudFile,System.Boolean,Microsoft.WindowsAzure.Storage.DataMovement.CopyOptions,Microsoft.WindowsAzure.Storage.DataMovement.SingleTransferContext,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member CopyAsync : Uri * Microsoft.WindowsAzure.Storage.File.CloudFile * bool * Microsoft.WindowsAzure.Storage.DataMovement.CopyOptions * Microsoft.WindowsAzure.Storage.DataMovement.SingleTransferContext * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.WindowsAzure.Storage.DataMovement.TransferManager.CopyAsync (sourceUri, destFile, isServiceCopy, options, context, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage.DataMovement</AssemblyName>
        <AssemblyVersion>0.5.3.0</AssemblyVersion>
        <AssemblyVersion>0.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Diagnostics.CodeAnalysis.SuppressMessage("Microsoft.Design", "CA1011:ConsiderPassingBaseTypesAsParameters", Justification="With TransferContext, it also accepts DirectoryTransferContext. Here forbid this behavior.")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="sourceUri" Type="System.Uri" />
        <Parameter Name="destFile" Type="Microsoft.WindowsAzure.Storage.File.CloudFile" />
        <Parameter Name="isServiceCopy" Type="System.Boolean" />
        <Parameter Name="options" Type="Microsoft.WindowsAzure.Storage.DataMovement.CopyOptions" />
        <Parameter Name="context" Type="Microsoft.WindowsAzure.Storage.DataMovement.SingleTransferContext" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="sourceUri"><span data-ttu-id="75481-237">Die <see cref="T:System.Uri" /> der Quelldatei.</span><span class="sxs-lookup"><span data-stu-id="75481-237">The <see cref="T:System.Uri" /> of the source file.</span></span></param>
        <param name="destFile"><span data-ttu-id="75481-238">Die <see cref="T:Microsoft.WindowsAzure.Storage.File.CloudFile" /> , die das Ziel Azure-Datei.</span><span class="sxs-lookup"><span data-stu-id="75481-238">The <see cref="T:Microsoft.WindowsAzure.Storage.File.CloudFile" /> that is the destination Azure file.</span></span></param>
        <param name="isServiceCopy"><span data-ttu-id="75481-239">Ein Flag, das angibt, ob die Kopie aufseiten des Dienstes asynchrone Kopie oder nicht ist.</span><span class="sxs-lookup"><span data-stu-id="75481-239">A flag indicating whether the copy is service-side asynchronous copy or not.</span></span>
            <span data-ttu-id="75481-240">Wenn dieses Flag, auf "true" werden aufseiten des Dienstes asychronen Kopie festgelegt ist wird verwendet. Wenn dieses Flag auf "false" festgelegt ist, wird Datei zuerst von der Quelle heruntergeladen und anschließend auf Ziel hochgeladen.</span><span class="sxs-lookup"><span data-stu-id="75481-240">If this flag is set to true, service-side asychronous copy will be used; if this flag is set to false, file is downloaded from source first, then uploaded to destination.</span></span></param>
        <param name="options"><span data-ttu-id="75481-241">Ein <see cref="T:Microsoft.WindowsAzure.Storage.DataMovement.CopyOptions" /> -Objekt, das zusätzliche Optionen für den Vorgang angibt.</span><span class="sxs-lookup"><span data-stu-id="75481-241">A <see cref="T:Microsoft.WindowsAzure.Storage.DataMovement.CopyOptions" /> object that specifies additional options for the operation.</span></span></param>
        <param name="context"><span data-ttu-id="75481-242">Ein <see cref="T:Microsoft.WindowsAzure.Storage.DataMovement.SingleTransferContext" /> -Objekt, das den Kontext für den aktuellen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="75481-242">A <see cref="T:Microsoft.WindowsAzure.Storage.DataMovement.SingleTransferContext" /> object that represents the context for the current operation.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="75481-243">Ein <see cref="T:System.Threading.CancellationToken" /> Objekt, das beim Warten auf Abschluss einer Aufgabe überwacht werden.</span><span class="sxs-lookup"><span data-stu-id="75481-243">A <see cref="T:System.Threading.CancellationToken" /> object to observe while waiting for a task to complete.</span></span></param>
        <summary>
            <span data-ttu-id="75481-244">Kopieren der Datei aus einem angegebenen URI auf eine Azure-Datei.</span><span class="sxs-lookup"><span data-stu-id="75481-244">Copy file from an specified URI to an Azure file.</span></span>
            </summary>
        <returns><span data-ttu-id="75481-245">Ein <see cref="T:System.Threading.Tasks.Task" />-Objekt, das den asynchronen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="75481-245">A <see cref="T:System.Threading.Tasks.Task" /> object that represents the asynchronous operation.</span></span></returns>
        <remarks><span data-ttu-id="75481-246">Kopieren von einem URI auf Azure-Datei synchron ist noch nicht unterstützt.</span><span class="sxs-lookup"><span data-stu-id="75481-246">Copying from an URI to Azure file synchronously is not supported yet.</span></span></remarks>
      </Docs>
    </Member>
    <Member MemberName="CopyDirectoryAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.DataMovement.TransferStatus&gt; CopyDirectoryAsync (Microsoft.WindowsAzure.Storage.Blob.CloudBlobDirectory sourceBlobDir, Microsoft.WindowsAzure.Storage.Blob.CloudBlobDirectory destBlobDir, bool isServiceCopy, Microsoft.WindowsAzure.Storage.DataMovement.CopyDirectoryOptions options, Microsoft.WindowsAzure.Storage.DataMovement.DirectoryTransferContext context);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.WindowsAzure.Storage.DataMovement.TransferStatus&gt; CopyDirectoryAsync(class Microsoft.WindowsAzure.Storage.Blob.CloudBlobDirectory sourceBlobDir, class Microsoft.WindowsAzure.Storage.Blob.CloudBlobDirectory destBlobDir, bool isServiceCopy, class Microsoft.WindowsAzure.Storage.DataMovement.CopyDirectoryOptions options, class Microsoft.WindowsAzure.Storage.DataMovement.DirectoryTransferContext context) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.DataMovement.TransferManager.CopyDirectoryAsync(Microsoft.WindowsAzure.Storage.Blob.CloudBlobDirectory,Microsoft.WindowsAzure.Storage.Blob.CloudBlobDirectory,System.Boolean,Microsoft.WindowsAzure.Storage.DataMovement.CopyDirectoryOptions,Microsoft.WindowsAzure.Storage.DataMovement.DirectoryTransferContext)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function CopyDirectoryAsync (sourceBlobDir As CloudBlobDirectory, destBlobDir As CloudBlobDirectory, isServiceCopy As Boolean, options As CopyDirectoryOptions, context As DirectoryTransferContext) As Task(Of TransferStatus)" />
      <MemberSignature Language="F#" Value="static member CopyDirectoryAsync : Microsoft.WindowsAzure.Storage.Blob.CloudBlobDirectory * Microsoft.WindowsAzure.Storage.Blob.CloudBlobDirectory * bool * Microsoft.WindowsAzure.Storage.DataMovement.CopyDirectoryOptions * Microsoft.WindowsAzure.Storage.DataMovement.DirectoryTransferContext -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.DataMovement.TransferStatus&gt;" Usage="Microsoft.WindowsAzure.Storage.DataMovement.TransferManager.CopyDirectoryAsync (sourceBlobDir, destBlobDir, isServiceCopy, options, context)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage.DataMovement</AssemblyName>
        <AssemblyVersion>0.5.3.0</AssemblyVersion>
        <AssemblyVersion>0.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.DataMovement.TransferStatus&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="sourceBlobDir" Type="Microsoft.WindowsAzure.Storage.Blob.CloudBlobDirectory" />
        <Parameter Name="destBlobDir" Type="Microsoft.WindowsAzure.Storage.Blob.CloudBlobDirectory" />
        <Parameter Name="isServiceCopy" Type="System.Boolean" />
        <Parameter Name="options" Type="Microsoft.WindowsAzure.Storage.DataMovement.CopyDirectoryOptions" />
        <Parameter Name="context" Type="Microsoft.WindowsAzure.Storage.DataMovement.DirectoryTransferContext" />
      </Parameters>
      <Docs>
        <param name="sourceBlobDir"><span data-ttu-id="75481-247">Die <see cref="T:Microsoft.WindowsAzure.Storage.Blob.CloudBlobDirectory" /> also das Quellverzeichnis Azure-Blob.</span><span class="sxs-lookup"><span data-stu-id="75481-247">The <see cref="T:Microsoft.WindowsAzure.Storage.Blob.CloudBlobDirectory" /> that is the source Azure blob directory.</span></span></param>
        <param name="destBlobDir"><span data-ttu-id="75481-248">Die <see cref="T:Microsoft.WindowsAzure.Storage.Blob.CloudBlobDirectory" /> , das Azure-Blob-Zielverzeichnis.</span><span class="sxs-lookup"><span data-stu-id="75481-248">The <see cref="T:Microsoft.WindowsAzure.Storage.Blob.CloudBlobDirectory" /> that is the destination Azure blob directory.</span></span></param>
        <param name="isServiceCopy"><span data-ttu-id="75481-249">Ein Flag, das angibt, ob die Kopie aufseiten des Dienstes asynchrone Kopie oder nicht ist.</span><span class="sxs-lookup"><span data-stu-id="75481-249">A flag indicating whether the copy is service-side asynchronous copy or not.</span></span>
            <span data-ttu-id="75481-250">Wenn dieses Flag, auf "true" werden aufseiten des Dienstes asychronen Kopie festgelegt ist wird verwendet. Wenn dieses Flag auf "false" festgelegt ist, wird Datei zuerst von der Quelle heruntergeladen und anschließend auf Ziel hochgeladen.</span><span class="sxs-lookup"><span data-stu-id="75481-250">If this flag is set to true, service-side asychronous copy will be used; if this flag is set to false, file is downloaded from source first, then uploaded to destination.</span></span></param>
        <param name="options"><span data-ttu-id="75481-251">Ein <see cref="T:Microsoft.WindowsAzure.Storage.DataMovement.CopyDirectoryOptions" /> -Objekt, das zusätzliche Optionen für den Vorgang angibt.</span><span class="sxs-lookup"><span data-stu-id="75481-251">A <see cref="T:Microsoft.WindowsAzure.Storage.DataMovement.CopyDirectoryOptions" /> object that specifies additional options for the operation.</span></span></param>
        <param name="context"><span data-ttu-id="75481-252">Ein <see cref="T:Microsoft.WindowsAzure.Storage.DataMovement.DirectoryTransferContext" /> -Objekt, das den Kontext für den aktuellen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="75481-252">A <see cref="T:Microsoft.WindowsAzure.Storage.DataMovement.DirectoryTransferContext" /> object that represents the context for the current operation.</span></span></param>
        <summary>
            <span data-ttu-id="75481-253">Kopieren Sie ein Azure-Blob-Verzeichnis, in ein anderes Azure-Blob-Verzeichnis.</span><span class="sxs-lookup"><span data-stu-id="75481-253">Copy an Azure blob directory to another Azure blob directory.</span></span>
            </summary>
        <returns><span data-ttu-id="75481-254">Ein <see cref="T:System.Threading.Tasks.Task`1" /> Objekt des Typs <see cref="T:Microsoft.WindowsAzure.Storage.DataMovement.TransferStatus" /> , die den asynchronen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="75481-254">A <see cref="T:System.Threading.Tasks.Task`1" /> object of type <see cref="T:Microsoft.WindowsAzure.Storage.DataMovement.TransferStatus" /> that represents the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CopyDirectoryAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.DataMovement.TransferStatus&gt; CopyDirectoryAsync (Microsoft.WindowsAzure.Storage.Blob.CloudBlobDirectory sourceBlobDir, Microsoft.WindowsAzure.Storage.File.CloudFileDirectory destFileDir, bool isServiceCopy, Microsoft.WindowsAzure.Storage.DataMovement.CopyDirectoryOptions options, Microsoft.WindowsAzure.Storage.DataMovement.DirectoryTransferContext context);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.WindowsAzure.Storage.DataMovement.TransferStatus&gt; CopyDirectoryAsync(class Microsoft.WindowsAzure.Storage.Blob.CloudBlobDirectory sourceBlobDir, class Microsoft.WindowsAzure.Storage.File.CloudFileDirectory destFileDir, bool isServiceCopy, class Microsoft.WindowsAzure.Storage.DataMovement.CopyDirectoryOptions options, class Microsoft.WindowsAzure.Storage.DataMovement.DirectoryTransferContext context) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.DataMovement.TransferManager.CopyDirectoryAsync(Microsoft.WindowsAzure.Storage.Blob.CloudBlobDirectory,Microsoft.WindowsAzure.Storage.File.CloudFileDirectory,System.Boolean,Microsoft.WindowsAzure.Storage.DataMovement.CopyDirectoryOptions,Microsoft.WindowsAzure.Storage.DataMovement.DirectoryTransferContext)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function CopyDirectoryAsync (sourceBlobDir As CloudBlobDirectory, destFileDir As CloudFileDirectory, isServiceCopy As Boolean, options As CopyDirectoryOptions, context As DirectoryTransferContext) As Task(Of TransferStatus)" />
      <MemberSignature Language="F#" Value="static member CopyDirectoryAsync : Microsoft.WindowsAzure.Storage.Blob.CloudBlobDirectory * Microsoft.WindowsAzure.Storage.File.CloudFileDirectory * bool * Microsoft.WindowsAzure.Storage.DataMovement.CopyDirectoryOptions * Microsoft.WindowsAzure.Storage.DataMovement.DirectoryTransferContext -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.DataMovement.TransferStatus&gt;" Usage="Microsoft.WindowsAzure.Storage.DataMovement.TransferManager.CopyDirectoryAsync (sourceBlobDir, destFileDir, isServiceCopy, options, context)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage.DataMovement</AssemblyName>
        <AssemblyVersion>0.5.3.0</AssemblyVersion>
        <AssemblyVersion>0.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.DataMovement.TransferStatus&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="sourceBlobDir" Type="Microsoft.WindowsAzure.Storage.Blob.CloudBlobDirectory" />
        <Parameter Name="destFileDir" Type="Microsoft.WindowsAzure.Storage.File.CloudFileDirectory" />
        <Parameter Name="isServiceCopy" Type="System.Boolean" />
        <Parameter Name="options" Type="Microsoft.WindowsAzure.Storage.DataMovement.CopyDirectoryOptions" />
        <Parameter Name="context" Type="Microsoft.WindowsAzure.Storage.DataMovement.DirectoryTransferContext" />
      </Parameters>
      <Docs>
        <param name="sourceBlobDir"><span data-ttu-id="75481-255">Die <see cref="T:Microsoft.WindowsAzure.Storage.Blob.CloudBlobDirectory" /> also das Quellverzeichnis Azure-Blob.</span><span class="sxs-lookup"><span data-stu-id="75481-255">The <see cref="T:Microsoft.WindowsAzure.Storage.Blob.CloudBlobDirectory" /> that is the source Azure blob directory.</span></span></param>
        <param name="destFileDir"><span data-ttu-id="75481-256">Die <see cref="T:Microsoft.WindowsAzure.Storage.File.CloudFileDirectory" /> also das Zielverzeichnis Azure-Datei.</span><span class="sxs-lookup"><span data-stu-id="75481-256">The <see cref="T:Microsoft.WindowsAzure.Storage.File.CloudFileDirectory" /> that is the destination Azure file directory.</span></span></param>
        <param name="isServiceCopy"><span data-ttu-id="75481-257">Ein Flag, das angibt, ob die Kopie aufseiten des Dienstes asynchrone Kopie oder nicht ist.</span><span class="sxs-lookup"><span data-stu-id="75481-257">A flag indicating whether the copy is service-side asynchronous copy or not.</span></span>
            <span data-ttu-id="75481-258">Wenn dieses Flag, auf "true" werden aufseiten des Dienstes asychronen Kopie festgelegt ist wird verwendet. Wenn dieses Flag auf "false" festgelegt ist, wird Datei zuerst von der Quelle heruntergeladen und anschließend auf Ziel hochgeladen.</span><span class="sxs-lookup"><span data-stu-id="75481-258">If this flag is set to true, service-side asychronous copy will be used; if this flag is set to false, file is downloaded from source first, then uploaded to destination.</span></span></param>
        <param name="options"><span data-ttu-id="75481-259">Ein <see cref="T:Microsoft.WindowsAzure.Storage.DataMovement.CopyDirectoryOptions" /> -Objekt, das zusätzliche Optionen für den Vorgang angibt.</span><span class="sxs-lookup"><span data-stu-id="75481-259">A <see cref="T:Microsoft.WindowsAzure.Storage.DataMovement.CopyDirectoryOptions" /> object that specifies additional options for the operation.</span></span></param>
        <param name="context"><span data-ttu-id="75481-260">Ein <see cref="T:Microsoft.WindowsAzure.Storage.DataMovement.DirectoryTransferContext" /> -Objekt, das den Kontext für den aktuellen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="75481-260">A <see cref="T:Microsoft.WindowsAzure.Storage.DataMovement.DirectoryTransferContext" /> object that represents the context for the current operation.</span></span></param>
        <summary>
            <span data-ttu-id="75481-261">Kopieren Sie ein Azure-Blob-Verzeichnis in einer Azure-Dateiverzeichnis.</span><span class="sxs-lookup"><span data-stu-id="75481-261">Copy an Azure blob directory to an Azure file directory.</span></span>
            </summary>
        <returns><span data-ttu-id="75481-262">Ein <see cref="T:System.Threading.Tasks.Task`1" /> Objekt des Typs <see cref="T:Microsoft.WindowsAzure.Storage.DataMovement.TransferStatus" /> , die den asynchronen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="75481-262">A <see cref="T:System.Threading.Tasks.Task`1" /> object of type <see cref="T:Microsoft.WindowsAzure.Storage.DataMovement.TransferStatus" /> that represents the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CopyDirectoryAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.DataMovement.TransferStatus&gt; CopyDirectoryAsync (Microsoft.WindowsAzure.Storage.File.CloudFileDirectory sourceFileDir, Microsoft.WindowsAzure.Storage.Blob.CloudBlobDirectory destBlobDir, bool isServiceCopy, Microsoft.WindowsAzure.Storage.DataMovement.CopyDirectoryOptions options, Microsoft.WindowsAzure.Storage.DataMovement.DirectoryTransferContext context);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.WindowsAzure.Storage.DataMovement.TransferStatus&gt; CopyDirectoryAsync(class Microsoft.WindowsAzure.Storage.File.CloudFileDirectory sourceFileDir, class Microsoft.WindowsAzure.Storage.Blob.CloudBlobDirectory destBlobDir, bool isServiceCopy, class Microsoft.WindowsAzure.Storage.DataMovement.CopyDirectoryOptions options, class Microsoft.WindowsAzure.Storage.DataMovement.DirectoryTransferContext context) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.DataMovement.TransferManager.CopyDirectoryAsync(Microsoft.WindowsAzure.Storage.File.CloudFileDirectory,Microsoft.WindowsAzure.Storage.Blob.CloudBlobDirectory,System.Boolean,Microsoft.WindowsAzure.Storage.DataMovement.CopyDirectoryOptions,Microsoft.WindowsAzure.Storage.DataMovement.DirectoryTransferContext)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function CopyDirectoryAsync (sourceFileDir As CloudFileDirectory, destBlobDir As CloudBlobDirectory, isServiceCopy As Boolean, options As CopyDirectoryOptions, context As DirectoryTransferContext) As Task(Of TransferStatus)" />
      <MemberSignature Language="F#" Value="static member CopyDirectoryAsync : Microsoft.WindowsAzure.Storage.File.CloudFileDirectory * Microsoft.WindowsAzure.Storage.Blob.CloudBlobDirectory * bool * Microsoft.WindowsAzure.Storage.DataMovement.CopyDirectoryOptions * Microsoft.WindowsAzure.Storage.DataMovement.DirectoryTransferContext -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.DataMovement.TransferStatus&gt;" Usage="Microsoft.WindowsAzure.Storage.DataMovement.TransferManager.CopyDirectoryAsync (sourceFileDir, destBlobDir, isServiceCopy, options, context)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage.DataMovement</AssemblyName>
        <AssemblyVersion>0.5.3.0</AssemblyVersion>
        <AssemblyVersion>0.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.DataMovement.TransferStatus&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="sourceFileDir" Type="Microsoft.WindowsAzure.Storage.File.CloudFileDirectory" />
        <Parameter Name="destBlobDir" Type="Microsoft.WindowsAzure.Storage.Blob.CloudBlobDirectory" />
        <Parameter Name="isServiceCopy" Type="System.Boolean" />
        <Parameter Name="options" Type="Microsoft.WindowsAzure.Storage.DataMovement.CopyDirectoryOptions" />
        <Parameter Name="context" Type="Microsoft.WindowsAzure.Storage.DataMovement.DirectoryTransferContext" />
      </Parameters>
      <Docs>
        <param name="sourceFileDir"><span data-ttu-id="75481-263">Die <see cref="T:Microsoft.WindowsAzure.Storage.File.CloudFileDirectory" /> also das Quellverzeichnis Azure-Datei.</span><span class="sxs-lookup"><span data-stu-id="75481-263">The <see cref="T:Microsoft.WindowsAzure.Storage.File.CloudFileDirectory" /> that is the source Azure file directory.</span></span></param>
        <param name="destBlobDir"><span data-ttu-id="75481-264">Die <see cref="T:Microsoft.WindowsAzure.Storage.Blob.CloudBlobDirectory" /> , das Azure-Blob-Zielverzeichnis.</span><span class="sxs-lookup"><span data-stu-id="75481-264">The <see cref="T:Microsoft.WindowsAzure.Storage.Blob.CloudBlobDirectory" /> that is the destination Azure blob directory.</span></span></param>
        <param name="isServiceCopy"><span data-ttu-id="75481-265">Ein Flag, das angibt, ob die Kopie aufseiten des Dienstes asynchrone Kopie oder nicht ist.</span><span class="sxs-lookup"><span data-stu-id="75481-265">A flag indicating whether the copy is service-side asynchronous copy or not.</span></span>
            <span data-ttu-id="75481-266">Wenn dieses Flag, auf "true" werden aufseiten des Dienstes asychronen Kopie festgelegt ist wird verwendet. Wenn dieses Flag auf "false" festgelegt ist, wird Datei zuerst von der Quelle heruntergeladen und anschließend auf Ziel hochgeladen.</span><span class="sxs-lookup"><span data-stu-id="75481-266">If this flag is set to true, service-side asychronous copy will be used; if this flag is set to false, file is downloaded from source first, then uploaded to destination.</span></span></param>
        <param name="options"><span data-ttu-id="75481-267">Ein <see cref="T:Microsoft.WindowsAzure.Storage.DataMovement.CopyDirectoryOptions" /> -Objekt, das zusätzliche Optionen für den Vorgang angibt.</span><span class="sxs-lookup"><span data-stu-id="75481-267">A <see cref="T:Microsoft.WindowsAzure.Storage.DataMovement.CopyDirectoryOptions" /> object that specifies additional options for the operation.</span></span></param>
        <param name="context"><span data-ttu-id="75481-268">Ein <see cref="T:Microsoft.WindowsAzure.Storage.DataMovement.DirectoryTransferContext" /> -Objekt, das den Kontext für den aktuellen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="75481-268">A <see cref="T:Microsoft.WindowsAzure.Storage.DataMovement.DirectoryTransferContext" /> object that represents the context for the current operation.</span></span></param>
        <summary>
            <span data-ttu-id="75481-269">Kopieren Sie ein Azure-Dateiverzeichnis auf ein Azure-Blob-Verzeichnis ein.</span><span class="sxs-lookup"><span data-stu-id="75481-269">Copy an Azure file directory to an Azure blob directory.</span></span>
            </summary>
        <returns><span data-ttu-id="75481-270">Ein <see cref="T:System.Threading.Tasks.Task`1" /> Objekt des Typs <see cref="T:Microsoft.WindowsAzure.Storage.DataMovement.TransferStatus" /> , die den asynchronen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="75481-270">A <see cref="T:System.Threading.Tasks.Task`1" /> object of type <see cref="T:Microsoft.WindowsAzure.Storage.DataMovement.TransferStatus" /> that represents the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CopyDirectoryAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.DataMovement.TransferStatus&gt; CopyDirectoryAsync (Microsoft.WindowsAzure.Storage.File.CloudFileDirectory sourceFileDir, Microsoft.WindowsAzure.Storage.File.CloudFileDirectory destFileDir, bool isServiceCopy, Microsoft.WindowsAzure.Storage.DataMovement.CopyDirectoryOptions options, Microsoft.WindowsAzure.Storage.DataMovement.DirectoryTransferContext context);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.WindowsAzure.Storage.DataMovement.TransferStatus&gt; CopyDirectoryAsync(class Microsoft.WindowsAzure.Storage.File.CloudFileDirectory sourceFileDir, class Microsoft.WindowsAzure.Storage.File.CloudFileDirectory destFileDir, bool isServiceCopy, class Microsoft.WindowsAzure.Storage.DataMovement.CopyDirectoryOptions options, class Microsoft.WindowsAzure.Storage.DataMovement.DirectoryTransferContext context) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.DataMovement.TransferManager.CopyDirectoryAsync(Microsoft.WindowsAzure.Storage.File.CloudFileDirectory,Microsoft.WindowsAzure.Storage.File.CloudFileDirectory,System.Boolean,Microsoft.WindowsAzure.Storage.DataMovement.CopyDirectoryOptions,Microsoft.WindowsAzure.Storage.DataMovement.DirectoryTransferContext)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function CopyDirectoryAsync (sourceFileDir As CloudFileDirectory, destFileDir As CloudFileDirectory, isServiceCopy As Boolean, options As CopyDirectoryOptions, context As DirectoryTransferContext) As Task(Of TransferStatus)" />
      <MemberSignature Language="F#" Value="static member CopyDirectoryAsync : Microsoft.WindowsAzure.Storage.File.CloudFileDirectory * Microsoft.WindowsAzure.Storage.File.CloudFileDirectory * bool * Microsoft.WindowsAzure.Storage.DataMovement.CopyDirectoryOptions * Microsoft.WindowsAzure.Storage.DataMovement.DirectoryTransferContext -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.DataMovement.TransferStatus&gt;" Usage="Microsoft.WindowsAzure.Storage.DataMovement.TransferManager.CopyDirectoryAsync (sourceFileDir, destFileDir, isServiceCopy, options, context)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage.DataMovement</AssemblyName>
        <AssemblyVersion>0.5.3.0</AssemblyVersion>
        <AssemblyVersion>0.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.DataMovement.TransferStatus&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="sourceFileDir" Type="Microsoft.WindowsAzure.Storage.File.CloudFileDirectory" />
        <Parameter Name="destFileDir" Type="Microsoft.WindowsAzure.Storage.File.CloudFileDirectory" />
        <Parameter Name="isServiceCopy" Type="System.Boolean" />
        <Parameter Name="options" Type="Microsoft.WindowsAzure.Storage.DataMovement.CopyDirectoryOptions" />
        <Parameter Name="context" Type="Microsoft.WindowsAzure.Storage.DataMovement.DirectoryTransferContext" />
      </Parameters>
      <Docs>
        <param name="sourceFileDir"><span data-ttu-id="75481-271">Die <see cref="T:Microsoft.WindowsAzure.Storage.File.CloudFileDirectory" /> also das Quellverzeichnis Azure-Datei.</span><span class="sxs-lookup"><span data-stu-id="75481-271">The <see cref="T:Microsoft.WindowsAzure.Storage.File.CloudFileDirectory" /> that is the source Azure file directory.</span></span></param>
        <param name="destFileDir"><span data-ttu-id="75481-272">Die <see cref="T:Microsoft.WindowsAzure.Storage.File.CloudFileDirectory" /> also das Zielverzeichnis Azure-Datei.</span><span class="sxs-lookup"><span data-stu-id="75481-272">The <see cref="T:Microsoft.WindowsAzure.Storage.File.CloudFileDirectory" /> that is the destination Azure file directory.</span></span></param>
        <param name="isServiceCopy"><span data-ttu-id="75481-273">Ein Flag, das angibt, ob die Kopie aufseiten des Dienstes asynchrone Kopie oder nicht ist.</span><span class="sxs-lookup"><span data-stu-id="75481-273">A flag indicating whether the copy is service-side asynchronous copy or not.</span></span>
            <span data-ttu-id="75481-274">Wenn dieses Flag, auf "true" werden aufseiten des Dienstes asychronen Kopie festgelegt ist wird verwendet. Wenn dieses Flag auf "false" festgelegt ist, wird Datei zuerst von der Quelle heruntergeladen und anschließend auf Ziel hochgeladen.</span><span class="sxs-lookup"><span data-stu-id="75481-274">If this flag is set to true, service-side asychronous copy will be used; if this flag is set to false, file is downloaded from source first, then uploaded to destination.</span></span></param>
        <param name="options"><span data-ttu-id="75481-275">Ein <see cref="T:Microsoft.WindowsAzure.Storage.DataMovement.CopyDirectoryOptions" /> -Objekt, das zusätzliche Optionen für den Vorgang angibt.</span><span class="sxs-lookup"><span data-stu-id="75481-275">A <see cref="T:Microsoft.WindowsAzure.Storage.DataMovement.CopyDirectoryOptions" /> object that specifies additional options for the operation.</span></span></param>
        <param name="context"><span data-ttu-id="75481-276">Ein <see cref="T:Microsoft.WindowsAzure.Storage.DataMovement.DirectoryTransferContext" /> -Objekt, das den Kontext für den aktuellen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="75481-276">A <see cref="T:Microsoft.WindowsAzure.Storage.DataMovement.DirectoryTransferContext" /> object that represents the context for the current operation.</span></span></param>
        <summary>
            <span data-ttu-id="75481-277">Kopieren Sie ein Azure-Dateiverzeichnis, in ein anderes Verzeichnis für Azure-Datei.</span><span class="sxs-lookup"><span data-stu-id="75481-277">Copy an Azure file directory to another Azure file directory.</span></span>
            </summary>
        <returns><span data-ttu-id="75481-278">Ein <see cref="T:System.Threading.Tasks.Task`1" /> Objekt des Typs <see cref="T:Microsoft.WindowsAzure.Storage.DataMovement.TransferStatus" /> , die den asynchronen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="75481-278">A <see cref="T:System.Threading.Tasks.Task`1" /> object of type <see cref="T:Microsoft.WindowsAzure.Storage.DataMovement.TransferStatus" /> that represents the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CopyDirectoryAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.DataMovement.TransferStatus&gt; CopyDirectoryAsync (Microsoft.WindowsAzure.Storage.Blob.CloudBlobDirectory sourceBlobDir, Microsoft.WindowsAzure.Storage.Blob.CloudBlobDirectory destBlobDir, bool isServiceCopy, Microsoft.WindowsAzure.Storage.DataMovement.CopyDirectoryOptions options, Microsoft.WindowsAzure.Storage.DataMovement.DirectoryTransferContext context, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.WindowsAzure.Storage.DataMovement.TransferStatus&gt; CopyDirectoryAsync(class Microsoft.WindowsAzure.Storage.Blob.CloudBlobDirectory sourceBlobDir, class Microsoft.WindowsAzure.Storage.Blob.CloudBlobDirectory destBlobDir, bool isServiceCopy, class Microsoft.WindowsAzure.Storage.DataMovement.CopyDirectoryOptions options, class Microsoft.WindowsAzure.Storage.DataMovement.DirectoryTransferContext context, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.DataMovement.TransferManager.CopyDirectoryAsync(Microsoft.WindowsAzure.Storage.Blob.CloudBlobDirectory,Microsoft.WindowsAzure.Storage.Blob.CloudBlobDirectory,System.Boolean,Microsoft.WindowsAzure.Storage.DataMovement.CopyDirectoryOptions,Microsoft.WindowsAzure.Storage.DataMovement.DirectoryTransferContext,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member CopyDirectoryAsync : Microsoft.WindowsAzure.Storage.Blob.CloudBlobDirectory * Microsoft.WindowsAzure.Storage.Blob.CloudBlobDirectory * bool * Microsoft.WindowsAzure.Storage.DataMovement.CopyDirectoryOptions * Microsoft.WindowsAzure.Storage.DataMovement.DirectoryTransferContext * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.DataMovement.TransferStatus&gt;" Usage="Microsoft.WindowsAzure.Storage.DataMovement.TransferManager.CopyDirectoryAsync (sourceBlobDir, destBlobDir, isServiceCopy, options, context, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage.DataMovement</AssemblyName>
        <AssemblyVersion>0.5.3.0</AssemblyVersion>
        <AssemblyVersion>0.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.DataMovement.TransferStatus&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="sourceBlobDir" Type="Microsoft.WindowsAzure.Storage.Blob.CloudBlobDirectory" />
        <Parameter Name="destBlobDir" Type="Microsoft.WindowsAzure.Storage.Blob.CloudBlobDirectory" />
        <Parameter Name="isServiceCopy" Type="System.Boolean" />
        <Parameter Name="options" Type="Microsoft.WindowsAzure.Storage.DataMovement.CopyDirectoryOptions" />
        <Parameter Name="context" Type="Microsoft.WindowsAzure.Storage.DataMovement.DirectoryTransferContext" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="sourceBlobDir"><span data-ttu-id="75481-279">Die <see cref="T:Microsoft.WindowsAzure.Storage.Blob.CloudBlobDirectory" /> also das Quellverzeichnis Azure-Blob.</span><span class="sxs-lookup"><span data-stu-id="75481-279">The <see cref="T:Microsoft.WindowsAzure.Storage.Blob.CloudBlobDirectory" /> that is the source Azure blob directory.</span></span></param>
        <param name="destBlobDir"><span data-ttu-id="75481-280">Die <see cref="T:Microsoft.WindowsAzure.Storage.Blob.CloudBlobDirectory" /> , das Azure-Blob-Zielverzeichnis.</span><span class="sxs-lookup"><span data-stu-id="75481-280">The <see cref="T:Microsoft.WindowsAzure.Storage.Blob.CloudBlobDirectory" /> that is the destination Azure blob directory.</span></span></param>
        <param name="isServiceCopy"><span data-ttu-id="75481-281">Ein Flag, das angibt, ob die Kopie aufseiten des Dienstes asynchrone Kopie oder nicht ist.</span><span class="sxs-lookup"><span data-stu-id="75481-281">A flag indicating whether the copy is service-side asynchronous copy or not.</span></span>
            <span data-ttu-id="75481-282">Wenn dieses Flag, auf "true" werden aufseiten des Dienstes asychronen Kopie festgelegt ist wird verwendet. Wenn dieses Flag auf "false" festgelegt ist, wird Datei zuerst von der Quelle heruntergeladen und anschließend auf Ziel hochgeladen.</span><span class="sxs-lookup"><span data-stu-id="75481-282">If this flag is set to true, service-side asychronous copy will be used; if this flag is set to false, file is downloaded from source first, then uploaded to destination.</span></span></param>
        <param name="options"><span data-ttu-id="75481-283">Ein <see cref="T:Microsoft.WindowsAzure.Storage.DataMovement.CopyDirectoryOptions" /> -Objekt, das zusätzliche Optionen für den Vorgang angibt.</span><span class="sxs-lookup"><span data-stu-id="75481-283">A <see cref="T:Microsoft.WindowsAzure.Storage.DataMovement.CopyDirectoryOptions" /> object that specifies additional options for the operation.</span></span></param>
        <param name="context"><span data-ttu-id="75481-284">Ein <see cref="T:Microsoft.WindowsAzure.Storage.DataMovement.DirectoryTransferContext" /> -Objekt, das den Kontext für den aktuellen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="75481-284">A <see cref="T:Microsoft.WindowsAzure.Storage.DataMovement.DirectoryTransferContext" /> object that represents the context for the current operation.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="75481-285">Ein <see cref="T:System.Threading.CancellationToken" /> Objekt, das beim Warten auf Abschluss einer Aufgabe überwacht werden.</span><span class="sxs-lookup"><span data-stu-id="75481-285">A <see cref="T:System.Threading.CancellationToken" /> object to observe while waiting for a task to complete.</span></span></param>
        <summary>
            <span data-ttu-id="75481-286">Kopieren Sie ein Azure-Blob-Verzeichnis, in ein anderes Azure-Blob-Verzeichnis.</span><span class="sxs-lookup"><span data-stu-id="75481-286">Copy an Azure blob directory to another Azure blob directory.</span></span>
            </summary>
        <returns><span data-ttu-id="75481-287">Ein <see cref="T:System.Threading.Tasks.Task`1" /> Objekt des Typs <see cref="T:Microsoft.WindowsAzure.Storage.DataMovement.TransferStatus" /> , die den asynchronen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="75481-287">A <see cref="T:System.Threading.Tasks.Task`1" /> object of type <see cref="T:Microsoft.WindowsAzure.Storage.DataMovement.TransferStatus" /> that represents the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CopyDirectoryAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.DataMovement.TransferStatus&gt; CopyDirectoryAsync (Microsoft.WindowsAzure.Storage.Blob.CloudBlobDirectory sourceBlobDir, Microsoft.WindowsAzure.Storage.File.CloudFileDirectory destFileDir, bool isServiceCopy, Microsoft.WindowsAzure.Storage.DataMovement.CopyDirectoryOptions options, Microsoft.WindowsAzure.Storage.DataMovement.DirectoryTransferContext context, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.WindowsAzure.Storage.DataMovement.TransferStatus&gt; CopyDirectoryAsync(class Microsoft.WindowsAzure.Storage.Blob.CloudBlobDirectory sourceBlobDir, class Microsoft.WindowsAzure.Storage.File.CloudFileDirectory destFileDir, bool isServiceCopy, class Microsoft.WindowsAzure.Storage.DataMovement.CopyDirectoryOptions options, class Microsoft.WindowsAzure.Storage.DataMovement.DirectoryTransferContext context, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.DataMovement.TransferManager.CopyDirectoryAsync(Microsoft.WindowsAzure.Storage.Blob.CloudBlobDirectory,Microsoft.WindowsAzure.Storage.File.CloudFileDirectory,System.Boolean,Microsoft.WindowsAzure.Storage.DataMovement.CopyDirectoryOptions,Microsoft.WindowsAzure.Storage.DataMovement.DirectoryTransferContext,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member CopyDirectoryAsync : Microsoft.WindowsAzure.Storage.Blob.CloudBlobDirectory * Microsoft.WindowsAzure.Storage.File.CloudFileDirectory * bool * Microsoft.WindowsAzure.Storage.DataMovement.CopyDirectoryOptions * Microsoft.WindowsAzure.Storage.DataMovement.DirectoryTransferContext * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.DataMovement.TransferStatus&gt;" Usage="Microsoft.WindowsAzure.Storage.DataMovement.TransferManager.CopyDirectoryAsync (sourceBlobDir, destFileDir, isServiceCopy, options, context, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage.DataMovement</AssemblyName>
        <AssemblyVersion>0.5.3.0</AssemblyVersion>
        <AssemblyVersion>0.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.DataMovement.TransferStatus&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="sourceBlobDir" Type="Microsoft.WindowsAzure.Storage.Blob.CloudBlobDirectory" />
        <Parameter Name="destFileDir" Type="Microsoft.WindowsAzure.Storage.File.CloudFileDirectory" />
        <Parameter Name="isServiceCopy" Type="System.Boolean" />
        <Parameter Name="options" Type="Microsoft.WindowsAzure.Storage.DataMovement.CopyDirectoryOptions" />
        <Parameter Name="context" Type="Microsoft.WindowsAzure.Storage.DataMovement.DirectoryTransferContext" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="sourceBlobDir"><span data-ttu-id="75481-288">Die <see cref="T:Microsoft.WindowsAzure.Storage.Blob.CloudBlobDirectory" /> also das Quellverzeichnis Azure-Blob.</span><span class="sxs-lookup"><span data-stu-id="75481-288">The <see cref="T:Microsoft.WindowsAzure.Storage.Blob.CloudBlobDirectory" /> that is the source Azure blob directory.</span></span></param>
        <param name="destFileDir"><span data-ttu-id="75481-289">Die <see cref="T:Microsoft.WindowsAzure.Storage.File.CloudFileDirectory" /> also das Zielverzeichnis Azure-Datei.</span><span class="sxs-lookup"><span data-stu-id="75481-289">The <see cref="T:Microsoft.WindowsAzure.Storage.File.CloudFileDirectory" /> that is the destination Azure file directory.</span></span></param>
        <param name="isServiceCopy"><span data-ttu-id="75481-290">Ein Flag, das angibt, ob die Kopie aufseiten des Dienstes asynchrone Kopie oder nicht ist.</span><span class="sxs-lookup"><span data-stu-id="75481-290">A flag indicating whether the copy is service-side asynchronous copy or not.</span></span>
            <span data-ttu-id="75481-291">Wenn dieses Flag, auf "true" werden aufseiten des Dienstes asychronen Kopie festgelegt ist wird verwendet. Wenn dieses Flag auf "false" festgelegt ist, wird Datei zuerst von der Quelle heruntergeladen und anschließend auf Ziel hochgeladen.</span><span class="sxs-lookup"><span data-stu-id="75481-291">If this flag is set to true, service-side asychronous copy will be used; if this flag is set to false, file is downloaded from source first, then uploaded to destination.</span></span></param>
        <param name="options"><span data-ttu-id="75481-292">Ein <see cref="T:Microsoft.WindowsAzure.Storage.DataMovement.CopyDirectoryOptions" /> -Objekt, das zusätzliche Optionen für den Vorgang angibt.</span><span class="sxs-lookup"><span data-stu-id="75481-292">A <see cref="T:Microsoft.WindowsAzure.Storage.DataMovement.CopyDirectoryOptions" /> object that specifies additional options for the operation.</span></span></param>
        <param name="context"><span data-ttu-id="75481-293">Ein <see cref="T:Microsoft.WindowsAzure.Storage.DataMovement.DirectoryTransferContext" /> -Objekt, das den Kontext für den aktuellen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="75481-293">A <see cref="T:Microsoft.WindowsAzure.Storage.DataMovement.DirectoryTransferContext" /> object that represents the context for the current operation.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="75481-294">Ein <see cref="T:System.Threading.CancellationToken" /> Objekt, das beim Warten auf Abschluss einer Aufgabe überwacht werden.</span><span class="sxs-lookup"><span data-stu-id="75481-294">A <see cref="T:System.Threading.CancellationToken" /> object to observe while waiting for a task to complete.</span></span></param>
        <summary>
            <span data-ttu-id="75481-295">Kopieren Sie ein Azure-Blob-Verzeichnis in einer Azure-Dateiverzeichnis.</span><span class="sxs-lookup"><span data-stu-id="75481-295">Copy an Azure blob directory to an Azure file directory.</span></span>
            </summary>
        <returns><span data-ttu-id="75481-296">Ein <see cref="T:System.Threading.Tasks.Task`1" /> Objekt des Typs <see cref="T:Microsoft.WindowsAzure.Storage.DataMovement.TransferStatus" /> , die den asynchronen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="75481-296">A <see cref="T:System.Threading.Tasks.Task`1" /> object of type <see cref="T:Microsoft.WindowsAzure.Storage.DataMovement.TransferStatus" /> that represents the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CopyDirectoryAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.DataMovement.TransferStatus&gt; CopyDirectoryAsync (Microsoft.WindowsAzure.Storage.File.CloudFileDirectory sourceFileDir, Microsoft.WindowsAzure.Storage.Blob.CloudBlobDirectory destBlobDir, bool isServiceCopy, Microsoft.WindowsAzure.Storage.DataMovement.CopyDirectoryOptions options, Microsoft.WindowsAzure.Storage.DataMovement.DirectoryTransferContext context, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.WindowsAzure.Storage.DataMovement.TransferStatus&gt; CopyDirectoryAsync(class Microsoft.WindowsAzure.Storage.File.CloudFileDirectory sourceFileDir, class Microsoft.WindowsAzure.Storage.Blob.CloudBlobDirectory destBlobDir, bool isServiceCopy, class Microsoft.WindowsAzure.Storage.DataMovement.CopyDirectoryOptions options, class Microsoft.WindowsAzure.Storage.DataMovement.DirectoryTransferContext context, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.DataMovement.TransferManager.CopyDirectoryAsync(Microsoft.WindowsAzure.Storage.File.CloudFileDirectory,Microsoft.WindowsAzure.Storage.Blob.CloudBlobDirectory,System.Boolean,Microsoft.WindowsAzure.Storage.DataMovement.CopyDirectoryOptions,Microsoft.WindowsAzure.Storage.DataMovement.DirectoryTransferContext,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member CopyDirectoryAsync : Microsoft.WindowsAzure.Storage.File.CloudFileDirectory * Microsoft.WindowsAzure.Storage.Blob.CloudBlobDirectory * bool * Microsoft.WindowsAzure.Storage.DataMovement.CopyDirectoryOptions * Microsoft.WindowsAzure.Storage.DataMovement.DirectoryTransferContext * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.DataMovement.TransferStatus&gt;" Usage="Microsoft.WindowsAzure.Storage.DataMovement.TransferManager.CopyDirectoryAsync (sourceFileDir, destBlobDir, isServiceCopy, options, context, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage.DataMovement</AssemblyName>
        <AssemblyVersion>0.5.3.0</AssemblyVersion>
        <AssemblyVersion>0.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.DataMovement.TransferStatus&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="sourceFileDir" Type="Microsoft.WindowsAzure.Storage.File.CloudFileDirectory" />
        <Parameter Name="destBlobDir" Type="Microsoft.WindowsAzure.Storage.Blob.CloudBlobDirectory" />
        <Parameter Name="isServiceCopy" Type="System.Boolean" />
        <Parameter Name="options" Type="Microsoft.WindowsAzure.Storage.DataMovement.CopyDirectoryOptions" />
        <Parameter Name="context" Type="Microsoft.WindowsAzure.Storage.DataMovement.DirectoryTransferContext" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="sourceFileDir"><span data-ttu-id="75481-297">Die <see cref="T:Microsoft.WindowsAzure.Storage.File.CloudFileDirectory" /> also das Quellverzeichnis Azure-Datei.</span><span class="sxs-lookup"><span data-stu-id="75481-297">The <see cref="T:Microsoft.WindowsAzure.Storage.File.CloudFileDirectory" /> that is the source Azure file directory.</span></span></param>
        <param name="destBlobDir"><span data-ttu-id="75481-298">Die <see cref="T:Microsoft.WindowsAzure.Storage.Blob.CloudBlobDirectory" /> , das Azure-Blob-Zielverzeichnis.</span><span class="sxs-lookup"><span data-stu-id="75481-298">The <see cref="T:Microsoft.WindowsAzure.Storage.Blob.CloudBlobDirectory" /> that is the destination Azure blob directory.</span></span></param>
        <param name="isServiceCopy"><span data-ttu-id="75481-299">Ein Flag, das angibt, ob die Kopie aufseiten des Dienstes asynchrone Kopie oder nicht ist.</span><span class="sxs-lookup"><span data-stu-id="75481-299">A flag indicating whether the copy is service-side asynchronous copy or not.</span></span>
            <span data-ttu-id="75481-300">Wenn dieses Flag, auf "true" werden aufseiten des Dienstes asychronen Kopie festgelegt ist wird verwendet. Wenn dieses Flag auf "false" festgelegt ist, wird Datei zuerst von der Quelle heruntergeladen und anschließend auf Ziel hochgeladen.</span><span class="sxs-lookup"><span data-stu-id="75481-300">If this flag is set to true, service-side asychronous copy will be used; if this flag is set to false, file is downloaded from source first, then uploaded to destination.</span></span></param>
        <param name="options"><span data-ttu-id="75481-301">Ein <see cref="T:Microsoft.WindowsAzure.Storage.DataMovement.CopyDirectoryOptions" /> -Objekt, das zusätzliche Optionen für den Vorgang angibt.</span><span class="sxs-lookup"><span data-stu-id="75481-301">A <see cref="T:Microsoft.WindowsAzure.Storage.DataMovement.CopyDirectoryOptions" /> object that specifies additional options for the operation.</span></span></param>
        <param name="context"><span data-ttu-id="75481-302">Ein <see cref="T:Microsoft.WindowsAzure.Storage.DataMovement.DirectoryTransferContext" /> -Objekt, das den Kontext für den aktuellen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="75481-302">A <see cref="T:Microsoft.WindowsAzure.Storage.DataMovement.DirectoryTransferContext" /> object that represents the context for the current operation.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="75481-303">Ein <see cref="T:System.Threading.CancellationToken" /> Objekt, das beim Warten auf Abschluss einer Aufgabe überwacht werden.</span><span class="sxs-lookup"><span data-stu-id="75481-303">A <see cref="T:System.Threading.CancellationToken" /> object to observe while waiting for a task to complete.</span></span></param>
        <summary>
            <span data-ttu-id="75481-304">Kopieren Sie ein Azure-Dateiverzeichnis auf ein Azure-Blob-Verzeichnis ein.</span><span class="sxs-lookup"><span data-stu-id="75481-304">Copy an Azure file directory to an Azure blob directory.</span></span>
            </summary>
        <returns><span data-ttu-id="75481-305">Ein <see cref="T:System.Threading.Tasks.Task`1" /> Objekt des Typs <see cref="T:Microsoft.WindowsAzure.Storage.DataMovement.TransferStatus" /> , die den asynchronen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="75481-305">A <see cref="T:System.Threading.Tasks.Task`1" /> object of type <see cref="T:Microsoft.WindowsAzure.Storage.DataMovement.TransferStatus" /> that represents the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CopyDirectoryAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.DataMovement.TransferStatus&gt; CopyDirectoryAsync (Microsoft.WindowsAzure.Storage.File.CloudFileDirectory sourceFileDir, Microsoft.WindowsAzure.Storage.File.CloudFileDirectory destFileDir, bool isServiceCopy, Microsoft.WindowsAzure.Storage.DataMovement.CopyDirectoryOptions options, Microsoft.WindowsAzure.Storage.DataMovement.DirectoryTransferContext context, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.WindowsAzure.Storage.DataMovement.TransferStatus&gt; CopyDirectoryAsync(class Microsoft.WindowsAzure.Storage.File.CloudFileDirectory sourceFileDir, class Microsoft.WindowsAzure.Storage.File.CloudFileDirectory destFileDir, bool isServiceCopy, class Microsoft.WindowsAzure.Storage.DataMovement.CopyDirectoryOptions options, class Microsoft.WindowsAzure.Storage.DataMovement.DirectoryTransferContext context, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.DataMovement.TransferManager.CopyDirectoryAsync(Microsoft.WindowsAzure.Storage.File.CloudFileDirectory,Microsoft.WindowsAzure.Storage.File.CloudFileDirectory,System.Boolean,Microsoft.WindowsAzure.Storage.DataMovement.CopyDirectoryOptions,Microsoft.WindowsAzure.Storage.DataMovement.DirectoryTransferContext,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member CopyDirectoryAsync : Microsoft.WindowsAzure.Storage.File.CloudFileDirectory * Microsoft.WindowsAzure.Storage.File.CloudFileDirectory * bool * Microsoft.WindowsAzure.Storage.DataMovement.CopyDirectoryOptions * Microsoft.WindowsAzure.Storage.DataMovement.DirectoryTransferContext * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.DataMovement.TransferStatus&gt;" Usage="Microsoft.WindowsAzure.Storage.DataMovement.TransferManager.CopyDirectoryAsync (sourceFileDir, destFileDir, isServiceCopy, options, context, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage.DataMovement</AssemblyName>
        <AssemblyVersion>0.5.3.0</AssemblyVersion>
        <AssemblyVersion>0.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.DataMovement.TransferStatus&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="sourceFileDir" Type="Microsoft.WindowsAzure.Storage.File.CloudFileDirectory" />
        <Parameter Name="destFileDir" Type="Microsoft.WindowsAzure.Storage.File.CloudFileDirectory" />
        <Parameter Name="isServiceCopy" Type="System.Boolean" />
        <Parameter Name="options" Type="Microsoft.WindowsAzure.Storage.DataMovement.CopyDirectoryOptions" />
        <Parameter Name="context" Type="Microsoft.WindowsAzure.Storage.DataMovement.DirectoryTransferContext" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="sourceFileDir"><span data-ttu-id="75481-306">Die <see cref="T:Microsoft.WindowsAzure.Storage.File.CloudFileDirectory" /> also das Quellverzeichnis Azure-Datei.</span><span class="sxs-lookup"><span data-stu-id="75481-306">The <see cref="T:Microsoft.WindowsAzure.Storage.File.CloudFileDirectory" /> that is the source Azure file directory.</span></span></param>
        <param name="destFileDir"><span data-ttu-id="75481-307">Die <see cref="T:Microsoft.WindowsAzure.Storage.File.CloudFileDirectory" /> also das Zielverzeichnis Azure-Datei.</span><span class="sxs-lookup"><span data-stu-id="75481-307">The <see cref="T:Microsoft.WindowsAzure.Storage.File.CloudFileDirectory" /> that is the destination Azure file directory.</span></span></param>
        <param name="isServiceCopy"><span data-ttu-id="75481-308">Ein Flag, das angibt, ob die Kopie aufseiten des Dienstes asynchrone Kopie oder nicht ist.</span><span class="sxs-lookup"><span data-stu-id="75481-308">A flag indicating whether the copy is service-side asynchronous copy or not.</span></span>
            <span data-ttu-id="75481-309">Wenn dieses Flag, auf "true" werden aufseiten des Dienstes asychronen Kopie festgelegt ist wird verwendet. Wenn dieses Flag auf "false" festgelegt ist, wird Datei zuerst von der Quelle heruntergeladen und anschließend auf Ziel hochgeladen.</span><span class="sxs-lookup"><span data-stu-id="75481-309">If this flag is set to true, service-side asychronous copy will be used; if this flag is set to false, file is downloaded from source first, then uploaded to destination.</span></span></param>
        <param name="options"><span data-ttu-id="75481-310">Ein <see cref="T:Microsoft.WindowsAzure.Storage.DataMovement.CopyDirectoryOptions" /> -Objekt, das zusätzliche Optionen für den Vorgang angibt.</span><span class="sxs-lookup"><span data-stu-id="75481-310">A <see cref="T:Microsoft.WindowsAzure.Storage.DataMovement.CopyDirectoryOptions" /> object that specifies additional options for the operation.</span></span></param>
        <param name="context"><span data-ttu-id="75481-311">Ein <see cref="T:Microsoft.WindowsAzure.Storage.DataMovement.DirectoryTransferContext" /> -Objekt, das den Kontext für den aktuellen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="75481-311">A <see cref="T:Microsoft.WindowsAzure.Storage.DataMovement.DirectoryTransferContext" /> object that represents the context for the current operation.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="75481-312">Ein <see cref="T:System.Threading.CancellationToken" /> Objekt, das beim Warten auf Abschluss einer Aufgabe überwacht werden.</span><span class="sxs-lookup"><span data-stu-id="75481-312">A <see cref="T:System.Threading.CancellationToken" /> object to observe while waiting for a task to complete.</span></span></param>
        <summary>
            <span data-ttu-id="75481-313">Kopieren Sie ein Azure-Dateiverzeichnis, in ein anderes Verzeichnis für Azure-Datei.</span><span class="sxs-lookup"><span data-stu-id="75481-313">Copy an Azure file directory to another Azure file directory.</span></span>
            </summary>
        <returns><span data-ttu-id="75481-314">Ein <see cref="T:System.Threading.Tasks.Task`1" /> Objekt des Typs <see cref="T:Microsoft.WindowsAzure.Storage.DataMovement.TransferStatus" /> , die den asynchronen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="75481-314">A <see cref="T:System.Threading.Tasks.Task`1" /> object of type <see cref="T:Microsoft.WindowsAzure.Storage.DataMovement.TransferStatus" /> that represents the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DownloadAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task DownloadAsync (Microsoft.WindowsAzure.Storage.Blob.CloudBlob sourceBlob, System.IO.Stream destStream);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task DownloadAsync(class Microsoft.WindowsAzure.Storage.Blob.CloudBlob sourceBlob, class System.IO.Stream destStream) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.DataMovement.TransferManager.DownloadAsync(Microsoft.WindowsAzure.Storage.Blob.CloudBlob,System.IO.Stream)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function DownloadAsync (sourceBlob As CloudBlob, destStream As Stream) As Task" />
      <MemberSignature Language="F#" Value="static member DownloadAsync : Microsoft.WindowsAzure.Storage.Blob.CloudBlob * System.IO.Stream -&gt; System.Threading.Tasks.Task" Usage="Microsoft.WindowsAzure.Storage.DataMovement.TransferManager.DownloadAsync (sourceBlob, destStream)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage.DataMovement</AssemblyName>
        <AssemblyVersion>0.5.3.0</AssemblyVersion>
        <AssemblyVersion>0.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="sourceBlob" Type="Microsoft.WindowsAzure.Storage.Blob.CloudBlob" />
        <Parameter Name="destStream" Type="System.IO.Stream" />
      </Parameters>
      <Docs>
        <param name="sourceBlob"><span data-ttu-id="75481-315">Die <see cref="T:Microsoft.WindowsAzure.Storage.Blob.CloudBlob" /> , der die Quelle Azure-Blob.</span><span class="sxs-lookup"><span data-stu-id="75481-315">The <see cref="T:Microsoft.WindowsAzure.Storage.Blob.CloudBlob" /> that is the source Azure blob.</span></span></param>
        <param name="destStream"><span data-ttu-id="75481-316">Ein <see cref="T:System.IO.Stream" /> Objekt, das den Zieldatenstrom darstellt.</span><span class="sxs-lookup"><span data-stu-id="75481-316">A <see cref="T:System.IO.Stream" /> object representing the destination stream.</span></span></param>
        <summary>
            <span data-ttu-id="75481-317">Eine Azure-blob aus dem Azure-Blob-Speicher herunterladen.</span><span class="sxs-lookup"><span data-stu-id="75481-317">Download an Azure blob from Azure Blob Storage.</span></span>
            </summary>
        <returns><span data-ttu-id="75481-318">Ein <see cref="T:System.Threading.Tasks.Task" />-Objekt, das den asynchronen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="75481-318">A <see cref="T:System.Threading.Tasks.Task" /> object that represents the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DownloadAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task DownloadAsync (Microsoft.WindowsAzure.Storage.Blob.CloudBlob sourceBlob, string destPath);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task DownloadAsync(class Microsoft.WindowsAzure.Storage.Blob.CloudBlob sourceBlob, string destPath) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.DataMovement.TransferManager.DownloadAsync(Microsoft.WindowsAzure.Storage.Blob.CloudBlob,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function DownloadAsync (sourceBlob As CloudBlob, destPath As String) As Task" />
      <MemberSignature Language="F#" Value="static member DownloadAsync : Microsoft.WindowsAzure.Storage.Blob.CloudBlob * string -&gt; System.Threading.Tasks.Task" Usage="Microsoft.WindowsAzure.Storage.DataMovement.TransferManager.DownloadAsync (sourceBlob, destPath)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage.DataMovement</AssemblyName>
        <AssemblyVersion>0.5.3.0</AssemblyVersion>
        <AssemblyVersion>0.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="sourceBlob" Type="Microsoft.WindowsAzure.Storage.Blob.CloudBlob" />
        <Parameter Name="destPath" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="sourceBlob"><span data-ttu-id="75481-319">Die <see cref="T:Microsoft.WindowsAzure.Storage.Blob.CloudBlob" /> , der die Quelle Azure-Blob.</span><span class="sxs-lookup"><span data-stu-id="75481-319">The <see cref="T:Microsoft.WindowsAzure.Storage.Blob.CloudBlob" /> that is the source Azure blob.</span></span></param>
        <param name="destPath"><span data-ttu-id="75481-320">Pfad zur Zieldatei.</span><span class="sxs-lookup"><span data-stu-id="75481-320">Path to the destination file.</span></span></param>
        <summary>
            <span data-ttu-id="75481-321">Eine Azure-blob aus dem Azure-Blob-Speicher herunterladen.</span><span class="sxs-lookup"><span data-stu-id="75481-321">Download an Azure blob from Azure Blob Storage.</span></span>
            </summary>
        <returns><span data-ttu-id="75481-322">Ein <see cref="T:System.Threading.Tasks.Task" />-Objekt, das den asynchronen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="75481-322">A <see cref="T:System.Threading.Tasks.Task" /> object that represents the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DownloadAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task DownloadAsync (Microsoft.WindowsAzure.Storage.File.CloudFile sourceFile, System.IO.Stream destStream);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task DownloadAsync(class Microsoft.WindowsAzure.Storage.File.CloudFile sourceFile, class System.IO.Stream destStream) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.DataMovement.TransferManager.DownloadAsync(Microsoft.WindowsAzure.Storage.File.CloudFile,System.IO.Stream)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function DownloadAsync (sourceFile As CloudFile, destStream As Stream) As Task" />
      <MemberSignature Language="F#" Value="static member DownloadAsync : Microsoft.WindowsAzure.Storage.File.CloudFile * System.IO.Stream -&gt; System.Threading.Tasks.Task" Usage="Microsoft.WindowsAzure.Storage.DataMovement.TransferManager.DownloadAsync (sourceFile, destStream)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage.DataMovement</AssemblyName>
        <AssemblyVersion>0.5.3.0</AssemblyVersion>
        <AssemblyVersion>0.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="sourceFile" Type="Microsoft.WindowsAzure.Storage.File.CloudFile" />
        <Parameter Name="destStream" Type="System.IO.Stream" />
      </Parameters>
      <Docs>
        <param name="sourceFile"><span data-ttu-id="75481-323">Die <see cref="T:Microsoft.WindowsAzure.Storage.File.CloudFile" /> , der die Quelle Azure-Datei.</span><span class="sxs-lookup"><span data-stu-id="75481-323">The <see cref="T:Microsoft.WindowsAzure.Storage.File.CloudFile" /> that is the source Azure file.</span></span></param>
        <param name="destStream"><span data-ttu-id="75481-324">Ein <see cref="T:System.IO.Stream" /> Objekt, das den Zieldatenstrom darstellt.</span><span class="sxs-lookup"><span data-stu-id="75481-324">A <see cref="T:System.IO.Stream" /> object representing the destination stream.</span></span></param>
        <summary>
            <span data-ttu-id="75481-325">Laden Sie eine Azure-Datei aus Azure File Storage herunter.</span><span class="sxs-lookup"><span data-stu-id="75481-325">Download an Azure file from Azure File Storage.</span></span>
            </summary>
        <returns><span data-ttu-id="75481-326">Ein <see cref="T:System.Threading.Tasks.Task" />-Objekt, das den asynchronen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="75481-326">A <see cref="T:System.Threading.Tasks.Task" /> object that represents the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DownloadAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task DownloadAsync (Microsoft.WindowsAzure.Storage.File.CloudFile sourceFile, string destPath);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task DownloadAsync(class Microsoft.WindowsAzure.Storage.File.CloudFile sourceFile, string destPath) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.DataMovement.TransferManager.DownloadAsync(Microsoft.WindowsAzure.Storage.File.CloudFile,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function DownloadAsync (sourceFile As CloudFile, destPath As String) As Task" />
      <MemberSignature Language="F#" Value="static member DownloadAsync : Microsoft.WindowsAzure.Storage.File.CloudFile * string -&gt; System.Threading.Tasks.Task" Usage="Microsoft.WindowsAzure.Storage.DataMovement.TransferManager.DownloadAsync (sourceFile, destPath)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage.DataMovement</AssemblyName>
        <AssemblyVersion>0.5.3.0</AssemblyVersion>
        <AssemblyVersion>0.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="sourceFile" Type="Microsoft.WindowsAzure.Storage.File.CloudFile" />
        <Parameter Name="destPath" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="sourceFile"><span data-ttu-id="75481-327">Die <see cref="T:Microsoft.WindowsAzure.Storage.File.CloudFile" /> , der die Quelle Azure-Datei.</span><span class="sxs-lookup"><span data-stu-id="75481-327">The <see cref="T:Microsoft.WindowsAzure.Storage.File.CloudFile" /> that is the source Azure file.</span></span></param>
        <param name="destPath"><span data-ttu-id="75481-328">Pfad zur Zieldatei.</span><span class="sxs-lookup"><span data-stu-id="75481-328">Path to the destination file.</span></span></param>
        <summary>
            <span data-ttu-id="75481-329">Laden Sie eine Azure-Datei aus Azure File Storage herunter.</span><span class="sxs-lookup"><span data-stu-id="75481-329">Download an Azure file from Azure File Storage.</span></span>
            </summary>
        <returns><span data-ttu-id="75481-330">Ein <see cref="T:System.Threading.Tasks.Task" />-Objekt, das den asynchronen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="75481-330">A <see cref="T:System.Threading.Tasks.Task" /> object that represents the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DownloadAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task DownloadAsync (Microsoft.WindowsAzure.Storage.Blob.CloudBlob sourceBlob, System.IO.Stream destStream, Microsoft.WindowsAzure.Storage.DataMovement.DownloadOptions options, Microsoft.WindowsAzure.Storage.DataMovement.SingleTransferContext context);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task DownloadAsync(class Microsoft.WindowsAzure.Storage.Blob.CloudBlob sourceBlob, class System.IO.Stream destStream, class Microsoft.WindowsAzure.Storage.DataMovement.DownloadOptions options, class Microsoft.WindowsAzure.Storage.DataMovement.SingleTransferContext context) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.DataMovement.TransferManager.DownloadAsync(Microsoft.WindowsAzure.Storage.Blob.CloudBlob,System.IO.Stream,Microsoft.WindowsAzure.Storage.DataMovement.DownloadOptions,Microsoft.WindowsAzure.Storage.DataMovement.SingleTransferContext)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function DownloadAsync (sourceBlob As CloudBlob, destStream As Stream, options As DownloadOptions, context As SingleTransferContext) As Task" />
      <MemberSignature Language="F#" Value="static member DownloadAsync : Microsoft.WindowsAzure.Storage.Blob.CloudBlob * System.IO.Stream * Microsoft.WindowsAzure.Storage.DataMovement.DownloadOptions * Microsoft.WindowsAzure.Storage.DataMovement.SingleTransferContext -&gt; System.Threading.Tasks.Task" Usage="Microsoft.WindowsAzure.Storage.DataMovement.TransferManager.DownloadAsync (sourceBlob, destStream, options, context)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage.DataMovement</AssemblyName>
        <AssemblyVersion>0.5.3.0</AssemblyVersion>
        <AssemblyVersion>0.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="sourceBlob" Type="Microsoft.WindowsAzure.Storage.Blob.CloudBlob" />
        <Parameter Name="destStream" Type="System.IO.Stream" />
        <Parameter Name="options" Type="Microsoft.WindowsAzure.Storage.DataMovement.DownloadOptions" />
        <Parameter Name="context" Type="Microsoft.WindowsAzure.Storage.DataMovement.SingleTransferContext" />
      </Parameters>
      <Docs>
        <param name="sourceBlob"><span data-ttu-id="75481-331">Die <see cref="T:Microsoft.WindowsAzure.Storage.Blob.CloudBlob" /> , der die Quelle Azure-Blob.</span><span class="sxs-lookup"><span data-stu-id="75481-331">The <see cref="T:Microsoft.WindowsAzure.Storage.Blob.CloudBlob" /> that is the source Azure blob.</span></span></param>
        <param name="destStream"><span data-ttu-id="75481-332">Ein <see cref="T:System.IO.Stream" /> Objekt, das den Zieldatenstrom darstellt.</span><span class="sxs-lookup"><span data-stu-id="75481-332">A <see cref="T:System.IO.Stream" /> object representing the destination stream.</span></span></param>
        <param name="options"><span data-ttu-id="75481-333">Ein <see cref="T:Microsoft.WindowsAzure.Storage.DataMovement.DownloadOptions" /> -Objekt, das zusätzliche Optionen für den Vorgang angibt.</span><span class="sxs-lookup"><span data-stu-id="75481-333">A <see cref="T:Microsoft.WindowsAzure.Storage.DataMovement.DownloadOptions" /> object that specifies additional options for the operation.</span></span></param>
        <param name="context"><span data-ttu-id="75481-334">Ein <see cref="T:Microsoft.WindowsAzure.Storage.DataMovement.SingleTransferContext" /> -Objekt, das den Kontext für den aktuellen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="75481-334">A <see cref="T:Microsoft.WindowsAzure.Storage.DataMovement.SingleTransferContext" /> object that represents the context for the current operation.</span></span></param>
        <summary>
            <span data-ttu-id="75481-335">Eine Azure-blob aus dem Azure-Blob-Speicher herunterladen.</span><span class="sxs-lookup"><span data-stu-id="75481-335">Download an Azure blob from Azure Blob Storage.</span></span>
            </summary>
        <returns><span data-ttu-id="75481-336">Ein <see cref="T:System.Threading.Tasks.Task" />-Objekt, das den asynchronen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="75481-336">A <see cref="T:System.Threading.Tasks.Task" /> object that represents the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DownloadAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task DownloadAsync (Microsoft.WindowsAzure.Storage.Blob.CloudBlob sourceBlob, string destPath, Microsoft.WindowsAzure.Storage.DataMovement.DownloadOptions options, Microsoft.WindowsAzure.Storage.DataMovement.SingleTransferContext context);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task DownloadAsync(class Microsoft.WindowsAzure.Storage.Blob.CloudBlob sourceBlob, string destPath, class Microsoft.WindowsAzure.Storage.DataMovement.DownloadOptions options, class Microsoft.WindowsAzure.Storage.DataMovement.SingleTransferContext context) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.DataMovement.TransferManager.DownloadAsync(Microsoft.WindowsAzure.Storage.Blob.CloudBlob,System.String,Microsoft.WindowsAzure.Storage.DataMovement.DownloadOptions,Microsoft.WindowsAzure.Storage.DataMovement.SingleTransferContext)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function DownloadAsync (sourceBlob As CloudBlob, destPath As String, options As DownloadOptions, context As SingleTransferContext) As Task" />
      <MemberSignature Language="F#" Value="static member DownloadAsync : Microsoft.WindowsAzure.Storage.Blob.CloudBlob * string * Microsoft.WindowsAzure.Storage.DataMovement.DownloadOptions * Microsoft.WindowsAzure.Storage.DataMovement.SingleTransferContext -&gt; System.Threading.Tasks.Task" Usage="Microsoft.WindowsAzure.Storage.DataMovement.TransferManager.DownloadAsync (sourceBlob, destPath, options, context)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage.DataMovement</AssemblyName>
        <AssemblyVersion>0.5.3.0</AssemblyVersion>
        <AssemblyVersion>0.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="sourceBlob" Type="Microsoft.WindowsAzure.Storage.Blob.CloudBlob" />
        <Parameter Name="destPath" Type="System.String" />
        <Parameter Name="options" Type="Microsoft.WindowsAzure.Storage.DataMovement.DownloadOptions" />
        <Parameter Name="context" Type="Microsoft.WindowsAzure.Storage.DataMovement.SingleTransferContext" />
      </Parameters>
      <Docs>
        <param name="sourceBlob"><span data-ttu-id="75481-337">Die <see cref="T:Microsoft.WindowsAzure.Storage.Blob.CloudBlob" /> , der die Quelle Azure-Blob.</span><span class="sxs-lookup"><span data-stu-id="75481-337">The <see cref="T:Microsoft.WindowsAzure.Storage.Blob.CloudBlob" /> that is the source Azure blob.</span></span></param>
        <param name="destPath"><span data-ttu-id="75481-338">Pfad zur Zieldatei.</span><span class="sxs-lookup"><span data-stu-id="75481-338">Path to the destination file.</span></span></param>
        <param name="options"><span data-ttu-id="75481-339">Ein <see cref="T:Microsoft.WindowsAzure.Storage.DataMovement.DownloadOptions" /> -Objekt, das zusätzliche Optionen für den Vorgang angibt.</span><span class="sxs-lookup"><span data-stu-id="75481-339">A <see cref="T:Microsoft.WindowsAzure.Storage.DataMovement.DownloadOptions" /> object that specifies additional options for the operation.</span></span></param>
        <param name="context"><span data-ttu-id="75481-340">Ein <see cref="T:Microsoft.WindowsAzure.Storage.DataMovement.SingleTransferContext" /> -Objekt, das den Kontext für den aktuellen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="75481-340">A <see cref="T:Microsoft.WindowsAzure.Storage.DataMovement.SingleTransferContext" /> object that represents the context for the current operation.</span></span></param>
        <summary>
            <span data-ttu-id="75481-341">Eine Azure-blob aus dem Azure-Blob-Speicher herunterladen.</span><span class="sxs-lookup"><span data-stu-id="75481-341">Download an Azure blob from Azure Blob Storage.</span></span>
            </summary>
        <returns><span data-ttu-id="75481-342">Ein <see cref="T:System.Threading.Tasks.Task" />-Objekt, das den asynchronen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="75481-342">A <see cref="T:System.Threading.Tasks.Task" /> object that represents the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DownloadAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task DownloadAsync (Microsoft.WindowsAzure.Storage.File.CloudFile sourceFile, System.IO.Stream destStream, Microsoft.WindowsAzure.Storage.DataMovement.DownloadOptions options, Microsoft.WindowsAzure.Storage.DataMovement.SingleTransferContext context);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task DownloadAsync(class Microsoft.WindowsAzure.Storage.File.CloudFile sourceFile, class System.IO.Stream destStream, class Microsoft.WindowsAzure.Storage.DataMovement.DownloadOptions options, class Microsoft.WindowsAzure.Storage.DataMovement.SingleTransferContext context) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.DataMovement.TransferManager.DownloadAsync(Microsoft.WindowsAzure.Storage.File.CloudFile,System.IO.Stream,Microsoft.WindowsAzure.Storage.DataMovement.DownloadOptions,Microsoft.WindowsAzure.Storage.DataMovement.SingleTransferContext)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function DownloadAsync (sourceFile As CloudFile, destStream As Stream, options As DownloadOptions, context As SingleTransferContext) As Task" />
      <MemberSignature Language="F#" Value="static member DownloadAsync : Microsoft.WindowsAzure.Storage.File.CloudFile * System.IO.Stream * Microsoft.WindowsAzure.Storage.DataMovement.DownloadOptions * Microsoft.WindowsAzure.Storage.DataMovement.SingleTransferContext -&gt; System.Threading.Tasks.Task" Usage="Microsoft.WindowsAzure.Storage.DataMovement.TransferManager.DownloadAsync (sourceFile, destStream, options, context)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage.DataMovement</AssemblyName>
        <AssemblyVersion>0.5.3.0</AssemblyVersion>
        <AssemblyVersion>0.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="sourceFile" Type="Microsoft.WindowsAzure.Storage.File.CloudFile" />
        <Parameter Name="destStream" Type="System.IO.Stream" />
        <Parameter Name="options" Type="Microsoft.WindowsAzure.Storage.DataMovement.DownloadOptions" />
        <Parameter Name="context" Type="Microsoft.WindowsAzure.Storage.DataMovement.SingleTransferContext" />
      </Parameters>
      <Docs>
        <param name="sourceFile"><span data-ttu-id="75481-343">Die <see cref="T:Microsoft.WindowsAzure.Storage.File.CloudFile" /> , der die Quelle Azure-Datei.</span><span class="sxs-lookup"><span data-stu-id="75481-343">The <see cref="T:Microsoft.WindowsAzure.Storage.File.CloudFile" /> that is the source Azure file.</span></span></param>
        <param name="destStream"><span data-ttu-id="75481-344">Ein <see cref="T:System.IO.Stream" /> Objekt, das den Zieldatenstrom darstellt.</span><span class="sxs-lookup"><span data-stu-id="75481-344">A <see cref="T:System.IO.Stream" /> object representing the destination stream.</span></span></param>
        <param name="options"><span data-ttu-id="75481-345">Ein <see cref="T:Microsoft.WindowsAzure.Storage.DataMovement.DownloadOptions" /> -Objekt, das zusätzliche Optionen für den Vorgang angibt.</span><span class="sxs-lookup"><span data-stu-id="75481-345">A <see cref="T:Microsoft.WindowsAzure.Storage.DataMovement.DownloadOptions" /> object that specifies additional options for the operation.</span></span></param>
        <param name="context"><span data-ttu-id="75481-346">Ein <see cref="T:Microsoft.WindowsAzure.Storage.DataMovement.SingleTransferContext" /> -Objekt, das den Kontext für den aktuellen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="75481-346">A <see cref="T:Microsoft.WindowsAzure.Storage.DataMovement.SingleTransferContext" /> object that represents the context for the current operation.</span></span></param>
        <summary>
            <span data-ttu-id="75481-347">Laden Sie eine Azure-Datei aus Azure File Storage herunter.</span><span class="sxs-lookup"><span data-stu-id="75481-347">Download an Azure file from Azure File Storage.</span></span>
            </summary>
        <returns><span data-ttu-id="75481-348">Ein <see cref="T:System.Threading.Tasks.Task" />-Objekt, das den asynchronen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="75481-348">A <see cref="T:System.Threading.Tasks.Task" /> object that represents the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DownloadAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task DownloadAsync (Microsoft.WindowsAzure.Storage.File.CloudFile sourceFile, string destPath, Microsoft.WindowsAzure.Storage.DataMovement.DownloadOptions options, Microsoft.WindowsAzure.Storage.DataMovement.SingleTransferContext context);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task DownloadAsync(class Microsoft.WindowsAzure.Storage.File.CloudFile sourceFile, string destPath, class Microsoft.WindowsAzure.Storage.DataMovement.DownloadOptions options, class Microsoft.WindowsAzure.Storage.DataMovement.SingleTransferContext context) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.DataMovement.TransferManager.DownloadAsync(Microsoft.WindowsAzure.Storage.File.CloudFile,System.String,Microsoft.WindowsAzure.Storage.DataMovement.DownloadOptions,Microsoft.WindowsAzure.Storage.DataMovement.SingleTransferContext)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function DownloadAsync (sourceFile As CloudFile, destPath As String, options As DownloadOptions, context As SingleTransferContext) As Task" />
      <MemberSignature Language="F#" Value="static member DownloadAsync : Microsoft.WindowsAzure.Storage.File.CloudFile * string * Microsoft.WindowsAzure.Storage.DataMovement.DownloadOptions * Microsoft.WindowsAzure.Storage.DataMovement.SingleTransferContext -&gt; System.Threading.Tasks.Task" Usage="Microsoft.WindowsAzure.Storage.DataMovement.TransferManager.DownloadAsync (sourceFile, destPath, options, context)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage.DataMovement</AssemblyName>
        <AssemblyVersion>0.5.3.0</AssemblyVersion>
        <AssemblyVersion>0.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="sourceFile" Type="Microsoft.WindowsAzure.Storage.File.CloudFile" />
        <Parameter Name="destPath" Type="System.String" />
        <Parameter Name="options" Type="Microsoft.WindowsAzure.Storage.DataMovement.DownloadOptions" />
        <Parameter Name="context" Type="Microsoft.WindowsAzure.Storage.DataMovement.SingleTransferContext" />
      </Parameters>
      <Docs>
        <param name="sourceFile"><span data-ttu-id="75481-349">Die <see cref="T:Microsoft.WindowsAzure.Storage.File.CloudFile" /> , der die Quelle Azure-Datei.</span><span class="sxs-lookup"><span data-stu-id="75481-349">The <see cref="T:Microsoft.WindowsAzure.Storage.File.CloudFile" /> that is the source Azure file.</span></span></param>
        <param name="destPath"><span data-ttu-id="75481-350">Pfad zur Zieldatei.</span><span class="sxs-lookup"><span data-stu-id="75481-350">Path to the destination file.</span></span></param>
        <param name="options"><span data-ttu-id="75481-351">Ein <see cref="T:Microsoft.WindowsAzure.Storage.DataMovement.DownloadOptions" /> -Objekt, das zusätzliche Optionen für den Vorgang angibt.</span><span class="sxs-lookup"><span data-stu-id="75481-351">A <see cref="T:Microsoft.WindowsAzure.Storage.DataMovement.DownloadOptions" /> object that specifies additional options for the operation.</span></span></param>
        <param name="context"><span data-ttu-id="75481-352">Ein <see cref="T:Microsoft.WindowsAzure.Storage.DataMovement.SingleTransferContext" /> -Objekt, das den Kontext für den aktuellen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="75481-352">A <see cref="T:Microsoft.WindowsAzure.Storage.DataMovement.SingleTransferContext" /> object that represents the context for the current operation.</span></span></param>
        <summary>
            <span data-ttu-id="75481-353">Laden Sie eine Azure-Datei aus Azure File Storage herunter.</span><span class="sxs-lookup"><span data-stu-id="75481-353">Download an Azure file from Azure File Storage.</span></span>
            </summary>
        <returns><span data-ttu-id="75481-354">Ein <see cref="T:System.Threading.Tasks.Task" />-Objekt, das den asynchronen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="75481-354">A <see cref="T:System.Threading.Tasks.Task" /> object that represents the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DownloadAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task DownloadAsync (Microsoft.WindowsAzure.Storage.Blob.CloudBlob sourceBlob, System.IO.Stream destStream, Microsoft.WindowsAzure.Storage.DataMovement.DownloadOptions options, Microsoft.WindowsAzure.Storage.DataMovement.SingleTransferContext context, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task DownloadAsync(class Microsoft.WindowsAzure.Storage.Blob.CloudBlob sourceBlob, class System.IO.Stream destStream, class Microsoft.WindowsAzure.Storage.DataMovement.DownloadOptions options, class Microsoft.WindowsAzure.Storage.DataMovement.SingleTransferContext context, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.DataMovement.TransferManager.DownloadAsync(Microsoft.WindowsAzure.Storage.Blob.CloudBlob,System.IO.Stream,Microsoft.WindowsAzure.Storage.DataMovement.DownloadOptions,Microsoft.WindowsAzure.Storage.DataMovement.SingleTransferContext,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member DownloadAsync : Microsoft.WindowsAzure.Storage.Blob.CloudBlob * System.IO.Stream * Microsoft.WindowsAzure.Storage.DataMovement.DownloadOptions * Microsoft.WindowsAzure.Storage.DataMovement.SingleTransferContext * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.WindowsAzure.Storage.DataMovement.TransferManager.DownloadAsync (sourceBlob, destStream, options, context, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage.DataMovement</AssemblyName>
        <AssemblyVersion>0.5.3.0</AssemblyVersion>
        <AssemblyVersion>0.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Diagnostics.CodeAnalysis.SuppressMessage("Microsoft.Design", "CA1011:ConsiderPassingBaseTypesAsParameters", Justification="With TransferContext, it also accepts DirectoryTransferContext. Here forbid this behavior.")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="sourceBlob" Type="Microsoft.WindowsAzure.Storage.Blob.CloudBlob" />
        <Parameter Name="destStream" Type="System.IO.Stream" />
        <Parameter Name="options" Type="Microsoft.WindowsAzure.Storage.DataMovement.DownloadOptions" />
        <Parameter Name="context" Type="Microsoft.WindowsAzure.Storage.DataMovement.SingleTransferContext" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="sourceBlob"><span data-ttu-id="75481-355">Die <see cref="T:Microsoft.WindowsAzure.Storage.Blob.CloudBlob" /> , der die Quelle Azure-Blob.</span><span class="sxs-lookup"><span data-stu-id="75481-355">The <see cref="T:Microsoft.WindowsAzure.Storage.Blob.CloudBlob" /> that is the source Azure blob.</span></span></param>
        <param name="destStream"><span data-ttu-id="75481-356">Ein <see cref="T:System.IO.Stream" /> Objekt, das den Zieldatenstrom darstellt.</span><span class="sxs-lookup"><span data-stu-id="75481-356">A <see cref="T:System.IO.Stream" /> object representing the destination stream.</span></span></param>
        <param name="options"><span data-ttu-id="75481-357">Ein <see cref="T:Microsoft.WindowsAzure.Storage.DataMovement.DownloadOptions" /> -Objekt, das zusätzliche Optionen für den Vorgang angibt.</span><span class="sxs-lookup"><span data-stu-id="75481-357">A <see cref="T:Microsoft.WindowsAzure.Storage.DataMovement.DownloadOptions" /> object that specifies additional options for the operation.</span></span></param>
        <param name="context"><span data-ttu-id="75481-358">Ein <see cref="T:Microsoft.WindowsAzure.Storage.DataMovement.SingleTransferContext" /> -Objekt, das den Kontext für den aktuellen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="75481-358">A <see cref="T:Microsoft.WindowsAzure.Storage.DataMovement.SingleTransferContext" /> object that represents the context for the current operation.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="75481-359">Ein <see cref="T:System.Threading.CancellationToken" /> Objekt, das beim Warten auf Abschluss einer Aufgabe überwacht werden.</span><span class="sxs-lookup"><span data-stu-id="75481-359">A <see cref="T:System.Threading.CancellationToken" /> object to observe while waiting for a task to complete.</span></span></param>
        <summary>
            <span data-ttu-id="75481-360">Eine Azure-blob aus dem Azure-Blob-Speicher herunterladen.</span><span class="sxs-lookup"><span data-stu-id="75481-360">Download an Azure blob from Azure Blob Storage.</span></span>
            </summary>
        <returns><span data-ttu-id="75481-361">Ein <see cref="T:System.Threading.Tasks.Task" />-Objekt, das den asynchronen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="75481-361">A <see cref="T:System.Threading.Tasks.Task" /> object that represents the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DownloadAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task DownloadAsync (Microsoft.WindowsAzure.Storage.Blob.CloudBlob sourceBlob, string destPath, Microsoft.WindowsAzure.Storage.DataMovement.DownloadOptions options, Microsoft.WindowsAzure.Storage.DataMovement.SingleTransferContext context, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task DownloadAsync(class Microsoft.WindowsAzure.Storage.Blob.CloudBlob sourceBlob, string destPath, class Microsoft.WindowsAzure.Storage.DataMovement.DownloadOptions options, class Microsoft.WindowsAzure.Storage.DataMovement.SingleTransferContext context, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.DataMovement.TransferManager.DownloadAsync(Microsoft.WindowsAzure.Storage.Blob.CloudBlob,System.String,Microsoft.WindowsAzure.Storage.DataMovement.DownloadOptions,Microsoft.WindowsAzure.Storage.DataMovement.SingleTransferContext,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member DownloadAsync : Microsoft.WindowsAzure.Storage.Blob.CloudBlob * string * Microsoft.WindowsAzure.Storage.DataMovement.DownloadOptions * Microsoft.WindowsAzure.Storage.DataMovement.SingleTransferContext * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.WindowsAzure.Storage.DataMovement.TransferManager.DownloadAsync (sourceBlob, destPath, options, context, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage.DataMovement</AssemblyName>
        <AssemblyVersion>0.5.3.0</AssemblyVersion>
        <AssemblyVersion>0.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Diagnostics.CodeAnalysis.SuppressMessage("Microsoft.Design", "CA1011:ConsiderPassingBaseTypesAsParameters", Justification="With TransferContext, it also accepts DirectoryTransferContext. Here forbid this behavior.")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="sourceBlob" Type="Microsoft.WindowsAzure.Storage.Blob.CloudBlob" />
        <Parameter Name="destPath" Type="System.String" />
        <Parameter Name="options" Type="Microsoft.WindowsAzure.Storage.DataMovement.DownloadOptions" />
        <Parameter Name="context" Type="Microsoft.WindowsAzure.Storage.DataMovement.SingleTransferContext" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="sourceBlob"><span data-ttu-id="75481-362">Die <see cref="T:Microsoft.WindowsAzure.Storage.Blob.CloudBlob" /> , der die Quelle Azure-Blob.</span><span class="sxs-lookup"><span data-stu-id="75481-362">The <see cref="T:Microsoft.WindowsAzure.Storage.Blob.CloudBlob" /> that is the source Azure blob.</span></span></param>
        <param name="destPath"><span data-ttu-id="75481-363">Pfad zur Zieldatei.</span><span class="sxs-lookup"><span data-stu-id="75481-363">Path to the destination file.</span></span></param>
        <param name="options"><span data-ttu-id="75481-364">Ein <see cref="T:Microsoft.WindowsAzure.Storage.DataMovement.DownloadOptions" /> -Objekt, das zusätzliche Optionen für den Vorgang angibt.</span><span class="sxs-lookup"><span data-stu-id="75481-364">A <see cref="T:Microsoft.WindowsAzure.Storage.DataMovement.DownloadOptions" /> object that specifies additional options for the operation.</span></span></param>
        <param name="context"><span data-ttu-id="75481-365">Ein <see cref="T:Microsoft.WindowsAzure.Storage.DataMovement.SingleTransferContext" /> -Objekt, das den Kontext für den aktuellen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="75481-365">A <see cref="T:Microsoft.WindowsAzure.Storage.DataMovement.SingleTransferContext" /> object that represents the context for the current operation.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="75481-366">Ein <see cref="T:System.Threading.CancellationToken" /> Objekt, das beim Warten auf Abschluss einer Aufgabe überwacht werden.</span><span class="sxs-lookup"><span data-stu-id="75481-366">A <see cref="T:System.Threading.CancellationToken" /> object to observe while waiting for a task to complete.</span></span></param>
        <summary>
            <span data-ttu-id="75481-367">Eine Azure-blob aus dem Azure-Blob-Speicher herunterladen.</span><span class="sxs-lookup"><span data-stu-id="75481-367">Download an Azure blob from Azure Blob Storage.</span></span>
            </summary>
        <returns><span data-ttu-id="75481-368">Ein <see cref="T:System.Threading.Tasks.Task" />-Objekt, das den asynchronen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="75481-368">A <see cref="T:System.Threading.Tasks.Task" /> object that represents the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DownloadAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task DownloadAsync (Microsoft.WindowsAzure.Storage.File.CloudFile sourceFile, System.IO.Stream destStream, Microsoft.WindowsAzure.Storage.DataMovement.DownloadOptions options, Microsoft.WindowsAzure.Storage.DataMovement.SingleTransferContext context, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task DownloadAsync(class Microsoft.WindowsAzure.Storage.File.CloudFile sourceFile, class System.IO.Stream destStream, class Microsoft.WindowsAzure.Storage.DataMovement.DownloadOptions options, class Microsoft.WindowsAzure.Storage.DataMovement.SingleTransferContext context, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.DataMovement.TransferManager.DownloadAsync(Microsoft.WindowsAzure.Storage.File.CloudFile,System.IO.Stream,Microsoft.WindowsAzure.Storage.DataMovement.DownloadOptions,Microsoft.WindowsAzure.Storage.DataMovement.SingleTransferContext,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member DownloadAsync : Microsoft.WindowsAzure.Storage.File.CloudFile * System.IO.Stream * Microsoft.WindowsAzure.Storage.DataMovement.DownloadOptions * Microsoft.WindowsAzure.Storage.DataMovement.SingleTransferContext * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.WindowsAzure.Storage.DataMovement.TransferManager.DownloadAsync (sourceFile, destStream, options, context, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage.DataMovement</AssemblyName>
        <AssemblyVersion>0.5.3.0</AssemblyVersion>
        <AssemblyVersion>0.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Diagnostics.CodeAnalysis.SuppressMessage("Microsoft.Design", "CA1011:ConsiderPassingBaseTypesAsParameters", Justification="With TransferContext, it also accepts DirectoryTransferContext. Here forbid this behavior.")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="sourceFile" Type="Microsoft.WindowsAzure.Storage.File.CloudFile" />
        <Parameter Name="destStream" Type="System.IO.Stream" />
        <Parameter Name="options" Type="Microsoft.WindowsAzure.Storage.DataMovement.DownloadOptions" />
        <Parameter Name="context" Type="Microsoft.WindowsAzure.Storage.DataMovement.SingleTransferContext" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="sourceFile"><span data-ttu-id="75481-369">Die <see cref="T:Microsoft.WindowsAzure.Storage.File.CloudFile" /> , der die Quelle Azure-Datei.</span><span class="sxs-lookup"><span data-stu-id="75481-369">The <see cref="T:Microsoft.WindowsAzure.Storage.File.CloudFile" /> that is the source Azure file.</span></span></param>
        <param name="destStream"><span data-ttu-id="75481-370">Ein <see cref="T:System.IO.Stream" /> Objekt, das den Zieldatenstrom darstellt.</span><span class="sxs-lookup"><span data-stu-id="75481-370">A <see cref="T:System.IO.Stream" /> object representing the destination stream.</span></span></param>
        <param name="options"><span data-ttu-id="75481-371">Ein <see cref="T:Microsoft.WindowsAzure.Storage.DataMovement.DownloadOptions" /> -Objekt, das zusätzliche Optionen für den Vorgang angibt.</span><span class="sxs-lookup"><span data-stu-id="75481-371">A <see cref="T:Microsoft.WindowsAzure.Storage.DataMovement.DownloadOptions" /> object that specifies additional options for the operation.</span></span></param>
        <param name="context"><span data-ttu-id="75481-372">Ein <see cref="T:Microsoft.WindowsAzure.Storage.DataMovement.SingleTransferContext" /> -Objekt, das den Kontext für den aktuellen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="75481-372">A <see cref="T:Microsoft.WindowsAzure.Storage.DataMovement.SingleTransferContext" /> object that represents the context for the current operation.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="75481-373">Ein <see cref="T:System.Threading.CancellationToken" /> Objekt, das beim Warten auf Abschluss einer Aufgabe überwacht werden.</span><span class="sxs-lookup"><span data-stu-id="75481-373">A <see cref="T:System.Threading.CancellationToken" /> object to observe while waiting for a task to complete.</span></span></param>
        <summary>
            <span data-ttu-id="75481-374">Laden Sie eine Azure-Datei aus Azure File Storage herunter.</span><span class="sxs-lookup"><span data-stu-id="75481-374">Download an Azure file from Azure File Storage.</span></span>
            </summary>
        <returns><span data-ttu-id="75481-375">Ein <see cref="T:System.Threading.Tasks.Task" />-Objekt, das den asynchronen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="75481-375">A <see cref="T:System.Threading.Tasks.Task" /> object that represents the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DownloadAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task DownloadAsync (Microsoft.WindowsAzure.Storage.File.CloudFile sourceFile, string destPath, Microsoft.WindowsAzure.Storage.DataMovement.DownloadOptions options, Microsoft.WindowsAzure.Storage.DataMovement.SingleTransferContext context, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task DownloadAsync(class Microsoft.WindowsAzure.Storage.File.CloudFile sourceFile, string destPath, class Microsoft.WindowsAzure.Storage.DataMovement.DownloadOptions options, class Microsoft.WindowsAzure.Storage.DataMovement.SingleTransferContext context, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.DataMovement.TransferManager.DownloadAsync(Microsoft.WindowsAzure.Storage.File.CloudFile,System.String,Microsoft.WindowsAzure.Storage.DataMovement.DownloadOptions,Microsoft.WindowsAzure.Storage.DataMovement.SingleTransferContext,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member DownloadAsync : Microsoft.WindowsAzure.Storage.File.CloudFile * string * Microsoft.WindowsAzure.Storage.DataMovement.DownloadOptions * Microsoft.WindowsAzure.Storage.DataMovement.SingleTransferContext * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.WindowsAzure.Storage.DataMovement.TransferManager.DownloadAsync (sourceFile, destPath, options, context, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage.DataMovement</AssemblyName>
        <AssemblyVersion>0.5.3.0</AssemblyVersion>
        <AssemblyVersion>0.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Diagnostics.CodeAnalysis.SuppressMessage("Microsoft.Design", "CA1011:ConsiderPassingBaseTypesAsParameters", Justification="With TransferContext, it also accepts DirectoryTransferContext. Here forbid this behavior.")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="sourceFile" Type="Microsoft.WindowsAzure.Storage.File.CloudFile" />
        <Parameter Name="destPath" Type="System.String" />
        <Parameter Name="options" Type="Microsoft.WindowsAzure.Storage.DataMovement.DownloadOptions" />
        <Parameter Name="context" Type="Microsoft.WindowsAzure.Storage.DataMovement.SingleTransferContext" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="sourceFile"><span data-ttu-id="75481-376">Die <see cref="T:Microsoft.WindowsAzure.Storage.File.CloudFile" /> , der die Quelle Azure-Datei.</span><span class="sxs-lookup"><span data-stu-id="75481-376">The <see cref="T:Microsoft.WindowsAzure.Storage.File.CloudFile" /> that is the source Azure file.</span></span></param>
        <param name="destPath"><span data-ttu-id="75481-377">Pfad zur Zieldatei.</span><span class="sxs-lookup"><span data-stu-id="75481-377">Path to the destination file.</span></span></param>
        <param name="options"><span data-ttu-id="75481-378">Ein <see cref="T:Microsoft.WindowsAzure.Storage.DataMovement.DownloadOptions" /> -Objekt, das zusätzliche Optionen für den Vorgang angibt.</span><span class="sxs-lookup"><span data-stu-id="75481-378">A <see cref="T:Microsoft.WindowsAzure.Storage.DataMovement.DownloadOptions" /> object that specifies additional options for the operation.</span></span></param>
        <param name="context"><span data-ttu-id="75481-379">Ein <see cref="T:Microsoft.WindowsAzure.Storage.DataMovement.SingleTransferContext" /> -Objekt, das den Kontext für den aktuellen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="75481-379">A <see cref="T:Microsoft.WindowsAzure.Storage.DataMovement.SingleTransferContext" /> object that represents the context for the current operation.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="75481-380">Ein <see cref="T:System.Threading.CancellationToken" /> Objekt, das beim Warten auf Abschluss einer Aufgabe überwacht werden.</span><span class="sxs-lookup"><span data-stu-id="75481-380">A <see cref="T:System.Threading.CancellationToken" /> object to observe while waiting for a task to complete.</span></span></param>
        <summary>
            <span data-ttu-id="75481-381">Laden Sie eine Azure-Datei aus Azure File Storage herunter.</span><span class="sxs-lookup"><span data-stu-id="75481-381">Download an Azure file from Azure File Storage.</span></span>
            </summary>
        <returns><span data-ttu-id="75481-382">Ein <see cref="T:System.Threading.Tasks.Task" />-Objekt, das den asynchronen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="75481-382">A <see cref="T:System.Threading.Tasks.Task" /> object that represents the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DownloadDirectoryAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.DataMovement.TransferStatus&gt; DownloadDirectoryAsync (Microsoft.WindowsAzure.Storage.Blob.CloudBlobDirectory sourceBlobDir, string destPath, Microsoft.WindowsAzure.Storage.DataMovement.DownloadDirectoryOptions options, Microsoft.WindowsAzure.Storage.DataMovement.DirectoryTransferContext context);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.WindowsAzure.Storage.DataMovement.TransferStatus&gt; DownloadDirectoryAsync(class Microsoft.WindowsAzure.Storage.Blob.CloudBlobDirectory sourceBlobDir, string destPath, class Microsoft.WindowsAzure.Storage.DataMovement.DownloadDirectoryOptions options, class Microsoft.WindowsAzure.Storage.DataMovement.DirectoryTransferContext context) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.DataMovement.TransferManager.DownloadDirectoryAsync(Microsoft.WindowsAzure.Storage.Blob.CloudBlobDirectory,System.String,Microsoft.WindowsAzure.Storage.DataMovement.DownloadDirectoryOptions,Microsoft.WindowsAzure.Storage.DataMovement.DirectoryTransferContext)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function DownloadDirectoryAsync (sourceBlobDir As CloudBlobDirectory, destPath As String, options As DownloadDirectoryOptions, context As DirectoryTransferContext) As Task(Of TransferStatus)" />
      <MemberSignature Language="F#" Value="static member DownloadDirectoryAsync : Microsoft.WindowsAzure.Storage.Blob.CloudBlobDirectory * string * Microsoft.WindowsAzure.Storage.DataMovement.DownloadDirectoryOptions * Microsoft.WindowsAzure.Storage.DataMovement.DirectoryTransferContext -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.DataMovement.TransferStatus&gt;" Usage="Microsoft.WindowsAzure.Storage.DataMovement.TransferManager.DownloadDirectoryAsync (sourceBlobDir, destPath, options, context)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage.DataMovement</AssemblyName>
        <AssemblyVersion>0.5.3.0</AssemblyVersion>
        <AssemblyVersion>0.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.DataMovement.TransferStatus&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="sourceBlobDir" Type="Microsoft.WindowsAzure.Storage.Blob.CloudBlobDirectory" />
        <Parameter Name="destPath" Type="System.String" />
        <Parameter Name="options" Type="Microsoft.WindowsAzure.Storage.DataMovement.DownloadDirectoryOptions" />
        <Parameter Name="context" Type="Microsoft.WindowsAzure.Storage.DataMovement.DirectoryTransferContext" />
      </Parameters>
      <Docs>
        <param name="sourceBlobDir"><span data-ttu-id="75481-383">Die <see cref="T:Microsoft.WindowsAzure.Storage.Blob.CloudBlobDirectory" /> also das Quellverzeichnis Azure-Blob.</span><span class="sxs-lookup"><span data-stu-id="75481-383">The <see cref="T:Microsoft.WindowsAzure.Storage.Blob.CloudBlobDirectory" /> that is the source Azure blob directory.</span></span></param>
        <param name="destPath"><span data-ttu-id="75481-384">Pfad zum Zielverzeichnis</span><span class="sxs-lookup"><span data-stu-id="75481-384">Path to the destination directory</span></span></param>
        <param name="options"><span data-ttu-id="75481-385">Ein <see cref="T:Microsoft.WindowsAzure.Storage.DataMovement.DownloadDirectoryOptions" /> -Objekt, das zusätzliche Optionen für den Vorgang angibt.</span><span class="sxs-lookup"><span data-stu-id="75481-385">A <see cref="T:Microsoft.WindowsAzure.Storage.DataMovement.DownloadDirectoryOptions" /> object that specifies additional options for the operation.</span></span></param>
        <param name="context"><span data-ttu-id="75481-386">Ein <see cref="T:Microsoft.WindowsAzure.Storage.DataMovement.DirectoryTransferContext" /> -Objekt, das den Kontext für den aktuellen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="75481-386">A <see cref="T:Microsoft.WindowsAzure.Storage.DataMovement.DirectoryTransferContext" /> object that represents the context for the current operation.</span></span></param>
        <summary>
            <span data-ttu-id="75481-387">Laden Sie ein Azure-Blob-Verzeichnis aus dem Azure-Blob-Speicher herunter.</span><span class="sxs-lookup"><span data-stu-id="75481-387">Download an Azure blob directory from Azure Blob Storage.</span></span>
            </summary>
        <returns><span data-ttu-id="75481-388">Ein <see cref="T:System.Threading.Tasks.Task`1" /> Objekt des Typs <see cref="T:Microsoft.WindowsAzure.Storage.DataMovement.TransferStatus" /> , die den asynchronen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="75481-388">A <see cref="T:System.Threading.Tasks.Task`1" /> object of type <see cref="T:Microsoft.WindowsAzure.Storage.DataMovement.TransferStatus" /> that represents the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DownloadDirectoryAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.DataMovement.TransferStatus&gt; DownloadDirectoryAsync (Microsoft.WindowsAzure.Storage.File.CloudFileDirectory sourceFileDir, string destPath, Microsoft.WindowsAzure.Storage.DataMovement.DownloadDirectoryOptions options, Microsoft.WindowsAzure.Storage.DataMovement.DirectoryTransferContext context);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.WindowsAzure.Storage.DataMovement.TransferStatus&gt; DownloadDirectoryAsync(class Microsoft.WindowsAzure.Storage.File.CloudFileDirectory sourceFileDir, string destPath, class Microsoft.WindowsAzure.Storage.DataMovement.DownloadDirectoryOptions options, class Microsoft.WindowsAzure.Storage.DataMovement.DirectoryTransferContext context) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.DataMovement.TransferManager.DownloadDirectoryAsync(Microsoft.WindowsAzure.Storage.File.CloudFileDirectory,System.String,Microsoft.WindowsAzure.Storage.DataMovement.DownloadDirectoryOptions,Microsoft.WindowsAzure.Storage.DataMovement.DirectoryTransferContext)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function DownloadDirectoryAsync (sourceFileDir As CloudFileDirectory, destPath As String, options As DownloadDirectoryOptions, context As DirectoryTransferContext) As Task(Of TransferStatus)" />
      <MemberSignature Language="F#" Value="static member DownloadDirectoryAsync : Microsoft.WindowsAzure.Storage.File.CloudFileDirectory * string * Microsoft.WindowsAzure.Storage.DataMovement.DownloadDirectoryOptions * Microsoft.WindowsAzure.Storage.DataMovement.DirectoryTransferContext -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.DataMovement.TransferStatus&gt;" Usage="Microsoft.WindowsAzure.Storage.DataMovement.TransferManager.DownloadDirectoryAsync (sourceFileDir, destPath, options, context)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage.DataMovement</AssemblyName>
        <AssemblyVersion>0.5.3.0</AssemblyVersion>
        <AssemblyVersion>0.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.DataMovement.TransferStatus&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="sourceFileDir" Type="Microsoft.WindowsAzure.Storage.File.CloudFileDirectory" />
        <Parameter Name="destPath" Type="System.String" />
        <Parameter Name="options" Type="Microsoft.WindowsAzure.Storage.DataMovement.DownloadDirectoryOptions" />
        <Parameter Name="context" Type="Microsoft.WindowsAzure.Storage.DataMovement.DirectoryTransferContext" />
      </Parameters>
      <Docs>
        <param name="sourceFileDir"><span data-ttu-id="75481-389">Die <see cref="T:Microsoft.WindowsAzure.Storage.File.CloudFileDirectory" /> also das Quellverzeichnis Azure-Datei.</span><span class="sxs-lookup"><span data-stu-id="75481-389">The <see cref="T:Microsoft.WindowsAzure.Storage.File.CloudFileDirectory" /> that is the source Azure file directory.</span></span></param>
        <param name="destPath"><span data-ttu-id="75481-390">Pfad zum Zielverzeichnis</span><span class="sxs-lookup"><span data-stu-id="75481-390">Path to the destination directory</span></span></param>
        <param name="options"><span data-ttu-id="75481-391">Ein <see cref="T:Microsoft.WindowsAzure.Storage.DataMovement.DownloadOptions" /> -Objekt, das zusätzliche Optionen für den Vorgang angibt.</span><span class="sxs-lookup"><span data-stu-id="75481-391">A <see cref="T:Microsoft.WindowsAzure.Storage.DataMovement.DownloadOptions" /> object that specifies additional options for the operation.</span></span></param>
        <param name="context"><span data-ttu-id="75481-392">Ein <see cref="T:Microsoft.WindowsAzure.Storage.DataMovement.DirectoryTransferContext" /> -Objekt, das den Kontext für den aktuellen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="75481-392">A <see cref="T:Microsoft.WindowsAzure.Storage.DataMovement.DirectoryTransferContext" /> object that represents the context for the current operation.</span></span></param>
        <summary>
            <span data-ttu-id="75481-393">Ein Azure-Dateiverzeichnis von Azure File Storage herunterladen.</span><span class="sxs-lookup"><span data-stu-id="75481-393">Download an Azure file directory from Azure File Storage.</span></span>
            </summary>
        <returns><span data-ttu-id="75481-394">Ein <see cref="T:System.Threading.Tasks.Task`1" /> Objekt des Typs <see cref="T:Microsoft.WindowsAzure.Storage.DataMovement.TransferStatus" /> , die den asynchronen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="75481-394">A <see cref="T:System.Threading.Tasks.Task`1" /> object of type <see cref="T:Microsoft.WindowsAzure.Storage.DataMovement.TransferStatus" /> that represents the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DownloadDirectoryAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.DataMovement.TransferStatus&gt; DownloadDirectoryAsync (Microsoft.WindowsAzure.Storage.Blob.CloudBlobDirectory sourceBlobDir, string destPath, Microsoft.WindowsAzure.Storage.DataMovement.DownloadDirectoryOptions options, Microsoft.WindowsAzure.Storage.DataMovement.DirectoryTransferContext context, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.WindowsAzure.Storage.DataMovement.TransferStatus&gt; DownloadDirectoryAsync(class Microsoft.WindowsAzure.Storage.Blob.CloudBlobDirectory sourceBlobDir, string destPath, class Microsoft.WindowsAzure.Storage.DataMovement.DownloadDirectoryOptions options, class Microsoft.WindowsAzure.Storage.DataMovement.DirectoryTransferContext context, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.DataMovement.TransferManager.DownloadDirectoryAsync(Microsoft.WindowsAzure.Storage.Blob.CloudBlobDirectory,System.String,Microsoft.WindowsAzure.Storage.DataMovement.DownloadDirectoryOptions,Microsoft.WindowsAzure.Storage.DataMovement.DirectoryTransferContext,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member DownloadDirectoryAsync : Microsoft.WindowsAzure.Storage.Blob.CloudBlobDirectory * string * Microsoft.WindowsAzure.Storage.DataMovement.DownloadDirectoryOptions * Microsoft.WindowsAzure.Storage.DataMovement.DirectoryTransferContext * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.DataMovement.TransferStatus&gt;" Usage="Microsoft.WindowsAzure.Storage.DataMovement.TransferManager.DownloadDirectoryAsync (sourceBlobDir, destPath, options, context, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage.DataMovement</AssemblyName>
        <AssemblyVersion>0.5.3.0</AssemblyVersion>
        <AssemblyVersion>0.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.DataMovement.TransferStatus&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="sourceBlobDir" Type="Microsoft.WindowsAzure.Storage.Blob.CloudBlobDirectory" />
        <Parameter Name="destPath" Type="System.String" />
        <Parameter Name="options" Type="Microsoft.WindowsAzure.Storage.DataMovement.DownloadDirectoryOptions" />
        <Parameter Name="context" Type="Microsoft.WindowsAzure.Storage.DataMovement.DirectoryTransferContext" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="sourceBlobDir"><span data-ttu-id="75481-395">Die <see cref="T:Microsoft.WindowsAzure.Storage.Blob.CloudBlobDirectory" /> also das Quellverzeichnis Azure-Blob.</span><span class="sxs-lookup"><span data-stu-id="75481-395">The <see cref="T:Microsoft.WindowsAzure.Storage.Blob.CloudBlobDirectory" /> that is the source Azure blob directory.</span></span></param>
        <param name="destPath"><span data-ttu-id="75481-396">Pfad zum Zielverzeichnis</span><span class="sxs-lookup"><span data-stu-id="75481-396">Path to the destination directory</span></span></param>
        <param name="options"><span data-ttu-id="75481-397">Ein <see cref="T:Microsoft.WindowsAzure.Storage.DataMovement.DownloadDirectoryOptions" /> -Objekt, das zusätzliche Optionen für den Vorgang angibt.</span><span class="sxs-lookup"><span data-stu-id="75481-397">A <see cref="T:Microsoft.WindowsAzure.Storage.DataMovement.DownloadDirectoryOptions" /> object that specifies additional options for the operation.</span></span></param>
        <param name="context"><span data-ttu-id="75481-398">Ein <see cref="T:Microsoft.WindowsAzure.Storage.DataMovement.DirectoryTransferContext" /> -Objekt, das den Kontext für den aktuellen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="75481-398">A <see cref="T:Microsoft.WindowsAzure.Storage.DataMovement.DirectoryTransferContext" /> object that represents the context for the current operation.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="75481-399">Ein <see cref="T:System.Threading.CancellationToken" /> Objekt, das beim Warten auf Abschluss einer Aufgabe überwacht werden.</span><span class="sxs-lookup"><span data-stu-id="75481-399">A <see cref="T:System.Threading.CancellationToken" /> object to observe while waiting for a task to complete.</span></span></param>
        <summary>
            <span data-ttu-id="75481-400">Laden Sie ein Azure-Blob-Verzeichnis aus dem Azure-Blob-Speicher herunter.</span><span class="sxs-lookup"><span data-stu-id="75481-400">Download an Azure blob directory from Azure Blob Storage.</span></span>
            </summary>
        <returns><span data-ttu-id="75481-401">Ein <see cref="T:System.Threading.Tasks.Task`1" /> Objekt des Typs <see cref="T:Microsoft.WindowsAzure.Storage.DataMovement.TransferStatus" /> , die den asynchronen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="75481-401">A <see cref="T:System.Threading.Tasks.Task`1" /> object of type <see cref="T:Microsoft.WindowsAzure.Storage.DataMovement.TransferStatus" /> that represents the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DownloadDirectoryAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.DataMovement.TransferStatus&gt; DownloadDirectoryAsync (Microsoft.WindowsAzure.Storage.File.CloudFileDirectory sourceFileDir, string destPath, Microsoft.WindowsAzure.Storage.DataMovement.DownloadDirectoryOptions options, Microsoft.WindowsAzure.Storage.DataMovement.DirectoryTransferContext context, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.WindowsAzure.Storage.DataMovement.TransferStatus&gt; DownloadDirectoryAsync(class Microsoft.WindowsAzure.Storage.File.CloudFileDirectory sourceFileDir, string destPath, class Microsoft.WindowsAzure.Storage.DataMovement.DownloadDirectoryOptions options, class Microsoft.WindowsAzure.Storage.DataMovement.DirectoryTransferContext context, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.DataMovement.TransferManager.DownloadDirectoryAsync(Microsoft.WindowsAzure.Storage.File.CloudFileDirectory,System.String,Microsoft.WindowsAzure.Storage.DataMovement.DownloadDirectoryOptions,Microsoft.WindowsAzure.Storage.DataMovement.DirectoryTransferContext,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member DownloadDirectoryAsync : Microsoft.WindowsAzure.Storage.File.CloudFileDirectory * string * Microsoft.WindowsAzure.Storage.DataMovement.DownloadDirectoryOptions * Microsoft.WindowsAzure.Storage.DataMovement.DirectoryTransferContext * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.DataMovement.TransferStatus&gt;" Usage="Microsoft.WindowsAzure.Storage.DataMovement.TransferManager.DownloadDirectoryAsync (sourceFileDir, destPath, options, context, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage.DataMovement</AssemblyName>
        <AssemblyVersion>0.5.3.0</AssemblyVersion>
        <AssemblyVersion>0.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.DataMovement.TransferStatus&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="sourceFileDir" Type="Microsoft.WindowsAzure.Storage.File.CloudFileDirectory" />
        <Parameter Name="destPath" Type="System.String" />
        <Parameter Name="options" Type="Microsoft.WindowsAzure.Storage.DataMovement.DownloadDirectoryOptions" />
        <Parameter Name="context" Type="Microsoft.WindowsAzure.Storage.DataMovement.DirectoryTransferContext" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="sourceFileDir"><span data-ttu-id="75481-402">Die <see cref="T:Microsoft.WindowsAzure.Storage.File.CloudFileDirectory" /> also das Quellverzeichnis Azure-Datei.</span><span class="sxs-lookup"><span data-stu-id="75481-402">The <see cref="T:Microsoft.WindowsAzure.Storage.File.CloudFileDirectory" /> that is the source Azure file directory.</span></span></param>
        <param name="destPath"><span data-ttu-id="75481-403">Pfad zum Zielverzeichnis</span><span class="sxs-lookup"><span data-stu-id="75481-403">Path to the destination directory</span></span></param>
        <param name="options"><span data-ttu-id="75481-404">Ein <see cref="T:Microsoft.WindowsAzure.Storage.DataMovement.DownloadOptions" /> -Objekt, das zusätzliche Optionen für den Vorgang angibt.</span><span class="sxs-lookup"><span data-stu-id="75481-404">A <see cref="T:Microsoft.WindowsAzure.Storage.DataMovement.DownloadOptions" /> object that specifies additional options for the operation.</span></span></param>
        <param name="context"><span data-ttu-id="75481-405">Ein <see cref="T:Microsoft.WindowsAzure.Storage.DataMovement.DirectoryTransferContext" /> -Objekt, das den Kontext für den aktuellen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="75481-405">A <see cref="T:Microsoft.WindowsAzure.Storage.DataMovement.DirectoryTransferContext" /> object that represents the context for the current operation.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="75481-406">Ein <see cref="T:System.Threading.CancellationToken" /> Objekt, das beim Warten auf Abschluss einer Aufgabe überwacht werden.</span><span class="sxs-lookup"><span data-stu-id="75481-406">A <see cref="T:System.Threading.CancellationToken" /> object to observe while waiting for a task to complete.</span></span></param>
        <summary>
            <span data-ttu-id="75481-407">Ein Azure-Dateiverzeichnis von Azure File Storage herunterladen.</span><span class="sxs-lookup"><span data-stu-id="75481-407">Download an Azure file directory from Azure File Storage.</span></span>
            </summary>
        <returns><span data-ttu-id="75481-408">Ein <see cref="T:System.Threading.Tasks.Task`1" /> Objekt des Typs <see cref="T:Microsoft.WindowsAzure.Storage.DataMovement.TransferStatus" /> , die den asynchronen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="75481-408">A <see cref="T:System.Threading.Tasks.Task`1" /> object of type <see cref="T:Microsoft.WindowsAzure.Storage.DataMovement.TransferStatus" /> that represents the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UploadAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task UploadAsync (System.IO.Stream sourceStream, Microsoft.WindowsAzure.Storage.Blob.CloudBlob destBlob);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task UploadAsync(class System.IO.Stream sourceStream, class Microsoft.WindowsAzure.Storage.Blob.CloudBlob destBlob) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.DataMovement.TransferManager.UploadAsync(System.IO.Stream,Microsoft.WindowsAzure.Storage.Blob.CloudBlob)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function UploadAsync (sourceStream As Stream, destBlob As CloudBlob) As Task" />
      <MemberSignature Language="F#" Value="static member UploadAsync : System.IO.Stream * Microsoft.WindowsAzure.Storage.Blob.CloudBlob -&gt; System.Threading.Tasks.Task" Usage="Microsoft.WindowsAzure.Storage.DataMovement.TransferManager.UploadAsync (sourceStream, destBlob)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage.DataMovement</AssemblyName>
        <AssemblyVersion>0.5.3.0</AssemblyVersion>
        <AssemblyVersion>0.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="sourceStream" Type="System.IO.Stream" />
        <Parameter Name="destBlob" Type="Microsoft.WindowsAzure.Storage.Blob.CloudBlob" />
      </Parameters>
      <Docs>
        <param name="sourceStream"><span data-ttu-id="75481-409">Ein <see cref="T:System.IO.Stream" /> Objekt, das den Dateiinhalt bietet.</span><span class="sxs-lookup"><span data-stu-id="75481-409">A <see cref="T:System.IO.Stream" /> object providing the file content.</span></span></param>
        <param name="destBlob"><span data-ttu-id="75481-410">Die <see cref="T:Microsoft.WindowsAzure.Storage.Blob.CloudBlob" /> , die das Ziel Azure-Blob.</span><span class="sxs-lookup"><span data-stu-id="75481-410">The <see cref="T:Microsoft.WindowsAzure.Storage.Blob.CloudBlob" /> that is the destination Azure blob.</span></span></param>
        <summary>
            <span data-ttu-id="75481-411">Hochladen einer Datei in Azure Blob-Speicher.</span><span class="sxs-lookup"><span data-stu-id="75481-411">Upload a file to Azure Blob Storage.</span></span>
            </summary>
        <returns><span data-ttu-id="75481-412">Ein <see cref="T:System.Threading.Tasks.Task" />-Objekt, das den asynchronen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="75481-412">A <see cref="T:System.Threading.Tasks.Task" /> object that represents the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UploadAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task UploadAsync (System.IO.Stream sourceStream, Microsoft.WindowsAzure.Storage.File.CloudFile destFile);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task UploadAsync(class System.IO.Stream sourceStream, class Microsoft.WindowsAzure.Storage.File.CloudFile destFile) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.DataMovement.TransferManager.UploadAsync(System.IO.Stream,Microsoft.WindowsAzure.Storage.File.CloudFile)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function UploadAsync (sourceStream As Stream, destFile As CloudFile) As Task" />
      <MemberSignature Language="F#" Value="static member UploadAsync : System.IO.Stream * Microsoft.WindowsAzure.Storage.File.CloudFile -&gt; System.Threading.Tasks.Task" Usage="Microsoft.WindowsAzure.Storage.DataMovement.TransferManager.UploadAsync (sourceStream, destFile)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage.DataMovement</AssemblyName>
        <AssemblyVersion>0.5.3.0</AssemblyVersion>
        <AssemblyVersion>0.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="sourceStream" Type="System.IO.Stream" />
        <Parameter Name="destFile" Type="Microsoft.WindowsAzure.Storage.File.CloudFile" />
      </Parameters>
      <Docs>
        <param name="sourceStream"><span data-ttu-id="75481-413">Ein <see cref="T:System.IO.Stream" /> Objekt, das den Dateiinhalt bietet.</span><span class="sxs-lookup"><span data-stu-id="75481-413">A <see cref="T:System.IO.Stream" /> object providing the file content.</span></span></param>
        <param name="destFile"><span data-ttu-id="75481-414">Die <see cref="T:Microsoft.WindowsAzure.Storage.File.CloudFile" /> , die das Ziel Azure-Datei.</span><span class="sxs-lookup"><span data-stu-id="75481-414">The <see cref="T:Microsoft.WindowsAzure.Storage.File.CloudFile" /> that is the destination Azure file.</span></span></param>
        <summary>
            <span data-ttu-id="75481-415">Hochladen einer Datei auf Azure-Dateispeicher.</span><span class="sxs-lookup"><span data-stu-id="75481-415">Upload a file to Azure File Storage.</span></span>
            </summary>
        <returns><span data-ttu-id="75481-416">Ein <see cref="T:System.Threading.Tasks.Task" />-Objekt, das den asynchronen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="75481-416">A <see cref="T:System.Threading.Tasks.Task" /> object that represents the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UploadAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task UploadAsync (string sourcePath, Microsoft.WindowsAzure.Storage.Blob.CloudBlob destBlob);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task UploadAsync(string sourcePath, class Microsoft.WindowsAzure.Storage.Blob.CloudBlob destBlob) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.DataMovement.TransferManager.UploadAsync(System.String,Microsoft.WindowsAzure.Storage.Blob.CloudBlob)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function UploadAsync (sourcePath As String, destBlob As CloudBlob) As Task" />
      <MemberSignature Language="F#" Value="static member UploadAsync : string * Microsoft.WindowsAzure.Storage.Blob.CloudBlob -&gt; System.Threading.Tasks.Task" Usage="Microsoft.WindowsAzure.Storage.DataMovement.TransferManager.UploadAsync (sourcePath, destBlob)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage.DataMovement</AssemblyName>
        <AssemblyVersion>0.5.3.0</AssemblyVersion>
        <AssemblyVersion>0.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="sourcePath" Type="System.String" />
        <Parameter Name="destBlob" Type="Microsoft.WindowsAzure.Storage.Blob.CloudBlob" />
      </Parameters>
      <Docs>
        <param name="sourcePath"><span data-ttu-id="75481-417">Der Pfad zur Quelldatei.</span><span class="sxs-lookup"><span data-stu-id="75481-417">Path to the source file.</span></span></param>
        <param name="destBlob"><span data-ttu-id="75481-418">Die <see cref="T:Microsoft.WindowsAzure.Storage.Blob.CloudBlob" /> , die das Ziel Azure-Blob.</span><span class="sxs-lookup"><span data-stu-id="75481-418">The <see cref="T:Microsoft.WindowsAzure.Storage.Blob.CloudBlob" /> that is the destination Azure blob.</span></span></param>
        <summary>
            <span data-ttu-id="75481-419">Hochladen einer Datei in Azure Blob-Speicher.</span><span class="sxs-lookup"><span data-stu-id="75481-419">Upload a file to Azure Blob Storage.</span></span>
            </summary>
        <returns><span data-ttu-id="75481-420">Ein <see cref="T:System.Threading.Tasks.Task" />-Objekt, das den asynchronen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="75481-420">A <see cref="T:System.Threading.Tasks.Task" /> object that represents the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UploadAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task UploadAsync (string sourcePath, Microsoft.WindowsAzure.Storage.File.CloudFile destFile);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task UploadAsync(string sourcePath, class Microsoft.WindowsAzure.Storage.File.CloudFile destFile) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.DataMovement.TransferManager.UploadAsync(System.String,Microsoft.WindowsAzure.Storage.File.CloudFile)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function UploadAsync (sourcePath As String, destFile As CloudFile) As Task" />
      <MemberSignature Language="F#" Value="static member UploadAsync : string * Microsoft.WindowsAzure.Storage.File.CloudFile -&gt; System.Threading.Tasks.Task" Usage="Microsoft.WindowsAzure.Storage.DataMovement.TransferManager.UploadAsync (sourcePath, destFile)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage.DataMovement</AssemblyName>
        <AssemblyVersion>0.5.3.0</AssemblyVersion>
        <AssemblyVersion>0.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="sourcePath" Type="System.String" />
        <Parameter Name="destFile" Type="Microsoft.WindowsAzure.Storage.File.CloudFile" />
      </Parameters>
      <Docs>
        <param name="sourcePath"><span data-ttu-id="75481-421">Der Pfad zur Quelldatei.</span><span class="sxs-lookup"><span data-stu-id="75481-421">Path to the source file.</span></span></param>
        <param name="destFile"><span data-ttu-id="75481-422">Die <see cref="T:Microsoft.WindowsAzure.Storage.File.CloudFile" /> , die das Ziel Azure-Datei.</span><span class="sxs-lookup"><span data-stu-id="75481-422">The <see cref="T:Microsoft.WindowsAzure.Storage.File.CloudFile" /> that is the destination Azure file.</span></span></param>
        <summary>
            <span data-ttu-id="75481-423">Hochladen einer Datei auf Azure-Dateispeicher.</span><span class="sxs-lookup"><span data-stu-id="75481-423">Upload a file to Azure File Storage.</span></span>
            </summary>
        <returns><span data-ttu-id="75481-424">Ein <see cref="T:System.Threading.Tasks.Task" />-Objekt, das den asynchronen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="75481-424">A <see cref="T:System.Threading.Tasks.Task" /> object that represents the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UploadAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task UploadAsync (System.IO.Stream sourceStream, Microsoft.WindowsAzure.Storage.Blob.CloudBlob destBlob, Microsoft.WindowsAzure.Storage.DataMovement.UploadOptions options, Microsoft.WindowsAzure.Storage.DataMovement.SingleTransferContext context);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task UploadAsync(class System.IO.Stream sourceStream, class Microsoft.WindowsAzure.Storage.Blob.CloudBlob destBlob, class Microsoft.WindowsAzure.Storage.DataMovement.UploadOptions options, class Microsoft.WindowsAzure.Storage.DataMovement.SingleTransferContext context) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.DataMovement.TransferManager.UploadAsync(System.IO.Stream,Microsoft.WindowsAzure.Storage.Blob.CloudBlob,Microsoft.WindowsAzure.Storage.DataMovement.UploadOptions,Microsoft.WindowsAzure.Storage.DataMovement.SingleTransferContext)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function UploadAsync (sourceStream As Stream, destBlob As CloudBlob, options As UploadOptions, context As SingleTransferContext) As Task" />
      <MemberSignature Language="F#" Value="static member UploadAsync : System.IO.Stream * Microsoft.WindowsAzure.Storage.Blob.CloudBlob * Microsoft.WindowsAzure.Storage.DataMovement.UploadOptions * Microsoft.WindowsAzure.Storage.DataMovement.SingleTransferContext -&gt; System.Threading.Tasks.Task" Usage="Microsoft.WindowsAzure.Storage.DataMovement.TransferManager.UploadAsync (sourceStream, destBlob, options, context)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage.DataMovement</AssemblyName>
        <AssemblyVersion>0.5.3.0</AssemblyVersion>
        <AssemblyVersion>0.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="sourceStream" Type="System.IO.Stream" />
        <Parameter Name="destBlob" Type="Microsoft.WindowsAzure.Storage.Blob.CloudBlob" />
        <Parameter Name="options" Type="Microsoft.WindowsAzure.Storage.DataMovement.UploadOptions" />
        <Parameter Name="context" Type="Microsoft.WindowsAzure.Storage.DataMovement.SingleTransferContext" />
      </Parameters>
      <Docs>
        <param name="sourceStream"><span data-ttu-id="75481-425">Ein <see cref="T:System.IO.Stream" /> Objekt, das den Dateiinhalt bietet.</span><span class="sxs-lookup"><span data-stu-id="75481-425">A <see cref="T:System.IO.Stream" /> object providing the file content.</span></span></param>
        <param name="destBlob"><span data-ttu-id="75481-426">Die <see cref="T:Microsoft.WindowsAzure.Storage.Blob.CloudBlob" /> , die das Ziel Azure-Blob.</span><span class="sxs-lookup"><span data-stu-id="75481-426">The <see cref="T:Microsoft.WindowsAzure.Storage.Blob.CloudBlob" /> that is the destination Azure blob.</span></span></param>
        <param name="options"><span data-ttu-id="75481-427">Ein <see cref="T:Microsoft.WindowsAzure.Storage.DataMovement.UploadOptions" /> -Objekt, das zusätzliche Optionen für den Vorgang angibt.</span><span class="sxs-lookup"><span data-stu-id="75481-427">An <see cref="T:Microsoft.WindowsAzure.Storage.DataMovement.UploadOptions" /> object that specifies additional options for the operation.</span></span></param>
        <param name="context"><span data-ttu-id="75481-428">Ein <see cref="T:Microsoft.WindowsAzure.Storage.DataMovement.SingleTransferContext" /> -Objekt, das den Kontext für den aktuellen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="75481-428">A <see cref="T:Microsoft.WindowsAzure.Storage.DataMovement.SingleTransferContext" /> object that represents the context for the current operation.</span></span></param>
        <summary>
            <span data-ttu-id="75481-429">Hochladen einer Datei in Azure Blob-Speicher.</span><span class="sxs-lookup"><span data-stu-id="75481-429">Upload a file to Azure Blob Storage.</span></span>
            </summary>
        <returns><span data-ttu-id="75481-430">Ein <see cref="T:System.Threading.Tasks.Task" />-Objekt, das den asynchronen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="75481-430">A <see cref="T:System.Threading.Tasks.Task" /> object that represents the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UploadAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task UploadAsync (System.IO.Stream sourceStream, Microsoft.WindowsAzure.Storage.File.CloudFile destFile, Microsoft.WindowsAzure.Storage.DataMovement.UploadOptions options, Microsoft.WindowsAzure.Storage.DataMovement.SingleTransferContext context);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task UploadAsync(class System.IO.Stream sourceStream, class Microsoft.WindowsAzure.Storage.File.CloudFile destFile, class Microsoft.WindowsAzure.Storage.DataMovement.UploadOptions options, class Microsoft.WindowsAzure.Storage.DataMovement.SingleTransferContext context) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.DataMovement.TransferManager.UploadAsync(System.IO.Stream,Microsoft.WindowsAzure.Storage.File.CloudFile,Microsoft.WindowsAzure.Storage.DataMovement.UploadOptions,Microsoft.WindowsAzure.Storage.DataMovement.SingleTransferContext)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function UploadAsync (sourceStream As Stream, destFile As CloudFile, options As UploadOptions, context As SingleTransferContext) As Task" />
      <MemberSignature Language="F#" Value="static member UploadAsync : System.IO.Stream * Microsoft.WindowsAzure.Storage.File.CloudFile * Microsoft.WindowsAzure.Storage.DataMovement.UploadOptions * Microsoft.WindowsAzure.Storage.DataMovement.SingleTransferContext -&gt; System.Threading.Tasks.Task" Usage="Microsoft.WindowsAzure.Storage.DataMovement.TransferManager.UploadAsync (sourceStream, destFile, options, context)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage.DataMovement</AssemblyName>
        <AssemblyVersion>0.5.3.0</AssemblyVersion>
        <AssemblyVersion>0.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="sourceStream" Type="System.IO.Stream" />
        <Parameter Name="destFile" Type="Microsoft.WindowsAzure.Storage.File.CloudFile" />
        <Parameter Name="options" Type="Microsoft.WindowsAzure.Storage.DataMovement.UploadOptions" />
        <Parameter Name="context" Type="Microsoft.WindowsAzure.Storage.DataMovement.SingleTransferContext" />
      </Parameters>
      <Docs>
        <param name="sourceStream"><span data-ttu-id="75481-431">Ein <see cref="T:System.IO.Stream" /> Objekt, das den Dateiinhalt bietet.</span><span class="sxs-lookup"><span data-stu-id="75481-431">A <see cref="T:System.IO.Stream" /> object providing the file content.</span></span></param>
        <param name="destFile"><span data-ttu-id="75481-432">Die <see cref="T:Microsoft.WindowsAzure.Storage.File.CloudFile" /> , die das Ziel Azure-Datei.</span><span class="sxs-lookup"><span data-stu-id="75481-432">The <see cref="T:Microsoft.WindowsAzure.Storage.File.CloudFile" /> that is the destination Azure file.</span></span></param>
        <param name="options"><span data-ttu-id="75481-433">Ein <see cref="T:Microsoft.WindowsAzure.Storage.DataMovement.UploadOptions" /> -Objekt, das zusätzliche Optionen für den Vorgang angibt.</span><span class="sxs-lookup"><span data-stu-id="75481-433">An <see cref="T:Microsoft.WindowsAzure.Storage.DataMovement.UploadOptions" /> object that specifies additional options for the operation.</span></span></param>
        <param name="context"><span data-ttu-id="75481-434">Ein <see cref="T:Microsoft.WindowsAzure.Storage.DataMovement.SingleTransferContext" /> -Objekt, das den Kontext für den aktuellen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="75481-434">A <see cref="T:Microsoft.WindowsAzure.Storage.DataMovement.SingleTransferContext" /> object that represents the context for the current operation.</span></span></param>
        <summary>
            <span data-ttu-id="75481-435">Hochladen einer Datei auf Azure-Dateispeicher.</span><span class="sxs-lookup"><span data-stu-id="75481-435">Upload a file to Azure File Storage.</span></span>
            </summary>
        <returns><span data-ttu-id="75481-436">Ein <see cref="T:System.Threading.Tasks.Task" />-Objekt, das den asynchronen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="75481-436">A <see cref="T:System.Threading.Tasks.Task" /> object that represents the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UploadAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task UploadAsync (string sourcePath, Microsoft.WindowsAzure.Storage.Blob.CloudBlob destBlob, Microsoft.WindowsAzure.Storage.DataMovement.UploadOptions options, Microsoft.WindowsAzure.Storage.DataMovement.SingleTransferContext context);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task UploadAsync(string sourcePath, class Microsoft.WindowsAzure.Storage.Blob.CloudBlob destBlob, class Microsoft.WindowsAzure.Storage.DataMovement.UploadOptions options, class Microsoft.WindowsAzure.Storage.DataMovement.SingleTransferContext context) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.DataMovement.TransferManager.UploadAsync(System.String,Microsoft.WindowsAzure.Storage.Blob.CloudBlob,Microsoft.WindowsAzure.Storage.DataMovement.UploadOptions,Microsoft.WindowsAzure.Storage.DataMovement.SingleTransferContext)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function UploadAsync (sourcePath As String, destBlob As CloudBlob, options As UploadOptions, context As SingleTransferContext) As Task" />
      <MemberSignature Language="F#" Value="static member UploadAsync : string * Microsoft.WindowsAzure.Storage.Blob.CloudBlob * Microsoft.WindowsAzure.Storage.DataMovement.UploadOptions * Microsoft.WindowsAzure.Storage.DataMovement.SingleTransferContext -&gt; System.Threading.Tasks.Task" Usage="Microsoft.WindowsAzure.Storage.DataMovement.TransferManager.UploadAsync (sourcePath, destBlob, options, context)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage.DataMovement</AssemblyName>
        <AssemblyVersion>0.5.3.0</AssemblyVersion>
        <AssemblyVersion>0.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="sourcePath" Type="System.String" />
        <Parameter Name="destBlob" Type="Microsoft.WindowsAzure.Storage.Blob.CloudBlob" />
        <Parameter Name="options" Type="Microsoft.WindowsAzure.Storage.DataMovement.UploadOptions" />
        <Parameter Name="context" Type="Microsoft.WindowsAzure.Storage.DataMovement.SingleTransferContext" />
      </Parameters>
      <Docs>
        <param name="sourcePath"><span data-ttu-id="75481-437">Der Pfad zur Quelldatei.</span><span class="sxs-lookup"><span data-stu-id="75481-437">Path to the source file.</span></span></param>
        <param name="destBlob"><span data-ttu-id="75481-438">Die <see cref="T:Microsoft.WindowsAzure.Storage.Blob.CloudBlob" /> , die das Ziel Azure-Blob.</span><span class="sxs-lookup"><span data-stu-id="75481-438">The <see cref="T:Microsoft.WindowsAzure.Storage.Blob.CloudBlob" /> that is the destination Azure blob.</span></span></param>
        <param name="options"><span data-ttu-id="75481-439">Ein <see cref="T:Microsoft.WindowsAzure.Storage.DataMovement.UploadOptions" /> -Objekt, das zusätzliche Optionen für den Vorgang angibt.</span><span class="sxs-lookup"><span data-stu-id="75481-439">An <see cref="T:Microsoft.WindowsAzure.Storage.DataMovement.UploadOptions" /> object that specifies additional options for the operation.</span></span></param>
        <param name="context"><span data-ttu-id="75481-440">Ein <see cref="T:Microsoft.WindowsAzure.Storage.DataMovement.SingleTransferContext" /> -Objekt, das den Kontext für den aktuellen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="75481-440">A <see cref="T:Microsoft.WindowsAzure.Storage.DataMovement.SingleTransferContext" /> object that represents the context for the current operation.</span></span></param>
        <summary>
            <span data-ttu-id="75481-441">Hochladen einer Datei in Azure Blob-Speicher.</span><span class="sxs-lookup"><span data-stu-id="75481-441">Upload a file to Azure Blob Storage.</span></span>
            </summary>
        <returns><span data-ttu-id="75481-442">Ein <see cref="T:System.Threading.Tasks.Task" />-Objekt, das den asynchronen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="75481-442">A <see cref="T:System.Threading.Tasks.Task" /> object that represents the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UploadAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task UploadAsync (string sourcePath, Microsoft.WindowsAzure.Storage.File.CloudFile destFile, Microsoft.WindowsAzure.Storage.DataMovement.UploadOptions options, Microsoft.WindowsAzure.Storage.DataMovement.SingleTransferContext context);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task UploadAsync(string sourcePath, class Microsoft.WindowsAzure.Storage.File.CloudFile destFile, class Microsoft.WindowsAzure.Storage.DataMovement.UploadOptions options, class Microsoft.WindowsAzure.Storage.DataMovement.SingleTransferContext context) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.DataMovement.TransferManager.UploadAsync(System.String,Microsoft.WindowsAzure.Storage.File.CloudFile,Microsoft.WindowsAzure.Storage.DataMovement.UploadOptions,Microsoft.WindowsAzure.Storage.DataMovement.SingleTransferContext)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function UploadAsync (sourcePath As String, destFile As CloudFile, options As UploadOptions, context As SingleTransferContext) As Task" />
      <MemberSignature Language="F#" Value="static member UploadAsync : string * Microsoft.WindowsAzure.Storage.File.CloudFile * Microsoft.WindowsAzure.Storage.DataMovement.UploadOptions * Microsoft.WindowsAzure.Storage.DataMovement.SingleTransferContext -&gt; System.Threading.Tasks.Task" Usage="Microsoft.WindowsAzure.Storage.DataMovement.TransferManager.UploadAsync (sourcePath, destFile, options, context)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage.DataMovement</AssemblyName>
        <AssemblyVersion>0.5.3.0</AssemblyVersion>
        <AssemblyVersion>0.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="sourcePath" Type="System.String" />
        <Parameter Name="destFile" Type="Microsoft.WindowsAzure.Storage.File.CloudFile" />
        <Parameter Name="options" Type="Microsoft.WindowsAzure.Storage.DataMovement.UploadOptions" />
        <Parameter Name="context" Type="Microsoft.WindowsAzure.Storage.DataMovement.SingleTransferContext" />
      </Parameters>
      <Docs>
        <param name="sourcePath"><span data-ttu-id="75481-443">Der Pfad zur Quelldatei.</span><span class="sxs-lookup"><span data-stu-id="75481-443">Path to the source file.</span></span></param>
        <param name="destFile"><span data-ttu-id="75481-444">Die <see cref="T:Microsoft.WindowsAzure.Storage.File.CloudFile" /> , die das Ziel Azure-Datei.</span><span class="sxs-lookup"><span data-stu-id="75481-444">The <see cref="T:Microsoft.WindowsAzure.Storage.File.CloudFile" /> that is the destination Azure file.</span></span></param>
        <param name="options"><span data-ttu-id="75481-445">Ein <see cref="T:Microsoft.WindowsAzure.Storage.DataMovement.UploadOptions" /> -Objekt, das zusätzliche Optionen für den Vorgang angibt.</span><span class="sxs-lookup"><span data-stu-id="75481-445">An <see cref="T:Microsoft.WindowsAzure.Storage.DataMovement.UploadOptions" /> object that specifies additional options for the operation.</span></span></param>
        <param name="context"><span data-ttu-id="75481-446">Ein <see cref="T:Microsoft.WindowsAzure.Storage.DataMovement.SingleTransferContext" /> -Objekt, das den Kontext für den aktuellen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="75481-446">A <see cref="T:Microsoft.WindowsAzure.Storage.DataMovement.SingleTransferContext" /> object that represents the context for the current operation.</span></span></param>
        <summary>
            <span data-ttu-id="75481-447">Hochladen einer Datei auf Azure-Dateispeicher.</span><span class="sxs-lookup"><span data-stu-id="75481-447">Upload a file to Azure File Storage.</span></span>
            </summary>
        <returns><span data-ttu-id="75481-448">Ein <see cref="T:System.Threading.Tasks.Task" />-Objekt, das den asynchronen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="75481-448">A <see cref="T:System.Threading.Tasks.Task" /> object that represents the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UploadAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task UploadAsync (System.IO.Stream sourceStream, Microsoft.WindowsAzure.Storage.Blob.CloudBlob destBlob, Microsoft.WindowsAzure.Storage.DataMovement.UploadOptions options, Microsoft.WindowsAzure.Storage.DataMovement.SingleTransferContext context, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task UploadAsync(class System.IO.Stream sourceStream, class Microsoft.WindowsAzure.Storage.Blob.CloudBlob destBlob, class Microsoft.WindowsAzure.Storage.DataMovement.UploadOptions options, class Microsoft.WindowsAzure.Storage.DataMovement.SingleTransferContext context, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.DataMovement.TransferManager.UploadAsync(System.IO.Stream,Microsoft.WindowsAzure.Storage.Blob.CloudBlob,Microsoft.WindowsAzure.Storage.DataMovement.UploadOptions,Microsoft.WindowsAzure.Storage.DataMovement.SingleTransferContext,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member UploadAsync : System.IO.Stream * Microsoft.WindowsAzure.Storage.Blob.CloudBlob * Microsoft.WindowsAzure.Storage.DataMovement.UploadOptions * Microsoft.WindowsAzure.Storage.DataMovement.SingleTransferContext * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.WindowsAzure.Storage.DataMovement.TransferManager.UploadAsync (sourceStream, destBlob, options, context, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage.DataMovement</AssemblyName>
        <AssemblyVersion>0.5.3.0</AssemblyVersion>
        <AssemblyVersion>0.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Diagnostics.CodeAnalysis.SuppressMessage("Microsoft.Design", "CA1011:ConsiderPassingBaseTypesAsParameters", Justification="With TransferContext, it also accepts DirectoryTransferContext. Here forbid this behavior.")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="sourceStream" Type="System.IO.Stream" />
        <Parameter Name="destBlob" Type="Microsoft.WindowsAzure.Storage.Blob.CloudBlob" />
        <Parameter Name="options" Type="Microsoft.WindowsAzure.Storage.DataMovement.UploadOptions" />
        <Parameter Name="context" Type="Microsoft.WindowsAzure.Storage.DataMovement.SingleTransferContext" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="sourceStream"><span data-ttu-id="75481-449">Ein <see cref="T:System.IO.Stream" /> Objekt, das den Dateiinhalt bietet.</span><span class="sxs-lookup"><span data-stu-id="75481-449">A <see cref="T:System.IO.Stream" /> object providing the file content.</span></span></param>
        <param name="destBlob"><span data-ttu-id="75481-450">Die <see cref="T:Microsoft.WindowsAzure.Storage.Blob.CloudBlob" /> , die das Ziel Azure-Blob.</span><span class="sxs-lookup"><span data-stu-id="75481-450">The <see cref="T:Microsoft.WindowsAzure.Storage.Blob.CloudBlob" /> that is the destination Azure blob.</span></span></param>
        <param name="options"><span data-ttu-id="75481-451">Ein <see cref="T:Microsoft.WindowsAzure.Storage.DataMovement.UploadOptions" /> -Objekt, das zusätzliche Optionen für den Vorgang angibt.</span><span class="sxs-lookup"><span data-stu-id="75481-451">An <see cref="T:Microsoft.WindowsAzure.Storage.DataMovement.UploadOptions" /> object that specifies additional options for the operation.</span></span></param>
        <param name="context"><span data-ttu-id="75481-452">Ein <see cref="T:Microsoft.WindowsAzure.Storage.DataMovement.SingleTransferContext" /> -Objekt, das den Kontext für den aktuellen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="75481-452">A <see cref="T:Microsoft.WindowsAzure.Storage.DataMovement.SingleTransferContext" /> object that represents the context for the current operation.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="75481-453">Ein <see cref="T:System.Threading.CancellationToken" /> Objekt, das beim Warten auf Abschluss einer Aufgabe überwacht werden.</span><span class="sxs-lookup"><span data-stu-id="75481-453">A <see cref="T:System.Threading.CancellationToken" /> object to observe while waiting for a task to complete.</span></span></param>
        <summary>
            <span data-ttu-id="75481-454">Hochladen einer Datei in Azure Blob-Speicher.</span><span class="sxs-lookup"><span data-stu-id="75481-454">Upload a file to Azure Blob Storage.</span></span>
            </summary>
        <returns><span data-ttu-id="75481-455">Ein <see cref="T:System.Threading.Tasks.Task" />-Objekt, das den asynchronen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="75481-455">A <see cref="T:System.Threading.Tasks.Task" /> object that represents the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UploadAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task UploadAsync (System.IO.Stream sourceStream, Microsoft.WindowsAzure.Storage.File.CloudFile destFile, Microsoft.WindowsAzure.Storage.DataMovement.UploadOptions options, Microsoft.WindowsAzure.Storage.DataMovement.SingleTransferContext context, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task UploadAsync(class System.IO.Stream sourceStream, class Microsoft.WindowsAzure.Storage.File.CloudFile destFile, class Microsoft.WindowsAzure.Storage.DataMovement.UploadOptions options, class Microsoft.WindowsAzure.Storage.DataMovement.SingleTransferContext context, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.DataMovement.TransferManager.UploadAsync(System.IO.Stream,Microsoft.WindowsAzure.Storage.File.CloudFile,Microsoft.WindowsAzure.Storage.DataMovement.UploadOptions,Microsoft.WindowsAzure.Storage.DataMovement.SingleTransferContext,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member UploadAsync : System.IO.Stream * Microsoft.WindowsAzure.Storage.File.CloudFile * Microsoft.WindowsAzure.Storage.DataMovement.UploadOptions * Microsoft.WindowsAzure.Storage.DataMovement.SingleTransferContext * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.WindowsAzure.Storage.DataMovement.TransferManager.UploadAsync (sourceStream, destFile, options, context, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage.DataMovement</AssemblyName>
        <AssemblyVersion>0.5.3.0</AssemblyVersion>
        <AssemblyVersion>0.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Diagnostics.CodeAnalysis.SuppressMessage("Microsoft.Design", "CA1011:ConsiderPassingBaseTypesAsParameters", Justification="With TransferContext, it also accepts DirectoryTransferContext. Here forbid this behavior.")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="sourceStream" Type="System.IO.Stream" />
        <Parameter Name="destFile" Type="Microsoft.WindowsAzure.Storage.File.CloudFile" />
        <Parameter Name="options" Type="Microsoft.WindowsAzure.Storage.DataMovement.UploadOptions" />
        <Parameter Name="context" Type="Microsoft.WindowsAzure.Storage.DataMovement.SingleTransferContext" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="sourceStream"><span data-ttu-id="75481-456">Ein <see cref="T:System.IO.Stream" /> Objekt, das den Dateiinhalt bietet.</span><span class="sxs-lookup"><span data-stu-id="75481-456">A <see cref="T:System.IO.Stream" /> object providing the file content.</span></span></param>
        <param name="destFile"><span data-ttu-id="75481-457">Die <see cref="T:Microsoft.WindowsAzure.Storage.File.CloudFile" /> , die das Ziel Azure-Datei.</span><span class="sxs-lookup"><span data-stu-id="75481-457">The <see cref="T:Microsoft.WindowsAzure.Storage.File.CloudFile" /> that is the destination Azure file.</span></span></param>
        <param name="options"><span data-ttu-id="75481-458">Ein <see cref="T:Microsoft.WindowsAzure.Storage.DataMovement.UploadOptions" /> -Objekt, das zusätzliche Optionen für den Vorgang angibt.</span><span class="sxs-lookup"><span data-stu-id="75481-458">An <see cref="T:Microsoft.WindowsAzure.Storage.DataMovement.UploadOptions" /> object that specifies additional options for the operation.</span></span></param>
        <param name="context"><span data-ttu-id="75481-459">Ein <see cref="T:Microsoft.WindowsAzure.Storage.DataMovement.SingleTransferContext" /> -Objekt, das den Kontext für den aktuellen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="75481-459">A <see cref="T:Microsoft.WindowsAzure.Storage.DataMovement.SingleTransferContext" /> object that represents the context for the current operation.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="75481-460">Ein <see cref="T:System.Threading.CancellationToken" /> Objekt, das beim Warten auf Abschluss einer Aufgabe überwacht werden.</span><span class="sxs-lookup"><span data-stu-id="75481-460">A <see cref="T:System.Threading.CancellationToken" /> object to observe while waiting for a task to complete.</span></span></param>
        <summary>
            <span data-ttu-id="75481-461">Hochladen einer Datei auf Azure-Dateispeicher.</span><span class="sxs-lookup"><span data-stu-id="75481-461">Upload a file to Azure File Storage.</span></span>
            </summary>
        <returns><span data-ttu-id="75481-462">Ein <see cref="T:System.Threading.Tasks.Task" />-Objekt, das den asynchronen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="75481-462">A <see cref="T:System.Threading.Tasks.Task" /> object that represents the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UploadAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task UploadAsync (string sourcePath, Microsoft.WindowsAzure.Storage.Blob.CloudBlob destBlob, Microsoft.WindowsAzure.Storage.DataMovement.UploadOptions options, Microsoft.WindowsAzure.Storage.DataMovement.SingleTransferContext context, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task UploadAsync(string sourcePath, class Microsoft.WindowsAzure.Storage.Blob.CloudBlob destBlob, class Microsoft.WindowsAzure.Storage.DataMovement.UploadOptions options, class Microsoft.WindowsAzure.Storage.DataMovement.SingleTransferContext context, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.DataMovement.TransferManager.UploadAsync(System.String,Microsoft.WindowsAzure.Storage.Blob.CloudBlob,Microsoft.WindowsAzure.Storage.DataMovement.UploadOptions,Microsoft.WindowsAzure.Storage.DataMovement.SingleTransferContext,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member UploadAsync : string * Microsoft.WindowsAzure.Storage.Blob.CloudBlob * Microsoft.WindowsAzure.Storage.DataMovement.UploadOptions * Microsoft.WindowsAzure.Storage.DataMovement.SingleTransferContext * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.WindowsAzure.Storage.DataMovement.TransferManager.UploadAsync (sourcePath, destBlob, options, context, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage.DataMovement</AssemblyName>
        <AssemblyVersion>0.5.3.0</AssemblyVersion>
        <AssemblyVersion>0.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Diagnostics.CodeAnalysis.SuppressMessage("Microsoft.Design", "CA1011:ConsiderPassingBaseTypesAsParameters", Justification="With TransferContext, it also accepts DirectoryTransferContext. Here forbid this behavior.")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="sourcePath" Type="System.String" />
        <Parameter Name="destBlob" Type="Microsoft.WindowsAzure.Storage.Blob.CloudBlob" />
        <Parameter Name="options" Type="Microsoft.WindowsAzure.Storage.DataMovement.UploadOptions" />
        <Parameter Name="context" Type="Microsoft.WindowsAzure.Storage.DataMovement.SingleTransferContext" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="sourcePath"><span data-ttu-id="75481-463">Der Pfad zur Quelldatei.</span><span class="sxs-lookup"><span data-stu-id="75481-463">Path to the source file.</span></span></param>
        <param name="destBlob"><span data-ttu-id="75481-464">Die <see cref="T:Microsoft.WindowsAzure.Storage.Blob.CloudBlob" /> , die das Ziel Azure-Blob.</span><span class="sxs-lookup"><span data-stu-id="75481-464">The <see cref="T:Microsoft.WindowsAzure.Storage.Blob.CloudBlob" /> that is the destination Azure blob.</span></span></param>
        <param name="options"><span data-ttu-id="75481-465">Ein <see cref="T:Microsoft.WindowsAzure.Storage.DataMovement.UploadOptions" /> -Objekt, das zusätzliche Optionen für den Vorgang angibt.</span><span class="sxs-lookup"><span data-stu-id="75481-465">An <see cref="T:Microsoft.WindowsAzure.Storage.DataMovement.UploadOptions" /> object that specifies additional options for the operation.</span></span></param>
        <param name="context"><span data-ttu-id="75481-466">Ein <see cref="T:Microsoft.WindowsAzure.Storage.DataMovement.SingleTransferContext" /> -Objekt, das den Kontext für den aktuellen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="75481-466">A <see cref="T:Microsoft.WindowsAzure.Storage.DataMovement.SingleTransferContext" /> object that represents the context for the current operation.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="75481-467">Ein <see cref="T:System.Threading.CancellationToken" /> Objekt, das beim Warten auf Abschluss einer Aufgabe überwacht werden.</span><span class="sxs-lookup"><span data-stu-id="75481-467">A <see cref="T:System.Threading.CancellationToken" /> object to observe while waiting for a task to complete.</span></span></param>
        <summary>
            <span data-ttu-id="75481-468">Hochladen einer Datei in Azure Blob-Speicher.</span><span class="sxs-lookup"><span data-stu-id="75481-468">Upload a file to Azure Blob Storage.</span></span>
            </summary>
        <returns><span data-ttu-id="75481-469">Ein <see cref="T:System.Threading.Tasks.Task" />-Objekt, das den asynchronen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="75481-469">A <see cref="T:System.Threading.Tasks.Task" /> object that represents the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UploadAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task UploadAsync (string sourcePath, Microsoft.WindowsAzure.Storage.File.CloudFile destFile, Microsoft.WindowsAzure.Storage.DataMovement.UploadOptions options, Microsoft.WindowsAzure.Storage.DataMovement.SingleTransferContext context, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task UploadAsync(string sourcePath, class Microsoft.WindowsAzure.Storage.File.CloudFile destFile, class Microsoft.WindowsAzure.Storage.DataMovement.UploadOptions options, class Microsoft.WindowsAzure.Storage.DataMovement.SingleTransferContext context, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.DataMovement.TransferManager.UploadAsync(System.String,Microsoft.WindowsAzure.Storage.File.CloudFile,Microsoft.WindowsAzure.Storage.DataMovement.UploadOptions,Microsoft.WindowsAzure.Storage.DataMovement.SingleTransferContext,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member UploadAsync : string * Microsoft.WindowsAzure.Storage.File.CloudFile * Microsoft.WindowsAzure.Storage.DataMovement.UploadOptions * Microsoft.WindowsAzure.Storage.DataMovement.SingleTransferContext * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.WindowsAzure.Storage.DataMovement.TransferManager.UploadAsync (sourcePath, destFile, options, context, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage.DataMovement</AssemblyName>
        <AssemblyVersion>0.5.3.0</AssemblyVersion>
        <AssemblyVersion>0.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Diagnostics.CodeAnalysis.SuppressMessage("Microsoft.Design", "CA1011:ConsiderPassingBaseTypesAsParameters", Justification="With TransferContext, it also accepts DirectoryTransferContext. Here forbid this behavior.")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="sourcePath" Type="System.String" />
        <Parameter Name="destFile" Type="Microsoft.WindowsAzure.Storage.File.CloudFile" />
        <Parameter Name="options" Type="Microsoft.WindowsAzure.Storage.DataMovement.UploadOptions" />
        <Parameter Name="context" Type="Microsoft.WindowsAzure.Storage.DataMovement.SingleTransferContext" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="sourcePath"><span data-ttu-id="75481-470">Der Pfad zur Quelldatei.</span><span class="sxs-lookup"><span data-stu-id="75481-470">Path to the source file.</span></span></param>
        <param name="destFile"><span data-ttu-id="75481-471">Die <see cref="T:Microsoft.WindowsAzure.Storage.File.CloudFile" /> , die das Ziel Azure-Datei.</span><span class="sxs-lookup"><span data-stu-id="75481-471">The <see cref="T:Microsoft.WindowsAzure.Storage.File.CloudFile" /> that is the destination Azure file.</span></span></param>
        <param name="options"><span data-ttu-id="75481-472">Ein <see cref="T:Microsoft.WindowsAzure.Storage.DataMovement.UploadOptions" /> -Objekt, das zusätzliche Optionen für den Vorgang angibt.</span><span class="sxs-lookup"><span data-stu-id="75481-472">An <see cref="T:Microsoft.WindowsAzure.Storage.DataMovement.UploadOptions" /> object that specifies additional options for the operation.</span></span></param>
        <param name="context"><span data-ttu-id="75481-473">Ein <see cref="T:Microsoft.WindowsAzure.Storage.DataMovement.SingleTransferContext" /> -Objekt, das den Kontext für den aktuellen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="75481-473">A <see cref="T:Microsoft.WindowsAzure.Storage.DataMovement.SingleTransferContext" /> object that represents the context for the current operation.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="75481-474">Ein <see cref="T:System.Threading.CancellationToken" /> Objekt, das beim Warten auf Abschluss einer Aufgabe überwacht werden.</span><span class="sxs-lookup"><span data-stu-id="75481-474">A <see cref="T:System.Threading.CancellationToken" /> object to observe while waiting for a task to complete.</span></span></param>
        <summary>
            <span data-ttu-id="75481-475">Hochladen einer Datei auf Azure-Dateispeicher.</span><span class="sxs-lookup"><span data-stu-id="75481-475">Upload a file to Azure File Storage.</span></span>
            </summary>
        <returns><span data-ttu-id="75481-476">Ein <see cref="T:System.Threading.Tasks.Task" />-Objekt, das den asynchronen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="75481-476">A <see cref="T:System.Threading.Tasks.Task" /> object that represents the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UploadDirectoryAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.DataMovement.TransferStatus&gt; UploadDirectoryAsync (string sourcePath, Microsoft.WindowsAzure.Storage.Blob.CloudBlobDirectory destBlobDir);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.WindowsAzure.Storage.DataMovement.TransferStatus&gt; UploadDirectoryAsync(string sourcePath, class Microsoft.WindowsAzure.Storage.Blob.CloudBlobDirectory destBlobDir) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.DataMovement.TransferManager.UploadDirectoryAsync(System.String,Microsoft.WindowsAzure.Storage.Blob.CloudBlobDirectory)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function UploadDirectoryAsync (sourcePath As String, destBlobDir As CloudBlobDirectory) As Task(Of TransferStatus)" />
      <MemberSignature Language="F#" Value="static member UploadDirectoryAsync : string * Microsoft.WindowsAzure.Storage.Blob.CloudBlobDirectory -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.DataMovement.TransferStatus&gt;" Usage="Microsoft.WindowsAzure.Storage.DataMovement.TransferManager.UploadDirectoryAsync (sourcePath, destBlobDir)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage.DataMovement</AssemblyName>
        <AssemblyVersion>0.5.3.0</AssemblyVersion>
        <AssemblyVersion>0.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.DataMovement.TransferStatus&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="sourcePath" Type="System.String" />
        <Parameter Name="destBlobDir" Type="Microsoft.WindowsAzure.Storage.Blob.CloudBlobDirectory" />
      </Parameters>
      <Docs>
        <param name="sourcePath"><span data-ttu-id="75481-477">Pfad zum Quellverzeichnis</span><span class="sxs-lookup"><span data-stu-id="75481-477">Path to the source directory</span></span></param>
        <param name="destBlobDir"><span data-ttu-id="75481-478">Die <see cref="T:Microsoft.WindowsAzure.Storage.Blob.CloudBlobDirectory" /> , das Azure-Blob-Zielverzeichnis.</span><span class="sxs-lookup"><span data-stu-id="75481-478">The <see cref="T:Microsoft.WindowsAzure.Storage.Blob.CloudBlobDirectory" /> that is the destination Azure blob directory.</span></span></param>
        <summary>
            <span data-ttu-id="75481-479">Laden Sie ein Verzeichnis in Azure Blob-Speicher hoch.</span><span class="sxs-lookup"><span data-stu-id="75481-479">Upload a directory to Azure Blob Storage.</span></span>
            </summary>
        <returns><span data-ttu-id="75481-480">Ein <see cref="T:System.Threading.Tasks.Task`1" /> Objekt des Typs <see cref="T:Microsoft.WindowsAzure.Storage.DataMovement.TransferStatus" /> , die den asynchronen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="75481-480">A <see cref="T:System.Threading.Tasks.Task`1" /> object of type <see cref="T:Microsoft.WindowsAzure.Storage.DataMovement.TransferStatus" /> that represents the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UploadDirectoryAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.DataMovement.TransferStatus&gt; UploadDirectoryAsync (string sourcePath, Microsoft.WindowsAzure.Storage.File.CloudFileDirectory destFileDir);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.WindowsAzure.Storage.DataMovement.TransferStatus&gt; UploadDirectoryAsync(string sourcePath, class Microsoft.WindowsAzure.Storage.File.CloudFileDirectory destFileDir) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.DataMovement.TransferManager.UploadDirectoryAsync(System.String,Microsoft.WindowsAzure.Storage.File.CloudFileDirectory)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function UploadDirectoryAsync (sourcePath As String, destFileDir As CloudFileDirectory) As Task(Of TransferStatus)" />
      <MemberSignature Language="F#" Value="static member UploadDirectoryAsync : string * Microsoft.WindowsAzure.Storage.File.CloudFileDirectory -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.DataMovement.TransferStatus&gt;" Usage="Microsoft.WindowsAzure.Storage.DataMovement.TransferManager.UploadDirectoryAsync (sourcePath, destFileDir)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage.DataMovement</AssemblyName>
        <AssemblyVersion>0.5.3.0</AssemblyVersion>
        <AssemblyVersion>0.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.DataMovement.TransferStatus&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="sourcePath" Type="System.String" />
        <Parameter Name="destFileDir" Type="Microsoft.WindowsAzure.Storage.File.CloudFileDirectory" />
      </Parameters>
      <Docs>
        <param name="sourcePath"><span data-ttu-id="75481-481">Pfad zum Quellverzeichnis</span><span class="sxs-lookup"><span data-stu-id="75481-481">Path to the source directory</span></span></param>
        <param name="destFileDir"><span data-ttu-id="75481-482">Die <see cref="T:Microsoft.WindowsAzure.Storage.File.CloudFileDirectory" /> also das Zielverzeichnis Azure-Datei.</span><span class="sxs-lookup"><span data-stu-id="75481-482">The <see cref="T:Microsoft.WindowsAzure.Storage.File.CloudFileDirectory" /> that is the destination Azure file directory.</span></span></param>
        <summary>
            <span data-ttu-id="75481-483">Laden Sie ein Verzeichnis in Azure File Storage hoch.</span><span class="sxs-lookup"><span data-stu-id="75481-483">Upload a directory to Azure File Storage.</span></span>
            </summary>
        <returns><span data-ttu-id="75481-484">Ein <see cref="T:System.Threading.Tasks.Task`1" /> Objekt des Typs <see cref="T:Microsoft.WindowsAzure.Storage.DataMovement.TransferStatus" /> , die den asynchronen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="75481-484">A <see cref="T:System.Threading.Tasks.Task`1" /> object of type <see cref="T:Microsoft.WindowsAzure.Storage.DataMovement.TransferStatus" /> that represents the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UploadDirectoryAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.DataMovement.TransferStatus&gt; UploadDirectoryAsync (string sourcePath, Microsoft.WindowsAzure.Storage.Blob.CloudBlobDirectory destBlobDir, Microsoft.WindowsAzure.Storage.DataMovement.UploadDirectoryOptions options, Microsoft.WindowsAzure.Storage.DataMovement.DirectoryTransferContext context);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.WindowsAzure.Storage.DataMovement.TransferStatus&gt; UploadDirectoryAsync(string sourcePath, class Microsoft.WindowsAzure.Storage.Blob.CloudBlobDirectory destBlobDir, class Microsoft.WindowsAzure.Storage.DataMovement.UploadDirectoryOptions options, class Microsoft.WindowsAzure.Storage.DataMovement.DirectoryTransferContext context) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.DataMovement.TransferManager.UploadDirectoryAsync(System.String,Microsoft.WindowsAzure.Storage.Blob.CloudBlobDirectory,Microsoft.WindowsAzure.Storage.DataMovement.UploadDirectoryOptions,Microsoft.WindowsAzure.Storage.DataMovement.DirectoryTransferContext)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function UploadDirectoryAsync (sourcePath As String, destBlobDir As CloudBlobDirectory, options As UploadDirectoryOptions, context As DirectoryTransferContext) As Task(Of TransferStatus)" />
      <MemberSignature Language="F#" Value="static member UploadDirectoryAsync : string * Microsoft.WindowsAzure.Storage.Blob.CloudBlobDirectory * Microsoft.WindowsAzure.Storage.DataMovement.UploadDirectoryOptions * Microsoft.WindowsAzure.Storage.DataMovement.DirectoryTransferContext -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.DataMovement.TransferStatus&gt;" Usage="Microsoft.WindowsAzure.Storage.DataMovement.TransferManager.UploadDirectoryAsync (sourcePath, destBlobDir, options, context)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage.DataMovement</AssemblyName>
        <AssemblyVersion>0.5.3.0</AssemblyVersion>
        <AssemblyVersion>0.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.DataMovement.TransferStatus&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="sourcePath" Type="System.String" />
        <Parameter Name="destBlobDir" Type="Microsoft.WindowsAzure.Storage.Blob.CloudBlobDirectory" />
        <Parameter Name="options" Type="Microsoft.WindowsAzure.Storage.DataMovement.UploadDirectoryOptions" />
        <Parameter Name="context" Type="Microsoft.WindowsAzure.Storage.DataMovement.DirectoryTransferContext" />
      </Parameters>
      <Docs>
        <param name="sourcePath"><span data-ttu-id="75481-485">Pfad zum Quellverzeichnis</span><span class="sxs-lookup"><span data-stu-id="75481-485">Path to the source directory</span></span></param>
        <param name="destBlobDir"><span data-ttu-id="75481-486">Die <see cref="T:Microsoft.WindowsAzure.Storage.Blob.CloudBlobDirectory" /> , das Azure-Blob-Zielverzeichnis.</span><span class="sxs-lookup"><span data-stu-id="75481-486">The <see cref="T:Microsoft.WindowsAzure.Storage.Blob.CloudBlobDirectory" /> that is the destination Azure blob directory.</span></span></param>
        <param name="options"><span data-ttu-id="75481-487">Ein <see cref="T:Microsoft.WindowsAzure.Storage.DataMovement.UploadDirectoryOptions" /> -Objekt, das zusätzliche Optionen für den Vorgang angibt.</span><span class="sxs-lookup"><span data-stu-id="75481-487">An <see cref="T:Microsoft.WindowsAzure.Storage.DataMovement.UploadDirectoryOptions" /> object that specifies additional options for the operation.</span></span></param>
        <param name="context"><span data-ttu-id="75481-488">Ein <see cref="T:Microsoft.WindowsAzure.Storage.DataMovement.DirectoryTransferContext" /> -Objekt, das den Kontext für den aktuellen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="75481-488">A <see cref="T:Microsoft.WindowsAzure.Storage.DataMovement.DirectoryTransferContext" /> object that represents the context for the current operation.</span></span></param>
        <summary>
            <span data-ttu-id="75481-489">Laden Sie ein Verzeichnis in Azure Blob-Speicher hoch.</span><span class="sxs-lookup"><span data-stu-id="75481-489">Upload a directory to Azure Blob Storage.</span></span>
            </summary>
        <returns><span data-ttu-id="75481-490">Ein <see cref="T:System.Threading.Tasks.Task`1" /> Objekt des Typs <see cref="T:Microsoft.WindowsAzure.Storage.DataMovement.TransferStatus" /> , die den asynchronen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="75481-490">A <see cref="T:System.Threading.Tasks.Task`1" /> object of type <see cref="T:Microsoft.WindowsAzure.Storage.DataMovement.TransferStatus" /> that represents the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UploadDirectoryAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.DataMovement.TransferStatus&gt; UploadDirectoryAsync (string sourcePath, Microsoft.WindowsAzure.Storage.File.CloudFileDirectory destFileDir, Microsoft.WindowsAzure.Storage.DataMovement.UploadDirectoryOptions options, Microsoft.WindowsAzure.Storage.DataMovement.DirectoryTransferContext context);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.WindowsAzure.Storage.DataMovement.TransferStatus&gt; UploadDirectoryAsync(string sourcePath, class Microsoft.WindowsAzure.Storage.File.CloudFileDirectory destFileDir, class Microsoft.WindowsAzure.Storage.DataMovement.UploadDirectoryOptions options, class Microsoft.WindowsAzure.Storage.DataMovement.DirectoryTransferContext context) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.DataMovement.TransferManager.UploadDirectoryAsync(System.String,Microsoft.WindowsAzure.Storage.File.CloudFileDirectory,Microsoft.WindowsAzure.Storage.DataMovement.UploadDirectoryOptions,Microsoft.WindowsAzure.Storage.DataMovement.DirectoryTransferContext)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function UploadDirectoryAsync (sourcePath As String, destFileDir As CloudFileDirectory, options As UploadDirectoryOptions, context As DirectoryTransferContext) As Task(Of TransferStatus)" />
      <MemberSignature Language="F#" Value="static member UploadDirectoryAsync : string * Microsoft.WindowsAzure.Storage.File.CloudFileDirectory * Microsoft.WindowsAzure.Storage.DataMovement.UploadDirectoryOptions * Microsoft.WindowsAzure.Storage.DataMovement.DirectoryTransferContext -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.DataMovement.TransferStatus&gt;" Usage="Microsoft.WindowsAzure.Storage.DataMovement.TransferManager.UploadDirectoryAsync (sourcePath, destFileDir, options, context)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage.DataMovement</AssemblyName>
        <AssemblyVersion>0.5.3.0</AssemblyVersion>
        <AssemblyVersion>0.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.DataMovement.TransferStatus&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="sourcePath" Type="System.String" />
        <Parameter Name="destFileDir" Type="Microsoft.WindowsAzure.Storage.File.CloudFileDirectory" />
        <Parameter Name="options" Type="Microsoft.WindowsAzure.Storage.DataMovement.UploadDirectoryOptions" />
        <Parameter Name="context" Type="Microsoft.WindowsAzure.Storage.DataMovement.DirectoryTransferContext" />
      </Parameters>
      <Docs>
        <param name="sourcePath"><span data-ttu-id="75481-491">Pfad zum Quellverzeichnis</span><span class="sxs-lookup"><span data-stu-id="75481-491">Path to the source directory</span></span></param>
        <param name="destFileDir"><span data-ttu-id="75481-492">Die <see cref="T:Microsoft.WindowsAzure.Storage.File.CloudFileDirectory" /> also das Zielverzeichnis Azure-Datei.</span><span class="sxs-lookup"><span data-stu-id="75481-492">The <see cref="T:Microsoft.WindowsAzure.Storage.File.CloudFileDirectory" /> that is the destination Azure file directory.</span></span></param>
        <param name="options"><span data-ttu-id="75481-493">Ein <see cref="T:Microsoft.WindowsAzure.Storage.DataMovement.UploadDirectoryOptions" /> -Objekt, das zusätzliche Optionen für den Vorgang angibt.</span><span class="sxs-lookup"><span data-stu-id="75481-493">An <see cref="T:Microsoft.WindowsAzure.Storage.DataMovement.UploadDirectoryOptions" /> object that specifies additional options for the operation.</span></span></param>
        <param name="context"><span data-ttu-id="75481-494">Ein <see cref="T:Microsoft.WindowsAzure.Storage.DataMovement.DirectoryTransferContext" /> -Objekt, das den Kontext für den aktuellen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="75481-494">A <see cref="T:Microsoft.WindowsAzure.Storage.DataMovement.DirectoryTransferContext" /> object that represents the context for the current operation.</span></span></param>
        <summary>
            <span data-ttu-id="75481-495">Laden Sie ein Verzeichnis in Azure File Storage hoch.</span><span class="sxs-lookup"><span data-stu-id="75481-495">Upload a directory to Azure File Storage.</span></span>
            </summary>
        <returns><span data-ttu-id="75481-496">Ein <see cref="T:System.Threading.Tasks.Task`1" /> Objekt des Typs <see cref="T:Microsoft.WindowsAzure.Storage.DataMovement.TransferStatus" /> , die den asynchronen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="75481-496">A <see cref="T:System.Threading.Tasks.Task`1" /> object of type <see cref="T:Microsoft.WindowsAzure.Storage.DataMovement.TransferStatus" /> that represents the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UploadDirectoryAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.DataMovement.TransferStatus&gt; UploadDirectoryAsync (string sourcePath, Microsoft.WindowsAzure.Storage.Blob.CloudBlobDirectory destBlobDir, Microsoft.WindowsAzure.Storage.DataMovement.UploadDirectoryOptions options, Microsoft.WindowsAzure.Storage.DataMovement.DirectoryTransferContext context, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.WindowsAzure.Storage.DataMovement.TransferStatus&gt; UploadDirectoryAsync(string sourcePath, class Microsoft.WindowsAzure.Storage.Blob.CloudBlobDirectory destBlobDir, class Microsoft.WindowsAzure.Storage.DataMovement.UploadDirectoryOptions options, class Microsoft.WindowsAzure.Storage.DataMovement.DirectoryTransferContext context, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.DataMovement.TransferManager.UploadDirectoryAsync(System.String,Microsoft.WindowsAzure.Storage.Blob.CloudBlobDirectory,Microsoft.WindowsAzure.Storage.DataMovement.UploadDirectoryOptions,Microsoft.WindowsAzure.Storage.DataMovement.DirectoryTransferContext,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member UploadDirectoryAsync : string * Microsoft.WindowsAzure.Storage.Blob.CloudBlobDirectory * Microsoft.WindowsAzure.Storage.DataMovement.UploadDirectoryOptions * Microsoft.WindowsAzure.Storage.DataMovement.DirectoryTransferContext * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.DataMovement.TransferStatus&gt;" Usage="Microsoft.WindowsAzure.Storage.DataMovement.TransferManager.UploadDirectoryAsync (sourcePath, destBlobDir, options, context, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage.DataMovement</AssemblyName>
        <AssemblyVersion>0.5.3.0</AssemblyVersion>
        <AssemblyVersion>0.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.DataMovement.TransferStatus&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="sourcePath" Type="System.String" />
        <Parameter Name="destBlobDir" Type="Microsoft.WindowsAzure.Storage.Blob.CloudBlobDirectory" />
        <Parameter Name="options" Type="Microsoft.WindowsAzure.Storage.DataMovement.UploadDirectoryOptions" />
        <Parameter Name="context" Type="Microsoft.WindowsAzure.Storage.DataMovement.DirectoryTransferContext" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="sourcePath"><span data-ttu-id="75481-497">Pfad zum Quellverzeichnis</span><span class="sxs-lookup"><span data-stu-id="75481-497">Path to the source directory</span></span></param>
        <param name="destBlobDir"><span data-ttu-id="75481-498">Die <see cref="T:Microsoft.WindowsAzure.Storage.Blob.CloudBlobDirectory" /> , das Azure-Blob-Zielverzeichnis.</span><span class="sxs-lookup"><span data-stu-id="75481-498">The <see cref="T:Microsoft.WindowsAzure.Storage.Blob.CloudBlobDirectory" /> that is the destination Azure blob directory.</span></span></param>
        <param name="options"><span data-ttu-id="75481-499">Ein <see cref="T:Microsoft.WindowsAzure.Storage.DataMovement.UploadDirectoryOptions" /> -Objekt, das zusätzliche Optionen für den Vorgang angibt.</span><span class="sxs-lookup"><span data-stu-id="75481-499">An <see cref="T:Microsoft.WindowsAzure.Storage.DataMovement.UploadDirectoryOptions" /> object that specifies additional options for the operation.</span></span></param>
        <param name="context"><span data-ttu-id="75481-500">Ein <see cref="T:Microsoft.WindowsAzure.Storage.DataMovement.DirectoryTransferContext" /> -Objekt, das den Kontext für den aktuellen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="75481-500">A <see cref="T:Microsoft.WindowsAzure.Storage.DataMovement.DirectoryTransferContext" /> object that represents the context for the current operation.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="75481-501">Ein <see cref="T:System.Threading.CancellationToken" /> Objekt, das beim Warten auf Abschluss einer Aufgabe überwacht werden.</span><span class="sxs-lookup"><span data-stu-id="75481-501">A <see cref="T:System.Threading.CancellationToken" /> object to observe while waiting for a task to complete.</span></span></param>
        <summary>
            <span data-ttu-id="75481-502">Laden Sie ein Verzeichnis in Azure Blob-Speicher hoch.</span><span class="sxs-lookup"><span data-stu-id="75481-502">Upload a directory to Azure Blob Storage.</span></span>
            </summary>
        <returns><span data-ttu-id="75481-503">Ein <see cref="T:System.Threading.Tasks.Task`1" /> Objekt des Typs <see cref="T:Microsoft.WindowsAzure.Storage.DataMovement.TransferStatus" /> , die den asynchronen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="75481-503">A <see cref="T:System.Threading.Tasks.Task`1" /> object of type <see cref="T:Microsoft.WindowsAzure.Storage.DataMovement.TransferStatus" /> that represents the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UploadDirectoryAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.DataMovement.TransferStatus&gt; UploadDirectoryAsync (string sourcePath, Microsoft.WindowsAzure.Storage.File.CloudFileDirectory destFileDir, Microsoft.WindowsAzure.Storage.DataMovement.UploadDirectoryOptions options, Microsoft.WindowsAzure.Storage.DataMovement.DirectoryTransferContext context, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.WindowsAzure.Storage.DataMovement.TransferStatus&gt; UploadDirectoryAsync(string sourcePath, class Microsoft.WindowsAzure.Storage.File.CloudFileDirectory destFileDir, class Microsoft.WindowsAzure.Storage.DataMovement.UploadDirectoryOptions options, class Microsoft.WindowsAzure.Storage.DataMovement.DirectoryTransferContext context, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.DataMovement.TransferManager.UploadDirectoryAsync(System.String,Microsoft.WindowsAzure.Storage.File.CloudFileDirectory,Microsoft.WindowsAzure.Storage.DataMovement.UploadDirectoryOptions,Microsoft.WindowsAzure.Storage.DataMovement.DirectoryTransferContext,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member UploadDirectoryAsync : string * Microsoft.WindowsAzure.Storage.File.CloudFileDirectory * Microsoft.WindowsAzure.Storage.DataMovement.UploadDirectoryOptions * Microsoft.WindowsAzure.Storage.DataMovement.DirectoryTransferContext * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.DataMovement.TransferStatus&gt;" Usage="Microsoft.WindowsAzure.Storage.DataMovement.TransferManager.UploadDirectoryAsync (sourcePath, destFileDir, options, context, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage.DataMovement</AssemblyName>
        <AssemblyVersion>0.5.3.0</AssemblyVersion>
        <AssemblyVersion>0.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.DataMovement.TransferStatus&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="sourcePath" Type="System.String" />
        <Parameter Name="destFileDir" Type="Microsoft.WindowsAzure.Storage.File.CloudFileDirectory" />
        <Parameter Name="options" Type="Microsoft.WindowsAzure.Storage.DataMovement.UploadDirectoryOptions" />
        <Parameter Name="context" Type="Microsoft.WindowsAzure.Storage.DataMovement.DirectoryTransferContext" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="sourcePath"><span data-ttu-id="75481-504">Pfad zum Quellverzeichnis</span><span class="sxs-lookup"><span data-stu-id="75481-504">Path to the source directory</span></span></param>
        <param name="destFileDir"><span data-ttu-id="75481-505">Die <see cref="T:Microsoft.WindowsAzure.Storage.File.CloudFileDirectory" /> also das Zielverzeichnis Azure-Datei.</span><span class="sxs-lookup"><span data-stu-id="75481-505">The <see cref="T:Microsoft.WindowsAzure.Storage.File.CloudFileDirectory" /> that is the destination Azure file directory.</span></span></param>
        <param name="options"><span data-ttu-id="75481-506">Ein <see cref="T:Microsoft.WindowsAzure.Storage.DataMovement.UploadDirectoryOptions" /> -Objekt, das zusätzliche Optionen für den Vorgang angibt.</span><span class="sxs-lookup"><span data-stu-id="75481-506">An <see cref="T:Microsoft.WindowsAzure.Storage.DataMovement.UploadDirectoryOptions" /> object that specifies additional options for the operation.</span></span></param>
        <param name="context"><span data-ttu-id="75481-507">Ein <see cref="T:Microsoft.WindowsAzure.Storage.DataMovement.DirectoryTransferContext" /> -Objekt, das den Kontext für den aktuellen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="75481-507">A <see cref="T:Microsoft.WindowsAzure.Storage.DataMovement.DirectoryTransferContext" /> object that represents the context for the current operation.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="75481-508">Ein <see cref="T:System.Threading.CancellationToken" /> Objekt, das beim Warten auf Abschluss einer Aufgabe überwacht werden.</span><span class="sxs-lookup"><span data-stu-id="75481-508">A <see cref="T:System.Threading.CancellationToken" /> object to observe while waiting for a task to complete.</span></span></param>
        <summary>
            <span data-ttu-id="75481-509">Laden Sie ein Verzeichnis in Azure File Storage hoch.</span><span class="sxs-lookup"><span data-stu-id="75481-509">Upload a directory to Azure File Storage.</span></span>
            </summary>
        <returns><span data-ttu-id="75481-510">Ein <see cref="T:System.Threading.Tasks.Task`1" /> Objekt des Typs <see cref="T:Microsoft.WindowsAzure.Storage.DataMovement.TransferStatus" /> , die den asynchronen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="75481-510">A <see cref="T:System.Threading.Tasks.Task`1" /> object of type <see cref="T:Microsoft.WindowsAzure.Storage.DataMovement.TransferStatus" /> that represents the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>