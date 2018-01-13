<Type Name="VaultsOperationsExtensions" FullName="Microsoft.Azure.Management.KeyVault.VaultsOperationsExtensions">
  <TypeSignature Language="C#" Value="public static class VaultsOperationsExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit VaultsOperationsExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.KeyVault.VaultsOperationsExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module VaultsOperationsExtensions" />
  <TypeSignature Language="F#" Value="type VaultsOperationsExtensions = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.KeyVault</AssemblyName>
    <AssemblyVersion>2.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="eb827-101">Erweiterungsmethoden für VaultsOperations.</span><span class="sxs-lookup"><span data-stu-id="eb827-101">Extension methods for VaultsOperations.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="BeginPurgeDeleted">
      <MemberSignature Language="C#" Value="public static void BeginPurgeDeleted (this Microsoft.Azure.Management.KeyVault.IVaultsOperations operations, string vaultName, string location);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void BeginPurgeDeleted(class Microsoft.Azure.Management.KeyVault.IVaultsOperations operations, string vaultName, string location) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.KeyVault.VaultsOperationsExtensions.BeginPurgeDeleted(Microsoft.Azure.Management.KeyVault.IVaultsOperations,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Sub BeginPurgeDeleted (operations As IVaultsOperations, vaultName As String, location As String)" />
      <MemberSignature Language="F#" Value="static member BeginPurgeDeleted : Microsoft.Azure.Management.KeyVault.IVaultsOperations * string * string -&gt; unit" Usage="Microsoft.Azure.Management.KeyVault.VaultsOperationsExtensions.BeginPurgeDeleted (operations, vaultName, location)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.KeyVault.IVaultsOperations" RefType="this" />
        <Parameter Name="vaultName" Type="System.String" />
        <Parameter Name="location" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="eb827-102">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="eb827-102">The operations group for this extension method.</span></span>
            </param>
        <param name="vaultName">
            <span data-ttu-id="eb827-103">Der Name des Tresors vorläufig gelöscht.</span><span class="sxs-lookup"><span data-stu-id="eb827-103">The name of the soft-deleted vault.</span></span>
            </param>
        <param name="location">
            <span data-ttu-id="eb827-104">Der Speicherort des Tresors vorläufig gelöscht.</span><span class="sxs-lookup"><span data-stu-id="eb827-104">The location of the soft-deleted vault.</span></span>
            </param>
        <summary>
            <span data-ttu-id="eb827-105">Dauerhaft löscht den angegebenen Tresor.</span><span class="sxs-lookup"><span data-stu-id="eb827-105">Permanently deletes the specified vault.</span></span> <span data-ttu-id="eb827-106">d. h. löscht gelöschte Azure Key Vault.</span><span class="sxs-lookup"><span data-stu-id="eb827-106">aka Purges the deleted Azure key vault.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginPurgeDeletedAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task BeginPurgeDeletedAsync (this Microsoft.Azure.Management.KeyVault.IVaultsOperations operations, string vaultName, string location, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task BeginPurgeDeletedAsync(class Microsoft.Azure.Management.KeyVault.IVaultsOperations operations, string vaultName, string location, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.KeyVault.VaultsOperationsExtensions.BeginPurgeDeletedAsync(Microsoft.Azure.Management.KeyVault.IVaultsOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginPurgeDeletedAsync : Microsoft.Azure.Management.KeyVault.IVaultsOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.KeyVault.VaultsOperationsExtensions.BeginPurgeDeletedAsync (operations, vaultName, location, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.KeyVault.VaultsOperationsExtensions/&lt;BeginPurgeDeletedAsync&gt;d__15))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.KeyVault.IVaultsOperations" RefType="this" />
        <Parameter Name="vaultName" Type="System.String" />
        <Parameter Name="location" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="eb827-107">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="eb827-107">The operations group for this extension method.</span></span>
            </param>
        <param name="vaultName">
            <span data-ttu-id="eb827-108">Der Name des Tresors vorläufig gelöscht.</span><span class="sxs-lookup"><span data-stu-id="eb827-108">The name of the soft-deleted vault.</span></span>
            </param>
        <param name="location">
            <span data-ttu-id="eb827-109">Der Speicherort des Tresors vorläufig gelöscht.</span><span class="sxs-lookup"><span data-stu-id="eb827-109">The location of the soft-deleted vault.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="eb827-110">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="eb827-110">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="eb827-111">Dauerhaft löscht den angegebenen Tresor.</span><span class="sxs-lookup"><span data-stu-id="eb827-111">Permanently deletes the specified vault.</span></span> <span data-ttu-id="eb827-112">d. h. löscht gelöschte Azure Key Vault.</span><span class="sxs-lookup"><span data-stu-id="eb827-112">aka Purges the deleted Azure key vault.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateOrUpdate">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.KeyVault.Models.Vault CreateOrUpdate (this Microsoft.Azure.Management.KeyVault.IVaultsOperations operations, string resourceGroupName, string vaultName, Microsoft.Azure.Management.KeyVault.Models.VaultCreateOrUpdateParameters parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.KeyVault.Models.Vault CreateOrUpdate(class Microsoft.Azure.Management.KeyVault.IVaultsOperations operations, string resourceGroupName, string vaultName, class Microsoft.Azure.Management.KeyVault.Models.VaultCreateOrUpdateParameters parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.KeyVault.VaultsOperationsExtensions.CreateOrUpdate(Microsoft.Azure.Management.KeyVault.IVaultsOperations,System.String,System.String,Microsoft.Azure.Management.KeyVault.Models.VaultCreateOrUpdateParameters)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function CreateOrUpdate (operations As IVaultsOperations, resourceGroupName As String, vaultName As String, parameters As VaultCreateOrUpdateParameters) As Vault" />
      <MemberSignature Language="F#" Value="static member CreateOrUpdate : Microsoft.Azure.Management.KeyVault.IVaultsOperations * string * string * Microsoft.Azure.Management.KeyVault.Models.VaultCreateOrUpdateParameters -&gt; Microsoft.Azure.Management.KeyVault.Models.Vault" Usage="Microsoft.Azure.Management.KeyVault.VaultsOperationsExtensions.CreateOrUpdate (operations, resourceGroupName, vaultName, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.KeyVault.Models.Vault</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.KeyVault.IVaultsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="vaultName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.KeyVault.Models.VaultCreateOrUpdateParameters" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="eb827-113">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="eb827-113">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="eb827-114">Der Name der Ressourcengruppe, zu der der Server gehört.</span><span class="sxs-lookup"><span data-stu-id="eb827-114">The name of the Resource Group to which the server belongs.</span></span>
            </param>
        <param name="vaultName">
            <span data-ttu-id="eb827-115">Name des Tresors</span><span class="sxs-lookup"><span data-stu-id="eb827-115">Name of the vault</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="eb827-116">Parameter zum Erstellen oder aktualisieren den Tresor</span><span class="sxs-lookup"><span data-stu-id="eb827-116">Parameters to create or update the vault</span></span>
            </param>
        <summary>
            <span data-ttu-id="eb827-117">Erstellen oder Aktualisieren eines schlüsseltresors im angegebenen Abonnement.</span><span class="sxs-lookup"><span data-stu-id="eb827-117">Create or update a key vault in the specified subscription.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateOrUpdateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.KeyVault.Models.Vault&gt; CreateOrUpdateAsync (this Microsoft.Azure.Management.KeyVault.IVaultsOperations operations, string resourceGroupName, string vaultName, Microsoft.Azure.Management.KeyVault.Models.VaultCreateOrUpdateParameters parameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.KeyVault.Models.Vault&gt; CreateOrUpdateAsync(class Microsoft.Azure.Management.KeyVault.IVaultsOperations operations, string resourceGroupName, string vaultName, class Microsoft.Azure.Management.KeyVault.Models.VaultCreateOrUpdateParameters parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.KeyVault.VaultsOperationsExtensions.CreateOrUpdateAsync(Microsoft.Azure.Management.KeyVault.IVaultsOperations,System.String,System.String,Microsoft.Azure.Management.KeyVault.Models.VaultCreateOrUpdateParameters,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member CreateOrUpdateAsync : Microsoft.Azure.Management.KeyVault.IVaultsOperations * string * string * Microsoft.Azure.Management.KeyVault.Models.VaultCreateOrUpdateParameters * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.KeyVault.Models.Vault&gt;" Usage="Microsoft.Azure.Management.KeyVault.VaultsOperationsExtensions.CreateOrUpdateAsync (operations, resourceGroupName, vaultName, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.KeyVault.VaultsOperationsExtensions/&lt;CreateOrUpdateAsync&gt;d__1))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.KeyVault.Models.Vault&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.KeyVault.IVaultsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="vaultName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.KeyVault.Models.VaultCreateOrUpdateParameters" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="eb827-118">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="eb827-118">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="eb827-119">Der Name der Ressourcengruppe, zu der der Server gehört.</span><span class="sxs-lookup"><span data-stu-id="eb827-119">The name of the Resource Group to which the server belongs.</span></span>
            </param>
        <param name="vaultName">
            <span data-ttu-id="eb827-120">Name des Tresors</span><span class="sxs-lookup"><span data-stu-id="eb827-120">Name of the vault</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="eb827-121">Parameter zum Erstellen oder aktualisieren den Tresor</span><span class="sxs-lookup"><span data-stu-id="eb827-121">Parameters to create or update the vault</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="eb827-122">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="eb827-122">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="eb827-123">Erstellen oder Aktualisieren eines schlüsseltresors im angegebenen Abonnement.</span><span class="sxs-lookup"><span data-stu-id="eb827-123">Create or update a key vault in the specified subscription.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Delete">
      <MemberSignature Language="C#" Value="public static void Delete (this Microsoft.Azure.Management.KeyVault.IVaultsOperations operations, string resourceGroupName, string vaultName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void Delete(class Microsoft.Azure.Management.KeyVault.IVaultsOperations operations, string resourceGroupName, string vaultName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.KeyVault.VaultsOperationsExtensions.Delete(Microsoft.Azure.Management.KeyVault.IVaultsOperations,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Sub Delete (operations As IVaultsOperations, resourceGroupName As String, vaultName As String)" />
      <MemberSignature Language="F#" Value="static member Delete : Microsoft.Azure.Management.KeyVault.IVaultsOperations * string * string -&gt; unit" Usage="Microsoft.Azure.Management.KeyVault.VaultsOperationsExtensions.Delete (operations, resourceGroupName, vaultName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.KeyVault.IVaultsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="vaultName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="eb827-124">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="eb827-124">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="eb827-125">Der Name der Ressourcengruppe, zu dem Tresor gehört.</span><span class="sxs-lookup"><span data-stu-id="eb827-125">The name of the Resource Group to which the vault belongs.</span></span>
            </param>
        <param name="vaultName">
            <span data-ttu-id="eb827-126">Der Name des dem Tresor löschen</span><span class="sxs-lookup"><span data-stu-id="eb827-126">The name of the vault to delete</span></span>
            </param>
        <summary>
            <span data-ttu-id="eb827-127">Löscht die angegebene Azure-schlüsseltresor.</span><span class="sxs-lookup"><span data-stu-id="eb827-127">Deletes the specified Azure key vault.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task DeleteAsync (this Microsoft.Azure.Management.KeyVault.IVaultsOperations operations, string resourceGroupName, string vaultName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task DeleteAsync(class Microsoft.Azure.Management.KeyVault.IVaultsOperations operations, string resourceGroupName, string vaultName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.KeyVault.VaultsOperationsExtensions.DeleteAsync(Microsoft.Azure.Management.KeyVault.IVaultsOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member DeleteAsync : Microsoft.Azure.Management.KeyVault.IVaultsOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.KeyVault.VaultsOperationsExtensions.DeleteAsync (operations, resourceGroupName, vaultName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.KeyVault.VaultsOperationsExtensions/&lt;DeleteAsync&gt;d__3))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.KeyVault.IVaultsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="vaultName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="eb827-128">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="eb827-128">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="eb827-129">Der Name der Ressourcengruppe, zu dem Tresor gehört.</span><span class="sxs-lookup"><span data-stu-id="eb827-129">The name of the Resource Group to which the vault belongs.</span></span>
            </param>
        <param name="vaultName">
            <span data-ttu-id="eb827-130">Der Name des dem Tresor löschen</span><span class="sxs-lookup"><span data-stu-id="eb827-130">The name of the vault to delete</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="eb827-131">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="eb827-131">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="eb827-132">Löscht die angegebene Azure-schlüsseltresor.</span><span class="sxs-lookup"><span data-stu-id="eb827-132">Deletes the specified Azure key vault.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Get">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.KeyVault.Models.Vault Get (this Microsoft.Azure.Management.KeyVault.IVaultsOperations operations, string resourceGroupName, string vaultName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.KeyVault.Models.Vault Get(class Microsoft.Azure.Management.KeyVault.IVaultsOperations operations, string resourceGroupName, string vaultName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.KeyVault.VaultsOperationsExtensions.Get(Microsoft.Azure.Management.KeyVault.IVaultsOperations,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function Get (operations As IVaultsOperations, resourceGroupName As String, vaultName As String) As Vault" />
      <MemberSignature Language="F#" Value="static member Get : Microsoft.Azure.Management.KeyVault.IVaultsOperations * string * string -&gt; Microsoft.Azure.Management.KeyVault.Models.Vault" Usage="Microsoft.Azure.Management.KeyVault.VaultsOperationsExtensions.Get (operations, resourceGroupName, vaultName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.KeyVault.Models.Vault</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.KeyVault.IVaultsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="vaultName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="eb827-133">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="eb827-133">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="eb827-134">Der Name der Ressourcengruppe, zu dem Tresor gehört.</span><span class="sxs-lookup"><span data-stu-id="eb827-134">The name of the Resource Group to which the vault belongs.</span></span>
            </param>
        <param name="vaultName">
            <span data-ttu-id="eb827-135">Der Name des Tresors.</span><span class="sxs-lookup"><span data-stu-id="eb827-135">The name of the vault.</span></span>
            </param>
        <summary>
            <span data-ttu-id="eb827-136">Ruft die angegebene Azure-schlüsseltresor.</span><span class="sxs-lookup"><span data-stu-id="eb827-136">Gets the specified Azure key vault.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.KeyVault.Models.Vault&gt; GetAsync (this Microsoft.Azure.Management.KeyVault.IVaultsOperations operations, string resourceGroupName, string vaultName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.KeyVault.Models.Vault&gt; GetAsync(class Microsoft.Azure.Management.KeyVault.IVaultsOperations operations, string resourceGroupName, string vaultName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.KeyVault.VaultsOperationsExtensions.GetAsync(Microsoft.Azure.Management.KeyVault.IVaultsOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetAsync : Microsoft.Azure.Management.KeyVault.IVaultsOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.KeyVault.Models.Vault&gt;" Usage="Microsoft.Azure.Management.KeyVault.VaultsOperationsExtensions.GetAsync (operations, resourceGroupName, vaultName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.KeyVault.VaultsOperationsExtensions/&lt;GetAsync&gt;d__5))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.KeyVault.Models.Vault&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.KeyVault.IVaultsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="vaultName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="eb827-137">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="eb827-137">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="eb827-138">Der Name der Ressourcengruppe, zu dem Tresor gehört.</span><span class="sxs-lookup"><span data-stu-id="eb827-138">The name of the Resource Group to which the vault belongs.</span></span>
            </param>
        <param name="vaultName">
            <span data-ttu-id="eb827-139">Der Name des Tresors.</span><span class="sxs-lookup"><span data-stu-id="eb827-139">The name of the vault.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="eb827-140">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="eb827-140">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="eb827-141">Ruft die angegebene Azure-schlüsseltresor.</span><span class="sxs-lookup"><span data-stu-id="eb827-141">Gets the specified Azure key vault.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetDeleted">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.KeyVault.Models.DeletedVault GetDeleted (this Microsoft.Azure.Management.KeyVault.IVaultsOperations operations, string vaultName, string location);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.KeyVault.Models.DeletedVault GetDeleted(class Microsoft.Azure.Management.KeyVault.IVaultsOperations operations, string vaultName, string location) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.KeyVault.VaultsOperationsExtensions.GetDeleted(Microsoft.Azure.Management.KeyVault.IVaultsOperations,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function GetDeleted (operations As IVaultsOperations, vaultName As String, location As String) As DeletedVault" />
      <MemberSignature Language="F#" Value="static member GetDeleted : Microsoft.Azure.Management.KeyVault.IVaultsOperations * string * string -&gt; Microsoft.Azure.Management.KeyVault.Models.DeletedVault" Usage="Microsoft.Azure.Management.KeyVault.VaultsOperationsExtensions.GetDeleted (operations, vaultName, location)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.KeyVault.Models.DeletedVault</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.KeyVault.IVaultsOperations" RefType="this" />
        <Parameter Name="vaultName" Type="System.String" />
        <Parameter Name="location" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="eb827-142">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="eb827-142">The operations group for this extension method.</span></span>
            </param>
        <param name="vaultName">
            <span data-ttu-id="eb827-143">Der Name des Tresors.</span><span class="sxs-lookup"><span data-stu-id="eb827-143">The name of the vault.</span></span>
            </param>
        <param name="location">
            <span data-ttu-id="eb827-144">Der Speicherort des Tresors gelöscht.</span><span class="sxs-lookup"><span data-stu-id="eb827-144">The location of the deleted vault.</span></span>
            </param>
        <summary>
            <span data-ttu-id="eb827-145">Ruft die gelöschten Azure Key Vault.</span><span class="sxs-lookup"><span data-stu-id="eb827-145">Gets the deleted Azure key vault.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetDeletedAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.KeyVault.Models.DeletedVault&gt; GetDeletedAsync (this Microsoft.Azure.Management.KeyVault.IVaultsOperations operations, string vaultName, string location, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.KeyVault.Models.DeletedVault&gt; GetDeletedAsync(class Microsoft.Azure.Management.KeyVault.IVaultsOperations operations, string vaultName, string location, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.KeyVault.VaultsOperationsExtensions.GetDeletedAsync(Microsoft.Azure.Management.KeyVault.IVaultsOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetDeletedAsync : Microsoft.Azure.Management.KeyVault.IVaultsOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.KeyVault.Models.DeletedVault&gt;" Usage="Microsoft.Azure.Management.KeyVault.VaultsOperationsExtensions.GetDeletedAsync (operations, vaultName, location, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.KeyVault.VaultsOperationsExtensions/&lt;GetDeletedAsync&gt;d__11))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.KeyVault.Models.DeletedVault&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.KeyVault.IVaultsOperations" RefType="this" />
        <Parameter Name="vaultName" Type="System.String" />
        <Parameter Name="location" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="eb827-146">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="eb827-146">The operations group for this extension method.</span></span>
            </param>
        <param name="vaultName">
            <span data-ttu-id="eb827-147">Der Name des Tresors.</span><span class="sxs-lookup"><span data-stu-id="eb827-147">The name of the vault.</span></span>
            </param>
        <param name="location">
            <span data-ttu-id="eb827-148">Der Speicherort des Tresors gelöscht.</span><span class="sxs-lookup"><span data-stu-id="eb827-148">The location of the deleted vault.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="eb827-149">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="eb827-149">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="eb827-150">Ruft die gelöschten Azure Key Vault.</span><span class="sxs-lookup"><span data-stu-id="eb827-150">Gets the deleted Azure key vault.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="List">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.KeyVault.Models.Resource&gt; List (this Microsoft.Azure.Management.KeyVault.IVaultsOperations operations, Nullable&lt;int&gt; top = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.KeyVault.Models.Resource&gt; List(class Microsoft.Azure.Management.KeyVault.IVaultsOperations operations, valuetype System.Nullable`1&lt;int32&gt; top) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.KeyVault.VaultsOperationsExtensions.List(Microsoft.Azure.Management.KeyVault.IVaultsOperations,System.Nullable{System.Int32})" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function List (operations As IVaultsOperations, Optional top As Nullable(Of Integer) = null) As IPage(Of Resource)" />
      <MemberSignature Language="F#" Value="static member List : Microsoft.Azure.Management.KeyVault.IVaultsOperations * Nullable&lt;int&gt; -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.KeyVault.Models.Resource&gt;" Usage="Microsoft.Azure.Management.KeyVault.VaultsOperationsExtensions.List (operations, top)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.KeyVault.Models.Resource&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.KeyVault.IVaultsOperations" RefType="this" />
        <Parameter Name="top" Type="System.Nullable&lt;System.Int32&gt;" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="eb827-151">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="eb827-151">The operations group for this extension method.</span></span>
            </param>
        <param name="top">
            <span data-ttu-id="eb827-152">Maximale Anzahl der zurückzugebenden Ergebnisseite.</span><span class="sxs-lookup"><span data-stu-id="eb827-152">Maximum number of results to return.</span></span>
            </param>
        <summary>
            <span data-ttu-id="eb827-153">Der List-Vorgang ruft Informationen zu den Tresoren, die dem Abonnement zugeordnet.</span><span class="sxs-lookup"><span data-stu-id="eb827-153">The List operation gets information about the vaults associated with the subscription.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.KeyVault.Models.Resource&gt;&gt; ListAsync (this Microsoft.Azure.Management.KeyVault.IVaultsOperations operations, Nullable&lt;int&gt; top = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.KeyVault.Models.Resource&gt;&gt; ListAsync(class Microsoft.Azure.Management.KeyVault.IVaultsOperations operations, valuetype System.Nullable`1&lt;int32&gt; top, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.KeyVault.VaultsOperationsExtensions.ListAsync(Microsoft.Azure.Management.KeyVault.IVaultsOperations,System.Nullable{System.Int32},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListAsync : Microsoft.Azure.Management.KeyVault.IVaultsOperations * Nullable&lt;int&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.KeyVault.Models.Resource&gt;&gt;" Usage="Microsoft.Azure.Management.KeyVault.VaultsOperationsExtensions.ListAsync (operations, top, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.KeyVault.VaultsOperationsExtensions/&lt;ListAsync&gt;d__17))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.KeyVault.Models.Resource&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.KeyVault.IVaultsOperations" RefType="this" />
        <Parameter Name="top" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="eb827-154">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="eb827-154">The operations group for this extension method.</span></span>
            </param>
        <param name="top">
            <span data-ttu-id="eb827-155">Maximale Anzahl der zurückzugebenden Ergebnisseite.</span><span class="sxs-lookup"><span data-stu-id="eb827-155">Maximum number of results to return.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="eb827-156">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="eb827-156">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="eb827-157">Der List-Vorgang ruft Informationen zu den Tresoren, die dem Abonnement zugeordnet.</span><span class="sxs-lookup"><span data-stu-id="eb827-157">The List operation gets information about the vaults associated with the subscription.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByResourceGroup">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.KeyVault.Models.Vault&gt; ListByResourceGroup (this Microsoft.Azure.Management.KeyVault.IVaultsOperations operations, string resourceGroupName, Nullable&lt;int&gt; top = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.KeyVault.Models.Vault&gt; ListByResourceGroup(class Microsoft.Azure.Management.KeyVault.IVaultsOperations operations, string resourceGroupName, valuetype System.Nullable`1&lt;int32&gt; top) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.KeyVault.VaultsOperationsExtensions.ListByResourceGroup(Microsoft.Azure.Management.KeyVault.IVaultsOperations,System.String,System.Nullable{System.Int32})" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListByResourceGroup (operations As IVaultsOperations, resourceGroupName As String, Optional top As Nullable(Of Integer) = null) As IPage(Of Vault)" />
      <MemberSignature Language="F#" Value="static member ListByResourceGroup : Microsoft.Azure.Management.KeyVault.IVaultsOperations * string * Nullable&lt;int&gt; -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.KeyVault.Models.Vault&gt;" Usage="Microsoft.Azure.Management.KeyVault.VaultsOperationsExtensions.ListByResourceGroup (operations, resourceGroupName, top)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.KeyVault.Models.Vault&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.KeyVault.IVaultsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="top" Type="System.Nullable&lt;System.Int32&gt;" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="eb827-158">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="eb827-158">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="eb827-159">Der Name der Ressourcengruppe, zu dem Tresor gehört.</span><span class="sxs-lookup"><span data-stu-id="eb827-159">The name of the Resource Group to which the vault belongs.</span></span>
            </param>
        <param name="top">
            <span data-ttu-id="eb827-160">Maximale Anzahl der zurückzugebenden Ergebnisseite.</span><span class="sxs-lookup"><span data-stu-id="eb827-160">Maximum number of results to return.</span></span>
            </param>
        <summary>
            <span data-ttu-id="eb827-161">Der List-Vorgang ruft Informationen zu den Tresoren verknüpft sind, mit dem Abonnement und in der angegebenen Ressourcengruppe ab.</span><span class="sxs-lookup"><span data-stu-id="eb827-161">The List operation gets information about the vaults associated with the subscription and within the specified resource group.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByResourceGroupAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.KeyVault.Models.Vault&gt;&gt; ListByResourceGroupAsync (this Microsoft.Azure.Management.KeyVault.IVaultsOperations operations, string resourceGroupName, Nullable&lt;int&gt; top = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.KeyVault.Models.Vault&gt;&gt; ListByResourceGroupAsync(class Microsoft.Azure.Management.KeyVault.IVaultsOperations operations, string resourceGroupName, valuetype System.Nullable`1&lt;int32&gt; top, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.KeyVault.VaultsOperationsExtensions.ListByResourceGroupAsync(Microsoft.Azure.Management.KeyVault.IVaultsOperations,System.String,System.Nullable{System.Int32},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListByResourceGroupAsync : Microsoft.Azure.Management.KeyVault.IVaultsOperations * string * Nullable&lt;int&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.KeyVault.Models.Vault&gt;&gt;" Usage="Microsoft.Azure.Management.KeyVault.VaultsOperationsExtensions.ListByResourceGroupAsync (operations, resourceGroupName, top, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.KeyVault.VaultsOperationsExtensions/&lt;ListByResourceGroupAsync&gt;d__7))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.KeyVault.Models.Vault&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.KeyVault.IVaultsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="top" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="eb827-162">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="eb827-162">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="eb827-163">Der Name der Ressourcengruppe, zu dem Tresor gehört.</span><span class="sxs-lookup"><span data-stu-id="eb827-163">The name of the Resource Group to which the vault belongs.</span></span>
            </param>
        <param name="top">
            <span data-ttu-id="eb827-164">Maximale Anzahl der zurückzugebenden Ergebnisseite.</span><span class="sxs-lookup"><span data-stu-id="eb827-164">Maximum number of results to return.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="eb827-165">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="eb827-165">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="eb827-166">Der List-Vorgang ruft Informationen zu den Tresoren verknüpft sind, mit dem Abonnement und in der angegebenen Ressourcengruppe ab.</span><span class="sxs-lookup"><span data-stu-id="eb827-166">The List operation gets information about the vaults associated with the subscription and within the specified resource group.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByResourceGroupNext">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.KeyVault.Models.Vault&gt; ListByResourceGroupNext (this Microsoft.Azure.Management.KeyVault.IVaultsOperations operations, string nextPageLink);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.KeyVault.Models.Vault&gt; ListByResourceGroupNext(class Microsoft.Azure.Management.KeyVault.IVaultsOperations operations, string nextPageLink) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.KeyVault.VaultsOperationsExtensions.ListByResourceGroupNext(Microsoft.Azure.Management.KeyVault.IVaultsOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListByResourceGroupNext (operations As IVaultsOperations, nextPageLink As String) As IPage(Of Vault)" />
      <MemberSignature Language="F#" Value="static member ListByResourceGroupNext : Microsoft.Azure.Management.KeyVault.IVaultsOperations * string -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.KeyVault.Models.Vault&gt;" Usage="Microsoft.Azure.Management.KeyVault.VaultsOperationsExtensions.ListByResourceGroupNext (operations, nextPageLink)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.KeyVault.Models.Vault&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.KeyVault.IVaultsOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="eb827-167">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="eb827-167">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="eb827-168">Die "NextLink" aus dem vorherigen erfolgreichen Aufruf List-Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="eb827-168">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <summary>
            <span data-ttu-id="eb827-169">Der List-Vorgang ruft Informationen zu den Tresoren verknüpft sind, mit dem Abonnement und in der angegebenen Ressourcengruppe ab.</span><span class="sxs-lookup"><span data-stu-id="eb827-169">The List operation gets information about the vaults associated with the subscription and within the specified resource group.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByResourceGroupNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.KeyVault.Models.Vault&gt;&gt; ListByResourceGroupNextAsync (this Microsoft.Azure.Management.KeyVault.IVaultsOperations operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.KeyVault.Models.Vault&gt;&gt; ListByResourceGroupNextAsync(class Microsoft.Azure.Management.KeyVault.IVaultsOperations operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.KeyVault.VaultsOperationsExtensions.ListByResourceGroupNextAsync(Microsoft.Azure.Management.KeyVault.IVaultsOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListByResourceGroupNextAsync : Microsoft.Azure.Management.KeyVault.IVaultsOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.KeyVault.Models.Vault&gt;&gt;" Usage="Microsoft.Azure.Management.KeyVault.VaultsOperationsExtensions.ListByResourceGroupNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.KeyVault.VaultsOperationsExtensions/&lt;ListByResourceGroupNextAsync&gt;d__19))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.KeyVault.Models.Vault&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.KeyVault.IVaultsOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="eb827-170">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="eb827-170">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="eb827-171">Die "NextLink" aus dem vorherigen erfolgreichen Aufruf List-Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="eb827-171">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="eb827-172">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="eb827-172">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="eb827-173">Der List-Vorgang ruft Informationen zu den Tresoren verknüpft sind, mit dem Abonnement und in der angegebenen Ressourcengruppe ab.</span><span class="sxs-lookup"><span data-stu-id="eb827-173">The List operation gets information about the vaults associated with the subscription and within the specified resource group.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListDeleted">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.KeyVault.Models.DeletedVault&gt; ListDeleted (this Microsoft.Azure.Management.KeyVault.IVaultsOperations operations);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.KeyVault.Models.DeletedVault&gt; ListDeleted(class Microsoft.Azure.Management.KeyVault.IVaultsOperations operations) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.KeyVault.VaultsOperationsExtensions.ListDeleted(Microsoft.Azure.Management.KeyVault.IVaultsOperations)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListDeleted (operations As IVaultsOperations) As IPage(Of DeletedVault)" />
      <MemberSignature Language="F#" Value="static member ListDeleted : Microsoft.Azure.Management.KeyVault.IVaultsOperations -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.KeyVault.Models.DeletedVault&gt;" Usage="Microsoft.Azure.Management.KeyVault.VaultsOperationsExtensions.ListDeleted operations" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.KeyVault.Models.DeletedVault&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.KeyVault.IVaultsOperations" RefType="this" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="eb827-174">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="eb827-174">The operations group for this extension method.</span></span>
            </param>
        <summary>
            <span data-ttu-id="eb827-175">Ruft Informationen zu den gelöschten Depots in einem Abonnement ab.</span><span class="sxs-lookup"><span data-stu-id="eb827-175">Gets information about the deleted vaults in a subscription.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListDeletedAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.KeyVault.Models.DeletedVault&gt;&gt; ListDeletedAsync (this Microsoft.Azure.Management.KeyVault.IVaultsOperations operations, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.KeyVault.Models.DeletedVault&gt;&gt; ListDeletedAsync(class Microsoft.Azure.Management.KeyVault.IVaultsOperations operations, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.KeyVault.VaultsOperationsExtensions.ListDeletedAsync(Microsoft.Azure.Management.KeyVault.IVaultsOperations,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListDeletedAsync : Microsoft.Azure.Management.KeyVault.IVaultsOperations * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.KeyVault.Models.DeletedVault&gt;&gt;" Usage="Microsoft.Azure.Management.KeyVault.VaultsOperationsExtensions.ListDeletedAsync (operations, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.KeyVault.VaultsOperationsExtensions/&lt;ListDeletedAsync&gt;d__9))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.KeyVault.Models.DeletedVault&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.KeyVault.IVaultsOperations" RefType="this" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="eb827-176">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="eb827-176">The operations group for this extension method.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="eb827-177">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="eb827-177">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="eb827-178">Ruft Informationen zu den gelöschten Depots in einem Abonnement ab.</span><span class="sxs-lookup"><span data-stu-id="eb827-178">Gets information about the deleted vaults in a subscription.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListDeletedNext">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.KeyVault.Models.DeletedVault&gt; ListDeletedNext (this Microsoft.Azure.Management.KeyVault.IVaultsOperations operations, string nextPageLink);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.KeyVault.Models.DeletedVault&gt; ListDeletedNext(class Microsoft.Azure.Management.KeyVault.IVaultsOperations operations, string nextPageLink) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.KeyVault.VaultsOperationsExtensions.ListDeletedNext(Microsoft.Azure.Management.KeyVault.IVaultsOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListDeletedNext (operations As IVaultsOperations, nextPageLink As String) As IPage(Of DeletedVault)" />
      <MemberSignature Language="F#" Value="static member ListDeletedNext : Microsoft.Azure.Management.KeyVault.IVaultsOperations * string -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.KeyVault.Models.DeletedVault&gt;" Usage="Microsoft.Azure.Management.KeyVault.VaultsOperationsExtensions.ListDeletedNext (operations, nextPageLink)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.KeyVault.Models.DeletedVault&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.KeyVault.IVaultsOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="eb827-179">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="eb827-179">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="eb827-180">Die "NextLink" aus dem vorherigen erfolgreichen Aufruf List-Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="eb827-180">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <summary>
            <span data-ttu-id="eb827-181">Ruft Informationen zu den gelöschten Depots in einem Abonnement ab.</span><span class="sxs-lookup"><span data-stu-id="eb827-181">Gets information about the deleted vaults in a subscription.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListDeletedNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.KeyVault.Models.DeletedVault&gt;&gt; ListDeletedNextAsync (this Microsoft.Azure.Management.KeyVault.IVaultsOperations operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.KeyVault.Models.DeletedVault&gt;&gt; ListDeletedNextAsync(class Microsoft.Azure.Management.KeyVault.IVaultsOperations operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.KeyVault.VaultsOperationsExtensions.ListDeletedNextAsync(Microsoft.Azure.Management.KeyVault.IVaultsOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListDeletedNextAsync : Microsoft.Azure.Management.KeyVault.IVaultsOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.KeyVault.Models.DeletedVault&gt;&gt;" Usage="Microsoft.Azure.Management.KeyVault.VaultsOperationsExtensions.ListDeletedNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.KeyVault.VaultsOperationsExtensions/&lt;ListDeletedNextAsync&gt;d__21))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.KeyVault.Models.DeletedVault&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.KeyVault.IVaultsOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="eb827-182">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="eb827-182">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="eb827-183">Die "NextLink" aus dem vorherigen erfolgreichen Aufruf List-Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="eb827-183">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="eb827-184">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="eb827-184">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="eb827-185">Ruft Informationen zu den gelöschten Depots in einem Abonnement ab.</span><span class="sxs-lookup"><span data-stu-id="eb827-185">Gets information about the deleted vaults in a subscription.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListNext">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.KeyVault.Models.Resource&gt; ListNext (this Microsoft.Azure.Management.KeyVault.IVaultsOperations operations, string nextPageLink);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.KeyVault.Models.Resource&gt; ListNext(class Microsoft.Azure.Management.KeyVault.IVaultsOperations operations, string nextPageLink) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.KeyVault.VaultsOperationsExtensions.ListNext(Microsoft.Azure.Management.KeyVault.IVaultsOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListNext (operations As IVaultsOperations, nextPageLink As String) As IPage(Of Resource)" />
      <MemberSignature Language="F#" Value="static member ListNext : Microsoft.Azure.Management.KeyVault.IVaultsOperations * string -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.KeyVault.Models.Resource&gt;" Usage="Microsoft.Azure.Management.KeyVault.VaultsOperationsExtensions.ListNext (operations, nextPageLink)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.KeyVault.Models.Resource&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.KeyVault.IVaultsOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="eb827-186">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="eb827-186">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="eb827-187">Die "NextLink" aus dem vorherigen erfolgreichen Aufruf List-Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="eb827-187">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <summary>
            <span data-ttu-id="eb827-188">Der List-Vorgang ruft Informationen zu den Tresoren, die dem Abonnement zugeordnet.</span><span class="sxs-lookup"><span data-stu-id="eb827-188">The List operation gets information about the vaults associated with the subscription.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.KeyVault.Models.Resource&gt;&gt; ListNextAsync (this Microsoft.Azure.Management.KeyVault.IVaultsOperations operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.KeyVault.Models.Resource&gt;&gt; ListNextAsync(class Microsoft.Azure.Management.KeyVault.IVaultsOperations operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.KeyVault.VaultsOperationsExtensions.ListNextAsync(Microsoft.Azure.Management.KeyVault.IVaultsOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListNextAsync : Microsoft.Azure.Management.KeyVault.IVaultsOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.KeyVault.Models.Resource&gt;&gt;" Usage="Microsoft.Azure.Management.KeyVault.VaultsOperationsExtensions.ListNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.KeyVault.VaultsOperationsExtensions/&lt;ListNextAsync&gt;d__23))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.KeyVault.Models.Resource&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.KeyVault.IVaultsOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="eb827-189">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="eb827-189">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="eb827-190">Die "NextLink" aus dem vorherigen erfolgreichen Aufruf List-Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="eb827-190">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="eb827-191">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="eb827-191">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="eb827-192">Der List-Vorgang ruft Informationen zu den Tresoren, die dem Abonnement zugeordnet.</span><span class="sxs-lookup"><span data-stu-id="eb827-192">The List operation gets information about the vaults associated with the subscription.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PurgeDeleted">
      <MemberSignature Language="C#" Value="public static void PurgeDeleted (this Microsoft.Azure.Management.KeyVault.IVaultsOperations operations, string vaultName, string location);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void PurgeDeleted(class Microsoft.Azure.Management.KeyVault.IVaultsOperations operations, string vaultName, string location) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.KeyVault.VaultsOperationsExtensions.PurgeDeleted(Microsoft.Azure.Management.KeyVault.IVaultsOperations,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Sub PurgeDeleted (operations As IVaultsOperations, vaultName As String, location As String)" />
      <MemberSignature Language="F#" Value="static member PurgeDeleted : Microsoft.Azure.Management.KeyVault.IVaultsOperations * string * string -&gt; unit" Usage="Microsoft.Azure.Management.KeyVault.VaultsOperationsExtensions.PurgeDeleted (operations, vaultName, location)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.KeyVault.IVaultsOperations" RefType="this" />
        <Parameter Name="vaultName" Type="System.String" />
        <Parameter Name="location" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="eb827-193">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="eb827-193">The operations group for this extension method.</span></span>
            </param>
        <param name="vaultName">
            <span data-ttu-id="eb827-194">Der Name des Tresors vorläufig gelöscht.</span><span class="sxs-lookup"><span data-stu-id="eb827-194">The name of the soft-deleted vault.</span></span>
            </param>
        <param name="location">
            <span data-ttu-id="eb827-195">Der Speicherort des Tresors vorläufig gelöscht.</span><span class="sxs-lookup"><span data-stu-id="eb827-195">The location of the soft-deleted vault.</span></span>
            </param>
        <summary>
            <span data-ttu-id="eb827-196">Dauerhaft löscht den angegebenen Tresor.</span><span class="sxs-lookup"><span data-stu-id="eb827-196">Permanently deletes the specified vault.</span></span> <span data-ttu-id="eb827-197">d. h. löscht gelöschte Azure Key Vault.</span><span class="sxs-lookup"><span data-stu-id="eb827-197">aka Purges the deleted Azure key vault.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PurgeDeletedAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task PurgeDeletedAsync (this Microsoft.Azure.Management.KeyVault.IVaultsOperations operations, string vaultName, string location, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task PurgeDeletedAsync(class Microsoft.Azure.Management.KeyVault.IVaultsOperations operations, string vaultName, string location, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.KeyVault.VaultsOperationsExtensions.PurgeDeletedAsync(Microsoft.Azure.Management.KeyVault.IVaultsOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member PurgeDeletedAsync : Microsoft.Azure.Management.KeyVault.IVaultsOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.KeyVault.VaultsOperationsExtensions.PurgeDeletedAsync (operations, vaultName, location, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.KeyVault.VaultsOperationsExtensions/&lt;PurgeDeletedAsync&gt;d__13))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.KeyVault.IVaultsOperations" RefType="this" />
        <Parameter Name="vaultName" Type="System.String" />
        <Parameter Name="location" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="eb827-198">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="eb827-198">The operations group for this extension method.</span></span>
            </param>
        <param name="vaultName">
            <span data-ttu-id="eb827-199">Der Name des Tresors vorläufig gelöscht.</span><span class="sxs-lookup"><span data-stu-id="eb827-199">The name of the soft-deleted vault.</span></span>
            </param>
        <param name="location">
            <span data-ttu-id="eb827-200">Der Speicherort des Tresors vorläufig gelöscht.</span><span class="sxs-lookup"><span data-stu-id="eb827-200">The location of the soft-deleted vault.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="eb827-201">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="eb827-201">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="eb827-202">Dauerhaft löscht den angegebenen Tresor.</span><span class="sxs-lookup"><span data-stu-id="eb827-202">Permanently deletes the specified vault.</span></span> <span data-ttu-id="eb827-203">d. h. löscht gelöschte Azure Key Vault.</span><span class="sxs-lookup"><span data-stu-id="eb827-203">aka Purges the deleted Azure key vault.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>