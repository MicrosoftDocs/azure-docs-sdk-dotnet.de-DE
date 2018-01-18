<Type Name="JobDetailsOperationsExtensions" FullName="Microsoft.Azure.Management.RecoveryServices.Backup.JobDetailsOperationsExtensions">
  <TypeSignature Language="C#" Value="public static class JobDetailsOperationsExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit JobDetailsOperationsExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.RecoveryServices.Backup.JobDetailsOperationsExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module JobDetailsOperationsExtensions" />
  <TypeSignature Language="F#" Value="type JobDetailsOperationsExtensions = class" />
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
            <span data-ttu-id="cbef7-101">Erweiterungsmethoden für JobDetailsOperations.</span><span class="sxs-lookup"><span data-stu-id="cbef7-101">Extension methods for JobDetailsOperations.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="Get">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.RecoveryServices.Backup.Models.JobResource Get (this Microsoft.Azure.Management.RecoveryServices.Backup.IJobDetailsOperations operations, string vaultName, string resourceGroupName, string jobName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.RecoveryServices.Backup.Models.JobResource Get(class Microsoft.Azure.Management.RecoveryServices.Backup.IJobDetailsOperations operations, string vaultName, string resourceGroupName, string jobName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.RecoveryServices.Backup.JobDetailsOperationsExtensions.Get(Microsoft.Azure.Management.RecoveryServices.Backup.IJobDetailsOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function Get (operations As IJobDetailsOperations, vaultName As String, resourceGroupName As String, jobName As String) As JobResource" />
      <MemberSignature Language="F#" Value="static member Get : Microsoft.Azure.Management.RecoveryServices.Backup.IJobDetailsOperations * string * string * string -&gt; Microsoft.Azure.Management.RecoveryServices.Backup.Models.JobResource" Usage="Microsoft.Azure.Management.RecoveryServices.Backup.JobDetailsOperationsExtensions.Get (operations, vaultName, resourceGroupName, jobName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.RecoveryServices.Backup.Models.JobResource</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.RecoveryServices.Backup.IJobDetailsOperations" RefType="this" />
        <Parameter Name="vaultName" Type="System.String" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="jobName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="cbef7-102">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="cbef7-102">The operations group for this extension method.</span></span>
            </param>
        <param name="vaultName">
            <span data-ttu-id="cbef7-103">Der Name des Recovery Services-Tresor.</span><span class="sxs-lookup"><span data-stu-id="cbef7-103">The name of the recovery services vault.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="cbef7-104">Der Name der Ressourcengruppe, in dem die Recovery-Tresor Services, ist vorhanden.</span><span class="sxs-lookup"><span data-stu-id="cbef7-104">The name of the resource group where the recovery services vault is present.</span></span>
            </param>
        <param name="jobName">
            <span data-ttu-id="cbef7-105">Der Name des Auftrags, deren Details werden abgerufen werden sollen.</span><span class="sxs-lookup"><span data-stu-id="cbef7-105">Name of the job whose details are to be fetched.</span></span>
            </param>
        <summary>
            <span data-ttu-id="cbef7-106">Ruft die Exteded-Informationen, die dem Auftrag zugeordnet.</span><span class="sxs-lookup"><span data-stu-id="cbef7-106">Gets exteded information associated with the job.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.RecoveryServices.Backup.Models.JobResource&gt; GetAsync (this Microsoft.Azure.Management.RecoveryServices.Backup.IJobDetailsOperations operations, string vaultName, string resourceGroupName, string jobName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.RecoveryServices.Backup.Models.JobResource&gt; GetAsync(class Microsoft.Azure.Management.RecoveryServices.Backup.IJobDetailsOperations operations, string vaultName, string resourceGroupName, string jobName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.RecoveryServices.Backup.JobDetailsOperationsExtensions.GetAsync(Microsoft.Azure.Management.RecoveryServices.Backup.IJobDetailsOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetAsync : Microsoft.Azure.Management.RecoveryServices.Backup.IJobDetailsOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.RecoveryServices.Backup.Models.JobResource&gt;" Usage="Microsoft.Azure.Management.RecoveryServices.Backup.JobDetailsOperationsExtensions.GetAsync (operations, vaultName, resourceGroupName, jobName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.RecoveryServices.Backup.JobDetailsOperationsExtensions/&lt;GetAsync&gt;d__1))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.RecoveryServices.Backup.Models.JobResource&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.RecoveryServices.Backup.IJobDetailsOperations" RefType="this" />
        <Parameter Name="vaultName" Type="System.String" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="jobName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="cbef7-107">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="cbef7-107">The operations group for this extension method.</span></span>
            </param>
        <param name="vaultName">
            <span data-ttu-id="cbef7-108">Der Name des Recovery Services-Tresor.</span><span class="sxs-lookup"><span data-stu-id="cbef7-108">The name of the recovery services vault.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="cbef7-109">Der Name der Ressourcengruppe, in dem die Recovery-Tresor Services, ist vorhanden.</span><span class="sxs-lookup"><span data-stu-id="cbef7-109">The name of the resource group where the recovery services vault is present.</span></span>
            </param>
        <param name="jobName">
            <span data-ttu-id="cbef7-110">Der Name des Auftrags, deren Details werden abgerufen werden sollen.</span><span class="sxs-lookup"><span data-stu-id="cbef7-110">Name of the job whose details are to be fetched.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="cbef7-111">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="cbef7-111">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="cbef7-112">Ruft die Exteded-Informationen, die dem Auftrag zugeordnet.</span><span class="sxs-lookup"><span data-stu-id="cbef7-112">Gets exteded information associated with the job.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>