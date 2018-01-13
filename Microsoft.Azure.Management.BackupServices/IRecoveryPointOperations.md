<Type Name="IRecoveryPointOperations" FullName="Microsoft.Azure.Management.BackupServices.IRecoveryPointOperations">
  <TypeSignature Language="C#" Value="public interface IRecoveryPointOperations" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IRecoveryPointOperations" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.BackupServices.IRecoveryPointOperations" />
  <TypeSignature Language="VB.NET" Value="Public Interface IRecoveryPointOperations" />
  <TypeSignature Language="F#" Value="type IRecoveryPointOperations = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.BackupServicesManagement</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            Die Definition der Wiederherstellungspunkt-Vorgänge für die Azure Backup-Erweiterung.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="GetAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.BackupServices.Models.CSMRecoveryPointGetOperationResponse&gt; GetAsync (string resourceGroupName, string resourceName, Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders customRequestHeaders, string containerName, string itemName, string recoveryPointName, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.BackupServices.Models.CSMRecoveryPointGetOperationResponse&gt; GetAsync(string resourceGroupName, string resourceName, class Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders customRequestHeaders, string containerName, string itemName, string recoveryPointName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.BackupServices.IRecoveryPointOperations.GetAsync(System.String,System.String,Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetAsync : string * string * Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.BackupServices.Models.CSMRecoveryPointGetOperationResponse&gt;" Usage="iRecoveryPointOperations.GetAsync (resourceGroupName, resourceName, customRequestHeaders, containerName, itemName, recoveryPointName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BackupServicesManagement</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.BackupServices.Models.CSMRecoveryPointGetOperationResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="resourceName" Type="System.String" />
        <Parameter Name="customRequestHeaders" Type="Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders" />
        <Parameter Name="containerName" Type="System.String" />
        <Parameter Name="itemName" Type="System.String" />
        <Parameter Name="recoveryPointName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">To be added.</param>
        <param name="resourceName">To be added.</param>
        <param name="customRequestHeaders">
            Header Anforderungsparameter.
            </param>
        <param name="containerName">To be added.</param>
        <param name="itemName">To be added.</param>
        <param name="recoveryPointName">To be added.</param>
        <param name="cancellationToken">
            Abbruchtoken.
            </param>
        <summary>
            Abrufen des Wiederherstellungspunkts an.
            </summary>
        <returns>
            Die Definition einer CSMRecoveryPointGetOperationResponse.
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.BackupServices.Models.CSMRecoveryPointListOperationResponse&gt; ListAsync (string resourceGroupName, string resourceName, Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders customRequestHeaders, string containerName, string itemName, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.BackupServices.Models.CSMRecoveryPointListOperationResponse&gt; ListAsync(string resourceGroupName, string resourceName, class Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders customRequestHeaders, string containerName, string itemName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.BackupServices.IRecoveryPointOperations.ListAsync(System.String,System.String,Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListAsync : string * string * Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.BackupServices.Models.CSMRecoveryPointListOperationResponse&gt;" Usage="iRecoveryPointOperations.ListAsync (resourceGroupName, resourceName, customRequestHeaders, containerName, itemName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BackupServicesManagement</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.BackupServices.Models.CSMRecoveryPointListOperationResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="resourceName" Type="System.String" />
        <Parameter Name="customRequestHeaders" Type="Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders" />
        <Parameter Name="containerName" Type="System.String" />
        <Parameter Name="itemName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">To be added.</param>
        <param name="resourceName">To be added.</param>
        <param name="customRequestHeaders">
            Header Anforderungsparameter.
            </param>
        <param name="containerName">To be added.</param>
        <param name="itemName">To be added.</param>
        <param name="cancellationToken">
            Abbruchtoken.
            </param>
        <summary>
            Ruft die Liste aller Wiederherstellungspunkte.
            </summary>
        <returns>
            Die Definition einer CSMRecoveryPointListOperationResponse.
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>