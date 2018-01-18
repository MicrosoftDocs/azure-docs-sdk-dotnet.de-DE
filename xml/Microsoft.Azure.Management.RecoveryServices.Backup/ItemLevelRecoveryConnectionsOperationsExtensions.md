<Type Name="ItemLevelRecoveryConnectionsOperationsExtensions" FullName="Microsoft.Azure.Management.RecoveryServices.Backup.ItemLevelRecoveryConnectionsOperationsExtensions">
  <TypeSignature Language="C#" Value="public static class ItemLevelRecoveryConnectionsOperationsExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit ItemLevelRecoveryConnectionsOperationsExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.RecoveryServices.Backup.ItemLevelRecoveryConnectionsOperationsExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module ItemLevelRecoveryConnectionsOperationsExtensions" />
  <TypeSignature Language="F#" Value="type ItemLevelRecoveryConnectionsOperationsExtensions = class" />
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
            <span data-ttu-id="e7a3f-101">Erweiterungsmethoden für ItemLevelRecoveryConnectionsOperations.</span><span class="sxs-lookup"><span data-stu-id="e7a3f-101">Extension methods for ItemLevelRecoveryConnectionsOperations.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="Provision">
      <MemberSignature Language="C#" Value="public static void Provision (this Microsoft.Azure.Management.RecoveryServices.Backup.IItemLevelRecoveryConnectionsOperations operations, string vaultName, string resourceGroupName, string fabricName, string containerName, string protectedItemName, string recoveryPointId, Microsoft.Azure.Management.RecoveryServices.Backup.Models.ILRRequestResource parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void Provision(class Microsoft.Azure.Management.RecoveryServices.Backup.IItemLevelRecoveryConnectionsOperations operations, string vaultName, string resourceGroupName, string fabricName, string containerName, string protectedItemName, string recoveryPointId, class Microsoft.Azure.Management.RecoveryServices.Backup.Models.ILRRequestResource parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.RecoveryServices.Backup.ItemLevelRecoveryConnectionsOperationsExtensions.Provision(Microsoft.Azure.Management.RecoveryServices.Backup.IItemLevelRecoveryConnectionsOperations,System.String,System.String,System.String,System.String,System.String,System.String,Microsoft.Azure.Management.RecoveryServices.Backup.Models.ILRRequestResource)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Sub Provision (operations As IItemLevelRecoveryConnectionsOperations, vaultName As String, resourceGroupName As String, fabricName As String, containerName As String, protectedItemName As String, recoveryPointId As String, parameters As ILRRequestResource)" />
      <MemberSignature Language="F#" Value="static member Provision : Microsoft.Azure.Management.RecoveryServices.Backup.IItemLevelRecoveryConnectionsOperations * string * string * string * string * string * string * Microsoft.Azure.Management.RecoveryServices.Backup.Models.ILRRequestResource -&gt; unit" Usage="Microsoft.Azure.Management.RecoveryServices.Backup.ItemLevelRecoveryConnectionsOperationsExtensions.Provision (operations, vaultName, resourceGroupName, fabricName, containerName, protectedItemName, recoveryPointId, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.RecoveryServices.Backup.IItemLevelRecoveryConnectionsOperations" RefType="this" />
        <Parameter Name="vaultName" Type="System.String" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="fabricName" Type="System.String" />
        <Parameter Name="containerName" Type="System.String" />
        <Parameter Name="protectedItemName" Type="System.String" />
        <Parameter Name="recoveryPointId" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.RecoveryServices.Backup.Models.ILRRequestResource" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="e7a3f-102">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="e7a3f-102">The operations group for this extension method.</span></span>
            </param>
        <param name="vaultName">
            <span data-ttu-id="e7a3f-103">Der Name des Recovery Services-Tresor.</span><span class="sxs-lookup"><span data-stu-id="e7a3f-103">The name of the recovery services vault.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="e7a3f-104">Der Name der Ressourcengruppe, in dem die Recovery-Tresor Services, ist vorhanden.</span><span class="sxs-lookup"><span data-stu-id="e7a3f-104">The name of the resource group where the recovery services vault is present.</span></span>
            </param>
        <param name="fabricName">
            <span data-ttu-id="e7a3f-105">Name des Fabric gesicherten Elementen zugeordnet.</span><span class="sxs-lookup"><span data-stu-id="e7a3f-105">Fabric name associated with the backed up items.</span></span>
            </param>
        <param name="containerName">
            <span data-ttu-id="e7a3f-106">Der Containername gesicherten Elementen zugeordnet.</span><span class="sxs-lookup"><span data-stu-id="e7a3f-106">Container name associated with the backed up items.</span></span>
            </param>
        <param name="protectedItemName">
            <span data-ttu-id="e7a3f-107">Gesichert Elementname, deren Dateien bzw. Ordner wiederhergestellt werden sollen.</span><span class="sxs-lookup"><span data-stu-id="e7a3f-107">Backed up item name whose files/folders are to be restored.</span></span>
            </param>
        <param name="recoveryPointId">
            <span data-ttu-id="e7a3f-108">Die ID des Wiederherstellungspunkts die gesicherte Daten darstellt.</span><span class="sxs-lookup"><span data-stu-id="e7a3f-108">Recovery point ID which represents backed up data.</span></span> <span data-ttu-id="e7a3f-109">iSCSI-Verbindung wird für diese gesicherten Daten bereitgestellt werden.</span><span class="sxs-lookup"><span data-stu-id="e7a3f-109">iSCSI connection will be provisioned for this backed up data.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="e7a3f-110">Wiederherstellung auf Elementebene ressourcenanforderung</span><span class="sxs-lookup"><span data-stu-id="e7a3f-110">resource ILR request</span></span>
            </param>
        <summary>
            <span data-ttu-id="e7a3f-111">Stellt ein Skript, das eine iSCSI-Verbindung die zu sichernden Daten aufruft.</span><span class="sxs-lookup"><span data-stu-id="e7a3f-111">Provisions a script which invokes an iSCSI connection to the backup data.</span></span>
            <span data-ttu-id="e7a3f-112">Dieses Skript ausgeführt, wird einen Datei-Explorer Anzeigen der wiederherstellbaren Dateien und Ordner geöffnet.</span><span class="sxs-lookup"><span data-stu-id="e7a3f-112">Executing this script opens a file explorer displaying all the recoverable files and folders.</span></span> <span data-ttu-id="e7a3f-113">Das ist ein asynchroner Vorgang.</span><span class="sxs-lookup"><span data-stu-id="e7a3f-113">This is an asynchronous operation.</span></span> <span data-ttu-id="e7a3f-114">Rufen Sie GetProtectedItemOperationResult-API auf, um den Status der Bereitstellung zu kennen.</span><span class="sxs-lookup"><span data-stu-id="e7a3f-114">To know the status of provisioning, call GetProtectedItemOperationResult API.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ProvisionAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task ProvisionAsync (this Microsoft.Azure.Management.RecoveryServices.Backup.IItemLevelRecoveryConnectionsOperations operations, string vaultName, string resourceGroupName, string fabricName, string containerName, string protectedItemName, string recoveryPointId, Microsoft.Azure.Management.RecoveryServices.Backup.Models.ILRRequestResource parameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task ProvisionAsync(class Microsoft.Azure.Management.RecoveryServices.Backup.IItemLevelRecoveryConnectionsOperations operations, string vaultName, string resourceGroupName, string fabricName, string containerName, string protectedItemName, string recoveryPointId, class Microsoft.Azure.Management.RecoveryServices.Backup.Models.ILRRequestResource parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.RecoveryServices.Backup.ItemLevelRecoveryConnectionsOperationsExtensions.ProvisionAsync(Microsoft.Azure.Management.RecoveryServices.Backup.IItemLevelRecoveryConnectionsOperations,System.String,System.String,System.String,System.String,System.String,System.String,Microsoft.Azure.Management.RecoveryServices.Backup.Models.ILRRequestResource,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ProvisionAsync : Microsoft.Azure.Management.RecoveryServices.Backup.IItemLevelRecoveryConnectionsOperations * string * string * string * string * string * string * Microsoft.Azure.Management.RecoveryServices.Backup.Models.ILRRequestResource * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.RecoveryServices.Backup.ItemLevelRecoveryConnectionsOperationsExtensions.ProvisionAsync (operations, vaultName, resourceGroupName, fabricName, containerName, protectedItemName, recoveryPointId, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.RecoveryServices.Backup.ItemLevelRecoveryConnectionsOperationsExtensions/&lt;ProvisionAsync&gt;d__1))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.RecoveryServices.Backup.IItemLevelRecoveryConnectionsOperations" RefType="this" />
        <Parameter Name="vaultName" Type="System.String" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="fabricName" Type="System.String" />
        <Parameter Name="containerName" Type="System.String" />
        <Parameter Name="protectedItemName" Type="System.String" />
        <Parameter Name="recoveryPointId" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.RecoveryServices.Backup.Models.ILRRequestResource" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="e7a3f-115">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="e7a3f-115">The operations group for this extension method.</span></span>
            </param>
        <param name="vaultName">
            <span data-ttu-id="e7a3f-116">Der Name des Recovery Services-Tresor.</span><span class="sxs-lookup"><span data-stu-id="e7a3f-116">The name of the recovery services vault.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="e7a3f-117">Der Name der Ressourcengruppe, in dem die Recovery-Tresor Services, ist vorhanden.</span><span class="sxs-lookup"><span data-stu-id="e7a3f-117">The name of the resource group where the recovery services vault is present.</span></span>
            </param>
        <param name="fabricName">
            <span data-ttu-id="e7a3f-118">Name des Fabric gesicherten Elementen zugeordnet.</span><span class="sxs-lookup"><span data-stu-id="e7a3f-118">Fabric name associated with the backed up items.</span></span>
            </param>
        <param name="containerName">
            <span data-ttu-id="e7a3f-119">Der Containername gesicherten Elementen zugeordnet.</span><span class="sxs-lookup"><span data-stu-id="e7a3f-119">Container name associated with the backed up items.</span></span>
            </param>
        <param name="protectedItemName">
            <span data-ttu-id="e7a3f-120">Gesichert Elementname, deren Dateien bzw. Ordner wiederhergestellt werden sollen.</span><span class="sxs-lookup"><span data-stu-id="e7a3f-120">Backed up item name whose files/folders are to be restored.</span></span>
            </param>
        <param name="recoveryPointId">
            <span data-ttu-id="e7a3f-121">Die ID des Wiederherstellungspunkts die gesicherte Daten darstellt.</span><span class="sxs-lookup"><span data-stu-id="e7a3f-121">Recovery point ID which represents backed up data.</span></span> <span data-ttu-id="e7a3f-122">iSCSI-Verbindung wird für diese gesicherten Daten bereitgestellt werden.</span><span class="sxs-lookup"><span data-stu-id="e7a3f-122">iSCSI connection will be provisioned for this backed up data.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="e7a3f-123">Wiederherstellung auf Elementebene ressourcenanforderung</span><span class="sxs-lookup"><span data-stu-id="e7a3f-123">resource ILR request</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="e7a3f-124">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="e7a3f-124">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="e7a3f-125">Stellt ein Skript, das eine iSCSI-Verbindung die zu sichernden Daten aufruft.</span><span class="sxs-lookup"><span data-stu-id="e7a3f-125">Provisions a script which invokes an iSCSI connection to the backup data.</span></span>
            <span data-ttu-id="e7a3f-126">Dieses Skript ausgeführt, wird einen Datei-Explorer Anzeigen der wiederherstellbaren Dateien und Ordner geöffnet.</span><span class="sxs-lookup"><span data-stu-id="e7a3f-126">Executing this script opens a file explorer displaying all the recoverable files and folders.</span></span> <span data-ttu-id="e7a3f-127">Das ist ein asynchroner Vorgang.</span><span class="sxs-lookup"><span data-stu-id="e7a3f-127">This is an asynchronous operation.</span></span> <span data-ttu-id="e7a3f-128">Rufen Sie GetProtectedItemOperationResult-API auf, um den Status der Bereitstellung zu kennen.</span><span class="sxs-lookup"><span data-stu-id="e7a3f-128">To know the status of provisioning, call GetProtectedItemOperationResult API.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Revoke">
      <MemberSignature Language="C#" Value="public static void Revoke (this Microsoft.Azure.Management.RecoveryServices.Backup.IItemLevelRecoveryConnectionsOperations operations, string vaultName, string resourceGroupName, string fabricName, string containerName, string protectedItemName, string recoveryPointId);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void Revoke(class Microsoft.Azure.Management.RecoveryServices.Backup.IItemLevelRecoveryConnectionsOperations operations, string vaultName, string resourceGroupName, string fabricName, string containerName, string protectedItemName, string recoveryPointId) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.RecoveryServices.Backup.ItemLevelRecoveryConnectionsOperationsExtensions.Revoke(Microsoft.Azure.Management.RecoveryServices.Backup.IItemLevelRecoveryConnectionsOperations,System.String,System.String,System.String,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Sub Revoke (operations As IItemLevelRecoveryConnectionsOperations, vaultName As String, resourceGroupName As String, fabricName As String, containerName As String, protectedItemName As String, recoveryPointId As String)" />
      <MemberSignature Language="F#" Value="static member Revoke : Microsoft.Azure.Management.RecoveryServices.Backup.IItemLevelRecoveryConnectionsOperations * string * string * string * string * string * string -&gt; unit" Usage="Microsoft.Azure.Management.RecoveryServices.Backup.ItemLevelRecoveryConnectionsOperationsExtensions.Revoke (operations, vaultName, resourceGroupName, fabricName, containerName, protectedItemName, recoveryPointId)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.RecoveryServices.Backup.IItemLevelRecoveryConnectionsOperations" RefType="this" />
        <Parameter Name="vaultName" Type="System.String" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="fabricName" Type="System.String" />
        <Parameter Name="containerName" Type="System.String" />
        <Parameter Name="protectedItemName" Type="System.String" />
        <Parameter Name="recoveryPointId" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="e7a3f-129">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="e7a3f-129">The operations group for this extension method.</span></span>
            </param>
        <param name="vaultName">
            <span data-ttu-id="e7a3f-130">Der Name des Recovery Services-Tresor.</span><span class="sxs-lookup"><span data-stu-id="e7a3f-130">The name of the recovery services vault.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="e7a3f-131">Der Name der Ressourcengruppe, in dem die Recovery-Tresor Services, ist vorhanden.</span><span class="sxs-lookup"><span data-stu-id="e7a3f-131">The name of the resource group where the recovery services vault is present.</span></span>
            </param>
        <param name="fabricName">
            <span data-ttu-id="e7a3f-132">Name des Fabric gesicherten Elementen zugeordnet.</span><span class="sxs-lookup"><span data-stu-id="e7a3f-132">Fabric name associated with the backed up items.</span></span>
            </param>
        <param name="containerName">
            <span data-ttu-id="e7a3f-133">Der Containername gesicherten Elementen zugeordnet.</span><span class="sxs-lookup"><span data-stu-id="e7a3f-133">Container name associated with the backed up items.</span></span>
            </param>
        <param name="protectedItemName">
            <span data-ttu-id="e7a3f-134">Gesichert Elementname, deren Dateien bzw. Ordner wiederhergestellt werden sollen.</span><span class="sxs-lookup"><span data-stu-id="e7a3f-134">Backed up item name whose files/folders are to be restored.</span></span>
            </param>
        <param name="recoveryPointId">
            <span data-ttu-id="e7a3f-135">Die ID des Wiederherstellungspunkts die gesicherte Daten darstellt.</span><span class="sxs-lookup"><span data-stu-id="e7a3f-135">Recovery point ID which represents backed up data.</span></span> <span data-ttu-id="e7a3f-136">iSCSI-Verbindung wird für diese gesicherten Daten aufgehoben.</span><span class="sxs-lookup"><span data-stu-id="e7a3f-136">iSCSI connection will be revoked for this backed up data.</span></span>
            </param>
        <summary>
            <span data-ttu-id="e7a3f-137">Widerruft eine iSCSI-Verbindung die verwendet werden kann, um ein Skript herunterladen.</span><span class="sxs-lookup"><span data-stu-id="e7a3f-137">Revokes an iSCSI connection which can be used to download a script.</span></span>
            <span data-ttu-id="e7a3f-138">Dieses Skript ausgeführt, öffnet einen Datei-Explorer alle wiederherstellbaren Dateien und Ordner anzeigen.</span><span class="sxs-lookup"><span data-stu-id="e7a3f-138">Executing this script opens a file explorer displaying all recoverable files and folders.</span></span> <span data-ttu-id="e7a3f-139">Das ist ein asynchroner Vorgang.</span><span class="sxs-lookup"><span data-stu-id="e7a3f-139">This is an asynchronous operation.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RevokeAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task RevokeAsync (this Microsoft.Azure.Management.RecoveryServices.Backup.IItemLevelRecoveryConnectionsOperations operations, string vaultName, string resourceGroupName, string fabricName, string containerName, string protectedItemName, string recoveryPointId, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task RevokeAsync(class Microsoft.Azure.Management.RecoveryServices.Backup.IItemLevelRecoveryConnectionsOperations operations, string vaultName, string resourceGroupName, string fabricName, string containerName, string protectedItemName, string recoveryPointId, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.RecoveryServices.Backup.ItemLevelRecoveryConnectionsOperationsExtensions.RevokeAsync(Microsoft.Azure.Management.RecoveryServices.Backup.IItemLevelRecoveryConnectionsOperations,System.String,System.String,System.String,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member RevokeAsync : Microsoft.Azure.Management.RecoveryServices.Backup.IItemLevelRecoveryConnectionsOperations * string * string * string * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.RecoveryServices.Backup.ItemLevelRecoveryConnectionsOperationsExtensions.RevokeAsync (operations, vaultName, resourceGroupName, fabricName, containerName, protectedItemName, recoveryPointId, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.RecoveryServices.Backup.ItemLevelRecoveryConnectionsOperationsExtensions/&lt;RevokeAsync&gt;d__3))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.RecoveryServices.Backup.IItemLevelRecoveryConnectionsOperations" RefType="this" />
        <Parameter Name="vaultName" Type="System.String" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="fabricName" Type="System.String" />
        <Parameter Name="containerName" Type="System.String" />
        <Parameter Name="protectedItemName" Type="System.String" />
        <Parameter Name="recoveryPointId" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="e7a3f-140">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="e7a3f-140">The operations group for this extension method.</span></span>
            </param>
        <param name="vaultName">
            <span data-ttu-id="e7a3f-141">Der Name des Recovery Services-Tresor.</span><span class="sxs-lookup"><span data-stu-id="e7a3f-141">The name of the recovery services vault.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="e7a3f-142">Der Name der Ressourcengruppe, in dem die Recovery-Tresor Services, ist vorhanden.</span><span class="sxs-lookup"><span data-stu-id="e7a3f-142">The name of the resource group where the recovery services vault is present.</span></span>
            </param>
        <param name="fabricName">
            <span data-ttu-id="e7a3f-143">Name des Fabric gesicherten Elementen zugeordnet.</span><span class="sxs-lookup"><span data-stu-id="e7a3f-143">Fabric name associated with the backed up items.</span></span>
            </param>
        <param name="containerName">
            <span data-ttu-id="e7a3f-144">Der Containername gesicherten Elementen zugeordnet.</span><span class="sxs-lookup"><span data-stu-id="e7a3f-144">Container name associated with the backed up items.</span></span>
            </param>
        <param name="protectedItemName">
            <span data-ttu-id="e7a3f-145">Gesichert Elementname, deren Dateien bzw. Ordner wiederhergestellt werden sollen.</span><span class="sxs-lookup"><span data-stu-id="e7a3f-145">Backed up item name whose files/folders are to be restored.</span></span>
            </param>
        <param name="recoveryPointId">
            <span data-ttu-id="e7a3f-146">Die ID des Wiederherstellungspunkts die gesicherte Daten darstellt.</span><span class="sxs-lookup"><span data-stu-id="e7a3f-146">Recovery point ID which represents backed up data.</span></span> <span data-ttu-id="e7a3f-147">iSCSI-Verbindung wird für diese gesicherten Daten aufgehoben.</span><span class="sxs-lookup"><span data-stu-id="e7a3f-147">iSCSI connection will be revoked for this backed up data.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="e7a3f-148">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="e7a3f-148">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="e7a3f-149">Widerruft eine iSCSI-Verbindung die verwendet werden kann, um ein Skript herunterladen.</span><span class="sxs-lookup"><span data-stu-id="e7a3f-149">Revokes an iSCSI connection which can be used to download a script.</span></span>
            <span data-ttu-id="e7a3f-150">Dieses Skript ausgeführt, öffnet einen Datei-Explorer alle wiederherstellbaren Dateien und Ordner anzeigen.</span><span class="sxs-lookup"><span data-stu-id="e7a3f-150">Executing this script opens a file explorer displaying all recoverable files and folders.</span></span> <span data-ttu-id="e7a3f-151">Das ist ein asynchroner Vorgang.</span><span class="sxs-lookup"><span data-stu-id="e7a3f-151">This is an asynchronous operation.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>