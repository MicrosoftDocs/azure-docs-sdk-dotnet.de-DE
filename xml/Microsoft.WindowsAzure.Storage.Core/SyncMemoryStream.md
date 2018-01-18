<Type Name="SyncMemoryStream" FullName="Microsoft.WindowsAzure.Storage.Core.SyncMemoryStream">
  <TypeSignature Language="C#" Value="public class SyncMemoryStream : System.IO.MemoryStream" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit SyncMemoryStream extends System.IO.MemoryStream" />
  <TypeSignature Language="DocId" Value="T:Microsoft.WindowsAzure.Storage.Core.SyncMemoryStream" />
  <TypeSignature Language="VB.NET" Value="Public Class SyncMemoryStream&#xA;Inherits MemoryStream" />
  <TypeSignature Language="F#" Value="type SyncMemoryStream = class&#xA;    inherit MemoryStream" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
    <AssemblyVersion>8.4.0.0</AssemblyVersion>
    <AssemblyVersion>8.7.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.IO.MemoryStream</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="a2c1a-101">Diese Klasse bietet Außerkraftsetzungen von APM-Lese-/Schreibzugriff für Speicherstream zur Verbesserung der Leistung.</span><span class="sxs-lookup"><span data-stu-id="a2c1a-101">This class provides APM Read/Write overrides for memory stream to improve performance.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public SyncMemoryStream ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Core.SyncMemoryStream.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="a2c1a-102">Initialisiert eine neue Instanz der Klasse SyncMemoryStream mit einer erweiterbaren Kapazität, die mit 0 (null) initialisiert.</span><span class="sxs-lookup"><span data-stu-id="a2c1a-102">Initializes a new instance of the SyncMemoryStream class with an expandable capacity initialized to zero.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public SyncMemoryStream (byte[] buffer);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(unsigned int8[] buffer) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Core.SyncMemoryStream.#ctor(System.Byte[])" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (buffer As Byte())" />
      <MemberSignature Language="F#" Value="new Microsoft.WindowsAzure.Storage.Core.SyncMemoryStream : byte[] -&gt; Microsoft.WindowsAzure.Storage.Core.SyncMemoryStream" Usage="new Microsoft.WindowsAzure.Storage.Core.SyncMemoryStream buffer" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="buffer" Type="System.Byte[]" />
      </Parameters>
      <Docs>
        <param name="buffer"><span data-ttu-id="a2c1a-103">Das Array vorzeichenloser Bytes, aus dem der aktuelle Stream erstellt werden soll.</span><span class="sxs-lookup"><span data-stu-id="a2c1a-103">The array of unsigned bytes from which to create the current stream.</span></span></param>
        <summary>
            <span data-ttu-id="a2c1a-104">Initialisiert eine neue, nicht veränderbare Größen Instanz der Klasse SyncMemoryStream basierend auf dem angegebenen Bytearray.</span><span class="sxs-lookup"><span data-stu-id="a2c1a-104">Initializes a new non-resizable instance of the SyncMemoryStream class based on the specified byte array.</span></span> 
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public SyncMemoryStream (byte[] buffer, int index);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(unsigned int8[] buffer, int32 index) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Core.SyncMemoryStream.#ctor(System.Byte[],System.Int32)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (buffer As Byte(), index As Integer)" />
      <MemberSignature Language="F#" Value="new Microsoft.WindowsAzure.Storage.Core.SyncMemoryStream : byte[] * int -&gt; Microsoft.WindowsAzure.Storage.Core.SyncMemoryStream" Usage="new Microsoft.WindowsAzure.Storage.Core.SyncMemoryStream (buffer, index)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="buffer" Type="System.Byte[]" />
        <Parameter Name="index" Type="System.Int32" />
      </Parameters>
      <Docs>
        <param name="buffer"><span data-ttu-id="a2c1a-105">Das Array vorzeichenloser Bytes, aus dem der aktuelle Stream erstellt werden soll.</span><span class="sxs-lookup"><span data-stu-id="a2c1a-105">The array of unsigned bytes from which to create the current stream.</span></span></param>
        <param name="index"><span data-ttu-id="a2c1a-106">Der Index in Puffer, an dem der Stream beginnt.</span><span class="sxs-lookup"><span data-stu-id="a2c1a-106">The index into buffer at which the stream begins.</span></span></param>
        <summary>
            <span data-ttu-id="a2c1a-107">Initialisiert eine neue nicht veränderbare Größen Instanz der Klasse SyncMemoryStream anhand des angegebenen Bereichs (Indexes) eines Bytearrays.</span><span class="sxs-lookup"><span data-stu-id="a2c1a-107">Initializes a new non-resizable instance of the SyncMemoryStream class based on the specified region (index) of a byte array.</span></span> 
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public SyncMemoryStream (byte[] buffer, int index, int count);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(unsigned int8[] buffer, int32 index, int32 count) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Core.SyncMemoryStream.#ctor(System.Byte[],System.Int32,System.Int32)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (buffer As Byte(), index As Integer, count As Integer)" />
      <MemberSignature Language="F#" Value="new Microsoft.WindowsAzure.Storage.Core.SyncMemoryStream : byte[] * int * int -&gt; Microsoft.WindowsAzure.Storage.Core.SyncMemoryStream" Usage="new Microsoft.WindowsAzure.Storage.Core.SyncMemoryStream (buffer, index, count)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="buffer" Type="System.Byte[]" />
        <Parameter Name="index" Type="System.Int32" />
        <Parameter Name="count" Type="System.Int32" />
      </Parameters>
      <Docs>
        <param name="buffer"><span data-ttu-id="a2c1a-108">Das Array vorzeichenloser Bytes, aus dem der aktuelle Stream erstellt werden soll.</span><span class="sxs-lookup"><span data-stu-id="a2c1a-108">The array of unsigned bytes from which to create the current stream.</span></span></param>
        <param name="index"><span data-ttu-id="a2c1a-109">Der Index in Puffer, an dem der Stream beginnt.</span><span class="sxs-lookup"><span data-stu-id="a2c1a-109">The index into buffer at which the stream begins.</span></span></param>
        <param name="count"><span data-ttu-id="a2c1a-110">Die Länge des Streams in Bytes.</span><span class="sxs-lookup"><span data-stu-id="a2c1a-110">The length of the stream in bytes.</span></span></param>
        <summary>
            <span data-ttu-id="a2c1a-111">Initialisiert eine neue nicht veränderbare Größen Instanz der Klasse SyncMemoryStream anhand des angegebenen Bereichs (Indexes) eines Bytearrays.</span><span class="sxs-lookup"><span data-stu-id="a2c1a-111">Initializes a new non-resizable instance of the SyncMemoryStream class based on the specified region (index) of a byte array.</span></span> 
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginRead">
      <MemberSignature Language="C#" Value="public override IAsyncResult BeginRead (byte[] buffer, int offset, int count, AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance class System.IAsyncResult BeginRead(unsigned int8[] buffer, int32 offset, int32 count, class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Core.SyncMemoryStream.BeginRead(System.Byte[],System.Int32,System.Int32,System.AsyncCallback,System.Object)" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function BeginRead (buffer As Byte(), offset As Integer, count As Integer, callback As AsyncCallback, state As Object) As IAsyncResult" />
      <MemberSignature Language="F#" Value="override this.BeginRead : byte[] * int * int * AsyncCallback * obj -&gt; IAsyncResult" Usage="syncMemoryStream.BeginRead (buffer, offset, count, callback, state)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.IAsyncResult</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="buffer" Type="System.Byte[]" />
        <Parameter Name="offset" Type="System.Int32" />
        <Parameter Name="count" Type="System.Int32" />
        <Parameter Name="callback" Type="System.AsyncCallback" />
        <Parameter Name="state" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="buffer"><span data-ttu-id="a2c1a-112">Nach dem Beenden dieser Methode enthält der Puffer das angegebene Bytearray mit den Werten zwischen Offset und (Offset + Zähler - 1), die durch aus der aktuellen Quelle gelesene Bytes ersetzt wurden.</span><span class="sxs-lookup"><span data-stu-id="a2c1a-112">When this method returns, the buffer contains the specified byte array with the values between offset and (offset + count - 1) replaced by the bytes read from the current source.</span></span></param>
        <param name="offset"><span data-ttu-id="a2c1a-113">Der nullbasierte Byteoffset im Puffer, ab dem die aus dem aktuellen Stream gelesenen Daten gespeichert werden.</span><span class="sxs-lookup"><span data-stu-id="a2c1a-113">The zero-based byte offset in buffer at which to begin storing the data read from the current stream.</span></span></param>
        <param name="count"><span data-ttu-id="a2c1a-114">Die maximale Anzahl der zu lesenden Bytes.</span><span class="sxs-lookup"><span data-stu-id="a2c1a-114">The maximum number of bytes to be read.</span></span></param>
        <param name="callback"><span data-ttu-id="a2c1a-115">Ein optionaler asynchroner Rückruf, der nach Abschluss des Lesevorgangs aufgerufen werden soll.</span><span class="sxs-lookup"><span data-stu-id="a2c1a-115">An optional asynchronous callback, to be called when the read is complete.</span></span></param>
        <param name="state"><span data-ttu-id="a2c1a-116">Ein vom Benutzer bereitgestelltes Objekt, das diese asynchrone Leseanforderung von anderen Anforderungen unterscheidet.</span><span class="sxs-lookup"><span data-stu-id="a2c1a-116">A user-provided object that distinguishes this particular asynchronous read request from other requests.</span></span></param>
        <summary>
            <span data-ttu-id="a2c1a-117">Beginnt einen asynchronen Lesevorgang.</span><span class="sxs-lookup"><span data-stu-id="a2c1a-117">Begins an asynchronous read operation.</span></span>
            </summary>
        <returns><span data-ttu-id="a2c1a-118">Ein "IAsyncResult", das den asynchronen Lesevorgang darstellt, der möglicherweise noch aussteht.</span><span class="sxs-lookup"><span data-stu-id="a2c1a-118">An IAsyncResult that represents the asynchronous read, which could still be pending.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginWrite">
      <MemberSignature Language="C#" Value="public override IAsyncResult BeginWrite (byte[] buffer, int offset, int count, AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance class System.IAsyncResult BeginWrite(unsigned int8[] buffer, int32 offset, int32 count, class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Core.SyncMemoryStream.BeginWrite(System.Byte[],System.Int32,System.Int32,System.AsyncCallback,System.Object)" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function BeginWrite (buffer As Byte(), offset As Integer, count As Integer, callback As AsyncCallback, state As Object) As IAsyncResult" />
      <MemberSignature Language="F#" Value="override this.BeginWrite : byte[] * int * int * AsyncCallback * obj -&gt; IAsyncResult" Usage="syncMemoryStream.BeginWrite (buffer, offset, count, callback, state)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.IAsyncResult</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="buffer" Type="System.Byte[]" />
        <Parameter Name="offset" Type="System.Int32" />
        <Parameter Name="count" Type="System.Int32" />
        <Parameter Name="callback" Type="System.AsyncCallback" />
        <Parameter Name="state" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="buffer"><span data-ttu-id="a2c1a-119">Der Puffer, aus dem Daten geschrieben werden sollen.</span><span class="sxs-lookup"><span data-stu-id="a2c1a-119">The buffer to write data from.</span></span></param>
        <param name="offset"><span data-ttu-id="a2c1a-120">Der nullbasierte Byteoffset im Puffer, ab dem Bytes in den aktuellen Stream kopiert werden soll.</span><span class="sxs-lookup"><span data-stu-id="a2c1a-120">The zero-based byte offset in buffer at which to begin copying bytes to the current stream.</span></span></param>
        <param name="count"><span data-ttu-id="a2c1a-121">Die Anzahl der zu schreibenden Bytes.</span><span class="sxs-lookup"><span data-stu-id="a2c1a-121">The number of bytes to write.</span></span></param>
        <param name="callback"><span data-ttu-id="a2c1a-122">Ein optionaler asynchroner Rückruf, der nach Abschluss des Schreibvorgangs aufgerufen wird.</span><span class="sxs-lookup"><span data-stu-id="a2c1a-122">An optional asynchronous callback, to be called when the write is complete.</span></span></param>
        <param name="state"><span data-ttu-id="a2c1a-123">Ein vom Benutzer bereitgestelltes Objekt, das diese asynchrone Schreibanforderung von anderen Anforderungen unterscheidet.</span><span class="sxs-lookup"><span data-stu-id="a2c1a-123">A user-provided object that distinguishes this particular asynchronous write request from other requests.</span></span></param>
        <summary>
            <span data-ttu-id="a2c1a-124">Beginnt einen asynchronen Schreibvorgang.</span><span class="sxs-lookup"><span data-stu-id="a2c1a-124">Begins an asynchronous write operation.</span></span>
            </summary>
        <returns><span data-ttu-id="a2c1a-125">Ein "IAsyncResult", das den asynchronen Schreibvorgang darstellt, der möglicherweise noch aussteht.</span><span class="sxs-lookup"><span data-stu-id="a2c1a-125">An IAsyncResult that represents the asynchronous write, which could still be pending.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EndRead">
      <MemberSignature Language="C#" Value="public override int EndRead (IAsyncResult asyncResult);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance int32 EndRead(class System.IAsyncResult asyncResult) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Core.SyncMemoryStream.EndRead(System.IAsyncResult)" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function EndRead (asyncResult As IAsyncResult) As Integer" />
      <MemberSignature Language="F#" Value="override this.EndRead : IAsyncResult -&gt; int" Usage="syncMemoryStream.EndRead asyncResult" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="asyncResult" Type="System.IAsyncResult" />
      </Parameters>
      <Docs>
        <param name="asyncResult"><span data-ttu-id="a2c1a-126">Der Verweis auf die ausstehende asynchrone Anforderung, die beendet werden soll.</span><span class="sxs-lookup"><span data-stu-id="a2c1a-126">The reference to the pending asynchronous request to finish.</span></span></param>
        <summary>
            <span data-ttu-id="a2c1a-127">Wartet, bis der ausstehende asynchrone Lesevorgang abgeschlossen ist.</span><span class="sxs-lookup"><span data-stu-id="a2c1a-127">Waits for the pending asynchronous read to complete.</span></span>
            </summary>
        <returns><span data-ttu-id="a2c1a-128">Die Gesamtanzahl der in den Puffer gelesenen Bytes.</span><span class="sxs-lookup"><span data-stu-id="a2c1a-128">The total number of bytes read into the buffer.</span></span> <span data-ttu-id="a2c1a-129">Dies kann weniger als die Anzahl der angeforderten Bytes sein, wenn diese Anzahl an Bytes derzeit nicht verfügbar ist, oder 0 (null), wenn das Streamende erreicht ist.</span><span class="sxs-lookup"><span data-stu-id="a2c1a-129">This can be less than the number of bytes requested if that many bytes are not currently available, or zero if the end of the stream has been reached.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EndWrite">
      <MemberSignature Language="C#" Value="public override void EndWrite (IAsyncResult asyncResult);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance void EndWrite(class System.IAsyncResult asyncResult) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Core.SyncMemoryStream.EndWrite(System.IAsyncResult)" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Sub EndWrite (asyncResult As IAsyncResult)" />
      <MemberSignature Language="F#" Value="override this.EndWrite : IAsyncResult -&gt; unit" Usage="syncMemoryStream.EndWrite asyncResult" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="asyncResult" Type="System.IAsyncResult" />
      </Parameters>
      <Docs>
        <param name="asyncResult"><span data-ttu-id="a2c1a-130">Der Verweis auf die ausstehende asynchrone Anforderung, die beendet werden soll.</span><span class="sxs-lookup"><span data-stu-id="a2c1a-130">The reference to the pending asynchronous request to finish.</span></span></param>
        <summary>
            <span data-ttu-id="a2c1a-131">Beendet einen asynchronen Schreibvorgang.</span><span class="sxs-lookup"><span data-stu-id="a2c1a-131">Ends an asynchronous write operation.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>