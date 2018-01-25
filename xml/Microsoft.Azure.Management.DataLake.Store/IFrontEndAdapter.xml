<Type Name="IFrontEndAdapter" FullName="Microsoft.Azure.Management.DataLake.Store.IFrontEndAdapter">
  <TypeSignature Language="C#" Value="public interface IFrontEndAdapter" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IFrontEndAdapter" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.DataLake.Store.IFrontEndAdapter" />
  <TypeSignature Language="VB.NET" Value="Public Interface IFrontEndAdapter" />
  <TypeSignature Language="F#" Value="type IFrontEndAdapter = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.DataLake.Store</AssemblyName>
    <AssemblyVersion>2.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="5583f-101">Definiert die Vorgänge, die die DataLakeTransferClient aus dem Front-End benötigt werden, um ausgeführt werden</span><span class="sxs-lookup"><span data-stu-id="5583f-101">Defines operations that the DataLakeTransferClient needs from the FrontEnd in order to operate</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="AppendToStream">
      <MemberSignature Language="C#" Value="public void AppendToStream (string streamPath, byte[] data, long offset, int length);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void AppendToStream(string streamPath, unsigned int8[] data, int64 offset, int32 length) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Store.IFrontEndAdapter.AppendToStream(System.String,System.Byte[],System.Int64,System.Int32)" />
      <MemberSignature Language="VB.NET" Value="Public Sub AppendToStream (streamPath As String, data As Byte(), offset As Long, length As Integer)" />
      <MemberSignature Language="F#" Value="abstract member AppendToStream : string * byte[] * int64 * int -&gt; unit" Usage="iFrontEndAdapter.AppendToStream (streamPath, data, offset, length)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Store</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="streamPath" Type="System.String" />
        <Parameter Name="data" Type="System.Byte[]" />
        <Parameter Name="offset" Type="System.Int64" />
        <Parameter Name="length" Type="System.Int32" />
      </Parameters>
      <Docs>
        <param name="streamPath"><span data-ttu-id="5583f-102">Der relative Pfad in den Stream.</span><span class="sxs-lookup"><span data-stu-id="5583f-102">The relative path to the stream.</span></span></param>
        <param name="data"><span data-ttu-id="5583f-103">Ein Array von Bytes, die in den Stream angefügt werden.</span><span class="sxs-lookup"><span data-stu-id="5583f-103">An array of bytes to be appended to the stream.</span></span></param>
        <param name="offset"><span data-ttu-id="5583f-104">Der Offset, bei dem in den Stream angefügt werden soll.</span><span class="sxs-lookup"><span data-stu-id="5583f-104">The offset at which to append to the stream.</span></span></param>
        <param name="length"><span data-ttu-id="5583f-105">Die Anzahl der Bytes, die angefügt werden soll (beginnend mit 0).</span><span class="sxs-lookup"><span data-stu-id="5583f-105">The number of bytes to append (starting at 0).</span></span></param>
        <summary>
            <span data-ttu-id="5583f-106">Fügt das angegebene Bytearray bis zum Ende einer angegebenen Datenstrom.</span><span class="sxs-lookup"><span data-stu-id="5583f-106">Appends the given byte array to the end of a given stream.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentNullException"><span data-ttu-id="5583f-107">Wenn die Daten an, die angefügt werden, null oder leer ist.</span><span class="sxs-lookup"><span data-stu-id="5583f-107">If the data to be appended is null or empty.</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName="Concatenate">
      <MemberSignature Language="C#" Value="public void Concatenate (string targetStreamPath, string[] inputStreamPaths, bool isDownload = false);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Concatenate(string targetStreamPath, string[] inputStreamPaths, bool isDownload) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Store.IFrontEndAdapter.Concatenate(System.String,System.String[],System.Boolean)" />
      <MemberSignature Language="VB.NET" Value="Public Sub Concatenate (targetStreamPath As String, inputStreamPaths As String(), Optional isDownload As Boolean = false)" />
      <MemberSignature Language="F#" Value="abstract member Concatenate : string * string[] * bool -&gt; unit" Usage="iFrontEndAdapter.Concatenate (targetStreamPath, inputStreamPaths, isDownload)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Store</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="targetStreamPath" Type="System.String" />
        <Parameter Name="inputStreamPaths" Type="System.String[]" />
        <Parameter Name="isDownload" Type="System.Boolean" />
      </Parameters>
      <Docs>
        <param name="targetStreamPath"><span data-ttu-id="5583f-108">Der relative Pfad auf den Zieldatenstrom.</span><span class="sxs-lookup"><span data-stu-id="5583f-108">The relative path to the target stream.</span></span></param>
        <param name="inputStreamPaths"><span data-ttu-id="5583f-109">Ein geordnetes Array von Pfaden, die der Eingabestreams.</span><span class="sxs-lookup"><span data-stu-id="5583f-109">An ordered array of paths to the input streams.</span></span></param>
        <param name="isDownload"><span data-ttu-id="5583f-110">Wenn auf festgelegt <c>"true"</c> [ist Download], d. h., es wird die Datenströme auf dem lokalen Computer statt auf dem Server verketten.</span><span class="sxs-lookup"><span data-stu-id="5583f-110">if set to <c>true</c> [is download], meaning we will concatenate the streams on the local machine instead of on the server.</span></span></param>
        <summary>
            <span data-ttu-id="5583f-111">Verkettet die angegebenen Eingabedatenströme (nacheinander) in den angegebenen Zieltyp Stream an.</span><span class="sxs-lookup"><span data-stu-id="5583f-111">Concatenates the given input streams (in order) into the given target stream.</span></span>
            <span data-ttu-id="5583f-112">Am Ende dieses Vorgangs werden der Eingabestreams gelöscht werden.</span><span class="sxs-lookup"><span data-stu-id="5583f-112">At the end of this operation, input streams will be deleted.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateStream">
      <MemberSignature Language="C#" Value="public void CreateStream (string streamPath, bool overwrite, byte[] data, int byteCount);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void CreateStream(string streamPath, bool overwrite, unsigned int8[] data, int32 byteCount) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Store.IFrontEndAdapter.CreateStream(System.String,System.Boolean,System.Byte[],System.Int32)" />
      <MemberSignature Language="VB.NET" Value="Public Sub CreateStream (streamPath As String, overwrite As Boolean, data As Byte(), byteCount As Integer)" />
      <MemberSignature Language="F#" Value="abstract member CreateStream : string * bool * byte[] * int -&gt; unit" Usage="iFrontEndAdapter.CreateStream (streamPath, overwrite, data, byteCount)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Store</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="streamPath" Type="System.String" />
        <Parameter Name="overwrite" Type="System.Boolean" />
        <Parameter Name="data" Type="System.Byte[]" />
        <Parameter Name="byteCount" Type="System.Int32" />
      </Parameters>
      <Docs>
        <param name="streamPath"><span data-ttu-id="5583f-113">Der relative Pfad in den Stream.</span><span class="sxs-lookup"><span data-stu-id="5583f-113">The relative path to the stream.</span></span></param>
        <param name="overwrite"><span data-ttu-id="5583f-114">Ob überschreiben einen vorhandenen Datenstrom.</span><span class="sxs-lookup"><span data-stu-id="5583f-114">Whether to overwrite an existing stream.</span></span></param>
        <param name="data"><span data-ttu-id="5583f-115">Die Daten.</span><span class="sxs-lookup"><span data-stu-id="5583f-115">The data.</span></span></param>
        <param name="byteCount"><span data-ttu-id="5583f-116">Die Anzahl von Bytes.</span><span class="sxs-lookup"><span data-stu-id="5583f-116">The byte count.</span></span></param>
        <summary>
            <span data-ttu-id="5583f-117">Erstellt einen neuen, leeren Datenstrom im angegebenen Pfad.</span><span class="sxs-lookup"><span data-stu-id="5583f-117">Creates a new, empty stream at the given path.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteStream">
      <MemberSignature Language="C#" Value="public void DeleteStream (string streamPath, bool recurse = false, bool isDownload = false);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void DeleteStream(string streamPath, bool recurse, bool isDownload) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Store.IFrontEndAdapter.DeleteStream(System.String,System.Boolean,System.Boolean)" />
      <MemberSignature Language="VB.NET" Value="Public Sub DeleteStream (streamPath As String, Optional recurse As Boolean = false, Optional isDownload As Boolean = false)" />
      <MemberSignature Language="F#" Value="abstract member DeleteStream : string * bool * bool -&gt; unit" Usage="iFrontEndAdapter.DeleteStream (streamPath, recurse, isDownload)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Store</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="streamPath" Type="System.String" />
        <Parameter Name="recurse" Type="System.Boolean" />
        <Parameter Name="isDownload" Type="System.Boolean" />
      </Parameters>
      <Docs>
        <param name="streamPath"><span data-ttu-id="5583f-118">Der relative Pfad in den Stream.</span><span class="sxs-lookup"><span data-stu-id="5583f-118">The relative path to the stream.</span></span></param>
        <param name="recurse"><span data-ttu-id="5583f-119">Wenn auf festgelegt <c>"true"</c> [Recurse].</span><span class="sxs-lookup"><span data-stu-id="5583f-119">if set to <c>true</c> [recurse].</span></span> <span data-ttu-id="5583f-120">Dies wird für nur die Ordner-Streams verwendet.</span><span class="sxs-lookup"><span data-stu-id="5583f-120">This is used for folder streams only.</span></span></param>
        <param name="isDownload"><span data-ttu-id="5583f-121">Wenn auf festgelegt <c>"true"</c> [ist Download], d. h., es wird einen Datenstrom, auf dem lokalen Computer statt auf dem Server gelöscht.</span><span class="sxs-lookup"><span data-stu-id="5583f-121">if set to <c>true</c> [is download], meaning we will delete a stream on the local machine instead of on the server.</span></span></param>
        <summary>
            <span data-ttu-id="5583f-122">Löscht einen vorhandenen Datenstrom im angegebenen Pfad.</span><span class="sxs-lookup"><span data-stu-id="5583f-122">Deletes an existing stream at the given path.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetStreamLength">
      <MemberSignature Language="C#" Value="public long GetStreamLength (string streamPath, bool isDownload = false);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance int64 GetStreamLength(string streamPath, bool isDownload) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Store.IFrontEndAdapter.GetStreamLength(System.String,System.Boolean)" />
      <MemberSignature Language="VB.NET" Value="Public Function GetStreamLength (streamPath As String, Optional isDownload As Boolean = false) As Long" />
      <MemberSignature Language="F#" Value="abstract member GetStreamLength : string * bool -&gt; int64" Usage="iFrontEndAdapter.GetStreamLength (streamPath, isDownload)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Store</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int64</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="streamPath" Type="System.String" />
        <Parameter Name="isDownload" Type="System.Boolean" />
      </Parameters>
      <Docs>
        <param name="streamPath"><span data-ttu-id="5583f-123">Der relative Pfad in den Stream.</span><span class="sxs-lookup"><span data-stu-id="5583f-123">The relative path to the stream.</span></span></param>
        <param name="isDownload"><span data-ttu-id="5583f-124">Wenn auf festgelegt <c>"true"</c> [ist Download], d. h., es wird die Länge des Streams abrufen, auf dem lokalen Computer statt auf dem Server.</span><span class="sxs-lookup"><span data-stu-id="5583f-124">if set to <c>true</c> [is download], meaning we will get the stream length on the local machine instead of on the server.</span></span></param>
        <summary>
            <span data-ttu-id="5583f-125">Ruft einen Wert, der angibt, der Länge des Streams in Bytes ab.</span><span class="sxs-lookup"><span data-stu-id="5583f-125">Gets a value indicating the length of a stream, in bytes.</span></span>
            </summary>
        <returns><span data-ttu-id="5583f-126">Die Länge des Streams in Bytes.</span><span class="sxs-lookup"><span data-stu-id="5583f-126">The length of the stream, in bytes.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IsDirectory">
      <MemberSignature Language="C#" Value="public bool IsDirectory (string streamPath);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance bool IsDirectory(string streamPath) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Store.IFrontEndAdapter.IsDirectory(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function IsDirectory (streamPath As String) As Boolean" />
      <MemberSignature Language="F#" Value="abstract member IsDirectory : string -&gt; bool" Usage="iFrontEndAdapter.IsDirectory streamPath" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Store</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="streamPath" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="streamPath"><span data-ttu-id="5583f-127">Der relative Pfad in den Stream.</span><span class="sxs-lookup"><span data-stu-id="5583f-127">The relative path to the stream.</span></span></param>
        <summary>
            <span data-ttu-id="5583f-128">Bestimmt, ob der Stream mit angegebenen Pfad auf dem Server ein Verzeichnis oder eine abschließende Datei ist.</span><span class="sxs-lookup"><span data-stu-id="5583f-128">Determines if the stream with given path on the server is a directory or a terminating file.</span></span>
            <span data-ttu-id="5583f-129">Dies wird ausschließlich für den Download verwendet.</span><span class="sxs-lookup"><span data-stu-id="5583f-129">This is used exclusively for download.</span></span>
            </summary>
        <returns><span data-ttu-id="5583f-130">"True", wenn der Stream andernfalls "false" ein Verzeichnis ist.</span><span class="sxs-lookup"><span data-stu-id="5583f-130">True if the stream is a directory, false otherwise.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListDirectory">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IDictionary&lt;string,long&gt; ListDirectory (string directoryPath, bool recursive);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Collections.Generic.IDictionary`2&lt;string, int64&gt; ListDirectory(string directoryPath, bool recursive) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Store.IFrontEndAdapter.ListDirectory(System.String,System.Boolean)" />
      <MemberSignature Language="VB.NET" Value="Public Function ListDirectory (directoryPath As String, recursive As Boolean) As IDictionary(Of String, Long)" />
      <MemberSignature Language="F#" Value="abstract member ListDirectory : string * bool -&gt; System.Collections.Generic.IDictionary&lt;string, int64&gt;" Usage="iFrontEndAdapter.ListDirectory (directoryPath, recursive)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Store</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IDictionary&lt;System.String,System.Int64&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="directoryPath" Type="System.String" />
        <Parameter Name="recursive" Type="System.Boolean" />
      </Parameters>
      <Docs>
        <param name="directoryPath"><span data-ttu-id="5583f-131">Der Verzeichnispfad.</span><span class="sxs-lookup"><span data-stu-id="5583f-131">The directory path.</span></span></param>
        <param name="recursive"><span data-ttu-id="5583f-132">Wenn auf festgelegt <c>"true"</c> [rekursive].</span><span class="sxs-lookup"><span data-stu-id="5583f-132">if set to <c>true</c> [recursive].</span></span></param>
        <summary>
            <span data-ttu-id="5583f-133">Führt das angegebene Data Lake-Speicher-Verzeichnis.</span><span class="sxs-lookup"><span data-stu-id="5583f-133">Lists the Data Lake Store directory specified.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="5583f-134">Die Liste der Zeichenfolge Pfade und die entsprechenden Dateigröße in Bytes.</span><span class="sxs-lookup"><span data-stu-id="5583f-134">The list of string paths and their corresponding file sizes, in bytes.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ReadStream">
      <MemberSignature Language="C#" Value="public System.IO.Stream ReadStream (string streamPath, long offset, long length, bool isDownload = false);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.IO.Stream ReadStream(string streamPath, int64 offset, int64 length, bool isDownload) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Store.IFrontEndAdapter.ReadStream(System.String,System.Int64,System.Int64,System.Boolean)" />
      <MemberSignature Language="VB.NET" Value="Public Function ReadStream (streamPath As String, offset As Long, length As Long, Optional isDownload As Boolean = false) As Stream" />
      <MemberSignature Language="F#" Value="abstract member ReadStream : string * int64 * int64 * bool -&gt; System.IO.Stream" Usage="iFrontEndAdapter.ReadStream (streamPath, offset, length, isDownload)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Store</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.IO.Stream</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="streamPath" Type="System.String" />
        <Parameter Name="offset" Type="System.Int64" />
        <Parameter Name="length" Type="System.Int64" />
        <Parameter Name="isDownload" Type="System.Boolean" />
      </Parameters>
      <Docs>
        <param name="streamPath"><span data-ttu-id="5583f-135">Der relative Pfad in den Stream.</span><span class="sxs-lookup"><span data-stu-id="5583f-135">The relative path to the stream.</span></span></param>
        <param name="offset"><span data-ttu-id="5583f-136">Der Offset, bei dem in den Stream angefügt werden soll.</span><span class="sxs-lookup"><span data-stu-id="5583f-136">The offset at which to append to the stream.</span></span></param>
        <param name="length"><span data-ttu-id="5583f-137">Die Anzahl der Bytes, die angefügt werden soll (beginnend mit 0).</span><span class="sxs-lookup"><span data-stu-id="5583f-137">The number of bytes to append (starting at 0).</span></span></param>
        <param name="isDownload"><span data-ttu-id="5583f-138">Wenn auf festgelegt <c>"true"</c> [ist Download], d. h., es wird einen Datenstrom, auf dem Server zum Auslesen, anstatt den lokalen Computer geöffnet.</span><span class="sxs-lookup"><span data-stu-id="5583f-138">if set to <c>true</c> [is download], meaning we will open a stream on the server to read from, instead of the local machine.</span></span></param>
        <summary>
            <span data-ttu-id="5583f-139">Öffnet einen Datenstrom zu lesen, die Angabe des Pfads der Proxyport stream</span><span class="sxs-lookup"><span data-stu-id="5583f-139">Opens a stream for reading given the speficied stream path</span></span>
            </summary>
        <returns />
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentNullException"><span data-ttu-id="5583f-140">Wenn die Daten an, die angefügt werden, null oder leer ist.</span><span class="sxs-lookup"><span data-stu-id="5583f-140">If the data to be appended is null or empty.</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName="StreamExists">
      <MemberSignature Language="C#" Value="public bool StreamExists (string streamPath, bool isDownload = false);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance bool StreamExists(string streamPath, bool isDownload) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Store.IFrontEndAdapter.StreamExists(System.String,System.Boolean)" />
      <MemberSignature Language="VB.NET" Value="Public Function StreamExists (streamPath As String, Optional isDownload As Boolean = false) As Boolean" />
      <MemberSignature Language="F#" Value="abstract member StreamExists : string * bool -&gt; bool" Usage="iFrontEndAdapter.StreamExists (streamPath, isDownload)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Store</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="streamPath" Type="System.String" />
        <Parameter Name="isDownload" Type="System.Boolean" />
      </Parameters>
      <Docs>
        <param name="streamPath"><span data-ttu-id="5583f-141">Der relative Pfad in den Stream.</span><span class="sxs-lookup"><span data-stu-id="5583f-141">The relative path to the stream.</span></span></param>
        <param name="isDownload"><span data-ttu-id="5583f-142">Wenn auf festgelegt <c>"true"</c> [ist Download], d. h., es testen, wenn der Datenstrom auf dem lokalen Computer statt auf dem Server vorhanden ist.</span><span class="sxs-lookup"><span data-stu-id="5583f-142">if set to <c>true</c> [is download], meaning we will test if the stream exists on the local machine instead of on the server.</span></span></param>
        <summary>
            <span data-ttu-id="5583f-143">Bestimmt, ob der Stream mit dem angegebenen Pfad vorhanden.</span><span class="sxs-lookup"><span data-stu-id="5583f-143">Determines if the stream with given path exists.</span></span>
            </summary>
        <returns><span data-ttu-id="5583f-144">"True", wenn der Stream "false" vorhanden, andernfalls ist.</span><span class="sxs-lookup"><span data-stu-id="5583f-144">True if the stream exists, false otherwise.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>