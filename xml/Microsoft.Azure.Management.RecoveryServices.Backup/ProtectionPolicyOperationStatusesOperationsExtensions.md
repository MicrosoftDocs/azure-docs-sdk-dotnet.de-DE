<Type Name="ProtectionPolicyOperationStatusesOperationsExtensions" FullName="Microsoft.Azure.Management.RecoveryServices.Backup.ProtectionPolicyOperationStatusesOperationsExtensions">
  <TypeSignature Language="C#" Value="public static class ProtectionPolicyOperationStatusesOperationsExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit ProtectionPolicyOperationStatusesOperationsExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.RecoveryServices.Backup.ProtectionPolicyOperationStatusesOperationsExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module ProtectionPolicyOperationStatusesOperationsExtensions" />
  <TypeSignature Language="F#" Value="type ProtectionPolicyOperationStatusesOperationsExtensions = class" />
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
            <span data-ttu-id="20592-101">Erweiterungsmethoden für ProtectionPolicyOperationStatusesOperations.</span><span class="sxs-lookup"><span data-stu-id="20592-101">Extension methods for ProtectionPolicyOperationStatusesOperations.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="Get">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.RecoveryServices.Backup.Models.OperationStatus Get (this Microsoft.Azure.Management.RecoveryServices.Backup.IProtectionPolicyOperationStatusesOperations operations, string vaultName, string resourceGroupName, string policyName, string operationId);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.RecoveryServices.Backup.Models.OperationStatus Get(class Microsoft.Azure.Management.RecoveryServices.Backup.IProtectionPolicyOperationStatusesOperations operations, string vaultName, string resourceGroupName, string policyName, string operationId) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.RecoveryServices.Backup.ProtectionPolicyOperationStatusesOperationsExtensions.Get(Microsoft.Azure.Management.RecoveryServices.Backup.IProtectionPolicyOperationStatusesOperations,System.String,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function Get (operations As IProtectionPolicyOperationStatusesOperations, vaultName As String, resourceGroupName As String, policyName As String, operationId As String) As OperationStatus" />
      <MemberSignature Language="F#" Value="static member Get : Microsoft.Azure.Management.RecoveryServices.Backup.IProtectionPolicyOperationStatusesOperations * string * string * string * string -&gt; Microsoft.Azure.Management.RecoveryServices.Backup.Models.OperationStatus" Usage="Microsoft.Azure.Management.RecoveryServices.Backup.ProtectionPolicyOperationStatusesOperationsExtensions.Get (operations, vaultName, resourceGroupName, policyName, operationId)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.RecoveryServices.Backup.Models.OperationStatus</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.RecoveryServices.Backup.IProtectionPolicyOperationStatusesOperations" RefType="this" />
        <Parameter Name="vaultName" Type="System.String" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="policyName" Type="System.String" />
        <Parameter Name="operationId" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="20592-102">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="20592-102">The operations group for this extension method.</span></span>
            </param>
        <param name="vaultName">
            <span data-ttu-id="20592-103">Der Name des Recovery Services-Tresor.</span><span class="sxs-lookup"><span data-stu-id="20592-103">The name of the recovery services vault.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="20592-104">Der Name der Ressourcengruppe, in dem die Recovery-Tresor Services, ist vorhanden.</span><span class="sxs-lookup"><span data-stu-id="20592-104">The name of the resource group where the recovery services vault is present.</span></span>
            </param>
        <param name="policyName">
            <span data-ttu-id="20592-105">Name der Sicherungsrichtlinie des Vorgangs, deren Status abgerufen werden muss.</span><span class="sxs-lookup"><span data-stu-id="20592-105">Backup policy name whose operation's status needs to be fetched.</span></span>
            </param>
        <param name="operationId">
            <span data-ttu-id="20592-106">Vorgangs-ID einen Vorgang dar, deren Status abgerufen werden muss.</span><span class="sxs-lookup"><span data-stu-id="20592-106">Operation ID which represents an operation whose status needs to be fetched.</span></span>
            </param>
        <summary>
            <span data-ttu-id="20592-107">Stellt den Status der asynchronen Vorgänge, z. B. Sicherung, Wiederherstellung bereit.</span><span class="sxs-lookup"><span data-stu-id="20592-107">Provides the status of the asynchronous operations like backup, restore.</span></span>
            <span data-ttu-id="20592-108">Der Status kann in Bearbeitung, abgeschlossen oder fehlerhaft sein.</span><span class="sxs-lookup"><span data-stu-id="20592-108">The status can be in progress, completed or failed.</span></span> <span data-ttu-id="20592-109">Sie können der Vorgangsstatus-Enumeration für alle möglichen Status eines Vorgangs verweisen.</span><span class="sxs-lookup"><span data-stu-id="20592-109">You can refer to the Operation Status enum for all the possible states of an operation.</span></span> <span data-ttu-id="20592-110">Einige Vorgänge Aufträge erstellt werden.</span><span class="sxs-lookup"><span data-stu-id="20592-110">Some operations create jobs.</span></span> <span data-ttu-id="20592-111">Diese Methode gibt die Liste der Aufträge Vorgang zugeordnet.</span><span class="sxs-lookup"><span data-stu-id="20592-111">This method returns the list of jobs associated with operation.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.RecoveryServices.Backup.Models.OperationStatus&gt; GetAsync (this Microsoft.Azure.Management.RecoveryServices.Backup.IProtectionPolicyOperationStatusesOperations operations, string vaultName, string resourceGroupName, string policyName, string operationId, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.RecoveryServices.Backup.Models.OperationStatus&gt; GetAsync(class Microsoft.Azure.Management.RecoveryServices.Backup.IProtectionPolicyOperationStatusesOperations operations, string vaultName, string resourceGroupName, string policyName, string operationId, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.RecoveryServices.Backup.ProtectionPolicyOperationStatusesOperationsExtensions.GetAsync(Microsoft.Azure.Management.RecoveryServices.Backup.IProtectionPolicyOperationStatusesOperations,System.String,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetAsync : Microsoft.Azure.Management.RecoveryServices.Backup.IProtectionPolicyOperationStatusesOperations * string * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.RecoveryServices.Backup.Models.OperationStatus&gt;" Usage="Microsoft.Azure.Management.RecoveryServices.Backup.ProtectionPolicyOperationStatusesOperationsExtensions.GetAsync (operations, vaultName, resourceGroupName, policyName, operationId, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.RecoveryServices.Backup.ProtectionPolicyOperationStatusesOperationsExtensions/&lt;GetAsync&gt;d__1))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.RecoveryServices.Backup.Models.OperationStatus&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.RecoveryServices.Backup.IProtectionPolicyOperationStatusesOperations" RefType="this" />
        <Parameter Name="vaultName" Type="System.String" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="policyName" Type="System.String" />
        <Parameter Name="operationId" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="20592-112">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="20592-112">The operations group for this extension method.</span></span>
            </param>
        <param name="vaultName">
            <span data-ttu-id="20592-113">Der Name des Recovery Services-Tresor.</span><span class="sxs-lookup"><span data-stu-id="20592-113">The name of the recovery services vault.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="20592-114">Der Name der Ressourcengruppe, in dem die Recovery-Tresor Services, ist vorhanden.</span><span class="sxs-lookup"><span data-stu-id="20592-114">The name of the resource group where the recovery services vault is present.</span></span>
            </param>
        <param name="policyName">
            <span data-ttu-id="20592-115">Name der Sicherungsrichtlinie des Vorgangs, deren Status abgerufen werden muss.</span><span class="sxs-lookup"><span data-stu-id="20592-115">Backup policy name whose operation's status needs to be fetched.</span></span>
            </param>
        <param name="operationId">
            <span data-ttu-id="20592-116">Vorgangs-ID einen Vorgang dar, deren Status abgerufen werden muss.</span><span class="sxs-lookup"><span data-stu-id="20592-116">Operation ID which represents an operation whose status needs to be fetched.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="20592-117">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="20592-117">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="20592-118">Stellt den Status der asynchronen Vorgänge, z. B. Sicherung, Wiederherstellung bereit.</span><span class="sxs-lookup"><span data-stu-id="20592-118">Provides the status of the asynchronous operations like backup, restore.</span></span>
            <span data-ttu-id="20592-119">Der Status kann in Bearbeitung, abgeschlossen oder fehlerhaft sein.</span><span class="sxs-lookup"><span data-stu-id="20592-119">The status can be in progress, completed or failed.</span></span> <span data-ttu-id="20592-120">Sie können der Vorgangsstatus-Enumeration für alle möglichen Status eines Vorgangs verweisen.</span><span class="sxs-lookup"><span data-stu-id="20592-120">You can refer to the Operation Status enum for all the possible states of an operation.</span></span> <span data-ttu-id="20592-121">Einige Vorgänge Aufträge erstellt werden.</span><span class="sxs-lookup"><span data-stu-id="20592-121">Some operations create jobs.</span></span> <span data-ttu-id="20592-122">Diese Methode gibt die Liste der Aufträge Vorgang zugeordnet.</span><span class="sxs-lookup"><span data-stu-id="20592-122">This method returns the list of jobs associated with operation.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>