<Type Name="TransferFolderMetadata" FullName="Microsoft.Azure.Management.DataLake.Store.TransferFolderMetadata">
  <TypeSignature Language="C#" Value="public class TransferFolderMetadata" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit TransferFolderMetadata extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.DataLake.Store.TransferFolderMetadata" />
  <TypeSignature Language="VB.NET" Value="Public Class TransferFolderMetadata" />
  <TypeSignature Language="F#" Value="type TransferFolderMetadata = class" />
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
      <AttributeName>System.Diagnostics.DebuggerDisplay("FileCount = {FileCount}, TransferId = {TransferId}, IsRecursive = {IsRecursive}")</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            <span data-ttu-id="167eb-101">Allgemeine Metadaten, die für eine Übertragung darstellt.</span><span class="sxs-lookup"><span data-stu-id="167eb-101">Represents general metadata pertaining to a transfer.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public TransferFolderMetadata (string metadataFilePath, Microsoft.Azure.Management.DataLake.Store.TransferParameters transferParameters, Microsoft.Azure.Management.DataLake.Store.IFrontEndAdapter frontend);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string metadataFilePath, class Microsoft.Azure.Management.DataLake.Store.TransferParameters transferParameters, class Microsoft.Azure.Management.DataLake.Store.IFrontEndAdapter frontend) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Store.TransferFolderMetadata.#ctor(System.String,Microsoft.Azure.Management.DataLake.Store.TransferParameters,Microsoft.Azure.Management.DataLake.Store.IFrontEndAdapter)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.DataLake.Store.TransferFolderMetadata : string * Microsoft.Azure.Management.DataLake.Store.TransferParameters * Microsoft.Azure.Management.DataLake.Store.IFrontEndAdapter -&gt; Microsoft.Azure.Management.DataLake.Store.TransferFolderMetadata" Usage="new Microsoft.Azure.Management.DataLake.Store.TransferFolderMetadata (metadataFilePath, transferParameters, frontend)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Store</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="metadataFilePath" Type="System.String" />
        <Parameter Name="transferParameters" Type="Microsoft.Azure.Management.DataLake.Store.TransferParameters" />
        <Parameter Name="frontend" Type="Microsoft.Azure.Management.DataLake.Store.IFrontEndAdapter" />
      </Parameters>
      <Docs>
        <param name="metadataFilePath"><span data-ttu-id="167eb-102">Der Dateipfad, auf diese Metadatendatei (für das Speichern von Zwecke) zugewiesen werden soll.</span><span class="sxs-lookup"><span data-stu-id="167eb-102">The file path to assign to this metadata file (for saving purposes).</span></span></param>
        <param name="transferParameters"><span data-ttu-id="167eb-103">Die Parameter zum Erstellen dieser Metadaten verwendet werden soll.</span><span class="sxs-lookup"><span data-stu-id="167eb-103">The parameters to use for constructing this metadata.</span></span></param>
        <param name="frontend"><span data-ttu-id="167eb-104">Das Front-End zu verwendende pro Dateimetadaten generiert werden soll.</span><span class="sxs-lookup"><span data-stu-id="167eb-104">The frontend to use when generating per file metadata.</span></span></param>
        <summary>
            <span data-ttu-id="167eb-105">Erstellt ein neues TransferFolderMetadata-Objekt aus der angegebenen Parameter.</span><span class="sxs-lookup"><span data-stu-id="167eb-105">Constructs a new TransferFolderMetadata object from the given parameters.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteFile">
      <MemberSignature Language="C#" Value="public void DeleteFile ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance void DeleteFile() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Store.TransferFolderMetadata.DeleteFile" />
      <MemberSignature Language="VB.NET" Value="Public Sub DeleteFile ()" />
      <MemberSignature Language="F#" Value="member this.DeleteFile : unit -&gt; unit" Usage="transferFolderMetadata.DeleteFile " />
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
            <span data-ttu-id="167eb-106">Löscht die Metadatendatei vom Datenträger.</span><span class="sxs-lookup"><span data-stu-id="167eb-106">Deletes the metadata file from disk.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:System.InvalidOperationException"><span data-ttu-id="167eb-107">MetadataFilePath von NULL oder leer sein.</span><span class="sxs-lookup"><span data-stu-id="167eb-107">Null or empty MetadataFilePath.</span></span> <span data-ttu-id="167eb-108">Metadaten können nicht gelöscht werden, bis diese Eigenschaft festgelegt wird.</span><span class="sxs-lookup"><span data-stu-id="167eb-108">Cannot delete metadata until this property is set.</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName="FileCount">
      <MemberSignature Language="C#" Value="public int FileCount { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 FileCount" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataLake.Store.TransferFolderMetadata.FileCount" />
      <MemberSignature Language="VB.NET" Value="Public Property FileCount As Integer" />
      <MemberSignature Language="F#" Value="member this.FileCount : int with get, set" Usage="Microsoft.Azure.Management.DataLake.Store.TransferFolderMetadata.FileCount" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Store</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="FileCount")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="167eb-109">Ruft ab oder legt einen Wert, der angibt, der Anzahl der Dateien in dieser Übertragung fest.</span><span class="sxs-lookup"><span data-stu-id="167eb-109">Gets or sets a value indicating the number of files in this transfer.</span></span>
            </summary>
        <value>
            <span data-ttu-id="167eb-110">Die Segmentanzahl.</span><span class="sxs-lookup"><span data-stu-id="167eb-110">The segment count.</span></span>
            </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Files">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.DataLake.Store.TransferMetadata[] Files { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.DataLake.Store.TransferMetadata[] Files" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataLake.Store.TransferFolderMetadata.Files" />
      <MemberSignature Language="VB.NET" Value="Public Property Files As TransferMetadata()" />
      <MemberSignature Language="F#" Value="member this.Files : Microsoft.Azure.Management.DataLake.Store.TransferMetadata[] with get, set" Usage="Microsoft.Azure.Management.DataLake.Store.TransferFolderMetadata.Files" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Store</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="Files")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.DataLake.Store.TransferMetadata[]</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="167eb-111">Ruft einen Zeiger auf ein Array von Dateimetadaten für die Übertragung an.</span><span class="sxs-lookup"><span data-stu-id="167eb-111">Gets a pointer to an array of file transfer metadata.</span></span> <span data-ttu-id="167eb-112">Dies wird für jede Datei verwendet, das übertragen wird.</span><span class="sxs-lookup"><span data-stu-id="167eb-112">This is used for each file that is being transferred.</span></span>
            </summary>
        <value>
            <span data-ttu-id="167eb-113">Die Segmente.</span><span class="sxs-lookup"><span data-stu-id="167eb-113">The segments.</span></span>
            </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="InputFolderPath">
      <MemberSignature Language="C#" Value="public string InputFolderPath { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string InputFolderPath" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataLake.Store.TransferFolderMetadata.InputFolderPath" />
      <MemberSignature Language="VB.NET" Value="Public Property InputFolderPath As String" />
      <MemberSignature Language="F#" Value="member this.InputFolderPath : string with get, set" Usage="Microsoft.Azure.Management.DataLake.Store.TransferFolderMetadata.InputFolderPath" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Store</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="InputFolderPath")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="167eb-114">Ruft ab oder legt einen Wert, der angibt, des vollständigen Pfads zu der Datei, die übertragen werden.</span><span class="sxs-lookup"><span data-stu-id="167eb-114">Gets or sets a value indicating the full path to the file to be transferred.</span></span>
            </summary>
        <value>
            <span data-ttu-id="167eb-115">Der Pfad der Eingabedatei.</span><span class="sxs-lookup"><span data-stu-id="167eb-115">The input file path.</span></span>
            </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IsRecursive">
      <MemberSignature Language="C#" Value="public bool IsRecursive { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool IsRecursive" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataLake.Store.TransferFolderMetadata.IsRecursive" />
      <MemberSignature Language="VB.NET" Value="Public Property IsRecursive As Boolean" />
      <MemberSignature Language="F#" Value="member this.IsRecursive : bool with get, set" Usage="Microsoft.Azure.Management.DataLake.Store.TransferFolderMetadata.IsRecursive" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Store</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="IsRecursive")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="167eb-116">Ruft einen Wert ab, ob Recurisve Directory Übertragung oder eine Flatfile Verzeichnis übertragen sieht</span><span class="sxs-lookup"><span data-stu-id="167eb-116">Gets a value indicating whether this is recurisve directory transfer or a flat directory transfer</span></span>
            </summary>
        <value>
          <span data-ttu-id="167eb-117"><c>"true"</c> Wenn diese Instanz rekursive; andernfalls <c>"false"</c>.</span><span class="sxs-lookup"><span data-stu-id="167eb-117"><c>true</c> if this instance is recursive; otherwise, <c>false</c>.</span></span>
            </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Save">
      <MemberSignature Language="C#" Value="public void Save ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance void Save() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Store.TransferFolderMetadata.Save" />
      <MemberSignature Language="VB.NET" Value="Public Sub Save ()" />
      <MemberSignature Language="F#" Value="member this.Save : unit -&gt; unit" Usage="transferFolderMetadata.Save " />
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
            <span data-ttu-id="167eb-118">Speichert die angegebenen Metadaten an den kanonischen Speicherort an.</span><span class="sxs-lookup"><span data-stu-id="167eb-118">Saves the given metadata to its canonical location.</span></span> <span data-ttu-id="167eb-119">Diese Methode ist threadsicher.</span><span class="sxs-lookup"><span data-stu-id="167eb-119">This method is thread-safe.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TargetStreamFolderPath">
      <MemberSignature Language="C#" Value="public string TargetStreamFolderPath { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string TargetStreamFolderPath" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataLake.Store.TransferFolderMetadata.TargetStreamFolderPath" />
      <MemberSignature Language="VB.NET" Value="Public Property TargetStreamFolderPath As String" />
      <MemberSignature Language="F#" Value="member this.TargetStreamFolderPath : string with get, set" Usage="Microsoft.Azure.Management.DataLake.Store.TransferFolderMetadata.TargetStreamFolderPath" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Store</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="TargetStreamFolderPath")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="167eb-120">Ruft ab oder legt einen Wert, der angibt, des vollständige Stream Ordnerpfad, der als Stammverzeichnis für alle Dateien und Ordner übertragenen verwendet wird.</span><span class="sxs-lookup"><span data-stu-id="167eb-120">Gets or sets a value indicating the full stream folder path that will be used as the root folder for all files and folders being transferred.</span></span>
            </summary>
        <value>
            <span data-ttu-id="167eb-121">Der Zielpfad Stream.</span><span class="sxs-lookup"><span data-stu-id="167eb-121">The target stream path.</span></span>
            </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TotalFileBytes">
      <MemberSignature Language="C#" Value="public long TotalFileBytes { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 TotalFileBytes" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataLake.Store.TransferFolderMetadata.TotalFileBytes" />
      <MemberSignature Language="VB.NET" Value="Public Property TotalFileBytes As Long" />
      <MemberSignature Language="F#" Value="member this.TotalFileBytes : int64 with get, set" Usage="Microsoft.Azure.Management.DataLake.Store.TransferFolderMetadata.TotalFileBytes" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Store</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="TotalFileBytes")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Int64</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="167eb-122">Ruft ab oder legt die Gesamtanzahl der Bytes für alle Dateien.</span><span class="sxs-lookup"><span data-stu-id="167eb-122">Gets or sets the total bytes for all the files.</span></span>
            </summary>
        <value>
            <span data-ttu-id="167eb-123">Die Gesamtanzahl der Bytes für alle Dateien.</span><span class="sxs-lookup"><span data-stu-id="167eb-123">The total bytes for all the files.</span></span>
            </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TransferId">
      <MemberSignature Language="C#" Value="public string TransferId { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string TransferId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataLake.Store.TransferFolderMetadata.TransferId" />
      <MemberSignature Language="VB.NET" Value="Public Property TransferId As String" />
      <MemberSignature Language="F#" Value="member this.TransferId : string with get, set" Usage="Microsoft.Azure.Management.DataLake.Store.TransferFolderMetadata.TransferId" />
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
            <span data-ttu-id="167eb-124">Ruft ab oder legt einen Wert, der angibt, des eindeutigen Bezeichners dieser Übertragung zugeordnet.</span><span class="sxs-lookup"><span data-stu-id="167eb-124">Gets or sets a value indicating the unique identifier associated with this transfer.</span></span>
            </summary>
        <value>
            <span data-ttu-id="167eb-125">Der Transfer-Bezeichner.</span><span class="sxs-lookup"><span data-stu-id="167eb-125">The transfer identifier.</span></span>
            </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>