<Type Name="BlobProperties" FullName="Microsoft.WindowsAzure.Storage.Blob.BlobProperties">
  <TypeSignature Language="C#" Value="public sealed class BlobProperties" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit BlobProperties extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.WindowsAzure.Storage.Blob.BlobProperties" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class BlobProperties" />
  <TypeSignature Language="F#" Value="type BlobProperties = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
    <AssemblyVersion>8.4.0.0</AssemblyVersion>
    <AssemblyVersion>8.7.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="169ee-101">Stellt die Systemeigenschaften für ein Blob dar.</span><span class="sxs-lookup"><span data-stu-id="169ee-101">Represents the system properties for a blob.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public BlobProperties ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.BlobProperties.#ctor" />
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
            <span data-ttu-id="169ee-102">Initialisiert eine neue Instanz der <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobProperties" />-Klasse.</span><span class="sxs-lookup"><span data-stu-id="169ee-102">Initializes a new instance of the <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobProperties" /> class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public BlobProperties (Microsoft.WindowsAzure.Storage.Blob.BlobProperties other);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class Microsoft.WindowsAzure.Storage.Blob.BlobProperties other) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.BlobProperties.#ctor(Microsoft.WindowsAzure.Storage.Blob.BlobProperties)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (other As BlobProperties)" />
      <MemberSignature Language="F#" Value="new Microsoft.WindowsAzure.Storage.Blob.BlobProperties : Microsoft.WindowsAzure.Storage.Blob.BlobProperties -&gt; Microsoft.WindowsAzure.Storage.Blob.BlobProperties" Usage="new Microsoft.WindowsAzure.Storage.Blob.BlobProperties other" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="other" Type="Microsoft.WindowsAzure.Storage.Blob.BlobProperties" />
      </Parameters>
      <Docs>
        <param name="other"><span data-ttu-id="169ee-103">Ein <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobProperties" />-Objekt.</span><span class="sxs-lookup"><span data-stu-id="169ee-103">A <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobProperties" /> object.</span></span></param>
        <summary>
            <span data-ttu-id="169ee-104">Initialisiert eine neue Instanz der dem <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobProperties" /> -Klasse auf Grundlage einer vorhandenen Instanz.</span><span class="sxs-lookup"><span data-stu-id="169ee-104">Initializes a new instance of the <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobProperties" /> class based on an existing instance.</span></span>
            </summary>
        <remarks><span data-ttu-id="169ee-105">Leasebezogene Eigenschaften werden nicht geklont werden, da eine Basis-Blob zugeordnete Lease nicht in die Momentaufnahme kopiert wird.</span><span class="sxs-lookup"><span data-stu-id="169ee-105">Lease-related properties will not be cloned, because a lease associated with the base blob is not copied to the snapshot.</span></span></remarks>
      </Docs>
    </Member>
    <Member MemberName="AppendBlobCommittedBlockCount">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; AppendBlobCommittedBlockCount { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; AppendBlobCommittedBlockCount" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.Blob.BlobProperties.AppendBlobCommittedBlockCount" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property AppendBlobCommittedBlockCount As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.AppendBlobCommittedBlockCount : Nullable&lt;int&gt;" Usage="Microsoft.WindowsAzure.Storage.Blob.BlobProperties.AppendBlobCommittedBlockCount" />
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
            <span data-ttu-id="169ee-106">Wenn das Blob ein Anhang-Blob ist, ruft die Anzahl der Blöcke mit ausgeführtem Commit.</span><span class="sxs-lookup"><span data-stu-id="169ee-106">If the blob is an append blob, gets the number of committed blocks.</span></span>
            </summary>
        <value><span data-ttu-id="169ee-107">Eine ganze Zahl, die die Anzahl der Blöcke mit ausgeführtem Commit enthält.</span><span class="sxs-lookup"><span data-stu-id="169ee-107">An integer containing the number of committed blocks.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BlobTierInferred">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; BlobTierInferred { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; BlobTierInferred" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.Blob.BlobProperties.BlobTierInferred" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property BlobTierInferred As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.BlobTierInferred : Nullable&lt;bool&gt;" Usage="Microsoft.WindowsAzure.Storage.Blob.BlobProperties.BlobTierInferred" />
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
            <span data-ttu-id="169ee-108">Ruft einen Wert, der angibt, ob die Ebene des BLOBs abgeleitet wurde.</span><span class="sxs-lookup"><span data-stu-id="169ee-108">Gets a value indicating if the tier of the blob has been inferred.</span></span>
            </summary>
        <value><span data-ttu-id="169ee-109">Ein Bool, darstellt, wenn die Blob-Ebene abgeleitet wurde.</span><span class="sxs-lookup"><span data-stu-id="169ee-109">A bool representing if the blob tier has been inferred.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BlobTierLastModifiedTime">
      <MemberSignature Language="C#" Value="public Nullable&lt;DateTimeOffset&gt; BlobTierLastModifiedTime { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.DateTimeOffset&gt; BlobTierLastModifiedTime" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.Blob.BlobProperties.BlobTierLastModifiedTime" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property BlobTierLastModifiedTime As Nullable(Of DateTimeOffset)" />
      <MemberSignature Language="F#" Value="member this.BlobTierLastModifiedTime : Nullable&lt;DateTimeOffset&gt;" Usage="Microsoft.WindowsAzure.Storage.Blob.BlobProperties.BlobTierLastModifiedTime" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.DateTimeOffset&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="169ee-110">Ruft die Zeit für ab, wenn die Ebene des Blob zuletzt geändert wurde, ausgedrückt als UTC-Wert.</span><span class="sxs-lookup"><span data-stu-id="169ee-110">Gets the time for when the tier of the blob was last-modified, expressed as a UTC value.</span></span>
            </summary>
        <value><span data-ttu-id="169ee-111">Ein <see cref="T:System.DateTimeOffset" /> , der die Uhrzeit die Ebene des BLOBs wurde zuletzt geändert, im UTC-Format enthält.</span><span class="sxs-lookup"><span data-stu-id="169ee-111">A <see cref="T:System.DateTimeOffset" /> containing the time for when the tier of the blob was last-modified, in UTC format.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BlobType">
      <MemberSignature Language="C#" Value="public Microsoft.WindowsAzure.Storage.Blob.BlobType BlobType { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype Microsoft.WindowsAzure.Storage.Blob.BlobType BlobType" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.Blob.BlobProperties.BlobType" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property BlobType As BlobType" />
      <MemberSignature Language="F#" Value="member this.BlobType : Microsoft.WindowsAzure.Storage.Blob.BlobType" Usage="Microsoft.WindowsAzure.Storage.Blob.BlobProperties.BlobType" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Storage.Blob.BlobType</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="169ee-112">Ruft den Typ des BLOBs ab.</span><span class="sxs-lookup"><span data-stu-id="169ee-112">Gets the type of the blob.</span></span>
            </summary>
        <value><span data-ttu-id="169ee-113">Ein <see cref="P:Microsoft.WindowsAzure.Storage.Blob.BlobProperties.BlobType" /> -Objekt, das den Typ des BLOBs angibt.</span><span class="sxs-lookup"><span data-stu-id="169ee-113">A <see cref="P:Microsoft.WindowsAzure.Storage.Blob.BlobProperties.BlobType" /> object that indicates the type of the blob.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CacheControl">
      <MemberSignature Language="C#" Value="public string CacheControl { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string CacheControl" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.Blob.BlobProperties.CacheControl" />
      <MemberSignature Language="VB.NET" Value="Public Property CacheControl As String" />
      <MemberSignature Language="F#" Value="member this.CacheControl : string with get, set" Usage="Microsoft.WindowsAzure.Storage.Blob.BlobProperties.CacheControl" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="169ee-114">Ruft ab oder legt den für das Blob gespeicherten Cache-Control-Wert fest.</span><span class="sxs-lookup"><span data-stu-id="169ee-114">Gets or sets the cache-control value stored for the blob.</span></span>
            </summary>
        <value><span data-ttu-id="169ee-115">Eine Zeichenfolge, die das Blob-Cache-Control-Wert enthält.</span><span class="sxs-lookup"><span data-stu-id="169ee-115">A string containing the blob's cache-control value.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ContentDisposition">
      <MemberSignature Language="C#" Value="public string ContentDisposition { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ContentDisposition" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.Blob.BlobProperties.ContentDisposition" />
      <MemberSignature Language="VB.NET" Value="Public Property ContentDisposition As String" />
      <MemberSignature Language="F#" Value="member this.ContentDisposition : string with get, set" Usage="Microsoft.WindowsAzure.Storage.Blob.BlobProperties.ContentDisposition" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="169ee-116">Ruft ab oder legt den für das Blob gespeicherten Content-Disposition-Wert fest.</span><span class="sxs-lookup"><span data-stu-id="169ee-116">Gets or sets the content-disposition value stored for the blob.</span></span>
            </summary>
        <value><span data-ttu-id="169ee-117">Eine Zeichenfolge, die Content-Disposition-Wert des BLOBs enthält.</span><span class="sxs-lookup"><span data-stu-id="169ee-117">A string containing the blob's content-disposition value.</span></span></value>
        <remarks>
            <span data-ttu-id="169ee-118">Wenn diese Eigenschaft nicht für das Blob festgelegt wurde, gibt es <c>null</c>.</span><span class="sxs-lookup"><span data-stu-id="169ee-118">If this property has not been set for the blob, it returns <c>null</c>.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ContentEncoding">
      <MemberSignature Language="C#" Value="public string ContentEncoding { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ContentEncoding" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.Blob.BlobProperties.ContentEncoding" />
      <MemberSignature Language="VB.NET" Value="Public Property ContentEncoding As String" />
      <MemberSignature Language="F#" Value="member this.ContentEncoding : string with get, set" Usage="Microsoft.WindowsAzure.Storage.Blob.BlobProperties.ContentEncoding" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="169ee-119">Ruft ab oder legt den für das Blob gespeicherten Content-encoding-Wert.</span><span class="sxs-lookup"><span data-stu-id="169ee-119">Gets or sets the content-encoding value stored for the blob.</span></span>
            </summary>
        <value><span data-ttu-id="169ee-120">Eine Zeichenfolge mit dem Blob-Content-encoding-Wert.</span><span class="sxs-lookup"><span data-stu-id="169ee-120">A string containing the blob's content-encoding value.</span></span></value>
        <remarks>
            <span data-ttu-id="169ee-121">Wenn diese Eigenschaft nicht für das Blob festgelegt wurde, gibt es <c>null</c>.</span><span class="sxs-lookup"><span data-stu-id="169ee-121">If this property has not been set for the blob, it returns <c>null</c>.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ContentLanguage">
      <MemberSignature Language="C#" Value="public string ContentLanguage { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ContentLanguage" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.Blob.BlobProperties.ContentLanguage" />
      <MemberSignature Language="VB.NET" Value="Public Property ContentLanguage As String" />
      <MemberSignature Language="F#" Value="member this.ContentLanguage : string with get, set" Usage="Microsoft.WindowsAzure.Storage.Blob.BlobProperties.ContentLanguage" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="169ee-122">Ruft ab oder legt den für das Blob gespeicherten Content-Language-Wert fest.</span><span class="sxs-lookup"><span data-stu-id="169ee-122">Gets or sets the content-language value stored for the blob.</span></span>
            </summary>
        <value><span data-ttu-id="169ee-123">Eine Zeichenfolge mit dem Blob-Content-Language-Wert.</span><span class="sxs-lookup"><span data-stu-id="169ee-123">A string containing the blob's content-language value.</span></span></value>
        <remarks>
            <span data-ttu-id="169ee-124">Wenn diese Eigenschaft nicht für das Blob festgelegt wurde, gibt es <c>null</c>.</span><span class="sxs-lookup"><span data-stu-id="169ee-124">If this property has not been set for the blob, it returns <c>null</c>.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ContentMD5">
      <MemberSignature Language="C#" Value="public string ContentMD5 { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ContentMD5" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.Blob.BlobProperties.ContentMD5" />
      <MemberSignature Language="VB.NET" Value="Public Property ContentMD5 As String" />
      <MemberSignature Language="F#" Value="member this.ContentMD5 : string with get, set" Usage="Microsoft.WindowsAzure.Storage.Blob.BlobProperties.ContentMD5" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="169ee-125">Ruft ab oder legt den für das Blob gespeicherten Content-MD5-Wert fest.</span><span class="sxs-lookup"><span data-stu-id="169ee-125">Gets or sets the content-MD5 value stored for the blob.</span></span>
            </summary>
        <value><span data-ttu-id="169ee-126">Eine Zeichenfolge, die Content-MD5-Hash des BLOBs enthält.</span><span class="sxs-lookup"><span data-stu-id="169ee-126">A string containing the blob's content-MD5 hash.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ContentType">
      <MemberSignature Language="C#" Value="public string ContentType { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ContentType" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.Blob.BlobProperties.ContentType" />
      <MemberSignature Language="VB.NET" Value="Public Property ContentType As String" />
      <MemberSignature Language="F#" Value="member this.ContentType : string with get, set" Usage="Microsoft.WindowsAzure.Storage.Blob.BlobProperties.ContentType" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="169ee-127">Ruft ab oder legt den für das Blob gespeicherten Content-Type-Wert fest.</span><span class="sxs-lookup"><span data-stu-id="169ee-127">Gets or sets the content-type value stored for the blob.</span></span>
            </summary>
        <value><span data-ttu-id="169ee-128">Eine Zeichenfolge mit dem Blob Content-Type-Wert.</span><span class="sxs-lookup"><span data-stu-id="169ee-128">A string containing the blob's content-type value.</span></span></value>
        <remarks>
            <span data-ttu-id="169ee-129">Wenn diese Eigenschaft nicht für das Blob festgelegt wurde, gibt es <c>null</c>.</span><span class="sxs-lookup"><span data-stu-id="169ee-129">If this property has not been set for the blob, it returns <c>null</c>.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ETag">
      <MemberSignature Language="C#" Value="public string ETag { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ETag" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.Blob.BlobProperties.ETag" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ETag As String" />
      <MemberSignature Language="F#" Value="member this.ETag : string" Usage="Microsoft.WindowsAzure.Storage.Blob.BlobProperties.ETag" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="169ee-130">Ruft ETag-Wert des BLOBs ab.</span><span class="sxs-lookup"><span data-stu-id="169ee-130">Gets the blob's ETag value.</span></span>
            </summary>
        <value><span data-ttu-id="169ee-131">Eine Zeichenfolge mit dem Blob-ETag-Wert.</span><span class="sxs-lookup"><span data-stu-id="169ee-131">A string containing the blob's ETag value.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IsIncrementalCopy">
      <MemberSignature Language="C#" Value="public bool IsIncrementalCopy { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool IsIncrementalCopy" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.Blob.BlobProperties.IsIncrementalCopy" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property IsIncrementalCopy As Boolean" />
      <MemberSignature Language="F#" Value="member this.IsIncrementalCopy : bool" Usage="Microsoft.WindowsAzure.Storage.Blob.BlobProperties.IsIncrementalCopy" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="169ee-132">Ruft einen Wert, der angibt, ab, unabhängig davon, ob dieses Blob eine inkrementelle Kopie ist.</span><span class="sxs-lookup"><span data-stu-id="169ee-132">Gets a value indicating whether or not this blob is an incremental copy.</span></span>
            </summary>
        <value><span data-ttu-id="169ee-133">Ein Bool, darstellt, wenn das Blob eine inkrementelle Kopie.</span><span class="sxs-lookup"><span data-stu-id="169ee-133">A bool representing if the blob is an incremental copy.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IsServerEncrypted">
      <MemberSignature Language="C#" Value="public bool IsServerEncrypted { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool IsServerEncrypted" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.Blob.BlobProperties.IsServerEncrypted" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property IsServerEncrypted As Boolean" />
      <MemberSignature Language="F#" Value="member this.IsServerEncrypted : bool" Usage="Microsoft.WindowsAzure.Storage.Blob.BlobProperties.IsServerEncrypted" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="169ee-134">Ruft die serverseitige Verschlüsselung Zustand des BLOBs ab.</span><span class="sxs-lookup"><span data-stu-id="169ee-134">Gets the blob's server-side encryption state.</span></span>
            </summary>
        <value><span data-ttu-id="169ee-135">Bool, serverseitige Verschlüsselungsstatus für das Blob darstellt.</span><span class="sxs-lookup"><span data-stu-id="169ee-135">A bool representing the blob's server-side encryption state.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="LastModified">
      <MemberSignature Language="C#" Value="public Nullable&lt;DateTimeOffset&gt; LastModified { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.DateTimeOffset&gt; LastModified" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.Blob.BlobProperties.LastModified" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property LastModified As Nullable(Of DateTimeOffset)" />
      <MemberSignature Language="F#" Value="member this.LastModified : Nullable&lt;DateTimeOffset&gt;" Usage="Microsoft.WindowsAzure.Storage.Blob.BlobProperties.LastModified" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.DateTimeOffset&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="169ee-136">Ruft die Uhrzeit der letzten Änderung für das Blob als UTC-Wert ausgedrückt.</span><span class="sxs-lookup"><span data-stu-id="169ee-136">Gets the the last-modified time for the blob, expressed as a UTC value.</span></span>
            </summary>
        <value><span data-ttu-id="169ee-137">Ein <see cref="T:System.DateTimeOffset" /> , die das Blob Last-modified-Zeit im UTC-Format enthält.</span><span class="sxs-lookup"><span data-stu-id="169ee-137">A <see cref="T:System.DateTimeOffset" /> containing the blob's last-modified time, in UTC format.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="LeaseDuration">
      <MemberSignature Language="C#" Value="public Microsoft.WindowsAzure.Storage.Blob.LeaseDuration LeaseDuration { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype Microsoft.WindowsAzure.Storage.Blob.LeaseDuration LeaseDuration" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.Blob.BlobProperties.LeaseDuration" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property LeaseDuration As LeaseDuration" />
      <MemberSignature Language="F#" Value="member this.LeaseDuration : Microsoft.WindowsAzure.Storage.Blob.LeaseDuration" Usage="Microsoft.WindowsAzure.Storage.Blob.BlobProperties.LeaseDuration" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Storage.Blob.LeaseDuration</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="169ee-138">Ruft die Leasedauer des BLOBs ab.</span><span class="sxs-lookup"><span data-stu-id="169ee-138">Gets the blob's lease duration.</span></span>
            </summary>
        <value><span data-ttu-id="169ee-139">Ein <see cref="P:Microsoft.WindowsAzure.Storage.Blob.BlobProperties.LeaseDuration" /> Objekt, das die Blob-Leasedauer angibt.</span><span class="sxs-lookup"><span data-stu-id="169ee-139">A <see cref="P:Microsoft.WindowsAzure.Storage.Blob.BlobProperties.LeaseDuration" /> object that indicates the blob's lease duration.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="LeaseState">
      <MemberSignature Language="C#" Value="public Microsoft.WindowsAzure.Storage.Blob.LeaseState LeaseState { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype Microsoft.WindowsAzure.Storage.Blob.LeaseState LeaseState" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.Blob.BlobProperties.LeaseState" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property LeaseState As LeaseState" />
      <MemberSignature Language="F#" Value="member this.LeaseState : Microsoft.WindowsAzure.Storage.Blob.LeaseState" Usage="Microsoft.WindowsAzure.Storage.Blob.BlobProperties.LeaseState" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Storage.Blob.LeaseState</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="169ee-140">Ruft die Leasezustand des BLOBs ab.</span><span class="sxs-lookup"><span data-stu-id="169ee-140">Gets the blob's lease state.</span></span>
            </summary>
        <value><span data-ttu-id="169ee-141">Ein <see cref="P:Microsoft.WindowsAzure.Storage.Blob.BlobProperties.LeaseState" /> Objekt, das Leasezustand des BLOBs angibt.</span><span class="sxs-lookup"><span data-stu-id="169ee-141">A <see cref="P:Microsoft.WindowsAzure.Storage.Blob.BlobProperties.LeaseState" /> object that indicates the blob's lease state.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="LeaseStatus">
      <MemberSignature Language="C#" Value="public Microsoft.WindowsAzure.Storage.Blob.LeaseStatus LeaseStatus { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype Microsoft.WindowsAzure.Storage.Blob.LeaseStatus LeaseStatus" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.Blob.BlobProperties.LeaseStatus" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property LeaseStatus As LeaseStatus" />
      <MemberSignature Language="F#" Value="member this.LeaseStatus : Microsoft.WindowsAzure.Storage.Blob.LeaseStatus" Usage="Microsoft.WindowsAzure.Storage.Blob.BlobProperties.LeaseStatus" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Storage.Blob.LeaseStatus</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="169ee-142">Ruft die Blob-Lease-Status ab.</span><span class="sxs-lookup"><span data-stu-id="169ee-142">Gets the blob's lease status.</span></span>
            </summary>
        <value><span data-ttu-id="169ee-143">Ein <see cref="P:Microsoft.WindowsAzure.Storage.Blob.BlobProperties.LeaseStatus" /> Objekt, das Leasestatus des BLOBs angibt.</span><span class="sxs-lookup"><span data-stu-id="169ee-143">A <see cref="P:Microsoft.WindowsAzure.Storage.Blob.BlobProperties.LeaseStatus" /> object that indicates the blob's lease status.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Length">
      <MemberSignature Language="C#" Value="public long Length { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 Length" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.Blob.BlobProperties.Length" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Length As Long" />
      <MemberSignature Language="F#" Value="member this.Length : int64" Usage="Microsoft.WindowsAzure.Storage.Blob.BlobProperties.Length" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int64</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="169ee-144">Ruft die Größe des BLOBs in Byte ab.</span><span class="sxs-lookup"><span data-stu-id="169ee-144">Gets the size of the blob, in bytes.</span></span>
            </summary>
        <value><span data-ttu-id="169ee-145">Ein long-Wert, der das Blob-Größe in Bytes enthält.</span><span class="sxs-lookup"><span data-stu-id="169ee-145">A long value containing the blob's size in bytes.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PageBlobSequenceNumber">
      <MemberSignature Language="C#" Value="public Nullable&lt;long&gt; PageBlobSequenceNumber { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int64&gt; PageBlobSequenceNumber" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.Blob.BlobProperties.PageBlobSequenceNumber" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property PageBlobSequenceNumber As Nullable(Of Long)" />
      <MemberSignature Language="F#" Value="member this.PageBlobSequenceNumber : Nullable&lt;int64&gt;" Usage="Microsoft.WindowsAzure.Storage.Blob.BlobProperties.PageBlobSequenceNumber" />
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
            <span data-ttu-id="169ee-146">Wenn das Blob ein Seitenblob ist, ruft die aktuelle Sequenznummer des BLOBs ab.</span><span class="sxs-lookup"><span data-stu-id="169ee-146">If the blob is a page blob, gets the blob's current sequence number.</span></span>
            </summary>
        <value><span data-ttu-id="169ee-147">Ein Long-Wert, der die aktuelle Sequenznummer des BLOBs enthält.</span><span class="sxs-lookup"><span data-stu-id="169ee-147">A long containing the blob's current sequence number.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PremiumPageBlobTier">
      <MemberSignature Language="C#" Value="public Nullable&lt;Microsoft.WindowsAzure.Storage.Blob.PremiumPageBlobTier&gt; PremiumPageBlobTier { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype Microsoft.WindowsAzure.Storage.Blob.PremiumPageBlobTier&gt; PremiumPageBlobTier" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.Blob.BlobProperties.PremiumPageBlobTier" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property PremiumPageBlobTier As Nullable(Of PremiumPageBlobTier)" />
      <MemberSignature Language="F#" Value="member this.PremiumPageBlobTier : Nullable&lt;Microsoft.WindowsAzure.Storage.Blob.PremiumPageBlobTier&gt;" Usage="Microsoft.WindowsAzure.Storage.Blob.BlobProperties.PremiumPageBlobTier" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;Microsoft.WindowsAzure.Storage.Blob.PremiumPageBlobTier&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="169ee-148">Ruft einen Wert, der angibt, auf der Ebene der Premium-Seiten-Blob.</span><span class="sxs-lookup"><span data-stu-id="169ee-148">Gets a value indicating the tier of the premium page blob.</span></span>
            </summary>
        <value><span data-ttu-id="169ee-149">Ein <see cref="P:Microsoft.WindowsAzure.Storage.Blob.BlobProperties.PremiumPageBlobTier" /> Objekt, das die Seite "-Blob-Ebene angibt.</span><span class="sxs-lookup"><span data-stu-id="169ee-149">A <see cref="P:Microsoft.WindowsAzure.Storage.Blob.BlobProperties.PremiumPageBlobTier" /> object that indicates the page blob tier.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RehydrationStatus">
      <MemberSignature Language="C#" Value="public Nullable&lt;Microsoft.WindowsAzure.Storage.Blob.RehydrationStatus&gt; RehydrationStatus { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype Microsoft.WindowsAzure.Storage.Blob.RehydrationStatus&gt; RehydrationStatus" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.Blob.BlobProperties.RehydrationStatus" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property RehydrationStatus As Nullable(Of RehydrationStatus)" />
      <MemberSignature Language="F#" Value="member this.RehydrationStatus : Nullable&lt;Microsoft.WindowsAzure.Storage.Blob.RehydrationStatus&gt;" Usage="Microsoft.WindowsAzure.Storage.Blob.BlobProperties.RehydrationStatus" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;Microsoft.WindowsAzure.Storage.Blob.RehydrationStatus&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="169ee-150">Ruft einen Wert, der angibt, dass das Blob wird Rehdrated und die Ebene des BLOBs nach Abschluss der Aktivierung aus dem Archiv.</span><span class="sxs-lookup"><span data-stu-id="169ee-150">Gets a value indicating that the blob is being rehdrated and the tier of the blob once the rehydration from archive has completed.</span></span>
            </summary>
        <value><span data-ttu-id="169ee-151">Ein <see cref="P:Microsoft.WindowsAzure.Storage.Blob.BlobProperties.RehydrationStatus" /> , die den Status der Aktivierung des Blob darstellt.</span><span class="sxs-lookup"><span data-stu-id="169ee-151">A <see cref="P:Microsoft.WindowsAzure.Storage.Blob.BlobProperties.RehydrationStatus" /> representing the rehydration status of the blob.</span></span></value>
        <remarks><span data-ttu-id="169ee-152">Gilt nur für Block-Blobs in dieser Version der Bibliothek.</span><span class="sxs-lookup"><span data-stu-id="169ee-152">Only applicable for block blobs in this version of the library.</span></span></remarks>
      </Docs>
    </Member>
    <Member MemberName="StandardBlobTier">
      <MemberSignature Language="C#" Value="public Nullable&lt;Microsoft.WindowsAzure.Storage.Blob.StandardBlobTier&gt; StandardBlobTier { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype Microsoft.WindowsAzure.Storage.Blob.StandardBlobTier&gt; StandardBlobTier" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.Blob.BlobProperties.StandardBlobTier" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property StandardBlobTier As Nullable(Of StandardBlobTier)" />
      <MemberSignature Language="F#" Value="member this.StandardBlobTier : Nullable&lt;Microsoft.WindowsAzure.Storage.Blob.StandardBlobTier&gt;" Usage="Microsoft.WindowsAzure.Storage.Blob.BlobProperties.StandardBlobTier" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;Microsoft.WindowsAzure.Storage.Blob.StandardBlobTier&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="169ee-153">Ruft einen Wert, der angibt, der die Block-Blob-Ebene.</span><span class="sxs-lookup"><span data-stu-id="169ee-153">Gets a value indicating the tier of the block blob.</span></span>
            </summary>
        <value><span data-ttu-id="169ee-154">Ein <see cref="P:Microsoft.WindowsAzure.Storage.Blob.BlobProperties.StandardBlobTier" /> Objekt, das die Block-Blob-Ebene angibt.</span><span class="sxs-lookup"><span data-stu-id="169ee-154">A <see cref="P:Microsoft.WindowsAzure.Storage.Blob.BlobProperties.StandardBlobTier" /> object that indicates the block blob tier.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>