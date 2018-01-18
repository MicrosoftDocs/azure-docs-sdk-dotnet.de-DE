<Type Name="ICredentialOperations" FullName="Microsoft.Azure.Management.Automation.ICredentialOperations">
  <TypeSignature Language="C#" Value="public interface ICredentialOperations" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract ICredentialOperations" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Automation.ICredentialOperations" />
  <TypeSignature Language="VB.NET" Value="Public Interface ICredentialOperations" />
  <TypeSignature Language="F#" Value="type ICredentialOperations = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
    <AssemblyVersion>2.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="ac6c5-101">Der Dienstvorgang für Automation-Anmeldeinformationen.</span><span class="sxs-lookup"><span data-stu-id="ac6c5-101">Service operation for automation credentials.</span></span>  <span data-ttu-id="ac6c5-102">(siehe http://aka.ms/azureautomationsdk/credentialoperations für Weitere Informationen)</span><span class="sxs-lookup"><span data-stu-id="ac6c5-102">(see http://aka.ms/azureautomationsdk/credentialoperations for more information)</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="CreateOrUpdateAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.CredentialCreateOrUpdateResponse&gt; CreateOrUpdateAsync (string resourceGroupName, string automationAccount, Microsoft.Azure.Management.Automation.Models.CredentialCreateOrUpdateParameters parameters, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Automation.Models.CredentialCreateOrUpdateResponse&gt; CreateOrUpdateAsync(string resourceGroupName, string automationAccount, class Microsoft.Azure.Management.Automation.Models.CredentialCreateOrUpdateParameters parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Automation.ICredentialOperations.CreateOrUpdateAsync(System.String,System.String,Microsoft.Azure.Management.Automation.Models.CredentialCreateOrUpdateParameters,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member CreateOrUpdateAsync : string * string * Microsoft.Azure.Management.Automation.Models.CredentialCreateOrUpdateParameters * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.CredentialCreateOrUpdateResponse&gt;" Usage="iCredentialOperations.CreateOrUpdateAsync (resourceGroupName, automationAccount, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.CredentialCreateOrUpdateResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="automationAccount" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Automation.Models.CredentialCreateOrUpdateParameters" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="ac6c5-103">der Name der Ressourcengruppe</span><span class="sxs-lookup"><span data-stu-id="ac6c5-103">The name of the resource group</span></span>
            </param>
        <param name="automationAccount">
            <span data-ttu-id="ac6c5-104">Der Name des Automation-Konto.</span><span class="sxs-lookup"><span data-stu-id="ac6c5-104">The automation account name.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="ac6c5-105">Die Parameter für die Anmeldeinformationen erstellen oder Aktualisieren zur Verfügung gestellt.</span><span class="sxs-lookup"><span data-stu-id="ac6c5-105">The parameters supplied to the create or update credential operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="ac6c5-106">Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="ac6c5-106">Cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="ac6c5-107">Erstellen von Anmeldeinformationen.</span><span class="sxs-lookup"><span data-stu-id="ac6c5-107">Create a credential.</span></span>  <span data-ttu-id="ac6c5-108">(siehe http://aka.ms/azureautomationsdk/credentialoperations für Weitere Informationen)</span><span class="sxs-lookup"><span data-stu-id="ac6c5-108">(see http://aka.ms/azureautomationsdk/credentialoperations for more information)</span></span>
            </summary>
        <returns>
            <span data-ttu-id="ac6c5-109">Das Antwort-Modell für den Vorgang der Anmeldeinformationen erstellen oder aktualisieren.</span><span class="sxs-lookup"><span data-stu-id="ac6c5-109">The response model for the create or update credential operation.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.AzureOperationResponse&gt; DeleteAsync (string resourceGroupName, string automationAccount, string credentialName, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.AzureOperationResponse&gt; DeleteAsync(string resourceGroupName, string automationAccount, string credentialName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Automation.ICredentialOperations.DeleteAsync(System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member DeleteAsync : string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.AzureOperationResponse&gt;" Usage="iCredentialOperations.DeleteAsync (resourceGroupName, automationAccount, credentialName, cancellationToken)" />
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
        <Parameter Name="credentialName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="ac6c5-110">der Name der Ressourcengruppe</span><span class="sxs-lookup"><span data-stu-id="ac6c5-110">The name of the resource group</span></span>
            </param>
        <param name="automationAccount">
            <span data-ttu-id="ac6c5-111">Der Name des Automation-Konto.</span><span class="sxs-lookup"><span data-stu-id="ac6c5-111">The automation account name.</span></span>
            </param>
        <param name="credentialName">
            <span data-ttu-id="ac6c5-112">Der Name der Anmeldeinformationen.</span><span class="sxs-lookup"><span data-stu-id="ac6c5-112">The name of credential.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="ac6c5-113">Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="ac6c5-113">Cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="ac6c5-114">Löschen Sie die Anmeldeinformationen ein.</span><span class="sxs-lookup"><span data-stu-id="ac6c5-114">Delete the credential.</span></span>  <span data-ttu-id="ac6c5-115">(siehe http://aka.ms/azureautomationsdk/credentialoperations für Weitere Informationen)</span><span class="sxs-lookup"><span data-stu-id="ac6c5-115">(see http://aka.ms/azureautomationsdk/credentialoperations for more information)</span></span>
            </summary>
        <returns>
            <span data-ttu-id="ac6c5-116">Eine standarddienstantwort einschließlich ein HTTP-Statuscodes und einer Anforderungs-ID.</span><span class="sxs-lookup"><span data-stu-id="ac6c5-116">A standard service response including an HTTP status code and request ID.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.CredentialGetResponse&gt; GetAsync (string resourceGroupName, string automationAccount, string credentialName, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Automation.Models.CredentialGetResponse&gt; GetAsync(string resourceGroupName, string automationAccount, string credentialName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Automation.ICredentialOperations.GetAsync(System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetAsync : string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.CredentialGetResponse&gt;" Usage="iCredentialOperations.GetAsync (resourceGroupName, automationAccount, credentialName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.CredentialGetResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="automationAccount" Type="System.String" />
        <Parameter Name="credentialName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="ac6c5-117">der Name der Ressourcengruppe</span><span class="sxs-lookup"><span data-stu-id="ac6c5-117">The name of the resource group</span></span>
            </param>
        <param name="automationAccount">
            <span data-ttu-id="ac6c5-118">Der Name des Automation-Konto.</span><span class="sxs-lookup"><span data-stu-id="ac6c5-118">The automation account name.</span></span>
            </param>
        <param name="credentialName">
            <span data-ttu-id="ac6c5-119">Der Name der Anmeldeinformationen.</span><span class="sxs-lookup"><span data-stu-id="ac6c5-119">The name of credential.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="ac6c5-120">Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="ac6c5-120">Cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="ac6c5-121">Abrufen der Anmeldeinformationen durch Anmeldeinformationen identifiziert.</span><span class="sxs-lookup"><span data-stu-id="ac6c5-121">Retrieve the credential identified by credential name.</span></span>  <span data-ttu-id="ac6c5-122">(siehe http://aka.ms/azureautomationsdk/credentialoperations für Weitere Informationen)</span><span class="sxs-lookup"><span data-stu-id="ac6c5-122">(see http://aka.ms/azureautomationsdk/credentialoperations for more information)</span></span>
            </summary>
        <returns>
            <span data-ttu-id="ac6c5-123">Das Antwort-Modell für die Get-Credential-Vorgang.</span><span class="sxs-lookup"><span data-stu-id="ac6c5-123">The response model for the get credential operation.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.CredentialListResponse&gt; ListAsync (string resourceGroupName, string automationAccount, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Automation.Models.CredentialListResponse&gt; ListAsync(string resourceGroupName, string automationAccount, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Automation.ICredentialOperations.ListAsync(System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListAsync : string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.CredentialListResponse&gt;" Usage="iCredentialOperations.ListAsync (resourceGroupName, automationAccount, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.CredentialListResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="automationAccount" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="ac6c5-124">der Name der Ressourcengruppe</span><span class="sxs-lookup"><span data-stu-id="ac6c5-124">The name of the resource group</span></span>
            </param>
        <param name="automationAccount">
            <span data-ttu-id="ac6c5-125">Der Name des Automation-Konto.</span><span class="sxs-lookup"><span data-stu-id="ac6c5-125">The automation account name.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="ac6c5-126">Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="ac6c5-126">Cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="ac6c5-127">Abrufen einer Liste von Anmeldeinformationen an.</span><span class="sxs-lookup"><span data-stu-id="ac6c5-127">Retrieve a list of credentials.</span></span>  <span data-ttu-id="ac6c5-128">(siehe http://aka.ms/azureautomationsdk/credentialoperations für Weitere Informationen)</span><span class="sxs-lookup"><span data-stu-id="ac6c5-128">(see http://aka.ms/azureautomationsdk/credentialoperations for more information)</span></span>
            </summary>
        <returns>
            <span data-ttu-id="ac6c5-129">Das Antwort-Modell für den Auflistungsvorgang für Anmeldeinformationen.</span><span class="sxs-lookup"><span data-stu-id="ac6c5-129">The response model for the list credential operation.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListNextAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.CredentialListResponse&gt; ListNextAsync (string nextLink, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Automation.Models.CredentialListResponse&gt; ListNextAsync(string nextLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Automation.ICredentialOperations.ListNextAsync(System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListNextAsync : string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.CredentialListResponse&gt;" Usage="iCredentialOperations.ListNextAsync (nextLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.CredentialListResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="nextLink" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="nextLink">
            <span data-ttu-id="ac6c5-130">Der Link zum Abrufen des nächsten Satzes von Elementen.</span><span class="sxs-lookup"><span data-stu-id="ac6c5-130">The link to retrieve next set of items.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="ac6c5-131">Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="ac6c5-131">Cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="ac6c5-132">Abgerufen Sie weitere Liste der Anmeldeinformationen werden.</span><span class="sxs-lookup"><span data-stu-id="ac6c5-132">Retrieve next list of credentials.</span></span>  <span data-ttu-id="ac6c5-133">(siehe http://aka.ms/azureautomationsdk/credentialoperations für Weitere Informationen)</span><span class="sxs-lookup"><span data-stu-id="ac6c5-133">(see http://aka.ms/azureautomationsdk/credentialoperations for more information)</span></span>
            </summary>
        <returns>
            <span data-ttu-id="ac6c5-134">Das Antwort-Modell für den Auflistungsvorgang für Anmeldeinformationen.</span><span class="sxs-lookup"><span data-stu-id="ac6c5-134">The response model for the list credential operation.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PatchAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.AzureOperationResponse&gt; PatchAsync (string resourceGroupName, string automationAccount, Microsoft.Azure.Management.Automation.Models.CredentialPatchParameters parameters, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.AzureOperationResponse&gt; PatchAsync(string resourceGroupName, string automationAccount, class Microsoft.Azure.Management.Automation.Models.CredentialPatchParameters parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Automation.ICredentialOperations.PatchAsync(System.String,System.String,Microsoft.Azure.Management.Automation.Models.CredentialPatchParameters,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member PatchAsync : string * string * Microsoft.Azure.Management.Automation.Models.CredentialPatchParameters * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.AzureOperationResponse&gt;" Usage="iCredentialOperations.PatchAsync (resourceGroupName, automationAccount, parameters, cancellationToken)" />
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
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Automation.Models.CredentialPatchParameters" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="ac6c5-135">der Name der Ressourcengruppe</span><span class="sxs-lookup"><span data-stu-id="ac6c5-135">The name of the resource group</span></span>
            </param>
        <param name="automationAccount">
            <span data-ttu-id="ac6c5-136">Der Name des Automation-Konto.</span><span class="sxs-lookup"><span data-stu-id="ac6c5-136">The automation account name.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="ac6c5-137">Die Parameter für die Patch-Anmeldeinformationen zur Verfügung gestellt.</span><span class="sxs-lookup"><span data-stu-id="ac6c5-137">The parameters supplied to the patch credential operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="ac6c5-138">Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="ac6c5-138">Cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="ac6c5-139">Aktualisieren Sie Anmeldeinformationen.</span><span class="sxs-lookup"><span data-stu-id="ac6c5-139">Update a credential.</span></span>  <span data-ttu-id="ac6c5-140">(siehe http://aka.ms/azureautomationsdk/credentialoperations für Weitere Informationen)</span><span class="sxs-lookup"><span data-stu-id="ac6c5-140">(see http://aka.ms/azureautomationsdk/credentialoperations for more information)</span></span>
            </summary>
        <returns>
            <span data-ttu-id="ac6c5-141">Eine standarddienstantwort einschließlich ein HTTP-Statuscodes und einer Anforderungs-ID.</span><span class="sxs-lookup"><span data-stu-id="ac6c5-141">A standard service response including an HTTP status code and request ID.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>