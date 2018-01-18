<Type Name="TransferParameters" FullName="Microsoft.Azure.Management.DataLake.Store.TransferParameters">
  <TypeSignature Language="C#" Value="public class TransferParameters" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit TransferParameters extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.DataLake.Store.TransferParameters" />
  <TypeSignature Language="VB.NET" Value="Public Class TransferParameters" />
  <TypeSignature Language="F#" Value="type TransferParameters = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.DataLake.Store</AssemblyName>
    <AssemblyVersion>2.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="35392-101">Stellt die Parameter für die DataLakeStoreTransferClient.</span><span class="sxs-lookup"><span data-stu-id="35392-101">Represents parameters for the DataLakeStoreTransferClient.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public TransferParameters (string inputFilePath, string targetStreamPath, string accountName, int perFileThreadCount = -1, int concurrentFileCount = -1, bool isOverwrite = false, bool isResume = false, bool isBinary = true, bool isRecursive = false, bool isDownload = false, long maxSegmentLength = 268435456, string localMetadataLocation = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string inputFilePath, string targetStreamPath, string accountName, int32 perFileThreadCount, int32 concurrentFileCount, bool isOverwrite, bool isResume, bool isBinary, bool isRecursive, bool isDownload, int64 maxSegmentLength, string localMetadataLocation) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Store.TransferParameters.#ctor(System.String,System.String,System.String,System.Int32,System.Int32,System.Boolean,System.Boolean,System.Boolean,System.Boolean,System.Boolean,System.Int64,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (inputFilePath As String, targetStreamPath As String, accountName As String, Optional perFileThreadCount As Integer = -1, Optional concurrentFileCount As Integer = -1, Optional isOverwrite As Boolean = false, Optional isResume As Boolean = false, Optional isBinary As Boolean = true, Optional isRecursive As Boolean = false, Optional isDownload As Boolean = false, Optional maxSegmentLength As Long = 268435456, Optional localMetadataLocation As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.DataLake.Store.TransferParameters : string * string * string * int * int * bool * bool * bool * bool * bool * int64 * string -&gt; Microsoft.Azure.Management.DataLake.Store.TransferParameters" Usage="new Microsoft.Azure.Management.DataLake.Store.TransferParameters (inputFilePath, targetStreamPath, accountName, perFileThreadCount, concurrentFileCount, isOverwrite, isResume, isBinary, isRecursive, isDownload, maxSegmentLength, localMetadataLocation)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Store</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="inputFilePath" Type="System.String" />
        <Parameter Name="targetStreamPath" Type="System.String" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="perFileThreadCount" Type="System.Int32" />
        <Parameter Name="concurrentFileCount" Type="System.Int32" />
        <Parameter Name="isOverwrite" Type="System.Boolean" />
        <Parameter Name="isResume" Type="System.Boolean" />
        <Parameter Name="isBinary" Type="System.Boolean" />
        <Parameter Name="isRecursive" Type="System.Boolean" />
        <Parameter Name="isDownload" Type="System.Boolean" />
        <Parameter Name="maxSegmentLength" Type="System.Int64" />
        <Parameter Name="localMetadataLocation" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="inputFilePath"><span data-ttu-id="35392-102">Der vollständige Pfad zur Datei oder zum Zielordner übertragen werden.</span><span class="sxs-lookup"><span data-stu-id="35392-102">The full path to the file or folder to be transferred.</span></span></param>
        <param name="targetStreamPath"><span data-ttu-id="35392-103">Der vollständige Stream-Pfad, in dem die Datei oder den Ordner übertragen werden sollen.</span><span class="sxs-lookup"><span data-stu-id="35392-103">The full stream path where the file or folder will be transferred to.</span></span></param>
        <param name="accountName"><span data-ttu-id="35392-104">Der Name des Kontos zu übertragen.</span><span class="sxs-lookup"><span data-stu-id="35392-104">Name of the account to transfer to.</span></span></param>
        <param name="perFileThreadCount"><span data-ttu-id="35392-105">Die pro Datei Thread-Anzahl, die angibt, der Anzahl der Dateisegmente parallel zu übertragen.</span><span class="sxs-lookup"><span data-stu-id="35392-105">The per file thread count, indicating the number of file segments to transfer in parallel.</span></span> <span data-ttu-id="35392-106">Diese Zahl ist für eine optimale Leistung bei FILE_SIZE/MaxSegmentLength Obergrenze.</span><span class="sxs-lookup"><span data-stu-id="35392-106">This number is capped at FILE_SIZE/maxSegmentLength for optimal performance.</span></span></param>
        <param name="concurrentFileCount"><span data-ttu-id="35392-107">Die parallele Dateianzahl, der angibt, der Anzahl der Dateien während der Übertragung Ordner parallel zu übertragen.</span><span class="sxs-lookup"><span data-stu-id="35392-107">The parallel file count, indicating the number of files to transfer in parallel during a folder transfer.</span></span> <span data-ttu-id="35392-108">Dieser Parameter wird für einzelne dateiübertragungen ignoriert.</span><span class="sxs-lookup"><span data-stu-id="35392-108">This parameter is ignored for single file transfers.</span></span> <span data-ttu-id="35392-109">Standard ist 5 für Ordner Übertragungen</span><span class="sxs-lookup"><span data-stu-id="35392-109">Default is 5 for folder transfers</span></span></param>
        <param name="isOverwrite"><span data-ttu-id="35392-110">(Optional) Ob der Zieldatenstrom oder nicht überschrieben werden soll.</span><span class="sxs-lookup"><span data-stu-id="35392-110">(Optional) Whether to overwrite the target stream or not.</span></span></param>
        <param name="isResume"><span data-ttu-id="35392-111">(Optional) Gibt an, ob eine zuvor unterbrochene Übertragung fortsetzen.</span><span class="sxs-lookup"><span data-stu-id="35392-111">(Optional) Indicates whether to resume a previously interrupted transfer.</span></span></param>
        <param name="isBinary"><span data-ttu-id="35392-112">(Optional) Gibt an, ob die Eingabedatei als Binärdatei (True) behandelt werden soll, oder ob richten Sie die Übertragung von Nachrichtenblöcken datensatzbegrenzungen (False).</span><span class="sxs-lookup"><span data-stu-id="35392-112">(Optional) Indicates whether to treat the input file as a binary file (true), or whether to align transfer blocks to record boundaries (false).</span></span></param>
        <param name="isRecursive"><span data-ttu-id="35392-113">(Optional) Gibt an, ob die Quelle Ordner rekursiv oder nicht übertragen werden soll.</span><span class="sxs-lookup"><span data-stu-id="35392-113">(Optional) Indicates whether to transfer the source folder recursively or not.</span></span> <span data-ttu-id="35392-114">Bei "true", wird das Quellverzeichnis übertragen, und alle untergeordneten Verzeichnissen, die Verzeichnisstruktur beibehalten.</span><span class="sxs-lookup"><span data-stu-id="35392-114">If true, will transfer the source directory and all sub directories, preserving directory structure.</span></span></param>
        <param name="isDownload"><span data-ttu-id="35392-115">(Optional) bei Festlegung auf <c>"true"</c> [ist Download] anstelle einer Übertragung-Szenario.</span><span class="sxs-lookup"><span data-stu-id="35392-115">(Optional) if set to <c>true</c> [is download] instead of an transfer scenario.</span></span> <span data-ttu-id="35392-116">Die Standardeinstellung ist "false".</span><span class="sxs-lookup"><span data-stu-id="35392-116">Default is false.</span></span></param>
        <param name="maxSegmentLength"><span data-ttu-id="35392-117">Maximale Länge der einzelnen Segmente.</span><span class="sxs-lookup"><span data-stu-id="35392-117">Maximum length of each segment.</span></span> <span data-ttu-id="35392-118">Der Standardwert ist 256mb, wodurch eine optimale Leistung zu erhalten.</span><span class="sxs-lookup"><span data-stu-id="35392-118">The default is 256mb, which gives optimal performance.</span></span> <span data-ttu-id="35392-119">Ändern Sie auf eigenes Risiko.</span><span class="sxs-lookup"><span data-stu-id="35392-119">Modify at your own risk.</span></span></param>
        <param name="localMetadataLocation"><span data-ttu-id="35392-120">(Optional) Gibt den Verzeichnispfad an, wo Sie die lokale Übertragung Metadaten-Datei zu speichern, während die Übertragung ausgeführt wird.</span><span class="sxs-lookup"><span data-stu-id="35392-120">(Optional) Indicates the directory path where to store the local transfer metadata file while the transfer is in progress.</span></span> <span data-ttu-id="35392-121">Dieser Speicherort muss beschreibbar aus dieser Anwendung handeln.</span><span class="sxs-lookup"><span data-stu-id="35392-121">This location must be writeable from this application.</span></span> <span data-ttu-id="35392-122">Standardspeicherort: SpecialFolder.LocalApplicationData.</span><span class="sxs-lookup"><span data-stu-id="35392-122">Default location: SpecialFolder.LocalApplicationData.</span></span></param>
        <summary>
            <span data-ttu-id="35392-123">Erstellt einen neuen Satz von Parametern für die DataLakeStoreTransferClient an.</span><span class="sxs-lookup"><span data-stu-id="35392-123">Creates a new set of parameters for the DataLakeStoreTransferClient.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AccountName">
      <MemberSignature Language="C#" Value="public string AccountName { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string AccountName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataLake.Store.TransferParameters.AccountName" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property AccountName As String" />
      <MemberSignature Language="F#" Value="member this.AccountName : string" Usage="Microsoft.Azure.Management.DataLake.Store.TransferParameters.AccountName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Store</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="35392-124">Ruft einen Wert, der angibt, der des Namens des Kontos, das auf übertragen oder Herunterladen aus.</span><span class="sxs-lookup"><span data-stu-id="35392-124">Gets a value indicating the name of the account to transfer to or download from.</span></span>
            </summary>
        <value>
            <span data-ttu-id="35392-125">Der Name des Kontos.</span><span class="sxs-lookup"><span data-stu-id="35392-125">The name of the account.</span></span>
            </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ConcurrentFileCount">
      <MemberSignature Language="C#" Value="public int ConcurrentFileCount { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 ConcurrentFileCount" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataLake.Store.TransferParameters.ConcurrentFileCount" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ConcurrentFileCount As Integer" />
      <MemberSignature Language="F#" Value="member this.ConcurrentFileCount : int" Usage="Microsoft.Azure.Management.DataLake.Store.TransferParameters.ConcurrentFileCount" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Store</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="35392-126">Ruft die Anzahl der parallel-Dateien, die angibt, wie viele Dateien in einem Ordner übertragen oder parallel heruntergeladen werden</span><span class="sxs-lookup"><span data-stu-id="35392-126">Gets the parallel file count, which indicates how many files in a folder will be transferred or downloaded in parallel</span></span>
            </summary>
        <value>
            <span data-ttu-id="35392-127">Die Anzahl der Dateien für die Übertragung oder Download auf einmal.</span><span class="sxs-lookup"><span data-stu-id="35392-127">The number of files to transfer or download at once.</span></span>
            </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Delimiter">
      <MemberSignature Language="C#" Value="public string Delimiter { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Delimiter" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataLake.Store.TransferParameters.Delimiter" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Delimiter As String" />
      <MemberSignature Language="F#" Value="member this.Delimiter : string" Usage="Microsoft.Azure.Management.DataLake.Store.TransferParameters.Delimiter" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Store</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="35392-128">Ruft einen Wert, der angibt, des Trennzeichens Datensatz Grenze für die Datei ab, sofern vorhanden.</span><span class="sxs-lookup"><span data-stu-id="35392-128">Gets a value indicating the record boundary delimiter for the file, if any.</span></span>
            </summary>
        <value>
            <span data-ttu-id="35392-129">Das Trennzeichen Datensatz Grenze</span><span class="sxs-lookup"><span data-stu-id="35392-129">The record boundary delimiter</span></span>
            </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="FileEncoding">
      <MemberSignature Language="C#" Value="public System.Text.Encoding FileEncoding { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Text.Encoding FileEncoding" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataLake.Store.TransferParameters.FileEncoding" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property FileEncoding As Encoding" />
      <MemberSignature Language="F#" Value="member this.FileEncoding : System.Text.Encoding" Usage="Microsoft.Azure.Management.DataLake.Store.TransferParameters.FileEncoding" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Store</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Text.Encoding</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="35392-130">Ruft einen Wert, der angibt, die Codierung der übertragenen Datei.</span><span class="sxs-lookup"><span data-stu-id="35392-130">Gets a value indicating the encoding of the file being transferred.</span></span>
            </summary>
        <value>
            <span data-ttu-id="35392-131">Die dateicodierung.</span><span class="sxs-lookup"><span data-stu-id="35392-131">The file encoding.</span></span>
            </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="InputFilePath">
      <MemberSignature Language="C#" Value="public string InputFilePath { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string InputFilePath" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataLake.Store.TransferParameters.InputFilePath" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property InputFilePath As String" />
      <MemberSignature Language="F#" Value="member this.InputFilePath : string" Usage="Microsoft.Azure.Management.DataLake.Store.TransferParameters.InputFilePath" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Store</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="35392-132">Ruft einen Wert, der angibt, des vollständigen Pfads zur Datei oder zum Zielordner übertragen werden.</span><span class="sxs-lookup"><span data-stu-id="35392-132">Gets a value indicating the full path to the file or folder to be transferred.</span></span>
            </summary>
        <value>
            <span data-ttu-id="35392-133">Der Pfad der Eingabedatei.</span><span class="sxs-lookup"><span data-stu-id="35392-133">The input file path.</span></span>
            </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IsBinary">
      <MemberSignature Language="C#" Value="public bool IsBinary { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool IsBinary" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataLake.Store.TransferParameters.IsBinary" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property IsBinary As Boolean" />
      <MemberSignature Language="F#" Value="member this.IsBinary : bool" Usage="Microsoft.Azure.Management.DataLake.Store.TransferParameters.IsBinary" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Store</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="35392-134">Ruft einen Wert, der angibt, ob die Eingabedatei als binärer (True) oder eine durch Trennzeichen getrennten Eingabe ("false") behandelt werden sollen.</span><span class="sxs-lookup"><span data-stu-id="35392-134">Gets a value indicating whether the input file should be treated as a binary (true) or a delimited input (false).</span></span>
            </summary>
        <value>
          <span data-ttu-id="35392-135"><c>"true"</c> Wenn diese Instanz binär ist, andernfalls ist <c>"false"</c>.</span><span class="sxs-lookup"><span data-stu-id="35392-135"><c>true</c> if this instance is binary; otherwise, <c>false</c>.</span></span>
            </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IsDownload">
      <MemberSignature Language="C#" Value="public bool IsDownload { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool IsDownload" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataLake.Store.TransferParameters.IsDownload" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property IsDownload As Boolean" />
      <MemberSignature Language="F#" Value="member this.IsDownload : bool" Usage="Microsoft.Azure.Management.DataLake.Store.TransferParameters.IsDownload" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Store</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="35392-136">Ruft einen Wert, der angibt, ob diese Instanz mit dem lokalen Computer statt übertragen heruntergeladen wird.</span><span class="sxs-lookup"><span data-stu-id="35392-136">Gets a value indicating whether this instance is downloading to the local machine instead of transfering.</span></span>
            </summary>
        <value>
          <span data-ttu-id="35392-137"><c>"true"</c> Wenn diese Instanz Download; andernfalls <c>"false"</c>.</span><span class="sxs-lookup"><span data-stu-id="35392-137"><c>true</c> if this instance is download; otherwise, <c>false</c>.</span></span>
            </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IsOverwrite">
      <MemberSignature Language="C#" Value="public bool IsOverwrite { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool IsOverwrite" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataLake.Store.TransferParameters.IsOverwrite" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property IsOverwrite As Boolean" />
      <MemberSignature Language="F#" Value="member this.IsOverwrite : bool" Usage="Microsoft.Azure.Management.DataLake.Store.TransferParameters.IsOverwrite" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Store</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="35392-138">Ruft einen Wert, der angibt, ob der Zieldatenstrom zu überschreiben, wenn sie bereits vorhanden ist.</span><span class="sxs-lookup"><span data-stu-id="35392-138">Gets a value indicating whether to overwrite the target stream if it already exists.</span></span>
            </summary>
        <value>
          <span data-ttu-id="35392-139"><c>"true"</c> dieser Instanz überschrieben werden; andernfalls <c>"false"</c>.</span><span class="sxs-lookup"><span data-stu-id="35392-139"><c>true</c> if this instance is overwrite; otherwise, <c>false</c>.</span></span>
            </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IsRecursive">
      <MemberSignature Language="C#" Value="public bool IsRecursive { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool IsRecursive" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataLake.Store.TransferParameters.IsRecursive" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property IsRecursive As Boolean" />
      <MemberSignature Language="F#" Value="member this.IsRecursive : bool" Usage="Microsoft.Azure.Management.DataLake.Store.TransferParameters.IsRecursive" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Store</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="35392-140">Ruft einen Wert, der angibt, ob die Übertragung Ordner rekursiv Übertragung Quellordner sollten.</span><span class="sxs-lookup"><span data-stu-id="35392-140">Gets a value indicating whether the folder transfer should recursively transfer the source folder.</span></span> <span data-ttu-id="35392-141">Dies gilt nur für Ordner übertragen und wird für die Übertragung von Dateien ignoriert.</span><span class="sxs-lookup"><span data-stu-id="35392-141">This is only valid for folder transfers and will be ignored for file transfers.</span></span>
            </summary>
        <value>
          <span data-ttu-id="35392-142"><c>"true"</c> Wenn diese Instanz rekursive; andernfalls <c>"false"</c>.</span><span class="sxs-lookup"><span data-stu-id="35392-142"><c>true</c> if this instance is recursive; otherwise, <c>false</c>.</span></span>
            </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IsResume">
      <MemberSignature Language="C#" Value="public bool IsResume { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool IsResume" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataLake.Store.TransferParameters.IsResume" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property IsResume As Boolean" />
      <MemberSignature Language="F#" Value="member this.IsResume : bool" Usage="Microsoft.Azure.Management.DataLake.Store.TransferParameters.IsResume" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Store</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="35392-143">Ruft einen Wert, der angibt, ob eine zuvor unterbrochene Übertragung fortsetzen.</span><span class="sxs-lookup"><span data-stu-id="35392-143">Gets a value indicating whether to resume a previously interrupted transfer.</span></span>
            </summary>
        <value>
          <span data-ttu-id="35392-144"><c>"true"</c> Wenn diese Instanz fortsetzen; andernfalls <c>"false"</c>.</span><span class="sxs-lookup"><span data-stu-id="35392-144"><c>true</c> if this instance is resume; otherwise, <c>false</c>.</span></span>
            </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="LocalMetadataLocation">
      <MemberSignature Language="C#" Value="public string LocalMetadataLocation { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string LocalMetadataLocation" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataLake.Store.TransferParameters.LocalMetadataLocation" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property LocalMetadataLocation As String" />
      <MemberSignature Language="F#" Value="member this.LocalMetadataLocation : string" Usage="Microsoft.Azure.Management.DataLake.Store.TransferParameters.LocalMetadataLocation" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Store</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="35392-145">Ruft einen Wert ab dem Verzeichnispfad, wo Sie die Metadaten für die Übertragung zu speichern.</span><span class="sxs-lookup"><span data-stu-id="35392-145">Gets a value indicating the directory path where to store the metadata for the transfer.</span></span>
            </summary>
        <value>
            <span data-ttu-id="35392-146">Der lokalen Metadaten-Speicherort.</span><span class="sxs-lookup"><span data-stu-id="35392-146">The local metadata location.</span></span>
            </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MaxSegementLength">
      <MemberSignature Language="C#" Value="public long MaxSegementLength { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 MaxSegementLength" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataLake.Store.TransferParameters.MaxSegementLength" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property MaxSegementLength As Long" />
      <MemberSignature Language="F#" Value="member this.MaxSegementLength : int64" Usage="Microsoft.Azure.Management.DataLake.Store.TransferParameters.MaxSegementLength" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Store</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int64</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="35392-147">Ruft die maximale Länge jedes Segments ab.</span><span class="sxs-lookup"><span data-stu-id="35392-147">Gets the maximum length of each segement.</span></span>
            </summary>
        <value>
            <span data-ttu-id="35392-148">Die maximale Länge jedes Segments.</span><span class="sxs-lookup"><span data-stu-id="35392-148">The maximum length of each segement.</span></span>
            </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PerFileThreadCount">
      <MemberSignature Language="C#" Value="public int PerFileThreadCount { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 PerFileThreadCount" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataLake.Store.TransferParameters.PerFileThreadCount" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property PerFileThreadCount As Integer" />
      <MemberSignature Language="F#" Value="member this.PerFileThreadCount : int" Usage="Microsoft.Azure.Management.DataLake.Store.TransferParameters.PerFileThreadCount" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Store</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="35392-149">Ruft einen Wert, der angibt, der maximalen Anzahl von parallelen Threads zur Verwendung einer einzelnen übertragen oder herunterladen.</span><span class="sxs-lookup"><span data-stu-id="35392-149">Gets a value indicating the maximum number of parallel threads to use for a single file transfer or download.</span></span>
            </summary>
        <value>
            <span data-ttu-id="35392-150">Die Thread-Anzahl der Dateien.</span><span class="sxs-lookup"><span data-stu-id="35392-150">The file thread count.</span></span>
            </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TargetStreamPath">
      <MemberSignature Language="C#" Value="public string TargetStreamPath { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string TargetStreamPath" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataLake.Store.TransferParameters.TargetStreamPath" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property TargetStreamPath As String" />
      <MemberSignature Language="F#" Value="member this.TargetStreamPath : string" Usage="Microsoft.Azure.Management.DataLake.Store.TransferParameters.TargetStreamPath" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Store</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="35392-151">Ruft einen Wert, der angibt, des vollständige Stream-Pfads, in dem die Datei übertragen werden sollen.</span><span class="sxs-lookup"><span data-stu-id="35392-151">Gets a value indicating the full stream path where the file will be transferred to.</span></span>
            </summary>
        <value>
            <span data-ttu-id="35392-152">Der Zielpfad Stream.</span><span class="sxs-lookup"><span data-stu-id="35392-152">The target stream path.</span></span>
            </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>