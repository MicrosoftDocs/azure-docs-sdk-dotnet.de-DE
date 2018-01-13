<Type Name="VaultsOperationsExtensions" FullName="Microsoft.Azure.Management.KeyVault.Fluent.VaultsOperationsExtensions">
  <TypeSignature Language="C#" Value="public static class VaultsOperationsExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit VaultsOperationsExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.KeyVault.Fluent.VaultsOperationsExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module VaultsOperationsExtensions" />
  <TypeSignature Language="F#" Value="type VaultsOperationsExtensions = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.KeyVault.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="f414e-101">Erweiterungsmethoden für VaultsOperations.</span><span class="sxs-lookup"><span data-stu-id="f414e-101">Extension methods for VaultsOperations.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="CreateOrUpdateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.KeyVault.Fluent.Models.VaultInner&gt; CreateOrUpdateAsync (this Microsoft.Azure.Management.KeyVault.Fluent.IVaultsOperations operations, string resourceGroupName, string vaultName, Microsoft.Azure.Management.KeyVault.Fluent.Models.VaultCreateOrUpdateParametersInner parameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.KeyVault.Fluent.Models.VaultInner&gt; CreateOrUpdateAsync(class Microsoft.Azure.Management.KeyVault.Fluent.IVaultsOperations operations, string resourceGroupName, string vaultName, class Microsoft.Azure.Management.KeyVault.Fluent.Models.VaultCreateOrUpdateParametersInner parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.KeyVault.Fluent.VaultsOperationsExtensions.CreateOrUpdateAsync(Microsoft.Azure.Management.KeyVault.Fluent.IVaultsOperations,System.String,System.String,Microsoft.Azure.Management.KeyVault.Fluent.Models.VaultCreateOrUpdateParametersInner,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member CreateOrUpdateAsync : Microsoft.Azure.Management.KeyVault.Fluent.IVaultsOperations * string * string * Microsoft.Azure.Management.KeyVault.Fluent.Models.VaultCreateOrUpdateParametersInner * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.KeyVault.Fluent.Models.VaultInner&gt;" Usage="Microsoft.Azure.Management.KeyVault.Fluent.VaultsOperationsExtensions.CreateOrUpdateAsync (operations, resourceGroupName, vaultName, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.KeyVault.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.KeyVault.Fluent.VaultsOperationsExtensions/&lt;CreateOrUpdateAsync&gt;d__0))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.KeyVault.Fluent.Models.VaultInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.KeyVault.Fluent.IVaultsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="vaultName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.KeyVault.Fluent.Models.VaultCreateOrUpdateParametersInner" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="f414e-102">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="f414e-102">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="f414e-103">Der Name der Ressourcengruppe, zu der der Server gehört.</span><span class="sxs-lookup"><span data-stu-id="f414e-103">The name of the Resource Group to which the server belongs.</span></span>
            </param>
        <param name="vaultName">
            <span data-ttu-id="f414e-104">Name des Tresors</span><span class="sxs-lookup"><span data-stu-id="f414e-104">Name of the vault</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="f414e-105">Parameter zum Erstellen oder aktualisieren den Tresor</span><span class="sxs-lookup"><span data-stu-id="f414e-105">Parameters to create or update the vault</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="f414e-106">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="f414e-106">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="f414e-107">Erstellen oder Aktualisieren eines schlüsseltresors im angegebenen Abonnement.</span><span class="sxs-lookup"><span data-stu-id="f414e-107">Create or update a key vault in the specified subscription.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task DeleteAsync (this Microsoft.Azure.Management.KeyVault.Fluent.IVaultsOperations operations, string resourceGroupName, string vaultName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task DeleteAsync(class Microsoft.Azure.Management.KeyVault.Fluent.IVaultsOperations operations, string resourceGroupName, string vaultName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.KeyVault.Fluent.VaultsOperationsExtensions.DeleteAsync(Microsoft.Azure.Management.KeyVault.Fluent.IVaultsOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member DeleteAsync : Microsoft.Azure.Management.KeyVault.Fluent.IVaultsOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.KeyVault.Fluent.VaultsOperationsExtensions.DeleteAsync (operations, resourceGroupName, vaultName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.KeyVault.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.KeyVault.Fluent.VaultsOperationsExtensions/&lt;DeleteAsync&gt;d__1))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.KeyVault.Fluent.IVaultsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="vaultName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="f414e-108">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="f414e-108">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="f414e-109">Der Name der Ressourcengruppe, zu dem Tresor gehört.</span><span class="sxs-lookup"><span data-stu-id="f414e-109">The name of the Resource Group to which the vault belongs.</span></span>
            </param>
        <param name="vaultName">
            <span data-ttu-id="f414e-110">Der Name des dem Tresor löschen</span><span class="sxs-lookup"><span data-stu-id="f414e-110">The name of the vault to delete</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="f414e-111">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="f414e-111">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="f414e-112">Löscht die angegebene Azure-schlüsseltresor.</span><span class="sxs-lookup"><span data-stu-id="f414e-112">Deletes the specified Azure key vault.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.KeyVault.Fluent.Models.VaultInner&gt; GetAsync (this Microsoft.Azure.Management.KeyVault.Fluent.IVaultsOperations operations, string resourceGroupName, string vaultName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.KeyVault.Fluent.Models.VaultInner&gt; GetAsync(class Microsoft.Azure.Management.KeyVault.Fluent.IVaultsOperations operations, string resourceGroupName, string vaultName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.KeyVault.Fluent.VaultsOperationsExtensions.GetAsync(Microsoft.Azure.Management.KeyVault.Fluent.IVaultsOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetAsync : Microsoft.Azure.Management.KeyVault.Fluent.IVaultsOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.KeyVault.Fluent.Models.VaultInner&gt;" Usage="Microsoft.Azure.Management.KeyVault.Fluent.VaultsOperationsExtensions.GetAsync (operations, resourceGroupName, vaultName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.KeyVault.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.KeyVault.Fluent.VaultsOperationsExtensions/&lt;GetAsync&gt;d__2))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.KeyVault.Fluent.Models.VaultInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.KeyVault.Fluent.IVaultsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="vaultName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="f414e-113">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="f414e-113">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="f414e-114">Der Name der Ressourcengruppe, zu dem Tresor gehört.</span><span class="sxs-lookup"><span data-stu-id="f414e-114">The name of the Resource Group to which the vault belongs.</span></span>
            </param>
        <param name="vaultName">
            <span data-ttu-id="f414e-115">Der Name des Tresors.</span><span class="sxs-lookup"><span data-stu-id="f414e-115">The name of the vault.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="f414e-116">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="f414e-116">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="f414e-117">Ruft die angegebene Azure-schlüsseltresor.</span><span class="sxs-lookup"><span data-stu-id="f414e-117">Gets the specified Azure key vault.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.KeyVault.Fluent.Models.VaultInner&gt;&gt; ListAsync (this Microsoft.Azure.Management.KeyVault.Fluent.IVaultsOperations operations, Nullable&lt;int&gt; top = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.KeyVault.Fluent.Models.VaultInner&gt;&gt; ListAsync(class Microsoft.Azure.Management.KeyVault.Fluent.IVaultsOperations operations, valuetype System.Nullable`1&lt;int32&gt; top, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.KeyVault.Fluent.VaultsOperationsExtensions.ListAsync(Microsoft.Azure.Management.KeyVault.Fluent.IVaultsOperations,System.Nullable{System.Int32},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListAsync : Microsoft.Azure.Management.KeyVault.Fluent.IVaultsOperations * Nullable&lt;int&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.KeyVault.Fluent.Models.VaultInner&gt;&gt;" Usage="Microsoft.Azure.Management.KeyVault.Fluent.VaultsOperationsExtensions.ListAsync (operations, top, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.KeyVault.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.KeyVault.Fluent.VaultsOperationsExtensions/&lt;ListAsync&gt;d__4))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.KeyVault.Fluent.Models.VaultInner&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.KeyVault.Fluent.IVaultsOperations" RefType="this" />
        <Parameter Name="top" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="f414e-118">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="f414e-118">The operations group for this extension method.</span></span>
            </param>
        <param name="top">
            <span data-ttu-id="f414e-119">Maximale Anzahl der zurückzugebenden Ergebnisseite.</span><span class="sxs-lookup"><span data-stu-id="f414e-119">Maximum number of results to return.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="f414e-120">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="f414e-120">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="f414e-121">Der List-Vorgang ruft Informationen zu den Tresoren, die dem Abonnement zugeordnet.</span><span class="sxs-lookup"><span data-stu-id="f414e-121">The List operation gets information about the vaults associated with the subscription.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByResourceGroupAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.KeyVault.Fluent.Models.VaultInner&gt;&gt; ListByResourceGroupAsync (this Microsoft.Azure.Management.KeyVault.Fluent.IVaultsOperations operations, string resourceGroupName, Nullable&lt;int&gt; top = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.KeyVault.Fluent.Models.VaultInner&gt;&gt; ListByResourceGroupAsync(class Microsoft.Azure.Management.KeyVault.Fluent.IVaultsOperations operations, string resourceGroupName, valuetype System.Nullable`1&lt;int32&gt; top, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.KeyVault.Fluent.VaultsOperationsExtensions.ListByResourceGroupAsync(Microsoft.Azure.Management.KeyVault.Fluent.IVaultsOperations,System.String,System.Nullable{System.Int32},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListByResourceGroupAsync : Microsoft.Azure.Management.KeyVault.Fluent.IVaultsOperations * string * Nullable&lt;int&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.KeyVault.Fluent.Models.VaultInner&gt;&gt;" Usage="Microsoft.Azure.Management.KeyVault.Fluent.VaultsOperationsExtensions.ListByResourceGroupAsync (operations, resourceGroupName, top, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.KeyVault.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.KeyVault.Fluent.VaultsOperationsExtensions/&lt;ListByResourceGroupAsync&gt;d__3))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.KeyVault.Fluent.Models.VaultInner&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.KeyVault.Fluent.IVaultsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="top" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="f414e-122">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="f414e-122">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="f414e-123">Der Name der Ressourcengruppe, zu dem Tresor gehört.</span><span class="sxs-lookup"><span data-stu-id="f414e-123">The name of the Resource Group to which the vault belongs.</span></span>
            </param>
        <param name="top">
            <span data-ttu-id="f414e-124">Maximale Anzahl der zurückzugebenden Ergebnisseite.</span><span class="sxs-lookup"><span data-stu-id="f414e-124">Maximum number of results to return.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="f414e-125">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="f414e-125">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="f414e-126">Der List-Vorgang ruft Informationen zu den Tresoren verknüpft sind, mit dem Abonnement und in der angegebenen Ressourcengruppe ab.</span><span class="sxs-lookup"><span data-stu-id="f414e-126">The List operation gets information about the vaults associated with the subscription and within the specified resource group.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByResourceGroupNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.KeyVault.Fluent.Models.VaultInner&gt;&gt; ListByResourceGroupNextAsync (this Microsoft.Azure.Management.KeyVault.Fluent.IVaultsOperations operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.KeyVault.Fluent.Models.VaultInner&gt;&gt; ListByResourceGroupNextAsync(class Microsoft.Azure.Management.KeyVault.Fluent.IVaultsOperations operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.KeyVault.Fluent.VaultsOperationsExtensions.ListByResourceGroupNextAsync(Microsoft.Azure.Management.KeyVault.Fluent.IVaultsOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListByResourceGroupNextAsync : Microsoft.Azure.Management.KeyVault.Fluent.IVaultsOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.KeyVault.Fluent.Models.VaultInner&gt;&gt;" Usage="Microsoft.Azure.Management.KeyVault.Fluent.VaultsOperationsExtensions.ListByResourceGroupNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.KeyVault.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.KeyVault.Fluent.VaultsOperationsExtensions/&lt;ListByResourceGroupNextAsync&gt;d__5))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.KeyVault.Fluent.Models.VaultInner&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.KeyVault.Fluent.IVaultsOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="f414e-127">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="f414e-127">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="f414e-128">Die "NextLink" aus dem vorherigen erfolgreichen Aufruf List-Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="f414e-128">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="f414e-129">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="f414e-129">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="f414e-130">Der List-Vorgang ruft Informationen zu den Tresoren verknüpft sind, mit dem Abonnement und in der angegebenen Ressourcengruppe ab.</span><span class="sxs-lookup"><span data-stu-id="f414e-130">The List operation gets information about the vaults associated with the subscription and within the specified resource group.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.KeyVault.Fluent.Models.VaultInner&gt;&gt; ListNextAsync (this Microsoft.Azure.Management.KeyVault.Fluent.IVaultsOperations operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.KeyVault.Fluent.Models.VaultInner&gt;&gt; ListNextAsync(class Microsoft.Azure.Management.KeyVault.Fluent.IVaultsOperations operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.KeyVault.Fluent.VaultsOperationsExtensions.ListNextAsync(Microsoft.Azure.Management.KeyVault.Fluent.IVaultsOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListNextAsync : Microsoft.Azure.Management.KeyVault.Fluent.IVaultsOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.KeyVault.Fluent.Models.VaultInner&gt;&gt;" Usage="Microsoft.Azure.Management.KeyVault.Fluent.VaultsOperationsExtensions.ListNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.KeyVault.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.KeyVault.Fluent.VaultsOperationsExtensions/&lt;ListNextAsync&gt;d__6))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.KeyVault.Fluent.Models.VaultInner&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.KeyVault.Fluent.IVaultsOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="f414e-131">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="f414e-131">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="f414e-132">Die "NextLink" aus dem vorherigen erfolgreichen Aufruf List-Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="f414e-132">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="f414e-133">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="f414e-133">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="f414e-134">Der List-Vorgang ruft Informationen zu den Tresoren, die dem Abonnement zugeordnet.</span><span class="sxs-lookup"><span data-stu-id="f414e-134">The List operation gets information about the vaults associated with the subscription.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>