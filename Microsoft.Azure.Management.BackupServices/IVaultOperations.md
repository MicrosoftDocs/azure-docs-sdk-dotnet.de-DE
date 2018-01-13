<Type Name="IVaultOperations" FullName="Microsoft.Azure.Management.BackupServices.IVaultOperations">
  <TypeSignature Language="C#" Value="public interface IVaultOperations" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IVaultOperations" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.BackupServices.IVaultOperations" />
  <TypeSignature Language="VB.NET" Value="Public Interface IVaultOperations" />
  <TypeSignature Language="F#" Value="type IVaultOperations = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.BackupServicesManagement</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="308e8-101">Definition der Tresor-bezogenen Vorgänge für die Azure Backup-Erweiterung.</span><span class="sxs-lookup"><span data-stu-id="308e8-101">Definition of Vault-related operations for the Azure Backup extension.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="CreateOrUpdateAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.BackupServices.Models.AzureBackupVaultGetResponse&gt; CreateOrUpdateAsync (string resourceGroupName, string resourceName, Microsoft.Azure.Management.BackupServices.Models.AzureBackupVaultCreateOrUpdateParameters parameters, Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders customRequestHeaders, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.BackupServices.Models.AzureBackupVaultGetResponse&gt; CreateOrUpdateAsync(string resourceGroupName, string resourceName, class Microsoft.Azure.Management.BackupServices.Models.AzureBackupVaultCreateOrUpdateParameters parameters, class Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders customRequestHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.BackupServices.IVaultOperations.CreateOrUpdateAsync(System.String,System.String,Microsoft.Azure.Management.BackupServices.Models.AzureBackupVaultCreateOrUpdateParameters,Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member CreateOrUpdateAsync : string * string * Microsoft.Azure.Management.BackupServices.Models.AzureBackupVaultCreateOrUpdateParameters * Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.BackupServices.Models.AzureBackupVaultGetResponse&gt;" Usage="iVaultOperations.CreateOrUpdateAsync (resourceGroupName, resourceName, parameters, customRequestHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BackupServicesManagement</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.BackupServices.Models.AzureBackupVaultGetResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="resourceName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.BackupServices.Models.AzureBackupVaultCreateOrUpdateParameters" />
        <Parameter Name="customRequestHeaders" Type="Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="308e8-102">Der Name der Ressourcengruppe, in welche Tresor gehört</span><span class="sxs-lookup"><span data-stu-id="308e8-102">The name of resource group to which vault belongs</span></span>
            </param>
        <param name="resourceName">
            <span data-ttu-id="308e8-103">Der Name des Tresors</span><span class="sxs-lookup"><span data-stu-id="308e8-103">The name of the vault</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="308e8-104">Parameter zum Erstellen oder aktualisieren den Tresor</span><span class="sxs-lookup"><span data-stu-id="308e8-104">Parameters to create or update the vault</span></span>
            </param>
        <param name="customRequestHeaders">
            <span data-ttu-id="308e8-105">Header Anforderungsparameter.</span><span class="sxs-lookup"><span data-stu-id="308e8-105">Request header parameters.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="308e8-106">Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="308e8-106">Cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="308e8-107">Erstellt einen neuen Azure-sicherungstresor an.</span><span class="sxs-lookup"><span data-stu-id="308e8-107">Creates a new Azure backup vault.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="308e8-108">Tresorinformationen.</span><span class="sxs-lookup"><span data-stu-id="308e8-108">Vault information.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.BackupServices.Models.AzureBackupVaultGetResponse&gt; DeleteAsync (string resourceGroupName, string resourceName, Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders customRequestHeaders, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.BackupServices.Models.AzureBackupVaultGetResponse&gt; DeleteAsync(string resourceGroupName, string resourceName, class Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders customRequestHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.BackupServices.IVaultOperations.DeleteAsync(System.String,System.String,Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member DeleteAsync : string * string * Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.BackupServices.Models.AzureBackupVaultGetResponse&gt;" Usage="iVaultOperations.DeleteAsync (resourceGroupName, resourceName, customRequestHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BackupServicesManagement</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.BackupServices.Models.AzureBackupVaultGetResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="resourceName" Type="System.String" />
        <Parameter Name="customRequestHeaders" Type="Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="308e8-109">Der Name der Ressourcengruppe, in welche Tresor gehört</span><span class="sxs-lookup"><span data-stu-id="308e8-109">The name of resource group to which vault belongs</span></span>
            </param>
        <param name="resourceName">
            <span data-ttu-id="308e8-110">Der Name des Tresors</span><span class="sxs-lookup"><span data-stu-id="308e8-110">The name of the vault</span></span>
            </param>
        <param name="customRequestHeaders">
            <span data-ttu-id="308e8-111">Header Anforderungsparameter.</span><span class="sxs-lookup"><span data-stu-id="308e8-111">Request header parameters.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="308e8-112">Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="308e8-112">Cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="308e8-113">Löscht die angegebene Azure backup-Tresor.</span><span class="sxs-lookup"><span data-stu-id="308e8-113">Deletes the specified Azure backup vault.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="308e8-114">Tresorinformationen.</span><span class="sxs-lookup"><span data-stu-id="308e8-114">Vault information.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.BackupServices.Models.AzureBackupVaultGetResponse&gt; GetAsync (string resourceGroupName, string resourceName, Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders customRequestHeaders, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.BackupServices.Models.AzureBackupVaultGetResponse&gt; GetAsync(string resourceGroupName, string resourceName, class Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders customRequestHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.BackupServices.IVaultOperations.GetAsync(System.String,System.String,Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetAsync : string * string * Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.BackupServices.Models.AzureBackupVaultGetResponse&gt;" Usage="iVaultOperations.GetAsync (resourceGroupName, resourceName, customRequestHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BackupServicesManagement</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.BackupServices.Models.AzureBackupVaultGetResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="resourceName" Type="System.String" />
        <Parameter Name="customRequestHeaders" Type="Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="308e8-115">Der Name der Ressourcengruppe, in welche Tresor gehört</span><span class="sxs-lookup"><span data-stu-id="308e8-115">The name of resource group to which vault belongs</span></span>
            </param>
        <param name="resourceName">
            <span data-ttu-id="308e8-116">Der Name des Tresors</span><span class="sxs-lookup"><span data-stu-id="308e8-116">The name of the vault</span></span>
            </param>
        <param name="customRequestHeaders">
            <span data-ttu-id="308e8-117">Header Anforderungsparameter.</span><span class="sxs-lookup"><span data-stu-id="308e8-117">Request header parameters.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="308e8-118">Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="308e8-118">Cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="308e8-119">Ruft die angegebene Azure-schlüsseltresor.</span><span class="sxs-lookup"><span data-stu-id="308e8-119">Gets the specified Azure key vault.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="308e8-120">Tresorinformationen.</span><span class="sxs-lookup"><span data-stu-id="308e8-120">Vault information.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetResourceStorageConfigAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.BackupServices.Models.GetResourceStorageConfigResponse&gt; GetResourceStorageConfigAsync (string resourceGroupName, string resourceName, Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders customRequestHeaders, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.BackupServices.Models.GetResourceStorageConfigResponse&gt; GetResourceStorageConfigAsync(string resourceGroupName, string resourceName, class Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders customRequestHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.BackupServices.IVaultOperations.GetResourceStorageConfigAsync(System.String,System.String,Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetResourceStorageConfigAsync : string * string * Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.BackupServices.Models.GetResourceStorageConfigResponse&gt;" Usage="iVaultOperations.GetResourceStorageConfigAsync (resourceGroupName, resourceName, customRequestHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BackupServicesManagement</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.BackupServices.Models.GetResourceStorageConfigResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="resourceName" Type="System.String" />
        <Parameter Name="customRequestHeaders" Type="Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="308e8-121">Der Name der Ressourcengruppe, in welche Tresor gehört</span><span class="sxs-lookup"><span data-stu-id="308e8-121">The name of resource group to which vault belongs</span></span>
            </param>
        <param name="resourceName">
            <span data-ttu-id="308e8-122">Der Name des Tresors</span><span class="sxs-lookup"><span data-stu-id="308e8-122">The name of the vault</span></span>
            </param>
        <param name="customRequestHeaders">
            <span data-ttu-id="308e8-123">Header Anforderungsparameter.</span><span class="sxs-lookup"><span data-stu-id="308e8-123">Request header parameters.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="308e8-124">Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="308e8-124">Cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="308e8-125">Ruft die Ressourcenkonfiguration Speicher ab.</span><span class="sxs-lookup"><span data-stu-id="308e8-125">Fetches resource storage config.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="308e8-126">Die Definition einer Get-Speicher-Config Ressourcenantwort.</span><span class="sxs-lookup"><span data-stu-id="308e8-126">The definition of a get resource storage config response.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.BackupServices.Models.AzureBackupVaultListResponse&gt; ListAsync (int top, Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders customRequestHeaders, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.BackupServices.Models.AzureBackupVaultListResponse&gt; ListAsync(int32 top, class Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders customRequestHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.BackupServices.IVaultOperations.ListAsync(System.Int32,Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListAsync : int * Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.BackupServices.Models.AzureBackupVaultListResponse&gt;" Usage="iVaultOperations.ListAsync (top, customRequestHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BackupServicesManagement</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.BackupServices.Models.AzureBackupVaultListResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="top" Type="System.Int32" />
        <Parameter Name="customRequestHeaders" Type="Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="top">
            <span data-ttu-id="308e8-127">Maximale Anzahl der zurückzugebenden Ergebnisseite.</span><span class="sxs-lookup"><span data-stu-id="308e8-127">Maximum number of results to return.</span></span>
            </param>
        <param name="customRequestHeaders">
            <span data-ttu-id="308e8-128">Header Anforderungsparameter.</span><span class="sxs-lookup"><span data-stu-id="308e8-128">Request header parameters.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="308e8-129">Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="308e8-129">Cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="308e8-130">Ruft die sicherungstresore Abonnement zugeordneten Informationen ab.</span><span class="sxs-lookup"><span data-stu-id="308e8-130">Gets information of the backup vaults associated with subscription.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="308e8-131">Liste der Tresore</span><span class="sxs-lookup"><span data-stu-id="308e8-131">List of vaults</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByResourceGroupAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.BackupServices.Models.AzureBackupVaultListResponse&gt; ListByResourceGroupAsync (string resourceGroupName, int top, Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders customRequestHeaders, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.BackupServices.Models.AzureBackupVaultListResponse&gt; ListByResourceGroupAsync(string resourceGroupName, int32 top, class Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders customRequestHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.BackupServices.IVaultOperations.ListByResourceGroupAsync(System.String,System.Int32,Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListByResourceGroupAsync : string * int * Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.BackupServices.Models.AzureBackupVaultListResponse&gt;" Usage="iVaultOperations.ListByResourceGroupAsync (resourceGroupName, top, customRequestHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BackupServicesManagement</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.BackupServices.Models.AzureBackupVaultListResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="top" Type="System.Int32" />
        <Parameter Name="customRequestHeaders" Type="Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="308e8-132">Ein optionales Argument, das den Namen der Ressourcengruppe angibt, die den Satz von Tresoren einschränkt, die zurückgegeben werden.</span><span class="sxs-lookup"><span data-stu-id="308e8-132">An optional argument which specifies the name of the resource group that constrains the set of vaults that are returned.</span></span>
            </param>
        <param name="top">
            <span data-ttu-id="308e8-133">Maximale Anzahl der zurückzugebenden Ergebnisseite.</span><span class="sxs-lookup"><span data-stu-id="308e8-133">Maximum number of results to return.</span></span>
            </param>
        <param name="customRequestHeaders">
            <span data-ttu-id="308e8-134">Header Anforderungsparameter.</span><span class="sxs-lookup"><span data-stu-id="308e8-134">Request header parameters.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="308e8-135">Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="308e8-135">Cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="308e8-136">Ruft die sicherungstresore Ressourcengruppe zugeordneten Informationen ab.</span><span class="sxs-lookup"><span data-stu-id="308e8-136">Gets information of the backup vaults associated with resource group.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="308e8-137">Liste der Tresore</span><span class="sxs-lookup"><span data-stu-id="308e8-137">List of vaults</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UpdateStorageTypeAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.BackupServices.OperationResponse&gt; UpdateStorageTypeAsync (string resourceGroupName, string resourceName, Microsoft.Azure.Management.BackupServices.Models.UpdateVaultStorageTypeRequest updateVaultStorageTypeRequest, Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders customRequestHeaders, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.BackupServices.OperationResponse&gt; UpdateStorageTypeAsync(string resourceGroupName, string resourceName, class Microsoft.Azure.Management.BackupServices.Models.UpdateVaultStorageTypeRequest updateVaultStorageTypeRequest, class Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders customRequestHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.BackupServices.IVaultOperations.UpdateStorageTypeAsync(System.String,System.String,Microsoft.Azure.Management.BackupServices.Models.UpdateVaultStorageTypeRequest,Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member UpdateStorageTypeAsync : string * string * Microsoft.Azure.Management.BackupServices.Models.UpdateVaultStorageTypeRequest * Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.BackupServices.OperationResponse&gt;" Usage="iVaultOperations.UpdateStorageTypeAsync (resourceGroupName, resourceName, updateVaultStorageTypeRequest, customRequestHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BackupServicesManagement</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.BackupServices.OperationResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="resourceName" Type="System.String" />
        <Parameter Name="updateVaultStorageTypeRequest" Type="Microsoft.Azure.Management.BackupServices.Models.UpdateVaultStorageTypeRequest" />
        <Parameter Name="customRequestHeaders" Type="Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">To be added.</param>
        <param name="resourceName">To be added.</param>
        <param name="updateVaultStorageTypeRequest">
            <span data-ttu-id="308e8-138">Anforderung zum Update Tresor Speicher Typ</span><span class="sxs-lookup"><span data-stu-id="308e8-138">Update Vault Storage Type Request</span></span>
            </param>
        <param name="customRequestHeaders">
            <span data-ttu-id="308e8-139">Header Anforderungsparameter.</span><span class="sxs-lookup"><span data-stu-id="308e8-139">Request header parameters.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="308e8-140">Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="308e8-140">Cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="308e8-141">Updates Tresor Speichertyp-Modell.</span><span class="sxs-lookup"><span data-stu-id="308e8-141">Updates vault storage model type.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="308e8-142">Die Definition einer Operation-Antwort.</span><span class="sxs-lookup"><span data-stu-id="308e8-142">The definition of a Operation Response.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UploadCertificateAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.BackupServices.Models.VaultCredUploadCertResponse&gt; UploadCertificateAsync (string resourceGroupName, string resourceName, string certificateName, Microsoft.Azure.Management.BackupServices.Models.VaultCredUploadCertRequest vaultCredUploadCertRequest, Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders customRequestHeaders, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.BackupServices.Models.VaultCredUploadCertResponse&gt; UploadCertificateAsync(string resourceGroupName, string resourceName, string certificateName, class Microsoft.Azure.Management.BackupServices.Models.VaultCredUploadCertRequest vaultCredUploadCertRequest, class Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders customRequestHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.BackupServices.IVaultOperations.UploadCertificateAsync(System.String,System.String,System.String,Microsoft.Azure.Management.BackupServices.Models.VaultCredUploadCertRequest,Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member UploadCertificateAsync : string * string * string * Microsoft.Azure.Management.BackupServices.Models.VaultCredUploadCertRequest * Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.BackupServices.Models.VaultCredUploadCertResponse&gt;" Usage="iVaultOperations.UploadCertificateAsync (resourceGroupName, resourceName, certificateName, vaultCredUploadCertRequest, customRequestHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BackupServicesManagement</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.BackupServices.Models.VaultCredUploadCertResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="resourceName" Type="System.String" />
        <Parameter Name="certificateName" Type="System.String" />
        <Parameter Name="vaultCredUploadCertRequest" Type="Microsoft.Azure.Management.BackupServices.Models.VaultCredUploadCertRequest" />
        <Parameter Name="customRequestHeaders" Type="Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">To be added.</param>
        <param name="resourceName">To be added.</param>
        <param name="certificateName">
            <span data-ttu-id="308e8-143">Der Name des Zertifikats.</span><span class="sxs-lookup"><span data-stu-id="308e8-143">Name of the certificate.</span></span>
            </param>
        <param name="vaultCredUploadCertRequest">
            <span data-ttu-id="308e8-144">Zertifikatparameter.</span><span class="sxs-lookup"><span data-stu-id="308e8-144">Certificate parameters.</span></span>
            </param>
        <param name="customRequestHeaders">
            <span data-ttu-id="308e8-145">Header Anforderungsparameter.</span><span class="sxs-lookup"><span data-stu-id="308e8-145">Request header parameters.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="308e8-146">Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="308e8-146">Cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="308e8-147">Uploads Tresor Zertifikat für Anmeldeinformationen.</span><span class="sxs-lookup"><span data-stu-id="308e8-147">Uploads vault credential certificate.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="308e8-148">Die Definition einer Antwort Zertifikat.</span><span class="sxs-lookup"><span data-stu-id="308e8-148">The definition of a certificate response.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>