<Type Name="VaultsOperationsExtensions" FullName="Microsoft.Azure.Management.RecoveryServices.VaultsOperationsExtensions">
  <TypeSignature Language="C#" Value="public static class VaultsOperationsExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit VaultsOperationsExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.RecoveryServices.VaultsOperationsExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module VaultsOperationsExtensions" />
  <TypeSignature Language="F#" Value="type VaultsOperationsExtensions = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.RecoveryServices</AssemblyName>
    <AssemblyVersion>4.2.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="efe5d-101">Erweiterungsmethoden für VaultsOperations.</span><span class="sxs-lookup"><span data-stu-id="efe5d-101">Extension methods for VaultsOperations.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="CreateOrUpdate">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.RecoveryServices.Models.Vault CreateOrUpdate (this Microsoft.Azure.Management.RecoveryServices.IVaultsOperations operations, string resourceGroupName, string vaultName, Microsoft.Azure.Management.RecoveryServices.Models.Vault vault);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.RecoveryServices.Models.Vault CreateOrUpdate(class Microsoft.Azure.Management.RecoveryServices.IVaultsOperations operations, string resourceGroupName, string vaultName, class Microsoft.Azure.Management.RecoveryServices.Models.Vault vault) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.RecoveryServices.VaultsOperationsExtensions.CreateOrUpdate(Microsoft.Azure.Management.RecoveryServices.IVaultsOperations,System.String,System.String,Microsoft.Azure.Management.RecoveryServices.Models.Vault)" />
      <MemberSignature Language="F#" Value="static member CreateOrUpdate : Microsoft.Azure.Management.RecoveryServices.IVaultsOperations * string * string * Microsoft.Azure.Management.RecoveryServices.Models.Vault -&gt; Microsoft.Azure.Management.RecoveryServices.Models.Vault" Usage="Microsoft.Azure.Management.RecoveryServices.VaultsOperationsExtensions.CreateOrUpdate (operations, resourceGroupName, vaultName, vault)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices</AssemblyName>
        <AssemblyVersion>4.2.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.RecoveryServices.Models.Vault</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.RecoveryServices.IVaultsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="vaultName" Type="System.String" />
        <Parameter Name="vault" Type="Microsoft.Azure.Management.RecoveryServices.Models.Vault" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="efe5d-102">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="efe5d-102">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="efe5d-103">Der Name der Ressourcengruppe, in dem die Recovery-Tresor Services, ist vorhanden.</span><span class="sxs-lookup"><span data-stu-id="efe5d-103">The name of the resource group where the recovery services vault is present.</span></span>
            </param>
        <param name="vaultName">
            <span data-ttu-id="efe5d-104">Der Name des Recovery Services-Tresor.</span><span class="sxs-lookup"><span data-stu-id="efe5d-104">The name of the recovery services vault.</span></span>
            </param>
        <param name="vault">
            <span data-ttu-id="efe5d-105">Recovery Services-Tresor erstellt werden soll.</span><span class="sxs-lookup"><span data-stu-id="efe5d-105">Recovery Services Vault to be created.</span></span>
            </param>
        <summary>
            <span data-ttu-id="efe5d-106">Erstellt oder aktualisiert einen wiederherstellungsdiensttresor.</span><span class="sxs-lookup"><span data-stu-id="efe5d-106">Creates or updates a Recovery Services vault.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateOrUpdateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.RecoveryServices.Models.Vault&gt; CreateOrUpdateAsync (this Microsoft.Azure.Management.RecoveryServices.IVaultsOperations operations, string resourceGroupName, string vaultName, Microsoft.Azure.Management.RecoveryServices.Models.Vault vault, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.RecoveryServices.Models.Vault&gt; CreateOrUpdateAsync(class Microsoft.Azure.Management.RecoveryServices.IVaultsOperations operations, string resourceGroupName, string vaultName, class Microsoft.Azure.Management.RecoveryServices.Models.Vault vault, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.RecoveryServices.VaultsOperationsExtensions.CreateOrUpdateAsync(Microsoft.Azure.Management.RecoveryServices.IVaultsOperations,System.String,System.String,Microsoft.Azure.Management.RecoveryServices.Models.Vault,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member CreateOrUpdateAsync : Microsoft.Azure.Management.RecoveryServices.IVaultsOperations * string * string * Microsoft.Azure.Management.RecoveryServices.Models.Vault * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.RecoveryServices.Models.Vault&gt;" Usage="Microsoft.Azure.Management.RecoveryServices.VaultsOperationsExtensions.CreateOrUpdateAsync (operations, resourceGroupName, vaultName, vault, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices</AssemblyName>
        <AssemblyVersion>4.2.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.RecoveryServices.VaultsOperationsExtensions/&lt;CreateOrUpdateAsync&gt;d__7))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.RecoveryServices.Models.Vault&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.RecoveryServices.IVaultsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="vaultName" Type="System.String" />
        <Parameter Name="vault" Type="Microsoft.Azure.Management.RecoveryServices.Models.Vault" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="efe5d-107">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="efe5d-107">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="efe5d-108">Der Name der Ressourcengruppe, in dem die Recovery-Tresor Services, ist vorhanden.</span><span class="sxs-lookup"><span data-stu-id="efe5d-108">The name of the resource group where the recovery services vault is present.</span></span>
            </param>
        <param name="vaultName">
            <span data-ttu-id="efe5d-109">Der Name des Recovery Services-Tresor.</span><span class="sxs-lookup"><span data-stu-id="efe5d-109">The name of the recovery services vault.</span></span>
            </param>
        <param name="vault">
            <span data-ttu-id="efe5d-110">Recovery Services-Tresor erstellt werden soll.</span><span class="sxs-lookup"><span data-stu-id="efe5d-110">Recovery Services Vault to be created.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="efe5d-111">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="efe5d-111">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="efe5d-112">Erstellt oder aktualisiert einen wiederherstellungsdiensttresor.</span><span class="sxs-lookup"><span data-stu-id="efe5d-112">Creates or updates a Recovery Services vault.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Delete">
      <MemberSignature Language="C#" Value="public static void Delete (this Microsoft.Azure.Management.RecoveryServices.IVaultsOperations operations, string resourceGroupName, string vaultName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void Delete(class Microsoft.Azure.Management.RecoveryServices.IVaultsOperations operations, string resourceGroupName, string vaultName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.RecoveryServices.VaultsOperationsExtensions.Delete(Microsoft.Azure.Management.RecoveryServices.IVaultsOperations,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Sub Delete (operations As IVaultsOperations, resourceGroupName As String, vaultName As String)" />
      <MemberSignature Language="F#" Value="static member Delete : Microsoft.Azure.Management.RecoveryServices.IVaultsOperations * string * string -&gt; unit" Usage="Microsoft.Azure.Management.RecoveryServices.VaultsOperationsExtensions.Delete (operations, resourceGroupName, vaultName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices</AssemblyName>
        <AssemblyVersion>4.2.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.RecoveryServices.IVaultsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="vaultName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="efe5d-113">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="efe5d-113">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="efe5d-114">Der Name der Ressourcengruppe, in dem die Recovery-Tresor Services, ist vorhanden.</span><span class="sxs-lookup"><span data-stu-id="efe5d-114">The name of the resource group where the recovery services vault is present.</span></span>
            </param>
        <param name="vaultName">
            <span data-ttu-id="efe5d-115">Der Name des Recovery Services-Tresor.</span><span class="sxs-lookup"><span data-stu-id="efe5d-115">The name of the recovery services vault.</span></span>
            </param>
        <summary>
            <span data-ttu-id="efe5d-116">Löscht einen Tresor.</span><span class="sxs-lookup"><span data-stu-id="efe5d-116">Deletes a vault.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task DeleteAsync (this Microsoft.Azure.Management.RecoveryServices.IVaultsOperations operations, string resourceGroupName, string vaultName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task DeleteAsync(class Microsoft.Azure.Management.RecoveryServices.IVaultsOperations operations, string resourceGroupName, string vaultName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.RecoveryServices.VaultsOperationsExtensions.DeleteAsync(Microsoft.Azure.Management.RecoveryServices.IVaultsOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member DeleteAsync : Microsoft.Azure.Management.RecoveryServices.IVaultsOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.RecoveryServices.VaultsOperationsExtensions.DeleteAsync (operations, resourceGroupName, vaultName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices</AssemblyName>
        <AssemblyVersion>4.2.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.RecoveryServices.VaultsOperationsExtensions/&lt;DeleteAsync&gt;d__9))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.RecoveryServices.IVaultsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="vaultName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="efe5d-117">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="efe5d-117">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="efe5d-118">Der Name der Ressourcengruppe, in dem die Recovery-Tresor Services, ist vorhanden.</span><span class="sxs-lookup"><span data-stu-id="efe5d-118">The name of the resource group where the recovery services vault is present.</span></span>
            </param>
        <param name="vaultName">
            <span data-ttu-id="efe5d-119">Der Name des Recovery Services-Tresor.</span><span class="sxs-lookup"><span data-stu-id="efe5d-119">The name of the recovery services vault.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="efe5d-120">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="efe5d-120">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="efe5d-121">Löscht einen Tresor.</span><span class="sxs-lookup"><span data-stu-id="efe5d-121">Deletes a vault.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Get">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.RecoveryServices.Models.Vault Get (this Microsoft.Azure.Management.RecoveryServices.IVaultsOperations operations, string resourceGroupName, string vaultName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.RecoveryServices.Models.Vault Get(class Microsoft.Azure.Management.RecoveryServices.IVaultsOperations operations, string resourceGroupName, string vaultName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.RecoveryServices.VaultsOperationsExtensions.Get(Microsoft.Azure.Management.RecoveryServices.IVaultsOperations,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function Get (operations As IVaultsOperations, resourceGroupName As String, vaultName As String) As Vault" />
      <MemberSignature Language="F#" Value="static member Get : Microsoft.Azure.Management.RecoveryServices.IVaultsOperations * string * string -&gt; Microsoft.Azure.Management.RecoveryServices.Models.Vault" Usage="Microsoft.Azure.Management.RecoveryServices.VaultsOperationsExtensions.Get (operations, resourceGroupName, vaultName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices</AssemblyName>
        <AssemblyVersion>4.2.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.RecoveryServices.Models.Vault</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.RecoveryServices.IVaultsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="vaultName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="efe5d-122">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="efe5d-122">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="efe5d-123">Der Name der Ressourcengruppe, in dem die Recovery-Tresor Services, ist vorhanden.</span><span class="sxs-lookup"><span data-stu-id="efe5d-123">The name of the resource group where the recovery services vault is present.</span></span>
            </param>
        <param name="vaultName">
            <span data-ttu-id="efe5d-124">Der Name des Recovery Services-Tresor.</span><span class="sxs-lookup"><span data-stu-id="efe5d-124">The name of the recovery services vault.</span></span>
            </param>
        <summary>
            <span data-ttu-id="efe5d-125">Ermitteln Sie die Vault-Details.</span><span class="sxs-lookup"><span data-stu-id="efe5d-125">Get the Vault details.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.RecoveryServices.Models.Vault&gt; GetAsync (this Microsoft.Azure.Management.RecoveryServices.IVaultsOperations operations, string resourceGroupName, string vaultName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.RecoveryServices.Models.Vault&gt; GetAsync(class Microsoft.Azure.Management.RecoveryServices.IVaultsOperations operations, string resourceGroupName, string vaultName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.RecoveryServices.VaultsOperationsExtensions.GetAsync(Microsoft.Azure.Management.RecoveryServices.IVaultsOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetAsync : Microsoft.Azure.Management.RecoveryServices.IVaultsOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.RecoveryServices.Models.Vault&gt;" Usage="Microsoft.Azure.Management.RecoveryServices.VaultsOperationsExtensions.GetAsync (operations, resourceGroupName, vaultName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices</AssemblyName>
        <AssemblyVersion>4.2.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.RecoveryServices.VaultsOperationsExtensions/&lt;GetAsync&gt;d__5))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.RecoveryServices.Models.Vault&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.RecoveryServices.IVaultsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="vaultName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="efe5d-126">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="efe5d-126">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="efe5d-127">Der Name der Ressourcengruppe, in dem die Recovery-Tresor Services, ist vorhanden.</span><span class="sxs-lookup"><span data-stu-id="efe5d-127">The name of the resource group where the recovery services vault is present.</span></span>
            </param>
        <param name="vaultName">
            <span data-ttu-id="efe5d-128">Der Name des Recovery Services-Tresor.</span><span class="sxs-lookup"><span data-stu-id="efe5d-128">The name of the recovery services vault.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="efe5d-129">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="efe5d-129">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="efe5d-130">Ermitteln Sie die Vault-Details.</span><span class="sxs-lookup"><span data-stu-id="efe5d-130">Get the Vault details.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByResourceGroup">
      <MemberSignature Language="C#" Value="public static System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.RecoveryServices.Models.Vault&gt; ListByResourceGroup (this Microsoft.Azure.Management.RecoveryServices.IVaultsOperations operations, string resourceGroupName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Management.RecoveryServices.Models.Vault&gt; ListByResourceGroup(class Microsoft.Azure.Management.RecoveryServices.IVaultsOperations operations, string resourceGroupName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.RecoveryServices.VaultsOperationsExtensions.ListByResourceGroup(Microsoft.Azure.Management.RecoveryServices.IVaultsOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListByResourceGroup (operations As IVaultsOperations, resourceGroupName As String) As IEnumerable(Of Vault)" />
      <MemberSignature Language="F#" Value="static member ListByResourceGroup : Microsoft.Azure.Management.RecoveryServices.IVaultsOperations * string -&gt; seq&lt;Microsoft.Azure.Management.RecoveryServices.Models.Vault&gt;" Usage="Microsoft.Azure.Management.RecoveryServices.VaultsOperationsExtensions.ListByResourceGroup (operations, resourceGroupName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices</AssemblyName>
        <AssemblyVersion>4.2.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.RecoveryServices.Models.Vault&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.RecoveryServices.IVaultsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="efe5d-131">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="efe5d-131">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="efe5d-132">Der Name der Ressourcengruppe, in dem die Recovery-Tresor Services, ist vorhanden.</span><span class="sxs-lookup"><span data-stu-id="efe5d-132">The name of the resource group where the recovery services vault is present.</span></span>
            </param>
        <summary>
            <span data-ttu-id="efe5d-133">Rufen Sie eine Liste der Tresore.</span><span class="sxs-lookup"><span data-stu-id="efe5d-133">Retrieve a list of Vaults.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByResourceGroupAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.RecoveryServices.Models.Vault&gt;&gt; ListByResourceGroupAsync (this Microsoft.Azure.Management.RecoveryServices.IVaultsOperations operations, string resourceGroupName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Management.RecoveryServices.Models.Vault&gt;&gt; ListByResourceGroupAsync(class Microsoft.Azure.Management.RecoveryServices.IVaultsOperations operations, string resourceGroupName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.RecoveryServices.VaultsOperationsExtensions.ListByResourceGroupAsync(Microsoft.Azure.Management.RecoveryServices.IVaultsOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListByResourceGroupAsync : Microsoft.Azure.Management.RecoveryServices.IVaultsOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;seq&lt;Microsoft.Azure.Management.RecoveryServices.Models.Vault&gt;&gt;" Usage="Microsoft.Azure.Management.RecoveryServices.VaultsOperationsExtensions.ListByResourceGroupAsync (operations, resourceGroupName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices</AssemblyName>
        <AssemblyVersion>4.2.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.RecoveryServices.VaultsOperationsExtensions/&lt;ListByResourceGroupAsync&gt;d__3))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.RecoveryServices.Models.Vault&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.RecoveryServices.IVaultsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="efe5d-134">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="efe5d-134">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="efe5d-135">Der Name der Ressourcengruppe, in dem die Recovery-Tresor Services, ist vorhanden.</span><span class="sxs-lookup"><span data-stu-id="efe5d-135">The name of the resource group where the recovery services vault is present.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="efe5d-136">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="efe5d-136">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="efe5d-137">Rufen Sie eine Liste der Tresore.</span><span class="sxs-lookup"><span data-stu-id="efe5d-137">Retrieve a list of Vaults.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListBySubscriptionId">
      <MemberSignature Language="C#" Value="public static System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.RecoveryServices.Models.Vault&gt; ListBySubscriptionId (this Microsoft.Azure.Management.RecoveryServices.IVaultsOperations operations);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Management.RecoveryServices.Models.Vault&gt; ListBySubscriptionId(class Microsoft.Azure.Management.RecoveryServices.IVaultsOperations operations) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.RecoveryServices.VaultsOperationsExtensions.ListBySubscriptionId(Microsoft.Azure.Management.RecoveryServices.IVaultsOperations)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListBySubscriptionId (operations As IVaultsOperations) As IEnumerable(Of Vault)" />
      <MemberSignature Language="F#" Value="static member ListBySubscriptionId : Microsoft.Azure.Management.RecoveryServices.IVaultsOperations -&gt; seq&lt;Microsoft.Azure.Management.RecoveryServices.Models.Vault&gt;" Usage="Microsoft.Azure.Management.RecoveryServices.VaultsOperationsExtensions.ListBySubscriptionId operations" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices</AssemblyName>
        <AssemblyVersion>4.2.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.RecoveryServices.Models.Vault&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.RecoveryServices.IVaultsOperations" RefType="this" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="efe5d-138">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="efe5d-138">The operations group for this extension method.</span></span>
            </param>
        <summary>
            <span data-ttu-id="efe5d-139">Ruft alle Ressourcen im Abonnement angegebenen Typs ab.</span><span class="sxs-lookup"><span data-stu-id="efe5d-139">Fetches all the resources of the specified type in the subscription.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListBySubscriptionIdAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.RecoveryServices.Models.Vault&gt;&gt; ListBySubscriptionIdAsync (this Microsoft.Azure.Management.RecoveryServices.IVaultsOperations operations, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Management.RecoveryServices.Models.Vault&gt;&gt; ListBySubscriptionIdAsync(class Microsoft.Azure.Management.RecoveryServices.IVaultsOperations operations, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.RecoveryServices.VaultsOperationsExtensions.ListBySubscriptionIdAsync(Microsoft.Azure.Management.RecoveryServices.IVaultsOperations,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListBySubscriptionIdAsync : Microsoft.Azure.Management.RecoveryServices.IVaultsOperations * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;seq&lt;Microsoft.Azure.Management.RecoveryServices.Models.Vault&gt;&gt;" Usage="Microsoft.Azure.Management.RecoveryServices.VaultsOperationsExtensions.ListBySubscriptionIdAsync (operations, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices</AssemblyName>
        <AssemblyVersion>4.2.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.RecoveryServices.VaultsOperationsExtensions/&lt;ListBySubscriptionIdAsync&gt;d__1))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.RecoveryServices.Models.Vault&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.RecoveryServices.IVaultsOperations" RefType="this" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="efe5d-140">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="efe5d-140">The operations group for this extension method.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="efe5d-141">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="efe5d-141">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="efe5d-142">Ruft alle Ressourcen im Abonnement angegebenen Typs ab.</span><span class="sxs-lookup"><span data-stu-id="efe5d-142">Fetches all the resources of the specified type in the subscription.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Update">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.RecoveryServices.Models.Vault Update (this Microsoft.Azure.Management.RecoveryServices.IVaultsOperations operations, string resourceGroupName, string vaultName, Microsoft.Azure.Management.RecoveryServices.Models.Vault vault);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.RecoveryServices.Models.Vault Update(class Microsoft.Azure.Management.RecoveryServices.IVaultsOperations operations, string resourceGroupName, string vaultName, class Microsoft.Azure.Management.RecoveryServices.Models.Vault vault) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.RecoveryServices.VaultsOperationsExtensions.Update(Microsoft.Azure.Management.RecoveryServices.IVaultsOperations,System.String,System.String,Microsoft.Azure.Management.RecoveryServices.Models.Vault)" />
      <MemberSignature Language="F#" Value="static member Update : Microsoft.Azure.Management.RecoveryServices.IVaultsOperations * string * string * Microsoft.Azure.Management.RecoveryServices.Models.Vault -&gt; Microsoft.Azure.Management.RecoveryServices.Models.Vault" Usage="Microsoft.Azure.Management.RecoveryServices.VaultsOperationsExtensions.Update (operations, resourceGroupName, vaultName, vault)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices</AssemblyName>
        <AssemblyVersion>4.2.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.RecoveryServices.Models.Vault</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.RecoveryServices.IVaultsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="vaultName" Type="System.String" />
        <Parameter Name="vault" Type="Microsoft.Azure.Management.RecoveryServices.Models.Vault" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="efe5d-143">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="efe5d-143">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="efe5d-144">Der Name der Ressourcengruppe, in dem die Recovery-Tresor Services, ist vorhanden.</span><span class="sxs-lookup"><span data-stu-id="efe5d-144">The name of the resource group where the recovery services vault is present.</span></span>
            </param>
        <param name="vaultName">
            <span data-ttu-id="efe5d-145">Der Name des Recovery Services-Tresor.</span><span class="sxs-lookup"><span data-stu-id="efe5d-145">The name of the recovery services vault.</span></span>
            </param>
        <param name="vault">
            <span data-ttu-id="efe5d-146">Recovery Services-Tresor erstellt werden soll.</span><span class="sxs-lookup"><span data-stu-id="efe5d-146">Recovery Services Vault to be created.</span></span>
            </param>
        <summary>
            <span data-ttu-id="efe5d-147">Aktualisiert den Tresor.</span><span class="sxs-lookup"><span data-stu-id="efe5d-147">Updates the vault.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UpdateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.RecoveryServices.Models.Vault&gt; UpdateAsync (this Microsoft.Azure.Management.RecoveryServices.IVaultsOperations operations, string resourceGroupName, string vaultName, Microsoft.Azure.Management.RecoveryServices.Models.Vault vault, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.RecoveryServices.Models.Vault&gt; UpdateAsync(class Microsoft.Azure.Management.RecoveryServices.IVaultsOperations operations, string resourceGroupName, string vaultName, class Microsoft.Azure.Management.RecoveryServices.Models.Vault vault, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.RecoveryServices.VaultsOperationsExtensions.UpdateAsync(Microsoft.Azure.Management.RecoveryServices.IVaultsOperations,System.String,System.String,Microsoft.Azure.Management.RecoveryServices.Models.Vault,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member UpdateAsync : Microsoft.Azure.Management.RecoveryServices.IVaultsOperations * string * string * Microsoft.Azure.Management.RecoveryServices.Models.Vault * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.RecoveryServices.Models.Vault&gt;" Usage="Microsoft.Azure.Management.RecoveryServices.VaultsOperationsExtensions.UpdateAsync (operations, resourceGroupName, vaultName, vault, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices</AssemblyName>
        <AssemblyVersion>4.2.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.RecoveryServices.VaultsOperationsExtensions/&lt;UpdateAsync&gt;d__11))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.RecoveryServices.Models.Vault&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.RecoveryServices.IVaultsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="vaultName" Type="System.String" />
        <Parameter Name="vault" Type="Microsoft.Azure.Management.RecoveryServices.Models.Vault" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="efe5d-148">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="efe5d-148">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="efe5d-149">Der Name der Ressourcengruppe, in dem die Recovery-Tresor Services, ist vorhanden.</span><span class="sxs-lookup"><span data-stu-id="efe5d-149">The name of the resource group where the recovery services vault is present.</span></span>
            </param>
        <param name="vaultName">
            <span data-ttu-id="efe5d-150">Der Name des Recovery Services-Tresor.</span><span class="sxs-lookup"><span data-stu-id="efe5d-150">The name of the recovery services vault.</span></span>
            </param>
        <param name="vault">
            <span data-ttu-id="efe5d-151">Recovery Services-Tresor erstellt werden soll.</span><span class="sxs-lookup"><span data-stu-id="efe5d-151">Recovery Services Vault to be created.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="efe5d-152">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="efe5d-152">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="efe5d-153">Aktualisiert den Tresor.</span><span class="sxs-lookup"><span data-stu-id="efe5d-153">Updates the vault.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>