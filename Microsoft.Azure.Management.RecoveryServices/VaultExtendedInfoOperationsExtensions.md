<Type Name="VaultExtendedInfoOperationsExtensions" FullName="Microsoft.Azure.Management.RecoveryServices.VaultExtendedInfoOperationsExtensions">
  <TypeSignature Language="C#" Value="public static class VaultExtendedInfoOperationsExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit VaultExtendedInfoOperationsExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.RecoveryServices.VaultExtendedInfoOperationsExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module VaultExtendedInfoOperationsExtensions" />
  <TypeSignature Language="F#" Value="type VaultExtendedInfoOperationsExtensions = class" />
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
            <span data-ttu-id="e7433-101">Erweiterungsmethoden für VaultExtendedInfoOperations.</span><span class="sxs-lookup"><span data-stu-id="e7433-101">Extension methods for VaultExtendedInfoOperations.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="CreateOrUpdate">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.RecoveryServices.Models.VaultExtendedInfoResource CreateOrUpdate (this Microsoft.Azure.Management.RecoveryServices.IVaultExtendedInfoOperations operations, string resourceGroupName, string vaultName, Microsoft.Azure.Management.RecoveryServices.Models.VaultExtendedInfoResource resourceResourceExtendedInfoDetails);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.RecoveryServices.Models.VaultExtendedInfoResource CreateOrUpdate(class Microsoft.Azure.Management.RecoveryServices.IVaultExtendedInfoOperations operations, string resourceGroupName, string vaultName, class Microsoft.Azure.Management.RecoveryServices.Models.VaultExtendedInfoResource resourceResourceExtendedInfoDetails) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.RecoveryServices.VaultExtendedInfoOperationsExtensions.CreateOrUpdate(Microsoft.Azure.Management.RecoveryServices.IVaultExtendedInfoOperations,System.String,System.String,Microsoft.Azure.Management.RecoveryServices.Models.VaultExtendedInfoResource)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function CreateOrUpdate (operations As IVaultExtendedInfoOperations, resourceGroupName As String, vaultName As String, resourceResourceExtendedInfoDetails As VaultExtendedInfoResource) As VaultExtendedInfoResource" />
      <MemberSignature Language="F#" Value="static member CreateOrUpdate : Microsoft.Azure.Management.RecoveryServices.IVaultExtendedInfoOperations * string * string * Microsoft.Azure.Management.RecoveryServices.Models.VaultExtendedInfoResource -&gt; Microsoft.Azure.Management.RecoveryServices.Models.VaultExtendedInfoResource" Usage="Microsoft.Azure.Management.RecoveryServices.VaultExtendedInfoOperationsExtensions.CreateOrUpdate (operations, resourceGroupName, vaultName, resourceResourceExtendedInfoDetails)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices</AssemblyName>
        <AssemblyVersion>4.2.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.RecoveryServices.Models.VaultExtendedInfoResource</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.RecoveryServices.IVaultExtendedInfoOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="vaultName" Type="System.String" />
        <Parameter Name="resourceResourceExtendedInfoDetails" Type="Microsoft.Azure.Management.RecoveryServices.Models.VaultExtendedInfoResource" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="e7433-102">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="e7433-102">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="e7433-103">Der Name der Ressourcengruppe, in dem die Recovery-Tresor Services, ist vorhanden.</span><span class="sxs-lookup"><span data-stu-id="e7433-103">The name of the resource group where the recovery services vault is present.</span></span>
            </param>
        <param name="vaultName">
            <span data-ttu-id="e7433-104">Der Name des Recovery Services-Tresor.</span><span class="sxs-lookup"><span data-stu-id="e7433-104">The name of the recovery services vault.</span></span>
            </param>
        <param name="resourceResourceExtendedInfoDetails">
            <span data-ttu-id="e7433-105">resourceResourceExtendedInfoDetails</span><span class="sxs-lookup"><span data-stu-id="e7433-105">resourceResourceExtendedInfoDetails</span></span>
            </param>
        <summary>
            <span data-ttu-id="e7433-106">Erstellen Sie erweiterte Informationen Tresor.</span><span class="sxs-lookup"><span data-stu-id="e7433-106">Create vault extended info.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateOrUpdateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.RecoveryServices.Models.VaultExtendedInfoResource&gt; CreateOrUpdateAsync (this Microsoft.Azure.Management.RecoveryServices.IVaultExtendedInfoOperations operations, string resourceGroupName, string vaultName, Microsoft.Azure.Management.RecoveryServices.Models.VaultExtendedInfoResource resourceResourceExtendedInfoDetails, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.RecoveryServices.Models.VaultExtendedInfoResource&gt; CreateOrUpdateAsync(class Microsoft.Azure.Management.RecoveryServices.IVaultExtendedInfoOperations operations, string resourceGroupName, string vaultName, class Microsoft.Azure.Management.RecoveryServices.Models.VaultExtendedInfoResource resourceResourceExtendedInfoDetails, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.RecoveryServices.VaultExtendedInfoOperationsExtensions.CreateOrUpdateAsync(Microsoft.Azure.Management.RecoveryServices.IVaultExtendedInfoOperations,System.String,System.String,Microsoft.Azure.Management.RecoveryServices.Models.VaultExtendedInfoResource,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member CreateOrUpdateAsync : Microsoft.Azure.Management.RecoveryServices.IVaultExtendedInfoOperations * string * string * Microsoft.Azure.Management.RecoveryServices.Models.VaultExtendedInfoResource * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.RecoveryServices.Models.VaultExtendedInfoResource&gt;" Usage="Microsoft.Azure.Management.RecoveryServices.VaultExtendedInfoOperationsExtensions.CreateOrUpdateAsync (operations, resourceGroupName, vaultName, resourceResourceExtendedInfoDetails, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices</AssemblyName>
        <AssemblyVersion>4.2.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.RecoveryServices.VaultExtendedInfoOperationsExtensions/&lt;CreateOrUpdateAsync&gt;d__3))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.RecoveryServices.Models.VaultExtendedInfoResource&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.RecoveryServices.IVaultExtendedInfoOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="vaultName" Type="System.String" />
        <Parameter Name="resourceResourceExtendedInfoDetails" Type="Microsoft.Azure.Management.RecoveryServices.Models.VaultExtendedInfoResource" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="e7433-107">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="e7433-107">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="e7433-108">Der Name der Ressourcengruppe, in dem die Recovery-Tresor Services, ist vorhanden.</span><span class="sxs-lookup"><span data-stu-id="e7433-108">The name of the resource group where the recovery services vault is present.</span></span>
            </param>
        <param name="vaultName">
            <span data-ttu-id="e7433-109">Der Name des Recovery Services-Tresor.</span><span class="sxs-lookup"><span data-stu-id="e7433-109">The name of the recovery services vault.</span></span>
            </param>
        <param name="resourceResourceExtendedInfoDetails">
            <span data-ttu-id="e7433-110">resourceResourceExtendedInfoDetails</span><span class="sxs-lookup"><span data-stu-id="e7433-110">resourceResourceExtendedInfoDetails</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="e7433-111">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="e7433-111">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="e7433-112">Erstellen Sie erweiterte Informationen Tresor.</span><span class="sxs-lookup"><span data-stu-id="e7433-112">Create vault extended info.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Get">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.RecoveryServices.Models.VaultExtendedInfoResource Get (this Microsoft.Azure.Management.RecoveryServices.IVaultExtendedInfoOperations operations, string resourceGroupName, string vaultName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.RecoveryServices.Models.VaultExtendedInfoResource Get(class Microsoft.Azure.Management.RecoveryServices.IVaultExtendedInfoOperations operations, string resourceGroupName, string vaultName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.RecoveryServices.VaultExtendedInfoOperationsExtensions.Get(Microsoft.Azure.Management.RecoveryServices.IVaultExtendedInfoOperations,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function Get (operations As IVaultExtendedInfoOperations, resourceGroupName As String, vaultName As String) As VaultExtendedInfoResource" />
      <MemberSignature Language="F#" Value="static member Get : Microsoft.Azure.Management.RecoveryServices.IVaultExtendedInfoOperations * string * string -&gt; Microsoft.Azure.Management.RecoveryServices.Models.VaultExtendedInfoResource" Usage="Microsoft.Azure.Management.RecoveryServices.VaultExtendedInfoOperationsExtensions.Get (operations, resourceGroupName, vaultName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices</AssemblyName>
        <AssemblyVersion>4.2.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.RecoveryServices.Models.VaultExtendedInfoResource</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.RecoveryServices.IVaultExtendedInfoOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="vaultName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="e7433-113">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="e7433-113">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="e7433-114">Der Name der Ressourcengruppe, in dem die Recovery-Tresor Services, ist vorhanden.</span><span class="sxs-lookup"><span data-stu-id="e7433-114">The name of the resource group where the recovery services vault is present.</span></span>
            </param>
        <param name="vaultName">
            <span data-ttu-id="e7433-115">Der Name des Recovery Services-Tresor.</span><span class="sxs-lookup"><span data-stu-id="e7433-115">The name of the recovery services vault.</span></span>
            </param>
        <summary>
            <span data-ttu-id="e7433-116">Rufen Sie den Tresor erweiterte Informationen.</span><span class="sxs-lookup"><span data-stu-id="e7433-116">Get the vault extended info.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.RecoveryServices.Models.VaultExtendedInfoResource&gt; GetAsync (this Microsoft.Azure.Management.RecoveryServices.IVaultExtendedInfoOperations operations, string resourceGroupName, string vaultName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.RecoveryServices.Models.VaultExtendedInfoResource&gt; GetAsync(class Microsoft.Azure.Management.RecoveryServices.IVaultExtendedInfoOperations operations, string resourceGroupName, string vaultName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.RecoveryServices.VaultExtendedInfoOperationsExtensions.GetAsync(Microsoft.Azure.Management.RecoveryServices.IVaultExtendedInfoOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetAsync : Microsoft.Azure.Management.RecoveryServices.IVaultExtendedInfoOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.RecoveryServices.Models.VaultExtendedInfoResource&gt;" Usage="Microsoft.Azure.Management.RecoveryServices.VaultExtendedInfoOperationsExtensions.GetAsync (operations, resourceGroupName, vaultName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices</AssemblyName>
        <AssemblyVersion>4.2.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.RecoveryServices.VaultExtendedInfoOperationsExtensions/&lt;GetAsync&gt;d__1))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.RecoveryServices.Models.VaultExtendedInfoResource&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.RecoveryServices.IVaultExtendedInfoOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="vaultName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="e7433-117">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="e7433-117">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="e7433-118">Der Name der Ressourcengruppe, in dem die Recovery-Tresor Services, ist vorhanden.</span><span class="sxs-lookup"><span data-stu-id="e7433-118">The name of the resource group where the recovery services vault is present.</span></span>
            </param>
        <param name="vaultName">
            <span data-ttu-id="e7433-119">Der Name des Recovery Services-Tresor.</span><span class="sxs-lookup"><span data-stu-id="e7433-119">The name of the recovery services vault.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="e7433-120">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="e7433-120">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="e7433-121">Rufen Sie den Tresor erweiterte Informationen.</span><span class="sxs-lookup"><span data-stu-id="e7433-121">Get the vault extended info.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Update">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.RecoveryServices.Models.VaultExtendedInfoResource Update (this Microsoft.Azure.Management.RecoveryServices.IVaultExtendedInfoOperations operations, string resourceGroupName, string vaultName, Microsoft.Azure.Management.RecoveryServices.Models.VaultExtendedInfoResource resourceResourceExtendedInfoDetails);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.RecoveryServices.Models.VaultExtendedInfoResource Update(class Microsoft.Azure.Management.RecoveryServices.IVaultExtendedInfoOperations operations, string resourceGroupName, string vaultName, class Microsoft.Azure.Management.RecoveryServices.Models.VaultExtendedInfoResource resourceResourceExtendedInfoDetails) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.RecoveryServices.VaultExtendedInfoOperationsExtensions.Update(Microsoft.Azure.Management.RecoveryServices.IVaultExtendedInfoOperations,System.String,System.String,Microsoft.Azure.Management.RecoveryServices.Models.VaultExtendedInfoResource)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function Update (operations As IVaultExtendedInfoOperations, resourceGroupName As String, vaultName As String, resourceResourceExtendedInfoDetails As VaultExtendedInfoResource) As VaultExtendedInfoResource" />
      <MemberSignature Language="F#" Value="static member Update : Microsoft.Azure.Management.RecoveryServices.IVaultExtendedInfoOperations * string * string * Microsoft.Azure.Management.RecoveryServices.Models.VaultExtendedInfoResource -&gt; Microsoft.Azure.Management.RecoveryServices.Models.VaultExtendedInfoResource" Usage="Microsoft.Azure.Management.RecoveryServices.VaultExtendedInfoOperationsExtensions.Update (operations, resourceGroupName, vaultName, resourceResourceExtendedInfoDetails)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices</AssemblyName>
        <AssemblyVersion>4.2.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.RecoveryServices.Models.VaultExtendedInfoResource</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.RecoveryServices.IVaultExtendedInfoOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="vaultName" Type="System.String" />
        <Parameter Name="resourceResourceExtendedInfoDetails" Type="Microsoft.Azure.Management.RecoveryServices.Models.VaultExtendedInfoResource" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="e7433-122">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="e7433-122">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="e7433-123">Der Name der Ressourcengruppe, in dem die Recovery-Tresor Services, ist vorhanden.</span><span class="sxs-lookup"><span data-stu-id="e7433-123">The name of the resource group where the recovery services vault is present.</span></span>
            </param>
        <param name="vaultName">
            <span data-ttu-id="e7433-124">Der Name des Recovery Services-Tresor.</span><span class="sxs-lookup"><span data-stu-id="e7433-124">The name of the recovery services vault.</span></span>
            </param>
        <param name="resourceResourceExtendedInfoDetails">
            <span data-ttu-id="e7433-125">resourceResourceExtendedInfoDetails</span><span class="sxs-lookup"><span data-stu-id="e7433-125">resourceResourceExtendedInfoDetails</span></span>
            </param>
        <summary>
            <span data-ttu-id="e7433-126">Tresor erweiterte Informationen zu aktualisieren.</span><span class="sxs-lookup"><span data-stu-id="e7433-126">Update vault extended info.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UpdateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.RecoveryServices.Models.VaultExtendedInfoResource&gt; UpdateAsync (this Microsoft.Azure.Management.RecoveryServices.IVaultExtendedInfoOperations operations, string resourceGroupName, string vaultName, Microsoft.Azure.Management.RecoveryServices.Models.VaultExtendedInfoResource resourceResourceExtendedInfoDetails, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.RecoveryServices.Models.VaultExtendedInfoResource&gt; UpdateAsync(class Microsoft.Azure.Management.RecoveryServices.IVaultExtendedInfoOperations operations, string resourceGroupName, string vaultName, class Microsoft.Azure.Management.RecoveryServices.Models.VaultExtendedInfoResource resourceResourceExtendedInfoDetails, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.RecoveryServices.VaultExtendedInfoOperationsExtensions.UpdateAsync(Microsoft.Azure.Management.RecoveryServices.IVaultExtendedInfoOperations,System.String,System.String,Microsoft.Azure.Management.RecoveryServices.Models.VaultExtendedInfoResource,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member UpdateAsync : Microsoft.Azure.Management.RecoveryServices.IVaultExtendedInfoOperations * string * string * Microsoft.Azure.Management.RecoveryServices.Models.VaultExtendedInfoResource * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.RecoveryServices.Models.VaultExtendedInfoResource&gt;" Usage="Microsoft.Azure.Management.RecoveryServices.VaultExtendedInfoOperationsExtensions.UpdateAsync (operations, resourceGroupName, vaultName, resourceResourceExtendedInfoDetails, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices</AssemblyName>
        <AssemblyVersion>4.2.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.RecoveryServices.VaultExtendedInfoOperationsExtensions/&lt;UpdateAsync&gt;d__5))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.RecoveryServices.Models.VaultExtendedInfoResource&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.RecoveryServices.IVaultExtendedInfoOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="vaultName" Type="System.String" />
        <Parameter Name="resourceResourceExtendedInfoDetails" Type="Microsoft.Azure.Management.RecoveryServices.Models.VaultExtendedInfoResource" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="e7433-127">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="e7433-127">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="e7433-128">Der Name der Ressourcengruppe, in dem die Recovery-Tresor Services, ist vorhanden.</span><span class="sxs-lookup"><span data-stu-id="e7433-128">The name of the resource group where the recovery services vault is present.</span></span>
            </param>
        <param name="vaultName">
            <span data-ttu-id="e7433-129">Der Name des Recovery Services-Tresor.</span><span class="sxs-lookup"><span data-stu-id="e7433-129">The name of the recovery services vault.</span></span>
            </param>
        <param name="resourceResourceExtendedInfoDetails">
            <span data-ttu-id="e7433-130">resourceResourceExtendedInfoDetails</span><span class="sxs-lookup"><span data-stu-id="e7433-130">resourceResourceExtendedInfoDetails</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="e7433-131">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="e7433-131">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="e7433-132">Tresor erweiterte Informationen zu aktualisieren.</span><span class="sxs-lookup"><span data-stu-id="e7433-132">Update vault extended info.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>