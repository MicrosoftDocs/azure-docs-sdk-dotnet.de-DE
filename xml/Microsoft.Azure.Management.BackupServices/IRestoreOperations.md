<Type Name="IRestoreOperations" FullName="Microsoft.Azure.Management.BackupServices.IRestoreOperations">
  <TypeSignature Language="C#" Value="public interface IRestoreOperations" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IRestoreOperations" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.BackupServices.IRestoreOperations" />
  <TypeSignature Language="VB.NET" Value="Public Interface IRestoreOperations" />
  <TypeSignature Language="F#" Value="type IRestoreOperations = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.BackupServicesManagement</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="88912-101">Definition von Wiederherstellungsvorgängen für die Azure Backup-Erweiterung.</span><span class="sxs-lookup"><span data-stu-id="88912-101">Definition of Restore operations for the Azure Backup extension.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="TriggerResotreAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.BackupServices.OperationResponse&gt; TriggerResotreAsync (string resourceGroupName, string resourceName, Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders customRequestHeaders, string containerName, string itemName, string recoveryPointName, Microsoft.Azure.Management.BackupServices.Models.CSMRestoreRequest parameters, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.BackupServices.OperationResponse&gt; TriggerResotreAsync(string resourceGroupName, string resourceName, class Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders customRequestHeaders, string containerName, string itemName, string recoveryPointName, class Microsoft.Azure.Management.BackupServices.Models.CSMRestoreRequest parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.BackupServices.IRestoreOperations.TriggerResotreAsync(System.String,System.String,Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders,System.String,System.String,System.String,Microsoft.Azure.Management.BackupServices.Models.CSMRestoreRequest,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member TriggerResotreAsync : string * string * Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders * string * string * string * Microsoft.Azure.Management.BackupServices.Models.CSMRestoreRequest * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.BackupServices.OperationResponse&gt;" Usage="iRestoreOperations.TriggerResotreAsync (resourceGroupName, resourceName, customRequestHeaders, containerName, itemName, recoveryPointName, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BackupServicesManagement</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.BackupServices.OperationResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="resourceName" Type="System.String" />
        <Parameter Name="customRequestHeaders" Type="Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders" />
        <Parameter Name="containerName" Type="System.String" />
        <Parameter Name="itemName" Type="System.String" />
        <Parameter Name="recoveryPointName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.BackupServices.Models.CSMRestoreRequest" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">To be added.</param>
        <param name="resourceName">To be added.</param>
        <param name="customRequestHeaders">
            <span data-ttu-id="88912-102">Header Anforderungsparameter.</span><span class="sxs-lookup"><span data-stu-id="88912-102">Request header parameters.</span></span>
            </param>
        <param name="containerName">To be added.</param>
        <param name="itemName">To be added.</param>
        <param name="recoveryPointName">To be added.</param>
        <param name="parameters">To be added.</param>
        <param name="cancellationToken">
            <span data-ttu-id="88912-103">Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="88912-103">Cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="88912-104">Stellen Sie die Azure-BackUpItem wieder her.</span><span class="sxs-lookup"><span data-stu-id="88912-104">Restore Azure BackUpItem.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="88912-105">Die Definition einer Operation-Antwort.</span><span class="sxs-lookup"><span data-stu-id="88912-105">The definition of a Operation Response.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>