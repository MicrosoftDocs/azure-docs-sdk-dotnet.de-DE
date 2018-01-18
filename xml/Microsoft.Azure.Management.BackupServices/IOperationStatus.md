<Type Name="IOperationStatus" FullName="Microsoft.Azure.Management.BackupServices.IOperationStatus">
  <TypeSignature Language="C#" Value="public interface IOperationStatus" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IOperationStatus" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.BackupServices.IOperationStatus" />
  <TypeSignature Language="VB.NET" Value="Public Interface IOperationStatus" />
  <TypeSignature Language="F#" Value="type IOperationStatus = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.BackupServicesManagement</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="a4442-101">Die Definition des Workflow-Vorgangs für die Azure Backup-Erweiterung.</span><span class="sxs-lookup"><span data-stu-id="a4442-101">Definition of Workflow operation for the Azure Backup extension.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="CSMGetAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.BackupServices.CSMOperationResult&gt; CSMGetAsync (string resourceGroupName, string resourceName, string operationId, Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders customRequestHeaders, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.BackupServices.CSMOperationResult&gt; CSMGetAsync(string resourceGroupName, string resourceName, string operationId, class Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders customRequestHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.BackupServices.IOperationStatus.CSMGetAsync(System.String,System.String,System.String,Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member CSMGetAsync : string * string * string * Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.BackupServices.CSMOperationResult&gt;" Usage="iOperationStatus.CSMGetAsync (resourceGroupName, resourceName, operationId, customRequestHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BackupServicesManagement</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.BackupServices.CSMOperationResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="resourceName" Type="System.String" />
        <Parameter Name="operationId" Type="System.String" />
        <Parameter Name="customRequestHeaders" Type="Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">To be added.</param>
        <param name="resourceName">To be added.</param>
        <param name="operationId">
            <span data-ttu-id="a4442-102">OperationId.</span><span class="sxs-lookup"><span data-stu-id="a4442-102">OperationId.</span></span>
            </param>
        <param name="customRequestHeaders">
            <span data-ttu-id="a4442-103">Header Anforderungsparameter.</span><span class="sxs-lookup"><span data-stu-id="a4442-103">Request header parameters.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="a4442-104">Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="a4442-104">Cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="a4442-105">Vorgangsstatus abrufen.</span><span class="sxs-lookup"><span data-stu-id="a4442-105">Get the Operation Status.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="a4442-106">Die Definition einer CSMOperationResult.</span><span class="sxs-lookup"><span data-stu-id="a4442-106">The definition of a CSMOperationResult.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>