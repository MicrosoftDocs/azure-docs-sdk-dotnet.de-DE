<Type Name="IProtectableObjectOperations" FullName="Microsoft.Azure.Management.BackupServices.IProtectableObjectOperations">
  <TypeSignature Language="C#" Value="public interface IProtectableObjectOperations" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IProtectableObjectOperations" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.BackupServices.IProtectableObjectOperations" />
  <TypeSignature Language="VB.NET" Value="Public Interface IProtectableObjectOperations" />
  <TypeSignature Language="F#" Value="type IProtectableObjectOperations = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.BackupServicesManagement</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="db4b6-101">Definition der schützbaren ObjectOperation Vorgänge für die Azure Backup-Erweiterung.</span><span class="sxs-lookup"><span data-stu-id="db4b6-101">Definition of Protectable ObjectOperation operations for the Azure Backup extension.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="ListCSMAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.BackupServices.Models.CSMItemListOperationResponse&gt; ListCSMAsync (string resourceGroupName, string resourceName, Microsoft.Azure.Management.BackupServices.Models.CSMItemQueryObject csmparameters, Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders customRequestHeaders, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.BackupServices.Models.CSMItemListOperationResponse&gt; ListCSMAsync(string resourceGroupName, string resourceName, class Microsoft.Azure.Management.BackupServices.Models.CSMItemQueryObject csmparameters, class Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders customRequestHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.BackupServices.IProtectableObjectOperations.ListCSMAsync(System.String,System.String,Microsoft.Azure.Management.BackupServices.Models.CSMItemQueryObject,Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListCSMAsync : string * string * Microsoft.Azure.Management.BackupServices.Models.CSMItemQueryObject * Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.BackupServices.Models.CSMItemListOperationResponse&gt;" Usage="iProtectableObjectOperations.ListCSMAsync (resourceGroupName, resourceName, csmparameters, customRequestHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BackupServicesManagement</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.BackupServices.Models.CSMItemListOperationResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="resourceName" Type="System.String" />
        <Parameter Name="csmparameters" Type="Microsoft.Azure.Management.BackupServices.Models.CSMItemQueryObject" />
        <Parameter Name="customRequestHeaders" Type="Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">To be added.</param>
        <param name="resourceName">To be added.</param>
        <param name="csmparameters">
            <span data-ttu-id="db4b6-102">Abfrageparameter Schützbare Objekte hinzugefügt.</span><span class="sxs-lookup"><span data-stu-id="db4b6-102">Protectable objects query parameter.</span></span>
            </param>
        <param name="customRequestHeaders">
            <span data-ttu-id="db4b6-103">Header Anforderungsparameter.</span><span class="sxs-lookup"><span data-stu-id="db4b6-103">Request header parameters.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="db4b6-104">Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="db4b6-104">Cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="db4b6-105">Rufen Sie die Liste aller Elemente</span><span class="sxs-lookup"><span data-stu-id="db4b6-105">Get the list of all items</span></span>
            </summary>
        <returns>
            <span data-ttu-id="db4b6-106">Die Definition einer CSMItemListOperationResponse.</span><span class="sxs-lookup"><span data-stu-id="db4b6-106">The definition of a CSMItemListOperationResponse.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>