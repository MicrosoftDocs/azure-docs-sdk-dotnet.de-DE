<Type Name="BackupsOperationsExtensions" FullName="Microsoft.Azure.Management.RecoveryServices.Backup.BackupsOperationsExtensions">
  <TypeSignature Language="C#" Value="public static class BackupsOperationsExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit BackupsOperationsExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.RecoveryServices.Backup.BackupsOperationsExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module BackupsOperationsExtensions" />
  <TypeSignature Language="F#" Value="type BackupsOperationsExtensions = class" />
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
            <span data-ttu-id="df2a1-101">Erweiterungsmethoden für BackupsOperations.</span><span class="sxs-lookup"><span data-stu-id="df2a1-101">Extension methods for BackupsOperations.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="Trigger">
      <MemberSignature Language="C#" Value="public static void Trigger (this Microsoft.Azure.Management.RecoveryServices.Backup.IBackupsOperations operations, string vaultName, string resourceGroupName, string fabricName, string containerName, string protectedItemName, Microsoft.Azure.Management.RecoveryServices.Backup.Models.BackupRequestResource parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void Trigger(class Microsoft.Azure.Management.RecoveryServices.Backup.IBackupsOperations operations, string vaultName, string resourceGroupName, string fabricName, string containerName, string protectedItemName, class Microsoft.Azure.Management.RecoveryServices.Backup.Models.BackupRequestResource parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.RecoveryServices.Backup.BackupsOperationsExtensions.Trigger(Microsoft.Azure.Management.RecoveryServices.Backup.IBackupsOperations,System.String,System.String,System.String,System.String,System.String,Microsoft.Azure.Management.RecoveryServices.Backup.Models.BackupRequestResource)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Sub Trigger (operations As IBackupsOperations, vaultName As String, resourceGroupName As String, fabricName As String, containerName As String, protectedItemName As String, parameters As BackupRequestResource)" />
      <MemberSignature Language="F#" Value="static member Trigger : Microsoft.Azure.Management.RecoveryServices.Backup.IBackupsOperations * string * string * string * string * string * Microsoft.Azure.Management.RecoveryServices.Backup.Models.BackupRequestResource -&gt; unit" Usage="Microsoft.Azure.Management.RecoveryServices.Backup.BackupsOperationsExtensions.Trigger (operations, vaultName, resourceGroupName, fabricName, containerName, protectedItemName, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.RecoveryServices.Backup.IBackupsOperations" RefType="this" />
        <Parameter Name="vaultName" Type="System.String" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="fabricName" Type="System.String" />
        <Parameter Name="containerName" Type="System.String" />
        <Parameter Name="protectedItemName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.RecoveryServices.Backup.Models.BackupRequestResource" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="df2a1-102">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="df2a1-102">The operations group for this extension method.</span></span>
            </param>
        <param name="vaultName">
            <span data-ttu-id="df2a1-103">Der Name des Recovery Services-Tresor.</span><span class="sxs-lookup"><span data-stu-id="df2a1-103">The name of the recovery services vault.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="df2a1-104">Der Name der Ressourcengruppe, in dem die Recovery-Tresor Services, ist vorhanden.</span><span class="sxs-lookup"><span data-stu-id="df2a1-104">The name of the resource group where the recovery services vault is present.</span></span>
            </param>
        <param name="fabricName">
            <span data-ttu-id="df2a1-105">Name des Fabric, das Sichern des Elements zugeordnet.</span><span class="sxs-lookup"><span data-stu-id="df2a1-105">Fabric name associated with the backup item.</span></span>
            </param>
        <param name="containerName">
            <span data-ttu-id="df2a1-106">Der Containername das Sichern des Elements zugeordnet.</span><span class="sxs-lookup"><span data-stu-id="df2a1-106">Container name associated with the backup item.</span></span>
            </param>
        <param name="protectedItemName">
            <span data-ttu-id="df2a1-107">Sichern des Elements für die sicherungsanforderungen ausgelöst werden soll.</span><span class="sxs-lookup"><span data-stu-id="df2a1-107">Backup item for which backup needs to be triggered.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="df2a1-108">Anforderung für die Sicherung der Ressource</span><span class="sxs-lookup"><span data-stu-id="df2a1-108">resource backup request</span></span>
            </param>
        <summary>
            <span data-ttu-id="df2a1-109">Trigger-Sicherung für das angegebene Element gesichert werden.</span><span class="sxs-lookup"><span data-stu-id="df2a1-109">Triggers backup for specified backed up item.</span></span> <span data-ttu-id="df2a1-110">Das ist ein asynchroner Vorgang.</span><span class="sxs-lookup"><span data-stu-id="df2a1-110">This is an asynchronous operation.</span></span> <span data-ttu-id="df2a1-111">Rufen Sie GetProtectedItemOperationResult-API auf, um den Status des Vorgangs zu kennen.</span><span class="sxs-lookup"><span data-stu-id="df2a1-111">To know the status of the operation, call GetProtectedItemOperationResult API.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TriggerAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task TriggerAsync (this Microsoft.Azure.Management.RecoveryServices.Backup.IBackupsOperations operations, string vaultName, string resourceGroupName, string fabricName, string containerName, string protectedItemName, Microsoft.Azure.Management.RecoveryServices.Backup.Models.BackupRequestResource parameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task TriggerAsync(class Microsoft.Azure.Management.RecoveryServices.Backup.IBackupsOperations operations, string vaultName, string resourceGroupName, string fabricName, string containerName, string protectedItemName, class Microsoft.Azure.Management.RecoveryServices.Backup.Models.BackupRequestResource parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.RecoveryServices.Backup.BackupsOperationsExtensions.TriggerAsync(Microsoft.Azure.Management.RecoveryServices.Backup.IBackupsOperations,System.String,System.String,System.String,System.String,System.String,Microsoft.Azure.Management.RecoveryServices.Backup.Models.BackupRequestResource,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member TriggerAsync : Microsoft.Azure.Management.RecoveryServices.Backup.IBackupsOperations * string * string * string * string * string * Microsoft.Azure.Management.RecoveryServices.Backup.Models.BackupRequestResource * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.RecoveryServices.Backup.BackupsOperationsExtensions.TriggerAsync (operations, vaultName, resourceGroupName, fabricName, containerName, protectedItemName, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.RecoveryServices.Backup.BackupsOperationsExtensions/&lt;TriggerAsync&gt;d__1))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.RecoveryServices.Backup.IBackupsOperations" RefType="this" />
        <Parameter Name="vaultName" Type="System.String" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="fabricName" Type="System.String" />
        <Parameter Name="containerName" Type="System.String" />
        <Parameter Name="protectedItemName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.RecoveryServices.Backup.Models.BackupRequestResource" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="df2a1-112">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="df2a1-112">The operations group for this extension method.</span></span>
            </param>
        <param name="vaultName">
            <span data-ttu-id="df2a1-113">Der Name des Recovery Services-Tresor.</span><span class="sxs-lookup"><span data-stu-id="df2a1-113">The name of the recovery services vault.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="df2a1-114">Der Name der Ressourcengruppe, in dem die Recovery-Tresor Services, ist vorhanden.</span><span class="sxs-lookup"><span data-stu-id="df2a1-114">The name of the resource group where the recovery services vault is present.</span></span>
            </param>
        <param name="fabricName">
            <span data-ttu-id="df2a1-115">Name des Fabric, das Sichern des Elements zugeordnet.</span><span class="sxs-lookup"><span data-stu-id="df2a1-115">Fabric name associated with the backup item.</span></span>
            </param>
        <param name="containerName">
            <span data-ttu-id="df2a1-116">Der Containername das Sichern des Elements zugeordnet.</span><span class="sxs-lookup"><span data-stu-id="df2a1-116">Container name associated with the backup item.</span></span>
            </param>
        <param name="protectedItemName">
            <span data-ttu-id="df2a1-117">Sichern des Elements für die sicherungsanforderungen ausgelöst werden soll.</span><span class="sxs-lookup"><span data-stu-id="df2a1-117">Backup item for which backup needs to be triggered.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="df2a1-118">Anforderung für die Sicherung der Ressource</span><span class="sxs-lookup"><span data-stu-id="df2a1-118">resource backup request</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="df2a1-119">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="df2a1-119">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="df2a1-120">Trigger-Sicherung für das angegebene Element gesichert werden.</span><span class="sxs-lookup"><span data-stu-id="df2a1-120">Triggers backup for specified backed up item.</span></span> <span data-ttu-id="df2a1-121">Das ist ein asynchroner Vorgang.</span><span class="sxs-lookup"><span data-stu-id="df2a1-121">This is an asynchronous operation.</span></span> <span data-ttu-id="df2a1-122">Rufen Sie GetProtectedItemOperationResult-API auf, um den Status des Vorgangs zu kennen.</span><span class="sxs-lookup"><span data-stu-id="df2a1-122">To know the status of the operation, call GetProtectedItemOperationResult API.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>