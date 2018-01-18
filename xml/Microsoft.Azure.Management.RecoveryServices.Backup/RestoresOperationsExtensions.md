<Type Name="RestoresOperationsExtensions" FullName="Microsoft.Azure.Management.RecoveryServices.Backup.RestoresOperationsExtensions">
  <TypeSignature Language="C#" Value="public static class RestoresOperationsExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit RestoresOperationsExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.RecoveryServices.Backup.RestoresOperationsExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module RestoresOperationsExtensions" />
  <TypeSignature Language="F#" Value="type RestoresOperationsExtensions = class" />
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
            <span data-ttu-id="699bc-101">Erweiterungsmethoden für RestoresOperations.</span><span class="sxs-lookup"><span data-stu-id="699bc-101">Extension methods for RestoresOperations.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="Trigger">
      <MemberSignature Language="C#" Value="public static void Trigger (this Microsoft.Azure.Management.RecoveryServices.Backup.IRestoresOperations operations, string vaultName, string resourceGroupName, string fabricName, string containerName, string protectedItemName, string recoveryPointId, Microsoft.Azure.Management.RecoveryServices.Backup.Models.RestoreRequestResource parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void Trigger(class Microsoft.Azure.Management.RecoveryServices.Backup.IRestoresOperations operations, string vaultName, string resourceGroupName, string fabricName, string containerName, string protectedItemName, string recoveryPointId, class Microsoft.Azure.Management.RecoveryServices.Backup.Models.RestoreRequestResource parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.RecoveryServices.Backup.RestoresOperationsExtensions.Trigger(Microsoft.Azure.Management.RecoveryServices.Backup.IRestoresOperations,System.String,System.String,System.String,System.String,System.String,System.String,Microsoft.Azure.Management.RecoveryServices.Backup.Models.RestoreRequestResource)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Sub Trigger (operations As IRestoresOperations, vaultName As String, resourceGroupName As String, fabricName As String, containerName As String, protectedItemName As String, recoveryPointId As String, parameters As RestoreRequestResource)" />
      <MemberSignature Language="F#" Value="static member Trigger : Microsoft.Azure.Management.RecoveryServices.Backup.IRestoresOperations * string * string * string * string * string * string * Microsoft.Azure.Management.RecoveryServices.Backup.Models.RestoreRequestResource -&gt; unit" Usage="Microsoft.Azure.Management.RecoveryServices.Backup.RestoresOperationsExtensions.Trigger (operations, vaultName, resourceGroupName, fabricName, containerName, protectedItemName, recoveryPointId, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.RecoveryServices.Backup.IRestoresOperations" RefType="this" />
        <Parameter Name="vaultName" Type="System.String" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="fabricName" Type="System.String" />
        <Parameter Name="containerName" Type="System.String" />
        <Parameter Name="protectedItemName" Type="System.String" />
        <Parameter Name="recoveryPointId" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.RecoveryServices.Backup.Models.RestoreRequestResource" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="699bc-102">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="699bc-102">The operations group for this extension method.</span></span>
            </param>
        <param name="vaultName">
            <span data-ttu-id="699bc-103">Der Name des Recovery Services-Tresor.</span><span class="sxs-lookup"><span data-stu-id="699bc-103">The name of the recovery services vault.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="699bc-104">Der Name der Ressourcengruppe, in dem die Recovery-Tresor Services, ist vorhanden.</span><span class="sxs-lookup"><span data-stu-id="699bc-104">The name of the resource group where the recovery services vault is present.</span></span>
            </param>
        <param name="fabricName">
            <span data-ttu-id="699bc-105">Name des Fabric gesicherten Elementen zugeordnet.</span><span class="sxs-lookup"><span data-stu-id="699bc-105">Fabric name associated with the backed up items.</span></span>
            </param>
        <param name="containerName">
            <span data-ttu-id="699bc-106">Der Containername gesicherten Elementen zugeordnet.</span><span class="sxs-lookup"><span data-stu-id="699bc-106">Container name associated with the backed up items.</span></span>
            </param>
        <param name="protectedItemName">
            <span data-ttu-id="699bc-107">Gesichert Element wiederhergestellt werden.</span><span class="sxs-lookup"><span data-stu-id="699bc-107">Backed up item to be restored.</span></span>
            </param>
        <param name="recoveryPointId">
            <span data-ttu-id="699bc-108">Die ID des Wiederherstellungspunkts dar die gesicherten Daten wiederhergestellt werden.</span><span class="sxs-lookup"><span data-stu-id="699bc-108">Recovery point ID which represents the backed up data to be restored.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="699bc-109">Anforderung zum Wiederherstellen von Ressourcen</span><span class="sxs-lookup"><span data-stu-id="699bc-109">resource restore request</span></span>
            </param>
        <summary>
            <span data-ttu-id="699bc-110">Stellt das angegebene gesicherte Daten.</span><span class="sxs-lookup"><span data-stu-id="699bc-110">Restores the specified backed up data.</span></span> <span data-ttu-id="699bc-111">Das ist ein asynchroner Vorgang.</span><span class="sxs-lookup"><span data-stu-id="699bc-111">This is an asynchronous operation.</span></span>
            <span data-ttu-id="699bc-112">Um den Status dieser API-Aufruf zu kennen, verwenden Sie GetProtectedItemOperationResult-API.</span><span class="sxs-lookup"><span data-stu-id="699bc-112">To know the status of this API call, use GetProtectedItemOperationResult API.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TriggerAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task TriggerAsync (this Microsoft.Azure.Management.RecoveryServices.Backup.IRestoresOperations operations, string vaultName, string resourceGroupName, string fabricName, string containerName, string protectedItemName, string recoveryPointId, Microsoft.Azure.Management.RecoveryServices.Backup.Models.RestoreRequestResource parameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task TriggerAsync(class Microsoft.Azure.Management.RecoveryServices.Backup.IRestoresOperations operations, string vaultName, string resourceGroupName, string fabricName, string containerName, string protectedItemName, string recoveryPointId, class Microsoft.Azure.Management.RecoveryServices.Backup.Models.RestoreRequestResource parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.RecoveryServices.Backup.RestoresOperationsExtensions.TriggerAsync(Microsoft.Azure.Management.RecoveryServices.Backup.IRestoresOperations,System.String,System.String,System.String,System.String,System.String,System.String,Microsoft.Azure.Management.RecoveryServices.Backup.Models.RestoreRequestResource,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member TriggerAsync : Microsoft.Azure.Management.RecoveryServices.Backup.IRestoresOperations * string * string * string * string * string * string * Microsoft.Azure.Management.RecoveryServices.Backup.Models.RestoreRequestResource * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.RecoveryServices.Backup.RestoresOperationsExtensions.TriggerAsync (operations, vaultName, resourceGroupName, fabricName, containerName, protectedItemName, recoveryPointId, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.RecoveryServices.Backup.RestoresOperationsExtensions/&lt;TriggerAsync&gt;d__1))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.RecoveryServices.Backup.IRestoresOperations" RefType="this" />
        <Parameter Name="vaultName" Type="System.String" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="fabricName" Type="System.String" />
        <Parameter Name="containerName" Type="System.String" />
        <Parameter Name="protectedItemName" Type="System.String" />
        <Parameter Name="recoveryPointId" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.RecoveryServices.Backup.Models.RestoreRequestResource" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="699bc-113">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="699bc-113">The operations group for this extension method.</span></span>
            </param>
        <param name="vaultName">
            <span data-ttu-id="699bc-114">Der Name des Recovery Services-Tresor.</span><span class="sxs-lookup"><span data-stu-id="699bc-114">The name of the recovery services vault.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="699bc-115">Der Name der Ressourcengruppe, in dem die Recovery-Tresor Services, ist vorhanden.</span><span class="sxs-lookup"><span data-stu-id="699bc-115">The name of the resource group where the recovery services vault is present.</span></span>
            </param>
        <param name="fabricName">
            <span data-ttu-id="699bc-116">Name des Fabric gesicherten Elementen zugeordnet.</span><span class="sxs-lookup"><span data-stu-id="699bc-116">Fabric name associated with the backed up items.</span></span>
            </param>
        <param name="containerName">
            <span data-ttu-id="699bc-117">Der Containername gesicherten Elementen zugeordnet.</span><span class="sxs-lookup"><span data-stu-id="699bc-117">Container name associated with the backed up items.</span></span>
            </param>
        <param name="protectedItemName">
            <span data-ttu-id="699bc-118">Gesichert Element wiederhergestellt werden.</span><span class="sxs-lookup"><span data-stu-id="699bc-118">Backed up item to be restored.</span></span>
            </param>
        <param name="recoveryPointId">
            <span data-ttu-id="699bc-119">Die ID des Wiederherstellungspunkts dar die gesicherten Daten wiederhergestellt werden.</span><span class="sxs-lookup"><span data-stu-id="699bc-119">Recovery point ID which represents the backed up data to be restored.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="699bc-120">Anforderung zum Wiederherstellen von Ressourcen</span><span class="sxs-lookup"><span data-stu-id="699bc-120">resource restore request</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="699bc-121">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="699bc-121">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="699bc-122">Stellt das angegebene gesicherte Daten.</span><span class="sxs-lookup"><span data-stu-id="699bc-122">Restores the specified backed up data.</span></span> <span data-ttu-id="699bc-123">Das ist ein asynchroner Vorgang.</span><span class="sxs-lookup"><span data-stu-id="699bc-123">This is an asynchronous operation.</span></span>
            <span data-ttu-id="699bc-124">Um den Status dieser API-Aufruf zu kennen, verwenden Sie GetProtectedItemOperationResult-API.</span><span class="sxs-lookup"><span data-stu-id="699bc-124">To know the status of this API call, use GetProtectedItemOperationResult API.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>