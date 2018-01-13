<Type Name="ProtectedItemsOperationsExtensions" FullName="Microsoft.Azure.Management.RecoveryServices.Backup.ProtectedItemsOperationsExtensions">
  <TypeSignature Language="C#" Value="public static class ProtectedItemsOperationsExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit ProtectedItemsOperationsExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.RecoveryServices.Backup.ProtectedItemsOperationsExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module ProtectedItemsOperationsExtensions" />
  <TypeSignature Language="F#" Value="type ProtectedItemsOperationsExtensions = class" />
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
            <span data-ttu-id="a64cc-101">Erweiterungsmethoden für ProtectedItemsOperations.</span><span class="sxs-lookup"><span data-stu-id="a64cc-101">Extension methods for ProtectedItemsOperations.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="CreateOrUpdate">
      <MemberSignature Language="C#" Value="public static void CreateOrUpdate (this Microsoft.Azure.Management.RecoveryServices.Backup.IProtectedItemsOperations operations, string vaultName, string resourceGroupName, string fabricName, string containerName, string protectedItemName, Microsoft.Azure.Management.RecoveryServices.Backup.Models.ProtectedItemResource parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void CreateOrUpdate(class Microsoft.Azure.Management.RecoveryServices.Backup.IProtectedItemsOperations operations, string vaultName, string resourceGroupName, string fabricName, string containerName, string protectedItemName, class Microsoft.Azure.Management.RecoveryServices.Backup.Models.ProtectedItemResource parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.RecoveryServices.Backup.ProtectedItemsOperationsExtensions.CreateOrUpdate(Microsoft.Azure.Management.RecoveryServices.Backup.IProtectedItemsOperations,System.String,System.String,System.String,System.String,System.String,Microsoft.Azure.Management.RecoveryServices.Backup.Models.ProtectedItemResource)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Sub CreateOrUpdate (operations As IProtectedItemsOperations, vaultName As String, resourceGroupName As String, fabricName As String, containerName As String, protectedItemName As String, parameters As ProtectedItemResource)" />
      <MemberSignature Language="F#" Value="static member CreateOrUpdate : Microsoft.Azure.Management.RecoveryServices.Backup.IProtectedItemsOperations * string * string * string * string * string * Microsoft.Azure.Management.RecoveryServices.Backup.Models.ProtectedItemResource -&gt; unit" Usage="Microsoft.Azure.Management.RecoveryServices.Backup.ProtectedItemsOperationsExtensions.CreateOrUpdate (operations, vaultName, resourceGroupName, fabricName, containerName, protectedItemName, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.RecoveryServices.Backup.IProtectedItemsOperations" RefType="this" />
        <Parameter Name="vaultName" Type="System.String" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="fabricName" Type="System.String" />
        <Parameter Name="containerName" Type="System.String" />
        <Parameter Name="protectedItemName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.RecoveryServices.Backup.Models.ProtectedItemResource" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="a64cc-102">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="a64cc-102">The operations group for this extension method.</span></span>
            </param>
        <param name="vaultName">
            <span data-ttu-id="a64cc-103">Der Name des Recovery Services-Tresor.</span><span class="sxs-lookup"><span data-stu-id="a64cc-103">The name of the recovery services vault.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="a64cc-104">Der Name der Ressourcengruppe, in dem die Recovery-Tresor Services, ist vorhanden.</span><span class="sxs-lookup"><span data-stu-id="a64cc-104">The name of the resource group where the recovery services vault is present.</span></span>
            </param>
        <param name="fabricName">
            <span data-ttu-id="a64cc-105">Name des Fabric, das Sichern des Elements zugeordnet.</span><span class="sxs-lookup"><span data-stu-id="a64cc-105">Fabric name associated with the backup item.</span></span>
            </param>
        <param name="containerName">
            <span data-ttu-id="a64cc-106">Der Containername das Sichern des Elements zugeordnet.</span><span class="sxs-lookup"><span data-stu-id="a64cc-106">Container name associated with the backup item.</span></span>
            </param>
        <param name="protectedItemName">
            <span data-ttu-id="a64cc-107">Der Elementname, die gesichert werden sollen.</span><span class="sxs-lookup"><span data-stu-id="a64cc-107">Item name to be backed up.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="a64cc-108">Ressource-Elements gesichert</span><span class="sxs-lookup"><span data-stu-id="a64cc-108">resource backed up item</span></span>
            </param>
        <summary>
            <span data-ttu-id="a64cc-109">Ermöglicht die Sicherung eines Elements ab oder ändert auf die Sicherungsrichtlinie Informationen eines bereits gesicherten Elements.</span><span class="sxs-lookup"><span data-stu-id="a64cc-109">Enables backup of an item or to modifies the backup policy information of an already backed up item.</span></span> <span data-ttu-id="a64cc-110">Das ist ein asynchroner Vorgang.</span><span class="sxs-lookup"><span data-stu-id="a64cc-110">This is an asynchronous operation.</span></span> <span data-ttu-id="a64cc-111">Um den Status des Vorgangs zu kennen, rufen Sie die GetItemOperationResult-API.</span><span class="sxs-lookup"><span data-stu-id="a64cc-111">To know the status of the operation, call the GetItemOperationResult API.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateOrUpdateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task CreateOrUpdateAsync (this Microsoft.Azure.Management.RecoveryServices.Backup.IProtectedItemsOperations operations, string vaultName, string resourceGroupName, string fabricName, string containerName, string protectedItemName, Microsoft.Azure.Management.RecoveryServices.Backup.Models.ProtectedItemResource parameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task CreateOrUpdateAsync(class Microsoft.Azure.Management.RecoveryServices.Backup.IProtectedItemsOperations operations, string vaultName, string resourceGroupName, string fabricName, string containerName, string protectedItemName, class Microsoft.Azure.Management.RecoveryServices.Backup.Models.ProtectedItemResource parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.RecoveryServices.Backup.ProtectedItemsOperationsExtensions.CreateOrUpdateAsync(Microsoft.Azure.Management.RecoveryServices.Backup.IProtectedItemsOperations,System.String,System.String,System.String,System.String,System.String,Microsoft.Azure.Management.RecoveryServices.Backup.Models.ProtectedItemResource,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member CreateOrUpdateAsync : Microsoft.Azure.Management.RecoveryServices.Backup.IProtectedItemsOperations * string * string * string * string * string * Microsoft.Azure.Management.RecoveryServices.Backup.Models.ProtectedItemResource * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.RecoveryServices.Backup.ProtectedItemsOperationsExtensions.CreateOrUpdateAsync (operations, vaultName, resourceGroupName, fabricName, containerName, protectedItemName, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.RecoveryServices.Backup.ProtectedItemsOperationsExtensions/&lt;CreateOrUpdateAsync&gt;d__3))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.RecoveryServices.Backup.IProtectedItemsOperations" RefType="this" />
        <Parameter Name="vaultName" Type="System.String" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="fabricName" Type="System.String" />
        <Parameter Name="containerName" Type="System.String" />
        <Parameter Name="protectedItemName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.RecoveryServices.Backup.Models.ProtectedItemResource" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="a64cc-112">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="a64cc-112">The operations group for this extension method.</span></span>
            </param>
        <param name="vaultName">
            <span data-ttu-id="a64cc-113">Der Name des Recovery Services-Tresor.</span><span class="sxs-lookup"><span data-stu-id="a64cc-113">The name of the recovery services vault.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="a64cc-114">Der Name der Ressourcengruppe, in dem die Recovery-Tresor Services, ist vorhanden.</span><span class="sxs-lookup"><span data-stu-id="a64cc-114">The name of the resource group where the recovery services vault is present.</span></span>
            </param>
        <param name="fabricName">
            <span data-ttu-id="a64cc-115">Name des Fabric, das Sichern des Elements zugeordnet.</span><span class="sxs-lookup"><span data-stu-id="a64cc-115">Fabric name associated with the backup item.</span></span>
            </param>
        <param name="containerName">
            <span data-ttu-id="a64cc-116">Der Containername das Sichern des Elements zugeordnet.</span><span class="sxs-lookup"><span data-stu-id="a64cc-116">Container name associated with the backup item.</span></span>
            </param>
        <param name="protectedItemName">
            <span data-ttu-id="a64cc-117">Der Elementname, die gesichert werden sollen.</span><span class="sxs-lookup"><span data-stu-id="a64cc-117">Item name to be backed up.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="a64cc-118">Ressource-Elements gesichert</span><span class="sxs-lookup"><span data-stu-id="a64cc-118">resource backed up item</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="a64cc-119">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="a64cc-119">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="a64cc-120">Ermöglicht die Sicherung eines Elements ab oder ändert auf die Sicherungsrichtlinie Informationen eines bereits gesicherten Elements.</span><span class="sxs-lookup"><span data-stu-id="a64cc-120">Enables backup of an item or to modifies the backup policy information of an already backed up item.</span></span> <span data-ttu-id="a64cc-121">Das ist ein asynchroner Vorgang.</span><span class="sxs-lookup"><span data-stu-id="a64cc-121">This is an asynchronous operation.</span></span> <span data-ttu-id="a64cc-122">Um den Status des Vorgangs zu kennen, rufen Sie die GetItemOperationResult-API.</span><span class="sxs-lookup"><span data-stu-id="a64cc-122">To know the status of the operation, call the GetItemOperationResult API.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Delete">
      <MemberSignature Language="C#" Value="public static void Delete (this Microsoft.Azure.Management.RecoveryServices.Backup.IProtectedItemsOperations operations, string vaultName, string resourceGroupName, string fabricName, string containerName, string protectedItemName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void Delete(class Microsoft.Azure.Management.RecoveryServices.Backup.IProtectedItemsOperations operations, string vaultName, string resourceGroupName, string fabricName, string containerName, string protectedItemName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.RecoveryServices.Backup.ProtectedItemsOperationsExtensions.Delete(Microsoft.Azure.Management.RecoveryServices.Backup.IProtectedItemsOperations,System.String,System.String,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Sub Delete (operations As IProtectedItemsOperations, vaultName As String, resourceGroupName As String, fabricName As String, containerName As String, protectedItemName As String)" />
      <MemberSignature Language="F#" Value="static member Delete : Microsoft.Azure.Management.RecoveryServices.Backup.IProtectedItemsOperations * string * string * string * string * string -&gt; unit" Usage="Microsoft.Azure.Management.RecoveryServices.Backup.ProtectedItemsOperationsExtensions.Delete (operations, vaultName, resourceGroupName, fabricName, containerName, protectedItemName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.RecoveryServices.Backup.IProtectedItemsOperations" RefType="this" />
        <Parameter Name="vaultName" Type="System.String" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="fabricName" Type="System.String" />
        <Parameter Name="containerName" Type="System.String" />
        <Parameter Name="protectedItemName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="a64cc-123">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="a64cc-123">The operations group for this extension method.</span></span>
            </param>
        <param name="vaultName">
            <span data-ttu-id="a64cc-124">Der Name des Recovery Services-Tresor.</span><span class="sxs-lookup"><span data-stu-id="a64cc-124">The name of the recovery services vault.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="a64cc-125">Der Name der Ressourcengruppe, in dem die Recovery-Tresor Services, ist vorhanden.</span><span class="sxs-lookup"><span data-stu-id="a64cc-125">The name of the resource group where the recovery services vault is present.</span></span>
            </param>
        <param name="fabricName">
            <span data-ttu-id="a64cc-126">Name des Fabric gesicherten Element zugeordnet.</span><span class="sxs-lookup"><span data-stu-id="a64cc-126">Fabric name associated with the backed up item.</span></span>
            </param>
        <param name="containerName">
            <span data-ttu-id="a64cc-127">Der Containername gesicherten Element zugeordnet.</span><span class="sxs-lookup"><span data-stu-id="a64cc-127">Container name associated with the backed up item.</span></span>
            </param>
        <param name="protectedItemName">
            <span data-ttu-id="a64cc-128">Gesichert, Element gelöscht werden soll.</span><span class="sxs-lookup"><span data-stu-id="a64cc-128">Backed up item to be deleted.</span></span>
            </param>
        <summary>
            <span data-ttu-id="a64cc-129">So deaktivieren Sie die Sicherung eines Elements innerhalb eines Containers verwendet.</span><span class="sxs-lookup"><span data-stu-id="a64cc-129">Used to disable backup of an item within a container.</span></span> <span data-ttu-id="a64cc-130">Das ist ein asynchroner Vorgang.</span><span class="sxs-lookup"><span data-stu-id="a64cc-130">This is an asynchronous operation.</span></span> <span data-ttu-id="a64cc-131">Um den Status der Anforderung kennen, rufen Sie die GetItemOperationResult-API.</span><span class="sxs-lookup"><span data-stu-id="a64cc-131">To know the status of the request, call the GetItemOperationResult API.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task DeleteAsync (this Microsoft.Azure.Management.RecoveryServices.Backup.IProtectedItemsOperations operations, string vaultName, string resourceGroupName, string fabricName, string containerName, string protectedItemName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task DeleteAsync(class Microsoft.Azure.Management.RecoveryServices.Backup.IProtectedItemsOperations operations, string vaultName, string resourceGroupName, string fabricName, string containerName, string protectedItemName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.RecoveryServices.Backup.ProtectedItemsOperationsExtensions.DeleteAsync(Microsoft.Azure.Management.RecoveryServices.Backup.IProtectedItemsOperations,System.String,System.String,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member DeleteAsync : Microsoft.Azure.Management.RecoveryServices.Backup.IProtectedItemsOperations * string * string * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.RecoveryServices.Backup.ProtectedItemsOperationsExtensions.DeleteAsync (operations, vaultName, resourceGroupName, fabricName, containerName, protectedItemName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.RecoveryServices.Backup.ProtectedItemsOperationsExtensions/&lt;DeleteAsync&gt;d__5))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.RecoveryServices.Backup.IProtectedItemsOperations" RefType="this" />
        <Parameter Name="vaultName" Type="System.String" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="fabricName" Type="System.String" />
        <Parameter Name="containerName" Type="System.String" />
        <Parameter Name="protectedItemName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="a64cc-132">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="a64cc-132">The operations group for this extension method.</span></span>
            </param>
        <param name="vaultName">
            <span data-ttu-id="a64cc-133">Der Name des Recovery Services-Tresor.</span><span class="sxs-lookup"><span data-stu-id="a64cc-133">The name of the recovery services vault.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="a64cc-134">Der Name der Ressourcengruppe, in dem die Recovery-Tresor Services, ist vorhanden.</span><span class="sxs-lookup"><span data-stu-id="a64cc-134">The name of the resource group where the recovery services vault is present.</span></span>
            </param>
        <param name="fabricName">
            <span data-ttu-id="a64cc-135">Name des Fabric gesicherten Element zugeordnet.</span><span class="sxs-lookup"><span data-stu-id="a64cc-135">Fabric name associated with the backed up item.</span></span>
            </param>
        <param name="containerName">
            <span data-ttu-id="a64cc-136">Der Containername gesicherten Element zugeordnet.</span><span class="sxs-lookup"><span data-stu-id="a64cc-136">Container name associated with the backed up item.</span></span>
            </param>
        <param name="protectedItemName">
            <span data-ttu-id="a64cc-137">Gesichert, Element gelöscht werden soll.</span><span class="sxs-lookup"><span data-stu-id="a64cc-137">Backed up item to be deleted.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="a64cc-138">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="a64cc-138">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="a64cc-139">So deaktivieren Sie die Sicherung eines Elements innerhalb eines Containers verwendet.</span><span class="sxs-lookup"><span data-stu-id="a64cc-139">Used to disable backup of an item within a container.</span></span> <span data-ttu-id="a64cc-140">Das ist ein asynchroner Vorgang.</span><span class="sxs-lookup"><span data-stu-id="a64cc-140">This is an asynchronous operation.</span></span> <span data-ttu-id="a64cc-141">Um den Status der Anforderung kennen, rufen Sie die GetItemOperationResult-API.</span><span class="sxs-lookup"><span data-stu-id="a64cc-141">To know the status of the request, call the GetItemOperationResult API.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Get">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.RecoveryServices.Backup.Models.ProtectedItemResource Get (this Microsoft.Azure.Management.RecoveryServices.Backup.IProtectedItemsOperations operations, string vaultName, string resourceGroupName, string fabricName, string containerName, string protectedItemName, Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.RecoveryServices.Backup.Models.GetProtectedItemQueryObject&gt; odataQuery = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.RecoveryServices.Backup.Models.ProtectedItemResource Get(class Microsoft.Azure.Management.RecoveryServices.Backup.IProtectedItemsOperations operations, string vaultName, string resourceGroupName, string fabricName, string containerName, string protectedItemName, class Microsoft.Rest.Azure.OData.ODataQuery`1&lt;class Microsoft.Azure.Management.RecoveryServices.Backup.Models.GetProtectedItemQueryObject&gt; odataQuery) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.RecoveryServices.Backup.ProtectedItemsOperationsExtensions.Get(Microsoft.Azure.Management.RecoveryServices.Backup.IProtectedItemsOperations,System.String,System.String,System.String,System.String,System.String,Microsoft.Rest.Azure.OData.ODataQuery{Microsoft.Azure.Management.RecoveryServices.Backup.Models.GetProtectedItemQueryObject})" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function Get (operations As IProtectedItemsOperations, vaultName As String, resourceGroupName As String, fabricName As String, containerName As String, protectedItemName As String, Optional odataQuery As ODataQuery(Of GetProtectedItemQueryObject) = null) As ProtectedItemResource" />
      <MemberSignature Language="F#" Value="static member Get : Microsoft.Azure.Management.RecoveryServices.Backup.IProtectedItemsOperations * string * string * string * string * string * Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.RecoveryServices.Backup.Models.GetProtectedItemQueryObject&gt; -&gt; Microsoft.Azure.Management.RecoveryServices.Backup.Models.ProtectedItemResource" Usage="Microsoft.Azure.Management.RecoveryServices.Backup.ProtectedItemsOperationsExtensions.Get (operations, vaultName, resourceGroupName, fabricName, containerName, protectedItemName, odataQuery)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.RecoveryServices.Backup.Models.ProtectedItemResource</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.RecoveryServices.Backup.IProtectedItemsOperations" RefType="this" />
        <Parameter Name="vaultName" Type="System.String" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="fabricName" Type="System.String" />
        <Parameter Name="containerName" Type="System.String" />
        <Parameter Name="protectedItemName" Type="System.String" />
        <Parameter Name="odataQuery" Type="Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.RecoveryServices.Backup.Models.GetProtectedItemQueryObject&gt;" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="a64cc-142">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="a64cc-142">The operations group for this extension method.</span></span>
            </param>
        <param name="vaultName">
            <span data-ttu-id="a64cc-143">Der Name des Recovery Services-Tresor.</span><span class="sxs-lookup"><span data-stu-id="a64cc-143">The name of the recovery services vault.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="a64cc-144">Der Name der Ressourcengruppe, in dem die Recovery-Tresor Services, ist vorhanden.</span><span class="sxs-lookup"><span data-stu-id="a64cc-144">The name of the resource group where the recovery services vault is present.</span></span>
            </param>
        <param name="fabricName">
            <span data-ttu-id="a64cc-145">Name des Fabric gesicherten Element zugeordnet.</span><span class="sxs-lookup"><span data-stu-id="a64cc-145">Fabric name associated with the backed up item.</span></span>
            </param>
        <param name="containerName">
            <span data-ttu-id="a64cc-146">Der Containername gesicherten Element zugeordnet.</span><span class="sxs-lookup"><span data-stu-id="a64cc-146">Container name associated with the backed up item.</span></span>
            </param>
        <param name="protectedItemName">
            <span data-ttu-id="a64cc-147">Gesichert, Name des Elements, dessen Details werden abgerufen werden sollen.</span><span class="sxs-lookup"><span data-stu-id="a64cc-147">Backed up item name whose details are to be fetched.</span></span>
            </param>
        <param name="odataQuery">
            <span data-ttu-id="a64cc-148">OData-Parameter des Vorgangs angewendet.</span><span class="sxs-lookup"><span data-stu-id="a64cc-148">OData parameters to apply to the operation.</span></span>
            </param>
        <summary>
            <span data-ttu-id="a64cc-149">Enthält die Details des gesicherten Elements.</span><span class="sxs-lookup"><span data-stu-id="a64cc-149">Provides the details of the backed up item.</span></span> <span data-ttu-id="a64cc-150">Das ist ein asynchroner Vorgang.</span><span class="sxs-lookup"><span data-stu-id="a64cc-150">This is an asynchronous operation.</span></span> <span data-ttu-id="a64cc-151">Um den Status des Vorgangs zu kennen, rufen Sie die GetItemOperationResult-API.</span><span class="sxs-lookup"><span data-stu-id="a64cc-151">To know the status of the operation, call the GetItemOperationResult API.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.RecoveryServices.Backup.Models.ProtectedItemResource&gt; GetAsync (this Microsoft.Azure.Management.RecoveryServices.Backup.IProtectedItemsOperations operations, string vaultName, string resourceGroupName, string fabricName, string containerName, string protectedItemName, Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.RecoveryServices.Backup.Models.GetProtectedItemQueryObject&gt; odataQuery = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.RecoveryServices.Backup.Models.ProtectedItemResource&gt; GetAsync(class Microsoft.Azure.Management.RecoveryServices.Backup.IProtectedItemsOperations operations, string vaultName, string resourceGroupName, string fabricName, string containerName, string protectedItemName, class Microsoft.Rest.Azure.OData.ODataQuery`1&lt;class Microsoft.Azure.Management.RecoveryServices.Backup.Models.GetProtectedItemQueryObject&gt; odataQuery, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.RecoveryServices.Backup.ProtectedItemsOperationsExtensions.GetAsync(Microsoft.Azure.Management.RecoveryServices.Backup.IProtectedItemsOperations,System.String,System.String,System.String,System.String,System.String,Microsoft.Rest.Azure.OData.ODataQuery{Microsoft.Azure.Management.RecoveryServices.Backup.Models.GetProtectedItemQueryObject},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetAsync : Microsoft.Azure.Management.RecoveryServices.Backup.IProtectedItemsOperations * string * string * string * string * string * Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.RecoveryServices.Backup.Models.GetProtectedItemQueryObject&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.RecoveryServices.Backup.Models.ProtectedItemResource&gt;" Usage="Microsoft.Azure.Management.RecoveryServices.Backup.ProtectedItemsOperationsExtensions.GetAsync (operations, vaultName, resourceGroupName, fabricName, containerName, protectedItemName, odataQuery, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.RecoveryServices.Backup.ProtectedItemsOperationsExtensions/&lt;GetAsync&gt;d__1))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.RecoveryServices.Backup.Models.ProtectedItemResource&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.RecoveryServices.Backup.IProtectedItemsOperations" RefType="this" />
        <Parameter Name="vaultName" Type="System.String" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="fabricName" Type="System.String" />
        <Parameter Name="containerName" Type="System.String" />
        <Parameter Name="protectedItemName" Type="System.String" />
        <Parameter Name="odataQuery" Type="Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.RecoveryServices.Backup.Models.GetProtectedItemQueryObject&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="a64cc-152">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="a64cc-152">The operations group for this extension method.</span></span>
            </param>
        <param name="vaultName">
            <span data-ttu-id="a64cc-153">Der Name des Recovery Services-Tresor.</span><span class="sxs-lookup"><span data-stu-id="a64cc-153">The name of the recovery services vault.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="a64cc-154">Der Name der Ressourcengruppe, in dem die Recovery-Tresor Services, ist vorhanden.</span><span class="sxs-lookup"><span data-stu-id="a64cc-154">The name of the resource group where the recovery services vault is present.</span></span>
            </param>
        <param name="fabricName">
            <span data-ttu-id="a64cc-155">Name des Fabric gesicherten Element zugeordnet.</span><span class="sxs-lookup"><span data-stu-id="a64cc-155">Fabric name associated with the backed up item.</span></span>
            </param>
        <param name="containerName">
            <span data-ttu-id="a64cc-156">Der Containername gesicherten Element zugeordnet.</span><span class="sxs-lookup"><span data-stu-id="a64cc-156">Container name associated with the backed up item.</span></span>
            </param>
        <param name="protectedItemName">
            <span data-ttu-id="a64cc-157">Gesichert, Name des Elements, dessen Details werden abgerufen werden sollen.</span><span class="sxs-lookup"><span data-stu-id="a64cc-157">Backed up item name whose details are to be fetched.</span></span>
            </param>
        <param name="odataQuery">
            <span data-ttu-id="a64cc-158">OData-Parameter des Vorgangs angewendet.</span><span class="sxs-lookup"><span data-stu-id="a64cc-158">OData parameters to apply to the operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="a64cc-159">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="a64cc-159">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="a64cc-160">Enthält die Details des gesicherten Elements.</span><span class="sxs-lookup"><span data-stu-id="a64cc-160">Provides the details of the backed up item.</span></span> <span data-ttu-id="a64cc-161">Das ist ein asynchroner Vorgang.</span><span class="sxs-lookup"><span data-stu-id="a64cc-161">This is an asynchronous operation.</span></span> <span data-ttu-id="a64cc-162">Um den Status des Vorgangs zu kennen, rufen Sie die GetItemOperationResult-API.</span><span class="sxs-lookup"><span data-stu-id="a64cc-162">To know the status of the operation, call the GetItemOperationResult API.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>