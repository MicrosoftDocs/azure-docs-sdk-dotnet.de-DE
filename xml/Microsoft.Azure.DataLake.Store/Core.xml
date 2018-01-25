<Type Name="Core" FullName="Microsoft.Azure.DataLake.Store.Core">
  <TypeSignature Language="C#" Value="public class Core" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit Core extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.DataLake.Store.Core" />
  <TypeSignature Language="VB.NET" Value="Public Class Core" />
  <TypeSignature Language="F#" Value="type Core = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.DataLake.Store</AssemblyName>
    <AssemblyVersion>0.1.0.0</AssemblyVersion>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="980d3-101">Core-Ebene.</span><span class="sxs-lookup"><span data-stu-id="980d3-101">Core layer.</span></span> <span data-ttu-id="980d3-102">Enthält Methoden für die REST-APIs.</span><span class="sxs-lookup"><span data-stu-id="980d3-102">It contains methods for REST APIs.</span></span> <span data-ttu-id="980d3-103">Für jeden rest-api Befehl eine HTTP-Anforderung an Server gesendet.</span><span class="sxs-lookup"><span data-stu-id="980d3-103">For each rest api command it sends a HTTP request to server.</span></span>
            <span data-ttu-id="980d3-104">Wir haben sowohl "Async" und "Sync-Versionen von CREATE-, ANFÜGEN, öffnen, CONCURRENTAPPEND.</span><span class="sxs-lookup"><span data-stu-id="980d3-104">We have both async and sync versions of CREATE, APPEND, OPEN, CONCURRENTAPPEND.</span></span> <span data-ttu-id="980d3-105">Der Grund, wir haben, ist, wenn die Anwendung diese Vorgänge, die häufig explizite Threads verwenden, und Verwenden von Async durchführt-"await" intern nicht benötigten Threads im Threadpool erstellt und die Leistung wird beeinträchtigt, aufgrund der Kontextwechsel.</span><span class="sxs-lookup"><span data-stu-id="980d3-105">The reason we have that is if the application is doing these operations heavily using explicit threads, then using async-await internally creates unecessary threads in threadpool and performance degrades due to context switching.</span></span> <span data-ttu-id="980d3-106">Anwendung kann in Fällen Uploader und Downloadprogramm explizite Threads erstellen.</span><span class="sxs-lookup"><span data-stu-id="980d3-106">Application can create explicit threads in cases of uploader and downloader.</span></span>
            <span data-ttu-id="980d3-107">Alle diese Vorgang auch aufrufen, Sync-Versionen MakeCall in WebTransport-Ebene.</span><span class="sxs-lookup"><span data-stu-id="980d3-107">All these operation also call sync versions of MakeCall in WebTransport layer.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public Core ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.DataLake.Store.Core.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DataLake.Store</AssemblyName>
        <AssemblyVersion>0.1.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>To be added.</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Append">
      <MemberSignature Language="C#" Value="public static void Append (string path, string leaseId, string sessionId, Microsoft.Azure.DataLake.Store.SyncFlag flag, long offsetFile, byte[] dataBytes, int offset, int length, Microsoft.Azure.DataLake.Store.AdlsClient client, Microsoft.Azure.DataLake.Store.RequestOptions req, Microsoft.Azure.DataLake.Store.OperationResponse resp);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void Append(string path, string leaseId, string sessionId, valuetype Microsoft.Azure.DataLake.Store.SyncFlag flag, int64 offsetFile, unsigned int8[] dataBytes, int32 offset, int32 length, class Microsoft.Azure.DataLake.Store.AdlsClient client, class Microsoft.Azure.DataLake.Store.RequestOptions req, class Microsoft.Azure.DataLake.Store.OperationResponse resp) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.DataLake.Store.Core.Append(System.String,System.String,System.String,Microsoft.Azure.DataLake.Store.SyncFlag,System.Int64,System.Byte[],System.Int32,System.Int32,Microsoft.Azure.DataLake.Store.AdlsClient,Microsoft.Azure.DataLake.Store.RequestOptions,Microsoft.Azure.DataLake.Store.OperationResponse)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Sub Append (path As String, leaseId As String, sessionId As String, flag As SyncFlag, offsetFile As Long, dataBytes As Byte(), offset As Integer, length As Integer, client As AdlsClient, req As RequestOptions, resp As OperationResponse)" />
      <MemberSignature Language="F#" Value="static member Append : string * string * string * Microsoft.Azure.DataLake.Store.SyncFlag * int64 * byte[] * int * int * Microsoft.Azure.DataLake.Store.AdlsClient * Microsoft.Azure.DataLake.Store.RequestOptions * Microsoft.Azure.DataLake.Store.OperationResponse -&gt; unit" Usage="Microsoft.Azure.DataLake.Store.Core.Append (path, leaseId, sessionId, flag, offsetFile, dataBytes, offset, length, client, req, resp)" />
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
        <Parameter Name="path" Type="System.String" />
        <Parameter Name="leaseId" Type="System.String" />
        <Parameter Name="sessionId" Type="System.String" />
        <Parameter Name="flag" Type="Microsoft.Azure.DataLake.Store.SyncFlag" />
        <Parameter Name="offsetFile" Type="System.Int64" />
        <Parameter Name="dataBytes" Type="System.Byte[]" />
        <Parameter Name="offset" Type="System.Int32" />
        <Parameter Name="length" Type="System.Int32" />
        <Parameter Name="client" Type="Microsoft.Azure.DataLake.Store.AdlsClient" />
        <Parameter Name="req" Type="Microsoft.Azure.DataLake.Store.RequestOptions" />
        <Parameter Name="resp" Type="Microsoft.Azure.DataLake.Store.OperationResponse" />
      </Parameters>
      <Docs>
        <param name="path"><span data-ttu-id="980d3-108">Pfad der Datei</span><span class="sxs-lookup"><span data-stu-id="980d3-108">Path of the file</span></span></param>
        <param name="leaseId"><span data-ttu-id="980d3-109">Zeichenfolge, die die Lease-ID enthält, wenn ein Client einer Lease für eine Datei kein anderer Client erhält kann Änderungen an der Datei vornehmen.</span><span class="sxs-lookup"><span data-stu-id="980d3-109">String containing the lease ID, when a client obtains a lease on a file no other client can make edits to the file</span></span> </param>
        <param name="sessionId"><span data-ttu-id="980d3-110">UUID, die verwendet wird, um den Handler für Dateien (Datenstrom) einfach auf den Server zu erhalten.</span><span class="sxs-lookup"><span data-stu-id="980d3-110">UUID that is used to obtain the file handler (stream) easily at server</span></span></param>
        <param name="flag"><span data-ttu-id="980d3-111">Übergeben Sie SyncFlag.DATA beim Schreiben von Bytes an Daten SyncFlag.METADATA übergeben, wenn Metadaten der Datei wie die Länge, die geändert Zeitpunkt aktualisiert werden, damit Sie mit den tatsächlichen Daten der Datei übereinstimmen muss.</span><span class="sxs-lookup"><span data-stu-id="980d3-111">Pass SyncFlag.DATA when writing bytes of data Pass SyncFlag.METADATA when metadata of the file like length, modified instant needs to be updated to be consistent with the actual data of file.</span></span> <span data-ttu-id="980d3-112">Nach dem Übergeben der SyncFlag.METADATA GetFileStatus und ListStatus gibt Sie konsistente Daten zurück.</span><span class="sxs-lookup"><span data-stu-id="980d3-112">After passing SyncFlag.METADATA GetFileStatus and ListStatus returns consistent data.</span></span>
                               <span data-ttu-id="980d3-113">Übergeben Sie SyncFlag.CLOSE, wenn keine weiteren Daten angefügt werden müssen, Dateimetadaten wird aktualisiert, Lease freigegeben und der Stream geschlossen ist.</span><span class="sxs-lookup"><span data-stu-id="980d3-113">Pass SyncFlag.CLOSE when no more data needs to be appended, file metadata is updated, lease is released and the stream is closed</span></span>  </param>
        <param name="offsetFile"><span data-ttu-id="980d3-114">Offset in der Datei, an der Daten angefügt wird</span><span class="sxs-lookup"><span data-stu-id="980d3-114">Offset in the file at which data will be appended</span></span></param>
        <param name="dataBytes"><span data-ttu-id="980d3-115">Array von Bytes, die in die Datei geschrieben.</span><span class="sxs-lookup"><span data-stu-id="980d3-115">Array of bytes to write to the file</span></span></param>
        <param name="offset"><span data-ttu-id="980d3-116">Offset im Bytearray</span><span class="sxs-lookup"><span data-stu-id="980d3-116">Offset in the byte array</span></span></param>
        <param name="length"><span data-ttu-id="980d3-117">Anzahl der Bytes vom Offset geschrieben.</span><span class="sxs-lookup"><span data-stu-id="980d3-117">Number of bytes to write from the offset</span></span></param>
        <param name="client"><span data-ttu-id="980d3-118">ADLS-Client</span><span class="sxs-lookup"><span data-stu-id="980d3-118">ADLS Client</span></span></param>
        <param name="req"><span data-ttu-id="980d3-119">Optionen zum Ändern des Verhaltens der HTTP-Anforderung</span><span class="sxs-lookup"><span data-stu-id="980d3-119">Options to change behavior of the Http request</span></span> </param>
        <param name="resp"><span data-ttu-id="980d3-120">Speichert die Antwort/Ausgabe der HTTP-Anforderung</span><span class="sxs-lookup"><span data-stu-id="980d3-120">Stores the response/ouput of the Http request</span></span> </param>
        <summary>
            <span data-ttu-id="980d3-121">Daten werden an Datei anfügen.</span><span class="sxs-lookup"><span data-stu-id="980d3-121">Append data to file.</span></span> <span data-ttu-id="980d3-122">Dies ist ein synchroner Vorgang.</span><span class="sxs-lookup"><span data-stu-id="980d3-122">This is a synchronous operation.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AppendAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task AppendAsync (string path, string leaseId, string sessionId, Microsoft.Azure.DataLake.Store.SyncFlag flag, long offsetFile, byte[] dataBytes, int offset, int length, Microsoft.Azure.DataLake.Store.AdlsClient client, Microsoft.Azure.DataLake.Store.RequestOptions req, Microsoft.Azure.DataLake.Store.OperationResponse resp, System.Threading.CancellationToken cancelToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task AppendAsync(string path, string leaseId, string sessionId, valuetype Microsoft.Azure.DataLake.Store.SyncFlag flag, int64 offsetFile, unsigned int8[] dataBytes, int32 offset, int32 length, class Microsoft.Azure.DataLake.Store.AdlsClient client, class Microsoft.Azure.DataLake.Store.RequestOptions req, class Microsoft.Azure.DataLake.Store.OperationResponse resp, valuetype System.Threading.CancellationToken cancelToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.DataLake.Store.Core.AppendAsync(System.String,System.String,System.String,Microsoft.Azure.DataLake.Store.SyncFlag,System.Int64,System.Byte[],System.Int32,System.Int32,Microsoft.Azure.DataLake.Store.AdlsClient,Microsoft.Azure.DataLake.Store.RequestOptions,Microsoft.Azure.DataLake.Store.OperationResponse,System.Threading.CancellationToken)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function AppendAsync (path As String, leaseId As String, sessionId As String, flag As SyncFlag, offsetFile As Long, dataBytes As Byte(), offset As Integer, length As Integer, client As AdlsClient, req As RequestOptions, resp As OperationResponse, Optional cancelToken As CancellationToken = null) As Task" />
      <MemberSignature Language="F#" Value="static member AppendAsync : string * string * string * Microsoft.Azure.DataLake.Store.SyncFlag * int64 * byte[] * int * int * Microsoft.Azure.DataLake.Store.AdlsClient * Microsoft.Azure.DataLake.Store.RequestOptions * Microsoft.Azure.DataLake.Store.OperationResponse * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.DataLake.Store.Core.AppendAsync (path, leaseId, sessionId, flag, offsetFile, dataBytes, offset, length, client, req, resp, cancelToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DataLake.Store</AssemblyName>
        <AssemblyVersion>0.1.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.DataLake.Store.Core/&lt;AppendAsync&gt;d__5))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="path" Type="System.String" />
        <Parameter Name="leaseId" Type="System.String" />
        <Parameter Name="sessionId" Type="System.String" />
        <Parameter Name="flag" Type="Microsoft.Azure.DataLake.Store.SyncFlag" />
        <Parameter Name="offsetFile" Type="System.Int64" />
        <Parameter Name="dataBytes" Type="System.Byte[]" />
        <Parameter Name="offset" Type="System.Int32" />
        <Parameter Name="length" Type="System.Int32" />
        <Parameter Name="client" Type="Microsoft.Azure.DataLake.Store.AdlsClient" />
        <Parameter Name="req" Type="Microsoft.Azure.DataLake.Store.RequestOptions" />
        <Parameter Name="resp" Type="Microsoft.Azure.DataLake.Store.OperationResponse" />
        <Parameter Name="cancelToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="path"><span data-ttu-id="980d3-123">Pfad der Datei</span><span class="sxs-lookup"><span data-stu-id="980d3-123">Path of the file</span></span></param>
        <param name="leaseId"><span data-ttu-id="980d3-124">Zeichenfolge, die die Lease-ID enthält, wenn ein Client einer Lease für eine Datei kein anderer Client erhält kann Änderungen an der Datei vornehmen.</span><span class="sxs-lookup"><span data-stu-id="980d3-124">String containing the lease ID, when a client obtains a lease on a file no other client can make edits to the file</span></span> </param>
        <param name="sessionId"><span data-ttu-id="980d3-125">UUID, die verwendet wird, um den Handler für Dateien (Datenstrom) einfach auf den Server zu erhalten.</span><span class="sxs-lookup"><span data-stu-id="980d3-125">UUID that is used to obtain the file handler (stream) easily at server</span></span></param>
        <param name="flag"><span data-ttu-id="980d3-126">Übergeben Sie SyncFlag.DATA beim Schreiben von Bytes an Daten SyncFlag.METADATA übergeben, wenn Metadaten der Datei wie die Länge, die geändert Zeitpunkt aktualisiert werden, damit Sie mit den tatsächlichen Daten der Datei übereinstimmen muss.</span><span class="sxs-lookup"><span data-stu-id="980d3-126">Pass SyncFlag.DATA when writing bytes of data Pass SyncFlag.METADATA when metadata of the file like length, modified instant needs to be updated to be consistent with the actual data of file.</span></span> <span data-ttu-id="980d3-127">Nach dem Übergeben der SyncFlag.METADATA GetFileStatus und ListStatus gibt Sie konsistente Daten zurück.</span><span class="sxs-lookup"><span data-stu-id="980d3-127">After passing SyncFlag.METADATA GetFileStatus and ListStatus returns consistent data.</span></span>
                               <span data-ttu-id="980d3-128">Übergeben Sie SyncFlag.CLOSE, wenn keine weiteren Daten angefügt werden müssen, Dateimetadaten wird aktualisiert, Lease freigegeben und der Stream geschlossen ist.</span><span class="sxs-lookup"><span data-stu-id="980d3-128">Pass SyncFlag.CLOSE when no more data needs to be appended, file metadata is updated, lease is released and the stream is closed</span></span>  </param>
        <param name="offsetFile"><span data-ttu-id="980d3-129">Offset in der Datei, an der Daten angefügt wird</span><span class="sxs-lookup"><span data-stu-id="980d3-129">Offset in the file at which data will be appended</span></span></param>
        <param name="dataBytes"><span data-ttu-id="980d3-130">Array von Bytes, die in die Datei geschrieben.</span><span class="sxs-lookup"><span data-stu-id="980d3-130">Array of bytes to write to the file</span></span></param>
        <param name="offset"><span data-ttu-id="980d3-131">Offset im Bytearray</span><span class="sxs-lookup"><span data-stu-id="980d3-131">Offset in the byte array</span></span></param>
        <param name="length"><span data-ttu-id="980d3-132">Anzahl der Bytes vom Offset geschrieben.</span><span class="sxs-lookup"><span data-stu-id="980d3-132">Number of bytes to write from the offset</span></span></param>
        <param name="client"><span data-ttu-id="980d3-133">ADLS-Client</span><span class="sxs-lookup"><span data-stu-id="980d3-133">ADLS Client</span></span></param>
        <param name="req"><span data-ttu-id="980d3-134">Optionen zum Ändern des Verhaltens der HTTP-Anforderung</span><span class="sxs-lookup"><span data-stu-id="980d3-134">Options to change behavior of the Http request</span></span> </param>
        <param name="resp"><span data-ttu-id="980d3-135">Speichert die Antwort/Ausgabe der HTTP-Anforderung</span><span class="sxs-lookup"><span data-stu-id="980d3-135">Stores the response/ouput of the Http request</span></span> </param>
        <param name="cancelToken"><span data-ttu-id="980d3-136">CancellationToken, um die Anforderung abzubrechen</span><span class="sxs-lookup"><span data-stu-id="980d3-136">CancellationToken to cancel the request</span></span></param>
        <summary>
            <span data-ttu-id="980d3-137">Daten werden an Datei anfügen.</span><span class="sxs-lookup"><span data-stu-id="980d3-137">Append data to file.</span></span> <span data-ttu-id="980d3-138">Das ist ein asynchroner Vorgang.</span><span class="sxs-lookup"><span data-stu-id="980d3-138">This is an asynchronous operation.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CheckAccessSync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task CheckAccessSync (string path, string rwx, Microsoft.Azure.DataLake.Store.AdlsClient client, Microsoft.Azure.DataLake.Store.RequestOptions req, Microsoft.Azure.DataLake.Store.OperationResponse resp, System.Threading.CancellationToken cancelToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task CheckAccessSync(string path, string rwx, class Microsoft.Azure.DataLake.Store.AdlsClient client, class Microsoft.Azure.DataLake.Store.RequestOptions req, class Microsoft.Azure.DataLake.Store.OperationResponse resp, valuetype System.Threading.CancellationToken cancelToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.DataLake.Store.Core.CheckAccessSync(System.String,System.String,Microsoft.Azure.DataLake.Store.AdlsClient,Microsoft.Azure.DataLake.Store.RequestOptions,Microsoft.Azure.DataLake.Store.OperationResponse,System.Threading.CancellationToken)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function CheckAccessSync (path As String, rwx As String, client As AdlsClient, req As RequestOptions, resp As OperationResponse, Optional cancelToken As CancellationToken = null) As Task" />
      <MemberSignature Language="F#" Value="static member CheckAccessSync : string * string * Microsoft.Azure.DataLake.Store.AdlsClient * Microsoft.Azure.DataLake.Store.RequestOptions * Microsoft.Azure.DataLake.Store.OperationResponse * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.DataLake.Store.Core.CheckAccessSync (path, rwx, client, req, resp, cancelToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DataLake.Store</AssemblyName>
        <AssemblyVersion>0.1.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.DataLake.Store.Core/&lt;CheckAccessSync&gt;d__20))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="path" Type="System.String" />
        <Parameter Name="rwx" Type="System.String" />
        <Parameter Name="client" Type="Microsoft.Azure.DataLake.Store.AdlsClient" />
        <Parameter Name="req" Type="Microsoft.Azure.DataLake.Store.RequestOptions" />
        <Parameter Name="resp" Type="Microsoft.Azure.DataLake.Store.OperationResponse" />
        <Parameter Name="cancelToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="path"><span data-ttu-id="980d3-139">Pfad der Datei oder des Verzeichnisses</span><span class="sxs-lookup"><span data-stu-id="980d3-139">Path of the file or directory</span></span></param>
        <param name="rwx"><span data-ttu-id="980d3-140">Berechtigung zum Einchecken von "Rwx" in Form einer Zeichenfolge.</span><span class="sxs-lookup"><span data-stu-id="980d3-140">Permission to check in "rwx" string form.</span></span> <span data-ttu-id="980d3-141">Für Beispiel, wenn der Benutzer möchte, um festzustellen, ob sie gelesen hat, führen Sie die Berechtigung, wäre die Zeichenfolge R-x</span><span class="sxs-lookup"><span data-stu-id="980d3-141">For example if the user wants to see if it has read, execute permission, the string would be r-x</span></span> </param>
        <param name="client"><span data-ttu-id="980d3-142">ADLS-Client</span><span class="sxs-lookup"><span data-stu-id="980d3-142">ADLS Client</span></span></param>
        <param name="req"><span data-ttu-id="980d3-143">Optionen zum Ändern des Verhaltens der HTTP-Anforderung</span><span class="sxs-lookup"><span data-stu-id="980d3-143">Options to change behavior of the Http request</span></span> </param>
        <param name="resp"><span data-ttu-id="980d3-144">Speichert die Antwort/Ausgabe der HTTP-Anforderung</span><span class="sxs-lookup"><span data-stu-id="980d3-144">Stores the response/ouput of the Http request</span></span> </param>
        <param name="cancelToken"><span data-ttu-id="980d3-145">CancellationToken, um die Anforderung abzubrechen</span><span class="sxs-lookup"><span data-stu-id="980d3-145">CancellationToken to cancel the request</span></span></param>
        <summary>
            <span data-ttu-id="980d3-146">Überprüft, ob die Benutzergruppe der Zugriff des angegebenen Pfads angegeben wurde</span><span class="sxs-lookup"><span data-stu-id="980d3-146">Checks if the user/group has specified access of the given path</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ConcatAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task ConcatAsync (string path, System.Collections.Generic.List&lt;string&gt; sourceFiles, Microsoft.Azure.DataLake.Store.AdlsClient client, Microsoft.Azure.DataLake.Store.RequestOptions req, Microsoft.Azure.DataLake.Store.OperationResponse resp, System.Threading.CancellationToken cancelToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task ConcatAsync(string path, class System.Collections.Generic.List`1&lt;string&gt; sourceFiles, class Microsoft.Azure.DataLake.Store.AdlsClient client, class Microsoft.Azure.DataLake.Store.RequestOptions req, class Microsoft.Azure.DataLake.Store.OperationResponse resp, valuetype System.Threading.CancellationToken cancelToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.DataLake.Store.Core.ConcatAsync(System.String,System.Collections.Generic.List{System.String},Microsoft.Azure.DataLake.Store.AdlsClient,Microsoft.Azure.DataLake.Store.RequestOptions,Microsoft.Azure.DataLake.Store.OperationResponse,System.Threading.CancellationToken)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function ConcatAsync (path As String, sourceFiles As List(Of String), client As AdlsClient, req As RequestOptions, resp As OperationResponse, Optional cancelToken As CancellationToken = null) As Task" />
      <MemberSignature Language="F#" Value="static member ConcatAsync : string * System.Collections.Generic.List&lt;string&gt; * Microsoft.Azure.DataLake.Store.AdlsClient * Microsoft.Azure.DataLake.Store.RequestOptions * Microsoft.Azure.DataLake.Store.OperationResponse * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.DataLake.Store.Core.ConcatAsync (path, sourceFiles, client, req, resp, cancelToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DataLake.Store</AssemblyName>
        <AssemblyVersion>0.1.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.DataLake.Store.Core/&lt;ConcatAsync&gt;d__15))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="path" Type="System.String" />
        <Parameter Name="sourceFiles" Type="System.Collections.Generic.List&lt;System.String&gt;" />
        <Parameter Name="client" Type="Microsoft.Azure.DataLake.Store.AdlsClient" />
        <Parameter Name="req" Type="Microsoft.Azure.DataLake.Store.RequestOptions" />
        <Parameter Name="resp" Type="Microsoft.Azure.DataLake.Store.OperationResponse" />
        <Parameter Name="cancelToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="path"><span data-ttu-id="980d3-147">Pfad des Ziels</span><span class="sxs-lookup"><span data-stu-id="980d3-147">Path of the destination</span></span></param>
        <param name="sourceFiles"><span data-ttu-id="980d3-148">Liste mit Pfaden der der Quelldateien</span><span class="sxs-lookup"><span data-stu-id="980d3-148">List containing paths of the source files</span></span></param>
        <param name="client"><span data-ttu-id="980d3-149">ADLS-Client</span><span class="sxs-lookup"><span data-stu-id="980d3-149">ADLS Client</span></span></param>
        <param name="req"><span data-ttu-id="980d3-150">Optionen zum Ändern des Verhaltens der HTTP-Anforderung</span><span class="sxs-lookup"><span data-stu-id="980d3-150">Options to change behavior of the Http request</span></span> </param>
        <param name="resp"><span data-ttu-id="980d3-151">Speichert die Antwort/Ausgabe der HTTP-Anforderung</span><span class="sxs-lookup"><span data-stu-id="980d3-151">Stores the response/ouput of the Http request</span></span> </param>
        <param name="cancelToken"><span data-ttu-id="980d3-152">CancellationToken, um die Anforderung abzubrechen</span><span class="sxs-lookup"><span data-stu-id="980d3-152">CancellationToken to cancel the request</span></span></param>
        <summary>
            <span data-ttu-id="980d3-153">Verketten Sie die Quelldateien in eine Zieldatei.</span><span class="sxs-lookup"><span data-stu-id="980d3-153">Concatenate source files to a destination file.</span></span> <span data-ttu-id="980d3-154">In der Standardeinstellung nicht löschen Quellverzeichnis abrufen</span><span class="sxs-lookup"><span data-stu-id="980d3-154">By default it wont delete source directory</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ConcatAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task ConcatAsync (string path, System.Collections.Generic.List&lt;string&gt; sourceFiles, bool deleteSourceDirectory, Microsoft.Azure.DataLake.Store.AdlsClient client, Microsoft.Azure.DataLake.Store.RequestOptions req, Microsoft.Azure.DataLake.Store.OperationResponse resp, System.Threading.CancellationToken cancelToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task ConcatAsync(string path, class System.Collections.Generic.List`1&lt;string&gt; sourceFiles, bool deleteSourceDirectory, class Microsoft.Azure.DataLake.Store.AdlsClient client, class Microsoft.Azure.DataLake.Store.RequestOptions req, class Microsoft.Azure.DataLake.Store.OperationResponse resp, valuetype System.Threading.CancellationToken cancelToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.DataLake.Store.Core.ConcatAsync(System.String,System.Collections.Generic.List{System.String},System.Boolean,Microsoft.Azure.DataLake.Store.AdlsClient,Microsoft.Azure.DataLake.Store.RequestOptions,Microsoft.Azure.DataLake.Store.OperationResponse,System.Threading.CancellationToken)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function ConcatAsync (path As String, sourceFiles As List(Of String), deleteSourceDirectory As Boolean, client As AdlsClient, req As RequestOptions, resp As OperationResponse, Optional cancelToken As CancellationToken = null) As Task" />
      <MemberSignature Language="F#" Value="static member ConcatAsync : string * System.Collections.Generic.List&lt;string&gt; * bool * Microsoft.Azure.DataLake.Store.AdlsClient * Microsoft.Azure.DataLake.Store.RequestOptions * Microsoft.Azure.DataLake.Store.OperationResponse * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.DataLake.Store.Core.ConcatAsync (path, sourceFiles, deleteSourceDirectory, client, req, resp, cancelToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DataLake.Store</AssemblyName>
        <AssemblyVersion>0.1.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.DataLake.Store.Core/&lt;ConcatAsync&gt;d__16))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="path" Type="System.String" />
        <Parameter Name="sourceFiles" Type="System.Collections.Generic.List&lt;System.String&gt;" />
        <Parameter Name="deleteSourceDirectory" Type="System.Boolean" />
        <Parameter Name="client" Type="Microsoft.Azure.DataLake.Store.AdlsClient" />
        <Parameter Name="req" Type="Microsoft.Azure.DataLake.Store.RequestOptions" />
        <Parameter Name="resp" Type="Microsoft.Azure.DataLake.Store.OperationResponse" />
        <Parameter Name="cancelToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="path"><span data-ttu-id="980d3-155">Pfad des Ziels</span><span class="sxs-lookup"><span data-stu-id="980d3-155">Path of the destination</span></span></param>
        <param name="sourceFiles"><span data-ttu-id="980d3-156">Liste mit Pfaden der der Quelldateien</span><span class="sxs-lookup"><span data-stu-id="980d3-156">List containing paths of the source files</span></span></param>
        <param name="deleteSourceDirectory"><span data-ttu-id="980d3-157">Bei "true" löscht dann das Quellverzeichnis, wenn alle Dateien unter es verkettet sind</span><span class="sxs-lookup"><span data-stu-id="980d3-157">If true then deletes the source directory if all the files under it are concatenated</span></span></param>
        <param name="client"><span data-ttu-id="980d3-158">ADLS-Client</span><span class="sxs-lookup"><span data-stu-id="980d3-158">ADLS Client</span></span></param>
        <param name="req"><span data-ttu-id="980d3-159">Optionen zum Ändern des Verhaltens der HTTP-Anforderung</span><span class="sxs-lookup"><span data-stu-id="980d3-159">Options to change behavior of the Http request</span></span> </param>
        <param name="resp"><span data-ttu-id="980d3-160">Speichert die Antwort/Ausgabe der HTTP-Anforderung</span><span class="sxs-lookup"><span data-stu-id="980d3-160">Stores the response/ouput of the Http request</span></span> </param>
        <param name="cancelToken"><span data-ttu-id="980d3-161">CancellationToken, um die Anforderung abzubrechen</span><span class="sxs-lookup"><span data-stu-id="980d3-161">CancellationToken to cancel the request</span></span></param>
        <summary>
            <span data-ttu-id="980d3-162">Verketten von Quelldateien in eine Zieldatei</span><span class="sxs-lookup"><span data-stu-id="980d3-162">Concatenate source files to a destination file</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ConcurrentAppend">
      <MemberSignature Language="C#" Value="public static void ConcurrentAppend (string path, bool autoCreate, byte[] dataBytes, int offset, int length, Microsoft.Azure.DataLake.Store.AdlsClient client, Microsoft.Azure.DataLake.Store.RequestOptions req, Microsoft.Azure.DataLake.Store.OperationResponse resp);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void ConcurrentAppend(string path, bool autoCreate, unsigned int8[] dataBytes, int32 offset, int32 length, class Microsoft.Azure.DataLake.Store.AdlsClient client, class Microsoft.Azure.DataLake.Store.RequestOptions req, class Microsoft.Azure.DataLake.Store.OperationResponse resp) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.DataLake.Store.Core.ConcurrentAppend(System.String,System.Boolean,System.Byte[],System.Int32,System.Int32,Microsoft.Azure.DataLake.Store.AdlsClient,Microsoft.Azure.DataLake.Store.RequestOptions,Microsoft.Azure.DataLake.Store.OperationResponse)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Sub ConcurrentAppend (path As String, autoCreate As Boolean, dataBytes As Byte(), offset As Integer, length As Integer, client As AdlsClient, req As RequestOptions, resp As OperationResponse)" />
      <MemberSignature Language="F#" Value="static member ConcurrentAppend : string * bool * byte[] * int * int * Microsoft.Azure.DataLake.Store.AdlsClient * Microsoft.Azure.DataLake.Store.RequestOptions * Microsoft.Azure.DataLake.Store.OperationResponse -&gt; unit" Usage="Microsoft.Azure.DataLake.Store.Core.ConcurrentAppend (path, autoCreate, dataBytes, offset, length, client, req, resp)" />
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
        <Parameter Name="path" Type="System.String" />
        <Parameter Name="autoCreate" Type="System.Boolean" />
        <Parameter Name="dataBytes" Type="System.Byte[]" />
        <Parameter Name="offset" Type="System.Int32" />
        <Parameter Name="length" Type="System.Int32" />
        <Parameter Name="client" Type="Microsoft.Azure.DataLake.Store.AdlsClient" />
        <Parameter Name="req" Type="Microsoft.Azure.DataLake.Store.RequestOptions" />
        <Parameter Name="resp" Type="Microsoft.Azure.DataLake.Store.OperationResponse" />
      </Parameters>
      <Docs>
        <param name="path"><span data-ttu-id="980d3-163">Pfad der Datei</span><span class="sxs-lookup"><span data-stu-id="980d3-163">Path of the file</span></span></param>
        <param name="autoCreate"></param>
        <param name="dataBytes"><span data-ttu-id="980d3-164">Array von Bytes, die in die Datei geschrieben.</span><span class="sxs-lookup"><span data-stu-id="980d3-164">Array of bytes to write to the file</span></span></param>
        <param name="offset"><span data-ttu-id="980d3-165">Offset im Bytearray</span><span class="sxs-lookup"><span data-stu-id="980d3-165">Offset in the byte array</span></span></param>
        <param name="length"><span data-ttu-id="980d3-166">Anzahl der Bytes vom Offset geschrieben.</span><span class="sxs-lookup"><span data-stu-id="980d3-166">Number of bytes to write from the offset</span></span></param>
        <param name="client"><span data-ttu-id="980d3-167">ADLS-Client</span><span class="sxs-lookup"><span data-stu-id="980d3-167">ADLS Client</span></span></param>
        <param name="req"><span data-ttu-id="980d3-168">Optionen zum Ändern des Verhaltens der HTTP-Anforderung</span><span class="sxs-lookup"><span data-stu-id="980d3-168">Options to change behavior of the Http request</span></span> </param>
        <param name="resp"><span data-ttu-id="980d3-169">Speichert die Antwort/Ausgabe der HTTP-Anforderung</span><span class="sxs-lookup"><span data-stu-id="980d3-169">Stores the response/ouput of the Http request</span></span> </param>
        <summary>
            <span data-ttu-id="980d3-170">Führt gleichzeitige synchron an den Server angefügt.</span><span class="sxs-lookup"><span data-stu-id="980d3-170">Performs concurrent append synchronously at server.</span></span> <span data-ttu-id="980d3-171">Der Offset, bei dem Anfügen treten richtet sich nach Server</span><span class="sxs-lookup"><span data-stu-id="980d3-171">The offset at which append will occur is determined by server</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ConcurrentAppendAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task ConcurrentAppendAsync (string path, bool autoCreate, byte[] dataBytes, int offset, int length, Microsoft.Azure.DataLake.Store.AdlsClient client, Microsoft.Azure.DataLake.Store.RequestOptions req, Microsoft.Azure.DataLake.Store.OperationResponse resp, System.Threading.CancellationToken cancelToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task ConcurrentAppendAsync(string path, bool autoCreate, unsigned int8[] dataBytes, int32 offset, int32 length, class Microsoft.Azure.DataLake.Store.AdlsClient client, class Microsoft.Azure.DataLake.Store.RequestOptions req, class Microsoft.Azure.DataLake.Store.OperationResponse resp, valuetype System.Threading.CancellationToken cancelToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.DataLake.Store.Core.ConcurrentAppendAsync(System.String,System.Boolean,System.Byte[],System.Int32,System.Int32,Microsoft.Azure.DataLake.Store.AdlsClient,Microsoft.Azure.DataLake.Store.RequestOptions,Microsoft.Azure.DataLake.Store.OperationResponse,System.Threading.CancellationToken)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function ConcurrentAppendAsync (path As String, autoCreate As Boolean, dataBytes As Byte(), offset As Integer, length As Integer, client As AdlsClient, req As RequestOptions, resp As OperationResponse, Optional cancelToken As CancellationToken = null) As Task" />
      <MemberSignature Language="F#" Value="static member ConcurrentAppendAsync : string * bool * byte[] * int * int * Microsoft.Azure.DataLake.Store.AdlsClient * Microsoft.Azure.DataLake.Store.RequestOptions * Microsoft.Azure.DataLake.Store.OperationResponse * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.DataLake.Store.Core.ConcurrentAppendAsync (path, autoCreate, dataBytes, offset, length, client, req, resp, cancelToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DataLake.Store</AssemblyName>
        <AssemblyVersion>0.1.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.DataLake.Store.Core/&lt;ConcurrentAppendAsync&gt;d__8))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="path" Type="System.String" />
        <Parameter Name="autoCreate" Type="System.Boolean" />
        <Parameter Name="dataBytes" Type="System.Byte[]" />
        <Parameter Name="offset" Type="System.Int32" />
        <Parameter Name="length" Type="System.Int32" />
        <Parameter Name="client" Type="Microsoft.Azure.DataLake.Store.AdlsClient" />
        <Parameter Name="req" Type="Microsoft.Azure.DataLake.Store.RequestOptions" />
        <Parameter Name="resp" Type="Microsoft.Azure.DataLake.Store.OperationResponse" />
        <Parameter Name="cancelToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="path"><span data-ttu-id="980d3-172">Pfad der Datei</span><span class="sxs-lookup"><span data-stu-id="980d3-172">Path of the file</span></span></param>
        <param name="autoCreate"></param>
        <param name="dataBytes"><span data-ttu-id="980d3-173">Array von Bytes, die in die Datei geschrieben.</span><span class="sxs-lookup"><span data-stu-id="980d3-173">Array of bytes to write to the file</span></span></param>
        <param name="offset"><span data-ttu-id="980d3-174">Offset im Bytearray</span><span class="sxs-lookup"><span data-stu-id="980d3-174">Offset in the byte array</span></span></param>
        <param name="length"><span data-ttu-id="980d3-175">Anzahl der Bytes vom Offset geschrieben.</span><span class="sxs-lookup"><span data-stu-id="980d3-175">Number of bytes to write from the offset</span></span></param>
        <param name="client"><span data-ttu-id="980d3-176">ADLS-Client</span><span class="sxs-lookup"><span data-stu-id="980d3-176">ADLS Client</span></span></param>
        <param name="req"><span data-ttu-id="980d3-177">Optionen zum Ändern des Verhaltens der HTTP-Anforderung</span><span class="sxs-lookup"><span data-stu-id="980d3-177">Options to change behavior of the Http request</span></span> </param>
        <param name="resp"><span data-ttu-id="980d3-178">Speichert die Antwort/Ausgabe der HTTP-Anforderung</span><span class="sxs-lookup"><span data-stu-id="980d3-178">Stores the response/ouput of the Http request</span></span> </param>
        <param name="cancelToken"><span data-ttu-id="980d3-179">CancellationToken, um die Anforderung abzubrechen</span><span class="sxs-lookup"><span data-stu-id="980d3-179">CancellationToken to cancel the request</span></span></param>
        <summary>
            <span data-ttu-id="980d3-180">Führt gleichzeitige asynchron an den Server angefügt.</span><span class="sxs-lookup"><span data-stu-id="980d3-180">Performs concurrent append asynchronously at server.</span></span> <span data-ttu-id="980d3-181">Der Offset, bei dem Anfügen treten richtet sich nach Server</span><span class="sxs-lookup"><span data-stu-id="980d3-181">The offset at which append will occur is determined by server</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Create">
      <MemberSignature Language="C#" Value="public static void Create (string path, bool overwrite, string octalPermission, string leaseId, string sessionId, bool createParent, Microsoft.Azure.DataLake.Store.SyncFlag flag, byte[] dataBytes, int offset, int length, Microsoft.Azure.DataLake.Store.AdlsClient client, Microsoft.Azure.DataLake.Store.RequestOptions req, Microsoft.Azure.DataLake.Store.OperationResponse resp);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void Create(string path, bool overwrite, string octalPermission, string leaseId, string sessionId, bool createParent, valuetype Microsoft.Azure.DataLake.Store.SyncFlag flag, unsigned int8[] dataBytes, int32 offset, int32 length, class Microsoft.Azure.DataLake.Store.AdlsClient client, class Microsoft.Azure.DataLake.Store.RequestOptions req, class Microsoft.Azure.DataLake.Store.OperationResponse resp) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.DataLake.Store.Core.Create(System.String,System.Boolean,System.String,System.String,System.String,System.Boolean,Microsoft.Azure.DataLake.Store.SyncFlag,System.Byte[],System.Int32,System.Int32,Microsoft.Azure.DataLake.Store.AdlsClient,Microsoft.Azure.DataLake.Store.RequestOptions,Microsoft.Azure.DataLake.Store.OperationResponse)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Sub Create (path As String, overwrite As Boolean, octalPermission As String, leaseId As String, sessionId As String, createParent As Boolean, flag As SyncFlag, dataBytes As Byte(), offset As Integer, length As Integer, client As AdlsClient, req As RequestOptions, resp As OperationResponse)" />
      <MemberSignature Language="F#" Value="static member Create : string * bool * string * string * string * bool * Microsoft.Azure.DataLake.Store.SyncFlag * byte[] * int * int * Microsoft.Azure.DataLake.Store.AdlsClient * Microsoft.Azure.DataLake.Store.RequestOptions * Microsoft.Azure.DataLake.Store.OperationResponse -&gt; unit" Usage="Microsoft.Azure.DataLake.Store.Core.Create (path, overwrite, octalPermission, leaseId, sessionId, createParent, flag, dataBytes, offset, length, client, req, resp)" />
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
        <Parameter Name="path" Type="System.String" />
        <Parameter Name="overwrite" Type="System.Boolean" />
        <Parameter Name="octalPermission" Type="System.String" />
        <Parameter Name="leaseId" Type="System.String" />
        <Parameter Name="sessionId" Type="System.String" />
        <Parameter Name="createParent" Type="System.Boolean" />
        <Parameter Name="flag" Type="Microsoft.Azure.DataLake.Store.SyncFlag" />
        <Parameter Name="dataBytes" Type="System.Byte[]" />
        <Parameter Name="offset" Type="System.Int32" />
        <Parameter Name="length" Type="System.Int32" />
        <Parameter Name="client" Type="Microsoft.Azure.DataLake.Store.AdlsClient" />
        <Parameter Name="req" Type="Microsoft.Azure.DataLake.Store.RequestOptions" />
        <Parameter Name="resp" Type="Microsoft.Azure.DataLake.Store.OperationResponse" />
      </Parameters>
      <Docs>
        <param name="path"><span data-ttu-id="980d3-182">Pfad der Datei</span><span class="sxs-lookup"><span data-stu-id="980d3-182">Path of the file</span></span></param>
        <param name="overwrite"><span data-ttu-id="980d3-183">Wird die vorhandene Datei überschrieben, wenn das Flag auf "true" festgelegt ist</span><span class="sxs-lookup"><span data-stu-id="980d3-183">Overwrites the existing file if the flag is true</span></span></param>
        <param name="octalPermission"><span data-ttu-id="980d3-184">Oktale Berechtigungszeichenfolge</span><span class="sxs-lookup"><span data-stu-id="980d3-184">Octal permission string</span></span></param>
        <param name="leaseId"><span data-ttu-id="980d3-185">Zeichenfolge, die die Lease-ID enthält, wenn ein Client einer Lease für eine Datei kein anderer Client erhält kann Änderungen an der Datei vornehmen.</span><span class="sxs-lookup"><span data-stu-id="980d3-185">String containing the lease ID, when a client obtains a lease on a file no other client can make edits to the file</span></span> </param>
        <param name="sessionId"><span data-ttu-id="980d3-186">UUID, die verwendet wird, um den Handler für Dateien (Datenstrom) einfach auf den Server zu erhalten.</span><span class="sxs-lookup"><span data-stu-id="980d3-186">UUID that is used to obtain the file handler (stream) easily at server</span></span></param>
        <param name="createParent"><span data-ttu-id="980d3-187">Bei "true" wird eine nicht vorhandene übergeordnete Verzeichnisse erstellt.</span><span class="sxs-lookup"><span data-stu-id="980d3-187">If true creates any non-existing parent directories</span></span></param>
        <param name="flag"><span data-ttu-id="980d3-188">Übergeben Sie SyncFlag.DATA beim Schreiben von Bytes an Daten SyncFlag.METADATA übergeben, wenn Metadaten der Datei wie die Länge, die geändert Zeitpunkt aktualisiert werden, damit Sie mit den tatsächlichen Daten der Datei übereinstimmen muss.</span><span class="sxs-lookup"><span data-stu-id="980d3-188">Pass SyncFlag.DATA when writing bytes of data Pass SyncFlag.METADATA when metadata of the file like length, modified instant needs to be updated to be consistent with the actual data of file.</span></span> <span data-ttu-id="980d3-189">Nach dem Übergeben der SyncFlag.METADATA GetFileStatus und ListStatus gibt Sie konsistente Daten zurück.</span><span class="sxs-lookup"><span data-stu-id="980d3-189">After passing SyncFlag.METADATA GetFileStatus and ListStatus returns consistent data.</span></span>
                               <span data-ttu-id="980d3-190">Übergeben Sie SyncFlag.CLOSE, wenn keine weiteren Daten angefügt werden müssen, Dateimetadaten wird aktualisiert, Lease freigegeben und der Stream geschlossen ist.</span><span class="sxs-lookup"><span data-stu-id="980d3-190">Pass SyncFlag.CLOSE when no more data needs to be appended, file metadata is updated, lease is released and the stream is closed</span></span>  </param>
        <param name="dataBytes"><span data-ttu-id="980d3-191">Array von Bytes, die in die Datei geschrieben.</span><span class="sxs-lookup"><span data-stu-id="980d3-191">Array of bytes to write to the file</span></span></param>
        <param name="offset"><span data-ttu-id="980d3-192">Offset im Bytearray</span><span class="sxs-lookup"><span data-stu-id="980d3-192">Offset in the byte array</span></span></param>
        <param name="length"><span data-ttu-id="980d3-193">Anzahl der Bytes vom Offset geschrieben.</span><span class="sxs-lookup"><span data-stu-id="980d3-193">Number of bytes to write from the offset</span></span></param>
        <param name="client"><span data-ttu-id="980d3-194">ADLS-Client</span><span class="sxs-lookup"><span data-stu-id="980d3-194">ADLS Client</span></span></param>
        <param name="req"><span data-ttu-id="980d3-195">Optionen zum Ändern des Verhaltens der HTTP-Anforderung</span><span class="sxs-lookup"><span data-stu-id="980d3-195">Options to change behavior of the Http request</span></span> </param>
        <param name="resp"><span data-ttu-id="980d3-196">Speichert die Antwort/Ausgabe der HTTP-Anforderung</span><span class="sxs-lookup"><span data-stu-id="980d3-196">Stores the response/ouput of the Http request</span></span> </param>
        <summary>
            <span data-ttu-id="980d3-197">Erstellen Sie eine neue Datei.</span><span class="sxs-lookup"><span data-stu-id="980d3-197">Create a new file.</span></span> <span data-ttu-id="980d3-198">Dies ist ein synchroner Vorgang.</span><span class="sxs-lookup"><span data-stu-id="980d3-198">This is a synchronous operation.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task CreateAsync (string path, bool overwrite, string octalPermission, string leaseId, string sessionId, bool createParent, Microsoft.Azure.DataLake.Store.SyncFlag flag, byte[] dataBytes, int offset, int length, Microsoft.Azure.DataLake.Store.AdlsClient client, Microsoft.Azure.DataLake.Store.RequestOptions req, Microsoft.Azure.DataLake.Store.OperationResponse resp, System.Threading.CancellationToken cancelToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task CreateAsync(string path, bool overwrite, string octalPermission, string leaseId, string sessionId, bool createParent, valuetype Microsoft.Azure.DataLake.Store.SyncFlag flag, unsigned int8[] dataBytes, int32 offset, int32 length, class Microsoft.Azure.DataLake.Store.AdlsClient client, class Microsoft.Azure.DataLake.Store.RequestOptions req, class Microsoft.Azure.DataLake.Store.OperationResponse resp, valuetype System.Threading.CancellationToken cancelToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.DataLake.Store.Core.CreateAsync(System.String,System.Boolean,System.String,System.String,System.String,System.Boolean,Microsoft.Azure.DataLake.Store.SyncFlag,System.Byte[],System.Int32,System.Int32,Microsoft.Azure.DataLake.Store.AdlsClient,Microsoft.Azure.DataLake.Store.RequestOptions,Microsoft.Azure.DataLake.Store.OperationResponse,System.Threading.CancellationToken)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function CreateAsync (path As String, overwrite As Boolean, octalPermission As String, leaseId As String, sessionId As String, createParent As Boolean, flag As SyncFlag, dataBytes As Byte(), offset As Integer, length As Integer, client As AdlsClient, req As RequestOptions, resp As OperationResponse, Optional cancelToken As CancellationToken = null) As Task" />
      <MemberSignature Language="F#" Value="static member CreateAsync : string * bool * string * string * string * bool * Microsoft.Azure.DataLake.Store.SyncFlag * byte[] * int * int * Microsoft.Azure.DataLake.Store.AdlsClient * Microsoft.Azure.DataLake.Store.RequestOptions * Microsoft.Azure.DataLake.Store.OperationResponse * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.DataLake.Store.Core.CreateAsync (path, overwrite, octalPermission, leaseId, sessionId, createParent, flag, dataBytes, offset, length, client, req, resp, cancelToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DataLake.Store</AssemblyName>
        <AssemblyVersion>0.1.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.DataLake.Store.Core/&lt;CreateAsync&gt;d__2))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="path" Type="System.String" />
        <Parameter Name="overwrite" Type="System.Boolean" />
        <Parameter Name="octalPermission" Type="System.String" />
        <Parameter Name="leaseId" Type="System.String" />
        <Parameter Name="sessionId" Type="System.String" />
        <Parameter Name="createParent" Type="System.Boolean" />
        <Parameter Name="flag" Type="Microsoft.Azure.DataLake.Store.SyncFlag" />
        <Parameter Name="dataBytes" Type="System.Byte[]" />
        <Parameter Name="offset" Type="System.Int32" />
        <Parameter Name="length" Type="System.Int32" />
        <Parameter Name="client" Type="Microsoft.Azure.DataLake.Store.AdlsClient" />
        <Parameter Name="req" Type="Microsoft.Azure.DataLake.Store.RequestOptions" />
        <Parameter Name="resp" Type="Microsoft.Azure.DataLake.Store.OperationResponse" />
        <Parameter Name="cancelToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="path"><span data-ttu-id="980d3-199">Pfad der Datei</span><span class="sxs-lookup"><span data-stu-id="980d3-199">Path of the file</span></span></param>
        <param name="overwrite"><span data-ttu-id="980d3-200">Wird die vorhandene Datei überschrieben, wenn das Flag auf "true" festgelegt ist</span><span class="sxs-lookup"><span data-stu-id="980d3-200">Overwrites the existing file if the flag is true</span></span></param>
        <param name="octalPermission"><span data-ttu-id="980d3-201">Oktale Berechtigungszeichenfolge</span><span class="sxs-lookup"><span data-stu-id="980d3-201">Octal permission string</span></span></param>
        <param name="leaseId"><span data-ttu-id="980d3-202">Zeichenfolge, die die Lease-ID enthält, wenn ein Client einer Lease für eine Datei kein anderer Client erhält kann Änderungen an der Datei vornehmen.</span><span class="sxs-lookup"><span data-stu-id="980d3-202">String containing the lease ID, when a client obtains a lease on a file no other client can make edits to the file</span></span> </param>
        <param name="sessionId"><span data-ttu-id="980d3-203">UUID, die verwendet wird, um den Handler für Dateien (Datenstrom) einfach auf den Server zu erhalten.</span><span class="sxs-lookup"><span data-stu-id="980d3-203">UUID that is used to obtain the file handler (stream) easily at server</span></span></param>
        <param name="createParent"><span data-ttu-id="980d3-204">Bei "true" wird eine nicht vorhandene übergeordnete Verzeichnisse erstellt.</span><span class="sxs-lookup"><span data-stu-id="980d3-204">If true creates any non-existing parent directories</span></span></param>
        <param name="flag"><span data-ttu-id="980d3-205">Übergeben Sie SyncFlag.DATA beim Schreiben von Bytes an Daten SyncFlag.METADATA übergeben, wenn Metadaten der Datei wie die Länge, die geändert Zeitpunkt aktualisiert werden, damit Sie mit den tatsächlichen Daten der Datei übereinstimmen muss.</span><span class="sxs-lookup"><span data-stu-id="980d3-205">Pass SyncFlag.DATA when writing bytes of data Pass SyncFlag.METADATA when metadata of the file like length, modified instant needs to be updated to be consistent with the actual data of file.</span></span> <span data-ttu-id="980d3-206">Nach dem Übergeben der SyncFlag.METADATA GetFileStatus und ListStatus gibt Sie konsistente Daten zurück.</span><span class="sxs-lookup"><span data-stu-id="980d3-206">After passing SyncFlag.METADATA GetFileStatus and ListStatus returns consistent data.</span></span>
                               <span data-ttu-id="980d3-207">Übergeben Sie SyncFlag.CLOSE, wenn keine weiteren Daten angefügt werden müssen, Dateimetadaten wird aktualisiert, Lease freigegeben und der Stream geschlossen ist.</span><span class="sxs-lookup"><span data-stu-id="980d3-207">Pass SyncFlag.CLOSE when no more data needs to be appended, file metadata is updated, lease is released and the stream is closed</span></span>  </param>
        <param name="dataBytes"><span data-ttu-id="980d3-208">Array von Bytes, die in die Datei geschrieben.</span><span class="sxs-lookup"><span data-stu-id="980d3-208">Array of bytes to write to the file</span></span></param>
        <param name="offset"><span data-ttu-id="980d3-209">Offset im Bytearray</span><span class="sxs-lookup"><span data-stu-id="980d3-209">Offset in the byte array</span></span></param>
        <param name="length"><span data-ttu-id="980d3-210">Anzahl der Bytes vom Offset geschrieben.</span><span class="sxs-lookup"><span data-stu-id="980d3-210">Number of bytes to write from the offset</span></span></param>
        <param name="client"><span data-ttu-id="980d3-211">ADLS-Client</span><span class="sxs-lookup"><span data-stu-id="980d3-211">ADLS Client</span></span></param>
        <param name="req"><span data-ttu-id="980d3-212">Optionen zum Ändern des Verhaltens der HTTP-Anforderung</span><span class="sxs-lookup"><span data-stu-id="980d3-212">Options to change behavior of the Http request</span></span> </param>
        <param name="resp"><span data-ttu-id="980d3-213">Speichert die Antwort/Ausgabe der HTTP-Anforderung</span><span class="sxs-lookup"><span data-stu-id="980d3-213">Stores the response/ouput of the Http request</span></span> </param>
        <param name="cancelToken"><span data-ttu-id="980d3-214">CancellationToken, um die Anforderung abzubrechen</span><span class="sxs-lookup"><span data-stu-id="980d3-214">CancellationToken to cancel the request</span></span></param>
        <summary>
            <span data-ttu-id="980d3-215">Erstellen Sie eine neue Datei.</span><span class="sxs-lookup"><span data-stu-id="980d3-215">Create a new file.</span></span> <span data-ttu-id="980d3-216">Das ist ein asynchroner Vorgang.</span><span class="sxs-lookup"><span data-stu-id="980d3-216">This is an asynchronous operation.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;bool&gt; DeleteAsync (string path, bool recursive, Microsoft.Azure.DataLake.Store.AdlsClient client, Microsoft.Azure.DataLake.Store.RequestOptions req, Microsoft.Azure.DataLake.Store.OperationResponse resp, System.Threading.CancellationToken cancelToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;bool&gt; DeleteAsync(string path, bool recursive, class Microsoft.Azure.DataLake.Store.AdlsClient client, class Microsoft.Azure.DataLake.Store.RequestOptions req, class Microsoft.Azure.DataLake.Store.OperationResponse resp, valuetype System.Threading.CancellationToken cancelToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.DataLake.Store.Core.DeleteAsync(System.String,System.Boolean,Microsoft.Azure.DataLake.Store.AdlsClient,Microsoft.Azure.DataLake.Store.RequestOptions,Microsoft.Azure.DataLake.Store.OperationResponse,System.Threading.CancellationToken)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function DeleteAsync (path As String, recursive As Boolean, client As AdlsClient, req As RequestOptions, resp As OperationResponse, Optional cancelToken As CancellationToken = null) As Task(Of Boolean)" />
      <MemberSignature Language="F#" Value="static member DeleteAsync : string * bool * Microsoft.Azure.DataLake.Store.AdlsClient * Microsoft.Azure.DataLake.Store.RequestOptions * Microsoft.Azure.DataLake.Store.OperationResponse * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;bool&gt;" Usage="Microsoft.Azure.DataLake.Store.Core.DeleteAsync (path, recursive, client, req, resp, cancelToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DataLake.Store</AssemblyName>
        <AssemblyVersion>0.1.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.DataLake.Store.Core/&lt;DeleteAsync&gt;d__13))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="path" Type="System.String" />
        <Parameter Name="recursive" Type="System.Boolean" />
        <Parameter Name="client" Type="Microsoft.Azure.DataLake.Store.AdlsClient" />
        <Parameter Name="req" Type="Microsoft.Azure.DataLake.Store.RequestOptions" />
        <Parameter Name="resp" Type="Microsoft.Azure.DataLake.Store.OperationResponse" />
        <Parameter Name="cancelToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="path"><span data-ttu-id="980d3-217">Pfad der Datei oder des Verzeichnisses</span><span class="sxs-lookup"><span data-stu-id="980d3-217">Path of the file or directory</span></span></param>
        <param name="recursive"></param>
        <param name="client"><span data-ttu-id="980d3-218">ADLS-Client</span><span class="sxs-lookup"><span data-stu-id="980d3-218">ADLS Client</span></span></param>
        <param name="req"><span data-ttu-id="980d3-219">Optionen zum Ändern des Verhaltens der HTTP-Anforderung</span><span class="sxs-lookup"><span data-stu-id="980d3-219">Options to change behavior of the Http request</span></span> </param>
        <param name="resp"><span data-ttu-id="980d3-220">Speichert die Antwort/Ausgabe der HTTP-Anforderung</span><span class="sxs-lookup"><span data-stu-id="980d3-220">Stores the response/ouput of the Http request</span></span> </param>
        <param name="cancelToken"><span data-ttu-id="980d3-221">CancellationToken, um die Anforderung abzubrechen</span><span class="sxs-lookup"><span data-stu-id="980d3-221">CancellationToken to cancel the request</span></span></param>
        <summary>
            <span data-ttu-id="980d3-222">Löscht eine Datei oder ein Verzeichnis</span><span class="sxs-lookup"><span data-stu-id="980d3-222">Deletes a file or directory</span></span>
            </summary>
        <returns><span data-ttu-id="980d3-223">True, wenn der Löschvorgang erfolgreich ist.</span><span class="sxs-lookup"><span data-stu-id="980d3-223">True if delete is successful</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAclStatusAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.DataLake.Store.Acl.AclStatus&gt; GetAclStatusAsync (string path, Nullable&lt;Microsoft.Azure.DataLake.Store.UserGroupRepresentation&gt; userIdFormat, Microsoft.Azure.DataLake.Store.AdlsClient client, Microsoft.Azure.DataLake.Store.RequestOptions req, Microsoft.Azure.DataLake.Store.OperationResponse resp, System.Threading.CancellationToken cancelToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.DataLake.Store.Acl.AclStatus&gt; GetAclStatusAsync(string path, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.DataLake.Store.UserGroupRepresentation&gt; userIdFormat, class Microsoft.Azure.DataLake.Store.AdlsClient client, class Microsoft.Azure.DataLake.Store.RequestOptions req, class Microsoft.Azure.DataLake.Store.OperationResponse resp, valuetype System.Threading.CancellationToken cancelToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.DataLake.Store.Core.GetAclStatusAsync(System.String,System.Nullable{Microsoft.Azure.DataLake.Store.UserGroupRepresentation},Microsoft.Azure.DataLake.Store.AdlsClient,Microsoft.Azure.DataLake.Store.RequestOptions,Microsoft.Azure.DataLake.Store.OperationResponse,System.Threading.CancellationToken)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function GetAclStatusAsync (path As String, userIdFormat As Nullable(Of UserGroupRepresentation), client As AdlsClient, req As RequestOptions, resp As OperationResponse, Optional cancelToken As CancellationToken = null) As Task(Of AclStatus)" />
      <MemberSignature Language="F#" Value="static member GetAclStatusAsync : string * Nullable&lt;Microsoft.Azure.DataLake.Store.UserGroupRepresentation&gt; * Microsoft.Azure.DataLake.Store.AdlsClient * Microsoft.Azure.DataLake.Store.RequestOptions * Microsoft.Azure.DataLake.Store.OperationResponse * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.DataLake.Store.Acl.AclStatus&gt;" Usage="Microsoft.Azure.DataLake.Store.Core.GetAclStatusAsync (path, userIdFormat, client, req, resp, cancelToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DataLake.Store</AssemblyName>
        <AssemblyVersion>0.1.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.DataLake.Store.Core/&lt;GetAclStatusAsync&gt;d__32))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.DataLake.Store.Acl.AclStatus&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="path" Type="System.String" />
        <Parameter Name="userIdFormat" Type="System.Nullable&lt;Microsoft.Azure.DataLake.Store.UserGroupRepresentation&gt;" />
        <Parameter Name="client" Type="Microsoft.Azure.DataLake.Store.AdlsClient" />
        <Parameter Name="req" Type="Microsoft.Azure.DataLake.Store.RequestOptions" />
        <Parameter Name="resp" Type="Microsoft.Azure.DataLake.Store.OperationResponse" />
        <Parameter Name="cancelToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="path"><span data-ttu-id="980d3-224">Pfad der Datei oder des Verzeichnisses</span><span class="sxs-lookup"><span data-stu-id="980d3-224">Path of the file or directory</span></span></param>
        <param name="userIdFormat"><span data-ttu-id="980d3-225">Möglichkeit, die Benutzer/Gruppenobjekt darzustellen.</span><span class="sxs-lookup"><span data-stu-id="980d3-225">way to represent the user/group object</span></span></param>
        <param name="client"><span data-ttu-id="980d3-226">ADLS-Client</span><span class="sxs-lookup"><span data-stu-id="980d3-226">ADLS Client</span></span></param>
        <param name="req"><span data-ttu-id="980d3-227">Optionen zum Ändern des Verhaltens der HTTP-Anforderung</span><span class="sxs-lookup"><span data-stu-id="980d3-227">Options to change behavior of the Http request</span></span> </param>
        <param name="resp"><span data-ttu-id="980d3-228">Speichert die Antwort/Ausgabe der HTTP-Anforderung</span><span class="sxs-lookup"><span data-stu-id="980d3-228">Stores the response/ouput of the Http request</span></span> </param>
        <param name="cancelToken"><span data-ttu-id="980d3-229">CancellationToken, um die Anforderung abzubrechen</span><span class="sxs-lookup"><span data-stu-id="980d3-229">CancellationToken to cancel the request</span></span></param>
        <summary>
            <span data-ttu-id="980d3-230">Ruft die ACL-Eintrag-Liste, Besitzer-ID, Gruppen-ID, oktale Berechtigung und persistente Bit (nur für ein Verzeichnis), der das Dateiverzeichnis ab</span><span class="sxs-lookup"><span data-stu-id="980d3-230">Gets the ACL entry list, owner ID, group ID, octal permission and sticky bit (only for a directory) of the file/directory</span></span>
            </summary>
        <returns><span data-ttu-id="980d3-231">ACL-Informationen: ACL-Eintrag-Liste, Besitzer-ID gruppieren-ID, oktale Berechtigung und persistente Bit</span><span class="sxs-lookup"><span data-stu-id="980d3-231">Acl information: ACL entry list, owner ID, group ID, octal permission and sticky bit</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetContentSummaryAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.DataLake.Store.ContentSummary&gt; GetContentSummaryAsync (string path, Microsoft.Azure.DataLake.Store.AdlsClient client, Microsoft.Azure.DataLake.Store.RequestOptions req, Microsoft.Azure.DataLake.Store.OperationResponse resp, System.Threading.CancellationToken cancelToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.DataLake.Store.ContentSummary&gt; GetContentSummaryAsync(string path, class Microsoft.Azure.DataLake.Store.AdlsClient client, class Microsoft.Azure.DataLake.Store.RequestOptions req, class Microsoft.Azure.DataLake.Store.OperationResponse resp, valuetype System.Threading.CancellationToken cancelToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.DataLake.Store.Core.GetContentSummaryAsync(System.String,Microsoft.Azure.DataLake.Store.AdlsClient,Microsoft.Azure.DataLake.Store.RequestOptions,Microsoft.Azure.DataLake.Store.OperationResponse,System.Threading.CancellationToken)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function GetContentSummaryAsync (path As String, client As AdlsClient, req As RequestOptions, resp As OperationResponse, Optional cancelToken As CancellationToken = null) As Task(Of ContentSummary)" />
      <MemberSignature Language="F#" Value="static member GetContentSummaryAsync : string * Microsoft.Azure.DataLake.Store.AdlsClient * Microsoft.Azure.DataLake.Store.RequestOptions * Microsoft.Azure.DataLake.Store.OperationResponse * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.DataLake.Store.ContentSummary&gt;" Usage="Microsoft.Azure.DataLake.Store.Core.GetContentSummaryAsync (path, client, req, resp, cancelToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DataLake.Store</AssemblyName>
        <AssemblyVersion>0.1.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.DataLake.Store.Core/&lt;GetContentSummaryAsync&gt;d__33))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.DataLake.Store.ContentSummary&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="path" Type="System.String" />
        <Parameter Name="client" Type="Microsoft.Azure.DataLake.Store.AdlsClient" />
        <Parameter Name="req" Type="Microsoft.Azure.DataLake.Store.RequestOptions" />
        <Parameter Name="resp" Type="Microsoft.Azure.DataLake.Store.OperationResponse" />
        <Parameter Name="cancelToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="path"><span data-ttu-id="980d3-232">Pfad des Verzeichnisses oder der Datei</span><span class="sxs-lookup"><span data-stu-id="980d3-232">Path of the directory or file</span></span></param>
        <param name="client"><span data-ttu-id="980d3-233">ADLS-Client</span><span class="sxs-lookup"><span data-stu-id="980d3-233">ADLS Client</span></span></param>
        <param name="req"><span data-ttu-id="980d3-234">Optionen zum Ändern des Verhaltens der HTTP-Anforderung</span><span class="sxs-lookup"><span data-stu-id="980d3-234">Options to change behavior of the Http request</span></span> </param>
        <param name="resp"><span data-ttu-id="980d3-235">Speichert die Antwort/Ausgabe der HTTP-Anforderung</span><span class="sxs-lookup"><span data-stu-id="980d3-235">Stores the response/ouput of the Http request</span></span> </param>
        <param name="cancelToken"><span data-ttu-id="980d3-236">CancellationToken, um die Anforderung abzubrechen</span><span class="sxs-lookup"><span data-stu-id="980d3-236">CancellationToken to cancel the request</span></span></param>
        <summary>
            <span data-ttu-id="980d3-237">Ruft Content Zusammenfassung einer Datei oder das Verzeichnis ab</span><span class="sxs-lookup"><span data-stu-id="980d3-237">Gets content summary of a file or directory</span></span>
            </summary>
        <returns><span data-ttu-id="980d3-238">ContentSummary des Pfads</span><span class="sxs-lookup"><span data-stu-id="980d3-238">ContentSummary of the path</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetFileStatusAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.DataLake.Store.DirectoryEntry&gt; GetFileStatusAsync (string path, Nullable&lt;Microsoft.Azure.DataLake.Store.UserGroupRepresentation&gt; userIdFormat, Microsoft.Azure.DataLake.Store.AdlsClient client, Microsoft.Azure.DataLake.Store.RequestOptions req, Microsoft.Azure.DataLake.Store.OperationResponse resp, System.Threading.CancellationToken cancelToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.DataLake.Store.DirectoryEntry&gt; GetFileStatusAsync(string path, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.DataLake.Store.UserGroupRepresentation&gt; userIdFormat, class Microsoft.Azure.DataLake.Store.AdlsClient client, class Microsoft.Azure.DataLake.Store.RequestOptions req, class Microsoft.Azure.DataLake.Store.OperationResponse resp, valuetype System.Threading.CancellationToken cancelToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.DataLake.Store.Core.GetFileStatusAsync(System.String,System.Nullable{Microsoft.Azure.DataLake.Store.UserGroupRepresentation},Microsoft.Azure.DataLake.Store.AdlsClient,Microsoft.Azure.DataLake.Store.RequestOptions,Microsoft.Azure.DataLake.Store.OperationResponse,System.Threading.CancellationToken)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function GetFileStatusAsync (path As String, userIdFormat As Nullable(Of UserGroupRepresentation), client As AdlsClient, req As RequestOptions, resp As OperationResponse, Optional cancelToken As CancellationToken = null) As Task(Of DirectoryEntry)" />
      <MemberSignature Language="F#" Value="static member GetFileStatusAsync : string * Nullable&lt;Microsoft.Azure.DataLake.Store.UserGroupRepresentation&gt; * Microsoft.Azure.DataLake.Store.AdlsClient * Microsoft.Azure.DataLake.Store.RequestOptions * Microsoft.Azure.DataLake.Store.OperationResponse * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.DataLake.Store.DirectoryEntry&gt;" Usage="Microsoft.Azure.DataLake.Store.Core.GetFileStatusAsync (path, userIdFormat, client, req, resp, cancelToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DataLake.Store</AssemblyName>
        <AssemblyVersion>0.1.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.DataLake.Store.Core/&lt;GetFileStatusAsync&gt;d__17))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.DataLake.Store.DirectoryEntry&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="path" Type="System.String" />
        <Parameter Name="userIdFormat" Type="System.Nullable&lt;Microsoft.Azure.DataLake.Store.UserGroupRepresentation&gt;" />
        <Parameter Name="client" Type="Microsoft.Azure.DataLake.Store.AdlsClient" />
        <Parameter Name="req" Type="Microsoft.Azure.DataLake.Store.RequestOptions" />
        <Parameter Name="resp" Type="Microsoft.Azure.DataLake.Store.OperationResponse" />
        <Parameter Name="cancelToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="path"><span data-ttu-id="980d3-239">Pfad der Datei oder des Verzeichnisses</span><span class="sxs-lookup"><span data-stu-id="980d3-239">Path of the file or directory</span></span></param>
        <param name="userIdFormat"><span data-ttu-id="980d3-240">Wie werden die Benutzer oder Gruppe Objekt dargestellt</span><span class="sxs-lookup"><span data-stu-id="980d3-240">Way the user or group object will be represented</span></span></param>
        <param name="client"><span data-ttu-id="980d3-241">ADLS-Client</span><span class="sxs-lookup"><span data-stu-id="980d3-241">ADLS Client</span></span></param>
        <param name="req"><span data-ttu-id="980d3-242">Optionen zum Ändern des Verhaltens der HTTP-Anforderung</span><span class="sxs-lookup"><span data-stu-id="980d3-242">Options to change behavior of the Http request</span></span> </param>
        <param name="resp"><span data-ttu-id="980d3-243">Speichert die Antwort/Ausgabe der HTTP-Anforderung</span><span class="sxs-lookup"><span data-stu-id="980d3-243">Stores the response/ouput of the Http request</span></span> </param>
        <param name="cancelToken"><span data-ttu-id="980d3-244">CancellationToken, um die Anforderung abzubrechen</span><span class="sxs-lookup"><span data-stu-id="980d3-244">CancellationToken to cancel the request</span></span></param>
        <summary>
            <span data-ttu-id="980d3-245">Ruft Metadaten, z. B. vollständiger Pfad, Typ (Datei oder Verzeichnis), Gruppe, Benutzer, Berechtigungen, Länge, der letzten Zugriffszeit, Uhrzeit der letzten Änderung, Ablaufzeit Acl Bit Replikation Faktor</span><span class="sxs-lookup"><span data-stu-id="980d3-245">Gets meta data like full path, type (file or directory), group, user, permission, length,last Access Time,last Modified Time, expiry time, acl Bit, replication Factor</span></span>
            </summary>
        <returns><span data-ttu-id="980d3-246">Gibt die Metadaten der Datei oder des Verzeichnisses zurück</span><span class="sxs-lookup"><span data-stu-id="980d3-246">Returns the metadata of the file or directory</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListStatusAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;System.Collections.Generic.List&lt;Microsoft.Azure.DataLake.Store.DirectoryEntry&gt;&gt; ListStatusAsync (string path, string listAfter, string listBefore, int listSize, Nullable&lt;Microsoft.Azure.DataLake.Store.UserGroupRepresentation&gt; userIdFormat, Microsoft.Azure.DataLake.Store.AdlsClient client, Microsoft.Azure.DataLake.Store.RequestOptions req, Microsoft.Azure.DataLake.Store.OperationResponse resp, System.Threading.CancellationToken cancelToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class System.Collections.Generic.List`1&lt;class Microsoft.Azure.DataLake.Store.DirectoryEntry&gt;&gt; ListStatusAsync(string path, string listAfter, string listBefore, int32 listSize, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.DataLake.Store.UserGroupRepresentation&gt; userIdFormat, class Microsoft.Azure.DataLake.Store.AdlsClient client, class Microsoft.Azure.DataLake.Store.RequestOptions req, class Microsoft.Azure.DataLake.Store.OperationResponse resp, valuetype System.Threading.CancellationToken cancelToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.DataLake.Store.Core.ListStatusAsync(System.String,System.String,System.String,System.Int32,System.Nullable{Microsoft.Azure.DataLake.Store.UserGroupRepresentation},Microsoft.Azure.DataLake.Store.AdlsClient,Microsoft.Azure.DataLake.Store.RequestOptions,Microsoft.Azure.DataLake.Store.OperationResponse,System.Threading.CancellationToken)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function ListStatusAsync (path As String, listAfter As String, listBefore As String, listSize As Integer, userIdFormat As Nullable(Of UserGroupRepresentation), client As AdlsClient, req As RequestOptions, resp As OperationResponse, Optional cancelToken As CancellationToken = null) As Task(Of List(Of DirectoryEntry))" />
      <MemberSignature Language="F#" Value="static member ListStatusAsync : string * string * string * int * Nullable&lt;Microsoft.Azure.DataLake.Store.UserGroupRepresentation&gt; * Microsoft.Azure.DataLake.Store.AdlsClient * Microsoft.Azure.DataLake.Store.RequestOptions * Microsoft.Azure.DataLake.Store.OperationResponse * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.Collections.Generic.List&lt;Microsoft.Azure.DataLake.Store.DirectoryEntry&gt;&gt;" Usage="Microsoft.Azure.DataLake.Store.Core.ListStatusAsync (path, listAfter, listBefore, listSize, userIdFormat, client, req, resp, cancelToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DataLake.Store</AssemblyName>
        <AssemblyVersion>0.1.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.DataLake.Store.Core/&lt;ListStatusAsync&gt;d__18))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Collections.Generic.List&lt;Microsoft.Azure.DataLake.Store.DirectoryEntry&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="path" Type="System.String" />
        <Parameter Name="listAfter" Type="System.String" />
        <Parameter Name="listBefore" Type="System.String" />
        <Parameter Name="listSize" Type="System.Int32" />
        <Parameter Name="userIdFormat" Type="System.Nullable&lt;Microsoft.Azure.DataLake.Store.UserGroupRepresentation&gt;" />
        <Parameter Name="client" Type="Microsoft.Azure.DataLake.Store.AdlsClient" />
        <Parameter Name="req" Type="Microsoft.Azure.DataLake.Store.RequestOptions" />
        <Parameter Name="resp" Type="Microsoft.Azure.DataLake.Store.OperationResponse" />
        <Parameter Name="cancelToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="path"><span data-ttu-id="980d3-247">Pfad des Verzeichnisses</span><span class="sxs-lookup"><span data-stu-id="980d3-247">Path of the directory</span></span></param>
        <param name="listAfter"><span data-ttu-id="980d3-248">Dateiname nach der Liste der Dateien vom Server abgerufen werden sollen</span><span class="sxs-lookup"><span data-stu-id="980d3-248">Filename after which list of files should be obtained from server</span></span></param>
        <param name="listBefore"><span data-ttu-id="980d3-249">FileName bis zu dem Liste der Dateien vom Server abgerufen werden sollen</span><span class="sxs-lookup"><span data-stu-id="980d3-249">Filename till which list of files should be obtained from server</span></span></param>
        <param name="listSize"><span data-ttu-id="980d3-250">Die Listengröße vom Server abgerufen</span><span class="sxs-lookup"><span data-stu-id="980d3-250">List size to obtain from server</span></span></param>
        <param name="userIdFormat"><span data-ttu-id="980d3-251">Wie werden die Benutzer oder Gruppe Objekt dargestellt</span><span class="sxs-lookup"><span data-stu-id="980d3-251">Way the user or group object will be represented</span></span></param>
        <param name="client"><span data-ttu-id="980d3-252">ADLS-Client</span><span class="sxs-lookup"><span data-stu-id="980d3-252">ADLS Client</span></span></param>
        <param name="req"><span data-ttu-id="980d3-253">Optionen zum Ändern des Verhaltens der HTTP-Anforderung</span><span class="sxs-lookup"><span data-stu-id="980d3-253">Options to change behavior of the Http request</span></span> </param>
        <param name="resp"><span data-ttu-id="980d3-254">Speichert die Antwort/Ausgabe der HTTP-Anforderung</span><span class="sxs-lookup"><span data-stu-id="980d3-254">Stores the response/ouput of the Http request</span></span> </param>
        <param name="cancelToken"><span data-ttu-id="980d3-255">CancellationToken, um die Anforderung abzubrechen</span><span class="sxs-lookup"><span data-stu-id="980d3-255">CancellationToken to cancel the request</span></span></param>
        <summary>
            <span data-ttu-id="980d3-256">Listet die Unterverzeichnisse oder in einem Verzeichnis enthaltenen Dateien</span><span class="sxs-lookup"><span data-stu-id="980d3-256">Lists the sub-directories or files contained in a directory</span></span>
            </summary>
        <returns><span data-ttu-id="980d3-257">Liste der directoryentries</span><span class="sxs-lookup"><span data-stu-id="980d3-257">List of directoryentries</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MkdirsAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;bool&gt; MkdirsAsync (string path, string octalPermission, Microsoft.Azure.DataLake.Store.AdlsClient client, Microsoft.Azure.DataLake.Store.RequestOptions req, Microsoft.Azure.DataLake.Store.OperationResponse resp, System.Threading.CancellationToken cancelToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;bool&gt; MkdirsAsync(string path, string octalPermission, class Microsoft.Azure.DataLake.Store.AdlsClient client, class Microsoft.Azure.DataLake.Store.RequestOptions req, class Microsoft.Azure.DataLake.Store.OperationResponse resp, valuetype System.Threading.CancellationToken cancelToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.DataLake.Store.Core.MkdirsAsync(System.String,System.String,Microsoft.Azure.DataLake.Store.AdlsClient,Microsoft.Azure.DataLake.Store.RequestOptions,Microsoft.Azure.DataLake.Store.OperationResponse,System.Threading.CancellationToken)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function MkdirsAsync (path As String, octalPermission As String, client As AdlsClient, req As RequestOptions, resp As OperationResponse, Optional cancelToken As CancellationToken = null) As Task(Of Boolean)" />
      <MemberSignature Language="F#" Value="static member MkdirsAsync : string * string * Microsoft.Azure.DataLake.Store.AdlsClient * Microsoft.Azure.DataLake.Store.RequestOptions * Microsoft.Azure.DataLake.Store.OperationResponse * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;bool&gt;" Usage="Microsoft.Azure.DataLake.Store.Core.MkdirsAsync (path, octalPermission, client, req, resp, cancelToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DataLake.Store</AssemblyName>
        <AssemblyVersion>0.1.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.DataLake.Store.Core/&lt;MkdirsAsync&gt;d__0))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="path" Type="System.String" />
        <Parameter Name="octalPermission" Type="System.String" />
        <Parameter Name="client" Type="Microsoft.Azure.DataLake.Store.AdlsClient" />
        <Parameter Name="req" Type="Microsoft.Azure.DataLake.Store.RequestOptions" />
        <Parameter Name="resp" Type="Microsoft.Azure.DataLake.Store.OperationResponse" />
        <Parameter Name="cancelToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="path"><span data-ttu-id="980d3-258">Pfad des Verzeichnisses</span><span class="sxs-lookup"><span data-stu-id="980d3-258">Path of the directory</span></span></param>
        <param name="octalPermission"><span data-ttu-id="980d3-259">Oktale Berechtigung</span><span class="sxs-lookup"><span data-stu-id="980d3-259">Octal Permission</span></span></param>
        <param name="client"><span data-ttu-id="980d3-260">ADLS-Client</span><span class="sxs-lookup"><span data-stu-id="980d3-260">ADLS Client</span></span></param>
        <param name="req"><span data-ttu-id="980d3-261">Optionen zum Ändern des Verhaltens der HTTP-Anforderung</span><span class="sxs-lookup"><span data-stu-id="980d3-261">Options to change behavior of the Http request</span></span> </param>
        <param name="resp"><span data-ttu-id="980d3-262">Speichert die Antwort/Ausgabe der HTTP-Anforderung</span><span class="sxs-lookup"><span data-stu-id="980d3-262">Stores the response/ouput of the Http request</span></span> </param>
        <param name="cancelToken"><span data-ttu-id="980d3-263">CancellationToken, um die Anforderung abzubrechen</span><span class="sxs-lookup"><span data-stu-id="980d3-263">CancellationToken to cancel the request</span></span></param>
        <summary>
            <span data-ttu-id="980d3-264">Erstellt ein Verzeichnis.</span><span class="sxs-lookup"><span data-stu-id="980d3-264">Creates a directory.</span></span> 
            </summary>
        <returns><span data-ttu-id="980d3-265">"true", wenn sie das Verzeichnis andernfalls "false" wird erstellt</span><span class="sxs-lookup"><span data-stu-id="980d3-265">true if it creates the directory else false</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ModifyAclEntriesAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task ModifyAclEntriesAsync (string path, System.Collections.Generic.List&lt;Microsoft.Azure.DataLake.Store.Acl.AclEntry&gt; aclSpecList, Microsoft.Azure.DataLake.Store.AdlsClient client, Microsoft.Azure.DataLake.Store.RequestOptions req, Microsoft.Azure.DataLake.Store.OperationResponse resp, System.Threading.CancellationToken cancelToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task ModifyAclEntriesAsync(string path, class System.Collections.Generic.List`1&lt;class Microsoft.Azure.DataLake.Store.Acl.AclEntry&gt; aclSpecList, class Microsoft.Azure.DataLake.Store.AdlsClient client, class Microsoft.Azure.DataLake.Store.RequestOptions req, class Microsoft.Azure.DataLake.Store.OperationResponse resp, valuetype System.Threading.CancellationToken cancelToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.DataLake.Store.Core.ModifyAclEntriesAsync(System.String,System.Collections.Generic.List{Microsoft.Azure.DataLake.Store.Acl.AclEntry},Microsoft.Azure.DataLake.Store.AdlsClient,Microsoft.Azure.DataLake.Store.RequestOptions,Microsoft.Azure.DataLake.Store.OperationResponse,System.Threading.CancellationToken)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function ModifyAclEntriesAsync (path As String, aclSpecList As List(Of AclEntry), client As AdlsClient, req As RequestOptions, resp As OperationResponse, Optional cancelToken As CancellationToken = null) As Task" />
      <MemberSignature Language="F#" Value="static member ModifyAclEntriesAsync : string * System.Collections.Generic.List&lt;Microsoft.Azure.DataLake.Store.Acl.AclEntry&gt; * Microsoft.Azure.DataLake.Store.AdlsClient * Microsoft.Azure.DataLake.Store.RequestOptions * Microsoft.Azure.DataLake.Store.OperationResponse * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.DataLake.Store.Core.ModifyAclEntriesAsync (path, aclSpecList, client, req, resp, cancelToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DataLake.Store</AssemblyName>
        <AssemblyVersion>0.1.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.DataLake.Store.Core/&lt;ModifyAclEntriesAsync&gt;d__25))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="path" Type="System.String" />
        <Parameter Name="aclSpecList" Type="System.Collections.Generic.List&lt;Microsoft.Azure.DataLake.Store.Acl.AclEntry&gt;" />
        <Parameter Name="client" Type="Microsoft.Azure.DataLake.Store.AdlsClient" />
        <Parameter Name="req" Type="Microsoft.Azure.DataLake.Store.RequestOptions" />
        <Parameter Name="resp" Type="Microsoft.Azure.DataLake.Store.OperationResponse" />
        <Parameter Name="cancelToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="path"><span data-ttu-id="980d3-266">Pfad der Datei oder des Verzeichnisses</span><span class="sxs-lookup"><span data-stu-id="980d3-266">Path of the file or directory</span></span></param>
        <param name="aclSpecList"><span data-ttu-id="980d3-267">Liste der Acl-Einträge zu ändern</span><span class="sxs-lookup"><span data-stu-id="980d3-267">List of Acl Entries to modify</span></span></param>
        <param name="client"><span data-ttu-id="980d3-268">ADLS-Client</span><span class="sxs-lookup"><span data-stu-id="980d3-268">ADLS Client</span></span></param>
        <param name="req"><span data-ttu-id="980d3-269">Optionen zum Ändern des Verhaltens der HTTP-Anforderung</span><span class="sxs-lookup"><span data-stu-id="980d3-269">Options to change behavior of the Http request</span></span> </param>
        <param name="resp"><span data-ttu-id="980d3-270">Speichert die Antwort/Ausgabe der HTTP-Anforderung</span><span class="sxs-lookup"><span data-stu-id="980d3-270">Stores the response/ouput of the Http request</span></span> </param>
        <param name="cancelToken"><span data-ttu-id="980d3-271">CancellationToken, um die Anforderung abzubrechen</span><span class="sxs-lookup"><span data-stu-id="980d3-271">CancellationToken to cancel the request</span></span></param>
        <summary>
            <span data-ttu-id="980d3-272">Ändert die Acl-Einträge einer Datei oder ein Verzeichnis mit die angegebene ACL-Liste.</span><span class="sxs-lookup"><span data-stu-id="980d3-272">Modifies acl entries of a file or directory with given ACL list.</span></span> <span data-ttu-id="980d3-273">Er führt die vorhandenen ACL zusammen mit angegebene Liste aufzulisten.</span><span class="sxs-lookup"><span data-stu-id="980d3-273">It merges the exisitng ACL list with given list.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ModifyAclEntriesAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task ModifyAclEntriesAsync (string path, string aclSpec, Microsoft.Azure.DataLake.Store.AdlsClient client, Microsoft.Azure.DataLake.Store.RequestOptions req, Microsoft.Azure.DataLake.Store.OperationResponse resp, System.Threading.CancellationToken cancelToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task ModifyAclEntriesAsync(string path, string aclSpec, class Microsoft.Azure.DataLake.Store.AdlsClient client, class Microsoft.Azure.DataLake.Store.RequestOptions req, class Microsoft.Azure.DataLake.Store.OperationResponse resp, valuetype System.Threading.CancellationToken cancelToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.DataLake.Store.Core.ModifyAclEntriesAsync(System.String,System.String,Microsoft.Azure.DataLake.Store.AdlsClient,Microsoft.Azure.DataLake.Store.RequestOptions,Microsoft.Azure.DataLake.Store.OperationResponse,System.Threading.CancellationToken)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function ModifyAclEntriesAsync (path As String, aclSpec As String, client As AdlsClient, req As RequestOptions, resp As OperationResponse, Optional cancelToken As CancellationToken = null) As Task" />
      <MemberSignature Language="F#" Value="static member ModifyAclEntriesAsync : string * string * Microsoft.Azure.DataLake.Store.AdlsClient * Microsoft.Azure.DataLake.Store.RequestOptions * Microsoft.Azure.DataLake.Store.OperationResponse * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.DataLake.Store.Core.ModifyAclEntriesAsync (path, aclSpec, client, req, resp, cancelToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DataLake.Store</AssemblyName>
        <AssemblyVersion>0.1.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.DataLake.Store.Core/&lt;ModifyAclEntriesAsync&gt;d__24))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="path" Type="System.String" />
        <Parameter Name="aclSpec" Type="System.String" />
        <Parameter Name="client" Type="Microsoft.Azure.DataLake.Store.AdlsClient" />
        <Parameter Name="req" Type="Microsoft.Azure.DataLake.Store.RequestOptions" />
        <Parameter Name="resp" Type="Microsoft.Azure.DataLake.Store.OperationResponse" />
        <Parameter Name="cancelToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="path"><span data-ttu-id="980d3-274">Pfad der Datei oder des Verzeichnisses</span><span class="sxs-lookup"><span data-stu-id="980d3-274">Path of the file or directory</span></span></param>
        <param name="aclSpec"><span data-ttu-id="980d3-275">AclSpec-Zeichenfolge, die ACL-Einträge durch Komma getrennt enthält</span><span class="sxs-lookup"><span data-stu-id="980d3-275">AclSpec string that contains the ACL entries delimited by comma</span></span> </param>
        <param name="client"><span data-ttu-id="980d3-276">ADLS-Client</span><span class="sxs-lookup"><span data-stu-id="980d3-276">ADLS Client</span></span></param>
        <param name="req"><span data-ttu-id="980d3-277">Optionen zum Ändern des Verhaltens der HTTP-Anforderung</span><span class="sxs-lookup"><span data-stu-id="980d3-277">Options to change behavior of the Http request</span></span> </param>
        <param name="resp"><span data-ttu-id="980d3-278">Speichert die Antwort/Ausgabe der HTTP-Anforderung</span><span class="sxs-lookup"><span data-stu-id="980d3-278">Stores the response/ouput of the Http request</span></span> </param>
        <param name="cancelToken"><span data-ttu-id="980d3-279">CancellationToken, um die Anforderung abzubrechen</span><span class="sxs-lookup"><span data-stu-id="980d3-279">CancellationToken to cancel the request</span></span></param>
        <summary>
            <span data-ttu-id="980d3-280">Ändert die Acl-Einträge einer Datei oder ein Verzeichnis mit die angegebene ACL-Liste.</span><span class="sxs-lookup"><span data-stu-id="980d3-280">Modifies acl entries of a file or directory with given ACL list.</span></span> <span data-ttu-id="980d3-281">Er führt die vorhandenen ACL zusammen mit angegebene Liste aufzulisten.</span><span class="sxs-lookup"><span data-stu-id="980d3-281">It merges the exisitng ACL list with given list.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Open">
      <MemberSignature Language="C#" Value="public static int Open (string path, string sessionId, long offsetFile, byte[] buffer, int offset, int lengthFile, Microsoft.Azure.DataLake.Store.AdlsClient client, Microsoft.Azure.DataLake.Store.RequestOptions req, Microsoft.Azure.DataLake.Store.OperationResponse resp);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig int32 Open(string path, string sessionId, int64 offsetFile, unsigned int8[] buffer, int32 offset, int32 lengthFile, class Microsoft.Azure.DataLake.Store.AdlsClient client, class Microsoft.Azure.DataLake.Store.RequestOptions req, class Microsoft.Azure.DataLake.Store.OperationResponse resp) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.DataLake.Store.Core.Open(System.String,System.String,System.Int64,System.Byte[],System.Int32,System.Int32,Microsoft.Azure.DataLake.Store.AdlsClient,Microsoft.Azure.DataLake.Store.RequestOptions,Microsoft.Azure.DataLake.Store.OperationResponse)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function Open (path As String, sessionId As String, offsetFile As Long, buffer As Byte(), offset As Integer, lengthFile As Integer, client As AdlsClient, req As RequestOptions, resp As OperationResponse) As Integer" />
      <MemberSignature Language="F#" Value="static member Open : string * string * int64 * byte[] * int * int * Microsoft.Azure.DataLake.Store.AdlsClient * Microsoft.Azure.DataLake.Store.RequestOptions * Microsoft.Azure.DataLake.Store.OperationResponse -&gt; int" Usage="Microsoft.Azure.DataLake.Store.Core.Open (path, sessionId, offsetFile, buffer, offset, lengthFile, client, req, resp)" />
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
        <Parameter Name="path" Type="System.String" />
        <Parameter Name="sessionId" Type="System.String" />
        <Parameter Name="offsetFile" Type="System.Int64" />
        <Parameter Name="buffer" Type="System.Byte[]" />
        <Parameter Name="offset" Type="System.Int32" />
        <Parameter Name="lengthFile" Type="System.Int32" />
        <Parameter Name="client" Type="Microsoft.Azure.DataLake.Store.AdlsClient" />
        <Parameter Name="req" Type="Microsoft.Azure.DataLake.Store.RequestOptions" />
        <Parameter Name="resp" Type="Microsoft.Azure.DataLake.Store.OperationResponse" />
      </Parameters>
      <Docs>
        <param name="path"><span data-ttu-id="980d3-282">Pfad der Datei</span><span class="sxs-lookup"><span data-stu-id="980d3-282">Path of the file</span></span></param>
        <param name="sessionId"><span data-ttu-id="980d3-283">UUID, die verwendet wird, um den Handler für Dateien (Datenstrom) einfach auf den Server zu erhalten.</span><span class="sxs-lookup"><span data-stu-id="980d3-283">UUID that is used to obtain the file handler (stream) easily at server</span></span></param>
        <param name="offsetFile"><span data-ttu-id="980d3-284">Offset in der Datei, bei der Daten aus gelesen werden</span><span class="sxs-lookup"><span data-stu-id="980d3-284">Offset in the file at which data will be read from</span></span></param>
        <param name="buffer"> <span data-ttu-id="980d3-285">Puffer, in dem gelesenen Daten gespeichert werden soll</span><span class="sxs-lookup"><span data-stu-id="980d3-285">Buffer where data read will be stored</span></span></param>
        <param name="offset"><span data-ttu-id="980d3-286">Offset im Puffer, in dem Daten gelesen werden</span><span class="sxs-lookup"><span data-stu-id="980d3-286">Offset in buffer where data will be read</span></span></param>
        <param name="lengthFile"><span data-ttu-id="980d3-287">Länge der Daten gelesen werden</span><span class="sxs-lookup"><span data-stu-id="980d3-287">Length of the data to be read</span></span></param>
        <param name="client"><span data-ttu-id="980d3-288">ADLS-Client</span><span class="sxs-lookup"><span data-stu-id="980d3-288">ADLS Client</span></span></param>
        <param name="req"><span data-ttu-id="980d3-289">Optionen zum Ändern des Verhaltens der HTTP-Anforderung</span><span class="sxs-lookup"><span data-stu-id="980d3-289">Options to change behavior of the Http request</span></span> </param>
        <param name="resp"><span data-ttu-id="980d3-290">Speichert die Antwort/Ausgabe der HTTP-Anforderung</span><span class="sxs-lookup"><span data-stu-id="980d3-290">Stores the response/ouput of the Http request</span></span> </param>
        <summary>
            <span data-ttu-id="980d3-291">Liest eine Datei vom Server an.</span><span class="sxs-lookup"><span data-stu-id="980d3-291">Reads a file from server.</span></span> <span data-ttu-id="980d3-292">Dies ist die synchrone Operation.</span><span class="sxs-lookup"><span data-stu-id="980d3-292">This is synchronous operation.</span></span>
            </summary>
        <returns><span data-ttu-id="980d3-293">Anzahl der gelesenen bytes</span><span class="sxs-lookup"><span data-stu-id="980d3-293">Number of bytes read</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OpenAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;int&gt; OpenAsync (string path, string sessionId, long offsetFile, byte[] buffer, int offset, int lengthFile, Microsoft.Azure.DataLake.Store.AdlsClient client, Microsoft.Azure.DataLake.Store.RequestOptions req, Microsoft.Azure.DataLake.Store.OperationResponse resp, System.Threading.CancellationToken cancelToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;int32&gt; OpenAsync(string path, string sessionId, int64 offsetFile, unsigned int8[] buffer, int32 offset, int32 lengthFile, class Microsoft.Azure.DataLake.Store.AdlsClient client, class Microsoft.Azure.DataLake.Store.RequestOptions req, class Microsoft.Azure.DataLake.Store.OperationResponse resp, valuetype System.Threading.CancellationToken cancelToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.DataLake.Store.Core.OpenAsync(System.String,System.String,System.Int64,System.Byte[],System.Int32,System.Int32,Microsoft.Azure.DataLake.Store.AdlsClient,Microsoft.Azure.DataLake.Store.RequestOptions,Microsoft.Azure.DataLake.Store.OperationResponse,System.Threading.CancellationToken)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function OpenAsync (path As String, sessionId As String, offsetFile As Long, buffer As Byte(), offset As Integer, lengthFile As Integer, client As AdlsClient, req As RequestOptions, resp As OperationResponse, Optional cancelToken As CancellationToken = null) As Task(Of Integer)" />
      <MemberSignature Language="F#" Value="static member OpenAsync : string * string * int64 * byte[] * int * int * Microsoft.Azure.DataLake.Store.AdlsClient * Microsoft.Azure.DataLake.Store.RequestOptions * Microsoft.Azure.DataLake.Store.OperationResponse * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;int&gt;" Usage="Microsoft.Azure.DataLake.Store.Core.OpenAsync (path, sessionId, offsetFile, buffer, offset, lengthFile, client, req, resp, cancelToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DataLake.Store</AssemblyName>
        <AssemblyVersion>0.1.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.DataLake.Store.Core/&lt;OpenAsync&gt;d__10))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="path" Type="System.String" />
        <Parameter Name="sessionId" Type="System.String" />
        <Parameter Name="offsetFile" Type="System.Int64" />
        <Parameter Name="buffer" Type="System.Byte[]" />
        <Parameter Name="offset" Type="System.Int32" />
        <Parameter Name="lengthFile" Type="System.Int32" />
        <Parameter Name="client" Type="Microsoft.Azure.DataLake.Store.AdlsClient" />
        <Parameter Name="req" Type="Microsoft.Azure.DataLake.Store.RequestOptions" />
        <Parameter Name="resp" Type="Microsoft.Azure.DataLake.Store.OperationResponse" />
        <Parameter Name="cancelToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="path"><span data-ttu-id="980d3-294">Pfad der Datei</span><span class="sxs-lookup"><span data-stu-id="980d3-294">Path of the file</span></span></param>
        <param name="sessionId"><span data-ttu-id="980d3-295">UUID, die verwendet wird, um den Handler für Dateien (Datenstrom) einfach auf den Server zu erhalten.</span><span class="sxs-lookup"><span data-stu-id="980d3-295">UUID that is used to obtain the file handler (stream) easily at server</span></span></param>
        <param name="offsetFile"><span data-ttu-id="980d3-296">Offset in der Datei, bei der Daten aus gelesen werden</span><span class="sxs-lookup"><span data-stu-id="980d3-296">Offset in the file at which data will be read from</span></span></param>
        <param name="buffer"> <span data-ttu-id="980d3-297">Puffer, in dem gelesenen Daten gespeichert werden soll</span><span class="sxs-lookup"><span data-stu-id="980d3-297">Buffer where data read will be stored</span></span></param>
        <param name="offset"><span data-ttu-id="980d3-298">Offset im Puffer, in dem Daten gelesen werden</span><span class="sxs-lookup"><span data-stu-id="980d3-298">Offset in buffer where data will be read</span></span></param>
        <param name="lengthFile"><span data-ttu-id="980d3-299">Länge der Daten gelesen werden</span><span class="sxs-lookup"><span data-stu-id="980d3-299">Length of the data to be read</span></span></param>
        <param name="client"><span data-ttu-id="980d3-300">ADLS-Client</span><span class="sxs-lookup"><span data-stu-id="980d3-300">ADLS Client</span></span></param>
        <param name="req"><span data-ttu-id="980d3-301">Optionen zum Ändern des Verhaltens der HTTP-Anforderung</span><span class="sxs-lookup"><span data-stu-id="980d3-301">Options to change behavior of the Http request</span></span> </param>
        <param name="resp"><span data-ttu-id="980d3-302">Speichert die Antwort/Ausgabe der HTTP-Anforderung</span><span class="sxs-lookup"><span data-stu-id="980d3-302">Stores the response/ouput of the Http request</span></span> </param>
        <param name="cancelToken"><span data-ttu-id="980d3-303">CancellationToken, um die Anforderung abzubrechen</span><span class="sxs-lookup"><span data-stu-id="980d3-303">CancellationToken to cancel the request</span></span></param>
        <summary>
            <span data-ttu-id="980d3-304">Liest eine Datei vom Server an.</span><span class="sxs-lookup"><span data-stu-id="980d3-304">Reads a file from server.</span></span> <span data-ttu-id="980d3-305">Das ist ein asynchroner Vorgang.</span><span class="sxs-lookup"><span data-stu-id="980d3-305">This is an asynchronous operation.</span></span>
            </summary>
        <returns><span data-ttu-id="980d3-306">Anzahl der gelesenen bytes</span><span class="sxs-lookup"><span data-stu-id="980d3-306">Number of bytes read</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RemoveAclAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task RemoveAclAsync (string path, Microsoft.Azure.DataLake.Store.AdlsClient client, Microsoft.Azure.DataLake.Store.RequestOptions req, Microsoft.Azure.DataLake.Store.OperationResponse resp, System.Threading.CancellationToken cancelToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task RemoveAclAsync(string path, class Microsoft.Azure.DataLake.Store.AdlsClient client, class Microsoft.Azure.DataLake.Store.RequestOptions req, class Microsoft.Azure.DataLake.Store.OperationResponse resp, valuetype System.Threading.CancellationToken cancelToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.DataLake.Store.Core.RemoveAclAsync(System.String,Microsoft.Azure.DataLake.Store.AdlsClient,Microsoft.Azure.DataLake.Store.RequestOptions,Microsoft.Azure.DataLake.Store.OperationResponse,System.Threading.CancellationToken)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function RemoveAclAsync (path As String, client As AdlsClient, req As RequestOptions, resp As OperationResponse, Optional cancelToken As CancellationToken = null) As Task" />
      <MemberSignature Language="F#" Value="static member RemoveAclAsync : string * Microsoft.Azure.DataLake.Store.AdlsClient * Microsoft.Azure.DataLake.Store.RequestOptions * Microsoft.Azure.DataLake.Store.OperationResponse * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.DataLake.Store.Core.RemoveAclAsync (path, client, req, resp, cancelToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DataLake.Store</AssemblyName>
        <AssemblyVersion>0.1.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.DataLake.Store.Core/&lt;RemoveAclAsync&gt;d__31))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="path" Type="System.String" />
        <Parameter Name="client" Type="Microsoft.Azure.DataLake.Store.AdlsClient" />
        <Parameter Name="req" Type="Microsoft.Azure.DataLake.Store.RequestOptions" />
        <Parameter Name="resp" Type="Microsoft.Azure.DataLake.Store.OperationResponse" />
        <Parameter Name="cancelToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="path"><span data-ttu-id="980d3-307">Pfad der Datei oder des Verzeichnisses</span><span class="sxs-lookup"><span data-stu-id="980d3-307">Path of the file or directory</span></span></param>
        <param name="client"><span data-ttu-id="980d3-308">ADLS-Client</span><span class="sxs-lookup"><span data-stu-id="980d3-308">ADLS Client</span></span></param>
        <param name="req"><span data-ttu-id="980d3-309">Optionen zum Ändern des Verhaltens der HTTP-Anforderung</span><span class="sxs-lookup"><span data-stu-id="980d3-309">Options to change behavior of the Http request</span></span> </param>
        <param name="resp"><span data-ttu-id="980d3-310">Speichert die Antwort/Ausgabe der HTTP-Anforderung</span><span class="sxs-lookup"><span data-stu-id="980d3-310">Stores the response/ouput of the Http request</span></span> </param>
        <param name="cancelToken"><span data-ttu-id="980d3-311">CancellationToken, um die Anforderung abzubrechen</span><span class="sxs-lookup"><span data-stu-id="980d3-311">CancellationToken to cancel the request</span></span></param>
        <summary>
            <span data-ttu-id="980d3-312">Entfernt alle Acl-Einträge für eine Datei oder ein Verzeichnis an.</span><span class="sxs-lookup"><span data-stu-id="980d3-312">Removes all Acl Entries for a file or directory.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RemoveAclEntriesAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task RemoveAclEntriesAsync (string path, System.Collections.Generic.List&lt;Microsoft.Azure.DataLake.Store.Acl.AclEntry&gt; aclSpecList, Microsoft.Azure.DataLake.Store.AdlsClient client, Microsoft.Azure.DataLake.Store.RequestOptions req, Microsoft.Azure.DataLake.Store.OperationResponse resp, System.Threading.CancellationToken cancelToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task RemoveAclEntriesAsync(string path, class System.Collections.Generic.List`1&lt;class Microsoft.Azure.DataLake.Store.Acl.AclEntry&gt; aclSpecList, class Microsoft.Azure.DataLake.Store.AdlsClient client, class Microsoft.Azure.DataLake.Store.RequestOptions req, class Microsoft.Azure.DataLake.Store.OperationResponse resp, valuetype System.Threading.CancellationToken cancelToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.DataLake.Store.Core.RemoveAclEntriesAsync(System.String,System.Collections.Generic.List{Microsoft.Azure.DataLake.Store.Acl.AclEntry},Microsoft.Azure.DataLake.Store.AdlsClient,Microsoft.Azure.DataLake.Store.RequestOptions,Microsoft.Azure.DataLake.Store.OperationResponse,System.Threading.CancellationToken)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function RemoveAclEntriesAsync (path As String, aclSpecList As List(Of AclEntry), client As AdlsClient, req As RequestOptions, resp As OperationResponse, Optional cancelToken As CancellationToken = null) As Task" />
      <MemberSignature Language="F#" Value="static member RemoveAclEntriesAsync : string * System.Collections.Generic.List&lt;Microsoft.Azure.DataLake.Store.Acl.AclEntry&gt; * Microsoft.Azure.DataLake.Store.AdlsClient * Microsoft.Azure.DataLake.Store.RequestOptions * Microsoft.Azure.DataLake.Store.OperationResponse * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.DataLake.Store.Core.RemoveAclEntriesAsync (path, aclSpecList, client, req, resp, cancelToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DataLake.Store</AssemblyName>
        <AssemblyVersion>0.1.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.DataLake.Store.Core/&lt;RemoveAclEntriesAsync&gt;d__29))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="path" Type="System.String" />
        <Parameter Name="aclSpecList" Type="System.Collections.Generic.List&lt;Microsoft.Azure.DataLake.Store.Acl.AclEntry&gt;" />
        <Parameter Name="client" Type="Microsoft.Azure.DataLake.Store.AdlsClient" />
        <Parameter Name="req" Type="Microsoft.Azure.DataLake.Store.RequestOptions" />
        <Parameter Name="resp" Type="Microsoft.Azure.DataLake.Store.OperationResponse" />
        <Parameter Name="cancelToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="path"><span data-ttu-id="980d3-313">Pfad der Datei oder des Verzeichnisses</span><span class="sxs-lookup"><span data-stu-id="980d3-313">Path of the file or directory</span></span></param>
        <param name="aclSpecList"><span data-ttu-id="980d3-314">Liste der zu entfernenden Acl-Einträge</span><span class="sxs-lookup"><span data-stu-id="980d3-314">List of Acl Entries to remove</span></span></param>
        <param name="client"><span data-ttu-id="980d3-315">ADLS-Client</span><span class="sxs-lookup"><span data-stu-id="980d3-315">ADLS Client</span></span></param>
        <param name="req"><span data-ttu-id="980d3-316">Optionen zum Ändern des Verhaltens der HTTP-Anforderung</span><span class="sxs-lookup"><span data-stu-id="980d3-316">Options to change behavior of the Http request</span></span> </param>
        <param name="resp"><span data-ttu-id="980d3-317">Speichert die Antwort/Ausgabe der HTTP-Anforderung</span><span class="sxs-lookup"><span data-stu-id="980d3-317">Stores the response/ouput of the Http request</span></span> </param>
        <param name="cancelToken"><span data-ttu-id="980d3-318">CancellationToken, um die Anforderung abzubrechen</span><span class="sxs-lookup"><span data-stu-id="980d3-318">CancellationToken to cancel the request</span></span></param>
        <summary>
            <span data-ttu-id="980d3-319">Entfernt den angegebenen Acl-Einträge für eine Datei oder ein Verzeichnis.</span><span class="sxs-lookup"><span data-stu-id="980d3-319">Removes specified Acl Entries for a file or directory.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RemoveAclEntriesAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task RemoveAclEntriesAsync (string path, string aclSpec, Microsoft.Azure.DataLake.Store.AdlsClient client, Microsoft.Azure.DataLake.Store.RequestOptions req, Microsoft.Azure.DataLake.Store.OperationResponse resp, System.Threading.CancellationToken cancelToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task RemoveAclEntriesAsync(string path, string aclSpec, class Microsoft.Azure.DataLake.Store.AdlsClient client, class Microsoft.Azure.DataLake.Store.RequestOptions req, class Microsoft.Azure.DataLake.Store.OperationResponse resp, valuetype System.Threading.CancellationToken cancelToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.DataLake.Store.Core.RemoveAclEntriesAsync(System.String,System.String,Microsoft.Azure.DataLake.Store.AdlsClient,Microsoft.Azure.DataLake.Store.RequestOptions,Microsoft.Azure.DataLake.Store.OperationResponse,System.Threading.CancellationToken)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function RemoveAclEntriesAsync (path As String, aclSpec As String, client As AdlsClient, req As RequestOptions, resp As OperationResponse, Optional cancelToken As CancellationToken = null) As Task" />
      <MemberSignature Language="F#" Value="static member RemoveAclEntriesAsync : string * string * Microsoft.Azure.DataLake.Store.AdlsClient * Microsoft.Azure.DataLake.Store.RequestOptions * Microsoft.Azure.DataLake.Store.OperationResponse * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.DataLake.Store.Core.RemoveAclEntriesAsync (path, aclSpec, client, req, resp, cancelToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DataLake.Store</AssemblyName>
        <AssemblyVersion>0.1.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.DataLake.Store.Core/&lt;RemoveAclEntriesAsync&gt;d__28))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="path" Type="System.String" />
        <Parameter Name="aclSpec" Type="System.String" />
        <Parameter Name="client" Type="Microsoft.Azure.DataLake.Store.AdlsClient" />
        <Parameter Name="req" Type="Microsoft.Azure.DataLake.Store.RequestOptions" />
        <Parameter Name="resp" Type="Microsoft.Azure.DataLake.Store.OperationResponse" />
        <Parameter Name="cancelToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="path"><span data-ttu-id="980d3-320">Pfad der Datei oder des Verzeichnisses</span><span class="sxs-lookup"><span data-stu-id="980d3-320">Path of the file or directory</span></span></param>
        <param name="aclSpec"><span data-ttu-id="980d3-321">Zeichenfolge, die zu entfernenden Acl-Einträge enthält.</span><span class="sxs-lookup"><span data-stu-id="980d3-321">string containing Acl Entries to remove</span></span></param>
        <param name="client"><span data-ttu-id="980d3-322">ADLS-Client</span><span class="sxs-lookup"><span data-stu-id="980d3-322">ADLS Client</span></span></param>
        <param name="req"><span data-ttu-id="980d3-323">Optionen zum Ändern des Verhaltens der HTTP-Anforderung</span><span class="sxs-lookup"><span data-stu-id="980d3-323">Options to change behavior of the Http request</span></span> </param>
        <param name="resp"><span data-ttu-id="980d3-324">Speichert die Antwort/Ausgabe der HTTP-Anforderung</span><span class="sxs-lookup"><span data-stu-id="980d3-324">Stores the response/ouput of the Http request</span></span> </param>
        <param name="cancelToken"><span data-ttu-id="980d3-325">CancellationToken, um die Anforderung abzubrechen</span><span class="sxs-lookup"><span data-stu-id="980d3-325">CancellationToken to cancel the request</span></span></param>
        <summary>
            <span data-ttu-id="980d3-326">Entfernt den angegebenen Acl-Einträge für eine Datei oder ein Verzeichnis.</span><span class="sxs-lookup"><span data-stu-id="980d3-326">Removes specified Acl Entries for a file or directory.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RemoveDefaultAclAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task RemoveDefaultAclAsync (string path, Microsoft.Azure.DataLake.Store.AdlsClient client, Microsoft.Azure.DataLake.Store.RequestOptions req, Microsoft.Azure.DataLake.Store.OperationResponse resp, System.Threading.CancellationToken cancelToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task RemoveDefaultAclAsync(string path, class Microsoft.Azure.DataLake.Store.AdlsClient client, class Microsoft.Azure.DataLake.Store.RequestOptions req, class Microsoft.Azure.DataLake.Store.OperationResponse resp, valuetype System.Threading.CancellationToken cancelToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.DataLake.Store.Core.RemoveDefaultAclAsync(System.String,Microsoft.Azure.DataLake.Store.AdlsClient,Microsoft.Azure.DataLake.Store.RequestOptions,Microsoft.Azure.DataLake.Store.OperationResponse,System.Threading.CancellationToken)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function RemoveDefaultAclAsync (path As String, client As AdlsClient, req As RequestOptions, resp As OperationResponse, Optional cancelToken As CancellationToken = null) As Task" />
      <MemberSignature Language="F#" Value="static member RemoveDefaultAclAsync : string * Microsoft.Azure.DataLake.Store.AdlsClient * Microsoft.Azure.DataLake.Store.RequestOptions * Microsoft.Azure.DataLake.Store.OperationResponse * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.DataLake.Store.Core.RemoveDefaultAclAsync (path, client, req, resp, cancelToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DataLake.Store</AssemblyName>
        <AssemblyVersion>0.1.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.DataLake.Store.Core/&lt;RemoveDefaultAclAsync&gt;d__30))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="path" Type="System.String" />
        <Parameter Name="client" Type="Microsoft.Azure.DataLake.Store.AdlsClient" />
        <Parameter Name="req" Type="Microsoft.Azure.DataLake.Store.RequestOptions" />
        <Parameter Name="resp" Type="Microsoft.Azure.DataLake.Store.OperationResponse" />
        <Parameter Name="cancelToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="path"><span data-ttu-id="980d3-327">Pfad der Datei oder des Verzeichnisses</span><span class="sxs-lookup"><span data-stu-id="980d3-327">Path of the file or directory</span></span></param>
        <param name="client"><span data-ttu-id="980d3-328">ADLS-Client</span><span class="sxs-lookup"><span data-stu-id="980d3-328">ADLS Client</span></span></param>
        <param name="req"><span data-ttu-id="980d3-329">Optionen zum Ändern des Verhaltens der HTTP-Anforderung</span><span class="sxs-lookup"><span data-stu-id="980d3-329">Options to change behavior of the Http request</span></span> </param>
        <param name="resp"><span data-ttu-id="980d3-330">Speichert die Antwort/Ausgabe der HTTP-Anforderung</span><span class="sxs-lookup"><span data-stu-id="980d3-330">Stores the response/ouput of the Http request</span></span> </param>
        <param name="cancelToken"><span data-ttu-id="980d3-331">CancellationToken, um die Anforderung abzubrechen</span><span class="sxs-lookup"><span data-stu-id="980d3-331">CancellationToken to cancel the request</span></span></param>
        <summary>
            <span data-ttu-id="980d3-332">Entfernt alle Acl-Einträge des AclScope-Standard für eine Datei oder ein Verzeichnis an.</span><span class="sxs-lookup"><span data-stu-id="980d3-332">Removes all Acl Entries of AclScope default for a file or directory.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RenameAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;bool&gt; RenameAsync (string path, string destination, bool overwrite, Microsoft.Azure.DataLake.Store.AdlsClient client, Microsoft.Azure.DataLake.Store.RequestOptions req, Microsoft.Azure.DataLake.Store.OperationResponse resp, System.Threading.CancellationToken cancelToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;bool&gt; RenameAsync(string path, string destination, bool overwrite, class Microsoft.Azure.DataLake.Store.AdlsClient client, class Microsoft.Azure.DataLake.Store.RequestOptions req, class Microsoft.Azure.DataLake.Store.OperationResponse resp, valuetype System.Threading.CancellationToken cancelToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.DataLake.Store.Core.RenameAsync(System.String,System.String,System.Boolean,Microsoft.Azure.DataLake.Store.AdlsClient,Microsoft.Azure.DataLake.Store.RequestOptions,Microsoft.Azure.DataLake.Store.OperationResponse,System.Threading.CancellationToken)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function RenameAsync (path As String, destination As String, overwrite As Boolean, client As AdlsClient, req As RequestOptions, resp As OperationResponse, Optional cancelToken As CancellationToken = null) As Task(Of Boolean)" />
      <MemberSignature Language="F#" Value="static member RenameAsync : string * string * bool * Microsoft.Azure.DataLake.Store.AdlsClient * Microsoft.Azure.DataLake.Store.RequestOptions * Microsoft.Azure.DataLake.Store.OperationResponse * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;bool&gt;" Usage="Microsoft.Azure.DataLake.Store.Core.RenameAsync (path, destination, overwrite, client, req, resp, cancelToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DataLake.Store</AssemblyName>
        <AssemblyVersion>0.1.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.DataLake.Store.Core/&lt;RenameAsync&gt;d__14))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="path" Type="System.String" />
        <Parameter Name="destination" Type="System.String" />
        <Parameter Name="overwrite" Type="System.Boolean" />
        <Parameter Name="client" Type="Microsoft.Azure.DataLake.Store.AdlsClient" />
        <Parameter Name="req" Type="Microsoft.Azure.DataLake.Store.RequestOptions" />
        <Parameter Name="resp" Type="Microsoft.Azure.DataLake.Store.OperationResponse" />
        <Parameter Name="cancelToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="path"><span data-ttu-id="980d3-333">Pfad der Quelldatei oder des Verzeichnisses</span><span class="sxs-lookup"><span data-stu-id="980d3-333">Path of the source file or directory</span></span></param>
        <param name="destination"><span data-ttu-id="980d3-334">Zielpfad</span><span class="sxs-lookup"><span data-stu-id="980d3-334">Destination path</span></span></param>
        <param name="overwrite"><span data-ttu-id="980d3-335">Für die Datei: Wenn "true" klicken Sie dann die Zieldatei überschreibt, sofern für Verzeichnis vorhanden: Wenn das Zielverzeichnis vorhanden ist, hat dieses Flag keine.</span><span class="sxs-lookup"><span data-stu-id="980d3-335">For file: If true then overwrites the destination file if it exists For directory: If the destination directory exists, then this flag has no use.</span></span> <span data-ttu-id="980d3-336">Da es die Quelle eine Ebene unter Ziel versetzt.</span><span class="sxs-lookup"><span data-stu-id="980d3-336">Because it puts the source one level under destination.</span></span>
                                    <span data-ttu-id="980d3-337">Wenn ein Unterverzeichnis mit demselben Namen wie eine Ebene unter der Zielpfad der Datenquelle vorhanden ist, hat dieses Flag keine verwenden.</span><span class="sxs-lookup"><span data-stu-id="980d3-337">If there is a subdirectory with same name as source one level under the destination path, this flag has no use.</span></span> <span data-ttu-id="980d3-338">Benennen Sie ein Fehler auftritt</span><span class="sxs-lookup"><span data-stu-id="980d3-338">Rename fails</span></span>  </param>
        <param name="client"><span data-ttu-id="980d3-339">ADLS-Client</span><span class="sxs-lookup"><span data-stu-id="980d3-339">ADLS Client</span></span></param>
        <param name="req"><span data-ttu-id="980d3-340">Optionen zum Ändern des Verhaltens der HTTP-Anforderung</span><span class="sxs-lookup"><span data-stu-id="980d3-340">Options to change behavior of the Http request</span></span> </param>
        <param name="resp"><span data-ttu-id="980d3-341">Speichert die Antwort/Ausgabe der HTTP-Anforderung</span><span class="sxs-lookup"><span data-stu-id="980d3-341">Stores the response/ouput of the Http request</span></span> </param>
        <param name="cancelToken"><span data-ttu-id="980d3-342">CancellationToken, um die Anforderung abzubrechen</span><span class="sxs-lookup"><span data-stu-id="980d3-342">CancellationToken to cancel the request</span></span></param>
        <summary>
            <span data-ttu-id="980d3-343">Benennt einen Pfad an.</span><span class="sxs-lookup"><span data-stu-id="980d3-343">Renames a path.</span></span>
            <span data-ttu-id="980d3-344">Zum Umbenennen des Verzeichnisses: Wenn das Ziel vorhanden ist, dann er die Quelle eine Ebene unter dem Ziel legt.</span><span class="sxs-lookup"><span data-stu-id="980d3-344">For renaming directory: If the destination exists then it puts the source directory one level under the destination.</span></span>
            </summary>
        <returns><span data-ttu-id="980d3-345">True, wenn die Umbenennung erfolgreich, andernfalls "false" ist.</span><span class="sxs-lookup"><span data-stu-id="980d3-345">True if rename is successful else false</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SetAclAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task SetAclAsync (string path, System.Collections.Generic.List&lt;Microsoft.Azure.DataLake.Store.Acl.AclEntry&gt; aclSpecList, Microsoft.Azure.DataLake.Store.AdlsClient client, Microsoft.Azure.DataLake.Store.RequestOptions req, Microsoft.Azure.DataLake.Store.OperationResponse resp, System.Threading.CancellationToken cancelToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task SetAclAsync(string path, class System.Collections.Generic.List`1&lt;class Microsoft.Azure.DataLake.Store.Acl.AclEntry&gt; aclSpecList, class Microsoft.Azure.DataLake.Store.AdlsClient client, class Microsoft.Azure.DataLake.Store.RequestOptions req, class Microsoft.Azure.DataLake.Store.OperationResponse resp, valuetype System.Threading.CancellationToken cancelToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.DataLake.Store.Core.SetAclAsync(System.String,System.Collections.Generic.List{Microsoft.Azure.DataLake.Store.Acl.AclEntry},Microsoft.Azure.DataLake.Store.AdlsClient,Microsoft.Azure.DataLake.Store.RequestOptions,Microsoft.Azure.DataLake.Store.OperationResponse,System.Threading.CancellationToken)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function SetAclAsync (path As String, aclSpecList As List(Of AclEntry), client As AdlsClient, req As RequestOptions, resp As OperationResponse, Optional cancelToken As CancellationToken = null) As Task" />
      <MemberSignature Language="F#" Value="static member SetAclAsync : string * System.Collections.Generic.List&lt;Microsoft.Azure.DataLake.Store.Acl.AclEntry&gt; * Microsoft.Azure.DataLake.Store.AdlsClient * Microsoft.Azure.DataLake.Store.RequestOptions * Microsoft.Azure.DataLake.Store.OperationResponse * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.DataLake.Store.Core.SetAclAsync (path, aclSpecList, client, req, resp, cancelToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DataLake.Store</AssemblyName>
        <AssemblyVersion>0.1.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.DataLake.Store.Core/&lt;SetAclAsync&gt;d__27))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="path" Type="System.String" />
        <Parameter Name="aclSpecList" Type="System.Collections.Generic.List&lt;Microsoft.Azure.DataLake.Store.Acl.AclEntry&gt;" />
        <Parameter Name="client" Type="Microsoft.Azure.DataLake.Store.AdlsClient" />
        <Parameter Name="req" Type="Microsoft.Azure.DataLake.Store.RequestOptions" />
        <Parameter Name="resp" Type="Microsoft.Azure.DataLake.Store.OperationResponse" />
        <Parameter Name="cancelToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="path"><span data-ttu-id="980d3-346">Pfad der Datei oder des Verzeichnisses</span><span class="sxs-lookup"><span data-stu-id="980d3-346">Path of the file or directory</span></span></param>
        <param name="aclSpecList"><span data-ttu-id="980d3-347">Liste der Acl-Einträge festlegen</span><span class="sxs-lookup"><span data-stu-id="980d3-347">List of Acl Entries to set</span></span> </param>
        <param name="client"><span data-ttu-id="980d3-348">ADLS-Client</span><span class="sxs-lookup"><span data-stu-id="980d3-348">ADLS Client</span></span></param>
        <param name="req"><span data-ttu-id="980d3-349">Optionen zum Ändern des Verhaltens der HTTP-Anforderung</span><span class="sxs-lookup"><span data-stu-id="980d3-349">Options to change behavior of the Http request</span></span> </param>
        <param name="resp"><span data-ttu-id="980d3-350">Speichert die Antwort/Ausgabe der HTTP-Anforderung</span><span class="sxs-lookup"><span data-stu-id="980d3-350">Stores the response/ouput of the Http request</span></span> </param>
        <param name="cancelToken"><span data-ttu-id="980d3-351">CancellationToken, um die Anforderung abzubrechen</span><span class="sxs-lookup"><span data-stu-id="980d3-351">CancellationToken to cancel the request</span></span></param>
        <summary>
            <span data-ttu-id="980d3-352">Legt die Acl-Einträge für eine Datei oder ein Verzeichnis fest.</span><span class="sxs-lookup"><span data-stu-id="980d3-352">Sets Acl Entries for a file or directory.</span></span> <span data-ttu-id="980d3-353">Es werden die vorhandenen Acl-Einträge für den Pfad.</span><span class="sxs-lookup"><span data-stu-id="980d3-353">It wipes out the existing Acl entries for the path.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SetAclAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task SetAclAsync (string path, string aclSpec, Microsoft.Azure.DataLake.Store.AdlsClient client, Microsoft.Azure.DataLake.Store.RequestOptions req, Microsoft.Azure.DataLake.Store.OperationResponse resp, System.Threading.CancellationToken cancelToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task SetAclAsync(string path, string aclSpec, class Microsoft.Azure.DataLake.Store.AdlsClient client, class Microsoft.Azure.DataLake.Store.RequestOptions req, class Microsoft.Azure.DataLake.Store.OperationResponse resp, valuetype System.Threading.CancellationToken cancelToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.DataLake.Store.Core.SetAclAsync(System.String,System.String,Microsoft.Azure.DataLake.Store.AdlsClient,Microsoft.Azure.DataLake.Store.RequestOptions,Microsoft.Azure.DataLake.Store.OperationResponse,System.Threading.CancellationToken)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function SetAclAsync (path As String, aclSpec As String, client As AdlsClient, req As RequestOptions, resp As OperationResponse, Optional cancelToken As CancellationToken = null) As Task" />
      <MemberSignature Language="F#" Value="static member SetAclAsync : string * string * Microsoft.Azure.DataLake.Store.AdlsClient * Microsoft.Azure.DataLake.Store.RequestOptions * Microsoft.Azure.DataLake.Store.OperationResponse * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.DataLake.Store.Core.SetAclAsync (path, aclSpec, client, req, resp, cancelToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DataLake.Store</AssemblyName>
        <AssemblyVersion>0.1.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.DataLake.Store.Core/&lt;SetAclAsync&gt;d__26))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="path" Type="System.String" />
        <Parameter Name="aclSpec" Type="System.String" />
        <Parameter Name="client" Type="Microsoft.Azure.DataLake.Store.AdlsClient" />
        <Parameter Name="req" Type="Microsoft.Azure.DataLake.Store.RequestOptions" />
        <Parameter Name="resp" Type="Microsoft.Azure.DataLake.Store.OperationResponse" />
        <Parameter Name="cancelToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="path"><span data-ttu-id="980d3-354">Pfad der Datei oder des Verzeichnisses</span><span class="sxs-lookup"><span data-stu-id="980d3-354">Path of the file or directory</span></span></param>
        <param name="aclSpec"><span data-ttu-id="980d3-355">AclSpec-Zeichenfolge, die ACL-Einträge durch Komma getrennt enthält</span><span class="sxs-lookup"><span data-stu-id="980d3-355">AclSpec string that contains the ACL entries delimited by comma</span></span> </param>
        <param name="client"><span data-ttu-id="980d3-356">ADLS-Client</span><span class="sxs-lookup"><span data-stu-id="980d3-356">ADLS Client</span></span></param>
        <param name="req"><span data-ttu-id="980d3-357">Optionen zum Ändern des Verhaltens der HTTP-Anforderung</span><span class="sxs-lookup"><span data-stu-id="980d3-357">Options to change behavior of the Http request</span></span> </param>
        <param name="resp"><span data-ttu-id="980d3-358">Speichert die Antwort/Ausgabe der HTTP-Anforderung</span><span class="sxs-lookup"><span data-stu-id="980d3-358">Stores the response/ouput of the Http request</span></span> </param>
        <param name="cancelToken"><span data-ttu-id="980d3-359">CancellationToken, um die Anforderung abzubrechen</span><span class="sxs-lookup"><span data-stu-id="980d3-359">CancellationToken to cancel the request</span></span></param>
        <summary>
            <span data-ttu-id="980d3-360">Legt die Acl-Einträge für eine Datei oder ein Verzeichnis fest.</span><span class="sxs-lookup"><span data-stu-id="980d3-360">Sets Acl Entries for a file or directory.</span></span> <span data-ttu-id="980d3-361">Es werden die vorhandenen Acl-Einträge für den Pfad.</span><span class="sxs-lookup"><span data-stu-id="980d3-361">It wipes out the existing Acl entries for the path.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SetExpiryTimeAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task SetExpiryTimeAsync (string path, Microsoft.Azure.DataLake.Store.ExpiryOption opt, long expiryTime, Microsoft.Azure.DataLake.Store.AdlsClient client, Microsoft.Azure.DataLake.Store.RequestOptions req, Microsoft.Azure.DataLake.Store.OperationResponse resp, System.Threading.CancellationToken cancelToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task SetExpiryTimeAsync(string path, valuetype Microsoft.Azure.DataLake.Store.ExpiryOption opt, int64 expiryTime, class Microsoft.Azure.DataLake.Store.AdlsClient client, class Microsoft.Azure.DataLake.Store.RequestOptions req, class Microsoft.Azure.DataLake.Store.OperationResponse resp, valuetype System.Threading.CancellationToken cancelToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.DataLake.Store.Core.SetExpiryTimeAsync(System.String,Microsoft.Azure.DataLake.Store.ExpiryOption,System.Int64,Microsoft.Azure.DataLake.Store.AdlsClient,Microsoft.Azure.DataLake.Store.RequestOptions,Microsoft.Azure.DataLake.Store.OperationResponse,System.Threading.CancellationToken)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function SetExpiryTimeAsync (path As String, opt As ExpiryOption, expiryTime As Long, client As AdlsClient, req As RequestOptions, resp As OperationResponse, Optional cancelToken As CancellationToken = null) As Task" />
      <MemberSignature Language="F#" Value="static member SetExpiryTimeAsync : string * Microsoft.Azure.DataLake.Store.ExpiryOption * int64 * Microsoft.Azure.DataLake.Store.AdlsClient * Microsoft.Azure.DataLake.Store.RequestOptions * Microsoft.Azure.DataLake.Store.OperationResponse * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.DataLake.Store.Core.SetExpiryTimeAsync (path, opt, expiryTime, client, req, resp, cancelToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DataLake.Store</AssemblyName>
        <AssemblyVersion>0.1.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.DataLake.Store.Core/&lt;SetExpiryTimeAsync&gt;d__19))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="path" Type="System.String" />
        <Parameter Name="opt" Type="Microsoft.Azure.DataLake.Store.ExpiryOption" />
        <Parameter Name="expiryTime" Type="System.Int64" />
        <Parameter Name="client" Type="Microsoft.Azure.DataLake.Store.AdlsClient" />
        <Parameter Name="req" Type="Microsoft.Azure.DataLake.Store.RequestOptions" />
        <Parameter Name="resp" Type="Microsoft.Azure.DataLake.Store.OperationResponse" />
        <Parameter Name="cancelToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="path"><span data-ttu-id="980d3-362">Pfad der Datei</span><span class="sxs-lookup"><span data-stu-id="980d3-362">Path of the file</span></span></param>
        <param name="opt"><span data-ttu-id="980d3-363">Andere Art von Ablauf-Methode, z. B.: nie ablaufen soll, relativ zum jetzt usw., die definiert, wie Sie ExpiryTime auswerten</span><span class="sxs-lookup"><span data-stu-id="980d3-363">Different type of expiry method for example: never expire, relative to now, etc that defines how to evaluate expiryTime</span></span></param>
        <param name="expiryTime"><span data-ttu-id="980d3-364">Nach Ablauf der Zeitwert.</span><span class="sxs-lookup"><span data-stu-id="980d3-364">Expiry time value.</span></span> <span data-ttu-id="980d3-365">Der Interepreation abhängig ist, auf welche Benutzer ExpiryOption übergibt</span><span class="sxs-lookup"><span data-stu-id="980d3-365">It's interepreation depends on what ExpiryOption user passes</span></span></param>
        <param name="client"><span data-ttu-id="980d3-366">ADLS-Client</span><span class="sxs-lookup"><span data-stu-id="980d3-366">ADLS Client</span></span></param>
        <param name="req"><span data-ttu-id="980d3-367">Optionen zum Ändern des Verhaltens der HTTP-Anforderung</span><span class="sxs-lookup"><span data-stu-id="980d3-367">Options to change behavior of the Http request</span></span> </param>
        <param name="resp"><span data-ttu-id="980d3-368">Speichert die Antwort/Ausgabe der HTTP-Anforderung</span><span class="sxs-lookup"><span data-stu-id="980d3-368">Stores the response/ouput of the Http request</span></span> </param>
        <param name="cancelToken"><span data-ttu-id="980d3-369">CancellationToken, um die Anforderung abzubrechen</span><span class="sxs-lookup"><span data-stu-id="980d3-369">CancellationToken to cancel the request</span></span></param>
        <summary>
            <span data-ttu-id="980d3-370">Legen Sie die Ablaufzeit</span><span class="sxs-lookup"><span data-stu-id="980d3-370">Set the expiry time</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SetOwnerAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task SetOwnerAsync (string path, string user, string group, Microsoft.Azure.DataLake.Store.AdlsClient client, Microsoft.Azure.DataLake.Store.RequestOptions req, Microsoft.Azure.DataLake.Store.OperationResponse resp, System.Threading.CancellationToken cancelToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task SetOwnerAsync(string path, string user, string group, class Microsoft.Azure.DataLake.Store.AdlsClient client, class Microsoft.Azure.DataLake.Store.RequestOptions req, class Microsoft.Azure.DataLake.Store.OperationResponse resp, valuetype System.Threading.CancellationToken cancelToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.DataLake.Store.Core.SetOwnerAsync(System.String,System.String,System.String,Microsoft.Azure.DataLake.Store.AdlsClient,Microsoft.Azure.DataLake.Store.RequestOptions,Microsoft.Azure.DataLake.Store.OperationResponse,System.Threading.CancellationToken)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function SetOwnerAsync (path As String, user As String, group As String, client As AdlsClient, req As RequestOptions, resp As OperationResponse, Optional cancelToken As CancellationToken = null) As Task" />
      <MemberSignature Language="F#" Value="static member SetOwnerAsync : string * string * string * Microsoft.Azure.DataLake.Store.AdlsClient * Microsoft.Azure.DataLake.Store.RequestOptions * Microsoft.Azure.DataLake.Store.OperationResponse * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.DataLake.Store.Core.SetOwnerAsync (path, user, group, client, req, resp, cancelToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DataLake.Store</AssemblyName>
        <AssemblyVersion>0.1.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.DataLake.Store.Core/&lt;SetOwnerAsync&gt;d__22))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="path" Type="System.String" />
        <Parameter Name="user" Type="System.String" />
        <Parameter Name="group" Type="System.String" />
        <Parameter Name="client" Type="Microsoft.Azure.DataLake.Store.AdlsClient" />
        <Parameter Name="req" Type="Microsoft.Azure.DataLake.Store.RequestOptions" />
        <Parameter Name="resp" Type="Microsoft.Azure.DataLake.Store.OperationResponse" />
        <Parameter Name="cancelToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="path"><span data-ttu-id="980d3-371">Pfad der Datei oder eines Verzeichnisses</span><span class="sxs-lookup"><span data-stu-id="980d3-371">Path of file or directory</span></span></param>
        <param name="user"><span data-ttu-id="980d3-372">Besitzer-Id des Pfads</span><span class="sxs-lookup"><span data-stu-id="980d3-372">Owner Id of the path</span></span></param>
        <param name="group"><span data-ttu-id="980d3-373">Gruppen-Id des Pfads</span><span class="sxs-lookup"><span data-stu-id="980d3-373">Group Id of the path</span></span></param>
        <param name="client"><span data-ttu-id="980d3-374">ADLS-Client</span><span class="sxs-lookup"><span data-stu-id="980d3-374">ADLS Client</span></span></param>
        <param name="req"><span data-ttu-id="980d3-375">Optionen zum Ändern des Verhaltens der HTTP-Anforderung</span><span class="sxs-lookup"><span data-stu-id="980d3-375">Options to change behavior of the Http request</span></span> </param>
        <param name="resp"><span data-ttu-id="980d3-376">Speichert die Antwort/Ausgabe der HTTP-Anforderung</span><span class="sxs-lookup"><span data-stu-id="980d3-376">Stores the response/ouput of the Http request</span></span> </param>
        <param name="cancelToken"><span data-ttu-id="980d3-377">CancellationToken, um die Anforderung abzubrechen</span><span class="sxs-lookup"><span data-stu-id="980d3-377">CancellationToken to cancel the request</span></span></param>
        <summary>
            <span data-ttu-id="980d3-378">Legt den Besitzer oder / und des Pfads</span><span class="sxs-lookup"><span data-stu-id="980d3-378">Sets the owner or/and group of the path</span></span>
            </summary>
        <returns />
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SetPermissionAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task SetPermissionAsync (string path, string permission, Microsoft.Azure.DataLake.Store.AdlsClient client, Microsoft.Azure.DataLake.Store.RequestOptions req, Microsoft.Azure.DataLake.Store.OperationResponse resp, System.Threading.CancellationToken cancelToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task SetPermissionAsync(string path, string permission, class Microsoft.Azure.DataLake.Store.AdlsClient client, class Microsoft.Azure.DataLake.Store.RequestOptions req, class Microsoft.Azure.DataLake.Store.OperationResponse resp, valuetype System.Threading.CancellationToken cancelToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.DataLake.Store.Core.SetPermissionAsync(System.String,System.String,Microsoft.Azure.DataLake.Store.AdlsClient,Microsoft.Azure.DataLake.Store.RequestOptions,Microsoft.Azure.DataLake.Store.OperationResponse,System.Threading.CancellationToken)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function SetPermissionAsync (path As String, permission As String, client As AdlsClient, req As RequestOptions, resp As OperationResponse, Optional cancelToken As CancellationToken = null) As Task" />
      <MemberSignature Language="F#" Value="static member SetPermissionAsync : string * string * Microsoft.Azure.DataLake.Store.AdlsClient * Microsoft.Azure.DataLake.Store.RequestOptions * Microsoft.Azure.DataLake.Store.OperationResponse * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.DataLake.Store.Core.SetPermissionAsync (path, permission, client, req, resp, cancelToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DataLake.Store</AssemblyName>
        <AssemblyVersion>0.1.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.DataLake.Store.Core/&lt;SetPermissionAsync&gt;d__21))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="path" Type="System.String" />
        <Parameter Name="permission" Type="System.String" />
        <Parameter Name="client" Type="Microsoft.Azure.DataLake.Store.AdlsClient" />
        <Parameter Name="req" Type="Microsoft.Azure.DataLake.Store.RequestOptions" />
        <Parameter Name="resp" Type="Microsoft.Azure.DataLake.Store.OperationResponse" />
        <Parameter Name="cancelToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="path"><span data-ttu-id="980d3-379">Pfad der Datei oder des Verzeichnisses</span><span class="sxs-lookup"><span data-stu-id="980d3-379">Path of the file or directory</span></span></param>
        <param name="permission"><span data-ttu-id="980d3-380">Berechtigung für das Einchecken oktale Unix-Format.</span><span class="sxs-lookup"><span data-stu-id="980d3-380">Permission to check in unix octal form.</span></span> <span data-ttu-id="980d3-381">Z. B., ob der Benutzer möchte, um festzustellen, ob der Besitzer gelesen hat schreiben execute-Berechtigung, alle Gruppen über die Schreibberechtigung Lese- und andere hat, dass die Berechtigung der Zeichenfolge 741 wäre lesen</span><span class="sxs-lookup"><span data-stu-id="980d3-381">For example if the user wants to see if owner has read, write execute permission, all groups has read write permission and others has read permission the string would be 741</span></span> </param>
        <param name="client"><span data-ttu-id="980d3-382">ADLS-Client</span><span class="sxs-lookup"><span data-stu-id="980d3-382">ADLS Client</span></span></param>
        <param name="req"><span data-ttu-id="980d3-383">Optionen zum Ändern des Verhaltens der HTTP-Anforderung</span><span class="sxs-lookup"><span data-stu-id="980d3-383">Options to change behavior of the Http request</span></span> </param>
        <param name="resp"><span data-ttu-id="980d3-384">Speichert die Antwort/Ausgabe der HTTP-Anforderung</span><span class="sxs-lookup"><span data-stu-id="980d3-384">Stores the response/ouput of the Http request</span></span> </param>
        <param name="cancelToken"><span data-ttu-id="980d3-385">CancellationToken, um die Anforderung abzubrechen</span><span class="sxs-lookup"><span data-stu-id="980d3-385">CancellationToken to cancel the request</span></span></param>
        <summary>
            <span data-ttu-id="980d3-386">Die Berechtigungssätze des angegebenen Pfads.</span><span class="sxs-lookup"><span data-stu-id="980d3-386">Sets the permission of the specified path</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>