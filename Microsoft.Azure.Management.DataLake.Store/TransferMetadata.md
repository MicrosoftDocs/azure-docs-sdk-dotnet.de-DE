<Type Name="TransferMetadata" FullName="Microsoft.Azure.Management.DataLake.Store.TransferMetadata">
  <TypeSignature Language="C#" Value="public class TransferMetadata" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit TransferMetadata extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.DataLake.Store.TransferMetadata" />
  <TypeSignature Language="VB.NET" Value="Public Class TransferMetadata" />
  <TypeSignature Language="F#" Value="type TransferMetadata = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.DataLake.Store</AssemblyName>
    <AssemblyVersion>2.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Attributes>
    <Attribute>
      <AttributeName>System.Diagnostics.DebuggerDisplay("Segments = {SegmentCount}, SegmentLength = {SegmentLength}, TransferId = {TransferId}, FileLength = {FileLength}, FilePath = {FilePath}, EncodingCodePage = {EncodingCodePage}, Delimiter = {Delimiter}")</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            <span data-ttu-id="88023-101">Allgemeine Metadaten, die für eine Übertragung darstellt.</span><span class="sxs-lookup"><span data-stu-id="88023-101">Represents general metadata pertaining to an transfer.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="DeleteFile">
      <MemberSignature Language="C#" Value="public void DeleteFile ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance void DeleteFile() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Store.TransferMetadata.DeleteFile" />
      <MemberSignature Language="VB.NET" Value="Public Sub DeleteFile ()" />
      <MemberSignature Language="F#" Value="member this.DeleteFile : unit -&gt; unit" Usage="transferMetadata.DeleteFile " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Store</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="88023-102">Löscht die Metadatendatei vom Datenträger.</span><span class="sxs-lookup"><span data-stu-id="88023-102">Deletes the metadata file from disk.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:System.InvalidOperationException"><span data-ttu-id="88023-103">MetadataFilePath von NULL oder leer sein.</span><span class="sxs-lookup"><span data-stu-id="88023-103">Null or empty MetadataFilePath.</span></span> <span data-ttu-id="88023-104">Metadaten können nicht gelöscht werden, bis diese Eigenschaft festgelegt wird.</span><span class="sxs-lookup"><span data-stu-id="88023-104">Cannot delete metadata until this property is set.</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName="Delimiter">
      <MemberSignature Language="C#" Value="public string Delimiter { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Delimiter" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataLake.Store.TransferMetadata.Delimiter" />
      <MemberSignature Language="VB.NET" Value="Public Property Delimiter As String" />
      <MemberSignature Language="F#" Value="member this.Delimiter : string with get, set" Usage="Microsoft.Azure.Management.DataLake.Store.TransferMetadata.Delimiter" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Store</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="Delimiter")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="88023-105">Ruft einen Wert, der angibt, des Trennzeichens Datensatz Grenze für die Datei ab, sofern vorhanden.</span><span class="sxs-lookup"><span data-stu-id="88023-105">Gets a value indicating the record boundary delimiter for the file, if any.</span></span>
            </summary>
        <value>
            <span data-ttu-id="88023-106">Das Trennzeichen Datensatz Grenze</span><span class="sxs-lookup"><span data-stu-id="88023-106">The record boundary delimiter</span></span>
            </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EncodingCodePage">
      <MemberSignature Language="C#" Value="public int EncodingCodePage { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 EncodingCodePage" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataLake.Store.TransferMetadata.EncodingCodePage" />
      <MemberSignature Language="VB.NET" Value="Public Property EncodingCodePage As Integer" />
      <MemberSignature Language="F#" Value="member this.EncodingCodePage : int with get, set" Usage="Microsoft.Azure.Management.DataLake.Store.TransferMetadata.EncodingCodePage" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Store</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="EncodingCodePage")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="88023-107">Die CodePage der aktuellen Codierung ruft verwendet wird.</span><span class="sxs-lookup"><span data-stu-id="88023-107">Gets the CodePage of the current encoding being used.</span></span>
            </summary>
        <value>
             <span data-ttu-id="88023-108">Die CodePage der aktuellen Codierung.</span><span class="sxs-lookup"><span data-stu-id="88023-108">The CodePage of the current encoding.</span></span>
            </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="FileLength">
      <MemberSignature Language="C#" Value="public long FileLength { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 FileLength" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataLake.Store.TransferMetadata.FileLength" />
      <MemberSignature Language="VB.NET" Value="Public Property FileLength As Long" />
      <MemberSignature Language="F#" Value="member this.FileLength : int64 with get, set" Usage="Microsoft.Azure.Management.DataLake.Store.TransferMetadata.FileLength" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Store</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="FileLength")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Int64</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="88023-109">Ruft ab oder legt einen Wert, der angibt, der Länge (in Bytes) der Datei, die übertragen werden.</span><span class="sxs-lookup"><span data-stu-id="88023-109">Gets or sets a value indicating the length (in bytes) of the file to be transferred.</span></span>
            </summary>
        <value>
            <span data-ttu-id="88023-110">Die Länge der Datei.</span><span class="sxs-lookup"><span data-stu-id="88023-110">The length of the file.</span></span>
            </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="InputFilePath">
      <MemberSignature Language="C#" Value="public string InputFilePath { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string InputFilePath" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataLake.Store.TransferMetadata.InputFilePath" />
      <MemberSignature Language="VB.NET" Value="Public Property InputFilePath As String" />
      <MemberSignature Language="F#" Value="member this.InputFilePath : string with get, set" Usage="Microsoft.Azure.Management.DataLake.Store.TransferMetadata.InputFilePath" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Store</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="InputFilePath")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="88023-111">/ Ruft ab oder legt einen Wert, der angibt, des vollständigen Pfads zu der Datei, die übertragen werden.</span><span class="sxs-lookup"><span data-stu-id="88023-111">/Gets or sets a value indicating the full path to the file to be transferred.</span></span>
            </summary>
        <value>
            <span data-ttu-id="88023-112">Der Pfad der Eingabedatei.</span><span class="sxs-lookup"><span data-stu-id="88023-112">The input file path.</span></span>
            </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IsBinary">
      <MemberSignature Language="C#" Value="public bool IsBinary { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool IsBinary" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataLake.Store.TransferMetadata.IsBinary" />
      <MemberSignature Language="VB.NET" Value="Public Property IsBinary As Boolean" />
      <MemberSignature Language="F#" Value="member this.IsBinary : bool with get, set" Usage="Microsoft.Azure.Management.DataLake.Store.TransferMetadata.IsBinary" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Store</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="IsBinary")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="88023-113">Ruft einen Wert, der angibt, ob die Übertragungsdatei als Binärdatei sollen oder nicht behandelt werden.</span><span class="sxs-lookup"><span data-stu-id="88023-113">Gets a value indicating whether the transfer file should be treated as a binary file or not.</span></span>
            </summary>
        <value>
          <span data-ttu-id="88023-114"><c>"true"</c> Wenn diese Instanz binär ist, andernfalls ist <c>"false"</c>.</span><span class="sxs-lookup"><span data-stu-id="88023-114"><c>true</c> if this instance is binary; otherwise, <c>false</c>.</span></span>
            </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IsDownload">
      <MemberSignature Language="C#" Value="public bool IsDownload { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool IsDownload" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataLake.Store.TransferMetadata.IsDownload" />
      <MemberSignature Language="VB.NET" Value="Public Property IsDownload As Boolean" />
      <MemberSignature Language="F#" Value="member this.IsDownload : bool with get, set" Usage="Microsoft.Azure.Management.DataLake.Store.TransferMetadata.IsDownload" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Store</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="IsDownload")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="88023-115">Ruft ab oder legt einen Wert, der angibt, ob diese Instanz ein Download, anstatt eine Übertragung fest.</span><span class="sxs-lookup"><span data-stu-id="88023-115">Gets or sets a value indicating whether this instance is a download instead of an transfer.</span></span>
            </summary>
        <value>
          <span data-ttu-id="88023-116"><c>"true"</c> Wenn diese Instanz Download; andernfalls <c>"false"</c>.</span><span class="sxs-lookup"><span data-stu-id="88023-116"><c>true</c> if this instance is download; otherwise, <c>false</c>.</span></span>
            </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SegmentCount">
      <MemberSignature Language="C#" Value="public int SegmentCount { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 SegmentCount" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataLake.Store.TransferMetadata.SegmentCount" />
      <MemberSignature Language="VB.NET" Value="Public Property SegmentCount As Integer" />
      <MemberSignature Language="F#" Value="member this.SegmentCount : int with get, set" Usage="Microsoft.Azure.Management.DataLake.Store.TransferMetadata.SegmentCount" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Store</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="SegmentCount")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="88023-117">Ruft ab oder legt einen Wert, der angibt, dass die Anzahl der Segmente, die diese Datei ist zum Zweck der übertragen sie aufgeteilt.</span><span class="sxs-lookup"><span data-stu-id="88023-117">Gets or sets a value indicating the number of segments this file is split into for purposes of transfering it.</span></span>
            </summary>
        <value>
            <span data-ttu-id="88023-118">Die Segmentanzahl.</span><span class="sxs-lookup"><span data-stu-id="88023-118">The segment count.</span></span>
            </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SegmentLength">
      <MemberSignature Language="C#" Value="public long SegmentLength { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 SegmentLength" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataLake.Store.TransferMetadata.SegmentLength" />
      <MemberSignature Language="VB.NET" Value="Public Property SegmentLength As Long" />
      <MemberSignature Language="F#" Value="member this.SegmentLength : int64 with get, set" Usage="Microsoft.Azure.Management.DataLake.Store.TransferMetadata.SegmentLength" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Store</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="SegmentLength")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Int64</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="88023-119">Ruft ab oder legt einen Wert, der angibt, der Länge (in Bytes) der einzelnen Segmente der Datei (mit Ausnahme der letzten Zeile der geringer sein kann).</span><span class="sxs-lookup"><span data-stu-id="88023-119">Gets or sets a value indicating the length (in bytes) of each segment of the file (except the last one, which may be less).</span></span>
            </summary>
        <value>
            <span data-ttu-id="88023-120">Die Länge des Segments.</span><span class="sxs-lookup"><span data-stu-id="88023-120">The length of the segment.</span></span>
            </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Segments">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.DataLake.Store.TransferSegmentMetadata[] Segments { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.DataLake.Store.TransferSegmentMetadata[] Segments" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataLake.Store.TransferMetadata.Segments" />
      <MemberSignature Language="VB.NET" Value="Public Property Segments As TransferSegmentMetadata()" />
      <MemberSignature Language="F#" Value="member this.Segments : Microsoft.Azure.Management.DataLake.Store.TransferSegmentMetadata[] with get, set" Usage="Microsoft.Azure.Management.DataLake.Store.TransferMetadata.Segments" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Store</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="Segments")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.DataLake.Store.TransferSegmentMetadata[]</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="88023-121">Ruft einen Zeiger auf ein Array von Segment Metadaten ab.</span><span class="sxs-lookup"><span data-stu-id="88023-121">Gets a pointer to an array of segment metadata.</span></span> <span data-ttu-id="88023-122">Die Segmente sind nach deren Segment-Anzahl (Reihenfolge) sortiert.</span><span class="sxs-lookup"><span data-stu-id="88023-122">The segments are ordered by their segment number (sequence).</span></span>
            </summary>
        <value>
            <span data-ttu-id="88023-123">Die Segmente.</span><span class="sxs-lookup"><span data-stu-id="88023-123">The segments.</span></span>
            </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SegmentStreamDirectory">
      <MemberSignature Language="C#" Value="public string SegmentStreamDirectory { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string SegmentStreamDirectory" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataLake.Store.TransferMetadata.SegmentStreamDirectory" />
      <MemberSignature Language="VB.NET" Value="Public Property SegmentStreamDirectory As String" />
      <MemberSignature Language="F#" Value="member this.SegmentStreamDirectory : string with get, set" Usage="Microsoft.Azure.Management.DataLake.Store.TransferMetadata.SegmentStreamDirectory" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Store</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="SegmentStreamDirectory")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="88023-124">Ruft ab oder legt einen Wert, der angibt, der Pfad des Verzeichnisses, in dem mittleren Segment Datenströme gespeichert werden.</span><span class="sxs-lookup"><span data-stu-id="88023-124">Gets or sets a value indicating the directory path where intermediate segment streams will be stored.</span></span>
            </summary>
        <value>
            <span data-ttu-id="88023-125">Der Zielpfad Stream.</span><span class="sxs-lookup"><span data-stu-id="88023-125">The target stream path.</span></span>
            </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Status">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.DataLake.Store.SegmentTransferStatus Status { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype Microsoft.Azure.Management.DataLake.Store.SegmentTransferStatus Status" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataLake.Store.TransferMetadata.Status" />
      <MemberSignature Language="VB.NET" Value="Public Property Status As SegmentTransferStatus" />
      <MemberSignature Language="F#" Value="member this.Status : Microsoft.Azure.Management.DataLake.Store.SegmentTransferStatus with get, set" Usage="Microsoft.Azure.Management.DataLake.Store.TransferMetadata.Status" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Store</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="Status")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.DataLake.Store.SegmentTransferStatus</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="88023-126">Ruft ab oder legt einen Wert, der angibt, des aktuellen Übertragungsstatus für die Übertragung von diesen Dateien fest.</span><span class="sxs-lookup"><span data-stu-id="88023-126">Gets or sets a value indicating the current transfer status for this file transfer.</span></span>
            <span data-ttu-id="88023-127">Dieser Wert wird zum Ordner Übertragung ausgeführt und Fortsetzen von überprüft.</span><span class="sxs-lookup"><span data-stu-id="88023-127">This value is checked for folder transfer progress and resuming.</span></span> <span data-ttu-id="88023-128">Einzelne Dateien verwenden Übertragungen Segment-Status für die Überwachung.</span><span class="sxs-lookup"><span data-stu-id="88023-128">Single file transfers use segment status for tracking.</span></span>
            </summary>
        <value>
            <span data-ttu-id="88023-129">Der Status.</span><span class="sxs-lookup"><span data-stu-id="88023-129">The status.</span></span>
            </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TargetStreamPath">
      <MemberSignature Language="C#" Value="public string TargetStreamPath { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string TargetStreamPath" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataLake.Store.TransferMetadata.TargetStreamPath" />
      <MemberSignature Language="VB.NET" Value="Public Property TargetStreamPath As String" />
      <MemberSignature Language="F#" Value="member this.TargetStreamPath : string with get, set" Usage="Microsoft.Azure.Management.DataLake.Store.TransferMetadata.TargetStreamPath" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Store</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="TargetStreamPath")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="88023-130">Ruft ab oder legt einen Wert, der angibt, des vollständige Stream-Pfads, in dem die Datei übertragen werden sollen.</span><span class="sxs-lookup"><span data-stu-id="88023-130">Gets or sets a value indicating the full stream path where the file will be transferred to.</span></span>
            </summary>
        <value>
            <span data-ttu-id="88023-131">Der Zielpfad Stream.</span><span class="sxs-lookup"><span data-stu-id="88023-131">The target stream path.</span></span>
            </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TransferId">
      <MemberSignature Language="C#" Value="public string TransferId { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string TransferId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataLake.Store.TransferMetadata.TransferId" />
      <MemberSignature Language="VB.NET" Value="Public Property TransferId As String" />
      <MemberSignature Language="F#" Value="member this.TransferId : string with get, set" Usage="Microsoft.Azure.Management.DataLake.Store.TransferMetadata.TransferId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Store</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="TransferId")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="88023-132">Ruft ab oder legt einen Wert, der angibt, des eindeutigen Bezeichners dieser Übertragung zugeordnet.</span><span class="sxs-lookup"><span data-stu-id="88023-132">Gets or sets a value indicating the unique identifier associated with this transfer.</span></span>
            </summary>
        <value>
            <span data-ttu-id="88023-133">Der Transfer-Bezeichner.</span><span class="sxs-lookup"><span data-stu-id="88023-133">The transfer identifier.</span></span>
            </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>