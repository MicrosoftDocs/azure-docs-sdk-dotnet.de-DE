<Type Name="OutputFileReference" FullName="Microsoft.Azure.Batch.Conventions.Files.OutputFileReference">
  <TypeSignature Language="C#" Value="public sealed class OutputFileReference" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit OutputFileReference extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Batch.Conventions.Files.OutputFileReference" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class OutputFileReference" />
  <TypeSignature Language="F#" Value="type OutputFileReference = class" />
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
            <span data-ttu-id="2a8b1-101">Ein Verweis auf eine Ausgabedatei-Task oder-Auftrag im dauerhaften Speicher.</span><span class="sxs-lookup"><span data-stu-id="2a8b1-101">A reference to a task or job output file in persistent storage.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="CloudBlob">
      <MemberSignature Language="C#" Value="public Microsoft.WindowsAzure.Storage.Blob.ICloudBlob CloudBlob { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.WindowsAzure.Storage.Blob.ICloudBlob CloudBlob" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Conventions.Files.OutputFileReference.CloudBlob" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property CloudBlob As ICloudBlob" />
      <MemberSignature Language="F#" Value="member this.CloudBlob : Microsoft.WindowsAzure.Storage.Blob.ICloudBlob" Usage="Microsoft.Azure.Batch.Conventions.Files.OutputFileReference.CloudBlob" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch.Conventions.Files</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Storage.Blob.ICloudBlob</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="2a8b1-102">Ruft einen Verweis auf die zugrunde liegende <see cref="T:Microsoft.WindowsAzure.Storage.Blob.ICloudBlob" /> Objekt, das die Datei im permanenten Speicher darstellt.</span><span class="sxs-lookup"><span data-stu-id="2a8b1-102">Gets a reference to the underlying <see cref="T:Microsoft.WindowsAzure.Storage.Blob.ICloudBlob" /> object representing the file in persistent storage.</span></span> <span data-ttu-id="2a8b1-103">Dies kann verwendet werden, um Blob-Methoden "oder" Overloads Diagnoseinformationen werden nicht durch Aufrufen der <see cref="T:Microsoft.Azure.Batch.Conventions.Files.OutputFileReference" /> Abstraktion.</span><span class="sxs-lookup"><span data-stu-id="2a8b1-103">This can be used to invoke blob methods or overloads not surfaced by the <see cref="T:Microsoft.Azure.Batch.Conventions.Files.OutputFileReference" /> abstraction.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task DeleteAsync (System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task DeleteAsync(valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Conventions.Files.OutputFileReference.DeleteAsync(System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.DeleteAsync : System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="outputFileReference.DeleteAsync cancellationToken" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch.Conventions.Files</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Batch.Conventions.Files.OutputFileReference/&lt;DeleteAsync&gt;d__12))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="cancellationToken"><span data-ttu-id="2a8b1-104">Ein <see cref="T:System.Threading.CancellationToken" /> für die Steuerung der Lebensdauer eines asynchronen Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="2a8b1-104">A <see cref="T:System.Threading.CancellationToken" /> for controlling the lifetime of the asynchronous operation.</span></span></param>
        <summary>
            <span data-ttu-id="2a8b1-105">Löscht die Datei aus dem permanenten Speicher.</span><span class="sxs-lookup"><span data-stu-id="2a8b1-105">Deletes the file from persistent storage.</span></span>
            </summary>
        <returns><span data-ttu-id="2a8b1-106">Ein <see cref="T:System.Threading.Tasks.Task" />-Element, das den asynchronen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="2a8b1-106">A <see cref="T:System.Threading.Tasks.Task" /> that represents the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
        <altmember cref="M:Microsoft.WindowsAzure.Storage.Blob.ICloudBlob.DeleteAsync" />
      </Docs>
    </Member>
    <Member MemberName="DownloadToByteArrayAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;int&gt; DownloadToByteArrayAsync (byte[] target, int index, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;int32&gt; DownloadToByteArrayAsync(unsigned int8[] target, int32 index, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Conventions.Files.OutputFileReference.DownloadToByteArrayAsync(System.Byte[],System.Int32,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.DownloadToByteArrayAsync : byte[] * int * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;int&gt;" Usage="outputFileReference.DownloadToByteArrayAsync (target, index, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch.Conventions.Files</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Batch.Conventions.Files.OutputFileReference/&lt;DownloadToByteArrayAsync&gt;d__11))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="target" Type="System.Byte[]" />
        <Parameter Name="index" Type="System.Int32" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="target"><span data-ttu-id="2a8b1-107">Das zielbytearray.</span><span class="sxs-lookup"><span data-stu-id="2a8b1-107">The target byte array.</span></span></param>
        <param name="index"><span data-ttu-id="2a8b1-108">Der Startoffset im Bytearray</span><span class="sxs-lookup"><span data-stu-id="2a8b1-108">The starting offset in the byte array</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="2a8b1-109">Ein <see cref="T:System.Threading.CancellationToken" /> für die Steuerung der Lebensdauer eines asynchronen Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="2a8b1-109">A <see cref="T:System.Threading.CancellationToken" /> for controlling the lifetime of the asynchronous operation.</span></span></param>
        <summary>
            <span data-ttu-id="2a8b1-110">Lädt den Inhalt der Datei in ein Bytearray herunter.</span><span class="sxs-lookup"><span data-stu-id="2a8b1-110">Downloads the contents of the file to a byte array.</span></span>
            </summary>
        <returns><span data-ttu-id="2a8b1-111">Die Gesamtanzahl der in den Puffer gelesenen Bytes.</span><span class="sxs-lookup"><span data-stu-id="2a8b1-111">The total number of bytes read into the buffer.</span></span></returns>
        <remarks>To be added.</remarks>
        <altmember cref="M:Microsoft.WindowsAzure.Storage.Blob.ICloudBlob.DownloadToByteArrayAsync(System.Byte[],System.Int32)" />
      </Docs>
    </Member>
    <Member MemberName="DownloadToFileAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task DownloadToFileAsync (string path, System.IO.FileMode mode, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task DownloadToFileAsync(string path, valuetype System.IO.FileMode mode, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Conventions.Files.OutputFileReference.DownloadToFileAsync(System.String,System.IO.FileMode,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.DownloadToFileAsync : string * System.IO.FileMode * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="outputFileReference.DownloadToFileAsync (path, mode, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch.Conventions.Files</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Batch.Conventions.Files.OutputFileReference/&lt;DownloadToFileAsync&gt;d__9))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="path" Type="System.String" />
        <Parameter Name="mode" Type="System.IO.FileMode" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="path"><span data-ttu-id="2a8b1-112">Der Pfad, der zum Herunterladen der Datei.</span><span class="sxs-lookup"><span data-stu-id="2a8b1-112">The path to which to download the file.</span></span></param>
        <param name="mode"><span data-ttu-id="2a8b1-113">Gibt an, wie die Datei geöffnet oder erstellt.</span><span class="sxs-lookup"><span data-stu-id="2a8b1-113">Specifies how to open or create the file.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="2a8b1-114">Ein <see cref="T:System.Threading.CancellationToken" /> für die Steuerung der Lebensdauer eines asynchronen Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="2a8b1-114">A <see cref="T:System.Threading.CancellationToken" /> for controlling the lifetime of the asynchronous operation.</span></span></param>
        <summary>
            <span data-ttu-id="2a8b1-115">Lädt den Inhalt der Datei in einem angegebenen Pfad.</span><span class="sxs-lookup"><span data-stu-id="2a8b1-115">Downloads the contents of the file to a specified path.</span></span>
            </summary>
        <returns><span data-ttu-id="2a8b1-116">Ein <see cref="T:System.Threading.Tasks.Task" />-Element, das den asynchronen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="2a8b1-116">A <see cref="T:System.Threading.Tasks.Task" /> that represents the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
        <altmember cref="M:Microsoft.WindowsAzure.Storage.Blob.ICloudBlob.DownloadToFileAsync(System.String,System.IO.FileMode)" />
      </Docs>
    </Member>
    <Member MemberName="DownloadToStreamAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task DownloadToStreamAsync (System.IO.Stream target, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task DownloadToStreamAsync(class System.IO.Stream target, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Conventions.Files.OutputFileReference.DownloadToStreamAsync(System.IO.Stream,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.DownloadToStreamAsync : System.IO.Stream * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="outputFileReference.DownloadToStreamAsync (target, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch.Conventions.Files</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Batch.Conventions.Files.OutputFileReference/&lt;DownloadToStreamAsync&gt;d__10))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="target" Type="System.IO.Stream" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="target"><span data-ttu-id="2a8b1-117">Der Zieldatenstrom.</span><span class="sxs-lookup"><span data-stu-id="2a8b1-117">The target stream.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="2a8b1-118">Ein <see cref="T:System.Threading.CancellationToken" /> für die Steuerung der Lebensdauer eines asynchronen Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="2a8b1-118">A <see cref="T:System.Threading.CancellationToken" /> for controlling the lifetime of the asynchronous operation.</span></span></param>
        <summary>
            <span data-ttu-id="2a8b1-119">Lädt den Inhalt der Datei in einen Datenstrom herunter.</span><span class="sxs-lookup"><span data-stu-id="2a8b1-119">Downloads the contents of the file to a stream.</span></span>
            </summary>
        <returns><span data-ttu-id="2a8b1-120">Ein <see cref="T:System.Threading.Tasks.Task" />-Element, das den asynchronen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="2a8b1-120">A <see cref="T:System.Threading.Tasks.Task" /> that represents the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
        <altmember cref="M:Microsoft.WindowsAzure.Storage.Blob.ICloudBlob.DownloadToStreamAsync(System.IO.Stream)" />
      </Docs>
    </Member>
    <Member MemberName="FilePath">
      <MemberSignature Language="C#" Value="public string FilePath { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string FilePath" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Conventions.Files.OutputFileReference.FilePath" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property FilePath As String" />
      <MemberSignature Language="F#" Value="member this.FilePath : string" Usage="Microsoft.Azure.Batch.Conventions.Files.OutputFileReference.FilePath" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch.Conventions.Files</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="2a8b1-121">Ruft den Pfad, unter dem die Datei gespeichert wurde.</span><span class="sxs-lookup"><span data-stu-id="2a8b1-121">Gets the path under which the file was stored.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks><span data-ttu-id="2a8b1-122">Wenn die Datei unter einem Verzeichnispfad gespeichert wurde, wird die FilePath-Eigenschaft der Verzeichnistrennzeichen des zugrunde liegenden Blob-Speichers (z. B. mydirectory/myfile.txt) verwendet.</span><span class="sxs-lookup"><span data-stu-id="2a8b1-122">If the file was stored under a directory path, the FilePath property uses the directory separator of the underlying blob storage (for example, mydirectory/myfile.txt).</span></span> <span data-ttu-id="2a8b1-123">Diese Pfade möglicherweise nicht direkt als Windows-Pfade verwendet werden kann.</span><span class="sxs-lookup"><span data-stu-id="2a8b1-123">Such paths may not be directly usable as Windows paths.</span></span></remarks>
      </Docs>
    </Member>
    <Member MemberName="OpenReadAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.IO.Stream&gt; OpenReadAsync (System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.IO.Stream&gt; OpenReadAsync(valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Conventions.Files.OutputFileReference.OpenReadAsync(System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.OpenReadAsync : System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.IO.Stream&gt;" Usage="outputFileReference.OpenReadAsync cancellationToken" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch.Conventions.Files</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Batch.Conventions.Files.OutputFileReference/&lt;OpenReadAsync&gt;d__13))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.IO.Stream&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="cancellationToken"><span data-ttu-id="2a8b1-124">Ein <see cref="T:System.Threading.CancellationToken" /> für die Steuerung der Lebensdauer eines asynchronen Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="2a8b1-124">A <see cref="T:System.Threading.CancellationToken" /> for controlling the lifetime of the asynchronous operation.</span></span></param>
        <summary>
            <span data-ttu-id="2a8b1-125">Öffnet einen Stream zum Lesen aus der Datei im dauerhaften Speicher.</span><span class="sxs-lookup"><span data-stu-id="2a8b1-125">Opens a stream for reading from the file in persistent storage.</span></span>
            </summary>
        <returns><span data-ttu-id="2a8b1-126">Ein Datenstrom, der zum Lesen aus dem Blob verwendet wird.</span><span class="sxs-lookup"><span data-stu-id="2a8b1-126">A stream to be used for reading from the blob.</span></span></returns>
        <remarks>To be added.</remarks>
        <altmember cref="M:Microsoft.WindowsAzure.Storage.Blob.ICloudBlob.OpenReadAsync(Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext)" />
      </Docs>
    </Member>
    <Member MemberName="Uri">
      <MemberSignature Language="C#" Value="public Uri Uri { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Uri Uri" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Conventions.Files.OutputFileReference.Uri" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Uri As Uri" />
      <MemberSignature Language="F#" Value="member this.Uri : Uri" Usage="Microsoft.Azure.Batch.Conventions.Files.OutputFileReference.Uri" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch.Conventions.Files</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Uri</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="2a8b1-127">Ruft den URI der Datei im dauerhaften Speicher ab.</span><span class="sxs-lookup"><span data-stu-id="2a8b1-127">Gets the URI of the file in persistent storage.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>