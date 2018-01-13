<Type Name="AdlsInputStream" FullName="Microsoft.Azure.DataLake.Store.AdlsInputStream">
  <TypeSignature Language="C#" Value="public class AdlsInputStream : System.IO.Stream" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit AdlsInputStream extends System.IO.Stream" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.DataLake.Store.AdlsInputStream" />
  <TypeSignature Language="VB.NET" Value="Public Class AdlsInputStream&#xA;Inherits Stream" />
  <TypeSignature Language="F#" Value="type AdlsInputStream = class&#xA;    inherit Stream" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.DataLake.Store</AssemblyName>
    <AssemblyVersion>0.1.0.0</AssemblyVersion>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.IO.Stream</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="3114e-101">ADLS-Eingabe-Datenstrom, der Daten aus einer Datei auf Data Lake liest.</span><span class="sxs-lookup"><span data-stu-id="3114e-101">ADLS Input stream that reads data from a file on Data lake.</span></span> <span data-ttu-id="3114e-102">Er liest in einem Massenvorgang Daten vom Server auf einen Puffer und Wiederherstellungsprozessen gepufferte Ausgabe an den Client gemäß der Anforderung.</span><span class="sxs-lookup"><span data-stu-id="3114e-102">It reads data in bulk from server to a buffer and then provides buffered output to the client as per request.</span></span>
            <span data-ttu-id="3114e-103">Daten können asynchron/synchron gelesen werden.</span><span class="sxs-lookup"><span data-stu-id="3114e-103">Data can be read asynchronously/synchronously.</span></span> <span data-ttu-id="3114e-104">Daten können nacheinander oder von beliebigen Punkt in der Datei gelesen werden.</span><span class="sxs-lookup"><span data-stu-id="3114e-104">Data can be read serially or from arbitrary points in file.</span></span> <span data-ttu-id="3114e-105">Gelesen wurde, bis der Transportschicht vollständig synchron ist.</span><span class="sxs-lookup"><span data-stu-id="3114e-105">Read is fully synchronous till the transport layer.</span></span> <span data-ttu-id="3114e-106">ReadAsync ist vollständig synchron ist, bis der Transportschicht.</span><span class="sxs-lookup"><span data-stu-id="3114e-106">ReadAsync is fully synchronous till the transport layer.</span></span> 
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="protected AdlsInputStream ();" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.DataLake.Store.AdlsInputStream.#ctor" />
      <MemberSignature Language="VB.NET" Value="Protected Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DataLake.Store</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="3114e-107">Nur für imitieren Zweck.</span><span class="sxs-lookup"><span data-stu-id="3114e-107">Only for Mocking purpose.</span></span> <span data-ttu-id="3114e-108">Für imitieren Zweck können Sie von dieser Klasse erben und die Methoden überschreiben</span><span class="sxs-lookup"><span data-stu-id="3114e-108">For mocking purpose you can inherit from this class and override your methods</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CanRead">
      <MemberSignature Language="C#" Value="public override bool CanRead { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool CanRead" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.DataLake.Store.AdlsInputStream.CanRead" />
      <MemberSignature Language="VB.NET" Value="Public Overrides ReadOnly Property CanRead As Boolean" />
      <MemberSignature Language="F#" Value="member this.CanRead : bool" Usage="Microsoft.Azure.DataLake.Store.AdlsInputStream.CanRead" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DataLake.Store</AssemblyName>
        <AssemblyVersion>0.1.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="3114e-109">Gibt an, ob Daten von Stream gelesen werden kann</span><span class="sxs-lookup"><span data-stu-id="3114e-109">Whether stream can read data</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CanSeek">
      <MemberSignature Language="C#" Value="public override bool CanSeek { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool CanSeek" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.DataLake.Store.AdlsInputStream.CanSeek" />
      <MemberSignature Language="VB.NET" Value="Public Overrides ReadOnly Property CanSeek As Boolean" />
      <MemberSignature Language="F#" Value="member this.CanSeek : bool" Usage="Microsoft.Azure.DataLake.Store.AdlsInputStream.CanSeek" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DataLake.Store</AssemblyName>
        <AssemblyVersion>0.1.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="3114e-110">Gibt an, ob der Stream Daten durchsucht werden kann</span><span class="sxs-lookup"><span data-stu-id="3114e-110">Whether the stream can seek data</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CanWrite">
      <MemberSignature Language="C#" Value="public override bool CanWrite { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool CanWrite" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.DataLake.Store.AdlsInputStream.CanWrite" />
      <MemberSignature Language="VB.NET" Value="Public Overrides ReadOnly Property CanWrite As Boolean" />
      <MemberSignature Language="F#" Value="member this.CanWrite : bool" Usage="Microsoft.Azure.DataLake.Store.AdlsInputStream.CanWrite" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DataLake.Store</AssemblyName>
        <AssemblyVersion>0.1.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="3114e-111">Gibt an, ob der Stream Daten schreiben</span><span class="sxs-lookup"><span data-stu-id="3114e-111">Whether the stream can write data</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Dispose">
      <MemberSignature Language="C#" Value="protected override void Dispose (bool disposing);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig virtual instance void Dispose(bool disposing) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.DataLake.Store.AdlsInputStream.Dispose(System.Boolean)" />
      <MemberSignature Language="VB.NET" Value="Protected Overrides Sub Dispose (disposing As Boolean)" />
      <MemberSignature Language="F#" Value="override this.Dispose : bool -&gt; unit" Usage="adlsInputStream.Dispose disposing" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DataLake.Store</AssemblyName>
        <AssemblyVersion>0.1.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="disposing" Type="System.Boolean" />
      </Parameters>
      <Docs>
        <param name="disposing"><span data-ttu-id="3114e-112">"true", um sowohl verwaltete als auch nicht verwaltete Ressourcen freizugeben; "false", um ausschließlich nicht verwaltete Ressourcen freizugeben.</span><span class="sxs-lookup"><span data-stu-id="3114e-112">true to release both managed and unmanaged resources; false to release only unmanaged resources</span></span></param>
        <summary>
            <span data-ttu-id="3114e-113">Die vom Stream nicht verwalteten Ressourcen frei und gibt optional die verwalteten Ressourcen frei</span><span class="sxs-lookup"><span data-stu-id="3114e-113">Releases the unmanaged resources used by the Stream and optionally releases the managed resources</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Flush">
      <MemberSignature Language="C#" Value="public override void Flush ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance void Flush() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.DataLake.Store.AdlsInputStream.Flush" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Sub Flush ()" />
      <MemberSignature Language="F#" Value="override this.Flush : unit -&gt; unit" Usage="adlsInputStream.Flush " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DataLake.Store</AssemblyName>
        <AssemblyVersion>0.1.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="3114e-114">Nicht unterstützt</span><span class="sxs-lookup"><span data-stu-id="3114e-114">Not supported</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Length">
      <MemberSignature Language="C#" Value="public override long Length { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 Length" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.DataLake.Store.AdlsInputStream.Length" />
      <MemberSignature Language="VB.NET" Value="Public Overrides ReadOnly Property Length As Long" />
      <MemberSignature Language="F#" Value="member this.Length : int64" Usage="Microsoft.Azure.DataLake.Store.AdlsInputStream.Length" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DataLake.Store</AssemblyName>
        <AssemblyVersion>0.1.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int64</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="3114e-115">Gesamtlänge der Datei</span><span class="sxs-lookup"><span data-stu-id="3114e-115">total Length of the file</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Position">
      <MemberSignature Language="C#" Value="public override long Position { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 Position" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.DataLake.Store.AdlsInputStream.Position" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Property Position As Long" />
      <MemberSignature Language="F#" Value="member this.Position : int64 with get, set" Usage="Microsoft.Azure.DataLake.Store.AdlsInputStream.Position" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DataLake.Store</AssemblyName>
        <AssemblyVersion>0.1.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int64</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="3114e-116">Position im Stream von Anfang</span><span class="sxs-lookup"><span data-stu-id="3114e-116">Position of the stream from begining</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Read">
      <MemberSignature Language="C#" Value="public override int Read (byte[] output, int offset, int count);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance int32 Read(unsigned int8[] output, int32 offset, int32 count) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.DataLake.Store.AdlsInputStream.Read(System.Byte[],System.Int32,System.Int32)" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function Read (output As Byte(), offset As Integer, count As Integer) As Integer" />
      <MemberSignature Language="F#" Value="override this.Read : byte[] * int * int -&gt; int" Usage="adlsInputStream.Read (output, offset, count)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DataLake.Store</AssemblyName>
        <AssemblyVersion>0.1.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="output" Type="System.Byte[]" />
        <Parameter Name="offset" Type="System.Int32" />
        <Parameter Name="count" Type="System.Int32" />
      </Parameters>
      <Docs>
        <param name="output"><span data-ttu-id="3114e-117">Ausgabebytearrays</span><span class="sxs-lookup"><span data-stu-id="3114e-117">Output byte array</span></span></param>
        <param name="offset"><span data-ttu-id="3114e-118">Offset, bei dem Daten im Ausgabearray eingefügt werden soll</span><span class="sxs-lookup"><span data-stu-id="3114e-118">offset at which data should be put in the output array</span></span></param>
        <param name="count"><span data-ttu-id="3114e-119">Anzahl gelesener bytes</span><span class="sxs-lookup"><span data-stu-id="3114e-119">Count of the bytes read</span></span></param>
        <summary>
            <span data-ttu-id="3114e-120">Liest eine Folge von Bytes aus dem aktuellen Stream und erhöht die Position im Stream um die Anzahl der Bytes, die synchronen Lesevorgang.</span><span class="sxs-lookup"><span data-stu-id="3114e-120">Reads a sequence of bytes from the current stream and advances the position within the stream by the number of bytes read Synchronous operation.</span></span>
            </summary>
        <returns><span data-ttu-id="3114e-121">Anzahl der gelesenen bytes</span><span class="sxs-lookup"><span data-stu-id="3114e-121">Number of bytes read</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Read">
      <MemberSignature Language="C#" Value="public int Read (long position, byte[] output, int offset, int count);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance int32 Read(int64 position, unsigned int8[] output, int32 offset, int32 count) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.DataLake.Store.AdlsInputStream.Read(System.Int64,System.Byte[],System.Int32,System.Int32)" />
      <MemberSignature Language="VB.NET" Value="Public Function Read (position As Long, output As Byte(), offset As Integer, count As Integer) As Integer" />
      <MemberSignature Language="F#" Value="override this.Read : int64 * byte[] * int * int -&gt; int" Usage="adlsInputStream.Read (position, output, offset, count)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DataLake.Store</AssemblyName>
        <AssemblyVersion>0.1.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="position" Type="System.Int64" />
        <Parameter Name="output" Type="System.Byte[]" />
        <Parameter Name="offset" Type="System.Int32" />
        <Parameter Name="count" Type="System.Int32" />
      </Parameters>
      <Docs>
        <param name="position"><span data-ttu-id="3114e-122">Position in der Datei aus, in dem sie beginnen soll, Lesen von Daten</span><span class="sxs-lookup"><span data-stu-id="3114e-122">Position in the file from where it should start reading data</span></span></param>
        <param name="output"><span data-ttu-id="3114e-123">Ausgabebytearrays</span><span class="sxs-lookup"><span data-stu-id="3114e-123">Output byte array</span></span></param>
        <param name="offset"><span data-ttu-id="3114e-124">Offset, bei dem Daten im Ausgabearray eingefügt werden soll</span><span class="sxs-lookup"><span data-stu-id="3114e-124">offset at which data should be put in the output array</span></span></param>
        <param name="count"><span data-ttu-id="3114e-125">Anzahl gelesener bytes</span><span class="sxs-lookup"><span data-stu-id="3114e-125">Count of the bytes read</span></span></param>
        <summary>
            <span data-ttu-id="3114e-126">Liest eine Folge von Bytes direkt vom Server an.</span><span class="sxs-lookup"><span data-stu-id="3114e-126">Reads a sequence of bytes directly from the server.</span></span> <span data-ttu-id="3114e-127">Es wird nichts in den Stream nicht aktualisiert.</span><span class="sxs-lookup"><span data-stu-id="3114e-127">It does not update anything in the stream.</span></span>
            </summary>
        <returns><span data-ttu-id="3114e-128">Anzahl der gelesenen bytes</span><span class="sxs-lookup"><span data-stu-id="3114e-128">Number of bytes read</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ReadAsync">
      <MemberSignature Language="C#" Value="public override System.Threading.Tasks.Task&lt;int&gt; ReadAsync (byte[] output, int offset, int count, System.Threading.CancellationToken cancelToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance class System.Threading.Tasks.Task`1&lt;int32&gt; ReadAsync(unsigned int8[] output, int32 offset, int32 count, valuetype System.Threading.CancellationToken cancelToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.DataLake.Store.AdlsInputStream.ReadAsync(System.Byte[],System.Int32,System.Int32,System.Threading.CancellationToken)" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function ReadAsync (output As Byte(), offset As Integer, count As Integer, cancelToken As CancellationToken) As Task(Of Integer)" />
      <MemberSignature Language="F#" Value="override this.ReadAsync : byte[] * int * int * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;int&gt;" Usage="adlsInputStream.ReadAsync (output, offset, count, cancelToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DataLake.Store</AssemblyName>
        <AssemblyVersion>0.1.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.DataLake.Store.AdlsInputStream/&lt;ReadAsync&gt;d__49))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="output" Type="System.Byte[]" />
        <Parameter Name="offset" Type="System.Int32" />
        <Parameter Name="count" Type="System.Int32" />
        <Parameter Name="cancelToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="output"><span data-ttu-id="3114e-129">Ausgabebytearrays</span><span class="sxs-lookup"><span data-stu-id="3114e-129">Output byte array</span></span></param>
        <param name="offset"><span data-ttu-id="3114e-130">Offset, bei dem Daten im Ausgabearray eingefügt werden soll</span><span class="sxs-lookup"><span data-stu-id="3114e-130">offset at which data should be put in the output array</span></span></param>
        <param name="count"><span data-ttu-id="3114e-131">Anzahl gelesener bytes</span><span class="sxs-lookup"><span data-stu-id="3114e-131">Count of the bytes read</span></span></param>
        <param name="cancelToken"><span data-ttu-id="3114e-132">Abbruchtoken</span><span class="sxs-lookup"><span data-stu-id="3114e-132">Cancellation Token</span></span></param>
        <summary>
            <span data-ttu-id="3114e-133">Liest eine Folge von Bytes aus dem aktuellen Stream und erhöht die Position im Stream um die Anzahl der Bytes, die asynchronen Lesevorgang.</span><span class="sxs-lookup"><span data-stu-id="3114e-133">Reads a sequence of bytes from the current stream and advances the position within the stream by the number of bytes read Asynchronous operation.</span></span>
            </summary>
        <returns><span data-ttu-id="3114e-134">Anzahl der gelesenen bytes</span><span class="sxs-lookup"><span data-stu-id="3114e-134">Number of bytes read</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ReadAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;int&gt; ReadAsync (long position, byte[] output, int offset, int count);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;int32&gt; ReadAsync(int64 position, unsigned int8[] output, int32 offset, int32 count) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.DataLake.Store.AdlsInputStream.ReadAsync(System.Int64,System.Byte[],System.Int32,System.Int32)" />
      <MemberSignature Language="VB.NET" Value="Public Function ReadAsync (position As Long, output As Byte(), offset As Integer, count As Integer) As Task(Of Integer)" />
      <MemberSignature Language="F#" Value="override this.ReadAsync : int64 * byte[] * int * int -&gt; System.Threading.Tasks.Task&lt;int&gt;" Usage="adlsInputStream.ReadAsync (position, output, offset, count)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DataLake.Store</AssemblyName>
        <AssemblyVersion>0.1.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.DataLake.Store.AdlsInputStream/&lt;ReadAsync&gt;d__55))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="position" Type="System.Int64" />
        <Parameter Name="output" Type="System.Byte[]" />
        <Parameter Name="offset" Type="System.Int32" />
        <Parameter Name="count" Type="System.Int32" />
      </Parameters>
      <Docs>
        <param name="position"><span data-ttu-id="3114e-135">Position in der Datei aus, in dem sie beginnen soll, Lesen von Daten</span><span class="sxs-lookup"><span data-stu-id="3114e-135">Position in the file from where it should start reading data</span></span></param>
        <param name="output"><span data-ttu-id="3114e-136">Ausgabebytearrays</span><span class="sxs-lookup"><span data-stu-id="3114e-136">Output byte array</span></span></param>
        <param name="offset"><span data-ttu-id="3114e-137">Offset, bei dem Daten im Ausgabearray eingefügt werden soll</span><span class="sxs-lookup"><span data-stu-id="3114e-137">offset at which data should be put in the output array</span></span></param>
        <param name="count"><span data-ttu-id="3114e-138">Anzahl gelesener bytes</span><span class="sxs-lookup"><span data-stu-id="3114e-138">Count of the bytes read</span></span></param>
        <summary>
            <span data-ttu-id="3114e-139">Liest eine Folge von Bytes direkt vom Server an.</span><span class="sxs-lookup"><span data-stu-id="3114e-139">Reads a sequence of bytes directly from the server.</span></span> <span data-ttu-id="3114e-140">Es wird nichts in den Stream nicht aktualisiert.</span><span class="sxs-lookup"><span data-stu-id="3114e-140">It does not update anything in the stream.</span></span>
            </summary>
        <returns><span data-ttu-id="3114e-141">Anzahl der gelesenen bytes</span><span class="sxs-lookup"><span data-stu-id="3114e-141">Number of bytes read</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Seek">
      <MemberSignature Language="C#" Value="public override long Seek (long offset, System.IO.SeekOrigin origin);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance int64 Seek(int64 offset, valuetype System.IO.SeekOrigin origin) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.DataLake.Store.AdlsInputStream.Seek(System.Int64,System.IO.SeekOrigin)" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function Seek (offset As Long, origin As SeekOrigin) As Long" />
      <MemberSignature Language="F#" Value="override this.Seek : int64 * System.IO.SeekOrigin -&gt; int64" Usage="adlsInputStream.Seek (offset, origin)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DataLake.Store</AssemblyName>
        <AssemblyVersion>0.1.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int64</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="offset" Type="System.Int64" />
        <Parameter Name="origin" Type="System.IO.SeekOrigin" />
      </Parameters>
      <Docs>
        <param name="offset"><span data-ttu-id="3114e-142">Byte-Offset relativ zum Ursprungsparameter</span><span class="sxs-lookup"><span data-stu-id="3114e-142">Byte offset relative to the origin parameter</span></span></param>
        <param name="origin"><span data-ttu-id="3114e-143">Ein Wert vom Typ "SeekOrigin", der angibt, das der Bezugspunkt ist verwendet, um die neue Position ermittelt wird.</span><span class="sxs-lookup"><span data-stu-id="3114e-143">A value of type SeekOrigin indicating the reference point used to obtain the new position.</span></span></param>
        <summary>
            <span data-ttu-id="3114e-144">Aktualisiert die Position des Streams basierend auf "SeekOrigin"</span><span class="sxs-lookup"><span data-stu-id="3114e-144">Updates the position of the stream based on SeekOrigin</span></span>
            </summary>
        <returns><span data-ttu-id="3114e-145">Aktuelle neue Position im stream</span><span class="sxs-lookup"><span data-stu-id="3114e-145">Current new position of the stream</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SetLength">
      <MemberSignature Language="C#" Value="public override void SetLength (long value);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance void SetLength(int64 value) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.DataLake.Store.AdlsInputStream.SetLength(System.Int64)" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Sub SetLength (value As Long)" />
      <MemberSignature Language="F#" Value="override this.SetLength : int64 -&gt; unit" Usage="adlsInputStream.SetLength value" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DataLake.Store</AssemblyName>
        <AssemblyVersion>0.1.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="value" Type="System.Int64" />
      </Parameters>
      <Docs>
        <param name="value"></param>
        <summary>
            <span data-ttu-id="3114e-146">Nicht unterstützt</span><span class="sxs-lookup"><span data-stu-id="3114e-146">Not supported</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Write">
      <MemberSignature Language="C#" Value="public override void Write (byte[] buffer, int offset, int count);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance void Write(unsigned int8[] buffer, int32 offset, int32 count) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.DataLake.Store.AdlsInputStream.Write(System.Byte[],System.Int32,System.Int32)" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Sub Write (buffer As Byte(), offset As Integer, count As Integer)" />
      <MemberSignature Language="F#" Value="override this.Write : byte[] * int * int -&gt; unit" Usage="adlsInputStream.Write (buffer, offset, count)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DataLake.Store</AssemblyName>
        <AssemblyVersion>0.1.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="buffer" Type="System.Byte[]" />
        <Parameter Name="offset" Type="System.Int32" />
        <Parameter Name="count" Type="System.Int32" />
      </Parameters>
      <Docs>
        <param name="buffer"></param>
        <param name="offset"></param>
        <param name="count"></param>
        <summary>
            <span data-ttu-id="3114e-147">Nicht unterstützt</span><span class="sxs-lookup"><span data-stu-id="3114e-147">Not supported</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>