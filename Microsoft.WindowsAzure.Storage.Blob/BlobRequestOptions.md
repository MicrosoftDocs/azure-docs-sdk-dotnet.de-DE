<Type Name="BlobRequestOptions" FullName="Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions">
  <TypeSignature Language="C#" Value="public sealed class BlobRequestOptions : Microsoft.WindowsAzure.Storage.IRequestOptions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit BlobRequestOptions extends System.Object implements class Microsoft.WindowsAzure.Storage.IRequestOptions" />
  <TypeSignature Language="DocId" Value="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class BlobRequestOptions&#xA;Implements IRequestOptions" />
  <TypeSignature Language="F#" Value="type BlobRequestOptions = class&#xA;    interface IRequestOptions" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
    <AssemblyVersion>8.4.0.0</AssemblyVersion>
    <AssemblyVersion>8.7.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces>
    <Interface>
      <InterfaceName>Microsoft.WindowsAzure.Storage.IRequestOptions</InterfaceName>
    </Interface>
  </Interfaces>
  <Docs>
    <summary>
            <span data-ttu-id="2592c-101">Stellt eine Reihe von Optionen für Timeout- und wiederholungsrichtlinien, die für eine Anforderung für den Blob-Dienst angegeben werden kann.</span><span class="sxs-lookup"><span data-stu-id="2592c-101">Represents a set of timeout and retry policy options that may be specified for a request against the Blob service.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public BlobRequestOptions ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions.#ctor" />
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
            <span data-ttu-id="2592c-102">Initialisiert eine neue Instanz der <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />-Klasse.</span><span class="sxs-lookup"><span data-stu-id="2592c-102">Initializes a new instance of the <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" /> class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AbsorbConditionalErrorsOnRetry">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; AbsorbConditionalErrorsOnRetry { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; AbsorbConditionalErrorsOnRetry" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions.AbsorbConditionalErrorsOnRetry" />
      <MemberSignature Language="VB.NET" Value="Public Property AbsorbConditionalErrorsOnRetry As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.AbsorbConditionalErrorsOnRetry : Nullable&lt;bool&gt; with get, set" Usage="Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions.AbsorbConditionalErrorsOnRetry" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="2592c-103">Ruft ab oder legt einen Wert, der angibt, ob bei einem Wiederholungsversuch für die Anforderung ein bedingten Fehler aufgenommen werden sollten.</span><span class="sxs-lookup"><span data-stu-id="2592c-103">Gets or sets a value that indicates whether a conditional failure should be absorbed on a retry attempt for the request.</span></span> 
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="2592c-104">Diese Option wird nur von verwendet die <see cref="T:Microsoft.WindowsAzure.Storage.Blob.CloudAppendBlob" /> Objekt in der <b>UploadFrom* </b> Methoden, die <b>AppendFrom* </b> Methoden, und die <b>BlobWriteStream</b> Klasse.</span><span class="sxs-lookup"><span data-stu-id="2592c-104">This option is used only by the <see cref="T:Microsoft.WindowsAzure.Storage.Blob.CloudAppendBlob" /> object in the <b>UploadFrom*</b> methods, the <b>AppendFrom*</b> methods, and the <b>BlobWriteStream</b> class.</span></span> <span data-ttu-id="2592c-105">Standardmäßig wird es auf festgelegt, <c>"false"</c>.</span><span class="sxs-lookup"><span data-stu-id="2592c-105">By default, it is set to <c>false</c>.</span></span> <span data-ttu-id="2592c-106">Legen Sie diese Option, um <c>"true"</c> nur für einzelne Writer-Szenarien.</span><span class="sxs-lookup"><span data-stu-id="2592c-106">Set this option to <c>true</c> only for single-writer scenarios.</span></span> <span data-ttu-id="2592c-107">Wenn diese Option auf <c>"true"</c> in einem Szenario mit mehreren Writer kann auf beschädigte Blob-Daten führen.</span><span class="sxs-lookup"><span data-stu-id="2592c-107">Setting this option to <c>true</c> in a multi-writer scenario may lead to corrupted blob data.</span></span>
            
            <span data-ttu-id="2592c-108">"UploadFrom \*" auf ein Anhang-Blob aufrufen, der Speicherclient die Eingabedaten in eine Anzahl von Datenblöcken unterbrochen, und Hochladen der einzelnen Datenblöcke mit einer "Append Block"-Operation.</span><span class="sxs-lookup"><span data-stu-id="2592c-108">When calling "UploadFrom\*" on an append blob, the Storage Client breaks the input data up into a number of data blocks, and uploads each data block with an "append block" operation.</span></span>
            <span data-ttu-id="2592c-109">Eine zugriffsbedingung "IfAppendPositionEqual" ist in der Regel wird der Block-Anfügevorgang hinzugefügt, damit der Uploadvorgang fehl, wenn ein anderer Prozess an einer beliebigen Stelle Daten in der Mitte diesen Datenstream angefügt wurde.</span><span class="sxs-lookup"><span data-stu-id="2592c-109">Normally, an "IfAppendPositionEqual" access condition is added to the append block operation, so that the upload operation will fail if some other process somewhere has appended data in the middle of this data stream.</span></span>
            <span data-ttu-id="2592c-110">Allerdings kann dies in einem sehr spezifischen Szenario "false" zu einem Fehler führen.</span><span class="sxs-lookup"><span data-stu-id="2592c-110">However, this can result in a false failure in a very specific case.</span></span> <span data-ttu-id="2592c-111">Fällt ein Anfügevorgang mit einem Timeout, besteht die Möglichkeit, die auf dem Dienst der Vorgang erfolgreich war, aber die Antwort "Success" nicht unbedingt an dem Client zurück.</span><span class="sxs-lookup"><span data-stu-id="2592c-111">If an append operation fails with a timeout, there is a chance that the operation succeeded on the service, but the "success" response did not make it back to the client.</span></span>
            <span data-ttu-id="2592c-112">In diesem Fall wird der Client erneut, und rufen dann einen "append Position nicht erfüllt" Fehler.</span><span class="sxs-lookup"><span data-stu-id="2592c-112">In this case, the client will retry, and then get an "append position not met" failure.</span></span>
            
            <span data-ttu-id="2592c-113">Wenn dieser Wert auf <c>"true"</c> führt zu den Uploadvorgang fortsetzen, wenn sie einen "append Position nicht erfüllt" Fehler bei der Wiederholung - Kontoführung für die oben genannten Möglichkeit sieht.</span><span class="sxs-lookup"><span data-stu-id="2592c-113">Setting this value to <c>true</c> results in the upload operation continuing when it sees an "append position not met" failure on retry - accounting for the above possibility.</span></span> <span data-ttu-id="2592c-114">Allerdings dies Schutz im Szenario mit mehreren Writer - verloren, wenn mehrere Threads gleichzeitig in das Blob hochgeladen werden, und dieser Wert, um festgelegt wird <c>"true"</c>, einige Daten verloren, da der Client nimmt die Daten wurde hochgeladen, wenn in der Tat wurde der andere Prozess Daten.</span><span class="sxs-lookup"><span data-stu-id="2592c-114">However, this loses protection in the multi-writer scenario - if multiple threads are uploading to the blob at once, and this value is set to <c>true</c>, some data may be lost, because the client thinks the data was uploaded, when in fact it was the other process' data.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="DisableContentMD5Validation">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; DisableContentMD5Validation { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; DisableContentMD5Validation" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions.DisableContentMD5Validation" />
      <MemberSignature Language="VB.NET" Value="Public Property DisableContentMD5Validation As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.DisableContentMD5Validation : Nullable&lt;bool&gt; with get, set" Usage="Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions.DisableContentMD5Validation" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="2592c-115">Ruft ab oder legt einen Wert fest, um anzugeben, dass die MD5-Überprüfung beim Herunterladen von Blobs deaktiviert wird.</span><span class="sxs-lookup"><span data-stu-id="2592c-115">Gets or sets a value to indicate that MD5 validation will be disabled when downloading blobs.</span></span>
            </summary>
        <value><span data-ttu-id="2592c-116">Verwendung <c>"true"</c> MD5-Prüfung, deaktivieren <c>"false"</c> MD5-Überprüfung zu aktivieren.</span><span class="sxs-lookup"><span data-stu-id="2592c-116">Use <c>true</c> to disable MD5 validation; <c>false</c> to enable MD5 validation.</span></span> <span data-ttu-id="2592c-117">Die Standardeinstellung lautet <c>false</c>.</span><span class="sxs-lookup"><span data-stu-id="2592c-117">Default is <c>false</c>.</span></span></value>
        <remarks>
            <span data-ttu-id="2592c-118">Wenn ein Blob herunterladen, wenn der Wert für das Blob bereits vorhanden ist, wird der Speicherdienst den MD5-Hash, der das gesamte Blob als einen Header enthalten.</span><span class="sxs-lookup"><span data-stu-id="2592c-118">When downloading a blob, if the value already exists on the blob, the Storage service will include the MD5 hash of the entire blob as a header.</span></span> <span data-ttu-id="2592c-119">Dieser Option wird gesteuert, und zwar unabhängig davon, ob der Speicherclient auf Download, MD5-Hash überprüft.</span><span class="sxs-lookup"><span data-stu-id="2592c-119">This option controls whether or not the Storage Client will validate that MD5 hash on download.</span></span>
            <span data-ttu-id="2592c-120">Ausführliche Informationen finden Sie unter <see cref="P:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions.StoreBlobContentMD5" />.</span><span class="sxs-lookup"><span data-stu-id="2592c-120">See <see cref="P:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions.StoreBlobContentMD5" /> for more details.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="EncryptionPolicy">
      <MemberSignature Language="C#" Value="public Microsoft.WindowsAzure.Storage.Blob.BlobEncryptionPolicy EncryptionPolicy { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.WindowsAzure.Storage.Blob.BlobEncryptionPolicy EncryptionPolicy" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions.EncryptionPolicy" />
      <MemberSignature Language="VB.NET" Value="Public Property EncryptionPolicy As BlobEncryptionPolicy" />
      <MemberSignature Language="F#" Value="member this.EncryptionPolicy : Microsoft.WindowsAzure.Storage.Blob.BlobEncryptionPolicy with get, set" Usage="Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions.EncryptionPolicy" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Storage.Blob.BlobEncryptionPolicy</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="2592c-121">Ruft ab oder legt die Verschlüsselungsrichtlinie für die Anforderung.</span><span class="sxs-lookup"><span data-stu-id="2592c-121">Gets or sets the encryption policy for the request.</span></span>
            </summary>
        <value><span data-ttu-id="2592c-122">Ein Objekt vom Typ <see cref="P:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions.EncryptionPolicy" />.</span><span class="sxs-lookup"><span data-stu-id="2592c-122">An object of type <see cref="P:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions.EncryptionPolicy" />.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="LocationMode">
      <MemberSignature Language="C#" Value="public Nullable&lt;Microsoft.WindowsAzure.Storage.RetryPolicies.LocationMode&gt; LocationMode { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype Microsoft.WindowsAzure.Storage.RetryPolicies.LocationMode&gt; LocationMode" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions.LocationMode" />
      <MemberSignature Language="VB.NET" Value="Public Property LocationMode As Nullable(Of LocationMode)" />
      <MemberSignature Language="F#" Value="member this.LocationMode : Nullable&lt;Microsoft.WindowsAzure.Storage.RetryPolicies.LocationMode&gt; with get, set" Usage="Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions.LocationMode" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:Microsoft.WindowsAzure.Storage.IRequestOptions.LocationMode</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;Microsoft.WindowsAzure.Storage.RetryPolicies.LocationMode&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
             <span data-ttu-id="2592c-123">Ruft ab oder legt den Positionsmodus der Anforderung fest.</span><span class="sxs-lookup"><span data-stu-id="2592c-123">Gets or sets the location mode of the request.</span></span>
             </summary>
        <value><span data-ttu-id="2592c-124">Ein <see cref="T:Microsoft.WindowsAzure.Storage.RetryPolicies.LocationMode" /> -Enumerationswert, der angibt, des Positionsmodus der Anforderung.</span><span class="sxs-lookup"><span data-stu-id="2592c-124">A <see cref="T:Microsoft.WindowsAzure.Storage.RetryPolicies.LocationMode" /> enumeration value indicating the location mode of the request.</span></span></value>
        <remarks><span data-ttu-id="2592c-125">Die LocationMode gibt an, in dem Speicherorte der Storage Client versucht, für die Anforderung.</span><span class="sxs-lookup"><span data-stu-id="2592c-125">The LocationMode specifies in which locations the Storage Client will attempt to make the request.</span></span> <span data-ttu-id="2592c-126">Dies gilt nur für Konten für RA-GRS - Konten, in denen Daten aus der primären oder sekundären Endpunkt gelesen werden kann.</span><span class="sxs-lookup"><span data-stu-id="2592c-126">This is only valid for RA-GRS accounts - accounts where data can be read from either the primary or the secondary endpoint.</span></span>
             </remarks>
      </Docs>
    </Member>
    <Member MemberName="MaximumExecutionTime">
      <MemberSignature Language="C#" Value="public Nullable&lt;TimeSpan&gt; MaximumExecutionTime { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.TimeSpan&gt; MaximumExecutionTime" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions.MaximumExecutionTime" />
      <MemberSignature Language="VB.NET" Value="Public Property MaximumExecutionTime As Nullable(Of TimeSpan)" />
      <MemberSignature Language="F#" Value="member this.MaximumExecutionTime : Nullable&lt;TimeSpan&gt; with get, set" Usage="Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions.MaximumExecutionTime" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:Microsoft.WindowsAzure.Storage.IRequestOptions.MaximumExecutionTime</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.TimeSpan&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="2592c-127">Ruft ab oder legt die maximale Ausführungszeit für alle möglichen Wiederholungen für die Anforderung.</span><span class="sxs-lookup"><span data-stu-id="2592c-127">Gets or sets the maximum execution time across all potential retries for the request.</span></span> 
            </summary>
        <value><span data-ttu-id="2592c-128">Ein <see cref="T:System.TimeSpan" /> , die die maximale Ausführungszeit für Wiederholungen für die Anforderung darstellt.</span><span class="sxs-lookup"><span data-stu-id="2592c-128">A <see cref="T:System.TimeSpan" /> representing the maximum execution time for retries for the request.</span></span></value>
        <remarks>
            <span data-ttu-id="2592c-129">Die maximale Ausführungszeit werden für einen einzelnen API-Aufruf zugeteilt.</span><span class="sxs-lookup"><span data-stu-id="2592c-129">The maximum execution time is the time allotted for a single API call.</span></span>
            <span data-ttu-id="2592c-130">Wenn der insgesamt in der API - für alle übrigen Anforderungen aufgewendete Zeit Wiederholungen usw. -diesen Wert überschreitet, tritt ein Timeout des Clients.</span><span class="sxs-lookup"><span data-stu-id="2592c-130">If the total amount of time spent in the API - across all REST requests, retries, etc - exceeds this value, the client will timeout.</span></span> <span data-ttu-id="2592c-131">Dieser Wert nur auf dem Client verfolgt wird, ist es nicht an den Dienst gesendet.</span><span class="sxs-lookup"><span data-stu-id="2592c-131">This value is only tracked on the client, it is not sent to the service.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ParallelOperationThreadCount">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; ParallelOperationThreadCount { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; ParallelOperationThreadCount" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions.ParallelOperationThreadCount" />
      <MemberSignature Language="VB.NET" Value="Public Property ParallelOperationThreadCount As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.ParallelOperationThreadCount : Nullable&lt;int&gt; with get, set" Usage="Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions.ParallelOperationThreadCount" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
             <span data-ttu-id="2592c-132">Ruft ab oder legt die Anzahl der Blöcke, die gleichzeitig hochgeladen werden können.</span><span class="sxs-lookup"><span data-stu-id="2592c-132">Gets or sets the number of blocks that may be simultaneously uploaded.</span></span>
             </summary>
        <value><span data-ttu-id="2592c-133">Ein ganzzahliger Wert, der angibt, der Anzahl der parallelen blobhochladevorgänge upload-Vorgänge, die fortgesetzt werden können.</span><span class="sxs-lookup"><span data-stu-id="2592c-133">An integer value indicating the number of parallel blob upload operations that may proceed.</span></span></value>
        <remarks>
             <span data-ttu-id="2592c-134">Wenn Sie die UploadFrom \*-Methoden für ein Blob zu verwenden, wird das Blob in Blöcke aufgeteilt werden.</span><span class="sxs-lookup"><span data-stu-id="2592c-134">When using the UploadFrom\* methods on a blob, the blob will be broken up into blocks.</span></span> <span data-ttu-id="2592c-135">Das Festlegen dieser Grenzwerte, die die Anzahl der ausstehenden e/a-"put Block" fordert, dass die Bibliothek zu einem bestimmten Zeitpunkt in-Flight aufweist.</span><span class="sxs-lookup"><span data-stu-id="2592c-135">Setting this value limits the number of outstanding I/O "put block" requests that the library will have in-flight at a given time.</span></span> <span data-ttu-id="2592c-136">Standard ist 1 (keine Parallelität).</span><span class="sxs-lookup"><span data-stu-id="2592c-136">Default is 1 (no parallelism).</span></span> <span data-ttu-id="2592c-137">Erhöhen des Werts möglicherweise schneller Blob-Uploads, je nach im Netzwerk zwischen dem Client und dem Azure Storage-Dienst.</span><span class="sxs-lookup"><span data-stu-id="2592c-137">Setting this value higher may result in faster blob uploads, depending on the network between the client and the Azure Storage service.</span></span>
             <span data-ttu-id="2592c-138">Wenn Blobs sind klein (weniger als 256 MB), lassen diesen Wert gleich 1 wird abgeraten.</span><span class="sxs-lookup"><span data-stu-id="2592c-138">If blobs are small (less than 256 MB), keeping this value equal to 1 is advised.</span></span>
             </remarks>
      </Docs>
    </Member>
    <Member MemberName="RequireEncryption">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; RequireEncryption { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; RequireEncryption" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions.RequireEncryption" />
      <MemberSignature Language="VB.NET" Value="Public Property RequireEncryption As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.RequireEncryption : Nullable&lt;bool&gt; with get, set" Usage="Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions.RequireEncryption" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:Microsoft.WindowsAzure.Storage.IRequestOptions.RequireEncryption</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="2592c-139">Ruft ab oder legt einen Wert anzugeben, ob die Daten geschrieben und gelesen werden, von der Clientbibliothek verschlüsselt werden sollen.</span><span class="sxs-lookup"><span data-stu-id="2592c-139">Gets or sets a value to indicate whether data written and read by the client library should be encrypted.</span></span>
            </summary>
        <value><span data-ttu-id="2592c-140">Verwendung <c>"true"</c> um anzugeben, dass die Daten werden soll, für alle Transaktionen verschlüsselt und entschlüsselt, und andernfalls <c>"false"</c>.</span><span class="sxs-lookup"><span data-stu-id="2592c-140">Use <c>true</c> to specify that data should be encrypted/decrypted for all transactions; otherwise, <c>false</c>.</span></span></value>
        <remarks>
            <span data-ttu-id="2592c-141">Hier RequireEncryption bezieht sich auf Client-seitige Ver-.</span><span class="sxs-lookup"><span data-stu-id="2592c-141">RequireEncryption here refers to Client-Side Encryption.</span></span>
            <span data-ttu-id="2592c-142">Wenn dieser Wert, um festgelegt wird <c>"true"</c>, alle Aufrufe schlagen fehl, wenn die Daten nicht mit einer Verschlüsselungsrichtlinie verschlüsselt und entschlüsselt sind.</span><span class="sxs-lookup"><span data-stu-id="2592c-142">If this value is set to <c>true</c>, all calls will fail if the data is not encrypted/decrypted with an encryption policy.</span></span> <span data-ttu-id="2592c-143">Wenn dieser Wert "false" (Standard), alle Daten, die heruntergeladen werden, die nicht verschlüsselt ist, wird als zurückgegeben-ist.</span><span class="sxs-lookup"><span data-stu-id="2592c-143">If this value is false (the default), any data being downloaded that is not encrypted will be returned as-is.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="RetryPolicy">
      <MemberSignature Language="C#" Value="public Microsoft.WindowsAzure.Storage.RetryPolicies.IRetryPolicy RetryPolicy { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.WindowsAzure.Storage.RetryPolicies.IRetryPolicy RetryPolicy" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions.RetryPolicy" />
      <MemberSignature Language="VB.NET" Value="Public Property RetryPolicy As IRetryPolicy" />
      <MemberSignature Language="F#" Value="member this.RetryPolicy : Microsoft.WindowsAzure.Storage.RetryPolicies.IRetryPolicy with get, set" Usage="Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions.RetryPolicy" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:Microsoft.WindowsAzure.Storage.IRequestOptions.RetryPolicy</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Storage.RetryPolicies.IRetryPolicy</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
             <span data-ttu-id="2592c-144">Ruft ab oder legt die wiederholungsrichtlinie für die Anforderung.</span><span class="sxs-lookup"><span data-stu-id="2592c-144">Gets or sets the retry policy for the request.</span></span>
             </summary>
        <value><span data-ttu-id="2592c-145">Ein Objekt vom Typ <see cref="T:Microsoft.WindowsAzure.Storage.RetryPolicies.IRetryPolicy" />.</span><span class="sxs-lookup"><span data-stu-id="2592c-145">An object of type <see cref="T:Microsoft.WindowsAzure.Storage.RetryPolicies.IRetryPolicy" />.</span></span></value>
        <remarks> <span data-ttu-id="2592c-146">Wiederholungsrichtlinien weisen die Storage Client um Anforderungsfehler zu wiederholen.</span><span class="sxs-lookup"><span data-stu-id="2592c-146">Retry policies instruct the Storage Client to retry failed requests.</span></span>
             <span data-ttu-id="2592c-147">Standardmäßig werden nur einige Fehler wiederholt.</span><span class="sxs-lookup"><span data-stu-id="2592c-147">By default, only some failures are retried.</span></span> <span data-ttu-id="2592c-148">Beispielsweise können Verbindungsfehler und Drosselung Fehlern wiederholt werden.</span><span class="sxs-lookup"><span data-stu-id="2592c-148">For example, connection failures and throttling failures can be retried.</span></span> <span data-ttu-id="2592c-149">Ressource nicht gefunden (404) oder Authentifizierungsfehler nicht wiederholt, da keine wahrscheinlich bei der Wiederholung erfolgreich sind.</span><span class="sxs-lookup"><span data-stu-id="2592c-149">Resource not found (404) or authentication failures are not retried, because these are not likely to succeed on retry.</span></span>
             <span data-ttu-id="2592c-150">Wenn dies nicht festgelegt ist, der Storage Client verwendet eine exponentiellen Backoff-wiederholungsrichtlinie, ruft die Wartezeit exponentiell länger zwischen den Anforderungen, bis zu einer Summe von ca. 30 Sekunden.</span><span class="sxs-lookup"><span data-stu-id="2592c-150">If not set, the Storage Client uses an exponential backoff retry policy, where the wait time gets exponentially longer between requests, up to a total of around 30 seconds.</span></span>
             <span data-ttu-id="2592c-151">Die standardmäßige wiederholungsrichtlinie wird in den meisten Szenarien empfohlen.</span><span class="sxs-lookup"><span data-stu-id="2592c-151">The default retry policy is recommended for most scenarios.</span></span>
             </remarks>
      </Docs>
    </Member>
    <Member MemberName="ServerTimeout">
      <MemberSignature Language="C#" Value="public Nullable&lt;TimeSpan&gt; ServerTimeout { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.TimeSpan&gt; ServerTimeout" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions.ServerTimeout" />
      <MemberSignature Language="VB.NET" Value="Public Property ServerTimeout As Nullable(Of TimeSpan)" />
      <MemberSignature Language="F#" Value="member this.ServerTimeout : Nullable&lt;TimeSpan&gt; with get, set" Usage="Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions.ServerTimeout" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:Microsoft.WindowsAzure.Storage.IRequestOptions.ServerTimeout</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.TimeSpan&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="2592c-152">Ruft ab oder legt das Servertimeout-Intervall für eine einzelne HTTP-Anforderung.</span><span class="sxs-lookup"><span data-stu-id="2592c-152">Gets or sets the server timeout interval for a single HTTP request.</span></span>
            </summary>
        <value><span data-ttu-id="2592c-153">Ein <see cref="T:System.TimeSpan" /> mit dem servertimeoutintervall für jede HTTP-Anforderung.</span><span class="sxs-lookup"><span data-stu-id="2592c-153">A <see cref="T:System.TimeSpan" /> containing the server timeout interval for each HTTP request.</span></span></value>
        <remarks>
            <span data-ttu-id="2592c-154">Das Servertimeout beträgt das Timeout an den Azure Storage-Dienst für jeden REST-Anforderung gesendet.</span><span class="sxs-lookup"><span data-stu-id="2592c-154">The server timeout is the timeout sent to the Azure Storage service for each REST request made.</span></span> <span data-ttu-id="2592c-155">Wenn die API namens mehrere REST-Aufrufe vornimmt (UploadFromStream, z. B. oder wenn die Anforderung wiederholt), dieses Timeout wird separat für jede Anforderung angewendet werden.</span><span class="sxs-lookup"><span data-stu-id="2592c-155">If the API called makes multiple REST calls (UploadFromStream, for example, or if the request retries), this timeout will be applied separately to each request.</span></span> <span data-ttu-id="2592c-156">Dieser Wert nicht nachverfolgt werden oder auf dem Client überprüft, es wird nur in den Speicherdienst übergeben.</span><span class="sxs-lookup"><span data-stu-id="2592c-156">This value is not tracked or validated on the client, it is only passed to the Storage service.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="SingleBlobUploadThresholdInBytes">
      <MemberSignature Language="C#" Value="public Nullable&lt;long&gt; SingleBlobUploadThresholdInBytes { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int64&gt; SingleBlobUploadThresholdInBytes" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions.SingleBlobUploadThresholdInBytes" />
      <MemberSignature Language="VB.NET" Value="Public Property SingleBlobUploadThresholdInBytes As Nullable(Of Long)" />
      <MemberSignature Language="F#" Value="member this.SingleBlobUploadThresholdInBytes : Nullable&lt;int64&gt; with get, set" Usage="Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions.SingleBlobUploadThresholdInBytes" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int64&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="2592c-157">Ruft ab oder legt die maximale Größe eines BLOBs in Byte, die als einzelnes Blob hochgeladen werden kann.</span><span class="sxs-lookup"><span data-stu-id="2592c-157">Gets or sets the maximum size of a blob in bytes that may be uploaded as a single blob.</span></span> 
            </summary>
        <value><span data-ttu-id="2592c-158">Ein Long-Wert, der angibt, der maximalen Größe eines BLOBs, in Bytes, der als einzelnes Blob im Bereich von 1 und 256 MB liegen einschließlich hochgeladen werden kann.</span><span class="sxs-lookup"><span data-stu-id="2592c-158">A long indicating the maximum size of a blob, in bytes, that may be uploaded as a single blob, ranging from between 1 and 256 MB inclusive.</span></span></value>
        <remarks><span data-ttu-id="2592c-159">Dieser Wert wird ignoriert, wenn die ParallelOperationThreadCount auf einen Wert größer als 1 festgelegt ist</span><span class="sxs-lookup"><span data-stu-id="2592c-159">This value will be ignored if the ParallelOperationThreadCount is set to a value greater than 1</span></span></remarks>
      </Docs>
    </Member>
    <Member MemberName="StoreBlobContentMD5">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; StoreBlobContentMD5 { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; StoreBlobContentMD5" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions.StoreBlobContentMD5" />
      <MemberSignature Language="VB.NET" Value="Public Property StoreBlobContentMD5 As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.StoreBlobContentMD5 : Nullable&lt;bool&gt; with get, set" Usage="Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions.StoreBlobContentMD5" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="2592c-160">Ruft ab oder legt einen Wert fest, um anzugeben, dass ein MD5-Hash berechnet und gespeichert, wenn einen Blob hochladen.</span><span class="sxs-lookup"><span data-stu-id="2592c-160">Gets or sets a value to indicate that an MD5 hash will be calculated and stored when uploading a blob.</span></span>
            </summary>
        <value><span data-ttu-id="2592c-161">Verwendung <c>"true"</c> zum Berechnen und speichern einen MD5-Hash beim Hochladen eines BLOBs; andernfalls <c>"false"</c>.</span><span class="sxs-lookup"><span data-stu-id="2592c-161">Use <c>true</c> to calculate and store an MD5 hash when uploading a blob; otherwise, <c>false</c>.</span></span> <span data-ttu-id="2592c-162">Standardmäßig <c>"false"</c>.</span><span class="sxs-lookup"><span data-stu-id="2592c-162">Defaults to <c>false</c>.</span></span></value>
        <remarks><span data-ttu-id="2592c-163">Diese Eigenschaft wird nicht unterstützt, für die <see cref="T:Microsoft.WindowsAzure.Storage.Blob.CloudAppendBlob" /> Append \* APIs.</span><span class="sxs-lookup"><span data-stu-id="2592c-163">This property is not supported for the <see cref="T:Microsoft.WindowsAzure.Storage.Blob.CloudAppendBlob" /> Append\* APIs.</span></span>
            <span data-ttu-id="2592c-164">Die Option zur StoreBlobContentMD5 weist die Storage Client während eines Vorgangs Upload den MD5-Hash des Blob-Inhalts zu berechnen.</span><span class="sxs-lookup"><span data-stu-id="2592c-164">The StoreBlobContentMD5 request option instructs the Storage Client to calculate the MD5 hash of the blob content during an upload operation.</span></span> <span data-ttu-id="2592c-165">Dieser Wert wird dann als Content-MD5-Header für das Blob gespeichert.</span><span class="sxs-lookup"><span data-stu-id="2592c-165">This value is then stored on the blob object as the Content-MD5 header.</span></span> <span data-ttu-id="2592c-166">Diese Option gilt nur, um Vorgänge hochzuladen.</span><span class="sxs-lookup"><span data-stu-id="2592c-166">This option applies only to upload operations.</span></span> <span data-ttu-id="2592c-167">Dies ist nützlich beim Überprüfen der Integrität des Blob bei späteren herunterladen und mit der Content-MD5-Header, gemäß Definition in der HTTP-Spezifikation kompatibel. Wenn der Speicherclient für spätere herunterladen, wenn der Content-MD5-Header vorhanden ist, wird der MD5-Hash des Inhalts überprüft werden, es sei denn, "DisableContentMD5Validation" festgelegt ist.</span><span class="sxs-lookup"><span data-stu-id="2592c-167">This is useful for validating the integrity of the blob upon later download, and compatible with the Content-MD5 header as defined in the HTTP spec. If using the Storage Client for later download, if the Content-MD5 header is present, the MD5 hash of the content will be validated, unless "DisableContentMD5Validation" is set.</span></span>
            <span data-ttu-id="2592c-168">Beachten Sie, dass dieser Wert auf den Azure-Speicherdienst hochladen oder Herunterladen von Daten nicht überprüft wird. Er ist lediglich gespeichert und zurückgegeben.</span><span class="sxs-lookup"><span data-stu-id="2592c-168">Note that this value is not validated on the Azure Storage service on either upload or download of data; it is merely stored and returned.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="UseTransactionalMD5">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; UseTransactionalMD5 { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; UseTransactionalMD5" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions.UseTransactionalMD5" />
      <MemberSignature Language="VB.NET" Value="Public Property UseTransactionalMD5 As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.UseTransactionalMD5 : Nullable&lt;bool&gt; with get, set" Usage="Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions.UseTransactionalMD5" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="2592c-169">Ruft ab oder legt einen Wert berechnen und Senden/prüfen von Inhalts-MD5 für Transaktionen.</span><span class="sxs-lookup"><span data-stu-id="2592c-169">Gets or sets a value to calculate and send/validate content MD5 for transactions.</span></span>
            </summary>
        <value><span data-ttu-id="2592c-170">Verwendung <c>"true"</c> zu berechnen und Senden/prüfen von Inhalts-MD5 für Transaktionen; andernfalls <c>"false"</c>.</span><span class="sxs-lookup"><span data-stu-id="2592c-170">Use <c>true</c> to calculate and send/validate content MD5 for transactions; otherwise, <c>false</c>.</span></span> <span data-ttu-id="2592c-171">Die Standardeinstellung lautet <c>false</c>.</span><span class="sxs-lookup"><span data-stu-id="2592c-171">Default is <c>false</c>.</span></span></value>
        <remarks>
            <span data-ttu-id="2592c-172">Die UseTransactionalMD5-Option weist der Speicherclient berechnet und überprüft den MD5-Hash der einzelnen Speicher REST-Vorgänge.</span><span class="sxs-lookup"><span data-stu-id="2592c-172">The UseTransactionalMD5 option instructs the Storage Client to calculate and validate the MD5 hash of individual Storage REST operations.</span></span> <span data-ttu-id="2592c-173">Für einen angegebenen REST-Vorgang Wenn dieser Wert festgelegt ist, sowohl die Storage Client den Speicherdienst berechnet den MD5-Hash der übertragenen Daten und schlägt fehl, wenn die Werte nicht übereinstimmen.</span><span class="sxs-lookup"><span data-stu-id="2592c-173">For a given REST operation, if this value is set, both the Storage Client and the Storage service will calculate the MD5 hash of the transferred data, and will fail if the values do not match.</span></span>
            <span data-ttu-id="2592c-174">Dieser Wert wird auf den Dienst oder der Client nicht beibehalten.</span><span class="sxs-lookup"><span data-stu-id="2592c-174">This value is not persisted on the service or the client.</span></span>
            <span data-ttu-id="2592c-175">Diese Option gilt für sowohl upload und download-Vorgänge.</span><span class="sxs-lookup"><span data-stu-id="2592c-175">This option applies to both upload and download operations.</span></span>
            <span data-ttu-id="2592c-176">Beachten Sie, dass HTTPS eine ähnliche Überprüfung während der Übertragung verwendet wird.</span><span class="sxs-lookup"><span data-stu-id="2592c-176">Note that HTTPS does a similar check during transit.</span></span> <span data-ttu-id="2592c-177">Wenn Sie HTTPS verwenden, wird empfohlen, dass diese Funktion deaktiviert werden.</span><span class="sxs-lookup"><span data-stu-id="2592c-177">If you are using HTTPS, we recommend this feature be off.</span></span>
            </remarks>
      </Docs>
    </Member>
  </Members>
</Type>