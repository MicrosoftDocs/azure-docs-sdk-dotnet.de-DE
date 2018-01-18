<Type Name="ExportJobsOperationResultsOperationsExtensions" FullName="Microsoft.Azure.Management.RecoveryServices.Backup.ExportJobsOperationResultsOperationsExtensions">
  <TypeSignature Language="C#" Value="public static class ExportJobsOperationResultsOperationsExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit ExportJobsOperationResultsOperationsExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.RecoveryServices.Backup.ExportJobsOperationResultsOperationsExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module ExportJobsOperationResultsOperationsExtensions" />
  <TypeSignature Language="F#" Value="type ExportJobsOperationResultsOperationsExtensions = class" />
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
            <span data-ttu-id="ff977-101">Erweiterungsmethoden für ExportJobsOperationResultsOperations.</span><span class="sxs-lookup"><span data-stu-id="ff977-101">Extension methods for ExportJobsOperationResultsOperations.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="Get">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.RecoveryServices.Backup.Models.OperationResultInfoBaseResource Get (this Microsoft.Azure.Management.RecoveryServices.Backup.IExportJobsOperationResultsOperations operations, string vaultName, string resourceGroupName, string operationId);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.RecoveryServices.Backup.Models.OperationResultInfoBaseResource Get(class Microsoft.Azure.Management.RecoveryServices.Backup.IExportJobsOperationResultsOperations operations, string vaultName, string resourceGroupName, string operationId) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.RecoveryServices.Backup.ExportJobsOperationResultsOperationsExtensions.Get(Microsoft.Azure.Management.RecoveryServices.Backup.IExportJobsOperationResultsOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function Get (operations As IExportJobsOperationResultsOperations, vaultName As String, resourceGroupName As String, operationId As String) As OperationResultInfoBaseResource" />
      <MemberSignature Language="F#" Value="static member Get : Microsoft.Azure.Management.RecoveryServices.Backup.IExportJobsOperationResultsOperations * string * string * string -&gt; Microsoft.Azure.Management.RecoveryServices.Backup.Models.OperationResultInfoBaseResource" Usage="Microsoft.Azure.Management.RecoveryServices.Backup.ExportJobsOperationResultsOperationsExtensions.Get (operations, vaultName, resourceGroupName, operationId)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.RecoveryServices.Backup.Models.OperationResultInfoBaseResource</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.RecoveryServices.Backup.IExportJobsOperationResultsOperations" RefType="this" />
        <Parameter Name="vaultName" Type="System.String" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="operationId" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="ff977-102">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="ff977-102">The operations group for this extension method.</span></span>
            </param>
        <param name="vaultName">
            <span data-ttu-id="ff977-103">Der Name des Recovery Services-Tresor.</span><span class="sxs-lookup"><span data-stu-id="ff977-103">The name of the recovery services vault.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="ff977-104">Der Name der Ressourcengruppe, in dem die Recovery-Tresor Services, ist vorhanden.</span><span class="sxs-lookup"><span data-stu-id="ff977-104">The name of the resource group where the recovery services vault is present.</span></span>
            </param>
        <param name="operationId">
            <span data-ttu-id="ff977-105">OperationID des exportauftrags dar.</span><span class="sxs-lookup"><span data-stu-id="ff977-105">OperationID which represents the export job.</span></span>
            </param>
        <summary>
            <span data-ttu-id="ff977-106">Ruft das Ergebnis des Vorgangs des Vorgangs durch Exportieren Aufträge API ausgelöst.</span><span class="sxs-lookup"><span data-stu-id="ff977-106">Gets the operation result of operation triggered by Export Jobs API.</span></span> <span data-ttu-id="ff977-107">Wenn der Vorgang erfolgreich ist, enthält er auch URL des Blob und einen SAS-Schlüssel, auf die gleiche.</span><span class="sxs-lookup"><span data-stu-id="ff977-107">If the operation is successful, then it also contains URL of a Blob and a SAS key to access the same.</span></span> <span data-ttu-id="ff977-108">Das Blob enthält, in die serialisierte JSON-Format exportierte Aufträgen.</span><span class="sxs-lookup"><span data-stu-id="ff977-108">The blob contains exported jobs in JSON serialized format.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.RecoveryServices.Backup.Models.OperationResultInfoBaseResource&gt; GetAsync (this Microsoft.Azure.Management.RecoveryServices.Backup.IExportJobsOperationResultsOperations operations, string vaultName, string resourceGroupName, string operationId, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.RecoveryServices.Backup.Models.OperationResultInfoBaseResource&gt; GetAsync(class Microsoft.Azure.Management.RecoveryServices.Backup.IExportJobsOperationResultsOperations operations, string vaultName, string resourceGroupName, string operationId, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.RecoveryServices.Backup.ExportJobsOperationResultsOperationsExtensions.GetAsync(Microsoft.Azure.Management.RecoveryServices.Backup.IExportJobsOperationResultsOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetAsync : Microsoft.Azure.Management.RecoveryServices.Backup.IExportJobsOperationResultsOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.RecoveryServices.Backup.Models.OperationResultInfoBaseResource&gt;" Usage="Microsoft.Azure.Management.RecoveryServices.Backup.ExportJobsOperationResultsOperationsExtensions.GetAsync (operations, vaultName, resourceGroupName, operationId, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.RecoveryServices.Backup.ExportJobsOperationResultsOperationsExtensions/&lt;GetAsync&gt;d__1))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.RecoveryServices.Backup.Models.OperationResultInfoBaseResource&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.RecoveryServices.Backup.IExportJobsOperationResultsOperations" RefType="this" />
        <Parameter Name="vaultName" Type="System.String" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="operationId" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="ff977-109">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="ff977-109">The operations group for this extension method.</span></span>
            </param>
        <param name="vaultName">
            <span data-ttu-id="ff977-110">Der Name des Recovery Services-Tresor.</span><span class="sxs-lookup"><span data-stu-id="ff977-110">The name of the recovery services vault.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="ff977-111">Der Name der Ressourcengruppe, in dem die Recovery-Tresor Services, ist vorhanden.</span><span class="sxs-lookup"><span data-stu-id="ff977-111">The name of the resource group where the recovery services vault is present.</span></span>
            </param>
        <param name="operationId">
            <span data-ttu-id="ff977-112">OperationID des exportauftrags dar.</span><span class="sxs-lookup"><span data-stu-id="ff977-112">OperationID which represents the export job.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="ff977-113">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="ff977-113">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="ff977-114">Ruft das Ergebnis des Vorgangs des Vorgangs durch Exportieren Aufträge API ausgelöst.</span><span class="sxs-lookup"><span data-stu-id="ff977-114">Gets the operation result of operation triggered by Export Jobs API.</span></span> <span data-ttu-id="ff977-115">Wenn der Vorgang erfolgreich ist, enthält er auch URL des Blob und einen SAS-Schlüssel, auf die gleiche.</span><span class="sxs-lookup"><span data-stu-id="ff977-115">If the operation is successful, then it also contains URL of a Blob and a SAS key to access the same.</span></span> <span data-ttu-id="ff977-116">Das Blob enthält, in die serialisierte JSON-Format exportierte Aufträgen.</span><span class="sxs-lookup"><span data-stu-id="ff977-116">The blob contains exported jobs in JSON serialized format.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>