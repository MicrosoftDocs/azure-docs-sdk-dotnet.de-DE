<Type Name="JobsOperationsExtensions" FullName="Microsoft.Azure.Management.RecoveryServices.Backup.JobsOperationsExtensions">
  <TypeSignature Language="C#" Value="public static class JobsOperationsExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit JobsOperationsExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.RecoveryServices.Backup.JobsOperationsExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module JobsOperationsExtensions" />
  <TypeSignature Language="F#" Value="type JobsOperationsExtensions = class" />
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
            <span data-ttu-id="cd88a-101">Erweiterungsmethoden für JobsOperations.</span><span class="sxs-lookup"><span data-stu-id="cd88a-101">Extension methods for JobsOperations.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="Export">
      <MemberSignature Language="C#" Value="public static void Export (this Microsoft.Azure.Management.RecoveryServices.Backup.IJobsOperations operations, string vaultName, string resourceGroupName, Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.RecoveryServices.Backup.Models.JobQueryObject&gt; odataQuery = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void Export(class Microsoft.Azure.Management.RecoveryServices.Backup.IJobsOperations operations, string vaultName, string resourceGroupName, class Microsoft.Rest.Azure.OData.ODataQuery`1&lt;class Microsoft.Azure.Management.RecoveryServices.Backup.Models.JobQueryObject&gt; odataQuery) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.RecoveryServices.Backup.JobsOperationsExtensions.Export(Microsoft.Azure.Management.RecoveryServices.Backup.IJobsOperations,System.String,System.String,Microsoft.Rest.Azure.OData.ODataQuery{Microsoft.Azure.Management.RecoveryServices.Backup.Models.JobQueryObject})" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Sub Export (operations As IJobsOperations, vaultName As String, resourceGroupName As String, Optional odataQuery As ODataQuery(Of JobQueryObject) = null)" />
      <MemberSignature Language="F#" Value="static member Export : Microsoft.Azure.Management.RecoveryServices.Backup.IJobsOperations * string * string * Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.RecoveryServices.Backup.Models.JobQueryObject&gt; -&gt; unit" Usage="Microsoft.Azure.Management.RecoveryServices.Backup.JobsOperationsExtensions.Export (operations, vaultName, resourceGroupName, odataQuery)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.RecoveryServices.Backup.IJobsOperations" RefType="this" />
        <Parameter Name="vaultName" Type="System.String" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="odataQuery" Type="Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.RecoveryServices.Backup.Models.JobQueryObject&gt;" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="cd88a-102">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="cd88a-102">The operations group for this extension method.</span></span>
            </param>
        <param name="vaultName">
            <span data-ttu-id="cd88a-103">Der Name des Recovery Services-Tresor.</span><span class="sxs-lookup"><span data-stu-id="cd88a-103">The name of the recovery services vault.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="cd88a-104">Der Name der Ressourcengruppe, in dem die Recovery-Tresor Services, ist vorhanden.</span><span class="sxs-lookup"><span data-stu-id="cd88a-104">The name of the resource group where the recovery services vault is present.</span></span>
            </param>
        <param name="odataQuery">
            <span data-ttu-id="cd88a-105">OData-Parameter des Vorgangs angewendet.</span><span class="sxs-lookup"><span data-stu-id="cd88a-105">OData parameters to apply to the operation.</span></span>
            </param>
        <summary>
            <span data-ttu-id="cd88a-106">Wird ausgelöst, Exportieren von Aufträgen, die vom Filter angegeben, und gibt die OperationID zum Nachverfolgen von zurück.</span><span class="sxs-lookup"><span data-stu-id="cd88a-106">Triggers export of jobs specified by filters and returns an OperationID to track.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ExportAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task ExportAsync (this Microsoft.Azure.Management.RecoveryServices.Backup.IJobsOperations operations, string vaultName, string resourceGroupName, Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.RecoveryServices.Backup.Models.JobQueryObject&gt; odataQuery = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task ExportAsync(class Microsoft.Azure.Management.RecoveryServices.Backup.IJobsOperations operations, string vaultName, string resourceGroupName, class Microsoft.Rest.Azure.OData.ODataQuery`1&lt;class Microsoft.Azure.Management.RecoveryServices.Backup.Models.JobQueryObject&gt; odataQuery, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.RecoveryServices.Backup.JobsOperationsExtensions.ExportAsync(Microsoft.Azure.Management.RecoveryServices.Backup.IJobsOperations,System.String,System.String,Microsoft.Rest.Azure.OData.ODataQuery{Microsoft.Azure.Management.RecoveryServices.Backup.Models.JobQueryObject},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ExportAsync : Microsoft.Azure.Management.RecoveryServices.Backup.IJobsOperations * string * string * Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.RecoveryServices.Backup.Models.JobQueryObject&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.RecoveryServices.Backup.JobsOperationsExtensions.ExportAsync (operations, vaultName, resourceGroupName, odataQuery, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.RecoveryServices.Backup.JobsOperationsExtensions/&lt;ExportAsync&gt;d__1))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.RecoveryServices.Backup.IJobsOperations" RefType="this" />
        <Parameter Name="vaultName" Type="System.String" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="odataQuery" Type="Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.RecoveryServices.Backup.Models.JobQueryObject&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="cd88a-107">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="cd88a-107">The operations group for this extension method.</span></span>
            </param>
        <param name="vaultName">
            <span data-ttu-id="cd88a-108">Der Name des Recovery Services-Tresor.</span><span class="sxs-lookup"><span data-stu-id="cd88a-108">The name of the recovery services vault.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="cd88a-109">Der Name der Ressourcengruppe, in dem die Recovery-Tresor Services, ist vorhanden.</span><span class="sxs-lookup"><span data-stu-id="cd88a-109">The name of the resource group where the recovery services vault is present.</span></span>
            </param>
        <param name="odataQuery">
            <span data-ttu-id="cd88a-110">OData-Parameter des Vorgangs angewendet.</span><span class="sxs-lookup"><span data-stu-id="cd88a-110">OData parameters to apply to the operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="cd88a-111">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="cd88a-111">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="cd88a-112">Wird ausgelöst, Exportieren von Aufträgen, die vom Filter angegeben, und gibt die OperationID zum Nachverfolgen von zurück.</span><span class="sxs-lookup"><span data-stu-id="cd88a-112">Triggers export of jobs specified by filters and returns an OperationID to track.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>