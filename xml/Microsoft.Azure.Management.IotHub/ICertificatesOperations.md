<Type Name="ICertificatesOperations" FullName="Microsoft.Azure.Management.IotHub.ICertificatesOperations">
  <TypeSignature Language="C#" Value="public interface ICertificatesOperations" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract ICertificatesOperations" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.IotHub.ICertificatesOperations" />
  <TypeSignature Language="VB.NET" Value="Public Interface ICertificatesOperations" />
  <TypeSignature Language="F#" Value="type ICertificatesOperations = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.IotHub</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="c8575-101">CertificatesOperations-Vorgänge.</span><span class="sxs-lookup"><span data-stu-id="c8575-101">CertificatesOperations operations.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="CreateOrUpdateWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.IotHub.Models.CertificateDescription&gt;&gt; CreateOrUpdateWithHttpMessagesAsync (string resourceGroupName, string resourceName, string certificateName, Microsoft.Azure.Management.IotHub.Models.CertificateBodyDescription certificateDescription, string ifMatch = null, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Management.IotHub.Models.CertificateDescription&gt;&gt; CreateOrUpdateWithHttpMessagesAsync(string resourceGroupName, string resourceName, string certificateName, class Microsoft.Azure.Management.IotHub.Models.CertificateBodyDescription certificateDescription, string ifMatch, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.IotHub.ICertificatesOperations.CreateOrUpdateWithHttpMessagesAsync(System.String,System.String,System.String,Microsoft.Azure.Management.IotHub.Models.CertificateBodyDescription,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member CreateOrUpdateWithHttpMessagesAsync : string * string * string * Microsoft.Azure.Management.IotHub.Models.CertificateBodyDescription * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.IotHub.Models.CertificateDescription&gt;&gt;" Usage="iCertificatesOperations.CreateOrUpdateWithHttpMessagesAsync (resourceGroupName, resourceName, certificateName, certificateDescription, ifMatch, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.IotHub</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.IotHub.Models.CertificateDescription&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="resourceName" Type="System.String" />
        <Parameter Name="certificateName" Type="System.String" />
        <Parameter Name="certificateDescription" Type="Microsoft.Azure.Management.IotHub.Models.CertificateBodyDescription" />
        <Parameter Name="ifMatch" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="c8575-102">Der Name der Ressourcengruppe, die den IoT Hub enthält.</span><span class="sxs-lookup"><span data-stu-id="c8575-102">The name of the resource group that contains the IoT hub.</span></span>
            </param>
        <param name="resourceName">
            <span data-ttu-id="c8575-103">Der Name der IoT Hub.</span><span class="sxs-lookup"><span data-stu-id="c8575-103">The name of the IoT hub.</span></span>
            </param>
        <param name="certificateName">
            <span data-ttu-id="c8575-104">Der Name des Zertifikats</span><span class="sxs-lookup"><span data-stu-id="c8575-104">The name of the certificate</span></span>
            </param>
        <param name="certificateDescription">
            <span data-ttu-id="c8575-105">Der Text des Zertifikats.</span><span class="sxs-lookup"><span data-stu-id="c8575-105">The certificate body.</span></span>
            </param>
        <param name="ifMatch">
            <span data-ttu-id="c8575-106">ETag des Zertifikats.</span><span class="sxs-lookup"><span data-stu-id="c8575-106">ETag of the Certificate.</span></span> <span data-ttu-id="c8575-107">Geben Sie zum Erstellen eines neuen Zertifikats.</span><span class="sxs-lookup"><span data-stu-id="c8575-107">Do not specify for creating a brand new certificate.</span></span> <span data-ttu-id="c8575-108">Zum Aktualisieren eines vorhandenen Zertifikats erforderlich.</span><span class="sxs-lookup"><span data-stu-id="c8575-108">Required to update an existing certificate.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="c8575-109">Die Header, die hinzugefügt werden auf Anforderung.</span><span class="sxs-lookup"><span data-stu-id="c8575-109">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="c8575-110">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="c8575-110">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="c8575-111">Hochladen des Zertifikats mit dem IoT Hub.</span><span class="sxs-lookup"><span data-stu-id="c8575-111">Upload the certificate to the IoT hub.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="c8575-112">Fügt die neuen oder vorhandenen Zertifikats ersetzt.</span><span class="sxs-lookup"><span data-stu-id="c8575-112">Adds new or replaces existing certificate.</span></span>
            </remarks>
        <exception cref="T:Microsoft.Azure.Management.IotHub.Models.ErrorDetailsException">
            <span data-ttu-id="c8575-113">Wird ausgelöst, wenn der Vorgang einen ungültigen Statuscode zurückgegeben hat.</span><span class="sxs-lookup"><span data-stu-id="c8575-113">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="c8575-114">Wird ausgelöst, wenn nicht die Antwort zu deserialisieren.</span><span class="sxs-lookup"><span data-stu-id="c8575-114">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="c8575-115">Wird ausgelöst, wenn ein erforderlicher Parameter null ist.</span><span class="sxs-lookup"><span data-stu-id="c8575-115">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="DeleteWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt; DeleteWithHttpMessagesAsync (string resourceGroupName, string resourceName, string certificateName, string ifMatch, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse&gt; DeleteWithHttpMessagesAsync(string resourceGroupName, string resourceName, string certificateName, string ifMatch, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.IotHub.ICertificatesOperations.DeleteWithHttpMessagesAsync(System.String,System.String,System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member DeleteWithHttpMessagesAsync : string * string * string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt;" Usage="iCertificatesOperations.DeleteWithHttpMessagesAsync (resourceGroupName, resourceName, certificateName, ifMatch, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.IotHub</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="resourceName" Type="System.String" />
        <Parameter Name="certificateName" Type="System.String" />
        <Parameter Name="ifMatch" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="c8575-116">Der Name der Ressourcengruppe, die den IoT Hub enthält.</span><span class="sxs-lookup"><span data-stu-id="c8575-116">The name of the resource group that contains the IoT hub.</span></span>
            </param>
        <param name="resourceName">
            <span data-ttu-id="c8575-117">Der Name der IoT Hub.</span><span class="sxs-lookup"><span data-stu-id="c8575-117">The name of the IoT hub.</span></span>
            </param>
        <param name="certificateName">
            <span data-ttu-id="c8575-118">Der Name des Zertifikats</span><span class="sxs-lookup"><span data-stu-id="c8575-118">The name of the certificate</span></span>
            </param>
        <param name="ifMatch">
            <span data-ttu-id="c8575-119">ETag des Zertifikats.</span><span class="sxs-lookup"><span data-stu-id="c8575-119">ETag of the Certificate.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="c8575-120">Die Header, die hinzugefügt werden auf Anforderung.</span><span class="sxs-lookup"><span data-stu-id="c8575-120">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="c8575-121">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="c8575-121">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="c8575-122">Löschen einer X509 Zertifikat.</span><span class="sxs-lookup"><span data-stu-id="c8575-122">Delete an X509 certificate.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="c8575-123">Löscht ein vorhandenes X509 Zertifikat oder bewirkt nichts, wenn er nicht vorhanden ist.</span><span class="sxs-lookup"><span data-stu-id="c8575-123">Deletes an existing X509 certificate or does nothing if it does not exist.</span></span>
            </remarks>
        <exception cref="T:Microsoft.Azure.Management.IotHub.Models.ErrorDetailsException">
            <span data-ttu-id="c8575-124">Wird ausgelöst, wenn der Vorgang einen ungültigen Statuscode zurückgegeben hat.</span><span class="sxs-lookup"><span data-stu-id="c8575-124">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="c8575-125">Wird ausgelöst, wenn ein erforderlicher Parameter null ist.</span><span class="sxs-lookup"><span data-stu-id="c8575-125">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="GenerateVerificationCodeWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.IotHub.Models.CertificateWithNonceDescription&gt;&gt; GenerateVerificationCodeWithHttpMessagesAsync (string resourceGroupName, string resourceName, string certificateName, string ifMatch, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Management.IotHub.Models.CertificateWithNonceDescription&gt;&gt; GenerateVerificationCodeWithHttpMessagesAsync(string resourceGroupName, string resourceName, string certificateName, string ifMatch, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.IotHub.ICertificatesOperations.GenerateVerificationCodeWithHttpMessagesAsync(System.String,System.String,System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GenerateVerificationCodeWithHttpMessagesAsync : string * string * string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.IotHub.Models.CertificateWithNonceDescription&gt;&gt;" Usage="iCertificatesOperations.GenerateVerificationCodeWithHttpMessagesAsync (resourceGroupName, resourceName, certificateName, ifMatch, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.IotHub</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.IotHub.Models.CertificateWithNonceDescription&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="resourceName" Type="System.String" />
        <Parameter Name="certificateName" Type="System.String" />
        <Parameter Name="ifMatch" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="c8575-126">Der Name der Ressourcengruppe, die den IoT Hub enthält.</span><span class="sxs-lookup"><span data-stu-id="c8575-126">The name of the resource group that contains the IoT hub.</span></span>
            </param>
        <param name="resourceName">
            <span data-ttu-id="c8575-127">Der Name der IoT Hub.</span><span class="sxs-lookup"><span data-stu-id="c8575-127">The name of the IoT hub.</span></span>
            </param>
        <param name="certificateName">
            <span data-ttu-id="c8575-128">Der Name des Zertifikats</span><span class="sxs-lookup"><span data-stu-id="c8575-128">The name of the certificate</span></span>
            </param>
        <param name="ifMatch">
            <span data-ttu-id="c8575-129">ETag des Zertifikats.</span><span class="sxs-lookup"><span data-stu-id="c8575-129">ETag of the Certificate.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="c8575-130">Die Header, die hinzugefügt werden auf Anforderung.</span><span class="sxs-lookup"><span data-stu-id="c8575-130">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="c8575-131">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="c8575-131">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="c8575-132">Überprüfungscode für den Nachweis des rechtmäßigen Besitzes Flusses zu generieren.</span><span class="sxs-lookup"><span data-stu-id="c8575-132">Generate verification code for proof of possession flow.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="c8575-133">Generiert Überprüfungscode für den Nachweis des rechtmäßigen Besitzes Flusses.</span><span class="sxs-lookup"><span data-stu-id="c8575-133">Generates verification code for proof of possession flow.</span></span> <span data-ttu-id="c8575-134">Der Überprüfungscode dienen zum Generieren eines Zertifikats Endknoten.</span><span class="sxs-lookup"><span data-stu-id="c8575-134">The verification code will be used to generate a leaf certificate.</span></span>
            </remarks>
        <exception cref="T:Microsoft.Azure.Management.IotHub.Models.ErrorDetailsException">
            <span data-ttu-id="c8575-135">Wird ausgelöst, wenn der Vorgang einen ungültigen Statuscode zurückgegeben hat.</span><span class="sxs-lookup"><span data-stu-id="c8575-135">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="c8575-136">Wird ausgelöst, wenn nicht die Antwort zu deserialisieren.</span><span class="sxs-lookup"><span data-stu-id="c8575-136">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="c8575-137">Wird ausgelöst, wenn ein erforderlicher Parameter null ist.</span><span class="sxs-lookup"><span data-stu-id="c8575-137">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="GetWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.IotHub.Models.CertificateDescription&gt;&gt; GetWithHttpMessagesAsync (string resourceGroupName, string resourceName, string certificateName, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Management.IotHub.Models.CertificateDescription&gt;&gt; GetWithHttpMessagesAsync(string resourceGroupName, string resourceName, string certificateName, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.IotHub.ICertificatesOperations.GetWithHttpMessagesAsync(System.String,System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetWithHttpMessagesAsync : string * string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.IotHub.Models.CertificateDescription&gt;&gt;" Usage="iCertificatesOperations.GetWithHttpMessagesAsync (resourceGroupName, resourceName, certificateName, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.IotHub</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.IotHub.Models.CertificateDescription&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="resourceName" Type="System.String" />
        <Parameter Name="certificateName" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="c8575-138">Der Name der Ressourcengruppe, die den IoT Hub enthält.</span><span class="sxs-lookup"><span data-stu-id="c8575-138">The name of the resource group that contains the IoT hub.</span></span>
            </param>
        <param name="resourceName">
            <span data-ttu-id="c8575-139">Der Name der IoT Hub.</span><span class="sxs-lookup"><span data-stu-id="c8575-139">The name of the IoT hub.</span></span>
            </param>
        <param name="certificateName">
            <span data-ttu-id="c8575-140">Der Name des Zertifikats</span><span class="sxs-lookup"><span data-stu-id="c8575-140">The name of the certificate</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="c8575-141">Die Header, die hinzugefügt werden auf Anforderung.</span><span class="sxs-lookup"><span data-stu-id="c8575-141">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="c8575-142">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="c8575-142">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="c8575-143">Abrufen des Zertifikats an.</span><span class="sxs-lookup"><span data-stu-id="c8575-143">Get the certificate.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="c8575-144">Gibt das Zertifikat an.</span><span class="sxs-lookup"><span data-stu-id="c8575-144">Returns the certificate.</span></span>
            </remarks>
        <exception cref="T:Microsoft.Azure.Management.IotHub.Models.ErrorDetailsException">
            <span data-ttu-id="c8575-145">Wird ausgelöst, wenn der Vorgang einen ungültigen Statuscode zurückgegeben hat.</span><span class="sxs-lookup"><span data-stu-id="c8575-145">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="c8575-146">Wird ausgelöst, wenn nicht die Antwort zu deserialisieren.</span><span class="sxs-lookup"><span data-stu-id="c8575-146">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="c8575-147">Wird ausgelöst, wenn ein erforderlicher Parameter null ist.</span><span class="sxs-lookup"><span data-stu-id="c8575-147">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="ListByIotHubWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.IotHub.Models.CertificateListDescription&gt;&gt; ListByIotHubWithHttpMessagesAsync (string resourceGroupName, string resourceName, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Management.IotHub.Models.CertificateListDescription&gt;&gt; ListByIotHubWithHttpMessagesAsync(string resourceGroupName, string resourceName, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.IotHub.ICertificatesOperations.ListByIotHubWithHttpMessagesAsync(System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListByIotHubWithHttpMessagesAsync : string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.IotHub.Models.CertificateListDescription&gt;&gt;" Usage="iCertificatesOperations.ListByIotHubWithHttpMessagesAsync (resourceGroupName, resourceName, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.IotHub</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.IotHub.Models.CertificateListDescription&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="resourceName" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="c8575-148">Der Name der Ressourcengruppe, die den IoT Hub enthält.</span><span class="sxs-lookup"><span data-stu-id="c8575-148">The name of the resource group that contains the IoT hub.</span></span>
            </param>
        <param name="resourceName">
            <span data-ttu-id="c8575-149">Der Name der IoT Hub.</span><span class="sxs-lookup"><span data-stu-id="c8575-149">The name of the IoT hub.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="c8575-150">Die Header, die hinzugefügt werden auf Anforderung.</span><span class="sxs-lookup"><span data-stu-id="c8575-150">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="c8575-151">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="c8575-151">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="c8575-152">Rufen Sie die Zertifikatliste.</span><span class="sxs-lookup"><span data-stu-id="c8575-152">Get the certificate list.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="c8575-153">Gibt die Liste der Zertifikate.</span><span class="sxs-lookup"><span data-stu-id="c8575-153">Returns the list of certificates.</span></span>
            </remarks>
        <exception cref="T:Microsoft.Azure.Management.IotHub.Models.ErrorDetailsException">
            <span data-ttu-id="c8575-154">Wird ausgelöst, wenn der Vorgang einen ungültigen Statuscode zurückgegeben hat.</span><span class="sxs-lookup"><span data-stu-id="c8575-154">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="c8575-155">Wird ausgelöst, wenn nicht die Antwort zu deserialisieren.</span><span class="sxs-lookup"><span data-stu-id="c8575-155">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="c8575-156">Wird ausgelöst, wenn ein erforderlicher Parameter null ist.</span><span class="sxs-lookup"><span data-stu-id="c8575-156">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="VerifyWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.IotHub.Models.CertificateDescription&gt;&gt; VerifyWithHttpMessagesAsync (string resourceGroupName, string resourceName, string certificateName, Microsoft.Azure.Management.IotHub.Models.CertificateVerificationDescription certificateVerificationBody, string ifMatch, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Management.IotHub.Models.CertificateDescription&gt;&gt; VerifyWithHttpMessagesAsync(string resourceGroupName, string resourceName, string certificateName, class Microsoft.Azure.Management.IotHub.Models.CertificateVerificationDescription certificateVerificationBody, string ifMatch, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.IotHub.ICertificatesOperations.VerifyWithHttpMessagesAsync(System.String,System.String,System.String,Microsoft.Azure.Management.IotHub.Models.CertificateVerificationDescription,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member VerifyWithHttpMessagesAsync : string * string * string * Microsoft.Azure.Management.IotHub.Models.CertificateVerificationDescription * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.IotHub.Models.CertificateDescription&gt;&gt;" Usage="iCertificatesOperations.VerifyWithHttpMessagesAsync (resourceGroupName, resourceName, certificateName, certificateVerificationBody, ifMatch, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.IotHub</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.IotHub.Models.CertificateDescription&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="resourceName" Type="System.String" />
        <Parameter Name="certificateName" Type="System.String" />
        <Parameter Name="certificateVerificationBody" Type="Microsoft.Azure.Management.IotHub.Models.CertificateVerificationDescription" />
        <Parameter Name="ifMatch" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="c8575-157">Der Name der Ressourcengruppe, die den IoT Hub enthält.</span><span class="sxs-lookup"><span data-stu-id="c8575-157">The name of the resource group that contains the IoT hub.</span></span>
            </param>
        <param name="resourceName">
            <span data-ttu-id="c8575-158">Der Name der IoT Hub.</span><span class="sxs-lookup"><span data-stu-id="c8575-158">The name of the IoT hub.</span></span>
            </param>
        <param name="certificateName">
            <span data-ttu-id="c8575-159">Der Name des Zertifikats</span><span class="sxs-lookup"><span data-stu-id="c8575-159">The name of the certificate</span></span>
            </param>
        <param name="certificateVerificationBody">
            <span data-ttu-id="c8575-160">Der Name des Zertifikats</span><span class="sxs-lookup"><span data-stu-id="c8575-160">The name of the certificate</span></span>
            </param>
        <param name="ifMatch">
            <span data-ttu-id="c8575-161">ETag des Zertifikats.</span><span class="sxs-lookup"><span data-stu-id="c8575-161">ETag of the Certificate.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="c8575-162">Die Header, die hinzugefügt werden auf Anforderung.</span><span class="sxs-lookup"><span data-stu-id="c8575-162">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="c8575-163">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="c8575-163">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="c8575-164">Überprüfen des Zertifikats privaten Schlüssel besitzt.</span><span class="sxs-lookup"><span data-stu-id="c8575-164">Verify certificate's private key possession.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="c8575-165">Überprüft das Zertifikat privaten Schlüssel besitzt durch Bereitstellen der Blattebene des Zertifikats durch das überprüft, ob vor hochgeladene Zertifikat ausgestellt.</span><span class="sxs-lookup"><span data-stu-id="c8575-165">Verifies the certificate's private key possession by providing the leaf cert issued by the verifying pre uploaded certificate.</span></span>
            </remarks>
        <exception cref="T:Microsoft.Azure.Management.IotHub.Models.ErrorDetailsException">
            <span data-ttu-id="c8575-166">Wird ausgelöst, wenn der Vorgang einen ungültigen Statuscode zurückgegeben hat.</span><span class="sxs-lookup"><span data-stu-id="c8575-166">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="c8575-167">Wird ausgelöst, wenn nicht die Antwort zu deserialisieren.</span><span class="sxs-lookup"><span data-stu-id="c8575-167">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="c8575-168">Wird ausgelöst, wenn ein erforderlicher Parameter null ist.</span><span class="sxs-lookup"><span data-stu-id="c8575-168">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>