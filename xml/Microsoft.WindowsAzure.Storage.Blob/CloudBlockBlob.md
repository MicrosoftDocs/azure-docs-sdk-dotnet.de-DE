<Type Name="CloudBlockBlob" FullName="Microsoft.WindowsAzure.Storage.Blob.CloudBlockBlob">
  <TypeSignature Language="C#" Value="public class CloudBlockBlob : Microsoft.WindowsAzure.Storage.Blob.CloudBlob, Microsoft.WindowsAzure.Storage.Blob.ICloudBlob" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit CloudBlockBlob extends Microsoft.WindowsAzure.Storage.Blob.CloudBlob implements class Microsoft.WindowsAzure.Storage.Blob.ICloudBlob, class Microsoft.WindowsAzure.Storage.Blob.IListBlobItem" />
  <TypeSignature Language="DocId" Value="T:Microsoft.WindowsAzure.Storage.Blob.CloudBlockBlob" />
  <TypeSignature Language="VB.NET" Value="Public Class CloudBlockBlob&#xA;Inherits CloudBlob&#xA;Implements ICloudBlob" />
  <TypeSignature Language="F#" Value="type CloudBlockBlob = class&#xA;    inherit CloudBlob&#xA;    interface ICloudBlob&#xA;    interface IListBlobItem" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
    <AssemblyVersion>8.4.0.0</AssemblyVersion>
    <AssemblyVersion>8.7.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.WindowsAzure.Storage.Blob.CloudBlob</BaseTypeName>
  </Base>
  <Interfaces>
    <Interface>
      <InterfaceName>Microsoft.WindowsAzure.Storage.Blob.ICloudBlob</InterfaceName>
    </Interface>
  </Interfaces>
  <Docs>
    <summary>
            <span data-ttu-id="f3327-101">Stellt ein Blob, das als eine Reihe von Blöcken hochgeladen wird.</span><span class="sxs-lookup"><span data-stu-id="f3327-101">Represents a blob that is uploaded as a set of blocks.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public CloudBlockBlob (Uri blobAbsoluteUri);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.Uri blobAbsoluteUri) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlockBlob.#ctor(System.Uri)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (blobAbsoluteUri As Uri)" />
      <MemberSignature Language="F#" Value="new Microsoft.WindowsAzure.Storage.Blob.CloudBlockBlob : Uri -&gt; Microsoft.WindowsAzure.Storage.Blob.CloudBlockBlob" Usage="new Microsoft.WindowsAzure.Storage.Blob.CloudBlockBlob blobAbsoluteUri" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="blobAbsoluteUri" Type="System.Uri" />
      </Parameters>
      <Docs>
        <param name="blobAbsoluteUri"><span data-ttu-id="f3327-102">Ein <see cref="T:System.Uri" /> , der den absoluten URI zum Blob angibt.</span><span class="sxs-lookup"><span data-stu-id="f3327-102">A <see cref="T:System.Uri" /> specifying the absolute URI to the blob.</span></span></param>
        <summary>
            <span data-ttu-id="f3327-103">Initialisiert eine neue Instanz der dem <see cref="T:Microsoft.WindowsAzure.Storage.Blob.CloudBlockBlob" /> -Klasse unter Verwendung eines absoluten URIS zum Blob.</span><span class="sxs-lookup"><span data-stu-id="f3327-103">Initializes a new instance of the <see cref="T:Microsoft.WindowsAzure.Storage.Blob.CloudBlockBlob" /> class using an absolute URI to the blob.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public CloudBlockBlob (Uri blobAbsoluteUri, Microsoft.WindowsAzure.Storage.Auth.StorageCredentials credentials);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.Uri blobAbsoluteUri, class Microsoft.WindowsAzure.Storage.Auth.StorageCredentials credentials) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlockBlob.#ctor(System.Uri,Microsoft.WindowsAzure.Storage.Auth.StorageCredentials)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (blobAbsoluteUri As Uri, credentials As StorageCredentials)" />
      <MemberSignature Language="F#" Value="new Microsoft.WindowsAzure.Storage.Blob.CloudBlockBlob : Uri * Microsoft.WindowsAzure.Storage.Auth.StorageCredentials -&gt; Microsoft.WindowsAzure.Storage.Blob.CloudBlockBlob" Usage="new Microsoft.WindowsAzure.Storage.Blob.CloudBlockBlob (blobAbsoluteUri, credentials)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="blobAbsoluteUri" Type="System.Uri" />
        <Parameter Name="credentials" Type="Microsoft.WindowsAzure.Storage.Auth.StorageCredentials" />
      </Parameters>
      <Docs>
        <param name="blobAbsoluteUri"><span data-ttu-id="f3327-104">Ein <see cref="T:System.Uri" /> , der den absoluten URI zum Blob angibt.</span><span class="sxs-lookup"><span data-stu-id="f3327-104">A <see cref="T:System.Uri" /> specifying the absolute URI to the blob.</span></span></param>
        <param name="credentials"><span data-ttu-id="f3327-105">Ein <see cref="T:Microsoft.WindowsAzure.Storage.Auth.StorageCredentials" />-Objekt.</span><span class="sxs-lookup"><span data-stu-id="f3327-105">A <see cref="T:Microsoft.WindowsAzure.Storage.Auth.StorageCredentials" /> object.</span></span></param>
        <summary>
            <span data-ttu-id="f3327-106">Initialisiert eine neue Instanz der dem <see cref="T:Microsoft.WindowsAzure.Storage.Blob.CloudBlockBlob" /> -Klasse unter Verwendung eines absoluten URIS zum Blob.</span><span class="sxs-lookup"><span data-stu-id="f3327-106">Initializes a new instance of the <see cref="T:Microsoft.WindowsAzure.Storage.Blob.CloudBlockBlob" /> class using an absolute URI to the blob.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public CloudBlockBlob (Microsoft.WindowsAzure.Storage.StorageUri blobAbsoluteUri, Nullable&lt;DateTimeOffset&gt; snapshotTime, Microsoft.WindowsAzure.Storage.Auth.StorageCredentials credentials);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class Microsoft.WindowsAzure.Storage.StorageUri blobAbsoluteUri, valuetype System.Nullable`1&lt;valuetype System.DateTimeOffset&gt; snapshotTime, class Microsoft.WindowsAzure.Storage.Auth.StorageCredentials credentials) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlockBlob.#ctor(Microsoft.WindowsAzure.Storage.StorageUri,System.Nullable{System.DateTimeOffset},Microsoft.WindowsAzure.Storage.Auth.StorageCredentials)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (blobAbsoluteUri As StorageUri, snapshotTime As Nullable(Of DateTimeOffset), credentials As StorageCredentials)" />
      <MemberSignature Language="F#" Value="new Microsoft.WindowsAzure.Storage.Blob.CloudBlockBlob : Microsoft.WindowsAzure.Storage.StorageUri * Nullable&lt;DateTimeOffset&gt; * Microsoft.WindowsAzure.Storage.Auth.StorageCredentials -&gt; Microsoft.WindowsAzure.Storage.Blob.CloudBlockBlob" Usage="new Microsoft.WindowsAzure.Storage.Blob.CloudBlockBlob (blobAbsoluteUri, snapshotTime, credentials)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="blobAbsoluteUri" Type="Microsoft.WindowsAzure.Storage.StorageUri" />
        <Parameter Name="snapshotTime" Type="System.Nullable&lt;System.DateTimeOffset&gt;" />
        <Parameter Name="credentials" Type="Microsoft.WindowsAzure.Storage.Auth.StorageCredentials" />
      </Parameters>
      <Docs>
        <param name="blobAbsoluteUri"><span data-ttu-id="f3327-107">Ein <see cref="T:Microsoft.WindowsAzure.Storage.StorageUri" /> , das den absoluten URI zum Blob am primären und sekundären Speicherorte enthält.</span><span class="sxs-lookup"><span data-stu-id="f3327-107">A <see cref="T:Microsoft.WindowsAzure.Storage.StorageUri" /> containing the absolute URI to the blob at both the primary and secondary locations.</span></span></param>
        <param name="snapshotTime"><span data-ttu-id="f3327-108">Ein <see cref="T:System.DateTimeOffset" /> den Momentaufnahme-Zeitstempel angeben, wenn das Blob eine Momentaufnahme ist.</span><span class="sxs-lookup"><span data-stu-id="f3327-108">A <see cref="T:System.DateTimeOffset" /> specifying the snapshot timestamp, if the blob is a snapshot.</span></span></param>
        <param name="credentials"><span data-ttu-id="f3327-109">Ein <see cref="T:Microsoft.WindowsAzure.Storage.Auth.StorageCredentials" />-Objekt.</span><span class="sxs-lookup"><span data-stu-id="f3327-109">A <see cref="T:Microsoft.WindowsAzure.Storage.Auth.StorageCredentials" /> object.</span></span></param>
        <summary>
            <span data-ttu-id="f3327-110">Initialisiert eine neue Instanz der dem <see cref="T:Microsoft.WindowsAzure.Storage.Blob.CloudBlockBlob" /> -Klasse unter Verwendung eines absoluten URIS zum Blob.</span><span class="sxs-lookup"><span data-stu-id="f3327-110">Initializes a new instance of the <see cref="T:Microsoft.WindowsAzure.Storage.Blob.CloudBlockBlob" /> class using an absolute URI to the blob.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public CloudBlockBlob (Uri blobAbsoluteUri, Nullable&lt;DateTimeOffset&gt; snapshotTime, Microsoft.WindowsAzure.Storage.Auth.StorageCredentials credentials);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.Uri blobAbsoluteUri, valuetype System.Nullable`1&lt;valuetype System.DateTimeOffset&gt; snapshotTime, class Microsoft.WindowsAzure.Storage.Auth.StorageCredentials credentials) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlockBlob.#ctor(System.Uri,System.Nullable{System.DateTimeOffset},Microsoft.WindowsAzure.Storage.Auth.StorageCredentials)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (blobAbsoluteUri As Uri, snapshotTime As Nullable(Of DateTimeOffset), credentials As StorageCredentials)" />
      <MemberSignature Language="F#" Value="new Microsoft.WindowsAzure.Storage.Blob.CloudBlockBlob : Uri * Nullable&lt;DateTimeOffset&gt; * Microsoft.WindowsAzure.Storage.Auth.StorageCredentials -&gt; Microsoft.WindowsAzure.Storage.Blob.CloudBlockBlob" Usage="new Microsoft.WindowsAzure.Storage.Blob.CloudBlockBlob (blobAbsoluteUri, snapshotTime, credentials)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="blobAbsoluteUri" Type="System.Uri" />
        <Parameter Name="snapshotTime" Type="System.Nullable&lt;System.DateTimeOffset&gt;" />
        <Parameter Name="credentials" Type="Microsoft.WindowsAzure.Storage.Auth.StorageCredentials" />
      </Parameters>
      <Docs>
        <param name="blobAbsoluteUri"><span data-ttu-id="f3327-111">Ein <see cref="T:System.Uri" /> , der den absoluten URI zum Blob angibt.</span><span class="sxs-lookup"><span data-stu-id="f3327-111">A <see cref="T:System.Uri" /> specifying the absolute URI to the blob.</span></span></param>
        <param name="snapshotTime"><span data-ttu-id="f3327-112">Ein <see cref="T:System.DateTimeOffset" /> den Momentaufnahme-Zeitstempel angeben, wenn das Blob eine Momentaufnahme ist.</span><span class="sxs-lookup"><span data-stu-id="f3327-112">A <see cref="T:System.DateTimeOffset" /> specifying the snapshot timestamp, if the blob is a snapshot.</span></span></param>
        <param name="credentials"><span data-ttu-id="f3327-113">Ein <see cref="T:Microsoft.WindowsAzure.Storage.Auth.StorageCredentials" />-Objekt.</span><span class="sxs-lookup"><span data-stu-id="f3327-113">A <see cref="T:Microsoft.WindowsAzure.Storage.Auth.StorageCredentials" /> object.</span></span></param>
        <summary>
            <span data-ttu-id="f3327-114">Initialisiert eine neue Instanz der dem <see cref="T:Microsoft.WindowsAzure.Storage.Blob.CloudBlockBlob" /> -Klasse unter Verwendung eines absoluten URIS zum Blob.</span><span class="sxs-lookup"><span data-stu-id="f3327-114">Initializes a new instance of the <see cref="T:Microsoft.WindowsAzure.Storage.Blob.CloudBlockBlob" /> class using an absolute URI to the blob.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginCreateSnapshot">
      <MemberSignature Language="C#" Value="public virtual Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginCreateSnapshot (AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginCreateSnapshot(class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlockBlob.BeginCreateSnapshot(System.AsyncCallback,System.Object)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function BeginCreateSnapshot (callback As AsyncCallback, state As Object) As ICancellableAsyncResult" />
      <MemberSignature Language="F#" Value="abstract member BeginCreateSnapshot : AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult&#xA;override this.BeginCreateSnapshot : AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" Usage="cloudBlockBlob.BeginCreateSnapshot (callback, state)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.WindowsAzure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Storage.ICancellableAsyncResult</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="callback" Type="System.AsyncCallback" />
        <Parameter Name="state" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="callback"><span data-ttu-id="f3327-115">Ein <see cref="T:System.AsyncCallback" /> Delegat, der Benachrichtigung erhalten sollen, wenn der asynchrone Vorgang abgeschlossen ist.</span><span class="sxs-lookup"><span data-stu-id="f3327-115">An <see cref="T:System.AsyncCallback" /> delegate that will receive notification when the asynchronous operation completes.</span></span></param>
        <param name="state"><span data-ttu-id="f3327-116">Ein benutzerdefiniertes Objekt, die an dem Rückrufdelegaten übergeben werden.</span><span class="sxs-lookup"><span data-stu-id="f3327-116">A user-defined object that will be passed to the callback delegate.</span></span></param>
        <summary>
            <span data-ttu-id="f3327-117">Startet einen asynchronen Vorgang zum Erstellen einer Momentaufnahme des BLOBs.</span><span class="sxs-lookup"><span data-stu-id="f3327-117">Begins an asynchronous operation to create a snapshot of the blob.</span></span>
            </summary>
        <returns><span data-ttu-id="f3327-118">Ein <see cref="T:Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" /> , das auf den asynchronen Vorgang verweist.</span><span class="sxs-lookup"><span data-stu-id="f3327-118">An <see cref="T:Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" /> that references the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginCreateSnapshot">
      <MemberSignature Language="C#" Value="public virtual Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginCreateSnapshot (System.Collections.Generic.IDictionary&lt;string,string&gt; metadata, Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, Microsoft.WindowsAzure.Storage.OperationContext operationContext, AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginCreateSnapshot(class System.Collections.Generic.IDictionary`2&lt;string, string&gt; metadata, class Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, class Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, class Microsoft.WindowsAzure.Storage.OperationContext operationContext, class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlockBlob.BeginCreateSnapshot(System.Collections.Generic.IDictionary{System.String,System.String},Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext,System.AsyncCallback,System.Object)" />
      <MemberSignature Language="F#" Value="abstract member BeginCreateSnapshot : System.Collections.Generic.IDictionary&lt;string, string&gt; * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult&#xA;override this.BeginCreateSnapshot : System.Collections.Generic.IDictionary&lt;string, string&gt; * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" Usage="cloudBlockBlob.BeginCreateSnapshot (metadata, accessCondition, options, operationContext, callback, state)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.WindowsAzure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Storage.ICancellableAsyncResult</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="metadata" Type="System.Collections.Generic.IDictionary&lt;System.String,System.String&gt;" />
        <Parameter Name="accessCondition" Type="Microsoft.WindowsAzure.Storage.AccessCondition" />
        <Parameter Name="options" Type="Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
        <Parameter Name="callback" Type="System.AsyncCallback" />
        <Parameter Name="state" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="metadata"><span data-ttu-id="f3327-119">Eine Auflistung von Name-Wert-Paare definieren die Metadaten der Momentaufnahme.</span><span class="sxs-lookup"><span data-stu-id="f3327-119">A collection of name-value pairs defining the metadata of the snapshot.</span></span></param>
        <param name="accessCondition"><span data-ttu-id="f3327-120">Ein <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> -Objekt, das die Bedingung, die erfüllt sein müssen, damit die Anforderung darstellt, um den Vorgang fortzusetzen.</span><span class="sxs-lookup"><span data-stu-id="f3327-120">An <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> object that represents the condition that must be met in order for the request to proceed.</span></span> <span data-ttu-id="f3327-121">Wenn <c>null</c>, keine Bedingung verwendet.</span><span class="sxs-lookup"><span data-stu-id="f3327-121">If <c>null</c>, no condition is used.</span></span></param>
        <param name="options"><span data-ttu-id="f3327-122">Ein <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" /> -Objekt, das zusätzliche Optionen für die Anforderung angibt oder <c>null</c>.</span><span class="sxs-lookup"><span data-stu-id="f3327-122">A <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" /> object that specifies additional options for the request, or <c>null</c>.</span></span></param>
        <param name="operationContext"><span data-ttu-id="f3327-123">Ein <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> -Objekt, das den Kontext für den aktuellen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="f3327-123">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <param name="callback"><span data-ttu-id="f3327-124">Ein <see cref="T:System.AsyncCallback" /> Delegat, der Benachrichtigung erhalten sollen, wenn der asynchrone Vorgang abgeschlossen ist.</span><span class="sxs-lookup"><span data-stu-id="f3327-124">An <see cref="T:System.AsyncCallback" /> delegate that will receive notification when the asynchronous operation completes.</span></span></param>
        <param name="state"><span data-ttu-id="f3327-125">Ein benutzerdefiniertes Objekt, die an dem Rückrufdelegaten übergeben werden.</span><span class="sxs-lookup"><span data-stu-id="f3327-125">A user-defined object that will be passed to the callback delegate.</span></span></param>
        <summary>
            <span data-ttu-id="f3327-126">Startet einen asynchronen Vorgang zum Erstellen einer Momentaufnahme des BLOBs.</span><span class="sxs-lookup"><span data-stu-id="f3327-126">Begins an asynchronous operation to create a snapshot of the blob.</span></span>
            </summary>
        <returns><span data-ttu-id="f3327-127">Ein <see cref="T:Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" /> , das auf den asynchronen Vorgang verweist.</span><span class="sxs-lookup"><span data-stu-id="f3327-127">An <see cref="T:Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" /> that references the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginDownloadBlockList">
      <MemberSignature Language="C#" Value="public virtual Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginDownloadBlockList (AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginDownloadBlockList(class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlockBlob.BeginDownloadBlockList(System.AsyncCallback,System.Object)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function BeginDownloadBlockList (callback As AsyncCallback, state As Object) As ICancellableAsyncResult" />
      <MemberSignature Language="F#" Value="abstract member BeginDownloadBlockList : AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult&#xA;override this.BeginDownloadBlockList : AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" Usage="cloudBlockBlob.BeginDownloadBlockList (callback, state)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.WindowsAzure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Storage.ICancellableAsyncResult</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="callback" Type="System.AsyncCallback" />
        <Parameter Name="state" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="callback"><span data-ttu-id="f3327-128">Ein <see cref="T:System.AsyncCallback" /> Delegat, der Benachrichtigung erhalten sollen, wenn der asynchrone Vorgang abgeschlossen ist.</span><span class="sxs-lookup"><span data-stu-id="f3327-128">An <see cref="T:System.AsyncCallback" /> delegate that will receive notification when the asynchronous operation completes.</span></span></param>
        <param name="state"><span data-ttu-id="f3327-129">Ein benutzerdefiniertes Objekt, die an dem Rückrufdelegaten übergeben werden.</span><span class="sxs-lookup"><span data-stu-id="f3327-129">A user-defined object that will be passed to the callback delegate.</span></span></param>
        <summary>
            <span data-ttu-id="f3327-130">Startet einen asynchronen Vorgang, um eine aufzählbare Auflistung der Blöcke des BLOBs, mithilfe des angegebenen blocklistenfilters zurückzugeben.</span><span class="sxs-lookup"><span data-stu-id="f3327-130">Begins an asynchronous operation to return an enumerable collection of the blob's blocks, using the specified block list filter.</span></span>
            </summary>
        <returns><span data-ttu-id="f3327-131">Ein <see cref="T:Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" /> , das auf den asynchronen Vorgang verweist.</span><span class="sxs-lookup"><span data-stu-id="f3327-131">An <see cref="T:Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" /> that references the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginDownloadBlockList">
      <MemberSignature Language="C#" Value="public virtual Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginDownloadBlockList (Microsoft.WindowsAzure.Storage.Blob.BlockListingFilter blockListingFilter, Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, Microsoft.WindowsAzure.Storage.OperationContext operationContext, AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginDownloadBlockList(valuetype Microsoft.WindowsAzure.Storage.Blob.BlockListingFilter blockListingFilter, class Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, class Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, class Microsoft.WindowsAzure.Storage.OperationContext operationContext, class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlockBlob.BeginDownloadBlockList(Microsoft.WindowsAzure.Storage.Blob.BlockListingFilter,Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext,System.AsyncCallback,System.Object)" />
      <MemberSignature Language="F#" Value="abstract member BeginDownloadBlockList : Microsoft.WindowsAzure.Storage.Blob.BlockListingFilter * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult&#xA;override this.BeginDownloadBlockList : Microsoft.WindowsAzure.Storage.Blob.BlockListingFilter * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" Usage="cloudBlockBlob.BeginDownloadBlockList (blockListingFilter, accessCondition, options, operationContext, callback, state)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.WindowsAzure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Storage.ICancellableAsyncResult</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="blockListingFilter" Type="Microsoft.WindowsAzure.Storage.Blob.BlockListingFilter" />
        <Parameter Name="accessCondition" Type="Microsoft.WindowsAzure.Storage.AccessCondition" />
        <Parameter Name="options" Type="Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
        <Parameter Name="callback" Type="System.AsyncCallback" />
        <Parameter Name="state" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="blockListingFilter"><span data-ttu-id="f3327-132">Ein <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlockListingFilter" /> -Enumerationswert ab, der angibt, ob Blöcke mit ausgeführtem Commit, Blöcke oder beides zurück.</span><span class="sxs-lookup"><span data-stu-id="f3327-132">A <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlockListingFilter" /> enumeration value that indicates whether to return committed blocks, uncommitted blocks, or both.</span></span></param>
        <param name="accessCondition"><span data-ttu-id="f3327-133">Ein <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> -Objekt, das die Bedingung, die erfüllt sein müssen, damit die Anforderung darstellt, um den Vorgang fortzusetzen.</span><span class="sxs-lookup"><span data-stu-id="f3327-133">An <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> object that represents the condition that must be met in order for the request to proceed.</span></span> <span data-ttu-id="f3327-134">Wenn <c>null</c>, keine Bedingung verwendet.</span><span class="sxs-lookup"><span data-stu-id="f3327-134">If <c>null</c>, no condition is used.</span></span></param>
        <param name="options"><span data-ttu-id="f3327-135">Ein <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" /> -Objekt, das zusätzliche Optionen für die Anforderung angibt.</span><span class="sxs-lookup"><span data-stu-id="f3327-135">A <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" /> object that specifies additional options for the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="f3327-136">Ein <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> -Objekt, das den Kontext für den aktuellen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="f3327-136">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <param name="callback"><span data-ttu-id="f3327-137">Ein <see cref="T:System.AsyncCallback" /> Delegat, der Benachrichtigung erhalten sollen, wenn der asynchrone Vorgang abgeschlossen ist.</span><span class="sxs-lookup"><span data-stu-id="f3327-137">An <see cref="T:System.AsyncCallback" /> delegate that will receive notification when the asynchronous operation completes.</span></span></param>
        <param name="state"><span data-ttu-id="f3327-138">Ein benutzerdefiniertes Objekt, die an dem Rückrufdelegaten übergeben werden.</span><span class="sxs-lookup"><span data-stu-id="f3327-138">A user-defined object that will be passed to the callback delegate.</span></span></param>
        <summary>
            <span data-ttu-id="f3327-139">Startet einen asynchronen Vorgang, um eine aufzählbare Auflistung der Blöcke des BLOBs, mithilfe des angegebenen blocklistenfilters zurückzugeben.</span><span class="sxs-lookup"><span data-stu-id="f3327-139">Begins an asynchronous operation to return an enumerable collection of the blob's blocks, using the specified block list filter.</span></span>
            </summary>
        <returns><span data-ttu-id="f3327-140">Ein <see cref="T:Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" /> , das auf den asynchronen Vorgang verweist.</span><span class="sxs-lookup"><span data-stu-id="f3327-140">An <see cref="T:Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" /> that references the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginDownloadText">
      <MemberSignature Language="C#" Value="public virtual Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginDownloadText (AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginDownloadText(class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlockBlob.BeginDownloadText(System.AsyncCallback,System.Object)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function BeginDownloadText (callback As AsyncCallback, state As Object) As ICancellableAsyncResult" />
      <MemberSignature Language="F#" Value="abstract member BeginDownloadText : AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult&#xA;override this.BeginDownloadText : AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" Usage="cloudBlockBlob.BeginDownloadText (callback, state)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.WindowsAzure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Storage.ICancellableAsyncResult</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="callback" Type="System.AsyncCallback" />
        <Parameter Name="state" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="callback"><span data-ttu-id="f3327-141">Ein <see cref="T:System.AsyncCallback" /> Delegat, der Benachrichtigung erhalten sollen, wenn der asynchrone Vorgang abgeschlossen ist.</span><span class="sxs-lookup"><span data-stu-id="f3327-141">An <see cref="T:System.AsyncCallback" /> delegate that will receive notification when the asynchronous operation completes.</span></span></param>
        <param name="state"><span data-ttu-id="f3327-142">Ein benutzerdefiniertes Objekt, die an dem Rückrufdelegaten übergeben werden.</span><span class="sxs-lookup"><span data-stu-id="f3327-142">A user-defined object that will be passed to the callback delegate.</span></span></param>
        <summary>
            <span data-ttu-id="f3327-143">Startet einen asynchronen Vorgang, um den Inhalt des BLOBs als Zeichenfolge herunterzuladen.</span><span class="sxs-lookup"><span data-stu-id="f3327-143">Begins an asynchronous operation to download the blob's contents as a string.</span></span>
            </summary>
        <returns><span data-ttu-id="f3327-144">Ein <see cref="T:Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" /> , das auf den asynchronen Vorgang verweist.</span><span class="sxs-lookup"><span data-stu-id="f3327-144">An <see cref="T:Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" /> that references the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginDownloadText">
      <MemberSignature Language="C#" Value="public virtual Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginDownloadText (System.Text.Encoding encoding, Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, Microsoft.WindowsAzure.Storage.OperationContext operationContext, AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginDownloadText(class System.Text.Encoding encoding, class Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, class Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, class Microsoft.WindowsAzure.Storage.OperationContext operationContext, class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlockBlob.BeginDownloadText(System.Text.Encoding,Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext,System.AsyncCallback,System.Object)" />
      <MemberSignature Language="F#" Value="abstract member BeginDownloadText : System.Text.Encoding * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult&#xA;override this.BeginDownloadText : System.Text.Encoding * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" Usage="cloudBlockBlob.BeginDownloadText (encoding, accessCondition, options, operationContext, callback, state)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.WindowsAzure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Storage.ICancellableAsyncResult</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="encoding" Type="System.Text.Encoding" />
        <Parameter Name="accessCondition" Type="Microsoft.WindowsAzure.Storage.AccessCondition" />
        <Parameter Name="options" Type="Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
        <Parameter Name="callback" Type="System.AsyncCallback" />
        <Parameter Name="state" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="encoding"><span data-ttu-id="f3327-145">Ein Objekt, das um zu verwendende textcodierung angibt.</span><span class="sxs-lookup"><span data-stu-id="f3327-145">An object that indicates the text encoding to use.</span></span></param>
        <param name="accessCondition"><span data-ttu-id="f3327-146">Ein <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> -Objekt, das die Bedingung, die erfüllt sein müssen, damit die Anforderung darstellt, um den Vorgang fortzusetzen.</span><span class="sxs-lookup"><span data-stu-id="f3327-146">An <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> object that represents the condition that must be met in order for the request to proceed.</span></span></param>
        <param name="options"><span data-ttu-id="f3327-147">Ein <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" /> -Objekt, das zusätzliche Optionen für die Anforderung angibt.</span><span class="sxs-lookup"><span data-stu-id="f3327-147">A <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" /> object that specifies additional options for the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="f3327-148">Ein <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> -Objekt, das den Kontext für den aktuellen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="f3327-148">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <param name="callback"><span data-ttu-id="f3327-149">Ein <see cref="T:System.AsyncCallback" /> Delegat, der Benachrichtigung erhalten sollen, wenn der asynchrone Vorgang abgeschlossen ist.</span><span class="sxs-lookup"><span data-stu-id="f3327-149">An <see cref="T:System.AsyncCallback" /> delegate that will receive notification when the asynchronous operation completes.</span></span></param>
        <param name="state"><span data-ttu-id="f3327-150">Ein benutzerdefiniertes Objekt, die an dem Rückrufdelegaten übergeben werden.</span><span class="sxs-lookup"><span data-stu-id="f3327-150">A user-defined object that will be passed to the callback delegate.</span></span></param>
        <summary>
            <span data-ttu-id="f3327-151">Startet einen asynchronen Vorgang, um den Inhalt des BLOBs als Zeichenfolge herunterzuladen.</span><span class="sxs-lookup"><span data-stu-id="f3327-151">Begins an asynchronous operation to download the blob's contents as a string.</span></span>
            </summary>
        <returns><span data-ttu-id="f3327-152">Ein <see cref="T:Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" /> , das auf den asynchronen Vorgang verweist.</span><span class="sxs-lookup"><span data-stu-id="f3327-152">An <see cref="T:Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" /> that references the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginOpenWrite">
      <MemberSignature Language="C#" Value="public virtual Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginOpenWrite (AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginOpenWrite(class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlockBlob.BeginOpenWrite(System.AsyncCallback,System.Object)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function BeginOpenWrite (callback As AsyncCallback, state As Object) As ICancellableAsyncResult" />
      <MemberSignature Language="F#" Value="abstract member BeginOpenWrite : AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult&#xA;override this.BeginOpenWrite : AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" Usage="cloudBlockBlob.BeginOpenWrite (callback, state)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.WindowsAzure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Storage.ICancellableAsyncResult</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="callback" Type="System.AsyncCallback" />
        <Parameter Name="state" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="callback"><span data-ttu-id="f3327-153">Ein <see cref="T:System.AsyncCallback" /> Delegat, der Benachrichtigung erhalten sollen, wenn der asynchrone Vorgang abgeschlossen ist.</span><span class="sxs-lookup"><span data-stu-id="f3327-153">An <see cref="T:System.AsyncCallback" /> delegate that will receive notification when the asynchronous operation completes.</span></span></param>
        <param name="state"><span data-ttu-id="f3327-154">Ein benutzerdefiniertes Objekt, die an dem Rückrufdelegaten übergeben werden.</span><span class="sxs-lookup"><span data-stu-id="f3327-154">A user-defined object that will be passed to the callback delegate.</span></span></param>
        <summary>
            <span data-ttu-id="f3327-155">Startet einen asynchronen Vorgang zum Öffnen eines Datenstroms zum Schreiben in das Blob.</span><span class="sxs-lookup"><span data-stu-id="f3327-155">Begins an asynchronous operation to open a stream for writing to the blob.</span></span> <span data-ttu-id="f3327-156">Wenn das Blob bereits vorhanden ist, wird sie überschrieben.</span><span class="sxs-lookup"><span data-stu-id="f3327-156">If the blob already exists, it will be overwritten.</span></span>
            </summary>
        <returns><span data-ttu-id="f3327-157">Ein <see cref="T:Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" /> , das auf den asynchronen Vorgang verweist.</span><span class="sxs-lookup"><span data-stu-id="f3327-157">An <see cref="T:Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" /> that references the asynchronous operation.</span></span></returns>
        <remarks>
          <para><span data-ttu-id="f3327-158">Beachten Sie, dass diese Methode immer einen Aufruf an sendet die <see cref="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlob.BeginFetchAttributes(Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext,System.AsyncCallback,System.Object)" /> Methode im Hintergrund.</span><span class="sxs-lookup"><span data-stu-id="f3327-158">Note that this method always makes a call to the <see cref="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlob.BeginFetchAttributes(Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext,System.AsyncCallback,System.Object)" /> method under the covers.</span></span></para>
          <para><span data-ttu-id="f3327-159">Legen Sie die <see cref="P:Microsoft.WindowsAzure.Storage.Blob.CloudBlockBlob.StreamWriteSizeInBytes" /> Eigenschaft vor dem Aufrufen dieser Methode, um anzugeben, die Blockgröße in Bytes von 16 KB bis 100 MB inklusive zu schreiben.</span><span class="sxs-lookup"><span data-stu-id="f3327-159">Set the <see cref="P:Microsoft.WindowsAzure.Storage.Blob.CloudBlockBlob.StreamWriteSizeInBytes" /> property before calling this method to specify the block size to write, in bytes, ranging from between 16 KB and 100 MB inclusive.</span></span></para>
          <para><span data-ttu-id="f3327-160">Um eine Ausnahme auslösen, wenn das Blob vorhanden ist, anstatt ihn zu überschreiben, finden Sie unter <see cref="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlockBlob.BeginOpenWrite(Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext,System.AsyncCallback,System.Object)" />.</span><span class="sxs-lookup"><span data-stu-id="f3327-160">To throw an exception if the blob exists instead of overwriting it, see <see cref="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlockBlob.BeginOpenWrite(Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext,System.AsyncCallback,System.Object)" />.</span></span></para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginOpenWrite">
      <MemberSignature Language="C#" Value="public virtual Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginOpenWrite (Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, Microsoft.WindowsAzure.Storage.OperationContext operationContext, AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginOpenWrite(class Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, class Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, class Microsoft.WindowsAzure.Storage.OperationContext operationContext, class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlockBlob.BeginOpenWrite(Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext,System.AsyncCallback,System.Object)" />
      <MemberSignature Language="F#" Value="abstract member BeginOpenWrite : Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult&#xA;override this.BeginOpenWrite : Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" Usage="cloudBlockBlob.BeginOpenWrite (accessCondition, options, operationContext, callback, state)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.WindowsAzure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Storage.ICancellableAsyncResult</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="accessCondition" Type="Microsoft.WindowsAzure.Storage.AccessCondition" />
        <Parameter Name="options" Type="Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
        <Parameter Name="callback" Type="System.AsyncCallback" />
        <Parameter Name="state" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="accessCondition"><span data-ttu-id="f3327-161">Ein <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> -Objekt, das die Bedingung, die erfüllt sein müssen, damit die Anforderung darstellt, um den Vorgang fortzusetzen.</span><span class="sxs-lookup"><span data-stu-id="f3327-161">An <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> object that represents the condition that must be met in order for the request to proceed.</span></span> <span data-ttu-id="f3327-162">Wenn <c>null</c>, keine Bedingung verwendet.</span><span class="sxs-lookup"><span data-stu-id="f3327-162">If <c>null</c>, no condition is used.</span></span></param>
        <param name="options"><span data-ttu-id="f3327-163">Ein <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" /> -Objekt, das zusätzliche Optionen für die Anforderung angibt.</span><span class="sxs-lookup"><span data-stu-id="f3327-163">A <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" /> object that specifies additional options for the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="f3327-164">Ein <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> -Objekt, das den Kontext für den aktuellen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="f3327-164">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <param name="callback"><span data-ttu-id="f3327-165">Ein <see cref="T:System.AsyncCallback" /> Delegat, der Benachrichtigung erhalten sollen, wenn der asynchrone Vorgang abgeschlossen ist.</span><span class="sxs-lookup"><span data-stu-id="f3327-165">An <see cref="T:System.AsyncCallback" /> delegate that will receive notification when the asynchronous operation completes.</span></span></param>
        <param name="state"><span data-ttu-id="f3327-166">Ein benutzerdefiniertes Objekt, die an dem Rückrufdelegaten übergeben werden.</span><span class="sxs-lookup"><span data-stu-id="f3327-166">A user-defined object that will be passed to the callback delegate.</span></span></param>
        <summary>
            <span data-ttu-id="f3327-167">Startet einen asynchronen Vorgang zum Öffnen eines Datenstroms zum Schreiben in das Blob.</span><span class="sxs-lookup"><span data-stu-id="f3327-167">Begins an asynchronous operation to open a stream for writing to the blob.</span></span> <span data-ttu-id="f3327-168">Wenn das Blob bereits vorhanden ist, wird sie überschrieben.</span><span class="sxs-lookup"><span data-stu-id="f3327-168">If the blob already exists, it will be overwritten.</span></span>
            </summary>
        <returns><span data-ttu-id="f3327-169">Ein <see cref="T:Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" /> , das auf den asynchronen Vorgang verweist.</span><span class="sxs-lookup"><span data-stu-id="f3327-169">An <see cref="T:Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" /> that references the asynchronous operation.</span></span></returns>
        <remarks>
          <para><span data-ttu-id="f3327-170">Beachten Sie, dass diese Methode immer einen Aufruf an sendet die <see cref="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlob.BeginFetchAttributes(Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext,System.AsyncCallback,System.Object)" /> Methode im Hintergrund.</span><span class="sxs-lookup"><span data-stu-id="f3327-170">Note that this method always makes a call to the <see cref="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlob.BeginFetchAttributes(Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext,System.AsyncCallback,System.Object)" /> method under the covers.</span></span></para>
          <para><span data-ttu-id="f3327-171">Legen Sie die <see cref="P:Microsoft.WindowsAzure.Storage.Blob.CloudBlockBlob.StreamWriteSizeInBytes" /> Eigenschaft vor dem Aufrufen dieser Methode, um anzugeben, die Blockgröße in Bytes von 16 KB bis 100 MB inklusive zu schreiben.</span><span class="sxs-lookup"><span data-stu-id="f3327-171">Set the <see cref="P:Microsoft.WindowsAzure.Storage.Blob.CloudBlockBlob.StreamWriteSizeInBytes" /> property before calling this method to specify the block size to write, in bytes, ranging from between 16 KB and 100 MB inclusive.</span></span></para>
          <para><span data-ttu-id="f3327-172">Um eine Ausnahme auslösen, wenn das Blob vorhanden ist, anstatt ihn zu überschreiben, übergeben Sie ein <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> Objekt mit generiert <see cref="M:Microsoft.WindowsAzure.Storage.AccessCondition.GenerateIfNotExistsCondition" />.</span><span class="sxs-lookup"><span data-stu-id="f3327-172">To throw an exception if the blob exists instead of overwriting it, pass in an <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> object generated using <see cref="M:Microsoft.WindowsAzure.Storage.AccessCondition.GenerateIfNotExistsCondition" />.</span></span></para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginPutBlock">
      <MemberSignature Language="C#" Value="public virtual Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginPutBlock (string blockId, System.IO.Stream blockData, string contentMD5, AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginPutBlock(string blockId, class System.IO.Stream blockData, string contentMD5, class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlockBlob.BeginPutBlock(System.String,System.IO.Stream,System.String,System.AsyncCallback,System.Object)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function BeginPutBlock (blockId As String, blockData As Stream, contentMD5 As String, callback As AsyncCallback, state As Object) As ICancellableAsyncResult" />
      <MemberSignature Language="F#" Value="abstract member BeginPutBlock : string * System.IO.Stream * string * AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult&#xA;override this.BeginPutBlock : string * System.IO.Stream * string * AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" Usage="cloudBlockBlob.BeginPutBlock (blockId, blockData, contentMD5, callback, state)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.WindowsAzure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Storage.ICancellableAsyncResult</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="blockId" Type="System.String" />
        <Parameter Name="blockData" Type="System.IO.Stream" />
        <Parameter Name="contentMD5" Type="System.String" />
        <Parameter Name="callback" Type="System.AsyncCallback" />
        <Parameter Name="state" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="blockId"><span data-ttu-id="f3327-173">Eine Base64-codierte Zeichenfolge, die den Block identifiziert.</span><span class="sxs-lookup"><span data-stu-id="f3327-173">A Base64-encoded string that identifies the block.</span></span></param>
        <param name="blockData"><span data-ttu-id="f3327-174">Ein <see cref="T:System.IO.Stream" /> -Objekt, das die Daten für den Block bereitstellt.</span><span class="sxs-lookup"><span data-stu-id="f3327-174">A <see cref="T:System.IO.Stream" /> object that provides the data for the block.</span></span></param>
        <param name="contentMD5"><span data-ttu-id="f3327-175">Ein optionaler Hashwert verwendet, um Transaktionsintegrität für den Block sicherzustellen.</span><span class="sxs-lookup"><span data-stu-id="f3327-175">An optional hash value used to ensure transactional integrity for the block.</span></span> <span data-ttu-id="f3327-176">Möglicherweise <c>null</c> oder eine leere Zeichenfolge.</span><span class="sxs-lookup"><span data-stu-id="f3327-176">May be <c>null</c> or an empty string.</span></span></param>
        <param name="callback"><span data-ttu-id="f3327-177">Ein <see cref="T:System.AsyncCallback" /> Delegat, der Benachrichtigung erhalten sollen, wenn der asynchrone Vorgang abgeschlossen ist.</span><span class="sxs-lookup"><span data-stu-id="f3327-177">An <see cref="T:System.AsyncCallback" /> delegate that will receive notification when the asynchronous operation completes.</span></span></param>
        <param name="state"><span data-ttu-id="f3327-178">Ein benutzerdefiniertes Objekt, die an dem Rückrufdelegaten übergeben werden.</span><span class="sxs-lookup"><span data-stu-id="f3327-178">A user-defined object that will be passed to the callback delegate.</span></span></param>
        <summary>
            <span data-ttu-id="f3327-179">Startet einen asynchronen Vorgang zum Hochladen eines einzelnen Blocks.</span><span class="sxs-lookup"><span data-stu-id="f3327-179">Begins an asynchronous operation to upload a single block.</span></span>
            </summary>
        <returns><span data-ttu-id="f3327-180">Ein <see cref="T:Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" /> , das auf den asynchronen Vorgang verweist.</span><span class="sxs-lookup"><span data-stu-id="f3327-180">An <see cref="T:Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" /> that references the asynchronous operation.</span></span></returns>
        <remarks>
            <span data-ttu-id="f3327-181">Clients können den Content-MD5-Header für einen angegebenen Block Put-Vorgang als Mittel zum Sicherstellen der Transaktionsintegrität unverschlüsselt gesendet.</span><span class="sxs-lookup"><span data-stu-id="f3327-181">Clients may send the Content-MD5 header for a given Put Block operation as a means to ensure transactional integrity over the wire.</span></span> <span data-ttu-id="f3327-182">Die <paramref name="contentMD5" /> Parameter ermöglicht Clients, die bereits Zugriff auf einen vorab berechneten MD5-Wert für einen angegebenen Bytebereich ihn zur Verfügung stellen.</span><span class="sxs-lookup"><span data-stu-id="f3327-182">The <paramref name="contentMD5" /> parameter permits clients who already have access to a pre-computed MD5 value for a given byte range to provide it.</span></span>
            <span data-ttu-id="f3327-183">Wenn die <see cref="P:BlobRequestOptions.UseTransactionalMd5" /> -Eigenschaftensatz auf <c>"true"</c> und die <paramref name="contentMD5" /> Parameter auf festgelegt ist <c>null</c>, und klicken Sie dann die Clientbibliothek intern den MD5-Wert berechnet wird.</span><span class="sxs-lookup"><span data-stu-id="f3327-183">If the <see cref="P:BlobRequestOptions.UseTransactionalMd5" /> property is set to <c>true</c> and the <paramref name="contentMD5" /> parameter is set to <c>null</c>, then the client library will calculate the MD5 value internally.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginPutBlock">
      <MemberSignature Language="C#" Value="public virtual Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginPutBlock (string blockId, System.IO.Stream blockData, string contentMD5, Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, Microsoft.WindowsAzure.Storage.OperationContext operationContext, AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginPutBlock(string blockId, class System.IO.Stream blockData, string contentMD5, class Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, class Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, class Microsoft.WindowsAzure.Storage.OperationContext operationContext, class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlockBlob.BeginPutBlock(System.String,System.IO.Stream,System.String,Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext,System.AsyncCallback,System.Object)" />
      <MemberSignature Language="F#" Value="abstract member BeginPutBlock : string * System.IO.Stream * string * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult&#xA;override this.BeginPutBlock : string * System.IO.Stream * string * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" Usage="cloudBlockBlob.BeginPutBlock (blockId, blockData, contentMD5, accessCondition, options, operationContext, callback, state)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.WindowsAzure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Storage.ICancellableAsyncResult</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="blockId" Type="System.String" />
        <Parameter Name="blockData" Type="System.IO.Stream" />
        <Parameter Name="contentMD5" Type="System.String" />
        <Parameter Name="accessCondition" Type="Microsoft.WindowsAzure.Storage.AccessCondition" />
        <Parameter Name="options" Type="Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
        <Parameter Name="callback" Type="System.AsyncCallback" />
        <Parameter Name="state" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="blockId"><span data-ttu-id="f3327-184">Eine Base64-codierte Zeichenfolge, die den Block identifiziert.</span><span class="sxs-lookup"><span data-stu-id="f3327-184">A Base64-encoded string that identifies the block.</span></span></param>
        <param name="blockData"><span data-ttu-id="f3327-185">Ein <see cref="T:System.IO.Stream" /> -Objekt, das die Daten für den Block bereitstellt.</span><span class="sxs-lookup"><span data-stu-id="f3327-185">A <see cref="T:System.IO.Stream" /> object that provides the data for the block.</span></span></param>
        <param name="contentMD5"><span data-ttu-id="f3327-186">Ein optionaler Hashwert verwendet, um Transaktionsintegrität für den Block sicherzustellen.</span><span class="sxs-lookup"><span data-stu-id="f3327-186">An optional hash value used to ensure transactional integrity for the block.</span></span> <span data-ttu-id="f3327-187">Möglicherweise <c>null</c> oder eine leere Zeichenfolge.</span><span class="sxs-lookup"><span data-stu-id="f3327-187">May be <c>null</c> or an empty string.</span></span></param>
        <param name="accessCondition"><span data-ttu-id="f3327-188">Ein <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> -Objekt, das die Bedingung, die erfüllt sein müssen, damit die Anforderung darstellt, um den Vorgang fortzusetzen.</span><span class="sxs-lookup"><span data-stu-id="f3327-188">An <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> object that represents the condition that must be met in order for the request to proceed.</span></span> <span data-ttu-id="f3327-189">Wenn <c>null</c>, keine Bedingung verwendet.</span><span class="sxs-lookup"><span data-stu-id="f3327-189">If <c>null</c>, no condition is used.</span></span></param>
        <param name="options"><span data-ttu-id="f3327-190">Ein <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" /> -Objekt, das zusätzliche Optionen für die Anforderung angibt oder <c>null</c>.</span><span class="sxs-lookup"><span data-stu-id="f3327-190">A <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" /> object that specifies additional options for the request, or <c>null</c>.</span></span> <span data-ttu-id="f3327-191">Wenn <c>null</c>, Standardoptionen gelten für die Anforderung.</span><span class="sxs-lookup"><span data-stu-id="f3327-191">If <c>null</c>, default options are applied to the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="f3327-192">Ein <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> -Objekt, das den Kontext für den aktuellen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="f3327-192">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <param name="callback"><span data-ttu-id="f3327-193">Ein <see cref="T:System.AsyncCallback" /> Delegat, der Benachrichtigung erhalten sollen, wenn der asynchrone Vorgang abgeschlossen ist.</span><span class="sxs-lookup"><span data-stu-id="f3327-193">An <see cref="T:System.AsyncCallback" /> delegate that will receive notification when the asynchronous operation completes.</span></span></param>
        <param name="state"><span data-ttu-id="f3327-194">Ein benutzerdefiniertes Objekt, die an dem Rückrufdelegaten übergeben werden.</span><span class="sxs-lookup"><span data-stu-id="f3327-194">A user-defined object that will be passed to the callback delegate.</span></span></param>
        <summary>
            <span data-ttu-id="f3327-195">Startet einen asynchronen Vorgang zum Hochladen eines einzelnen Blocks.</span><span class="sxs-lookup"><span data-stu-id="f3327-195">Begins an asynchronous operation to upload a single block.</span></span>
            </summary>
        <returns><span data-ttu-id="f3327-196">Ein <see cref="T:Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" /> , das auf den asynchronen Vorgang verweist.</span><span class="sxs-lookup"><span data-stu-id="f3327-196">An <see cref="T:Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" /> that references the asynchronous operation.</span></span></returns>
        <remarks>
            <span data-ttu-id="f3327-197">Clients können den Content-MD5-Header für einen angegebenen Block Put-Vorgang als Mittel zum Sicherstellen der Transaktionsintegrität unverschlüsselt gesendet.</span><span class="sxs-lookup"><span data-stu-id="f3327-197">Clients may send the Content-MD5 header for a given Put Block operation as a means to ensure transactional integrity over the wire.</span></span> <span data-ttu-id="f3327-198">Die <paramref name="contentMD5" /> Parameter ermöglicht Clients, die bereits Zugriff auf einen vorab berechneten MD5-Wert für einen angegebenen Bytebereich ihn zur Verfügung stellen.</span><span class="sxs-lookup"><span data-stu-id="f3327-198">The <paramref name="contentMD5" /> parameter permits clients who already have access to a pre-computed MD5 value for a given byte range to provide it.</span></span>
            <span data-ttu-id="f3327-199">Wenn die <see cref="P:BlobRequestOptions.UseTransactionalMd5" /> -Eigenschaftensatz auf <c>"true"</c> und die <paramref name="contentMD5" /> Parameter auf festgelegt ist <c>null</c>, und klicken Sie dann die Clientbibliothek intern den MD5-Wert berechnet wird.</span><span class="sxs-lookup"><span data-stu-id="f3327-199">If the <see cref="P:BlobRequestOptions.UseTransactionalMd5" /> property is set to <c>true</c> and the <paramref name="contentMD5" /> parameter is set to <c>null</c>, then the client library will calculate the MD5 value internally.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginPutBlockList">
      <MemberSignature Language="C#" Value="public virtual Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginPutBlockList (System.Collections.Generic.IEnumerable&lt;string&gt; blockList, AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginPutBlockList(class System.Collections.Generic.IEnumerable`1&lt;string&gt; blockList, class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlockBlob.BeginPutBlockList(System.Collections.Generic.IEnumerable{System.String},System.AsyncCallback,System.Object)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function BeginPutBlockList (blockList As IEnumerable(Of String), callback As AsyncCallback, state As Object) As ICancellableAsyncResult" />
      <MemberSignature Language="F#" Value="abstract member BeginPutBlockList : seq&lt;string&gt; * AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult&#xA;override this.BeginPutBlockList : seq&lt;string&gt; * AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" Usage="cloudBlockBlob.BeginPutBlockList (blockList, callback, state)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.WindowsAzure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Storage.ICancellableAsyncResult</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="blockList" Type="System.Collections.Generic.IEnumerable&lt;System.String&gt;" />
        <Parameter Name="callback" Type="System.AsyncCallback" />
        <Parameter Name="state" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="blockList"><span data-ttu-id="f3327-200">Eine aufzählbare Auflistung von Block-IDs als Base64-codierte Zeichenfolgen.</span><span class="sxs-lookup"><span data-stu-id="f3327-200">An enumerable collection of block IDs, as Base64-encoded strings.</span></span></param>
        <param name="callback"><span data-ttu-id="f3327-201">Ein <see cref="T:System.AsyncCallback" /> Delegat, der Benachrichtigung erhalten sollen, wenn der asynchrone Vorgang abgeschlossen ist.</span><span class="sxs-lookup"><span data-stu-id="f3327-201">An <see cref="T:System.AsyncCallback" /> delegate that will receive notification when the asynchronous operation completes.</span></span></param>
        <param name="state"><span data-ttu-id="f3327-202">Ein benutzerdefiniertes Objekt, die an dem Rückrufdelegaten übergeben werden.</span><span class="sxs-lookup"><span data-stu-id="f3327-202">A user-defined object that will be passed to the callback delegate.</span></span></param>
        <summary>
            <span data-ttu-id="f3327-203">Startet einen asynchronen Vorgang zum Hochladen einer Liste von Blöcken in ein neues oder vorhandenes Blob.</span><span class="sxs-lookup"><span data-stu-id="f3327-203">Begins an asynchronous operation to upload a list of blocks to a new or existing blob.</span></span> 
            </summary>
        <returns><span data-ttu-id="f3327-204">Ein <see cref="T:Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" /> , das auf den asynchronen Vorgang verweist.</span><span class="sxs-lookup"><span data-stu-id="f3327-204">An <see cref="T:Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" /> that references the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginPutBlockList">
      <MemberSignature Language="C#" Value="public virtual Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginPutBlockList (System.Collections.Generic.IEnumerable&lt;string&gt; blockList, Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, Microsoft.WindowsAzure.Storage.OperationContext operationContext, AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginPutBlockList(class System.Collections.Generic.IEnumerable`1&lt;string&gt; blockList, class Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, class Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, class Microsoft.WindowsAzure.Storage.OperationContext operationContext, class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlockBlob.BeginPutBlockList(System.Collections.Generic.IEnumerable{System.String},Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext,System.AsyncCallback,System.Object)" />
      <MemberSignature Language="F#" Value="abstract member BeginPutBlockList : seq&lt;string&gt; * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult&#xA;override this.BeginPutBlockList : seq&lt;string&gt; * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" Usage="cloudBlockBlob.BeginPutBlockList (blockList, accessCondition, options, operationContext, callback, state)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.WindowsAzure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Storage.ICancellableAsyncResult</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="blockList" Type="System.Collections.Generic.IEnumerable&lt;System.String&gt;" />
        <Parameter Name="accessCondition" Type="Microsoft.WindowsAzure.Storage.AccessCondition" />
        <Parameter Name="options" Type="Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
        <Parameter Name="callback" Type="System.AsyncCallback" />
        <Parameter Name="state" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="blockList"><span data-ttu-id="f3327-205">Eine aufzählbare Auflistung von Block-IDs als Base64-codierte Zeichenfolgen.</span><span class="sxs-lookup"><span data-stu-id="f3327-205">An enumerable collection of block IDs, as Base64-encoded strings.</span></span></param>
        <param name="accessCondition"><span data-ttu-id="f3327-206">Ein <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> -Objekt, das die Bedingung, die erfüllt sein müssen, damit die Anforderung darstellt, um den Vorgang fortzusetzen.</span><span class="sxs-lookup"><span data-stu-id="f3327-206">An <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> object that represents the condition that must be met in order for the request to proceed.</span></span> <span data-ttu-id="f3327-207">Wenn <c>null</c>, keine Bedingung verwendet.</span><span class="sxs-lookup"><span data-stu-id="f3327-207">If <c>null</c>, no condition is used.</span></span></param>
        <param name="options"><span data-ttu-id="f3327-208">Ein <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" /> -Objekt, das zusätzliche Optionen für die Anforderung angibt.</span><span class="sxs-lookup"><span data-stu-id="f3327-208">A <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" /> object that specifies additional options for the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="f3327-209">Ein <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> -Objekt, das den Kontext für den aktuellen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="f3327-209">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <param name="callback"><span data-ttu-id="f3327-210">Ein <see cref="T:System.AsyncCallback" /> Delegat, der Benachrichtigung erhalten sollen, wenn der asynchrone Vorgang abgeschlossen ist.</span><span class="sxs-lookup"><span data-stu-id="f3327-210">An <see cref="T:System.AsyncCallback" /> delegate that will receive notification when the asynchronous operation completes.</span></span></param>
        <param name="state"><span data-ttu-id="f3327-211">Ein benutzerdefiniertes Objekt, die an dem Rückrufdelegaten übergeben werden.</span><span class="sxs-lookup"><span data-stu-id="f3327-211">A user-defined object that will be passed to the callback delegate.</span></span></param>
        <summary>
            <span data-ttu-id="f3327-212">Startet einen asynchronen Vorgang zum Hochladen einer Liste von Blöcken in ein neues oder vorhandenes Blob.</span><span class="sxs-lookup"><span data-stu-id="f3327-212">Begins an asynchronous operation to upload a list of blocks to a new or existing blob.</span></span> 
            </summary>
        <returns><span data-ttu-id="f3327-213">Ein <see cref="T:Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" /> , das auf den asynchronen Vorgang verweist.</span><span class="sxs-lookup"><span data-stu-id="f3327-213">An <see cref="T:Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" /> that references the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginSetStandardBlobTier">
      <MemberSignature Language="C#" Value="public virtual Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginSetStandardBlobTier (Microsoft.WindowsAzure.Storage.Blob.StandardBlobTier standardBlobTier, AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginSetStandardBlobTier(valuetype Microsoft.WindowsAzure.Storage.Blob.StandardBlobTier standardBlobTier, class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlockBlob.BeginSetStandardBlobTier(Microsoft.WindowsAzure.Storage.Blob.StandardBlobTier,System.AsyncCallback,System.Object)" />
      <MemberSignature Language="F#" Value="abstract member BeginSetStandardBlobTier : Microsoft.WindowsAzure.Storage.Blob.StandardBlobTier * AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult&#xA;override this.BeginSetStandardBlobTier : Microsoft.WindowsAzure.Storage.Blob.StandardBlobTier * AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" Usage="cloudBlockBlob.BeginSetStandardBlobTier (standardBlobTier, callback, state)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.WindowsAzure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Storage.ICancellableAsyncResult</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="standardBlobTier" Type="Microsoft.WindowsAzure.Storage.Blob.StandardBlobTier" />
        <Parameter Name="callback" Type="System.AsyncCallback" />
        <Parameter Name="state" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="standardBlobTier"><span data-ttu-id="f3327-214">Ein <see cref="T:Microsoft.WindowsAzure.Storage.Blob.StandardBlobTier" /> , legen Sie die Ebene darstellt.</span><span class="sxs-lookup"><span data-stu-id="f3327-214">A <see cref="T:Microsoft.WindowsAzure.Storage.Blob.StandardBlobTier" /> representing the tier to set.</span></span></param>
        <param name="callback"><span data-ttu-id="f3327-215">Ein <see cref="T:System.AsyncCallback" /> Delegat, der Benachrichtigung erhalten sollen, wenn der asynchrone Vorgang abgeschlossen ist.</span><span class="sxs-lookup"><span data-stu-id="f3327-215">An <see cref="T:System.AsyncCallback" /> delegate that will receive notification when the asynchronous operation completes.</span></span></param>
        <param name="state"><span data-ttu-id="f3327-216">Ein benutzerdefiniertes Objekt, die an dem Rückrufdelegaten übergeben werden.</span><span class="sxs-lookup"><span data-stu-id="f3327-216">A user-defined object that will be passed to the callback delegate.</span></span></param>
        <summary>
            <span data-ttu-id="f3327-217">Startet einen asynchronen Vorgang zum Festlegen der Ebene des BLOBs auf einen standard-Speicherkonto.</span><span class="sxs-lookup"><span data-stu-id="f3327-217">Begins an asynchronous operation to set the tier of the blob on a standard storage account.</span></span>
            </summary>
        <returns><span data-ttu-id="f3327-218">Ein <see cref="T:Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" /> , das auf den asynchronen Vorgang verweist.</span><span class="sxs-lookup"><span data-stu-id="f3327-218">An <see cref="T:Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" /> that references the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginSetStandardBlobTier">
      <MemberSignature Language="C#" Value="public virtual Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginSetStandardBlobTier (Microsoft.WindowsAzure.Storage.Blob.StandardBlobTier standardBlobTier, Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, Microsoft.WindowsAzure.Storage.OperationContext operationContext, AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginSetStandardBlobTier(valuetype Microsoft.WindowsAzure.Storage.Blob.StandardBlobTier standardBlobTier, class Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, class Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, class Microsoft.WindowsAzure.Storage.OperationContext operationContext, class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlockBlob.BeginSetStandardBlobTier(Microsoft.WindowsAzure.Storage.Blob.StandardBlobTier,Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext,System.AsyncCallback,System.Object)" />
      <MemberSignature Language="F#" Value="abstract member BeginSetStandardBlobTier : Microsoft.WindowsAzure.Storage.Blob.StandardBlobTier * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult&#xA;override this.BeginSetStandardBlobTier : Microsoft.WindowsAzure.Storage.Blob.StandardBlobTier * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" Usage="cloudBlockBlob.BeginSetStandardBlobTier (standardBlobTier, accessCondition, options, operationContext, callback, state)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.WindowsAzure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Storage.ICancellableAsyncResult</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="standardBlobTier" Type="Microsoft.WindowsAzure.Storage.Blob.StandardBlobTier" />
        <Parameter Name="accessCondition" Type="Microsoft.WindowsAzure.Storage.AccessCondition" />
        <Parameter Name="options" Type="Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
        <Parameter Name="callback" Type="System.AsyncCallback" />
        <Parameter Name="state" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="standardBlobTier"><span data-ttu-id="f3327-219">Ein <see cref="T:Microsoft.WindowsAzure.Storage.Blob.StandardBlobTier" /> , legen Sie die Ebene darstellt.</span><span class="sxs-lookup"><span data-stu-id="f3327-219">A <see cref="T:Microsoft.WindowsAzure.Storage.Blob.StandardBlobTier" /> representing the tier to set.</span></span></param>
        <param name="accessCondition"><span data-ttu-id="f3327-220">Ein <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> -Objekt, das die Bedingung, die erfüllt sein müssen, damit die Anforderung darstellt, um den Vorgang fortzusetzen.</span><span class="sxs-lookup"><span data-stu-id="f3327-220">An <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> object that represents the condition that must be met in order for the request to proceed.</span></span> <span data-ttu-id="f3327-221">Wenn <c>null</c>, keine Bedingung verwendet.</span><span class="sxs-lookup"><span data-stu-id="f3327-221">If <c>null</c>, no condition is used.</span></span></param>
        <param name="options"><span data-ttu-id="f3327-222">Ein <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" /> -Objekt, das zusätzliche Optionen für die Anforderung angibt oder <c>null</c>.</span><span class="sxs-lookup"><span data-stu-id="f3327-222">A <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" /> object that specifies additional options for the request, or <c>null</c>.</span></span></param>
        <param name="operationContext"><span data-ttu-id="f3327-223">Ein <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> -Objekt, das den Kontext für den aktuellen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="f3327-223">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <param name="callback"><span data-ttu-id="f3327-224">Ein <see cref="T:System.AsyncCallback" /> Delegat, der Benachrichtigung erhalten sollen, wenn der asynchrone Vorgang abgeschlossen ist.</span><span class="sxs-lookup"><span data-stu-id="f3327-224">An <see cref="T:System.AsyncCallback" /> delegate that will receive notification when the asynchronous operation completes.</span></span></param>
        <param name="state"><span data-ttu-id="f3327-225">Ein benutzerdefiniertes Objekt, die an dem Rückrufdelegaten übergeben werden.</span><span class="sxs-lookup"><span data-stu-id="f3327-225">A user-defined object that will be passed to the callback delegate.</span></span></param>
        <summary>
            <span data-ttu-id="f3327-226">Startet einen asynchronen Vorgang zum Festlegen der Ebene des BLOBs auf einen standard-Speicherkonto.</span><span class="sxs-lookup"><span data-stu-id="f3327-226">Begins an asynchronous operation to set the tier of the blob on a standard storage account.</span></span>
            </summary>
        <returns><span data-ttu-id="f3327-227">Ein <see cref="T:Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" /> , das auf den asynchronen Vorgang verweist.</span><span class="sxs-lookup"><span data-stu-id="f3327-227">An <see cref="T:Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" /> that references the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginStartCopy">
      <MemberSignature Language="C#" Value="public virtual Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginStartCopy (Microsoft.WindowsAzure.Storage.Blob.CloudBlockBlob source, AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginStartCopy(class Microsoft.WindowsAzure.Storage.Blob.CloudBlockBlob source, class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlockBlob.BeginStartCopy(Microsoft.WindowsAzure.Storage.Blob.CloudBlockBlob,System.AsyncCallback,System.Object)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function BeginStartCopy (source As CloudBlockBlob, callback As AsyncCallback, state As Object) As ICancellableAsyncResult" />
      <MemberSignature Language="F#" Value="override this.BeginStartCopy : Microsoft.WindowsAzure.Storage.Blob.CloudBlockBlob * AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" Usage="cloudBlockBlob.BeginStartCopy (source, callback, state)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.WindowsAzure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Storage.ICancellableAsyncResult</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="source" Type="Microsoft.WindowsAzure.Storage.Blob.CloudBlockBlob" />
        <Parameter Name="callback" Type="System.AsyncCallback" />
        <Parameter Name="state" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="source"><span data-ttu-id="f3327-228">Ein <see cref="T:Microsoft.WindowsAzure.Storage.Blob.CloudBlockBlob" />-Objekt.</span><span class="sxs-lookup"><span data-stu-id="f3327-228">A <see cref="T:Microsoft.WindowsAzure.Storage.Blob.CloudBlockBlob" /> object.</span></span></param>
        <param name="callback"><span data-ttu-id="f3327-229">Ein <see cref="T:System.AsyncCallback" /> Delegat, der Benachrichtigung erhalten sollen, wenn der asynchrone Vorgang abgeschlossen ist.</span><span class="sxs-lookup"><span data-stu-id="f3327-229">An <see cref="T:System.AsyncCallback" /> delegate that will receive notification when the asynchronous operation completes.</span></span></param>
        <param name="state"><span data-ttu-id="f3327-230">Ein benutzerdefiniertes Objekt, die an dem Rückrufdelegaten übergeben werden.</span><span class="sxs-lookup"><span data-stu-id="f3327-230">A user-defined object that will be passed to the callback delegate.</span></span></param>
        <summary>
            <span data-ttu-id="f3327-231">Startet einen asynchronen Vorgang zum Starten von einem anderen Block-Blob-Inhalte, Eigenschaften und Metadaten in diesem Block-Blob kopiert.</span><span class="sxs-lookup"><span data-stu-id="f3327-231">Begins an asynchronous operation to start copying another block blob's contents, properties, and metadata to this block blob.</span></span>
            </summary>
        <returns><span data-ttu-id="f3327-232">Ein <see cref="T:Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" /> , das auf den asynchronen Vorgang verweist.</span><span class="sxs-lookup"><span data-stu-id="f3327-232">An <see cref="T:Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" /> that references the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginStartCopy">
      <MemberSignature Language="C#" Value="public virtual Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginStartCopy (Microsoft.WindowsAzure.Storage.File.CloudFile source, AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginStartCopy(class Microsoft.WindowsAzure.Storage.File.CloudFile source, class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlockBlob.BeginStartCopy(Microsoft.WindowsAzure.Storage.File.CloudFile,System.AsyncCallback,System.Object)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function BeginStartCopy (source As CloudFile, callback As AsyncCallback, state As Object) As ICancellableAsyncResult" />
      <MemberSignature Language="F#" Value="override this.BeginStartCopy : Microsoft.WindowsAzure.Storage.File.CloudFile * AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" Usage="cloudBlockBlob.BeginStartCopy (source, callback, state)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.WindowsAzure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Storage.ICancellableAsyncResult</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="source" Type="Microsoft.WindowsAzure.Storage.File.CloudFile" />
        <Parameter Name="callback" Type="System.AsyncCallback" />
        <Parameter Name="state" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="source"><span data-ttu-id="f3327-233">Ein <see cref="T:Microsoft.WindowsAzure.Storage.File.CloudFile" />-Objekt.</span><span class="sxs-lookup"><span data-stu-id="f3327-233">A <see cref="T:Microsoft.WindowsAzure.Storage.File.CloudFile" /> object.</span></span></param>
        <param name="callback"><span data-ttu-id="f3327-234">Ein <see cref="T:System.AsyncCallback" /> Delegat, der Benachrichtigung erhalten sollen, wenn der asynchrone Vorgang abgeschlossen ist.</span><span class="sxs-lookup"><span data-stu-id="f3327-234">An <see cref="T:System.AsyncCallback" /> delegate that will receive notification when the asynchronous operation completes.</span></span></param>
        <param name="state"><span data-ttu-id="f3327-235">Ein benutzerdefiniertes Objekt, die an dem Rückrufdelegaten übergeben werden.</span><span class="sxs-lookup"><span data-stu-id="f3327-235">A user-defined object that will be passed to the callback delegate.</span></span></param>
        <summary>
            <span data-ttu-id="f3327-236">Startet einen asynchronen Vorgang zum Starten von Inhalt, Eigenschaften und Metadaten einer Datei in diesem Block-Blob kopiert.</span><span class="sxs-lookup"><span data-stu-id="f3327-236">Begins an asynchronous operation to start copying a file's contents, properties, and metadata to this block blob.</span></span>
            </summary>
        <returns><span data-ttu-id="f3327-237">Ein <see cref="T:Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" /> , das auf den asynchronen Vorgang verweist.</span><span class="sxs-lookup"><span data-stu-id="f3327-237">An <see cref="T:Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" /> that references the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginStartCopy">
      <MemberSignature Language="C#" Value="public virtual Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginStartCopy (Microsoft.WindowsAzure.Storage.Blob.CloudBlockBlob source, Microsoft.WindowsAzure.Storage.AccessCondition sourceAccessCondition, Microsoft.WindowsAzure.Storage.AccessCondition destAccessCondition, Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, Microsoft.WindowsAzure.Storage.OperationContext operationContext, AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginStartCopy(class Microsoft.WindowsAzure.Storage.Blob.CloudBlockBlob source, class Microsoft.WindowsAzure.Storage.AccessCondition sourceAccessCondition, class Microsoft.WindowsAzure.Storage.AccessCondition destAccessCondition, class Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, class Microsoft.WindowsAzure.Storage.OperationContext operationContext, class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlockBlob.BeginStartCopy(Microsoft.WindowsAzure.Storage.Blob.CloudBlockBlob,Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext,System.AsyncCallback,System.Object)" />
      <MemberSignature Language="F#" Value="override this.BeginStartCopy : Microsoft.WindowsAzure.Storage.Blob.CloudBlockBlob * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" Usage="cloudBlockBlob.BeginStartCopy (source, sourceAccessCondition, destAccessCondition, options, operationContext, callback, state)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.WindowsAzure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Storage.ICancellableAsyncResult</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="source" Type="Microsoft.WindowsAzure.Storage.Blob.CloudBlockBlob" />
        <Parameter Name="sourceAccessCondition" Type="Microsoft.WindowsAzure.Storage.AccessCondition" />
        <Parameter Name="destAccessCondition" Type="Microsoft.WindowsAzure.Storage.AccessCondition" />
        <Parameter Name="options" Type="Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
        <Parameter Name="callback" Type="System.AsyncCallback" />
        <Parameter Name="state" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="source"><span data-ttu-id="f3327-238">Ein <see cref="T:Microsoft.WindowsAzure.Storage.Blob.CloudBlockBlob" />-Objekt.</span><span class="sxs-lookup"><span data-stu-id="f3327-238">A <see cref="T:Microsoft.WindowsAzure.Storage.Blob.CloudBlockBlob" /> object.</span></span></param>
        <param name="sourceAccessCondition"><span data-ttu-id="f3327-239">Ein <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> -Objekt, das die zugriffsbedingungen für das Quell-Blob darstellt.</span><span class="sxs-lookup"><span data-stu-id="f3327-239">An <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> object that represents the access conditions for the source blob.</span></span> <span data-ttu-id="f3327-240">Wenn <c>null</c>, keine Bedingung verwendet.</span><span class="sxs-lookup"><span data-stu-id="f3327-240">If <c>null</c>, no condition is used.</span></span></param>
        <param name="destAccessCondition"><span data-ttu-id="f3327-241">Ein <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> -Objekt, das die zugriffsbedingungen für das Ziel-Blob darstellt.</span><span class="sxs-lookup"><span data-stu-id="f3327-241">An <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> object that represents the access conditions for the destination blob.</span></span> <span data-ttu-id="f3327-242">Wenn <c>null</c>, keine Bedingung verwendet.</span><span class="sxs-lookup"><span data-stu-id="f3327-242">If <c>null</c>, no condition is used.</span></span></param>
        <param name="options"><span data-ttu-id="f3327-243">Ein <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" /> -Objekt, das zusätzliche Optionen für die Anforderung angibt.</span><span class="sxs-lookup"><span data-stu-id="f3327-243">A <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" /> object that specifies additional options for the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="f3327-244">Ein <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> -Objekt, das den Kontext für den aktuellen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="f3327-244">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <param name="callback"><span data-ttu-id="f3327-245">Ein <see cref="T:System.AsyncCallback" /> Delegat, der Benachrichtigung erhalten sollen, wenn der asynchrone Vorgang abgeschlossen ist.</span><span class="sxs-lookup"><span data-stu-id="f3327-245">An <see cref="T:System.AsyncCallback" /> delegate that will receive notification when the asynchronous operation completes.</span></span></param>
        <param name="state"><span data-ttu-id="f3327-246">Ein benutzerdefiniertes Objekt, die an dem Rückrufdelegaten übergeben werden.</span><span class="sxs-lookup"><span data-stu-id="f3327-246">A user-defined object that will be passed to the callback delegate.</span></span></param>
        <summary>
            <span data-ttu-id="f3327-247">Startet einen asynchronen Vorgang zum Starten von einem anderen Block-Blob-Inhalte, Eigenschaften und Metadaten in diesem Block-Blob kopiert.</span><span class="sxs-lookup"><span data-stu-id="f3327-247">Begins an asynchronous operation to start copying another block blob's contents, properties, and metadata to this block blob.</span></span>
            </summary>
        <returns><span data-ttu-id="f3327-248">Ein <see cref="T:Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" /> , das auf den asynchronen Vorgang verweist.</span><span class="sxs-lookup"><span data-stu-id="f3327-248">An <see cref="T:Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" /> that references the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginStartCopy">
      <MemberSignature Language="C#" Value="public virtual Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginStartCopy (Microsoft.WindowsAzure.Storage.File.CloudFile source, Microsoft.WindowsAzure.Storage.AccessCondition sourceAccessCondition, Microsoft.WindowsAzure.Storage.AccessCondition destAccessCondition, Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, Microsoft.WindowsAzure.Storage.OperationContext operationContext, AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginStartCopy(class Microsoft.WindowsAzure.Storage.File.CloudFile source, class Microsoft.WindowsAzure.Storage.AccessCondition sourceAccessCondition, class Microsoft.WindowsAzure.Storage.AccessCondition destAccessCondition, class Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, class Microsoft.WindowsAzure.Storage.OperationContext operationContext, class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlockBlob.BeginStartCopy(Microsoft.WindowsAzure.Storage.File.CloudFile,Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext,System.AsyncCallback,System.Object)" />
      <MemberSignature Language="F#" Value="override this.BeginStartCopy : Microsoft.WindowsAzure.Storage.File.CloudFile * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" Usage="cloudBlockBlob.BeginStartCopy (source, sourceAccessCondition, destAccessCondition, options, operationContext, callback, state)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.WindowsAzure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Storage.ICancellableAsyncResult</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="source" Type="Microsoft.WindowsAzure.Storage.File.CloudFile" />
        <Parameter Name="sourceAccessCondition" Type="Microsoft.WindowsAzure.Storage.AccessCondition" />
        <Parameter Name="destAccessCondition" Type="Microsoft.WindowsAzure.Storage.AccessCondition" />
        <Parameter Name="options" Type="Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
        <Parameter Name="callback" Type="System.AsyncCallback" />
        <Parameter Name="state" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="source"><span data-ttu-id="f3327-249">Ein <see cref="T:Microsoft.WindowsAzure.Storage.File.CloudFile" />-Objekt.</span><span class="sxs-lookup"><span data-stu-id="f3327-249">A <see cref="T:Microsoft.WindowsAzure.Storage.File.CloudFile" /> object.</span></span></param>
        <param name="sourceAccessCondition"><span data-ttu-id="f3327-250">Ein <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> -Objekt, das die zugriffsbedingungen für die Quelldatei darstellt.</span><span class="sxs-lookup"><span data-stu-id="f3327-250">An <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> object that represents the access conditions for the source file.</span></span> <span data-ttu-id="f3327-251">Wenn <c>null</c>, keine Bedingung verwendet.</span><span class="sxs-lookup"><span data-stu-id="f3327-251">If <c>null</c>, no condition is used.</span></span></param>
        <param name="destAccessCondition"><span data-ttu-id="f3327-252">Ein <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> -Objekt, das die zugriffsbedingungen für das Ziel-Blob darstellt.</span><span class="sxs-lookup"><span data-stu-id="f3327-252">An <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> object that represents the access conditions for the destination blob.</span></span> <span data-ttu-id="f3327-253">Wenn <c>null</c>, keine Bedingung verwendet.</span><span class="sxs-lookup"><span data-stu-id="f3327-253">If <c>null</c>, no condition is used.</span></span></param>
        <param name="options"><span data-ttu-id="f3327-254">Ein <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" /> -Objekt, das zusätzliche Optionen für die Anforderung angibt.</span><span class="sxs-lookup"><span data-stu-id="f3327-254">A <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" /> object that specifies additional options for the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="f3327-255">Ein <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> -Objekt, das den Kontext für den aktuellen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="f3327-255">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <param name="callback"><span data-ttu-id="f3327-256">Ein <see cref="T:System.AsyncCallback" /> Delegat, der Benachrichtigung erhalten sollen, wenn der asynchrone Vorgang abgeschlossen ist.</span><span class="sxs-lookup"><span data-stu-id="f3327-256">An <see cref="T:System.AsyncCallback" /> delegate that will receive notification when the asynchronous operation completes.</span></span></param>
        <param name="state"><span data-ttu-id="f3327-257">Ein benutzerdefiniertes Objekt, die an dem Rückrufdelegaten übergeben werden.</span><span class="sxs-lookup"><span data-stu-id="f3327-257">A user-defined object that will be passed to the callback delegate.</span></span></param>
        <summary>
            <span data-ttu-id="f3327-258">Startet einen asynchronen Vorgang zum Starten von Inhalt, Eigenschaften und Metadaten einer Datei in diesem Block-Blob kopiert.</span><span class="sxs-lookup"><span data-stu-id="f3327-258">Begins an asynchronous operation to start copying a file's contents, properties, and metadata to this block blob.</span></span>
            </summary>
        <returns><span data-ttu-id="f3327-259">Ein <see cref="T:Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" /> , das auf den asynchronen Vorgang verweist.</span><span class="sxs-lookup"><span data-stu-id="f3327-259">An <see cref="T:Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" /> that references the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginUploadFromByteArray">
      <MemberSignature Language="C#" Value="public virtual Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginUploadFromByteArray (byte[] buffer, int index, int count, AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginUploadFromByteArray(unsigned int8[] buffer, int32 index, int32 count, class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlockBlob.BeginUploadFromByteArray(System.Byte[],System.Int32,System.Int32,System.AsyncCallback,System.Object)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function BeginUploadFromByteArray (buffer As Byte(), index As Integer, count As Integer, callback As AsyncCallback, state As Object) As ICancellableAsyncResult" />
      <MemberSignature Language="F#" Value="abstract member BeginUploadFromByteArray : byte[] * int * int * AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult&#xA;override this.BeginUploadFromByteArray : byte[] * int * int * AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" Usage="cloudBlockBlob.BeginUploadFromByteArray (buffer, index, count, callback, state)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.WindowsAzure.Storage.Blob.ICloudBlob.BeginUploadFromByteArray(System.Byte[],System.Int32,System.Int32,System.AsyncCallback,System.Object)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.WindowsAzure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Storage.ICancellableAsyncResult</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="buffer" Type="System.Byte[]" />
        <Parameter Name="index" Type="System.Int32" />
        <Parameter Name="count" Type="System.Int32" />
        <Parameter Name="callback" Type="System.AsyncCallback" />
        <Parameter Name="state" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="buffer"><span data-ttu-id="f3327-260">Ein Bytearray.</span><span class="sxs-lookup"><span data-stu-id="f3327-260">An array of bytes.</span></span></param>
        <param name="index"><span data-ttu-id="f3327-261">Der nullbasierte Byteoffset im Puffer, ab dem Bytes in den Blob hochgeladen werden soll.</span><span class="sxs-lookup"><span data-stu-id="f3327-261">The zero-based byte offset in buffer at which to begin uploading bytes to the blob.</span></span></param>
        <param name="count"><span data-ttu-id="f3327-262">Die Anzahl der Bytes, die in das Blob geschrieben werden.</span><span class="sxs-lookup"><span data-stu-id="f3327-262">The number of bytes to be written to the blob.</span></span></param>
        <param name="callback"><span data-ttu-id="f3327-263">Ein <see cref="T:System.AsyncCallback" /> Delegat, der Benachrichtigung erhalten sollen, wenn der asynchrone Vorgang abgeschlossen ist.</span><span class="sxs-lookup"><span data-stu-id="f3327-263">An <see cref="T:System.AsyncCallback" /> delegate that will receive notification when the asynchronous operation completes.</span></span></param>
        <param name="state"><span data-ttu-id="f3327-264">Ein benutzerdefiniertes Objekt, die an dem Rückrufdelegaten übergeben werden.</span><span class="sxs-lookup"><span data-stu-id="f3327-264">A user-defined object that will be passed to the callback delegate.</span></span></param>
        <summary>
            <span data-ttu-id="f3327-265">Startet einen asynchronen Vorgang, um den Inhalt eines Bytearrays in ein Blob hochladen.</span><span class="sxs-lookup"><span data-stu-id="f3327-265">Begins an asynchronous operation to upload the contents of a byte array to a blob.</span></span> <span data-ttu-id="f3327-266">Wenn das Blob bereits vorhanden ist, wird sie überschrieben.</span><span class="sxs-lookup"><span data-stu-id="f3327-266">If the blob already exists, it will be overwritten.</span></span>
            </summary>
        <returns><span data-ttu-id="f3327-267">Ein <see cref="T:Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" /> , das auf den asynchronen Vorgang verweist.</span><span class="sxs-lookup"><span data-stu-id="f3327-267">An <see cref="T:Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" /> that references the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginUploadFromByteArray">
      <MemberSignature Language="C#" Value="public virtual Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginUploadFromByteArray (byte[] buffer, int index, int count, Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, Microsoft.WindowsAzure.Storage.OperationContext operationContext, AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginUploadFromByteArray(unsigned int8[] buffer, int32 index, int32 count, class Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, class Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, class Microsoft.WindowsAzure.Storage.OperationContext operationContext, class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlockBlob.BeginUploadFromByteArray(System.Byte[],System.Int32,System.Int32,Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext,System.AsyncCallback,System.Object)" />
      <MemberSignature Language="F#" Value="abstract member BeginUploadFromByteArray : byte[] * int * int * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult&#xA;override this.BeginUploadFromByteArray : byte[] * int * int * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" Usage="cloudBlockBlob.BeginUploadFromByteArray (buffer, index, count, accessCondition, options, operationContext, callback, state)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.WindowsAzure.Storage.Blob.ICloudBlob.BeginUploadFromByteArray(System.Byte[],System.Int32,System.Int32,Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext,System.AsyncCallback,System.Object)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.WindowsAzure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Storage.ICancellableAsyncResult</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="buffer" Type="System.Byte[]" />
        <Parameter Name="index" Type="System.Int32" />
        <Parameter Name="count" Type="System.Int32" />
        <Parameter Name="accessCondition" Type="Microsoft.WindowsAzure.Storage.AccessCondition" />
        <Parameter Name="options" Type="Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
        <Parameter Name="callback" Type="System.AsyncCallback" />
        <Parameter Name="state" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="buffer"><span data-ttu-id="f3327-268">Ein Bytearray.</span><span class="sxs-lookup"><span data-stu-id="f3327-268">An array of bytes.</span></span></param>
        <param name="index"><span data-ttu-id="f3327-269">Der nullbasierte Byteoffset im Puffer, ab dem Bytes in den Blob hochgeladen werden soll.</span><span class="sxs-lookup"><span data-stu-id="f3327-269">The zero-based byte offset in buffer at which to begin uploading bytes to the blob.</span></span></param>
        <param name="count"><span data-ttu-id="f3327-270">Die Anzahl der Bytes, die in das Blob geschrieben werden.</span><span class="sxs-lookup"><span data-stu-id="f3327-270">The number of bytes to be written to the blob.</span></span></param>
        <param name="accessCondition"><span data-ttu-id="f3327-271">Ein <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> -Objekt, das die Bedingung, die erfüllt sein müssen, damit die Anforderung darstellt, um den Vorgang fortzusetzen.</span><span class="sxs-lookup"><span data-stu-id="f3327-271">An <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> object that represents the condition that must be met in order for the request to proceed.</span></span></param>
        <param name="options"><span data-ttu-id="f3327-272">Ein <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" /> -Objekt, das zusätzliche Optionen für die Anforderung angibt.</span><span class="sxs-lookup"><span data-stu-id="f3327-272">A <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" /> object that specifies additional options for the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="f3327-273">Ein <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> -Objekt, das den Kontext für den aktuellen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="f3327-273">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <param name="callback"><span data-ttu-id="f3327-274">Ein <see cref="T:System.AsyncCallback" /> Delegat, der Benachrichtigung erhalten sollen, wenn der asynchrone Vorgang abgeschlossen ist.</span><span class="sxs-lookup"><span data-stu-id="f3327-274">An <see cref="T:System.AsyncCallback" /> delegate that will receive notification when the asynchronous operation completes.</span></span></param>
        <param name="state"><span data-ttu-id="f3327-275">Ein benutzerdefiniertes Objekt, die an dem Rückrufdelegaten übergeben werden.</span><span class="sxs-lookup"><span data-stu-id="f3327-275">A user-defined object that will be passed to the callback delegate.</span></span></param>
        <summary>
            <span data-ttu-id="f3327-276">Startet einen asynchronen Vorgang, um den Inhalt eines Bytearrays in ein Blob hochladen.</span><span class="sxs-lookup"><span data-stu-id="f3327-276">Begins an asynchronous operation to upload the contents of a byte array to a blob.</span></span> <span data-ttu-id="f3327-277">Wenn das Blob bereits vorhanden ist, wird sie überschrieben.</span><span class="sxs-lookup"><span data-stu-id="f3327-277">If the blob already exists, it will be overwritten.</span></span>
            </summary>
        <returns><span data-ttu-id="f3327-278">Ein <see cref="T:Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" /> , das auf den asynchronen Vorgang verweist.</span><span class="sxs-lookup"><span data-stu-id="f3327-278">An <see cref="T:Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" /> that references the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginUploadFromFile">
      <MemberSignature Language="C#" Value="public virtual Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginUploadFromFile (string path, AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginUploadFromFile(string path, class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlockBlob.BeginUploadFromFile(System.String,System.AsyncCallback,System.Object)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function BeginUploadFromFile (path As String, callback As AsyncCallback, state As Object) As ICancellableAsyncResult" />
      <MemberSignature Language="F#" Value="abstract member BeginUploadFromFile : string * AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult&#xA;override this.BeginUploadFromFile : string * AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" Usage="cloudBlockBlob.BeginUploadFromFile (path, callback, state)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.WindowsAzure.Storage.Blob.ICloudBlob.BeginUploadFromFile(System.String,System.AsyncCallback,System.Object)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.WindowsAzure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Storage.ICancellableAsyncResult</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="path" Type="System.String" />
        <Parameter Name="callback" Type="System.AsyncCallback" />
        <Parameter Name="state" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="path"><span data-ttu-id="f3327-279">Eine Zeichenfolge mit den Dateipfad der Blob-Inhalte bereitstellen.</span><span class="sxs-lookup"><span data-stu-id="f3327-279">A string containing the file path providing the blob content.</span></span></param>
        <param name="callback"><span data-ttu-id="f3327-280">Ein <see cref="T:System.AsyncCallback" /> Delegat, der Benachrichtigung erhalten sollen, wenn der asynchrone Vorgang abgeschlossen ist.</span><span class="sxs-lookup"><span data-stu-id="f3327-280">An <see cref="T:System.AsyncCallback" /> delegate that will receive notification when the asynchronous operation completes.</span></span></param>
        <param name="state"><span data-ttu-id="f3327-281">Ein benutzerdefiniertes Objekt, die an dem Rückrufdelegaten übergeben werden.</span><span class="sxs-lookup"><span data-stu-id="f3327-281">A user-defined object that will be passed to the callback delegate.</span></span></param>
        <summary>
            <span data-ttu-id="f3327-282">Startet einen asynchronen Vorgang zum Hochladen einer Datei in ein Blob.</span><span class="sxs-lookup"><span data-stu-id="f3327-282">Begins an asynchronous operation to upload a file to a blob.</span></span> <span data-ttu-id="f3327-283">Wenn das Blob bereits vorhanden ist, wird sie überschrieben.</span><span class="sxs-lookup"><span data-stu-id="f3327-283">If the blob already exists, it will be overwritten.</span></span>
            </summary>
        <returns><span data-ttu-id="f3327-284">Ein <see cref="T:Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" /> , das auf den asynchronen Vorgang verweist.</span><span class="sxs-lookup"><span data-stu-id="f3327-284">An <see cref="T:Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" /> that references the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginUploadFromFile">
      <MemberSignature Language="C#" Value="public virtual Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginUploadFromFile (string path, Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, Microsoft.WindowsAzure.Storage.OperationContext operationContext, AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginUploadFromFile(string path, class Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, class Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, class Microsoft.WindowsAzure.Storage.OperationContext operationContext, class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlockBlob.BeginUploadFromFile(System.String,Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext,System.AsyncCallback,System.Object)" />
      <MemberSignature Language="F#" Value="abstract member BeginUploadFromFile : string * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult&#xA;override this.BeginUploadFromFile : string * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" Usage="cloudBlockBlob.BeginUploadFromFile (path, accessCondition, options, operationContext, callback, state)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.WindowsAzure.Storage.Blob.ICloudBlob.BeginUploadFromFile(System.String,Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext,System.AsyncCallback,System.Object)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.WindowsAzure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Storage.ICancellableAsyncResult</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="path" Type="System.String" />
        <Parameter Name="accessCondition" Type="Microsoft.WindowsAzure.Storage.AccessCondition" />
        <Parameter Name="options" Type="Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
        <Parameter Name="callback" Type="System.AsyncCallback" />
        <Parameter Name="state" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="path"><span data-ttu-id="f3327-285">Eine Zeichenfolge mit den Dateipfad der Blob-Inhalte bereitstellen.</span><span class="sxs-lookup"><span data-stu-id="f3327-285">A string containing the file path providing the blob content.</span></span></param>
        <param name="accessCondition"><span data-ttu-id="f3327-286">Ein <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> -Objekt, das die Bedingung, die erfüllt sein müssen, damit die Anforderung darstellt, um den Vorgang fortzusetzen.</span><span class="sxs-lookup"><span data-stu-id="f3327-286">An <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> object that represents the condition that must be met in order for the request to proceed.</span></span></param>
        <param name="options"><span data-ttu-id="f3327-287">Ein <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" /> -Objekt, das zusätzliche Optionen für die Anforderung angibt.</span><span class="sxs-lookup"><span data-stu-id="f3327-287">A <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" /> object that specifies additional options for the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="f3327-288">Ein <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> -Objekt, das den Kontext für den aktuellen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="f3327-288">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <param name="callback"><span data-ttu-id="f3327-289">Ein <see cref="T:System.AsyncCallback" /> Delegat, der Benachrichtigung erhalten sollen, wenn der asynchrone Vorgang abgeschlossen ist.</span><span class="sxs-lookup"><span data-stu-id="f3327-289">An <see cref="T:System.AsyncCallback" /> delegate that will receive notification when the asynchronous operation completes.</span></span></param>
        <param name="state"><span data-ttu-id="f3327-290">Ein benutzerdefiniertes Objekt, die an dem Rückrufdelegaten übergeben werden.</span><span class="sxs-lookup"><span data-stu-id="f3327-290">A user-defined object that will be passed to the callback delegate.</span></span></param>
        <summary>
            <span data-ttu-id="f3327-291">Startet einen asynchronen Vorgang zum Hochladen einer Datei in ein Blob.</span><span class="sxs-lookup"><span data-stu-id="f3327-291">Begins an asynchronous operation to upload a file to a blob.</span></span> <span data-ttu-id="f3327-292">Wenn das Blob bereits vorhanden ist, wird sie überschrieben.</span><span class="sxs-lookup"><span data-stu-id="f3327-292">If the blob already exists, it will be overwritten.</span></span>
            </summary>
        <returns><span data-ttu-id="f3327-293">Ein <see cref="T:Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" /> , das auf den asynchronen Vorgang verweist.</span><span class="sxs-lookup"><span data-stu-id="f3327-293">An <see cref="T:Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" /> that references the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginUploadFromStream">
      <MemberSignature Language="C#" Value="public virtual Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginUploadFromStream (System.IO.Stream source, AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginUploadFromStream(class System.IO.Stream source, class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlockBlob.BeginUploadFromStream(System.IO.Stream,System.AsyncCallback,System.Object)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function BeginUploadFromStream (source As Stream, callback As AsyncCallback, state As Object) As ICancellableAsyncResult" />
      <MemberSignature Language="F#" Value="abstract member BeginUploadFromStream : System.IO.Stream * AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult&#xA;override this.BeginUploadFromStream : System.IO.Stream * AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" Usage="cloudBlockBlob.BeginUploadFromStream (source, callback, state)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.WindowsAzure.Storage.Blob.ICloudBlob.BeginUploadFromStream(System.IO.Stream,System.AsyncCallback,System.Object)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.WindowsAzure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Storage.ICancellableAsyncResult</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="source" Type="System.IO.Stream" />
        <Parameter Name="callback" Type="System.AsyncCallback" />
        <Parameter Name="state" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="source"><span data-ttu-id="f3327-294">Ein <see cref="T:System.IO.Stream" /> Objekt, das den Blob-Inhalt.</span><span class="sxs-lookup"><span data-stu-id="f3327-294">A <see cref="T:System.IO.Stream" /> object providing the blob content.</span></span></param>
        <param name="callback"><span data-ttu-id="f3327-295">Ein <see cref="T:System.AsyncCallback" /> Delegat, der Benachrichtigung erhalten sollen, wenn der asynchrone Vorgang abgeschlossen ist.</span><span class="sxs-lookup"><span data-stu-id="f3327-295">An <see cref="T:System.AsyncCallback" /> delegate that will receive notification when the asynchronous operation completes.</span></span></param>
        <param name="state"><span data-ttu-id="f3327-296">Ein benutzerdefiniertes Objekt, die an dem Rückrufdelegaten übergeben werden.</span><span class="sxs-lookup"><span data-stu-id="f3327-296">A user-defined object that will be passed to the callback delegate.</span></span></param>
        <summary>
            <span data-ttu-id="f3327-297">Startet einen asynchronen Vorgang zum Hochladen eines Datenstroms in ein Block-Blob.</span><span class="sxs-lookup"><span data-stu-id="f3327-297">Begins an asynchronous operation to upload a stream to a block blob.</span></span> <span data-ttu-id="f3327-298">Wenn das Blob bereits vorhanden ist, wird sie überschrieben.</span><span class="sxs-lookup"><span data-stu-id="f3327-298">If the blob already exists, it will be overwritten.</span></span>
            </summary>
        <returns><span data-ttu-id="f3327-299">Ein <see cref="T:Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" /> , das auf den asynchronen Vorgang verweist.</span><span class="sxs-lookup"><span data-stu-id="f3327-299">An <see cref="T:Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" /> that references the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginUploadFromStream">
      <MemberSignature Language="C#" Value="public virtual Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginUploadFromStream (System.IO.Stream source, long length, AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginUploadFromStream(class System.IO.Stream source, int64 length, class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlockBlob.BeginUploadFromStream(System.IO.Stream,System.Int64,System.AsyncCallback,System.Object)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function BeginUploadFromStream (source As Stream, length As Long, callback As AsyncCallback, state As Object) As ICancellableAsyncResult" />
      <MemberSignature Language="F#" Value="abstract member BeginUploadFromStream : System.IO.Stream * int64 * AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult&#xA;override this.BeginUploadFromStream : System.IO.Stream * int64 * AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" Usage="cloudBlockBlob.BeginUploadFromStream (source, length, callback, state)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.WindowsAzure.Storage.Blob.ICloudBlob.BeginUploadFromStream(System.IO.Stream,System.Int64,System.AsyncCallback,System.Object)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.WindowsAzure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Storage.ICancellableAsyncResult</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="source" Type="System.IO.Stream" />
        <Parameter Name="length" Type="System.Int64" />
        <Parameter Name="callback" Type="System.AsyncCallback" />
        <Parameter Name="state" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="source"><span data-ttu-id="f3327-300">Ein <see cref="T:System.IO.Stream" /> Objekt, das den Blob-Inhalt.</span><span class="sxs-lookup"><span data-stu-id="f3327-300">A <see cref="T:System.IO.Stream" /> object providing the blob content.</span></span></param>
        <param name="length"><span data-ttu-id="f3327-301">Die Anzahl der Bytes, die aus dem Quelldatenstrom in seiner derzeitigen Position zu schreiben.</span><span class="sxs-lookup"><span data-stu-id="f3327-301">The number of bytes to write from the source stream at its current position.</span></span></param>
        <param name="callback"><span data-ttu-id="f3327-302">Ein <see cref="T:System.AsyncCallback" /> Delegat, der Benachrichtigung erhalten sollen, wenn der asynchrone Vorgang abgeschlossen ist.</span><span class="sxs-lookup"><span data-stu-id="f3327-302">An <see cref="T:System.AsyncCallback" /> delegate that will receive notification when the asynchronous operation completes.</span></span></param>
        <param name="state"><span data-ttu-id="f3327-303">Ein benutzerdefiniertes Objekt, die an dem Rückrufdelegaten übergeben werden.</span><span class="sxs-lookup"><span data-stu-id="f3327-303">A user-defined object that will be passed to the callback delegate.</span></span></param>
        <summary>
            <span data-ttu-id="f3327-304">Startet einen asynchronen Vorgang zum Hochladen eines Datenstroms in ein Block-Blob.</span><span class="sxs-lookup"><span data-stu-id="f3327-304">Begins an asynchronous operation to upload a stream to a block blob.</span></span> <span data-ttu-id="f3327-305">Wenn das Blob bereits vorhanden ist, wird sie überschrieben.</span><span class="sxs-lookup"><span data-stu-id="f3327-305">If the blob already exists, it will be overwritten.</span></span>
            </summary>
        <returns><span data-ttu-id="f3327-306">Ein <see cref="T:Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" /> , das auf den asynchronen Vorgang verweist.</span><span class="sxs-lookup"><span data-stu-id="f3327-306">An <see cref="T:Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" /> that references the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginUploadFromStream">
      <MemberSignature Language="C#" Value="public virtual Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginUploadFromStream (System.IO.Stream source, Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, Microsoft.WindowsAzure.Storage.OperationContext operationContext, AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginUploadFromStream(class System.IO.Stream source, class Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, class Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, class Microsoft.WindowsAzure.Storage.OperationContext operationContext, class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlockBlob.BeginUploadFromStream(System.IO.Stream,Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext,System.AsyncCallback,System.Object)" />
      <MemberSignature Language="F#" Value="abstract member BeginUploadFromStream : System.IO.Stream * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult&#xA;override this.BeginUploadFromStream : System.IO.Stream * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" Usage="cloudBlockBlob.BeginUploadFromStream (source, accessCondition, options, operationContext, callback, state)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.WindowsAzure.Storage.Blob.ICloudBlob.BeginUploadFromStream(System.IO.Stream,Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext,System.AsyncCallback,System.Object)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.WindowsAzure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Storage.ICancellableAsyncResult</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="source" Type="System.IO.Stream" />
        <Parameter Name="accessCondition" Type="Microsoft.WindowsAzure.Storage.AccessCondition" />
        <Parameter Name="options" Type="Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
        <Parameter Name="callback" Type="System.AsyncCallback" />
        <Parameter Name="state" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="source"><span data-ttu-id="f3327-307">Ein <see cref="T:System.IO.Stream" /> Objekt, das den Blob-Inhalt.</span><span class="sxs-lookup"><span data-stu-id="f3327-307">A <see cref="T:System.IO.Stream" /> object providing the blob content.</span></span></param>
        <param name="accessCondition"><span data-ttu-id="f3327-308">Ein <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> -Objekt, das die Bedingung, die erfüllt sein müssen, damit die Anforderung darstellt, um den Vorgang fortzusetzen.</span><span class="sxs-lookup"><span data-stu-id="f3327-308">An <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> object that represents the condition that must be met in order for the request to proceed.</span></span> <span data-ttu-id="f3327-309">Wenn <c>null</c>, keine Bedingung verwendet.</span><span class="sxs-lookup"><span data-stu-id="f3327-309">If <c>null</c>, no condition is used.</span></span></param>
        <param name="options"><span data-ttu-id="f3327-310">Ein <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" /> -Objekt, das zusätzliche Optionen für die Anforderung angibt.</span><span class="sxs-lookup"><span data-stu-id="f3327-310">A <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" /> object that specifies additional options for the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="f3327-311">Ein <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> -Objekt, das den Kontext für den aktuellen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="f3327-311">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <param name="callback"><span data-ttu-id="f3327-312">Ein <see cref="T:System.AsyncCallback" /> Delegat, der Benachrichtigung erhalten sollen, wenn der asynchrone Vorgang abgeschlossen ist.</span><span class="sxs-lookup"><span data-stu-id="f3327-312">An <see cref="T:System.AsyncCallback" /> delegate that will receive notification when the asynchronous operation completes.</span></span></param>
        <param name="state"><span data-ttu-id="f3327-313">Ein benutzerdefiniertes Objekt, die an dem Rückrufdelegaten übergeben werden.</span><span class="sxs-lookup"><span data-stu-id="f3327-313">A user-defined object that will be passed to the callback delegate.</span></span></param>
        <summary>
            <span data-ttu-id="f3327-314">Startet einen asynchronen Vorgang zum Hochladen eines Datenstroms in ein Block-Blob.</span><span class="sxs-lookup"><span data-stu-id="f3327-314">Begins an asynchronous operation to upload a stream to a block blob.</span></span> <span data-ttu-id="f3327-315">Wenn das Blob bereits vorhanden ist, wird sie überschrieben.</span><span class="sxs-lookup"><span data-stu-id="f3327-315">If the blob already exists, it will be overwritten.</span></span>
            </summary>
        <returns><span data-ttu-id="f3327-316">Ein <see cref="T:Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" /> , das auf den asynchronen Vorgang verweist.</span><span class="sxs-lookup"><span data-stu-id="f3327-316">An <see cref="T:Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" /> that references the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginUploadFromStream">
      <MemberSignature Language="C#" Value="public virtual Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginUploadFromStream (System.IO.Stream source, long length, Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, Microsoft.WindowsAzure.Storage.OperationContext operationContext, AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginUploadFromStream(class System.IO.Stream source, int64 length, class Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, class Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, class Microsoft.WindowsAzure.Storage.OperationContext operationContext, class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlockBlob.BeginUploadFromStream(System.IO.Stream,System.Int64,Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext,System.AsyncCallback,System.Object)" />
      <MemberSignature Language="F#" Value="abstract member BeginUploadFromStream : System.IO.Stream * int64 * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult&#xA;override this.BeginUploadFromStream : System.IO.Stream * int64 * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" Usage="cloudBlockBlob.BeginUploadFromStream (source, length, accessCondition, options, operationContext, callback, state)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.WindowsAzure.Storage.Blob.ICloudBlob.BeginUploadFromStream(System.IO.Stream,System.Int64,Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext,System.AsyncCallback,System.Object)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.WindowsAzure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Storage.ICancellableAsyncResult</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="source" Type="System.IO.Stream" />
        <Parameter Name="length" Type="System.Int64" />
        <Parameter Name="accessCondition" Type="Microsoft.WindowsAzure.Storage.AccessCondition" />
        <Parameter Name="options" Type="Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
        <Parameter Name="callback" Type="System.AsyncCallback" />
        <Parameter Name="state" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="source"><span data-ttu-id="f3327-317">Ein <see cref="T:System.IO.Stream" /> Objekt, das den Blob-Inhalt.</span><span class="sxs-lookup"><span data-stu-id="f3327-317">A <see cref="T:System.IO.Stream" /> object providing the blob content.</span></span></param>
        <param name="length"><span data-ttu-id="f3327-318">Die Anzahl der Bytes, die aus dem Quelldatenstrom in seiner derzeitigen Position zu schreiben.</span><span class="sxs-lookup"><span data-stu-id="f3327-318">The number of bytes to write from the source stream at its current position.</span></span></param>
        <param name="accessCondition"><span data-ttu-id="f3327-319">Ein <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> -Objekt, das die Bedingung, die erfüllt sein müssen, damit die Anforderung darstellt, um den Vorgang fortzusetzen.</span><span class="sxs-lookup"><span data-stu-id="f3327-319">An <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> object that represents the condition that must be met in order for the request to proceed.</span></span> <span data-ttu-id="f3327-320">Wenn <c>null</c>, keine Bedingung verwendet.</span><span class="sxs-lookup"><span data-stu-id="f3327-320">If <c>null</c>, no condition is used.</span></span></param>
        <param name="options"><span data-ttu-id="f3327-321">Ein <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" /> -Objekt, das zusätzliche Optionen für die Anforderung angibt.</span><span class="sxs-lookup"><span data-stu-id="f3327-321">A <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" /> object that specifies additional options for the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="f3327-322">Ein <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> -Objekt, das den Kontext für den aktuellen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="f3327-322">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <param name="callback"><span data-ttu-id="f3327-323">Ein <see cref="T:System.AsyncCallback" /> Delegat, der Benachrichtigung erhalten sollen, wenn der asynchrone Vorgang abgeschlossen ist.</span><span class="sxs-lookup"><span data-stu-id="f3327-323">An <see cref="T:System.AsyncCallback" /> delegate that will receive notification when the asynchronous operation completes.</span></span></param>
        <param name="state"><span data-ttu-id="f3327-324">Ein benutzerdefiniertes Objekt, die an dem Rückrufdelegaten übergeben werden.</span><span class="sxs-lookup"><span data-stu-id="f3327-324">A user-defined object that will be passed to the callback delegate.</span></span></param>
        <summary>
            <span data-ttu-id="f3327-325">Startet einen asynchronen Vorgang zum Hochladen eines Datenstroms in ein Block-Blob.</span><span class="sxs-lookup"><span data-stu-id="f3327-325">Begins an asynchronous operation to upload a stream to a block blob.</span></span> <span data-ttu-id="f3327-326">Wenn das Blob bereits vorhanden ist, wird sie überschrieben.</span><span class="sxs-lookup"><span data-stu-id="f3327-326">If the blob already exists, it will be overwritten.</span></span>
            </summary>
        <returns><span data-ttu-id="f3327-327">Ein <see cref="T:Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" /> , das auf den asynchronen Vorgang verweist.</span><span class="sxs-lookup"><span data-stu-id="f3327-327">An <see cref="T:Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" /> that references the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginUploadText">
      <MemberSignature Language="C#" Value="public virtual Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginUploadText (string content, AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginUploadText(string content, class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlockBlob.BeginUploadText(System.String,System.AsyncCallback,System.Object)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function BeginUploadText (content As String, callback As AsyncCallback, state As Object) As ICancellableAsyncResult" />
      <MemberSignature Language="F#" Value="abstract member BeginUploadText : string * AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult&#xA;override this.BeginUploadText : string * AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" Usage="cloudBlockBlob.BeginUploadText (content, callback, state)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.WindowsAzure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Storage.ICancellableAsyncResult</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="content" Type="System.String" />
        <Parameter Name="callback" Type="System.AsyncCallback" />
        <Parameter Name="state" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="content"><span data-ttu-id="f3327-328">Eine Zeichenfolge, die hochzuladenden Text enthält.</span><span class="sxs-lookup"><span data-stu-id="f3327-328">A string containing the text to upload.</span></span></param>
        <param name="callback"><span data-ttu-id="f3327-329">Ein <see cref="T:System.AsyncCallback" /> Delegat, der Benachrichtigung erhalten sollen, wenn der asynchrone Vorgang abgeschlossen ist.</span><span class="sxs-lookup"><span data-stu-id="f3327-329">An <see cref="T:System.AsyncCallback" /> delegate that will receive notification when the asynchronous operation completes.</span></span></param>
        <param name="state"><span data-ttu-id="f3327-330">Ein benutzerdefiniertes Objekt, die an dem Rückrufdelegaten übergeben werden.</span><span class="sxs-lookup"><span data-stu-id="f3327-330">A user-defined object that will be passed to the callback delegate.</span></span></param>
        <summary>
            <span data-ttu-id="f3327-331">Startet einen asynchronen Vorgang zum Hochladen einer Textzeichenfolge in ein Blob.</span><span class="sxs-lookup"><span data-stu-id="f3327-331">Begins an asynchronous operation to upload a string of text to a blob.</span></span> <span data-ttu-id="f3327-332">Wenn das Blob bereits vorhanden ist, wird sie überschrieben.</span><span class="sxs-lookup"><span data-stu-id="f3327-332">If the blob already exists, it will be overwritten.</span></span>
            </summary>
        <returns><span data-ttu-id="f3327-333">Ein <see cref="T:Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" /> , das auf den asynchronen Vorgang verweist.</span><span class="sxs-lookup"><span data-stu-id="f3327-333">An <see cref="T:Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" /> that references the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginUploadText">
      <MemberSignature Language="C#" Value="public virtual Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginUploadText (string content, System.Text.Encoding encoding, Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, Microsoft.WindowsAzure.Storage.OperationContext operationContext, AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginUploadText(string content, class System.Text.Encoding encoding, class Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, class Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, class Microsoft.WindowsAzure.Storage.OperationContext operationContext, class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlockBlob.BeginUploadText(System.String,System.Text.Encoding,Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext,System.AsyncCallback,System.Object)" />
      <MemberSignature Language="F#" Value="abstract member BeginUploadText : string * System.Text.Encoding * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult&#xA;override this.BeginUploadText : string * System.Text.Encoding * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" Usage="cloudBlockBlob.BeginUploadText (content, encoding, accessCondition, options, operationContext, callback, state)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.WindowsAzure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Storage.ICancellableAsyncResult</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="content" Type="System.String" />
        <Parameter Name="encoding" Type="System.Text.Encoding" />
        <Parameter Name="accessCondition" Type="Microsoft.WindowsAzure.Storage.AccessCondition" />
        <Parameter Name="options" Type="Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
        <Parameter Name="callback" Type="System.AsyncCallback" />
        <Parameter Name="state" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="content"><span data-ttu-id="f3327-334">Eine Zeichenfolge, die hochzuladenden Text enthält.</span><span class="sxs-lookup"><span data-stu-id="f3327-334">A string containing the text to upload.</span></span></param>
        <param name="encoding"><span data-ttu-id="f3327-335">Ein <see cref="T:System.Text.Encoding" /> Objekt, das die um zu verwendende textcodierung angibt.</span><span class="sxs-lookup"><span data-stu-id="f3327-335">A <see cref="T:System.Text.Encoding" /> object that indicates the text encoding to use.</span></span> <span data-ttu-id="f3327-336">Wenn <c>null</c>, UTF-8 verwendet werden.</span><span class="sxs-lookup"><span data-stu-id="f3327-336">If <c>null</c>, UTF-8 will be used.</span></span></param>
        <param name="accessCondition"><span data-ttu-id="f3327-337">Ein <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> -Objekt, das die Bedingung, die erfüllt sein müssen, damit die Anforderung darstellt, um den Vorgang fortzusetzen.</span><span class="sxs-lookup"><span data-stu-id="f3327-337">An <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> object that represents the condition that must be met in order for the request to proceed.</span></span></param>
        <param name="options"><span data-ttu-id="f3327-338">Ein <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" /> -Objekt, das zusätzliche Optionen für die Anforderung angibt.</span><span class="sxs-lookup"><span data-stu-id="f3327-338">A <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" /> object that specifies additional options for the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="f3327-339">Ein <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> -Objekt, das den Kontext für den aktuellen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="f3327-339">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <param name="callback"><span data-ttu-id="f3327-340">Ein <see cref="T:System.AsyncCallback" /> Delegat, der Benachrichtigung erhalten sollen, wenn der asynchrone Vorgang abgeschlossen ist.</span><span class="sxs-lookup"><span data-stu-id="f3327-340">An <see cref="T:System.AsyncCallback" /> delegate that will receive notification when the asynchronous operation completes.</span></span></param>
        <param name="state"><span data-ttu-id="f3327-341">Ein benutzerdefiniertes Objekt, die an dem Rückrufdelegaten übergeben werden.</span><span class="sxs-lookup"><span data-stu-id="f3327-341">A user-defined object that will be passed to the callback delegate.</span></span></param>
        <summary>
            <span data-ttu-id="f3327-342">Startet einen asynchronen Vorgang zum Hochladen einer Textzeichenfolge in ein Blob.</span><span class="sxs-lookup"><span data-stu-id="f3327-342">Begins an asynchronous operation to upload a string of text to a blob.</span></span> <span data-ttu-id="f3327-343">Wenn das Blob bereits vorhanden ist, wird sie überschrieben.</span><span class="sxs-lookup"><span data-stu-id="f3327-343">If the blob already exists, it will be overwritten.</span></span>
            </summary>
        <returns><span data-ttu-id="f3327-344">Ein <see cref="T:Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" /> , das auf den asynchronen Vorgang verweist.</span><span class="sxs-lookup"><span data-stu-id="f3327-344">An <see cref="T:Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" /> that references the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateSnapshot">
      <MemberSignature Language="C#" Value="public virtual Microsoft.WindowsAzure.Storage.Blob.CloudBlockBlob CreateSnapshot (System.Collections.Generic.IDictionary&lt;string,string&gt; metadata = null, Microsoft.WindowsAzure.Storage.AccessCondition accessCondition = null, Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options = null, Microsoft.WindowsAzure.Storage.OperationContext operationContext = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.WindowsAzure.Storage.Blob.CloudBlockBlob CreateSnapshot(class System.Collections.Generic.IDictionary`2&lt;string, string&gt; metadata, class Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, class Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlockBlob.CreateSnapshot(System.Collections.Generic.IDictionary{System.String,System.String},Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="abstract member CreateSnapshot : System.Collections.Generic.IDictionary&lt;string, string&gt; * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; Microsoft.WindowsAzure.Storage.Blob.CloudBlockBlob&#xA;override this.CreateSnapshot : System.Collections.Generic.IDictionary&lt;string, string&gt; * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; Microsoft.WindowsAzure.Storage.Blob.CloudBlockBlob" Usage="cloudBlockBlob.CreateSnapshot (metadata, accessCondition, options, operationContext)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.WindowsAzure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Storage.Blob.CloudBlockBlob</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="metadata" Type="System.Collections.Generic.IDictionary&lt;System.String,System.String&gt;" />
        <Parameter Name="accessCondition" Type="Microsoft.WindowsAzure.Storage.AccessCondition" />
        <Parameter Name="options" Type="Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="metadata"><span data-ttu-id="f3327-345">Eine Auflistung von Name-Wert-Paare definieren die Metadaten der Momentaufnahme.</span><span class="sxs-lookup"><span data-stu-id="f3327-345">A collection of name-value pairs defining the metadata of the snapshot.</span></span></param>
        <param name="accessCondition"><span data-ttu-id="f3327-346">Ein <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> -Objekt, das die Bedingung, die erfüllt sein müssen, damit die Anforderung darstellt, um den Vorgang fortzusetzen.</span><span class="sxs-lookup"><span data-stu-id="f3327-346">An <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> object that represents the condition that must be met in order for the request to proceed.</span></span> <span data-ttu-id="f3327-347">Wenn <c>null</c>, keine Bedingung verwendet.</span><span class="sxs-lookup"><span data-stu-id="f3327-347">If <c>null</c>, no condition is used.</span></span></param>
        <param name="options"><span data-ttu-id="f3327-348">Ein <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" /> -Objekt, das zusätzliche Optionen für die Anforderung angibt oder <c>null</c>.</span><span class="sxs-lookup"><span data-stu-id="f3327-348">A <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" /> object that specifies additional options for the request, or <c>null</c>.</span></span> <span data-ttu-id="f3327-349">Wenn <c>null</c>, Standardoptionen gelten für die Anforderung.</span><span class="sxs-lookup"><span data-stu-id="f3327-349">If <c>null</c>, default options are applied to the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="f3327-350">Ein <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> -Objekt, das den Kontext für den aktuellen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="f3327-350">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <summary>
            <span data-ttu-id="f3327-351">Erstellt eine Momentaufnahme des BLOBs.</span><span class="sxs-lookup"><span data-stu-id="f3327-351">Creates a snapshot of the blob.</span></span>
            </summary>
        <returns><span data-ttu-id="f3327-352">Ein <see cref="T:Microsoft.WindowsAzure.Storage.Blob.CloudBlockBlob" /> -Objekt, das eine Blob-Momentaufnahme ist.</span><span class="sxs-lookup"><span data-stu-id="f3327-352">A <see cref="T:Microsoft.WindowsAzure.Storage.Blob.CloudBlockBlob" /> object that is a blob snapshot.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateSnapshotAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Blob.CloudBlockBlob&gt; CreateSnapshotAsync ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.WindowsAzure.Storage.Blob.CloudBlockBlob&gt; CreateSnapshotAsync() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlockBlob.CreateSnapshotAsync" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function CreateSnapshotAsync () As Task(Of CloudBlockBlob)" />
      <MemberSignature Language="F#" Value="abstract member CreateSnapshotAsync : unit -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Blob.CloudBlockBlob&gt;&#xA;override this.CreateSnapshotAsync : unit -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Blob.CloudBlockBlob&gt;" Usage="cloudBlockBlob.CreateSnapshotAsync " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.WindowsAzure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Blob.CloudBlockBlob&gt;</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="f3327-353">Initiiert einen asynchronen Vorgang zum Erstellen einer Momentaufnahme des BLOBs.</span><span class="sxs-lookup"><span data-stu-id="f3327-353">Initiates an asynchronous operation to create a snapshot of the blob.</span></span>
            </summary>
        <returns><span data-ttu-id="f3327-354">Ein <see cref="T:System.Threading.Tasks.Task`1" /> Objekt des Typs <see cref="T:Microsoft.WindowsAzure.Storage.Blob.CloudBlockBlob" /> , die den asynchronen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="f3327-354">A <see cref="T:System.Threading.Tasks.Task`1" /> object of type <see cref="T:Microsoft.WindowsAzure.Storage.Blob.CloudBlockBlob" /> that represents the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateSnapshotAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Blob.CloudBlockBlob&gt; CreateSnapshotAsync (System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.WindowsAzure.Storage.Blob.CloudBlockBlob&gt; CreateSnapshotAsync(valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlockBlob.CreateSnapshotAsync(System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member CreateSnapshotAsync : System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Blob.CloudBlockBlob&gt;&#xA;override this.CreateSnapshotAsync : System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Blob.CloudBlockBlob&gt;" Usage="cloudBlockBlob.CreateSnapshotAsync cancellationToken" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.WindowsAzure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Blob.CloudBlockBlob&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="cancellationToken"><span data-ttu-id="f3327-355">Ein <see cref="T:System.Threading.CancellationToken" />, das beim Warten auf den Abschluss einer Aufgabe überwacht werden soll.</span><span class="sxs-lookup"><span data-stu-id="f3327-355">A <see cref="T:System.Threading.CancellationToken" /> to observe while waiting for a task to complete.</span></span></param>
        <summary>
            <span data-ttu-id="f3327-356">Initiiert einen asynchronen Vorgang zum Erstellen einer Momentaufnahme des BLOBs.</span><span class="sxs-lookup"><span data-stu-id="f3327-356">Initiates an asynchronous operation to create a snapshot of the blob.</span></span>
            </summary>
        <returns><span data-ttu-id="f3327-357">Ein <see cref="T:System.Threading.Tasks.Task`1" /> Objekt des Typs <see cref="T:Microsoft.WindowsAzure.Storage.Blob.CloudBlockBlob" /> , die den asynchronen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="f3327-357">A <see cref="T:System.Threading.Tasks.Task`1" /> object of type <see cref="T:Microsoft.WindowsAzure.Storage.Blob.CloudBlockBlob" /> that represents the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateSnapshotAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Blob.CloudBlockBlob&gt; CreateSnapshotAsync (System.Collections.Generic.IDictionary&lt;string,string&gt; metadata, Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, Microsoft.WindowsAzure.Storage.OperationContext operationContext);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.WindowsAzure.Storage.Blob.CloudBlockBlob&gt; CreateSnapshotAsync(class System.Collections.Generic.IDictionary`2&lt;string, string&gt; metadata, class Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, class Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlockBlob.CreateSnapshotAsync(System.Collections.Generic.IDictionary{System.String,System.String},Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="abstract member CreateSnapshotAsync : System.Collections.Generic.IDictionary&lt;string, string&gt; * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Blob.CloudBlockBlob&gt;&#xA;override this.CreateSnapshotAsync : System.Collections.Generic.IDictionary&lt;string, string&gt; * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Blob.CloudBlockBlob&gt;" Usage="cloudBlockBlob.CreateSnapshotAsync (metadata, accessCondition, options, operationContext)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.WindowsAzure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Blob.CloudBlockBlob&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="metadata" Type="System.Collections.Generic.IDictionary&lt;System.String,System.String&gt;" />
        <Parameter Name="accessCondition" Type="Microsoft.WindowsAzure.Storage.AccessCondition" />
        <Parameter Name="options" Type="Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="metadata"><span data-ttu-id="f3327-358">Eine Auflistung von Name-Wert-Paare definieren die Metadaten der Momentaufnahme.</span><span class="sxs-lookup"><span data-stu-id="f3327-358">A collection of name-value pairs defining the metadata of the snapshot.</span></span></param>
        <param name="accessCondition"><span data-ttu-id="f3327-359">Ein <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> -Objekt, das die Bedingung, die erfüllt sein müssen, damit die Anforderung darstellt, um den Vorgang fortzusetzen.</span><span class="sxs-lookup"><span data-stu-id="f3327-359">An <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> object that represents the condition that must be met in order for the request to proceed.</span></span> <span data-ttu-id="f3327-360">Wenn <c>null</c>, keine Bedingung verwendet.</span><span class="sxs-lookup"><span data-stu-id="f3327-360">If <c>null</c>, no condition is used.</span></span></param>
        <param name="options"><span data-ttu-id="f3327-361">Ein <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" /> -Objekt, das zusätzliche Optionen für die Anforderung angibt.</span><span class="sxs-lookup"><span data-stu-id="f3327-361">A <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" /> object that specifies additional options for the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="f3327-362">Ein <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> -Objekt, das den Kontext für den aktuellen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="f3327-362">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <summary>
            <span data-ttu-id="f3327-363">Initiiert einen asynchronen Vorgang zum Erstellen einer Momentaufnahme des BLOBs.</span><span class="sxs-lookup"><span data-stu-id="f3327-363">Initiates an asynchronous operation to create a snapshot of the blob.</span></span>
            </summary>
        <returns><span data-ttu-id="f3327-364">Ein <see cref="T:System.Threading.Tasks.Task`1" /> Objekt des Typs <see cref="T:Microsoft.WindowsAzure.Storage.Blob.CloudBlockBlob" /> , die den asynchronen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="f3327-364">A <see cref="T:System.Threading.Tasks.Task`1" /> object of type <see cref="T:Microsoft.WindowsAzure.Storage.Blob.CloudBlockBlob" /> that represents the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateSnapshotAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Blob.CloudBlockBlob&gt; CreateSnapshotAsync (System.Collections.Generic.IDictionary&lt;string,string&gt; metadata, Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, Microsoft.WindowsAzure.Storage.OperationContext operationContext, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.WindowsAzure.Storage.Blob.CloudBlockBlob&gt; CreateSnapshotAsync(class System.Collections.Generic.IDictionary`2&lt;string, string&gt; metadata, class Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, class Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, class Microsoft.WindowsAzure.Storage.OperationContext operationContext, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlockBlob.CreateSnapshotAsync(System.Collections.Generic.IDictionary{System.String,System.String},Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member CreateSnapshotAsync : System.Collections.Generic.IDictionary&lt;string, string&gt; * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Blob.CloudBlockBlob&gt;&#xA;override this.CreateSnapshotAsync : System.Collections.Generic.IDictionary&lt;string, string&gt; * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Blob.CloudBlockBlob&gt;" Usage="cloudBlockBlob.CreateSnapshotAsync (metadata, accessCondition, options, operationContext, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.WindowsAzure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Blob.CloudBlockBlob&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="metadata" Type="System.Collections.Generic.IDictionary&lt;System.String,System.String&gt;" />
        <Parameter Name="accessCondition" Type="Microsoft.WindowsAzure.Storage.AccessCondition" />
        <Parameter Name="options" Type="Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="metadata"><span data-ttu-id="f3327-365">Eine Auflistung von Name-Wert-Paare definieren die Metadaten der Momentaufnahme.</span><span class="sxs-lookup"><span data-stu-id="f3327-365">A collection of name-value pairs defining the metadata of the snapshot.</span></span></param>
        <param name="accessCondition"><span data-ttu-id="f3327-366">Ein <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> -Objekt, das die Bedingung, die erfüllt sein müssen, damit die Anforderung darstellt, um den Vorgang fortzusetzen.</span><span class="sxs-lookup"><span data-stu-id="f3327-366">An <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> object that represents the condition that must be met in order for the request to proceed.</span></span> <span data-ttu-id="f3327-367">Wenn <c>null</c>, keine Bedingung verwendet.</span><span class="sxs-lookup"><span data-stu-id="f3327-367">If <c>null</c>, no condition is used.</span></span></param>
        <param name="options"><span data-ttu-id="f3327-368">Ein <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" /> -Objekt, das zusätzliche Optionen für die Anforderung angibt.</span><span class="sxs-lookup"><span data-stu-id="f3327-368">A <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" /> object that specifies additional options for the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="f3327-369">Ein <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> -Objekt, das den Kontext für den aktuellen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="f3327-369">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="f3327-370">Ein <see cref="T:System.Threading.CancellationToken" />, das beim Warten auf den Abschluss einer Aufgabe überwacht werden soll.</span><span class="sxs-lookup"><span data-stu-id="f3327-370">A <see cref="T:System.Threading.CancellationToken" /> to observe while waiting for a task to complete.</span></span></param>
        <summary>
            <span data-ttu-id="f3327-371">Initiiert einen asynchronen Vorgang zum Erstellen einer Momentaufnahme des BLOBs.</span><span class="sxs-lookup"><span data-stu-id="f3327-371">Initiates an asynchronous operation to create a snapshot of the blob.</span></span>
            </summary>
        <returns><span data-ttu-id="f3327-372">Ein <see cref="T:System.Threading.Tasks.Task`1" /> Objekt des Typs <see cref="T:Microsoft.WindowsAzure.Storage.Blob.CloudBlockBlob" /> , die den asynchronen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="f3327-372">A <see cref="T:System.Threading.Tasks.Task`1" /> object of type <see cref="T:Microsoft.WindowsAzure.Storage.Blob.CloudBlockBlob" /> that represents the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DownloadBlockList">
      <MemberSignature Language="C#" Value="public virtual System.Collections.Generic.IEnumerable&lt;Microsoft.WindowsAzure.Storage.Blob.ListBlockItem&gt; DownloadBlockList (Microsoft.WindowsAzure.Storage.Blob.BlockListingFilter blockListingFilter = Microsoft.WindowsAzure.Storage.Blob.BlockListingFilter.Committed, Microsoft.WindowsAzure.Storage.AccessCondition accessCondition = null, Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options = null, Microsoft.WindowsAzure.Storage.OperationContext operationContext = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.WindowsAzure.Storage.Blob.ListBlockItem&gt; DownloadBlockList(valuetype Microsoft.WindowsAzure.Storage.Blob.BlockListingFilter blockListingFilter, class Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, class Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlockBlob.DownloadBlockList(Microsoft.WindowsAzure.Storage.Blob.BlockListingFilter,Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="abstract member DownloadBlockList : Microsoft.WindowsAzure.Storage.Blob.BlockListingFilter * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; seq&lt;Microsoft.WindowsAzure.Storage.Blob.ListBlockItem&gt;&#xA;override this.DownloadBlockList : Microsoft.WindowsAzure.Storage.Blob.BlockListingFilter * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; seq&lt;Microsoft.WindowsAzure.Storage.Blob.ListBlockItem&gt;" Usage="cloudBlockBlob.DownloadBlockList (blockListingFilter, accessCondition, options, operationContext)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.WindowsAzure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IEnumerable&lt;Microsoft.WindowsAzure.Storage.Blob.ListBlockItem&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="blockListingFilter" Type="Microsoft.WindowsAzure.Storage.Blob.BlockListingFilter" />
        <Parameter Name="accessCondition" Type="Microsoft.WindowsAzure.Storage.AccessCondition" />
        <Parameter Name="options" Type="Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="blockListingFilter"><span data-ttu-id="f3327-373">Ein <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlockListingFilter" /> -Enumerationswert ab, der angibt, ob Blöcke mit ausgeführtem Commit, Blöcke oder beides zurück.</span><span class="sxs-lookup"><span data-stu-id="f3327-373">A <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlockListingFilter" /> enumeration value that indicates whether to return committed blocks, uncommitted blocks, or both.</span></span></param>
        <param name="accessCondition"><span data-ttu-id="f3327-374">Ein <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> -Objekt, das die Bedingung, die erfüllt sein müssen, damit die Anforderung darstellt, um den Vorgang fortzusetzen.</span><span class="sxs-lookup"><span data-stu-id="f3327-374">An <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> object that represents the condition that must be met in order for the request to proceed.</span></span> <span data-ttu-id="f3327-375">Wenn <c>null</c>, keine Bedingung verwendet.</span><span class="sxs-lookup"><span data-stu-id="f3327-375">If <c>null</c>, no condition is used.</span></span></param>
        <param name="options"><span data-ttu-id="f3327-376">Ein <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" /> -Objekt, das zusätzliche Optionen für die Anforderung angibt.</span><span class="sxs-lookup"><span data-stu-id="f3327-376">A <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" /> object that specifies additional options for the request.</span></span> <span data-ttu-id="f3327-377">Wenn <c>null</c>, Standardoptionen gelten für die Anforderung.</span><span class="sxs-lookup"><span data-stu-id="f3327-377">If <c>null</c>, default options are applied to the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="f3327-378">Ein <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> -Objekt, das den Kontext für den aktuellen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="f3327-378">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <summary>
            <span data-ttu-id="f3327-379">Gibt eine aufzählbare Auflistung der Blöcke des BLOBs, mithilfe des angegebenen blocklistenfilters zurück.</span><span class="sxs-lookup"><span data-stu-id="f3327-379">Returns an enumerable collection of the blob's blocks, using the specified block list filter.</span></span>
            </summary>
        <returns><span data-ttu-id="f3327-380">Eine aufzählbare Auflistung von Objekten implementieren <see cref="T:Microsoft.WindowsAzure.Storage.Blob.ListBlockItem" />.</span><span class="sxs-lookup"><span data-stu-id="f3327-380">An enumerable collection of objects implementing <see cref="T:Microsoft.WindowsAzure.Storage.Blob.ListBlockItem" />.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DownloadBlockListAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.WindowsAzure.Storage.Blob.ListBlockItem&gt;&gt; DownloadBlockListAsync ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.WindowsAzure.Storage.Blob.ListBlockItem&gt;&gt; DownloadBlockListAsync() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlockBlob.DownloadBlockListAsync" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function DownloadBlockListAsync () As Task(Of IEnumerable(Of ListBlockItem))" />
      <MemberSignature Language="F#" Value="abstract member DownloadBlockListAsync : unit -&gt; System.Threading.Tasks.Task&lt;seq&lt;Microsoft.WindowsAzure.Storage.Blob.ListBlockItem&gt;&gt;&#xA;override this.DownloadBlockListAsync : unit -&gt; System.Threading.Tasks.Task&lt;seq&lt;Microsoft.WindowsAzure.Storage.Blob.ListBlockItem&gt;&gt;" Usage="cloudBlockBlob.DownloadBlockListAsync " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.WindowsAzure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.WindowsAzure.Storage.Blob.ListBlockItem&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="f3327-381">Initiiert einen asynchronen Vorgang, um eine aufzählbare Auflistung der Blöcke des BLOBs, mithilfe des angegebenen blocklistenfilters zurückzugeben.</span><span class="sxs-lookup"><span data-stu-id="f3327-381">Initiates an asynchronous operation to return an enumerable collection of the blob's blocks, using the specified block list filter.</span></span>
            </summary>
        <returns><span data-ttu-id="f3327-382">Ein <see cref="T:System.Threading.Tasks.Task`1" /> Objekt, das eine aufzählbare Auflistung von Typ <see cref="T:Microsoft.WindowsAzure.Storage.Blob.ListBlockItem" /> , die den asynchronen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="f3327-382">A <see cref="T:System.Threading.Tasks.Task`1" /> object that is an enumerable collection of type <see cref="T:Microsoft.WindowsAzure.Storage.Blob.ListBlockItem" /> that represents the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DownloadBlockListAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.WindowsAzure.Storage.Blob.ListBlockItem&gt;&gt; DownloadBlockListAsync (System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.WindowsAzure.Storage.Blob.ListBlockItem&gt;&gt; DownloadBlockListAsync(valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlockBlob.DownloadBlockListAsync(System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member DownloadBlockListAsync : System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;seq&lt;Microsoft.WindowsAzure.Storage.Blob.ListBlockItem&gt;&gt;&#xA;override this.DownloadBlockListAsync : System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;seq&lt;Microsoft.WindowsAzure.Storage.Blob.ListBlockItem&gt;&gt;" Usage="cloudBlockBlob.DownloadBlockListAsync cancellationToken" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.WindowsAzure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.WindowsAzure.Storage.Blob.ListBlockItem&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="cancellationToken"><span data-ttu-id="f3327-383">Ein <see cref="T:System.Threading.CancellationToken" />, das beim Warten auf den Abschluss einer Aufgabe überwacht werden soll.</span><span class="sxs-lookup"><span data-stu-id="f3327-383">A <see cref="T:System.Threading.CancellationToken" /> to observe while waiting for a task to complete.</span></span></param>
        <summary>
            <span data-ttu-id="f3327-384">Initiiert einen asynchronen Vorgang, um eine aufzählbare Auflistung der Blöcke des BLOBs, mithilfe des angegebenen blocklistenfilters zurückzugeben.</span><span class="sxs-lookup"><span data-stu-id="f3327-384">Initiates an asynchronous operation to return an enumerable collection of the blob's blocks, using the specified block list filter.</span></span>
            </summary>
        <returns><span data-ttu-id="f3327-385">Ein <see cref="T:System.Threading.Tasks.Task`1" /> Objekt, das eine aufzählbare Auflistung von Typ <see cref="T:Microsoft.WindowsAzure.Storage.Blob.ListBlockItem" /> , die den asynchronen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="f3327-385">A <see cref="T:System.Threading.Tasks.Task`1" /> object that is an enumerable collection of type <see cref="T:Microsoft.WindowsAzure.Storage.Blob.ListBlockItem" /> that represents the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DownloadBlockListAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.WindowsAzure.Storage.Blob.ListBlockItem&gt;&gt; DownloadBlockListAsync (Microsoft.WindowsAzure.Storage.Blob.BlockListingFilter blockListingFilter, Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, Microsoft.WindowsAzure.Storage.OperationContext operationContext);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.WindowsAzure.Storage.Blob.ListBlockItem&gt;&gt; DownloadBlockListAsync(valuetype Microsoft.WindowsAzure.Storage.Blob.BlockListingFilter blockListingFilter, class Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, class Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlockBlob.DownloadBlockListAsync(Microsoft.WindowsAzure.Storage.Blob.BlockListingFilter,Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="abstract member DownloadBlockListAsync : Microsoft.WindowsAzure.Storage.Blob.BlockListingFilter * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Threading.Tasks.Task&lt;seq&lt;Microsoft.WindowsAzure.Storage.Blob.ListBlockItem&gt;&gt;&#xA;override this.DownloadBlockListAsync : Microsoft.WindowsAzure.Storage.Blob.BlockListingFilter * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Threading.Tasks.Task&lt;seq&lt;Microsoft.WindowsAzure.Storage.Blob.ListBlockItem&gt;&gt;" Usage="cloudBlockBlob.DownloadBlockListAsync (blockListingFilter, accessCondition, options, operationContext)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.WindowsAzure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.WindowsAzure.Storage.Blob.ListBlockItem&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="blockListingFilter" Type="Microsoft.WindowsAzure.Storage.Blob.BlockListingFilter" />
        <Parameter Name="accessCondition" Type="Microsoft.WindowsAzure.Storage.AccessCondition" />
        <Parameter Name="options" Type="Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="blockListingFilter"><span data-ttu-id="f3327-386">Ein <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlockListingFilter" /> -Enumerationswert ab, der angibt, ob Blöcke mit ausgeführtem Commit, Blöcke oder beides zurück.</span><span class="sxs-lookup"><span data-stu-id="f3327-386">A <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlockListingFilter" /> enumeration value that indicates whether to return committed blocks, uncommitted blocks, or both.</span></span></param>
        <param name="accessCondition"><span data-ttu-id="f3327-387">Ein <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> -Objekt, das die Bedingung, die erfüllt sein müssen, damit die Anforderung darstellt, um den Vorgang fortzusetzen.</span><span class="sxs-lookup"><span data-stu-id="f3327-387">An <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> object that represents the condition that must be met in order for the request to proceed.</span></span> <span data-ttu-id="f3327-388">Wenn <c>null</c>, keine Bedingung verwendet.</span><span class="sxs-lookup"><span data-stu-id="f3327-388">If <c>null</c>, no condition is used.</span></span></param>
        <param name="options"><span data-ttu-id="f3327-389">Ein <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" /> -Objekt, das zusätzliche Optionen für die Anforderung angibt.</span><span class="sxs-lookup"><span data-stu-id="f3327-389">A <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" /> object that specifies additional options for the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="f3327-390">Ein <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> -Objekt, das den Kontext für den aktuellen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="f3327-390">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <summary>
            <span data-ttu-id="f3327-391">Initiiert einen asynchronen Vorgang, um eine aufzählbare Auflistung der Blöcke des BLOBs, mithilfe des angegebenen blocklistenfilters zurückzugeben.</span><span class="sxs-lookup"><span data-stu-id="f3327-391">Initiates an asynchronous operation to return an enumerable collection of the blob's blocks, using the specified block list filter.</span></span>
            </summary>
        <returns><span data-ttu-id="f3327-392">Ein <see cref="T:System.Threading.Tasks.Task`1" /> Objekt, das eine aufzählbare Auflistung von Typ <see cref="T:Microsoft.WindowsAzure.Storage.Blob.ListBlockItem" /> , die den asynchronen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="f3327-392">A <see cref="T:System.Threading.Tasks.Task`1" /> object that is an enumerable collection of type <see cref="T:Microsoft.WindowsAzure.Storage.Blob.ListBlockItem" /> that represents the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DownloadBlockListAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.WindowsAzure.Storage.Blob.ListBlockItem&gt;&gt; DownloadBlockListAsync (Microsoft.WindowsAzure.Storage.Blob.BlockListingFilter blockListingFilter, Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, Microsoft.WindowsAzure.Storage.OperationContext operationContext, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.WindowsAzure.Storage.Blob.ListBlockItem&gt;&gt; DownloadBlockListAsync(valuetype Microsoft.WindowsAzure.Storage.Blob.BlockListingFilter blockListingFilter, class Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, class Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, class Microsoft.WindowsAzure.Storage.OperationContext operationContext, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlockBlob.DownloadBlockListAsync(Microsoft.WindowsAzure.Storage.Blob.BlockListingFilter,Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member DownloadBlockListAsync : Microsoft.WindowsAzure.Storage.Blob.BlockListingFilter * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;seq&lt;Microsoft.WindowsAzure.Storage.Blob.ListBlockItem&gt;&gt;&#xA;override this.DownloadBlockListAsync : Microsoft.WindowsAzure.Storage.Blob.BlockListingFilter * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;seq&lt;Microsoft.WindowsAzure.Storage.Blob.ListBlockItem&gt;&gt;" Usage="cloudBlockBlob.DownloadBlockListAsync (blockListingFilter, accessCondition, options, operationContext, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.WindowsAzure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.WindowsAzure.Storage.Blob.ListBlockItem&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="blockListingFilter" Type="Microsoft.WindowsAzure.Storage.Blob.BlockListingFilter" />
        <Parameter Name="accessCondition" Type="Microsoft.WindowsAzure.Storage.AccessCondition" />
        <Parameter Name="options" Type="Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="blockListingFilter"><span data-ttu-id="f3327-393">Ein <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlockListingFilter" /> -Enumerationswert ab, der angibt, ob Blöcke mit ausgeführtem Commit, Blöcke oder beides zurück.</span><span class="sxs-lookup"><span data-stu-id="f3327-393">A <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlockListingFilter" /> enumeration value that indicates whether to return committed blocks, uncommitted blocks, or both.</span></span></param>
        <param name="accessCondition"><span data-ttu-id="f3327-394">Ein <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> -Objekt, das die Bedingung, die erfüllt sein müssen, damit die Anforderung darstellt, um den Vorgang fortzusetzen.</span><span class="sxs-lookup"><span data-stu-id="f3327-394">An <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> object that represents the condition that must be met in order for the request to proceed.</span></span> <span data-ttu-id="f3327-395">Wenn <c>null</c>, keine Bedingung verwendet.</span><span class="sxs-lookup"><span data-stu-id="f3327-395">If <c>null</c>, no condition is used.</span></span></param>
        <param name="options"><span data-ttu-id="f3327-396">Ein <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" /> -Objekt, das zusätzliche Optionen für die Anforderung angibt.</span><span class="sxs-lookup"><span data-stu-id="f3327-396">A <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" /> object that specifies additional options for the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="f3327-397">Ein <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> -Objekt, das den Kontext für den aktuellen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="f3327-397">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="f3327-398">Ein <see cref="T:System.Threading.CancellationToken" />, das beim Warten auf den Abschluss einer Aufgabe überwacht werden soll.</span><span class="sxs-lookup"><span data-stu-id="f3327-398">A <see cref="T:System.Threading.CancellationToken" /> to observe while waiting for a task to complete.</span></span></param>
        <summary>
            <span data-ttu-id="f3327-399">Initiiert einen asynchronen Vorgang, um eine aufzählbare Auflistung der Blöcke des BLOBs, mithilfe des angegebenen blocklistenfilters zurückzugeben.</span><span class="sxs-lookup"><span data-stu-id="f3327-399">Initiates an asynchronous operation to return an enumerable collection of the blob's blocks, using the specified block list filter.</span></span>
            </summary>
        <returns><span data-ttu-id="f3327-400">Ein <see cref="T:System.Threading.Tasks.Task`1" /> Objekt, das eine aufzählbare Auflistung von Typ <see cref="T:Microsoft.WindowsAzure.Storage.Blob.ListBlockItem" /> , die den asynchronen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="f3327-400">A <see cref="T:System.Threading.Tasks.Task`1" /> object that is an enumerable collection of type <see cref="T:Microsoft.WindowsAzure.Storage.Blob.ListBlockItem" /> that represents the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DownloadText">
      <MemberSignature Language="C#" Value="public virtual string DownloadText (System.Text.Encoding encoding = null, Microsoft.WindowsAzure.Storage.AccessCondition accessCondition = null, Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options = null, Microsoft.WindowsAzure.Storage.OperationContext operationContext = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance string DownloadText(class System.Text.Encoding encoding, class Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, class Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlockBlob.DownloadText(System.Text.Encoding,Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="abstract member DownloadText : System.Text.Encoding * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; string&#xA;override this.DownloadText : System.Text.Encoding * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; string" Usage="cloudBlockBlob.DownloadText (encoding, accessCondition, options, operationContext)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.WindowsAzure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="encoding" Type="System.Text.Encoding" />
        <Parameter Name="accessCondition" Type="Microsoft.WindowsAzure.Storage.AccessCondition" />
        <Parameter Name="options" Type="Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="encoding"><span data-ttu-id="f3327-401">Ein Objekt, das um zu verwendende textcodierung angibt.</span><span class="sxs-lookup"><span data-stu-id="f3327-401">An object that indicates the text encoding to use.</span></span></param>
        <param name="accessCondition"><span data-ttu-id="f3327-402">Ein <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> -Objekt, das die Bedingung, die erfüllt sein müssen, damit die Anforderung darstellt, um den Vorgang fortzusetzen.</span><span class="sxs-lookup"><span data-stu-id="f3327-402">An <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> object that represents the condition that must be met in order for the request to proceed.</span></span></param>
        <param name="options"><span data-ttu-id="f3327-403">Ein <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" /> -Objekt, das zusätzliche Optionen für die Anforderung angibt.</span><span class="sxs-lookup"><span data-stu-id="f3327-403">A <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" /> object that specifies additional options for the request.</span></span> <span data-ttu-id="f3327-404">Wenn <c>null</c>, Standardoptionen gelten für die Anforderung.</span><span class="sxs-lookup"><span data-stu-id="f3327-404">If <c>null</c>, default options are applied to the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="f3327-405">Ein <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> -Objekt, das den Kontext für den aktuellen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="f3327-405">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <summary>
            <span data-ttu-id="f3327-406">Lädt den Inhalt des BLOBs als Zeichenfolge herunter.</span><span class="sxs-lookup"><span data-stu-id="f3327-406">Downloads the blob's contents as a string.</span></span>
            </summary>
        <returns><span data-ttu-id="f3327-407">Der Inhalt des BLOBs als Zeichenfolge.</span><span class="sxs-lookup"><span data-stu-id="f3327-407">The contents of the blob, as a string.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DownloadTextAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task&lt;string&gt; DownloadTextAsync ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;string&gt; DownloadTextAsync() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlockBlob.DownloadTextAsync" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function DownloadTextAsync () As Task(Of String)" />
      <MemberSignature Language="F#" Value="abstract member DownloadTextAsync : unit -&gt; System.Threading.Tasks.Task&lt;string&gt;&#xA;override this.DownloadTextAsync : unit -&gt; System.Threading.Tasks.Task&lt;string&gt;" Usage="cloudBlockBlob.DownloadTextAsync " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.WindowsAzure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.String&gt;</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="f3327-408">Initiiert einen asynchronen Vorgang, um den Inhalt des BLOBs als Zeichenfolge herunterzuladen.</span><span class="sxs-lookup"><span data-stu-id="f3327-408">Initiates an asynchronous operation to download the blob's contents as a string.</span></span>
            </summary>
        <returns><span data-ttu-id="f3327-409">Ein <see cref="T:System.Threading.Tasks.Task`1" /> Objekt des Typs <c>Zeichenfolge</c> , die den asynchronen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="f3327-409">A <see cref="T:System.Threading.Tasks.Task`1" /> object of type <c>string</c> that represents the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DownloadTextAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task&lt;string&gt; DownloadTextAsync (System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;string&gt; DownloadTextAsync(valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlockBlob.DownloadTextAsync(System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member DownloadTextAsync : System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;string&gt;&#xA;override this.DownloadTextAsync : System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;string&gt;" Usage="cloudBlockBlob.DownloadTextAsync cancellationToken" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.WindowsAzure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.String&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="cancellationToken"><span data-ttu-id="f3327-410">Ein <see cref="T:System.Threading.CancellationToken" />, das beim Warten auf den Abschluss einer Aufgabe überwacht werden soll.</span><span class="sxs-lookup"><span data-stu-id="f3327-410">A <see cref="T:System.Threading.CancellationToken" /> to observe while waiting for a task to complete.</span></span></param>
        <summary>
            <span data-ttu-id="f3327-411">Initiiert einen asynchronen Vorgang, um den Inhalt des BLOBs als Zeichenfolge herunterzuladen.</span><span class="sxs-lookup"><span data-stu-id="f3327-411">Initiates an asynchronous operation to download the blob's contents as a string.</span></span>
            </summary>
        <returns><span data-ttu-id="f3327-412">Ein <see cref="T:System.Threading.Tasks.Task`1" /> Objekt des Typs <c>Zeichenfolge</c> , die den asynchronen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="f3327-412">A <see cref="T:System.Threading.Tasks.Task`1" /> object of type <c>string</c> that represents the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DownloadTextAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task&lt;string&gt; DownloadTextAsync (System.Text.Encoding encoding, Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, Microsoft.WindowsAzure.Storage.OperationContext operationContext);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;string&gt; DownloadTextAsync(class System.Text.Encoding encoding, class Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, class Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlockBlob.DownloadTextAsync(System.Text.Encoding,Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="abstract member DownloadTextAsync : System.Text.Encoding * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Threading.Tasks.Task&lt;string&gt;&#xA;override this.DownloadTextAsync : System.Text.Encoding * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Threading.Tasks.Task&lt;string&gt;" Usage="cloudBlockBlob.DownloadTextAsync (encoding, accessCondition, options, operationContext)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.WindowsAzure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.String&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="encoding" Type="System.Text.Encoding" />
        <Parameter Name="accessCondition" Type="Microsoft.WindowsAzure.Storage.AccessCondition" />
        <Parameter Name="options" Type="Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="encoding"><span data-ttu-id="f3327-413">Ein Objekt, das um zu verwendende textcodierung angibt.</span><span class="sxs-lookup"><span data-stu-id="f3327-413">An object that indicates the text encoding to use.</span></span></param>
        <param name="accessCondition"><span data-ttu-id="f3327-414">Ein <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> -Objekt, das die Bedingung, die erfüllt sein müssen, damit die Anforderung darstellt, um den Vorgang fortzusetzen.</span><span class="sxs-lookup"><span data-stu-id="f3327-414">An <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> object that represents the condition that must be met in order for the request to proceed.</span></span></param>
        <param name="options"><span data-ttu-id="f3327-415">Ein <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" /> -Objekt, das zusätzliche Optionen für die Anforderung angibt.</span><span class="sxs-lookup"><span data-stu-id="f3327-415">A <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" /> object that specifies additional options for the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="f3327-416">Ein <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> -Objekt, das den Kontext für den aktuellen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="f3327-416">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <summary>
            <span data-ttu-id="f3327-417">Initiiert einen asynchronen Vorgang, um den Inhalt des BLOBs als Zeichenfolge herunterzuladen.</span><span class="sxs-lookup"><span data-stu-id="f3327-417">Initiates an asynchronous operation to download the blob's contents as a string.</span></span>
            </summary>
        <returns><span data-ttu-id="f3327-418">Ein <see cref="T:System.Threading.Tasks.Task`1" /> Objekt des Typs <c>Zeichenfolge</c> , die den asynchronen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="f3327-418">A <see cref="T:System.Threading.Tasks.Task`1" /> object of type <c>string</c> that represents the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DownloadTextAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task&lt;string&gt; DownloadTextAsync (System.Text.Encoding encoding, Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, Microsoft.WindowsAzure.Storage.OperationContext operationContext, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;string&gt; DownloadTextAsync(class System.Text.Encoding encoding, class Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, class Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, class Microsoft.WindowsAzure.Storage.OperationContext operationContext, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlockBlob.DownloadTextAsync(System.Text.Encoding,Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member DownloadTextAsync : System.Text.Encoding * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;string&gt;&#xA;override this.DownloadTextAsync : System.Text.Encoding * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;string&gt;" Usage="cloudBlockBlob.DownloadTextAsync (encoding, accessCondition, options, operationContext, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.WindowsAzure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.String&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="encoding" Type="System.Text.Encoding" />
        <Parameter Name="accessCondition" Type="Microsoft.WindowsAzure.Storage.AccessCondition" />
        <Parameter Name="options" Type="Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="encoding"><span data-ttu-id="f3327-419">Ein Objekt, das um zu verwendende textcodierung angibt.</span><span class="sxs-lookup"><span data-stu-id="f3327-419">An object that indicates the text encoding to use.</span></span></param>
        <param name="accessCondition"><span data-ttu-id="f3327-420">Ein <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> -Objekt, das die Bedingung, die erfüllt sein müssen, damit die Anforderung darstellt, um den Vorgang fortzusetzen.</span><span class="sxs-lookup"><span data-stu-id="f3327-420">An <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> object that represents the condition that must be met in order for the request to proceed.</span></span></param>
        <param name="options"><span data-ttu-id="f3327-421">Ein <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" /> -Objekt, das zusätzliche Optionen für die Anforderung angibt.</span><span class="sxs-lookup"><span data-stu-id="f3327-421">A <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" /> object that specifies additional options for the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="f3327-422">Ein <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> -Objekt, das den Kontext für den aktuellen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="f3327-422">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="f3327-423">Ein <see cref="T:System.Threading.CancellationToken" />, das beim Warten auf den Abschluss einer Aufgabe überwacht werden soll.</span><span class="sxs-lookup"><span data-stu-id="f3327-423">A <see cref="T:System.Threading.CancellationToken" /> to observe while waiting for a task to complete.</span></span></param>
        <summary>
            <span data-ttu-id="f3327-424">Initiiert einen asynchronen Vorgang, um den Inhalt des BLOBs als Zeichenfolge herunterzuladen.</span><span class="sxs-lookup"><span data-stu-id="f3327-424">Initiates an asynchronous operation to download the blob's contents as a string.</span></span>
            </summary>
        <returns><span data-ttu-id="f3327-425">Ein <see cref="T:System.Threading.Tasks.Task`1" /> Objekt des Typs <c>Zeichenfolge</c> , die den asynchronen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="f3327-425">A <see cref="T:System.Threading.Tasks.Task`1" /> object of type <c>string</c> that represents the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DownloadTextAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task&lt;string&gt; DownloadTextAsync (System.Text.Encoding encoding, Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, Microsoft.WindowsAzure.Storage.OperationContext operationContext, IProgress&lt;Microsoft.WindowsAzure.Storage.Core.Util.StorageProgress&gt; progressHandler, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;string&gt; DownloadTextAsync(class System.Text.Encoding encoding, class Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, class Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, class Microsoft.WindowsAzure.Storage.OperationContext operationContext, class System.IProgress`1&lt;class Microsoft.WindowsAzure.Storage.Core.Util.StorageProgress&gt; progressHandler, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlockBlob.DownloadTextAsync(System.Text.Encoding,Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext,System.IProgress{Microsoft.WindowsAzure.Storage.Core.Util.StorageProgress},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member DownloadTextAsync : System.Text.Encoding * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * IProgress&lt;Microsoft.WindowsAzure.Storage.Core.Util.StorageProgress&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;string&gt;&#xA;override this.DownloadTextAsync : System.Text.Encoding * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * IProgress&lt;Microsoft.WindowsAzure.Storage.Core.Util.StorageProgress&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;string&gt;" Usage="cloudBlockBlob.DownloadTextAsync (encoding, accessCondition, options, operationContext, progressHandler, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.WindowsAzure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.String&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="encoding" Type="System.Text.Encoding" />
        <Parameter Name="accessCondition" Type="Microsoft.WindowsAzure.Storage.AccessCondition" />
        <Parameter Name="options" Type="Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
        <Parameter Name="progressHandler" Type="System.IProgress&lt;Microsoft.WindowsAzure.Storage.Core.Util.StorageProgress&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="encoding"><span data-ttu-id="f3327-426">Ein Objekt, das um zu verwendende textcodierung angibt.</span><span class="sxs-lookup"><span data-stu-id="f3327-426">An object that indicates the text encoding to use.</span></span></param>
        <param name="accessCondition"><span data-ttu-id="f3327-427">Ein <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> -Objekt, das die Bedingung, die erfüllt sein müssen, damit die Anforderung darstellt, um den Vorgang fortzusetzen.</span><span class="sxs-lookup"><span data-stu-id="f3327-427">An <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> object that represents the condition that must be met in order for the request to proceed.</span></span></param>
        <param name="options"><span data-ttu-id="f3327-428">Ein <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" /> -Objekt, das zusätzliche Optionen für die Anforderung angibt.</span><span class="sxs-lookup"><span data-stu-id="f3327-428">A <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" /> object that specifies additional options for the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="f3327-429">Ein <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> -Objekt, das den Kontext für den aktuellen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="f3327-429">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <param name="progressHandler"> <span data-ttu-id="f3327-430">Ein <see cref="T:System.IProgress`1" /> Objekt behandelt <see cref="T:Microsoft.WindowsAzure.Storage.Core.Util.StorageProgress" /> Nachrichten.</span><span class="sxs-lookup"><span data-stu-id="f3327-430">A <see cref="T:System.IProgress`1" /> object to handle <see cref="T:Microsoft.WindowsAzure.Storage.Core.Util.StorageProgress" /> messages.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="f3327-431">Ein <see cref="T:System.Threading.CancellationToken" />, das beim Warten auf den Abschluss einer Aufgabe überwacht werden soll.</span><span class="sxs-lookup"><span data-stu-id="f3327-431">A <see cref="T:System.Threading.CancellationToken" /> to observe while waiting for a task to complete.</span></span></param>
        <summary>
            <span data-ttu-id="f3327-432">Initiiert einen asynchronen Vorgang, um den Inhalt des BLOBs als Zeichenfolge herunterzuladen.</span><span class="sxs-lookup"><span data-stu-id="f3327-432">Initiates an asynchronous operation to download the blob's contents as a string.</span></span>
            </summary>
        <returns><span data-ttu-id="f3327-433">Ein <see cref="T:System.Threading.Tasks.Task`1" /> Objekt des Typs <c>Zeichenfolge</c> , die den asynchronen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="f3327-433">A <see cref="T:System.Threading.Tasks.Task`1" /> object of type <c>string</c> that represents the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EndCreateSnapshot">
      <MemberSignature Language="C#" Value="public virtual Microsoft.WindowsAzure.Storage.Blob.CloudBlockBlob EndCreateSnapshot (IAsyncResult asyncResult);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.WindowsAzure.Storage.Blob.CloudBlockBlob EndCreateSnapshot(class System.IAsyncResult asyncResult) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlockBlob.EndCreateSnapshot(System.IAsyncResult)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function EndCreateSnapshot (asyncResult As IAsyncResult) As CloudBlockBlob" />
      <MemberSignature Language="F#" Value="abstract member EndCreateSnapshot : IAsyncResult -&gt; Microsoft.WindowsAzure.Storage.Blob.CloudBlockBlob&#xA;override this.EndCreateSnapshot : IAsyncResult -&gt; Microsoft.WindowsAzure.Storage.Blob.CloudBlockBlob" Usage="cloudBlockBlob.EndCreateSnapshot asyncResult" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Storage.Blob.CloudBlockBlob</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="asyncResult" Type="System.IAsyncResult" />
      </Parameters>
      <Docs>
        <param name="asyncResult"><span data-ttu-id="f3327-434">Eine <see cref="T:System.IAsyncResult" /> , die auf den ausstehenden asynchronen Vorgang verweist.</span><span class="sxs-lookup"><span data-stu-id="f3327-434">An <see cref="T:System.IAsyncResult" /> that references the pending asynchronous operation.</span></span></param>
        <summary>
            <span data-ttu-id="f3327-435">Beendet einen asynchronen Vorgang zum Erstellen einer Momentaufnahme des BLOBs.</span><span class="sxs-lookup"><span data-stu-id="f3327-435">Ends an asynchronous operation to create a snapshot of the blob.</span></span>
            </summary>
        <returns><span data-ttu-id="f3327-436">Ein <see cref="T:Microsoft.WindowsAzure.Storage.Blob.CloudBlockBlob" /> -Objekt, das eine Blob-Momentaufnahme ist.</span><span class="sxs-lookup"><span data-stu-id="f3327-436">A <see cref="T:Microsoft.WindowsAzure.Storage.Blob.CloudBlockBlob" /> object that is a blob snapshot.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EndDownloadBlockList">
      <MemberSignature Language="C#" Value="public virtual System.Collections.Generic.IEnumerable&lt;Microsoft.WindowsAzure.Storage.Blob.ListBlockItem&gt; EndDownloadBlockList (IAsyncResult asyncResult);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.WindowsAzure.Storage.Blob.ListBlockItem&gt; EndDownloadBlockList(class System.IAsyncResult asyncResult) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlockBlob.EndDownloadBlockList(System.IAsyncResult)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function EndDownloadBlockList (asyncResult As IAsyncResult) As IEnumerable(Of ListBlockItem)" />
      <MemberSignature Language="F#" Value="abstract member EndDownloadBlockList : IAsyncResult -&gt; seq&lt;Microsoft.WindowsAzure.Storage.Blob.ListBlockItem&gt;&#xA;override this.EndDownloadBlockList : IAsyncResult -&gt; seq&lt;Microsoft.WindowsAzure.Storage.Blob.ListBlockItem&gt;" Usage="cloudBlockBlob.EndDownloadBlockList asyncResult" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IEnumerable&lt;Microsoft.WindowsAzure.Storage.Blob.ListBlockItem&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="asyncResult" Type="System.IAsyncResult" />
      </Parameters>
      <Docs>
        <param name="asyncResult"><span data-ttu-id="f3327-437">Eine <see cref="T:System.IAsyncResult" /> , die auf den ausstehenden asynchronen Vorgang verweist.</span><span class="sxs-lookup"><span data-stu-id="f3327-437">An <see cref="T:System.IAsyncResult" /> that references the pending asynchronous operation.</span></span></param>
        <summary>
            <span data-ttu-id="f3327-438">Beendet einen asynchronen Vorgang, um eine aufzählbare Auflistung der Blöcke des BLOBs, mithilfe des angegebenen blocklistenfilters zurückzugeben.</span><span class="sxs-lookup"><span data-stu-id="f3327-438">Ends an asynchronous operation to return an enumerable collection of the blob's blocks, using the specified block list filter.</span></span>
            </summary>
        <returns><span data-ttu-id="f3327-439">Eine aufzählbare Auflistung von Objekten implementieren <see cref="T:Microsoft.WindowsAzure.Storage.Blob.ListBlockItem" />.</span><span class="sxs-lookup"><span data-stu-id="f3327-439">An enumerable collection of objects implementing <see cref="T:Microsoft.WindowsAzure.Storage.Blob.ListBlockItem" />.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EndDownloadText">
      <MemberSignature Language="C#" Value="public virtual string EndDownloadText (IAsyncResult asyncResult);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance string EndDownloadText(class System.IAsyncResult asyncResult) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlockBlob.EndDownloadText(System.IAsyncResult)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function EndDownloadText (asyncResult As IAsyncResult) As String" />
      <MemberSignature Language="F#" Value="abstract member EndDownloadText : IAsyncResult -&gt; string&#xA;override this.EndDownloadText : IAsyncResult -&gt; string" Usage="cloudBlockBlob.EndDownloadText asyncResult" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="asyncResult" Type="System.IAsyncResult" />
      </Parameters>
      <Docs>
        <param name="asyncResult"><span data-ttu-id="f3327-440">Eine <see cref="T:System.IAsyncResult" /> , die auf den ausstehenden asynchronen Vorgang verweist.</span><span class="sxs-lookup"><span data-stu-id="f3327-440">An <see cref="T:System.IAsyncResult" /> that references the pending asynchronous operation.</span></span></param>
        <summary>
            <span data-ttu-id="f3327-441">Beendet einen asynchronen Vorgang, um den Inhalt des BLOBs als Zeichenfolge herunterzuladen.</span><span class="sxs-lookup"><span data-stu-id="f3327-441">Ends an asynchronous operation to download the blob's contents as a string.</span></span>
            </summary>
        <returns><span data-ttu-id="f3327-442">Der Inhalt des BLOBs als Zeichenfolge.</span><span class="sxs-lookup"><span data-stu-id="f3327-442">The contents of the blob, as a string.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EndOpenWrite">
      <MemberSignature Language="C#" Value="public virtual Microsoft.WindowsAzure.Storage.Blob.CloudBlobStream EndOpenWrite (IAsyncResult asyncResult);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.WindowsAzure.Storage.Blob.CloudBlobStream EndOpenWrite(class System.IAsyncResult asyncResult) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlockBlob.EndOpenWrite(System.IAsyncResult)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function EndOpenWrite (asyncResult As IAsyncResult) As CloudBlobStream" />
      <MemberSignature Language="F#" Value="abstract member EndOpenWrite : IAsyncResult -&gt; Microsoft.WindowsAzure.Storage.Blob.CloudBlobStream&#xA;override this.EndOpenWrite : IAsyncResult -&gt; Microsoft.WindowsAzure.Storage.Blob.CloudBlobStream" Usage="cloudBlockBlob.EndOpenWrite asyncResult" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Storage.Blob.CloudBlobStream</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="asyncResult" Type="System.IAsyncResult" />
      </Parameters>
      <Docs>
        <param name="asyncResult"><span data-ttu-id="f3327-443">Eine <see cref="T:System.IAsyncResult" /> , die auf den ausstehenden asynchronen Vorgang verweist.</span><span class="sxs-lookup"><span data-stu-id="f3327-443">An <see cref="T:System.IAsyncResult" /> that references the pending asynchronous operation.</span></span></param>
        <summary>
            <span data-ttu-id="f3327-444">Beendet einen asynchronen Vorgang zum Öffnen eines Datenstroms zum Schreiben in das Blob.</span><span class="sxs-lookup"><span data-stu-id="f3327-444">Ends an asynchronous operation to open a stream for writing to the blob.</span></span>
            </summary>
        <returns><span data-ttu-id="f3327-445">Ein <see cref="T:Microsoft.WindowsAzure.Storage.Blob.CloudBlobStream" /> zum Schreiben in den Blob verwendet werden soll.</span><span class="sxs-lookup"><span data-stu-id="f3327-445">A <see cref="T:Microsoft.WindowsAzure.Storage.Blob.CloudBlobStream" /> to be used for writing to the blob.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EndPutBlock">
      <MemberSignature Language="C#" Value="public virtual void EndPutBlock (IAsyncResult asyncResult);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void EndPutBlock(class System.IAsyncResult asyncResult) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlockBlob.EndPutBlock(System.IAsyncResult)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub EndPutBlock (asyncResult As IAsyncResult)" />
      <MemberSignature Language="F#" Value="abstract member EndPutBlock : IAsyncResult -&gt; unit&#xA;override this.EndPutBlock : IAsyncResult -&gt; unit" Usage="cloudBlockBlob.EndPutBlock asyncResult" />
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
        <param name="asyncResult"><span data-ttu-id="f3327-446">Eine <see cref="T:System.IAsyncResult" /> , die auf den ausstehenden asynchronen Vorgang verweist.</span><span class="sxs-lookup"><span data-stu-id="f3327-446">An <see cref="T:System.IAsyncResult" /> that references the pending asynchronous operation.</span></span></param>
        <summary>
            <span data-ttu-id="f3327-447">Beendet einen asynchronen Vorgang zum Hochladen eines einzelnen Blocks.</span><span class="sxs-lookup"><span data-stu-id="f3327-447">Ends an asynchronous operation to upload a single block.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EndPutBlockList">
      <MemberSignature Language="C#" Value="public virtual void EndPutBlockList (IAsyncResult asyncResult);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void EndPutBlockList(class System.IAsyncResult asyncResult) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlockBlob.EndPutBlockList(System.IAsyncResult)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub EndPutBlockList (asyncResult As IAsyncResult)" />
      <MemberSignature Language="F#" Value="abstract member EndPutBlockList : IAsyncResult -&gt; unit&#xA;override this.EndPutBlockList : IAsyncResult -&gt; unit" Usage="cloudBlockBlob.EndPutBlockList asyncResult" />
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
        <param name="asyncResult"><span data-ttu-id="f3327-448">Eine <see cref="T:System.IAsyncResult" /> , die auf den ausstehenden asynchronen Vorgang verweist.</span><span class="sxs-lookup"><span data-stu-id="f3327-448">An <see cref="T:System.IAsyncResult" /> that references the pending asynchronous operation.</span></span></param>
        <summary>
            <span data-ttu-id="f3327-449">Beendet einen asynchronen Vorgang zum Hochladen einer Liste von Blöcken in ein neues oder vorhandenes Blob.</span><span class="sxs-lookup"><span data-stu-id="f3327-449">Ends an asynchronous operation to upload a list of blocks to a new or existing blob.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EndSetStandardBlobTier">
      <MemberSignature Language="C#" Value="public virtual void EndSetStandardBlobTier (IAsyncResult asyncResult);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void EndSetStandardBlobTier(class System.IAsyncResult asyncResult) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlockBlob.EndSetStandardBlobTier(System.IAsyncResult)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub EndSetStandardBlobTier (asyncResult As IAsyncResult)" />
      <MemberSignature Language="F#" Value="abstract member EndSetStandardBlobTier : IAsyncResult -&gt; unit&#xA;override this.EndSetStandardBlobTier : IAsyncResult -&gt; unit" Usage="cloudBlockBlob.EndSetStandardBlobTier asyncResult" />
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
        <param name="asyncResult"><span data-ttu-id="f3327-450">Eine <see cref="T:System.IAsyncResult" /> , die auf den ausstehenden asynchronen Vorgang verweist.</span><span class="sxs-lookup"><span data-stu-id="f3327-450">An <see cref="T:System.IAsyncResult" /> that references the pending asynchronous operation.</span></span></param>
        <summary>
            <span data-ttu-id="f3327-451">Beendet einen asynchronen Vorgang zum Festlegen der Ebene des BLOBs auf einen standard-Speicherkonto an.</span><span class="sxs-lookup"><span data-stu-id="f3327-451">Ends an asynchronous operation to set the tier of the blob on a standard storage account.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EndUploadFromByteArray">
      <MemberSignature Language="C#" Value="public virtual void EndUploadFromByteArray (IAsyncResult asyncResult);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void EndUploadFromByteArray(class System.IAsyncResult asyncResult) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlockBlob.EndUploadFromByteArray(System.IAsyncResult)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub EndUploadFromByteArray (asyncResult As IAsyncResult)" />
      <MemberSignature Language="F#" Value="abstract member EndUploadFromByteArray : IAsyncResult -&gt; unit&#xA;override this.EndUploadFromByteArray : IAsyncResult -&gt; unit" Usage="cloudBlockBlob.EndUploadFromByteArray asyncResult" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.WindowsAzure.Storage.Blob.ICloudBlob.EndUploadFromByteArray(System.IAsyncResult)</InterfaceMember>
      </Implements>
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
        <param name="asyncResult"><span data-ttu-id="f3327-452">Eine <see cref="T:System.IAsyncResult" /> , die auf den ausstehenden asynchronen Vorgang verweist.</span><span class="sxs-lookup"><span data-stu-id="f3327-452">An <see cref="T:System.IAsyncResult" /> that references the pending asynchronous operation.</span></span></param>
        <summary>
            <span data-ttu-id="f3327-453">Beendet einen asynchronen Vorgang, um den Inhalt eines Bytearrays in ein Blob hochladen.</span><span class="sxs-lookup"><span data-stu-id="f3327-453">Ends an asynchronous operation to upload the contents of a byte array to a blob.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EndUploadFromFile">
      <MemberSignature Language="C#" Value="public virtual void EndUploadFromFile (IAsyncResult asyncResult);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void EndUploadFromFile(class System.IAsyncResult asyncResult) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlockBlob.EndUploadFromFile(System.IAsyncResult)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub EndUploadFromFile (asyncResult As IAsyncResult)" />
      <MemberSignature Language="F#" Value="abstract member EndUploadFromFile : IAsyncResult -&gt; unit&#xA;override this.EndUploadFromFile : IAsyncResult -&gt; unit" Usage="cloudBlockBlob.EndUploadFromFile asyncResult" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.WindowsAzure.Storage.Blob.ICloudBlob.EndUploadFromFile(System.IAsyncResult)</InterfaceMember>
      </Implements>
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
        <param name="asyncResult"><span data-ttu-id="f3327-454">Eine <see cref="T:System.IAsyncResult" /> , die auf den ausstehenden asynchronen Vorgang verweist.</span><span class="sxs-lookup"><span data-stu-id="f3327-454">An <see cref="T:System.IAsyncResult" /> that references the pending asynchronous operation.</span></span></param>
        <summary>
            <span data-ttu-id="f3327-455">Beendet einen asynchronen Vorgang zum Hochladen einer Datei in ein Blob.</span><span class="sxs-lookup"><span data-stu-id="f3327-455">Ends an asynchronous operation to upload a file to a blob.</span></span> 
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EndUploadFromStream">
      <MemberSignature Language="C#" Value="public virtual void EndUploadFromStream (IAsyncResult asyncResult);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void EndUploadFromStream(class System.IAsyncResult asyncResult) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlockBlob.EndUploadFromStream(System.IAsyncResult)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub EndUploadFromStream (asyncResult As IAsyncResult)" />
      <MemberSignature Language="F#" Value="abstract member EndUploadFromStream : IAsyncResult -&gt; unit&#xA;override this.EndUploadFromStream : IAsyncResult -&gt; unit" Usage="cloudBlockBlob.EndUploadFromStream asyncResult" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.WindowsAzure.Storage.Blob.ICloudBlob.EndUploadFromStream(System.IAsyncResult)</InterfaceMember>
      </Implements>
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
        <param name="asyncResult"><span data-ttu-id="f3327-456">Eine <see cref="T:System.IAsyncResult" /> , die auf den ausstehenden asynchronen Vorgang verweist.</span><span class="sxs-lookup"><span data-stu-id="f3327-456">An <see cref="T:System.IAsyncResult" /> that references the pending asynchronous operation.</span></span></param>
        <summary>
            <span data-ttu-id="f3327-457">Beendet einen asynchronen Vorgang zum Hochladen eines Datenstroms in ein Block-Blob.</span><span class="sxs-lookup"><span data-stu-id="f3327-457">Ends an asynchronous operation to upload a stream to a block blob.</span></span> 
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EndUploadText">
      <MemberSignature Language="C#" Value="public virtual void EndUploadText (IAsyncResult asyncResult);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void EndUploadText(class System.IAsyncResult asyncResult) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlockBlob.EndUploadText(System.IAsyncResult)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub EndUploadText (asyncResult As IAsyncResult)" />
      <MemberSignature Language="F#" Value="abstract member EndUploadText : IAsyncResult -&gt; unit&#xA;override this.EndUploadText : IAsyncResult -&gt; unit" Usage="cloudBlockBlob.EndUploadText asyncResult" />
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
        <param name="asyncResult"><span data-ttu-id="f3327-458">Eine <see cref="T:System.IAsyncResult" /> , die auf den ausstehenden asynchronen Vorgang verweist.</span><span class="sxs-lookup"><span data-stu-id="f3327-458">An <see cref="T:System.IAsyncResult" /> that references the pending asynchronous operation.</span></span></param>
        <summary>
            <span data-ttu-id="f3327-459">Beendet einen asynchronen Vorgang zum Hochladen einer Textzeichenfolge in ein Blob.</span><span class="sxs-lookup"><span data-stu-id="f3327-459">Ends an asynchronous operation to upload a string of text to a blob.</span></span> 
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OpenWrite">
      <MemberSignature Language="C#" Value="public virtual Microsoft.WindowsAzure.Storage.Blob.CloudBlobStream OpenWrite (Microsoft.WindowsAzure.Storage.AccessCondition accessCondition = null, Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options = null, Microsoft.WindowsAzure.Storage.OperationContext operationContext = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.WindowsAzure.Storage.Blob.CloudBlobStream OpenWrite(class Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, class Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlockBlob.OpenWrite(Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="abstract member OpenWrite : Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; Microsoft.WindowsAzure.Storage.Blob.CloudBlobStream&#xA;override this.OpenWrite : Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; Microsoft.WindowsAzure.Storage.Blob.CloudBlobStream" Usage="cloudBlockBlob.OpenWrite (accessCondition, options, operationContext)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.WindowsAzure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Storage.Blob.CloudBlobStream</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="accessCondition" Type="Microsoft.WindowsAzure.Storage.AccessCondition" />
        <Parameter Name="options" Type="Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="accessCondition"><span data-ttu-id="f3327-460">Ein <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> -Objekt, das die Bedingung, die erfüllt sein müssen, damit die Anforderung darstellt, um den Vorgang fortzusetzen.</span><span class="sxs-lookup"><span data-stu-id="f3327-460">An <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> object that represents the condition that must be met in order for the request to proceed.</span></span> <span data-ttu-id="f3327-461">Wenn <c>null</c>, keine Bedingung verwendet.</span><span class="sxs-lookup"><span data-stu-id="f3327-461">If <c>null</c>, no condition is used.</span></span></param>
        <param name="options"><span data-ttu-id="f3327-462">Ein <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" /> -Objekt, das zusätzliche Optionen für die Anforderung angibt.</span><span class="sxs-lookup"><span data-stu-id="f3327-462">A <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" /> object that specifies additional options for the request.</span></span> <span data-ttu-id="f3327-463">Wenn <c>null</c>, Standardoptionen gelten für die Anforderung.</span><span class="sxs-lookup"><span data-stu-id="f3327-463">If <c>null</c>, default options are applied to the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="f3327-464">Ein <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> -Objekt, das den Kontext für den aktuellen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="f3327-464">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <summary>
            <span data-ttu-id="f3327-465">Öffnet einen Stream zum Schreiben in das Blob.</span><span class="sxs-lookup"><span data-stu-id="f3327-465">Opens a stream for writing to the blob.</span></span> <span data-ttu-id="f3327-466">Wenn das Blob bereits vorhanden ist, wird sie überschrieben.</span><span class="sxs-lookup"><span data-stu-id="f3327-466">If the blob already exists, it will be overwritten.</span></span>
            </summary>
        <returns><span data-ttu-id="f3327-467">Ein <see cref="T:Microsoft.WindowsAzure.Storage.Blob.CloudBlobStream" /> zum Schreiben in den Blob verwendet werden soll.</span><span class="sxs-lookup"><span data-stu-id="f3327-467">A <see cref="T:Microsoft.WindowsAzure.Storage.Blob.CloudBlobStream" /> to be used for writing to the blob.</span></span></returns>
        <remarks>
          <para><span data-ttu-id="f3327-468">Beachten Sie, dass diese Methode immer einen Aufruf an sendet die <see cref="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlob.FetchAttributes(Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext)" /> Methode im Hintergrund.</span><span class="sxs-lookup"><span data-stu-id="f3327-468">Note that this method always makes a call to the <see cref="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlob.FetchAttributes(Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext)" /> method under the covers.</span></span></para>
          <para><span data-ttu-id="f3327-469">Legen Sie die <see cref="P:Microsoft.WindowsAzure.Storage.Blob.CloudBlockBlob.StreamWriteSizeInBytes" /> Eigenschaft vor dem Aufrufen dieser Methode, um anzugeben, die Blockgröße in Bytes von 16 KB bis 100 MB inklusive zu schreiben.</span><span class="sxs-lookup"><span data-stu-id="f3327-469">Set the <see cref="P:Microsoft.WindowsAzure.Storage.Blob.CloudBlockBlob.StreamWriteSizeInBytes" /> property before calling this method to specify the block size to write, in bytes, ranging from between 16 KB and 100 MB inclusive.</span></span></para>
          <para><span data-ttu-id="f3327-470">Um eine Ausnahme auslösen, wenn das Blob vorhanden ist, anstatt ihn zu überschreiben, übergeben Sie ein <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> Objekt mit generiert <see cref="M:Microsoft.WindowsAzure.Storage.AccessCondition.GenerateIfNotExistsCondition" />.</span><span class="sxs-lookup"><span data-stu-id="f3327-470">To throw an exception if the blob exists instead of overwriting it, pass in an <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> object generated using <see cref="M:Microsoft.WindowsAzure.Storage.AccessCondition.GenerateIfNotExistsCondition" />.</span></span></para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="OpenWriteAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Blob.CloudBlobStream&gt; OpenWriteAsync ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.WindowsAzure.Storage.Blob.CloudBlobStream&gt; OpenWriteAsync() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlockBlob.OpenWriteAsync" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function OpenWriteAsync () As Task(Of CloudBlobStream)" />
      <MemberSignature Language="F#" Value="abstract member OpenWriteAsync : unit -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Blob.CloudBlobStream&gt;&#xA;override this.OpenWriteAsync : unit -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Blob.CloudBlobStream&gt;" Usage="cloudBlockBlob.OpenWriteAsync " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.WindowsAzure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Blob.CloudBlobStream&gt;</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="f3327-471">Initiiert einen asynchronen Vorgang zum Öffnen eines Datenstroms zum Schreiben in das Blob.</span><span class="sxs-lookup"><span data-stu-id="f3327-471">Initiates an asynchronous operation to open a stream for writing to the blob.</span></span> <span data-ttu-id="f3327-472">Wenn das Blob bereits vorhanden ist, wird sie überschrieben.</span><span class="sxs-lookup"><span data-stu-id="f3327-472">If the blob already exists, it will be overwritten.</span></span>
            </summary>
        <returns><span data-ttu-id="f3327-473">Ein <see cref="T:System.Threading.Tasks.Task`1" /> Objekt des Typs <see cref="T:Microsoft.WindowsAzure.Storage.Blob.CloudBlobStream" /> , die den asynchronen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="f3327-473">A <see cref="T:System.Threading.Tasks.Task`1" /> object of type <see cref="T:Microsoft.WindowsAzure.Storage.Blob.CloudBlobStream" /> that represents the asynchronous operation.</span></span></returns>
        <remarks>
          <para><span data-ttu-id="f3327-474">Beachten Sie, dass diese Methode immer einen Aufruf an sendet die <see cref="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlob.FetchAttributesAsync(Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext,System.Threading.CancellationToken)" /> Methode im Hintergrund.</span><span class="sxs-lookup"><span data-stu-id="f3327-474">Note that this method always makes a call to the <see cref="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlob.FetchAttributesAsync(Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext,System.Threading.CancellationToken)" /> method under the covers.</span></span></para>
          <para><span data-ttu-id="f3327-475">Legen Sie die <see cref="P:Microsoft.WindowsAzure.Storage.Blob.CloudBlockBlob.StreamWriteSizeInBytes" /> Eigenschaft vor dem Aufrufen dieser Methode, um anzugeben, die Blockgröße in Bytes von 16 KB bis 100 MB inklusive zu schreiben.</span><span class="sxs-lookup"><span data-stu-id="f3327-475">Set the <see cref="P:Microsoft.WindowsAzure.Storage.Blob.CloudBlockBlob.StreamWriteSizeInBytes" /> property before calling this method to specify the block size to write, in bytes, ranging from between 16 KB and 100 MB inclusive.</span></span></para>
          <para><span data-ttu-id="f3327-476">Um eine Ausnahme auslösen, wenn das Blob vorhanden ist, anstatt ihn zu überschreiben, finden Sie unter <see cref="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlockBlob.OpenWriteAsync(Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext)" />.</span><span class="sxs-lookup"><span data-stu-id="f3327-476">To throw an exception if the blob exists instead of overwriting it, see <see cref="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlockBlob.OpenWriteAsync(Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext)" />.</span></span></para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="OpenWriteAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Blob.CloudBlobStream&gt; OpenWriteAsync (System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.WindowsAzure.Storage.Blob.CloudBlobStream&gt; OpenWriteAsync(valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlockBlob.OpenWriteAsync(System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member OpenWriteAsync : System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Blob.CloudBlobStream&gt;&#xA;override this.OpenWriteAsync : System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Blob.CloudBlobStream&gt;" Usage="cloudBlockBlob.OpenWriteAsync cancellationToken" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.WindowsAzure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Blob.CloudBlobStream&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="cancellationToken"><span data-ttu-id="f3327-477">Ein <see cref="T:System.Threading.CancellationToken" />, das beim Warten auf den Abschluss einer Aufgabe überwacht werden soll.</span><span class="sxs-lookup"><span data-stu-id="f3327-477">A <see cref="T:System.Threading.CancellationToken" /> to observe while waiting for a task to complete.</span></span></param>
        <summary>
            <span data-ttu-id="f3327-478">Initiiert einen asynchronen Vorgang zum Öffnen eines Datenstroms zum Schreiben in das Blob.</span><span class="sxs-lookup"><span data-stu-id="f3327-478">Initiates an asynchronous operation to open a stream for writing to the blob.</span></span> <span data-ttu-id="f3327-479">Wenn das Blob bereits vorhanden ist, wird sie überschrieben.</span><span class="sxs-lookup"><span data-stu-id="f3327-479">If the blob already exists, it will be overwritten.</span></span>
            </summary>
        <returns><span data-ttu-id="f3327-480">Ein <see cref="T:System.Threading.Tasks.Task`1" /> Objekt des Typs <see cref="T:Microsoft.WindowsAzure.Storage.Blob.CloudBlobStream" /> , die den asynchronen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="f3327-480">A <see cref="T:System.Threading.Tasks.Task`1" /> object of type <see cref="T:Microsoft.WindowsAzure.Storage.Blob.CloudBlobStream" /> that represents the asynchronous operation.</span></span></returns>
        <remarks>
          <para><span data-ttu-id="f3327-481">Beachten Sie, dass diese Methode immer einen Aufruf an sendet die <see cref="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlob.FetchAttributesAsync(Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext,System.Threading.CancellationToken)" /> Methode im Hintergrund.</span><span class="sxs-lookup"><span data-stu-id="f3327-481">Note that this method always makes a call to the <see cref="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlob.FetchAttributesAsync(Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext,System.Threading.CancellationToken)" /> method under the covers.</span></span></para>
          <para><span data-ttu-id="f3327-482">Legen Sie die <see cref="P:Microsoft.WindowsAzure.Storage.Blob.CloudBlockBlob.StreamWriteSizeInBytes" /> Eigenschaft vor dem Aufrufen dieser Methode, um anzugeben, die Blockgröße in Bytes von 16 KB bis 100 MB inklusive zu schreiben.</span><span class="sxs-lookup"><span data-stu-id="f3327-482">Set the <see cref="P:Microsoft.WindowsAzure.Storage.Blob.CloudBlockBlob.StreamWriteSizeInBytes" /> property before calling this method to specify the block size to write, in bytes, ranging from between 16 KB and 100 MB inclusive.</span></span></para>
          <para><span data-ttu-id="f3327-483">Um eine Ausnahme auslösen, wenn das Blob vorhanden ist, anstatt ihn zu überschreiben, finden Sie unter <see cref="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlockBlob.OpenWriteAsync(Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext,System.Threading.CancellationToken)" />.</span><span class="sxs-lookup"><span data-stu-id="f3327-483">To throw an exception if the blob exists instead of overwriting it, see <see cref="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlockBlob.OpenWriteAsync(Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext,System.Threading.CancellationToken)" />.</span></span></para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="OpenWriteAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Blob.CloudBlobStream&gt; OpenWriteAsync (Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, Microsoft.WindowsAzure.Storage.OperationContext operationContext);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.WindowsAzure.Storage.Blob.CloudBlobStream&gt; OpenWriteAsync(class Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, class Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlockBlob.OpenWriteAsync(Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="abstract member OpenWriteAsync : Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Blob.CloudBlobStream&gt;&#xA;override this.OpenWriteAsync : Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Blob.CloudBlobStream&gt;" Usage="cloudBlockBlob.OpenWriteAsync (accessCondition, options, operationContext)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.WindowsAzure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Blob.CloudBlobStream&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="accessCondition" Type="Microsoft.WindowsAzure.Storage.AccessCondition" />
        <Parameter Name="options" Type="Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="accessCondition"><span data-ttu-id="f3327-484">Ein <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> -Objekt, das die Bedingung, die erfüllt sein müssen, damit die Anforderung darstellt, um den Vorgang fortzusetzen.</span><span class="sxs-lookup"><span data-stu-id="f3327-484">An <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> object that represents the condition that must be met in order for the request to proceed.</span></span> <span data-ttu-id="f3327-485">Wenn <c>null</c>, keine Bedingung verwendet.</span><span class="sxs-lookup"><span data-stu-id="f3327-485">If <c>null</c>, no condition is used.</span></span></param>
        <param name="options"><span data-ttu-id="f3327-486">Ein <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" /> -Objekt, das zusätzliche Optionen für die Anforderung angibt.</span><span class="sxs-lookup"><span data-stu-id="f3327-486">A <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" /> object that specifies additional options for the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="f3327-487">Ein <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> -Objekt, das den Kontext für den aktuellen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="f3327-487">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <summary>
            <span data-ttu-id="f3327-488">Initiiert einen asynchronen Vorgang zum Öffnen eines Datenstroms zum Schreiben in das Blob.</span><span class="sxs-lookup"><span data-stu-id="f3327-488">Initiates an asynchronous operation to open a stream for writing to the blob.</span></span> <span data-ttu-id="f3327-489">Wenn das Blob bereits vorhanden ist, wird sie überschrieben.</span><span class="sxs-lookup"><span data-stu-id="f3327-489">If the blob already exists, it will be overwritten.</span></span>
            </summary>
        <returns><span data-ttu-id="f3327-490">Ein <see cref="T:System.Threading.Tasks.Task`1" /> Objekt des Typs <see cref="T:Microsoft.WindowsAzure.Storage.Blob.CloudBlobStream" /> , die den asynchronen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="f3327-490">A <see cref="T:System.Threading.Tasks.Task`1" /> object of type <see cref="T:Microsoft.WindowsAzure.Storage.Blob.CloudBlobStream" /> that represents the asynchronous operation.</span></span></returns>
        <remarks>
          <para><span data-ttu-id="f3327-491">Beachten Sie, dass diese Methode immer einen Aufruf an sendet die <see cref="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlob.FetchAttributesAsync(Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext,System.Threading.CancellationToken)" /> Methode im Hintergrund.</span><span class="sxs-lookup"><span data-stu-id="f3327-491">Note that this method always makes a call to the <see cref="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlob.FetchAttributesAsync(Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext,System.Threading.CancellationToken)" /> method under the covers.</span></span></para>
          <para><span data-ttu-id="f3327-492">Legen Sie die <see cref="P:Microsoft.WindowsAzure.Storage.Blob.CloudBlockBlob.StreamWriteSizeInBytes" /> Eigenschaft vor dem Aufrufen dieser Methode, um anzugeben, die Blockgröße in Bytes von 16 KB bis 100 MB inklusive zu schreiben.</span><span class="sxs-lookup"><span data-stu-id="f3327-492">Set the <see cref="P:Microsoft.WindowsAzure.Storage.Blob.CloudBlockBlob.StreamWriteSizeInBytes" /> property before calling this method to specify the block size to write, in bytes, ranging from between 16 KB and 100 MB inclusive.</span></span></para>
          <para><span data-ttu-id="f3327-493">Um eine Ausnahme auslösen, wenn das Blob vorhanden ist, anstatt ihn zu überschreiben, übergeben Sie ein <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> Objekt mit generiert <see cref="M:Microsoft.WindowsAzure.Storage.AccessCondition.GenerateIfNotExistsCondition" />.</span><span class="sxs-lookup"><span data-stu-id="f3327-493">To throw an exception if the blob exists instead of overwriting it, pass in an <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> object generated using <see cref="M:Microsoft.WindowsAzure.Storage.AccessCondition.GenerateIfNotExistsCondition" />.</span></span></para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="OpenWriteAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Blob.CloudBlobStream&gt; OpenWriteAsync (Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, Microsoft.WindowsAzure.Storage.OperationContext operationContext, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.WindowsAzure.Storage.Blob.CloudBlobStream&gt; OpenWriteAsync(class Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, class Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, class Microsoft.WindowsAzure.Storage.OperationContext operationContext, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlockBlob.OpenWriteAsync(Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member OpenWriteAsync : Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Blob.CloudBlobStream&gt;&#xA;override this.OpenWriteAsync : Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Blob.CloudBlobStream&gt;" Usage="cloudBlockBlob.OpenWriteAsync (accessCondition, options, operationContext, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.WindowsAzure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Blob.CloudBlobStream&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="accessCondition" Type="Microsoft.WindowsAzure.Storage.AccessCondition" />
        <Parameter Name="options" Type="Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="accessCondition"><span data-ttu-id="f3327-494">Ein <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> -Objekt, das die Bedingung, die erfüllt sein müssen, damit die Anforderung darstellt, um den Vorgang fortzusetzen.</span><span class="sxs-lookup"><span data-stu-id="f3327-494">An <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> object that represents the condition that must be met in order for the request to proceed.</span></span> <span data-ttu-id="f3327-495">Wenn <c>null</c>, keine Bedingung verwendet.</span><span class="sxs-lookup"><span data-stu-id="f3327-495">If <c>null</c>, no condition is used.</span></span></param>
        <param name="options"><span data-ttu-id="f3327-496">Ein <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" /> -Objekt, das zusätzliche Optionen für die Anforderung angibt.</span><span class="sxs-lookup"><span data-stu-id="f3327-496">A <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" /> object that specifies additional options for the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="f3327-497">Ein <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> -Objekt, das den Kontext für den aktuellen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="f3327-497">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="f3327-498">Ein <see cref="T:System.Threading.CancellationToken" />, das beim Warten auf den Abschluss einer Aufgabe überwacht werden soll.</span><span class="sxs-lookup"><span data-stu-id="f3327-498">A <see cref="T:System.Threading.CancellationToken" /> to observe while waiting for a task to complete.</span></span></param>
        <summary>
            <span data-ttu-id="f3327-499">Initiiert einen asynchronen Vorgang zum Öffnen eines Datenstroms zum Schreiben in das Blob.</span><span class="sxs-lookup"><span data-stu-id="f3327-499">Initiates an asynchronous operation to open a stream for writing to the blob.</span></span> <span data-ttu-id="f3327-500">Wenn das Blob bereits vorhanden ist, wird sie überschrieben.</span><span class="sxs-lookup"><span data-stu-id="f3327-500">If the blob already exists, it will be overwritten.</span></span>
            </summary>
        <returns><span data-ttu-id="f3327-501">Ein <see cref="T:System.Threading.Tasks.Task`1" /> Objekt des Typs <see cref="T:Microsoft.WindowsAzure.Storage.Blob.CloudBlobStream" /> , die den asynchronen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="f3327-501">A <see cref="T:System.Threading.Tasks.Task`1" /> object of type <see cref="T:Microsoft.WindowsAzure.Storage.Blob.CloudBlobStream" /> that represents the asynchronous operation.</span></span></returns>
        <remarks>
          <para><span data-ttu-id="f3327-502">Beachten Sie, dass diese Methode immer einen Aufruf an sendet die <see cref="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlob.FetchAttributesAsync(Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext,System.Threading.CancellationToken)" /> Methode im Hintergrund.</span><span class="sxs-lookup"><span data-stu-id="f3327-502">Note that this method always makes a call to the <see cref="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlob.FetchAttributesAsync(Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext,System.Threading.CancellationToken)" /> method under the covers.</span></span></para>
          <para><span data-ttu-id="f3327-503">Legen Sie die <see cref="P:Microsoft.WindowsAzure.Storage.Blob.CloudBlockBlob.StreamWriteSizeInBytes" /> Eigenschaft vor dem Aufrufen dieser Methode, um anzugeben, die Blockgröße in Bytes von 16 KB bis 100 MB inklusive zu schreiben.</span><span class="sxs-lookup"><span data-stu-id="f3327-503">Set the <see cref="P:Microsoft.WindowsAzure.Storage.Blob.CloudBlockBlob.StreamWriteSizeInBytes" /> property before calling this method to specify the block size to write, in bytes, ranging from between 16 KB and 100 MB inclusive.</span></span></para>
          <para><span data-ttu-id="f3327-504">Um eine Ausnahme auslösen, wenn das Blob vorhanden ist, anstatt ihn zu überschreiben, übergeben Sie ein <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> Objekt mit generiert <see cref="M:Microsoft.WindowsAzure.Storage.AccessCondition.GenerateIfNotExistsCondition" />.</span><span class="sxs-lookup"><span data-stu-id="f3327-504">To throw an exception if the blob exists instead of overwriting it, pass in an <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> object generated using <see cref="M:Microsoft.WindowsAzure.Storage.AccessCondition.GenerateIfNotExistsCondition" />.</span></span></para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="PutBlock">
      <MemberSignature Language="C#" Value="public virtual void PutBlock (string blockId, System.IO.Stream blockData, string contentMD5, Microsoft.WindowsAzure.Storage.AccessCondition accessCondition = null, Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options = null, Microsoft.WindowsAzure.Storage.OperationContext operationContext = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void PutBlock(string blockId, class System.IO.Stream blockData, string contentMD5, class Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, class Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlockBlob.PutBlock(System.String,System.IO.Stream,System.String,Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="abstract member PutBlock : string * System.IO.Stream * string * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; unit&#xA;override this.PutBlock : string * System.IO.Stream * string * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; unit" Usage="cloudBlockBlob.PutBlock (blockId, blockData, contentMD5, accessCondition, options, operationContext)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.WindowsAzure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="blockId" Type="System.String" />
        <Parameter Name="blockData" Type="System.IO.Stream" />
        <Parameter Name="contentMD5" Type="System.String" />
        <Parameter Name="accessCondition" Type="Microsoft.WindowsAzure.Storage.AccessCondition" />
        <Parameter Name="options" Type="Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="blockId"><span data-ttu-id="f3327-505">Eine Base64-codierte Zeichenfolge, die den Block identifiziert.</span><span class="sxs-lookup"><span data-stu-id="f3327-505">A Base64-encoded string that identifies the block.</span></span></param>
        <param name="blockData"><span data-ttu-id="f3327-506">Ein <see cref="T:System.IO.Stream" /> -Objekt, das die Daten für den Block bereitstellt.</span><span class="sxs-lookup"><span data-stu-id="f3327-506">A <see cref="T:System.IO.Stream" /> object that provides the data for the block.</span></span></param>
        <param name="contentMD5"><span data-ttu-id="f3327-507">Ein optionaler Hashwert verwendet, um Transaktionsintegrität für den Block sicherzustellen.</span><span class="sxs-lookup"><span data-stu-id="f3327-507">An optional hash value used to ensure transactional integrity for the block.</span></span> <span data-ttu-id="f3327-508">Möglicherweise <c>null</c> oder eine leere Zeichenfolge.</span><span class="sxs-lookup"><span data-stu-id="f3327-508">May be <c>null</c> or an empty string.</span></span></param>
        <param name="accessCondition"><span data-ttu-id="f3327-509">Ein <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> -Objekt, das die Bedingung, die erfüllt sein müssen, damit die Anforderung darstellt, um den Vorgang fortzusetzen.</span><span class="sxs-lookup"><span data-stu-id="f3327-509">An <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> object that represents the condition that must be met in order for the request to proceed.</span></span> <span data-ttu-id="f3327-510">Wenn <c>null</c>, keine Bedingung verwendet.</span><span class="sxs-lookup"><span data-stu-id="f3327-510">If <c>null</c>, no condition is used.</span></span></param>
        <param name="options"><span data-ttu-id="f3327-511">Ein <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" /> -Objekt, das zusätzliche Optionen für die Anforderung angibt.</span><span class="sxs-lookup"><span data-stu-id="f3327-511">A <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" /> object that specifies additional options for the request.</span></span> <span data-ttu-id="f3327-512">Wenn <c>null</c>, Standardoptionen gelten für die Anforderung.</span><span class="sxs-lookup"><span data-stu-id="f3327-512">If <c>null</c>, default options are applied to the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="f3327-513">Ein <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> -Objekt, das den Kontext für den aktuellen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="f3327-513">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <summary>
            <span data-ttu-id="f3327-514">Lädt einen einzelnen Block hoch.</span><span class="sxs-lookup"><span data-stu-id="f3327-514">Uploads a single block.</span></span>
            </summary>
        <remarks>
            <span data-ttu-id="f3327-515">Clients können den Content-MD5-Header für einen angegebenen Block Put-Vorgang als Mittel zum Sicherstellen der Transaktionsintegrität unverschlüsselt gesendet.</span><span class="sxs-lookup"><span data-stu-id="f3327-515">Clients may send the Content-MD5 header for a given Put Block operation as a means to ensure transactional integrity over the wire.</span></span> <span data-ttu-id="f3327-516">Die <paramref name="contentMD5" /> Parameter ermöglicht Clients, die bereits Zugriff auf einen vorab berechneten MD5-Wert für einen angegebenen Bytebereich ihn zur Verfügung stellen.</span><span class="sxs-lookup"><span data-stu-id="f3327-516">The <paramref name="contentMD5" /> parameter permits clients who already have access to a pre-computed MD5 value for a given byte range to provide it.</span></span>
            <span data-ttu-id="f3327-517">Wenn die <see cref="P:BlobRequestOptions.UseTransactionalMd5" /> -Eigenschaftensatz auf <c>"true"</c> und die <paramref name="contentMD5" /> Parameter auf festgelegt ist <c>null</c>, und klicken Sie dann die Clientbibliothek intern den MD5-Wert berechnet wird.</span><span class="sxs-lookup"><span data-stu-id="f3327-517">If the <see cref="P:BlobRequestOptions.UseTransactionalMd5" /> property is set to <c>true</c> and the <paramref name="contentMD5" /> parameter is set to <c>null</c>, then the client library will calculate the MD5 value internally.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="PutBlockAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task PutBlockAsync (string blockId, System.IO.Stream blockData, string contentMD5);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task PutBlockAsync(string blockId, class System.IO.Stream blockData, string contentMD5) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlockBlob.PutBlockAsync(System.String,System.IO.Stream,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function PutBlockAsync (blockId As String, blockData As Stream, contentMD5 As String) As Task" />
      <MemberSignature Language="F#" Value="abstract member PutBlockAsync : string * System.IO.Stream * string -&gt; System.Threading.Tasks.Task&#xA;override this.PutBlockAsync : string * System.IO.Stream * string -&gt; System.Threading.Tasks.Task" Usage="cloudBlockBlob.PutBlockAsync (blockId, blockData, contentMD5)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.WindowsAzure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="blockId" Type="System.String" />
        <Parameter Name="blockData" Type="System.IO.Stream" />
        <Parameter Name="contentMD5" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="blockId"><span data-ttu-id="f3327-518">Eine Base64-codierte Zeichenfolge, die den Block identifiziert.</span><span class="sxs-lookup"><span data-stu-id="f3327-518">A Base64-encoded string that identifies the block.</span></span></param>
        <param name="blockData"><span data-ttu-id="f3327-519">Ein <see cref="T:System.IO.Stream" /> -Objekt, das die Daten für den Block bereitstellt.</span><span class="sxs-lookup"><span data-stu-id="f3327-519">A <see cref="T:System.IO.Stream" /> object that provides the data for the block.</span></span></param>
        <param name="contentMD5"><span data-ttu-id="f3327-520">Ein optionaler Hashwert verwendet, um Transaktionsintegrität für den Block sicherzustellen.</span><span class="sxs-lookup"><span data-stu-id="f3327-520">An optional hash value used to ensure transactional integrity for the block.</span></span> <span data-ttu-id="f3327-521">Möglicherweise <c>null</c> oder eine leere Zeichenfolge.</span><span class="sxs-lookup"><span data-stu-id="f3327-521">May be <c>null</c> or an empty string.</span></span></param>
        <summary>
            <span data-ttu-id="f3327-522">Initiiert einen asynchronen Vorgang zum Hochladen eines einzelnen Blocks.</span><span class="sxs-lookup"><span data-stu-id="f3327-522">Initiates an asynchronous operation to upload a single block.</span></span>
            </summary>
        <returns><span data-ttu-id="f3327-523">Ein <see cref="T:System.Threading.Tasks.Task" />-Objekt, das den asynchronen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="f3327-523">A <see cref="T:System.Threading.Tasks.Task" /> object that represents the asynchronous operation.</span></span></returns>
        <remarks>
            <span data-ttu-id="f3327-524">Clients können den Content-MD5-Header für einen angegebenen Block Put-Vorgang als Mittel zum Sicherstellen der Transaktionsintegrität unverschlüsselt gesendet.</span><span class="sxs-lookup"><span data-stu-id="f3327-524">Clients may send the Content-MD5 header for a given Put Block operation as a means to ensure transactional integrity over the wire.</span></span> <span data-ttu-id="f3327-525">Die <paramref name="contentMD5" /> Parameter ermöglicht Clients, die bereits Zugriff auf einen vorab berechneten MD5-Wert für einen angegebenen Bytebereich ihn zur Verfügung stellen.</span><span class="sxs-lookup"><span data-stu-id="f3327-525">The <paramref name="contentMD5" /> parameter permits clients who already have access to a pre-computed MD5 value for a given byte range to provide it.</span></span>
            <span data-ttu-id="f3327-526">Wenn die <see cref="P:BlobRequestOptions.UseTransactionalMd5" /> -Eigenschaftensatz auf <c>"true"</c> und die <paramref name="contentMD5" /> Parameter auf festgelegt ist <c>null</c>, und klicken Sie dann die Clientbibliothek intern den MD5-Wert berechnet wird.</span><span class="sxs-lookup"><span data-stu-id="f3327-526">If the <see cref="P:BlobRequestOptions.UseTransactionalMd5" /> property is set to <c>true</c> and the <paramref name="contentMD5" /> parameter is set to <c>null</c>, then the client library will calculate the MD5 value internally.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="PutBlockAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task PutBlockAsync (string blockId, System.IO.Stream blockData, string contentMD5, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task PutBlockAsync(string blockId, class System.IO.Stream blockData, string contentMD5, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlockBlob.PutBlockAsync(System.String,System.IO.Stream,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member PutBlockAsync : string * System.IO.Stream * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&#xA;override this.PutBlockAsync : string * System.IO.Stream * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="cloudBlockBlob.PutBlockAsync (blockId, blockData, contentMD5, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.WindowsAzure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="blockId" Type="System.String" />
        <Parameter Name="blockData" Type="System.IO.Stream" />
        <Parameter Name="contentMD5" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="blockId"><span data-ttu-id="f3327-527">Eine Base64-codierte Zeichenfolge, die den Block identifiziert.</span><span class="sxs-lookup"><span data-stu-id="f3327-527">A Base64-encoded string that identifies the block.</span></span></param>
        <param name="blockData"><span data-ttu-id="f3327-528">Ein <see cref="T:System.IO.Stream" /> -Objekt, das die Daten für den Block bereitstellt.</span><span class="sxs-lookup"><span data-stu-id="f3327-528">A <see cref="T:System.IO.Stream" /> object that provides the data for the block.</span></span></param>
        <param name="contentMD5"><span data-ttu-id="f3327-529">Ein optionaler Hashwert verwendet, um Transaktionsintegrität für den Block sicherzustellen.</span><span class="sxs-lookup"><span data-stu-id="f3327-529">An optional hash value used to ensure transactional integrity for the block.</span></span> <span data-ttu-id="f3327-530">Möglicherweise <c>null</c> oder eine leere Zeichenfolge.</span><span class="sxs-lookup"><span data-stu-id="f3327-530">May be <c>null</c> or an empty string.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="f3327-531">Ein <see cref="T:System.Threading.CancellationToken" />, das beim Warten auf den Abschluss einer Aufgabe überwacht werden soll.</span><span class="sxs-lookup"><span data-stu-id="f3327-531">A <see cref="T:System.Threading.CancellationToken" /> to observe while waiting for a task to complete.</span></span></param>
        <summary>
            <span data-ttu-id="f3327-532">Initiiert einen asynchronen Vorgang zum Hochladen eines einzelnen Blocks.</span><span class="sxs-lookup"><span data-stu-id="f3327-532">Initiates an asynchronous operation to upload a single block.</span></span>
            </summary>
        <returns><span data-ttu-id="f3327-533">Ein <see cref="T:System.Threading.Tasks.Task" />-Objekt, das den asynchronen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="f3327-533">A <see cref="T:System.Threading.Tasks.Task" /> object that represents the asynchronous operation.</span></span></returns>
        <remarks>
            <span data-ttu-id="f3327-534">Clients können den Content-MD5-Header für einen angegebenen Block Put-Vorgang als Mittel zum Sicherstellen der Transaktionsintegrität unverschlüsselt gesendet.</span><span class="sxs-lookup"><span data-stu-id="f3327-534">Clients may send the Content-MD5 header for a given Put Block operation as a means to ensure transactional integrity over the wire.</span></span> <span data-ttu-id="f3327-535">Die <paramref name="contentMD5" /> Parameter ermöglicht Clients, die bereits Zugriff auf einen vorab berechneten MD5-Wert für einen angegebenen Bytebereich ihn zur Verfügung stellen.</span><span class="sxs-lookup"><span data-stu-id="f3327-535">The <paramref name="contentMD5" /> parameter permits clients who already have access to a pre-computed MD5 value for a given byte range to provide it.</span></span>
            <span data-ttu-id="f3327-536">Wenn die <see cref="P:BlobRequestOptions.UseTransactionalMd5" /> -Eigenschaftensatz auf <c>"true"</c> und die <paramref name="contentMD5" /> Parameter auf festgelegt ist <c>null</c>, und klicken Sie dann die Clientbibliothek intern den MD5-Wert berechnet wird.</span><span class="sxs-lookup"><span data-stu-id="f3327-536">If the <see cref="P:BlobRequestOptions.UseTransactionalMd5" /> property is set to <c>true</c> and the <paramref name="contentMD5" /> parameter is set to <c>null</c>, then the client library will calculate the MD5 value internally.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="PutBlockAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task PutBlockAsync (string blockId, System.IO.Stream blockData, string contentMD5, Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, Microsoft.WindowsAzure.Storage.OperationContext operationContext);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task PutBlockAsync(string blockId, class System.IO.Stream blockData, string contentMD5, class Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, class Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlockBlob.PutBlockAsync(System.String,System.IO.Stream,System.String,Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="abstract member PutBlockAsync : string * System.IO.Stream * string * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Threading.Tasks.Task&#xA;override this.PutBlockAsync : string * System.IO.Stream * string * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Threading.Tasks.Task" Usage="cloudBlockBlob.PutBlockAsync (blockId, blockData, contentMD5, accessCondition, options, operationContext)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.WindowsAzure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="blockId" Type="System.String" />
        <Parameter Name="blockData" Type="System.IO.Stream" />
        <Parameter Name="contentMD5" Type="System.String" />
        <Parameter Name="accessCondition" Type="Microsoft.WindowsAzure.Storage.AccessCondition" />
        <Parameter Name="options" Type="Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="blockId"><span data-ttu-id="f3327-537">Eine Base64-codierte Zeichenfolge, die den Block identifiziert.</span><span class="sxs-lookup"><span data-stu-id="f3327-537">A Base64-encoded string that identifies the block.</span></span></param>
        <param name="blockData"><span data-ttu-id="f3327-538">Ein <see cref="T:System.IO.Stream" /> -Objekt, das die Daten für den Block bereitstellt.</span><span class="sxs-lookup"><span data-stu-id="f3327-538">A <see cref="T:System.IO.Stream" /> object that provides the data for the block.</span></span></param>
        <param name="contentMD5"><span data-ttu-id="f3327-539">Ein optionaler Hashwert verwendet, um Transaktionsintegrität für den Block sicherzustellen.</span><span class="sxs-lookup"><span data-stu-id="f3327-539">An optional hash value used to ensure transactional integrity for the block.</span></span> <span data-ttu-id="f3327-540">Möglicherweise <c>null</c> oder eine leere Zeichenfolge.</span><span class="sxs-lookup"><span data-stu-id="f3327-540">May be <c>null</c> or an empty string.</span></span></param>
        <param name="accessCondition"><span data-ttu-id="f3327-541">Ein <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> -Objekt, das die Bedingung, die erfüllt sein müssen, damit die Anforderung darstellt, um den Vorgang fortzusetzen.</span><span class="sxs-lookup"><span data-stu-id="f3327-541">An <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> object that represents the condition that must be met in order for the request to proceed.</span></span> <span data-ttu-id="f3327-542">Wenn <c>null</c>, keine Bedingung verwendet.</span><span class="sxs-lookup"><span data-stu-id="f3327-542">If <c>null</c>, no condition is used.</span></span></param>
        <param name="options"><span data-ttu-id="f3327-543">Ein <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" /> -Objekt, das zusätzliche Optionen für die Anforderung angibt.</span><span class="sxs-lookup"><span data-stu-id="f3327-543">A <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" /> object that specifies additional options for the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="f3327-544">Ein <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> -Objekt, das den Kontext für den aktuellen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="f3327-544">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <summary>
            <span data-ttu-id="f3327-545">Initiiert einen asynchronen Vorgang zum Hochladen eines einzelnen Blocks.</span><span class="sxs-lookup"><span data-stu-id="f3327-545">Initiates an asynchronous operation to upload a single block.</span></span>
            </summary>
        <returns><span data-ttu-id="f3327-546">Ein <see cref="T:System.Threading.Tasks.Task" />-Objekt, das den asynchronen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="f3327-546">A <see cref="T:System.Threading.Tasks.Task" /> object that represents the asynchronous operation.</span></span></returns>
        <remarks>
            <span data-ttu-id="f3327-547">Clients können den Content-MD5-Header für einen angegebenen Block Put-Vorgang als Mittel zum Sicherstellen der Transaktionsintegrität unverschlüsselt gesendet.</span><span class="sxs-lookup"><span data-stu-id="f3327-547">Clients may send the Content-MD5 header for a given Put Block operation as a means to ensure transactional integrity over the wire.</span></span> <span data-ttu-id="f3327-548">Die <paramref name="contentMD5" /> Parameter ermöglicht Clients, die bereits Zugriff auf einen vorab berechneten MD5-Wert für einen angegebenen Bytebereich ihn zur Verfügung stellen.</span><span class="sxs-lookup"><span data-stu-id="f3327-548">The <paramref name="contentMD5" /> parameter permits clients who already have access to a pre-computed MD5 value for a given byte range to provide it.</span></span>
            <span data-ttu-id="f3327-549">Wenn die <see cref="P:BlobRequestOptions.UseTransactionalMd5" /> -Eigenschaftensatz auf <c>"true"</c> und die <paramref name="contentMD5" /> Parameter auf festgelegt ist <c>null</c>, und klicken Sie dann die Clientbibliothek intern den MD5-Wert berechnet wird.</span><span class="sxs-lookup"><span data-stu-id="f3327-549">If the <see cref="P:BlobRequestOptions.UseTransactionalMd5" /> property is set to <c>true</c> and the <paramref name="contentMD5" /> parameter is set to <c>null</c>, then the client library will calculate the MD5 value internally.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="PutBlockAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task PutBlockAsync (string blockId, System.IO.Stream blockData, string contentMD5, Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, Microsoft.WindowsAzure.Storage.OperationContext operationContext, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task PutBlockAsync(string blockId, class System.IO.Stream blockData, string contentMD5, class Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, class Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, class Microsoft.WindowsAzure.Storage.OperationContext operationContext, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlockBlob.PutBlockAsync(System.String,System.IO.Stream,System.String,Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member PutBlockAsync : string * System.IO.Stream * string * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&#xA;override this.PutBlockAsync : string * System.IO.Stream * string * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="cloudBlockBlob.PutBlockAsync (blockId, blockData, contentMD5, accessCondition, options, operationContext, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.WindowsAzure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="blockId" Type="System.String" />
        <Parameter Name="blockData" Type="System.IO.Stream" />
        <Parameter Name="contentMD5" Type="System.String" />
        <Parameter Name="accessCondition" Type="Microsoft.WindowsAzure.Storage.AccessCondition" />
        <Parameter Name="options" Type="Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="blockId"><span data-ttu-id="f3327-550">Eine Base64-codierte Zeichenfolge, die den Block identifiziert.</span><span class="sxs-lookup"><span data-stu-id="f3327-550">A Base64-encoded string that identifies the block.</span></span></param>
        <param name="blockData"><span data-ttu-id="f3327-551">Ein <see cref="T:System.IO.Stream" /> -Objekt, das die Daten für den Block bereitstellt.</span><span class="sxs-lookup"><span data-stu-id="f3327-551">A <see cref="T:System.IO.Stream" /> object that provides the data for the block.</span></span></param>
        <param name="contentMD5"><span data-ttu-id="f3327-552">Ein optionaler Hashwert verwendet, um Transaktionsintegrität für den Block sicherzustellen.</span><span class="sxs-lookup"><span data-stu-id="f3327-552">An optional hash value used to ensure transactional integrity for the block.</span></span> <span data-ttu-id="f3327-553">Möglicherweise <c>null</c> oder eine leere Zeichenfolge.</span><span class="sxs-lookup"><span data-stu-id="f3327-553">May be <c>null</c> or an empty string.</span></span></param>
        <param name="accessCondition"><span data-ttu-id="f3327-554">Ein <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> -Objekt, das die Bedingung, die erfüllt sein müssen, damit die Anforderung darstellt, um den Vorgang fortzusetzen.</span><span class="sxs-lookup"><span data-stu-id="f3327-554">An <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> object that represents the condition that must be met in order for the request to proceed.</span></span> <span data-ttu-id="f3327-555">Wenn <c>null</c>, keine Bedingung verwendet.</span><span class="sxs-lookup"><span data-stu-id="f3327-555">If <c>null</c>, no condition is used.</span></span></param>
        <param name="options"><span data-ttu-id="f3327-556">Ein <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" /> -Objekt, das zusätzliche Optionen für die Anforderung angibt.</span><span class="sxs-lookup"><span data-stu-id="f3327-556">A <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" /> object that specifies additional options for the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="f3327-557">Ein <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> -Objekt, das den Kontext für den aktuellen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="f3327-557">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="f3327-558">Ein <see cref="T:System.Threading.CancellationToken" />, das beim Warten auf den Abschluss einer Aufgabe überwacht werden soll.</span><span class="sxs-lookup"><span data-stu-id="f3327-558">A <see cref="T:System.Threading.CancellationToken" /> to observe while waiting for a task to complete.</span></span></param>
        <summary>
            <span data-ttu-id="f3327-559">Initiiert einen asynchronen Vorgang zum Hochladen eines einzelnen Blocks.</span><span class="sxs-lookup"><span data-stu-id="f3327-559">Initiates an asynchronous operation to upload a single block.</span></span>
            </summary>
        <returns><span data-ttu-id="f3327-560">Ein <see cref="T:System.Threading.Tasks.Task" />-Objekt, das den asynchronen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="f3327-560">A <see cref="T:System.Threading.Tasks.Task" /> object that represents the asynchronous operation.</span></span></returns>
        <remarks>
            <span data-ttu-id="f3327-561">Clients können den Content-MD5-Header für einen angegebenen Block Put-Vorgang als Mittel zum Sicherstellen der Transaktionsintegrität unverschlüsselt gesendet.</span><span class="sxs-lookup"><span data-stu-id="f3327-561">Clients may send the Content-MD5 header for a given Put Block operation as a means to ensure transactional integrity over the wire.</span></span> <span data-ttu-id="f3327-562">Die <paramref name="contentMD5" /> Parameter ermöglicht Clients, die bereits Zugriff auf einen vorab berechneten MD5-Wert für einen angegebenen Bytebereich ihn zur Verfügung stellen.</span><span class="sxs-lookup"><span data-stu-id="f3327-562">The <paramref name="contentMD5" /> parameter permits clients who already have access to a pre-computed MD5 value for a given byte range to provide it.</span></span>
            <span data-ttu-id="f3327-563">Wenn die <see cref="P:BlobRequestOptions.UseTransactionalMd5" /> -Eigenschaftensatz auf <c>"true"</c> und die <paramref name="contentMD5" /> Parameter auf festgelegt ist <c>null</c>, und klicken Sie dann die Clientbibliothek intern den MD5-Wert berechnet wird.</span><span class="sxs-lookup"><span data-stu-id="f3327-563">If the <see cref="P:BlobRequestOptions.UseTransactionalMd5" /> property is set to <c>true</c> and the <paramref name="contentMD5" /> parameter is set to <c>null</c>, then the client library will calculate the MD5 value internally.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="PutBlockAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task PutBlockAsync (string blockId, System.IO.Stream blockData, string contentMD5, Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, Microsoft.WindowsAzure.Storage.OperationContext operationContext, IProgress&lt;Microsoft.WindowsAzure.Storage.Core.Util.StorageProgress&gt; progressHandler, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task PutBlockAsync(string blockId, class System.IO.Stream blockData, string contentMD5, class Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, class Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, class Microsoft.WindowsAzure.Storage.OperationContext operationContext, class System.IProgress`1&lt;class Microsoft.WindowsAzure.Storage.Core.Util.StorageProgress&gt; progressHandler, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlockBlob.PutBlockAsync(System.String,System.IO.Stream,System.String,Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext,System.IProgress{Microsoft.WindowsAzure.Storage.Core.Util.StorageProgress},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member PutBlockAsync : string * System.IO.Stream * string * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * IProgress&lt;Microsoft.WindowsAzure.Storage.Core.Util.StorageProgress&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&#xA;override this.PutBlockAsync : string * System.IO.Stream * string * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * IProgress&lt;Microsoft.WindowsAzure.Storage.Core.Util.StorageProgress&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="cloudBlockBlob.PutBlockAsync (blockId, blockData, contentMD5, accessCondition, options, operationContext, progressHandler, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.WindowsAzure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="blockId" Type="System.String" />
        <Parameter Name="blockData" Type="System.IO.Stream" />
        <Parameter Name="contentMD5" Type="System.String" />
        <Parameter Name="accessCondition" Type="Microsoft.WindowsAzure.Storage.AccessCondition" />
        <Parameter Name="options" Type="Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
        <Parameter Name="progressHandler" Type="System.IProgress&lt;Microsoft.WindowsAzure.Storage.Core.Util.StorageProgress&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="blockId"><span data-ttu-id="f3327-564">Eine Base64-codierte Zeichenfolge, die den Block identifiziert.</span><span class="sxs-lookup"><span data-stu-id="f3327-564">A Base64-encoded string that identifies the block.</span></span></param>
        <param name="blockData"><span data-ttu-id="f3327-565">Ein <see cref="T:System.IO.Stream" /> -Objekt, das die Daten für den Block bereitstellt.</span><span class="sxs-lookup"><span data-stu-id="f3327-565">A <see cref="T:System.IO.Stream" /> object that provides the data for the block.</span></span></param>
        <param name="contentMD5"><span data-ttu-id="f3327-566">Ein optionaler Hashwert verwendet, um Transaktionsintegrität für den Block sicherzustellen.</span><span class="sxs-lookup"><span data-stu-id="f3327-566">An optional hash value used to ensure transactional integrity for the block.</span></span> <span data-ttu-id="f3327-567">Möglicherweise <c>null</c> oder eine leere Zeichenfolge.</span><span class="sxs-lookup"><span data-stu-id="f3327-567">May be <c>null</c> or an empty string.</span></span></param>
        <param name="accessCondition"><span data-ttu-id="f3327-568">Ein <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> -Objekt, das die Bedingung, die erfüllt sein müssen, damit die Anforderung darstellt, um den Vorgang fortzusetzen.</span><span class="sxs-lookup"><span data-stu-id="f3327-568">An <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> object that represents the condition that must be met in order for the request to proceed.</span></span> <span data-ttu-id="f3327-569">Wenn <c>null</c>, keine Bedingung verwendet.</span><span class="sxs-lookup"><span data-stu-id="f3327-569">If <c>null</c>, no condition is used.</span></span></param>
        <param name="options"><span data-ttu-id="f3327-570">Ein <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" /> -Objekt, das zusätzliche Optionen für die Anforderung angibt.</span><span class="sxs-lookup"><span data-stu-id="f3327-570">A <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" /> object that specifies additional options for the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="f3327-571">Ein <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> -Objekt, das den Kontext für den aktuellen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="f3327-571">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <param name="progressHandler"> <span data-ttu-id="f3327-572">Ein <see cref="T:System.IProgress`1" /> Objekt behandelt <see cref="T:Microsoft.WindowsAzure.Storage.Core.Util.StorageProgress" /> Nachrichten.</span><span class="sxs-lookup"><span data-stu-id="f3327-572">A <see cref="T:System.IProgress`1" /> object to handle <see cref="T:Microsoft.WindowsAzure.Storage.Core.Util.StorageProgress" /> messages.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="f3327-573">Ein <see cref="T:System.Threading.CancellationToken" />, das beim Warten auf den Abschluss einer Aufgabe überwacht werden soll.</span><span class="sxs-lookup"><span data-stu-id="f3327-573">A <see cref="T:System.Threading.CancellationToken" /> to observe while waiting for a task to complete.</span></span></param>
        <summary>
            <span data-ttu-id="f3327-574">Initiiert einen asynchronen Vorgang zum Hochladen eines einzelnen Blocks.</span><span class="sxs-lookup"><span data-stu-id="f3327-574">Initiates an asynchronous operation to upload a single block.</span></span>
            </summary>
        <returns><span data-ttu-id="f3327-575">Ein <see cref="T:System.Threading.Tasks.Task" />-Objekt, das den asynchronen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="f3327-575">A <see cref="T:System.Threading.Tasks.Task" /> object that represents the asynchronous operation.</span></span></returns>
        <remarks>
            <span data-ttu-id="f3327-576">Clients können den Content-MD5-Header für einen angegebenen Block Put-Vorgang als Mittel zum Sicherstellen der Transaktionsintegrität unverschlüsselt gesendet.</span><span class="sxs-lookup"><span data-stu-id="f3327-576">Clients may send the Content-MD5 header for a given Put Block operation as a means to ensure transactional integrity over the wire.</span></span> <span data-ttu-id="f3327-577">Die <paramref name="contentMD5" /> Parameter ermöglicht Clients, die bereits Zugriff auf einen vorab berechneten MD5-Wert für einen angegebenen Bytebereich ihn zur Verfügung stellen.</span><span class="sxs-lookup"><span data-stu-id="f3327-577">The <paramref name="contentMD5" /> parameter permits clients who already have access to a pre-computed MD5 value for a given byte range to provide it.</span></span>
            <span data-ttu-id="f3327-578">Wenn die <see cref="P:BlobRequestOptions.UseTransactionalMd5" /> -Eigenschaftensatz auf <c>"true"</c> und die <paramref name="contentMD5" /> Parameter auf festgelegt ist <c>null</c>, und klicken Sie dann die Clientbibliothek intern den MD5-Wert berechnet wird.</span><span class="sxs-lookup"><span data-stu-id="f3327-578">If the <see cref="P:BlobRequestOptions.UseTransactionalMd5" /> property is set to <c>true</c> and the <paramref name="contentMD5" /> parameter is set to <c>null</c>, then the client library will calculate the MD5 value internally.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="PutBlockList">
      <MemberSignature Language="C#" Value="public virtual void PutBlockList (System.Collections.Generic.IEnumerable&lt;string&gt; blockList, Microsoft.WindowsAzure.Storage.AccessCondition accessCondition = null, Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options = null, Microsoft.WindowsAzure.Storage.OperationContext operationContext = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void PutBlockList(class System.Collections.Generic.IEnumerable`1&lt;string&gt; blockList, class Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, class Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlockBlob.PutBlockList(System.Collections.Generic.IEnumerable{System.String},Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="abstract member PutBlockList : seq&lt;string&gt; * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; unit&#xA;override this.PutBlockList : seq&lt;string&gt; * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; unit" Usage="cloudBlockBlob.PutBlockList (blockList, accessCondition, options, operationContext)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.WindowsAzure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="blockList" Type="System.Collections.Generic.IEnumerable&lt;System.String&gt;" />
        <Parameter Name="accessCondition" Type="Microsoft.WindowsAzure.Storage.AccessCondition" />
        <Parameter Name="options" Type="Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="blockList"><span data-ttu-id="f3327-579">Eine aufzählbare Auflistung von Block-IDs als Base64-codierte Zeichenfolgen.</span><span class="sxs-lookup"><span data-stu-id="f3327-579">An enumerable collection of block IDs, as Base64-encoded strings.</span></span></param>
        <param name="accessCondition"><span data-ttu-id="f3327-580">Ein <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> -Objekt, das die Bedingung, die erfüllt sein müssen, damit die Anforderung darstellt, um den Vorgang fortzusetzen.</span><span class="sxs-lookup"><span data-stu-id="f3327-580">An <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> object that represents the condition that must be met in order for the request to proceed.</span></span> <span data-ttu-id="f3327-581">Wenn <c>null</c>, keine Bedingung verwendet.</span><span class="sxs-lookup"><span data-stu-id="f3327-581">If <c>null</c>, no condition is used.</span></span></param>
        <param name="options"><span data-ttu-id="f3327-582">Ein <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" /> -Objekt, das zusätzliche Optionen für die Anforderung angibt.</span><span class="sxs-lookup"><span data-stu-id="f3327-582">A <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" /> object that specifies additional options for the request.</span></span> <span data-ttu-id="f3327-583">Wenn <c>null</c>, Standardoptionen gelten für die Anforderung.</span><span class="sxs-lookup"><span data-stu-id="f3327-583">If <c>null</c>, default options are applied to the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="f3327-584">Ein <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> -Objekt, das den Kontext für den aktuellen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="f3327-584">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <summary>
            <span data-ttu-id="f3327-585">Lädt eine Liste von Blöcken in ein neues oder vorhandenes Blob hoch.</span><span class="sxs-lookup"><span data-stu-id="f3327-585">Uploads a list of blocks to a new or existing blob.</span></span> 
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PutBlockListAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task PutBlockListAsync (System.Collections.Generic.IEnumerable&lt;string&gt; blockList);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task PutBlockListAsync(class System.Collections.Generic.IEnumerable`1&lt;string&gt; blockList) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlockBlob.PutBlockListAsync(System.Collections.Generic.IEnumerable{System.String})" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function PutBlockListAsync (blockList As IEnumerable(Of String)) As Task" />
      <MemberSignature Language="F#" Value="abstract member PutBlockListAsync : seq&lt;string&gt; -&gt; System.Threading.Tasks.Task&#xA;override this.PutBlockListAsync : seq&lt;string&gt; -&gt; System.Threading.Tasks.Task" Usage="cloudBlockBlob.PutBlockListAsync blockList" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.WindowsAzure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="blockList" Type="System.Collections.Generic.IEnumerable&lt;System.String&gt;" />
      </Parameters>
      <Docs>
        <param name="blockList"><span data-ttu-id="f3327-586">Eine aufzählbare Auflistung von Block-IDs als Base64-codierte Zeichenfolgen.</span><span class="sxs-lookup"><span data-stu-id="f3327-586">An enumerable collection of block IDs, as Base64-encoded strings.</span></span></param>
        <summary>
            <span data-ttu-id="f3327-587">Initiiert einen asynchronen Vorgang zum Hochladen einer Liste von Blöcken in ein neues oder vorhandenes Blob.</span><span class="sxs-lookup"><span data-stu-id="f3327-587">Initiates an asynchronous operation to upload a list of blocks to a new or existing blob.</span></span> 
            </summary>
        <returns><span data-ttu-id="f3327-588">Ein <see cref="T:System.Threading.Tasks.Task" />-Objekt, das den asynchronen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="f3327-588">A <see cref="T:System.Threading.Tasks.Task" /> object that represents the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PutBlockListAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task PutBlockListAsync (System.Collections.Generic.IEnumerable&lt;string&gt; blockList, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task PutBlockListAsync(class System.Collections.Generic.IEnumerable`1&lt;string&gt; blockList, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlockBlob.PutBlockListAsync(System.Collections.Generic.IEnumerable{System.String},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member PutBlockListAsync : seq&lt;string&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&#xA;override this.PutBlockListAsync : seq&lt;string&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="cloudBlockBlob.PutBlockListAsync (blockList, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.WindowsAzure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="blockList" Type="System.Collections.Generic.IEnumerable&lt;System.String&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="blockList"><span data-ttu-id="f3327-589">Eine aufzählbare Auflistung von Block-IDs als Base64-codierte Zeichenfolgen.</span><span class="sxs-lookup"><span data-stu-id="f3327-589">An enumerable collection of block IDs, as Base64-encoded strings.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="f3327-590">Ein <see cref="T:System.Threading.CancellationToken" />, das beim Warten auf den Abschluss einer Aufgabe überwacht werden soll.</span><span class="sxs-lookup"><span data-stu-id="f3327-590">A <see cref="T:System.Threading.CancellationToken" /> to observe while waiting for a task to complete.</span></span></param>
        <summary>
            <span data-ttu-id="f3327-591">Initiiert einen asynchronen Vorgang zum Hochladen einer Liste von Blöcken in ein neues oder vorhandenes Blob.</span><span class="sxs-lookup"><span data-stu-id="f3327-591">Initiates an asynchronous operation to upload a list of blocks to a new or existing blob.</span></span> 
            </summary>
        <returns><span data-ttu-id="f3327-592">Ein <see cref="T:System.Threading.Tasks.Task" />-Objekt, das den asynchronen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="f3327-592">A <see cref="T:System.Threading.Tasks.Task" /> object that represents the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PutBlockListAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task PutBlockListAsync (System.Collections.Generic.IEnumerable&lt;string&gt; blockList, Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, Microsoft.WindowsAzure.Storage.OperationContext operationContext);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task PutBlockListAsync(class System.Collections.Generic.IEnumerable`1&lt;string&gt; blockList, class Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, class Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlockBlob.PutBlockListAsync(System.Collections.Generic.IEnumerable{System.String},Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="abstract member PutBlockListAsync : seq&lt;string&gt; * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Threading.Tasks.Task&#xA;override this.PutBlockListAsync : seq&lt;string&gt; * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Threading.Tasks.Task" Usage="cloudBlockBlob.PutBlockListAsync (blockList, accessCondition, options, operationContext)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.WindowsAzure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="blockList" Type="System.Collections.Generic.IEnumerable&lt;System.String&gt;" />
        <Parameter Name="accessCondition" Type="Microsoft.WindowsAzure.Storage.AccessCondition" />
        <Parameter Name="options" Type="Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="blockList"><span data-ttu-id="f3327-593">Eine aufzählbare Auflistung von Block-IDs als Base64-codierte Zeichenfolgen.</span><span class="sxs-lookup"><span data-stu-id="f3327-593">An enumerable collection of block IDs, as Base64-encoded strings.</span></span></param>
        <param name="accessCondition"><span data-ttu-id="f3327-594">Ein <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> -Objekt, das die Bedingung, die erfüllt sein müssen, damit die Anforderung darstellt, um den Vorgang fortzusetzen.</span><span class="sxs-lookup"><span data-stu-id="f3327-594">An <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> object that represents the condition that must be met in order for the request to proceed.</span></span> <span data-ttu-id="f3327-595">Wenn <c>null</c>, keine Bedingung verwendet.</span><span class="sxs-lookup"><span data-stu-id="f3327-595">If <c>null</c>, no condition is used.</span></span></param>
        <param name="options"><span data-ttu-id="f3327-596">Ein <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" /> -Objekt, das zusätzliche Optionen für die Anforderung angibt.</span><span class="sxs-lookup"><span data-stu-id="f3327-596">A <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" /> object that specifies additional options for the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="f3327-597">Ein <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> -Objekt, das den Kontext für den aktuellen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="f3327-597">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <summary>
            <span data-ttu-id="f3327-598">Initiiert einen asynchronen Vorgang zum Hochladen einer Liste von Blöcken in ein neues oder vorhandenes Blob.</span><span class="sxs-lookup"><span data-stu-id="f3327-598">Initiates an asynchronous operation to upload a list of blocks to a new or existing blob.</span></span> 
            </summary>
        <returns><span data-ttu-id="f3327-599">Ein <see cref="T:System.Threading.Tasks.Task" />-Objekt, das den asynchronen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="f3327-599">A <see cref="T:System.Threading.Tasks.Task" /> object that represents the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PutBlockListAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task PutBlockListAsync (System.Collections.Generic.IEnumerable&lt;string&gt; blockList, Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, Microsoft.WindowsAzure.Storage.OperationContext operationContext, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task PutBlockListAsync(class System.Collections.Generic.IEnumerable`1&lt;string&gt; blockList, class Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, class Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, class Microsoft.WindowsAzure.Storage.OperationContext operationContext, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlockBlob.PutBlockListAsync(System.Collections.Generic.IEnumerable{System.String},Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member PutBlockListAsync : seq&lt;string&gt; * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&#xA;override this.PutBlockListAsync : seq&lt;string&gt; * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="cloudBlockBlob.PutBlockListAsync (blockList, accessCondition, options, operationContext, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.WindowsAzure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="blockList" Type="System.Collections.Generic.IEnumerable&lt;System.String&gt;" />
        <Parameter Name="accessCondition" Type="Microsoft.WindowsAzure.Storage.AccessCondition" />
        <Parameter Name="options" Type="Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="blockList"><span data-ttu-id="f3327-600">Eine aufzählbare Auflistung von Block-IDs als Base64-codierte Zeichenfolgen.</span><span class="sxs-lookup"><span data-stu-id="f3327-600">An enumerable collection of block IDs, as Base64-encoded strings.</span></span></param>
        <param name="accessCondition"><span data-ttu-id="f3327-601">Ein <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> -Objekt, das die Bedingung, die erfüllt sein müssen, damit die Anforderung darstellt, um den Vorgang fortzusetzen.</span><span class="sxs-lookup"><span data-stu-id="f3327-601">An <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> object that represents the condition that must be met in order for the request to proceed.</span></span> <span data-ttu-id="f3327-602">Wenn <c>null</c>, keine Bedingung verwendet.</span><span class="sxs-lookup"><span data-stu-id="f3327-602">If <c>null</c>, no condition is used.</span></span></param>
        <param name="options"><span data-ttu-id="f3327-603">Ein <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" /> -Objekt, das zusätzliche Optionen für die Anforderung angibt.</span><span class="sxs-lookup"><span data-stu-id="f3327-603">A <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" /> object that specifies additional options for the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="f3327-604">Ein <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> -Objekt, das den Kontext für den aktuellen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="f3327-604">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="f3327-605">Ein <see cref="T:System.Threading.CancellationToken" />, das beim Warten auf den Abschluss einer Aufgabe überwacht werden soll.</span><span class="sxs-lookup"><span data-stu-id="f3327-605">A <see cref="T:System.Threading.CancellationToken" /> to observe while waiting for a task to complete.</span></span></param>
        <summary>
            <span data-ttu-id="f3327-606">Initiiert einen asynchronen Vorgang zum Hochladen einer Liste von Blöcken in ein neues oder vorhandenes Blob.</span><span class="sxs-lookup"><span data-stu-id="f3327-606">Initiates an asynchronous operation to upload a list of blocks to a new or existing blob.</span></span> 
            </summary>
        <returns><span data-ttu-id="f3327-607">Ein <see cref="T:System.Threading.Tasks.Task" />-Objekt, das den asynchronen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="f3327-607">A <see cref="T:System.Threading.Tasks.Task" /> object that represents the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SetStandardBlobTier">
      <MemberSignature Language="C#" Value="public virtual void SetStandardBlobTier (Microsoft.WindowsAzure.Storage.Blob.StandardBlobTier standardBlobTier, Microsoft.WindowsAzure.Storage.AccessCondition accessCondition = null, Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options = null, Microsoft.WindowsAzure.Storage.OperationContext operationContext = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void SetStandardBlobTier(valuetype Microsoft.WindowsAzure.Storage.Blob.StandardBlobTier standardBlobTier, class Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, class Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlockBlob.SetStandardBlobTier(Microsoft.WindowsAzure.Storage.Blob.StandardBlobTier,Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="abstract member SetStandardBlobTier : Microsoft.WindowsAzure.Storage.Blob.StandardBlobTier * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; unit&#xA;override this.SetStandardBlobTier : Microsoft.WindowsAzure.Storage.Blob.StandardBlobTier * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; unit" Usage="cloudBlockBlob.SetStandardBlobTier (standardBlobTier, accessCondition, options, operationContext)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.WindowsAzure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="standardBlobTier" Type="Microsoft.WindowsAzure.Storage.Blob.StandardBlobTier" />
        <Parameter Name="accessCondition" Type="Microsoft.WindowsAzure.Storage.AccessCondition" />
        <Parameter Name="options" Type="Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="standardBlobTier"><span data-ttu-id="f3327-608">Ein <see cref="T:Microsoft.WindowsAzure.Storage.Blob.StandardBlobTier" /> , legen Sie die Ebene darstellt.</span><span class="sxs-lookup"><span data-stu-id="f3327-608">A <see cref="T:Microsoft.WindowsAzure.Storage.Blob.StandardBlobTier" /> representing the tier to set.</span></span></param>
        <param name="accessCondition"><span data-ttu-id="f3327-609">Ein <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> -Objekt, das die Bedingung, die erfüllt sein müssen, damit die Anforderung darstellt, um den Vorgang fortzusetzen.</span><span class="sxs-lookup"><span data-stu-id="f3327-609">An <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> object that represents the condition that must be met in order for the request to proceed.</span></span> <span data-ttu-id="f3327-610">Wenn <c>null</c>, keine Bedingung verwendet.</span><span class="sxs-lookup"><span data-stu-id="f3327-610">If <c>null</c>, no condition is used.</span></span></param>
        <param name="options"><span data-ttu-id="f3327-611">Ein <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" /> -Objekt, das zusätzliche Optionen für die Anforderung angibt oder <c>null</c>.</span><span class="sxs-lookup"><span data-stu-id="f3327-611">A <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" /> object that specifies additional options for the request, or <c>null</c>.</span></span> <span data-ttu-id="f3327-612">Wenn <c>null</c>, Standardoptionen gelten für die Anforderung.</span><span class="sxs-lookup"><span data-stu-id="f3327-612">If <c>null</c>, default options are applied to the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="f3327-613">Ein <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> -Objekt, das den Kontext für den aktuellen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="f3327-613">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <summary>
            <span data-ttu-id="f3327-614">Legt die Ebene des BLOBs auf einen standard-Speicherkonto.</span><span class="sxs-lookup"><span data-stu-id="f3327-614">Sets the tier of the blob on a standard storage account.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SetStandardBlobTierAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task SetStandardBlobTierAsync (Microsoft.WindowsAzure.Storage.Blob.StandardBlobTier standardBlobTier);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task SetStandardBlobTierAsync(valuetype Microsoft.WindowsAzure.Storage.Blob.StandardBlobTier standardBlobTier) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlockBlob.SetStandardBlobTierAsync(Microsoft.WindowsAzure.Storage.Blob.StandardBlobTier)" />
      <MemberSignature Language="F#" Value="abstract member SetStandardBlobTierAsync : Microsoft.WindowsAzure.Storage.Blob.StandardBlobTier -&gt; System.Threading.Tasks.Task&#xA;override this.SetStandardBlobTierAsync : Microsoft.WindowsAzure.Storage.Blob.StandardBlobTier -&gt; System.Threading.Tasks.Task" Usage="cloudBlockBlob.SetStandardBlobTierAsync standardBlobTier" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.WindowsAzure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="standardBlobTier" Type="Microsoft.WindowsAzure.Storage.Blob.StandardBlobTier" />
      </Parameters>
      <Docs>
        <param name="standardBlobTier"><span data-ttu-id="f3327-615">Ein <see cref="T:Microsoft.WindowsAzure.Storage.Blob.StandardBlobTier" /> , legen Sie die Ebene darstellt.</span><span class="sxs-lookup"><span data-stu-id="f3327-615">A <see cref="T:Microsoft.WindowsAzure.Storage.Blob.StandardBlobTier" /> representing the tier to set.</span></span></param>
        <summary>
            <span data-ttu-id="f3327-616">Initiiert einen asynchronen Vorgang zum Festlegen der Ebene des BLOBs auf einen standard-Speicherkonto an.</span><span class="sxs-lookup"><span data-stu-id="f3327-616">Initiates an asynchronous operation to set the tier of the blob on a standard storage account.</span></span>
            </summary>
        <returns><span data-ttu-id="f3327-617">Ein <see cref="T:System.Threading.Tasks.Task" />-Objekt, das den asynchronen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="f3327-617">A <see cref="T:System.Threading.Tasks.Task" /> object that represents the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SetStandardBlobTierAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task SetStandardBlobTierAsync (Microsoft.WindowsAzure.Storage.Blob.StandardBlobTier standardBlobTier, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task SetStandardBlobTierAsync(valuetype Microsoft.WindowsAzure.Storage.Blob.StandardBlobTier standardBlobTier, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlockBlob.SetStandardBlobTierAsync(Microsoft.WindowsAzure.Storage.Blob.StandardBlobTier,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member SetStandardBlobTierAsync : Microsoft.WindowsAzure.Storage.Blob.StandardBlobTier * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&#xA;override this.SetStandardBlobTierAsync : Microsoft.WindowsAzure.Storage.Blob.StandardBlobTier * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="cloudBlockBlob.SetStandardBlobTierAsync (standardBlobTier, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.WindowsAzure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="standardBlobTier" Type="Microsoft.WindowsAzure.Storage.Blob.StandardBlobTier" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="standardBlobTier"><span data-ttu-id="f3327-618">Ein <see cref="T:Microsoft.WindowsAzure.Storage.Blob.StandardBlobTier" /> , legen Sie die Ebene darstellt.</span><span class="sxs-lookup"><span data-stu-id="f3327-618">A <see cref="T:Microsoft.WindowsAzure.Storage.Blob.StandardBlobTier" /> representing the tier to set.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="f3327-619">Ein <see cref="T:System.Threading.CancellationToken" />, das beim Warten auf den Abschluss einer Aufgabe überwacht werden soll.</span><span class="sxs-lookup"><span data-stu-id="f3327-619">A <see cref="T:System.Threading.CancellationToken" /> to observe while waiting for a task to complete.</span></span></param>
        <summary>
            <span data-ttu-id="f3327-620">Initiiert einen asynchronen Vorgang zum Festlegen der Ebene des BLOBs auf einen standard-Speicherkonto an.</span><span class="sxs-lookup"><span data-stu-id="f3327-620">Initiates an asynchronous operation to set the tier of the blob on a standard storage account.</span></span>
            </summary>
        <returns><span data-ttu-id="f3327-621">Ein <see cref="T:System.Threading.Tasks.Task" />-Objekt, das den asynchronen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="f3327-621">A <see cref="T:System.Threading.Tasks.Task" /> object that represents the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SetStandardBlobTierAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task SetStandardBlobTierAsync (Microsoft.WindowsAzure.Storage.Blob.StandardBlobTier standardBlobTier, Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, Microsoft.WindowsAzure.Storage.OperationContext operationContext);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task SetStandardBlobTierAsync(valuetype Microsoft.WindowsAzure.Storage.Blob.StandardBlobTier standardBlobTier, class Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, class Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlockBlob.SetStandardBlobTierAsync(Microsoft.WindowsAzure.Storage.Blob.StandardBlobTier,Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="abstract member SetStandardBlobTierAsync : Microsoft.WindowsAzure.Storage.Blob.StandardBlobTier * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Threading.Tasks.Task&#xA;override this.SetStandardBlobTierAsync : Microsoft.WindowsAzure.Storage.Blob.StandardBlobTier * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Threading.Tasks.Task" Usage="cloudBlockBlob.SetStandardBlobTierAsync (standardBlobTier, accessCondition, options, operationContext)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.WindowsAzure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="standardBlobTier" Type="Microsoft.WindowsAzure.Storage.Blob.StandardBlobTier" />
        <Parameter Name="accessCondition" Type="Microsoft.WindowsAzure.Storage.AccessCondition" />
        <Parameter Name="options" Type="Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="standardBlobTier"><span data-ttu-id="f3327-622">Ein <see cref="T:Microsoft.WindowsAzure.Storage.Blob.StandardBlobTier" /> , legen Sie die Ebene darstellt.</span><span class="sxs-lookup"><span data-stu-id="f3327-622">A <see cref="T:Microsoft.WindowsAzure.Storage.Blob.StandardBlobTier" /> representing the tier to set.</span></span></param>
        <param name="accessCondition"><span data-ttu-id="f3327-623">Ein <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> -Objekt, das die Bedingung, die erfüllt sein müssen, damit die Anforderung darstellt, um den Vorgang fortzusetzen.</span><span class="sxs-lookup"><span data-stu-id="f3327-623">An <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> object that represents the condition that must be met in order for the request to proceed.</span></span> <span data-ttu-id="f3327-624">Wenn <c>null</c>, keine Bedingung verwendet.</span><span class="sxs-lookup"><span data-stu-id="f3327-624">If <c>null</c>, no condition is used.</span></span></param>
        <param name="options"><span data-ttu-id="f3327-625">Ein <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" /> -Objekt, das zusätzliche Optionen für die Anforderung angibt.</span><span class="sxs-lookup"><span data-stu-id="f3327-625">A <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" /> object that specifies additional options for the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="f3327-626">Ein <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> -Objekt, das den Kontext für den aktuellen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="f3327-626">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <summary>
            <span data-ttu-id="f3327-627">Initiiert einen asynchronen Vorgang zum Festlegen der Ebene des BLOBs auf einen standard-Speicherkonto an.</span><span class="sxs-lookup"><span data-stu-id="f3327-627">Initiates an asynchronous operation to set the tier of the blob on a standard storage account.</span></span>
            </summary>
        <returns><span data-ttu-id="f3327-628">Ein <see cref="T:System.Threading.Tasks.Task" />-Objekt, das den asynchronen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="f3327-628">A <see cref="T:System.Threading.Tasks.Task" /> object that represents the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SetStandardBlobTierAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task SetStandardBlobTierAsync (Microsoft.WindowsAzure.Storage.Blob.StandardBlobTier standardBlobTier, Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, Microsoft.WindowsAzure.Storage.OperationContext operationContext, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task SetStandardBlobTierAsync(valuetype Microsoft.WindowsAzure.Storage.Blob.StandardBlobTier standardBlobTier, class Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, class Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, class Microsoft.WindowsAzure.Storage.OperationContext operationContext, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlockBlob.SetStandardBlobTierAsync(Microsoft.WindowsAzure.Storage.Blob.StandardBlobTier,Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member SetStandardBlobTierAsync : Microsoft.WindowsAzure.Storage.Blob.StandardBlobTier * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&#xA;override this.SetStandardBlobTierAsync : Microsoft.WindowsAzure.Storage.Blob.StandardBlobTier * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="cloudBlockBlob.SetStandardBlobTierAsync (standardBlobTier, accessCondition, options, operationContext, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.WindowsAzure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="standardBlobTier" Type="Microsoft.WindowsAzure.Storage.Blob.StandardBlobTier" />
        <Parameter Name="accessCondition" Type="Microsoft.WindowsAzure.Storage.AccessCondition" />
        <Parameter Name="options" Type="Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="standardBlobTier"><span data-ttu-id="f3327-629">Ein <see cref="T:Microsoft.WindowsAzure.Storage.Blob.StandardBlobTier" /> , legen Sie die Ebene darstellt.</span><span class="sxs-lookup"><span data-stu-id="f3327-629">A <see cref="T:Microsoft.WindowsAzure.Storage.Blob.StandardBlobTier" /> representing the tier to set.</span></span></param>
        <param name="accessCondition"><span data-ttu-id="f3327-630">Ein <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> -Objekt, das die Bedingung, die erfüllt sein müssen, damit die Anforderung darstellt, um den Vorgang fortzusetzen.</span><span class="sxs-lookup"><span data-stu-id="f3327-630">An <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> object that represents the condition that must be met in order for the request to proceed.</span></span> <span data-ttu-id="f3327-631">Wenn <c>null</c>, keine Bedingung verwendet.</span><span class="sxs-lookup"><span data-stu-id="f3327-631">If <c>null</c>, no condition is used.</span></span></param>
        <param name="options"><span data-ttu-id="f3327-632">Ein <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" /> -Objekt, das zusätzliche Optionen für die Anforderung angibt.</span><span class="sxs-lookup"><span data-stu-id="f3327-632">A <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" /> object that specifies additional options for the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="f3327-633">Ein <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> -Objekt, das den Kontext für den aktuellen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="f3327-633">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="f3327-634">Ein <see cref="T:System.Threading.CancellationToken" />, das beim Warten auf den Abschluss einer Aufgabe überwacht werden soll.</span><span class="sxs-lookup"><span data-stu-id="f3327-634">A <see cref="T:System.Threading.CancellationToken" /> to observe while waiting for a task to complete.</span></span></param>
        <summary>
            <span data-ttu-id="f3327-635">Initiiert einen asynchronen Vorgang zum Festlegen der Ebene des BLOBs auf einen standard-Speicherkonto an.</span><span class="sxs-lookup"><span data-stu-id="f3327-635">Initiates an asynchronous operation to set the tier of the blob on a standard storage account.</span></span>
            </summary>
        <returns><span data-ttu-id="f3327-636">Ein <see cref="T:System.Threading.Tasks.Task" />-Objekt, das den asynchronen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="f3327-636">A <see cref="T:System.Threading.Tasks.Task" /> object that represents the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="StartCopy">
      <MemberSignature Language="C#" Value="public virtual string StartCopy (Microsoft.WindowsAzure.Storage.Blob.CloudBlockBlob source, Microsoft.WindowsAzure.Storage.AccessCondition sourceAccessCondition = null, Microsoft.WindowsAzure.Storage.AccessCondition destAccessCondition = null, Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options = null, Microsoft.WindowsAzure.Storage.OperationContext operationContext = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance string StartCopy(class Microsoft.WindowsAzure.Storage.Blob.CloudBlockBlob source, class Microsoft.WindowsAzure.Storage.AccessCondition sourceAccessCondition, class Microsoft.WindowsAzure.Storage.AccessCondition destAccessCondition, class Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlockBlob.StartCopy(Microsoft.WindowsAzure.Storage.Blob.CloudBlockBlob,Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="override this.StartCopy : Microsoft.WindowsAzure.Storage.Blob.CloudBlockBlob * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; string" Usage="cloudBlockBlob.StartCopy (source, sourceAccessCondition, destAccessCondition, options, operationContext)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.WindowsAzure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="source" Type="Microsoft.WindowsAzure.Storage.Blob.CloudBlockBlob" />
        <Parameter Name="sourceAccessCondition" Type="Microsoft.WindowsAzure.Storage.AccessCondition" />
        <Parameter Name="destAccessCondition" Type="Microsoft.WindowsAzure.Storage.AccessCondition" />
        <Parameter Name="options" Type="Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="source"><span data-ttu-id="f3327-637">Ein <see cref="T:Microsoft.WindowsAzure.Storage.Blob.CloudBlockBlob" />-Objekt.</span><span class="sxs-lookup"><span data-stu-id="f3327-637">A <see cref="T:Microsoft.WindowsAzure.Storage.Blob.CloudBlockBlob" /> object.</span></span></param>
        <param name="sourceAccessCondition"><span data-ttu-id="f3327-638">Ein <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> -Objekt, das die zugriffsbedingungen für das Quell-Blob darstellt.</span><span class="sxs-lookup"><span data-stu-id="f3327-638">An <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> object that represents the access conditions for the source blob.</span></span> <span data-ttu-id="f3327-639">Wenn <c>null</c>, keine Bedingung verwendet.</span><span class="sxs-lookup"><span data-stu-id="f3327-639">If <c>null</c>, no condition is used.</span></span></param>
        <param name="destAccessCondition"><span data-ttu-id="f3327-640">Ein <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> -Objekt, das die zugriffsbedingungen für das Ziel-Blob darstellt.</span><span class="sxs-lookup"><span data-stu-id="f3327-640">An <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> object that represents the access conditions for the destination blob.</span></span> <span data-ttu-id="f3327-641">Wenn <c>null</c>, keine Bedingung verwendet.</span><span class="sxs-lookup"><span data-stu-id="f3327-641">If <c>null</c>, no condition is used.</span></span></param>
        <param name="options"><span data-ttu-id="f3327-642">Ein <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" /> -Objekt, das zusätzliche Optionen für die Anforderung angibt.</span><span class="sxs-lookup"><span data-stu-id="f3327-642">A <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" /> object that specifies additional options for the request.</span></span> <span data-ttu-id="f3327-643">Wenn <c>null</c>, Standardoptionen gelten für die Anforderung.</span><span class="sxs-lookup"><span data-stu-id="f3327-643">If <c>null</c>, default options are applied to the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="f3327-644">Ein <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> -Objekt, das den Kontext für den aktuellen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="f3327-644">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <summary>
            <span data-ttu-id="f3327-645">Startet einen Vorgang zum Starten von einem anderen Block-Blob-Inhalte, Eigenschaften und Metadaten in diesem Block-Blob kopiert.</span><span class="sxs-lookup"><span data-stu-id="f3327-645">Begins an operation to start copying another block blob's contents, properties, and metadata to this block blob.</span></span>
            </summary>
        <returns><span data-ttu-id="f3327-646">Der Kopiervorgang zugeordnete Kopie-ID.</span><span class="sxs-lookup"><span data-stu-id="f3327-646">The copy ID associated with the copy operation.</span></span></returns>
        <remarks>
            <span data-ttu-id="f3327-647">Diese Methode ruft die Blob-ETag, Uhrzeit der letzten Änderung und Teil den Kopierstatus ab.</span><span class="sxs-lookup"><span data-stu-id="f3327-647">This method fetches the blob's ETag, last-modified time, and part of the copy state.</span></span>
            <span data-ttu-id="f3327-648">Die Kopie-ID und kopieren Sie den Statusfeldern abgerufen werden, und die restliche den Kopierstatus deaktiviert ist.</span><span class="sxs-lookup"><span data-stu-id="f3327-648">The copy ID and copy status fields are fetched, and the rest of the copy state is cleared.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="StartCopy">
      <MemberSignature Language="C#" Value="public virtual string StartCopy (Microsoft.WindowsAzure.Storage.File.CloudFile source, Microsoft.WindowsAzure.Storage.AccessCondition sourceAccessCondition = null, Microsoft.WindowsAzure.Storage.AccessCondition destAccessCondition = null, Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options = null, Microsoft.WindowsAzure.Storage.OperationContext operationContext = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance string StartCopy(class Microsoft.WindowsAzure.Storage.File.CloudFile source, class Microsoft.WindowsAzure.Storage.AccessCondition sourceAccessCondition, class Microsoft.WindowsAzure.Storage.AccessCondition destAccessCondition, class Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlockBlob.StartCopy(Microsoft.WindowsAzure.Storage.File.CloudFile,Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="override this.StartCopy : Microsoft.WindowsAzure.Storage.File.CloudFile * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; string" Usage="cloudBlockBlob.StartCopy (source, sourceAccessCondition, destAccessCondition, options, operationContext)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.WindowsAzure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="source" Type="Microsoft.WindowsAzure.Storage.File.CloudFile" />
        <Parameter Name="sourceAccessCondition" Type="Microsoft.WindowsAzure.Storage.AccessCondition" />
        <Parameter Name="destAccessCondition" Type="Microsoft.WindowsAzure.Storage.AccessCondition" />
        <Parameter Name="options" Type="Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="source"><span data-ttu-id="f3327-649">Ein <see cref="T:Microsoft.WindowsAzure.Storage.File.CloudFile" />-Objekt.</span><span class="sxs-lookup"><span data-stu-id="f3327-649">A <see cref="T:Microsoft.WindowsAzure.Storage.File.CloudFile" /> object.</span></span></param>
        <param name="sourceAccessCondition"><span data-ttu-id="f3327-650">Ein <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> -Objekt, das die zugriffsbedingungen für die Quelldatei darstellt.</span><span class="sxs-lookup"><span data-stu-id="f3327-650">An <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> object that represents the access conditions for the source file.</span></span> <span data-ttu-id="f3327-651">Wenn <c>null</c>, keine Bedingung verwendet.</span><span class="sxs-lookup"><span data-stu-id="f3327-651">If <c>null</c>, no condition is used.</span></span></param>
        <param name="destAccessCondition"><span data-ttu-id="f3327-652">Ein <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> -Objekt, das die zugriffsbedingungen für das Ziel-Blob darstellt.</span><span class="sxs-lookup"><span data-stu-id="f3327-652">An <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> object that represents the access conditions for the destination blob.</span></span> <span data-ttu-id="f3327-653">Wenn <c>null</c>, keine Bedingung verwendet.</span><span class="sxs-lookup"><span data-stu-id="f3327-653">If <c>null</c>, no condition is used.</span></span></param>
        <param name="options"><span data-ttu-id="f3327-654">Ein <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" /> -Objekt, das zusätzliche Optionen für die Anforderung angibt.</span><span class="sxs-lookup"><span data-stu-id="f3327-654">A <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" /> object that specifies additional options for the request.</span></span> <span data-ttu-id="f3327-655">Wenn <c>null</c>, Standardoptionen gelten für die Anforderung.</span><span class="sxs-lookup"><span data-stu-id="f3327-655">If <c>null</c>, default options are applied to the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="f3327-656">Ein <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> -Objekt, das den Kontext für den aktuellen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="f3327-656">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <summary>
            <span data-ttu-id="f3327-657">Startet einen Vorgang zum Starten einer Azure-Datei Inhalt, Eigenschaften und Metadaten in diesem Block-Blob kopiert.</span><span class="sxs-lookup"><span data-stu-id="f3327-657">Begins an operation to start copying an Azure file's contents, properties, and metadata to this block blob.</span></span>
            </summary>
        <returns><span data-ttu-id="f3327-658">Der Kopiervorgang zugeordnete Kopie-ID.</span><span class="sxs-lookup"><span data-stu-id="f3327-658">The copy ID associated with the copy operation.</span></span></returns>
        <remarks>
            <span data-ttu-id="f3327-659">Diese Methode ruft die Blob-ETag, Uhrzeit der letzten Änderung und Teil den Kopierstatus ab.</span><span class="sxs-lookup"><span data-stu-id="f3327-659">This method fetches the blob's ETag, last-modified time, and part of the copy state.</span></span>
            <span data-ttu-id="f3327-660">Die Kopie-ID und kopieren Sie den Statusfeldern abgerufen werden, und die restliche den Kopierstatus deaktiviert ist.</span><span class="sxs-lookup"><span data-stu-id="f3327-660">The copy ID and copy status fields are fetched, and the rest of the copy state is cleared.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="StartCopyAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task&lt;string&gt; StartCopyAsync (Microsoft.WindowsAzure.Storage.Blob.CloudBlockBlob source);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;string&gt; StartCopyAsync(class Microsoft.WindowsAzure.Storage.Blob.CloudBlockBlob source) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlockBlob.StartCopyAsync(Microsoft.WindowsAzure.Storage.Blob.CloudBlockBlob)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function StartCopyAsync (source As CloudBlockBlob) As Task(Of String)" />
      <MemberSignature Language="F#" Value="override this.StartCopyAsync : Microsoft.WindowsAzure.Storage.Blob.CloudBlockBlob -&gt; System.Threading.Tasks.Task&lt;string&gt;" Usage="cloudBlockBlob.StartCopyAsync source" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.WindowsAzure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.String&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="source" Type="Microsoft.WindowsAzure.Storage.Blob.CloudBlockBlob" />
      </Parameters>
      <Docs>
        <param name="source"><span data-ttu-id="f3327-661">Ein <see cref="T:Microsoft.WindowsAzure.Storage.Blob.CloudBlockBlob" />-Objekt.</span><span class="sxs-lookup"><span data-stu-id="f3327-661">A <see cref="T:Microsoft.WindowsAzure.Storage.Blob.CloudBlockBlob" /> object.</span></span></param>
        <summary>
            <span data-ttu-id="f3327-662">Initiiert einen asynchronen Vorgang zum Starten von einem anderen Block-Blob-Inhalte, Eigenschaften und Metadaten in diesem Block-Blob kopiert.</span><span class="sxs-lookup"><span data-stu-id="f3327-662">Initiates an asynchronous operation to start copying another block blob's contents, properties, and metadata to this block blob.</span></span>
            </summary>
        <returns><span data-ttu-id="f3327-663">Ein <see cref="T:System.Threading.Tasks.Task`1" /> Objekt des Typs <c>Zeichenfolge</c> , die den asynchronen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="f3327-663">A <see cref="T:System.Threading.Tasks.Task`1" /> object of type <c>string</c> that represents the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="StartCopyAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task&lt;string&gt; StartCopyAsync (Microsoft.WindowsAzure.Storage.File.CloudFile source);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;string&gt; StartCopyAsync(class Microsoft.WindowsAzure.Storage.File.CloudFile source) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlockBlob.StartCopyAsync(Microsoft.WindowsAzure.Storage.File.CloudFile)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function StartCopyAsync (source As CloudFile) As Task(Of String)" />
      <MemberSignature Language="F#" Value="override this.StartCopyAsync : Microsoft.WindowsAzure.Storage.File.CloudFile -&gt; System.Threading.Tasks.Task&lt;string&gt;" Usage="cloudBlockBlob.StartCopyAsync source" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.WindowsAzure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.String&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="source" Type="Microsoft.WindowsAzure.Storage.File.CloudFile" />
      </Parameters>
      <Docs>
        <param name="source"><span data-ttu-id="f3327-664">Ein <see cref="T:Microsoft.WindowsAzure.Storage.File.CloudFile" />-Objekt.</span><span class="sxs-lookup"><span data-stu-id="f3327-664">A <see cref="T:Microsoft.WindowsAzure.Storage.File.CloudFile" /> object.</span></span></param>
        <summary>
            <span data-ttu-id="f3327-665">Initiiert einen asynchronen Vorgang zum Starten von Inhalt, Eigenschaften und Metadaten einer Datei in diesem Block-Blob kopiert.</span><span class="sxs-lookup"><span data-stu-id="f3327-665">Initiates an asynchronous operation to start copying a file's contents, properties, and metadata to this block blob.</span></span>
            </summary>
        <returns><span data-ttu-id="f3327-666">Ein <see cref="T:System.Threading.Tasks.Task`1" /> Objekt des Typs <c>Zeichenfolge</c> , die den asynchronen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="f3327-666">A <see cref="T:System.Threading.Tasks.Task`1" /> object of type <c>string</c> that represents the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="StartCopyAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task&lt;string&gt; StartCopyAsync (Microsoft.WindowsAzure.Storage.Blob.CloudBlockBlob source, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;string&gt; StartCopyAsync(class Microsoft.WindowsAzure.Storage.Blob.CloudBlockBlob source, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlockBlob.StartCopyAsync(Microsoft.WindowsAzure.Storage.Blob.CloudBlockBlob,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="override this.StartCopyAsync : Microsoft.WindowsAzure.Storage.Blob.CloudBlockBlob * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;string&gt;" Usage="cloudBlockBlob.StartCopyAsync (source, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.WindowsAzure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.String&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="source" Type="Microsoft.WindowsAzure.Storage.Blob.CloudBlockBlob" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="source"><span data-ttu-id="f3327-667">Ein <see cref="T:Microsoft.WindowsAzure.Storage.Blob.CloudBlockBlob" />-Objekt.</span><span class="sxs-lookup"><span data-stu-id="f3327-667">A <see cref="T:Microsoft.WindowsAzure.Storage.Blob.CloudBlockBlob" /> object.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="f3327-668">Ein <see cref="T:System.Threading.CancellationToken" />, das beim Warten auf den Abschluss einer Aufgabe überwacht werden soll.</span><span class="sxs-lookup"><span data-stu-id="f3327-668">A <see cref="T:System.Threading.CancellationToken" /> to observe while waiting for a task to complete.</span></span></param>
        <summary>
            <span data-ttu-id="f3327-669">Initiiert einen asynchronen Vorgang zum Starten von einem anderen Block-Blob-Inhalte, Eigenschaften und Metadaten in diesem Block-Blob kopiert.</span><span class="sxs-lookup"><span data-stu-id="f3327-669">Initiates an asynchronous operation to start copying another block blob's contents, properties, and metadata to this block blob.</span></span>
            </summary>
        <returns><span data-ttu-id="f3327-670">Ein <see cref="T:System.Threading.Tasks.Task`1" /> Objekt des Typs <c>Zeichenfolge</c> , die den asynchronen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="f3327-670">A <see cref="T:System.Threading.Tasks.Task`1" /> object of type <c>string</c> that represents the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="StartCopyAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task&lt;string&gt; StartCopyAsync (Microsoft.WindowsAzure.Storage.File.CloudFile source, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;string&gt; StartCopyAsync(class Microsoft.WindowsAzure.Storage.File.CloudFile source, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlockBlob.StartCopyAsync(Microsoft.WindowsAzure.Storage.File.CloudFile,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="override this.StartCopyAsync : Microsoft.WindowsAzure.Storage.File.CloudFile * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;string&gt;" Usage="cloudBlockBlob.StartCopyAsync (source, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.WindowsAzure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.String&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="source" Type="Microsoft.WindowsAzure.Storage.File.CloudFile" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="source"><span data-ttu-id="f3327-671">Ein <see cref="T:Microsoft.WindowsAzure.Storage.File.CloudFile" />-Objekt.</span><span class="sxs-lookup"><span data-stu-id="f3327-671">A <see cref="T:Microsoft.WindowsAzure.Storage.File.CloudFile" /> object.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="f3327-672">Ein <see cref="T:System.Threading.CancellationToken" />, das beim Warten auf den Abschluss einer Aufgabe überwacht werden soll.</span><span class="sxs-lookup"><span data-stu-id="f3327-672">A <see cref="T:System.Threading.CancellationToken" /> to observe while waiting for a task to complete.</span></span></param>
        <summary>
            <span data-ttu-id="f3327-673">Initiiert einen asynchronen Vorgang zum Starten von Inhalt, Eigenschaften und Metadaten einer Datei in diesem Block-Blob kopiert.</span><span class="sxs-lookup"><span data-stu-id="f3327-673">Initiates an asynchronous operation to start copying a file's contents, properties, and metadata to this block blob.</span></span>
            </summary>
        <returns><span data-ttu-id="f3327-674">Ein <see cref="T:System.Threading.Tasks.Task`1" /> Objekt des Typs <c>Zeichenfolge</c> , die den asynchronen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="f3327-674">A <see cref="T:System.Threading.Tasks.Task`1" /> object of type <c>string</c> that represents the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="StartCopyAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task&lt;string&gt; StartCopyAsync (Microsoft.WindowsAzure.Storage.Blob.CloudBlockBlob source, Microsoft.WindowsAzure.Storage.AccessCondition sourceAccessCondition, Microsoft.WindowsAzure.Storage.AccessCondition destAccessCondition, Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, Microsoft.WindowsAzure.Storage.OperationContext operationContext);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;string&gt; StartCopyAsync(class Microsoft.WindowsAzure.Storage.Blob.CloudBlockBlob source, class Microsoft.WindowsAzure.Storage.AccessCondition sourceAccessCondition, class Microsoft.WindowsAzure.Storage.AccessCondition destAccessCondition, class Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlockBlob.StartCopyAsync(Microsoft.WindowsAzure.Storage.Blob.CloudBlockBlob,Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="override this.StartCopyAsync : Microsoft.WindowsAzure.Storage.Blob.CloudBlockBlob * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Threading.Tasks.Task&lt;string&gt;" Usage="cloudBlockBlob.StartCopyAsync (source, sourceAccessCondition, destAccessCondition, options, operationContext)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.WindowsAzure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.String&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="source" Type="Microsoft.WindowsAzure.Storage.Blob.CloudBlockBlob" />
        <Parameter Name="sourceAccessCondition" Type="Microsoft.WindowsAzure.Storage.AccessCondition" />
        <Parameter Name="destAccessCondition" Type="Microsoft.WindowsAzure.Storage.AccessCondition" />
        <Parameter Name="options" Type="Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="source"><span data-ttu-id="f3327-675">Ein <see cref="T:Microsoft.WindowsAzure.Storage.Blob.CloudBlockBlob" />-Objekt.</span><span class="sxs-lookup"><span data-stu-id="f3327-675">A <see cref="T:Microsoft.WindowsAzure.Storage.Blob.CloudBlockBlob" /> object.</span></span></param>
        <param name="sourceAccessCondition"><span data-ttu-id="f3327-676">Ein <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> -Objekt, das die zugriffsbedingungen für das Quell-Blob darstellt.</span><span class="sxs-lookup"><span data-stu-id="f3327-676">An <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> object that represents the access conditions for the source blob.</span></span> <span data-ttu-id="f3327-677">Wenn <c>null</c>, keine Bedingung verwendet.</span><span class="sxs-lookup"><span data-stu-id="f3327-677">If <c>null</c>, no condition is used.</span></span></param>
        <param name="destAccessCondition"><span data-ttu-id="f3327-678">Ein <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> -Objekt, das die zugriffsbedingungen für das Ziel-Blob darstellt.</span><span class="sxs-lookup"><span data-stu-id="f3327-678">An <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> object that represents the access conditions for the destination blob.</span></span> <span data-ttu-id="f3327-679">Wenn <c>null</c>, keine Bedingung verwendet.</span><span class="sxs-lookup"><span data-stu-id="f3327-679">If <c>null</c>, no condition is used.</span></span></param>
        <param name="options"><span data-ttu-id="f3327-680">Ein <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" /> -Objekt, das zusätzliche Optionen für die Anforderung angibt.</span><span class="sxs-lookup"><span data-stu-id="f3327-680">A <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" /> object that specifies additional options for the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="f3327-681">Ein <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> -Objekt, das den Kontext für den aktuellen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="f3327-681">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <summary>
            <span data-ttu-id="f3327-682">Initiiert einen asynchronen Vorgang zum Starten von einem anderen Block-Blob-Inhalte, Eigenschaften und Metadaten in diesem Block-Blob kopiert.</span><span class="sxs-lookup"><span data-stu-id="f3327-682">Initiates an asynchronous operation to start copying another block blob's contents, properties, and metadata to this block blob.</span></span>
            </summary>
        <returns><span data-ttu-id="f3327-683">Ein <see cref="T:System.Threading.Tasks.Task`1" /> Objekt des Typs <c>Zeichenfolge</c> , die den asynchronen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="f3327-683">A <see cref="T:System.Threading.Tasks.Task`1" /> object of type <c>string</c> that represents the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="StartCopyAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task&lt;string&gt; StartCopyAsync (Microsoft.WindowsAzure.Storage.File.CloudFile source, Microsoft.WindowsAzure.Storage.AccessCondition sourceAccessCondition, Microsoft.WindowsAzure.Storage.AccessCondition destAccessCondition, Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, Microsoft.WindowsAzure.Storage.OperationContext operationContext);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;string&gt; StartCopyAsync(class Microsoft.WindowsAzure.Storage.File.CloudFile source, class Microsoft.WindowsAzure.Storage.AccessCondition sourceAccessCondition, class Microsoft.WindowsAzure.Storage.AccessCondition destAccessCondition, class Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlockBlob.StartCopyAsync(Microsoft.WindowsAzure.Storage.File.CloudFile,Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="override this.StartCopyAsync : Microsoft.WindowsAzure.Storage.File.CloudFile * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Threading.Tasks.Task&lt;string&gt;" Usage="cloudBlockBlob.StartCopyAsync (source, sourceAccessCondition, destAccessCondition, options, operationContext)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.WindowsAzure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.String&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="source" Type="Microsoft.WindowsAzure.Storage.File.CloudFile" />
        <Parameter Name="sourceAccessCondition" Type="Microsoft.WindowsAzure.Storage.AccessCondition" />
        <Parameter Name="destAccessCondition" Type="Microsoft.WindowsAzure.Storage.AccessCondition" />
        <Parameter Name="options" Type="Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="source"><span data-ttu-id="f3327-684">Ein <see cref="T:Microsoft.WindowsAzure.Storage.File.CloudFile" />-Objekt.</span><span class="sxs-lookup"><span data-stu-id="f3327-684">A <see cref="T:Microsoft.WindowsAzure.Storage.File.CloudFile" /> object.</span></span></param>
        <param name="sourceAccessCondition"><span data-ttu-id="f3327-685">Ein <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> -Objekt, das die zugriffsbedingungen für die Quelldatei darstellt.</span><span class="sxs-lookup"><span data-stu-id="f3327-685">An <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> object that represents the access conditions for the source file.</span></span> <span data-ttu-id="f3327-686">Wenn <c>null</c>, keine Bedingung verwendet.</span><span class="sxs-lookup"><span data-stu-id="f3327-686">If <c>null</c>, no condition is used.</span></span></param>
        <param name="destAccessCondition"><span data-ttu-id="f3327-687">Ein <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> -Objekt, das die zugriffsbedingungen für das Ziel-Blob darstellt.</span><span class="sxs-lookup"><span data-stu-id="f3327-687">An <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> object that represents the access conditions for the destination blob.</span></span> <span data-ttu-id="f3327-688">Wenn <c>null</c>, keine Bedingung verwendet.</span><span class="sxs-lookup"><span data-stu-id="f3327-688">If <c>null</c>, no condition is used.</span></span></param>
        <param name="options"><span data-ttu-id="f3327-689">Ein <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" /> -Objekt, das zusätzliche Optionen für die Anforderung angibt.</span><span class="sxs-lookup"><span data-stu-id="f3327-689">A <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" /> object that specifies additional options for the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="f3327-690">Ein <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> -Objekt, das den Kontext für den aktuellen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="f3327-690">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <summary>
            <span data-ttu-id="f3327-691">Initiiert einen asynchronen Vorgang zum Starten von Inhalt, Eigenschaften und Metadaten einer Datei in diesem Block-Blob kopiert.</span><span class="sxs-lookup"><span data-stu-id="f3327-691">Initiates an asynchronous operation to start copying a file's contents, properties, and metadata to this block blob.</span></span>
            </summary>
        <returns><span data-ttu-id="f3327-692">Ein <see cref="T:System.Threading.Tasks.Task`1" /> Objekt des Typs <c>Zeichenfolge</c> , die den asynchronen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="f3327-692">A <see cref="T:System.Threading.Tasks.Task`1" /> object of type <c>string</c> that represents the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="StartCopyAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task&lt;string&gt; StartCopyAsync (Microsoft.WindowsAzure.Storage.Blob.CloudBlockBlob source, Microsoft.WindowsAzure.Storage.AccessCondition sourceAccessCondition, Microsoft.WindowsAzure.Storage.AccessCondition destAccessCondition, Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, Microsoft.WindowsAzure.Storage.OperationContext operationContext, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;string&gt; StartCopyAsync(class Microsoft.WindowsAzure.Storage.Blob.CloudBlockBlob source, class Microsoft.WindowsAzure.Storage.AccessCondition sourceAccessCondition, class Microsoft.WindowsAzure.Storage.AccessCondition destAccessCondition, class Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, class Microsoft.WindowsAzure.Storage.OperationContext operationContext, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlockBlob.StartCopyAsync(Microsoft.WindowsAzure.Storage.Blob.CloudBlockBlob,Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="override this.StartCopyAsync : Microsoft.WindowsAzure.Storage.Blob.CloudBlockBlob * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;string&gt;" Usage="cloudBlockBlob.StartCopyAsync (source, sourceAccessCondition, destAccessCondition, options, operationContext, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.WindowsAzure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.String&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="source" Type="Microsoft.WindowsAzure.Storage.Blob.CloudBlockBlob" />
        <Parameter Name="sourceAccessCondition" Type="Microsoft.WindowsAzure.Storage.AccessCondition" />
        <Parameter Name="destAccessCondition" Type="Microsoft.WindowsAzure.Storage.AccessCondition" />
        <Parameter Name="options" Type="Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="source"><span data-ttu-id="f3327-693">Ein <see cref="T:Microsoft.WindowsAzure.Storage.Blob.CloudBlockBlob" />-Objekt.</span><span class="sxs-lookup"><span data-stu-id="f3327-693">A <see cref="T:Microsoft.WindowsAzure.Storage.Blob.CloudBlockBlob" /> object.</span></span></param>
        <param name="sourceAccessCondition"><span data-ttu-id="f3327-694">Ein <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> -Objekt, das die zugriffsbedingungen für das Quell-Blob darstellt.</span><span class="sxs-lookup"><span data-stu-id="f3327-694">An <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> object that represents the access conditions for the source blob.</span></span> <span data-ttu-id="f3327-695">Wenn <c>null</c>, keine Bedingung verwendet.</span><span class="sxs-lookup"><span data-stu-id="f3327-695">If <c>null</c>, no condition is used.</span></span></param>
        <param name="destAccessCondition"><span data-ttu-id="f3327-696">Ein <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> -Objekt, das die zugriffsbedingungen für das Ziel-Blob darstellt.</span><span class="sxs-lookup"><span data-stu-id="f3327-696">An <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> object that represents the access conditions for the destination blob.</span></span> <span data-ttu-id="f3327-697">Wenn <c>null</c>, keine Bedingung verwendet.</span><span class="sxs-lookup"><span data-stu-id="f3327-697">If <c>null</c>, no condition is used.</span></span></param>
        <param name="options"><span data-ttu-id="f3327-698">Ein <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" /> -Objekt, das zusätzliche Optionen für die Anforderung angibt.</span><span class="sxs-lookup"><span data-stu-id="f3327-698">A <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" /> object that specifies additional options for the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="f3327-699">Ein <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> -Objekt, das den Kontext für den aktuellen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="f3327-699">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="f3327-700">Ein <see cref="T:System.Threading.CancellationToken" />, das beim Warten auf den Abschluss einer Aufgabe überwacht werden soll.</span><span class="sxs-lookup"><span data-stu-id="f3327-700">A <see cref="T:System.Threading.CancellationToken" /> to observe while waiting for a task to complete.</span></span></param>
        <summary>
            <span data-ttu-id="f3327-701">Initiiert einen asynchronen Vorgang zum Starten von einem anderen Block-Blob-Inhalte, Eigenschaften und Metadaten in diesem Block-Blob kopiert.</span><span class="sxs-lookup"><span data-stu-id="f3327-701">Initiates an asynchronous operation to start copying another block blob's contents, properties, and metadata to this block blob.</span></span>
            </summary>
        <returns><span data-ttu-id="f3327-702">Ein <see cref="T:System.Threading.Tasks.Task`1" /> Objekt des Typs <c>Zeichenfolge</c> , die den asynchronen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="f3327-702">A <see cref="T:System.Threading.Tasks.Task`1" /> object of type <c>string</c> that represents the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="StartCopyAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task&lt;string&gt; StartCopyAsync (Microsoft.WindowsAzure.Storage.File.CloudFile source, Microsoft.WindowsAzure.Storage.AccessCondition sourceAccessCondition, Microsoft.WindowsAzure.Storage.AccessCondition destAccessCondition, Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, Microsoft.WindowsAzure.Storage.OperationContext operationContext, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;string&gt; StartCopyAsync(class Microsoft.WindowsAzure.Storage.File.CloudFile source, class Microsoft.WindowsAzure.Storage.AccessCondition sourceAccessCondition, class Microsoft.WindowsAzure.Storage.AccessCondition destAccessCondition, class Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, class Microsoft.WindowsAzure.Storage.OperationContext operationContext, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlockBlob.StartCopyAsync(Microsoft.WindowsAzure.Storage.File.CloudFile,Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="override this.StartCopyAsync : Microsoft.WindowsAzure.Storage.File.CloudFile * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;string&gt;" Usage="cloudBlockBlob.StartCopyAsync (source, sourceAccessCondition, destAccessCondition, options, operationContext, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.WindowsAzure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.String&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="source" Type="Microsoft.WindowsAzure.Storage.File.CloudFile" />
        <Parameter Name="sourceAccessCondition" Type="Microsoft.WindowsAzure.Storage.AccessCondition" />
        <Parameter Name="destAccessCondition" Type="Microsoft.WindowsAzure.Storage.AccessCondition" />
        <Parameter Name="options" Type="Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="source"><span data-ttu-id="f3327-703">Ein <see cref="T:Microsoft.WindowsAzure.Storage.File.CloudFile" />-Objekt.</span><span class="sxs-lookup"><span data-stu-id="f3327-703">A <see cref="T:Microsoft.WindowsAzure.Storage.File.CloudFile" /> object.</span></span></param>
        <param name="sourceAccessCondition"><span data-ttu-id="f3327-704">Ein <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> -Objekt, das die zugriffsbedingungen für die Quelldatei darstellt.</span><span class="sxs-lookup"><span data-stu-id="f3327-704">An <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> object that represents the access conditions for the source file.</span></span> <span data-ttu-id="f3327-705">Wenn <c>null</c>, keine Bedingung verwendet.</span><span class="sxs-lookup"><span data-stu-id="f3327-705">If <c>null</c>, no condition is used.</span></span></param>
        <param name="destAccessCondition"><span data-ttu-id="f3327-706">Ein <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> -Objekt, das die zugriffsbedingungen für das Ziel-Blob darstellt.</span><span class="sxs-lookup"><span data-stu-id="f3327-706">An <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> object that represents the access conditions for the destination blob.</span></span> <span data-ttu-id="f3327-707">Wenn <c>null</c>, keine Bedingung verwendet.</span><span class="sxs-lookup"><span data-stu-id="f3327-707">If <c>null</c>, no condition is used.</span></span></param>
        <param name="options"><span data-ttu-id="f3327-708">Ein <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" /> -Objekt, das zusätzliche Optionen für die Anforderung angibt.</span><span class="sxs-lookup"><span data-stu-id="f3327-708">A <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" /> object that specifies additional options for the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="f3327-709">Ein <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> -Objekt, das den Kontext für den aktuellen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="f3327-709">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="f3327-710">Ein <see cref="T:System.Threading.CancellationToken" />, das beim Warten auf den Abschluss einer Aufgabe überwacht werden soll.</span><span class="sxs-lookup"><span data-stu-id="f3327-710">A <see cref="T:System.Threading.CancellationToken" /> to observe while waiting for a task to complete.</span></span></param>
        <summary>
            <span data-ttu-id="f3327-711">Initiiert einen asynchronen Vorgang zum Starten von Inhalt, Eigenschaften und Metadaten einer Datei in diesem Block-Blob kopiert.</span><span class="sxs-lookup"><span data-stu-id="f3327-711">Initiates an asynchronous operation to start copying a file's contents, properties, and metadata to this block blob.</span></span>
            </summary>
        <returns><span data-ttu-id="f3327-712">Ein <see cref="T:System.Threading.Tasks.Task`1" /> Objekt des Typs <c>Zeichenfolge</c> , die den asynchronen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="f3327-712">A <see cref="T:System.Threading.Tasks.Task`1" /> object of type <c>string</c> that represents the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="StreamWriteSizeInBytes">
      <MemberSignature Language="C#" Value="public int StreamWriteSizeInBytes { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 StreamWriteSizeInBytes" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.Blob.CloudBlockBlob.StreamWriteSizeInBytes" />
      <MemberSignature Language="VB.NET" Value="Public Property StreamWriteSizeInBytes As Integer" />
      <MemberSignature Language="F#" Value="member this.StreamWriteSizeInBytes : int with get, set" Usage="Microsoft.WindowsAzure.Storage.Blob.CloudBlockBlob.StreamWriteSizeInBytes" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:Microsoft.WindowsAzure.Storage.Blob.ICloudBlob.StreamWriteSizeInBytes</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="f3327-713">Ruft ab oder legt die Blockgröße zum Schreiben in ein Block-Blob.</span><span class="sxs-lookup"><span data-stu-id="f3327-713">Gets or sets the block size for writing to a block blob.</span></span>
            </summary>
        <value><span data-ttu-id="f3327-714">Die Größe eines Blocks in Bytes von 16 KB und 100 MB liegen.</span><span class="sxs-lookup"><span data-stu-id="f3327-714">The size of a block, in bytes, ranging from between 16 KB and 100 MB inclusive.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UploadFromByteArray">
      <MemberSignature Language="C#" Value="public virtual void UploadFromByteArray (byte[] buffer, int index, int count, Microsoft.WindowsAzure.Storage.AccessCondition accessCondition = null, Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options = null, Microsoft.WindowsAzure.Storage.OperationContext operationContext = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void UploadFromByteArray(unsigned int8[] buffer, int32 index, int32 count, class Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, class Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlockBlob.UploadFromByteArray(System.Byte[],System.Int32,System.Int32,Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="abstract member UploadFromByteArray : byte[] * int * int * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; unit&#xA;override this.UploadFromByteArray : byte[] * int * int * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; unit" Usage="cloudBlockBlob.UploadFromByteArray (buffer, index, count, accessCondition, options, operationContext)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.WindowsAzure.Storage.Blob.ICloudBlob.UploadFromByteArray(System.Byte[],System.Int32,System.Int32,Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.WindowsAzure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="buffer" Type="System.Byte[]" />
        <Parameter Name="index" Type="System.Int32" />
        <Parameter Name="count" Type="System.Int32" />
        <Parameter Name="accessCondition" Type="Microsoft.WindowsAzure.Storage.AccessCondition" />
        <Parameter Name="options" Type="Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="buffer"><span data-ttu-id="f3327-715">Ein Bytearray.</span><span class="sxs-lookup"><span data-stu-id="f3327-715">An array of bytes.</span></span></param>
        <param name="index"><span data-ttu-id="f3327-716">Der nullbasierte Byteoffset im Puffer, ab dem Bytes in den Blob hochgeladen werden soll.</span><span class="sxs-lookup"><span data-stu-id="f3327-716">The zero-based byte offset in buffer at which to begin uploading bytes to the blob.</span></span></param>
        <param name="count"><span data-ttu-id="f3327-717">Die Anzahl der Bytes, die in das Blob geschrieben werden.</span><span class="sxs-lookup"><span data-stu-id="f3327-717">The number of bytes to be written to the blob.</span></span></param>
        <param name="accessCondition"><span data-ttu-id="f3327-718">Ein <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> -Objekt, das die Bedingung, die erfüllt sein müssen, damit die Anforderung darstellt, um den Vorgang fortzusetzen.</span><span class="sxs-lookup"><span data-stu-id="f3327-718">An <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> object that represents the condition that must be met in order for the request to proceed.</span></span></param>
        <param name="options"><span data-ttu-id="f3327-719">Ein <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" /> -Objekt, das zusätzliche Optionen für die Anforderung angibt.</span><span class="sxs-lookup"><span data-stu-id="f3327-719">A <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" /> object that specifies additional options for the request.</span></span> <span data-ttu-id="f3327-720">Wenn <c>null</c>, Standardoptionen gelten für die Anforderung.</span><span class="sxs-lookup"><span data-stu-id="f3327-720">If <c>null</c>, default options are applied to the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="f3327-721">Ein <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> -Objekt, das den Kontext für den aktuellen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="f3327-721">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <summary>
            <span data-ttu-id="f3327-722">Lädt den Inhalt eines Bytearrays in ein Blob hoch.</span><span class="sxs-lookup"><span data-stu-id="f3327-722">Uploads the contents of a byte array to a blob.</span></span> <span data-ttu-id="f3327-723">Wenn das Blob bereits vorhanden ist, wird sie überschrieben.</span><span class="sxs-lookup"><span data-stu-id="f3327-723">If the blob already exists, it will be overwritten.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UploadFromByteArrayAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task UploadFromByteArrayAsync (byte[] buffer, int index, int count);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task UploadFromByteArrayAsync(unsigned int8[] buffer, int32 index, int32 count) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlockBlob.UploadFromByteArrayAsync(System.Byte[],System.Int32,System.Int32)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function UploadFromByteArrayAsync (buffer As Byte(), index As Integer, count As Integer) As Task" />
      <MemberSignature Language="F#" Value="abstract member UploadFromByteArrayAsync : byte[] * int * int -&gt; System.Threading.Tasks.Task&#xA;override this.UploadFromByteArrayAsync : byte[] * int * int -&gt; System.Threading.Tasks.Task" Usage="cloudBlockBlob.UploadFromByteArrayAsync (buffer, index, count)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.WindowsAzure.Storage.Blob.ICloudBlob.UploadFromByteArrayAsync(System.Byte[],System.Int32,System.Int32)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.WindowsAzure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="buffer" Type="System.Byte[]" />
        <Parameter Name="index" Type="System.Int32" />
        <Parameter Name="count" Type="System.Int32" />
      </Parameters>
      <Docs>
        <param name="buffer"><span data-ttu-id="f3327-724">Ein Bytearray.</span><span class="sxs-lookup"><span data-stu-id="f3327-724">An array of bytes.</span></span></param>
        <param name="index"><span data-ttu-id="f3327-725">Der nullbasierte Byteoffset im Puffer, ab dem Bytes in den Blob hochgeladen werden soll.</span><span class="sxs-lookup"><span data-stu-id="f3327-725">The zero-based byte offset in buffer at which to begin uploading bytes to the blob.</span></span></param>
        <param name="count"><span data-ttu-id="f3327-726">Die Anzahl der Bytes, die in das Blob geschrieben werden.</span><span class="sxs-lookup"><span data-stu-id="f3327-726">The number of bytes to be written to the blob.</span></span></param>
        <summary>
            <span data-ttu-id="f3327-727">Initiiert einen asynchronen Vorgang, um den Inhalt eines Bytearrays in ein Blob hochladen.</span><span class="sxs-lookup"><span data-stu-id="f3327-727">Initiates an asynchronous operation to upload the contents of a byte array to a blob.</span></span> <span data-ttu-id="f3327-728">Wenn das Blob bereits vorhanden ist, wird sie überschrieben.</span><span class="sxs-lookup"><span data-stu-id="f3327-728">If the blob already exists, it will be overwritten.</span></span>
            </summary>
        <returns><span data-ttu-id="f3327-729">Ein <see cref="T:System.Threading.Tasks.Task" />-Objekt, das den asynchronen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="f3327-729">A <see cref="T:System.Threading.Tasks.Task" /> object that represents the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UploadFromByteArrayAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task UploadFromByteArrayAsync (byte[] buffer, int index, int count, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task UploadFromByteArrayAsync(unsigned int8[] buffer, int32 index, int32 count, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlockBlob.UploadFromByteArrayAsync(System.Byte[],System.Int32,System.Int32,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member UploadFromByteArrayAsync : byte[] * int * int * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&#xA;override this.UploadFromByteArrayAsync : byte[] * int * int * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="cloudBlockBlob.UploadFromByteArrayAsync (buffer, index, count, cancellationToken)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.WindowsAzure.Storage.Blob.ICloudBlob.UploadFromByteArrayAsync(System.Byte[],System.Int32,System.Int32,System.Threading.CancellationToken)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.WindowsAzure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="buffer" Type="System.Byte[]" />
        <Parameter Name="index" Type="System.Int32" />
        <Parameter Name="count" Type="System.Int32" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="buffer"><span data-ttu-id="f3327-730">Ein Bytearray.</span><span class="sxs-lookup"><span data-stu-id="f3327-730">An array of bytes.</span></span></param>
        <param name="index"><span data-ttu-id="f3327-731">Der nullbasierte Byteoffset im Puffer, ab dem Bytes in den Blob hochgeladen werden soll.</span><span class="sxs-lookup"><span data-stu-id="f3327-731">The zero-based byte offset in buffer at which to begin uploading bytes to the blob.</span></span></param>
        <param name="count"><span data-ttu-id="f3327-732">Die Anzahl der Bytes, die in das Blob geschrieben werden.</span><span class="sxs-lookup"><span data-stu-id="f3327-732">The number of bytes to be written to the blob.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="f3327-733">Ein <see cref="T:System.Threading.CancellationToken" />, das beim Warten auf den Abschluss einer Aufgabe überwacht werden soll.</span><span class="sxs-lookup"><span data-stu-id="f3327-733">A <see cref="T:System.Threading.CancellationToken" /> to observe while waiting for a task to complete.</span></span></param>
        <summary>
            <span data-ttu-id="f3327-734">Initiiert einen asynchronen Vorgang, um den Inhalt eines Bytearrays in ein Blob hochladen.</span><span class="sxs-lookup"><span data-stu-id="f3327-734">Initiates an asynchronous operation to upload the contents of a byte array to a blob.</span></span> <span data-ttu-id="f3327-735">Wenn das Blob bereits vorhanden ist, wird sie überschrieben.</span><span class="sxs-lookup"><span data-stu-id="f3327-735">If the blob already exists, it will be overwritten.</span></span>
            </summary>
        <returns><span data-ttu-id="f3327-736">Ein <see cref="T:System.Threading.Tasks.Task" />-Objekt, das den asynchronen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="f3327-736">A <see cref="T:System.Threading.Tasks.Task" /> object that represents the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UploadFromByteArrayAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task UploadFromByteArrayAsync (byte[] buffer, int index, int count, Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, Microsoft.WindowsAzure.Storage.OperationContext operationContext);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task UploadFromByteArrayAsync(unsigned int8[] buffer, int32 index, int32 count, class Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, class Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlockBlob.UploadFromByteArrayAsync(System.Byte[],System.Int32,System.Int32,Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="abstract member UploadFromByteArrayAsync : byte[] * int * int * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Threading.Tasks.Task&#xA;override this.UploadFromByteArrayAsync : byte[] * int * int * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Threading.Tasks.Task" Usage="cloudBlockBlob.UploadFromByteArrayAsync (buffer, index, count, accessCondition, options, operationContext)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.WindowsAzure.Storage.Blob.ICloudBlob.UploadFromByteArrayAsync(System.Byte[],System.Int32,System.Int32,Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.WindowsAzure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="buffer" Type="System.Byte[]" />
        <Parameter Name="index" Type="System.Int32" />
        <Parameter Name="count" Type="System.Int32" />
        <Parameter Name="accessCondition" Type="Microsoft.WindowsAzure.Storage.AccessCondition" />
        <Parameter Name="options" Type="Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="buffer"><span data-ttu-id="f3327-737">Ein Bytearray.</span><span class="sxs-lookup"><span data-stu-id="f3327-737">An array of bytes.</span></span></param>
        <param name="index"><span data-ttu-id="f3327-738">Der nullbasierte Byteoffset im Puffer, ab dem Bytes in den Blob hochgeladen werden soll.</span><span class="sxs-lookup"><span data-stu-id="f3327-738">The zero-based byte offset in buffer at which to begin uploading bytes to the blob.</span></span></param>
        <param name="count"><span data-ttu-id="f3327-739">Die Anzahl der Bytes, die in das Blob geschrieben werden.</span><span class="sxs-lookup"><span data-stu-id="f3327-739">The number of bytes to be written to the blob.</span></span></param>
        <param name="accessCondition"><span data-ttu-id="f3327-740">Ein <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> -Objekt, das die Bedingung, die erfüllt sein müssen, damit die Anforderung darstellt, um den Vorgang fortzusetzen.</span><span class="sxs-lookup"><span data-stu-id="f3327-740">An <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> object that represents the condition that must be met in order for the request to proceed.</span></span></param>
        <param name="options"><span data-ttu-id="f3327-741">Ein <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" /> -Objekt, das zusätzliche Optionen für die Anforderung angibt.</span><span class="sxs-lookup"><span data-stu-id="f3327-741">A <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" /> object that specifies additional options for the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="f3327-742">Ein <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> -Objekt, das den Kontext für den aktuellen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="f3327-742">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <summary>
            <span data-ttu-id="f3327-743">Initiiert einen asynchronen Vorgang, um den Inhalt eines Bytearrays in ein Blob hochladen.</span><span class="sxs-lookup"><span data-stu-id="f3327-743">Initiates an asynchronous operation to upload the contents of a byte array to a blob.</span></span> <span data-ttu-id="f3327-744">Wenn das Blob bereits vorhanden ist, wird sie überschrieben.</span><span class="sxs-lookup"><span data-stu-id="f3327-744">If the blob already exists, it will be overwritten.</span></span>
            </summary>
        <returns><span data-ttu-id="f3327-745">Ein <see cref="T:System.Threading.Tasks.Task" />-Objekt, das den asynchronen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="f3327-745">A <see cref="T:System.Threading.Tasks.Task" /> object that represents the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UploadFromByteArrayAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task UploadFromByteArrayAsync (byte[] buffer, int index, int count, Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, Microsoft.WindowsAzure.Storage.OperationContext operationContext, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task UploadFromByteArrayAsync(unsigned int8[] buffer, int32 index, int32 count, class Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, class Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, class Microsoft.WindowsAzure.Storage.OperationContext operationContext, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlockBlob.UploadFromByteArrayAsync(System.Byte[],System.Int32,System.Int32,Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member UploadFromByteArrayAsync : byte[] * int * int * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&#xA;override this.UploadFromByteArrayAsync : byte[] * int * int * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="cloudBlockBlob.UploadFromByteArrayAsync (buffer, index, count, accessCondition, options, operationContext, cancellationToken)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.WindowsAzure.Storage.Blob.ICloudBlob.UploadFromByteArrayAsync(System.Byte[],System.Int32,System.Int32,Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext,System.Threading.CancellationToken)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.WindowsAzure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="buffer" Type="System.Byte[]" />
        <Parameter Name="index" Type="System.Int32" />
        <Parameter Name="count" Type="System.Int32" />
        <Parameter Name="accessCondition" Type="Microsoft.WindowsAzure.Storage.AccessCondition" />
        <Parameter Name="options" Type="Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="buffer"><span data-ttu-id="f3327-746">Ein Bytearray.</span><span class="sxs-lookup"><span data-stu-id="f3327-746">An array of bytes.</span></span></param>
        <param name="index"><span data-ttu-id="f3327-747">Der nullbasierte Byteoffset im Puffer, ab dem Bytes in den Blob hochgeladen werden soll.</span><span class="sxs-lookup"><span data-stu-id="f3327-747">The zero-based byte offset in buffer at which to begin uploading bytes to the blob.</span></span></param>
        <param name="count"><span data-ttu-id="f3327-748">Die Anzahl der Bytes, die in das Blob geschrieben werden.</span><span class="sxs-lookup"><span data-stu-id="f3327-748">The number of bytes to be written to the blob.</span></span></param>
        <param name="accessCondition"><span data-ttu-id="f3327-749">Ein <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> -Objekt, das die Bedingung, die erfüllt sein müssen, damit die Anforderung darstellt, um den Vorgang fortzusetzen.</span><span class="sxs-lookup"><span data-stu-id="f3327-749">An <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> object that represents the condition that must be met in order for the request to proceed.</span></span></param>
        <param name="options"><span data-ttu-id="f3327-750">Ein <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" /> -Objekt, das zusätzliche Optionen für die Anforderung angibt.</span><span class="sxs-lookup"><span data-stu-id="f3327-750">A <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" /> object that specifies additional options for the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="f3327-751">Ein <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> -Objekt, das den Kontext für den aktuellen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="f3327-751">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="f3327-752">Ein <see cref="T:System.Threading.CancellationToken" />, das beim Warten auf den Abschluss einer Aufgabe überwacht werden soll.</span><span class="sxs-lookup"><span data-stu-id="f3327-752">A <see cref="T:System.Threading.CancellationToken" /> to observe while waiting for a task to complete.</span></span></param>
        <summary>
            <span data-ttu-id="f3327-753">Initiiert einen asynchronen Vorgang, um den Inhalt eines Bytearrays in ein Blob hochladen.</span><span class="sxs-lookup"><span data-stu-id="f3327-753">Initiates an asynchronous operation to upload the contents of a byte array to a blob.</span></span> <span data-ttu-id="f3327-754">Wenn das Blob bereits vorhanden ist, wird sie überschrieben.</span><span class="sxs-lookup"><span data-stu-id="f3327-754">If the blob already exists, it will be overwritten.</span></span>
            </summary>
        <returns><span data-ttu-id="f3327-755">Ein <see cref="T:System.Threading.Tasks.Task" />-Objekt, das den asynchronen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="f3327-755">A <see cref="T:System.Threading.Tasks.Task" /> object that represents the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UploadFromByteArrayAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task UploadFromByteArrayAsync (byte[] buffer, int index, int count, Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, Microsoft.WindowsAzure.Storage.OperationContext operationContext, IProgress&lt;Microsoft.WindowsAzure.Storage.Core.Util.StorageProgress&gt; progressHandler, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task UploadFromByteArrayAsync(unsigned int8[] buffer, int32 index, int32 count, class Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, class Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, class Microsoft.WindowsAzure.Storage.OperationContext operationContext, class System.IProgress`1&lt;class Microsoft.WindowsAzure.Storage.Core.Util.StorageProgress&gt; progressHandler, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlockBlob.UploadFromByteArrayAsync(System.Byte[],System.Int32,System.Int32,Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext,System.IProgress{Microsoft.WindowsAzure.Storage.Core.Util.StorageProgress},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member UploadFromByteArrayAsync : byte[] * int * int * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * IProgress&lt;Microsoft.WindowsAzure.Storage.Core.Util.StorageProgress&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&#xA;override this.UploadFromByteArrayAsync : byte[] * int * int * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * IProgress&lt;Microsoft.WindowsAzure.Storage.Core.Util.StorageProgress&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="cloudBlockBlob.UploadFromByteArrayAsync (buffer, index, count, accessCondition, options, operationContext, progressHandler, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.WindowsAzure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="buffer" Type="System.Byte[]" />
        <Parameter Name="index" Type="System.Int32" />
        <Parameter Name="count" Type="System.Int32" />
        <Parameter Name="accessCondition" Type="Microsoft.WindowsAzure.Storage.AccessCondition" />
        <Parameter Name="options" Type="Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
        <Parameter Name="progressHandler" Type="System.IProgress&lt;Microsoft.WindowsAzure.Storage.Core.Util.StorageProgress&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="buffer"><span data-ttu-id="f3327-756">Ein Bytearray.</span><span class="sxs-lookup"><span data-stu-id="f3327-756">An array of bytes.</span></span></param>
        <param name="index"><span data-ttu-id="f3327-757">Der nullbasierte Byteoffset im Puffer, ab dem Bytes in den Blob hochgeladen werden soll.</span><span class="sxs-lookup"><span data-stu-id="f3327-757">The zero-based byte offset in buffer at which to begin uploading bytes to the blob.</span></span></param>
        <param name="count"><span data-ttu-id="f3327-758">Die Anzahl der Bytes, die in das Blob geschrieben werden.</span><span class="sxs-lookup"><span data-stu-id="f3327-758">The number of bytes to be written to the blob.</span></span></param>
        <param name="accessCondition"><span data-ttu-id="f3327-759">Ein <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> -Objekt, das die Bedingung, die erfüllt sein müssen, damit die Anforderung darstellt, um den Vorgang fortzusetzen.</span><span class="sxs-lookup"><span data-stu-id="f3327-759">An <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> object that represents the condition that must be met in order for the request to proceed.</span></span></param>
        <param name="options"><span data-ttu-id="f3327-760">Ein <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" /> -Objekt, das zusätzliche Optionen für die Anforderung angibt.</span><span class="sxs-lookup"><span data-stu-id="f3327-760">A <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" /> object that specifies additional options for the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="f3327-761">Ein <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> -Objekt, das den Kontext für den aktuellen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="f3327-761">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <param name="progressHandler"> <span data-ttu-id="f3327-762">Ein <see cref="T:System.IProgress`1" /> Objekt behandelt <see cref="T:Microsoft.WindowsAzure.Storage.Core.Util.StorageProgress" /> Nachrichten.</span><span class="sxs-lookup"><span data-stu-id="f3327-762">A <see cref="T:System.IProgress`1" /> object to handle <see cref="T:Microsoft.WindowsAzure.Storage.Core.Util.StorageProgress" /> messages.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="f3327-763">Ein <see cref="T:System.Threading.CancellationToken" />, das beim Warten auf den Abschluss einer Aufgabe überwacht werden soll.</span><span class="sxs-lookup"><span data-stu-id="f3327-763">A <see cref="T:System.Threading.CancellationToken" /> to observe while waiting for a task to complete.</span></span></param>
        <summary>
            <span data-ttu-id="f3327-764">Initiiert einen asynchronen Vorgang, um den Inhalt eines Bytearrays in ein Blob hochladen.</span><span class="sxs-lookup"><span data-stu-id="f3327-764">Initiates an asynchronous operation to upload the contents of a byte array to a blob.</span></span> <span data-ttu-id="f3327-765">Wenn das Blob bereits vorhanden ist, wird sie überschrieben.</span><span class="sxs-lookup"><span data-stu-id="f3327-765">If the blob already exists, it will be overwritten.</span></span>
            </summary>
        <returns><span data-ttu-id="f3327-766">Ein <see cref="T:System.Threading.Tasks.Task" />-Objekt, das den asynchronen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="f3327-766">A <see cref="T:System.Threading.Tasks.Task" /> object that represents the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UploadFromFile">
      <MemberSignature Language="C#" Value="public virtual void UploadFromFile (string path, Microsoft.WindowsAzure.Storage.AccessCondition accessCondition = null, Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options = null, Microsoft.WindowsAzure.Storage.OperationContext operationContext = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void UploadFromFile(string path, class Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, class Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlockBlob.UploadFromFile(System.String,Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="abstract member UploadFromFile : string * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; unit&#xA;override this.UploadFromFile : string * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; unit" Usage="cloudBlockBlob.UploadFromFile (path, accessCondition, options, operationContext)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.WindowsAzure.Storage.Blob.ICloudBlob.UploadFromFile(System.String,Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.WindowsAzure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="path" Type="System.String" />
        <Parameter Name="accessCondition" Type="Microsoft.WindowsAzure.Storage.AccessCondition" />
        <Parameter Name="options" Type="Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="path"><span data-ttu-id="f3327-767">Eine Zeichenfolge mit den Dateipfad der Blob-Inhalte bereitstellen.</span><span class="sxs-lookup"><span data-stu-id="f3327-767">A string containing the file path providing the blob content.</span></span></param>
        <param name="accessCondition"><span data-ttu-id="f3327-768">Ein <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> -Objekt, das die Bedingung, die erfüllt sein müssen, damit die Anforderung darstellt, um den Vorgang fortzusetzen.</span><span class="sxs-lookup"><span data-stu-id="f3327-768">An <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> object that represents the condition that must be met in order for the request to proceed.</span></span></param>
        <param name="options"><span data-ttu-id="f3327-769">Ein <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" /> -Objekt, das zusätzliche Optionen für die Anforderung angibt.</span><span class="sxs-lookup"><span data-stu-id="f3327-769">A <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" /> object that specifies additional options for the request.</span></span> <span data-ttu-id="f3327-770">Wenn <c>null</c>, Standardoptionen gelten für die Anforderung.</span><span class="sxs-lookup"><span data-stu-id="f3327-770">If <c>null</c>, default options are applied to the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="f3327-771">Ein <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> -Objekt, das den Kontext für den aktuellen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="f3327-771">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <summary>
            <span data-ttu-id="f3327-772">Lädt eine Datei in den Blob-Dienst hoch.</span><span class="sxs-lookup"><span data-stu-id="f3327-772">Uploads a file to the Blob service.</span></span> <span data-ttu-id="f3327-773">Wenn das Blob bereits vorhanden ist, wird sie überschrieben.</span><span class="sxs-lookup"><span data-stu-id="f3327-773">If the blob already exists, it will be overwritten.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UploadFromFileAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task UploadFromFileAsync (string path);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task UploadFromFileAsync(string path) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlockBlob.UploadFromFileAsync(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function UploadFromFileAsync (path As String) As Task" />
      <MemberSignature Language="F#" Value="abstract member UploadFromFileAsync : string -&gt; System.Threading.Tasks.Task&#xA;override this.UploadFromFileAsync : string -&gt; System.Threading.Tasks.Task" Usage="cloudBlockBlob.UploadFromFileAsync path" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.WindowsAzure.Storage.Blob.ICloudBlob.UploadFromFileAsync(System.String)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.WindowsAzure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="path" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="path"><span data-ttu-id="f3327-774">Eine Zeichenfolge mit den Dateipfad der Blob-Inhalte bereitstellen.</span><span class="sxs-lookup"><span data-stu-id="f3327-774">A string containing the file path providing the blob content.</span></span></param>
        <summary>
            <span data-ttu-id="f3327-775">Initiiert einen asynchronen Vorgang zum Hochladen einer Datei in ein Blob.</span><span class="sxs-lookup"><span data-stu-id="f3327-775">Initiates an asynchronous operation to upload a file to a blob.</span></span> <span data-ttu-id="f3327-776">Wenn das Blob bereits vorhanden ist, wird sie überschrieben.</span><span class="sxs-lookup"><span data-stu-id="f3327-776">If the blob already exists, it will be overwritten.</span></span>
            </summary>
        <returns><span data-ttu-id="f3327-777">Ein <see cref="T:System.Threading.Tasks.Task" />-Objekt, das den asynchronen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="f3327-777">A <see cref="T:System.Threading.Tasks.Task" /> object that represents the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UploadFromFileAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task UploadFromFileAsync (string path, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task UploadFromFileAsync(string path, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlockBlob.UploadFromFileAsync(System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member UploadFromFileAsync : string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&#xA;override this.UploadFromFileAsync : string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="cloudBlockBlob.UploadFromFileAsync (path, cancellationToken)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.WindowsAzure.Storage.Blob.ICloudBlob.UploadFromFileAsync(System.String,System.Threading.CancellationToken)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.WindowsAzure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="path" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="path"><span data-ttu-id="f3327-778">Eine Zeichenfolge mit den Dateipfad der Blob-Inhalte bereitstellen.</span><span class="sxs-lookup"><span data-stu-id="f3327-778">A string containing the file path providing the blob content.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="f3327-779">Ein <see cref="T:System.Threading.CancellationToken" />, das beim Warten auf den Abschluss einer Aufgabe überwacht werden soll.</span><span class="sxs-lookup"><span data-stu-id="f3327-779">A <see cref="T:System.Threading.CancellationToken" /> to observe while waiting for a task to complete.</span></span></param>
        <summary>
            <span data-ttu-id="f3327-780">Initiiert einen asynchronen Vorgang zum Hochladen einer Datei in ein Blob.</span><span class="sxs-lookup"><span data-stu-id="f3327-780">Initiates an asynchronous operation to upload a file to a blob.</span></span> <span data-ttu-id="f3327-781">Wenn das Blob bereits vorhanden ist, wird sie überschrieben.</span><span class="sxs-lookup"><span data-stu-id="f3327-781">If the blob already exists, it will be overwritten.</span></span>
            </summary>
        <returns><span data-ttu-id="f3327-782">Ein <see cref="T:System.Threading.Tasks.Task" />-Objekt, das den asynchronen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="f3327-782">A <see cref="T:System.Threading.Tasks.Task" /> object that represents the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UploadFromFileAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task UploadFromFileAsync (string path, Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, Microsoft.WindowsAzure.Storage.OperationContext operationContext);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task UploadFromFileAsync(string path, class Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, class Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlockBlob.UploadFromFileAsync(System.String,Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="abstract member UploadFromFileAsync : string * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Threading.Tasks.Task&#xA;override this.UploadFromFileAsync : string * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Threading.Tasks.Task" Usage="cloudBlockBlob.UploadFromFileAsync (path, accessCondition, options, operationContext)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.WindowsAzure.Storage.Blob.ICloudBlob.UploadFromFileAsync(System.String,Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.WindowsAzure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="path" Type="System.String" />
        <Parameter Name="accessCondition" Type="Microsoft.WindowsAzure.Storage.AccessCondition" />
        <Parameter Name="options" Type="Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="path"><span data-ttu-id="f3327-783">Eine Zeichenfolge mit den Dateipfad der Blob-Inhalte bereitstellen.</span><span class="sxs-lookup"><span data-stu-id="f3327-783">A string containing the file path providing the blob content.</span></span></param>
        <param name="accessCondition"><span data-ttu-id="f3327-784">Ein <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> -Objekt, das die Bedingung, die erfüllt sein müssen, damit die Anforderung darstellt, um den Vorgang fortzusetzen.</span><span class="sxs-lookup"><span data-stu-id="f3327-784">An <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> object that represents the condition that must be met in order for the request to proceed.</span></span></param>
        <param name="options"><span data-ttu-id="f3327-785">Ein <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" /> -Objekt, das zusätzliche Optionen für die Anforderung angibt.</span><span class="sxs-lookup"><span data-stu-id="f3327-785">A <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" /> object that specifies additional options for the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="f3327-786">Ein <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> -Objekt, das den Kontext für den aktuellen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="f3327-786">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <summary>
            <span data-ttu-id="f3327-787">Initiiert einen asynchronen Vorgang zum Hochladen einer Datei in ein Blob.</span><span class="sxs-lookup"><span data-stu-id="f3327-787">Initiates an asynchronous operation to upload a file to a blob.</span></span> <span data-ttu-id="f3327-788">Wenn das Blob bereits vorhanden ist, wird sie überschrieben.</span><span class="sxs-lookup"><span data-stu-id="f3327-788">If the blob already exists, it will be overwritten.</span></span>
            </summary>
        <returns><span data-ttu-id="f3327-789">Ein <see cref="T:System.Threading.Tasks.Task" />-Objekt, das den asynchronen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="f3327-789">A <see cref="T:System.Threading.Tasks.Task" /> object that represents the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UploadFromFileAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task UploadFromFileAsync (string path, Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, Microsoft.WindowsAzure.Storage.OperationContext operationContext, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task UploadFromFileAsync(string path, class Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, class Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, class Microsoft.WindowsAzure.Storage.OperationContext operationContext, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlockBlob.UploadFromFileAsync(System.String,Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member UploadFromFileAsync : string * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&#xA;override this.UploadFromFileAsync : string * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="cloudBlockBlob.UploadFromFileAsync (path, accessCondition, options, operationContext, cancellationToken)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.WindowsAzure.Storage.Blob.ICloudBlob.UploadFromFileAsync(System.String,Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext,System.Threading.CancellationToken)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.WindowsAzure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="path" Type="System.String" />
        <Parameter Name="accessCondition" Type="Microsoft.WindowsAzure.Storage.AccessCondition" />
        <Parameter Name="options" Type="Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="path"><span data-ttu-id="f3327-790">Eine Zeichenfolge mit den Dateipfad der Blob-Inhalte bereitstellen.</span><span class="sxs-lookup"><span data-stu-id="f3327-790">A string containing the file path providing the blob content.</span></span></param>
        <param name="accessCondition"><span data-ttu-id="f3327-791">Ein <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> -Objekt, das die Bedingung, die erfüllt sein müssen, damit die Anforderung darstellt, um den Vorgang fortzusetzen.</span><span class="sxs-lookup"><span data-stu-id="f3327-791">An <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> object that represents the condition that must be met in order for the request to proceed.</span></span></param>
        <param name="options"><span data-ttu-id="f3327-792">Ein <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" /> -Objekt, das zusätzliche Optionen für die Anforderung angibt.</span><span class="sxs-lookup"><span data-stu-id="f3327-792">A <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" /> object that specifies additional options for the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="f3327-793">Ein <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> -Objekt, das den Kontext für den aktuellen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="f3327-793">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="f3327-794">Ein <see cref="T:System.Threading.CancellationToken" />, das beim Warten auf den Abschluss einer Aufgabe überwacht werden soll.</span><span class="sxs-lookup"><span data-stu-id="f3327-794">A <see cref="T:System.Threading.CancellationToken" /> to observe while waiting for a task to complete.</span></span></param>
        <summary>
            <span data-ttu-id="f3327-795">Initiiert einen asynchronen Vorgang zum Hochladen einer Datei in ein Blob.</span><span class="sxs-lookup"><span data-stu-id="f3327-795">Initiates an asynchronous operation to upload a file to a blob.</span></span> <span data-ttu-id="f3327-796">Wenn das Blob bereits vorhanden ist, wird sie überschrieben.</span><span class="sxs-lookup"><span data-stu-id="f3327-796">If the blob already exists, it will be overwritten.</span></span>
            </summary>
        <returns><span data-ttu-id="f3327-797">Ein <see cref="T:System.Threading.Tasks.Task" />-Objekt, das den asynchronen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="f3327-797">A <see cref="T:System.Threading.Tasks.Task" /> object that represents the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UploadFromFileAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task UploadFromFileAsync (string path, Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, Microsoft.WindowsAzure.Storage.OperationContext operationContext, IProgress&lt;Microsoft.WindowsAzure.Storage.Core.Util.StorageProgress&gt; progressHandler, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task UploadFromFileAsync(string path, class Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, class Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, class Microsoft.WindowsAzure.Storage.OperationContext operationContext, class System.IProgress`1&lt;class Microsoft.WindowsAzure.Storage.Core.Util.StorageProgress&gt; progressHandler, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlockBlob.UploadFromFileAsync(System.String,Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext,System.IProgress{Microsoft.WindowsAzure.Storage.Core.Util.StorageProgress},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member UploadFromFileAsync : string * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * IProgress&lt;Microsoft.WindowsAzure.Storage.Core.Util.StorageProgress&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&#xA;override this.UploadFromFileAsync : string * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * IProgress&lt;Microsoft.WindowsAzure.Storage.Core.Util.StorageProgress&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="cloudBlockBlob.UploadFromFileAsync (path, accessCondition, options, operationContext, progressHandler, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.WindowsAzure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="path" Type="System.String" />
        <Parameter Name="accessCondition" Type="Microsoft.WindowsAzure.Storage.AccessCondition" />
        <Parameter Name="options" Type="Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
        <Parameter Name="progressHandler" Type="System.IProgress&lt;Microsoft.WindowsAzure.Storage.Core.Util.StorageProgress&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="path"><span data-ttu-id="f3327-798">Eine Zeichenfolge mit den Dateipfad der Blob-Inhalte bereitstellen.</span><span class="sxs-lookup"><span data-stu-id="f3327-798">A string containing the file path providing the blob content.</span></span></param>
        <param name="accessCondition"><span data-ttu-id="f3327-799">Ein <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> -Objekt, das die Bedingung, die erfüllt sein müssen, damit die Anforderung darstellt, um den Vorgang fortzusetzen.</span><span class="sxs-lookup"><span data-stu-id="f3327-799">An <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> object that represents the condition that must be met in order for the request to proceed.</span></span></param>
        <param name="options"><span data-ttu-id="f3327-800">Ein <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" /> -Objekt, das zusätzliche Optionen für die Anforderung angibt.</span><span class="sxs-lookup"><span data-stu-id="f3327-800">A <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" /> object that specifies additional options for the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="f3327-801">Ein <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> -Objekt, das den Kontext für den aktuellen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="f3327-801">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <param name="progressHandler"> <span data-ttu-id="f3327-802">Ein <see cref="T:System.IProgress`1" /> Objekt behandelt <see cref="T:Microsoft.WindowsAzure.Storage.Core.Util.StorageProgress" /> Nachrichten.</span><span class="sxs-lookup"><span data-stu-id="f3327-802">A <see cref="T:System.IProgress`1" /> object to handle <see cref="T:Microsoft.WindowsAzure.Storage.Core.Util.StorageProgress" /> messages.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="f3327-803">Ein <see cref="T:System.Threading.CancellationToken" />, das beim Warten auf den Abschluss einer Aufgabe überwacht werden soll.</span><span class="sxs-lookup"><span data-stu-id="f3327-803">A <see cref="T:System.Threading.CancellationToken" /> to observe while waiting for a task to complete.</span></span></param>
        <summary>
            <span data-ttu-id="f3327-804">Initiiert einen asynchronen Vorgang zum Hochladen einer Datei in ein Blob.</span><span class="sxs-lookup"><span data-stu-id="f3327-804">Initiates an asynchronous operation to upload a file to a blob.</span></span> <span data-ttu-id="f3327-805">Wenn das Blob bereits vorhanden ist, wird sie überschrieben.</span><span class="sxs-lookup"><span data-stu-id="f3327-805">If the blob already exists, it will be overwritten.</span></span>
            </summary>
        <returns><span data-ttu-id="f3327-806">Ein <see cref="T:System.Threading.Tasks.Task" />-Objekt, das den asynchronen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="f3327-806">A <see cref="T:System.Threading.Tasks.Task" /> object that represents the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UploadFromStream">
      <MemberSignature Language="C#" Value="public virtual void UploadFromStream (System.IO.Stream source, Microsoft.WindowsAzure.Storage.AccessCondition accessCondition = null, Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options = null, Microsoft.WindowsAzure.Storage.OperationContext operationContext = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void UploadFromStream(class System.IO.Stream source, class Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, class Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlockBlob.UploadFromStream(System.IO.Stream,Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="abstract member UploadFromStream : System.IO.Stream * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; unit&#xA;override this.UploadFromStream : System.IO.Stream * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; unit" Usage="cloudBlockBlob.UploadFromStream (source, accessCondition, options, operationContext)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.WindowsAzure.Storage.Blob.ICloudBlob.UploadFromStream(System.IO.Stream,Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.WindowsAzure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="source" Type="System.IO.Stream" />
        <Parameter Name="accessCondition" Type="Microsoft.WindowsAzure.Storage.AccessCondition" />
        <Parameter Name="options" Type="Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="source"><span data-ttu-id="f3327-807">Ein <see cref="T:System.IO.Stream" /> Objekt, das den Blob-Inhalt.</span><span class="sxs-lookup"><span data-stu-id="f3327-807">A <see cref="T:System.IO.Stream" /> object providing the blob content.</span></span></param>
        <param name="accessCondition"><span data-ttu-id="f3327-808">Ein <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> -Objekt, das die Bedingung, die erfüllt sein müssen, damit die Anforderung darstellt, um den Vorgang fortzusetzen.</span><span class="sxs-lookup"><span data-stu-id="f3327-808">An <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> object that represents the condition that must be met in order for the request to proceed.</span></span> <span data-ttu-id="f3327-809">Wenn <c>null</c>, keine Bedingung verwendet.</span><span class="sxs-lookup"><span data-stu-id="f3327-809">If <c>null</c>, no condition is used.</span></span></param>
        <param name="options"><span data-ttu-id="f3327-810">Ein <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" /> -Objekt, das zusätzliche Optionen für die Anforderung angibt.</span><span class="sxs-lookup"><span data-stu-id="f3327-810">A <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" /> object that specifies additional options for the request.</span></span> <span data-ttu-id="f3327-811">Wenn <c>null</c>, Standardoptionen gelten für die Anforderung.</span><span class="sxs-lookup"><span data-stu-id="f3327-811">If <c>null</c>, default options are applied to the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="f3327-812">Ein <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> -Objekt, das den Kontext für den aktuellen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="f3327-812">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <summary>
            <span data-ttu-id="f3327-813">Lädt einen Datenstrom in ein Blockblob hoch.</span><span class="sxs-lookup"><span data-stu-id="f3327-813">Uploads a stream to a block blob.</span></span> <span data-ttu-id="f3327-814">Wenn das Blob bereits vorhanden ist, wird sie überschrieben.</span><span class="sxs-lookup"><span data-stu-id="f3327-814">If the blob already exists, it will be overwritten.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UploadFromStream">
      <MemberSignature Language="C#" Value="public virtual void UploadFromStream (System.IO.Stream source, long length, Microsoft.WindowsAzure.Storage.AccessCondition accessCondition = null, Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options = null, Microsoft.WindowsAzure.Storage.OperationContext operationContext = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void UploadFromStream(class System.IO.Stream source, int64 length, class Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, class Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlockBlob.UploadFromStream(System.IO.Stream,System.Int64,Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="abstract member UploadFromStream : System.IO.Stream * int64 * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; unit&#xA;override this.UploadFromStream : System.IO.Stream * int64 * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; unit" Usage="cloudBlockBlob.UploadFromStream (source, length, accessCondition, options, operationContext)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.WindowsAzure.Storage.Blob.ICloudBlob.UploadFromStream(System.IO.Stream,System.Int64,Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.WindowsAzure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="source" Type="System.IO.Stream" />
        <Parameter Name="length" Type="System.Int64" />
        <Parameter Name="accessCondition" Type="Microsoft.WindowsAzure.Storage.AccessCondition" />
        <Parameter Name="options" Type="Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="source"><span data-ttu-id="f3327-815">Ein <see cref="T:System.IO.Stream" /> Objekt, das den Blob-Inhalt.</span><span class="sxs-lookup"><span data-stu-id="f3327-815">A <see cref="T:System.IO.Stream" /> object providing the blob content.</span></span></param>
        <param name="length"><span data-ttu-id="f3327-816">Die Anzahl der Bytes, die aus dem Quelldatenstrom in seiner derzeitigen Position zu schreiben.</span><span class="sxs-lookup"><span data-stu-id="f3327-816">The number of bytes to write from the source stream at its current position.</span></span></param>
        <param name="accessCondition"><span data-ttu-id="f3327-817">Ein <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> -Objekt, das die Bedingung, die erfüllt sein müssen, damit die Anforderung darstellt, um den Vorgang fortzusetzen.</span><span class="sxs-lookup"><span data-stu-id="f3327-817">An <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> object that represents the condition that must be met in order for the request to proceed.</span></span> <span data-ttu-id="f3327-818">Wenn <c>null</c>, keine Bedingung verwendet.</span><span class="sxs-lookup"><span data-stu-id="f3327-818">If <c>null</c>, no condition is used.</span></span></param>
        <param name="options"><span data-ttu-id="f3327-819">Ein <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" /> -Objekt, das zusätzliche Optionen für die Anforderung angibt.</span><span class="sxs-lookup"><span data-stu-id="f3327-819">A <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" /> object that specifies additional options for the request.</span></span> <span data-ttu-id="f3327-820">Wenn <c>null</c>, Standardoptionen gelten für die Anforderung.</span><span class="sxs-lookup"><span data-stu-id="f3327-820">If <c>null</c>, default options are applied to the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="f3327-821">Ein <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> -Objekt, das den Kontext für den aktuellen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="f3327-821">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <summary>
            <span data-ttu-id="f3327-822">Lädt einen Datenstrom in ein Blockblob hoch.</span><span class="sxs-lookup"><span data-stu-id="f3327-822">Uploads a stream to a block blob.</span></span> <span data-ttu-id="f3327-823">Wenn das Blob bereits vorhanden ist, wird sie überschrieben.</span><span class="sxs-lookup"><span data-stu-id="f3327-823">If the blob already exists, it will be overwritten.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UploadFromStreamAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task UploadFromStreamAsync (System.IO.Stream source);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task UploadFromStreamAsync(class System.IO.Stream source) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlockBlob.UploadFromStreamAsync(System.IO.Stream)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function UploadFromStreamAsync (source As Stream) As Task" />
      <MemberSignature Language="F#" Value="abstract member UploadFromStreamAsync : System.IO.Stream -&gt; System.Threading.Tasks.Task&#xA;override this.UploadFromStreamAsync : System.IO.Stream -&gt; System.Threading.Tasks.Task" Usage="cloudBlockBlob.UploadFromStreamAsync source" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.WindowsAzure.Storage.Blob.ICloudBlob.UploadFromStreamAsync(System.IO.Stream)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.WindowsAzure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="source" Type="System.IO.Stream" />
      </Parameters>
      <Docs>
        <param name="source"><span data-ttu-id="f3327-824">Ein <see cref="T:System.IO.Stream" /> Objekt, das den Blob-Inhalt.</span><span class="sxs-lookup"><span data-stu-id="f3327-824">A <see cref="T:System.IO.Stream" /> object providing the blob content.</span></span></param>
        <summary>
            <span data-ttu-id="f3327-825">Initiiert einen asynchronen Vorgang zum Hochladen eines Datenstroms in ein Block-Blob.</span><span class="sxs-lookup"><span data-stu-id="f3327-825">Initiates an asynchronous operation to upload a stream to a block blob.</span></span> <span data-ttu-id="f3327-826">Wenn das Blob bereits vorhanden ist, wird sie überschrieben.</span><span class="sxs-lookup"><span data-stu-id="f3327-826">If the blob already exists, it will be overwritten.</span></span>
            </summary>
        <returns><span data-ttu-id="f3327-827">Ein <see cref="T:System.Threading.Tasks.Task" />-Objekt, das den asynchronen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="f3327-827">A <see cref="T:System.Threading.Tasks.Task" /> object that represents the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UploadFromStreamAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task UploadFromStreamAsync (System.IO.Stream source, long length);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task UploadFromStreamAsync(class System.IO.Stream source, int64 length) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlockBlob.UploadFromStreamAsync(System.IO.Stream,System.Int64)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function UploadFromStreamAsync (source As Stream, length As Long) As Task" />
      <MemberSignature Language="F#" Value="abstract member UploadFromStreamAsync : System.IO.Stream * int64 -&gt; System.Threading.Tasks.Task&#xA;override this.UploadFromStreamAsync : System.IO.Stream * int64 -&gt; System.Threading.Tasks.Task" Usage="cloudBlockBlob.UploadFromStreamAsync (source, length)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.WindowsAzure.Storage.Blob.ICloudBlob.UploadFromStreamAsync(System.IO.Stream,System.Int64)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.WindowsAzure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="source" Type="System.IO.Stream" />
        <Parameter Name="length" Type="System.Int64" />
      </Parameters>
      <Docs>
        <param name="source"><span data-ttu-id="f3327-828">Ein <see cref="T:System.IO.Stream" /> Objekt, das den Blob-Inhalt.</span><span class="sxs-lookup"><span data-stu-id="f3327-828">A <see cref="T:System.IO.Stream" /> object providing the blob content.</span></span></param>
        <param name="length"><span data-ttu-id="f3327-829">Die Anzahl der Bytes, die aus dem Quelldatenstrom in seiner derzeitigen Position zu schreiben.</span><span class="sxs-lookup"><span data-stu-id="f3327-829">The number of bytes to write from the source stream at its current position.</span></span></param>
        <summary>
            <span data-ttu-id="f3327-830">Initiiert einen asynchronen Vorgang zum Hochladen eines Datenstroms in ein Block-Blob.</span><span class="sxs-lookup"><span data-stu-id="f3327-830">Initiates an asynchronous operation to upload a stream to a block blob.</span></span> <span data-ttu-id="f3327-831">Wenn das Blob bereits vorhanden ist, wird sie überschrieben.</span><span class="sxs-lookup"><span data-stu-id="f3327-831">If the blob already exists, it will be overwritten.</span></span>
            </summary>
        <returns><span data-ttu-id="f3327-832">Ein <see cref="T:System.Threading.Tasks.Task" />-Objekt, das den asynchronen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="f3327-832">A <see cref="T:System.Threading.Tasks.Task" /> object that represents the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UploadFromStreamAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task UploadFromStreamAsync (System.IO.Stream source, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task UploadFromStreamAsync(class System.IO.Stream source, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlockBlob.UploadFromStreamAsync(System.IO.Stream,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member UploadFromStreamAsync : System.IO.Stream * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&#xA;override this.UploadFromStreamAsync : System.IO.Stream * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="cloudBlockBlob.UploadFromStreamAsync (source, cancellationToken)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.WindowsAzure.Storage.Blob.ICloudBlob.UploadFromStreamAsync(System.IO.Stream,System.Threading.CancellationToken)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.WindowsAzure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="source" Type="System.IO.Stream" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="source"><span data-ttu-id="f3327-833">Ein <see cref="T:System.IO.Stream" /> Objekt, das den Blob-Inhalt.</span><span class="sxs-lookup"><span data-stu-id="f3327-833">A <see cref="T:System.IO.Stream" /> object providing the blob content.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="f3327-834">Ein <see cref="T:System.Threading.CancellationToken" />, das beim Warten auf den Abschluss einer Aufgabe überwacht werden soll.</span><span class="sxs-lookup"><span data-stu-id="f3327-834">A <see cref="T:System.Threading.CancellationToken" /> to observe while waiting for a task to complete.</span></span></param>
        <summary>
            <span data-ttu-id="f3327-835">Initiiert einen asynchronen Vorgang zum Hochladen eines Datenstroms in ein Block-Blob.</span><span class="sxs-lookup"><span data-stu-id="f3327-835">Initiates an asynchronous operation to upload a stream to a block blob.</span></span> <span data-ttu-id="f3327-836">Wenn das Blob bereits vorhanden ist, wird sie überschrieben.</span><span class="sxs-lookup"><span data-stu-id="f3327-836">If the blob already exists, it will be overwritten.</span></span>
            </summary>
        <returns><span data-ttu-id="f3327-837">Ein <see cref="T:System.Threading.Tasks.Task" />-Objekt, das den asynchronen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="f3327-837">A <see cref="T:System.Threading.Tasks.Task" /> object that represents the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UploadFromStreamAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task UploadFromStreamAsync (System.IO.Stream source, long length, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task UploadFromStreamAsync(class System.IO.Stream source, int64 length, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlockBlob.UploadFromStreamAsync(System.IO.Stream,System.Int64,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member UploadFromStreamAsync : System.IO.Stream * int64 * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&#xA;override this.UploadFromStreamAsync : System.IO.Stream * int64 * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="cloudBlockBlob.UploadFromStreamAsync (source, length, cancellationToken)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.WindowsAzure.Storage.Blob.ICloudBlob.UploadFromStreamAsync(System.IO.Stream,System.Int64,System.Threading.CancellationToken)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.WindowsAzure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="source" Type="System.IO.Stream" />
        <Parameter Name="length" Type="System.Int64" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="source"><span data-ttu-id="f3327-838">Ein <see cref="T:System.IO.Stream" /> Objekt, das den Blob-Inhalt.</span><span class="sxs-lookup"><span data-stu-id="f3327-838">A <see cref="T:System.IO.Stream" /> object providing the blob content.</span></span></param>
        <param name="length"><span data-ttu-id="f3327-839">Die Anzahl der Bytes, die aus dem Quelldatenstrom in seiner derzeitigen Position zu schreiben.</span><span class="sxs-lookup"><span data-stu-id="f3327-839">The number of bytes to write from the source stream at its current position.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="f3327-840">Ein <see cref="T:System.Threading.CancellationToken" />, das beim Warten auf den Abschluss einer Aufgabe überwacht werden soll.</span><span class="sxs-lookup"><span data-stu-id="f3327-840">A <see cref="T:System.Threading.CancellationToken" /> to observe while waiting for a task to complete.</span></span></param>
        <summary>
            <span data-ttu-id="f3327-841">Initiiert einen asynchronen Vorgang zum Hochladen eines Datenstroms in ein Block-Blob.</span><span class="sxs-lookup"><span data-stu-id="f3327-841">Initiates an asynchronous operation to upload a stream to a block blob.</span></span> <span data-ttu-id="f3327-842">Wenn das Blob bereits vorhanden ist, wird sie überschrieben.</span><span class="sxs-lookup"><span data-stu-id="f3327-842">If the blob already exists, it will be overwritten.</span></span>
            </summary>
        <returns><span data-ttu-id="f3327-843">Ein <see cref="T:System.Threading.Tasks.Task" />-Objekt, das den asynchronen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="f3327-843">A <see cref="T:System.Threading.Tasks.Task" /> object that represents the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UploadFromStreamAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task UploadFromStreamAsync (System.IO.Stream source, Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, Microsoft.WindowsAzure.Storage.OperationContext operationContext);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task UploadFromStreamAsync(class System.IO.Stream source, class Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, class Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlockBlob.UploadFromStreamAsync(System.IO.Stream,Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="abstract member UploadFromStreamAsync : System.IO.Stream * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Threading.Tasks.Task&#xA;override this.UploadFromStreamAsync : System.IO.Stream * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Threading.Tasks.Task" Usage="cloudBlockBlob.UploadFromStreamAsync (source, accessCondition, options, operationContext)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.WindowsAzure.Storage.Blob.ICloudBlob.UploadFromStreamAsync(System.IO.Stream,Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.WindowsAzure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="source" Type="System.IO.Stream" />
        <Parameter Name="accessCondition" Type="Microsoft.WindowsAzure.Storage.AccessCondition" />
        <Parameter Name="options" Type="Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="source"><span data-ttu-id="f3327-844">Ein <see cref="T:System.IO.Stream" /> Objekt, das den Blob-Inhalt.</span><span class="sxs-lookup"><span data-stu-id="f3327-844">A <see cref="T:System.IO.Stream" /> object providing the blob content.</span></span></param>
        <param name="accessCondition"><span data-ttu-id="f3327-845">Ein <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> -Objekt, das die Bedingung, die erfüllt sein müssen, damit die Anforderung darstellt, um den Vorgang fortzusetzen.</span><span class="sxs-lookup"><span data-stu-id="f3327-845">An <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> object that represents the condition that must be met in order for the request to proceed.</span></span> <span data-ttu-id="f3327-846">Wenn <c>null</c>, keine Bedingung verwendet.</span><span class="sxs-lookup"><span data-stu-id="f3327-846">If <c>null</c>, no condition is used.</span></span></param>
        <param name="options"><span data-ttu-id="f3327-847">Ein <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" /> -Objekt, das zusätzliche Optionen für die Anforderung angibt.</span><span class="sxs-lookup"><span data-stu-id="f3327-847">A <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" /> object that specifies additional options for the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="f3327-848">Ein <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> -Objekt, das den Kontext für den aktuellen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="f3327-848">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <summary>
            <span data-ttu-id="f3327-849">Initiiert einen asynchronen Vorgang zum Hochladen eines Datenstroms in ein Block-Blob.</span><span class="sxs-lookup"><span data-stu-id="f3327-849">Initiates an asynchronous operation to upload a stream to a block blob.</span></span> <span data-ttu-id="f3327-850">Wenn das Blob bereits vorhanden ist, wird sie überschrieben.</span><span class="sxs-lookup"><span data-stu-id="f3327-850">If the blob already exists, it will be overwritten.</span></span>
            </summary>
        <returns><span data-ttu-id="f3327-851">Ein <see cref="T:System.Threading.Tasks.Task" />-Objekt, das den asynchronen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="f3327-851">A <see cref="T:System.Threading.Tasks.Task" /> object that represents the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UploadFromStreamAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task UploadFromStreamAsync (System.IO.Stream source, Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, Microsoft.WindowsAzure.Storage.OperationContext operationContext, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task UploadFromStreamAsync(class System.IO.Stream source, class Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, class Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, class Microsoft.WindowsAzure.Storage.OperationContext operationContext, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlockBlob.UploadFromStreamAsync(System.IO.Stream,Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member UploadFromStreamAsync : System.IO.Stream * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&#xA;override this.UploadFromStreamAsync : System.IO.Stream * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="cloudBlockBlob.UploadFromStreamAsync (source, accessCondition, options, operationContext, cancellationToken)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.WindowsAzure.Storage.Blob.ICloudBlob.UploadFromStreamAsync(System.IO.Stream,Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext,System.Threading.CancellationToken)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.WindowsAzure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="source" Type="System.IO.Stream" />
        <Parameter Name="accessCondition" Type="Microsoft.WindowsAzure.Storage.AccessCondition" />
        <Parameter Name="options" Type="Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="source"><span data-ttu-id="f3327-852">Ein <see cref="T:System.IO.Stream" /> Objekt, das den Blob-Inhalt.</span><span class="sxs-lookup"><span data-stu-id="f3327-852">A <see cref="T:System.IO.Stream" /> object providing the blob content.</span></span></param>
        <param name="accessCondition"><span data-ttu-id="f3327-853">Ein <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> -Objekt, das die Bedingung, die erfüllt sein müssen, damit die Anforderung darstellt, um den Vorgang fortzusetzen.</span><span class="sxs-lookup"><span data-stu-id="f3327-853">An <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> object that represents the condition that must be met in order for the request to proceed.</span></span> <span data-ttu-id="f3327-854">Wenn <c>null</c>, keine Bedingung verwendet.</span><span class="sxs-lookup"><span data-stu-id="f3327-854">If <c>null</c>, no condition is used.</span></span></param>
        <param name="options"><span data-ttu-id="f3327-855">Ein <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" /> -Objekt, das zusätzliche Optionen für die Anforderung angibt.</span><span class="sxs-lookup"><span data-stu-id="f3327-855">A <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" /> object that specifies additional options for the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="f3327-856">Ein <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> -Objekt, das den Kontext für den aktuellen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="f3327-856">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="f3327-857">Ein <see cref="T:System.Threading.CancellationToken" />, das beim Warten auf den Abschluss einer Aufgabe überwacht werden soll.</span><span class="sxs-lookup"><span data-stu-id="f3327-857">A <see cref="T:System.Threading.CancellationToken" /> to observe while waiting for a task to complete.</span></span></param>
        <summary>
            <span data-ttu-id="f3327-858">Initiiert einen asynchronen Vorgang zum Hochladen eines Datenstroms in ein Block-Blob.</span><span class="sxs-lookup"><span data-stu-id="f3327-858">Initiates an asynchronous operation to upload a stream to a block blob.</span></span> <span data-ttu-id="f3327-859">Wenn das Blob bereits vorhanden ist, wird sie überschrieben.</span><span class="sxs-lookup"><span data-stu-id="f3327-859">If the blob already exists, it will be overwritten.</span></span>
            </summary>
        <returns><span data-ttu-id="f3327-860">Ein <see cref="T:System.Threading.Tasks.Task" />-Objekt, das den asynchronen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="f3327-860">A <see cref="T:System.Threading.Tasks.Task" /> object that represents the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UploadFromStreamAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task UploadFromStreamAsync (System.IO.Stream source, long length, Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, Microsoft.WindowsAzure.Storage.OperationContext operationContext);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task UploadFromStreamAsync(class System.IO.Stream source, int64 length, class Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, class Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlockBlob.UploadFromStreamAsync(System.IO.Stream,System.Int64,Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="abstract member UploadFromStreamAsync : System.IO.Stream * int64 * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Threading.Tasks.Task&#xA;override this.UploadFromStreamAsync : System.IO.Stream * int64 * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Threading.Tasks.Task" Usage="cloudBlockBlob.UploadFromStreamAsync (source, length, accessCondition, options, operationContext)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.WindowsAzure.Storage.Blob.ICloudBlob.UploadFromStreamAsync(System.IO.Stream,System.Int64,Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.WindowsAzure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="source" Type="System.IO.Stream" />
        <Parameter Name="length" Type="System.Int64" />
        <Parameter Name="accessCondition" Type="Microsoft.WindowsAzure.Storage.AccessCondition" />
        <Parameter Name="options" Type="Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="source"><span data-ttu-id="f3327-861">Ein <see cref="T:System.IO.Stream" /> Objekt, das den Blob-Inhalt.</span><span class="sxs-lookup"><span data-stu-id="f3327-861">A <see cref="T:System.IO.Stream" /> object providing the blob content.</span></span></param>
        <param name="length"><span data-ttu-id="f3327-862">Die Anzahl der Bytes, die aus dem Quelldatenstrom in seiner derzeitigen Position zu schreiben.</span><span class="sxs-lookup"><span data-stu-id="f3327-862">The number of bytes to write from the source stream at its current position.</span></span></param>
        <param name="accessCondition"><span data-ttu-id="f3327-863">Ein <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> -Objekt, das die Bedingung, die erfüllt sein müssen, damit die Anforderung darstellt, um den Vorgang fortzusetzen.</span><span class="sxs-lookup"><span data-stu-id="f3327-863">An <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> object that represents the condition that must be met in order for the request to proceed.</span></span> <span data-ttu-id="f3327-864">Wenn <c>null</c>, keine Bedingung verwendet.</span><span class="sxs-lookup"><span data-stu-id="f3327-864">If <c>null</c>, no condition is used.</span></span></param>
        <param name="options"><span data-ttu-id="f3327-865">Ein <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" /> -Objekt, das zusätzliche Optionen für die Anforderung angibt.</span><span class="sxs-lookup"><span data-stu-id="f3327-865">A <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" /> object that specifies additional options for the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="f3327-866">Ein <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> -Objekt, das den Kontext für den aktuellen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="f3327-866">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <summary>
            <span data-ttu-id="f3327-867">Initiiert einen asynchronen Vorgang zum Hochladen eines Datenstroms in ein Block-Blob.</span><span class="sxs-lookup"><span data-stu-id="f3327-867">Initiates an asynchronous operation to upload a stream to a block blob.</span></span> <span data-ttu-id="f3327-868">Wenn das Blob bereits vorhanden ist, wird sie überschrieben.</span><span class="sxs-lookup"><span data-stu-id="f3327-868">If the blob already exists, it will be overwritten.</span></span>
            </summary>
        <returns><span data-ttu-id="f3327-869">Ein <see cref="T:System.Threading.Tasks.Task" />-Objekt, das den asynchronen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="f3327-869">A <see cref="T:System.Threading.Tasks.Task" /> object that represents the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UploadFromStreamAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task UploadFromStreamAsync (System.IO.Stream source, Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, Microsoft.WindowsAzure.Storage.OperationContext operationContext, IProgress&lt;Microsoft.WindowsAzure.Storage.Core.Util.StorageProgress&gt; progressHandler, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task UploadFromStreamAsync(class System.IO.Stream source, class Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, class Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, class Microsoft.WindowsAzure.Storage.OperationContext operationContext, class System.IProgress`1&lt;class Microsoft.WindowsAzure.Storage.Core.Util.StorageProgress&gt; progressHandler, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlockBlob.UploadFromStreamAsync(System.IO.Stream,Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext,System.IProgress{Microsoft.WindowsAzure.Storage.Core.Util.StorageProgress},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member UploadFromStreamAsync : System.IO.Stream * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * IProgress&lt;Microsoft.WindowsAzure.Storage.Core.Util.StorageProgress&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&#xA;override this.UploadFromStreamAsync : System.IO.Stream * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * IProgress&lt;Microsoft.WindowsAzure.Storage.Core.Util.StorageProgress&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="cloudBlockBlob.UploadFromStreamAsync (source, accessCondition, options, operationContext, progressHandler, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.WindowsAzure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="source" Type="System.IO.Stream" />
        <Parameter Name="accessCondition" Type="Microsoft.WindowsAzure.Storage.AccessCondition" />
        <Parameter Name="options" Type="Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
        <Parameter Name="progressHandler" Type="System.IProgress&lt;Microsoft.WindowsAzure.Storage.Core.Util.StorageProgress&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="source"><span data-ttu-id="f3327-870">Ein <see cref="T:System.IO.Stream" /> Objekt, das den Blob-Inhalt.</span><span class="sxs-lookup"><span data-stu-id="f3327-870">A <see cref="T:System.IO.Stream" /> object providing the blob content.</span></span></param>
        <param name="accessCondition"><span data-ttu-id="f3327-871">Ein <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> -Objekt, das die Bedingung, die erfüllt sein müssen, damit die Anforderung darstellt, um den Vorgang fortzusetzen.</span><span class="sxs-lookup"><span data-stu-id="f3327-871">An <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> object that represents the condition that must be met in order for the request to proceed.</span></span> <span data-ttu-id="f3327-872">Wenn <c>null</c>, keine Bedingung verwendet.</span><span class="sxs-lookup"><span data-stu-id="f3327-872">If <c>null</c>, no condition is used.</span></span></param>
        <param name="options"><span data-ttu-id="f3327-873">Ein <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" /> -Objekt, das zusätzliche Optionen für die Anforderung angibt.</span><span class="sxs-lookup"><span data-stu-id="f3327-873">A <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" /> object that specifies additional options for the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="f3327-874">Ein <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> -Objekt, das den Kontext für den aktuellen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="f3327-874">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <param name="progressHandler"> <span data-ttu-id="f3327-875">Ein <see cref="T:System.IProgress`1" /> Objekt behandelt <see cref="T:Microsoft.WindowsAzure.Storage.Core.Util.StorageProgress" /> Nachrichten.</span><span class="sxs-lookup"><span data-stu-id="f3327-875">A <see cref="T:System.IProgress`1" /> object to handle <see cref="T:Microsoft.WindowsAzure.Storage.Core.Util.StorageProgress" /> messages.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="f3327-876">Ein <see cref="T:System.Threading.CancellationToken" />, das beim Warten auf den Abschluss einer Aufgabe überwacht werden soll.</span><span class="sxs-lookup"><span data-stu-id="f3327-876">A <see cref="T:System.Threading.CancellationToken" /> to observe while waiting for a task to complete.</span></span></param>
        <summary>
            <span data-ttu-id="f3327-877">Initiiert einen asynchronen Vorgang zum Hochladen eines Datenstroms in ein Block-Blob.</span><span class="sxs-lookup"><span data-stu-id="f3327-877">Initiates an asynchronous operation to upload a stream to a block blob.</span></span> <span data-ttu-id="f3327-878">Wenn das Blob bereits vorhanden ist, wird sie überschrieben.</span><span class="sxs-lookup"><span data-stu-id="f3327-878">If the blob already exists, it will be overwritten.</span></span>
            </summary>
        <returns><span data-ttu-id="f3327-879">Ein <see cref="T:System.Threading.Tasks.Task" />-Objekt, das den asynchronen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="f3327-879">A <see cref="T:System.Threading.Tasks.Task" /> object that represents the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UploadFromStreamAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task UploadFromStreamAsync (System.IO.Stream source, long length, Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, Microsoft.WindowsAzure.Storage.OperationContext operationContext, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task UploadFromStreamAsync(class System.IO.Stream source, int64 length, class Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, class Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, class Microsoft.WindowsAzure.Storage.OperationContext operationContext, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlockBlob.UploadFromStreamAsync(System.IO.Stream,System.Int64,Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member UploadFromStreamAsync : System.IO.Stream * int64 * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&#xA;override this.UploadFromStreamAsync : System.IO.Stream * int64 * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="cloudBlockBlob.UploadFromStreamAsync (source, length, accessCondition, options, operationContext, cancellationToken)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.WindowsAzure.Storage.Blob.ICloudBlob.UploadFromStreamAsync(System.IO.Stream,System.Int64,Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext,System.Threading.CancellationToken)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.WindowsAzure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="source" Type="System.IO.Stream" />
        <Parameter Name="length" Type="System.Int64" />
        <Parameter Name="accessCondition" Type="Microsoft.WindowsAzure.Storage.AccessCondition" />
        <Parameter Name="options" Type="Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="source"><span data-ttu-id="f3327-880">Ein <see cref="T:System.IO.Stream" /> Objekt, das den Blob-Inhalt.</span><span class="sxs-lookup"><span data-stu-id="f3327-880">A <see cref="T:System.IO.Stream" /> object providing the blob content.</span></span></param>
        <param name="length"><span data-ttu-id="f3327-881">Die Anzahl der Bytes, die aus dem Quelldatenstrom in seiner derzeitigen Position zu schreiben.</span><span class="sxs-lookup"><span data-stu-id="f3327-881">The number of bytes to write from the source stream at its current position.</span></span></param>
        <param name="accessCondition"><span data-ttu-id="f3327-882">Ein <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> -Objekt, das die Bedingung, die erfüllt sein müssen, damit die Anforderung darstellt, um den Vorgang fortzusetzen.</span><span class="sxs-lookup"><span data-stu-id="f3327-882">An <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> object that represents the condition that must be met in order for the request to proceed.</span></span> <span data-ttu-id="f3327-883">Wenn <c>null</c>, keine Bedingung verwendet.</span><span class="sxs-lookup"><span data-stu-id="f3327-883">If <c>null</c>, no condition is used.</span></span></param>
        <param name="options"><span data-ttu-id="f3327-884">Ein <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" /> -Objekt, das zusätzliche Optionen für die Anforderung angibt.</span><span class="sxs-lookup"><span data-stu-id="f3327-884">A <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" /> object that specifies additional options for the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="f3327-885">Ein <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> -Objekt, das den Kontext für den aktuellen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="f3327-885">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="f3327-886">Ein <see cref="T:System.Threading.CancellationToken" />, das beim Warten auf den Abschluss einer Aufgabe überwacht werden soll.</span><span class="sxs-lookup"><span data-stu-id="f3327-886">A <see cref="T:System.Threading.CancellationToken" /> to observe while waiting for a task to complete.</span></span></param>
        <summary>
            <span data-ttu-id="f3327-887">Initiiert einen asynchronen Vorgang zum Hochladen eines Datenstroms in ein Block-Blob.</span><span class="sxs-lookup"><span data-stu-id="f3327-887">Initiates an asynchronous operation to upload a stream to a block blob.</span></span> <span data-ttu-id="f3327-888">Wenn das Blob bereits vorhanden ist, wird sie überschrieben.</span><span class="sxs-lookup"><span data-stu-id="f3327-888">If the blob already exists, it will be overwritten.</span></span>
            </summary>
        <returns><span data-ttu-id="f3327-889">Ein <see cref="T:System.Threading.Tasks.Task" />-Objekt, das den asynchronen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="f3327-889">A <see cref="T:System.Threading.Tasks.Task" /> object that represents the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UploadFromStreamAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task UploadFromStreamAsync (System.IO.Stream source, long length, Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, Microsoft.WindowsAzure.Storage.OperationContext operationContext, IProgress&lt;Microsoft.WindowsAzure.Storage.Core.Util.StorageProgress&gt; progressHandler, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task UploadFromStreamAsync(class System.IO.Stream source, int64 length, class Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, class Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, class Microsoft.WindowsAzure.Storage.OperationContext operationContext, class System.IProgress`1&lt;class Microsoft.WindowsAzure.Storage.Core.Util.StorageProgress&gt; progressHandler, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlockBlob.UploadFromStreamAsync(System.IO.Stream,System.Int64,Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext,System.IProgress{Microsoft.WindowsAzure.Storage.Core.Util.StorageProgress},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member UploadFromStreamAsync : System.IO.Stream * int64 * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * IProgress&lt;Microsoft.WindowsAzure.Storage.Core.Util.StorageProgress&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&#xA;override this.UploadFromStreamAsync : System.IO.Stream * int64 * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * IProgress&lt;Microsoft.WindowsAzure.Storage.Core.Util.StorageProgress&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="cloudBlockBlob.UploadFromStreamAsync (source, length, accessCondition, options, operationContext, progressHandler, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.WindowsAzure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="source" Type="System.IO.Stream" />
        <Parameter Name="length" Type="System.Int64" />
        <Parameter Name="accessCondition" Type="Microsoft.WindowsAzure.Storage.AccessCondition" />
        <Parameter Name="options" Type="Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
        <Parameter Name="progressHandler" Type="System.IProgress&lt;Microsoft.WindowsAzure.Storage.Core.Util.StorageProgress&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="source"><span data-ttu-id="f3327-890">Ein <see cref="T:System.IO.Stream" /> Objekt, das den Blob-Inhalt.</span><span class="sxs-lookup"><span data-stu-id="f3327-890">A <see cref="T:System.IO.Stream" /> object providing the blob content.</span></span></param>
        <param name="length"><span data-ttu-id="f3327-891">Die Anzahl der Bytes, die aus dem Quelldatenstrom in seiner derzeitigen Position zu schreiben.</span><span class="sxs-lookup"><span data-stu-id="f3327-891">The number of bytes to write from the source stream at its current position.</span></span></param>
        <param name="accessCondition"><span data-ttu-id="f3327-892">Ein <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> -Objekt, das die Bedingung, die erfüllt sein müssen, damit die Anforderung darstellt, um den Vorgang fortzusetzen.</span><span class="sxs-lookup"><span data-stu-id="f3327-892">An <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> object that represents the condition that must be met in order for the request to proceed.</span></span> <span data-ttu-id="f3327-893">Wenn <c>null</c>, keine Bedingung verwendet.</span><span class="sxs-lookup"><span data-stu-id="f3327-893">If <c>null</c>, no condition is used.</span></span></param>
        <param name="options"><span data-ttu-id="f3327-894">Ein <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" /> -Objekt, das zusätzliche Optionen für die Anforderung angibt.</span><span class="sxs-lookup"><span data-stu-id="f3327-894">A <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" /> object that specifies additional options for the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="f3327-895">Ein <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> -Objekt, das den Kontext für den aktuellen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="f3327-895">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <param name="progressHandler"> <span data-ttu-id="f3327-896">Ein <see cref="T:System.IProgress`1" /> Objekt behandelt <see cref="T:Microsoft.WindowsAzure.Storage.Core.Util.StorageProgress" /> Nachrichten.</span><span class="sxs-lookup"><span data-stu-id="f3327-896">A <see cref="T:System.IProgress`1" /> object to handle <see cref="T:Microsoft.WindowsAzure.Storage.Core.Util.StorageProgress" /> messages.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="f3327-897">Ein <see cref="T:System.Threading.CancellationToken" />, das beim Warten auf den Abschluss einer Aufgabe überwacht werden soll.</span><span class="sxs-lookup"><span data-stu-id="f3327-897">A <see cref="T:System.Threading.CancellationToken" /> to observe while waiting for a task to complete.</span></span></param>
        <summary>
            <span data-ttu-id="f3327-898">Initiiert einen asynchronen Vorgang zum Hochladen eines Datenstroms in ein Block-Blob.</span><span class="sxs-lookup"><span data-stu-id="f3327-898">Initiates an asynchronous operation to upload a stream to a block blob.</span></span> <span data-ttu-id="f3327-899">Wenn das Blob bereits vorhanden ist, wird sie überschrieben.</span><span class="sxs-lookup"><span data-stu-id="f3327-899">If the blob already exists, it will be overwritten.</span></span>
            </summary>
        <returns><span data-ttu-id="f3327-900">Ein <see cref="T:System.Threading.Tasks.Task" />-Objekt, das den asynchronen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="f3327-900">A <see cref="T:System.Threading.Tasks.Task" /> object that represents the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UploadText">
      <MemberSignature Language="C#" Value="public virtual void UploadText (string content, System.Text.Encoding encoding = null, Microsoft.WindowsAzure.Storage.AccessCondition accessCondition = null, Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options = null, Microsoft.WindowsAzure.Storage.OperationContext operationContext = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void UploadText(string content, class System.Text.Encoding encoding, class Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, class Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlockBlob.UploadText(System.String,System.Text.Encoding,Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="abstract member UploadText : string * System.Text.Encoding * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; unit&#xA;override this.UploadText : string * System.Text.Encoding * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; unit" Usage="cloudBlockBlob.UploadText (content, encoding, accessCondition, options, operationContext)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.WindowsAzure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="content" Type="System.String" />
        <Parameter Name="encoding" Type="System.Text.Encoding" />
        <Parameter Name="accessCondition" Type="Microsoft.WindowsAzure.Storage.AccessCondition" />
        <Parameter Name="options" Type="Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="content"><span data-ttu-id="f3327-901">Eine Zeichenfolge, die hochzuladenden Text enthält.</span><span class="sxs-lookup"><span data-stu-id="f3327-901">A string containing the text to upload.</span></span></param>
        <param name="encoding"><span data-ttu-id="f3327-902">Ein <see cref="T:System.Text.Encoding" /> Objekt, das die um zu verwendende textcodierung angibt.</span><span class="sxs-lookup"><span data-stu-id="f3327-902">A <see cref="T:System.Text.Encoding" /> object that indicates the text encoding to use.</span></span> <span data-ttu-id="f3327-903">Wenn <c>null</c>, UTF-8 verwendet werden.</span><span class="sxs-lookup"><span data-stu-id="f3327-903">If <c>null</c>, UTF-8 will be used.</span></span></param>
        <param name="accessCondition"><span data-ttu-id="f3327-904">Ein <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> -Objekt, das die Bedingung, die erfüllt sein müssen, damit die Anforderung darstellt, um den Vorgang fortzusetzen.</span><span class="sxs-lookup"><span data-stu-id="f3327-904">An <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> object that represents the condition that must be met in order for the request to proceed.</span></span></param>
        <param name="options"><span data-ttu-id="f3327-905">Ein <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" /> -Objekt, das zusätzliche Optionen für die Anforderung angibt.</span><span class="sxs-lookup"><span data-stu-id="f3327-905">A <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" /> object that specifies additional options for the request.</span></span> <span data-ttu-id="f3327-906">Wenn <c>null</c>, Standardoptionen gelten für die Anforderung.</span><span class="sxs-lookup"><span data-stu-id="f3327-906">If <c>null</c>, default options are applied to the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="f3327-907">Ein <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> -Objekt, das den Kontext für den aktuellen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="f3327-907">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <summary>
            <span data-ttu-id="f3327-908">Lädt eine Textzeichenfolge in ein Blob hoch.</span><span class="sxs-lookup"><span data-stu-id="f3327-908">Uploads a string of text to a blob.</span></span> <span data-ttu-id="f3327-909">Wenn das Blob bereits vorhanden ist, wird sie überschrieben.</span><span class="sxs-lookup"><span data-stu-id="f3327-909">If the blob already exists, it will be overwritten.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UploadTextAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task UploadTextAsync (string content);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task UploadTextAsync(string content) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlockBlob.UploadTextAsync(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function UploadTextAsync (content As String) As Task" />
      <MemberSignature Language="F#" Value="abstract member UploadTextAsync : string -&gt; System.Threading.Tasks.Task&#xA;override this.UploadTextAsync : string -&gt; System.Threading.Tasks.Task" Usage="cloudBlockBlob.UploadTextAsync content" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.WindowsAzure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="content" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="content"><span data-ttu-id="f3327-910">Eine Zeichenfolge, die hochzuladenden Text enthält.</span><span class="sxs-lookup"><span data-stu-id="f3327-910">A string containing the text to upload.</span></span></param>
        <summary>
            <span data-ttu-id="f3327-911">Initiiert einen asynchronen Vorgang zum Hochladen einer Textzeichenfolge in ein Blob.</span><span class="sxs-lookup"><span data-stu-id="f3327-911">Initiates an asynchronous operation to upload a string of text to a blob.</span></span> <span data-ttu-id="f3327-912">Wenn das Blob bereits vorhanden ist, wird sie überschrieben.</span><span class="sxs-lookup"><span data-stu-id="f3327-912">If the blob already exists, it will be overwritten.</span></span>
            </summary>
        <returns><span data-ttu-id="f3327-913">Ein <see cref="T:System.Threading.Tasks.Task" />-Objekt, das den asynchronen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="f3327-913">A <see cref="T:System.Threading.Tasks.Task" /> object that represents the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UploadTextAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task UploadTextAsync (string content, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task UploadTextAsync(string content, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlockBlob.UploadTextAsync(System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member UploadTextAsync : string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&#xA;override this.UploadTextAsync : string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="cloudBlockBlob.UploadTextAsync (content, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.WindowsAzure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="content" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="content"><span data-ttu-id="f3327-914">Eine Zeichenfolge, die hochzuladenden Text enthält.</span><span class="sxs-lookup"><span data-stu-id="f3327-914">A string containing the text to upload.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="f3327-915">Ein <see cref="T:System.Threading.CancellationToken" />, das beim Warten auf den Abschluss einer Aufgabe überwacht werden soll.</span><span class="sxs-lookup"><span data-stu-id="f3327-915">A <see cref="T:System.Threading.CancellationToken" /> to observe while waiting for a task to complete.</span></span></param>
        <summary>
            <span data-ttu-id="f3327-916">Initiiert einen asynchronen Vorgang zum Hochladen einer Textzeichenfolge in ein Blob.</span><span class="sxs-lookup"><span data-stu-id="f3327-916">Initiates an asynchronous operation to upload a string of text to a blob.</span></span> <span data-ttu-id="f3327-917">Wenn das Blob bereits vorhanden ist, wird sie überschrieben.</span><span class="sxs-lookup"><span data-stu-id="f3327-917">If the blob already exists, it will be overwritten.</span></span>
            </summary>
        <returns><span data-ttu-id="f3327-918">Ein <see cref="T:System.Threading.Tasks.Task" />-Objekt, das den asynchronen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="f3327-918">A <see cref="T:System.Threading.Tasks.Task" /> object that represents the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UploadTextAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task UploadTextAsync (string content, System.Text.Encoding encoding, Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, Microsoft.WindowsAzure.Storage.OperationContext operationContext);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task UploadTextAsync(string content, class System.Text.Encoding encoding, class Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, class Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlockBlob.UploadTextAsync(System.String,System.Text.Encoding,Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="abstract member UploadTextAsync : string * System.Text.Encoding * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Threading.Tasks.Task&#xA;override this.UploadTextAsync : string * System.Text.Encoding * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Threading.Tasks.Task" Usage="cloudBlockBlob.UploadTextAsync (content, encoding, accessCondition, options, operationContext)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.WindowsAzure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="content" Type="System.String" />
        <Parameter Name="encoding" Type="System.Text.Encoding" />
        <Parameter Name="accessCondition" Type="Microsoft.WindowsAzure.Storage.AccessCondition" />
        <Parameter Name="options" Type="Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="content"><span data-ttu-id="f3327-919">Eine Zeichenfolge, die hochzuladenden Text enthält.</span><span class="sxs-lookup"><span data-stu-id="f3327-919">A string containing the text to upload.</span></span></param>
        <param name="encoding"><span data-ttu-id="f3327-920">Ein <see cref="T:System.Text.Encoding" /> Objekt, das die um zu verwendende textcodierung angibt.</span><span class="sxs-lookup"><span data-stu-id="f3327-920">A <see cref="T:System.Text.Encoding" /> object that indicates the text encoding to use.</span></span> <span data-ttu-id="f3327-921">Wenn <c>null</c>, UTF-8 verwendet werden.</span><span class="sxs-lookup"><span data-stu-id="f3327-921">If <c>null</c>, UTF-8 will be used.</span></span></param>
        <param name="accessCondition"><span data-ttu-id="f3327-922">Ein <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> -Objekt, das die Bedingung, die erfüllt sein müssen, damit die Anforderung darstellt, um den Vorgang fortzusetzen.</span><span class="sxs-lookup"><span data-stu-id="f3327-922">An <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> object that represents the condition that must be met in order for the request to proceed.</span></span></param>
        <param name="options"><span data-ttu-id="f3327-923">Ein <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" /> -Objekt, das zusätzliche Optionen für die Anforderung angibt.</span><span class="sxs-lookup"><span data-stu-id="f3327-923">A <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" /> object that specifies additional options for the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="f3327-924">Ein <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> -Objekt, das den Kontext für den aktuellen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="f3327-924">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <summary>
            <span data-ttu-id="f3327-925">Initiiert einen asynchronen Vorgang zum Hochladen einer Textzeichenfolge in ein Blob.</span><span class="sxs-lookup"><span data-stu-id="f3327-925">Initiates an asynchronous operation to upload a string of text to a blob.</span></span> <span data-ttu-id="f3327-926">Wenn das Blob bereits vorhanden ist, wird sie überschrieben.</span><span class="sxs-lookup"><span data-stu-id="f3327-926">If the blob already exists, it will be overwritten.</span></span>
            </summary>
        <returns><span data-ttu-id="f3327-927">Ein <see cref="T:System.Threading.Tasks.Task" />-Objekt, das den asynchronen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="f3327-927">A <see cref="T:System.Threading.Tasks.Task" /> object that represents the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UploadTextAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task UploadTextAsync (string content, System.Text.Encoding encoding, Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, Microsoft.WindowsAzure.Storage.OperationContext operationContext, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task UploadTextAsync(string content, class System.Text.Encoding encoding, class Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, class Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, class Microsoft.WindowsAzure.Storage.OperationContext operationContext, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlockBlob.UploadTextAsync(System.String,System.Text.Encoding,Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member UploadTextAsync : string * System.Text.Encoding * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&#xA;override this.UploadTextAsync : string * System.Text.Encoding * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="cloudBlockBlob.UploadTextAsync (content, encoding, accessCondition, options, operationContext, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.WindowsAzure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="content" Type="System.String" />
        <Parameter Name="encoding" Type="System.Text.Encoding" />
        <Parameter Name="accessCondition" Type="Microsoft.WindowsAzure.Storage.AccessCondition" />
        <Parameter Name="options" Type="Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="content"><span data-ttu-id="f3327-928">Eine Zeichenfolge, die hochzuladenden Text enthält.</span><span class="sxs-lookup"><span data-stu-id="f3327-928">A string containing the text to upload.</span></span></param>
        <param name="encoding"><span data-ttu-id="f3327-929">Ein <see cref="T:System.Text.Encoding" /> Objekt, das die um zu verwendende textcodierung angibt.</span><span class="sxs-lookup"><span data-stu-id="f3327-929">A <see cref="T:System.Text.Encoding" /> object that indicates the text encoding to use.</span></span> <span data-ttu-id="f3327-930">Wenn <c>null</c>, UTF-8 verwendet werden.</span><span class="sxs-lookup"><span data-stu-id="f3327-930">If <c>null</c>, UTF-8 will be used.</span></span></param>
        <param name="accessCondition"><span data-ttu-id="f3327-931">Ein <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> -Objekt, das die Bedingung, die erfüllt sein müssen, damit die Anforderung darstellt, um den Vorgang fortzusetzen.</span><span class="sxs-lookup"><span data-stu-id="f3327-931">An <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> object that represents the condition that must be met in order for the request to proceed.</span></span></param>
        <param name="options"><span data-ttu-id="f3327-932">Ein <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" /> -Objekt, das zusätzliche Optionen für die Anforderung angibt.</span><span class="sxs-lookup"><span data-stu-id="f3327-932">A <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" /> object that specifies additional options for the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="f3327-933">Ein <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> -Objekt, das den Kontext für den aktuellen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="f3327-933">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="f3327-934">Ein <see cref="T:System.Threading.CancellationToken" />, das beim Warten auf den Abschluss einer Aufgabe überwacht werden soll.</span><span class="sxs-lookup"><span data-stu-id="f3327-934">A <see cref="T:System.Threading.CancellationToken" /> to observe while waiting for a task to complete.</span></span></param>
        <summary>
            <span data-ttu-id="f3327-935">Initiiert einen asynchronen Vorgang zum Hochladen einer Textzeichenfolge in ein Blob.</span><span class="sxs-lookup"><span data-stu-id="f3327-935">Initiates an asynchronous operation to upload a string of text to a blob.</span></span> <span data-ttu-id="f3327-936">Wenn das Blob bereits vorhanden ist, wird sie überschrieben.</span><span class="sxs-lookup"><span data-stu-id="f3327-936">If the blob already exists, it will be overwritten.</span></span>
            </summary>
        <returns><span data-ttu-id="f3327-937">Ein <see cref="T:System.Threading.Tasks.Task" />-Objekt, das den asynchronen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="f3327-937">A <see cref="T:System.Threading.Tasks.Task" /> object that represents the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UploadTextAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task UploadTextAsync (string content, System.Text.Encoding encoding, Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, Microsoft.WindowsAzure.Storage.OperationContext operationContext, IProgress&lt;Microsoft.WindowsAzure.Storage.Core.Util.StorageProgress&gt; progressHandler, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task UploadTextAsync(string content, class System.Text.Encoding encoding, class Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, class Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, class Microsoft.WindowsAzure.Storage.OperationContext operationContext, class System.IProgress`1&lt;class Microsoft.WindowsAzure.Storage.Core.Util.StorageProgress&gt; progressHandler, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlockBlob.UploadTextAsync(System.String,System.Text.Encoding,Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext,System.IProgress{Microsoft.WindowsAzure.Storage.Core.Util.StorageProgress},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member UploadTextAsync : string * System.Text.Encoding * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * IProgress&lt;Microsoft.WindowsAzure.Storage.Core.Util.StorageProgress&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&#xA;override this.UploadTextAsync : string * System.Text.Encoding * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * IProgress&lt;Microsoft.WindowsAzure.Storage.Core.Util.StorageProgress&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="cloudBlockBlob.UploadTextAsync (content, encoding, accessCondition, options, operationContext, progressHandler, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.WindowsAzure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="content" Type="System.String" />
        <Parameter Name="encoding" Type="System.Text.Encoding" />
        <Parameter Name="accessCondition" Type="Microsoft.WindowsAzure.Storage.AccessCondition" />
        <Parameter Name="options" Type="Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
        <Parameter Name="progressHandler" Type="System.IProgress&lt;Microsoft.WindowsAzure.Storage.Core.Util.StorageProgress&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="content"><span data-ttu-id="f3327-938">Eine Zeichenfolge, die hochzuladenden Text enthält.</span><span class="sxs-lookup"><span data-stu-id="f3327-938">A string containing the text to upload.</span></span></param>
        <param name="encoding"><span data-ttu-id="f3327-939">Ein <see cref="T:System.Text.Encoding" /> Objekt, das die um zu verwendende textcodierung angibt.</span><span class="sxs-lookup"><span data-stu-id="f3327-939">A <see cref="T:System.Text.Encoding" /> object that indicates the text encoding to use.</span></span> <span data-ttu-id="f3327-940">Wenn <c>null</c>, UTF-8 verwendet werden.</span><span class="sxs-lookup"><span data-stu-id="f3327-940">If <c>null</c>, UTF-8 will be used.</span></span></param>
        <param name="accessCondition"><span data-ttu-id="f3327-941">Ein <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> -Objekt, das die Bedingung, die erfüllt sein müssen, damit die Anforderung darstellt, um den Vorgang fortzusetzen.</span><span class="sxs-lookup"><span data-stu-id="f3327-941">An <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> object that represents the condition that must be met in order for the request to proceed.</span></span></param>
        <param name="options"><span data-ttu-id="f3327-942">Ein <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" /> -Objekt, das zusätzliche Optionen für die Anforderung angibt.</span><span class="sxs-lookup"><span data-stu-id="f3327-942">A <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" /> object that specifies additional options for the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="f3327-943">Ein <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> -Objekt, das den Kontext für den aktuellen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="f3327-943">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <param name="progressHandler"> <span data-ttu-id="f3327-944">Ein <see cref="T:System.IProgress`1" /> Objekt behandelt <see cref="T:Microsoft.WindowsAzure.Storage.Core.Util.StorageProgress" /> Nachrichten.</span><span class="sxs-lookup"><span data-stu-id="f3327-944">A <see cref="T:System.IProgress`1" /> object to handle <see cref="T:Microsoft.WindowsAzure.Storage.Core.Util.StorageProgress" /> messages.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="f3327-945">Ein <see cref="T:System.Threading.CancellationToken" />, das beim Warten auf den Abschluss einer Aufgabe überwacht werden soll.</span><span class="sxs-lookup"><span data-stu-id="f3327-945">A <see cref="T:System.Threading.CancellationToken" /> to observe while waiting for a task to complete.</span></span></param>
        <summary>
            <span data-ttu-id="f3327-946">Initiiert einen asynchronen Vorgang zum Hochladen einer Textzeichenfolge in ein Blob.</span><span class="sxs-lookup"><span data-stu-id="f3327-946">Initiates an asynchronous operation to upload a string of text to a blob.</span></span> <span data-ttu-id="f3327-947">Wenn das Blob bereits vorhanden ist, wird sie überschrieben.</span><span class="sxs-lookup"><span data-stu-id="f3327-947">If the blob already exists, it will be overwritten.</span></span>
            </summary>
        <returns><span data-ttu-id="f3327-948">Ein <see cref="T:System.Threading.Tasks.Task" />-Objekt, das den asynchronen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="f3327-948">A <see cref="T:System.Threading.Tasks.Task" /> object that represents the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>