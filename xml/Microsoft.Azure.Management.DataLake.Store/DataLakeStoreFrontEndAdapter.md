<Type Name="DataLakeStoreFrontEndAdapter" FullName="Microsoft.Azure.Management.DataLake.Store.DataLakeStoreFrontEndAdapter">
  <TypeSignature Language="C#" Value="public class DataLakeStoreFrontEndAdapter : Microsoft.Azure.Management.DataLake.Store.IFrontEndAdapter" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit DataLakeStoreFrontEndAdapter extends System.Object implements class Microsoft.Azure.Management.DataLake.Store.IFrontEndAdapter" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.DataLake.Store.DataLakeStoreFrontEndAdapter" />
  <TypeSignature Language="VB.NET" Value="Public Class DataLakeStoreFrontEndAdapter&#xA;Implements IFrontEndAdapter" />
  <TypeSignature Language="F#" Value="type DataLakeStoreFrontEndAdapter = class&#xA;    interface IFrontEndAdapter" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.DataLake.Store</AssemblyName>
    <AssemblyVersion>2.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.DataLake.Store.IFrontEndAdapter</InterfaceName>
    </Interface>
  </Interfaces>
  <Docs>
    <summary>
            <span data-ttu-id="cadf9-101">Ein front-End-Adapter, der mit dem Store DataLake kommuniziert.</span><span class="sxs-lookup"><span data-stu-id="cadf9-101">A front end adapter that communicates with the DataLake Store.</span></span>
            <span data-ttu-id="cadf9-102">Dies ist eines Syncrhonous-Aufruf-Adapters mit bestimmten Einschränkungen Effizienz.</span><span class="sxs-lookup"><span data-stu-id="cadf9-102">This is a syncrhonous call adapter, which has certain efficiency limitations.</span></span>
            <span data-ttu-id="cadf9-103">In der Zukunft sollten neue Adapter, die erstellt werden das Implementieren der Methoden asynchron.</span><span class="sxs-lookup"><span data-stu-id="cadf9-103">In the future, new adapters that are created should consider implementing the methods asynchronously.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public DataLakeStoreFrontEndAdapter (string accountName, Microsoft.Azure.Management.DataLake.Store.IDataLakeStoreFileSystemManagementClient client);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string accountName, class Microsoft.Azure.Management.DataLake.Store.IDataLakeStoreFileSystemManagementClient client) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Store.DataLakeStoreFrontEndAdapter.#ctor(System.String,Microsoft.Azure.Management.DataLake.Store.IDataLakeStoreFileSystemManagementClient)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (accountName As String, client As IDataLakeStoreFileSystemManagementClient)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.DataLake.Store.DataLakeStoreFrontEndAdapter : string * Microsoft.Azure.Management.DataLake.Store.IDataLakeStoreFileSystemManagementClient -&gt; Microsoft.Azure.Management.DataLake.Store.DataLakeStoreFrontEndAdapter" Usage="new Microsoft.Azure.Management.DataLake.Store.DataLakeStoreFrontEndAdapter (accountName, client)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Store</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="client" Type="Microsoft.Azure.Management.DataLake.Store.IDataLakeStoreFileSystemManagementClient" />
      </Parameters>
      <Docs>
        <param name="accountName"><span data-ttu-id="cadf9-104">Der Name des Kontos.</span><span class="sxs-lookup"><span data-stu-id="cadf9-104">Name of the account.</span></span></param>
        <param name="client"><span data-ttu-id="cadf9-105">Der Client.</span><span class="sxs-lookup"><span data-stu-id="cadf9-105">The client.</span></span></param>
        <summary>
            <span data-ttu-id="cadf9-106">Initialisiert eine neue Instanz der <see cref="T:Microsoft.Azure.Management.DataLake.Store.DataLakeStoreFrontEndAdapter" />-Klasse.</span><span class="sxs-lookup"><span data-stu-id="cadf9-106">Initializes a new instance of the <see cref="T:Microsoft.Azure.Management.DataLake.Store.DataLakeStoreFrontEndAdapter" /> class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public DataLakeStoreFrontEndAdapter (string accountName, Microsoft.Azure.Management.DataLake.Store.IDataLakeStoreFileSystemManagementClient client, System.Threading.CancellationToken token);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string accountName, class Microsoft.Azure.Management.DataLake.Store.IDataLakeStoreFileSystemManagementClient client, valuetype System.Threading.CancellationToken token) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Store.DataLakeStoreFrontEndAdapter.#ctor(System.String,Microsoft.Azure.Management.DataLake.Store.IDataLakeStoreFileSystemManagementClient,System.Threading.CancellationToken)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (accountName As String, client As IDataLakeStoreFileSystemManagementClient, token As CancellationToken)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.DataLake.Store.DataLakeStoreFrontEndAdapter : string * Microsoft.Azure.Management.DataLake.Store.IDataLakeStoreFileSystemManagementClient * System.Threading.CancellationToken -&gt; Microsoft.Azure.Management.DataLake.Store.DataLakeStoreFrontEndAdapter" Usage="new Microsoft.Azure.Management.DataLake.Store.DataLakeStoreFrontEndAdapter (accountName, client, token)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Store</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="client" Type="Microsoft.Azure.Management.DataLake.Store.IDataLakeStoreFileSystemManagementClient" />
        <Parameter Name="token" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="accountName"><span data-ttu-id="cadf9-107">Der Name des Kontos.</span><span class="sxs-lookup"><span data-stu-id="cadf9-107">Name of the account.</span></span></param>
        <param name="client"><span data-ttu-id="cadf9-108">Der Client.</span><span class="sxs-lookup"><span data-stu-id="cadf9-108">The client.</span></span></param>
        <param name="token"><span data-ttu-id="cadf9-109">Das Token.</span><span class="sxs-lookup"><span data-stu-id="cadf9-109">The token.</span></span></param>
        <summary>
            <span data-ttu-id="cadf9-110">Initialisiert eine neue Instanz der <see cref="T:Microsoft.Azure.Management.DataLake.Store.DataLakeStoreFrontEndAdapter" />-Klasse.</span><span class="sxs-lookup"><span data-stu-id="cadf9-110">Initializes a new instance of the <see cref="T:Microsoft.Azure.Management.DataLake.Store.DataLakeStoreFrontEndAdapter" /> class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AppendToStream">
      <MemberSignature Language="C#" Value="public void AppendToStream (string streamPath, byte[] data, long offset, int byteCount);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void AppendToStream(string streamPath, unsigned int8[] data, int64 offset, int32 byteCount) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Store.DataLakeStoreFrontEndAdapter.AppendToStream(System.String,System.Byte[],System.Int64,System.Int32)" />
      <MemberSignature Language="VB.NET" Value="Public Sub AppendToStream (streamPath As String, data As Byte(), offset As Long, byteCount As Integer)" />
      <MemberSignature Language="F#" Value="abstract member AppendToStream : string * byte[] * int64 * int -&gt; unit&#xA;override this.AppendToStream : string * byte[] * int64 * int -&gt; unit" Usage="dataLakeStoreFrontEndAdapter.AppendToStream (streamPath, data, offset, byteCount)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.Azure.Management.DataLake.Store.IFrontEndAdapter.AppendToStream(System.String,System.Byte[],System.Int64,System.Int32)</InterfaceMember>
      </Implements>
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
        <Parameter Name="byteCount" Type="System.Int32" />
      </Parameters>
      <Docs>
        <param name="streamPath"><span data-ttu-id="cadf9-111">Der Stream-Pfad.</span><span class="sxs-lookup"><span data-stu-id="cadf9-111">The stream path.</span></span></param>
        <param name="data"><span data-ttu-id="cadf9-112">Die Daten.</span><span class="sxs-lookup"><span data-stu-id="cadf9-112">The data.</span></span></param>
        <param name="offset"><span data-ttu-id="cadf9-113">Der Offset.</span><span class="sxs-lookup"><span data-stu-id="cadf9-113">The offset.</span></span></param>
        <param name="byteCount"><span data-ttu-id="cadf9-114">Die Anzahl von Bytes.</span><span class="sxs-lookup"><span data-stu-id="cadf9-114">The byte count.</span></span></param>
        <summary>
            <span data-ttu-id="cadf9-115">Fügt an den Stream.</span><span class="sxs-lookup"><span data-stu-id="cadf9-115">Appends to stream.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:System.Threading.Tasks.TaskCanceledException" />
      </Docs>
    </Member>
    <Member MemberName="Concatenate">
      <MemberSignature Language="C#" Value="public void Concatenate (string targetStreamPath, string[] inputStreamPaths, bool isDownload = false);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Concatenate(string targetStreamPath, string[] inputStreamPaths, bool isDownload) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Store.DataLakeStoreFrontEndAdapter.Concatenate(System.String,System.String[],System.Boolean)" />
      <MemberSignature Language="VB.NET" Value="Public Sub Concatenate (targetStreamPath As String, inputStreamPaths As String(), Optional isDownload As Boolean = false)" />
      <MemberSignature Language="F#" Value="abstract member Concatenate : string * string[] * bool -&gt; unit&#xA;override this.Concatenate : string * string[] * bool -&gt; unit" Usage="dataLakeStoreFrontEndAdapter.Concatenate (targetStreamPath, inputStreamPaths, isDownload)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.Azure.Management.DataLake.Store.IFrontEndAdapter.Concatenate(System.String,System.String[],System.Boolean)</InterfaceMember>
      </Implements>
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
        <param name="targetStreamPath"><span data-ttu-id="cadf9-116">Der relative Pfad auf den Zieldatenstrom.</span><span class="sxs-lookup"><span data-stu-id="cadf9-116">The relative path to the target stream.</span></span></param>
        <param name="inputStreamPaths"><span data-ttu-id="cadf9-117">Ein geordnetes Array von Pfaden, die der Eingabestreams.</span><span class="sxs-lookup"><span data-stu-id="cadf9-117">An ordered array of paths to the input streams.</span></span></param>
        <param name="isDownload"><span data-ttu-id="cadf9-118">Wenn auf festgelegt <c>"true"</c> [ist Download], d. h., es wird die Datenströme auf dem lokalen Computer statt auf dem Server verketten.</span><span class="sxs-lookup"><span data-stu-id="cadf9-118">if set to <c>true</c> [is download], meaning we will concatenate the streams on the local machine instead of on the server.</span></span></param>
        <summary>
            <span data-ttu-id="cadf9-119">Verkettet die angegebenen Eingabedatenströme (nacheinander) in den angegebenen Zieltyp Stream an.</span><span class="sxs-lookup"><span data-stu-id="cadf9-119">Concatenates the given input streams (in order) into the given target stream.</span></span>
            <span data-ttu-id="cadf9-120">Am Ende dieses Vorgangs werden der Eingabestreams gelöscht werden.</span><span class="sxs-lookup"><span data-stu-id="cadf9-120">At the end of this operation, input streams will be deleted.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:System.Threading.Tasks.TaskCanceledException" />
      </Docs>
    </Member>
    <Member MemberName="CreateStream">
      <MemberSignature Language="C#" Value="public void CreateStream (string streamPath, bool overwrite, byte[] data, int byteCount);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void CreateStream(string streamPath, bool overwrite, unsigned int8[] data, int32 byteCount) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Store.DataLakeStoreFrontEndAdapter.CreateStream(System.String,System.Boolean,System.Byte[],System.Int32)" />
      <MemberSignature Language="VB.NET" Value="Public Sub CreateStream (streamPath As String, overwrite As Boolean, data As Byte(), byteCount As Integer)" />
      <MemberSignature Language="F#" Value="abstract member CreateStream : string * bool * byte[] * int -&gt; unit&#xA;override this.CreateStream : string * bool * byte[] * int -&gt; unit" Usage="dataLakeStoreFrontEndAdapter.CreateStream (streamPath, overwrite, data, byteCount)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.Azure.Management.DataLake.Store.IFrontEndAdapter.CreateStream(System.String,System.Boolean,System.Byte[],System.Int32)</InterfaceMember>
      </Implements>
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
        <param name="streamPath"><span data-ttu-id="cadf9-121">Der relative Pfad in den Stream.</span><span class="sxs-lookup"><span data-stu-id="cadf9-121">The relative path to the stream.</span></span></param>
        <param name="overwrite"><span data-ttu-id="cadf9-122">Ob überschreiben einen vorhandenen Datenstrom.</span><span class="sxs-lookup"><span data-stu-id="cadf9-122">Whether to overwrite an existing stream.</span></span></param>
        <param name="data"><span data-ttu-id="cadf9-123">Die Daten.</span><span class="sxs-lookup"><span data-stu-id="cadf9-123">The data.</span></span></param>
        <param name="byteCount"><span data-ttu-id="cadf9-124">Die Anzahl von Bytes.</span><span class="sxs-lookup"><span data-stu-id="cadf9-124">The byte count.</span></span></param>
        <summary>
            <span data-ttu-id="cadf9-125">Erstellt einen neuen, leeren Datenstrom im angegebenen Pfad.</span><span class="sxs-lookup"><span data-stu-id="cadf9-125">Creates a new, empty stream at the given path.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:System.Threading.Tasks.TaskCanceledException" />
      </Docs>
    </Member>
    <Member MemberName="DeleteStream">
      <MemberSignature Language="C#" Value="public void DeleteStream (string streamPath, bool recurse = false, bool isDownload = false);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void DeleteStream(string streamPath, bool recurse, bool isDownload) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Store.DataLakeStoreFrontEndAdapter.DeleteStream(System.String,System.Boolean,System.Boolean)" />
      <MemberSignature Language="VB.NET" Value="Public Sub DeleteStream (streamPath As String, Optional recurse As Boolean = false, Optional isDownload As Boolean = false)" />
      <MemberSignature Language="F#" Value="abstract member DeleteStream : string * bool * bool -&gt; unit&#xA;override this.DeleteStream : string * bool * bool -&gt; unit" Usage="dataLakeStoreFrontEndAdapter.DeleteStream (streamPath, recurse, isDownload)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.Azure.Management.DataLake.Store.IFrontEndAdapter.DeleteStream(System.String,System.Boolean,System.Boolean)</InterfaceMember>
      </Implements>
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
        <param name="streamPath"><span data-ttu-id="cadf9-126">Der relative Pfad in den Stream.</span><span class="sxs-lookup"><span data-stu-id="cadf9-126">The relative path to the stream.</span></span></param>
        <param name="recurse"><span data-ttu-id="cadf9-127">Wenn auf festgelegt <c>"true"</c> [Recurse].</span><span class="sxs-lookup"><span data-stu-id="cadf9-127">if set to <c>true</c> [recurse].</span></span> <span data-ttu-id="cadf9-128">Dies wird für nur die Ordner-Streams verwendet.</span><span class="sxs-lookup"><span data-stu-id="cadf9-128">This is used for folder streams only.</span></span></param>
        <param name="isDownload"><span data-ttu-id="cadf9-129">Wenn auf festgelegt <c>"true"</c> [ist Download], d. h., es wird einen Datenstrom, auf dem lokalen Computer statt auf dem Server gelöscht.</span><span class="sxs-lookup"><span data-stu-id="cadf9-129">if set to <c>true</c> [is download], meaning we will delete a stream on the local machine instead of on the server.</span></span></param>
        <summary>
            <span data-ttu-id="cadf9-130">Löscht einen vorhandenen Datenstrom im angegebenen Pfad.</span><span class="sxs-lookup"><span data-stu-id="cadf9-130">Deletes an existing stream at the given path.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:System.Threading.Tasks.TaskCanceledException" />
      </Docs>
    </Member>
    <Member MemberName="GetStreamLength">
      <MemberSignature Language="C#" Value="public long GetStreamLength (string streamPath, bool isDownload = false);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance int64 GetStreamLength(string streamPath, bool isDownload) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Store.DataLakeStoreFrontEndAdapter.GetStreamLength(System.String,System.Boolean)" />
      <MemberSignature Language="VB.NET" Value="Public Function GetStreamLength (streamPath As String, Optional isDownload As Boolean = false) As Long" />
      <MemberSignature Language="F#" Value="abstract member GetStreamLength : string * bool -&gt; int64&#xA;override this.GetStreamLength : string * bool -&gt; int64" Usage="dataLakeStoreFrontEndAdapter.GetStreamLength (streamPath, isDownload)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.Azure.Management.DataLake.Store.IFrontEndAdapter.GetStreamLength(System.String,System.Boolean)</InterfaceMember>
      </Implements>
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
        <param name="streamPath"><span data-ttu-id="cadf9-131">Der relative Pfad in den Stream.</span><span class="sxs-lookup"><span data-stu-id="cadf9-131">The relative path to the stream.</span></span></param>
        <param name="isDownload"><span data-ttu-id="cadf9-132">Wenn auf festgelegt <c>"true"</c> [ist Download], d. h., es wird die Länge des Streams abrufen, auf dem lokalen Computer statt auf dem Server.</span><span class="sxs-lookup"><span data-stu-id="cadf9-132">if set to <c>true</c> [is download], meaning we will get the stream length on the local machine instead of on the server.</span></span></param>
        <summary>
            <span data-ttu-id="cadf9-133">Ruft einen Wert, der angibt, der Länge des Streams in Bytes ab.</span><span class="sxs-lookup"><span data-stu-id="cadf9-133">Gets a value indicating the length of a stream, in bytes.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="cadf9-134">Die Länge des Streams in Bytes.</span><span class="sxs-lookup"><span data-stu-id="cadf9-134">The length of the stream, in bytes.</span></span>
            </returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.Threading.Tasks.TaskCanceledException" />
      </Docs>
    </Member>
    <Member MemberName="IsDirectory">
      <MemberSignature Language="C#" Value="public bool IsDirectory (string streamPath);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance bool IsDirectory(string streamPath) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Store.DataLakeStoreFrontEndAdapter.IsDirectory(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function IsDirectory (streamPath As String) As Boolean" />
      <MemberSignature Language="F#" Value="abstract member IsDirectory : string -&gt; bool&#xA;override this.IsDirectory : string -&gt; bool" Usage="dataLakeStoreFrontEndAdapter.IsDirectory streamPath" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.Azure.Management.DataLake.Store.IFrontEndAdapter.IsDirectory(System.String)</InterfaceMember>
      </Implements>
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
        <param name="streamPath"><span data-ttu-id="cadf9-135">Der relative Pfad in den Stream.</span><span class="sxs-lookup"><span data-stu-id="cadf9-135">The relative path to the stream.</span></span></param>
        <summary>
            <span data-ttu-id="cadf9-136">Bestimmt, ob der Stream mit angegebenen Pfad auf dem Server ein Verzeichnis oder eine abschließende Datei ist.</span><span class="sxs-lookup"><span data-stu-id="cadf9-136">Determines if the stream with given path on the server is a directory or a terminating file.</span></span>
            <span data-ttu-id="cadf9-137">Dies wird ausschließlich für den Download verwendet.</span><span class="sxs-lookup"><span data-stu-id="cadf9-137">This is used exclusively for download.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="cadf9-138">"True", wenn der Stream andernfalls "false" ein Verzeichnis ist.</span><span class="sxs-lookup"><span data-stu-id="cadf9-138">True if the stream is a directory, false otherwise.</span></span>
            </returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.Threading.Tasks.TaskCanceledException" />
      </Docs>
    </Member>
    <Member MemberName="ListDirectory">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IDictionary&lt;string,long&gt; ListDirectory (string directoryPath, bool recursive);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Collections.Generic.IDictionary`2&lt;string, int64&gt; ListDirectory(string directoryPath, bool recursive) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Store.DataLakeStoreFrontEndAdapter.ListDirectory(System.String,System.Boolean)" />
      <MemberSignature Language="VB.NET" Value="Public Function ListDirectory (directoryPath As String, recursive As Boolean) As IDictionary(Of String, Long)" />
      <MemberSignature Language="F#" Value="abstract member ListDirectory : string * bool -&gt; System.Collections.Generic.IDictionary&lt;string, int64&gt;&#xA;override this.ListDirectory : string * bool -&gt; System.Collections.Generic.IDictionary&lt;string, int64&gt;" Usage="dataLakeStoreFrontEndAdapter.ListDirectory (directoryPath, recursive)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.Azure.Management.DataLake.Store.IFrontEndAdapter.ListDirectory(System.String,System.Boolean)</InterfaceMember>
      </Implements>
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
        <param name="directoryPath"><span data-ttu-id="cadf9-139">Der Verzeichnispfad.</span><span class="sxs-lookup"><span data-stu-id="cadf9-139">The directory path.</span></span></param>
        <param name="recursive"><span data-ttu-id="cadf9-140">Wenn auf festgelegt <c>"true"</c> [rekursive].</span><span class="sxs-lookup"><span data-stu-id="cadf9-140">if set to <c>true</c> [recursive].</span></span></param>
        <summary>
            <span data-ttu-id="cadf9-141">Führt das angegebene Data Lake-Speicher-Verzeichnis.</span><span class="sxs-lookup"><span data-stu-id="cadf9-141">Lists the Data Lake Store directory specified.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="cadf9-142">Die Liste der Zeichenfolge Pfade und die entsprechenden Dateigröße in Bytes.</span><span class="sxs-lookup"><span data-stu-id="cadf9-142">The list of string paths and their corresponding file sizes, in bytes.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ReadStream">
      <MemberSignature Language="C#" Value="public System.IO.Stream ReadStream (string streamPath, long offset, long length, bool isDownload = false);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.IO.Stream ReadStream(string streamPath, int64 offset, int64 length, bool isDownload) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Store.DataLakeStoreFrontEndAdapter.ReadStream(System.String,System.Int64,System.Int64,System.Boolean)" />
      <MemberSignature Language="VB.NET" Value="Public Function ReadStream (streamPath As String, offset As Long, length As Long, Optional isDownload As Boolean = false) As Stream" />
      <MemberSignature Language="F#" Value="abstract member ReadStream : string * int64 * int64 * bool -&gt; System.IO.Stream&#xA;override this.ReadStream : string * int64 * int64 * bool -&gt; System.IO.Stream" Usage="dataLakeStoreFrontEndAdapter.ReadStream (streamPath, offset, length, isDownload)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.Azure.Management.DataLake.Store.IFrontEndAdapter.ReadStream(System.String,System.Int64,System.Int64,System.Boolean)</InterfaceMember>
      </Implements>
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
        <param name="streamPath">To be added.</param>
        <param name="offset">To be added.</param>
        <param name="length">To be added.</param>
        <param name="isDownload">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="StreamExists">
      <MemberSignature Language="C#" Value="public bool StreamExists (string streamPath, bool isDownload = false);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance bool StreamExists(string streamPath, bool isDownload) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Store.DataLakeStoreFrontEndAdapter.StreamExists(System.String,System.Boolean)" />
      <MemberSignature Language="VB.NET" Value="Public Function StreamExists (streamPath As String, Optional isDownload As Boolean = false) As Boolean" />
      <MemberSignature Language="F#" Value="abstract member StreamExists : string * bool -&gt; bool&#xA;override this.StreamExists : string * bool -&gt; bool" Usage="dataLakeStoreFrontEndAdapter.StreamExists (streamPath, isDownload)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.Azure.Management.DataLake.Store.IFrontEndAdapter.StreamExists(System.String,System.Boolean)</InterfaceMember>
      </Implements>
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
        <param name="streamPath"><span data-ttu-id="cadf9-143">Der relative Pfad in den Stream.</span><span class="sxs-lookup"><span data-stu-id="cadf9-143">The relative path to the stream.</span></span></param>
        <param name="isDownload"><span data-ttu-id="cadf9-144">Wenn auf festgelegt <c>"true"</c> [ist Download], d. h., es testen, wenn der Datenstrom auf dem lokalen Computer statt auf dem Server vorhanden ist.</span><span class="sxs-lookup"><span data-stu-id="cadf9-144">if set to <c>true</c> [is download], meaning we will test if the stream exists on the local machine instead of on the server.</span></span></param>
        <summary>
            <span data-ttu-id="cadf9-145">Bestimmt, ob der Stream mit dem angegebenen Pfad vorhanden.</span><span class="sxs-lookup"><span data-stu-id="cadf9-145">Determines if the stream with given path exists.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="cadf9-146">"True", wenn der Stream "false" vorhanden, andernfalls ist.</span><span class="sxs-lookup"><span data-stu-id="cadf9-146">True if the stream exists, false otherwise.</span></span>
            </returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.Threading.Tasks.TaskCanceledException" />
      </Docs>
    </Member>
  </Members>
</Type>