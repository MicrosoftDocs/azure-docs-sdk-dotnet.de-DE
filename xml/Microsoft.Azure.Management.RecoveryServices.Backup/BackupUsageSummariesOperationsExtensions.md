<Type Name="BackupUsageSummariesOperationsExtensions" FullName="Microsoft.Azure.Management.RecoveryServices.Backup.BackupUsageSummariesOperationsExtensions">
  <TypeSignature Language="C#" Value="public static class BackupUsageSummariesOperationsExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit BackupUsageSummariesOperationsExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.RecoveryServices.Backup.BackupUsageSummariesOperationsExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module BackupUsageSummariesOperationsExtensions" />
  <TypeSignature Language="F#" Value="type BackupUsageSummariesOperationsExtensions = class" />
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
            <span data-ttu-id="c5e00-101">Erweiterungsmethoden für BackupUsageSummariesOperations.</span><span class="sxs-lookup"><span data-stu-id="c5e00-101">Extension methods for BackupUsageSummariesOperations.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="List">
      <MemberSignature Language="C#" Value="public static System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.RecoveryServices.Backup.Models.BackupManagementUsage&gt; List (this Microsoft.Azure.Management.RecoveryServices.Backup.IBackupUsageSummariesOperations operations, string vaultName, string resourceGroupName, Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.RecoveryServices.Backup.Models.BMSBackupSummariesQueryObject&gt; odataQuery = null, string skipToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Management.RecoveryServices.Backup.Models.BackupManagementUsage&gt; List(class Microsoft.Azure.Management.RecoveryServices.Backup.IBackupUsageSummariesOperations operations, string vaultName, string resourceGroupName, class Microsoft.Rest.Azure.OData.ODataQuery`1&lt;class Microsoft.Azure.Management.RecoveryServices.Backup.Models.BMSBackupSummariesQueryObject&gt; odataQuery, string skipToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.RecoveryServices.Backup.BackupUsageSummariesOperationsExtensions.List(Microsoft.Azure.Management.RecoveryServices.Backup.IBackupUsageSummariesOperations,System.String,System.String,Microsoft.Rest.Azure.OData.ODataQuery{Microsoft.Azure.Management.RecoveryServices.Backup.Models.BMSBackupSummariesQueryObject},System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function List (operations As IBackupUsageSummariesOperations, vaultName As String, resourceGroupName As String, Optional odataQuery As ODataQuery(Of BMSBackupSummariesQueryObject) = null, Optional skipToken As String = null) As IEnumerable(Of BackupManagementUsage)" />
      <MemberSignature Language="F#" Value="static member List : Microsoft.Azure.Management.RecoveryServices.Backup.IBackupUsageSummariesOperations * string * string * Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.RecoveryServices.Backup.Models.BMSBackupSummariesQueryObject&gt; * string -&gt; seq&lt;Microsoft.Azure.Management.RecoveryServices.Backup.Models.BackupManagementUsage&gt;" Usage="Microsoft.Azure.Management.RecoveryServices.Backup.BackupUsageSummariesOperationsExtensions.List (operations, vaultName, resourceGroupName, odataQuery, skipToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.RecoveryServices.Backup.Models.BackupManagementUsage&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.RecoveryServices.Backup.IBackupUsageSummariesOperations" RefType="this" />
        <Parameter Name="vaultName" Type="System.String" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="odataQuery" Type="Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.RecoveryServices.Backup.Models.BMSBackupSummariesQueryObject&gt;" />
        <Parameter Name="skipToken" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="c5e00-102">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="c5e00-102">The operations group for this extension method.</span></span>
            </param>
        <param name="vaultName">
            <span data-ttu-id="c5e00-103">Der Name des Recovery Services-Tresor.</span><span class="sxs-lookup"><span data-stu-id="c5e00-103">The name of the recovery services vault.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="c5e00-104">Der Name der Ressourcengruppe, in dem die Recovery-Tresor Services, ist vorhanden.</span><span class="sxs-lookup"><span data-stu-id="c5e00-104">The name of the resource group where the recovery services vault is present.</span></span>
            </param>
        <param name="odataQuery">
            <span data-ttu-id="c5e00-105">OData-Parameter des Vorgangs angewendet.</span><span class="sxs-lookup"><span data-stu-id="c5e00-105">OData parameters to apply to the operation.</span></span>
            </param>
        <param name="skipToken">
            <span data-ttu-id="c5e00-106">SkipToken Filter.</span><span class="sxs-lookup"><span data-stu-id="c5e00-106">skipToken Filter.</span></span>
            </param>
        <summary>
            <span data-ttu-id="c5e00-107">Dadurch wird die sicherungsverwaltung Zusammenfassungen des Tresors.</span><span class="sxs-lookup"><span data-stu-id="c5e00-107">Fetches the backup management usage summaries of the vault.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.RecoveryServices.Backup.Models.BackupManagementUsage&gt;&gt; ListAsync (this Microsoft.Azure.Management.RecoveryServices.Backup.IBackupUsageSummariesOperations operations, string vaultName, string resourceGroupName, Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.RecoveryServices.Backup.Models.BMSBackupSummariesQueryObject&gt; odataQuery = null, string skipToken = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Management.RecoveryServices.Backup.Models.BackupManagementUsage&gt;&gt; ListAsync(class Microsoft.Azure.Management.RecoveryServices.Backup.IBackupUsageSummariesOperations operations, string vaultName, string resourceGroupName, class Microsoft.Rest.Azure.OData.ODataQuery`1&lt;class Microsoft.Azure.Management.RecoveryServices.Backup.Models.BMSBackupSummariesQueryObject&gt; odataQuery, string skipToken, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.RecoveryServices.Backup.BackupUsageSummariesOperationsExtensions.ListAsync(Microsoft.Azure.Management.RecoveryServices.Backup.IBackupUsageSummariesOperations,System.String,System.String,Microsoft.Rest.Azure.OData.ODataQuery{Microsoft.Azure.Management.RecoveryServices.Backup.Models.BMSBackupSummariesQueryObject},System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListAsync : Microsoft.Azure.Management.RecoveryServices.Backup.IBackupUsageSummariesOperations * string * string * Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.RecoveryServices.Backup.Models.BMSBackupSummariesQueryObject&gt; * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;seq&lt;Microsoft.Azure.Management.RecoveryServices.Backup.Models.BackupManagementUsage&gt;&gt;" Usage="Microsoft.Azure.Management.RecoveryServices.Backup.BackupUsageSummariesOperationsExtensions.ListAsync (operations, vaultName, resourceGroupName, odataQuery, skipToken, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.RecoveryServices.Backup.BackupUsageSummariesOperationsExtensions/&lt;ListAsync&gt;d__1))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.RecoveryServices.Backup.Models.BackupManagementUsage&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.RecoveryServices.Backup.IBackupUsageSummariesOperations" RefType="this" />
        <Parameter Name="vaultName" Type="System.String" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="odataQuery" Type="Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.RecoveryServices.Backup.Models.BMSBackupSummariesQueryObject&gt;" />
        <Parameter Name="skipToken" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="c5e00-108">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="c5e00-108">The operations group for this extension method.</span></span>
            </param>
        <param name="vaultName">
            <span data-ttu-id="c5e00-109">Der Name des Recovery Services-Tresor.</span><span class="sxs-lookup"><span data-stu-id="c5e00-109">The name of the recovery services vault.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="c5e00-110">Der Name der Ressourcengruppe, in dem die Recovery-Tresor Services, ist vorhanden.</span><span class="sxs-lookup"><span data-stu-id="c5e00-110">The name of the resource group where the recovery services vault is present.</span></span>
            </param>
        <param name="odataQuery">
            <span data-ttu-id="c5e00-111">OData-Parameter des Vorgangs angewendet.</span><span class="sxs-lookup"><span data-stu-id="c5e00-111">OData parameters to apply to the operation.</span></span>
            </param>
        <param name="skipToken">
            <span data-ttu-id="c5e00-112">SkipToken Filter.</span><span class="sxs-lookup"><span data-stu-id="c5e00-112">skipToken Filter.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="c5e00-113">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="c5e00-113">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="c5e00-114">Dadurch wird die sicherungsverwaltung Zusammenfassungen des Tresors.</span><span class="sxs-lookup"><span data-stu-id="c5e00-114">Fetches the backup management usage summaries of the vault.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>