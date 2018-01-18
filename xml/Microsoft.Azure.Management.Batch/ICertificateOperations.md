<Type Name="ICertificateOperations" FullName="Microsoft.Azure.Management.Batch.ICertificateOperations">
  <TypeSignature Language="C#" Value="public interface ICertificateOperations" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract ICertificateOperations" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Batch.ICertificateOperations" />
  <TypeSignature Language="VB.NET" Value="Public Interface ICertificateOperations" />
  <TypeSignature Language="F#" Value="type ICertificateOperations = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="fbd77-101">CertificateOperations-Vorgänge.</span><span class="sxs-lookup"><span data-stu-id="fbd77-101">CertificateOperations operations.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="BeginCreateWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Batch.Models.Certificate,Microsoft.Azure.Management.Batch.Models.CertificateCreateHeaders&gt;&gt; BeginCreateWithHttpMessagesAsync (string resourceGroupName, string accountName, string certificateName, Microsoft.Azure.Management.Batch.Models.CertificateCreateOrUpdateParameters parameters, string ifMatch = null, string ifNoneMatch = null, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`2&lt;class Microsoft.Azure.Management.Batch.Models.Certificate, class Microsoft.Azure.Management.Batch.Models.CertificateCreateHeaders&gt;&gt; BeginCreateWithHttpMessagesAsync(string resourceGroupName, string accountName, string certificateName, class Microsoft.Azure.Management.Batch.Models.CertificateCreateOrUpdateParameters parameters, string ifMatch, string ifNoneMatch, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Batch.ICertificateOperations.BeginCreateWithHttpMessagesAsync(System.String,System.String,System.String,Microsoft.Azure.Management.Batch.Models.CertificateCreateOrUpdateParameters,System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member BeginCreateWithHttpMessagesAsync : string * string * string * Microsoft.Azure.Management.Batch.Models.CertificateCreateOrUpdateParameters * string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Batch.Models.Certificate, Microsoft.Azure.Management.Batch.Models.CertificateCreateHeaders&gt;&gt;" Usage="iCertificateOperations.BeginCreateWithHttpMessagesAsync (resourceGroupName, accountName, certificateName, parameters, ifMatch, ifNoneMatch, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Batch.Models.Certificate,Microsoft.Azure.Management.Batch.Models.CertificateCreateHeaders&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="certificateName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Batch.Models.CertificateCreateOrUpdateParameters" />
        <Parameter Name="ifMatch" Type="System.String" />
        <Parameter Name="ifNoneMatch" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="fbd77-102">Der Name der Ressourcengruppe, die das Batch-Konto enthält.</span><span class="sxs-lookup"><span data-stu-id="fbd77-102">The name of the resource group that contains the Batch account.</span></span>
            </param>
        <param name="accountName">
            <span data-ttu-id="fbd77-103">Der Name des Batch-Konto.</span><span class="sxs-lookup"><span data-stu-id="fbd77-103">The name of the Batch account.</span></span>
            </param>
        <param name="certificateName">
            <span data-ttu-id="fbd77-104">Der Bezeichner für das Zertifikat.</span><span class="sxs-lookup"><span data-stu-id="fbd77-104">The identifier for the certificate.</span></span> <span data-ttu-id="fbd77-105">Dies muss der Algorithmus und Fingerabdruck getrennt durch einen Bindestrich bestehen und muss die Daten in der Anforderung entsprechen.</span><span class="sxs-lookup"><span data-stu-id="fbd77-105">This must be made up of algorithm and thumbprint separated by a dash, and must match the certificate data in the request.</span></span> <span data-ttu-id="fbd77-106">Z. B. SHA1-a3d1c5.</span><span class="sxs-lookup"><span data-stu-id="fbd77-106">For example SHA1-a3d1c5.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="fbd77-107">Zusätzliche Parameter für die zertifikaterstellung.</span><span class="sxs-lookup"><span data-stu-id="fbd77-107">Additional parameters for certificate creation.</span></span>
            </param>
        <param name="ifMatch">
            <span data-ttu-id="fbd77-108">Die entitätszustandsversion (ETag) das Zertifikat zu aktualisieren.</span><span class="sxs-lookup"><span data-stu-id="fbd77-108">The entity state (ETag) version of the certificate to update.</span></span> <span data-ttu-id="fbd77-109">Der Wert "\*" können verwendet werden, um die Operation angewendet werden, wenn das Zertifikat bereits vorhanden ist.</span><span class="sxs-lookup"><span data-stu-id="fbd77-109">A value of "\*" can be used to apply the operation only if the certificate already exists.</span></span> <span data-ttu-id="fbd77-110">Wenn nicht angegeben, wird dieser Vorgang immer angewendet werden.</span><span class="sxs-lookup"><span data-stu-id="fbd77-110">If omitted, this operation will always be applied.</span></span>
            </param>
        <param name="ifNoneMatch">
            <span data-ttu-id="fbd77-111">Legen Sie auf "\*" um ein neues Zertifikat erstellt werden, sondern um zu verhindern, aktualisieren ein vorhandenes Zertifikat zu ermöglichen.</span><span class="sxs-lookup"><span data-stu-id="fbd77-111">Set to '\*' to allow a new certificate to be created, but to prevent updating an existing certificate.</span></span> <span data-ttu-id="fbd77-112">Andere Werte werden ignoriert.</span><span class="sxs-lookup"><span data-stu-id="fbd77-112">Other values will be ignored.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="fbd77-113">Die Header, die hinzugefügt werden auf Anforderung.</span><span class="sxs-lookup"><span data-stu-id="fbd77-113">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="fbd77-114">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="fbd77-114">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="fbd77-115">Erstellt ein neues Zertifikat in das angegebene Konto an.</span><span class="sxs-lookup"><span data-stu-id="fbd77-115">Creates a new certificate inside the specified account.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="fbd77-116">Wird ausgelöst, wenn der Vorgang einen ungültigen Statuscode zurückgegeben hat.</span><span class="sxs-lookup"><span data-stu-id="fbd77-116">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="fbd77-117">Wird ausgelöst, wenn nicht die Antwort zu deserialisieren.</span><span class="sxs-lookup"><span data-stu-id="fbd77-117">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="fbd77-118">Wird ausgelöst, wenn ein erforderlicher Parameter null ist.</span><span class="sxs-lookup"><span data-stu-id="fbd77-118">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="BeginDeleteWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationHeaderResponse&lt;Microsoft.Azure.Management.Batch.Models.CertificateDeleteHeaders&gt;&gt; BeginDeleteWithHttpMessagesAsync (string resourceGroupName, string accountName, string certificateName, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationHeaderResponse`1&lt;class Microsoft.Azure.Management.Batch.Models.CertificateDeleteHeaders&gt;&gt; BeginDeleteWithHttpMessagesAsync(string resourceGroupName, string accountName, string certificateName, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Batch.ICertificateOperations.BeginDeleteWithHttpMessagesAsync(System.String,System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member BeginDeleteWithHttpMessagesAsync : string * string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationHeaderResponse&lt;Microsoft.Azure.Management.Batch.Models.CertificateDeleteHeaders&gt;&gt;" Usage="iCertificateOperations.BeginDeleteWithHttpMessagesAsync (resourceGroupName, accountName, certificateName, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationHeaderResponse&lt;Microsoft.Azure.Management.Batch.Models.CertificateDeleteHeaders&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="certificateName" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="fbd77-119">Der Name der Ressourcengruppe, die das Batch-Konto enthält.</span><span class="sxs-lookup"><span data-stu-id="fbd77-119">The name of the resource group that contains the Batch account.</span></span>
            </param>
        <param name="accountName">
            <span data-ttu-id="fbd77-120">Der Name des Batch-Konto.</span><span class="sxs-lookup"><span data-stu-id="fbd77-120">The name of the Batch account.</span></span>
            </param>
        <param name="certificateName">
            <span data-ttu-id="fbd77-121">Der Bezeichner für das Zertifikat.</span><span class="sxs-lookup"><span data-stu-id="fbd77-121">The identifier for the certificate.</span></span> <span data-ttu-id="fbd77-122">Dies muss der Algorithmus und Fingerabdruck getrennt durch einen Bindestrich bestehen und muss die Daten in der Anforderung entsprechen.</span><span class="sxs-lookup"><span data-stu-id="fbd77-122">This must be made up of algorithm and thumbprint separated by a dash, and must match the certificate data in the request.</span></span> <span data-ttu-id="fbd77-123">Z. B. SHA1-a3d1c5.</span><span class="sxs-lookup"><span data-stu-id="fbd77-123">For example SHA1-a3d1c5.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="fbd77-124">Die Header, die hinzugefügt werden auf Anforderung.</span><span class="sxs-lookup"><span data-stu-id="fbd77-124">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="fbd77-125">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="fbd77-125">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="fbd77-126">Löscht das angegebene Zertifikat.</span><span class="sxs-lookup"><span data-stu-id="fbd77-126">Deletes the specified certificate.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="fbd77-127">Wird ausgelöst, wenn der Vorgang einen ungültigen Statuscode zurückgegeben hat.</span><span class="sxs-lookup"><span data-stu-id="fbd77-127">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="fbd77-128">Wird ausgelöst, wenn ein erforderlicher Parameter null ist.</span><span class="sxs-lookup"><span data-stu-id="fbd77-128">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="CancelDeletionWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Batch.Models.Certificate,Microsoft.Azure.Management.Batch.Models.CertificateCancelDeletionHeaders&gt;&gt; CancelDeletionWithHttpMessagesAsync (string resourceGroupName, string accountName, string certificateName, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`2&lt;class Microsoft.Azure.Management.Batch.Models.Certificate, class Microsoft.Azure.Management.Batch.Models.CertificateCancelDeletionHeaders&gt;&gt; CancelDeletionWithHttpMessagesAsync(string resourceGroupName, string accountName, string certificateName, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Batch.ICertificateOperations.CancelDeletionWithHttpMessagesAsync(System.String,System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member CancelDeletionWithHttpMessagesAsync : string * string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Batch.Models.Certificate, Microsoft.Azure.Management.Batch.Models.CertificateCancelDeletionHeaders&gt;&gt;" Usage="iCertificateOperations.CancelDeletionWithHttpMessagesAsync (resourceGroupName, accountName, certificateName, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Batch.Models.Certificate,Microsoft.Azure.Management.Batch.Models.CertificateCancelDeletionHeaders&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="certificateName" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="fbd77-129">Der Name der Ressourcengruppe, die das Batch-Konto enthält.</span><span class="sxs-lookup"><span data-stu-id="fbd77-129">The name of the resource group that contains the Batch account.</span></span>
            </param>
        <param name="accountName">
            <span data-ttu-id="fbd77-130">Der Name des Batch-Konto.</span><span class="sxs-lookup"><span data-stu-id="fbd77-130">The name of the Batch account.</span></span>
            </param>
        <param name="certificateName">
            <span data-ttu-id="fbd77-131">Der Bezeichner für das Zertifikat.</span><span class="sxs-lookup"><span data-stu-id="fbd77-131">The identifier for the certificate.</span></span> <span data-ttu-id="fbd77-132">Dies muss der Algorithmus und Fingerabdruck getrennt durch einen Bindestrich bestehen und muss die Daten in der Anforderung entsprechen.</span><span class="sxs-lookup"><span data-stu-id="fbd77-132">This must be made up of algorithm and thumbprint separated by a dash, and must match the certificate data in the request.</span></span> <span data-ttu-id="fbd77-133">Z. B. SHA1-a3d1c5.</span><span class="sxs-lookup"><span data-stu-id="fbd77-133">For example SHA1-a3d1c5.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="fbd77-134">Die Header, die hinzugefügt werden auf Anforderung.</span><span class="sxs-lookup"><span data-stu-id="fbd77-134">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="fbd77-135">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="fbd77-135">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="fbd77-136">Bricht einen fehlerhaften Löschvorgang eines Zertifikats aus dem angegebenen Konto ab.</span><span class="sxs-lookup"><span data-stu-id="fbd77-136">Cancels a failed deletion of a certificate from the specified account.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="fbd77-137">Wenn Sie versuchen, löschen ein Zertifikat, das von einem Pool verwendet wird oder compute-Knoten, ändert den Status des Zertifikats in DeleteFailed aus.</span><span class="sxs-lookup"><span data-stu-id="fbd77-137">If you try to delete a certificate that is being used by a pool or compute node, the status of the certificate changes to deleteFailed.</span></span> <span data-ttu-id="fbd77-138">Wenn Sie sich entscheiden, dass Sie das Zertifikat weiterhin zu verwenden möchten, können Sie diesen Vorgang verwenden, um den Status des Zertifikats erneut auf aktiv festzulegen.</span><span class="sxs-lookup"><span data-stu-id="fbd77-138">If you decide that you want to continue using the certificate, you can use this operation to set the status of the certificate back to active.</span></span> <span data-ttu-id="fbd77-139">Wenn Sie das Zertifikat löschen möchten, müssen Sie nicht, diesen Vorgang auszuführen, nach dem fehlerhaften Löschvorgang.</span><span class="sxs-lookup"><span data-stu-id="fbd77-139">If you intend to delete the certificate, you do not need to run this operation after the deletion failed.</span></span> <span data-ttu-id="fbd77-140">Sie müssen sicherstellen, dass das Zertifikat nicht von Ressourcen verwendet wird, und klicken Sie dann Sie es beim Löschen des Zertifikats versuchen.</span><span class="sxs-lookup"><span data-stu-id="fbd77-140">You must make sure that the certificate is not being used by any resources, and then you can try again to delete the certificate.</span></span>
            </remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="fbd77-141">Wird ausgelöst, wenn der Vorgang einen ungültigen Statuscode zurückgegeben hat.</span><span class="sxs-lookup"><span data-stu-id="fbd77-141">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="fbd77-142">Wird ausgelöst, wenn nicht die Antwort zu deserialisieren.</span><span class="sxs-lookup"><span data-stu-id="fbd77-142">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="fbd77-143">Wird ausgelöst, wenn ein erforderlicher Parameter null ist.</span><span class="sxs-lookup"><span data-stu-id="fbd77-143">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="CreateWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Batch.Models.Certificate,Microsoft.Azure.Management.Batch.Models.CertificateCreateHeaders&gt;&gt; CreateWithHttpMessagesAsync (string resourceGroupName, string accountName, string certificateName, Microsoft.Azure.Management.Batch.Models.CertificateCreateOrUpdateParameters parameters, string ifMatch = null, string ifNoneMatch = null, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`2&lt;class Microsoft.Azure.Management.Batch.Models.Certificate, class Microsoft.Azure.Management.Batch.Models.CertificateCreateHeaders&gt;&gt; CreateWithHttpMessagesAsync(string resourceGroupName, string accountName, string certificateName, class Microsoft.Azure.Management.Batch.Models.CertificateCreateOrUpdateParameters parameters, string ifMatch, string ifNoneMatch, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Batch.ICertificateOperations.CreateWithHttpMessagesAsync(System.String,System.String,System.String,Microsoft.Azure.Management.Batch.Models.CertificateCreateOrUpdateParameters,System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member CreateWithHttpMessagesAsync : string * string * string * Microsoft.Azure.Management.Batch.Models.CertificateCreateOrUpdateParameters * string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Batch.Models.Certificate, Microsoft.Azure.Management.Batch.Models.CertificateCreateHeaders&gt;&gt;" Usage="iCertificateOperations.CreateWithHttpMessagesAsync (resourceGroupName, accountName, certificateName, parameters, ifMatch, ifNoneMatch, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Batch.Models.Certificate,Microsoft.Azure.Management.Batch.Models.CertificateCreateHeaders&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="certificateName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Batch.Models.CertificateCreateOrUpdateParameters" />
        <Parameter Name="ifMatch" Type="System.String" />
        <Parameter Name="ifNoneMatch" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="fbd77-144">Der Name der Ressourcengruppe, die das Batch-Konto enthält.</span><span class="sxs-lookup"><span data-stu-id="fbd77-144">The name of the resource group that contains the Batch account.</span></span>
            </param>
        <param name="accountName">
            <span data-ttu-id="fbd77-145">Der Name des Batch-Konto.</span><span class="sxs-lookup"><span data-stu-id="fbd77-145">The name of the Batch account.</span></span>
            </param>
        <param name="certificateName">
            <span data-ttu-id="fbd77-146">Der Bezeichner für das Zertifikat.</span><span class="sxs-lookup"><span data-stu-id="fbd77-146">The identifier for the certificate.</span></span> <span data-ttu-id="fbd77-147">Dies muss der Algorithmus und Fingerabdruck getrennt durch einen Bindestrich bestehen und muss die Daten in der Anforderung entsprechen.</span><span class="sxs-lookup"><span data-stu-id="fbd77-147">This must be made up of algorithm and thumbprint separated by a dash, and must match the certificate data in the request.</span></span> <span data-ttu-id="fbd77-148">Z. B. SHA1-a3d1c5.</span><span class="sxs-lookup"><span data-stu-id="fbd77-148">For example SHA1-a3d1c5.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="fbd77-149">Zusätzliche Parameter für die zertifikaterstellung.</span><span class="sxs-lookup"><span data-stu-id="fbd77-149">Additional parameters for certificate creation.</span></span>
            </param>
        <param name="ifMatch">
            <span data-ttu-id="fbd77-150">Die entitätszustandsversion (ETag) das Zertifikat zu aktualisieren.</span><span class="sxs-lookup"><span data-stu-id="fbd77-150">The entity state (ETag) version of the certificate to update.</span></span> <span data-ttu-id="fbd77-151">Der Wert "\*" können verwendet werden, um die Operation angewendet werden, wenn das Zertifikat bereits vorhanden ist.</span><span class="sxs-lookup"><span data-stu-id="fbd77-151">A value of "\*" can be used to apply the operation only if the certificate already exists.</span></span> <span data-ttu-id="fbd77-152">Wenn nicht angegeben, wird dieser Vorgang immer angewendet werden.</span><span class="sxs-lookup"><span data-stu-id="fbd77-152">If omitted, this operation will always be applied.</span></span>
            </param>
        <param name="ifNoneMatch">
            <span data-ttu-id="fbd77-153">Legen Sie auf "\*" um ein neues Zertifikat erstellt werden, sondern um zu verhindern, aktualisieren ein vorhandenes Zertifikat zu ermöglichen.</span><span class="sxs-lookup"><span data-stu-id="fbd77-153">Set to '\*' to allow a new certificate to be created, but to prevent updating an existing certificate.</span></span> <span data-ttu-id="fbd77-154">Andere Werte werden ignoriert.</span><span class="sxs-lookup"><span data-stu-id="fbd77-154">Other values will be ignored.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="fbd77-155">Die Header, die hinzugefügt werden auf Anforderung.</span><span class="sxs-lookup"><span data-stu-id="fbd77-155">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="fbd77-156">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="fbd77-156">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="fbd77-157">Erstellt ein neues Zertifikat in das angegebene Konto an.</span><span class="sxs-lookup"><span data-stu-id="fbd77-157">Creates a new certificate inside the specified account.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="fbd77-158">Wird ausgelöst, wenn der Vorgang einen ungültigen Statuscode zurückgegeben hat.</span><span class="sxs-lookup"><span data-stu-id="fbd77-158">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="fbd77-159">Wird ausgelöst, wenn nicht die Antwort zu deserialisieren.</span><span class="sxs-lookup"><span data-stu-id="fbd77-159">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="fbd77-160">Wird ausgelöst, wenn ein erforderlicher Parameter null ist.</span><span class="sxs-lookup"><span data-stu-id="fbd77-160">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="DeleteWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationHeaderResponse&lt;Microsoft.Azure.Management.Batch.Models.CertificateDeleteHeaders&gt;&gt; DeleteWithHttpMessagesAsync (string resourceGroupName, string accountName, string certificateName, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationHeaderResponse`1&lt;class Microsoft.Azure.Management.Batch.Models.CertificateDeleteHeaders&gt;&gt; DeleteWithHttpMessagesAsync(string resourceGroupName, string accountName, string certificateName, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Batch.ICertificateOperations.DeleteWithHttpMessagesAsync(System.String,System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member DeleteWithHttpMessagesAsync : string * string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationHeaderResponse&lt;Microsoft.Azure.Management.Batch.Models.CertificateDeleteHeaders&gt;&gt;" Usage="iCertificateOperations.DeleteWithHttpMessagesAsync (resourceGroupName, accountName, certificateName, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationHeaderResponse&lt;Microsoft.Azure.Management.Batch.Models.CertificateDeleteHeaders&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="certificateName" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="fbd77-161">Der Name der Ressourcengruppe, die das Batch-Konto enthält.</span><span class="sxs-lookup"><span data-stu-id="fbd77-161">The name of the resource group that contains the Batch account.</span></span>
            </param>
        <param name="accountName">
            <span data-ttu-id="fbd77-162">Der Name des Batch-Konto.</span><span class="sxs-lookup"><span data-stu-id="fbd77-162">The name of the Batch account.</span></span>
            </param>
        <param name="certificateName">
            <span data-ttu-id="fbd77-163">Der Bezeichner für das Zertifikat.</span><span class="sxs-lookup"><span data-stu-id="fbd77-163">The identifier for the certificate.</span></span> <span data-ttu-id="fbd77-164">Dies muss der Algorithmus und Fingerabdruck getrennt durch einen Bindestrich bestehen und muss die Daten in der Anforderung entsprechen.</span><span class="sxs-lookup"><span data-stu-id="fbd77-164">This must be made up of algorithm and thumbprint separated by a dash, and must match the certificate data in the request.</span></span> <span data-ttu-id="fbd77-165">Z. B. SHA1-a3d1c5.</span><span class="sxs-lookup"><span data-stu-id="fbd77-165">For example SHA1-a3d1c5.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="fbd77-166">Die Header, die hinzugefügt werden auf Anforderung.</span><span class="sxs-lookup"><span data-stu-id="fbd77-166">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="fbd77-167">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="fbd77-167">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="fbd77-168">Löscht das angegebene Zertifikat.</span><span class="sxs-lookup"><span data-stu-id="fbd77-168">Deletes the specified certificate.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="fbd77-169">Wird ausgelöst, wenn der Vorgang einen ungültigen Statuscode zurückgegeben hat.</span><span class="sxs-lookup"><span data-stu-id="fbd77-169">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="fbd77-170">Wird ausgelöst, wenn ein erforderlicher Parameter null ist.</span><span class="sxs-lookup"><span data-stu-id="fbd77-170">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="GetWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Batch.Models.Certificate,Microsoft.Azure.Management.Batch.Models.CertificateGetHeaders&gt;&gt; GetWithHttpMessagesAsync (string resourceGroupName, string accountName, string certificateName, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`2&lt;class Microsoft.Azure.Management.Batch.Models.Certificate, class Microsoft.Azure.Management.Batch.Models.CertificateGetHeaders&gt;&gt; GetWithHttpMessagesAsync(string resourceGroupName, string accountName, string certificateName, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Batch.ICertificateOperations.GetWithHttpMessagesAsync(System.String,System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetWithHttpMessagesAsync : string * string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Batch.Models.Certificate, Microsoft.Azure.Management.Batch.Models.CertificateGetHeaders&gt;&gt;" Usage="iCertificateOperations.GetWithHttpMessagesAsync (resourceGroupName, accountName, certificateName, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Batch.Models.Certificate,Microsoft.Azure.Management.Batch.Models.CertificateGetHeaders&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="certificateName" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="fbd77-171">Der Name der Ressourcengruppe, die das Batch-Konto enthält.</span><span class="sxs-lookup"><span data-stu-id="fbd77-171">The name of the resource group that contains the Batch account.</span></span>
            </param>
        <param name="accountName">
            <span data-ttu-id="fbd77-172">Der Name des Batch-Konto.</span><span class="sxs-lookup"><span data-stu-id="fbd77-172">The name of the Batch account.</span></span>
            </param>
        <param name="certificateName">
            <span data-ttu-id="fbd77-173">Der Bezeichner für das Zertifikat.</span><span class="sxs-lookup"><span data-stu-id="fbd77-173">The identifier for the certificate.</span></span> <span data-ttu-id="fbd77-174">Dies muss der Algorithmus und Fingerabdruck getrennt durch einen Bindestrich bestehen und muss die Daten in der Anforderung entsprechen.</span><span class="sxs-lookup"><span data-stu-id="fbd77-174">This must be made up of algorithm and thumbprint separated by a dash, and must match the certificate data in the request.</span></span> <span data-ttu-id="fbd77-175">Z. B. SHA1-a3d1c5.</span><span class="sxs-lookup"><span data-stu-id="fbd77-175">For example SHA1-a3d1c5.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="fbd77-176">Die Header, die hinzugefügt werden auf Anforderung.</span><span class="sxs-lookup"><span data-stu-id="fbd77-176">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="fbd77-177">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="fbd77-177">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="fbd77-178">Ruft Informationen über das angegebene Zertifikat ab.</span><span class="sxs-lookup"><span data-stu-id="fbd77-178">Gets information about the specified certificate.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="fbd77-179">Wird ausgelöst, wenn der Vorgang einen ungültigen Statuscode zurückgegeben hat.</span><span class="sxs-lookup"><span data-stu-id="fbd77-179">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="fbd77-180">Wird ausgelöst, wenn nicht die Antwort zu deserialisieren.</span><span class="sxs-lookup"><span data-stu-id="fbd77-180">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="fbd77-181">Wird ausgelöst, wenn ein erforderlicher Parameter null ist.</span><span class="sxs-lookup"><span data-stu-id="fbd77-181">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="ListByBatchAccountNextWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Batch.Models.Certificate&gt;&gt;&gt; ListByBatchAccountNextWithHttpMessagesAsync (string nextPageLink, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Batch.Models.Certificate&gt;&gt;&gt; ListByBatchAccountNextWithHttpMessagesAsync(string nextPageLink, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Batch.ICertificateOperations.ListByBatchAccountNextWithHttpMessagesAsync(System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListByBatchAccountNextWithHttpMessagesAsync : string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Batch.Models.Certificate&gt;&gt;&gt;" Usage="iCertificateOperations.ListByBatchAccountNextWithHttpMessagesAsync (nextPageLink, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Batch.Models.Certificate&gt;&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="nextPageLink">
            <span data-ttu-id="fbd77-182">Die "NextLink" aus dem vorherigen erfolgreichen Aufruf List-Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="fbd77-182">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="fbd77-183">Die Header, die hinzugefügt werden auf Anforderung.</span><span class="sxs-lookup"><span data-stu-id="fbd77-183">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="fbd77-184">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="fbd77-184">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="fbd77-185">Zeigt eine Liste aller Zertifikate in das angegebene Konto.</span><span class="sxs-lookup"><span data-stu-id="fbd77-185">Lists all of the certificates in the specified account.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="fbd77-186">Wird ausgelöst, wenn der Vorgang einen ungültigen Statuscode zurückgegeben hat.</span><span class="sxs-lookup"><span data-stu-id="fbd77-186">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="fbd77-187">Wird ausgelöst, wenn nicht die Antwort zu deserialisieren.</span><span class="sxs-lookup"><span data-stu-id="fbd77-187">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="fbd77-188">Wird ausgelöst, wenn ein erforderlicher Parameter null ist.</span><span class="sxs-lookup"><span data-stu-id="fbd77-188">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="ListByBatchAccountWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Batch.Models.Certificate&gt;&gt;&gt; ListByBatchAccountWithHttpMessagesAsync (string resourceGroupName, string accountName, Nullable&lt;int&gt; maxresults = null, string select = null, string filter = null, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Batch.Models.Certificate&gt;&gt;&gt; ListByBatchAccountWithHttpMessagesAsync(string resourceGroupName, string accountName, valuetype System.Nullable`1&lt;int32&gt; maxresults, string select, string filter, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Batch.ICertificateOperations.ListByBatchAccountWithHttpMessagesAsync(System.String,System.String,System.Nullable{System.Int32},System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListByBatchAccountWithHttpMessagesAsync : string * string * Nullable&lt;int&gt; * string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Batch.Models.Certificate&gt;&gt;&gt;" Usage="iCertificateOperations.ListByBatchAccountWithHttpMessagesAsync (resourceGroupName, accountName, maxresults, select, filter, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Batch.Models.Certificate&gt;&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="maxresults" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="select" Type="System.String" />
        <Parameter Name="filter" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="fbd77-189">Der Name der Ressourcengruppe, die das Batch-Konto enthält.</span><span class="sxs-lookup"><span data-stu-id="fbd77-189">The name of the resource group that contains the Batch account.</span></span>
            </param>
        <param name="accountName">
            <span data-ttu-id="fbd77-190">Der Name des Batch-Konto.</span><span class="sxs-lookup"><span data-stu-id="fbd77-190">The name of the Batch account.</span></span>
            </param>
        <param name="maxresults">
            <span data-ttu-id="fbd77-191">Die maximale Anzahl von Elementen, die in der Antwort zurückgegeben.</span><span class="sxs-lookup"><span data-stu-id="fbd77-191">The maximum number of items to return in the response.</span></span>
            </param>
        <param name="select">
            <span data-ttu-id="fbd77-192">Durch Trennzeichen getrennte Liste von Eigenschaften, die zurückgegeben werden sollen.</span><span class="sxs-lookup"><span data-stu-id="fbd77-192">Comma separated list of properties that should be returned.</span></span> <span data-ttu-id="fbd77-193">z. B. "Eigenschaften/ProvisioningState".</span><span class="sxs-lookup"><span data-stu-id="fbd77-193">e.g. "properties/provisioningState".</span></span> <span data-ttu-id="fbd77-194">Nur die ersten Ebene unter Eigenschaften Eigenschaften / zur Auswahl gültig sind.</span><span class="sxs-lookup"><span data-stu-id="fbd77-194">Only top level properties under properties/ are valid for selection.</span></span>
            </param>
        <param name="filter">
            <span data-ttu-id="fbd77-195">OData-Filterausdruck.</span><span class="sxs-lookup"><span data-stu-id="fbd77-195">OData filter expression.</span></span> <span data-ttu-id="fbd77-196">Gültige Eigenschaften für die Filterung sind "Eigenschaften/ProvisioningState", "Eigenschaften/ProvisioningStateTransitionTime", "Name".</span><span class="sxs-lookup"><span data-stu-id="fbd77-196">Valid properties for filtering are "properties/provisioningState", "properties/provisioningStateTransitionTime", "name".</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="fbd77-197">Die Header, die hinzugefügt werden auf Anforderung.</span><span class="sxs-lookup"><span data-stu-id="fbd77-197">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="fbd77-198">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="fbd77-198">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="fbd77-199">Zeigt eine Liste aller Zertifikate in das angegebene Konto.</span><span class="sxs-lookup"><span data-stu-id="fbd77-199">Lists all of the certificates in the specified account.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="fbd77-200">Wird ausgelöst, wenn der Vorgang einen ungültigen Statuscode zurückgegeben hat.</span><span class="sxs-lookup"><span data-stu-id="fbd77-200">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="fbd77-201">Wird ausgelöst, wenn nicht die Antwort zu deserialisieren.</span><span class="sxs-lookup"><span data-stu-id="fbd77-201">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="fbd77-202">Wird ausgelöst, wenn ein erforderlicher Parameter null ist.</span><span class="sxs-lookup"><span data-stu-id="fbd77-202">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="UpdateWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Batch.Models.Certificate,Microsoft.Azure.Management.Batch.Models.CertificateUpdateHeaders&gt;&gt; UpdateWithHttpMessagesAsync (string resourceGroupName, string accountName, string certificateName, Microsoft.Azure.Management.Batch.Models.CertificateCreateOrUpdateParameters parameters, string ifMatch = null, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`2&lt;class Microsoft.Azure.Management.Batch.Models.Certificate, class Microsoft.Azure.Management.Batch.Models.CertificateUpdateHeaders&gt;&gt; UpdateWithHttpMessagesAsync(string resourceGroupName, string accountName, string certificateName, class Microsoft.Azure.Management.Batch.Models.CertificateCreateOrUpdateParameters parameters, string ifMatch, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Batch.ICertificateOperations.UpdateWithHttpMessagesAsync(System.String,System.String,System.String,Microsoft.Azure.Management.Batch.Models.CertificateCreateOrUpdateParameters,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member UpdateWithHttpMessagesAsync : string * string * string * Microsoft.Azure.Management.Batch.Models.CertificateCreateOrUpdateParameters * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Batch.Models.Certificate, Microsoft.Azure.Management.Batch.Models.CertificateUpdateHeaders&gt;&gt;" Usage="iCertificateOperations.UpdateWithHttpMessagesAsync (resourceGroupName, accountName, certificateName, parameters, ifMatch, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Batch.Models.Certificate,Microsoft.Azure.Management.Batch.Models.CertificateUpdateHeaders&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="certificateName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Batch.Models.CertificateCreateOrUpdateParameters" />
        <Parameter Name="ifMatch" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="fbd77-203">Der Name der Ressourcengruppe, die das Batch-Konto enthält.</span><span class="sxs-lookup"><span data-stu-id="fbd77-203">The name of the resource group that contains the Batch account.</span></span>
            </param>
        <param name="accountName">
            <span data-ttu-id="fbd77-204">Der Name des Batch-Konto.</span><span class="sxs-lookup"><span data-stu-id="fbd77-204">The name of the Batch account.</span></span>
            </param>
        <param name="certificateName">
            <span data-ttu-id="fbd77-205">Der Bezeichner für das Zertifikat.</span><span class="sxs-lookup"><span data-stu-id="fbd77-205">The identifier for the certificate.</span></span> <span data-ttu-id="fbd77-206">Dies muss der Algorithmus und Fingerabdruck getrennt durch einen Bindestrich bestehen und muss die Daten in der Anforderung entsprechen.</span><span class="sxs-lookup"><span data-stu-id="fbd77-206">This must be made up of algorithm and thumbprint separated by a dash, and must match the certificate data in the request.</span></span> <span data-ttu-id="fbd77-207">Z. B. SHA1-a3d1c5.</span><span class="sxs-lookup"><span data-stu-id="fbd77-207">For example SHA1-a3d1c5.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="fbd77-208">Das Zertifikat zu aktualisierenden Entität.</span><span class="sxs-lookup"><span data-stu-id="fbd77-208">Certificate entity to update.</span></span>
            </param>
        <param name="ifMatch">
            <span data-ttu-id="fbd77-209">Die entitätszustandsversion (ETag) das Zertifikat zu aktualisieren.</span><span class="sxs-lookup"><span data-stu-id="fbd77-209">The entity state (ETag) version of the certificate to update.</span></span> <span data-ttu-id="fbd77-210">Dieser Wert ausgelassen oder auf festgelegt werden kann "\*" um den Vorgang ohne Bedingung anzuwenden.</span><span class="sxs-lookup"><span data-stu-id="fbd77-210">This value can be omitted or set to "\*" to apply the operation unconditionally.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="fbd77-211">Die Header, die hinzugefügt werden auf Anforderung.</span><span class="sxs-lookup"><span data-stu-id="fbd77-211">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="fbd77-212">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="fbd77-212">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="fbd77-213">Aktualisiert die Eigenschaften eines vorhandenen Zertifikats an.</span><span class="sxs-lookup"><span data-stu-id="fbd77-213">Updates the properties of an existing certificate.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="fbd77-214">Wird ausgelöst, wenn der Vorgang einen ungültigen Statuscode zurückgegeben hat.</span><span class="sxs-lookup"><span data-stu-id="fbd77-214">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="fbd77-215">Wird ausgelöst, wenn nicht die Antwort zu deserialisieren.</span><span class="sxs-lookup"><span data-stu-id="fbd77-215">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="fbd77-216">Wird ausgelöst, wenn ein erforderlicher Parameter null ist.</span><span class="sxs-lookup"><span data-stu-id="fbd77-216">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>