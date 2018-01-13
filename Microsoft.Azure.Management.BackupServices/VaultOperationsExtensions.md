<Type Name="VaultOperationsExtensions" FullName="Microsoft.Azure.Management.BackupServices.VaultOperationsExtensions">
  <TypeSignature Language="C#" Value="public static class VaultOperationsExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit VaultOperationsExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.BackupServices.VaultOperationsExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module VaultOperationsExtensions" />
  <TypeSignature Language="F#" Value="type VaultOperationsExtensions = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.BackupServicesManagement</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>To be added.</summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="CreateOrUpdate">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.BackupServices.Models.AzureBackupVaultGetResponse CreateOrUpdate (this Microsoft.Azure.Management.BackupServices.IVaultOperations operations, string resourceGroupName, string resourceName, Microsoft.Azure.Management.BackupServices.Models.AzureBackupVaultCreateOrUpdateParameters parameters, Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders customRequestHeaders);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.BackupServices.Models.AzureBackupVaultGetResponse CreateOrUpdate(class Microsoft.Azure.Management.BackupServices.IVaultOperations operations, string resourceGroupName, string resourceName, class Microsoft.Azure.Management.BackupServices.Models.AzureBackupVaultCreateOrUpdateParameters parameters, class Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders customRequestHeaders) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.BackupServices.VaultOperationsExtensions.CreateOrUpdate(Microsoft.Azure.Management.BackupServices.IVaultOperations,System.String,System.String,Microsoft.Azure.Management.BackupServices.Models.AzureBackupVaultCreateOrUpdateParameters,Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders)" />
      <MemberSignature Language="F#" Value="static member CreateOrUpdate : Microsoft.Azure.Management.BackupServices.IVaultOperations * string * string * Microsoft.Azure.Management.BackupServices.Models.AzureBackupVaultCreateOrUpdateParameters * Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders -&gt; Microsoft.Azure.Management.BackupServices.Models.AzureBackupVaultGetResponse" Usage="Microsoft.Azure.Management.BackupServices.VaultOperationsExtensions.CreateOrUpdate (operations, resourceGroupName, resourceName, parameters, customRequestHeaders)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BackupServicesManagement</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.BackupServices.Models.AzureBackupVaultGetResponse</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.BackupServices.IVaultOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="resourceName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.BackupServices.Models.AzureBackupVaultCreateOrUpdateParameters" />
        <Parameter Name="customRequestHeaders" Type="Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders" />
      </Parameters>
      <Docs>
        <param name="operations">
            Verweis auf die Microsoft.Azure.Management.BackupServices.IVaultOperations.
            </param>
        <param name="resourceGroupName">
            Erforderlich. Der Name der Ressourcengruppe, in welche Tresor gehört
            </param>
        <param name="resourceName">
            Erforderlich. Der Name des Tresors
            </param>
        <param name="parameters">
            Erforderlich. Parameter zum Erstellen oder aktualisieren den Tresor
            </param>
        <param name="customRequestHeaders">
            Optional. Header Anforderungsparameter.
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
    <Member MemberName="CreateOrUpdateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.BackupServices.Models.AzureBackupVaultGetResponse&gt; CreateOrUpdateAsync (this Microsoft.Azure.Management.BackupServices.IVaultOperations operations, string resourceGroupName, string resourceName, Microsoft.Azure.Management.BackupServices.Models.AzureBackupVaultCreateOrUpdateParameters parameters, Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders customRequestHeaders);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.BackupServices.Models.AzureBackupVaultGetResponse&gt; CreateOrUpdateAsync(class Microsoft.Azure.Management.BackupServices.IVaultOperations operations, string resourceGroupName, string resourceName, class Microsoft.Azure.Management.BackupServices.Models.AzureBackupVaultCreateOrUpdateParameters parameters, class Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders customRequestHeaders) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.BackupServices.VaultOperationsExtensions.CreateOrUpdateAsync(Microsoft.Azure.Management.BackupServices.IVaultOperations,System.String,System.String,Microsoft.Azure.Management.BackupServices.Models.AzureBackupVaultCreateOrUpdateParameters,Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders)" />
      <MemberSignature Language="F#" Value="static member CreateOrUpdateAsync : Microsoft.Azure.Management.BackupServices.IVaultOperations * string * string * Microsoft.Azure.Management.BackupServices.Models.AzureBackupVaultCreateOrUpdateParameters * Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.BackupServices.Models.AzureBackupVaultGetResponse&gt;" Usage="Microsoft.Azure.Management.BackupServices.VaultOperationsExtensions.CreateOrUpdateAsync (operations, resourceGroupName, resourceName, parameters, customRequestHeaders)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BackupServicesManagement</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.BackupServices.Models.AzureBackupVaultGetResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.BackupServices.IVaultOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="resourceName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.BackupServices.Models.AzureBackupVaultCreateOrUpdateParameters" />
        <Parameter Name="customRequestHeaders" Type="Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders" />
      </Parameters>
      <Docs>
        <param name="operations">
            Verweis auf die Microsoft.Azure.Management.BackupServices.IVaultOperations.
            </param>
        <param name="resourceGroupName">
            Erforderlich. Der Name der Ressourcengruppe, in welche Tresor gehört
            </param>
        <param name="resourceName">
            Erforderlich. Der Name des Tresors
            </param>
        <param name="parameters">
            Erforderlich. Parameter zum Erstellen oder aktualisieren den Tresor
            </param>
        <param name="customRequestHeaders">
            Optional. Header Anforderungsparameter.
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
    <Member MemberName="Delete">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.BackupServices.Models.AzureBackupVaultGetResponse Delete (this Microsoft.Azure.Management.BackupServices.IVaultOperations operations, string resourceGroupName, string resourceName, Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders customRequestHeaders);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.BackupServices.Models.AzureBackupVaultGetResponse Delete(class Microsoft.Azure.Management.BackupServices.IVaultOperations operations, string resourceGroupName, string resourceName, class Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders customRequestHeaders) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.BackupServices.VaultOperationsExtensions.Delete(Microsoft.Azure.Management.BackupServices.IVaultOperations,System.String,System.String,Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders)" />
      <MemberSignature Language="F#" Value="static member Delete : Microsoft.Azure.Management.BackupServices.IVaultOperations * string * string * Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders -&gt; Microsoft.Azure.Management.BackupServices.Models.AzureBackupVaultGetResponse" Usage="Microsoft.Azure.Management.BackupServices.VaultOperationsExtensions.Delete (operations, resourceGroupName, resourceName, customRequestHeaders)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BackupServicesManagement</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.BackupServices.Models.AzureBackupVaultGetResponse</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.BackupServices.IVaultOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="resourceName" Type="System.String" />
        <Parameter Name="customRequestHeaders" Type="Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders" />
      </Parameters>
      <Docs>
        <param name="operations">
            Verweis auf die Microsoft.Azure.Management.BackupServices.IVaultOperations.
            </param>
        <param name="resourceGroupName">
            Erforderlich. Der Name der Ressourcengruppe, in welche Tresor gehört
            </param>
        <param name="resourceName">
            Erforderlich. Der Name des Tresors
            </param>
        <param name="customRequestHeaders">
            Optional. Header Anforderungsparameter.
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
    <Member MemberName="DeleteAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.BackupServices.Models.AzureBackupVaultGetResponse&gt; DeleteAsync (this Microsoft.Azure.Management.BackupServices.IVaultOperations operations, string resourceGroupName, string resourceName, Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders customRequestHeaders);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.BackupServices.Models.AzureBackupVaultGetResponse&gt; DeleteAsync(class Microsoft.Azure.Management.BackupServices.IVaultOperations operations, string resourceGroupName, string resourceName, class Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders customRequestHeaders) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.BackupServices.VaultOperationsExtensions.DeleteAsync(Microsoft.Azure.Management.BackupServices.IVaultOperations,System.String,System.String,Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders)" />
      <MemberSignature Language="F#" Value="static member DeleteAsync : Microsoft.Azure.Management.BackupServices.IVaultOperations * string * string * Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.BackupServices.Models.AzureBackupVaultGetResponse&gt;" Usage="Microsoft.Azure.Management.BackupServices.VaultOperationsExtensions.DeleteAsync (operations, resourceGroupName, resourceName, customRequestHeaders)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BackupServicesManagement</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.BackupServices.Models.AzureBackupVaultGetResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.BackupServices.IVaultOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="resourceName" Type="System.String" />
        <Parameter Name="customRequestHeaders" Type="Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders" />
      </Parameters>
      <Docs>
        <param name="operations">
            Verweis auf die Microsoft.Azure.Management.BackupServices.IVaultOperations.
            </param>
        <param name="resourceGroupName">
            Erforderlich. Der Name der Ressourcengruppe, in welche Tresor gehört
            </param>
        <param name="resourceName">
            Erforderlich. Der Name des Tresors
            </param>
        <param name="customRequestHeaders">
            Optional. Header Anforderungsparameter.
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
    <Member MemberName="Get">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.BackupServices.Models.AzureBackupVaultGetResponse Get (this Microsoft.Azure.Management.BackupServices.IVaultOperations operations, string resourceGroupName, string resourceName, Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders customRequestHeaders);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.BackupServices.Models.AzureBackupVaultGetResponse Get(class Microsoft.Azure.Management.BackupServices.IVaultOperations operations, string resourceGroupName, string resourceName, class Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders customRequestHeaders) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.BackupServices.VaultOperationsExtensions.Get(Microsoft.Azure.Management.BackupServices.IVaultOperations,System.String,System.String,Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders)" />
      <MemberSignature Language="F#" Value="static member Get : Microsoft.Azure.Management.BackupServices.IVaultOperations * string * string * Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders -&gt; Microsoft.Azure.Management.BackupServices.Models.AzureBackupVaultGetResponse" Usage="Microsoft.Azure.Management.BackupServices.VaultOperationsExtensions.Get (operations, resourceGroupName, resourceName, customRequestHeaders)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BackupServicesManagement</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.BackupServices.Models.AzureBackupVaultGetResponse</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.BackupServices.IVaultOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="resourceName" Type="System.String" />
        <Parameter Name="customRequestHeaders" Type="Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders" />
      </Parameters>
      <Docs>
        <param name="operations">
            Verweis auf die Microsoft.Azure.Management.BackupServices.IVaultOperations.
            </param>
        <param name="resourceGroupName">
            Erforderlich. Der Name der Ressourcengruppe, in welche Tresor gehört
            </param>
        <param name="resourceName">
            Erforderlich. Der Name des Tresors
            </param>
        <param name="customRequestHeaders">
            Optional. Header Anforderungsparameter.
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
    <Member MemberName="GetAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.BackupServices.Models.AzureBackupVaultGetResponse&gt; GetAsync (this Microsoft.Azure.Management.BackupServices.IVaultOperations operations, string resourceGroupName, string resourceName, Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders customRequestHeaders);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.BackupServices.Models.AzureBackupVaultGetResponse&gt; GetAsync(class Microsoft.Azure.Management.BackupServices.IVaultOperations operations, string resourceGroupName, string resourceName, class Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders customRequestHeaders) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.BackupServices.VaultOperationsExtensions.GetAsync(Microsoft.Azure.Management.BackupServices.IVaultOperations,System.String,System.String,Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders)" />
      <MemberSignature Language="F#" Value="static member GetAsync : Microsoft.Azure.Management.BackupServices.IVaultOperations * string * string * Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.BackupServices.Models.AzureBackupVaultGetResponse&gt;" Usage="Microsoft.Azure.Management.BackupServices.VaultOperationsExtensions.GetAsync (operations, resourceGroupName, resourceName, customRequestHeaders)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BackupServicesManagement</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.BackupServices.Models.AzureBackupVaultGetResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.BackupServices.IVaultOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="resourceName" Type="System.String" />
        <Parameter Name="customRequestHeaders" Type="Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders" />
      </Parameters>
      <Docs>
        <param name="operations">
            Verweis auf die Microsoft.Azure.Management.BackupServices.IVaultOperations.
            </param>
        <param name="resourceGroupName">
            Erforderlich. Der Name der Ressourcengruppe, in welche Tresor gehört
            </param>
        <param name="resourceName">
            Erforderlich. Der Name des Tresors
            </param>
        <param name="customRequestHeaders">
            Optional. Header Anforderungsparameter.
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
    <Member MemberName="GetResourceStorageConfig">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.BackupServices.Models.GetResourceStorageConfigResponse GetResourceStorageConfig (this Microsoft.Azure.Management.BackupServices.IVaultOperations operations, string resourceGroupName, string resourceName, Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders customRequestHeaders);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.BackupServices.Models.GetResourceStorageConfigResponse GetResourceStorageConfig(class Microsoft.Azure.Management.BackupServices.IVaultOperations operations, string resourceGroupName, string resourceName, class Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders customRequestHeaders) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.BackupServices.VaultOperationsExtensions.GetResourceStorageConfig(Microsoft.Azure.Management.BackupServices.IVaultOperations,System.String,System.String,Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders)" />
      <MemberSignature Language="F#" Value="static member GetResourceStorageConfig : Microsoft.Azure.Management.BackupServices.IVaultOperations * string * string * Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders -&gt; Microsoft.Azure.Management.BackupServices.Models.GetResourceStorageConfigResponse" Usage="Microsoft.Azure.Management.BackupServices.VaultOperationsExtensions.GetResourceStorageConfig (operations, resourceGroupName, resourceName, customRequestHeaders)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BackupServicesManagement</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.BackupServices.Models.GetResourceStorageConfigResponse</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.BackupServices.IVaultOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="resourceName" Type="System.String" />
        <Parameter Name="customRequestHeaders" Type="Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders" />
      </Parameters>
      <Docs>
        <param name="operations">
            Verweis auf die Microsoft.Azure.Management.BackupServices.IVaultOperations.
            </param>
        <param name="resourceGroupName">
            Erforderlich. Der Name der Ressourcengruppe, in welche Tresor gehört
            </param>
        <param name="resourceName">
            Erforderlich. Der Name des Tresors
            </param>
        <param name="customRequestHeaders">
            Optional. Header Anforderungsparameter.
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
    <Member MemberName="GetResourceStorageConfigAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.BackupServices.Models.GetResourceStorageConfigResponse&gt; GetResourceStorageConfigAsync (this Microsoft.Azure.Management.BackupServices.IVaultOperations operations, string resourceGroupName, string resourceName, Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders customRequestHeaders);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.BackupServices.Models.GetResourceStorageConfigResponse&gt; GetResourceStorageConfigAsync(class Microsoft.Azure.Management.BackupServices.IVaultOperations operations, string resourceGroupName, string resourceName, class Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders customRequestHeaders) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.BackupServices.VaultOperationsExtensions.GetResourceStorageConfigAsync(Microsoft.Azure.Management.BackupServices.IVaultOperations,System.String,System.String,Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders)" />
      <MemberSignature Language="F#" Value="static member GetResourceStorageConfigAsync : Microsoft.Azure.Management.BackupServices.IVaultOperations * string * string * Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.BackupServices.Models.GetResourceStorageConfigResponse&gt;" Usage="Microsoft.Azure.Management.BackupServices.VaultOperationsExtensions.GetResourceStorageConfigAsync (operations, resourceGroupName, resourceName, customRequestHeaders)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BackupServicesManagement</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.BackupServices.Models.GetResourceStorageConfigResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.BackupServices.IVaultOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="resourceName" Type="System.String" />
        <Parameter Name="customRequestHeaders" Type="Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders" />
      </Parameters>
      <Docs>
        <param name="operations">
            Verweis auf die Microsoft.Azure.Management.BackupServices.IVaultOperations.
            </param>
        <param name="resourceGroupName">
            Erforderlich. Der Name der Ressourcengruppe, in welche Tresor gehört
            </param>
        <param name="resourceName">
            Erforderlich. Der Name des Tresors
            </param>
        <param name="customRequestHeaders">
            Optional. Header Anforderungsparameter.
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
    <Member MemberName="List">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.BackupServices.Models.AzureBackupVaultListResponse List (this Microsoft.Azure.Management.BackupServices.IVaultOperations operations, int top, Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders customRequestHeaders);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.BackupServices.Models.AzureBackupVaultListResponse List(class Microsoft.Azure.Management.BackupServices.IVaultOperations operations, int32 top, class Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders customRequestHeaders) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.BackupServices.VaultOperationsExtensions.List(Microsoft.Azure.Management.BackupServices.IVaultOperations,System.Int32,Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders)" />
      <MemberSignature Language="F#" Value="static member List : Microsoft.Azure.Management.BackupServices.IVaultOperations * int * Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders -&gt; Microsoft.Azure.Management.BackupServices.Models.AzureBackupVaultListResponse" Usage="Microsoft.Azure.Management.BackupServices.VaultOperationsExtensions.List (operations, top, customRequestHeaders)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BackupServicesManagement</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.BackupServices.Models.AzureBackupVaultListResponse</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.BackupServices.IVaultOperations" RefType="this" />
        <Parameter Name="top" Type="System.Int32" />
        <Parameter Name="customRequestHeaders" Type="Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders" />
      </Parameters>
      <Docs>
        <param name="operations">
            Verweis auf die Microsoft.Azure.Management.BackupServices.IVaultOperations.
            </param>
        <param name="top">
            Erforderlich. Maximale Anzahl der zurückzugebenden Ergebnisseite.
            </param>
        <param name="customRequestHeaders">
            Optional. Header Anforderungsparameter.
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
    <Member MemberName="ListAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.BackupServices.Models.AzureBackupVaultListResponse&gt; ListAsync (this Microsoft.Azure.Management.BackupServices.IVaultOperations operations, int top, Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders customRequestHeaders);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.BackupServices.Models.AzureBackupVaultListResponse&gt; ListAsync(class Microsoft.Azure.Management.BackupServices.IVaultOperations operations, int32 top, class Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders customRequestHeaders) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.BackupServices.VaultOperationsExtensions.ListAsync(Microsoft.Azure.Management.BackupServices.IVaultOperations,System.Int32,Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders)" />
      <MemberSignature Language="F#" Value="static member ListAsync : Microsoft.Azure.Management.BackupServices.IVaultOperations * int * Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.BackupServices.Models.AzureBackupVaultListResponse&gt;" Usage="Microsoft.Azure.Management.BackupServices.VaultOperationsExtensions.ListAsync (operations, top, customRequestHeaders)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BackupServicesManagement</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.BackupServices.Models.AzureBackupVaultListResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.BackupServices.IVaultOperations" RefType="this" />
        <Parameter Name="top" Type="System.Int32" />
        <Parameter Name="customRequestHeaders" Type="Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders" />
      </Parameters>
      <Docs>
        <param name="operations">
            Verweis auf die Microsoft.Azure.Management.BackupServices.IVaultOperations.
            </param>
        <param name="top">
            Erforderlich. Maximale Anzahl der zurückzugebenden Ergebnisseite.
            </param>
        <param name="customRequestHeaders">
            Optional. Header Anforderungsparameter.
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
    <Member MemberName="ListByResourceGroup">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.BackupServices.Models.AzureBackupVaultListResponse ListByResourceGroup (this Microsoft.Azure.Management.BackupServices.IVaultOperations operations, string resourceGroupName, int top, Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders customRequestHeaders);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.BackupServices.Models.AzureBackupVaultListResponse ListByResourceGroup(class Microsoft.Azure.Management.BackupServices.IVaultOperations operations, string resourceGroupName, int32 top, class Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders customRequestHeaders) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.BackupServices.VaultOperationsExtensions.ListByResourceGroup(Microsoft.Azure.Management.BackupServices.IVaultOperations,System.String,System.Int32,Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders)" />
      <MemberSignature Language="F#" Value="static member ListByResourceGroup : Microsoft.Azure.Management.BackupServices.IVaultOperations * string * int * Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders -&gt; Microsoft.Azure.Management.BackupServices.Models.AzureBackupVaultListResponse" Usage="Microsoft.Azure.Management.BackupServices.VaultOperationsExtensions.ListByResourceGroup (operations, resourceGroupName, top, customRequestHeaders)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BackupServicesManagement</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.BackupServices.Models.AzureBackupVaultListResponse</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.BackupServices.IVaultOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="top" Type="System.Int32" />
        <Parameter Name="customRequestHeaders" Type="Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders" />
      </Parameters>
      <Docs>
        <param name="operations">
            Verweis auf die Microsoft.Azure.Management.BackupServices.IVaultOperations.
            </param>
        <param name="resourceGroupName">
            Optional. Ein optionales Argument, das den Namen der Ressourcengruppe angibt, die den Satz von Tresoren einschränkt, die zurückgegeben werden.
            </param>
        <param name="top">
            Erforderlich. Maximale Anzahl der zurückzugebenden Ergebnisseite.
            </param>
        <param name="customRequestHeaders">
            Optional. Header Anforderungsparameter.
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
    <Member MemberName="ListByResourceGroupAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.BackupServices.Models.AzureBackupVaultListResponse&gt; ListByResourceGroupAsync (this Microsoft.Azure.Management.BackupServices.IVaultOperations operations, string resourceGroupName, int top, Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders customRequestHeaders);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.BackupServices.Models.AzureBackupVaultListResponse&gt; ListByResourceGroupAsync(class Microsoft.Azure.Management.BackupServices.IVaultOperations operations, string resourceGroupName, int32 top, class Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders customRequestHeaders) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.BackupServices.VaultOperationsExtensions.ListByResourceGroupAsync(Microsoft.Azure.Management.BackupServices.IVaultOperations,System.String,System.Int32,Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders)" />
      <MemberSignature Language="F#" Value="static member ListByResourceGroupAsync : Microsoft.Azure.Management.BackupServices.IVaultOperations * string * int * Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.BackupServices.Models.AzureBackupVaultListResponse&gt;" Usage="Microsoft.Azure.Management.BackupServices.VaultOperationsExtensions.ListByResourceGroupAsync (operations, resourceGroupName, top, customRequestHeaders)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BackupServicesManagement</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.BackupServices.Models.AzureBackupVaultListResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.BackupServices.IVaultOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="top" Type="System.Int32" />
        <Parameter Name="customRequestHeaders" Type="Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders" />
      </Parameters>
      <Docs>
        <param name="operations">
            Verweis auf die Microsoft.Azure.Management.BackupServices.IVaultOperations.
            </param>
        <param name="resourceGroupName">
            Optional. Ein optionales Argument, das den Namen der Ressourcengruppe angibt, die den Satz von Tresoren einschränkt, die zurückgegeben werden.
            </param>
        <param name="top">
            Erforderlich. Maximale Anzahl der zurückzugebenden Ergebnisseite.
            </param>
        <param name="customRequestHeaders">
            Optional. Header Anforderungsparameter.
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
    <Member MemberName="UpdateStorageType">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.BackupServices.OperationResponse UpdateStorageType (this Microsoft.Azure.Management.BackupServices.IVaultOperations operations, string resourceGroupName, string resourceName, Microsoft.Azure.Management.BackupServices.Models.UpdateVaultStorageTypeRequest updateVaultStorageTypeRequest, Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders customRequestHeaders);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.BackupServices.OperationResponse UpdateStorageType(class Microsoft.Azure.Management.BackupServices.IVaultOperations operations, string resourceGroupName, string resourceName, class Microsoft.Azure.Management.BackupServices.Models.UpdateVaultStorageTypeRequest updateVaultStorageTypeRequest, class Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders customRequestHeaders) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.BackupServices.VaultOperationsExtensions.UpdateStorageType(Microsoft.Azure.Management.BackupServices.IVaultOperations,System.String,System.String,Microsoft.Azure.Management.BackupServices.Models.UpdateVaultStorageTypeRequest,Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders)" />
      <MemberSignature Language="F#" Value="static member UpdateStorageType : Microsoft.Azure.Management.BackupServices.IVaultOperations * string * string * Microsoft.Azure.Management.BackupServices.Models.UpdateVaultStorageTypeRequest * Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders -&gt; Microsoft.Azure.Management.BackupServices.OperationResponse" Usage="Microsoft.Azure.Management.BackupServices.VaultOperationsExtensions.UpdateStorageType (operations, resourceGroupName, resourceName, updateVaultStorageTypeRequest, customRequestHeaders)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BackupServicesManagement</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.BackupServices.OperationResponse</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.BackupServices.IVaultOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="resourceName" Type="System.String" />
        <Parameter Name="updateVaultStorageTypeRequest" Type="Microsoft.Azure.Management.BackupServices.Models.UpdateVaultStorageTypeRequest" />
        <Parameter Name="customRequestHeaders" Type="Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders" />
      </Parameters>
      <Docs>
        <param name="operations">
            Verweis auf die Microsoft.Azure.Management.BackupServices.IVaultOperations.
            </param>
        <param name="resourceGroupName">
            Erforderlich.
            </param>
        <param name="resourceName">
            Erforderlich.
            </param>
        <param name="updateVaultStorageTypeRequest">
            Erforderlich. Anforderung zum Update Tresor Speicher Typ
            </param>
        <param name="customRequestHeaders">
            Optional. Header Anforderungsparameter.
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
    <Member MemberName="UpdateStorageTypeAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.BackupServices.OperationResponse&gt; UpdateStorageTypeAsync (this Microsoft.Azure.Management.BackupServices.IVaultOperations operations, string resourceGroupName, string resourceName, Microsoft.Azure.Management.BackupServices.Models.UpdateVaultStorageTypeRequest updateVaultStorageTypeRequest, Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders customRequestHeaders);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.BackupServices.OperationResponse&gt; UpdateStorageTypeAsync(class Microsoft.Azure.Management.BackupServices.IVaultOperations operations, string resourceGroupName, string resourceName, class Microsoft.Azure.Management.BackupServices.Models.UpdateVaultStorageTypeRequest updateVaultStorageTypeRequest, class Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders customRequestHeaders) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.BackupServices.VaultOperationsExtensions.UpdateStorageTypeAsync(Microsoft.Azure.Management.BackupServices.IVaultOperations,System.String,System.String,Microsoft.Azure.Management.BackupServices.Models.UpdateVaultStorageTypeRequest,Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders)" />
      <MemberSignature Language="F#" Value="static member UpdateStorageTypeAsync : Microsoft.Azure.Management.BackupServices.IVaultOperations * string * string * Microsoft.Azure.Management.BackupServices.Models.UpdateVaultStorageTypeRequest * Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.BackupServices.OperationResponse&gt;" Usage="Microsoft.Azure.Management.BackupServices.VaultOperationsExtensions.UpdateStorageTypeAsync (operations, resourceGroupName, resourceName, updateVaultStorageTypeRequest, customRequestHeaders)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BackupServicesManagement</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.BackupServices.OperationResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.BackupServices.IVaultOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="resourceName" Type="System.String" />
        <Parameter Name="updateVaultStorageTypeRequest" Type="Microsoft.Azure.Management.BackupServices.Models.UpdateVaultStorageTypeRequest" />
        <Parameter Name="customRequestHeaders" Type="Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders" />
      </Parameters>
      <Docs>
        <param name="operations">
            Verweis auf die Microsoft.Azure.Management.BackupServices.IVaultOperations.
            </param>
        <param name="resourceGroupName">
            Erforderlich.
            </param>
        <param name="resourceName">
            Erforderlich.
            </param>
        <param name="updateVaultStorageTypeRequest">
            Erforderlich. Anforderung zum Update Tresor Speicher Typ
            </param>
        <param name="customRequestHeaders">
            Optional. Header Anforderungsparameter.
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
    <Member MemberName="UploadCertificate">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.BackupServices.Models.VaultCredUploadCertResponse UploadCertificate (this Microsoft.Azure.Management.BackupServices.IVaultOperations operations, string resourceGroupName, string resourceName, string certificateName, Microsoft.Azure.Management.BackupServices.Models.VaultCredUploadCertRequest vaultCredUploadCertRequest, Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders customRequestHeaders);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.BackupServices.Models.VaultCredUploadCertResponse UploadCertificate(class Microsoft.Azure.Management.BackupServices.IVaultOperations operations, string resourceGroupName, string resourceName, string certificateName, class Microsoft.Azure.Management.BackupServices.Models.VaultCredUploadCertRequest vaultCredUploadCertRequest, class Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders customRequestHeaders) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.BackupServices.VaultOperationsExtensions.UploadCertificate(Microsoft.Azure.Management.BackupServices.IVaultOperations,System.String,System.String,System.String,Microsoft.Azure.Management.BackupServices.Models.VaultCredUploadCertRequest,Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders)" />
      <MemberSignature Language="F#" Value="static member UploadCertificate : Microsoft.Azure.Management.BackupServices.IVaultOperations * string * string * string * Microsoft.Azure.Management.BackupServices.Models.VaultCredUploadCertRequest * Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders -&gt; Microsoft.Azure.Management.BackupServices.Models.VaultCredUploadCertResponse" Usage="Microsoft.Azure.Management.BackupServices.VaultOperationsExtensions.UploadCertificate (operations, resourceGroupName, resourceName, certificateName, vaultCredUploadCertRequest, customRequestHeaders)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BackupServicesManagement</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.BackupServices.Models.VaultCredUploadCertResponse</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.BackupServices.IVaultOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="resourceName" Type="System.String" />
        <Parameter Name="certificateName" Type="System.String" />
        <Parameter Name="vaultCredUploadCertRequest" Type="Microsoft.Azure.Management.BackupServices.Models.VaultCredUploadCertRequest" />
        <Parameter Name="customRequestHeaders" Type="Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders" />
      </Parameters>
      <Docs>
        <param name="operations">
            Verweis auf die Microsoft.Azure.Management.BackupServices.IVaultOperations.
            </param>
        <param name="resourceGroupName">
            Erforderlich.
            </param>
        <param name="resourceName">
            Erforderlich.
            </param>
        <param name="certificateName">
            Erforderlich. Der Name des Zertifikats.
            </param>
        <param name="vaultCredUploadCertRequest">
            Erforderlich. Zertifikatparameter.
            </param>
        <param name="customRequestHeaders">
            Optional. Header Anforderungsparameter.
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
    <Member MemberName="UploadCertificateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.BackupServices.Models.VaultCredUploadCertResponse&gt; UploadCertificateAsync (this Microsoft.Azure.Management.BackupServices.IVaultOperations operations, string resourceGroupName, string resourceName, string certificateName, Microsoft.Azure.Management.BackupServices.Models.VaultCredUploadCertRequest vaultCredUploadCertRequest, Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders customRequestHeaders);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.BackupServices.Models.VaultCredUploadCertResponse&gt; UploadCertificateAsync(class Microsoft.Azure.Management.BackupServices.IVaultOperations operations, string resourceGroupName, string resourceName, string certificateName, class Microsoft.Azure.Management.BackupServices.Models.VaultCredUploadCertRequest vaultCredUploadCertRequest, class Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders customRequestHeaders) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.BackupServices.VaultOperationsExtensions.UploadCertificateAsync(Microsoft.Azure.Management.BackupServices.IVaultOperations,System.String,System.String,System.String,Microsoft.Azure.Management.BackupServices.Models.VaultCredUploadCertRequest,Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders)" />
      <MemberSignature Language="F#" Value="static member UploadCertificateAsync : Microsoft.Azure.Management.BackupServices.IVaultOperations * string * string * string * Microsoft.Azure.Management.BackupServices.Models.VaultCredUploadCertRequest * Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.BackupServices.Models.VaultCredUploadCertResponse&gt;" Usage="Microsoft.Azure.Management.BackupServices.VaultOperationsExtensions.UploadCertificateAsync (operations, resourceGroupName, resourceName, certificateName, vaultCredUploadCertRequest, customRequestHeaders)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BackupServicesManagement</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.BackupServices.Models.VaultCredUploadCertResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.BackupServices.IVaultOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="resourceName" Type="System.String" />
        <Parameter Name="certificateName" Type="System.String" />
        <Parameter Name="vaultCredUploadCertRequest" Type="Microsoft.Azure.Management.BackupServices.Models.VaultCredUploadCertRequest" />
        <Parameter Name="customRequestHeaders" Type="Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders" />
      </Parameters>
      <Docs>
        <param name="operations">
            Verweis auf die Microsoft.Azure.Management.BackupServices.IVaultOperations.
            </param>
        <param name="resourceGroupName">
            Erforderlich.
            </param>
        <param name="resourceName">
            Erforderlich.
            </param>
        <param name="certificateName">
            Erforderlich. Der Name des Zertifikats.
            </param>
        <param name="vaultCredUploadCertRequest">
            Erforderlich. Zertifikatparameter.
            </param>
        <param name="customRequestHeaders">
            Optional. Header Anforderungsparameter.
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