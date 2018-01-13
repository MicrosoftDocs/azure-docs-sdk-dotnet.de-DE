<Type Name="IVaultOperations" FullName="Microsoft.Azure.Management.BackupServices.IVaultOperations">
  <TypeSignature Language="C#" Value="public interface IVaultOperations" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IVaultOperations" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.BackupServices.IVaultOperations" />
  <TypeSignature Language="VB.NET" Value="Public Interface IVaultOperations" />
  <TypeSignature Language="F#" Value="type IVaultOperations = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.BackupServicesManagement</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            Definition der Tresor-bezogenen Vorgänge für die Azure Backup-Erweiterung.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="CreateOrUpdateAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.BackupServices.Models.AzureBackupVaultGetResponse&gt; CreateOrUpdateAsync (string resourceGroupName, string resourceName, Microsoft.Azure.Management.BackupServices.Models.AzureBackupVaultCreateOrUpdateParameters parameters, Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders customRequestHeaders, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.BackupServices.Models.AzureBackupVaultGetResponse&gt; CreateOrUpdateAsync(string resourceGroupName, string resourceName, class Microsoft.Azure.Management.BackupServices.Models.AzureBackupVaultCreateOrUpdateParameters parameters, class Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders customRequestHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.BackupServices.IVaultOperations.CreateOrUpdateAsync(System.String,System.String,Microsoft.Azure.Management.BackupServices.Models.AzureBackupVaultCreateOrUpdateParameters,Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member CreateOrUpdateAsync : string * string * Microsoft.Azure.Management.BackupServices.Models.AzureBackupVaultCreateOrUpdateParameters * Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.BackupServices.Models.AzureBackupVaultGetResponse&gt;" Usage="iVaultOperations.CreateOrUpdateAsync (resourceGroupName, resourceName, parameters, customRequestHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BackupServicesManagement</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.BackupServices.Models.AzureBackupVaultGetResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="resourceName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.BackupServices.Models.AzureBackupVaultCreateOrUpdateParameters" />
        <Parameter Name="customRequestHeaders" Type="Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            Der Name der Ressourcengruppe, in welche Tresor gehört
            </param>
        <param name="resourceName">
            Der Name des Tresors
            </param>
        <param name="parameters">
            Parameter zum Erstellen oder aktualisieren den Tresor
            </param>
        <param name="customRequestHeaders">
            Header Anforderungsparameter.
            </param>
        <param name="cancellationToken">
            Abbruchtoken.
            </param>
        <summary>
            Erstellt einen neuen Azure-sicherungstresor an.
            </summary>
        <returns>
            Tresorinformationen.
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.BackupServices.Models.AzureBackupVaultGetResponse&gt; DeleteAsync (string resourceGroupName, string resourceName, Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders customRequestHeaders, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.BackupServices.Models.AzureBackupVaultGetResponse&gt; DeleteAsync(string resourceGroupName, string resourceName, class Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders customRequestHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.BackupServices.IVaultOperations.DeleteAsync(System.String,System.String,Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member DeleteAsync : string * string * Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.BackupServices.Models.AzureBackupVaultGetResponse&gt;" Usage="iVaultOperations.DeleteAsync (resourceGroupName, resourceName, customRequestHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BackupServicesManagement</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.BackupServices.Models.AzureBackupVaultGetResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="resourceName" Type="System.String" />
        <Parameter Name="customRequestHeaders" Type="Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            Der Name der Ressourcengruppe, in welche Tresor gehört
            </param>
        <param name="resourceName">
            Der Name des Tresors
            </param>
        <param name="customRequestHeaders">
            Header Anforderungsparameter.
            </param>
        <param name="cancellationToken">
            Abbruchtoken.
            </param>
        <summary>
            Löscht die angegebene Azure backup-Tresor.
            </summary>
        <returns>
            Tresorinformationen.
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.BackupServices.Models.AzureBackupVaultGetResponse&gt; GetAsync (string resourceGroupName, string resourceName, Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders customRequestHeaders, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.BackupServices.Models.AzureBackupVaultGetResponse&gt; GetAsync(string resourceGroupName, string resourceName, class Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders customRequestHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.BackupServices.IVaultOperations.GetAsync(System.String,System.String,Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetAsync : string * string * Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.BackupServices.Models.AzureBackupVaultGetResponse&gt;" Usage="iVaultOperations.GetAsync (resourceGroupName, resourceName, customRequestHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BackupServicesManagement</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.BackupServices.Models.AzureBackupVaultGetResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="resourceName" Type="System.String" />
        <Parameter Name="customRequestHeaders" Type="Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            Der Name der Ressourcengruppe, in welche Tresor gehört
            </param>
        <param name="resourceName">
            Der Name des Tresors
            </param>
        <param name="customRequestHeaders">
            Header Anforderungsparameter.
            </param>
        <param name="cancellationToken">
            Abbruchtoken.
            </param>
        <summary>
            Ruft die angegebene Azure-schlüsseltresor.
            </summary>
        <returns>
            Tresorinformationen.
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetResourceStorageConfigAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.BackupServices.Models.GetResourceStorageConfigResponse&gt; GetResourceStorageConfigAsync (string resourceGroupName, string resourceName, Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders customRequestHeaders, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.BackupServices.Models.GetResourceStorageConfigResponse&gt; GetResourceStorageConfigAsync(string resourceGroupName, string resourceName, class Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders customRequestHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.BackupServices.IVaultOperations.GetResourceStorageConfigAsync(System.String,System.String,Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetResourceStorageConfigAsync : string * string * Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.BackupServices.Models.GetResourceStorageConfigResponse&gt;" Usage="iVaultOperations.GetResourceStorageConfigAsync (resourceGroupName, resourceName, customRequestHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BackupServicesManagement</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.BackupServices.Models.GetResourceStorageConfigResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="resourceName" Type="System.String" />
        <Parameter Name="customRequestHeaders" Type="Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            Der Name der Ressourcengruppe, in welche Tresor gehört
            </param>
        <param name="resourceName">
            Der Name des Tresors
            </param>
        <param name="customRequestHeaders">
            Header Anforderungsparameter.
            </param>
        <param name="cancellationToken">
            Abbruchtoken.
            </param>
        <summary>
            Ruft die Ressourcenkonfiguration Speicher ab.
            </summary>
        <returns>
            Die Definition einer Get-Speicher-Config Ressourcenantwort.
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.BackupServices.Models.AzureBackupVaultListResponse&gt; ListAsync (int top, Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders customRequestHeaders, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.BackupServices.Models.AzureBackupVaultListResponse&gt; ListAsync(int32 top, class Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders customRequestHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.BackupServices.IVaultOperations.ListAsync(System.Int32,Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListAsync : int * Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.BackupServices.Models.AzureBackupVaultListResponse&gt;" Usage="iVaultOperations.ListAsync (top, customRequestHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BackupServicesManagement</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.BackupServices.Models.AzureBackupVaultListResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="top" Type="System.Int32" />
        <Parameter Name="customRequestHeaders" Type="Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="top">
            Maximale Anzahl der zurückzugebenden Ergebnisseite.
            </param>
        <param name="customRequestHeaders">
            Header Anforderungsparameter.
            </param>
        <param name="cancellationToken">
            Abbruchtoken.
            </param>
        <summary>
            Ruft die sicherungstresore Abonnement zugeordneten Informationen ab.
            </summary>
        <returns>
            Liste der Tresore
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByResourceGroupAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.BackupServices.Models.AzureBackupVaultListResponse&gt; ListByResourceGroupAsync (string resourceGroupName, int top, Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders customRequestHeaders, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.BackupServices.Models.AzureBackupVaultListResponse&gt; ListByResourceGroupAsync(string resourceGroupName, int32 top, class Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders customRequestHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.BackupServices.IVaultOperations.ListByResourceGroupAsync(System.String,System.Int32,Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListByResourceGroupAsync : string * int * Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.BackupServices.Models.AzureBackupVaultListResponse&gt;" Usage="iVaultOperations.ListByResourceGroupAsync (resourceGroupName, top, customRequestHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BackupServicesManagement</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.BackupServices.Models.AzureBackupVaultListResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="top" Type="System.Int32" />
        <Parameter Name="customRequestHeaders" Type="Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            Ein optionales Argument, das den Namen der Ressourcengruppe angibt, die den Satz von Tresoren einschränkt, die zurückgegeben werden.
            </param>
        <param name="top">
            Maximale Anzahl der zurückzugebenden Ergebnisseite.
            </param>
        <param name="customRequestHeaders">
            Header Anforderungsparameter.
            </param>
        <param name="cancellationToken">
            Abbruchtoken.
            </param>
        <summary>
            Ruft die sicherungstresore Ressourcengruppe zugeordneten Informationen ab.
            </summary>
        <returns>
            Liste der Tresore
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UpdateStorageTypeAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.BackupServices.OperationResponse&gt; UpdateStorageTypeAsync (string resourceGroupName, string resourceName, Microsoft.Azure.Management.BackupServices.Models.UpdateVaultStorageTypeRequest updateVaultStorageTypeRequest, Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders customRequestHeaders, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.BackupServices.OperationResponse&gt; UpdateStorageTypeAsync(string resourceGroupName, string resourceName, class Microsoft.Azure.Management.BackupServices.Models.UpdateVaultStorageTypeRequest updateVaultStorageTypeRequest, class Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders customRequestHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.BackupServices.IVaultOperations.UpdateStorageTypeAsync(System.String,System.String,Microsoft.Azure.Management.BackupServices.Models.UpdateVaultStorageTypeRequest,Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member UpdateStorageTypeAsync : string * string * Microsoft.Azure.Management.BackupServices.Models.UpdateVaultStorageTypeRequest * Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.BackupServices.OperationResponse&gt;" Usage="iVaultOperations.UpdateStorageTypeAsync (resourceGroupName, resourceName, updateVaultStorageTypeRequest, customRequestHeaders, cancellationToken)" />
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
        <Parameter Name="updateVaultStorageTypeRequest" Type="Microsoft.Azure.Management.BackupServices.Models.UpdateVaultStorageTypeRequest" />
        <Parameter Name="customRequestHeaders" Type="Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">To be added.</param>
        <param name="resourceName">To be added.</param>
        <param name="updateVaultStorageTypeRequest">
            Anforderung zum Update Tresor Speicher Typ
            </param>
        <param name="customRequestHeaders">
            Header Anforderungsparameter.
            </param>
        <param name="cancellationToken">
            Abbruchtoken.
            </param>
        <summary>
            Updates Tresor Speichertyp-Modell.
            </summary>
        <returns>
            Die Definition einer Operation-Antwort.
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UploadCertificateAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.BackupServices.Models.VaultCredUploadCertResponse&gt; UploadCertificateAsync (string resourceGroupName, string resourceName, string certificateName, Microsoft.Azure.Management.BackupServices.Models.VaultCredUploadCertRequest vaultCredUploadCertRequest, Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders customRequestHeaders, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.BackupServices.Models.VaultCredUploadCertResponse&gt; UploadCertificateAsync(string resourceGroupName, string resourceName, string certificateName, class Microsoft.Azure.Management.BackupServices.Models.VaultCredUploadCertRequest vaultCredUploadCertRequest, class Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders customRequestHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.BackupServices.IVaultOperations.UploadCertificateAsync(System.String,System.String,System.String,Microsoft.Azure.Management.BackupServices.Models.VaultCredUploadCertRequest,Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member UploadCertificateAsync : string * string * string * Microsoft.Azure.Management.BackupServices.Models.VaultCredUploadCertRequest * Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.BackupServices.Models.VaultCredUploadCertResponse&gt;" Usage="iVaultOperations.UploadCertificateAsync (resourceGroupName, resourceName, certificateName, vaultCredUploadCertRequest, customRequestHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BackupServicesManagement</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.BackupServices.Models.VaultCredUploadCertResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="resourceName" Type="System.String" />
        <Parameter Name="certificateName" Type="System.String" />
        <Parameter Name="vaultCredUploadCertRequest" Type="Microsoft.Azure.Management.BackupServices.Models.VaultCredUploadCertRequest" />
        <Parameter Name="customRequestHeaders" Type="Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">To be added.</param>
        <param name="resourceName">To be added.</param>
        <param name="certificateName">
            Der Name des Zertifikats.
            </param>
        <param name="vaultCredUploadCertRequest">
            Zertifikatparameter.
            </param>
        <param name="customRequestHeaders">
            Header Anforderungsparameter.
            </param>
        <param name="cancellationToken">
            Abbruchtoken.
            </param>
        <summary>
            Uploads Tresor Zertifikat für Anmeldeinformationen.
            </summary>
        <returns>
            Die Definition einer Antwort Zertifikat.
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>