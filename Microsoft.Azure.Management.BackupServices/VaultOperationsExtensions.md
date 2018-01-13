<Type Name="VaultOperationsExtensions" FullName="Microsoft.Azure.Management.BackupServices.VaultOperationsExtensions">
  <TypeSignature Language="C#" Value="public static class VaultOperationsExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit VaultOperationsExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.BackupServices.VaultOperationsExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module VaultOperationsExtensions" />
  <TypeSignature Language="F#" Value="type VaultOperationsExtensions = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.BackupServicesManagement</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>To be added.</summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="CreateOrUpdate">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.BackupServices.Models.AzureBackupVaultGetResponse CreateOrUpdate (this Microsoft.Azure.Management.BackupServices.IVaultOperations operations, string resourceGroupName, string resourceName, Microsoft.Azure.Management.BackupServices.Models.AzureBackupVaultCreateOrUpdateParameters parameters, Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders customRequestHeaders);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.BackupServices.Models.AzureBackupVaultGetResponse CreateOrUpdate(class Microsoft.Azure.Management.BackupServices.IVaultOperations operations, string resourceGroupName, string resourceName, class Microsoft.Azure.Management.BackupServices.Models.AzureBackupVaultCreateOrUpdateParameters parameters, class Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders customRequestHeaders) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.BackupServices.VaultOperationsExtensions.CreateOrUpdate(Microsoft.Azure.Management.BackupServices.IVaultOperations,System.String,System.String,Microsoft.Azure.Management.BackupServices.Models.AzureBackupVaultCreateOrUpdateParameters,Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders)" />
      <MemberSignature Language="F#" Value="static member CreateOrUpdate : Microsoft.Azure.Management.BackupServices.IVaultOperations * string * string * Microsoft.Azure.Management.BackupServices.Models.AzureBackupVaultCreateOrUpdateParameters * Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders -&gt; Microsoft.Azure.Management.BackupServices.Models.AzureBackupVaultGetResponse" Usage="Microsoft.Azure.Management.BackupServices.VaultOperationsExtensions.CreateOrUpdate (operations, resourceGroupName, resourceName, parameters, customRequestHeaders)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BackupServicesManagement</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.BackupServices.Models.AzureBackupVaultGetResponse</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.BackupServices.IVaultOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="resourceName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.BackupServices.Models.AzureBackupVaultCreateOrUpdateParameters" />
        <Parameter Name="customRequestHeaders" Type="Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="45258-101">Verweis auf die Microsoft.Azure.Management.BackupServices.IVaultOperations.</span><span class="sxs-lookup"><span data-stu-id="45258-101">Reference to the Microsoft.Azure.Management.BackupServices.IVaultOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="45258-102">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="45258-102">Required.</span></span> <span data-ttu-id="45258-103">Der Name der Ressourcengruppe, in welche Tresor gehört</span><span class="sxs-lookup"><span data-stu-id="45258-103">The name of resource group to which vault belongs</span></span>
            </param>
        <param name="resourceName">
            <span data-ttu-id="45258-104">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="45258-104">Required.</span></span> <span data-ttu-id="45258-105">Der Name des Tresors</span><span class="sxs-lookup"><span data-stu-id="45258-105">The name of the vault</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="45258-106">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="45258-106">Required.</span></span> <span data-ttu-id="45258-107">Parameter zum Erstellen oder aktualisieren den Tresor</span><span class="sxs-lookup"><span data-stu-id="45258-107">Parameters to create or update the vault</span></span>
            </param>
        <param name="customRequestHeaders">
            <span data-ttu-id="45258-108">Optional.</span><span class="sxs-lookup"><span data-stu-id="45258-108">Optional.</span></span> <span data-ttu-id="45258-109">Header Anforderungsparameter.</span><span class="sxs-lookup"><span data-stu-id="45258-109">Request header parameters.</span></span>
            </param>
        <summary>
            <span data-ttu-id="45258-110">Erstellt einen neuen Azure-sicherungstresor an.</span><span class="sxs-lookup"><span data-stu-id="45258-110">Creates a new Azure backup vault.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="45258-111">Tresorinformationen.</span><span class="sxs-lookup"><span data-stu-id="45258-111">Vault information.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateOrUpdateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.BackupServices.Models.AzureBackupVaultGetResponse&gt; CreateOrUpdateAsync (this Microsoft.Azure.Management.BackupServices.IVaultOperations operations, string resourceGroupName, string resourceName, Microsoft.Azure.Management.BackupServices.Models.AzureBackupVaultCreateOrUpdateParameters parameters, Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders customRequestHeaders);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.BackupServices.Models.AzureBackupVaultGetResponse&gt; CreateOrUpdateAsync(class Microsoft.Azure.Management.BackupServices.IVaultOperations operations, string resourceGroupName, string resourceName, class Microsoft.Azure.Management.BackupServices.Models.AzureBackupVaultCreateOrUpdateParameters parameters, class Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders customRequestHeaders) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.BackupServices.VaultOperationsExtensions.CreateOrUpdateAsync(Microsoft.Azure.Management.BackupServices.IVaultOperations,System.String,System.String,Microsoft.Azure.Management.BackupServices.Models.AzureBackupVaultCreateOrUpdateParameters,Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders)" />
      <MemberSignature Language="F#" Value="static member CreateOrUpdateAsync : Microsoft.Azure.Management.BackupServices.IVaultOperations * string * string * Microsoft.Azure.Management.BackupServices.Models.AzureBackupVaultCreateOrUpdateParameters * Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.BackupServices.Models.AzureBackupVaultGetResponse&gt;" Usage="Microsoft.Azure.Management.BackupServices.VaultOperationsExtensions.CreateOrUpdateAsync (operations, resourceGroupName, resourceName, parameters, customRequestHeaders)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BackupServicesManagement</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.BackupServices.Models.AzureBackupVaultGetResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.BackupServices.IVaultOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="resourceName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.BackupServices.Models.AzureBackupVaultCreateOrUpdateParameters" />
        <Parameter Name="customRequestHeaders" Type="Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="45258-112">Verweis auf die Microsoft.Azure.Management.BackupServices.IVaultOperations.</span><span class="sxs-lookup"><span data-stu-id="45258-112">Reference to the Microsoft.Azure.Management.BackupServices.IVaultOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="45258-113">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="45258-113">Required.</span></span> <span data-ttu-id="45258-114">Der Name der Ressourcengruppe, in welche Tresor gehört</span><span class="sxs-lookup"><span data-stu-id="45258-114">The name of resource group to which vault belongs</span></span>
            </param>
        <param name="resourceName">
            <span data-ttu-id="45258-115">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="45258-115">Required.</span></span> <span data-ttu-id="45258-116">Der Name des Tresors</span><span class="sxs-lookup"><span data-stu-id="45258-116">The name of the vault</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="45258-117">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="45258-117">Required.</span></span> <span data-ttu-id="45258-118">Parameter zum Erstellen oder aktualisieren den Tresor</span><span class="sxs-lookup"><span data-stu-id="45258-118">Parameters to create or update the vault</span></span>
            </param>
        <param name="customRequestHeaders">
            <span data-ttu-id="45258-119">Optional.</span><span class="sxs-lookup"><span data-stu-id="45258-119">Optional.</span></span> <span data-ttu-id="45258-120">Header Anforderungsparameter.</span><span class="sxs-lookup"><span data-stu-id="45258-120">Request header parameters.</span></span>
            </param>
        <summary>
            <span data-ttu-id="45258-121">Erstellt einen neuen Azure-sicherungstresor an.</span><span class="sxs-lookup"><span data-stu-id="45258-121">Creates a new Azure backup vault.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="45258-122">Tresorinformationen.</span><span class="sxs-lookup"><span data-stu-id="45258-122">Vault information.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Delete">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.BackupServices.Models.AzureBackupVaultGetResponse Delete (this Microsoft.Azure.Management.BackupServices.IVaultOperations operations, string resourceGroupName, string resourceName, Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders customRequestHeaders);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.BackupServices.Models.AzureBackupVaultGetResponse Delete(class Microsoft.Azure.Management.BackupServices.IVaultOperations operations, string resourceGroupName, string resourceName, class Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders customRequestHeaders) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.BackupServices.VaultOperationsExtensions.Delete(Microsoft.Azure.Management.BackupServices.IVaultOperations,System.String,System.String,Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders)" />
      <MemberSignature Language="F#" Value="static member Delete : Microsoft.Azure.Management.BackupServices.IVaultOperations * string * string * Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders -&gt; Microsoft.Azure.Management.BackupServices.Models.AzureBackupVaultGetResponse" Usage="Microsoft.Azure.Management.BackupServices.VaultOperationsExtensions.Delete (operations, resourceGroupName, resourceName, customRequestHeaders)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BackupServicesManagement</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.BackupServices.Models.AzureBackupVaultGetResponse</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.BackupServices.IVaultOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="resourceName" Type="System.String" />
        <Parameter Name="customRequestHeaders" Type="Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="45258-123">Verweis auf die Microsoft.Azure.Management.BackupServices.IVaultOperations.</span><span class="sxs-lookup"><span data-stu-id="45258-123">Reference to the Microsoft.Azure.Management.BackupServices.IVaultOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="45258-124">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="45258-124">Required.</span></span> <span data-ttu-id="45258-125">Der Name der Ressourcengruppe, in welche Tresor gehört</span><span class="sxs-lookup"><span data-stu-id="45258-125">The name of resource group to which vault belongs</span></span>
            </param>
        <param name="resourceName">
            <span data-ttu-id="45258-126">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="45258-126">Required.</span></span> <span data-ttu-id="45258-127">Der Name des Tresors</span><span class="sxs-lookup"><span data-stu-id="45258-127">The name of the vault</span></span>
            </param>
        <param name="customRequestHeaders">
            <span data-ttu-id="45258-128">Optional.</span><span class="sxs-lookup"><span data-stu-id="45258-128">Optional.</span></span> <span data-ttu-id="45258-129">Header Anforderungsparameter.</span><span class="sxs-lookup"><span data-stu-id="45258-129">Request header parameters.</span></span>
            </param>
        <summary>
            <span data-ttu-id="45258-130">Löscht die angegebene Azure backup-Tresor.</span><span class="sxs-lookup"><span data-stu-id="45258-130">Deletes the specified Azure backup vault.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="45258-131">Tresorinformationen.</span><span class="sxs-lookup"><span data-stu-id="45258-131">Vault information.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.BackupServices.Models.AzureBackupVaultGetResponse&gt; DeleteAsync (this Microsoft.Azure.Management.BackupServices.IVaultOperations operations, string resourceGroupName, string resourceName, Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders customRequestHeaders);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.BackupServices.Models.AzureBackupVaultGetResponse&gt; DeleteAsync(class Microsoft.Azure.Management.BackupServices.IVaultOperations operations, string resourceGroupName, string resourceName, class Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders customRequestHeaders) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.BackupServices.VaultOperationsExtensions.DeleteAsync(Microsoft.Azure.Management.BackupServices.IVaultOperations,System.String,System.String,Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders)" />
      <MemberSignature Language="F#" Value="static member DeleteAsync : Microsoft.Azure.Management.BackupServices.IVaultOperations * string * string * Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.BackupServices.Models.AzureBackupVaultGetResponse&gt;" Usage="Microsoft.Azure.Management.BackupServices.VaultOperationsExtensions.DeleteAsync (operations, resourceGroupName, resourceName, customRequestHeaders)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BackupServicesManagement</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.BackupServices.Models.AzureBackupVaultGetResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.BackupServices.IVaultOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="resourceName" Type="System.String" />
        <Parameter Name="customRequestHeaders" Type="Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="45258-132">Verweis auf die Microsoft.Azure.Management.BackupServices.IVaultOperations.</span><span class="sxs-lookup"><span data-stu-id="45258-132">Reference to the Microsoft.Azure.Management.BackupServices.IVaultOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="45258-133">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="45258-133">Required.</span></span> <span data-ttu-id="45258-134">Der Name der Ressourcengruppe, in welche Tresor gehört</span><span class="sxs-lookup"><span data-stu-id="45258-134">The name of resource group to which vault belongs</span></span>
            </param>
        <param name="resourceName">
            <span data-ttu-id="45258-135">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="45258-135">Required.</span></span> <span data-ttu-id="45258-136">Der Name des Tresors</span><span class="sxs-lookup"><span data-stu-id="45258-136">The name of the vault</span></span>
            </param>
        <param name="customRequestHeaders">
            <span data-ttu-id="45258-137">Optional.</span><span class="sxs-lookup"><span data-stu-id="45258-137">Optional.</span></span> <span data-ttu-id="45258-138">Header Anforderungsparameter.</span><span class="sxs-lookup"><span data-stu-id="45258-138">Request header parameters.</span></span>
            </param>
        <summary>
            <span data-ttu-id="45258-139">Löscht die angegebene Azure backup-Tresor.</span><span class="sxs-lookup"><span data-stu-id="45258-139">Deletes the specified Azure backup vault.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="45258-140">Tresorinformationen.</span><span class="sxs-lookup"><span data-stu-id="45258-140">Vault information.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Get">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.BackupServices.Models.AzureBackupVaultGetResponse Get (this Microsoft.Azure.Management.BackupServices.IVaultOperations operations, string resourceGroupName, string resourceName, Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders customRequestHeaders);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.BackupServices.Models.AzureBackupVaultGetResponse Get(class Microsoft.Azure.Management.BackupServices.IVaultOperations operations, string resourceGroupName, string resourceName, class Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders customRequestHeaders) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.BackupServices.VaultOperationsExtensions.Get(Microsoft.Azure.Management.BackupServices.IVaultOperations,System.String,System.String,Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders)" />
      <MemberSignature Language="F#" Value="static member Get : Microsoft.Azure.Management.BackupServices.IVaultOperations * string * string * Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders -&gt; Microsoft.Azure.Management.BackupServices.Models.AzureBackupVaultGetResponse" Usage="Microsoft.Azure.Management.BackupServices.VaultOperationsExtensions.Get (operations, resourceGroupName, resourceName, customRequestHeaders)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BackupServicesManagement</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.BackupServices.Models.AzureBackupVaultGetResponse</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.BackupServices.IVaultOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="resourceName" Type="System.String" />
        <Parameter Name="customRequestHeaders" Type="Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="45258-141">Verweis auf die Microsoft.Azure.Management.BackupServices.IVaultOperations.</span><span class="sxs-lookup"><span data-stu-id="45258-141">Reference to the Microsoft.Azure.Management.BackupServices.IVaultOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="45258-142">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="45258-142">Required.</span></span> <span data-ttu-id="45258-143">Der Name der Ressourcengruppe, in welche Tresor gehört</span><span class="sxs-lookup"><span data-stu-id="45258-143">The name of resource group to which vault belongs</span></span>
            </param>
        <param name="resourceName">
            <span data-ttu-id="45258-144">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="45258-144">Required.</span></span> <span data-ttu-id="45258-145">Der Name des Tresors</span><span class="sxs-lookup"><span data-stu-id="45258-145">The name of the vault</span></span>
            </param>
        <param name="customRequestHeaders">
            <span data-ttu-id="45258-146">Optional.</span><span class="sxs-lookup"><span data-stu-id="45258-146">Optional.</span></span> <span data-ttu-id="45258-147">Header Anforderungsparameter.</span><span class="sxs-lookup"><span data-stu-id="45258-147">Request header parameters.</span></span>
            </param>
        <summary>
            <span data-ttu-id="45258-148">Ruft die angegebene Azure-schlüsseltresor.</span><span class="sxs-lookup"><span data-stu-id="45258-148">Gets the specified Azure key vault.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="45258-149">Tresorinformationen.</span><span class="sxs-lookup"><span data-stu-id="45258-149">Vault information.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.BackupServices.Models.AzureBackupVaultGetResponse&gt; GetAsync (this Microsoft.Azure.Management.BackupServices.IVaultOperations operations, string resourceGroupName, string resourceName, Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders customRequestHeaders);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.BackupServices.Models.AzureBackupVaultGetResponse&gt; GetAsync(class Microsoft.Azure.Management.BackupServices.IVaultOperations operations, string resourceGroupName, string resourceName, class Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders customRequestHeaders) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.BackupServices.VaultOperationsExtensions.GetAsync(Microsoft.Azure.Management.BackupServices.IVaultOperations,System.String,System.String,Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders)" />
      <MemberSignature Language="F#" Value="static member GetAsync : Microsoft.Azure.Management.BackupServices.IVaultOperations * string * string * Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.BackupServices.Models.AzureBackupVaultGetResponse&gt;" Usage="Microsoft.Azure.Management.BackupServices.VaultOperationsExtensions.GetAsync (operations, resourceGroupName, resourceName, customRequestHeaders)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BackupServicesManagement</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.BackupServices.Models.AzureBackupVaultGetResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.BackupServices.IVaultOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="resourceName" Type="System.String" />
        <Parameter Name="customRequestHeaders" Type="Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="45258-150">Verweis auf die Microsoft.Azure.Management.BackupServices.IVaultOperations.</span><span class="sxs-lookup"><span data-stu-id="45258-150">Reference to the Microsoft.Azure.Management.BackupServices.IVaultOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="45258-151">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="45258-151">Required.</span></span> <span data-ttu-id="45258-152">Der Name der Ressourcengruppe, in welche Tresor gehört</span><span class="sxs-lookup"><span data-stu-id="45258-152">The name of resource group to which vault belongs</span></span>
            </param>
        <param name="resourceName">
            <span data-ttu-id="45258-153">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="45258-153">Required.</span></span> <span data-ttu-id="45258-154">Der Name des Tresors</span><span class="sxs-lookup"><span data-stu-id="45258-154">The name of the vault</span></span>
            </param>
        <param name="customRequestHeaders">
            <span data-ttu-id="45258-155">Optional.</span><span class="sxs-lookup"><span data-stu-id="45258-155">Optional.</span></span> <span data-ttu-id="45258-156">Header Anforderungsparameter.</span><span class="sxs-lookup"><span data-stu-id="45258-156">Request header parameters.</span></span>
            </param>
        <summary>
            <span data-ttu-id="45258-157">Ruft die angegebene Azure-schlüsseltresor.</span><span class="sxs-lookup"><span data-stu-id="45258-157">Gets the specified Azure key vault.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="45258-158">Tresorinformationen.</span><span class="sxs-lookup"><span data-stu-id="45258-158">Vault information.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetResourceStorageConfig">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.BackupServices.Models.GetResourceStorageConfigResponse GetResourceStorageConfig (this Microsoft.Azure.Management.BackupServices.IVaultOperations operations, string resourceGroupName, string resourceName, Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders customRequestHeaders);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.BackupServices.Models.GetResourceStorageConfigResponse GetResourceStorageConfig(class Microsoft.Azure.Management.BackupServices.IVaultOperations operations, string resourceGroupName, string resourceName, class Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders customRequestHeaders) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.BackupServices.VaultOperationsExtensions.GetResourceStorageConfig(Microsoft.Azure.Management.BackupServices.IVaultOperations,System.String,System.String,Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders)" />
      <MemberSignature Language="F#" Value="static member GetResourceStorageConfig : Microsoft.Azure.Management.BackupServices.IVaultOperations * string * string * Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders -&gt; Microsoft.Azure.Management.BackupServices.Models.GetResourceStorageConfigResponse" Usage="Microsoft.Azure.Management.BackupServices.VaultOperationsExtensions.GetResourceStorageConfig (operations, resourceGroupName, resourceName, customRequestHeaders)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BackupServicesManagement</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.BackupServices.Models.GetResourceStorageConfigResponse</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.BackupServices.IVaultOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="resourceName" Type="System.String" />
        <Parameter Name="customRequestHeaders" Type="Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="45258-159">Verweis auf die Microsoft.Azure.Management.BackupServices.IVaultOperations.</span><span class="sxs-lookup"><span data-stu-id="45258-159">Reference to the Microsoft.Azure.Management.BackupServices.IVaultOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="45258-160">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="45258-160">Required.</span></span> <span data-ttu-id="45258-161">Der Name der Ressourcengruppe, in welche Tresor gehört</span><span class="sxs-lookup"><span data-stu-id="45258-161">The name of resource group to which vault belongs</span></span>
            </param>
        <param name="resourceName">
            <span data-ttu-id="45258-162">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="45258-162">Required.</span></span> <span data-ttu-id="45258-163">Der Name des Tresors</span><span class="sxs-lookup"><span data-stu-id="45258-163">The name of the vault</span></span>
            </param>
        <param name="customRequestHeaders">
            <span data-ttu-id="45258-164">Optional.</span><span class="sxs-lookup"><span data-stu-id="45258-164">Optional.</span></span> <span data-ttu-id="45258-165">Header Anforderungsparameter.</span><span class="sxs-lookup"><span data-stu-id="45258-165">Request header parameters.</span></span>
            </param>
        <summary>
            <span data-ttu-id="45258-166">Ruft die Ressourcenkonfiguration Speicher ab.</span><span class="sxs-lookup"><span data-stu-id="45258-166">Fetches resource storage config.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="45258-167">Die Definition einer Get-Speicher-Config Ressourcenantwort.</span><span class="sxs-lookup"><span data-stu-id="45258-167">The definition of a get resource storage config response.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetResourceStorageConfigAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.BackupServices.Models.GetResourceStorageConfigResponse&gt; GetResourceStorageConfigAsync (this Microsoft.Azure.Management.BackupServices.IVaultOperations operations, string resourceGroupName, string resourceName, Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders customRequestHeaders);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.BackupServices.Models.GetResourceStorageConfigResponse&gt; GetResourceStorageConfigAsync(class Microsoft.Azure.Management.BackupServices.IVaultOperations operations, string resourceGroupName, string resourceName, class Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders customRequestHeaders) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.BackupServices.VaultOperationsExtensions.GetResourceStorageConfigAsync(Microsoft.Azure.Management.BackupServices.IVaultOperations,System.String,System.String,Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders)" />
      <MemberSignature Language="F#" Value="static member GetResourceStorageConfigAsync : Microsoft.Azure.Management.BackupServices.IVaultOperations * string * string * Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.BackupServices.Models.GetResourceStorageConfigResponse&gt;" Usage="Microsoft.Azure.Management.BackupServices.VaultOperationsExtensions.GetResourceStorageConfigAsync (operations, resourceGroupName, resourceName, customRequestHeaders)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BackupServicesManagement</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.BackupServices.Models.GetResourceStorageConfigResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.BackupServices.IVaultOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="resourceName" Type="System.String" />
        <Parameter Name="customRequestHeaders" Type="Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="45258-168">Verweis auf die Microsoft.Azure.Management.BackupServices.IVaultOperations.</span><span class="sxs-lookup"><span data-stu-id="45258-168">Reference to the Microsoft.Azure.Management.BackupServices.IVaultOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="45258-169">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="45258-169">Required.</span></span> <span data-ttu-id="45258-170">Der Name der Ressourcengruppe, in welche Tresor gehört</span><span class="sxs-lookup"><span data-stu-id="45258-170">The name of resource group to which vault belongs</span></span>
            </param>
        <param name="resourceName">
            <span data-ttu-id="45258-171">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="45258-171">Required.</span></span> <span data-ttu-id="45258-172">Der Name des Tresors</span><span class="sxs-lookup"><span data-stu-id="45258-172">The name of the vault</span></span>
            </param>
        <param name="customRequestHeaders">
            <span data-ttu-id="45258-173">Optional.</span><span class="sxs-lookup"><span data-stu-id="45258-173">Optional.</span></span> <span data-ttu-id="45258-174">Header Anforderungsparameter.</span><span class="sxs-lookup"><span data-stu-id="45258-174">Request header parameters.</span></span>
            </param>
        <summary>
            <span data-ttu-id="45258-175">Ruft die Ressourcenkonfiguration Speicher ab.</span><span class="sxs-lookup"><span data-stu-id="45258-175">Fetches resource storage config.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="45258-176">Die Definition einer Get-Speicher-Config Ressourcenantwort.</span><span class="sxs-lookup"><span data-stu-id="45258-176">The definition of a get resource storage config response.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="List">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.BackupServices.Models.AzureBackupVaultListResponse List (this Microsoft.Azure.Management.BackupServices.IVaultOperations operations, int top, Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders customRequestHeaders);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.BackupServices.Models.AzureBackupVaultListResponse List(class Microsoft.Azure.Management.BackupServices.IVaultOperations operations, int32 top, class Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders customRequestHeaders) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.BackupServices.VaultOperationsExtensions.List(Microsoft.Azure.Management.BackupServices.IVaultOperations,System.Int32,Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders)" />
      <MemberSignature Language="F#" Value="static member List : Microsoft.Azure.Management.BackupServices.IVaultOperations * int * Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders -&gt; Microsoft.Azure.Management.BackupServices.Models.AzureBackupVaultListResponse" Usage="Microsoft.Azure.Management.BackupServices.VaultOperationsExtensions.List (operations, top, customRequestHeaders)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BackupServicesManagement</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.BackupServices.Models.AzureBackupVaultListResponse</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.BackupServices.IVaultOperations" RefType="this" />
        <Parameter Name="top" Type="System.Int32" />
        <Parameter Name="customRequestHeaders" Type="Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="45258-177">Verweis auf die Microsoft.Azure.Management.BackupServices.IVaultOperations.</span><span class="sxs-lookup"><span data-stu-id="45258-177">Reference to the Microsoft.Azure.Management.BackupServices.IVaultOperations.</span></span>
            </param>
        <param name="top">
            <span data-ttu-id="45258-178">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="45258-178">Required.</span></span> <span data-ttu-id="45258-179">Maximale Anzahl der zurückzugebenden Ergebnisseite.</span><span class="sxs-lookup"><span data-stu-id="45258-179">Maximum number of results to return.</span></span>
            </param>
        <param name="customRequestHeaders">
            <span data-ttu-id="45258-180">Optional.</span><span class="sxs-lookup"><span data-stu-id="45258-180">Optional.</span></span> <span data-ttu-id="45258-181">Header Anforderungsparameter.</span><span class="sxs-lookup"><span data-stu-id="45258-181">Request header parameters.</span></span>
            </param>
        <summary>
            <span data-ttu-id="45258-182">Ruft die sicherungstresore Abonnement zugeordneten Informationen ab.</span><span class="sxs-lookup"><span data-stu-id="45258-182">Gets information of the backup vaults associated with subscription.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="45258-183">Liste der Tresore</span><span class="sxs-lookup"><span data-stu-id="45258-183">List of vaults</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.BackupServices.Models.AzureBackupVaultListResponse&gt; ListAsync (this Microsoft.Azure.Management.BackupServices.IVaultOperations operations, int top, Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders customRequestHeaders);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.BackupServices.Models.AzureBackupVaultListResponse&gt; ListAsync(class Microsoft.Azure.Management.BackupServices.IVaultOperations operations, int32 top, class Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders customRequestHeaders) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.BackupServices.VaultOperationsExtensions.ListAsync(Microsoft.Azure.Management.BackupServices.IVaultOperations,System.Int32,Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders)" />
      <MemberSignature Language="F#" Value="static member ListAsync : Microsoft.Azure.Management.BackupServices.IVaultOperations * int * Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.BackupServices.Models.AzureBackupVaultListResponse&gt;" Usage="Microsoft.Azure.Management.BackupServices.VaultOperationsExtensions.ListAsync (operations, top, customRequestHeaders)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BackupServicesManagement</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.BackupServices.Models.AzureBackupVaultListResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.BackupServices.IVaultOperations" RefType="this" />
        <Parameter Name="top" Type="System.Int32" />
        <Parameter Name="customRequestHeaders" Type="Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="45258-184">Verweis auf die Microsoft.Azure.Management.BackupServices.IVaultOperations.</span><span class="sxs-lookup"><span data-stu-id="45258-184">Reference to the Microsoft.Azure.Management.BackupServices.IVaultOperations.</span></span>
            </param>
        <param name="top">
            <span data-ttu-id="45258-185">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="45258-185">Required.</span></span> <span data-ttu-id="45258-186">Maximale Anzahl der zurückzugebenden Ergebnisseite.</span><span class="sxs-lookup"><span data-stu-id="45258-186">Maximum number of results to return.</span></span>
            </param>
        <param name="customRequestHeaders">
            <span data-ttu-id="45258-187">Optional.</span><span class="sxs-lookup"><span data-stu-id="45258-187">Optional.</span></span> <span data-ttu-id="45258-188">Header Anforderungsparameter.</span><span class="sxs-lookup"><span data-stu-id="45258-188">Request header parameters.</span></span>
            </param>
        <summary>
            <span data-ttu-id="45258-189">Ruft die sicherungstresore Abonnement zugeordneten Informationen ab.</span><span class="sxs-lookup"><span data-stu-id="45258-189">Gets information of the backup vaults associated with subscription.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="45258-190">Liste der Tresore</span><span class="sxs-lookup"><span data-stu-id="45258-190">List of vaults</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByResourceGroup">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.BackupServices.Models.AzureBackupVaultListResponse ListByResourceGroup (this Microsoft.Azure.Management.BackupServices.IVaultOperations operations, string resourceGroupName, int top, Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders customRequestHeaders);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.BackupServices.Models.AzureBackupVaultListResponse ListByResourceGroup(class Microsoft.Azure.Management.BackupServices.IVaultOperations operations, string resourceGroupName, int32 top, class Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders customRequestHeaders) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.BackupServices.VaultOperationsExtensions.ListByResourceGroup(Microsoft.Azure.Management.BackupServices.IVaultOperations,System.String,System.Int32,Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders)" />
      <MemberSignature Language="F#" Value="static member ListByResourceGroup : Microsoft.Azure.Management.BackupServices.IVaultOperations * string * int * Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders -&gt; Microsoft.Azure.Management.BackupServices.Models.AzureBackupVaultListResponse" Usage="Microsoft.Azure.Management.BackupServices.VaultOperationsExtensions.ListByResourceGroup (operations, resourceGroupName, top, customRequestHeaders)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BackupServicesManagement</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.BackupServices.Models.AzureBackupVaultListResponse</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.BackupServices.IVaultOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="top" Type="System.Int32" />
        <Parameter Name="customRequestHeaders" Type="Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="45258-191">Verweis auf die Microsoft.Azure.Management.BackupServices.IVaultOperations.</span><span class="sxs-lookup"><span data-stu-id="45258-191">Reference to the Microsoft.Azure.Management.BackupServices.IVaultOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="45258-192">Optional.</span><span class="sxs-lookup"><span data-stu-id="45258-192">Optional.</span></span> <span data-ttu-id="45258-193">Ein optionales Argument, das den Namen der Ressourcengruppe angibt, die den Satz von Tresoren einschränkt, die zurückgegeben werden.</span><span class="sxs-lookup"><span data-stu-id="45258-193">An optional argument which specifies the name of the resource group that constrains the set of vaults that are returned.</span></span>
            </param>
        <param name="top">
            <span data-ttu-id="45258-194">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="45258-194">Required.</span></span> <span data-ttu-id="45258-195">Maximale Anzahl der zurückzugebenden Ergebnisseite.</span><span class="sxs-lookup"><span data-stu-id="45258-195">Maximum number of results to return.</span></span>
            </param>
        <param name="customRequestHeaders">
            <span data-ttu-id="45258-196">Optional.</span><span class="sxs-lookup"><span data-stu-id="45258-196">Optional.</span></span> <span data-ttu-id="45258-197">Header Anforderungsparameter.</span><span class="sxs-lookup"><span data-stu-id="45258-197">Request header parameters.</span></span>
            </param>
        <summary>
            <span data-ttu-id="45258-198">Ruft die sicherungstresore Ressourcengruppe zugeordneten Informationen ab.</span><span class="sxs-lookup"><span data-stu-id="45258-198">Gets information of the backup vaults associated with resource group.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="45258-199">Liste der Tresore</span><span class="sxs-lookup"><span data-stu-id="45258-199">List of vaults</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByResourceGroupAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.BackupServices.Models.AzureBackupVaultListResponse&gt; ListByResourceGroupAsync (this Microsoft.Azure.Management.BackupServices.IVaultOperations operations, string resourceGroupName, int top, Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders customRequestHeaders);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.BackupServices.Models.AzureBackupVaultListResponse&gt; ListByResourceGroupAsync(class Microsoft.Azure.Management.BackupServices.IVaultOperations operations, string resourceGroupName, int32 top, class Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders customRequestHeaders) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.BackupServices.VaultOperationsExtensions.ListByResourceGroupAsync(Microsoft.Azure.Management.BackupServices.IVaultOperations,System.String,System.Int32,Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders)" />
      <MemberSignature Language="F#" Value="static member ListByResourceGroupAsync : Microsoft.Azure.Management.BackupServices.IVaultOperations * string * int * Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.BackupServices.Models.AzureBackupVaultListResponse&gt;" Usage="Microsoft.Azure.Management.BackupServices.VaultOperationsExtensions.ListByResourceGroupAsync (operations, resourceGroupName, top, customRequestHeaders)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BackupServicesManagement</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.BackupServices.Models.AzureBackupVaultListResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.BackupServices.IVaultOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="top" Type="System.Int32" />
        <Parameter Name="customRequestHeaders" Type="Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="45258-200">Verweis auf die Microsoft.Azure.Management.BackupServices.IVaultOperations.</span><span class="sxs-lookup"><span data-stu-id="45258-200">Reference to the Microsoft.Azure.Management.BackupServices.IVaultOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="45258-201">Optional.</span><span class="sxs-lookup"><span data-stu-id="45258-201">Optional.</span></span> <span data-ttu-id="45258-202">Ein optionales Argument, das den Namen der Ressourcengruppe angibt, die den Satz von Tresoren einschränkt, die zurückgegeben werden.</span><span class="sxs-lookup"><span data-stu-id="45258-202">An optional argument which specifies the name of the resource group that constrains the set of vaults that are returned.</span></span>
            </param>
        <param name="top">
            <span data-ttu-id="45258-203">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="45258-203">Required.</span></span> <span data-ttu-id="45258-204">Maximale Anzahl der zurückzugebenden Ergebnisseite.</span><span class="sxs-lookup"><span data-stu-id="45258-204">Maximum number of results to return.</span></span>
            </param>
        <param name="customRequestHeaders">
            <span data-ttu-id="45258-205">Optional.</span><span class="sxs-lookup"><span data-stu-id="45258-205">Optional.</span></span> <span data-ttu-id="45258-206">Header Anforderungsparameter.</span><span class="sxs-lookup"><span data-stu-id="45258-206">Request header parameters.</span></span>
            </param>
        <summary>
            <span data-ttu-id="45258-207">Ruft die sicherungstresore Ressourcengruppe zugeordneten Informationen ab.</span><span class="sxs-lookup"><span data-stu-id="45258-207">Gets information of the backup vaults associated with resource group.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="45258-208">Liste der Tresore</span><span class="sxs-lookup"><span data-stu-id="45258-208">List of vaults</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UpdateStorageType">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.BackupServices.OperationResponse UpdateStorageType (this Microsoft.Azure.Management.BackupServices.IVaultOperations operations, string resourceGroupName, string resourceName, Microsoft.Azure.Management.BackupServices.Models.UpdateVaultStorageTypeRequest updateVaultStorageTypeRequest, Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders customRequestHeaders);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.BackupServices.OperationResponse UpdateStorageType(class Microsoft.Azure.Management.BackupServices.IVaultOperations operations, string resourceGroupName, string resourceName, class Microsoft.Azure.Management.BackupServices.Models.UpdateVaultStorageTypeRequest updateVaultStorageTypeRequest, class Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders customRequestHeaders) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.BackupServices.VaultOperationsExtensions.UpdateStorageType(Microsoft.Azure.Management.BackupServices.IVaultOperations,System.String,System.String,Microsoft.Azure.Management.BackupServices.Models.UpdateVaultStorageTypeRequest,Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders)" />
      <MemberSignature Language="F#" Value="static member UpdateStorageType : Microsoft.Azure.Management.BackupServices.IVaultOperations * string * string * Microsoft.Azure.Management.BackupServices.Models.UpdateVaultStorageTypeRequest * Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders -&gt; Microsoft.Azure.Management.BackupServices.OperationResponse" Usage="Microsoft.Azure.Management.BackupServices.VaultOperationsExtensions.UpdateStorageType (operations, resourceGroupName, resourceName, updateVaultStorageTypeRequest, customRequestHeaders)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BackupServicesManagement</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.BackupServices.OperationResponse</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.BackupServices.IVaultOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="resourceName" Type="System.String" />
        <Parameter Name="updateVaultStorageTypeRequest" Type="Microsoft.Azure.Management.BackupServices.Models.UpdateVaultStorageTypeRequest" />
        <Parameter Name="customRequestHeaders" Type="Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="45258-209">Verweis auf die Microsoft.Azure.Management.BackupServices.IVaultOperations.</span><span class="sxs-lookup"><span data-stu-id="45258-209">Reference to the Microsoft.Azure.Management.BackupServices.IVaultOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="45258-210">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="45258-210">Required.</span></span>
            </param>
        <param name="resourceName">
            <span data-ttu-id="45258-211">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="45258-211">Required.</span></span>
            </param>
        <param name="updateVaultStorageTypeRequest">
            <span data-ttu-id="45258-212">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="45258-212">Required.</span></span> <span data-ttu-id="45258-213">Anforderung zum Update Tresor Speicher Typ</span><span class="sxs-lookup"><span data-stu-id="45258-213">Update Vault Storage Type Request</span></span>
            </param>
        <param name="customRequestHeaders">
            <span data-ttu-id="45258-214">Optional.</span><span class="sxs-lookup"><span data-stu-id="45258-214">Optional.</span></span> <span data-ttu-id="45258-215">Header Anforderungsparameter.</span><span class="sxs-lookup"><span data-stu-id="45258-215">Request header parameters.</span></span>
            </param>
        <summary>
            <span data-ttu-id="45258-216">Updates Tresor Speichertyp-Modell.</span><span class="sxs-lookup"><span data-stu-id="45258-216">Updates vault storage model type.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="45258-217">Die Definition einer Operation-Antwort.</span><span class="sxs-lookup"><span data-stu-id="45258-217">The definition of a Operation Response.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UpdateStorageTypeAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.BackupServices.OperationResponse&gt; UpdateStorageTypeAsync (this Microsoft.Azure.Management.BackupServices.IVaultOperations operations, string resourceGroupName, string resourceName, Microsoft.Azure.Management.BackupServices.Models.UpdateVaultStorageTypeRequest updateVaultStorageTypeRequest, Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders customRequestHeaders);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.BackupServices.OperationResponse&gt; UpdateStorageTypeAsync(class Microsoft.Azure.Management.BackupServices.IVaultOperations operations, string resourceGroupName, string resourceName, class Microsoft.Azure.Management.BackupServices.Models.UpdateVaultStorageTypeRequest updateVaultStorageTypeRequest, class Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders customRequestHeaders) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.BackupServices.VaultOperationsExtensions.UpdateStorageTypeAsync(Microsoft.Azure.Management.BackupServices.IVaultOperations,System.String,System.String,Microsoft.Azure.Management.BackupServices.Models.UpdateVaultStorageTypeRequest,Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders)" />
      <MemberSignature Language="F#" Value="static member UpdateStorageTypeAsync : Microsoft.Azure.Management.BackupServices.IVaultOperations * string * string * Microsoft.Azure.Management.BackupServices.Models.UpdateVaultStorageTypeRequest * Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.BackupServices.OperationResponse&gt;" Usage="Microsoft.Azure.Management.BackupServices.VaultOperationsExtensions.UpdateStorageTypeAsync (operations, resourceGroupName, resourceName, updateVaultStorageTypeRequest, customRequestHeaders)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BackupServicesManagement</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.BackupServices.OperationResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.BackupServices.IVaultOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="resourceName" Type="System.String" />
        <Parameter Name="updateVaultStorageTypeRequest" Type="Microsoft.Azure.Management.BackupServices.Models.UpdateVaultStorageTypeRequest" />
        <Parameter Name="customRequestHeaders" Type="Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="45258-218">Verweis auf die Microsoft.Azure.Management.BackupServices.IVaultOperations.</span><span class="sxs-lookup"><span data-stu-id="45258-218">Reference to the Microsoft.Azure.Management.BackupServices.IVaultOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="45258-219">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="45258-219">Required.</span></span>
            </param>
        <param name="resourceName">
            <span data-ttu-id="45258-220">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="45258-220">Required.</span></span>
            </param>
        <param name="updateVaultStorageTypeRequest">
            <span data-ttu-id="45258-221">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="45258-221">Required.</span></span> <span data-ttu-id="45258-222">Anforderung zum Update Tresor Speicher Typ</span><span class="sxs-lookup"><span data-stu-id="45258-222">Update Vault Storage Type Request</span></span>
            </param>
        <param name="customRequestHeaders">
            <span data-ttu-id="45258-223">Optional.</span><span class="sxs-lookup"><span data-stu-id="45258-223">Optional.</span></span> <span data-ttu-id="45258-224">Header Anforderungsparameter.</span><span class="sxs-lookup"><span data-stu-id="45258-224">Request header parameters.</span></span>
            </param>
        <summary>
            <span data-ttu-id="45258-225">Updates Tresor Speichertyp-Modell.</span><span class="sxs-lookup"><span data-stu-id="45258-225">Updates vault storage model type.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="45258-226">Die Definition einer Operation-Antwort.</span><span class="sxs-lookup"><span data-stu-id="45258-226">The definition of a Operation Response.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UploadCertificate">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.BackupServices.Models.VaultCredUploadCertResponse UploadCertificate (this Microsoft.Azure.Management.BackupServices.IVaultOperations operations, string resourceGroupName, string resourceName, string certificateName, Microsoft.Azure.Management.BackupServices.Models.VaultCredUploadCertRequest vaultCredUploadCertRequest, Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders customRequestHeaders);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.BackupServices.Models.VaultCredUploadCertResponse UploadCertificate(class Microsoft.Azure.Management.BackupServices.IVaultOperations operations, string resourceGroupName, string resourceName, string certificateName, class Microsoft.Azure.Management.BackupServices.Models.VaultCredUploadCertRequest vaultCredUploadCertRequest, class Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders customRequestHeaders) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.BackupServices.VaultOperationsExtensions.UploadCertificate(Microsoft.Azure.Management.BackupServices.IVaultOperations,System.String,System.String,System.String,Microsoft.Azure.Management.BackupServices.Models.VaultCredUploadCertRequest,Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders)" />
      <MemberSignature Language="F#" Value="static member UploadCertificate : Microsoft.Azure.Management.BackupServices.IVaultOperations * string * string * string * Microsoft.Azure.Management.BackupServices.Models.VaultCredUploadCertRequest * Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders -&gt; Microsoft.Azure.Management.BackupServices.Models.VaultCredUploadCertResponse" Usage="Microsoft.Azure.Management.BackupServices.VaultOperationsExtensions.UploadCertificate (operations, resourceGroupName, resourceName, certificateName, vaultCredUploadCertRequest, customRequestHeaders)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BackupServicesManagement</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.BackupServices.Models.VaultCredUploadCertResponse</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.BackupServices.IVaultOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="resourceName" Type="System.String" />
        <Parameter Name="certificateName" Type="System.String" />
        <Parameter Name="vaultCredUploadCertRequest" Type="Microsoft.Azure.Management.BackupServices.Models.VaultCredUploadCertRequest" />
        <Parameter Name="customRequestHeaders" Type="Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="45258-227">Verweis auf die Microsoft.Azure.Management.BackupServices.IVaultOperations.</span><span class="sxs-lookup"><span data-stu-id="45258-227">Reference to the Microsoft.Azure.Management.BackupServices.IVaultOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="45258-228">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="45258-228">Required.</span></span>
            </param>
        <param name="resourceName">
            <span data-ttu-id="45258-229">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="45258-229">Required.</span></span>
            </param>
        <param name="certificateName">
            <span data-ttu-id="45258-230">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="45258-230">Required.</span></span> <span data-ttu-id="45258-231">Der Name des Zertifikats.</span><span class="sxs-lookup"><span data-stu-id="45258-231">Name of the certificate.</span></span>
            </param>
        <param name="vaultCredUploadCertRequest">
            <span data-ttu-id="45258-232">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="45258-232">Required.</span></span> <span data-ttu-id="45258-233">Zertifikatparameter.</span><span class="sxs-lookup"><span data-stu-id="45258-233">Certificate parameters.</span></span>
            </param>
        <param name="customRequestHeaders">
            <span data-ttu-id="45258-234">Optional.</span><span class="sxs-lookup"><span data-stu-id="45258-234">Optional.</span></span> <span data-ttu-id="45258-235">Header Anforderungsparameter.</span><span class="sxs-lookup"><span data-stu-id="45258-235">Request header parameters.</span></span>
            </param>
        <summary>
            <span data-ttu-id="45258-236">Uploads Tresor Zertifikat für Anmeldeinformationen.</span><span class="sxs-lookup"><span data-stu-id="45258-236">Uploads vault credential certificate.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="45258-237">Die Definition einer Antwort Zertifikat.</span><span class="sxs-lookup"><span data-stu-id="45258-237">The definition of a certificate response.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UploadCertificateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.BackupServices.Models.VaultCredUploadCertResponse&gt; UploadCertificateAsync (this Microsoft.Azure.Management.BackupServices.IVaultOperations operations, string resourceGroupName, string resourceName, string certificateName, Microsoft.Azure.Management.BackupServices.Models.VaultCredUploadCertRequest vaultCredUploadCertRequest, Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders customRequestHeaders);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.BackupServices.Models.VaultCredUploadCertResponse&gt; UploadCertificateAsync(class Microsoft.Azure.Management.BackupServices.IVaultOperations operations, string resourceGroupName, string resourceName, string certificateName, class Microsoft.Azure.Management.BackupServices.Models.VaultCredUploadCertRequest vaultCredUploadCertRequest, class Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders customRequestHeaders) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.BackupServices.VaultOperationsExtensions.UploadCertificateAsync(Microsoft.Azure.Management.BackupServices.IVaultOperations,System.String,System.String,System.String,Microsoft.Azure.Management.BackupServices.Models.VaultCredUploadCertRequest,Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders)" />
      <MemberSignature Language="F#" Value="static member UploadCertificateAsync : Microsoft.Azure.Management.BackupServices.IVaultOperations * string * string * string * Microsoft.Azure.Management.BackupServices.Models.VaultCredUploadCertRequest * Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.BackupServices.Models.VaultCredUploadCertResponse&gt;" Usage="Microsoft.Azure.Management.BackupServices.VaultOperationsExtensions.UploadCertificateAsync (operations, resourceGroupName, resourceName, certificateName, vaultCredUploadCertRequest, customRequestHeaders)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BackupServicesManagement</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.BackupServices.Models.VaultCredUploadCertResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.BackupServices.IVaultOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="resourceName" Type="System.String" />
        <Parameter Name="certificateName" Type="System.String" />
        <Parameter Name="vaultCredUploadCertRequest" Type="Microsoft.Azure.Management.BackupServices.Models.VaultCredUploadCertRequest" />
        <Parameter Name="customRequestHeaders" Type="Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="45258-238">Verweis auf die Microsoft.Azure.Management.BackupServices.IVaultOperations.</span><span class="sxs-lookup"><span data-stu-id="45258-238">Reference to the Microsoft.Azure.Management.BackupServices.IVaultOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="45258-239">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="45258-239">Required.</span></span>
            </param>
        <param name="resourceName">
            <span data-ttu-id="45258-240">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="45258-240">Required.</span></span>
            </param>
        <param name="certificateName">
            <span data-ttu-id="45258-241">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="45258-241">Required.</span></span> <span data-ttu-id="45258-242">Der Name des Zertifikats.</span><span class="sxs-lookup"><span data-stu-id="45258-242">Name of the certificate.</span></span>
            </param>
        <param name="vaultCredUploadCertRequest">
            <span data-ttu-id="45258-243">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="45258-243">Required.</span></span> <span data-ttu-id="45258-244">Zertifikatparameter.</span><span class="sxs-lookup"><span data-stu-id="45258-244">Certificate parameters.</span></span>
            </param>
        <param name="customRequestHeaders">
            <span data-ttu-id="45258-245">Optional.</span><span class="sxs-lookup"><span data-stu-id="45258-245">Optional.</span></span> <span data-ttu-id="45258-246">Header Anforderungsparameter.</span><span class="sxs-lookup"><span data-stu-id="45258-246">Request header parameters.</span></span>
            </param>
        <summary>
            <span data-ttu-id="45258-247">Uploads Tresor Zertifikat für Anmeldeinformationen.</span><span class="sxs-lookup"><span data-stu-id="45258-247">Uploads vault credential certificate.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="45258-248">Die Definition einer Antwort Zertifikat.</span><span class="sxs-lookup"><span data-stu-id="45258-248">The definition of a certificate response.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>