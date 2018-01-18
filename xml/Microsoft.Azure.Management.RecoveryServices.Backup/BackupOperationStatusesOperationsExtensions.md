<Type Name="BackupOperationStatusesOperationsExtensions" FullName="Microsoft.Azure.Management.RecoveryServices.Backup.BackupOperationStatusesOperationsExtensions">
  <TypeSignature Language="C#" Value="public static class BackupOperationStatusesOperationsExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit BackupOperationStatusesOperationsExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.RecoveryServices.Backup.BackupOperationStatusesOperationsExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module BackupOperationStatusesOperationsExtensions" />
  <TypeSignature Language="F#" Value="type BackupOperationStatusesOperationsExtensions = class" />
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
            <span data-ttu-id="2f9f5-101">Erweiterungsmethoden für BackupOperationStatusesOperations.</span><span class="sxs-lookup"><span data-stu-id="2f9f5-101">Extension methods for BackupOperationStatusesOperations.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="Get">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.RecoveryServices.Backup.Models.OperationStatus Get (this Microsoft.Azure.Management.RecoveryServices.Backup.IBackupOperationStatusesOperations operations, string vaultName, string resourceGroupName, string operationId);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.RecoveryServices.Backup.Models.OperationStatus Get(class Microsoft.Azure.Management.RecoveryServices.Backup.IBackupOperationStatusesOperations operations, string vaultName, string resourceGroupName, string operationId) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.RecoveryServices.Backup.BackupOperationStatusesOperationsExtensions.Get(Microsoft.Azure.Management.RecoveryServices.Backup.IBackupOperationStatusesOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function Get (operations As IBackupOperationStatusesOperations, vaultName As String, resourceGroupName As String, operationId As String) As OperationStatus" />
      <MemberSignature Language="F#" Value="static member Get : Microsoft.Azure.Management.RecoveryServices.Backup.IBackupOperationStatusesOperations * string * string * string -&gt; Microsoft.Azure.Management.RecoveryServices.Backup.Models.OperationStatus" Usage="Microsoft.Azure.Management.RecoveryServices.Backup.BackupOperationStatusesOperationsExtensions.Get (operations, vaultName, resourceGroupName, operationId)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.RecoveryServices.Backup.Models.OperationStatus</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.RecoveryServices.Backup.IBackupOperationStatusesOperations" RefType="this" />
        <Parameter Name="vaultName" Type="System.String" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="operationId" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="2f9f5-102">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="2f9f5-102">The operations group for this extension method.</span></span>
            </param>
        <param name="vaultName">
            <span data-ttu-id="2f9f5-103">Der Name des Recovery Services-Tresor.</span><span class="sxs-lookup"><span data-stu-id="2f9f5-103">The name of the recovery services vault.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="2f9f5-104">Der Name der Ressourcengruppe, in dem die Recovery-Tresor Services, ist vorhanden.</span><span class="sxs-lookup"><span data-stu-id="2f9f5-104">The name of the resource group where the recovery services vault is present.</span></span>
            </param>
        <param name="operationId">
            <span data-ttu-id="2f9f5-105">OperationID, der den Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="2f9f5-105">OperationID which represents the operation.</span></span>
            </param>
        <summary>
            <span data-ttu-id="2f9f5-106">Ruft den Status eines Vorgangs wie z. B. das Auslösen einer sicherungs wiederherstellen.</span><span class="sxs-lookup"><span data-stu-id="2f9f5-106">Fetches the status of an operation such as triggering a backup, restore.</span></span>
            <span data-ttu-id="2f9f5-107">Der Status kann in Bearbeitung, abgeschlossen oder fehlerhaft sein.</span><span class="sxs-lookup"><span data-stu-id="2f9f5-107">The status can be in progress, completed or failed.</span></span> <span data-ttu-id="2f9f5-108">Sie können die OperationStatus-Enumeration für alle möglichen Status eines Vorgangs verweisen.</span><span class="sxs-lookup"><span data-stu-id="2f9f5-108">You can refer to the OperationStatus enum for all the possible states of an operation.</span></span> <span data-ttu-id="2f9f5-109">Einige Vorgänge Aufträge erstellt werden.</span><span class="sxs-lookup"><span data-stu-id="2f9f5-109">Some operations create jobs.</span></span> <span data-ttu-id="2f9f5-110">Diese Methode gibt die Liste der Aufträge auf, wenn der Vorgang abgeschlossen ist.</span><span class="sxs-lookup"><span data-stu-id="2f9f5-110">This method returns the list of jobs when the operation is complete.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.RecoveryServices.Backup.Models.OperationStatus&gt; GetAsync (this Microsoft.Azure.Management.RecoveryServices.Backup.IBackupOperationStatusesOperations operations, string vaultName, string resourceGroupName, string operationId, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.RecoveryServices.Backup.Models.OperationStatus&gt; GetAsync(class Microsoft.Azure.Management.RecoveryServices.Backup.IBackupOperationStatusesOperations operations, string vaultName, string resourceGroupName, string operationId, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.RecoveryServices.Backup.BackupOperationStatusesOperationsExtensions.GetAsync(Microsoft.Azure.Management.RecoveryServices.Backup.IBackupOperationStatusesOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetAsync : Microsoft.Azure.Management.RecoveryServices.Backup.IBackupOperationStatusesOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.RecoveryServices.Backup.Models.OperationStatus&gt;" Usage="Microsoft.Azure.Management.RecoveryServices.Backup.BackupOperationStatusesOperationsExtensions.GetAsync (operations, vaultName, resourceGroupName, operationId, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.RecoveryServices.Backup.BackupOperationStatusesOperationsExtensions/&lt;GetAsync&gt;d__1))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.RecoveryServices.Backup.Models.OperationStatus&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.RecoveryServices.Backup.IBackupOperationStatusesOperations" RefType="this" />
        <Parameter Name="vaultName" Type="System.String" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="operationId" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="2f9f5-111">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="2f9f5-111">The operations group for this extension method.</span></span>
            </param>
        <param name="vaultName">
            <span data-ttu-id="2f9f5-112">Der Name des Recovery Services-Tresor.</span><span class="sxs-lookup"><span data-stu-id="2f9f5-112">The name of the recovery services vault.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="2f9f5-113">Der Name der Ressourcengruppe, in dem die Recovery-Tresor Services, ist vorhanden.</span><span class="sxs-lookup"><span data-stu-id="2f9f5-113">The name of the resource group where the recovery services vault is present.</span></span>
            </param>
        <param name="operationId">
            <span data-ttu-id="2f9f5-114">OperationID, der den Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="2f9f5-114">OperationID which represents the operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="2f9f5-115">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="2f9f5-115">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="2f9f5-116">Ruft den Status eines Vorgangs wie z. B. das Auslösen einer sicherungs wiederherstellen.</span><span class="sxs-lookup"><span data-stu-id="2f9f5-116">Fetches the status of an operation such as triggering a backup, restore.</span></span>
            <span data-ttu-id="2f9f5-117">Der Status kann in Bearbeitung, abgeschlossen oder fehlerhaft sein.</span><span class="sxs-lookup"><span data-stu-id="2f9f5-117">The status can be in progress, completed or failed.</span></span> <span data-ttu-id="2f9f5-118">Sie können die OperationStatus-Enumeration für alle möglichen Status eines Vorgangs verweisen.</span><span class="sxs-lookup"><span data-stu-id="2f9f5-118">You can refer to the OperationStatus enum for all the possible states of an operation.</span></span> <span data-ttu-id="2f9f5-119">Einige Vorgänge Aufträge erstellt werden.</span><span class="sxs-lookup"><span data-stu-id="2f9f5-119">Some operations create jobs.</span></span> <span data-ttu-id="2f9f5-120">Diese Methode gibt die Liste der Aufträge auf, wenn der Vorgang abgeschlossen ist.</span><span class="sxs-lookup"><span data-stu-id="2f9f5-120">This method returns the list of jobs when the operation is complete.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>