<Type Name="CloudBlobContainer" FullName="Microsoft.WindowsAzure.Storage.Blob.CloudBlobContainer">
  <TypeSignature Language="C#" Value="public class CloudBlobContainer" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit CloudBlobContainer extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.WindowsAzure.Storage.Blob.CloudBlobContainer" />
  <TypeSignature Language="VB.NET" Value="Public Class CloudBlobContainer" />
  <TypeSignature Language="F#" Value="type CloudBlobContainer = class" />
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
            <span data-ttu-id="5d9cd-101">Stellt einen Container im Microsoft Azure Blob-Dienst dar.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-101">Represents a container in the Microsoft Azure Blob service.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public CloudBlobContainer (Uri containerAddress);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.Uri containerAddress) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlobContainer.#ctor(System.Uri)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (containerAddress As Uri)" />
      <MemberSignature Language="F#" Value="new Microsoft.WindowsAzure.Storage.Blob.CloudBlobContainer : Uri -&gt; Microsoft.WindowsAzure.Storage.Blob.CloudBlobContainer" Usage="new Microsoft.WindowsAzure.Storage.Blob.CloudBlobContainer containerAddress" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="containerAddress" Type="System.Uri" />
      </Parameters>
      <Docs>
        <param name="containerAddress"><span data-ttu-id="5d9cd-102">Ein <see cref="T:System.Uri" /> Objekt, das den absoluten URI zum Container angibt.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-102">A <see cref="T:System.Uri" /> object specifying the absolute URI to the container.</span></span></param>
        <summary>
            <span data-ttu-id="5d9cd-103">Initialisiert eine neue Instanz der <see cref="T:Microsoft.WindowsAzure.Storage.Blob.CloudBlobContainer" />-Klasse.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-103">Initializes a new instance of the <see cref="T:Microsoft.WindowsAzure.Storage.Blob.CloudBlobContainer" /> class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public CloudBlobContainer (Microsoft.WindowsAzure.Storage.StorageUri containerAddress, Microsoft.WindowsAzure.Storage.Auth.StorageCredentials credentials);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class Microsoft.WindowsAzure.Storage.StorageUri containerAddress, class Microsoft.WindowsAzure.Storage.Auth.StorageCredentials credentials) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlobContainer.#ctor(Microsoft.WindowsAzure.Storage.StorageUri,Microsoft.WindowsAzure.Storage.Auth.StorageCredentials)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (containerAddress As StorageUri, credentials As StorageCredentials)" />
      <MemberSignature Language="F#" Value="new Microsoft.WindowsAzure.Storage.Blob.CloudBlobContainer : Microsoft.WindowsAzure.Storage.StorageUri * Microsoft.WindowsAzure.Storage.Auth.StorageCredentials -&gt; Microsoft.WindowsAzure.Storage.Blob.CloudBlobContainer" Usage="new Microsoft.WindowsAzure.Storage.Blob.CloudBlobContainer (containerAddress, credentials)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="containerAddress" Type="Microsoft.WindowsAzure.Storage.StorageUri" />
        <Parameter Name="credentials" Type="Microsoft.WindowsAzure.Storage.Auth.StorageCredentials" />
      </Parameters>
      <Docs>
        <param name="containerAddress"><span data-ttu-id="5d9cd-104">Ein <see cref="T:System.Uri" /> Objekt, das den absoluten URI zum Container angibt.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-104">A <see cref="T:System.Uri" /> object specifying the absolute URI to the container.</span></span></param>
        <param name="credentials"><span data-ttu-id="5d9cd-105">Ein <see cref="T:Microsoft.WindowsAzure.Storage.Auth.StorageCredentials" />-Objekt.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-105">A <see cref="T:Microsoft.WindowsAzure.Storage.Auth.StorageCredentials" /> object.</span></span></param>
        <summary>
            <span data-ttu-id="5d9cd-106">Initialisiert eine neue Instanz der <see cref="T:Microsoft.WindowsAzure.Storage.Blob.CloudBlobContainer" />-Klasse.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-106">Initializes a new instance of the <see cref="T:Microsoft.WindowsAzure.Storage.Blob.CloudBlobContainer" /> class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public CloudBlobContainer (Uri containerAddress, Microsoft.WindowsAzure.Storage.Auth.StorageCredentials credentials);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.Uri containerAddress, class Microsoft.WindowsAzure.Storage.Auth.StorageCredentials credentials) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlobContainer.#ctor(System.Uri,Microsoft.WindowsAzure.Storage.Auth.StorageCredentials)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (containerAddress As Uri, credentials As StorageCredentials)" />
      <MemberSignature Language="F#" Value="new Microsoft.WindowsAzure.Storage.Blob.CloudBlobContainer : Uri * Microsoft.WindowsAzure.Storage.Auth.StorageCredentials -&gt; Microsoft.WindowsAzure.Storage.Blob.CloudBlobContainer" Usage="new Microsoft.WindowsAzure.Storage.Blob.CloudBlobContainer (containerAddress, credentials)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="containerAddress" Type="System.Uri" />
        <Parameter Name="credentials" Type="Microsoft.WindowsAzure.Storage.Auth.StorageCredentials" />
      </Parameters>
      <Docs>
        <param name="containerAddress"><span data-ttu-id="5d9cd-107">Ein <see cref="T:System.Uri" /> Objekt, das den absoluten URI zum Container angibt.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-107">A <see cref="T:System.Uri" /> object specifying the absolute URI to the container.</span></span></param>
        <param name="credentials"><span data-ttu-id="5d9cd-108">Ein <see cref="T:Microsoft.WindowsAzure.Storage.Auth.StorageCredentials" />-Objekt.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-108">A <see cref="T:Microsoft.WindowsAzure.Storage.Auth.StorageCredentials" /> object.</span></span></param>
        <summary>
            <span data-ttu-id="5d9cd-109">Initialisiert eine neue Instanz der <see cref="T:Microsoft.WindowsAzure.Storage.Blob.CloudBlobContainer" />-Klasse.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-109">Initializes a new instance of the <see cref="T:Microsoft.WindowsAzure.Storage.Blob.CloudBlobContainer" /> class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AcquireLease">
      <MemberSignature Language="C#" Value="public virtual string AcquireLease (Nullable&lt;TimeSpan&gt; leaseTime, string proposedLeaseId, Microsoft.WindowsAzure.Storage.AccessCondition accessCondition = null, Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options = null, Microsoft.WindowsAzure.Storage.OperationContext operationContext = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance string AcquireLease(valuetype System.Nullable`1&lt;valuetype System.TimeSpan&gt; leaseTime, string proposedLeaseId, class Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, class Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlobContainer.AcquireLease(System.Nullable{System.TimeSpan},System.String,Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="abstract member AcquireLease : Nullable&lt;TimeSpan&gt; * string * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; string&#xA;override this.AcquireLease : Nullable&lt;TimeSpan&gt; * string * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; string" Usage="cloudBlobContainer.AcquireLease (leaseTime, proposedLeaseId, accessCondition, options, operationContext)" />
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
        <Parameter Name="leaseTime" Type="System.Nullable&lt;System.TimeSpan&gt;" />
        <Parameter Name="proposedLeaseId" Type="System.String" />
        <Parameter Name="accessCondition" Type="Microsoft.WindowsAzure.Storage.AccessCondition" />
        <Parameter Name="options" Type="Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="leaseTime"><span data-ttu-id="5d9cd-110">Ein <see cref="T:System.TimeSpan" /> auf Sekunden abgerundet, die für die Leasedauer, die werden Zeitspanne darstellt.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-110">A <see cref="T:System.TimeSpan" /> representing the span of time for which to acquire the lease, which will be rounded down to seconds.</span></span> <span data-ttu-id="5d9cd-111">Wenn <c>null</c>, wird eine unbegrenzte Lease erworben werden.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-111">If <c>null</c>, an infinite lease will be acquired.</span></span> <span data-ttu-id="5d9cd-112">Wenn Sie nicht null ist, dies muss 15 bis 60 Sekunden.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-112">If not null, this must be 15 to 60 seconds.</span></span></param>
        <param name="proposedLeaseId"><span data-ttu-id="5d9cd-113">Eine Zeichenfolge, die die vorgeschlagene Lease-ID für die neue Leasedauer darstellt oder <c>null</c> , wenn keine Lease-ID vorgeschlagen wird.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-113">A string representing the proposed lease ID for the new lease, or <c>null</c> if no lease ID is proposed.</span></span></param>
        <param name="accessCondition"><span data-ttu-id="5d9cd-114">Ein <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> -Objekt, das die Bedingung, die erfüllt sein müssen, damit die Anforderung darstellt, um den Vorgang fortzusetzen.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-114">An <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> object that represents the condition that must be met in order for the request to proceed.</span></span> <span data-ttu-id="5d9cd-115">Wenn <c>null</c>, keine Bedingung verwendet.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-115">If <c>null</c>, no condition is used.</span></span></param>
        <param name="options"><span data-ttu-id="5d9cd-116">Ein <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" /> -Objekt, das zusätzliche Optionen für die Anforderung angibt.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-116">A <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" /> object that specifies additional options for the request.</span></span> <span data-ttu-id="5d9cd-117">Wenn <c>null</c>, Standardoptionen gelten für die Anforderung.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-117">If <c>null</c>, default options are applied to the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="5d9cd-118">Ein <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> -Objekt, das den Kontext für den aktuellen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-118">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <summary>
            <span data-ttu-id="5d9cd-119">Ruft eine Lease für diesen Container ab.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-119">Acquires a lease on this container.</span></span>
            </summary>
        <returns><span data-ttu-id="5d9cd-120">Die ID der erworbenen Lease.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-120">The ID of the acquired lease.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AcquireLeaseAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task&lt;string&gt; AcquireLeaseAsync (Nullable&lt;TimeSpan&gt; leaseTime, string proposedLeaseId = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;string&gt; AcquireLeaseAsync(valuetype System.Nullable`1&lt;valuetype System.TimeSpan&gt; leaseTime, string proposedLeaseId) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlobContainer.AcquireLeaseAsync(System.Nullable{System.TimeSpan},System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function AcquireLeaseAsync (leaseTime As Nullable(Of TimeSpan), Optional proposedLeaseId As String = null) As Task(Of String)" />
      <MemberSignature Language="F#" Value="abstract member AcquireLeaseAsync : Nullable&lt;TimeSpan&gt; * string -&gt; System.Threading.Tasks.Task&lt;string&gt;&#xA;override this.AcquireLeaseAsync : Nullable&lt;TimeSpan&gt; * string -&gt; System.Threading.Tasks.Task&lt;string&gt;" Usage="cloudBlobContainer.AcquireLeaseAsync (leaseTime, proposedLeaseId)" />
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
        <Parameter Name="leaseTime" Type="System.Nullable&lt;System.TimeSpan&gt;" />
        <Parameter Name="proposedLeaseId" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="leaseTime"><span data-ttu-id="5d9cd-121">Ein <see cref="T:System.TimeSpan" /> auf Sekunden abgerundet, die für die Leasedauer, die werden Zeitspanne darstellt.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-121">A <see cref="T:System.TimeSpan" /> representing the span of time for which to acquire the lease, which will be rounded down to seconds.</span></span> <span data-ttu-id="5d9cd-122">Wenn <c>null</c>, wird eine unbegrenzte Lease erworben werden.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-122">If <c>null</c>, an infinite lease will be acquired.</span></span> <span data-ttu-id="5d9cd-123">Wenn Sie nicht null ist, dies muss 15 bis 60 Sekunden.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-123">If not null, this must be 15 to 60 seconds.</span></span></param>
        <param name="proposedLeaseId"><span data-ttu-id="5d9cd-124">Eine Zeichenfolge, die die vorgeschlagene Lease-ID für die neue Leasedauer darstellt oder <c>null</c> , wenn keine Lease-ID vorgeschlagen wird.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-124">A string representing the proposed lease ID for the new lease, or <c>null</c> if no lease ID is proposed.</span></span></param>
        <summary>
            <span data-ttu-id="5d9cd-125">Initiiert einen asynchronen Vorgang, der eine Lease für diesen Container abruft.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-125">Initiates an asynchronous operation that acquires a lease on this container.</span></span>
            </summary>
        <returns><span data-ttu-id="5d9cd-126">Ein <see cref="T:System.Threading.Tasks.Task`1" />-Objekt, das den asynchronen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-126">A <see cref="T:System.Threading.Tasks.Task`1" /> object that represents the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AcquireLeaseAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task&lt;string&gt; AcquireLeaseAsync (Nullable&lt;TimeSpan&gt; leaseTime, string proposedLeaseId, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;string&gt; AcquireLeaseAsync(valuetype System.Nullable`1&lt;valuetype System.TimeSpan&gt; leaseTime, string proposedLeaseId, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlobContainer.AcquireLeaseAsync(System.Nullable{System.TimeSpan},System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member AcquireLeaseAsync : Nullable&lt;TimeSpan&gt; * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;string&gt;&#xA;override this.AcquireLeaseAsync : Nullable&lt;TimeSpan&gt; * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;string&gt;" Usage="cloudBlobContainer.AcquireLeaseAsync (leaseTime, proposedLeaseId, cancellationToken)" />
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
        <Parameter Name="leaseTime" Type="System.Nullable&lt;System.TimeSpan&gt;" />
        <Parameter Name="proposedLeaseId" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="leaseTime"><span data-ttu-id="5d9cd-127">Ein <see cref="T:System.TimeSpan" /> auf Sekunden abgerundet, die für die Leasedauer, die werden Zeitspanne darstellt.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-127">A <see cref="T:System.TimeSpan" /> representing the span of time for which to acquire the lease, which will be rounded down to seconds.</span></span> <span data-ttu-id="5d9cd-128">Wenn <c>null</c>, wird eine unbegrenzte Lease erworben werden.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-128">If <c>null</c>, an infinite lease will be acquired.</span></span> <span data-ttu-id="5d9cd-129">Wenn Sie nicht null ist, dies muss 15 bis 60 Sekunden.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-129">If not null, this must be 15 to 60 seconds.</span></span></param>
        <param name="proposedLeaseId"><span data-ttu-id="5d9cd-130">Eine Zeichenfolge, die die vorgeschlagene Lease-ID für die neue Leasedauer darstellt oder <c>null</c> , wenn keine Lease-ID vorgeschlagen wird.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-130">A string representing the proposed lease ID for the new lease, or <c>null</c> if no lease ID is proposed.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="5d9cd-131">Ein <see cref="T:System.Threading.CancellationToken" />, das beim Warten auf den Abschluss einer Aufgabe überwacht werden soll.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-131">A <see cref="T:System.Threading.CancellationToken" /> to observe while waiting for a task to complete.</span></span></param>
        <summary>
            <span data-ttu-id="5d9cd-132">Initiiert einen asynchronen Vorgang, der eine Lease für diesen Container abruft.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-132">Initiates an asynchronous operation that acquires a lease on this container.</span></span>
            </summary>
        <returns><span data-ttu-id="5d9cd-133">Ein <see cref="T:System.Threading.Tasks.Task`1" />-Objekt, das den asynchronen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-133">A <see cref="T:System.Threading.Tasks.Task`1" /> object that represents the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AcquireLeaseAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task&lt;string&gt; AcquireLeaseAsync (Nullable&lt;TimeSpan&gt; leaseTime, string proposedLeaseId, Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, Microsoft.WindowsAzure.Storage.OperationContext operationContext);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;string&gt; AcquireLeaseAsync(valuetype System.Nullable`1&lt;valuetype System.TimeSpan&gt; leaseTime, string proposedLeaseId, class Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, class Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlobContainer.AcquireLeaseAsync(System.Nullable{System.TimeSpan},System.String,Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="abstract member AcquireLeaseAsync : Nullable&lt;TimeSpan&gt; * string * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Threading.Tasks.Task&lt;string&gt;&#xA;override this.AcquireLeaseAsync : Nullable&lt;TimeSpan&gt; * string * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Threading.Tasks.Task&lt;string&gt;" Usage="cloudBlobContainer.AcquireLeaseAsync (leaseTime, proposedLeaseId, accessCondition, options, operationContext)" />
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
        <Parameter Name="leaseTime" Type="System.Nullable&lt;System.TimeSpan&gt;" />
        <Parameter Name="proposedLeaseId" Type="System.String" />
        <Parameter Name="accessCondition" Type="Microsoft.WindowsAzure.Storage.AccessCondition" />
        <Parameter Name="options" Type="Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="leaseTime"><span data-ttu-id="5d9cd-134">Ein <see cref="T:System.TimeSpan" /> auf Sekunden abgerundet, die für die Leasedauer, die werden Zeitspanne darstellt.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-134">A <see cref="T:System.TimeSpan" /> representing the span of time for which to acquire the lease, which will be rounded down to seconds.</span></span> <span data-ttu-id="5d9cd-135">Wenn <c>null</c>, wird eine unbegrenzte Lease erworben werden.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-135">If <c>null</c>, an infinite lease will be acquired.</span></span> <span data-ttu-id="5d9cd-136">Wenn Sie nicht null ist, dies muss 15 bis 60 Sekunden.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-136">If not null, this must be 15 to 60 seconds.</span></span></param>
        <param name="proposedLeaseId"><span data-ttu-id="5d9cd-137">Eine Zeichenfolge, die die vorgeschlagene Lease-ID für die neue Leasedauer darstellt oder <c>null</c> , wenn keine Lease-ID vorgeschlagen wird.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-137">A string representing the proposed lease ID for the new lease, or <c>null</c> if no lease ID is proposed.</span></span></param>
        <param name="accessCondition"><span data-ttu-id="5d9cd-138">Ein <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> -Objekt, das die Bedingung, die erfüllt sein müssen, damit die Anforderung darstellt, um den Vorgang fortzusetzen.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-138">An <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> object that represents the condition that must be met in order for the request to proceed.</span></span> <span data-ttu-id="5d9cd-139">Wenn <c>null</c>, keine Bedingung verwendet.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-139">If <c>null</c>, no condition is used.</span></span></param>
        <param name="options"><span data-ttu-id="5d9cd-140">Ein <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" /> -Objekt, das zusätzliche Optionen für die Anforderung angibt.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-140">A <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" /> object that specifies additional options for the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="5d9cd-141">Ein <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> -Objekt, das den Kontext für den aktuellen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-141">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <summary>
            <span data-ttu-id="5d9cd-142">Initiiert einen asynchronen Vorgang, der eine Lease für diesen Container abruft.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-142">Initiates an asynchronous operation that acquires a lease on this container.</span></span>
            </summary>
        <returns><span data-ttu-id="5d9cd-143">Ein <see cref="T:System.Threading.Tasks.Task`1" />-Objekt, das den asynchronen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-143">A <see cref="T:System.Threading.Tasks.Task`1" /> object that represents the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AcquireLeaseAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task&lt;string&gt; AcquireLeaseAsync (Nullable&lt;TimeSpan&gt; leaseTime, string proposedLeaseId, Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, Microsoft.WindowsAzure.Storage.OperationContext operationContext, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;string&gt; AcquireLeaseAsync(valuetype System.Nullable`1&lt;valuetype System.TimeSpan&gt; leaseTime, string proposedLeaseId, class Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, class Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, class Microsoft.WindowsAzure.Storage.OperationContext operationContext, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlobContainer.AcquireLeaseAsync(System.Nullable{System.TimeSpan},System.String,Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member AcquireLeaseAsync : Nullable&lt;TimeSpan&gt; * string * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;string&gt;&#xA;override this.AcquireLeaseAsync : Nullable&lt;TimeSpan&gt; * string * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;string&gt;" Usage="cloudBlobContainer.AcquireLeaseAsync (leaseTime, proposedLeaseId, accessCondition, options, operationContext, cancellationToken)" />
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
        <Parameter Name="leaseTime" Type="System.Nullable&lt;System.TimeSpan&gt;" />
        <Parameter Name="proposedLeaseId" Type="System.String" />
        <Parameter Name="accessCondition" Type="Microsoft.WindowsAzure.Storage.AccessCondition" />
        <Parameter Name="options" Type="Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="leaseTime"><span data-ttu-id="5d9cd-144">Ein <see cref="T:System.TimeSpan" /> auf Sekunden abgerundet, die für die Leasedauer, die werden Zeitspanne darstellt.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-144">A <see cref="T:System.TimeSpan" /> representing the span of time for which to acquire the lease, which will be rounded down to seconds.</span></span> <span data-ttu-id="5d9cd-145">Wenn <c>null</c>, wird eine unbegrenzte Lease erworben werden.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-145">If <c>null</c>, an infinite lease will be acquired.</span></span> <span data-ttu-id="5d9cd-146">Wenn Sie nicht null ist, dies muss 15 bis 60 Sekunden.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-146">If not null, this must be 15 to 60 seconds.</span></span></param>
        <param name="proposedLeaseId"><span data-ttu-id="5d9cd-147">Eine Zeichenfolge, die die vorgeschlagene Lease-ID für die neue Leasedauer darstellt oder <c>null</c> , wenn keine Lease-ID vorgeschlagen wird.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-147">A string representing the proposed lease ID for the new lease, or <c>null</c> if no lease ID is proposed.</span></span></param>
        <param name="accessCondition"><span data-ttu-id="5d9cd-148">Ein <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> -Objekt, das die Bedingung, die erfüllt sein müssen, damit die Anforderung darstellt, um den Vorgang fortzusetzen.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-148">An <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> object that represents the condition that must be met in order for the request to proceed.</span></span> <span data-ttu-id="5d9cd-149">Wenn <c>null</c>, keine Bedingung verwendet.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-149">If <c>null</c>, no condition is used.</span></span></param>
        <param name="options"><span data-ttu-id="5d9cd-150">Ein <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" /> -Objekt, das zusätzliche Optionen für die Anforderung angibt.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-150">A <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" /> object that specifies additional options for the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="5d9cd-151">Ein <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> -Objekt, das den Kontext für den aktuellen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-151">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="5d9cd-152">Ein <see cref="T:System.Threading.CancellationToken" />, das beim Warten auf den Abschluss einer Aufgabe überwacht werden soll.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-152">A <see cref="T:System.Threading.CancellationToken" /> to observe while waiting for a task to complete.</span></span></param>
        <summary>
            <span data-ttu-id="5d9cd-153">Initiiert einen asynchronen Vorgang, der eine Lease für diesen Container abruft.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-153">Initiates an asynchronous operation that acquires a lease on this container.</span></span>
            </summary>
        <returns><span data-ttu-id="5d9cd-154">Ein <see cref="T:System.Threading.Tasks.Task`1" />-Objekt, das den asynchronen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-154">A <see cref="T:System.Threading.Tasks.Task`1" /> object that represents the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginAcquireLease">
      <MemberSignature Language="C#" Value="public virtual Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginAcquireLease (Nullable&lt;TimeSpan&gt; leaseTime, string proposedLeaseId, AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginAcquireLease(valuetype System.Nullable`1&lt;valuetype System.TimeSpan&gt; leaseTime, string proposedLeaseId, class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlobContainer.BeginAcquireLease(System.Nullable{System.TimeSpan},System.String,System.AsyncCallback,System.Object)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function BeginAcquireLease (leaseTime As Nullable(Of TimeSpan), proposedLeaseId As String, callback As AsyncCallback, state As Object) As ICancellableAsyncResult" />
      <MemberSignature Language="F#" Value="abstract member BeginAcquireLease : Nullable&lt;TimeSpan&gt; * string * AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult&#xA;override this.BeginAcquireLease : Nullable&lt;TimeSpan&gt; * string * AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" Usage="cloudBlobContainer.BeginAcquireLease (leaseTime, proposedLeaseId, callback, state)" />
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
        <Parameter Name="leaseTime" Type="System.Nullable&lt;System.TimeSpan&gt;" />
        <Parameter Name="proposedLeaseId" Type="System.String" />
        <Parameter Name="callback" Type="System.AsyncCallback" />
        <Parameter Name="state" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="leaseTime"><span data-ttu-id="5d9cd-155">Ein <see cref="T:System.TimeSpan" /> auf Sekunden abgerundet, die für die Leasedauer, die werden Zeitspanne darstellt.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-155">A <see cref="T:System.TimeSpan" /> representing the span of time for which to acquire the lease, which will be rounded down to seconds.</span></span> <span data-ttu-id="5d9cd-156">Wenn <c>null</c>, wird eine unbegrenzte Lease erworben werden.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-156">If <c>null</c>, an infinite lease will be acquired.</span></span> <span data-ttu-id="5d9cd-157">Wenn Sie nicht null ist, dies muss 15 bis 60 Sekunden.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-157">If not null, this must be 15 to 60 seconds.</span></span></param>
        <param name="proposedLeaseId"><span data-ttu-id="5d9cd-158">Eine Zeichenfolge, die die vorgeschlagene Lease-ID für die neue Leasedauer darstellt oder <c>null</c> , wenn keine Lease-ID vorgeschlagen wird.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-158">A string representing the proposed lease ID for the new lease, or <c>null</c> if no lease ID is proposed.</span></span></param>
        <param name="callback"><span data-ttu-id="5d9cd-159">Eine optionale Rückrufdelegat, der Benachrichtigung erhalten sollen, wenn der asynchrone Vorgang abgeschlossen ist.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-159">An optional callback delegate that will receive notification when the asynchronous operation completes.</span></span></param>
        <param name="state"><span data-ttu-id="5d9cd-160">Ein benutzerdefiniertes Objekt, die an dem Rückrufdelegaten übergeben werden.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-160">A user-defined object that will be passed to the callback delegate.</span></span></param>
        <summary>
            <span data-ttu-id="5d9cd-161">Startet einen asynchronen Vorgang zum Abrufen einer Lease für diesen Container.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-161">Begins an asynchronous operation to acquire a lease on this container.</span></span>
            </summary>
        <returns><span data-ttu-id="5d9cd-162">Ein <see cref="T:Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" /> , das auf den asynchronen Vorgang verweist.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-162">An <see cref="T:Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" /> that references the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginAcquireLease">
      <MemberSignature Language="C#" Value="public virtual Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginAcquireLease (Nullable&lt;TimeSpan&gt; leaseTime, string proposedLeaseId, Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, Microsoft.WindowsAzure.Storage.OperationContext operationContext, AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginAcquireLease(valuetype System.Nullable`1&lt;valuetype System.TimeSpan&gt; leaseTime, string proposedLeaseId, class Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, class Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, class Microsoft.WindowsAzure.Storage.OperationContext operationContext, class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlobContainer.BeginAcquireLease(System.Nullable{System.TimeSpan},System.String,Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext,System.AsyncCallback,System.Object)" />
      <MemberSignature Language="F#" Value="abstract member BeginAcquireLease : Nullable&lt;TimeSpan&gt; * string * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult&#xA;override this.BeginAcquireLease : Nullable&lt;TimeSpan&gt; * string * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" Usage="cloudBlobContainer.BeginAcquireLease (leaseTime, proposedLeaseId, accessCondition, options, operationContext, callback, state)" />
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
        <Parameter Name="leaseTime" Type="System.Nullable&lt;System.TimeSpan&gt;" />
        <Parameter Name="proposedLeaseId" Type="System.String" />
        <Parameter Name="accessCondition" Type="Microsoft.WindowsAzure.Storage.AccessCondition" />
        <Parameter Name="options" Type="Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
        <Parameter Name="callback" Type="System.AsyncCallback" />
        <Parameter Name="state" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="leaseTime"><span data-ttu-id="5d9cd-163">Ein <see cref="T:System.TimeSpan" /> auf Sekunden abgerundet, die für die Leasedauer, die werden Zeitspanne darstellt.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-163">A <see cref="T:System.TimeSpan" /> representing the span of time for which to acquire the lease, which will be rounded down to seconds.</span></span> <span data-ttu-id="5d9cd-164">Wenn <c>null</c>, wird eine unbegrenzte Lease erworben werden.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-164">If <c>null</c>, an infinite lease will be acquired.</span></span> <span data-ttu-id="5d9cd-165">Wenn Sie nicht null ist, dies muss 15 bis 60 Sekunden.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-165">If not null, this must be 15 to 60 seconds.</span></span></param>
        <param name="proposedLeaseId"><span data-ttu-id="5d9cd-166">Eine Zeichenfolge, die die vorgeschlagene Lease-ID für die neue Leasedauer darstellt oder <c>null</c> , wenn keine Lease-ID vorgeschlagen wird.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-166">A string representing the proposed lease ID for the new lease, or <c>null</c> if no lease ID is proposed.</span></span></param>
        <param name="accessCondition"><span data-ttu-id="5d9cd-167">Ein <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> -Objekt, das die Bedingung, die erfüllt sein müssen, damit die Anforderung darstellt, um den Vorgang fortzusetzen.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-167">An <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> object that represents the condition that must be met in order for the request to proceed.</span></span> <span data-ttu-id="5d9cd-168">Wenn <c>null</c>, keine Bedingung verwendet.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-168">If <c>null</c>, no condition is used.</span></span></param>
        <param name="options"><span data-ttu-id="5d9cd-169">Ein <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" /> -Objekt, das zusätzliche Optionen für die Anforderung angibt.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-169">A <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" /> object that specifies additional options for the request.</span></span> <span data-ttu-id="5d9cd-170">Wenn <c>null</c>, Standardoptionen gelten für die Anforderung.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-170">If <c>null</c>, default options are applied to the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="5d9cd-171">Ein <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> -Objekt, das den Kontext für den aktuellen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-171">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <param name="callback"><span data-ttu-id="5d9cd-172">Eine optionale Rückrufdelegat, der Benachrichtigung erhalten sollen, wenn der asynchrone Vorgang abgeschlossen ist.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-172">An optional callback delegate that will receive notification when the asynchronous operation completes.</span></span></param>
        <param name="state"><span data-ttu-id="5d9cd-173">Ein benutzerdefiniertes Objekt, die an dem Rückrufdelegaten übergeben werden.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-173">A user-defined object that will be passed to the callback delegate.</span></span></param>
        <summary>
            <span data-ttu-id="5d9cd-174">Startet einen asynchronen Vorgang zum Abrufen einer Lease für diesen Container.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-174">Begins an asynchronous operation to acquire a lease on this container.</span></span>
            </summary>
        <returns><span data-ttu-id="5d9cd-175">Ein <see cref="T:Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" /> , das auf den asynchronen Vorgang verweist.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-175">An <see cref="T:Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" /> that references the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginBreakLease">
      <MemberSignature Language="C#" Value="public virtual Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginBreakLease (Nullable&lt;TimeSpan&gt; breakPeriod, AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginBreakLease(valuetype System.Nullable`1&lt;valuetype System.TimeSpan&gt; breakPeriod, class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlobContainer.BeginBreakLease(System.Nullable{System.TimeSpan},System.AsyncCallback,System.Object)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function BeginBreakLease (breakPeriod As Nullable(Of TimeSpan), callback As AsyncCallback, state As Object) As ICancellableAsyncResult" />
      <MemberSignature Language="F#" Value="abstract member BeginBreakLease : Nullable&lt;TimeSpan&gt; * AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult&#xA;override this.BeginBreakLease : Nullable&lt;TimeSpan&gt; * AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" Usage="cloudBlobContainer.BeginBreakLease (breakPeriod, callback, state)" />
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
        <Parameter Name="breakPeriod" Type="System.Nullable&lt;System.TimeSpan&gt;" />
        <Parameter Name="callback" Type="System.AsyncCallback" />
        <Parameter Name="state" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="breakPeriod"><span data-ttu-id="5d9cd-176">Ein <see cref="T:System.TimeSpan" /> , die die Menge an Zeit, die auf den, Leasedauer auf Sekunden abgerundet darstellt.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-176">A <see cref="T:System.TimeSpan" /> representing the amount of time to allow the lease to remain, which will be rounded down to seconds.</span></span> <span data-ttu-id="5d9cd-177">Wenn <c>null</c>, der Unterbrechungszeitraum ist der Rest der aktuellen Lease oder 0 (null) bei unbegrenzten Leases.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-177">If <c>null</c>, the break period is the remainder of the current lease, or zero for infinite leases.</span></span></param>
        <param name="callback"><span data-ttu-id="5d9cd-178">Eine optionale Rückrufdelegat, der Benachrichtigung erhalten sollen, wenn der asynchrone Vorgang abgeschlossen ist.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-178">An optional callback delegate that will receive notification when the asynchronous operation completes.</span></span></param>
        <param name="state"><span data-ttu-id="5d9cd-179">Ein benutzerdefiniertes Objekt, die an dem Rückrufdelegaten übergeben werden.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-179">A user-defined object that will be passed to the callback delegate.</span></span></param>
        <summary>
            <span data-ttu-id="5d9cd-180">Startet einen asynchronen Vorgang zum Unterbrechen der aktuellen Lease für diesen Container.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-180">Begins an asynchronous operation to break the current lease on this container.</span></span>
            </summary>
        <returns><span data-ttu-id="5d9cd-181">Ein <see cref="T:Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" /> , das auf den asynchronen Vorgang verweist.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-181">An <see cref="T:Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" /> that references the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginBreakLease">
      <MemberSignature Language="C#" Value="public virtual Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginBreakLease (Nullable&lt;TimeSpan&gt; breakPeriod, Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, Microsoft.WindowsAzure.Storage.OperationContext operationContext, AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginBreakLease(valuetype System.Nullable`1&lt;valuetype System.TimeSpan&gt; breakPeriod, class Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, class Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, class Microsoft.WindowsAzure.Storage.OperationContext operationContext, class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlobContainer.BeginBreakLease(System.Nullable{System.TimeSpan},Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext,System.AsyncCallback,System.Object)" />
      <MemberSignature Language="F#" Value="abstract member BeginBreakLease : Nullable&lt;TimeSpan&gt; * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult&#xA;override this.BeginBreakLease : Nullable&lt;TimeSpan&gt; * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" Usage="cloudBlobContainer.BeginBreakLease (breakPeriod, accessCondition, options, operationContext, callback, state)" />
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
        <Parameter Name="breakPeriod" Type="System.Nullable&lt;System.TimeSpan&gt;" />
        <Parameter Name="accessCondition" Type="Microsoft.WindowsAzure.Storage.AccessCondition" />
        <Parameter Name="options" Type="Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
        <Parameter Name="callback" Type="System.AsyncCallback" />
        <Parameter Name="state" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="breakPeriod"><span data-ttu-id="5d9cd-182">Ein <see cref="T:System.TimeSpan" /> , die die Menge an Zeit, die auf den, Leasedauer auf Sekunden abgerundet darstellt.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-182">A <see cref="T:System.TimeSpan" /> representing the amount of time to allow the lease to remain, which will be rounded down to seconds.</span></span> <span data-ttu-id="5d9cd-183">Wenn <c>null</c>, der Unterbrechungszeitraum ist der Rest der aktuellen Lease oder 0 (null) bei unbegrenzten Leases.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-183">If <c>null</c>, the break period is the remainder of the current lease, or zero for infinite leases.</span></span></param>
        <param name="accessCondition"><span data-ttu-id="5d9cd-184">Ein <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> -Objekt, das die Bedingung, die erfüllt sein müssen, damit die Anforderung darstellt, um den Vorgang fortzusetzen.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-184">An <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> object that represents the condition that must be met in order for the request to proceed.</span></span> <span data-ttu-id="5d9cd-185">Wenn <c>null</c>, keine Bedingung verwendet.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-185">If <c>null</c>, no condition is used.</span></span></param>
        <param name="options"><span data-ttu-id="5d9cd-186">Ein <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" /> -Objekt, das zusätzliche Optionen für die Anforderung angibt.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-186">A <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" /> object that specifies additional options for the request.</span></span> <span data-ttu-id="5d9cd-187">Wenn <c>null</c>, Standardoptionen gelten für die Anforderung.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-187">If <c>null</c>, default options are applied to the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="5d9cd-188">Ein <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> -Objekt, das den Kontext für den aktuellen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-188">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <param name="callback"><span data-ttu-id="5d9cd-189">Eine optionale Rückrufdelegat, der Benachrichtigung erhalten sollen, wenn der asynchrone Vorgang abgeschlossen ist.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-189">An optional callback delegate that will receive notification when the asynchronous operation completes.</span></span></param>
        <param name="state"><span data-ttu-id="5d9cd-190">Ein benutzerdefiniertes Objekt, die an dem Rückrufdelegaten übergeben werden.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-190">A user-defined object that will be passed to the callback delegate.</span></span></param>
        <summary>
            <span data-ttu-id="5d9cd-191">Startet einen asynchronen Vorgang zum Unterbrechen der aktuellen Lease für diesen Container.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-191">Begins an asynchronous operation to break the current lease on this container.</span></span>
            </summary>
        <returns><span data-ttu-id="5d9cd-192">Ein <see cref="T:Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" /> , das auf den asynchronen Vorgang verweist.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-192">An <see cref="T:Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" /> that references the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginChangeLease">
      <MemberSignature Language="C#" Value="public virtual Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginChangeLease (string proposedLeaseId, Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginChangeLease(string proposedLeaseId, class Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlobContainer.BeginChangeLease(System.String,Microsoft.WindowsAzure.Storage.AccessCondition,System.AsyncCallback,System.Object)" />
      <MemberSignature Language="F#" Value="abstract member BeginChangeLease : string * Microsoft.WindowsAzure.Storage.AccessCondition * AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult&#xA;override this.BeginChangeLease : string * Microsoft.WindowsAzure.Storage.AccessCondition * AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" Usage="cloudBlobContainer.BeginChangeLease (proposedLeaseId, accessCondition, callback, state)" />
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
        <Parameter Name="proposedLeaseId" Type="System.String" />
        <Parameter Name="accessCondition" Type="Microsoft.WindowsAzure.Storage.AccessCondition" />
        <Parameter Name="callback" Type="System.AsyncCallback" />
        <Parameter Name="state" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="proposedLeaseId"><span data-ttu-id="5d9cd-193">Eine Zeichenfolge, die die vorgeschlagene Lease-ID für die neue Leasedauer darstellt.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-193">A string representing the proposed lease ID for the new lease.</span></span> <span data-ttu-id="5d9cd-194">Dies darf nicht null sein.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-194">This cannot be null.</span></span></param>
        <param name="accessCondition"><span data-ttu-id="5d9cd-195">Ein <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> Objekt, das die Bedingung, die erfüllt sein muss, damit die Anforderung zu fortfahren, darstellt, einschließlich einer erforderlichen Lease-ID.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-195">An <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> object that represents the condition that must be met in order for the request to proceed, including a required lease ID.</span></span></param>
        <param name="callback"><span data-ttu-id="5d9cd-196">Eine optionale Rückrufdelegat, der Benachrichtigung erhalten sollen, wenn der asynchrone Vorgang abgeschlossen ist.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-196">An optional callback delegate that will receive notification when the asynchronous operation completes.</span></span></param>
        <param name="state"><span data-ttu-id="5d9cd-197">Ein benutzerdefiniertes Objekt, die an dem Rückrufdelegaten übergeben werden.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-197">A user-defined object that will be passed to the callback delegate.</span></span></param>
        <summary>
            <span data-ttu-id="5d9cd-198">Startet einen asynchronen Vorgang zum Ändern der Lease für diesen Container.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-198">Begins an asynchronous operation to change the lease on this container.</span></span>
            </summary>
        <returns><span data-ttu-id="5d9cd-199">Ein <see cref="T:Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" /> , das auf den asynchronen Vorgang verweist.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-199">An <see cref="T:Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" /> that references the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginChangeLease">
      <MemberSignature Language="C#" Value="public virtual Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginChangeLease (string proposedLeaseId, Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, Microsoft.WindowsAzure.Storage.OperationContext operationContext, AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginChangeLease(string proposedLeaseId, class Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, class Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, class Microsoft.WindowsAzure.Storage.OperationContext operationContext, class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlobContainer.BeginChangeLease(System.String,Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext,System.AsyncCallback,System.Object)" />
      <MemberSignature Language="F#" Value="abstract member BeginChangeLease : string * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult&#xA;override this.BeginChangeLease : string * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" Usage="cloudBlobContainer.BeginChangeLease (proposedLeaseId, accessCondition, options, operationContext, callback, state)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Storage.ICancellableAsyncResult</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="proposedLeaseId" Type="System.String" />
        <Parameter Name="accessCondition" Type="Microsoft.WindowsAzure.Storage.AccessCondition" />
        <Parameter Name="options" Type="Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
        <Parameter Name="callback" Type="System.AsyncCallback" />
        <Parameter Name="state" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="proposedLeaseId"><span data-ttu-id="5d9cd-200">Eine Zeichenfolge, die die vorgeschlagene Lease-ID für die neue Leasedauer darstellt.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-200">A string representing the proposed lease ID for the new lease.</span></span> <span data-ttu-id="5d9cd-201">Dies darf nicht null sein.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-201">This cannot be null.</span></span></param>
        <param name="accessCondition"><span data-ttu-id="5d9cd-202">Ein <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> Objekt, das die Bedingung, die erfüllt sein muss, damit die Anforderung zu fortfahren, darstellt, einschließlich einer erforderlichen Lease-ID.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-202">An <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> object that represents the condition that must be met in order for the request to proceed, including a required lease ID.</span></span></param>
        <param name="options"><span data-ttu-id="5d9cd-203">Ein <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" /> -Objekt, das zusätzliche Optionen für die Anforderung angibt.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-203">A <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" /> object that specifies additional options for the request.</span></span> <span data-ttu-id="5d9cd-204">Wenn <c>null</c>, Standardoptionen gelten für die Anforderung.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-204">If <c>null</c>, default options are applied to the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="5d9cd-205">Ein <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> -Objekt, das den Kontext für den aktuellen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-205">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <param name="callback"><span data-ttu-id="5d9cd-206">Eine optionale Rückrufdelegat, der Benachrichtigung erhalten sollen, wenn der asynchrone Vorgang abgeschlossen ist.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-206">An optional callback delegate that will receive notification when the asynchronous operation completes.</span></span></param>
        <param name="state"><span data-ttu-id="5d9cd-207">Ein benutzerdefiniertes Objekt, die an dem Rückrufdelegaten übergeben werden.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-207">A user-defined object that will be passed to the callback delegate.</span></span></param>
        <summary>
            <span data-ttu-id="5d9cd-208">Startet einen asynchronen Vorgang zum Ändern der Lease für diesen Container.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-208">Begins an asynchronous operation to change the lease on this container.</span></span>
            </summary>
        <returns><span data-ttu-id="5d9cd-209">Ein <see cref="T:Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" /> , das auf den asynchronen Vorgang verweist.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-209">An <see cref="T:Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" /> that references the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginCreate">
      <MemberSignature Language="C#" Value="public virtual Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginCreate (AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginCreate(class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlobContainer.BeginCreate(System.AsyncCallback,System.Object)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function BeginCreate (callback As AsyncCallback, state As Object) As ICancellableAsyncResult" />
      <MemberSignature Language="F#" Value="abstract member BeginCreate : AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult&#xA;override this.BeginCreate : AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" Usage="cloudBlobContainer.BeginCreate (callback, state)" />
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
        <param name="callback"><span data-ttu-id="5d9cd-210">Ein <see cref="T:System.AsyncCallback" /> Delegat, der Benachrichtigung erhalten sollen, wenn der asynchrone Vorgang abgeschlossen ist.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-210">An <see cref="T:System.AsyncCallback" /> delegate that will receive notification when the asynchronous operation completes.</span></span></param>
        <param name="state"><span data-ttu-id="5d9cd-211">Ein benutzerdefiniertes Objekt, die an dem Rückrufdelegaten übergeben werden.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-211">A user-defined object that will be passed to the callback delegate.</span></span></param>
        <summary>
            <span data-ttu-id="5d9cd-212">Startet einen asynchronen Vorgang zum Erstellen eines Containers.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-212">Begins an asynchronous operation to create a container.</span></span>
            </summary>
        <returns><span data-ttu-id="5d9cd-213">Ein <see cref="T:Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" /> , das auf den asynchronen Vorgang verweist.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-213">An <see cref="T:Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" /> that references the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginCreate">
      <MemberSignature Language="C#" Value="public virtual Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginCreate (Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, Microsoft.WindowsAzure.Storage.OperationContext operationContext, AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginCreate(class Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, class Microsoft.WindowsAzure.Storage.OperationContext operationContext, class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlobContainer.BeginCreate(Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext,System.AsyncCallback,System.Object)" />
      <MemberSignature Language="F#" Value="abstract member BeginCreate : Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult&#xA;override this.BeginCreate : Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" Usage="cloudBlobContainer.BeginCreate (options, operationContext, callback, state)" />
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
        <Parameter Name="options" Type="Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
        <Parameter Name="callback" Type="System.AsyncCallback" />
        <Parameter Name="state" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="options"><span data-ttu-id="5d9cd-214">Ein <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" /> -Objekt, das zusätzliche Optionen für die Anforderung angibt.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-214">A <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" /> object that specifies additional options for the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="5d9cd-215">Ein <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> -Objekt, das den Kontext für den aktuellen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-215">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <param name="callback"><span data-ttu-id="5d9cd-216">Ein <see cref="T:System.AsyncCallback" /> Delegat, der Benachrichtigung erhalten sollen, wenn der asynchrone Vorgang abgeschlossen ist.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-216">An <see cref="T:System.AsyncCallback" /> delegate that will receive notification when the asynchronous operation completes.</span></span></param>
        <param name="state"><span data-ttu-id="5d9cd-217">Ein benutzerdefiniertes Objekt, die an dem Rückrufdelegaten übergeben werden.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-217">A user-defined object that will be passed to the callback delegate.</span></span></param>
        <summary>
            <span data-ttu-id="5d9cd-218">Startet einen asynchronen Vorgang zum Erstellen eines Containers.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-218">Begins an asynchronous operation to create a container.</span></span>
            </summary>
        <returns><span data-ttu-id="5d9cd-219">Ein <see cref="T:Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" /> , das auf den asynchronen Vorgang verweist.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-219">An <see cref="T:Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" /> that references the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginCreate">
      <MemberSignature Language="C#" Value="public virtual Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginCreate (Microsoft.WindowsAzure.Storage.Blob.BlobContainerPublicAccessType accessType, Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, Microsoft.WindowsAzure.Storage.OperationContext operationContext, AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginCreate(valuetype Microsoft.WindowsAzure.Storage.Blob.BlobContainerPublicAccessType accessType, class Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, class Microsoft.WindowsAzure.Storage.OperationContext operationContext, class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlobContainer.BeginCreate(Microsoft.WindowsAzure.Storage.Blob.BlobContainerPublicAccessType,Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext,System.AsyncCallback,System.Object)" />
      <MemberSignature Language="F#" Value="abstract member BeginCreate : Microsoft.WindowsAzure.Storage.Blob.BlobContainerPublicAccessType * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult&#xA;override this.BeginCreate : Microsoft.WindowsAzure.Storage.Blob.BlobContainerPublicAccessType * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" Usage="cloudBlobContainer.BeginCreate (accessType, options, operationContext, callback, state)" />
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
        <Parameter Name="accessType" Type="Microsoft.WindowsAzure.Storage.Blob.BlobContainerPublicAccessType" />
        <Parameter Name="options" Type="Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
        <Parameter Name="callback" Type="System.AsyncCallback" />
        <Parameter Name="state" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="accessType"><span data-ttu-id="5d9cd-220">Ein <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobContainerPublicAccessType" /> Objekt, das angibt, ob die Daten im Container öffentlich zugegriffen werden können und welche Zugriffsebene zulässig sein.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-220">An <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobContainerPublicAccessType" /> object that specifies whether data in the container may be accessed publicly and what level of access is to be allowed.</span></span></param>
        <param name="options"><span data-ttu-id="5d9cd-221">Ein <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" /> -Objekt, das zusätzliche Optionen für die Anforderung angibt.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-221">A <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" /> object that specifies additional options for the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="5d9cd-222">Ein <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> -Objekt, das den Kontext für den aktuellen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-222">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <param name="callback"><span data-ttu-id="5d9cd-223">Ein <see cref="T:System.AsyncCallback" /> Delegat, der Benachrichtigung erhalten sollen, wenn der asynchrone Vorgang abgeschlossen ist.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-223">An <see cref="T:System.AsyncCallback" /> delegate that will receive notification when the asynchronous operation completes.</span></span></param>
        <param name="state"><span data-ttu-id="5d9cd-224">Ein benutzerdefiniertes Objekt, die an dem Rückrufdelegaten übergeben werden.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-224">A user-defined object that will be passed to the callback delegate.</span></span></param>
        <summary>
            <span data-ttu-id="5d9cd-225">Startet einen asynchronen Vorgang zum Erstellen eines Containers, und geben Sie die Ebene des Zugriffs auf die Daten des Containers an.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-225">Begins an asynchronous operation to create a container and specify the level of access to the container's data.</span></span>
            </summary>
        <returns><span data-ttu-id="5d9cd-226">Ein <see cref="T:Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" /> , das auf den asynchronen Vorgang verweist.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-226">An <see cref="T:Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" /> that references the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginCreateIfNotExists">
      <MemberSignature Language="C#" Value="public virtual Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginCreateIfNotExists (AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginCreateIfNotExists(class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlobContainer.BeginCreateIfNotExists(System.AsyncCallback,System.Object)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function BeginCreateIfNotExists (callback As AsyncCallback, state As Object) As ICancellableAsyncResult" />
      <MemberSignature Language="F#" Value="abstract member BeginCreateIfNotExists : AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult&#xA;override this.BeginCreateIfNotExists : AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" Usage="cloudBlobContainer.BeginCreateIfNotExists (callback, state)" />
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
        <param name="callback"><span data-ttu-id="5d9cd-227">Ein <see cref="T:System.AsyncCallback" /> Delegat, der Benachrichtigung erhalten sollen, wenn der asynchrone Vorgang abgeschlossen ist.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-227">An <see cref="T:System.AsyncCallback" /> delegate that will receive notification when the asynchronous operation completes.</span></span></param>
        <param name="state"><span data-ttu-id="5d9cd-228">Ein benutzerdefiniertes Objekt, die an dem Rückrufdelegaten übergeben werden.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-228">A user-defined object that will be passed to the callback delegate.</span></span></param>
        <summary>
            <span data-ttu-id="5d9cd-229">Beginnt eine asynchrone Anforderung an den Container zu erstellen, wenn sie nicht bereits vorhanden ist.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-229">Begins an asynchronous request to create the container if it does not already exist.</span></span>
            </summary>
        <returns><span data-ttu-id="5d9cd-230">Ein <see cref="T:Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" /> , das auf den asynchronen Vorgang verweist.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-230">An <see cref="T:Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" /> that references the asynchronous operation.</span></span></returns>
        <remarks><span data-ttu-id="5d9cd-231">Diese API erfordert, erstellen oder Schreibberechtigungen.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-231">This API requires Create or Write permissions.</span></span></remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginCreateIfNotExists">
      <MemberSignature Language="C#" Value="public virtual Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginCreateIfNotExists (Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, Microsoft.WindowsAzure.Storage.OperationContext operationContext, AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginCreateIfNotExists(class Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, class Microsoft.WindowsAzure.Storage.OperationContext operationContext, class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlobContainer.BeginCreateIfNotExists(Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext,System.AsyncCallback,System.Object)" />
      <MemberSignature Language="F#" Value="abstract member BeginCreateIfNotExists : Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult&#xA;override this.BeginCreateIfNotExists : Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" Usage="cloudBlobContainer.BeginCreateIfNotExists (options, operationContext, callback, state)" />
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
        <Parameter Name="options" Type="Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
        <Parameter Name="callback" Type="System.AsyncCallback" />
        <Parameter Name="state" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="options"><span data-ttu-id="5d9cd-232">Ein <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" /> -Objekt, das zusätzliche Optionen für die Anforderung angibt.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-232">A <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" /> object that specifies additional options for the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="5d9cd-233">Ein <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> -Objekt, das den Kontext für den aktuellen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-233">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <param name="callback"><span data-ttu-id="5d9cd-234">Ein <see cref="T:System.AsyncCallback" /> Delegat, der Benachrichtigung erhalten sollen, wenn der asynchrone Vorgang abgeschlossen ist.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-234">An <see cref="T:System.AsyncCallback" /> delegate that will receive notification when the asynchronous operation completes.</span></span></param>
        <param name="state"><span data-ttu-id="5d9cd-235">Ein benutzerdefiniertes Objekt, die an dem Rückrufdelegaten übergeben werden.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-235">A user-defined object that will be passed to the callback delegate.</span></span></param>
        <summary>
            <span data-ttu-id="5d9cd-236">Beginnt eine asynchrone Anforderung an den Container zu erstellen, wenn sie nicht bereits vorhanden ist.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-236">Begins an asynchronous request to create the container if it does not already exist.</span></span>
            </summary>
        <returns><span data-ttu-id="5d9cd-237">Ein <see cref="T:Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" /> , das auf den asynchronen Vorgang verweist.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-237">An <see cref="T:Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" /> that references the asynchronous operation.</span></span></returns>
        <remarks><span data-ttu-id="5d9cd-238">Diese API erfordert, erstellen oder Schreibberechtigungen.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-238">This API requires Create or Write permissions.</span></span></remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginCreateIfNotExists">
      <MemberSignature Language="C#" Value="public virtual Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginCreateIfNotExists (Microsoft.WindowsAzure.Storage.Blob.BlobContainerPublicAccessType accessType, Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, Microsoft.WindowsAzure.Storage.OperationContext operationContext, AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginCreateIfNotExists(valuetype Microsoft.WindowsAzure.Storage.Blob.BlobContainerPublicAccessType accessType, class Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, class Microsoft.WindowsAzure.Storage.OperationContext operationContext, class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlobContainer.BeginCreateIfNotExists(Microsoft.WindowsAzure.Storage.Blob.BlobContainerPublicAccessType,Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext,System.AsyncCallback,System.Object)" />
      <MemberSignature Language="F#" Value="abstract member BeginCreateIfNotExists : Microsoft.WindowsAzure.Storage.Blob.BlobContainerPublicAccessType * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult&#xA;override this.BeginCreateIfNotExists : Microsoft.WindowsAzure.Storage.Blob.BlobContainerPublicAccessType * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" Usage="cloudBlobContainer.BeginCreateIfNotExists (accessType, options, operationContext, callback, state)" />
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
        <Parameter Name="accessType" Type="Microsoft.WindowsAzure.Storage.Blob.BlobContainerPublicAccessType" />
        <Parameter Name="options" Type="Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
        <Parameter Name="callback" Type="System.AsyncCallback" />
        <Parameter Name="state" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="accessType"><span data-ttu-id="5d9cd-239">Ein <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobContainerPublicAccessType" /> Objekt, das angibt, ob die Daten im Container öffentlich zugegriffen werden können und die Ebene des Zugriffs.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-239">An <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobContainerPublicAccessType" /> object that specifies whether data in the container may be accessed publicly and the level of access.</span></span></param>
        <param name="options"><span data-ttu-id="5d9cd-240">Ein <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" /> -Objekt, das zusätzliche Optionen für die Anforderung angibt.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-240">A <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" /> object that specifies additional options for the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="5d9cd-241">Ein <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> -Objekt, das den Kontext für den aktuellen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-241">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <param name="callback"><span data-ttu-id="5d9cd-242">Ein <see cref="T:System.AsyncCallback" /> Delegat, der Benachrichtigung erhalten sollen, wenn der asynchrone Vorgang abgeschlossen ist.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-242">An <see cref="T:System.AsyncCallback" /> delegate that will receive notification when the asynchronous operation completes.</span></span></param>
        <param name="state"><span data-ttu-id="5d9cd-243">Ein benutzerdefiniertes Objekt, die an dem Rückrufdelegaten übergeben werden.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-243">A user-defined object that will be passed to the callback delegate.</span></span></param>
        <summary>
            <span data-ttu-id="5d9cd-244">Beginnt eine asynchrone Anforderung an den Container zu erstellen, wenn sie nicht bereits vorhanden ist.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-244">Begins an asynchronous request to create the container if it does not already exist.</span></span>
            </summary>
        <returns><span data-ttu-id="5d9cd-245">Ein <see cref="T:Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" /> , das auf den asynchronen Vorgang verweist.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-245">An <see cref="T:Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" /> that references the asynchronous operation.</span></span></returns>
        <remarks><span data-ttu-id="5d9cd-246">Diese API erfordert, erstellen oder Schreibberechtigungen.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-246">This API requires Create or Write permissions.</span></span></remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginDelete">
      <MemberSignature Language="C#" Value="public virtual Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginDelete (AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginDelete(class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlobContainer.BeginDelete(System.AsyncCallback,System.Object)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function BeginDelete (callback As AsyncCallback, state As Object) As ICancellableAsyncResult" />
      <MemberSignature Language="F#" Value="abstract member BeginDelete : AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult&#xA;override this.BeginDelete : AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" Usage="cloudBlobContainer.BeginDelete (callback, state)" />
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
        <param name="callback"><span data-ttu-id="5d9cd-247">Ein <see cref="T:System.AsyncCallback" /> Delegat, der Benachrichtigung erhalten sollen, wenn der asynchrone Vorgang abgeschlossen ist.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-247">An <see cref="T:System.AsyncCallback" /> delegate that will receive notification when the asynchronous operation completes.</span></span></param>
        <param name="state"><span data-ttu-id="5d9cd-248">Ein benutzerdefiniertes Objekt, die an dem Rückrufdelegaten übergeben werden.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-248">A user-defined object that will be passed to the callback delegate.</span></span></param>
        <summary>
            <span data-ttu-id="5d9cd-249">Startet einen asynchronen Vorgang zum Löschen eines Containers.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-249">Begins an asynchronous operation to delete a container.</span></span>
            </summary>
        <returns><span data-ttu-id="5d9cd-250">Ein <see cref="T:Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" /> , das auf den asynchronen Vorgang verweist.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-250">An <see cref="T:Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" /> that references the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginDelete">
      <MemberSignature Language="C#" Value="public virtual Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginDelete (Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, Microsoft.WindowsAzure.Storage.OperationContext operationContext, AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginDelete(class Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, class Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, class Microsoft.WindowsAzure.Storage.OperationContext operationContext, class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlobContainer.BeginDelete(Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext,System.AsyncCallback,System.Object)" />
      <MemberSignature Language="F#" Value="abstract member BeginDelete : Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult&#xA;override this.BeginDelete : Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" Usage="cloudBlobContainer.BeginDelete (accessCondition, options, operationContext, callback, state)" />
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
        <param name="accessCondition"><span data-ttu-id="5d9cd-251">Ein <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> -Objekt, das die Bedingung, die erfüllt sein müssen, damit die Anforderung darstellt, um den Vorgang fortzusetzen.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-251">An <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> object that represents the condition that must be met in order for the request to proceed.</span></span> <span data-ttu-id="5d9cd-252">Wenn <c>null</c>, keine Bedingung verwendet.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-252">If <c>null</c>, no condition is used.</span></span></param>
        <param name="options"><span data-ttu-id="5d9cd-253">Ein <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" /> -Objekt, das zusätzliche Optionen für die Anforderung angibt.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-253">A <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" /> object that specifies additional options for the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="5d9cd-254">Ein <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> -Objekt, das den Kontext für den aktuellen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-254">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <param name="callback"><span data-ttu-id="5d9cd-255">Ein <see cref="T:System.AsyncCallback" /> Delegat, der Benachrichtigung erhalten sollen, wenn der asynchrone Vorgang abgeschlossen ist.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-255">An <see cref="T:System.AsyncCallback" /> delegate that will receive notification when the asynchronous operation completes.</span></span></param>
        <param name="state"><span data-ttu-id="5d9cd-256">Ein benutzerdefiniertes Objekt, die an dem Rückrufdelegaten übergeben werden.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-256">A user-defined object that will be passed to the callback delegate.</span></span></param>
        <summary>
            <span data-ttu-id="5d9cd-257">Startet einen asynchronen Vorgang zum Löschen eines Containers.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-257">Begins an asynchronous operation to delete a container.</span></span>
            </summary>
        <returns><span data-ttu-id="5d9cd-258">Ein <see cref="T:Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" /> , das auf den asynchronen Vorgang verweist.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-258">An <see cref="T:Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" /> that references the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginDeleteIfExists">
      <MemberSignature Language="C#" Value="public virtual Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginDeleteIfExists (AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginDeleteIfExists(class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlobContainer.BeginDeleteIfExists(System.AsyncCallback,System.Object)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function BeginDeleteIfExists (callback As AsyncCallback, state As Object) As ICancellableAsyncResult" />
      <MemberSignature Language="F#" Value="abstract member BeginDeleteIfExists : AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult&#xA;override this.BeginDeleteIfExists : AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" Usage="cloudBlobContainer.BeginDeleteIfExists (callback, state)" />
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
        <param name="callback"><span data-ttu-id="5d9cd-259">Ein <see cref="T:System.AsyncCallback" /> Delegat, der Benachrichtigung erhalten sollen, wenn der asynchrone Vorgang abgeschlossen ist.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-259">An <see cref="T:System.AsyncCallback" /> delegate that will receive notification when the asynchronous operation completes.</span></span></param>
        <param name="state"><span data-ttu-id="5d9cd-260">Ein benutzerdefiniertes Objekt, die an dem Rückrufdelegaten übergeben werden.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-260">A user-defined object that will be passed to the callback delegate.</span></span></param>
        <summary>
            <span data-ttu-id="5d9cd-261">Beginnt eine asynchrone Anforderung zum Löschen des Containers, wenn sie bereits vorhanden ist.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-261">Begins an asynchronous request to delete the container if it already exists.</span></span>
            </summary>
        <returns><span data-ttu-id="5d9cd-262">Ein <see cref="T:Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" /> , das auf den asynchronen Vorgang verweist.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-262">An <see cref="T:Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" /> that references the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginDeleteIfExists">
      <MemberSignature Language="C#" Value="public virtual Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginDeleteIfExists (Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, Microsoft.WindowsAzure.Storage.OperationContext operationContext, AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginDeleteIfExists(class Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, class Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, class Microsoft.WindowsAzure.Storage.OperationContext operationContext, class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlobContainer.BeginDeleteIfExists(Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext,System.AsyncCallback,System.Object)" />
      <MemberSignature Language="F#" Value="abstract member BeginDeleteIfExists : Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult&#xA;override this.BeginDeleteIfExists : Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" Usage="cloudBlobContainer.BeginDeleteIfExists (accessCondition, options, operationContext, callback, state)" />
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
        <param name="accessCondition"><span data-ttu-id="5d9cd-263">Ein <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> -Objekt, das die Bedingung, die erfüllt sein müssen, damit die Anforderung darstellt, um den Vorgang fortzusetzen.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-263">An <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> object that represents the condition that must be met in order for the request to proceed.</span></span> <span data-ttu-id="5d9cd-264">Wenn <c>null</c>, keine Bedingung verwendet.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-264">If <c>null</c>, no condition is used.</span></span></param>
        <param name="options"><span data-ttu-id="5d9cd-265">Ein <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" /> -Objekt, das zusätzliche Optionen für die Anforderung angibt.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-265">A <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" /> object that specifies additional options for the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="5d9cd-266">Ein <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> -Objekt, das den Kontext für den aktuellen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-266">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <param name="callback"><span data-ttu-id="5d9cd-267">Ein <see cref="T:System.AsyncCallback" /> Delegat, der Benachrichtigung erhalten sollen, wenn der asynchrone Vorgang abgeschlossen ist.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-267">An <see cref="T:System.AsyncCallback" /> delegate that will receive notification when the asynchronous operation completes.</span></span></param>
        <param name="state"><span data-ttu-id="5d9cd-268">Ein benutzerdefiniertes Objekt, die an dem Rückrufdelegaten übergeben werden.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-268">A user-defined object that will be passed to the callback delegate.</span></span></param>
        <summary>
            <span data-ttu-id="5d9cd-269">Beginnt eine asynchrone Anforderung zum Löschen des Containers, wenn sie bereits vorhanden ist.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-269">Begins an asynchronous request to delete the container if it already exists.</span></span>
            </summary>
        <returns><span data-ttu-id="5d9cd-270">Ein <see cref="T:Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" /> , das auf den asynchronen Vorgang verweist.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-270">An <see cref="T:Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" /> that references the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginExists">
      <MemberSignature Language="C#" Value="public virtual Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginExists (AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginExists(class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlobContainer.BeginExists(System.AsyncCallback,System.Object)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function BeginExists (callback As AsyncCallback, state As Object) As ICancellableAsyncResult" />
      <MemberSignature Language="F#" Value="abstract member BeginExists : AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult&#xA;override this.BeginExists : AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" Usage="cloudBlobContainer.BeginExists (callback, state)" />
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
        <param name="callback"><span data-ttu-id="5d9cd-271">Ein <see cref="T:System.AsyncCallback" /> Delegat, der Benachrichtigung erhalten sollen, wenn der asynchrone Vorgang abgeschlossen ist.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-271">An <see cref="T:System.AsyncCallback" /> delegate that will receive notification when the asynchronous operation completes.</span></span></param>
        <param name="state"><span data-ttu-id="5d9cd-272">Ein benutzerdefiniertes Objekt, die an dem Rückrufdelegaten übergeben werden.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-272">A user-defined object that will be passed to the callback delegate.</span></span></param>
        <summary>
            <span data-ttu-id="5d9cd-273">Beginnt eine asynchrone Anforderung zu überprüfen, ob der Container vorhanden ist.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-273">Begins an asynchronous request to check whether the container exists.</span></span>
            </summary>
        <returns><span data-ttu-id="5d9cd-274">Ein <see cref="T:Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" /> , das auf den asynchronen Vorgang verweist.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-274">An <see cref="T:Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" /> that references the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginExists">
      <MemberSignature Language="C#" Value="public virtual Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginExists (Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, Microsoft.WindowsAzure.Storage.OperationContext operationContext, AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginExists(class Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, class Microsoft.WindowsAzure.Storage.OperationContext operationContext, class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlobContainer.BeginExists(Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext,System.AsyncCallback,System.Object)" />
      <MemberSignature Language="F#" Value="abstract member BeginExists : Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult&#xA;override this.BeginExists : Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" Usage="cloudBlobContainer.BeginExists (options, operationContext, callback, state)" />
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
        <Parameter Name="options" Type="Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
        <Parameter Name="callback" Type="System.AsyncCallback" />
        <Parameter Name="state" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="options"><span data-ttu-id="5d9cd-275">Ein <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" /> -Objekt, das zusätzliche Optionen für die Anforderung angibt.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-275">A <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" /> object that specifies additional options for the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="5d9cd-276">Ein <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> -Objekt, das den Kontext für den aktuellen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-276">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <param name="callback"><span data-ttu-id="5d9cd-277">Ein <see cref="T:System.AsyncCallback" /> Delegat, der Benachrichtigung erhalten sollen, wenn der asynchrone Vorgang abgeschlossen ist.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-277">An <see cref="T:System.AsyncCallback" /> delegate that will receive notification when the asynchronous operation completes.</span></span></param>
        <param name="state"><span data-ttu-id="5d9cd-278">Ein benutzerdefiniertes Objekt, die an dem Rückrufdelegaten übergeben werden.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-278">A user-defined object that will be passed to the callback delegate.</span></span></param>
        <summary>
            <span data-ttu-id="5d9cd-279">Beginnt eine asynchrone Anforderung zu überprüfen, ob der Container vorhanden ist.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-279">Begins an asynchronous request to check whether the container exists.</span></span>
            </summary>
        <returns><span data-ttu-id="5d9cd-280">Ein <see cref="T:Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" /> , das auf den asynchronen Vorgang verweist.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-280">An <see cref="T:Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" /> that references the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginFetchAttributes">
      <MemberSignature Language="C#" Value="public virtual Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginFetchAttributes (AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginFetchAttributes(class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlobContainer.BeginFetchAttributes(System.AsyncCallback,System.Object)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function BeginFetchAttributes (callback As AsyncCallback, state As Object) As ICancellableAsyncResult" />
      <MemberSignature Language="F#" Value="abstract member BeginFetchAttributes : AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult&#xA;override this.BeginFetchAttributes : AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" Usage="cloudBlobContainer.BeginFetchAttributes (callback, state)" />
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
        <param name="callback"><span data-ttu-id="5d9cd-281">Ein <see cref="T:System.AsyncCallback" /> Delegat, der Benachrichtigung erhalten sollen, wenn der asynchrone Vorgang abgeschlossen ist.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-281">An <see cref="T:System.AsyncCallback" /> delegate that will receive notification when the asynchronous operation completes.</span></span></param>
        <param name="state"><span data-ttu-id="5d9cd-282">Ein benutzerdefiniertes Objekt, die an dem Rückrufdelegaten übergeben werden.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-282">A user-defined object that will be passed to the callback delegate.</span></span></param>
        <summary>
            <span data-ttu-id="5d9cd-283">Startet einen asynchronen Vorgang zum Abrufen der containerattribute.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-283">Begins an asynchronous operation to retrieve the container's attributes.</span></span>
            </summary>
        <returns><span data-ttu-id="5d9cd-284">Ein <see cref="T:Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" /> , das auf den asynchronen Vorgang verweist.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-284">An <see cref="T:Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" /> that references the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginFetchAttributes">
      <MemberSignature Language="C#" Value="public virtual Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginFetchAttributes (Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, Microsoft.WindowsAzure.Storage.OperationContext operationContext, AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginFetchAttributes(class Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, class Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, class Microsoft.WindowsAzure.Storage.OperationContext operationContext, class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlobContainer.BeginFetchAttributes(Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext,System.AsyncCallback,System.Object)" />
      <MemberSignature Language="F#" Value="abstract member BeginFetchAttributes : Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult&#xA;override this.BeginFetchAttributes : Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" Usage="cloudBlobContainer.BeginFetchAttributes (accessCondition, options, operationContext, callback, state)" />
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
        <param name="accessCondition"><span data-ttu-id="5d9cd-285">Ein <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> -Objekt, das die Bedingung, die erfüllt sein müssen, damit die Anforderung darstellt, um den Vorgang fortzusetzen.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-285">An <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> object that represents the condition that must be met in order for the request to proceed.</span></span> <span data-ttu-id="5d9cd-286">Wenn <c>null</c>, keine Bedingung verwendet.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-286">If <c>null</c>, no condition is used.</span></span></param>
        <param name="options"><span data-ttu-id="5d9cd-287">Ein <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" /> -Objekt, das zusätzliche Optionen für die Anforderung angibt.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-287">A <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" /> object that specifies additional options for the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="5d9cd-288">Ein <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> -Objekt, das den Kontext für den aktuellen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-288">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <param name="callback"><span data-ttu-id="5d9cd-289">Ein <see cref="T:System.AsyncCallback" /> Delegat, der Benachrichtigung erhalten sollen, wenn der asynchrone Vorgang abgeschlossen ist.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-289">An <see cref="T:System.AsyncCallback" /> delegate that will receive notification when the asynchronous operation completes.</span></span></param>
        <param name="state"><span data-ttu-id="5d9cd-290">Ein benutzerdefiniertes Objekt, die an dem Rückrufdelegaten übergeben werden.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-290">A user-defined object that will be passed to the callback delegate.</span></span></param>
        <summary>
            <span data-ttu-id="5d9cd-291">Startet einen asynchronen Vorgang zum Abrufen der containerattribute.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-291">Begins an asynchronous operation to retrieve the container's attributes.</span></span>
            </summary>
        <returns><span data-ttu-id="5d9cd-292">Ein <see cref="T:Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" /> , das auf den asynchronen Vorgang verweist.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-292">An <see cref="T:Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" /> that references the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginGetBlobReferenceFromServer">
      <MemberSignature Language="C#" Value="public virtual Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginGetBlobReferenceFromServer (string blobName, AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginGetBlobReferenceFromServer(string blobName, class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlobContainer.BeginGetBlobReferenceFromServer(System.String,System.AsyncCallback,System.Object)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function BeginGetBlobReferenceFromServer (blobName As String, callback As AsyncCallback, state As Object) As ICancellableAsyncResult" />
      <MemberSignature Language="F#" Value="abstract member BeginGetBlobReferenceFromServer : string * AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult&#xA;override this.BeginGetBlobReferenceFromServer : string * AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" Usage="cloudBlobContainer.BeginGetBlobReferenceFromServer (blobName, callback, state)" />
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
        <Parameter Name="blobName" Type="System.String" />
        <Parameter Name="callback" Type="System.AsyncCallback" />
        <Parameter Name="state" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="blobName"><span data-ttu-id="5d9cd-293">Eine Zeichenfolge, die den Namen des BLOBs enthält.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-293">A string containing the name of the blob.</span></span></param>
        <param name="callback"><span data-ttu-id="5d9cd-294">Ein <see cref="T:System.AsyncCallback" /> Delegat, der Benachrichtigung erhalten sollen, wenn der asynchrone Vorgang abgeschlossen ist.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-294">An <see cref="T:System.AsyncCallback" /> delegate that will receive notification when the asynchronous operation completes.</span></span></param>
        <param name="state"><span data-ttu-id="5d9cd-295">Ein benutzerdefiniertes Objekt, die an dem Rückrufdelegaten übergeben werden.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-295">A user-defined object that will be passed to the callback delegate.</span></span></param>
        <summary>
            <span data-ttu-id="5d9cd-296">Startet einen asynchronen Vorgang zum Abrufen von eines Verweises auf ein Blob in diesem Container.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-296">Begins an asynchronous operation to get a reference to a blob in this container.</span></span>
            </summary>
        <returns><span data-ttu-id="5d9cd-297">Ein <see cref="T:Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" /> , das auf den asynchronen Vorgang verweist.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-297">An <see cref="T:Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" /> that references the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginGetBlobReferenceFromServer">
      <MemberSignature Language="C#" Value="public virtual Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginGetBlobReferenceFromServer (string blobName, Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, Microsoft.WindowsAzure.Storage.OperationContext operationContext, AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginGetBlobReferenceFromServer(string blobName, class Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, class Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, class Microsoft.WindowsAzure.Storage.OperationContext operationContext, class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlobContainer.BeginGetBlobReferenceFromServer(System.String,Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext,System.AsyncCallback,System.Object)" />
      <MemberSignature Language="F#" Value="abstract member BeginGetBlobReferenceFromServer : string * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult&#xA;override this.BeginGetBlobReferenceFromServer : string * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" Usage="cloudBlobContainer.BeginGetBlobReferenceFromServer (blobName, accessCondition, options, operationContext, callback, state)" />
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
        <Parameter Name="blobName" Type="System.String" />
        <Parameter Name="accessCondition" Type="Microsoft.WindowsAzure.Storage.AccessCondition" />
        <Parameter Name="options" Type="Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
        <Parameter Name="callback" Type="System.AsyncCallback" />
        <Parameter Name="state" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="blobName"><span data-ttu-id="5d9cd-298">Eine Zeichenfolge, die den Namen des BLOBs enthält.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-298">A string containing the name of the blob.</span></span></param>
        <param name="accessCondition"><span data-ttu-id="5d9cd-299">Ein <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> -Objekt, das die Bedingung, die erfüllt sein müssen, damit die Anforderung darstellt, um den Vorgang fortzusetzen.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-299">An <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> object that represents the condition that must be met in order for the request to proceed.</span></span> <span data-ttu-id="5d9cd-300">Wenn <c>null</c>, keine Bedingung verwendet.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-300">If <c>null</c>, no condition is used.</span></span></param>
        <param name="options"><span data-ttu-id="5d9cd-301">Ein <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" /> -Objekt, das zusätzliche Optionen für die Anforderung angibt.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-301">A <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" /> object that specifies additional options for the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="5d9cd-302">Ein <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> -Objekt, das den Kontext für den aktuellen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-302">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <param name="callback"><span data-ttu-id="5d9cd-303">Ein <see cref="T:System.AsyncCallback" /> Delegat, der Benachrichtigung erhalten sollen, wenn der asynchrone Vorgang abgeschlossen ist.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-303">An <see cref="T:System.AsyncCallback" /> delegate that will receive notification when the asynchronous operation completes.</span></span></param>
        <param name="state"><span data-ttu-id="5d9cd-304">Ein benutzerdefiniertes Objekt, die an dem Rückrufdelegaten übergeben werden.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-304">A user-defined object that will be passed to the callback delegate.</span></span></param>
        <summary>
            <span data-ttu-id="5d9cd-305">Startet einen asynchronen Vorgang zum Abrufen von eines Verweises auf ein Blob in diesem Container.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-305">Begins an asynchronous operation to get a reference to a blob in this container.</span></span>
            </summary>
        <returns><span data-ttu-id="5d9cd-306">Ein <see cref="T:Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" /> , das auf den asynchronen Vorgang verweist.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-306">An <see cref="T:Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" /> that references the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginGetPermissions">
      <MemberSignature Language="C#" Value="public virtual Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginGetPermissions (AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginGetPermissions(class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlobContainer.BeginGetPermissions(System.AsyncCallback,System.Object)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function BeginGetPermissions (callback As AsyncCallback, state As Object) As ICancellableAsyncResult" />
      <MemberSignature Language="F#" Value="abstract member BeginGetPermissions : AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult&#xA;override this.BeginGetPermissions : AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" Usage="cloudBlobContainer.BeginGetPermissions (callback, state)" />
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
        <param name="callback"><span data-ttu-id="5d9cd-307">Ein <see cref="T:System.AsyncCallback" /> Delegat, der Benachrichtigung erhalten sollen, wenn der asynchrone Vorgang abgeschlossen ist.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-307">An <see cref="T:System.AsyncCallback" /> delegate that will receive notification when the asynchronous operation completes.</span></span></param>
        <param name="state"><span data-ttu-id="5d9cd-308">Ein benutzerdefiniertes Objekt, die an dem Rückrufdelegaten übergeben werden.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-308">A user-defined object that will be passed to the callback delegate.</span></span></param>
        <summary>
            <span data-ttu-id="5d9cd-309">Beginnt eine asynchrone Anforderung zum Abrufen der berechtigungseinstellungen für den Container.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-309">Begins an asynchronous request to get the permissions settings for the container.</span></span>
            </summary>
        <returns><span data-ttu-id="5d9cd-310">Ein <see cref="T:Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" /> , das auf den asynchronen Vorgang verweist.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-310">An <see cref="T:Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" /> that references the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginGetPermissions">
      <MemberSignature Language="C#" Value="public virtual Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginGetPermissions (Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, Microsoft.WindowsAzure.Storage.OperationContext operationContext, AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginGetPermissions(class Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, class Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, class Microsoft.WindowsAzure.Storage.OperationContext operationContext, class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlobContainer.BeginGetPermissions(Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext,System.AsyncCallback,System.Object)" />
      <MemberSignature Language="F#" Value="abstract member BeginGetPermissions : Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult&#xA;override this.BeginGetPermissions : Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" Usage="cloudBlobContainer.BeginGetPermissions (accessCondition, options, operationContext, callback, state)" />
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
        <param name="accessCondition"><span data-ttu-id="5d9cd-311">Ein <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> -Objekt, das die Bedingung, die erfüllt sein müssen, damit die Anforderung darstellt, um den Vorgang fortzusetzen.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-311">An <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> object that represents the condition that must be met in order for the request to proceed.</span></span> <span data-ttu-id="5d9cd-312">Wenn <c>null</c>, keine Bedingung verwendet.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-312">If <c>null</c>, no condition is used.</span></span></param>
        <param name="options"><span data-ttu-id="5d9cd-313">Ein <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" /> -Objekt, das zusätzliche Optionen für die Anforderung angibt.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-313">A <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" /> object that specifies additional options for the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="5d9cd-314">Ein <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> -Objekt, das den Kontext für den aktuellen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-314">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <param name="callback"><span data-ttu-id="5d9cd-315">Ein <see cref="T:System.AsyncCallback" /> Delegat, der Benachrichtigung erhalten sollen, wenn der asynchrone Vorgang abgeschlossen ist.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-315">An <see cref="T:System.AsyncCallback" /> delegate that will receive notification when the asynchronous operation completes.</span></span></param>
        <param name="state"><span data-ttu-id="5d9cd-316">Ein benutzerdefiniertes Objekt, die an dem Rückrufdelegaten übergeben werden.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-316">A user-defined object that will be passed to the callback delegate.</span></span></param>
        <summary>
            <span data-ttu-id="5d9cd-317">Beginnt eine asynchrone Anforderung zum Abrufen der berechtigungseinstellungen für den Container.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-317">Begins an asynchronous request to get the permissions settings for the container.</span></span>
            </summary>
        <returns><span data-ttu-id="5d9cd-318">Ein <see cref="T:Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" /> , das auf den asynchronen Vorgang verweist.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-318">An <see cref="T:Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" /> that references the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginListBlobsSegmented">
      <MemberSignature Language="C#" Value="public virtual Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginListBlobsSegmented (Microsoft.WindowsAzure.Storage.Blob.BlobContinuationToken currentToken, AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginListBlobsSegmented(class Microsoft.WindowsAzure.Storage.Blob.BlobContinuationToken currentToken, class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlobContainer.BeginListBlobsSegmented(Microsoft.WindowsAzure.Storage.Blob.BlobContinuationToken,System.AsyncCallback,System.Object)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function BeginListBlobsSegmented (currentToken As BlobContinuationToken, callback As AsyncCallback, state As Object) As ICancellableAsyncResult" />
      <MemberSignature Language="F#" Value="abstract member BeginListBlobsSegmented : Microsoft.WindowsAzure.Storage.Blob.BlobContinuationToken * AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult&#xA;override this.BeginListBlobsSegmented : Microsoft.WindowsAzure.Storage.Blob.BlobContinuationToken * AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" Usage="cloudBlobContainer.BeginListBlobsSegmented (currentToken, callback, state)" />
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
        <Parameter Name="currentToken" Type="Microsoft.WindowsAzure.Storage.Blob.BlobContinuationToken" />
        <Parameter Name="callback" Type="System.AsyncCallback" />
        <Parameter Name="state" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="currentToken"><span data-ttu-id="5d9cd-319">Eine von einem vorherigen Auflistungsvorgang zurückgegebenes Fortsetzungstoken.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-319">A continuation token returned by a previous listing operation.</span></span></param>
        <param name="callback"><span data-ttu-id="5d9cd-320">Ein <see cref="T:System.AsyncCallback" /> Delegat, der Benachrichtigung erhalten sollen, wenn der asynchrone Vorgang abgeschlossen ist.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-320">An <see cref="T:System.AsyncCallback" /> delegate that will receive notification when the asynchronous operation completes.</span></span></param>
        <param name="state"><span data-ttu-id="5d9cd-321">Ein benutzerdefiniertes Objekt, die an dem Rückrufdelegaten übergeben werden.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-321">A user-defined object that will be passed to the callback delegate.</span></span></param>
        <summary>
            <span data-ttu-id="5d9cd-322">Startet einen asynchronen Vorgang zum Zurückgeben eines ergebnissegments, das eine Auflistung von Blob-Elemente im Container enthält.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-322">Begins an asynchronous operation to return a result segment containing a collection of blob items in the container.</span></span>
            </summary>
        <returns><span data-ttu-id="5d9cd-323">Ein <see cref="T:Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" /> , das auf den asynchronen Vorgang verweist.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-323">An <see cref="T:Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" /> that references the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginListBlobsSegmented">
      <MemberSignature Language="C#" Value="public virtual Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginListBlobsSegmented (string prefix, Microsoft.WindowsAzure.Storage.Blob.BlobContinuationToken currentToken, AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginListBlobsSegmented(string prefix, class Microsoft.WindowsAzure.Storage.Blob.BlobContinuationToken currentToken, class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlobContainer.BeginListBlobsSegmented(System.String,Microsoft.WindowsAzure.Storage.Blob.BlobContinuationToken,System.AsyncCallback,System.Object)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function BeginListBlobsSegmented (prefix As String, currentToken As BlobContinuationToken, callback As AsyncCallback, state As Object) As ICancellableAsyncResult" />
      <MemberSignature Language="F#" Value="abstract member BeginListBlobsSegmented : string * Microsoft.WindowsAzure.Storage.Blob.BlobContinuationToken * AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult&#xA;override this.BeginListBlobsSegmented : string * Microsoft.WindowsAzure.Storage.Blob.BlobContinuationToken * AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" Usage="cloudBlobContainer.BeginListBlobsSegmented (prefix, currentToken, callback, state)" />
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
        <Parameter Name="prefix" Type="System.String" />
        <Parameter Name="currentToken" Type="Microsoft.WindowsAzure.Storage.Blob.BlobContinuationToken" />
        <Parameter Name="callback" Type="System.AsyncCallback" />
        <Parameter Name="state" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="prefix"><span data-ttu-id="5d9cd-324">Eine Zeichenfolge mit dem Blob-Namenspräfix.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-324">A string containing the blob name prefix.</span></span></param>
        <param name="currentToken"><span data-ttu-id="5d9cd-325">Eine von einem vorherigen Auflistungsvorgang zurückgegebenes Fortsetzungstoken.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-325">A continuation token returned by a previous listing operation.</span></span></param>
        <param name="callback"><span data-ttu-id="5d9cd-326">Ein <see cref="T:System.AsyncCallback" /> Delegat, der Benachrichtigung erhalten sollen, wenn der asynchrone Vorgang abgeschlossen ist.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-326">An <see cref="T:System.AsyncCallback" /> delegate that will receive notification when the asynchronous operation completes.</span></span></param>
        <param name="state"><span data-ttu-id="5d9cd-327">Ein benutzerdefiniertes Objekt, die an dem Rückrufdelegaten übergeben werden.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-327">A user-defined object that will be passed to the callback delegate.</span></span></param>
        <summary>
            <span data-ttu-id="5d9cd-328">Startet einen asynchronen Vorgang zum Zurückgeben eines ergebnissegments, das eine Auflistung von Blob-Elemente im Container enthält.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-328">Begins an asynchronous operation to return a result segment containing a collection of blob items in the container.</span></span>
            </summary>
        <returns><span data-ttu-id="5d9cd-329">Ein <see cref="T:Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" /> , das auf den asynchronen Vorgang verweist.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-329">An <see cref="T:Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" /> that references the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginListBlobsSegmented">
      <MemberSignature Language="C#" Value="public virtual Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginListBlobsSegmented (string prefix, bool useFlatBlobListing, Microsoft.WindowsAzure.Storage.Blob.BlobListingDetails blobListingDetails, Nullable&lt;int&gt; maxResults, Microsoft.WindowsAzure.Storage.Blob.BlobContinuationToken currentToken, Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, Microsoft.WindowsAzure.Storage.OperationContext operationContext, AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginListBlobsSegmented(string prefix, bool useFlatBlobListing, valuetype Microsoft.WindowsAzure.Storage.Blob.BlobListingDetails blobListingDetails, valuetype System.Nullable`1&lt;int32&gt; maxResults, class Microsoft.WindowsAzure.Storage.Blob.BlobContinuationToken currentToken, class Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, class Microsoft.WindowsAzure.Storage.OperationContext operationContext, class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlobContainer.BeginListBlobsSegmented(System.String,System.Boolean,Microsoft.WindowsAzure.Storage.Blob.BlobListingDetails,System.Nullable{System.Int32},Microsoft.WindowsAzure.Storage.Blob.BlobContinuationToken,Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext,System.AsyncCallback,System.Object)" />
      <MemberSignature Language="F#" Value="abstract member BeginListBlobsSegmented : string * bool * Microsoft.WindowsAzure.Storage.Blob.BlobListingDetails * Nullable&lt;int&gt; * Microsoft.WindowsAzure.Storage.Blob.BlobContinuationToken * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult&#xA;override this.BeginListBlobsSegmented : string * bool * Microsoft.WindowsAzure.Storage.Blob.BlobListingDetails * Nullable&lt;int&gt; * Microsoft.WindowsAzure.Storage.Blob.BlobContinuationToken * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" Usage="cloudBlobContainer.BeginListBlobsSegmented (prefix, useFlatBlobListing, blobListingDetails, maxResults, currentToken, options, operationContext, callback, state)" />
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
        <Parameter Name="prefix" Type="System.String" />
        <Parameter Name="useFlatBlobListing" Type="System.Boolean" />
        <Parameter Name="blobListingDetails" Type="Microsoft.WindowsAzure.Storage.Blob.BlobListingDetails" />
        <Parameter Name="maxResults" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="currentToken" Type="Microsoft.WindowsAzure.Storage.Blob.BlobContinuationToken" />
        <Parameter Name="options" Type="Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
        <Parameter Name="callback" Type="System.AsyncCallback" />
        <Parameter Name="state" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="prefix"><span data-ttu-id="5d9cd-330">Eine Zeichenfolge mit dem Blob-Namenspräfix.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-330">A string containing the blob name prefix.</span></span></param>
        <param name="useFlatBlobListing"><span data-ttu-id="5d9cd-331">Ein boolescher Wert, der angibt, ob Blobs in einer flachen Liste oder hierarchisch nach virtuellem Verzeichnis aufgelistet.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-331">A boolean value that specifies whether to list blobs in a flat listing, or whether to list blobs hierarchically, by virtual directory.</span></span></param>
        <param name="blobListingDetails"><span data-ttu-id="5d9cd-332">Ein <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobListingDetails" /> -Enumeration, die in die Auflistung einzuschließenden Elemente beschreibt.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-332">A <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobListingDetails" /> enumeration describing which items to include in the listing.</span></span></param>
        <param name="maxResults"><span data-ttu-id="5d9cd-333">Ein nicht negativer ganzzahliger Wert, der die maximale Anzahl von gleichzeitig pro Vorgang gilt ein Grenzwert von 5000 zurückzugebenden Ergebnisse angibt.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-333">A non-negative integer value that indicates the maximum number of results to be returned at a time, up to the per-operation limit of 5000.</span></span> <span data-ttu-id="5d9cd-334">Wenn dieser Wert ist <c>null</c>, die maximale zulässige Anzahl von Ergebnissen wird sein (bis 5.000) zurückgegeben.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-334">If this value is <c>null</c>, the maximum possible number of results will be returned, up to 5000.</span></span></param>
        <param name="currentToken"><span data-ttu-id="5d9cd-335">Eine von einem vorherigen Auflistungsvorgang zurückgegebenes Fortsetzungstoken.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-335">A continuation token returned by a previous listing operation.</span></span></param>
        <param name="options"><span data-ttu-id="5d9cd-336">Ein <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" /> -Objekt, das zusätzliche Optionen für die Anforderung angibt.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-336">A <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" /> object that specifies additional options for the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="5d9cd-337">Ein <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> -Objekt, das den Kontext für den aktuellen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-337">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <param name="callback"><span data-ttu-id="5d9cd-338">Ein <see cref="T:System.AsyncCallback" /> Delegat, der Benachrichtigung erhalten sollen, wenn der asynchrone Vorgang abgeschlossen ist.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-338">An <see cref="T:System.AsyncCallback" /> delegate that will receive notification when the asynchronous operation completes.</span></span></param>
        <param name="state"><span data-ttu-id="5d9cd-339">Ein benutzerdefiniertes Objekt, die an dem Rückrufdelegaten übergeben werden.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-339">A user-defined object that will be passed to the callback delegate.</span></span></param>
        <summary>
            <span data-ttu-id="5d9cd-340">Startet einen asynchronen Vorgang zum Zurückgeben eines ergebnissegments, das eine Auflistung von Blob-Elemente im Container enthält.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-340">Begins an asynchronous operation to return a result segment containing a collection of blob items in the container.</span></span>
            </summary>
        <returns><span data-ttu-id="5d9cd-341">Ein <see cref="T:Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" /> , das auf den asynchronen Vorgang verweist.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-341">An <see cref="T:Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" /> that references the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginReleaseLease">
      <MemberSignature Language="C#" Value="public virtual Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginReleaseLease (Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginReleaseLease(class Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlobContainer.BeginReleaseLease(Microsoft.WindowsAzure.Storage.AccessCondition,System.AsyncCallback,System.Object)" />
      <MemberSignature Language="F#" Value="abstract member BeginReleaseLease : Microsoft.WindowsAzure.Storage.AccessCondition * AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult&#xA;override this.BeginReleaseLease : Microsoft.WindowsAzure.Storage.AccessCondition * AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" Usage="cloudBlobContainer.BeginReleaseLease (accessCondition, callback, state)" />
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
        <Parameter Name="callback" Type="System.AsyncCallback" />
        <Parameter Name="state" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="accessCondition"><span data-ttu-id="5d9cd-342">Ein <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> Objekt, das die Bedingung, die erfüllt sein muss, damit die Anforderung zu fortfahren, darstellt, einschließlich einer erforderlichen Lease-ID.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-342">An <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> object that represents the condition that must be met in order for the request to proceed, including a required lease ID.</span></span></param>
        <param name="callback"><span data-ttu-id="5d9cd-343">Eine optionale Rückrufdelegat, der Benachrichtigung erhalten sollen, wenn der asynchrone Vorgang abgeschlossen ist.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-343">An optional callback delegate that will receive notification when the asynchronous operation completes.</span></span></param>
        <param name="state"><span data-ttu-id="5d9cd-344">Ein benutzerdefiniertes Objekt, die an dem Rückrufdelegaten übergeben werden.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-344">A user-defined object that will be passed to the callback delegate.</span></span></param>
        <summary>
            <span data-ttu-id="5d9cd-345">Startet einen asynchronen Vorgang zum Freigeben der Lease für diesen Container.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-345">Begins an asynchronous operation to release the lease on this container.</span></span>
            </summary>
        <returns><span data-ttu-id="5d9cd-346">Ein <see cref="T:Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" /> , das auf den asynchronen Vorgang verweist.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-346">An <see cref="T:Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" /> that references the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginReleaseLease">
      <MemberSignature Language="C#" Value="public virtual Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginReleaseLease (Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, Microsoft.WindowsAzure.Storage.OperationContext operationContext, AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginReleaseLease(class Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, class Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, class Microsoft.WindowsAzure.Storage.OperationContext operationContext, class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlobContainer.BeginReleaseLease(Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext,System.AsyncCallback,System.Object)" />
      <MemberSignature Language="F#" Value="abstract member BeginReleaseLease : Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult&#xA;override this.BeginReleaseLease : Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" Usage="cloudBlobContainer.BeginReleaseLease (accessCondition, options, operationContext, callback, state)" />
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
        <param name="accessCondition"><span data-ttu-id="5d9cd-347">Ein <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> Objekt, das die Bedingung, die erfüllt sein muss, damit die Anforderung zu fortfahren, darstellt, einschließlich einer erforderlichen Lease-ID.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-347">An <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> object that represents the condition that must be met in order for the request to proceed, including a required lease ID.</span></span></param>
        <param name="options"><span data-ttu-id="5d9cd-348">Ein <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" /> -Objekt, das zusätzliche Optionen für die Anforderung angibt.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-348">A <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" /> object that specifies additional options for the request.</span></span> <span data-ttu-id="5d9cd-349">Wenn <c>null</c>, Standardoptionen gelten für die Anforderung.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-349">If <c>null</c>, default options are applied to the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="5d9cd-350">Ein <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> -Objekt, das den Kontext für den aktuellen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-350">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <param name="callback"><span data-ttu-id="5d9cd-351">Eine optionale Rückrufdelegat, der Benachrichtigung erhalten sollen, wenn der asynchrone Vorgang abgeschlossen ist.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-351">An optional callback delegate that will receive notification when the asynchronous operation completes.</span></span></param>
        <param name="state"><span data-ttu-id="5d9cd-352">Ein benutzerdefiniertes Objekt, die an dem Rückrufdelegaten übergeben werden.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-352">A user-defined object that will be passed to the callback delegate.</span></span></param>
        <summary>
            <span data-ttu-id="5d9cd-353">Startet einen asynchronen Vorgang zum Freigeben der Lease für diesen Container.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-353">Begins an asynchronous operation to release the lease on this container.</span></span>
            </summary>
        <returns><span data-ttu-id="5d9cd-354">Ein <see cref="T:Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" /> , das auf den asynchronen Vorgang verweist.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-354">An <see cref="T:Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" /> that references the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginRenewLease">
      <MemberSignature Language="C#" Value="public virtual Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginRenewLease (Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginRenewLease(class Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlobContainer.BeginRenewLease(Microsoft.WindowsAzure.Storage.AccessCondition,System.AsyncCallback,System.Object)" />
      <MemberSignature Language="F#" Value="abstract member BeginRenewLease : Microsoft.WindowsAzure.Storage.AccessCondition * AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult&#xA;override this.BeginRenewLease : Microsoft.WindowsAzure.Storage.AccessCondition * AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" Usage="cloudBlobContainer.BeginRenewLease (accessCondition, callback, state)" />
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
        <Parameter Name="callback" Type="System.AsyncCallback" />
        <Parameter Name="state" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="accessCondition"><span data-ttu-id="5d9cd-355">Ein <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> Objekt, das die Bedingung, die erfüllt sein muss, damit die Anforderung zu fortfahren, darstellt, einschließlich einer erforderlichen Lease-ID.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-355">An <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> object that represents the condition that must be met in order for the request to proceed, including a required lease ID.</span></span></param>
        <param name="callback"><span data-ttu-id="5d9cd-356">Eine optionale Rückrufdelegat, der Benachrichtigung erhalten sollen, wenn der asynchrone Vorgang abgeschlossen ist.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-356">An optional callback delegate that will receive notification when the asynchronous operation completes.</span></span></param>
        <param name="state"><span data-ttu-id="5d9cd-357">Ein benutzerdefiniertes Objekt, die an dem Rückrufdelegaten übergeben werden.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-357">A user-defined object that will be passed to the callback delegate.</span></span></param>
        <summary>
            <span data-ttu-id="5d9cd-358">Startet einen asynchronen Vorgang zum Erneuern einer Lease für diesen Container.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-358">Begins an asynchronous operation to renew a lease on this container.</span></span>
            </summary>
        <returns><span data-ttu-id="5d9cd-359">Ein <see cref="T:Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" /> , das auf den asynchronen Vorgang verweist.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-359">An <see cref="T:Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" /> that references the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginRenewLease">
      <MemberSignature Language="C#" Value="public virtual Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginRenewLease (Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, Microsoft.WindowsAzure.Storage.OperationContext operationContext, AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginRenewLease(class Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, class Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, class Microsoft.WindowsAzure.Storage.OperationContext operationContext, class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlobContainer.BeginRenewLease(Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext,System.AsyncCallback,System.Object)" />
      <MemberSignature Language="F#" Value="abstract member BeginRenewLease : Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult&#xA;override this.BeginRenewLease : Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" Usage="cloudBlobContainer.BeginRenewLease (accessCondition, options, operationContext, callback, state)" />
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
        <param name="accessCondition"><span data-ttu-id="5d9cd-360">Ein <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> Objekt, das die Bedingung, die erfüllt sein muss, damit die Anforderung zu fortfahren, darstellt, einschließlich einer erforderlichen Lease-ID.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-360">An <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> object that represents the condition that must be met in order for the request to proceed, including a required lease ID.</span></span></param>
        <param name="options"><span data-ttu-id="5d9cd-361">Ein <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" /> -Objekt, das zusätzliche Optionen für die Anforderung angibt.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-361">A <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" /> object that specifies additional options for the request.</span></span> <span data-ttu-id="5d9cd-362">Wenn <c>null</c>, Standardoptionen gelten für die Anforderung.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-362">If <c>null</c>, default options are applied to the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="5d9cd-363">Ein <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> -Objekt, das den Kontext für den aktuellen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-363">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <param name="callback"><span data-ttu-id="5d9cd-364">Eine optionale Rückrufdelegat, der Benachrichtigung erhalten sollen, wenn der asynchrone Vorgang abgeschlossen ist.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-364">An optional callback delegate that will receive notification when the asynchronous operation completes.</span></span></param>
        <param name="state"><span data-ttu-id="5d9cd-365">Ein benutzerdefiniertes Objekt, die an dem Rückrufdelegaten übergeben werden.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-365">A user-defined object that will be passed to the callback delegate.</span></span></param>
        <summary>
            <span data-ttu-id="5d9cd-366">Startet einen asynchronen Vorgang zum Erneuern einer Lease für diesen Container.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-366">Begins an asynchronous operation to renew a lease on this container.</span></span>
            </summary>
        <returns><span data-ttu-id="5d9cd-367">Ein <see cref="T:Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" /> , das auf den asynchronen Vorgang verweist.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-367">An <see cref="T:Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" /> that references the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginSetMetadata">
      <MemberSignature Language="C#" Value="public virtual Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginSetMetadata (AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginSetMetadata(class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlobContainer.BeginSetMetadata(System.AsyncCallback,System.Object)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function BeginSetMetadata (callback As AsyncCallback, state As Object) As ICancellableAsyncResult" />
      <MemberSignature Language="F#" Value="abstract member BeginSetMetadata : AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult&#xA;override this.BeginSetMetadata : AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" Usage="cloudBlobContainer.BeginSetMetadata (callback, state)" />
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
        <param name="callback"><span data-ttu-id="5d9cd-368">Ein <see cref="T:System.AsyncCallback" /> Delegat, der Benachrichtigung erhalten sollen, wenn der asynchrone Vorgang abgeschlossen ist.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-368">An <see cref="T:System.AsyncCallback" /> delegate that will receive notification when the asynchronous operation completes.</span></span></param>
        <param name="state"><span data-ttu-id="5d9cd-369">Ein benutzerdefiniertes Objekt, die an dem Rückrufdelegaten übergeben werden.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-369">A user-defined object that will be passed to the callback delegate.</span></span></param>
        <summary>
            <span data-ttu-id="5d9cd-370">Startet einen asynchronen Vorgang zum Festlegen von benutzerdefinierten Metadaten für den Container.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-370">Begins an asynchronous operation to set user-defined metadata on the container.</span></span>
            </summary>
        <returns><span data-ttu-id="5d9cd-371">Ein <see cref="T:Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" /> , das auf den asynchronen Vorgang verweist.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-371">An <see cref="T:Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" /> that references the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginSetMetadata">
      <MemberSignature Language="C#" Value="public virtual Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginSetMetadata (Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, Microsoft.WindowsAzure.Storage.OperationContext operationContext, AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginSetMetadata(class Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, class Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, class Microsoft.WindowsAzure.Storage.OperationContext operationContext, class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlobContainer.BeginSetMetadata(Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext,System.AsyncCallback,System.Object)" />
      <MemberSignature Language="F#" Value="abstract member BeginSetMetadata : Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult&#xA;override this.BeginSetMetadata : Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" Usage="cloudBlobContainer.BeginSetMetadata (accessCondition, options, operationContext, callback, state)" />
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
        <param name="accessCondition"><span data-ttu-id="5d9cd-372">Ein <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> -Objekt, das die Bedingung, die erfüllt sein müssen, damit die Anforderung darstellt, um den Vorgang fortzusetzen.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-372">An <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> object that represents the condition that must be met in order for the request to proceed.</span></span> <span data-ttu-id="5d9cd-373">Wenn <c>null</c>, keine Bedingung verwendet.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-373">If <c>null</c>, no condition is used.</span></span></param>
        <param name="options"><span data-ttu-id="5d9cd-374">Ein <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" /> -Objekt, das zusätzliche Optionen für die Anforderung angibt.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-374">A <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" /> object that specifies additional options for the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="5d9cd-375">Ein <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> -Objekt, das den Kontext für den aktuellen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-375">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <param name="callback"><span data-ttu-id="5d9cd-376">Ein <see cref="T:System.AsyncCallback" /> Delegat, der Benachrichtigung erhalten sollen, wenn der asynchrone Vorgang abgeschlossen ist.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-376">An <see cref="T:System.AsyncCallback" /> delegate that will receive notification when the asynchronous operation completes.</span></span></param>
        <param name="state"><span data-ttu-id="5d9cd-377">Ein benutzerdefiniertes Objekt, die an dem Rückrufdelegaten übergeben werden.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-377">A user-defined object that will be passed to the callback delegate.</span></span></param>
        <summary>
            <span data-ttu-id="5d9cd-378">Startet einen asynchronen Vorgang zum Festlegen von benutzerdefinierten Metadaten für den Container.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-378">Begins an asynchronous operation to set user-defined metadata on the container.</span></span>
            </summary>
        <returns><span data-ttu-id="5d9cd-379">Ein <see cref="T:Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" /> , das auf den asynchronen Vorgang verweist.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-379">An <see cref="T:Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" /> that references the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginSetPermissions">
      <MemberSignature Language="C#" Value="public virtual Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginSetPermissions (Microsoft.WindowsAzure.Storage.Blob.BlobContainerPermissions permissions, AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginSetPermissions(class Microsoft.WindowsAzure.Storage.Blob.BlobContainerPermissions permissions, class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlobContainer.BeginSetPermissions(Microsoft.WindowsAzure.Storage.Blob.BlobContainerPermissions,System.AsyncCallback,System.Object)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function BeginSetPermissions (permissions As BlobContainerPermissions, callback As AsyncCallback, state As Object) As ICancellableAsyncResult" />
      <MemberSignature Language="F#" Value="abstract member BeginSetPermissions : Microsoft.WindowsAzure.Storage.Blob.BlobContainerPermissions * AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult&#xA;override this.BeginSetPermissions : Microsoft.WindowsAzure.Storage.Blob.BlobContainerPermissions * AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" Usage="cloudBlobContainer.BeginSetPermissions (permissions, callback, state)" />
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
        <Parameter Name="permissions" Type="Microsoft.WindowsAzure.Storage.Blob.BlobContainerPermissions" />
        <Parameter Name="callback" Type="System.AsyncCallback" />
        <Parameter Name="state" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="permissions"><span data-ttu-id="5d9cd-380">Die Berechtigungen für den Container angewendet werden soll.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-380">The permissions to apply to the container.</span></span></param>
        <param name="callback"><span data-ttu-id="5d9cd-381">Ein <see cref="T:System.AsyncCallback" /> Delegat, der Benachrichtigung erhalten sollen, wenn der asynchrone Vorgang abgeschlossen ist.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-381">An <see cref="T:System.AsyncCallback" /> delegate that will receive notification when the asynchronous operation completes.</span></span></param>
        <param name="state"><span data-ttu-id="5d9cd-382">Ein benutzerdefiniertes Objekt, die an dem Rückrufdelegaten übergeben werden.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-382">A user-defined object that will be passed to the callback delegate.</span></span></param>
        <summary>
            <span data-ttu-id="5d9cd-383">Beginnt eine asynchrone Anforderung zum Festlegen von Berechtigungen für den Container.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-383">Begins an asynchronous request to set permissions for the container.</span></span>
            </summary>
        <returns><span data-ttu-id="5d9cd-384">Ein <see cref="T:Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" /> , das auf den asynchronen Vorgang verweist.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-384">An <see cref="T:Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" /> that references the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginSetPermissions">
      <MemberSignature Language="C#" Value="public virtual Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginSetPermissions (Microsoft.WindowsAzure.Storage.Blob.BlobContainerPermissions permissions, Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, Microsoft.WindowsAzure.Storage.OperationContext operationContext, AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginSetPermissions(class Microsoft.WindowsAzure.Storage.Blob.BlobContainerPermissions permissions, class Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, class Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, class Microsoft.WindowsAzure.Storage.OperationContext operationContext, class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlobContainer.BeginSetPermissions(Microsoft.WindowsAzure.Storage.Blob.BlobContainerPermissions,Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext,System.AsyncCallback,System.Object)" />
      <MemberSignature Language="F#" Value="abstract member BeginSetPermissions : Microsoft.WindowsAzure.Storage.Blob.BlobContainerPermissions * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult&#xA;override this.BeginSetPermissions : Microsoft.WindowsAzure.Storage.Blob.BlobContainerPermissions * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" Usage="cloudBlobContainer.BeginSetPermissions (permissions, accessCondition, options, operationContext, callback, state)" />
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
        <Parameter Name="permissions" Type="Microsoft.WindowsAzure.Storage.Blob.BlobContainerPermissions" />
        <Parameter Name="accessCondition" Type="Microsoft.WindowsAzure.Storage.AccessCondition" />
        <Parameter Name="options" Type="Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
        <Parameter Name="callback" Type="System.AsyncCallback" />
        <Parameter Name="state" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="permissions"><span data-ttu-id="5d9cd-385">Die Berechtigungen für den Container angewendet werden soll.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-385">The permissions to apply to the container.</span></span></param>
        <param name="accessCondition"><span data-ttu-id="5d9cd-386">Ein <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> -Objekt, das die Bedingung, die erfüllt sein müssen, damit die Anforderung darstellt, um den Vorgang fortzusetzen.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-386">An <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> object that represents the condition that must be met in order for the request to proceed.</span></span> <span data-ttu-id="5d9cd-387">Wenn <c>null</c>, keine Bedingung verwendet.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-387">If <c>null</c>, no condition is used.</span></span></param>
        <param name="options"><span data-ttu-id="5d9cd-388">Ein <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" /> -Objekt, das zusätzliche Optionen für die Anforderung angibt.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-388">A <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" /> object that specifies additional options for the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="5d9cd-389">Ein <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> -Objekt, das den Kontext für den aktuellen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-389">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <param name="callback"><span data-ttu-id="5d9cd-390">Ein <see cref="T:System.AsyncCallback" /> Delegat, der Benachrichtigung erhalten sollen, wenn der asynchrone Vorgang abgeschlossen ist.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-390">An <see cref="T:System.AsyncCallback" /> delegate that will receive notification when the asynchronous operation completes.</span></span></param>
        <param name="state"><span data-ttu-id="5d9cd-391">Ein benutzerdefiniertes Objekt, die an dem Rückrufdelegaten übergeben werden.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-391">A user-defined object that will be passed to the callback delegate.</span></span></param>
        <summary>
            <span data-ttu-id="5d9cd-392">Beginnt eine asynchrone Anforderung zum Festlegen von Berechtigungen für den Container.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-392">Begins an asynchronous request to set permissions for the container.</span></span>
            </summary>
        <returns><span data-ttu-id="5d9cd-393">Ein <see cref="T:Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" /> , das auf den asynchronen Vorgang verweist.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-393">An <see cref="T:Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" /> that references the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BreakLease">
      <MemberSignature Language="C#" Value="public virtual TimeSpan BreakLease (Nullable&lt;TimeSpan&gt; breakPeriod = null, Microsoft.WindowsAzure.Storage.AccessCondition accessCondition = null, Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options = null, Microsoft.WindowsAzure.Storage.OperationContext operationContext = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance valuetype System.TimeSpan BreakLease(valuetype System.Nullable`1&lt;valuetype System.TimeSpan&gt; breakPeriod, class Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, class Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlobContainer.BreakLease(System.Nullable{System.TimeSpan},Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="abstract member BreakLease : Nullable&lt;TimeSpan&gt; * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; TimeSpan&#xA;override this.BreakLease : Nullable&lt;TimeSpan&gt; * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; TimeSpan" Usage="cloudBlobContainer.BreakLease (breakPeriod, accessCondition, options, operationContext)" />
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
        <ReturnType>System.TimeSpan</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="breakPeriod" Type="System.Nullable&lt;System.TimeSpan&gt;" />
        <Parameter Name="accessCondition" Type="Microsoft.WindowsAzure.Storage.AccessCondition" />
        <Parameter Name="options" Type="Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="breakPeriod"><span data-ttu-id="5d9cd-394">Ein <see cref="T:System.TimeSpan" /> , die die Menge an Zeit, die auf den, Leasedauer auf Sekunden abgerundet darstellt.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-394">A <see cref="T:System.TimeSpan" /> representing the amount of time to allow the lease to remain, which will be rounded down to seconds.</span></span> <span data-ttu-id="5d9cd-395">Wenn <c>null</c>, der Unterbrechungszeitraum ist der Rest der aktuellen Lease oder 0 (null) bei unbegrenzten Leases.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-395">If <c>null</c>, the break period is the remainder of the current lease, or zero for infinite leases.</span></span></param>
        <param name="accessCondition"><span data-ttu-id="5d9cd-396">Ein <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> -Objekt, das die Bedingung, die erfüllt sein müssen, damit die Anforderung darstellt, um den Vorgang fortzusetzen.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-396">An <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> object that represents the condition that must be met in order for the request to proceed.</span></span> <span data-ttu-id="5d9cd-397">Wenn <c>null</c>, keine Bedingung verwendet.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-397">If <c>null</c>, no condition is used.</span></span></param>
        <param name="options"><span data-ttu-id="5d9cd-398">Ein <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" /> -Objekt, das zusätzliche Optionen für die Anforderung angibt.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-398">A <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" /> object that specifies additional options for the request.</span></span> <span data-ttu-id="5d9cd-399">Wenn <c>null</c>, Standardoptionen gelten für die Anforderung.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-399">If <c>null</c>, default options are applied to the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="5d9cd-400">Ein <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> -Objekt, das den Kontext für den aktuellen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-400">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <summary>
            <span data-ttu-id="5d9cd-401">Unterbricht die aktuelle Lease für diesen Container.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-401">Breaks the current lease on this container.</span></span>
            </summary>
        <returns><span data-ttu-id="5d9cd-402">Ein <see cref="T:System.TimeSpan" /> , das die Zeitspanne, bevor die Lease, auf dem zweiten endet darstellt.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-402">A <see cref="T:System.TimeSpan" /> representing the amount of time before the lease ends, to the second.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BreakLeaseAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task&lt;TimeSpan&gt; BreakLeaseAsync (Nullable&lt;TimeSpan&gt; breakPeriod);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;valuetype System.TimeSpan&gt; BreakLeaseAsync(valuetype System.Nullable`1&lt;valuetype System.TimeSpan&gt; breakPeriod) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlobContainer.BreakLeaseAsync(System.Nullable{System.TimeSpan})" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function BreakLeaseAsync (breakPeriod As Nullable(Of TimeSpan)) As Task(Of TimeSpan)" />
      <MemberSignature Language="F#" Value="abstract member BreakLeaseAsync : Nullable&lt;TimeSpan&gt; -&gt; System.Threading.Tasks.Task&lt;TimeSpan&gt;&#xA;override this.BreakLeaseAsync : Nullable&lt;TimeSpan&gt; -&gt; System.Threading.Tasks.Task&lt;TimeSpan&gt;" Usage="cloudBlobContainer.BreakLeaseAsync breakPeriod" />
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
        <ReturnType>System.Threading.Tasks.Task&lt;System.TimeSpan&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="breakPeriod" Type="System.Nullable&lt;System.TimeSpan&gt;" />
      </Parameters>
      <Docs>
        <param name="breakPeriod"><span data-ttu-id="5d9cd-403">Ein <see cref="T:System.TimeSpan" /> , die die Menge an Zeit, die auf den, Leasedauer auf Sekunden abgerundet darstellt.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-403">A <see cref="T:System.TimeSpan" /> representing the amount of time to allow the lease to remain, which will be rounded down to seconds.</span></span> <span data-ttu-id="5d9cd-404">Wenn <c>null</c>, der Unterbrechungszeitraum ist der Rest der aktuellen Lease oder 0 (null) bei unbegrenzten Leases.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-404">If <c>null</c>, the break period is the remainder of the current lease, or zero for infinite leases.</span></span></param>
        <summary>
            <span data-ttu-id="5d9cd-405">Initiiert einen asynchronen Vorgang, der die aktuelle Lease für diesen Container zu beeinträchtigen.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-405">Initiates an asynchronous operation that breaks the current lease on this container.</span></span>
            </summary>
        <returns><span data-ttu-id="5d9cd-406">Ein <see cref="T:System.Threading.Tasks.Task`1" />-Objekt, das den asynchronen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-406">A <see cref="T:System.Threading.Tasks.Task`1" /> object that represents the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BreakLeaseAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task&lt;TimeSpan&gt; BreakLeaseAsync (Nullable&lt;TimeSpan&gt; breakPeriod, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;valuetype System.TimeSpan&gt; BreakLeaseAsync(valuetype System.Nullable`1&lt;valuetype System.TimeSpan&gt; breakPeriod, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlobContainer.BreakLeaseAsync(System.Nullable{System.TimeSpan},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member BreakLeaseAsync : Nullable&lt;TimeSpan&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;TimeSpan&gt;&#xA;override this.BreakLeaseAsync : Nullable&lt;TimeSpan&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;TimeSpan&gt;" Usage="cloudBlobContainer.BreakLeaseAsync (breakPeriod, cancellationToken)" />
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
        <ReturnType>System.Threading.Tasks.Task&lt;System.TimeSpan&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="breakPeriod" Type="System.Nullable&lt;System.TimeSpan&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="breakPeriod"><span data-ttu-id="5d9cd-407">Ein <see cref="T:System.TimeSpan" /> , die die Menge an Zeit, die auf den, Leasedauer auf Sekunden abgerundet darstellt.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-407">A <see cref="T:System.TimeSpan" /> representing the amount of time to allow the lease to remain, which will be rounded down to seconds.</span></span> <span data-ttu-id="5d9cd-408">Wenn <c>null</c>, der Unterbrechungszeitraum ist der Rest der aktuellen Lease oder 0 (null) bei unbegrenzten Leases.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-408">If <c>null</c>, the break period is the remainder of the current lease, or zero for infinite leases.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="5d9cd-409">Ein <see cref="T:System.Threading.CancellationToken" />, das beim Warten auf den Abschluss einer Aufgabe überwacht werden soll.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-409">A <see cref="T:System.Threading.CancellationToken" /> to observe while waiting for a task to complete.</span></span></param>
        <summary>
            <span data-ttu-id="5d9cd-410">Initiiert einen asynchronen Vorgang, der die aktuelle Lease für diesen Container zu beeinträchtigen.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-410">Initiates an asynchronous operation that breaks the current lease on this container.</span></span>
            </summary>
        <returns><span data-ttu-id="5d9cd-411">Ein <see cref="T:System.Threading.Tasks.Task`1" />-Objekt, das den asynchronen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-411">A <see cref="T:System.Threading.Tasks.Task`1" /> object that represents the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BreakLeaseAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task&lt;TimeSpan&gt; BreakLeaseAsync (Nullable&lt;TimeSpan&gt; breakPeriod, Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, Microsoft.WindowsAzure.Storage.OperationContext operationContext);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;valuetype System.TimeSpan&gt; BreakLeaseAsync(valuetype System.Nullable`1&lt;valuetype System.TimeSpan&gt; breakPeriod, class Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, class Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlobContainer.BreakLeaseAsync(System.Nullable{System.TimeSpan},Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="abstract member BreakLeaseAsync : Nullable&lt;TimeSpan&gt; * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Threading.Tasks.Task&lt;TimeSpan&gt;&#xA;override this.BreakLeaseAsync : Nullable&lt;TimeSpan&gt; * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Threading.Tasks.Task&lt;TimeSpan&gt;" Usage="cloudBlobContainer.BreakLeaseAsync (breakPeriod, accessCondition, options, operationContext)" />
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
        <ReturnType>System.Threading.Tasks.Task&lt;System.TimeSpan&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="breakPeriod" Type="System.Nullable&lt;System.TimeSpan&gt;" />
        <Parameter Name="accessCondition" Type="Microsoft.WindowsAzure.Storage.AccessCondition" />
        <Parameter Name="options" Type="Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="breakPeriod"><span data-ttu-id="5d9cd-412">Ein <see cref="T:System.TimeSpan" /> , die die Menge an Zeit, die auf den, Leasedauer auf Sekunden abgerundet darstellt.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-412">A <see cref="T:System.TimeSpan" /> representing the amount of time to allow the lease to remain, which will be rounded down to seconds.</span></span> <span data-ttu-id="5d9cd-413">Wenn <c>null</c>, der Unterbrechungszeitraum ist der Rest der aktuellen Lease oder 0 (null) bei unbegrenzten Leases.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-413">If <c>null</c>, the break period is the remainder of the current lease, or zero for infinite leases.</span></span></param>
        <param name="accessCondition"><span data-ttu-id="5d9cd-414">Ein <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> -Objekt, das die Bedingung, die erfüllt sein müssen, damit die Anforderung darstellt, um den Vorgang fortzusetzen.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-414">An <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> object that represents the condition that must be met in order for the request to proceed.</span></span> <span data-ttu-id="5d9cd-415">Wenn <c>null</c>, keine Bedingung verwendet.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-415">If <c>null</c>, no condition is used.</span></span></param>
        <param name="options"><span data-ttu-id="5d9cd-416">Ein <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" /> -Objekt, das zusätzliche Optionen für die Anforderung angibt.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-416">A <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" /> object that specifies additional options for the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="5d9cd-417">Ein <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> -Objekt, das den Kontext für den aktuellen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-417">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <summary>
            <span data-ttu-id="5d9cd-418">Initiiert einen asynchronen Vorgang, der die aktuelle Lease für diesen Container zu beeinträchtigen.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-418">Initiates an asynchronous operation that breaks the current lease on this container.</span></span>
            </summary>
        <returns><span data-ttu-id="5d9cd-419">Ein <see cref="T:System.Threading.Tasks.Task`1" />-Objekt, das den asynchronen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-419">A <see cref="T:System.Threading.Tasks.Task`1" /> object that represents the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BreakLeaseAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task&lt;TimeSpan&gt; BreakLeaseAsync (Nullable&lt;TimeSpan&gt; breakPeriod, Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, Microsoft.WindowsAzure.Storage.OperationContext operationContext, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;valuetype System.TimeSpan&gt; BreakLeaseAsync(valuetype System.Nullable`1&lt;valuetype System.TimeSpan&gt; breakPeriod, class Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, class Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, class Microsoft.WindowsAzure.Storage.OperationContext operationContext, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlobContainer.BreakLeaseAsync(System.Nullable{System.TimeSpan},Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member BreakLeaseAsync : Nullable&lt;TimeSpan&gt; * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;TimeSpan&gt;&#xA;override this.BreakLeaseAsync : Nullable&lt;TimeSpan&gt; * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;TimeSpan&gt;" Usage="cloudBlobContainer.BreakLeaseAsync (breakPeriod, accessCondition, options, operationContext, cancellationToken)" />
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
        <ReturnType>System.Threading.Tasks.Task&lt;System.TimeSpan&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="breakPeriod" Type="System.Nullable&lt;System.TimeSpan&gt;" />
        <Parameter Name="accessCondition" Type="Microsoft.WindowsAzure.Storage.AccessCondition" />
        <Parameter Name="options" Type="Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="breakPeriod"><span data-ttu-id="5d9cd-420">Ein <see cref="T:System.TimeSpan" /> , die die Menge an Zeit, die auf den, Leasedauer auf Sekunden abgerundet darstellt.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-420">A <see cref="T:System.TimeSpan" /> representing the amount of time to allow the lease to remain, which will be rounded down to seconds.</span></span> <span data-ttu-id="5d9cd-421">Wenn <c>null</c>, der Unterbrechungszeitraum ist der Rest der aktuellen Lease oder 0 (null) bei unbegrenzten Leases.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-421">If <c>null</c>, the break period is the remainder of the current lease, or zero for infinite leases.</span></span></param>
        <param name="accessCondition"><span data-ttu-id="5d9cd-422">Ein <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> -Objekt, das die Bedingung, die erfüllt sein müssen, damit die Anforderung darstellt, um den Vorgang fortzusetzen.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-422">An <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> object that represents the condition that must be met in order for the request to proceed.</span></span> <span data-ttu-id="5d9cd-423">Wenn <c>null</c>, keine Bedingung verwendet.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-423">If <c>null</c>, no condition is used.</span></span></param>
        <param name="options"><span data-ttu-id="5d9cd-424">Ein <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" /> -Objekt, das zusätzliche Optionen für die Anforderung angibt.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-424">A <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" /> object that specifies additional options for the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="5d9cd-425">Ein <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> -Objekt, das den Kontext für den aktuellen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-425">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="5d9cd-426">Ein <see cref="T:System.Threading.CancellationToken" />, das beim Warten auf den Abschluss einer Aufgabe überwacht werden soll.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-426">A <see cref="T:System.Threading.CancellationToken" /> to observe while waiting for a task to complete.</span></span></param>
        <summary>
            <span data-ttu-id="5d9cd-427">Initiiert einen asynchronen Vorgang, der die aktuelle Lease für diesen Container zu beeinträchtigen.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-427">Initiates an asynchronous operation that breaks the current lease on this container.</span></span>
            </summary>
        <returns><span data-ttu-id="5d9cd-428">Ein <see cref="T:System.Threading.Tasks.Task`1" />-Objekt, das den asynchronen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-428">A <see cref="T:System.Threading.Tasks.Task`1" /> object that represents the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ChangeLease">
      <MemberSignature Language="C#" Value="public virtual string ChangeLease (string proposedLeaseId, Microsoft.WindowsAzure.Storage.AccessCondition accessCondition = null, Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options = null, Microsoft.WindowsAzure.Storage.OperationContext operationContext = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance string ChangeLease(string proposedLeaseId, class Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, class Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlobContainer.ChangeLease(System.String,Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="abstract member ChangeLease : string * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; string&#xA;override this.ChangeLease : string * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; string" Usage="cloudBlobContainer.ChangeLease (proposedLeaseId, accessCondition, options, operationContext)" />
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
        <Parameter Name="proposedLeaseId" Type="System.String" />
        <Parameter Name="accessCondition" Type="Microsoft.WindowsAzure.Storage.AccessCondition" />
        <Parameter Name="options" Type="Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="proposedLeaseId"><span data-ttu-id="5d9cd-429">Eine Zeichenfolge, die die vorgeschlagene Lease-ID für die neue Leasedauer darstellt.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-429">A string representing the proposed lease ID for the new lease.</span></span> <span data-ttu-id="5d9cd-430">Dies darf nicht null sein.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-430">This cannot be null.</span></span></param>
        <param name="accessCondition"><span data-ttu-id="5d9cd-431">Ein <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> Objekt, das die Bedingung, die erfüllt sein muss, damit die Anforderung zu fortfahren, darstellt, einschließlich einer erforderlichen Lease-ID.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-431">An <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> object that represents the condition that must be met in order for the request to proceed, including a required lease ID.</span></span></param>
        <param name="options"><span data-ttu-id="5d9cd-432">Ein <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" /> -Objekt, das zusätzliche Optionen für die Anforderung angibt.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-432">A <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" /> object that specifies additional options for the request.</span></span> <span data-ttu-id="5d9cd-433">Wenn <c>null</c>, Standardoptionen gelten für die Anforderung.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-433">If <c>null</c>, default options are applied to the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="5d9cd-434">Ein <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> -Objekt, das den Kontext für den aktuellen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-434">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <summary>
            <span data-ttu-id="5d9cd-435">Ändert die Lease-ID für diesen Container.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-435">Changes the lease ID on this container.</span></span>
            </summary>
        <returns><span data-ttu-id="5d9cd-436">Die neue Lease-ID.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-436">The new lease ID.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ChangeLeaseAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task&lt;string&gt; ChangeLeaseAsync (string proposedLeaseId, Microsoft.WindowsAzure.Storage.AccessCondition accessCondition);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;string&gt; ChangeLeaseAsync(string proposedLeaseId, class Microsoft.WindowsAzure.Storage.AccessCondition accessCondition) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlobContainer.ChangeLeaseAsync(System.String,Microsoft.WindowsAzure.Storage.AccessCondition)" />
      <MemberSignature Language="F#" Value="abstract member ChangeLeaseAsync : string * Microsoft.WindowsAzure.Storage.AccessCondition -&gt; System.Threading.Tasks.Task&lt;string&gt;&#xA;override this.ChangeLeaseAsync : string * Microsoft.WindowsAzure.Storage.AccessCondition -&gt; System.Threading.Tasks.Task&lt;string&gt;" Usage="cloudBlobContainer.ChangeLeaseAsync (proposedLeaseId, accessCondition)" />
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
        <Parameter Name="proposedLeaseId" Type="System.String" />
        <Parameter Name="accessCondition" Type="Microsoft.WindowsAzure.Storage.AccessCondition" />
      </Parameters>
      <Docs>
        <param name="proposedLeaseId"><span data-ttu-id="5d9cd-437">Eine Zeichenfolge, die die vorgeschlagene Lease-ID für die neue Leasedauer darstellt.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-437">A string representing the proposed lease ID for the new lease.</span></span> <span data-ttu-id="5d9cd-438">Dies darf nicht null sein.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-438">This cannot be null.</span></span></param>
        <param name="accessCondition"><span data-ttu-id="5d9cd-439">Ein <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> Objekt, das die Bedingung, die erfüllt sein muss, damit die Anforderung zu fortfahren, darstellt, einschließlich einer erforderlichen Lease-ID.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-439">An <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> object that represents the condition that must be met in order for the request to proceed, including a required lease ID.</span></span></param>
        <summary>
            <span data-ttu-id="5d9cd-440">Initiiert einen asynchronen Vorgang, der die Lease-ID für diesen Container zu ändern.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-440">Initiates an asynchronous operation that changes the lease ID on this container.</span></span>
            </summary>
        <returns><span data-ttu-id="5d9cd-441">Ein <see cref="T:System.Threading.Tasks.Task`1" />-Objekt, das den asynchronen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-441">A <see cref="T:System.Threading.Tasks.Task`1" /> object that represents the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ChangeLeaseAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task&lt;string&gt; ChangeLeaseAsync (string proposedLeaseId, Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;string&gt; ChangeLeaseAsync(string proposedLeaseId, class Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlobContainer.ChangeLeaseAsync(System.String,Microsoft.WindowsAzure.Storage.AccessCondition,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ChangeLeaseAsync : string * Microsoft.WindowsAzure.Storage.AccessCondition * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;string&gt;&#xA;override this.ChangeLeaseAsync : string * Microsoft.WindowsAzure.Storage.AccessCondition * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;string&gt;" Usage="cloudBlobContainer.ChangeLeaseAsync (proposedLeaseId, accessCondition, cancellationToken)" />
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
        <Parameter Name="proposedLeaseId" Type="System.String" />
        <Parameter Name="accessCondition" Type="Microsoft.WindowsAzure.Storage.AccessCondition" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="proposedLeaseId"><span data-ttu-id="5d9cd-442">Eine Zeichenfolge, die die vorgeschlagene Lease-ID für die neue Leasedauer darstellt.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-442">A string representing the proposed lease ID for the new lease.</span></span> <span data-ttu-id="5d9cd-443">Dies darf nicht null sein.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-443">This cannot be null.</span></span></param>
        <param name="accessCondition"><span data-ttu-id="5d9cd-444">Ein <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> Objekt, das die Bedingung, die erfüllt sein muss, damit die Anforderung zu fortfahren, darstellt, einschließlich einer erforderlichen Lease-ID.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-444">An <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> object that represents the condition that must be met in order for the request to proceed, including a required lease ID.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="5d9cd-445">Ein <see cref="T:System.Threading.CancellationToken" />, das beim Warten auf den Abschluss einer Aufgabe überwacht werden soll.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-445">A <see cref="T:System.Threading.CancellationToken" /> to observe while waiting for a task to complete.</span></span></param>
        <summary>
            <span data-ttu-id="5d9cd-446">Initiiert einen asynchronen Vorgang, der die Lease-ID für diesen Container zu ändern.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-446">Initiates an asynchronous operation that changes the lease ID on this container.</span></span>
            </summary>
        <returns><span data-ttu-id="5d9cd-447">Ein <see cref="T:System.Threading.Tasks.Task`1" />-Objekt, das den asynchronen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-447">A <see cref="T:System.Threading.Tasks.Task`1" /> object that represents the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ChangeLeaseAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task&lt;string&gt; ChangeLeaseAsync (string proposedLeaseId, Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, Microsoft.WindowsAzure.Storage.OperationContext operationContext);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;string&gt; ChangeLeaseAsync(string proposedLeaseId, class Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, class Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlobContainer.ChangeLeaseAsync(System.String,Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="abstract member ChangeLeaseAsync : string * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Threading.Tasks.Task&lt;string&gt;&#xA;override this.ChangeLeaseAsync : string * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Threading.Tasks.Task&lt;string&gt;" Usage="cloudBlobContainer.ChangeLeaseAsync (proposedLeaseId, accessCondition, options, operationContext)" />
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
        <Parameter Name="proposedLeaseId" Type="System.String" />
        <Parameter Name="accessCondition" Type="Microsoft.WindowsAzure.Storage.AccessCondition" />
        <Parameter Name="options" Type="Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="proposedLeaseId"><span data-ttu-id="5d9cd-448">Eine Zeichenfolge, die die vorgeschlagene Lease-ID für die neue Leasedauer darstellt.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-448">A string representing the proposed lease ID for the new lease.</span></span> <span data-ttu-id="5d9cd-449">Dies darf nicht null sein.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-449">This cannot be null.</span></span></param>
        <param name="accessCondition"><span data-ttu-id="5d9cd-450">Ein <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> Objekt, das die Bedingung, die erfüllt sein muss, damit die Anforderung zu fortfahren, darstellt, einschließlich einer erforderlichen Lease-ID.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-450">An <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> object that represents the condition that must be met in order for the request to proceed, including a required lease ID.</span></span></param>
        <param name="options"><span data-ttu-id="5d9cd-451">Ein <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" /> -Objekt, das zusätzliche Optionen für die Anforderung angibt.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-451">A <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" /> object that specifies additional options for the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="5d9cd-452">Ein <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> -Objekt, das den Kontext für den aktuellen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-452">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <summary>
            <span data-ttu-id="5d9cd-453">Initiiert einen asynchronen Vorgang, der die Lease-ID für diesen Container zu ändern.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-453">Initiates an asynchronous operation that changes the lease ID on this container.</span></span>
            </summary>
        <returns><span data-ttu-id="5d9cd-454">Ein <see cref="T:System.Threading.Tasks.Task`1" />-Objekt, das den asynchronen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-454">A <see cref="T:System.Threading.Tasks.Task`1" /> object that represents the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ChangeLeaseAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task&lt;string&gt; ChangeLeaseAsync (string proposedLeaseId, Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, Microsoft.WindowsAzure.Storage.OperationContext operationContext, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;string&gt; ChangeLeaseAsync(string proposedLeaseId, class Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, class Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, class Microsoft.WindowsAzure.Storage.OperationContext operationContext, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlobContainer.ChangeLeaseAsync(System.String,Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ChangeLeaseAsync : string * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;string&gt;&#xA;override this.ChangeLeaseAsync : string * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;string&gt;" Usage="cloudBlobContainer.ChangeLeaseAsync (proposedLeaseId, accessCondition, options, operationContext, cancellationToken)" />
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
        <Parameter Name="proposedLeaseId" Type="System.String" />
        <Parameter Name="accessCondition" Type="Microsoft.WindowsAzure.Storage.AccessCondition" />
        <Parameter Name="options" Type="Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="proposedLeaseId"><span data-ttu-id="5d9cd-455">Eine Zeichenfolge, die die vorgeschlagene Lease-ID für die neue Leasedauer darstellt.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-455">A string representing the proposed lease ID for the new lease.</span></span> <span data-ttu-id="5d9cd-456">Dies darf nicht null sein.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-456">This cannot be null.</span></span></param>
        <param name="accessCondition"><span data-ttu-id="5d9cd-457">Ein <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> Objekt, das die Bedingung, die erfüllt sein muss, damit die Anforderung zu fortfahren, darstellt, einschließlich einer erforderlichen Lease-ID.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-457">An <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> object that represents the condition that must be met in order for the request to proceed, including a required lease ID.</span></span></param>
        <param name="options"><span data-ttu-id="5d9cd-458">Ein <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" /> -Objekt, das zusätzliche Optionen für die Anforderung angibt.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-458">A <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" /> object that specifies additional options for the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="5d9cd-459">Ein <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> -Objekt, das den Kontext für den aktuellen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-459">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="5d9cd-460">Ein <see cref="T:System.Threading.CancellationToken" />, das beim Warten auf den Abschluss einer Aufgabe überwacht werden soll.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-460">A <see cref="T:System.Threading.CancellationToken" /> to observe while waiting for a task to complete.</span></span></param>
        <summary>
            <span data-ttu-id="5d9cd-461">Initiiert einen asynchronen Vorgang, der die Lease-ID für diesen Container zu ändern.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-461">Initiates an asynchronous operation that changes the lease ID on this container.</span></span>
            </summary>
        <returns><span data-ttu-id="5d9cd-462">Ein <see cref="T:System.Threading.Tasks.Task`1" />-Objekt, das den asynchronen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-462">A <see cref="T:System.Threading.Tasks.Task`1" /> object that represents the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Create">
      <MemberSignature Language="C#" Value="public virtual void Create (Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions requestOptions = null, Microsoft.WindowsAzure.Storage.OperationContext operationContext = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Create(class Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions requestOptions, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlobContainer.Create(Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="abstract member Create : Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; unit&#xA;override this.Create : Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; unit" Usage="cloudBlobContainer.Create (requestOptions, operationContext)" />
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
        <Parameter Name="requestOptions" Type="Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="requestOptions"><span data-ttu-id="5d9cd-463">Ein <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" /> -Objekt, das zusätzliche Optionen für die Anforderung angibt.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-463">A <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" /> object that specifies additional options for the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="5d9cd-464">Ein <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> -Objekt, das den Kontext für den aktuellen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-464">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <summary>
            <span data-ttu-id="5d9cd-465">Erstellt den Container.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-465">Creates the container.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Create">
      <MemberSignature Language="C#" Value="public virtual void Create (Microsoft.WindowsAzure.Storage.Blob.BlobContainerPublicAccessType accessType, Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions requestOptions = null, Microsoft.WindowsAzure.Storage.OperationContext operationContext = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Create(valuetype Microsoft.WindowsAzure.Storage.Blob.BlobContainerPublicAccessType accessType, class Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions requestOptions, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlobContainer.Create(Microsoft.WindowsAzure.Storage.Blob.BlobContainerPublicAccessType,Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="abstract member Create : Microsoft.WindowsAzure.Storage.Blob.BlobContainerPublicAccessType * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; unit&#xA;override this.Create : Microsoft.WindowsAzure.Storage.Blob.BlobContainerPublicAccessType * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; unit" Usage="cloudBlobContainer.Create (accessType, requestOptions, operationContext)" />
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
        <Parameter Name="accessType" Type="Microsoft.WindowsAzure.Storage.Blob.BlobContainerPublicAccessType" />
        <Parameter Name="requestOptions" Type="Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="accessType"><span data-ttu-id="5d9cd-466">Ein <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobContainerPublicAccessType" /> Objekt, das angibt, ob die Daten im Container öffentlich zugegriffen werden können und welche Zugriffsebene zulässig sein.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-466">An <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobContainerPublicAccessType" /> object that specifies whether data in the container may be accessed publicly and what level of access is to be allowed.</span></span></param>
        <param name="requestOptions"><span data-ttu-id="5d9cd-467">Ein <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" /> -Objekt, das zusätzliche Optionen für die Anforderung angibt.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-467">A <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" /> object that specifies additional options for the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="5d9cd-468">Ein <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> -Objekt, das den Kontext für den aktuellen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-468">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <summary>
            <span data-ttu-id="5d9cd-469">Erstellt den Container, und gibt die Ebene des Zugriffs auf die Daten des Containers.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-469">Creates the container and specifies the level of access to the container's data.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task CreateAsync ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task CreateAsync() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlobContainer.CreateAsync" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function CreateAsync () As Task" />
      <MemberSignature Language="F#" Value="abstract member CreateAsync : unit -&gt; System.Threading.Tasks.Task&#xA;override this.CreateAsync : unit -&gt; System.Threading.Tasks.Task" Usage="cloudBlobContainer.CreateAsync " />
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
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="5d9cd-470">Initiiert einen asynchronen Vorgang, der einen Container erstellt.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-470">Initiates an asynchronous operation that creates a container.</span></span>
            </summary>
        <returns><span data-ttu-id="5d9cd-471">Ein <see cref="T:System.Threading.Tasks.Task" />-Objekt, das den asynchronen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-471">A <see cref="T:System.Threading.Tasks.Task" /> object that represents the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task CreateAsync (System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task CreateAsync(valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlobContainer.CreateAsync(System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member CreateAsync : System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&#xA;override this.CreateAsync : System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="cloudBlobContainer.CreateAsync cancellationToken" />
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
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="cancellationToken"><span data-ttu-id="5d9cd-472">Ein <see cref="T:System.Threading.CancellationToken" />, das beim Warten auf den Abschluss einer Aufgabe überwacht werden soll.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-472">A <see cref="T:System.Threading.CancellationToken" /> to observe while waiting for a task to complete.</span></span></param>
        <summary>
            <span data-ttu-id="5d9cd-473">Initiiert einen asynchronen Vorgang, der einen Container erstellt.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-473">Initiates an asynchronous operation that creates a container.</span></span>
            </summary>
        <returns><span data-ttu-id="5d9cd-474">Ein <see cref="T:System.Threading.Tasks.Task" />-Objekt, das den asynchronen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-474">A <see cref="T:System.Threading.Tasks.Task" /> object that represents the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task CreateAsync (Microsoft.WindowsAzure.Storage.Blob.BlobContainerPublicAccessType accessType, Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, Microsoft.WindowsAzure.Storage.OperationContext operationContext);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task CreateAsync(valuetype Microsoft.WindowsAzure.Storage.Blob.BlobContainerPublicAccessType accessType, class Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlobContainer.CreateAsync(Microsoft.WindowsAzure.Storage.Blob.BlobContainerPublicAccessType,Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="abstract member CreateAsync : Microsoft.WindowsAzure.Storage.Blob.BlobContainerPublicAccessType * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Threading.Tasks.Task&#xA;override this.CreateAsync : Microsoft.WindowsAzure.Storage.Blob.BlobContainerPublicAccessType * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Threading.Tasks.Task" Usage="cloudBlobContainer.CreateAsync (accessType, options, operationContext)" />
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
        <Parameter Name="accessType" Type="Microsoft.WindowsAzure.Storage.Blob.BlobContainerPublicAccessType" />
        <Parameter Name="options" Type="Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="accessType"><span data-ttu-id="5d9cd-475">Ein <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobContainerPublicAccessType" /> Objekt, das angibt, ob die Daten im Container öffentlich zugegriffen werden können und welche Zugriffsebene zulässig sein.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-475">An <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobContainerPublicAccessType" /> object that specifies whether data in the container may be accessed publicly and what level of access is to be allowed.</span></span></param>
        <param name="options"><span data-ttu-id="5d9cd-476">Ein <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" /> -Objekt, das zusätzliche Optionen für die Anforderung angibt.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-476">A <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" /> object that specifies additional options for the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="5d9cd-477">Ein <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> -Objekt, das den Kontext für den aktuellen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-477">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <summary>
            <span data-ttu-id="5d9cd-478">Initiiert einen asynchronen Vorgang, der einen Container erstellt.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-478">Initiates an asynchronous operation that creates a container.</span></span>
            </summary>
        <returns><span data-ttu-id="5d9cd-479">Ein <see cref="T:System.Threading.Tasks.Task" />-Objekt, das den asynchronen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-479">A <see cref="T:System.Threading.Tasks.Task" /> object that represents the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task CreateAsync (Microsoft.WindowsAzure.Storage.Blob.BlobContainerPublicAccessType accessType, Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, Microsoft.WindowsAzure.Storage.OperationContext operationContext, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task CreateAsync(valuetype Microsoft.WindowsAzure.Storage.Blob.BlobContainerPublicAccessType accessType, class Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, class Microsoft.WindowsAzure.Storage.OperationContext operationContext, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlobContainer.CreateAsync(Microsoft.WindowsAzure.Storage.Blob.BlobContainerPublicAccessType,Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member CreateAsync : Microsoft.WindowsAzure.Storage.Blob.BlobContainerPublicAccessType * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&#xA;override this.CreateAsync : Microsoft.WindowsAzure.Storage.Blob.BlobContainerPublicAccessType * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="cloudBlobContainer.CreateAsync (accessType, options, operationContext, cancellationToken)" />
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
        <Parameter Name="accessType" Type="Microsoft.WindowsAzure.Storage.Blob.BlobContainerPublicAccessType" />
        <Parameter Name="options" Type="Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="accessType"><span data-ttu-id="5d9cd-480">Ein <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobContainerPublicAccessType" /> Objekt, das angibt, ob die Daten im Container öffentlich zugegriffen werden können und welche Zugriffsebene zulässig sein.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-480">An <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobContainerPublicAccessType" /> object that specifies whether data in the container may be accessed publicly and what level of access is to be allowed.</span></span></param>
        <param name="options"><span data-ttu-id="5d9cd-481">Ein <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" /> -Objekt, das zusätzliche Optionen für die Anforderung angibt.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-481">A <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" /> object that specifies additional options for the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="5d9cd-482">Ein <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> -Objekt, das den Kontext für den aktuellen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-482">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="5d9cd-483">Ein <see cref="T:System.Threading.CancellationToken" />, das beim Warten auf den Abschluss einer Aufgabe überwacht werden soll.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-483">A <see cref="T:System.Threading.CancellationToken" /> to observe while waiting for a task to complete.</span></span></param>
        <summary>
            <span data-ttu-id="5d9cd-484">Initiiert einen asynchronen Vorgang, der ein Container erstellt wird, und gibt die Ebene des Zugriffs auf die Daten des Containers an.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-484">Initiates an asynchronous operation that creates a container and specifies the level of access to the container's data.</span></span>
            </summary>
        <returns><span data-ttu-id="5d9cd-485">Ein <see cref="T:System.Threading.Tasks.Task" />-Objekt, das den asynchronen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-485">A <see cref="T:System.Threading.Tasks.Task" /> object that represents the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateIfNotExists">
      <MemberSignature Language="C#" Value="public virtual bool CreateIfNotExists (Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions requestOptions = null, Microsoft.WindowsAzure.Storage.OperationContext operationContext = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance bool CreateIfNotExists(class Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions requestOptions, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlobContainer.CreateIfNotExists(Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="abstract member CreateIfNotExists : Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; bool&#xA;override this.CreateIfNotExists : Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; bool" Usage="cloudBlobContainer.CreateIfNotExists (requestOptions, operationContext)" />
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
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="requestOptions" Type="Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="requestOptions"><span data-ttu-id="5d9cd-486">Ein <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" /> -Objekt, das zusätzliche Optionen für die Anforderung angibt.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-486">A <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" /> object that specifies additional options for the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="5d9cd-487">Ein <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> -Objekt, das den Kontext für den aktuellen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-487">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <summary>
            <span data-ttu-id="5d9cd-488">Erstellt den Container an, wenn sie nicht bereits vorhanden ist.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-488">Creates the container if it does not already exist.</span></span>
            </summary>
        <returns>
          <span data-ttu-id="5d9cd-489"><c>"true"</c> Wenn der Container noch nicht vorhanden war und erstellt; andernfalls wurde <c>"false"</c>.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-489"><c>true</c> if the container did not already exist and was created; otherwise <c>false</c>.</span></span></returns>
        <remarks><span data-ttu-id="5d9cd-490">Diese API erfordert, erstellen oder Schreibberechtigungen.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-490">This API requires Create or Write permissions.</span></span></remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateIfNotExists">
      <MemberSignature Language="C#" Value="public virtual bool CreateIfNotExists (Microsoft.WindowsAzure.Storage.Blob.BlobContainerPublicAccessType accessType, Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions requestOptions = null, Microsoft.WindowsAzure.Storage.OperationContext operationContext = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance bool CreateIfNotExists(valuetype Microsoft.WindowsAzure.Storage.Blob.BlobContainerPublicAccessType accessType, class Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions requestOptions, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlobContainer.CreateIfNotExists(Microsoft.WindowsAzure.Storage.Blob.BlobContainerPublicAccessType,Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="abstract member CreateIfNotExists : Microsoft.WindowsAzure.Storage.Blob.BlobContainerPublicAccessType * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; bool&#xA;override this.CreateIfNotExists : Microsoft.WindowsAzure.Storage.Blob.BlobContainerPublicAccessType * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; bool" Usage="cloudBlobContainer.CreateIfNotExists (accessType, requestOptions, operationContext)" />
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
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="accessType" Type="Microsoft.WindowsAzure.Storage.Blob.BlobContainerPublicAccessType" />
        <Parameter Name="requestOptions" Type="Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="accessType"><span data-ttu-id="5d9cd-491">Ein <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobContainerPublicAccessType" /> Objekt, das angibt, ob die Daten im Container öffentlich zugegriffen werden können und welche Zugriffsebene zulässig sein.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-491">An <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobContainerPublicAccessType" /> object that specifies whether data in the container may be accessed publicly and what level of access is to be allowed.</span></span></param>
        <param name="requestOptions"><span data-ttu-id="5d9cd-492">Ein <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" /> -Objekt, das zusätzliche Optionen für die Anforderung angibt.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-492">A <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" /> object that specifies additional options for the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="5d9cd-493">Ein <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> -Objekt, das den Kontext für den aktuellen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-493">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <summary>
            <span data-ttu-id="5d9cd-494">Erstellt den Container an, wenn sie nicht bereits vorhanden ist, und gibt an, ob der Container oder dessen Blobs öffentlich zugegriffen werden kann.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-494">Creates the container if it does not already exist and specifies whether the container or its blobs are publicly accessible.</span></span>
            </summary>
        <returns>
          <span data-ttu-id="5d9cd-495"><c>"true"</c> Wenn der Container noch nicht vorhanden war und erstellt; andernfalls wurde <c>"false"</c>.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-495"><c>true</c> if the container did not already exist and was created; otherwise <c>false</c>.</span></span></returns>
        <remarks><span data-ttu-id="5d9cd-496">Diese API erfordert, erstellen oder Schreibberechtigungen.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-496">This API requires Create or Write permissions.</span></span></remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateIfNotExistsAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task&lt;bool&gt; CreateIfNotExistsAsync ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;bool&gt; CreateIfNotExistsAsync() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlobContainer.CreateIfNotExistsAsync" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function CreateIfNotExistsAsync () As Task(Of Boolean)" />
      <MemberSignature Language="F#" Value="abstract member CreateIfNotExistsAsync : unit -&gt; System.Threading.Tasks.Task&lt;bool&gt;&#xA;override this.CreateIfNotExistsAsync : unit -&gt; System.Threading.Tasks.Task&lt;bool&gt;" Usage="cloudBlobContainer.CreateIfNotExistsAsync " />
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
        <ReturnType>System.Threading.Tasks.Task&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="5d9cd-497">Initiiert einen asynchronen Vorgang, der der Container erstellt, wenn sie nicht bereits vorhanden ist.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-497">Initiates an asynchronous operation that creates the container if it does not already exist.</span></span>
            </summary>
        <returns><span data-ttu-id="5d9cd-498">Ein <see cref="T:System.Threading.Tasks.Task`1" />-Objekt, das den asynchronen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-498">A <see cref="T:System.Threading.Tasks.Task`1" /> object that represents the asynchronous operation.</span></span></returns>
        <remarks><span data-ttu-id="5d9cd-499">Diese API erfordert, erstellen oder Schreibberechtigungen.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-499">This API requires Create or Write permissions.</span></span></remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateIfNotExistsAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task&lt;bool&gt; CreateIfNotExistsAsync (System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;bool&gt; CreateIfNotExistsAsync(valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlobContainer.CreateIfNotExistsAsync(System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member CreateIfNotExistsAsync : System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;bool&gt;&#xA;override this.CreateIfNotExistsAsync : System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;bool&gt;" Usage="cloudBlobContainer.CreateIfNotExistsAsync cancellationToken" />
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
        <ReturnType>System.Threading.Tasks.Task&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="cancellationToken"><span data-ttu-id="5d9cd-500">Ein <see cref="T:System.Threading.CancellationToken" />, das beim Warten auf den Abschluss einer Aufgabe überwacht werden soll.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-500">A <see cref="T:System.Threading.CancellationToken" /> to observe while waiting for a task to complete.</span></span></param>
        <summary>
            <span data-ttu-id="5d9cd-501">Initiiert einen asynchronen Vorgang, der der Container erstellt, wenn sie nicht bereits vorhanden ist.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-501">Initiates an asynchronous operation that creates the container if it does not already exist.</span></span>
            </summary>
        <returns><span data-ttu-id="5d9cd-502">Ein <see cref="T:System.Threading.Tasks.Task`1" />-Objekt, das den asynchronen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-502">A <see cref="T:System.Threading.Tasks.Task`1" /> object that represents the asynchronous operation.</span></span></returns>
        <remarks><span data-ttu-id="5d9cd-503">Diese API erfordert, erstellen oder Schreibberechtigungen.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-503">This API requires Create or Write permissions.</span></span></remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateIfNotExistsAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task&lt;bool&gt; CreateIfNotExistsAsync (Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, Microsoft.WindowsAzure.Storage.OperationContext operationContext);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;bool&gt; CreateIfNotExistsAsync(class Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlobContainer.CreateIfNotExistsAsync(Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="abstract member CreateIfNotExistsAsync : Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Threading.Tasks.Task&lt;bool&gt;&#xA;override this.CreateIfNotExistsAsync : Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Threading.Tasks.Task&lt;bool&gt;" Usage="cloudBlobContainer.CreateIfNotExistsAsync (options, operationContext)" />
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
        <ReturnType>System.Threading.Tasks.Task&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="options" Type="Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="options"><span data-ttu-id="5d9cd-504">Ein <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" /> -Objekt, das zusätzliche Optionen für die Anforderung angibt.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-504">A <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" /> object that specifies additional options for the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="5d9cd-505">Ein <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> -Objekt, das den Kontext für den aktuellen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-505">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <summary>
            <span data-ttu-id="5d9cd-506">Initiiert einen asynchronen Vorgang, der der Container erstellt, wenn sie nicht bereits vorhanden ist.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-506">Initiates an asynchronous operation that creates the container if it does not already exist.</span></span>
            </summary>
        <returns><span data-ttu-id="5d9cd-507">Ein <see cref="T:System.Threading.Tasks.Task`1" />-Objekt, das den asynchronen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-507">A <see cref="T:System.Threading.Tasks.Task`1" /> object that represents the asynchronous operation.</span></span></returns>
        <remarks><span data-ttu-id="5d9cd-508">Diese API erfordert, erstellen oder Schreibberechtigungen.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-508">This API requires Create or Write permissions.</span></span></remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateIfNotExistsAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task&lt;bool&gt; CreateIfNotExistsAsync (Microsoft.WindowsAzure.Storage.Blob.BlobContainerPublicAccessType accessType, Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, Microsoft.WindowsAzure.Storage.OperationContext operationContext);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;bool&gt; CreateIfNotExistsAsync(valuetype Microsoft.WindowsAzure.Storage.Blob.BlobContainerPublicAccessType accessType, class Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlobContainer.CreateIfNotExistsAsync(Microsoft.WindowsAzure.Storage.Blob.BlobContainerPublicAccessType,Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="abstract member CreateIfNotExistsAsync : Microsoft.WindowsAzure.Storage.Blob.BlobContainerPublicAccessType * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Threading.Tasks.Task&lt;bool&gt;&#xA;override this.CreateIfNotExistsAsync : Microsoft.WindowsAzure.Storage.Blob.BlobContainerPublicAccessType * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Threading.Tasks.Task&lt;bool&gt;" Usage="cloudBlobContainer.CreateIfNotExistsAsync (accessType, options, operationContext)" />
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
        <ReturnType>System.Threading.Tasks.Task&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="accessType" Type="Microsoft.WindowsAzure.Storage.Blob.BlobContainerPublicAccessType" />
        <Parameter Name="options" Type="Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="accessType"><span data-ttu-id="5d9cd-509">Ein <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobContainerPublicAccessType" /> Objekt, das angibt, ob die Daten im Container öffentlich zugegriffen werden können und die Ebene des Zugriffs.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-509">An <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobContainerPublicAccessType" /> object that specifies whether data in the container may be accessed publicly and the level of access.</span></span></param>
        <param name="options"><span data-ttu-id="5d9cd-510">Ein <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" /> -Objekt, das zusätzliche Optionen für die Anforderung angibt.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-510">A <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" /> object that specifies additional options for the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="5d9cd-511">Ein <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> -Objekt, das den Kontext für den aktuellen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-511">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <summary>
            <span data-ttu-id="5d9cd-512">Initiiert einen asynchronen Vorgang, der der Container erstellt, wenn sie nicht bereits vorhanden ist.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-512">Initiates an asynchronous operation that creates the container if it does not already exist.</span></span>
            </summary>
        <returns><span data-ttu-id="5d9cd-513">Ein <see cref="T:System.Threading.Tasks.Task`1" />-Objekt, das den asynchronen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-513">A <see cref="T:System.Threading.Tasks.Task`1" /> object that represents the asynchronous operation.</span></span></returns>
        <remarks><span data-ttu-id="5d9cd-514">Diese API erfordert, erstellen oder Schreibberechtigungen.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-514">This API requires Create or Write permissions.</span></span></remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateIfNotExistsAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task&lt;bool&gt; CreateIfNotExistsAsync (Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, Microsoft.WindowsAzure.Storage.OperationContext operationContext, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;bool&gt; CreateIfNotExistsAsync(class Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, class Microsoft.WindowsAzure.Storage.OperationContext operationContext, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlobContainer.CreateIfNotExistsAsync(Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member CreateIfNotExistsAsync : Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;bool&gt;&#xA;override this.CreateIfNotExistsAsync : Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;bool&gt;" Usage="cloudBlobContainer.CreateIfNotExistsAsync (options, operationContext, cancellationToken)" />
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
        <ReturnType>System.Threading.Tasks.Task&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="options" Type="Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="options"><span data-ttu-id="5d9cd-515">Ein <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" /> -Objekt, das zusätzliche Optionen für die Anforderung angibt.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-515">A <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" /> object that specifies additional options for the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="5d9cd-516">Ein <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> -Objekt, das den Kontext für den aktuellen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-516">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="5d9cd-517">Ein <see cref="T:System.Threading.CancellationToken" />, das beim Warten auf den Abschluss einer Aufgabe überwacht werden soll.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-517">A <see cref="T:System.Threading.CancellationToken" /> to observe while waiting for a task to complete.</span></span></param>
        <summary>
            <span data-ttu-id="5d9cd-518">Initiiert einen asynchronen Vorgang, der der Container erstellt, wenn sie nicht bereits vorhanden ist.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-518">Initiates an asynchronous operation that creates the container if it does not already exist.</span></span>
            </summary>
        <returns><span data-ttu-id="5d9cd-519">Ein <see cref="T:System.Threading.Tasks.Task`1" />-Objekt, das den asynchronen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-519">A <see cref="T:System.Threading.Tasks.Task`1" /> object that represents the asynchronous operation.</span></span></returns>
        <remarks><span data-ttu-id="5d9cd-520">Diese API erfordert, erstellen oder Schreibberechtigungen.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-520">This API requires Create or Write permissions.</span></span></remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateIfNotExistsAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task&lt;bool&gt; CreateIfNotExistsAsync (Microsoft.WindowsAzure.Storage.Blob.BlobContainerPublicAccessType accessType, Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, Microsoft.WindowsAzure.Storage.OperationContext operationContext, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;bool&gt; CreateIfNotExistsAsync(valuetype Microsoft.WindowsAzure.Storage.Blob.BlobContainerPublicAccessType accessType, class Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, class Microsoft.WindowsAzure.Storage.OperationContext operationContext, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlobContainer.CreateIfNotExistsAsync(Microsoft.WindowsAzure.Storage.Blob.BlobContainerPublicAccessType,Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member CreateIfNotExistsAsync : Microsoft.WindowsAzure.Storage.Blob.BlobContainerPublicAccessType * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;bool&gt;&#xA;override this.CreateIfNotExistsAsync : Microsoft.WindowsAzure.Storage.Blob.BlobContainerPublicAccessType * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;bool&gt;" Usage="cloudBlobContainer.CreateIfNotExistsAsync (accessType, options, operationContext, cancellationToken)" />
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
        <ReturnType>System.Threading.Tasks.Task&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="accessType" Type="Microsoft.WindowsAzure.Storage.Blob.BlobContainerPublicAccessType" />
        <Parameter Name="options" Type="Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="accessType"><span data-ttu-id="5d9cd-521">Ein <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobContainerPublicAccessType" /> Objekt, das angibt, ob die Daten im Container öffentlich zugegriffen werden können und die Ebene des Zugriffs.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-521">An <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobContainerPublicAccessType" /> object that specifies whether data in the container may be accessed publicly and the level of access.</span></span></param>
        <param name="options"><span data-ttu-id="5d9cd-522">Ein <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" /> -Objekt, das zusätzliche Optionen für die Anforderung angibt.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-522">A <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" /> object that specifies additional options for the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="5d9cd-523">Ein <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> -Objekt, das den Kontext für den aktuellen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-523">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="5d9cd-524">Ein <see cref="T:System.Threading.CancellationToken" />, das beim Warten auf den Abschluss einer Aufgabe überwacht werden soll.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-524">A <see cref="T:System.Threading.CancellationToken" /> to observe while waiting for a task to complete.</span></span></param>
        <summary>
            <span data-ttu-id="5d9cd-525">Initiiert einen asynchronen Vorgang, der der Container erstellt, wenn sie nicht bereits vorhanden ist.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-525">Initiates an asynchronous operation that creates the container if it does not already exist.</span></span>
            </summary>
        <returns><span data-ttu-id="5d9cd-526">Ein <see cref="T:System.Threading.Tasks.Task`1" />-Objekt, das den asynchronen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-526">A <see cref="T:System.Threading.Tasks.Task`1" /> object that represents the asynchronous operation.</span></span></returns>
        <remarks><span data-ttu-id="5d9cd-527">Diese API erfordert, erstellen oder Schreibberechtigungen.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-527">This API requires Create or Write permissions.</span></span></remarks>
      </Docs>
    </Member>
    <Member MemberName="Delete">
      <MemberSignature Language="C#" Value="public virtual void Delete (Microsoft.WindowsAzure.Storage.AccessCondition accessCondition = null, Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options = null, Microsoft.WindowsAzure.Storage.OperationContext operationContext = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Delete(class Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, class Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlobContainer.Delete(Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="abstract member Delete : Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; unit&#xA;override this.Delete : Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; unit" Usage="cloudBlobContainer.Delete (accessCondition, options, operationContext)" />
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
        <Parameter Name="accessCondition" Type="Microsoft.WindowsAzure.Storage.AccessCondition" />
        <Parameter Name="options" Type="Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="accessCondition"><span data-ttu-id="5d9cd-528">Ein <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> -Objekt, das die Bedingung, die erfüllt sein müssen, damit die Anforderung darstellt, um den Vorgang fortzusetzen.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-528">An <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> object that represents the condition that must be met in order for the request to proceed.</span></span> <span data-ttu-id="5d9cd-529">Wenn <c>null</c>, keine Bedingung verwendet.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-529">If <c>null</c>, no condition is used.</span></span></param>
        <param name="options"><span data-ttu-id="5d9cd-530">Ein <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" /> -Objekt, das zusätzliche Optionen für die Anforderung angibt.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-530">A <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" /> object that specifies additional options for the request.</span></span> <span data-ttu-id="5d9cd-531">Wenn <c>null</c>, Standardoptionen gelten für die Anforderung.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-531">If <c>null</c>, default options are applied to the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="5d9cd-532">Ein <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> -Objekt, das den Kontext für den aktuellen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-532">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <summary>
            <span data-ttu-id="5d9cd-533">Löscht den Container.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-533">Deletes the container.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task DeleteAsync ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task DeleteAsync() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlobContainer.DeleteAsync" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function DeleteAsync () As Task" />
      <MemberSignature Language="F#" Value="abstract member DeleteAsync : unit -&gt; System.Threading.Tasks.Task&#xA;override this.DeleteAsync : unit -&gt; System.Threading.Tasks.Task" Usage="cloudBlobContainer.DeleteAsync " />
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
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="5d9cd-534">Initiiert einen asynchronen Vorgang, mit dem den Container gelöscht wird.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-534">Initiates an asynchronous operation that deletes the container.</span></span>
            </summary>
        <returns><span data-ttu-id="5d9cd-535">Ein <see cref="T:System.Threading.Tasks.Task" />-Objekt, das den asynchronen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-535">A <see cref="T:System.Threading.Tasks.Task" /> object that represents the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task DeleteAsync (System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task DeleteAsync(valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlobContainer.DeleteAsync(System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member DeleteAsync : System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&#xA;override this.DeleteAsync : System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="cloudBlobContainer.DeleteAsync cancellationToken" />
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
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="cancellationToken"><span data-ttu-id="5d9cd-536">Ein <see cref="T:System.Threading.CancellationToken" />, das beim Warten auf den Abschluss einer Aufgabe überwacht werden soll.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-536">A <see cref="T:System.Threading.CancellationToken" /> to observe while waiting for a task to complete.</span></span></param>
        <summary>
            <span data-ttu-id="5d9cd-537">Initiiert einen asynchronen Vorgang, mit dem den Container gelöscht wird.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-537">Initiates an asynchronous operation that deletes the container.</span></span>
            </summary>
        <returns><span data-ttu-id="5d9cd-538">Ein <see cref="T:System.Threading.Tasks.Task" />-Objekt, das den asynchronen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-538">A <see cref="T:System.Threading.Tasks.Task" /> object that represents the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task DeleteAsync (Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, Microsoft.WindowsAzure.Storage.OperationContext operationContext);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task DeleteAsync(class Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, class Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlobContainer.DeleteAsync(Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="abstract member DeleteAsync : Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Threading.Tasks.Task&#xA;override this.DeleteAsync : Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Threading.Tasks.Task" Usage="cloudBlobContainer.DeleteAsync (accessCondition, options, operationContext)" />
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
        <Parameter Name="accessCondition" Type="Microsoft.WindowsAzure.Storage.AccessCondition" />
        <Parameter Name="options" Type="Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="accessCondition"><span data-ttu-id="5d9cd-539">Ein <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> -Objekt, das die Bedingung, die erfüllt sein müssen, damit die Anforderung darstellt, um den Vorgang fortzusetzen.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-539">An <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> object that represents the condition that must be met in order for the request to proceed.</span></span> <span data-ttu-id="5d9cd-540">Wenn <c>null</c>, keine Bedingung verwendet.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-540">If <c>null</c>, no condition is used.</span></span></param>
        <param name="options"><span data-ttu-id="5d9cd-541">Ein <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" /> -Objekt, das zusätzliche Optionen für die Anforderung angibt.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-541">A <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" /> object that specifies additional options for the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="5d9cd-542">Ein <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> -Objekt, das den Kontext für den aktuellen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-542">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <summary>
            <span data-ttu-id="5d9cd-543">Initiiert einen asynchronen Vorgang, mit dem den Container gelöscht wird.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-543">Initiates an asynchronous operation that deletes the container.</span></span>
            </summary>
        <returns><span data-ttu-id="5d9cd-544">Ein <see cref="T:System.Threading.Tasks.Task" />-Objekt, das den asynchronen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-544">A <see cref="T:System.Threading.Tasks.Task" /> object that represents the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task DeleteAsync (Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, Microsoft.WindowsAzure.Storage.OperationContext operationContext, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task DeleteAsync(class Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, class Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, class Microsoft.WindowsAzure.Storage.OperationContext operationContext, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlobContainer.DeleteAsync(Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member DeleteAsync : Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&#xA;override this.DeleteAsync : Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="cloudBlobContainer.DeleteAsync (accessCondition, options, operationContext, cancellationToken)" />
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
        <Parameter Name="accessCondition" Type="Microsoft.WindowsAzure.Storage.AccessCondition" />
        <Parameter Name="options" Type="Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="accessCondition"><span data-ttu-id="5d9cd-545">Ein <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> -Objekt, das die Bedingung, die erfüllt sein müssen, damit die Anforderung darstellt, um den Vorgang fortzusetzen.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-545">An <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> object that represents the condition that must be met in order for the request to proceed.</span></span> <span data-ttu-id="5d9cd-546">Wenn <c>null</c>, keine Bedingung verwendet.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-546">If <c>null</c>, no condition is used.</span></span></param>
        <param name="options"><span data-ttu-id="5d9cd-547">Ein <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" /> -Objekt, das zusätzliche Optionen für die Anforderung angibt.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-547">A <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" /> object that specifies additional options for the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="5d9cd-548">Ein <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> -Objekt, das den Kontext für den aktuellen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-548">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="5d9cd-549">Ein <see cref="T:System.Threading.CancellationToken" />, das beim Warten auf den Abschluss einer Aufgabe überwacht werden soll.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-549">A <see cref="T:System.Threading.CancellationToken" /> to observe while waiting for a task to complete.</span></span></param>
        <summary>
            <span data-ttu-id="5d9cd-550">Initiiert einen asynchronen Vorgang, mit dem den Container gelöscht wird.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-550">Initiates an asynchronous operation that deletes the container.</span></span>
            </summary>
        <returns><span data-ttu-id="5d9cd-551">Ein <see cref="T:System.Threading.Tasks.Task" />-Objekt, das den asynchronen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-551">A <see cref="T:System.Threading.Tasks.Task" /> object that represents the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteIfExists">
      <MemberSignature Language="C#" Value="public virtual bool DeleteIfExists (Microsoft.WindowsAzure.Storage.AccessCondition accessCondition = null, Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options = null, Microsoft.WindowsAzure.Storage.OperationContext operationContext = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance bool DeleteIfExists(class Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, class Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlobContainer.DeleteIfExists(Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="abstract member DeleteIfExists : Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; bool&#xA;override this.DeleteIfExists : Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; bool" Usage="cloudBlobContainer.DeleteIfExists (accessCondition, options, operationContext)" />
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
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="accessCondition" Type="Microsoft.WindowsAzure.Storage.AccessCondition" />
        <Parameter Name="options" Type="Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="accessCondition"><span data-ttu-id="5d9cd-552">Ein <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> -Objekt, das die Bedingung, die erfüllt sein müssen, damit die Anforderung darstellt, um den Vorgang fortzusetzen.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-552">An <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> object that represents the condition that must be met in order for the request to proceed.</span></span> <span data-ttu-id="5d9cd-553">Wenn <c>null</c>, keine Bedingung verwendet.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-553">If <c>null</c>, no condition is used.</span></span></param>
        <param name="options"><span data-ttu-id="5d9cd-554">Ein <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" /> -Objekt, das zusätzliche Optionen für die Anforderung angibt.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-554">A <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" /> object that specifies additional options for the request.</span></span> <span data-ttu-id="5d9cd-555">Wenn <c>null</c>, Standardoptionen gelten für die Anforderung.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-555">If <c>null</c>, default options are applied to the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="5d9cd-556">Ein <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> -Objekt, das den Kontext für den aktuellen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-556">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <summary>
            <span data-ttu-id="5d9cd-557">Löscht den Container an, wenn sie bereits vorhanden ist.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-557">Deletes the container if it already exists.</span></span>
            </summary>
        <returns>
          <span data-ttu-id="5d9cd-558"><c>"true"</c> Wenn der Container noch nicht vorhanden war und erstellt; andernfalls wurde <c>"false"</c>.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-558"><c>true</c> if the container did not already exist and was created; otherwise <c>false</c>.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteIfExistsAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task&lt;bool&gt; DeleteIfExistsAsync ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;bool&gt; DeleteIfExistsAsync() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlobContainer.DeleteIfExistsAsync" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function DeleteIfExistsAsync () As Task(Of Boolean)" />
      <MemberSignature Language="F#" Value="abstract member DeleteIfExistsAsync : unit -&gt; System.Threading.Tasks.Task&lt;bool&gt;&#xA;override this.DeleteIfExistsAsync : unit -&gt; System.Threading.Tasks.Task&lt;bool&gt;" Usage="cloudBlobContainer.DeleteIfExistsAsync " />
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
        <ReturnType>System.Threading.Tasks.Task&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="5d9cd-559">Initiiert einen asynchronen Vorgang, der den Container zu löschen, wenn sie bereits vorhanden ist.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-559">Initiates an asynchronous operation that deletes the container if it already exists.</span></span>
            </summary>
        <returns><span data-ttu-id="5d9cd-560">Ein <see cref="T:System.Threading.Tasks.Task`1" />-Objekt, das den asynchronen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-560">A <see cref="T:System.Threading.Tasks.Task`1" /> object that represents the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteIfExistsAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task&lt;bool&gt; DeleteIfExistsAsync (System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;bool&gt; DeleteIfExistsAsync(valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlobContainer.DeleteIfExistsAsync(System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member DeleteIfExistsAsync : System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;bool&gt;&#xA;override this.DeleteIfExistsAsync : System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;bool&gt;" Usage="cloudBlobContainer.DeleteIfExistsAsync cancellationToken" />
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
        <ReturnType>System.Threading.Tasks.Task&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="cancellationToken"><span data-ttu-id="5d9cd-561">Ein <see cref="T:System.Threading.CancellationToken" />, das beim Warten auf den Abschluss einer Aufgabe überwacht werden soll.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-561">A <see cref="T:System.Threading.CancellationToken" /> to observe while waiting for a task to complete.</span></span></param>
        <summary>
            <span data-ttu-id="5d9cd-562">Initiiert einen asynchronen Vorgang, der den Container zu löschen, wenn sie bereits vorhanden ist.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-562">Initiates an asynchronous operation that deletes the container if it already exists.</span></span>
            </summary>
        <returns><span data-ttu-id="5d9cd-563">Ein <see cref="T:System.Threading.Tasks.Task`1" />-Objekt, das den asynchronen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-563">A <see cref="T:System.Threading.Tasks.Task`1" /> object that represents the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteIfExistsAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task&lt;bool&gt; DeleteIfExistsAsync (Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, Microsoft.WindowsAzure.Storage.OperationContext operationContext);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;bool&gt; DeleteIfExistsAsync(class Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, class Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlobContainer.DeleteIfExistsAsync(Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="abstract member DeleteIfExistsAsync : Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Threading.Tasks.Task&lt;bool&gt;&#xA;override this.DeleteIfExistsAsync : Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Threading.Tasks.Task&lt;bool&gt;" Usage="cloudBlobContainer.DeleteIfExistsAsync (accessCondition, options, operationContext)" />
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
        <ReturnType>System.Threading.Tasks.Task&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="accessCondition" Type="Microsoft.WindowsAzure.Storage.AccessCondition" />
        <Parameter Name="options" Type="Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="accessCondition"><span data-ttu-id="5d9cd-564">Ein <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> -Objekt, das die Bedingung, die erfüllt sein müssen, damit die Anforderung darstellt, um den Vorgang fortzusetzen.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-564">An <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> object that represents the condition that must be met in order for the request to proceed.</span></span> <span data-ttu-id="5d9cd-565">Wenn <c>null</c>, keine Bedingung verwendet.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-565">If <c>null</c>, no condition is used.</span></span></param>
        <param name="options"><span data-ttu-id="5d9cd-566">Ein <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" /> -Objekt, das zusätzliche Optionen für die Anforderung angibt.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-566">A <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" /> object that specifies additional options for the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="5d9cd-567">Ein <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> -Objekt, das den Kontext für den aktuellen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-567">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <summary>
            <span data-ttu-id="5d9cd-568">Initiiert einen asynchronen Vorgang, der den Container zu löschen, wenn sie bereits vorhanden ist.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-568">Initiates an asynchronous operation that deletes the container if it already exists.</span></span>
            </summary>
        <returns><span data-ttu-id="5d9cd-569">Ein <see cref="T:System.Threading.Tasks.Task`1" />-Objekt, das den asynchronen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-569">A <see cref="T:System.Threading.Tasks.Task`1" /> object that represents the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteIfExistsAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task&lt;bool&gt; DeleteIfExistsAsync (Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, Microsoft.WindowsAzure.Storage.OperationContext operationContext, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;bool&gt; DeleteIfExistsAsync(class Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, class Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, class Microsoft.WindowsAzure.Storage.OperationContext operationContext, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlobContainer.DeleteIfExistsAsync(Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member DeleteIfExistsAsync : Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;bool&gt;&#xA;override this.DeleteIfExistsAsync : Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;bool&gt;" Usage="cloudBlobContainer.DeleteIfExistsAsync (accessCondition, options, operationContext, cancellationToken)" />
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
        <ReturnType>System.Threading.Tasks.Task&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="accessCondition" Type="Microsoft.WindowsAzure.Storage.AccessCondition" />
        <Parameter Name="options" Type="Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="accessCondition"><span data-ttu-id="5d9cd-570">Ein <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> -Objekt, das die Bedingung, die erfüllt sein müssen, damit die Anforderung darstellt, um den Vorgang fortzusetzen.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-570">An <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> object that represents the condition that must be met in order for the request to proceed.</span></span> <span data-ttu-id="5d9cd-571">Wenn <c>null</c>, keine Bedingung verwendet.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-571">If <c>null</c>, no condition is used.</span></span></param>
        <param name="options"><span data-ttu-id="5d9cd-572">Ein <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" /> -Objekt, das zusätzliche Optionen für die Anforderung angibt.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-572">A <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" /> object that specifies additional options for the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="5d9cd-573">Ein <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> -Objekt, das den Kontext für den aktuellen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-573">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="5d9cd-574">Ein <see cref="T:System.Threading.CancellationToken" />, das beim Warten auf den Abschluss einer Aufgabe überwacht werden soll.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-574">A <see cref="T:System.Threading.CancellationToken" /> to observe while waiting for a task to complete.</span></span></param>
        <summary>
            <span data-ttu-id="5d9cd-575">Initiiert einen asynchronen Vorgang, der den Container zu löschen, wenn sie bereits vorhanden ist.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-575">Initiates an asynchronous operation that deletes the container if it already exists.</span></span>
            </summary>
        <returns><span data-ttu-id="5d9cd-576">Ein <see cref="T:System.Threading.Tasks.Task`1" />-Objekt, das den asynchronen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-576">A <see cref="T:System.Threading.Tasks.Task`1" /> object that represents the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EndAcquireLease">
      <MemberSignature Language="C#" Value="public virtual string EndAcquireLease (IAsyncResult asyncResult);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance string EndAcquireLease(class System.IAsyncResult asyncResult) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlobContainer.EndAcquireLease(System.IAsyncResult)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function EndAcquireLease (asyncResult As IAsyncResult) As String" />
      <MemberSignature Language="F#" Value="abstract member EndAcquireLease : IAsyncResult -&gt; string&#xA;override this.EndAcquireLease : IAsyncResult -&gt; string" Usage="cloudBlobContainer.EndAcquireLease asyncResult" />
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
        <param name="asyncResult"><span data-ttu-id="5d9cd-577">Ein "IAsyncResult", die auf den ausstehenden asynchronen Vorgang verweist.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-577">An IAsyncResult that references the pending asynchronous operation.</span></span></param>
        <summary>
            <span data-ttu-id="5d9cd-578">Beendet einen asynchronen Vorgang zum Abrufen einer Lease für diesen Container.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-578">Ends an asynchronous operation to acquire a lease on this container.</span></span>
            </summary>
        <returns><span data-ttu-id="5d9cd-579">Die ID der erworbenen Lease.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-579">The ID of the acquired lease.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EndBreakLease">
      <MemberSignature Language="C#" Value="public virtual TimeSpan EndBreakLease (IAsyncResult asyncResult);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance valuetype System.TimeSpan EndBreakLease(class System.IAsyncResult asyncResult) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlobContainer.EndBreakLease(System.IAsyncResult)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function EndBreakLease (asyncResult As IAsyncResult) As TimeSpan" />
      <MemberSignature Language="F#" Value="abstract member EndBreakLease : IAsyncResult -&gt; TimeSpan&#xA;override this.EndBreakLease : IAsyncResult -&gt; TimeSpan" Usage="cloudBlobContainer.EndBreakLease asyncResult" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.TimeSpan</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="asyncResult" Type="System.IAsyncResult" />
      </Parameters>
      <Docs>
        <param name="asyncResult"><span data-ttu-id="5d9cd-580">Ein "IAsyncResult", die auf den ausstehenden asynchronen Vorgang verweist.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-580">An IAsyncResult that references the pending asynchronous operation.</span></span></param>
        <summary>
            <span data-ttu-id="5d9cd-581">Beendet einen asynchronen Vorgang zum Unterbrechen der aktuellen Lease für diesen Container.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-581">Ends an asynchronous operation to break the current lease on this container.</span></span>
            </summary>
        <returns><span data-ttu-id="5d9cd-582">Ein <see cref="T:System.TimeSpan" /> , das die Zeitspanne, bevor die Lease, auf dem zweiten endet darstellt.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-582">A <see cref="T:System.TimeSpan" /> representing the amount of time before the lease ends, to the second.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EndChangeLease">
      <MemberSignature Language="C#" Value="public virtual string EndChangeLease (IAsyncResult asyncResult);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance string EndChangeLease(class System.IAsyncResult asyncResult) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlobContainer.EndChangeLease(System.IAsyncResult)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function EndChangeLease (asyncResult As IAsyncResult) As String" />
      <MemberSignature Language="F#" Value="abstract member EndChangeLease : IAsyncResult -&gt; string&#xA;override this.EndChangeLease : IAsyncResult -&gt; string" Usage="cloudBlobContainer.EndChangeLease asyncResult" />
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
        <param name="asyncResult"><span data-ttu-id="5d9cd-583">Ein "IAsyncResult", die auf den ausstehenden asynchronen Vorgang verweist.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-583">An IAsyncResult that references the pending asynchronous operation.</span></span></param>
        <summary>
            <span data-ttu-id="5d9cd-584">Beendet einen asynchronen Vorgang zum Ändern der Lease für diesen Container.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-584">Ends an asynchronous operation to change the lease on this container.</span></span>
            </summary>
        <returns><span data-ttu-id="5d9cd-585">Die neue Lease-ID.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-585">The new lease ID.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EndCreate">
      <MemberSignature Language="C#" Value="public virtual void EndCreate (IAsyncResult asyncResult);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void EndCreate(class System.IAsyncResult asyncResult) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlobContainer.EndCreate(System.IAsyncResult)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub EndCreate (asyncResult As IAsyncResult)" />
      <MemberSignature Language="F#" Value="abstract member EndCreate : IAsyncResult -&gt; unit&#xA;override this.EndCreate : IAsyncResult -&gt; unit" Usage="cloudBlobContainer.EndCreate asyncResult" />
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
        <param name="asyncResult"><span data-ttu-id="5d9cd-586">Eine <see cref="T:System.IAsyncResult" /> , die auf den ausstehenden asynchronen Vorgang verweist.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-586">An <see cref="T:System.IAsyncResult" /> that references the pending asynchronous operation.</span></span></param>
        <summary>
            <span data-ttu-id="5d9cd-587">Beendet einen asynchronen Vorgang zum Erstellen eines Containers.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-587">Ends an asynchronous operation to create a container.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EndCreateIfNotExists">
      <MemberSignature Language="C#" Value="public virtual bool EndCreateIfNotExists (IAsyncResult asyncResult);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance bool EndCreateIfNotExists(class System.IAsyncResult asyncResult) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlobContainer.EndCreateIfNotExists(System.IAsyncResult)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function EndCreateIfNotExists (asyncResult As IAsyncResult) As Boolean" />
      <MemberSignature Language="F#" Value="abstract member EndCreateIfNotExists : IAsyncResult -&gt; bool&#xA;override this.EndCreateIfNotExists : IAsyncResult -&gt; bool" Usage="cloudBlobContainer.EndCreateIfNotExists asyncResult" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="asyncResult" Type="System.IAsyncResult" />
      </Parameters>
      <Docs>
        <param name="asyncResult"><span data-ttu-id="5d9cd-588">Eine <see cref="T:System.IAsyncResult" /> , die auf den ausstehenden asynchronen Vorgang verweist.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-588">An <see cref="T:System.IAsyncResult" /> that references the pending asynchronous operation.</span></span></param>
        <summary>
            <span data-ttu-id="5d9cd-589">Gibt das Ergebnis eine asynchrone Anforderung an den Container zu erstellen, wenn sie nicht bereits vorhanden ist.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-589">Returns the result of an asynchronous request to create the container if it does not already exist.</span></span>
            </summary>
        <returns>
          <span data-ttu-id="5d9cd-590"><c>"true"</c> Wenn der Container noch nicht vorhanden war und erstellt; andernfalls wurde, <c>"false"</c>.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-590"><c>true</c> if the container did not already exist and was created; otherwise, <c>false</c>.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EndDelete">
      <MemberSignature Language="C#" Value="public virtual void EndDelete (IAsyncResult asyncResult);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void EndDelete(class System.IAsyncResult asyncResult) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlobContainer.EndDelete(System.IAsyncResult)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub EndDelete (asyncResult As IAsyncResult)" />
      <MemberSignature Language="F#" Value="abstract member EndDelete : IAsyncResult -&gt; unit&#xA;override this.EndDelete : IAsyncResult -&gt; unit" Usage="cloudBlobContainer.EndDelete asyncResult" />
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
        <param name="asyncResult"><span data-ttu-id="5d9cd-591">Eine <see cref="T:System.IAsyncResult" /> , die auf den ausstehenden asynchronen Vorgang verweist.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-591">An <see cref="T:System.IAsyncResult" /> that references the pending asynchronous operation.</span></span></param>
        <summary>
            <span data-ttu-id="5d9cd-592">Beendet einen asynchronen Vorgang zum Löschen eines Containers.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-592">Ends an asynchronous operation to delete a container.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EndDeleteIfExists">
      <MemberSignature Language="C#" Value="public virtual bool EndDeleteIfExists (IAsyncResult asyncResult);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance bool EndDeleteIfExists(class System.IAsyncResult asyncResult) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlobContainer.EndDeleteIfExists(System.IAsyncResult)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function EndDeleteIfExists (asyncResult As IAsyncResult) As Boolean" />
      <MemberSignature Language="F#" Value="abstract member EndDeleteIfExists : IAsyncResult -&gt; bool&#xA;override this.EndDeleteIfExists : IAsyncResult -&gt; bool" Usage="cloudBlobContainer.EndDeleteIfExists asyncResult" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="asyncResult" Type="System.IAsyncResult" />
      </Parameters>
      <Docs>
        <param name="asyncResult"><span data-ttu-id="5d9cd-593">Eine <see cref="T:System.IAsyncResult" /> , die auf den ausstehenden asynchronen Vorgang verweist.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-593">An <see cref="T:System.IAsyncResult" /> that references the pending asynchronous operation.</span></span></param>
        <summary>
            <span data-ttu-id="5d9cd-594">Gibt das Ergebnis eine asynchrone Anforderung an den Container zu löschen, wenn sie bereits vorhanden ist.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-594">Returns the result of an asynchronous request to delete the container if it already exists.</span></span>
            </summary>
        <returns>
          <span data-ttu-id="5d9cd-595"><c>"true"</c> Wenn der Container noch nicht vorhanden war und erstellt; andernfalls wurde, <c>"false"</c>.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-595"><c>true</c> if the container did not already exist and was created; otherwise, <c>false</c>.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EndExists">
      <MemberSignature Language="C#" Value="public virtual bool EndExists (IAsyncResult asyncResult);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance bool EndExists(class System.IAsyncResult asyncResult) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlobContainer.EndExists(System.IAsyncResult)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function EndExists (asyncResult As IAsyncResult) As Boolean" />
      <MemberSignature Language="F#" Value="abstract member EndExists : IAsyncResult -&gt; bool&#xA;override this.EndExists : IAsyncResult -&gt; bool" Usage="cloudBlobContainer.EndExists asyncResult" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="asyncResult" Type="System.IAsyncResult" />
      </Parameters>
      <Docs>
        <param name="asyncResult"><span data-ttu-id="5d9cd-596">Eine <see cref="T:System.IAsyncResult" /> , die auf den ausstehenden asynchronen Vorgang verweist.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-596">An <see cref="T:System.IAsyncResult" /> that references the pending asynchronous operation.</span></span></param>
        <summary>
            <span data-ttu-id="5d9cd-597">Gibt das asynchrone Ergebnis der Anforderung zu überprüfen, ob der Container vorhanden ist.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-597">Returns the asynchronous result of the request to check whether the container exists.</span></span>
            </summary>
        <returns>
          <span data-ttu-id="5d9cd-598"><c>"true"</c> , wenn der Container vorhanden ist.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-598"><c>true</c> if the container exists.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EndFetchAttributes">
      <MemberSignature Language="C#" Value="public virtual void EndFetchAttributes (IAsyncResult asyncResult);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void EndFetchAttributes(class System.IAsyncResult asyncResult) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlobContainer.EndFetchAttributes(System.IAsyncResult)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub EndFetchAttributes (asyncResult As IAsyncResult)" />
      <MemberSignature Language="F#" Value="abstract member EndFetchAttributes : IAsyncResult -&gt; unit&#xA;override this.EndFetchAttributes : IAsyncResult -&gt; unit" Usage="cloudBlobContainer.EndFetchAttributes asyncResult" />
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
        <param name="asyncResult"><span data-ttu-id="5d9cd-599">Eine <see cref="T:System.IAsyncResult" /> , die auf den ausstehenden asynchronen Vorgang verweist.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-599">An <see cref="T:System.IAsyncResult" /> that references the pending asynchronous operation.</span></span></param>
        <summary>
            <span data-ttu-id="5d9cd-600">Beendet einen asynchronen Vorgang zum Abrufen der containerattribute.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-600">Ends an asynchronous operation to retrieve the container's attributes.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EndGetBlobReferenceFromServer">
      <MemberSignature Language="C#" Value="public virtual Microsoft.WindowsAzure.Storage.Blob.ICloudBlob EndGetBlobReferenceFromServer (IAsyncResult asyncResult);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.WindowsAzure.Storage.Blob.ICloudBlob EndGetBlobReferenceFromServer(class System.IAsyncResult asyncResult) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlobContainer.EndGetBlobReferenceFromServer(System.IAsyncResult)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function EndGetBlobReferenceFromServer (asyncResult As IAsyncResult) As ICloudBlob" />
      <MemberSignature Language="F#" Value="abstract member EndGetBlobReferenceFromServer : IAsyncResult -&gt; Microsoft.WindowsAzure.Storage.Blob.ICloudBlob&#xA;override this.EndGetBlobReferenceFromServer : IAsyncResult -&gt; Microsoft.WindowsAzure.Storage.Blob.ICloudBlob" Usage="cloudBlobContainer.EndGetBlobReferenceFromServer asyncResult" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Storage.Blob.ICloudBlob</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="asyncResult" Type="System.IAsyncResult" />
      </Parameters>
      <Docs>
        <param name="asyncResult"><span data-ttu-id="5d9cd-601">Eine <see cref="T:System.IAsyncResult" /> , die auf den ausstehenden asynchronen Vorgang verweist.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-601">An <see cref="T:System.IAsyncResult" /> that references the pending asynchronous operation.</span></span></param>
        <summary>
            <span data-ttu-id="5d9cd-602">Beendet einen asynchronen Vorgang zum Abrufen von eines Verweises auf ein Blob in diesem Container.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-602">Ends an asynchronous operation to get a reference to a blob in this container.</span></span>
            </summary>
        <returns><span data-ttu-id="5d9cd-603">Ein Verweis auf das Blob.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-603">A reference to the blob.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EndGetPermissions">
      <MemberSignature Language="C#" Value="public virtual Microsoft.WindowsAzure.Storage.Blob.BlobContainerPermissions EndGetPermissions (IAsyncResult asyncResult);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.WindowsAzure.Storage.Blob.BlobContainerPermissions EndGetPermissions(class System.IAsyncResult asyncResult) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlobContainer.EndGetPermissions(System.IAsyncResult)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function EndGetPermissions (asyncResult As IAsyncResult) As BlobContainerPermissions" />
      <MemberSignature Language="F#" Value="abstract member EndGetPermissions : IAsyncResult -&gt; Microsoft.WindowsAzure.Storage.Blob.BlobContainerPermissions&#xA;override this.EndGetPermissions : IAsyncResult -&gt; Microsoft.WindowsAzure.Storage.Blob.BlobContainerPermissions" Usage="cloudBlobContainer.EndGetPermissions asyncResult" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Storage.Blob.BlobContainerPermissions</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="asyncResult" Type="System.IAsyncResult" />
      </Parameters>
      <Docs>
        <param name="asyncResult"><span data-ttu-id="5d9cd-604">Eine <see cref="T:System.IAsyncResult" /> , die auf den ausstehenden asynchronen Vorgang verweist.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-604">An <see cref="T:System.IAsyncResult" /> that references the pending asynchronous operation.</span></span></param>
        <summary>
            <span data-ttu-id="5d9cd-605">Gibt das asynchrone Ergebnis der Anforderung zum Abrufen der berechtigungseinstellungen für den Container zurück.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-605">Returns the asynchronous result of the request to get the permissions settings for the container.</span></span>
            </summary>
        <returns><span data-ttu-id="5d9cd-606">Die Berechtigungen des Containers.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-606">The container's permissions.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EndListBlobsSegmented">
      <MemberSignature Language="C#" Value="public virtual Microsoft.WindowsAzure.Storage.Blob.BlobResultSegment EndListBlobsSegmented (IAsyncResult asyncResult);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.WindowsAzure.Storage.Blob.BlobResultSegment EndListBlobsSegmented(class System.IAsyncResult asyncResult) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlobContainer.EndListBlobsSegmented(System.IAsyncResult)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function EndListBlobsSegmented (asyncResult As IAsyncResult) As BlobResultSegment" />
      <MemberSignature Language="F#" Value="abstract member EndListBlobsSegmented : IAsyncResult -&gt; Microsoft.WindowsAzure.Storage.Blob.BlobResultSegment&#xA;override this.EndListBlobsSegmented : IAsyncResult -&gt; Microsoft.WindowsAzure.Storage.Blob.BlobResultSegment" Usage="cloudBlobContainer.EndListBlobsSegmented asyncResult" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Storage.Blob.BlobResultSegment</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="asyncResult" Type="System.IAsyncResult" />
      </Parameters>
      <Docs>
        <param name="asyncResult"><span data-ttu-id="5d9cd-607">Eine <see cref="T:System.IAsyncResult" /> , die auf den ausstehenden asynchronen Vorgang verweist.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-607">An <see cref="T:System.IAsyncResult" /> that references the pending asynchronous operation.</span></span></param>
        <summary>
            <span data-ttu-id="5d9cd-608">Beendet einen asynchronen Vorgang zum Zurückgeben eines ergebnissegments, das eine Auflistung von Blob-Elemente im Container enthält.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-608">Ends an asynchronous operation to return a result segment containing a collection of blob items in the container.</span></span>
            </summary>
        <returns><span data-ttu-id="5d9cd-609">Ein ergebnissegment mit Objekten implementiert, <see cref="T:Microsoft.WindowsAzure.Storage.Blob.IListBlobItem" />.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-609">A result segment containing objects that implement <see cref="T:Microsoft.WindowsAzure.Storage.Blob.IListBlobItem" />.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EndReleaseLease">
      <MemberSignature Language="C#" Value="public virtual void EndReleaseLease (IAsyncResult asyncResult);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void EndReleaseLease(class System.IAsyncResult asyncResult) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlobContainer.EndReleaseLease(System.IAsyncResult)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub EndReleaseLease (asyncResult As IAsyncResult)" />
      <MemberSignature Language="F#" Value="abstract member EndReleaseLease : IAsyncResult -&gt; unit&#xA;override this.EndReleaseLease : IAsyncResult -&gt; unit" Usage="cloudBlobContainer.EndReleaseLease asyncResult" />
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
        <param name="asyncResult"><span data-ttu-id="5d9cd-610">Ein "IAsyncResult", die auf den ausstehenden asynchronen Vorgang verweist.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-610">An IAsyncResult that references the pending asynchronous operation.</span></span></param>
        <summary>
            <span data-ttu-id="5d9cd-611">Beendet einen asynchronen Vorgang zum Freigeben der Lease für diesen Container.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-611">Ends an asynchronous operation to release the lease on this container.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EndRenewLease">
      <MemberSignature Language="C#" Value="public virtual void EndRenewLease (IAsyncResult asyncResult);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void EndRenewLease(class System.IAsyncResult asyncResult) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlobContainer.EndRenewLease(System.IAsyncResult)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub EndRenewLease (asyncResult As IAsyncResult)" />
      <MemberSignature Language="F#" Value="abstract member EndRenewLease : IAsyncResult -&gt; unit&#xA;override this.EndRenewLease : IAsyncResult -&gt; unit" Usage="cloudBlobContainer.EndRenewLease asyncResult" />
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
        <param name="asyncResult"><span data-ttu-id="5d9cd-612">Ein "IAsyncResult", die auf den ausstehenden asynchronen Vorgang verweist.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-612">An IAsyncResult that references the pending asynchronous operation.</span></span></param>
        <summary>
            <span data-ttu-id="5d9cd-613">Beendet einen asynchronen Vorgang zum Erneuern einer Lease für diesen Container.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-613">Ends an asynchronous operation to renew a lease on this container.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EndSetMetadata">
      <MemberSignature Language="C#" Value="public virtual void EndSetMetadata (IAsyncResult asyncResult);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void EndSetMetadata(class System.IAsyncResult asyncResult) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlobContainer.EndSetMetadata(System.IAsyncResult)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub EndSetMetadata (asyncResult As IAsyncResult)" />
      <MemberSignature Language="F#" Value="abstract member EndSetMetadata : IAsyncResult -&gt; unit&#xA;override this.EndSetMetadata : IAsyncResult -&gt; unit" Usage="cloudBlobContainer.EndSetMetadata asyncResult" />
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
        <param name="asyncResult"><span data-ttu-id="5d9cd-614">Eine <see cref="T:System.IAsyncResult" /> , die auf den ausstehenden asynchronen Vorgang verweist.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-614">An <see cref="T:System.IAsyncResult" /> that references the pending asynchronous operation.</span></span></param>
        <summary>
            <span data-ttu-id="5d9cd-615">Beendet einen asynchronen Anforderungsvorgang zum Festlegen von benutzerdefinierten Metadaten für den Container an.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-615">Ends an asynchronous request operation to set user-defined metadata on the container.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EndSetPermissions">
      <MemberSignature Language="C#" Value="public virtual void EndSetPermissions (IAsyncResult asyncResult);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void EndSetPermissions(class System.IAsyncResult asyncResult) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlobContainer.EndSetPermissions(System.IAsyncResult)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub EndSetPermissions (asyncResult As IAsyncResult)" />
      <MemberSignature Language="F#" Value="abstract member EndSetPermissions : IAsyncResult -&gt; unit&#xA;override this.EndSetPermissions : IAsyncResult -&gt; unit" Usage="cloudBlobContainer.EndSetPermissions asyncResult" />
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
        <param name="asyncResult"><span data-ttu-id="5d9cd-616">Eine <see cref="T:System.IAsyncResult" /> , die auf den ausstehenden asynchronen Vorgang verweist.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-616">An <see cref="T:System.IAsyncResult" /> that references the pending asynchronous operation.</span></span></param>
        <summary>
            <span data-ttu-id="5d9cd-617">Gibt das Ergebnis eine asynchrone Anforderung zum Festlegen von Berechtigungen für den Container zurück.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-617">Returns the result of an asynchronous request to set permissions for the container.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Exists">
      <MemberSignature Language="C#" Value="public virtual bool Exists (Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions requestOptions = null, Microsoft.WindowsAzure.Storage.OperationContext operationContext = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance bool Exists(class Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions requestOptions, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlobContainer.Exists(Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="abstract member Exists : Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; bool&#xA;override this.Exists : Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; bool" Usage="cloudBlobContainer.Exists (requestOptions, operationContext)" />
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
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="requestOptions" Type="Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="requestOptions"><span data-ttu-id="5d9cd-618">Ein <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" /> -Objekt, das zusätzliche Optionen für die Anforderung angibt.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-618">A <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" /> object that specifies additional options for the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="5d9cd-619">Ein <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> -Objekt, das den Kontext für den aktuellen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-619">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <summary>
            <span data-ttu-id="5d9cd-620">Überprüft, ob der Container vorhanden ist.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-620">Checks whether the container exists.</span></span>
            </summary>
        <returns>
          <span data-ttu-id="5d9cd-621"><c>"true"</c> , wenn der Container vorhanden ist.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-621"><c>true</c> if the container exists.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ExistsAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task&lt;bool&gt; ExistsAsync ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;bool&gt; ExistsAsync() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlobContainer.ExistsAsync" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function ExistsAsync () As Task(Of Boolean)" />
      <MemberSignature Language="F#" Value="abstract member ExistsAsync : unit -&gt; System.Threading.Tasks.Task&lt;bool&gt;&#xA;override this.ExistsAsync : unit -&gt; System.Threading.Tasks.Task&lt;bool&gt;" Usage="cloudBlobContainer.ExistsAsync " />
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
        <ReturnType>System.Threading.Tasks.Task&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="5d9cd-622">Initiiert einen asynchronen Vorgang, der überprüft, ob der Container vorhanden ist.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-622">Initiates an asynchronous operation that checks whether the container exists.</span></span>
            </summary>
        <returns><span data-ttu-id="5d9cd-623">Ein <see cref="T:System.Threading.Tasks.Task`1" />-Objekt, das den asynchronen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-623">A <see cref="T:System.Threading.Tasks.Task`1" /> object that represents the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ExistsAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task&lt;bool&gt; ExistsAsync (System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;bool&gt; ExistsAsync(valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlobContainer.ExistsAsync(System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ExistsAsync : System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;bool&gt;&#xA;override this.ExistsAsync : System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;bool&gt;" Usage="cloudBlobContainer.ExistsAsync cancellationToken" />
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
        <ReturnType>System.Threading.Tasks.Task&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="cancellationToken"><span data-ttu-id="5d9cd-624">Ein <see cref="T:System.Threading.CancellationToken" />, das beim Warten auf den Abschluss einer Aufgabe überwacht werden soll.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-624">A <see cref="T:System.Threading.CancellationToken" /> to observe while waiting for a task to complete.</span></span></param>
        <summary>
            <span data-ttu-id="5d9cd-625">Initiiert einen asynchronen Vorgang, der überprüft, ob der Container vorhanden ist.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-625">Initiates an asynchronous operation that checks whether the container exists.</span></span>
            </summary>
        <returns><span data-ttu-id="5d9cd-626">Ein <see cref="T:System.Threading.Tasks.Task`1" />-Objekt, das den asynchronen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-626">A <see cref="T:System.Threading.Tasks.Task`1" /> object that represents the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ExistsAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task&lt;bool&gt; ExistsAsync (Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, Microsoft.WindowsAzure.Storage.OperationContext operationContext);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;bool&gt; ExistsAsync(class Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlobContainer.ExistsAsync(Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="abstract member ExistsAsync : Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Threading.Tasks.Task&lt;bool&gt;&#xA;override this.ExistsAsync : Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Threading.Tasks.Task&lt;bool&gt;" Usage="cloudBlobContainer.ExistsAsync (options, operationContext)" />
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
        <ReturnType>System.Threading.Tasks.Task&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="options" Type="Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="options"><span data-ttu-id="5d9cd-627">Ein <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" /> -Objekt, das zusätzliche Optionen für die Anforderung angibt.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-627">A <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" /> object that specifies additional options for the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="5d9cd-628">Ein <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> -Objekt, das den Kontext für den aktuellen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-628">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <summary>
            <span data-ttu-id="5d9cd-629">Initiiert einen asynchronen Vorgang, der überprüft, ob der Container vorhanden ist.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-629">Initiates an asynchronous operation that checks whether the container exists.</span></span>
            </summary>
        <returns><span data-ttu-id="5d9cd-630">Ein <see cref="T:System.Threading.Tasks.Task`1" />-Objekt, das den asynchronen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-630">A <see cref="T:System.Threading.Tasks.Task`1" /> object that represents the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ExistsAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task&lt;bool&gt; ExistsAsync (Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, Microsoft.WindowsAzure.Storage.OperationContext operationContext, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;bool&gt; ExistsAsync(class Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, class Microsoft.WindowsAzure.Storage.OperationContext operationContext, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlobContainer.ExistsAsync(Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ExistsAsync : Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;bool&gt;&#xA;override this.ExistsAsync : Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;bool&gt;" Usage="cloudBlobContainer.ExistsAsync (options, operationContext, cancellationToken)" />
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
        <ReturnType>System.Threading.Tasks.Task&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="options" Type="Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="options"><span data-ttu-id="5d9cd-631">Ein <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" /> -Objekt, das zusätzliche Optionen für die Anforderung angibt.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-631">A <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" /> object that specifies additional options for the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="5d9cd-632">Ein <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> -Objekt, das den Kontext für den aktuellen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-632">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="5d9cd-633">Ein <see cref="T:System.Threading.CancellationToken" />, das beim Warten auf den Abschluss einer Aufgabe überwacht werden soll.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-633">A <see cref="T:System.Threading.CancellationToken" /> to observe while waiting for a task to complete.</span></span></param>
        <summary>
            <span data-ttu-id="5d9cd-634">Initiiert einen asynchronen Vorgang, der überprüft, ob der Container vorhanden ist.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-634">Initiates an asynchronous operation that checks whether the container exists.</span></span>
            </summary>
        <returns><span data-ttu-id="5d9cd-635">Ein <see cref="T:System.Threading.Tasks.Task`1" />-Objekt, das den asynchronen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-635">A <see cref="T:System.Threading.Tasks.Task`1" /> object that represents the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="FetchAttributes">
      <MemberSignature Language="C#" Value="public virtual void FetchAttributes (Microsoft.WindowsAzure.Storage.AccessCondition accessCondition = null, Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options = null, Microsoft.WindowsAzure.Storage.OperationContext operationContext = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void FetchAttributes(class Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, class Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlobContainer.FetchAttributes(Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="abstract member FetchAttributes : Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; unit&#xA;override this.FetchAttributes : Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; unit" Usage="cloudBlobContainer.FetchAttributes (accessCondition, options, operationContext)" />
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
        <Parameter Name="accessCondition" Type="Microsoft.WindowsAzure.Storage.AccessCondition" />
        <Parameter Name="options" Type="Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="accessCondition"><span data-ttu-id="5d9cd-636">Ein <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> -Objekt, das die Bedingung, die erfüllt sein müssen, damit die Anforderung darstellt, um den Vorgang fortzusetzen.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-636">An <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> object that represents the condition that must be met in order for the request to proceed.</span></span> <span data-ttu-id="5d9cd-637">Wenn <c>null</c>, keine Bedingung verwendet.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-637">If <c>null</c>, no condition is used.</span></span></param>
        <param name="options"><span data-ttu-id="5d9cd-638">Ein <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" /> -Objekt, das zusätzliche Optionen für die Anforderung angibt.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-638">A <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" /> object that specifies additional options for the request.</span></span> <span data-ttu-id="5d9cd-639">Wenn <c>null</c>, Standardoptionen gelten für die Anforderung.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-639">If <c>null</c>, default options are applied to the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="5d9cd-640">Ein <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> -Objekt, das den Kontext für den aktuellen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-640">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <summary>
            <span data-ttu-id="5d9cd-641">Ruft die Attribute des Containers ab.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-641">Retrieves the container's attributes.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="FetchAttributesAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task FetchAttributesAsync ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task FetchAttributesAsync() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlobContainer.FetchAttributesAsync" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function FetchAttributesAsync () As Task" />
      <MemberSignature Language="F#" Value="abstract member FetchAttributesAsync : unit -&gt; System.Threading.Tasks.Task&#xA;override this.FetchAttributesAsync : unit -&gt; System.Threading.Tasks.Task" Usage="cloudBlobContainer.FetchAttributesAsync " />
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
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="5d9cd-642">Initiiert einen asynchronen Vorgang, der die Attribute des Containers abruft.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-642">Initiates an asynchronous operation that retrieves the container's attributes.</span></span>
            </summary>
        <returns><span data-ttu-id="5d9cd-643">Ein <see cref="T:System.Threading.Tasks.Task" />-Objekt, das den asynchronen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-643">A <see cref="T:System.Threading.Tasks.Task" /> object that represents the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="FetchAttributesAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task FetchAttributesAsync (System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task FetchAttributesAsync(valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlobContainer.FetchAttributesAsync(System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member FetchAttributesAsync : System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&#xA;override this.FetchAttributesAsync : System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="cloudBlobContainer.FetchAttributesAsync cancellationToken" />
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
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="cancellationToken"><span data-ttu-id="5d9cd-644">Ein <see cref="T:System.Threading.CancellationToken" />, das beim Warten auf den Abschluss einer Aufgabe überwacht werden soll.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-644">A <see cref="T:System.Threading.CancellationToken" /> to observe while waiting for a task to complete.</span></span></param>
        <summary>
            <span data-ttu-id="5d9cd-645">Initiiert einen asynchronen Vorgang, der die Attribute des Containers abruft.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-645">Initiates an asynchronous operation that retrieves the container's attributes.</span></span>
            </summary>
        <returns><span data-ttu-id="5d9cd-646">Ein <see cref="T:System.Threading.Tasks.Task" />-Objekt, das den asynchronen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-646">A <see cref="T:System.Threading.Tasks.Task" /> object that represents the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="FetchAttributesAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task FetchAttributesAsync (Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, Microsoft.WindowsAzure.Storage.OperationContext operationContext);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task FetchAttributesAsync(class Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, class Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlobContainer.FetchAttributesAsync(Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="abstract member FetchAttributesAsync : Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Threading.Tasks.Task&#xA;override this.FetchAttributesAsync : Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Threading.Tasks.Task" Usage="cloudBlobContainer.FetchAttributesAsync (accessCondition, options, operationContext)" />
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
        <Parameter Name="accessCondition" Type="Microsoft.WindowsAzure.Storage.AccessCondition" />
        <Parameter Name="options" Type="Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="accessCondition"><span data-ttu-id="5d9cd-647">Ein <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> -Objekt, das die Bedingung, die erfüllt sein müssen, damit die Anforderung darstellt, um den Vorgang fortzusetzen.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-647">An <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> object that represents the condition that must be met in order for the request to proceed.</span></span> <span data-ttu-id="5d9cd-648">Wenn <c>null</c>, keine Bedingung verwendet.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-648">If <c>null</c>, no condition is used.</span></span></param>
        <param name="options"><span data-ttu-id="5d9cd-649">Ein <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" /> -Objekt, das zusätzliche Optionen für die Anforderung angibt.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-649">A <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" /> object that specifies additional options for the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="5d9cd-650">Ein <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> -Objekt, das den Kontext für den aktuellen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-650">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <summary>
            <span data-ttu-id="5d9cd-651">Initiiert einen asynchronen Vorgang, der die Attribute des Containers abruft.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-651">Initiates an asynchronous operation that retrieves the container's attributes.</span></span>
            </summary>
        <returns><span data-ttu-id="5d9cd-652">Ein <see cref="T:System.Threading.Tasks.Task" />-Objekt, das den asynchronen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-652">A <see cref="T:System.Threading.Tasks.Task" /> object that represents the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="FetchAttributesAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task FetchAttributesAsync (Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, Microsoft.WindowsAzure.Storage.OperationContext operationContext, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task FetchAttributesAsync(class Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, class Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, class Microsoft.WindowsAzure.Storage.OperationContext operationContext, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlobContainer.FetchAttributesAsync(Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member FetchAttributesAsync : Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&#xA;override this.FetchAttributesAsync : Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="cloudBlobContainer.FetchAttributesAsync (accessCondition, options, operationContext, cancellationToken)" />
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
        <Parameter Name="accessCondition" Type="Microsoft.WindowsAzure.Storage.AccessCondition" />
        <Parameter Name="options" Type="Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="accessCondition"><span data-ttu-id="5d9cd-653">Ein <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> -Objekt, das die Bedingung, die erfüllt sein müssen, damit die Anforderung darstellt, um den Vorgang fortzusetzen.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-653">An <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> object that represents the condition that must be met in order for the request to proceed.</span></span> <span data-ttu-id="5d9cd-654">Wenn <c>null</c>, keine Bedingung verwendet.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-654">If <c>null</c>, no condition is used.</span></span></param>
        <param name="options"><span data-ttu-id="5d9cd-655">Ein <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" /> -Objekt, das zusätzliche Optionen für die Anforderung angibt.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-655">A <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" /> object that specifies additional options for the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="5d9cd-656">Ein <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> -Objekt, das den Kontext für den aktuellen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-656">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="5d9cd-657">Ein <see cref="T:System.Threading.CancellationToken" />, das beim Warten auf den Abschluss einer Aufgabe überwacht werden soll.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-657">A <see cref="T:System.Threading.CancellationToken" /> to observe while waiting for a task to complete.</span></span></param>
        <summary>
            <span data-ttu-id="5d9cd-658">Initiiert einen asynchronen Vorgang, der die Attribute des Containers abruft.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-658">Initiates an asynchronous operation that retrieves the container's attributes.</span></span>
            </summary>
        <returns><span data-ttu-id="5d9cd-659">Ein <see cref="T:System.Threading.Tasks.Task" />-Objekt, das den asynchronen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-659">A <see cref="T:System.Threading.Tasks.Task" /> object that represents the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAppendBlobReference">
      <MemberSignature Language="C#" Value="public virtual Microsoft.WindowsAzure.Storage.Blob.CloudAppendBlob GetAppendBlobReference (string blobName);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.WindowsAzure.Storage.Blob.CloudAppendBlob GetAppendBlobReference(string blobName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlobContainer.GetAppendBlobReference(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function GetAppendBlobReference (blobName As String) As CloudAppendBlob" />
      <MemberSignature Language="F#" Value="abstract member GetAppendBlobReference : string -&gt; Microsoft.WindowsAzure.Storage.Blob.CloudAppendBlob&#xA;override this.GetAppendBlobReference : string -&gt; Microsoft.WindowsAzure.Storage.Blob.CloudAppendBlob" Usage="cloudBlobContainer.GetAppendBlobReference blobName" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Storage.Blob.CloudAppendBlob</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="blobName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="blobName"><span data-ttu-id="5d9cd-660">Eine Zeichenfolge, die mit dem Namen des Anhang-BLOBs.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-660">A string containing the name of the append blob.</span></span></param>
        <summary>
            <span data-ttu-id="5d9cd-661">Ruft einen Verweis auf ein Anhang-Blob in diesem Container ab.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-661">Gets a reference to an append blob in this container.</span></span>
            </summary>
        <returns><span data-ttu-id="5d9cd-662">Ein <see cref="T:Microsoft.WindowsAzure.Storage.Blob.CloudAppendBlob" />-Objekt.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-662">A <see cref="T:Microsoft.WindowsAzure.Storage.Blob.CloudAppendBlob" /> object.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAppendBlobReference">
      <MemberSignature Language="C#" Value="public virtual Microsoft.WindowsAzure.Storage.Blob.CloudAppendBlob GetAppendBlobReference (string blobName, Nullable&lt;DateTimeOffset&gt; snapshotTime);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.WindowsAzure.Storage.Blob.CloudAppendBlob GetAppendBlobReference(string blobName, valuetype System.Nullable`1&lt;valuetype System.DateTimeOffset&gt; snapshotTime) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlobContainer.GetAppendBlobReference(System.String,System.Nullable{System.DateTimeOffset})" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function GetAppendBlobReference (blobName As String, snapshotTime As Nullable(Of DateTimeOffset)) As CloudAppendBlob" />
      <MemberSignature Language="F#" Value="abstract member GetAppendBlobReference : string * Nullable&lt;DateTimeOffset&gt; -&gt; Microsoft.WindowsAzure.Storage.Blob.CloudAppendBlob&#xA;override this.GetAppendBlobReference : string * Nullable&lt;DateTimeOffset&gt; -&gt; Microsoft.WindowsAzure.Storage.Blob.CloudAppendBlob" Usage="cloudBlobContainer.GetAppendBlobReference (blobName, snapshotTime)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Storage.Blob.CloudAppendBlob</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="blobName" Type="System.String" />
        <Parameter Name="snapshotTime" Type="System.Nullable&lt;System.DateTimeOffset&gt;" />
      </Parameters>
      <Docs>
        <param name="blobName"><span data-ttu-id="5d9cd-663">Eine Zeichenfolge, die mit dem Namen des Anhang-BLOBs.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-663">A string containing the name of the append blob.</span></span></param>
        <param name="snapshotTime"><span data-ttu-id="5d9cd-664">Ein <see cref="T:System.DateTimeOffset" /> den Momentaufnahme-Zeitstempel angeben, wenn das Blob eine Momentaufnahme ist.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-664">A <see cref="T:System.DateTimeOffset" /> specifying the snapshot timestamp, if the blob is a snapshot.</span></span></param>
        <summary>
            <span data-ttu-id="5d9cd-665">Ruft einen Verweis auf ein Anhang-Blob in diesem Container ab.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-665">Gets a reference to an append blob in this container.</span></span>
            </summary>
        <returns><span data-ttu-id="5d9cd-666">Ein <see cref="T:Microsoft.WindowsAzure.Storage.Blob.CloudAppendBlob" />-Objekt.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-666">A <see cref="T:Microsoft.WindowsAzure.Storage.Blob.CloudAppendBlob" /> object.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetBlobReference">
      <MemberSignature Language="C#" Value="public virtual Microsoft.WindowsAzure.Storage.Blob.CloudBlob GetBlobReference (string blobName);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.WindowsAzure.Storage.Blob.CloudBlob GetBlobReference(string blobName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlobContainer.GetBlobReference(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function GetBlobReference (blobName As String) As CloudBlob" />
      <MemberSignature Language="F#" Value="abstract member GetBlobReference : string -&gt; Microsoft.WindowsAzure.Storage.Blob.CloudBlob&#xA;override this.GetBlobReference : string -&gt; Microsoft.WindowsAzure.Storage.Blob.CloudBlob" Usage="cloudBlobContainer.GetBlobReference blobName" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Storage.Blob.CloudBlob</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="blobName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="blobName"><span data-ttu-id="5d9cd-667">Eine Zeichenfolge, die den Namen des BLOBs enthält.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-667">A string containing the name of the blob.</span></span></param>
        <summary>
            <span data-ttu-id="5d9cd-668">Ruft einen Verweis auf ein Blob in diesem Container ab.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-668">Gets a reference to a blob in this container.</span></span>
            </summary>
        <returns><span data-ttu-id="5d9cd-669">Ein <see cref="T:Microsoft.WindowsAzure.Storage.Blob.CloudBlob" />-Objekt.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-669">A <see cref="T:Microsoft.WindowsAzure.Storage.Blob.CloudBlob" /> object.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetBlobReference">
      <MemberSignature Language="C#" Value="public virtual Microsoft.WindowsAzure.Storage.Blob.CloudBlob GetBlobReference (string blobName, Nullable&lt;DateTimeOffset&gt; snapshotTime);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.WindowsAzure.Storage.Blob.CloudBlob GetBlobReference(string blobName, valuetype System.Nullable`1&lt;valuetype System.DateTimeOffset&gt; snapshotTime) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlobContainer.GetBlobReference(System.String,System.Nullable{System.DateTimeOffset})" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function GetBlobReference (blobName As String, snapshotTime As Nullable(Of DateTimeOffset)) As CloudBlob" />
      <MemberSignature Language="F#" Value="abstract member GetBlobReference : string * Nullable&lt;DateTimeOffset&gt; -&gt; Microsoft.WindowsAzure.Storage.Blob.CloudBlob&#xA;override this.GetBlobReference : string * Nullable&lt;DateTimeOffset&gt; -&gt; Microsoft.WindowsAzure.Storage.Blob.CloudBlob" Usage="cloudBlobContainer.GetBlobReference (blobName, snapshotTime)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Storage.Blob.CloudBlob</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="blobName" Type="System.String" />
        <Parameter Name="snapshotTime" Type="System.Nullable&lt;System.DateTimeOffset&gt;" />
      </Parameters>
      <Docs>
        <param name="blobName"><span data-ttu-id="5d9cd-670">Eine Zeichenfolge, die den Namen des BLOBs enthält.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-670">A string containing the name of the blob.</span></span></param>
        <param name="snapshotTime"><span data-ttu-id="5d9cd-671">Ein <see cref="T:System.DateTimeOffset" /> den Momentaufnahme-Zeitstempel angeben, wenn das Blob eine Momentaufnahme ist.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-671">A <see cref="T:System.DateTimeOffset" /> specifying the snapshot timestamp, if the blob is a snapshot.</span></span></param>
        <summary>
            <span data-ttu-id="5d9cd-672">Ruft einen Verweis auf ein Blob in diesem Container ab.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-672">Gets a reference to a blob in this container.</span></span>
            </summary>
        <returns><span data-ttu-id="5d9cd-673">Ein <see cref="T:Microsoft.WindowsAzure.Storage.Blob.CloudBlob" />-Objekt.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-673">A <see cref="T:Microsoft.WindowsAzure.Storage.Blob.CloudBlob" /> object.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetBlobReferenceFromServer">
      <MemberSignature Language="C#" Value="public virtual Microsoft.WindowsAzure.Storage.Blob.ICloudBlob GetBlobReferenceFromServer (string blobName, Microsoft.WindowsAzure.Storage.AccessCondition accessCondition = null, Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options = null, Microsoft.WindowsAzure.Storage.OperationContext operationContext = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.WindowsAzure.Storage.Blob.ICloudBlob GetBlobReferenceFromServer(string blobName, class Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, class Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlobContainer.GetBlobReferenceFromServer(System.String,Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="abstract member GetBlobReferenceFromServer : string * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; Microsoft.WindowsAzure.Storage.Blob.ICloudBlob&#xA;override this.GetBlobReferenceFromServer : string * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; Microsoft.WindowsAzure.Storage.Blob.ICloudBlob" Usage="cloudBlobContainer.GetBlobReferenceFromServer (blobName, accessCondition, options, operationContext)" />
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
        <ReturnType>Microsoft.WindowsAzure.Storage.Blob.ICloudBlob</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="blobName" Type="System.String" />
        <Parameter Name="accessCondition" Type="Microsoft.WindowsAzure.Storage.AccessCondition" />
        <Parameter Name="options" Type="Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="blobName"><span data-ttu-id="5d9cd-674">Eine Zeichenfolge, die den Namen des BLOBs enthält.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-674">A string containing the name of the blob.</span></span></param>
        <param name="accessCondition"><span data-ttu-id="5d9cd-675">Ein <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> -Objekt, das die Bedingung, die erfüllt sein müssen, damit die Anforderung darstellt, um den Vorgang fortzusetzen.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-675">An <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> object that represents the condition that must be met in order for the request to proceed.</span></span> <span data-ttu-id="5d9cd-676">Wenn <c>null</c>, keine Bedingung verwendet.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-676">If <c>null</c>, no condition is used.</span></span></param>
        <param name="options"><span data-ttu-id="5d9cd-677">Ein <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" /> -Objekt, das zusätzliche Optionen für die Anforderung angibt.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-677">A <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" /> object that specifies additional options for the request.</span></span> <span data-ttu-id="5d9cd-678">Wenn <c>null</c>, Standardoptionen gelten für die Anforderung.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-678">If <c>null</c>, default options are applied to the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="5d9cd-679">Ein <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> -Objekt, das den Kontext für den aktuellen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-679">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <summary>
            <span data-ttu-id="5d9cd-680">Ruft einen Verweis auf ein Blob in diesem Container ab.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-680">Gets a reference to a blob in this container.</span></span>
            </summary>
        <returns><span data-ttu-id="5d9cd-681">Ein Verweis auf das Blob.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-681">A reference to the blob.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetBlobReferenceFromServerAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Blob.ICloudBlob&gt; GetBlobReferenceFromServerAsync (string blobName);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.WindowsAzure.Storage.Blob.ICloudBlob&gt; GetBlobReferenceFromServerAsync(string blobName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlobContainer.GetBlobReferenceFromServerAsync(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function GetBlobReferenceFromServerAsync (blobName As String) As Task(Of ICloudBlob)" />
      <MemberSignature Language="F#" Value="abstract member GetBlobReferenceFromServerAsync : string -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Blob.ICloudBlob&gt;&#xA;override this.GetBlobReferenceFromServerAsync : string -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Blob.ICloudBlob&gt;" Usage="cloudBlobContainer.GetBlobReferenceFromServerAsync blobName" />
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
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Blob.ICloudBlob&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="blobName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="blobName"><span data-ttu-id="5d9cd-682">Eine Zeichenfolge, die den Namen des BLOBs enthält.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-682">A string containing the name of the blob.</span></span></param>
        <summary>
            <span data-ttu-id="5d9cd-683">Initiiert einen asynchronen Vorgang, der einen Verweis auf ein Blob in diesem Container abruft.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-683">Initiates an asynchronous operation that gets a reference to a blob in this container.</span></span>
            </summary>
        <returns><span data-ttu-id="5d9cd-684">Ein <see cref="T:System.Threading.Tasks.Task`1" />-Objekt, das den asynchronen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-684">A <see cref="T:System.Threading.Tasks.Task`1" /> object that represents the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetBlobReferenceFromServerAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Blob.ICloudBlob&gt; GetBlobReferenceFromServerAsync (string blobName, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.WindowsAzure.Storage.Blob.ICloudBlob&gt; GetBlobReferenceFromServerAsync(string blobName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlobContainer.GetBlobReferenceFromServerAsync(System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetBlobReferenceFromServerAsync : string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Blob.ICloudBlob&gt;&#xA;override this.GetBlobReferenceFromServerAsync : string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Blob.ICloudBlob&gt;" Usage="cloudBlobContainer.GetBlobReferenceFromServerAsync (blobName, cancellationToken)" />
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
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Blob.ICloudBlob&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="blobName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="blobName"><span data-ttu-id="5d9cd-685">Eine Zeichenfolge, die den Namen des BLOBs enthält.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-685">A string containing the name of the blob.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="5d9cd-686">Ein <see cref="T:System.Threading.CancellationToken" />, das beim Warten auf den Abschluss einer Aufgabe überwacht werden soll.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-686">A <see cref="T:System.Threading.CancellationToken" /> to observe while waiting for a task to complete.</span></span></param>
        <summary>
            <span data-ttu-id="5d9cd-687">Initiiert einen asynchronen Vorgang, der einen Verweis auf ein Blob in diesem Container abruft.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-687">Initiates an asynchronous operation that gets a reference to a blob in this container.</span></span>
            </summary>
        <returns><span data-ttu-id="5d9cd-688">Ein <see cref="T:System.Threading.Tasks.Task`1" />-Objekt, das den asynchronen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-688">A <see cref="T:System.Threading.Tasks.Task`1" /> object that represents the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetBlobReferenceFromServerAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Blob.ICloudBlob&gt; GetBlobReferenceFromServerAsync (string blobName, Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, Microsoft.WindowsAzure.Storage.OperationContext operationContext);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.WindowsAzure.Storage.Blob.ICloudBlob&gt; GetBlobReferenceFromServerAsync(string blobName, class Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, class Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlobContainer.GetBlobReferenceFromServerAsync(System.String,Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="abstract member GetBlobReferenceFromServerAsync : string * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Blob.ICloudBlob&gt;&#xA;override this.GetBlobReferenceFromServerAsync : string * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Blob.ICloudBlob&gt;" Usage="cloudBlobContainer.GetBlobReferenceFromServerAsync (blobName, accessCondition, options, operationContext)" />
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
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Blob.ICloudBlob&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="blobName" Type="System.String" />
        <Parameter Name="accessCondition" Type="Microsoft.WindowsAzure.Storage.AccessCondition" />
        <Parameter Name="options" Type="Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="blobName"><span data-ttu-id="5d9cd-689">Eine Zeichenfolge, die den Namen des BLOBs enthält.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-689">A string containing the name of the blob.</span></span></param>
        <param name="accessCondition"><span data-ttu-id="5d9cd-690">Ein <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> -Objekt, das die Bedingung, die erfüllt sein müssen, damit die Anforderung darstellt, um den Vorgang fortzusetzen.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-690">An <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> object that represents the condition that must be met in order for the request to proceed.</span></span> <span data-ttu-id="5d9cd-691">Wenn <c>null</c>, keine Bedingung verwendet.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-691">If <c>null</c>, no condition is used.</span></span></param>
        <param name="options"><span data-ttu-id="5d9cd-692">Ein <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" /> -Objekt, das zusätzliche Optionen für die Anforderung angibt.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-692">A <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" /> object that specifies additional options for the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="5d9cd-693">Ein <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> -Objekt, das den Kontext für den aktuellen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-693">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <summary>
            <span data-ttu-id="5d9cd-694">Initiiert einen asynchronen Vorgang, der einen Verweis auf ein Blob in diesem Container abruft.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-694">Initiates an asynchronous operation that gets a reference to a blob in this container.</span></span>
            </summary>
        <returns><span data-ttu-id="5d9cd-695">Ein <see cref="T:System.Threading.Tasks.Task`1" />-Objekt, das den asynchronen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-695">A <see cref="T:System.Threading.Tasks.Task`1" /> object that represents the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetBlobReferenceFromServerAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Blob.ICloudBlob&gt; GetBlobReferenceFromServerAsync (string blobName, Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, Microsoft.WindowsAzure.Storage.OperationContext operationContext, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.WindowsAzure.Storage.Blob.ICloudBlob&gt; GetBlobReferenceFromServerAsync(string blobName, class Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, class Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, class Microsoft.WindowsAzure.Storage.OperationContext operationContext, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlobContainer.GetBlobReferenceFromServerAsync(System.String,Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetBlobReferenceFromServerAsync : string * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Blob.ICloudBlob&gt;&#xA;override this.GetBlobReferenceFromServerAsync : string * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Blob.ICloudBlob&gt;" Usage="cloudBlobContainer.GetBlobReferenceFromServerAsync (blobName, accessCondition, options, operationContext, cancellationToken)" />
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
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Blob.ICloudBlob&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="blobName" Type="System.String" />
        <Parameter Name="accessCondition" Type="Microsoft.WindowsAzure.Storage.AccessCondition" />
        <Parameter Name="options" Type="Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="blobName"><span data-ttu-id="5d9cd-696">Eine Zeichenfolge, die den Namen des BLOBs enthält.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-696">A string containing the name of the blob.</span></span></param>
        <param name="accessCondition"><span data-ttu-id="5d9cd-697">Ein <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> -Objekt, das die Bedingung, die erfüllt sein müssen, damit die Anforderung darstellt, um den Vorgang fortzusetzen.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-697">An <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> object that represents the condition that must be met in order for the request to proceed.</span></span> <span data-ttu-id="5d9cd-698">Wenn <c>null</c>, keine Bedingung verwendet.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-698">If <c>null</c>, no condition is used.</span></span></param>
        <param name="options"><span data-ttu-id="5d9cd-699">Ein <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" /> -Objekt, das zusätzliche Optionen für die Anforderung angibt.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-699">A <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" /> object that specifies additional options for the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="5d9cd-700">Ein <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> -Objekt, das den Kontext für den aktuellen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-700">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="5d9cd-701">Ein <see cref="T:System.Threading.CancellationToken" />, das beim Warten auf den Abschluss einer Aufgabe überwacht werden soll.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-701">A <see cref="T:System.Threading.CancellationToken" /> to observe while waiting for a task to complete.</span></span></param>
        <summary>
            <span data-ttu-id="5d9cd-702">Initiiert einen asynchronen Vorgang, der einen Verweis auf ein Blob in diesem Container abruft.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-702">Initiates an asynchronous operation that gets a reference to a blob in this container.</span></span>
            </summary>
        <returns><span data-ttu-id="5d9cd-703">Ein <see cref="T:System.Threading.Tasks.Task`1" />-Objekt, das den asynchronen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-703">A <see cref="T:System.Threading.Tasks.Task`1" /> object that represents the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetBlockBlobReference">
      <MemberSignature Language="C#" Value="public virtual Microsoft.WindowsAzure.Storage.Blob.CloudBlockBlob GetBlockBlobReference (string blobName);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.WindowsAzure.Storage.Blob.CloudBlockBlob GetBlockBlobReference(string blobName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlobContainer.GetBlockBlobReference(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function GetBlockBlobReference (blobName As String) As CloudBlockBlob" />
      <MemberSignature Language="F#" Value="abstract member GetBlockBlobReference : string -&gt; Microsoft.WindowsAzure.Storage.Blob.CloudBlockBlob&#xA;override this.GetBlockBlobReference : string -&gt; Microsoft.WindowsAzure.Storage.Blob.CloudBlockBlob" Usage="cloudBlobContainer.GetBlockBlobReference blobName" />
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
        <Parameter Name="blobName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="blobName"><span data-ttu-id="5d9cd-704">Eine Zeichenfolge, die den Namen des blockblobs enthält.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-704">A string containing the name of the block blob.</span></span></param>
        <summary>
            <span data-ttu-id="5d9cd-705">Ruft einen Verweis auf ein Blockblob in diesem Container ab.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-705">Gets a reference to a block blob in this container.</span></span>
            </summary>
        <returns><span data-ttu-id="5d9cd-706">Ein <see cref="T:Microsoft.WindowsAzure.Storage.Blob.CloudBlockBlob" />-Objekt.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-706">A <see cref="T:Microsoft.WindowsAzure.Storage.Blob.CloudBlockBlob" /> object.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetBlockBlobReference">
      <MemberSignature Language="C#" Value="public virtual Microsoft.WindowsAzure.Storage.Blob.CloudBlockBlob GetBlockBlobReference (string blobName, Nullable&lt;DateTimeOffset&gt; snapshotTime);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.WindowsAzure.Storage.Blob.CloudBlockBlob GetBlockBlobReference(string blobName, valuetype System.Nullable`1&lt;valuetype System.DateTimeOffset&gt; snapshotTime) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlobContainer.GetBlockBlobReference(System.String,System.Nullable{System.DateTimeOffset})" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function GetBlockBlobReference (blobName As String, snapshotTime As Nullable(Of DateTimeOffset)) As CloudBlockBlob" />
      <MemberSignature Language="F#" Value="abstract member GetBlockBlobReference : string * Nullable&lt;DateTimeOffset&gt; -&gt; Microsoft.WindowsAzure.Storage.Blob.CloudBlockBlob&#xA;override this.GetBlockBlobReference : string * Nullable&lt;DateTimeOffset&gt; -&gt; Microsoft.WindowsAzure.Storage.Blob.CloudBlockBlob" Usage="cloudBlobContainer.GetBlockBlobReference (blobName, snapshotTime)" />
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
        <Parameter Name="blobName" Type="System.String" />
        <Parameter Name="snapshotTime" Type="System.Nullable&lt;System.DateTimeOffset&gt;" />
      </Parameters>
      <Docs>
        <param name="blobName"><span data-ttu-id="5d9cd-707">Eine Zeichenfolge, die den Namen des blockblobs enthält.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-707">A string containing the name of the block blob.</span></span></param>
        <param name="snapshotTime"><span data-ttu-id="5d9cd-708">Ein <see cref="T:System.DateTimeOffset" /> den Momentaufnahme-Zeitstempel angeben, wenn das Blob eine Momentaufnahme ist.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-708">A <see cref="T:System.DateTimeOffset" /> specifying the snapshot timestamp, if the blob is a snapshot.</span></span></param>
        <summary>
            <span data-ttu-id="5d9cd-709">Ruft einen Verweis auf ein Blockblob in diesem Container ab.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-709">Gets a reference to a block blob in this container.</span></span>
            </summary>
        <returns><span data-ttu-id="5d9cd-710">Ein <see cref="T:Microsoft.WindowsAzure.Storage.Blob.CloudBlockBlob" />-Objekt.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-710">A <see cref="T:Microsoft.WindowsAzure.Storage.Blob.CloudBlockBlob" /> object.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetDirectoryReference">
      <MemberSignature Language="C#" Value="public virtual Microsoft.WindowsAzure.Storage.Blob.CloudBlobDirectory GetDirectoryReference (string relativeAddress);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.WindowsAzure.Storage.Blob.CloudBlobDirectory GetDirectoryReference(string relativeAddress) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlobContainer.GetDirectoryReference(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function GetDirectoryReference (relativeAddress As String) As CloudBlobDirectory" />
      <MemberSignature Language="F#" Value="abstract member GetDirectoryReference : string -&gt; Microsoft.WindowsAzure.Storage.Blob.CloudBlobDirectory&#xA;override this.GetDirectoryReference : string -&gt; Microsoft.WindowsAzure.Storage.Blob.CloudBlobDirectory" Usage="cloudBlobContainer.GetDirectoryReference relativeAddress" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Storage.Blob.CloudBlobDirectory</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="relativeAddress" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="relativeAddress"><span data-ttu-id="5d9cd-711">Eine Zeichenfolge mit dem Namen des virtuellen Blob-Verzeichnisses.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-711">A string containing the name of the virtual blob directory.</span></span></param>
        <summary>
            <span data-ttu-id="5d9cd-712">Ruft einen Verweis auf ein virtuelles Blob-Verzeichnis unter diesem Container ab.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-712">Gets a reference to a virtual blob directory beneath this container.</span></span>
            </summary>
        <returns><span data-ttu-id="5d9cd-713">Ein <see cref="T:Microsoft.WindowsAzure.Storage.Blob.CloudBlobDirectory" />-Objekt.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-713">A <see cref="T:Microsoft.WindowsAzure.Storage.Blob.CloudBlobDirectory" /> object.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetPageBlobReference">
      <MemberSignature Language="C#" Value="public virtual Microsoft.WindowsAzure.Storage.Blob.CloudPageBlob GetPageBlobReference (string blobName);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.WindowsAzure.Storage.Blob.CloudPageBlob GetPageBlobReference(string blobName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlobContainer.GetPageBlobReference(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function GetPageBlobReference (blobName As String) As CloudPageBlob" />
      <MemberSignature Language="F#" Value="abstract member GetPageBlobReference : string -&gt; Microsoft.WindowsAzure.Storage.Blob.CloudPageBlob&#xA;override this.GetPageBlobReference : string -&gt; Microsoft.WindowsAzure.Storage.Blob.CloudPageBlob" Usage="cloudBlobContainer.GetPageBlobReference blobName" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Storage.Blob.CloudPageBlob</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="blobName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="blobName"><span data-ttu-id="5d9cd-714">Eine Zeichenfolge, die mit dem Namen des Seitenblobs.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-714">A string containing the name of the page blob.</span></span></param>
        <summary>
            <span data-ttu-id="5d9cd-715">Ruft einen Verweis auf ein Seitenblob in diesem Container ab.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-715">Gets a reference to a page blob in this container.</span></span>
            </summary>
        <returns><span data-ttu-id="5d9cd-716">Ein <see cref="T:Microsoft.WindowsAzure.Storage.Blob.CloudPageBlob" />-Objekt.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-716">A <see cref="T:Microsoft.WindowsAzure.Storage.Blob.CloudPageBlob" /> object.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetPageBlobReference">
      <MemberSignature Language="C#" Value="public virtual Microsoft.WindowsAzure.Storage.Blob.CloudPageBlob GetPageBlobReference (string blobName, Nullable&lt;DateTimeOffset&gt; snapshotTime);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.WindowsAzure.Storage.Blob.CloudPageBlob GetPageBlobReference(string blobName, valuetype System.Nullable`1&lt;valuetype System.DateTimeOffset&gt; snapshotTime) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlobContainer.GetPageBlobReference(System.String,System.Nullable{System.DateTimeOffset})" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function GetPageBlobReference (blobName As String, snapshotTime As Nullable(Of DateTimeOffset)) As CloudPageBlob" />
      <MemberSignature Language="F#" Value="abstract member GetPageBlobReference : string * Nullable&lt;DateTimeOffset&gt; -&gt; Microsoft.WindowsAzure.Storage.Blob.CloudPageBlob&#xA;override this.GetPageBlobReference : string * Nullable&lt;DateTimeOffset&gt; -&gt; Microsoft.WindowsAzure.Storage.Blob.CloudPageBlob" Usage="cloudBlobContainer.GetPageBlobReference (blobName, snapshotTime)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Storage.Blob.CloudPageBlob</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="blobName" Type="System.String" />
        <Parameter Name="snapshotTime" Type="System.Nullable&lt;System.DateTimeOffset&gt;" />
      </Parameters>
      <Docs>
        <param name="blobName"><span data-ttu-id="5d9cd-717">Eine Zeichenfolge, die mit dem Namen des Seitenblobs.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-717">A string containing the name of the page blob.</span></span></param>
        <param name="snapshotTime"><span data-ttu-id="5d9cd-718">Ein <see cref="T:System.DateTimeOffset" /> den Momentaufnahme-Zeitstempel angeben, wenn das Blob eine Momentaufnahme ist.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-718">A <see cref="T:System.DateTimeOffset" /> specifying the snapshot timestamp, if the blob is a snapshot.</span></span></param>
        <summary>
            <span data-ttu-id="5d9cd-719">Gibt einen Verweis auf ein Seitenblob in diesem virtuellen Verzeichnis zurück.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-719">Returns a reference to a page blob in this virtual directory.</span></span>
            </summary>
        <returns><span data-ttu-id="5d9cd-720">Ein <see cref="T:Microsoft.WindowsAzure.Storage.Blob.CloudPageBlob" />-Objekt.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-720">A <see cref="T:Microsoft.WindowsAzure.Storage.Blob.CloudPageBlob" /> object.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetPermissions">
      <MemberSignature Language="C#" Value="public virtual Microsoft.WindowsAzure.Storage.Blob.BlobContainerPermissions GetPermissions (Microsoft.WindowsAzure.Storage.AccessCondition accessCondition = null, Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options = null, Microsoft.WindowsAzure.Storage.OperationContext operationContext = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.WindowsAzure.Storage.Blob.BlobContainerPermissions GetPermissions(class Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, class Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlobContainer.GetPermissions(Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="abstract member GetPermissions : Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; Microsoft.WindowsAzure.Storage.Blob.BlobContainerPermissions&#xA;override this.GetPermissions : Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; Microsoft.WindowsAzure.Storage.Blob.BlobContainerPermissions" Usage="cloudBlobContainer.GetPermissions (accessCondition, options, operationContext)" />
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
        <ReturnType>Microsoft.WindowsAzure.Storage.Blob.BlobContainerPermissions</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="accessCondition" Type="Microsoft.WindowsAzure.Storage.AccessCondition" />
        <Parameter Name="options" Type="Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="accessCondition"><span data-ttu-id="5d9cd-721">Ein <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> -Objekt, das die Bedingung, die erfüllt sein müssen, damit die Anforderung darstellt, um den Vorgang fortzusetzen.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-721">An <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> object that represents the condition that must be met in order for the request to proceed.</span></span> <span data-ttu-id="5d9cd-722">Wenn <c>null</c>, keine Bedingung verwendet.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-722">If <c>null</c>, no condition is used.</span></span></param>
        <param name="options"><span data-ttu-id="5d9cd-723">Ein <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" /> -Objekt, das zusätzliche Optionen für die Anforderung angibt.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-723">A <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" /> object that specifies additional options for the request.</span></span> <span data-ttu-id="5d9cd-724">Wenn <c>null</c>, Standardoptionen gelten für die Anforderung.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-724">If <c>null</c>, default options are applied to the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="5d9cd-725">Ein <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> -Objekt, das den Kontext für den aktuellen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-725">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <summary>
            <span data-ttu-id="5d9cd-726">Ruft die berechtigungseinstellungen für den Container ab.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-726">Gets the permissions settings for the container.</span></span>
            </summary>
        <returns><span data-ttu-id="5d9cd-727">Die Berechtigungen des Containers.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-727">The container's permissions.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetPermissionsAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Blob.BlobContainerPermissions&gt; GetPermissionsAsync ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.WindowsAzure.Storage.Blob.BlobContainerPermissions&gt; GetPermissionsAsync() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlobContainer.GetPermissionsAsync" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function GetPermissionsAsync () As Task(Of BlobContainerPermissions)" />
      <MemberSignature Language="F#" Value="abstract member GetPermissionsAsync : unit -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Blob.BlobContainerPermissions&gt;&#xA;override this.GetPermissionsAsync : unit -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Blob.BlobContainerPermissions&gt;" Usage="cloudBlobContainer.GetPermissionsAsync " />
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
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Blob.BlobContainerPermissions&gt;</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="5d9cd-728">Initiiert einen asynchronen Vorgang, der die berechtigungseinstellungen für den Container abgerufen wird.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-728">Initiates an asynchronous operation that gets the permissions settings for the container.</span></span>
            </summary>
        <returns><span data-ttu-id="5d9cd-729">Ein <see cref="T:System.Threading.Tasks.Task`1" />-Objekt, das den asynchronen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-729">A <see cref="T:System.Threading.Tasks.Task`1" /> object that represents the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetPermissionsAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Blob.BlobContainerPermissions&gt; GetPermissionsAsync (System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.WindowsAzure.Storage.Blob.BlobContainerPermissions&gt; GetPermissionsAsync(valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlobContainer.GetPermissionsAsync(System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetPermissionsAsync : System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Blob.BlobContainerPermissions&gt;&#xA;override this.GetPermissionsAsync : System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Blob.BlobContainerPermissions&gt;" Usage="cloudBlobContainer.GetPermissionsAsync cancellationToken" />
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
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Blob.BlobContainerPermissions&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="cancellationToken"><span data-ttu-id="5d9cd-730">Ein <see cref="T:System.Threading.CancellationToken" />, das beim Warten auf den Abschluss einer Aufgabe überwacht werden soll.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-730">A <see cref="T:System.Threading.CancellationToken" /> to observe while waiting for a task to complete.</span></span></param>
        <summary>
            <span data-ttu-id="5d9cd-731">Initiiert einen asynchronen Vorgang, der die berechtigungseinstellungen für den Container abgerufen wird.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-731">Initiates an asynchronous operation that gets the permissions settings for the container.</span></span>
            </summary>
        <returns><span data-ttu-id="5d9cd-732">Ein <see cref="T:System.Threading.Tasks.Task`1" />-Objekt, das den asynchronen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-732">A <see cref="T:System.Threading.Tasks.Task`1" /> object that represents the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetPermissionsAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Blob.BlobContainerPermissions&gt; GetPermissionsAsync (Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, Microsoft.WindowsAzure.Storage.OperationContext operationContext);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.WindowsAzure.Storage.Blob.BlobContainerPermissions&gt; GetPermissionsAsync(class Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, class Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlobContainer.GetPermissionsAsync(Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="abstract member GetPermissionsAsync : Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Blob.BlobContainerPermissions&gt;&#xA;override this.GetPermissionsAsync : Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Blob.BlobContainerPermissions&gt;" Usage="cloudBlobContainer.GetPermissionsAsync (accessCondition, options, operationContext)" />
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
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Blob.BlobContainerPermissions&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="accessCondition" Type="Microsoft.WindowsAzure.Storage.AccessCondition" />
        <Parameter Name="options" Type="Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="accessCondition"><span data-ttu-id="5d9cd-733">Ein <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> -Objekt, das die Bedingung, die erfüllt sein müssen, damit die Anforderung darstellt, um den Vorgang fortzusetzen.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-733">An <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> object that represents the condition that must be met in order for the request to proceed.</span></span> <span data-ttu-id="5d9cd-734">Wenn <c>null</c>, keine Bedingung verwendet.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-734">If <c>null</c>, no condition is used.</span></span></param>
        <param name="options"><span data-ttu-id="5d9cd-735">Ein <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" /> -Objekt, das zusätzliche Optionen für die Anforderung angibt.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-735">A <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" /> object that specifies additional options for the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="5d9cd-736">Ein <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> -Objekt, das den Kontext für den aktuellen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-736">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <summary>
            <span data-ttu-id="5d9cd-737">Initiiert einen asynchronen Vorgang, der die berechtigungseinstellungen für den Container abgerufen wird.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-737">Initiates an asynchronous operation that gets the permissions settings for the container.</span></span>
            </summary>
        <returns><span data-ttu-id="5d9cd-738">Ein <see cref="T:System.Threading.Tasks.Task`1" />-Objekt, das den asynchronen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-738">A <see cref="T:System.Threading.Tasks.Task`1" /> object that represents the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetPermissionsAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Blob.BlobContainerPermissions&gt; GetPermissionsAsync (Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, Microsoft.WindowsAzure.Storage.OperationContext operationContext, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.WindowsAzure.Storage.Blob.BlobContainerPermissions&gt; GetPermissionsAsync(class Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, class Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, class Microsoft.WindowsAzure.Storage.OperationContext operationContext, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlobContainer.GetPermissionsAsync(Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetPermissionsAsync : Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Blob.BlobContainerPermissions&gt;&#xA;override this.GetPermissionsAsync : Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Blob.BlobContainerPermissions&gt;" Usage="cloudBlobContainer.GetPermissionsAsync (accessCondition, options, operationContext, cancellationToken)" />
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
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Blob.BlobContainerPermissions&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="accessCondition" Type="Microsoft.WindowsAzure.Storage.AccessCondition" />
        <Parameter Name="options" Type="Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="accessCondition"><span data-ttu-id="5d9cd-739">Ein <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> -Objekt, das die Bedingung, die erfüllt sein müssen, damit die Anforderung darstellt, um den Vorgang fortzusetzen.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-739">An <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> object that represents the condition that must be met in order for the request to proceed.</span></span> <span data-ttu-id="5d9cd-740">Wenn <c>null</c>, keine Bedingung verwendet.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-740">If <c>null</c>, no condition is used.</span></span></param>
        <param name="options"><span data-ttu-id="5d9cd-741">Ein <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" /> -Objekt, das zusätzliche Optionen für die Anforderung angibt.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-741">A <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" /> object that specifies additional options for the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="5d9cd-742">Ein <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> -Objekt, das den Kontext für den aktuellen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-742">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="5d9cd-743">Ein <see cref="T:System.Threading.CancellationToken" />, das beim Warten auf den Abschluss einer Aufgabe überwacht werden soll.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-743">A <see cref="T:System.Threading.CancellationToken" /> to observe while waiting for a task to complete.</span></span></param>
        <summary>
            <span data-ttu-id="5d9cd-744">Initiiert einen asynchronen Vorgang, der die berechtigungseinstellungen für den Container abgerufen wird.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-744">Initiates an asynchronous operation that gets the permissions settings for the container.</span></span>
            </summary>
        <returns><span data-ttu-id="5d9cd-745">Ein <see cref="T:System.Threading.Tasks.Task`1" />-Objekt, das den asynchronen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-745">A <see cref="T:System.Threading.Tasks.Task`1" /> object that represents the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetSharedAccessSignature">
      <MemberSignature Language="C#" Value="public string GetSharedAccessSignature (Microsoft.WindowsAzure.Storage.Blob.SharedAccessBlobPolicy policy);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance string GetSharedAccessSignature(class Microsoft.WindowsAzure.Storage.Blob.SharedAccessBlobPolicy policy) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlobContainer.GetSharedAccessSignature(Microsoft.WindowsAzure.Storage.Blob.SharedAccessBlobPolicy)" />
      <MemberSignature Language="VB.NET" Value="Public Function GetSharedAccessSignature (policy As SharedAccessBlobPolicy) As String" />
      <MemberSignature Language="F#" Value="member this.GetSharedAccessSignature : Microsoft.WindowsAzure.Storage.Blob.SharedAccessBlobPolicy -&gt; string" Usage="cloudBlobContainer.GetSharedAccessSignature policy" />
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
        <Parameter Name="policy" Type="Microsoft.WindowsAzure.Storage.Blob.SharedAccessBlobPolicy" />
      </Parameters>
      <Docs>
        <param name="policy"><span data-ttu-id="5d9cd-746">Ein <see cref="T:Microsoft.WindowsAzure.Storage.Blob.SharedAccessBlobPolicy" /> Objekt, das die Zugriffsrichtlinie für die SAS angibt.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-746">A <see cref="T:Microsoft.WindowsAzure.Storage.Blob.SharedAccessBlobPolicy" /> object specifying the access policy for the shared access signature.</span></span></param>
        <summary>
            <span data-ttu-id="5d9cd-747">Gibt eine SAS für den Container zurück.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-747">Returns a shared access signature for the container.</span></span>
            </summary>
        <returns><span data-ttu-id="5d9cd-748">Eine SAS als URI-Abfragezeichenfolge.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-748">A shared access signature, as a URI query string.</span></span></returns>
        <remarks><span data-ttu-id="5d9cd-749">Die zurückgegebene Abfragezeichenfolge enthält das vorangestellte Fragezeichen.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-749">The query string returned includes the leading question mark.</span></span></remarks>
      </Docs>
    </Member>
    <Member MemberName="GetSharedAccessSignature">
      <MemberSignature Language="C#" Value="public string GetSharedAccessSignature (Microsoft.WindowsAzure.Storage.Blob.SharedAccessBlobPolicy policy, string groupPolicyIdentifier);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance string GetSharedAccessSignature(class Microsoft.WindowsAzure.Storage.Blob.SharedAccessBlobPolicy policy, string groupPolicyIdentifier) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlobContainer.GetSharedAccessSignature(Microsoft.WindowsAzure.Storage.Blob.SharedAccessBlobPolicy,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function GetSharedAccessSignature (policy As SharedAccessBlobPolicy, groupPolicyIdentifier As String) As String" />
      <MemberSignature Language="F#" Value="member this.GetSharedAccessSignature : Microsoft.WindowsAzure.Storage.Blob.SharedAccessBlobPolicy * string -&gt; string" Usage="cloudBlobContainer.GetSharedAccessSignature (policy, groupPolicyIdentifier)" />
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
        <Parameter Name="policy" Type="Microsoft.WindowsAzure.Storage.Blob.SharedAccessBlobPolicy" />
        <Parameter Name="groupPolicyIdentifier" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="policy"><span data-ttu-id="5d9cd-750">Ein <see cref="T:Microsoft.WindowsAzure.Storage.Blob.SharedAccessBlobPolicy" /> Objekt, das die Zugriffsrichtlinie für die SAS angibt.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-750">A <see cref="T:Microsoft.WindowsAzure.Storage.Blob.SharedAccessBlobPolicy" /> object specifying the access policy for the shared access signature.</span></span></param>
        <param name="groupPolicyIdentifier"><span data-ttu-id="5d9cd-751">Eine Zugriffsrichtlinie auf Containerebene.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-751">A container-level access policy.</span></span></param>
        <summary>
            <span data-ttu-id="5d9cd-752">Gibt eine SAS für den Container zurück.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-752">Returns a shared access signature for the container.</span></span>
            </summary>
        <returns><span data-ttu-id="5d9cd-753">Eine SAS als URI-Abfragezeichenfolge.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-753">A shared access signature, as a URI query string.</span></span></returns>
        <remarks><span data-ttu-id="5d9cd-754">Die zurückgegebene Abfragezeichenfolge enthält das vorangestellte Fragezeichen.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-754">The query string returned includes the leading question mark.</span></span></remarks>
      </Docs>
    </Member>
    <Member MemberName="GetSharedAccessSignature">
      <MemberSignature Language="C#" Value="public string GetSharedAccessSignature (Microsoft.WindowsAzure.Storage.Blob.SharedAccessBlobPolicy policy, string groupPolicyIdentifier, Nullable&lt;Microsoft.WindowsAzure.Storage.SharedAccessProtocol&gt; protocols, Microsoft.WindowsAzure.Storage.IPAddressOrRange ipAddressOrRange);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance string GetSharedAccessSignature(class Microsoft.WindowsAzure.Storage.Blob.SharedAccessBlobPolicy policy, string groupPolicyIdentifier, valuetype System.Nullable`1&lt;valuetype Microsoft.WindowsAzure.Storage.SharedAccessProtocol&gt; protocols, class Microsoft.WindowsAzure.Storage.IPAddressOrRange ipAddressOrRange) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlobContainer.GetSharedAccessSignature(Microsoft.WindowsAzure.Storage.Blob.SharedAccessBlobPolicy,System.String,System.Nullable{Microsoft.WindowsAzure.Storage.SharedAccessProtocol},Microsoft.WindowsAzure.Storage.IPAddressOrRange)" />
      <MemberSignature Language="F#" Value="member this.GetSharedAccessSignature : Microsoft.WindowsAzure.Storage.Blob.SharedAccessBlobPolicy * string * Nullable&lt;Microsoft.WindowsAzure.Storage.SharedAccessProtocol&gt; * Microsoft.WindowsAzure.Storage.IPAddressOrRange -&gt; string" Usage="cloudBlobContainer.GetSharedAccessSignature (policy, groupPolicyIdentifier, protocols, ipAddressOrRange)" />
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
        <Parameter Name="policy" Type="Microsoft.WindowsAzure.Storage.Blob.SharedAccessBlobPolicy" />
        <Parameter Name="groupPolicyIdentifier" Type="System.String" />
        <Parameter Name="protocols" Type="System.Nullable&lt;Microsoft.WindowsAzure.Storage.SharedAccessProtocol&gt;" />
        <Parameter Name="ipAddressOrRange" Type="Microsoft.WindowsAzure.Storage.IPAddressOrRange" />
      </Parameters>
      <Docs>
        <param name="policy"><span data-ttu-id="5d9cd-755">Ein <see cref="T:Microsoft.WindowsAzure.Storage.Blob.SharedAccessBlobPolicy" /> Objekt, das die Zugriffsrichtlinie für die SAS angibt.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-755">A <see cref="T:Microsoft.WindowsAzure.Storage.Blob.SharedAccessBlobPolicy" /> object specifying the access policy for the shared access signature.</span></span></param>
        <param name="groupPolicyIdentifier"><span data-ttu-id="5d9cd-756">Eine Zugriffsrichtlinie auf Containerebene.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-756">A container-level access policy.</span></span></param>
        <param name="protocols"><span data-ttu-id="5d9cd-757">Die zulässige Protokolle (nur Https oder http und Https).</span><span class="sxs-lookup"><span data-stu-id="5d9cd-757">The allowed protocols (https only, or http and https).</span></span> <span data-ttu-id="5d9cd-758">NULL, wenn Sie nicht Protokoll beschränken möchten.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-758">Null if you don't want to restrict protocol.</span></span></param>
        <param name="ipAddressOrRange"><span data-ttu-id="5d9cd-759">Die zulässigen IP-Adresse oder IP-Adressbereich.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-759">The allowed IP address or IP address range.</span></span> <span data-ttu-id="5d9cd-760">NULL, wenn Sie einschränken möchten, nicht basierend auf IP-Adresse.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-760">Null if you don't want to restrict based on IP address.</span></span></param>
        <summary>
            <span data-ttu-id="5d9cd-761">Gibt eine SAS für den Container zurück.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-761">Returns a shared access signature for the container.</span></span>
            </summary>
        <returns><span data-ttu-id="5d9cd-762">Eine SAS als URI-Abfragezeichenfolge.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-762">A shared access signature, as a URI query string.</span></span></returns>
        <remarks><span data-ttu-id="5d9cd-763">Die zurückgegebene Abfragezeichenfolge enthält das vorangestellte Fragezeichen.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-763">The query string returned includes the leading question mark.</span></span></remarks>
      </Docs>
    </Member>
    <Member MemberName="ListBlobs">
      <MemberSignature Language="C#" Value="public virtual System.Collections.Generic.IEnumerable&lt;Microsoft.WindowsAzure.Storage.Blob.IListBlobItem&gt; ListBlobs (string prefix = null, bool useFlatBlobListing = false, Microsoft.WindowsAzure.Storage.Blob.BlobListingDetails blobListingDetails = Microsoft.WindowsAzure.Storage.Blob.BlobListingDetails.None, Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options = null, Microsoft.WindowsAzure.Storage.OperationContext operationContext = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.WindowsAzure.Storage.Blob.IListBlobItem&gt; ListBlobs(string prefix, bool useFlatBlobListing, valuetype Microsoft.WindowsAzure.Storage.Blob.BlobListingDetails blobListingDetails, class Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlobContainer.ListBlobs(System.String,System.Boolean,Microsoft.WindowsAzure.Storage.Blob.BlobListingDetails,Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="abstract member ListBlobs : string * bool * Microsoft.WindowsAzure.Storage.Blob.BlobListingDetails * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; seq&lt;Microsoft.WindowsAzure.Storage.Blob.IListBlobItem&gt;&#xA;override this.ListBlobs : string * bool * Microsoft.WindowsAzure.Storage.Blob.BlobListingDetails * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; seq&lt;Microsoft.WindowsAzure.Storage.Blob.IListBlobItem&gt;" Usage="cloudBlobContainer.ListBlobs (prefix, useFlatBlobListing, blobListingDetails, options, operationContext)" />
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
        <ReturnType>System.Collections.Generic.IEnumerable&lt;Microsoft.WindowsAzure.Storage.Blob.IListBlobItem&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="prefix" Type="System.String" />
        <Parameter Name="useFlatBlobListing" Type="System.Boolean" />
        <Parameter Name="blobListingDetails" Type="Microsoft.WindowsAzure.Storage.Blob.BlobListingDetails" />
        <Parameter Name="options" Type="Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="prefix"><span data-ttu-id="5d9cd-764">Eine Zeichenfolge mit dem Blob-Namenspräfix.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-764">A string containing the blob name prefix.</span></span></param>
        <param name="useFlatBlobListing"><span data-ttu-id="5d9cd-765">Ein boolescher Wert, der angibt, ob Blobs in einer flachen Liste oder hierarchisch nach virtuellem Verzeichnis aufgelistet.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-765">A boolean value that specifies whether to list blobs in a flat listing, or whether to list blobs hierarchically, by virtual directory.</span></span></param>
        <param name="blobListingDetails"><span data-ttu-id="5d9cd-766">Ein <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobListingDetails" /> -Enumeration, die in die Auflistung einzuschließenden Elemente beschreibt.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-766">A <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobListingDetails" /> enumeration describing which items to include in the listing.</span></span></param>
        <param name="options"><span data-ttu-id="5d9cd-767">Ein <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" /> -Objekt, das zusätzliche Optionen für die Anforderung angibt.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-767">A <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" /> object that specifies additional options for the request.</span></span> <span data-ttu-id="5d9cd-768">Wenn <c>null</c>, Standardoptionen gelten für die Anforderung.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-768">If <c>null</c>, default options are applied to the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="5d9cd-769">Ein <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> -Objekt, das den Kontext für den aktuellen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-769">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <summary>
            <span data-ttu-id="5d9cd-770">Gibt eine aufzählbare Auflistung von Blobs im Container, die verzögert abgerufen werden.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-770">Returns an enumerable collection of the blobs in the container that are retrieved lazily.</span></span>
            </summary>
        <returns><span data-ttu-id="5d9cd-771">Eine aufzählbare Auflistung von Objekten, implementieren <see cref="T:Microsoft.WindowsAzure.Storage.Blob.IListBlobItem" /> und verzögert abgerufen werden.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-771">An enumerable collection of objects that implement <see cref="T:Microsoft.WindowsAzure.Storage.Blob.IListBlobItem" /> and are retrieved lazily.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListBlobsSegmented">
      <MemberSignature Language="C#" Value="public virtual Microsoft.WindowsAzure.Storage.Blob.BlobResultSegment ListBlobsSegmented (Microsoft.WindowsAzure.Storage.Blob.BlobContinuationToken currentToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.WindowsAzure.Storage.Blob.BlobResultSegment ListBlobsSegmented(class Microsoft.WindowsAzure.Storage.Blob.BlobContinuationToken currentToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlobContainer.ListBlobsSegmented(Microsoft.WindowsAzure.Storage.Blob.BlobContinuationToken)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function ListBlobsSegmented (currentToken As BlobContinuationToken) As BlobResultSegment" />
      <MemberSignature Language="F#" Value="abstract member ListBlobsSegmented : Microsoft.WindowsAzure.Storage.Blob.BlobContinuationToken -&gt; Microsoft.WindowsAzure.Storage.Blob.BlobResultSegment&#xA;override this.ListBlobsSegmented : Microsoft.WindowsAzure.Storage.Blob.BlobContinuationToken -&gt; Microsoft.WindowsAzure.Storage.Blob.BlobResultSegment" Usage="cloudBlobContainer.ListBlobsSegmented currentToken" />
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
        <ReturnType>Microsoft.WindowsAzure.Storage.Blob.BlobResultSegment</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="currentToken" Type="Microsoft.WindowsAzure.Storage.Blob.BlobContinuationToken" />
      </Parameters>
      <Docs>
        <param name="currentToken"><span data-ttu-id="5d9cd-772">Eine von einem vorherigen Auflistungsvorgang zurückgegebenes Fortsetzungstoken.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-772">A continuation token returned by a previous listing operation.</span></span></param>
        <summary>
            <span data-ttu-id="5d9cd-773">Gibt ein ergebnissegment mit einer Auflistung von Blob-Elemente im Container zurück.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-773">Returns a result segment containing a collection of blob items in the container.</span></span>
            </summary>
        <returns><span data-ttu-id="5d9cd-774">Ein ergebnissegment mit Objekten implementiert, <see cref="T:Microsoft.WindowsAzure.Storage.Blob.IListBlobItem" />.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-774">A result segment containing objects that implement <see cref="T:Microsoft.WindowsAzure.Storage.Blob.IListBlobItem" />.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListBlobsSegmented">
      <MemberSignature Language="C#" Value="public virtual Microsoft.WindowsAzure.Storage.Blob.BlobResultSegment ListBlobsSegmented (string prefix, Microsoft.WindowsAzure.Storage.Blob.BlobContinuationToken currentToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.WindowsAzure.Storage.Blob.BlobResultSegment ListBlobsSegmented(string prefix, class Microsoft.WindowsAzure.Storage.Blob.BlobContinuationToken currentToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlobContainer.ListBlobsSegmented(System.String,Microsoft.WindowsAzure.Storage.Blob.BlobContinuationToken)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function ListBlobsSegmented (prefix As String, currentToken As BlobContinuationToken) As BlobResultSegment" />
      <MemberSignature Language="F#" Value="abstract member ListBlobsSegmented : string * Microsoft.WindowsAzure.Storage.Blob.BlobContinuationToken -&gt; Microsoft.WindowsAzure.Storage.Blob.BlobResultSegment&#xA;override this.ListBlobsSegmented : string * Microsoft.WindowsAzure.Storage.Blob.BlobContinuationToken -&gt; Microsoft.WindowsAzure.Storage.Blob.BlobResultSegment" Usage="cloudBlobContainer.ListBlobsSegmented (prefix, currentToken)" />
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
        <ReturnType>Microsoft.WindowsAzure.Storage.Blob.BlobResultSegment</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="prefix" Type="System.String" />
        <Parameter Name="currentToken" Type="Microsoft.WindowsAzure.Storage.Blob.BlobContinuationToken" />
      </Parameters>
      <Docs>
        <param name="prefix"><span data-ttu-id="5d9cd-775">Eine Zeichenfolge mit dem Blob-Namenspräfix.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-775">A string containing the blob name prefix.</span></span></param>
        <param name="currentToken"><span data-ttu-id="5d9cd-776">Eine von einem vorherigen Auflistungsvorgang zurückgegebenes Fortsetzungstoken.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-776">A continuation token returned by a previous listing operation.</span></span></param>
        <summary>
            <span data-ttu-id="5d9cd-777">Gibt ein ergebnissegment mit einer Auflistung von Blob-Elemente im Container zurück.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-777">Returns a result segment containing a collection of blob items in the container.</span></span>
            </summary>
        <returns><span data-ttu-id="5d9cd-778">Ein ergebnissegment mit Objekten implementiert, <see cref="T:Microsoft.WindowsAzure.Storage.Blob.IListBlobItem" />.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-778">A result segment containing objects that implement <see cref="T:Microsoft.WindowsAzure.Storage.Blob.IListBlobItem" />.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListBlobsSegmented">
      <MemberSignature Language="C#" Value="public virtual Microsoft.WindowsAzure.Storage.Blob.BlobResultSegment ListBlobsSegmented (string prefix, bool useFlatBlobListing, Microsoft.WindowsAzure.Storage.Blob.BlobListingDetails blobListingDetails, Nullable&lt;int&gt; maxResults, Microsoft.WindowsAzure.Storage.Blob.BlobContinuationToken currentToken, Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, Microsoft.WindowsAzure.Storage.OperationContext operationContext);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.WindowsAzure.Storage.Blob.BlobResultSegment ListBlobsSegmented(string prefix, bool useFlatBlobListing, valuetype Microsoft.WindowsAzure.Storage.Blob.BlobListingDetails blobListingDetails, valuetype System.Nullable`1&lt;int32&gt; maxResults, class Microsoft.WindowsAzure.Storage.Blob.BlobContinuationToken currentToken, class Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlobContainer.ListBlobsSegmented(System.String,System.Boolean,Microsoft.WindowsAzure.Storage.Blob.BlobListingDetails,System.Nullable{System.Int32},Microsoft.WindowsAzure.Storage.Blob.BlobContinuationToken,Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="abstract member ListBlobsSegmented : string * bool * Microsoft.WindowsAzure.Storage.Blob.BlobListingDetails * Nullable&lt;int&gt; * Microsoft.WindowsAzure.Storage.Blob.BlobContinuationToken * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; Microsoft.WindowsAzure.Storage.Blob.BlobResultSegment&#xA;override this.ListBlobsSegmented : string * bool * Microsoft.WindowsAzure.Storage.Blob.BlobListingDetails * Nullable&lt;int&gt; * Microsoft.WindowsAzure.Storage.Blob.BlobContinuationToken * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; Microsoft.WindowsAzure.Storage.Blob.BlobResultSegment" Usage="cloudBlobContainer.ListBlobsSegmented (prefix, useFlatBlobListing, blobListingDetails, maxResults, currentToken, options, operationContext)" />
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
        <ReturnType>Microsoft.WindowsAzure.Storage.Blob.BlobResultSegment</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="prefix" Type="System.String" />
        <Parameter Name="useFlatBlobListing" Type="System.Boolean" />
        <Parameter Name="blobListingDetails" Type="Microsoft.WindowsAzure.Storage.Blob.BlobListingDetails" />
        <Parameter Name="maxResults" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="currentToken" Type="Microsoft.WindowsAzure.Storage.Blob.BlobContinuationToken" />
        <Parameter Name="options" Type="Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="prefix"><span data-ttu-id="5d9cd-779">Eine Zeichenfolge mit dem Blob-Namenspräfix.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-779">A string containing the blob name prefix.</span></span></param>
        <param name="useFlatBlobListing"><span data-ttu-id="5d9cd-780">Ein boolescher Wert, der angibt, ob Blobs in einer flachen Liste oder hierarchisch nach virtuellem Verzeichnis aufgelistet.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-780">A boolean value that specifies whether to list blobs in a flat listing, or whether to list blobs hierarchically, by virtual directory.</span></span></param>
        <param name="blobListingDetails"><span data-ttu-id="5d9cd-781">Ein <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobListingDetails" /> -Enumeration, die in die Auflistung einzuschließenden Elemente beschreibt.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-781">A <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobListingDetails" /> enumeration describing which items to include in the listing.</span></span></param>
        <param name="maxResults"><span data-ttu-id="5d9cd-782">Ein nicht negativer ganzzahliger Wert, der die maximale Anzahl von gleichzeitig pro Vorgang gilt ein Grenzwert von 5000 zurückzugebenden Ergebnisse angibt.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-782">A non-negative integer value that indicates the maximum number of results to be returned at a time, up to the per-operation limit of 5000.</span></span> <span data-ttu-id="5d9cd-783">Wenn dieser Wert ist <c>null</c>, die maximale zulässige Anzahl von Ergebnissen wird sein (bis 5.000) zurückgegeben.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-783">If this value is <c>null</c>, the maximum possible number of results will be returned, up to 5000.</span></span></param>
        <param name="currentToken"><span data-ttu-id="5d9cd-784">Eine von einem vorherigen Auflistungsvorgang zurückgegebenes Fortsetzungstoken.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-784">A continuation token returned by a previous listing operation.</span></span></param>
        <param name="options"><span data-ttu-id="5d9cd-785">Ein <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" /> -Objekt, das zusätzliche Optionen für die Anforderung angibt.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-785">A <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" /> object that specifies additional options for the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="5d9cd-786">Ein <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> -Objekt, das den Kontext für den aktuellen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-786">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <summary>
            <span data-ttu-id="5d9cd-787">Gibt ein ergebnissegment mit einer Auflistung von Blob-Elemente im Container zurück.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-787">Returns a result segment containing a collection of blob items in the container.</span></span>
            </summary>
        <returns><span data-ttu-id="5d9cd-788">Ein ergebnissegment mit Objekten implementiert, <see cref="T:Microsoft.WindowsAzure.Storage.Blob.IListBlobItem" />.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-788">A result segment containing objects that implement <see cref="T:Microsoft.WindowsAzure.Storage.Blob.IListBlobItem" />.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListBlobsSegmentedAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Blob.BlobResultSegment&gt; ListBlobsSegmentedAsync (Microsoft.WindowsAzure.Storage.Blob.BlobContinuationToken currentToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.WindowsAzure.Storage.Blob.BlobResultSegment&gt; ListBlobsSegmentedAsync(class Microsoft.WindowsAzure.Storage.Blob.BlobContinuationToken currentToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlobContainer.ListBlobsSegmentedAsync(Microsoft.WindowsAzure.Storage.Blob.BlobContinuationToken)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function ListBlobsSegmentedAsync (currentToken As BlobContinuationToken) As Task(Of BlobResultSegment)" />
      <MemberSignature Language="F#" Value="abstract member ListBlobsSegmentedAsync : Microsoft.WindowsAzure.Storage.Blob.BlobContinuationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Blob.BlobResultSegment&gt;&#xA;override this.ListBlobsSegmentedAsync : Microsoft.WindowsAzure.Storage.Blob.BlobContinuationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Blob.BlobResultSegment&gt;" Usage="cloudBlobContainer.ListBlobsSegmentedAsync currentToken" />
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
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Blob.BlobResultSegment&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="currentToken" Type="Microsoft.WindowsAzure.Storage.Blob.BlobContinuationToken" />
      </Parameters>
      <Docs>
        <param name="currentToken"><span data-ttu-id="5d9cd-789">Eine von einem vorherigen Auflistungsvorgang zurückgegebenes Fortsetzungstoken.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-789">A continuation token returned by a previous listing operation.</span></span></param>
        <summary>
            <span data-ttu-id="5d9cd-790">Initiiert einen asynchronen Vorgang, der ein ergebnissegment mit einer Auflistung von Blob-Elemente im Container zurückgibt.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-790">Initiates an asynchronous operation that returns a result segment containing a collection of blob items in the container.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListBlobsSegmentedAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Blob.BlobResultSegment&gt; ListBlobsSegmentedAsync (Microsoft.WindowsAzure.Storage.Blob.BlobContinuationToken currentToken, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.WindowsAzure.Storage.Blob.BlobResultSegment&gt; ListBlobsSegmentedAsync(class Microsoft.WindowsAzure.Storage.Blob.BlobContinuationToken currentToken, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlobContainer.ListBlobsSegmentedAsync(Microsoft.WindowsAzure.Storage.Blob.BlobContinuationToken,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListBlobsSegmentedAsync : Microsoft.WindowsAzure.Storage.Blob.BlobContinuationToken * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Blob.BlobResultSegment&gt;&#xA;override this.ListBlobsSegmentedAsync : Microsoft.WindowsAzure.Storage.Blob.BlobContinuationToken * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Blob.BlobResultSegment&gt;" Usage="cloudBlobContainer.ListBlobsSegmentedAsync (currentToken, cancellationToken)" />
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
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Blob.BlobResultSegment&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="currentToken" Type="Microsoft.WindowsAzure.Storage.Blob.BlobContinuationToken" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="currentToken"><span data-ttu-id="5d9cd-791">Eine von einem vorherigen Auflistungsvorgang zurückgegebenes Fortsetzungstoken.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-791">A continuation token returned by a previous listing operation.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="5d9cd-792">Ein <see cref="T:System.Threading.CancellationToken" />, das beim Warten auf den Abschluss einer Aufgabe überwacht werden soll.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-792">A <see cref="T:System.Threading.CancellationToken" /> to observe while waiting for a task to complete.</span></span></param>
        <summary>
            <span data-ttu-id="5d9cd-793">Initiiert einen asynchronen Vorgang, der ein ergebnissegment mit einer Auflistung von Blob-Elemente im Container zurückgibt.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-793">Initiates an asynchronous operation that returns a result segment containing a collection of blob items in the container.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListBlobsSegmentedAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Blob.BlobResultSegment&gt; ListBlobsSegmentedAsync (string prefix, Microsoft.WindowsAzure.Storage.Blob.BlobContinuationToken currentToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.WindowsAzure.Storage.Blob.BlobResultSegment&gt; ListBlobsSegmentedAsync(string prefix, class Microsoft.WindowsAzure.Storage.Blob.BlobContinuationToken currentToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlobContainer.ListBlobsSegmentedAsync(System.String,Microsoft.WindowsAzure.Storage.Blob.BlobContinuationToken)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function ListBlobsSegmentedAsync (prefix As String, currentToken As BlobContinuationToken) As Task(Of BlobResultSegment)" />
      <MemberSignature Language="F#" Value="abstract member ListBlobsSegmentedAsync : string * Microsoft.WindowsAzure.Storage.Blob.BlobContinuationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Blob.BlobResultSegment&gt;&#xA;override this.ListBlobsSegmentedAsync : string * Microsoft.WindowsAzure.Storage.Blob.BlobContinuationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Blob.BlobResultSegment&gt;" Usage="cloudBlobContainer.ListBlobsSegmentedAsync (prefix, currentToken)" />
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
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Blob.BlobResultSegment&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="prefix" Type="System.String" />
        <Parameter Name="currentToken" Type="Microsoft.WindowsAzure.Storage.Blob.BlobContinuationToken" />
      </Parameters>
      <Docs>
        <param name="prefix"><span data-ttu-id="5d9cd-794">Eine Zeichenfolge mit dem Blob-Namenspräfix.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-794">A string containing the blob name prefix.</span></span></param>
        <param name="currentToken"><span data-ttu-id="5d9cd-795">Eine von einem vorherigen Auflistungsvorgang zurückgegebenes Fortsetzungstoken.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-795">A continuation token returned by a previous listing operation.</span></span></param>
        <summary>
            <span data-ttu-id="5d9cd-796">Initiiert einen asynchronen Vorgang, der ein ergebnissegment mit einer Auflistung von Blob-Elemente im Container zurückgibt.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-796">Initiates an asynchronous operation that returns a result segment containing a collection of blob items in the container.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListBlobsSegmentedAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Blob.BlobResultSegment&gt; ListBlobsSegmentedAsync (string prefix, Microsoft.WindowsAzure.Storage.Blob.BlobContinuationToken currentToken, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.WindowsAzure.Storage.Blob.BlobResultSegment&gt; ListBlobsSegmentedAsync(string prefix, class Microsoft.WindowsAzure.Storage.Blob.BlobContinuationToken currentToken, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlobContainer.ListBlobsSegmentedAsync(System.String,Microsoft.WindowsAzure.Storage.Blob.BlobContinuationToken,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListBlobsSegmentedAsync : string * Microsoft.WindowsAzure.Storage.Blob.BlobContinuationToken * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Blob.BlobResultSegment&gt;&#xA;override this.ListBlobsSegmentedAsync : string * Microsoft.WindowsAzure.Storage.Blob.BlobContinuationToken * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Blob.BlobResultSegment&gt;" Usage="cloudBlobContainer.ListBlobsSegmentedAsync (prefix, currentToken, cancellationToken)" />
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
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Blob.BlobResultSegment&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="prefix" Type="System.String" />
        <Parameter Name="currentToken" Type="Microsoft.WindowsAzure.Storage.Blob.BlobContinuationToken" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="prefix"><span data-ttu-id="5d9cd-797">Eine Zeichenfolge mit dem Blob-Namenspräfix.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-797">A string containing the blob name prefix.</span></span></param>
        <param name="currentToken"><span data-ttu-id="5d9cd-798">Eine von einem vorherigen Auflistungsvorgang zurückgegebenes Fortsetzungstoken.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-798">A continuation token returned by a previous listing operation.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="5d9cd-799">Ein <see cref="T:System.Threading.CancellationToken" />, das beim Warten auf den Abschluss einer Aufgabe überwacht werden soll.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-799">A <see cref="T:System.Threading.CancellationToken" /> to observe while waiting for a task to complete.</span></span></param>
        <summary>
            <span data-ttu-id="5d9cd-800">Initiiert einen asynchronen Vorgang, der ein ergebnissegment mit einer Auflistung von Blob-Elemente im Container zurückgibt.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-800">Initiates an asynchronous operation that returns a result segment containing a collection of blob items in the container.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListBlobsSegmentedAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Blob.BlobResultSegment&gt; ListBlobsSegmentedAsync (string prefix, bool useFlatBlobListing, Microsoft.WindowsAzure.Storage.Blob.BlobListingDetails blobListingDetails, Nullable&lt;int&gt; maxResults, Microsoft.WindowsAzure.Storage.Blob.BlobContinuationToken currentToken, Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, Microsoft.WindowsAzure.Storage.OperationContext operationContext);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.WindowsAzure.Storage.Blob.BlobResultSegment&gt; ListBlobsSegmentedAsync(string prefix, bool useFlatBlobListing, valuetype Microsoft.WindowsAzure.Storage.Blob.BlobListingDetails blobListingDetails, valuetype System.Nullable`1&lt;int32&gt; maxResults, class Microsoft.WindowsAzure.Storage.Blob.BlobContinuationToken currentToken, class Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlobContainer.ListBlobsSegmentedAsync(System.String,System.Boolean,Microsoft.WindowsAzure.Storage.Blob.BlobListingDetails,System.Nullable{System.Int32},Microsoft.WindowsAzure.Storage.Blob.BlobContinuationToken,Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="abstract member ListBlobsSegmentedAsync : string * bool * Microsoft.WindowsAzure.Storage.Blob.BlobListingDetails * Nullable&lt;int&gt; * Microsoft.WindowsAzure.Storage.Blob.BlobContinuationToken * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Blob.BlobResultSegment&gt;&#xA;override this.ListBlobsSegmentedAsync : string * bool * Microsoft.WindowsAzure.Storage.Blob.BlobListingDetails * Nullable&lt;int&gt; * Microsoft.WindowsAzure.Storage.Blob.BlobContinuationToken * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Blob.BlobResultSegment&gt;" Usage="cloudBlobContainer.ListBlobsSegmentedAsync (prefix, useFlatBlobListing, blobListingDetails, maxResults, currentToken, options, operationContext)" />
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
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Blob.BlobResultSegment&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="prefix" Type="System.String" />
        <Parameter Name="useFlatBlobListing" Type="System.Boolean" />
        <Parameter Name="blobListingDetails" Type="Microsoft.WindowsAzure.Storage.Blob.BlobListingDetails" />
        <Parameter Name="maxResults" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="currentToken" Type="Microsoft.WindowsAzure.Storage.Blob.BlobContinuationToken" />
        <Parameter Name="options" Type="Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="prefix"><span data-ttu-id="5d9cd-801">Eine Zeichenfolge mit dem Blob-Namenspräfix.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-801">A string containing the blob name prefix.</span></span></param>
        <param name="useFlatBlobListing"><span data-ttu-id="5d9cd-802">Ein boolescher Wert, der angibt, ob Blobs in einer flachen Liste oder hierarchisch nach virtuellem Verzeichnis aufgelistet.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-802">A boolean value that specifies whether to list blobs in a flat listing, or whether to list blobs hierarchically, by virtual directory.</span></span></param>
        <param name="blobListingDetails"><span data-ttu-id="5d9cd-803">Ein <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobListingDetails" /> -Enumeration, die in die Auflistung einzuschließenden Elemente beschreibt.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-803">A <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobListingDetails" /> enumeration describing which items to include in the listing.</span></span></param>
        <param name="maxResults"><span data-ttu-id="5d9cd-804">Ein nicht negativer ganzzahliger Wert, der die maximale Anzahl von gleichzeitig pro Vorgang gilt ein Grenzwert von 5000 zurückzugebenden Ergebnisse angibt.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-804">A non-negative integer value that indicates the maximum number of results to be returned at a time, up to the per-operation limit of 5000.</span></span> <span data-ttu-id="5d9cd-805">Wenn dieser Wert ist <c>null</c>, die maximale zulässige Anzahl von Ergebnissen wird sein (bis 5.000) zurückgegeben.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-805">If this value is <c>null</c>, the maximum possible number of results will be returned, up to 5000.</span></span></param>
        <param name="currentToken"><span data-ttu-id="5d9cd-806">Eine von einem vorherigen Auflistungsvorgang zurückgegebenes Fortsetzungstoken.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-806">A continuation token returned by a previous listing operation.</span></span></param>
        <param name="options"><span data-ttu-id="5d9cd-807">Ein <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" /> -Objekt, das zusätzliche Optionen für die Anforderung angibt.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-807">A <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" /> object that specifies additional options for the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="5d9cd-808">Ein <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> -Objekt, das den Kontext für den aktuellen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-808">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <summary>
            <span data-ttu-id="5d9cd-809">Initiiert einen asynchronen Vorgang, der ein ergebnissegment mit einer Auflistung von Blob-Elemente im Container zurückgibt.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-809">Initiates an asynchronous operation that returns a result segment containing a collection of blob items in the container.</span></span>
            </summary>
        <returns><span data-ttu-id="5d9cd-810">Ein <see cref="T:System.Threading.Tasks.Task`1" />-Objekt, das den asynchronen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-810">A <see cref="T:System.Threading.Tasks.Task`1" /> object that represents the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListBlobsSegmentedAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Blob.BlobResultSegment&gt; ListBlobsSegmentedAsync (string prefix, bool useFlatBlobListing, Microsoft.WindowsAzure.Storage.Blob.BlobListingDetails blobListingDetails, Nullable&lt;int&gt; maxResults, Microsoft.WindowsAzure.Storage.Blob.BlobContinuationToken currentToken, Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, Microsoft.WindowsAzure.Storage.OperationContext operationContext, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.WindowsAzure.Storage.Blob.BlobResultSegment&gt; ListBlobsSegmentedAsync(string prefix, bool useFlatBlobListing, valuetype Microsoft.WindowsAzure.Storage.Blob.BlobListingDetails blobListingDetails, valuetype System.Nullable`1&lt;int32&gt; maxResults, class Microsoft.WindowsAzure.Storage.Blob.BlobContinuationToken currentToken, class Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, class Microsoft.WindowsAzure.Storage.OperationContext operationContext, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlobContainer.ListBlobsSegmentedAsync(System.String,System.Boolean,Microsoft.WindowsAzure.Storage.Blob.BlobListingDetails,System.Nullable{System.Int32},Microsoft.WindowsAzure.Storage.Blob.BlobContinuationToken,Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListBlobsSegmentedAsync : string * bool * Microsoft.WindowsAzure.Storage.Blob.BlobListingDetails * Nullable&lt;int&gt; * Microsoft.WindowsAzure.Storage.Blob.BlobContinuationToken * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Blob.BlobResultSegment&gt;&#xA;override this.ListBlobsSegmentedAsync : string * bool * Microsoft.WindowsAzure.Storage.Blob.BlobListingDetails * Nullable&lt;int&gt; * Microsoft.WindowsAzure.Storage.Blob.BlobContinuationToken * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Blob.BlobResultSegment&gt;" Usage="cloudBlobContainer.ListBlobsSegmentedAsync (prefix, useFlatBlobListing, blobListingDetails, maxResults, currentToken, options, operationContext, cancellationToken)" />
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
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Blob.BlobResultSegment&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="prefix" Type="System.String" />
        <Parameter Name="useFlatBlobListing" Type="System.Boolean" />
        <Parameter Name="blobListingDetails" Type="Microsoft.WindowsAzure.Storage.Blob.BlobListingDetails" />
        <Parameter Name="maxResults" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="currentToken" Type="Microsoft.WindowsAzure.Storage.Blob.BlobContinuationToken" />
        <Parameter Name="options" Type="Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="prefix"><span data-ttu-id="5d9cd-811">Eine Zeichenfolge mit dem Blob-Namenspräfix.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-811">A string containing the blob name prefix.</span></span></param>
        <param name="useFlatBlobListing"><span data-ttu-id="5d9cd-812">Ein boolescher Wert, der angibt, ob Blobs in einer flachen Liste oder hierarchisch nach virtuellem Verzeichnis aufgelistet.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-812">A boolean value that specifies whether to list blobs in a flat listing, or whether to list blobs hierarchically, by virtual directory.</span></span></param>
        <param name="blobListingDetails"><span data-ttu-id="5d9cd-813">Ein <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobListingDetails" /> -Enumeration, die in die Auflistung einzuschließenden Elemente beschreibt.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-813">A <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobListingDetails" /> enumeration describing which items to include in the listing.</span></span></param>
        <param name="maxResults"><span data-ttu-id="5d9cd-814">Ein nicht negativer ganzzahliger Wert, der die maximale Anzahl von gleichzeitig pro Vorgang gilt ein Grenzwert von 5000 zurückzugebenden Ergebnisse angibt.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-814">A non-negative integer value that indicates the maximum number of results to be returned at a time, up to the per-operation limit of 5000.</span></span> <span data-ttu-id="5d9cd-815">Wenn dieser Wert ist <c>null</c>, die maximale zulässige Anzahl von Ergebnissen wird sein (bis 5.000) zurückgegeben.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-815">If this value is <c>null</c>, the maximum possible number of results will be returned, up to 5000.</span></span></param>
        <param name="currentToken"><span data-ttu-id="5d9cd-816">Eine von einem vorherigen Auflistungsvorgang zurückgegebenes Fortsetzungstoken.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-816">A continuation token returned by a previous listing operation.</span></span></param>
        <param name="options"><span data-ttu-id="5d9cd-817">Ein <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" /> -Objekt, das zusätzliche Optionen für die Anforderung angibt.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-817">A <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" /> object that specifies additional options for the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="5d9cd-818">Ein <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> -Objekt, das den Kontext für den aktuellen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-818">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="5d9cd-819">Ein <see cref="T:System.Threading.CancellationToken" />, das beim Warten auf den Abschluss einer Aufgabe überwacht werden soll.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-819">A <see cref="T:System.Threading.CancellationToken" /> to observe while waiting for a task to complete.</span></span></param>
        <summary>
            <span data-ttu-id="5d9cd-820">Initiiert einen asynchronen Vorgang, der ein ergebnissegment mit einer Auflistung von Blob-Elemente im Container zurückgibt.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-820">Initiates an asynchronous operation that returns a result segment containing a collection of blob items in the container.</span></span>
            </summary>
        <returns><span data-ttu-id="5d9cd-821">Ein <see cref="T:System.Threading.Tasks.Task`1" />-Objekt, das den asynchronen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-821">A <see cref="T:System.Threading.Tasks.Task`1" /> object that represents the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Metadata">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IDictionary&lt;string,string&gt; Metadata { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IDictionary`2&lt;string, string&gt; Metadata" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.Blob.CloudBlobContainer.Metadata" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Metadata As IDictionary(Of String, String)" />
      <MemberSignature Language="F#" Value="member this.Metadata : System.Collections.Generic.IDictionary&lt;string, string&gt;" Usage="Microsoft.WindowsAzure.Storage.Blob.CloudBlobContainer.Metadata" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IDictionary&lt;System.String,System.String&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="5d9cd-822">Ruft die Metadaten des Containers ab.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-822">Gets the container's metadata.</span></span>
            </summary>
        <value><span data-ttu-id="5d9cd-823">Ein <see cref="T:System.Collections.Generic.IDictionary`2" /> Objekt, das die Metadaten des Containers enthält.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-823">An <see cref="T:System.Collections.Generic.IDictionary`2" /> object containing the container's metadata.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Name">
      <MemberSignature Language="C#" Value="public string Name { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Name" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.Blob.CloudBlobContainer.Name" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Name As String" />
      <MemberSignature Language="F#" Value="member this.Name : string" Usage="Microsoft.WindowsAzure.Storage.Blob.CloudBlobContainer.Name" />
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
            <span data-ttu-id="5d9cd-824">Ruft den Namen des Containers ab.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-824">Gets the name of the container.</span></span>
            </summary>
        <value><span data-ttu-id="5d9cd-825">Eine Zeichenfolge mit dem Containernamen.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-825">A string containing the container name.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Properties">
      <MemberSignature Language="C#" Value="public Microsoft.WindowsAzure.Storage.Blob.BlobContainerProperties Properties { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.WindowsAzure.Storage.Blob.BlobContainerProperties Properties" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.Blob.CloudBlobContainer.Properties" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Properties As BlobContainerProperties" />
      <MemberSignature Language="F#" Value="member this.Properties : Microsoft.WindowsAzure.Storage.Blob.BlobContainerProperties" Usage="Microsoft.WindowsAzure.Storage.Blob.CloudBlobContainer.Properties" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Storage.Blob.BlobContainerProperties</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="5d9cd-826">Ruft die Systemeigenschaften des Containers ab.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-826">Gets the container's system properties.</span></span>
            </summary>
        <value><span data-ttu-id="5d9cd-827">Ein <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobContainerProperties" />-Objekt.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-827">A <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobContainerProperties" /> object.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ReleaseLease">
      <MemberSignature Language="C#" Value="public virtual void ReleaseLease (Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options = null, Microsoft.WindowsAzure.Storage.OperationContext operationContext = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void ReleaseLease(class Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, class Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlobContainer.ReleaseLease(Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="abstract member ReleaseLease : Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; unit&#xA;override this.ReleaseLease : Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; unit" Usage="cloudBlobContainer.ReleaseLease (accessCondition, options, operationContext)" />
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
        <Parameter Name="accessCondition" Type="Microsoft.WindowsAzure.Storage.AccessCondition" />
        <Parameter Name="options" Type="Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="accessCondition"><span data-ttu-id="5d9cd-828">Ein <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> Objekt, das die Bedingung, die erfüllt sein muss, damit die Anforderung zu fortfahren, darstellt, einschließlich einer erforderlichen Lease-ID.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-828">An <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> object that represents the condition that must be met in order for the request to proceed, including a required lease ID.</span></span></param>
        <param name="options"><span data-ttu-id="5d9cd-829">Ein <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" /> -Objekt, das zusätzliche Optionen für die Anforderung angibt.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-829">A <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" /> object that specifies additional options for the request.</span></span> <span data-ttu-id="5d9cd-830">Wenn <c>null</c>, Standardoptionen gelten für die Anforderung.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-830">If <c>null</c>, default options are applied to the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="5d9cd-831">Ein <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> -Objekt, das den Kontext für den aktuellen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-831">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <summary>
            <span data-ttu-id="5d9cd-832">Gibt die Lease für diesen Container frei.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-832">Releases the lease on this container.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ReleaseLeaseAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task ReleaseLeaseAsync (Microsoft.WindowsAzure.Storage.AccessCondition accessCondition);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task ReleaseLeaseAsync(class Microsoft.WindowsAzure.Storage.AccessCondition accessCondition) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlobContainer.ReleaseLeaseAsync(Microsoft.WindowsAzure.Storage.AccessCondition)" />
      <MemberSignature Language="F#" Value="abstract member ReleaseLeaseAsync : Microsoft.WindowsAzure.Storage.AccessCondition -&gt; System.Threading.Tasks.Task&#xA;override this.ReleaseLeaseAsync : Microsoft.WindowsAzure.Storage.AccessCondition -&gt; System.Threading.Tasks.Task" Usage="cloudBlobContainer.ReleaseLeaseAsync accessCondition" />
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
        <Parameter Name="accessCondition" Type="Microsoft.WindowsAzure.Storage.AccessCondition" />
      </Parameters>
      <Docs>
        <param name="accessCondition"><span data-ttu-id="5d9cd-833">Ein <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> Objekt, das die Bedingung, die erfüllt sein muss, damit die Anforderung zu fortfahren, darstellt, einschließlich einer erforderlichen Lease-ID.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-833">An <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> object that represents the condition that must be met in order for the request to proceed, including a required lease ID.</span></span></param>
        <summary>
            <span data-ttu-id="5d9cd-834">Initiiert einen asynchronen Vorgang, der die Lease für diesen Container frei.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-834">Initiates an asynchronous operation that releases the lease on this container.</span></span>
            </summary>
        <returns><span data-ttu-id="5d9cd-835">Ein <see cref="T:System.Threading.Tasks.Task" />-Objekt, das den asynchronen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-835">A <see cref="T:System.Threading.Tasks.Task" /> object that represents the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ReleaseLeaseAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task ReleaseLeaseAsync (Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task ReleaseLeaseAsync(class Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlobContainer.ReleaseLeaseAsync(Microsoft.WindowsAzure.Storage.AccessCondition,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ReleaseLeaseAsync : Microsoft.WindowsAzure.Storage.AccessCondition * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&#xA;override this.ReleaseLeaseAsync : Microsoft.WindowsAzure.Storage.AccessCondition * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="cloudBlobContainer.ReleaseLeaseAsync (accessCondition, cancellationToken)" />
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
        <Parameter Name="accessCondition" Type="Microsoft.WindowsAzure.Storage.AccessCondition" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="accessCondition"><span data-ttu-id="5d9cd-836">Ein <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> Objekt, das die Bedingung, die erfüllt sein muss, damit die Anforderung zu fortfahren, darstellt, einschließlich einer erforderlichen Lease-ID.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-836">An <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> object that represents the condition that must be met in order for the request to proceed, including a required lease ID.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="5d9cd-837">Ein <see cref="T:System.Threading.CancellationToken" />, das beim Warten auf den Abschluss einer Aufgabe überwacht werden soll.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-837">A <see cref="T:System.Threading.CancellationToken" /> to observe while waiting for a task to complete.</span></span></param>
        <summary>
            <span data-ttu-id="5d9cd-838">Initiiert einen asynchronen Vorgang, der die Lease für diesen Container frei.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-838">Initiates an asynchronous operation that releases the lease on this container.</span></span>
            </summary>
        <returns><span data-ttu-id="5d9cd-839">Ein <see cref="T:System.Threading.Tasks.Task" />-Objekt, das den asynchronen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-839">A <see cref="T:System.Threading.Tasks.Task" /> object that represents the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ReleaseLeaseAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task ReleaseLeaseAsync (Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, Microsoft.WindowsAzure.Storage.OperationContext operationContext);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task ReleaseLeaseAsync(class Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, class Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlobContainer.ReleaseLeaseAsync(Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="abstract member ReleaseLeaseAsync : Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Threading.Tasks.Task&#xA;override this.ReleaseLeaseAsync : Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Threading.Tasks.Task" Usage="cloudBlobContainer.ReleaseLeaseAsync (accessCondition, options, operationContext)" />
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
        <Parameter Name="accessCondition" Type="Microsoft.WindowsAzure.Storage.AccessCondition" />
        <Parameter Name="options" Type="Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="accessCondition"><span data-ttu-id="5d9cd-840">Ein <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> Objekt, das die Bedingung, die erfüllt sein muss, damit die Anforderung zu fortfahren, darstellt, einschließlich einer erforderlichen Lease-ID.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-840">An <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> object that represents the condition that must be met in order for the request to proceed, including a required lease ID.</span></span></param>
        <param name="options"><span data-ttu-id="5d9cd-841">Ein <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" /> -Objekt, das zusätzliche Optionen für die Anforderung angibt.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-841">A <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" /> object that specifies additional options for the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="5d9cd-842">Ein <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> -Objekt, das den Kontext für den aktuellen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-842">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <summary>
            <span data-ttu-id="5d9cd-843">Initiiert einen asynchronen Vorgang, der die Lease für diesen Container frei.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-843">Initiates an asynchronous operation that releases the lease on this container.</span></span>
            </summary>
        <returns><span data-ttu-id="5d9cd-844">Ein <see cref="T:System.Threading.Tasks.Task" />-Objekt, das den asynchronen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-844">A <see cref="T:System.Threading.Tasks.Task" /> object that represents the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ReleaseLeaseAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task ReleaseLeaseAsync (Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, Microsoft.WindowsAzure.Storage.OperationContext operationContext, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task ReleaseLeaseAsync(class Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, class Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, class Microsoft.WindowsAzure.Storage.OperationContext operationContext, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlobContainer.ReleaseLeaseAsync(Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ReleaseLeaseAsync : Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&#xA;override this.ReleaseLeaseAsync : Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="cloudBlobContainer.ReleaseLeaseAsync (accessCondition, options, operationContext, cancellationToken)" />
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
        <Parameter Name="accessCondition" Type="Microsoft.WindowsAzure.Storage.AccessCondition" />
        <Parameter Name="options" Type="Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="accessCondition"><span data-ttu-id="5d9cd-845">Ein <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> Objekt, das die Bedingung, die erfüllt sein muss, damit die Anforderung zu fortfahren, darstellt, einschließlich einer erforderlichen Lease-ID.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-845">An <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> object that represents the condition that must be met in order for the request to proceed, including a required lease ID.</span></span></param>
        <param name="options"><span data-ttu-id="5d9cd-846">Ein <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" /> -Objekt, das zusätzliche Optionen für die Anforderung angibt.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-846">A <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" /> object that specifies additional options for the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="5d9cd-847">Ein <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> -Objekt, das den Kontext für den aktuellen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-847">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="5d9cd-848">Ein <see cref="T:System.Threading.CancellationToken" />, das beim Warten auf den Abschluss einer Aufgabe überwacht werden soll.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-848">A <see cref="T:System.Threading.CancellationToken" /> to observe while waiting for a task to complete.</span></span></param>
        <summary>
            <span data-ttu-id="5d9cd-849">Initiiert einen asynchronen Vorgang, der die Lease für diesen Container frei.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-849">Initiates an asynchronous operation that releases the lease on this container.</span></span>
            </summary>
        <returns><span data-ttu-id="5d9cd-850">Ein <see cref="T:System.Threading.Tasks.Task" />-Objekt, das den asynchronen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-850">A <see cref="T:System.Threading.Tasks.Task" /> object that represents the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RenewLease">
      <MemberSignature Language="C#" Value="public virtual void RenewLease (Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options = null, Microsoft.WindowsAzure.Storage.OperationContext operationContext = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void RenewLease(class Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, class Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlobContainer.RenewLease(Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="abstract member RenewLease : Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; unit&#xA;override this.RenewLease : Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; unit" Usage="cloudBlobContainer.RenewLease (accessCondition, options, operationContext)" />
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
        <Parameter Name="accessCondition" Type="Microsoft.WindowsAzure.Storage.AccessCondition" />
        <Parameter Name="options" Type="Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="accessCondition"><span data-ttu-id="5d9cd-851">Ein <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> Objekt, das die Bedingung, die erfüllt sein muss, damit die Anforderung zu fortfahren, darstellt, einschließlich einer erforderlichen Lease-ID.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-851">An <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> object that represents the condition that must be met in order for the request to proceed, including a required lease ID.</span></span></param>
        <param name="options"><span data-ttu-id="5d9cd-852">Ein <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" /> -Objekt, das zusätzliche Optionen für die Anforderung angibt.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-852">A <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" /> object that specifies additional options for the request.</span></span> <span data-ttu-id="5d9cd-853">Wenn <c>null</c>, Standardoptionen gelten für die Anforderung.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-853">If <c>null</c>, default options are applied to the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="5d9cd-854">Ein <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> -Objekt, das den Kontext für den aktuellen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-854">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <summary>
            <span data-ttu-id="5d9cd-855">Erneuert eine Lease für diesen Container.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-855">Renews a lease on this container.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RenewLeaseAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task RenewLeaseAsync (Microsoft.WindowsAzure.Storage.AccessCondition accessCondition);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task RenewLeaseAsync(class Microsoft.WindowsAzure.Storage.AccessCondition accessCondition) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlobContainer.RenewLeaseAsync(Microsoft.WindowsAzure.Storage.AccessCondition)" />
      <MemberSignature Language="F#" Value="abstract member RenewLeaseAsync : Microsoft.WindowsAzure.Storage.AccessCondition -&gt; System.Threading.Tasks.Task&#xA;override this.RenewLeaseAsync : Microsoft.WindowsAzure.Storage.AccessCondition -&gt; System.Threading.Tasks.Task" Usage="cloudBlobContainer.RenewLeaseAsync accessCondition" />
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
        <Parameter Name="accessCondition" Type="Microsoft.WindowsAzure.Storage.AccessCondition" />
      </Parameters>
      <Docs>
        <param name="accessCondition"><span data-ttu-id="5d9cd-856">Ein <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> Objekt, das die Bedingung, die erfüllt sein muss, damit die Anforderung zu fortfahren, darstellt, einschließlich einer erforderlichen Lease-ID.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-856">An <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> object that represents the condition that must be met in order for the request to proceed, including a required lease ID.</span></span></param>
        <summary>
            <span data-ttu-id="5d9cd-857">Initiiert einen asynchronen Vorgang, der erneuert eine Lease für diesen Container.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-857">Initiates an asynchronous operation that renews a lease on this container.</span></span>
            </summary>
        <returns><span data-ttu-id="5d9cd-858">Ein <see cref="T:System.Threading.Tasks.Task" />-Objekt, das den asynchronen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-858">A <see cref="T:System.Threading.Tasks.Task" /> object that represents the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RenewLeaseAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task RenewLeaseAsync (Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task RenewLeaseAsync(class Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlobContainer.RenewLeaseAsync(Microsoft.WindowsAzure.Storage.AccessCondition,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member RenewLeaseAsync : Microsoft.WindowsAzure.Storage.AccessCondition * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&#xA;override this.RenewLeaseAsync : Microsoft.WindowsAzure.Storage.AccessCondition * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="cloudBlobContainer.RenewLeaseAsync (accessCondition, cancellationToken)" />
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
        <Parameter Name="accessCondition" Type="Microsoft.WindowsAzure.Storage.AccessCondition" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="accessCondition"><span data-ttu-id="5d9cd-859">Ein <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> Objekt, das die Bedingung, die erfüllt sein muss, damit die Anforderung zu fortfahren, darstellt, einschließlich einer erforderlichen Lease-ID.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-859">An <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> object that represents the condition that must be met in order for the request to proceed, including a required lease ID.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="5d9cd-860">Ein <see cref="T:System.Threading.CancellationToken" />, das beim Warten auf den Abschluss einer Aufgabe überwacht werden soll.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-860">A <see cref="T:System.Threading.CancellationToken" /> to observe while waiting for a task to complete.</span></span></param>
        <summary>
            <span data-ttu-id="5d9cd-861">Initiiert einen asynchronen Vorgang, der erneuert eine Lease für diesen Container.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-861">Initiates an asynchronous operation that renews a lease on this container.</span></span>
            </summary>
        <returns><span data-ttu-id="5d9cd-862">Ein <see cref="T:System.Threading.Tasks.Task" />-Objekt, das den asynchronen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-862">A <see cref="T:System.Threading.Tasks.Task" /> object that represents the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RenewLeaseAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task RenewLeaseAsync (Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, Microsoft.WindowsAzure.Storage.OperationContext operationContext);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task RenewLeaseAsync(class Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, class Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlobContainer.RenewLeaseAsync(Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="abstract member RenewLeaseAsync : Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Threading.Tasks.Task&#xA;override this.RenewLeaseAsync : Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Threading.Tasks.Task" Usage="cloudBlobContainer.RenewLeaseAsync (accessCondition, options, operationContext)" />
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
        <Parameter Name="accessCondition" Type="Microsoft.WindowsAzure.Storage.AccessCondition" />
        <Parameter Name="options" Type="Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="accessCondition"><span data-ttu-id="5d9cd-863">Ein <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> Objekt, das die Bedingung, die erfüllt sein muss, damit die Anforderung zu fortfahren, darstellt, einschließlich einer erforderlichen Lease-ID.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-863">An <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> object that represents the condition that must be met in order for the request to proceed, including a required lease ID.</span></span></param>
        <param name="options"><span data-ttu-id="5d9cd-864">Ein <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" /> -Objekt, das zusätzliche Optionen für die Anforderung angibt.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-864">A <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" /> object that specifies additional options for the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="5d9cd-865">Ein <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> -Objekt, das den Kontext für den aktuellen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-865">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <summary>
            <span data-ttu-id="5d9cd-866">Initiiert einen asynchronen Vorgang, der erneuert eine Lease für diesen Container.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-866">Initiates an asynchronous operation that renews a lease on this container.</span></span>
            </summary>
        <returns><span data-ttu-id="5d9cd-867">Ein <see cref="T:System.Threading.Tasks.Task" />-Objekt, das den asynchronen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-867">A <see cref="T:System.Threading.Tasks.Task" /> object that represents the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RenewLeaseAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task RenewLeaseAsync (Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, Microsoft.WindowsAzure.Storage.OperationContext operationContext, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task RenewLeaseAsync(class Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, class Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, class Microsoft.WindowsAzure.Storage.OperationContext operationContext, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlobContainer.RenewLeaseAsync(Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member RenewLeaseAsync : Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&#xA;override this.RenewLeaseAsync : Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="cloudBlobContainer.RenewLeaseAsync (accessCondition, options, operationContext, cancellationToken)" />
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
        <Parameter Name="accessCondition" Type="Microsoft.WindowsAzure.Storage.AccessCondition" />
        <Parameter Name="options" Type="Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="accessCondition"><span data-ttu-id="5d9cd-868">Ein <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> Objekt, das die Bedingung, die erfüllt sein muss, damit die Anforderung zu fortfahren, darstellt, einschließlich einer erforderlichen Lease-ID.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-868">An <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> object that represents the condition that must be met in order for the request to proceed, including a required lease ID.</span></span></param>
        <param name="options"><span data-ttu-id="5d9cd-869">Ein <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" /> -Objekt, das zusätzliche Optionen für die Anforderung angibt.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-869">A <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" /> object that specifies additional options for the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="5d9cd-870">Ein <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> -Objekt, das den Kontext für den aktuellen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-870">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="5d9cd-871">Ein <see cref="T:System.Threading.CancellationToken" />, das beim Warten auf den Abschluss einer Aufgabe überwacht werden soll.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-871">A <see cref="T:System.Threading.CancellationToken" /> to observe while waiting for a task to complete.</span></span></param>
        <summary>
            <span data-ttu-id="5d9cd-872">Initiiert einen asynchronen Vorgang, der erneuert eine Lease für diesen Container.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-872">Initiates an asynchronous operation that renews a lease on this container.</span></span>
            </summary>
        <returns><span data-ttu-id="5d9cd-873">Ein <see cref="T:System.Threading.Tasks.Task" />-Objekt, das den asynchronen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-873">A <see cref="T:System.Threading.Tasks.Task" /> object that represents the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ServiceClient">
      <MemberSignature Language="C#" Value="public Microsoft.WindowsAzure.Storage.Blob.CloudBlobClient ServiceClient { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.WindowsAzure.Storage.Blob.CloudBlobClient ServiceClient" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.Blob.CloudBlobContainer.ServiceClient" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ServiceClient As CloudBlobClient" />
      <MemberSignature Language="F#" Value="member this.ServiceClient : Microsoft.WindowsAzure.Storage.Blob.CloudBlobClient" Usage="Microsoft.WindowsAzure.Storage.Blob.CloudBlobContainer.ServiceClient" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Storage.Blob.CloudBlobClient</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="5d9cd-874">Ruft den Blob-Dienstclient für den Container ab.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-874">Gets the Blob service client for the container.</span></span>
            </summary>
        <value><span data-ttu-id="5d9cd-875">Ein <see cref="T:Microsoft.WindowsAzure.Storage.Blob.CloudBlobClient" />-Objekt.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-875">A <see cref="T:Microsoft.WindowsAzure.Storage.Blob.CloudBlobClient" /> object.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SetMetadata">
      <MemberSignature Language="C#" Value="public virtual void SetMetadata (Microsoft.WindowsAzure.Storage.AccessCondition accessCondition = null, Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options = null, Microsoft.WindowsAzure.Storage.OperationContext operationContext = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void SetMetadata(class Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, class Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlobContainer.SetMetadata(Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="abstract member SetMetadata : Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; unit&#xA;override this.SetMetadata : Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; unit" Usage="cloudBlobContainer.SetMetadata (accessCondition, options, operationContext)" />
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
        <Parameter Name="accessCondition" Type="Microsoft.WindowsAzure.Storage.AccessCondition" />
        <Parameter Name="options" Type="Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="accessCondition"><span data-ttu-id="5d9cd-876">Ein <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> -Objekt, das die Bedingung, die erfüllt sein müssen, damit die Anforderung darstellt, um den Vorgang fortzusetzen.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-876">An <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> object that represents the condition that must be met in order for the request to proceed.</span></span> <span data-ttu-id="5d9cd-877">Wenn <c>null</c>, keine Bedingung verwendet.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-877">If <c>null</c>, no condition is used.</span></span></param>
        <param name="options"><span data-ttu-id="5d9cd-878">Ein <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" /> -Objekt, das zusätzliche Optionen für die Anforderung angibt.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-878">A <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" /> object that specifies additional options for the request.</span></span> <span data-ttu-id="5d9cd-879">Wenn <c>null</c>, Standardoptionen gelten für die Anforderung.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-879">If <c>null</c>, default options are applied to the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="5d9cd-880">Ein <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> -Objekt, das den Kontext für den aktuellen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-880">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <summary>
            <span data-ttu-id="5d9cd-881">Legt die Metadaten des Containers benutzerdefinierte fest.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-881">Sets the container's user-defined metadata.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SetMetadataAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task SetMetadataAsync ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task SetMetadataAsync() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlobContainer.SetMetadataAsync" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function SetMetadataAsync () As Task" />
      <MemberSignature Language="F#" Value="abstract member SetMetadataAsync : unit -&gt; System.Threading.Tasks.Task&#xA;override this.SetMetadataAsync : unit -&gt; System.Threading.Tasks.Task" Usage="cloudBlobContainer.SetMetadataAsync " />
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
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="5d9cd-882">Initiiert einen asynchronen Vorgang, durch die benutzerdefinierten Metadaten des Containers festgelegt.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-882">Initiates an asynchronous operation that sets container's user-defined metadata.</span></span>
            </summary>
        <returns><span data-ttu-id="5d9cd-883">Ein <see cref="T:System.Threading.Tasks.Task" />-Objekt, das den asynchronen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-883">A <see cref="T:System.Threading.Tasks.Task" /> object that represents the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SetMetadataAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task SetMetadataAsync (System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task SetMetadataAsync(valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlobContainer.SetMetadataAsync(System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member SetMetadataAsync : System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&#xA;override this.SetMetadataAsync : System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="cloudBlobContainer.SetMetadataAsync cancellationToken" />
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
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="cancellationToken"><span data-ttu-id="5d9cd-884">Ein <see cref="T:System.Threading.CancellationToken" />, das beim Warten auf den Abschluss einer Aufgabe überwacht werden soll.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-884">A <see cref="T:System.Threading.CancellationToken" /> to observe while waiting for a task to complete.</span></span></param>
        <summary>
            <span data-ttu-id="5d9cd-885">Initiiert einen asynchronen Vorgang, durch die benutzerdefinierten Metadaten des Containers festgelegt.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-885">Initiates an asynchronous operation that sets container's user-defined metadata.</span></span>
            </summary>
        <returns><span data-ttu-id="5d9cd-886">Ein <see cref="T:System.Threading.Tasks.Task" />-Objekt, das den asynchronen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-886">A <see cref="T:System.Threading.Tasks.Task" /> object that represents the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SetMetadataAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task SetMetadataAsync (Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, Microsoft.WindowsAzure.Storage.OperationContext operationContext);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task SetMetadataAsync(class Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, class Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlobContainer.SetMetadataAsync(Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="abstract member SetMetadataAsync : Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Threading.Tasks.Task&#xA;override this.SetMetadataAsync : Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Threading.Tasks.Task" Usage="cloudBlobContainer.SetMetadataAsync (accessCondition, options, operationContext)" />
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
        <Parameter Name="accessCondition" Type="Microsoft.WindowsAzure.Storage.AccessCondition" />
        <Parameter Name="options" Type="Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="accessCondition"><span data-ttu-id="5d9cd-887">Ein <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> -Objekt, das die Bedingung, die erfüllt sein müssen, damit die Anforderung darstellt, um den Vorgang fortzusetzen.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-887">An <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> object that represents the condition that must be met in order for the request to proceed.</span></span> <span data-ttu-id="5d9cd-888">Wenn <c>null</c>, keine Bedingung verwendet.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-888">If <c>null</c>, no condition is used.</span></span></param>
        <param name="options"><span data-ttu-id="5d9cd-889">Ein <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" /> -Objekt, das zusätzliche Optionen für die Anforderung angibt.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-889">A <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" /> object that specifies additional options for the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="5d9cd-890">Ein <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> -Objekt, das den Kontext für den aktuellen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-890">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <summary>
            <span data-ttu-id="5d9cd-891">Initiiert einen asynchronen Vorgang, durch die benutzerdefinierten Metadaten des Containers festgelegt.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-891">Initiates an asynchronous operation that sets container's user-defined metadata.</span></span>
            </summary>
        <returns><span data-ttu-id="5d9cd-892">Ein <see cref="T:System.Threading.Tasks.Task" />-Objekt, das den asynchronen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-892">A <see cref="T:System.Threading.Tasks.Task" /> object that represents the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SetMetadataAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task SetMetadataAsync (Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, Microsoft.WindowsAzure.Storage.OperationContext operationContext, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task SetMetadataAsync(class Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, class Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, class Microsoft.WindowsAzure.Storage.OperationContext operationContext, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlobContainer.SetMetadataAsync(Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member SetMetadataAsync : Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&#xA;override this.SetMetadataAsync : Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="cloudBlobContainer.SetMetadataAsync (accessCondition, options, operationContext, cancellationToken)" />
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
        <Parameter Name="accessCondition" Type="Microsoft.WindowsAzure.Storage.AccessCondition" />
        <Parameter Name="options" Type="Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="accessCondition"><span data-ttu-id="5d9cd-893">Ein <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> -Objekt, das die Bedingung, die erfüllt sein müssen, damit die Anforderung darstellt, um den Vorgang fortzusetzen.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-893">An <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> object that represents the condition that must be met in order for the request to proceed.</span></span> <span data-ttu-id="5d9cd-894">Wenn <c>null</c>, keine Bedingung verwendet.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-894">If <c>null</c>, no condition is used.</span></span></param>
        <param name="options"><span data-ttu-id="5d9cd-895">Ein <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" /> -Objekt, das zusätzliche Optionen für die Anforderung angibt.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-895">A <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" /> object that specifies additional options for the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="5d9cd-896">Ein <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> -Objekt, das den Kontext für den aktuellen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-896">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="5d9cd-897">Ein <see cref="T:System.Threading.CancellationToken" />, das beim Warten auf den Abschluss einer Aufgabe überwacht werden soll.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-897">A <see cref="T:System.Threading.CancellationToken" /> to observe while waiting for a task to complete.</span></span></param>
        <summary>
            <span data-ttu-id="5d9cd-898">Initiiert einen asynchronen Vorgang, durch die benutzerdefinierten Metadaten des Containers festgelegt.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-898">Initiates an asynchronous operation that sets container's user-defined metadata.</span></span>
            </summary>
        <returns><span data-ttu-id="5d9cd-899">Ein <see cref="T:System.Threading.Tasks.Task" />-Objekt, das den asynchronen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-899">A <see cref="T:System.Threading.Tasks.Task" /> object that represents the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SetPermissions">
      <MemberSignature Language="C#" Value="public virtual void SetPermissions (Microsoft.WindowsAzure.Storage.Blob.BlobContainerPermissions permissions, Microsoft.WindowsAzure.Storage.AccessCondition accessCondition = null, Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options = null, Microsoft.WindowsAzure.Storage.OperationContext operationContext = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void SetPermissions(class Microsoft.WindowsAzure.Storage.Blob.BlobContainerPermissions permissions, class Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, class Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlobContainer.SetPermissions(Microsoft.WindowsAzure.Storage.Blob.BlobContainerPermissions,Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="abstract member SetPermissions : Microsoft.WindowsAzure.Storage.Blob.BlobContainerPermissions * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; unit&#xA;override this.SetPermissions : Microsoft.WindowsAzure.Storage.Blob.BlobContainerPermissions * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; unit" Usage="cloudBlobContainer.SetPermissions (permissions, accessCondition, options, operationContext)" />
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
        <Parameter Name="permissions" Type="Microsoft.WindowsAzure.Storage.Blob.BlobContainerPermissions" />
        <Parameter Name="accessCondition" Type="Microsoft.WindowsAzure.Storage.AccessCondition" />
        <Parameter Name="options" Type="Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="permissions"><span data-ttu-id="5d9cd-900">Die Berechtigungen für den Container angewendet werden soll.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-900">The permissions to apply to the container.</span></span></param>
        <param name="accessCondition"><span data-ttu-id="5d9cd-901">Ein <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> -Objekt, das die Bedingung, die erfüllt sein müssen, damit die Anforderung darstellt, um den Vorgang fortzusetzen.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-901">An <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> object that represents the condition that must be met in order for the request to proceed.</span></span> <span data-ttu-id="5d9cd-902">Wenn <c>null</c>, keine Bedingung verwendet.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-902">If <c>null</c>, no condition is used.</span></span></param>
        <param name="options"><span data-ttu-id="5d9cd-903">Ein <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" /> -Objekt, das zusätzliche Optionen für die Anforderung angibt.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-903">A <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" /> object that specifies additional options for the request.</span></span> <span data-ttu-id="5d9cd-904">Wenn <c>null</c>, Standardoptionen gelten für die Anforderung.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-904">If <c>null</c>, default options are applied to the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="5d9cd-905">Ein <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> -Objekt, das den Kontext für den aktuellen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-905">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <summary>
            <span data-ttu-id="5d9cd-906">Legt Berechtigungen für den Container fest.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-906">Sets permissions for the container.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SetPermissionsAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task SetPermissionsAsync (Microsoft.WindowsAzure.Storage.Blob.BlobContainerPermissions permissions);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task SetPermissionsAsync(class Microsoft.WindowsAzure.Storage.Blob.BlobContainerPermissions permissions) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlobContainer.SetPermissionsAsync(Microsoft.WindowsAzure.Storage.Blob.BlobContainerPermissions)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function SetPermissionsAsync (permissions As BlobContainerPermissions) As Task" />
      <MemberSignature Language="F#" Value="abstract member SetPermissionsAsync : Microsoft.WindowsAzure.Storage.Blob.BlobContainerPermissions -&gt; System.Threading.Tasks.Task&#xA;override this.SetPermissionsAsync : Microsoft.WindowsAzure.Storage.Blob.BlobContainerPermissions -&gt; System.Threading.Tasks.Task" Usage="cloudBlobContainer.SetPermissionsAsync permissions" />
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
        <Parameter Name="permissions" Type="Microsoft.WindowsAzure.Storage.Blob.BlobContainerPermissions" />
      </Parameters>
      <Docs>
        <param name="permissions"><span data-ttu-id="5d9cd-907">Die Berechtigungen für den Container angewendet werden soll.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-907">The permissions to apply to the container.</span></span></param>
        <summary>
            <span data-ttu-id="5d9cd-908">Initiiert einen asynchronen Vorgang, der Berechtigungen für den Container festgelegt.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-908">Initiates an asynchronous operation that sets permissions for the container.</span></span>
            </summary>
        <returns><span data-ttu-id="5d9cd-909">Ein <see cref="T:System.Threading.Tasks.Task" />-Objekt, das den asynchronen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-909">A <see cref="T:System.Threading.Tasks.Task" /> object that represents the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SetPermissionsAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task SetPermissionsAsync (Microsoft.WindowsAzure.Storage.Blob.BlobContainerPermissions permissions, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task SetPermissionsAsync(class Microsoft.WindowsAzure.Storage.Blob.BlobContainerPermissions permissions, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlobContainer.SetPermissionsAsync(Microsoft.WindowsAzure.Storage.Blob.BlobContainerPermissions,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member SetPermissionsAsync : Microsoft.WindowsAzure.Storage.Blob.BlobContainerPermissions * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&#xA;override this.SetPermissionsAsync : Microsoft.WindowsAzure.Storage.Blob.BlobContainerPermissions * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="cloudBlobContainer.SetPermissionsAsync (permissions, cancellationToken)" />
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
        <Parameter Name="permissions" Type="Microsoft.WindowsAzure.Storage.Blob.BlobContainerPermissions" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="permissions"><span data-ttu-id="5d9cd-910">Die Berechtigungen für den Container angewendet werden soll.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-910">The permissions to apply to the container.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="5d9cd-911">Ein <see cref="T:System.Threading.CancellationToken" />, das beim Warten auf den Abschluss einer Aufgabe überwacht werden soll.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-911">A <see cref="T:System.Threading.CancellationToken" /> to observe while waiting for a task to complete.</span></span></param>
        <summary>
            <span data-ttu-id="5d9cd-912">Initiiert einen asynchronen Vorgang, der Berechtigungen für den Container festgelegt.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-912">Initiates an asynchronous operation that sets permissions for the container.</span></span>
            </summary>
        <returns><span data-ttu-id="5d9cd-913">Ein <see cref="T:System.Threading.Tasks.Task" />-Objekt, das den asynchronen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-913">A <see cref="T:System.Threading.Tasks.Task" /> object that represents the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SetPermissionsAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task SetPermissionsAsync (Microsoft.WindowsAzure.Storage.Blob.BlobContainerPermissions permissions, Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, Microsoft.WindowsAzure.Storage.OperationContext operationContext);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task SetPermissionsAsync(class Microsoft.WindowsAzure.Storage.Blob.BlobContainerPermissions permissions, class Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, class Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlobContainer.SetPermissionsAsync(Microsoft.WindowsAzure.Storage.Blob.BlobContainerPermissions,Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="abstract member SetPermissionsAsync : Microsoft.WindowsAzure.Storage.Blob.BlobContainerPermissions * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Threading.Tasks.Task&#xA;override this.SetPermissionsAsync : Microsoft.WindowsAzure.Storage.Blob.BlobContainerPermissions * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Threading.Tasks.Task" Usage="cloudBlobContainer.SetPermissionsAsync (permissions, accessCondition, options, operationContext)" />
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
        <Parameter Name="permissions" Type="Microsoft.WindowsAzure.Storage.Blob.BlobContainerPermissions" />
        <Parameter Name="accessCondition" Type="Microsoft.WindowsAzure.Storage.AccessCondition" />
        <Parameter Name="options" Type="Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="permissions"><span data-ttu-id="5d9cd-914">Die Berechtigungen für den Container angewendet werden soll.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-914">The permissions to apply to the container.</span></span></param>
        <param name="accessCondition"><span data-ttu-id="5d9cd-915">Ein <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> -Objekt, das die Bedingung, die erfüllt sein müssen, damit die Anforderung darstellt, um den Vorgang fortzusetzen.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-915">An <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> object that represents the condition that must be met in order for the request to proceed.</span></span> <span data-ttu-id="5d9cd-916">Wenn <c>null</c>, keine Bedingung verwendet.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-916">If <c>null</c>, no condition is used.</span></span></param>
        <param name="options"><span data-ttu-id="5d9cd-917">Ein <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" /> -Objekt, das zusätzliche Optionen für die Anforderung angibt.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-917">A <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" /> object that specifies additional options for the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="5d9cd-918">Ein <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> -Objekt, das den Kontext für den aktuellen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-918">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <summary>
            <span data-ttu-id="5d9cd-919">Initiiert einen asynchronen Vorgang, der Berechtigungen für den Container festgelegt.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-919">Initiates an asynchronous operation that sets permissions for the container.</span></span>
            </summary>
        <returns><span data-ttu-id="5d9cd-920">Ein <see cref="T:System.Threading.Tasks.Task" />-Objekt, das den asynchronen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-920">A <see cref="T:System.Threading.Tasks.Task" /> object that represents the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SetPermissionsAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task SetPermissionsAsync (Microsoft.WindowsAzure.Storage.Blob.BlobContainerPermissions permissions, Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, Microsoft.WindowsAzure.Storage.OperationContext operationContext, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task SetPermissionsAsync(class Microsoft.WindowsAzure.Storage.Blob.BlobContainerPermissions permissions, class Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, class Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, class Microsoft.WindowsAzure.Storage.OperationContext operationContext, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlobContainer.SetPermissionsAsync(Microsoft.WindowsAzure.Storage.Blob.BlobContainerPermissions,Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member SetPermissionsAsync : Microsoft.WindowsAzure.Storage.Blob.BlobContainerPermissions * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&#xA;override this.SetPermissionsAsync : Microsoft.WindowsAzure.Storage.Blob.BlobContainerPermissions * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="cloudBlobContainer.SetPermissionsAsync (permissions, accessCondition, options, operationContext, cancellationToken)" />
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
        <Parameter Name="permissions" Type="Microsoft.WindowsAzure.Storage.Blob.BlobContainerPermissions" />
        <Parameter Name="accessCondition" Type="Microsoft.WindowsAzure.Storage.AccessCondition" />
        <Parameter Name="options" Type="Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="permissions"><span data-ttu-id="5d9cd-921">Die Berechtigungen für den Container angewendet werden soll.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-921">The permissions to apply to the container.</span></span></param>
        <param name="accessCondition"><span data-ttu-id="5d9cd-922">Ein <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> -Objekt, das die Bedingung, die erfüllt sein müssen, damit die Anforderung darstellt, um den Vorgang fortzusetzen.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-922">An <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> object that represents the condition that must be met in order for the request to proceed.</span></span> <span data-ttu-id="5d9cd-923">Wenn <c>null</c>, keine Bedingung verwendet.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-923">If <c>null</c>, no condition is used.</span></span></param>
        <param name="options"><span data-ttu-id="5d9cd-924">Ein <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" /> -Objekt, das zusätzliche Optionen für die Anforderung angibt.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-924">A <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" /> object that specifies additional options for the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="5d9cd-925">Ein <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> -Objekt, das den Kontext für den aktuellen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-925">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="5d9cd-926">Ein <see cref="T:System.Threading.CancellationToken" />, das beim Warten auf den Abschluss einer Aufgabe überwacht werden soll.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-926">A <see cref="T:System.Threading.CancellationToken" /> to observe while waiting for a task to complete.</span></span></param>
        <summary>
            <span data-ttu-id="5d9cd-927">Initiiert einen asynchronen Vorgang, der Berechtigungen für den Container festgelegt.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-927">Initiates an asynchronous operation that sets permissions for the container.</span></span>
            </summary>
        <returns><span data-ttu-id="5d9cd-928">Ein <see cref="T:System.Threading.Tasks.Task" />-Objekt, das den asynchronen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-928">A <see cref="T:System.Threading.Tasks.Task" /> object that represents the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="StorageUri">
      <MemberSignature Language="C#" Value="public Microsoft.WindowsAzure.Storage.StorageUri StorageUri { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.WindowsAzure.Storage.StorageUri StorageUri" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.Blob.CloudBlobContainer.StorageUri" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property StorageUri As StorageUri" />
      <MemberSignature Language="F#" Value="member this.StorageUri : Microsoft.WindowsAzure.Storage.StorageUri" Usage="Microsoft.WindowsAzure.Storage.Blob.CloudBlobContainer.StorageUri" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Storage.StorageUri</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="5d9cd-929">Ruft die Container URIs für die primären und sekundären Speicherorte ab.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-929">Gets the container's URIs for both the primary and secondary locations.</span></span>
            </summary>
        <value><span data-ttu-id="5d9cd-930">Ein Objekt des Typs <see cref="P:Microsoft.WindowsAzure.Storage.Blob.CloudBlobContainer.StorageUri" /> , die Container-URIs für die primären und sekundären Speicherorte enthält.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-930">An object of type <see cref="P:Microsoft.WindowsAzure.Storage.Blob.CloudBlobContainer.StorageUri" /> containing the container's URIs for both the primary and secondary locations.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Uri">
      <MemberSignature Language="C#" Value="public Uri Uri { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Uri Uri" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.Blob.CloudBlobContainer.Uri" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Uri As Uri" />
      <MemberSignature Language="F#" Value="member this.Uri : Uri" Usage="Microsoft.WindowsAzure.Storage.Blob.CloudBlobContainer.Uri" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Uri</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="5d9cd-931">Ruft den Container-URI für den primären Speicherort ab.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-931">Gets the container's URI for the primary location.</span></span>
            </summary>
        <value><span data-ttu-id="5d9cd-932">Ein <see cref="T:System.Uri" /> , der den absoluten URI zum Container am primären Speicherort angibt.</span><span class="sxs-lookup"><span data-stu-id="5d9cd-932">A <see cref="T:System.Uri" /> specifying the absolute URI to the container at the primary location.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>