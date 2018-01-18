<Type Name="ICertificateOperations" FullName="Microsoft.Azure.Management.Automation.ICertificateOperations">
  <TypeSignature Language="C#" Value="public interface ICertificateOperations" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract ICertificateOperations" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Automation.ICertificateOperations" />
  <TypeSignature Language="VB.NET" Value="Public Interface ICertificateOperations" />
  <TypeSignature Language="F#" Value="type ICertificateOperations = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
    <AssemblyVersion>2.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="5cdbd-101">Der Dienstvorgang für Automation-Zertifikate.</span><span class="sxs-lookup"><span data-stu-id="5cdbd-101">Service operation for automation certificates.</span></span>  <span data-ttu-id="5cdbd-102">(siehe http://aka.ms/azureautomationsdk/certificateoperations für Weitere Informationen)</span><span class="sxs-lookup"><span data-stu-id="5cdbd-102">(see http://aka.ms/azureautomationsdk/certificateoperations for more information)</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="CreateOrUpdateAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.CertificateCreateOrUpdateResponse&gt; CreateOrUpdateAsync (string resourceGroupName, string automationAccount, Microsoft.Azure.Management.Automation.Models.CertificateCreateOrUpdateParameters parameters, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Automation.Models.CertificateCreateOrUpdateResponse&gt; CreateOrUpdateAsync(string resourceGroupName, string automationAccount, class Microsoft.Azure.Management.Automation.Models.CertificateCreateOrUpdateParameters parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Automation.ICertificateOperations.CreateOrUpdateAsync(System.String,System.String,Microsoft.Azure.Management.Automation.Models.CertificateCreateOrUpdateParameters,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member CreateOrUpdateAsync : string * string * Microsoft.Azure.Management.Automation.Models.CertificateCreateOrUpdateParameters * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.CertificateCreateOrUpdateResponse&gt;" Usage="iCertificateOperations.CreateOrUpdateAsync (resourceGroupName, automationAccount, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.CertificateCreateOrUpdateResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="automationAccount" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Automation.Models.CertificateCreateOrUpdateParameters" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="5cdbd-103">der Name der Ressourcengruppe</span><span class="sxs-lookup"><span data-stu-id="5cdbd-103">The name of the resource group</span></span>
            </param>
        <param name="automationAccount">
            <span data-ttu-id="5cdbd-104">Der Name des Automation-Konto.</span><span class="sxs-lookup"><span data-stu-id="5cdbd-104">The automation account name.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="5cdbd-105">Die Parameter für das Zertifikat erstellen oder Aktualisieren zur Verfügung gestellt.</span><span class="sxs-lookup"><span data-stu-id="5cdbd-105">The parameters supplied to the create or update certificate operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="5cdbd-106">Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="5cdbd-106">Cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="5cdbd-107">Erstellen Sie ein Zertifikat an.</span><span class="sxs-lookup"><span data-stu-id="5cdbd-107">Create a certificate.</span></span>  <span data-ttu-id="5cdbd-108">(siehe http://aka.ms/azureautomationsdk/certificateoperations für Weitere Informationen)</span><span class="sxs-lookup"><span data-stu-id="5cdbd-108">(see http://aka.ms/azureautomationsdk/certificateoperations for more information)</span></span>
            </summary>
        <returns>
            <span data-ttu-id="5cdbd-109">Das Antwort-Modell für den Vorgang der Zertifikat erstellen oder aktualisieren.</span><span class="sxs-lookup"><span data-stu-id="5cdbd-109">The response model for the create or update certificate operation.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.AzureOperationResponse&gt; DeleteAsync (string resourceGroupName, string automationAccount, string certificateName, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.AzureOperationResponse&gt; DeleteAsync(string resourceGroupName, string automationAccount, string certificateName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Automation.ICertificateOperations.DeleteAsync(System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member DeleteAsync : string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.AzureOperationResponse&gt;" Usage="iCertificateOperations.DeleteAsync (resourceGroupName, automationAccount, certificateName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.AzureOperationResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="automationAccount" Type="System.String" />
        <Parameter Name="certificateName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="5cdbd-110">der Name der Ressourcengruppe</span><span class="sxs-lookup"><span data-stu-id="5cdbd-110">The name of the resource group</span></span>
            </param>
        <param name="automationAccount">
            <span data-ttu-id="5cdbd-111">Der Name des Automation-Konto.</span><span class="sxs-lookup"><span data-stu-id="5cdbd-111">The automation account name.</span></span>
            </param>
        <param name="certificateName">
            <span data-ttu-id="5cdbd-112">Der Name des Zertifikats.</span><span class="sxs-lookup"><span data-stu-id="5cdbd-112">The name of certificate.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="5cdbd-113">Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="5cdbd-113">Cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="5cdbd-114">Löschen Sie das Zertifikat an.</span><span class="sxs-lookup"><span data-stu-id="5cdbd-114">Delete the certificate.</span></span>  <span data-ttu-id="5cdbd-115">(siehe http://aka.ms/azureautomationsdk/certificateoperations für Weitere Informationen)</span><span class="sxs-lookup"><span data-stu-id="5cdbd-115">(see http://aka.ms/azureautomationsdk/certificateoperations for more information)</span></span>
            </summary>
        <returns>
            <span data-ttu-id="5cdbd-116">Eine standarddienstantwort einschließlich ein HTTP-Statuscodes und einer Anforderungs-ID.</span><span class="sxs-lookup"><span data-stu-id="5cdbd-116">A standard service response including an HTTP status code and request ID.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.CertificateGetResponse&gt; GetAsync (string resourceGroupName, string automationAccount, string certificateName, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Automation.Models.CertificateGetResponse&gt; GetAsync(string resourceGroupName, string automationAccount, string certificateName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Automation.ICertificateOperations.GetAsync(System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetAsync : string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.CertificateGetResponse&gt;" Usage="iCertificateOperations.GetAsync (resourceGroupName, automationAccount, certificateName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.CertificateGetResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="automationAccount" Type="System.String" />
        <Parameter Name="certificateName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="5cdbd-117">der Name der Ressourcengruppe</span><span class="sxs-lookup"><span data-stu-id="5cdbd-117">The name of the resource group</span></span>
            </param>
        <param name="automationAccount">
            <span data-ttu-id="5cdbd-118">Der Name des Automation-Konto.</span><span class="sxs-lookup"><span data-stu-id="5cdbd-118">The automation account name.</span></span>
            </param>
        <param name="certificateName">
            <span data-ttu-id="5cdbd-119">Der Name des Zertifikats.</span><span class="sxs-lookup"><span data-stu-id="5cdbd-119">The name of certificate.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="5cdbd-120">Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="5cdbd-120">Cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="5cdbd-121">Rufen Sie das Zertifikat, das Zertifikat namentlich identifiziert.</span><span class="sxs-lookup"><span data-stu-id="5cdbd-121">Retrieve the certificate identified by certificate name.</span></span>  <span data-ttu-id="5cdbd-122">(siehe http://aka.ms/azureautomationsdk/certificateoperations für Weitere Informationen)</span><span class="sxs-lookup"><span data-stu-id="5cdbd-122">(see http://aka.ms/azureautomationsdk/certificateoperations for more information)</span></span>
            </summary>
        <returns>
            <span data-ttu-id="5cdbd-123">Das Antwort-Modell für den Abrufvorgang für das Zertifikat.</span><span class="sxs-lookup"><span data-stu-id="5cdbd-123">The response model for the get certificate operation.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.CertificateListResponse&gt; ListAsync (string resourceGroupName, string automationAccount, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Automation.Models.CertificateListResponse&gt; ListAsync(string resourceGroupName, string automationAccount, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Automation.ICertificateOperations.ListAsync(System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListAsync : string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.CertificateListResponse&gt;" Usage="iCertificateOperations.ListAsync (resourceGroupName, automationAccount, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.CertificateListResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="automationAccount" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="5cdbd-124">der Name der Ressourcengruppe</span><span class="sxs-lookup"><span data-stu-id="5cdbd-124">The name of the resource group</span></span>
            </param>
        <param name="automationAccount">
            <span data-ttu-id="5cdbd-125">Der Name des Automation-Konto.</span><span class="sxs-lookup"><span data-stu-id="5cdbd-125">The automation account name.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="5cdbd-126">Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="5cdbd-126">Cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="5cdbd-127">Rufen Sie eine Liste von Zertifikaten.</span><span class="sxs-lookup"><span data-stu-id="5cdbd-127">Retrieve a list of certificates.</span></span>  <span data-ttu-id="5cdbd-128">(siehe http://aka.ms/azureautomationsdk/certificateoperations für Weitere Informationen)</span><span class="sxs-lookup"><span data-stu-id="5cdbd-128">(see http://aka.ms/azureautomationsdk/certificateoperations for more information)</span></span>
            </summary>
        <returns>
            <span data-ttu-id="5cdbd-129">Das Antwort-Modell für den Auflistungsvorgang für das Zertifikat.</span><span class="sxs-lookup"><span data-stu-id="5cdbd-129">The response model for the list certificate operation.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListNextAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.CertificateListResponse&gt; ListNextAsync (string nextLink, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Automation.Models.CertificateListResponse&gt; ListNextAsync(string nextLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Automation.ICertificateOperations.ListNextAsync(System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListNextAsync : string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.CertificateListResponse&gt;" Usage="iCertificateOperations.ListNextAsync (nextLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.CertificateListResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="nextLink" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="nextLink">
            <span data-ttu-id="5cdbd-130">Der Link zum Abrufen des nächsten Satzes von Elementen.</span><span class="sxs-lookup"><span data-stu-id="5cdbd-130">The link to retrieve next set of items.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="5cdbd-131">Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="5cdbd-131">Cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="5cdbd-132">Abgerufen Sie weitere Liste der Zertifikate werden.</span><span class="sxs-lookup"><span data-stu-id="5cdbd-132">Retrieve next list of certificates.</span></span>  <span data-ttu-id="5cdbd-133">(siehe http://aka.ms/azureautomationsdk/certificateoperations für Weitere Informationen)</span><span class="sxs-lookup"><span data-stu-id="5cdbd-133">(see http://aka.ms/azureautomationsdk/certificateoperations for more information)</span></span>
            </summary>
        <returns>
            <span data-ttu-id="5cdbd-134">Das Antwort-Modell für den Auflistungsvorgang für das Zertifikat.</span><span class="sxs-lookup"><span data-stu-id="5cdbd-134">The response model for the list certificate operation.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PatchAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.AzureOperationResponse&gt; PatchAsync (string resourceGroupName, string automationAccount, Microsoft.Azure.Management.Automation.Models.CertificatePatchParameters parameters, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.AzureOperationResponse&gt; PatchAsync(string resourceGroupName, string automationAccount, class Microsoft.Azure.Management.Automation.Models.CertificatePatchParameters parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Automation.ICertificateOperations.PatchAsync(System.String,System.String,Microsoft.Azure.Management.Automation.Models.CertificatePatchParameters,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member PatchAsync : string * string * Microsoft.Azure.Management.Automation.Models.CertificatePatchParameters * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.AzureOperationResponse&gt;" Usage="iCertificateOperations.PatchAsync (resourceGroupName, automationAccount, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.AzureOperationResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="automationAccount" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Automation.Models.CertificatePatchParameters" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="5cdbd-135">der Name der Ressourcengruppe</span><span class="sxs-lookup"><span data-stu-id="5cdbd-135">The name of the resource group</span></span>
            </param>
        <param name="automationAccount">
            <span data-ttu-id="5cdbd-136">Der Name des Automation-Konto.</span><span class="sxs-lookup"><span data-stu-id="5cdbd-136">The automation account name.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="5cdbd-137">Die Parameter für den Patch-Vorgang Zertifikat bereitgestellte.</span><span class="sxs-lookup"><span data-stu-id="5cdbd-137">The parameters supplied to the patch certificate operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="5cdbd-138">Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="5cdbd-138">Cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="5cdbd-139">Aktualisieren eines Zertifikats an.</span><span class="sxs-lookup"><span data-stu-id="5cdbd-139">Update a certificate.</span></span>  <span data-ttu-id="5cdbd-140">(siehe http://aka.ms/azureautomationsdk/certificateoperations für Weitere Informationen)</span><span class="sxs-lookup"><span data-stu-id="5cdbd-140">(see http://aka.ms/azureautomationsdk/certificateoperations for more information)</span></span>
            </summary>
        <returns>
            <span data-ttu-id="5cdbd-141">Eine standarddienstantwort einschließlich ein HTTP-Statuscodes und einer Anforderungs-ID.</span><span class="sxs-lookup"><span data-stu-id="5cdbd-141">A standard service response including an HTTP status code and request ID.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>