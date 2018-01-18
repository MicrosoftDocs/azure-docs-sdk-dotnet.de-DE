<Type Name="ProtectionPoliciesOperationsExtensions" FullName="Microsoft.Azure.Management.RecoveryServices.Backup.ProtectionPoliciesOperationsExtensions">
  <TypeSignature Language="C#" Value="public static class ProtectionPoliciesOperationsExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit ProtectionPoliciesOperationsExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.RecoveryServices.Backup.ProtectionPoliciesOperationsExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module ProtectionPoliciesOperationsExtensions" />
  <TypeSignature Language="F#" Value="type ProtectionPoliciesOperationsExtensions = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
    <AssemblyVersion>2.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="7b68f-101">Erweiterungsmethoden für ProtectionPoliciesOperations.</span><span class="sxs-lookup"><span data-stu-id="7b68f-101">Extension methods for ProtectionPoliciesOperations.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="CreateOrUpdate">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.RecoveryServices.Backup.Models.ProtectionPolicyResource CreateOrUpdate (this Microsoft.Azure.Management.RecoveryServices.Backup.IProtectionPoliciesOperations operations, string vaultName, string resourceGroupName, string policyName, Microsoft.Azure.Management.RecoveryServices.Backup.Models.ProtectionPolicyResource parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.RecoveryServices.Backup.Models.ProtectionPolicyResource CreateOrUpdate(class Microsoft.Azure.Management.RecoveryServices.Backup.IProtectionPoliciesOperations operations, string vaultName, string resourceGroupName, string policyName, class Microsoft.Azure.Management.RecoveryServices.Backup.Models.ProtectionPolicyResource parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.RecoveryServices.Backup.ProtectionPoliciesOperationsExtensions.CreateOrUpdate(Microsoft.Azure.Management.RecoveryServices.Backup.IProtectionPoliciesOperations,System.String,System.String,System.String,Microsoft.Azure.Management.RecoveryServices.Backup.Models.ProtectionPolicyResource)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function CreateOrUpdate (operations As IProtectionPoliciesOperations, vaultName As String, resourceGroupName As String, policyName As String, parameters As ProtectionPolicyResource) As ProtectionPolicyResource" />
      <MemberSignature Language="F#" Value="static member CreateOrUpdate : Microsoft.Azure.Management.RecoveryServices.Backup.IProtectionPoliciesOperations * string * string * string * Microsoft.Azure.Management.RecoveryServices.Backup.Models.ProtectionPolicyResource -&gt; Microsoft.Azure.Management.RecoveryServices.Backup.Models.ProtectionPolicyResource" Usage="Microsoft.Azure.Management.RecoveryServices.Backup.ProtectionPoliciesOperationsExtensions.CreateOrUpdate (operations, vaultName, resourceGroupName, policyName, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.RecoveryServices.Backup.Models.ProtectionPolicyResource</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.RecoveryServices.Backup.IProtectionPoliciesOperations" RefType="this" />
        <Parameter Name="vaultName" Type="System.String" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="policyName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.RecoveryServices.Backup.Models.ProtectionPolicyResource" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="7b68f-102">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="7b68f-102">The operations group for this extension method.</span></span>
            </param>
        <param name="vaultName">
            <span data-ttu-id="7b68f-103">Der Name des Recovery Services-Tresor.</span><span class="sxs-lookup"><span data-stu-id="7b68f-103">The name of the recovery services vault.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="7b68f-104">Der Name der Ressourcengruppe, in dem die Recovery-Tresor Services, ist vorhanden.</span><span class="sxs-lookup"><span data-stu-id="7b68f-104">The name of the resource group where the recovery services vault is present.</span></span>
            </param>
        <param name="policyName">
            <span data-ttu-id="7b68f-105">Die Sicherungsrichtlinie erstellt werden soll.</span><span class="sxs-lookup"><span data-stu-id="7b68f-105">Backup policy to be created.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="7b68f-106">Ressource Sicherungsrichtlinie</span><span class="sxs-lookup"><span data-stu-id="7b68f-106">resource backup policy</span></span>
            </param>
        <summary>
            <span data-ttu-id="7b68f-107">Erstellt oder ändert eine Sicherungsrichtlinie.</span><span class="sxs-lookup"><span data-stu-id="7b68f-107">Creates or modifies a backup policy.</span></span> <span data-ttu-id="7b68f-108">Das ist ein asynchroner Vorgang.</span><span class="sxs-lookup"><span data-stu-id="7b68f-108">This is an asynchronous operation.</span></span>
            <span data-ttu-id="7b68f-109">Status des Vorgangs kann mit GetPolicyOperationResult-API abgerufen werden.</span><span class="sxs-lookup"><span data-stu-id="7b68f-109">Status of the operation can be fetched using GetPolicyOperationResult API.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateOrUpdateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.RecoveryServices.Backup.Models.ProtectionPolicyResource&gt; CreateOrUpdateAsync (this Microsoft.Azure.Management.RecoveryServices.Backup.IProtectionPoliciesOperations operations, string vaultName, string resourceGroupName, string policyName, Microsoft.Azure.Management.RecoveryServices.Backup.Models.ProtectionPolicyResource parameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.RecoveryServices.Backup.Models.ProtectionPolicyResource&gt; CreateOrUpdateAsync(class Microsoft.Azure.Management.RecoveryServices.Backup.IProtectionPoliciesOperations operations, string vaultName, string resourceGroupName, string policyName, class Microsoft.Azure.Management.RecoveryServices.Backup.Models.ProtectionPolicyResource parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.RecoveryServices.Backup.ProtectionPoliciesOperationsExtensions.CreateOrUpdateAsync(Microsoft.Azure.Management.RecoveryServices.Backup.IProtectionPoliciesOperations,System.String,System.String,System.String,Microsoft.Azure.Management.RecoveryServices.Backup.Models.ProtectionPolicyResource,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member CreateOrUpdateAsync : Microsoft.Azure.Management.RecoveryServices.Backup.IProtectionPoliciesOperations * string * string * string * Microsoft.Azure.Management.RecoveryServices.Backup.Models.ProtectionPolicyResource * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.RecoveryServices.Backup.Models.ProtectionPolicyResource&gt;" Usage="Microsoft.Azure.Management.RecoveryServices.Backup.ProtectionPoliciesOperationsExtensions.CreateOrUpdateAsync (operations, vaultName, resourceGroupName, policyName, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.RecoveryServices.Backup.ProtectionPoliciesOperationsExtensions/&lt;CreateOrUpdateAsync&gt;d__3))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.RecoveryServices.Backup.Models.ProtectionPolicyResource&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.RecoveryServices.Backup.IProtectionPoliciesOperations" RefType="this" />
        <Parameter Name="vaultName" Type="System.String" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="policyName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.RecoveryServices.Backup.Models.ProtectionPolicyResource" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="7b68f-110">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="7b68f-110">The operations group for this extension method.</span></span>
            </param>
        <param name="vaultName">
            <span data-ttu-id="7b68f-111">Der Name des Recovery Services-Tresor.</span><span class="sxs-lookup"><span data-stu-id="7b68f-111">The name of the recovery services vault.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="7b68f-112">Der Name der Ressourcengruppe, in dem die Recovery-Tresor Services, ist vorhanden.</span><span class="sxs-lookup"><span data-stu-id="7b68f-112">The name of the resource group where the recovery services vault is present.</span></span>
            </param>
        <param name="policyName">
            <span data-ttu-id="7b68f-113">Die Sicherungsrichtlinie erstellt werden soll.</span><span class="sxs-lookup"><span data-stu-id="7b68f-113">Backup policy to be created.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="7b68f-114">Ressource Sicherungsrichtlinie</span><span class="sxs-lookup"><span data-stu-id="7b68f-114">resource backup policy</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="7b68f-115">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="7b68f-115">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="7b68f-116">Erstellt oder ändert eine Sicherungsrichtlinie.</span><span class="sxs-lookup"><span data-stu-id="7b68f-116">Creates or modifies a backup policy.</span></span> <span data-ttu-id="7b68f-117">Das ist ein asynchroner Vorgang.</span><span class="sxs-lookup"><span data-stu-id="7b68f-117">This is an asynchronous operation.</span></span>
            <span data-ttu-id="7b68f-118">Status des Vorgangs kann mit GetPolicyOperationResult-API abgerufen werden.</span><span class="sxs-lookup"><span data-stu-id="7b68f-118">Status of the operation can be fetched using GetPolicyOperationResult API.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Delete">
      <MemberSignature Language="C#" Value="public static void Delete (this Microsoft.Azure.Management.RecoveryServices.Backup.IProtectionPoliciesOperations operations, string vaultName, string resourceGroupName, string policyName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void Delete(class Microsoft.Azure.Management.RecoveryServices.Backup.IProtectionPoliciesOperations operations, string vaultName, string resourceGroupName, string policyName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.RecoveryServices.Backup.ProtectionPoliciesOperationsExtensions.Delete(Microsoft.Azure.Management.RecoveryServices.Backup.IProtectionPoliciesOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Sub Delete (operations As IProtectionPoliciesOperations, vaultName As String, resourceGroupName As String, policyName As String)" />
      <MemberSignature Language="F#" Value="static member Delete : Microsoft.Azure.Management.RecoveryServices.Backup.IProtectionPoliciesOperations * string * string * string -&gt; unit" Usage="Microsoft.Azure.Management.RecoveryServices.Backup.ProtectionPoliciesOperationsExtensions.Delete (operations, vaultName, resourceGroupName, policyName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.RecoveryServices.Backup.IProtectionPoliciesOperations" RefType="this" />
        <Parameter Name="vaultName" Type="System.String" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="policyName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="7b68f-119">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="7b68f-119">The operations group for this extension method.</span></span>
            </param>
        <param name="vaultName">
            <span data-ttu-id="7b68f-120">Der Name des Recovery Services-Tresor.</span><span class="sxs-lookup"><span data-stu-id="7b68f-120">The name of the recovery services vault.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="7b68f-121">Der Name der Ressourcengruppe, in dem die Recovery-Tresor Services, ist vorhanden.</span><span class="sxs-lookup"><span data-stu-id="7b68f-121">The name of the resource group where the recovery services vault is present.</span></span>
            </param>
        <param name="policyName">
            <span data-ttu-id="7b68f-122">Die Sicherungsrichtlinie gelöscht werden soll.</span><span class="sxs-lookup"><span data-stu-id="7b68f-122">Backup policy to be deleted.</span></span>
            </param>
        <summary>
            <span data-ttu-id="7b68f-123">Löscht den angegebenen Sicherungsrichtlinie aus Ihrer Recovery Services-Tresor.</span><span class="sxs-lookup"><span data-stu-id="7b68f-123">Deletes specified backup policy from your Recovery Services Vault.</span></span> <span data-ttu-id="7b68f-124">Das ist ein asynchroner Vorgang.</span><span class="sxs-lookup"><span data-stu-id="7b68f-124">This is an asynchronous operation.</span></span> <span data-ttu-id="7b68f-125">Status des Vorgangs kann mit GetPolicyOperationResult-API abgerufen werden.</span><span class="sxs-lookup"><span data-stu-id="7b68f-125">Status of the operation can be fetched using GetPolicyOperationResult API.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task DeleteAsync (this Microsoft.Azure.Management.RecoveryServices.Backup.IProtectionPoliciesOperations operations, string vaultName, string resourceGroupName, string policyName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task DeleteAsync(class Microsoft.Azure.Management.RecoveryServices.Backup.IProtectionPoliciesOperations operations, string vaultName, string resourceGroupName, string policyName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.RecoveryServices.Backup.ProtectionPoliciesOperationsExtensions.DeleteAsync(Microsoft.Azure.Management.RecoveryServices.Backup.IProtectionPoliciesOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member DeleteAsync : Microsoft.Azure.Management.RecoveryServices.Backup.IProtectionPoliciesOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.RecoveryServices.Backup.ProtectionPoliciesOperationsExtensions.DeleteAsync (operations, vaultName, resourceGroupName, policyName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.RecoveryServices.Backup.ProtectionPoliciesOperationsExtensions/&lt;DeleteAsync&gt;d__5))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.RecoveryServices.Backup.IProtectionPoliciesOperations" RefType="this" />
        <Parameter Name="vaultName" Type="System.String" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="policyName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="7b68f-126">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="7b68f-126">The operations group for this extension method.</span></span>
            </param>
        <param name="vaultName">
            <span data-ttu-id="7b68f-127">Der Name des Recovery Services-Tresor.</span><span class="sxs-lookup"><span data-stu-id="7b68f-127">The name of the recovery services vault.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="7b68f-128">Der Name der Ressourcengruppe, in dem die Recovery-Tresor Services, ist vorhanden.</span><span class="sxs-lookup"><span data-stu-id="7b68f-128">The name of the resource group where the recovery services vault is present.</span></span>
            </param>
        <param name="policyName">
            <span data-ttu-id="7b68f-129">Die Sicherungsrichtlinie gelöscht werden soll.</span><span class="sxs-lookup"><span data-stu-id="7b68f-129">Backup policy to be deleted.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="7b68f-130">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="7b68f-130">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="7b68f-131">Löscht den angegebenen Sicherungsrichtlinie aus Ihrer Recovery Services-Tresor.</span><span class="sxs-lookup"><span data-stu-id="7b68f-131">Deletes specified backup policy from your Recovery Services Vault.</span></span> <span data-ttu-id="7b68f-132">Das ist ein asynchroner Vorgang.</span><span class="sxs-lookup"><span data-stu-id="7b68f-132">This is an asynchronous operation.</span></span> <span data-ttu-id="7b68f-133">Status des Vorgangs kann mit GetPolicyOperationResult-API abgerufen werden.</span><span class="sxs-lookup"><span data-stu-id="7b68f-133">Status of the operation can be fetched using GetPolicyOperationResult API.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Get">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.RecoveryServices.Backup.Models.ProtectionPolicyResource Get (this Microsoft.Azure.Management.RecoveryServices.Backup.IProtectionPoliciesOperations operations, string vaultName, string resourceGroupName, string policyName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.RecoveryServices.Backup.Models.ProtectionPolicyResource Get(class Microsoft.Azure.Management.RecoveryServices.Backup.IProtectionPoliciesOperations operations, string vaultName, string resourceGroupName, string policyName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.RecoveryServices.Backup.ProtectionPoliciesOperationsExtensions.Get(Microsoft.Azure.Management.RecoveryServices.Backup.IProtectionPoliciesOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function Get (operations As IProtectionPoliciesOperations, vaultName As String, resourceGroupName As String, policyName As String) As ProtectionPolicyResource" />
      <MemberSignature Language="F#" Value="static member Get : Microsoft.Azure.Management.RecoveryServices.Backup.IProtectionPoliciesOperations * string * string * string -&gt; Microsoft.Azure.Management.RecoveryServices.Backup.Models.ProtectionPolicyResource" Usage="Microsoft.Azure.Management.RecoveryServices.Backup.ProtectionPoliciesOperationsExtensions.Get (operations, vaultName, resourceGroupName, policyName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.RecoveryServices.Backup.Models.ProtectionPolicyResource</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.RecoveryServices.Backup.IProtectionPoliciesOperations" RefType="this" />
        <Parameter Name="vaultName" Type="System.String" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="policyName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="7b68f-134">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="7b68f-134">The operations group for this extension method.</span></span>
            </param>
        <param name="vaultName">
            <span data-ttu-id="7b68f-135">Der Name des Recovery Services-Tresor.</span><span class="sxs-lookup"><span data-stu-id="7b68f-135">The name of the recovery services vault.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="7b68f-136">Der Name der Ressourcengruppe, in dem die Recovery-Tresor Services, ist vorhanden.</span><span class="sxs-lookup"><span data-stu-id="7b68f-136">The name of the resource group where the recovery services vault is present.</span></span>
            </param>
        <param name="policyName">
            <span data-ttu-id="7b68f-137">Sicherungsrichtlinie Informationen abgerufen werden sollen.</span><span class="sxs-lookup"><span data-stu-id="7b68f-137">Backup policy information to be fetched.</span></span>
            </param>
        <summary>
            <span data-ttu-id="7b68f-138">Enthält die Details der Sicherungsrichtlinien, die Recovery Services-Tresor zugeordnet sind.</span><span class="sxs-lookup"><span data-stu-id="7b68f-138">Provides the details of the backup policies associated to Recovery Services Vault.</span></span> <span data-ttu-id="7b68f-139">Das ist ein asynchroner Vorgang.</span><span class="sxs-lookup"><span data-stu-id="7b68f-139">This is an asynchronous operation.</span></span> <span data-ttu-id="7b68f-140">Status des Vorgangs kann mit GetPolicyOperationResult-API abgerufen werden.</span><span class="sxs-lookup"><span data-stu-id="7b68f-140">Status of the operation can be fetched using GetPolicyOperationResult API.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.RecoveryServices.Backup.Models.ProtectionPolicyResource&gt; GetAsync (this Microsoft.Azure.Management.RecoveryServices.Backup.IProtectionPoliciesOperations operations, string vaultName, string resourceGroupName, string policyName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.RecoveryServices.Backup.Models.ProtectionPolicyResource&gt; GetAsync(class Microsoft.Azure.Management.RecoveryServices.Backup.IProtectionPoliciesOperations operations, string vaultName, string resourceGroupName, string policyName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.RecoveryServices.Backup.ProtectionPoliciesOperationsExtensions.GetAsync(Microsoft.Azure.Management.RecoveryServices.Backup.IProtectionPoliciesOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetAsync : Microsoft.Azure.Management.RecoveryServices.Backup.IProtectionPoliciesOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.RecoveryServices.Backup.Models.ProtectionPolicyResource&gt;" Usage="Microsoft.Azure.Management.RecoveryServices.Backup.ProtectionPoliciesOperationsExtensions.GetAsync (operations, vaultName, resourceGroupName, policyName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.RecoveryServices.Backup.ProtectionPoliciesOperationsExtensions/&lt;GetAsync&gt;d__1))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.RecoveryServices.Backup.Models.ProtectionPolicyResource&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.RecoveryServices.Backup.IProtectionPoliciesOperations" RefType="this" />
        <Parameter Name="vaultName" Type="System.String" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="policyName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="7b68f-141">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="7b68f-141">The operations group for this extension method.</span></span>
            </param>
        <param name="vaultName">
            <span data-ttu-id="7b68f-142">Der Name des Recovery Services-Tresor.</span><span class="sxs-lookup"><span data-stu-id="7b68f-142">The name of the recovery services vault.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="7b68f-143">Der Name der Ressourcengruppe, in dem die Recovery-Tresor Services, ist vorhanden.</span><span class="sxs-lookup"><span data-stu-id="7b68f-143">The name of the resource group where the recovery services vault is present.</span></span>
            </param>
        <param name="policyName">
            <span data-ttu-id="7b68f-144">Sicherungsrichtlinie Informationen abgerufen werden sollen.</span><span class="sxs-lookup"><span data-stu-id="7b68f-144">Backup policy information to be fetched.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="7b68f-145">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="7b68f-145">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="7b68f-146">Enthält die Details der Sicherungsrichtlinien, die Recovery Services-Tresor zugeordnet sind.</span><span class="sxs-lookup"><span data-stu-id="7b68f-146">Provides the details of the backup policies associated to Recovery Services Vault.</span></span> <span data-ttu-id="7b68f-147">Das ist ein asynchroner Vorgang.</span><span class="sxs-lookup"><span data-stu-id="7b68f-147">This is an asynchronous operation.</span></span> <span data-ttu-id="7b68f-148">Status des Vorgangs kann mit GetPolicyOperationResult-API abgerufen werden.</span><span class="sxs-lookup"><span data-stu-id="7b68f-148">Status of the operation can be fetched using GetPolicyOperationResult API.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>