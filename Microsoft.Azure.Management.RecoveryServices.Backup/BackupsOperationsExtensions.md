<Type Name="BackupsOperationsExtensions" FullName="Microsoft.Azure.Management.RecoveryServices.Backup.BackupsOperationsExtensions">
  <TypeSignature Language="C#" Value="public static class BackupsOperationsExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit BackupsOperationsExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.RecoveryServices.Backup.BackupsOperationsExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module BackupsOperationsExtensions" />
  <TypeSignature Language="F#" Value="type BackupsOperationsExtensions = class" />
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
            Erweiterungsmethoden für BackupsOperations.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="Trigger">
      <MemberSignature Language="C#" Value="public static void Trigger (this Microsoft.Azure.Management.RecoveryServices.Backup.IBackupsOperations operations, string vaultName, string resourceGroupName, string fabricName, string containerName, string protectedItemName, Microsoft.Azure.Management.RecoveryServices.Backup.Models.BackupRequestResource parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void Trigger(class Microsoft.Azure.Management.RecoveryServices.Backup.IBackupsOperations operations, string vaultName, string resourceGroupName, string fabricName, string containerName, string protectedItemName, class Microsoft.Azure.Management.RecoveryServices.Backup.Models.BackupRequestResource parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.RecoveryServices.Backup.BackupsOperationsExtensions.Trigger(Microsoft.Azure.Management.RecoveryServices.Backup.IBackupsOperations,System.String,System.String,System.String,System.String,System.String,Microsoft.Azure.Management.RecoveryServices.Backup.Models.BackupRequestResource)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Sub Trigger (operations As IBackupsOperations, vaultName As String, resourceGroupName As String, fabricName As String, containerName As String, protectedItemName As String, parameters As BackupRequestResource)" />
      <MemberSignature Language="F#" Value="static member Trigger : Microsoft.Azure.Management.RecoveryServices.Backup.IBackupsOperations * string * string * string * string * string * Microsoft.Azure.Management.RecoveryServices.Backup.Models.BackupRequestResource -&gt; unit" Usage="Microsoft.Azure.Management.RecoveryServices.Backup.BackupsOperationsExtensions.Trigger (operations, vaultName, resourceGroupName, fabricName, containerName, protectedItemName, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.RecoveryServices.Backup.IBackupsOperations" RefType="this" />
        <Parameter Name="vaultName" Type="System.String" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="fabricName" Type="System.String" />
        <Parameter Name="containerName" Type="System.String" />
        <Parameter Name="protectedItemName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.RecoveryServices.Backup.Models.BackupRequestResource" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="vaultName">
            Der Name des Recovery Services-Tresor.
            </param>
        <param name="resourceGroupName">
            Der Name der Ressourcengruppe, in dem die Recovery-Tresor Services, ist vorhanden.
            </param>
        <param name="fabricName">
            Name des Fabric, das Sichern des Elements zugeordnet.
            </param>
        <param name="containerName">
            Der Containername das Sichern des Elements zugeordnet.
            </param>
        <param name="protectedItemName">
            Sichern des Elements für die sicherungsanforderungen ausgelöst werden soll.
            </param>
        <param name="parameters">
            Anforderung für die Sicherung der Ressource
            </param>
        <summary>
            Trigger-Sicherung für das angegebene Element gesichert werden. Das ist ein asynchroner Vorgang. Rufen Sie GetProtectedItemOperationResult-API auf, um den Status des Vorgangs zu kennen.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TriggerAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task TriggerAsync (this Microsoft.Azure.Management.RecoveryServices.Backup.IBackupsOperations operations, string vaultName, string resourceGroupName, string fabricName, string containerName, string protectedItemName, Microsoft.Azure.Management.RecoveryServices.Backup.Models.BackupRequestResource parameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task TriggerAsync(class Microsoft.Azure.Management.RecoveryServices.Backup.IBackupsOperations operations, string vaultName, string resourceGroupName, string fabricName, string containerName, string protectedItemName, class Microsoft.Azure.Management.RecoveryServices.Backup.Models.BackupRequestResource parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.RecoveryServices.Backup.BackupsOperationsExtensions.TriggerAsync(Microsoft.Azure.Management.RecoveryServices.Backup.IBackupsOperations,System.String,System.String,System.String,System.String,System.String,Microsoft.Azure.Management.RecoveryServices.Backup.Models.BackupRequestResource,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member TriggerAsync : Microsoft.Azure.Management.RecoveryServices.Backup.IBackupsOperations * string * string * string * string * string * Microsoft.Azure.Management.RecoveryServices.Backup.Models.BackupRequestResource * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.RecoveryServices.Backup.BackupsOperationsExtensions.TriggerAsync (operations, vaultName, resourceGroupName, fabricName, containerName, protectedItemName, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.RecoveryServices.Backup.BackupsOperationsExtensions/&lt;TriggerAsync&gt;d__1))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.RecoveryServices.Backup.IBackupsOperations" RefType="this" />
        <Parameter Name="vaultName" Type="System.String" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="fabricName" Type="System.String" />
        <Parameter Name="containerName" Type="System.String" />
        <Parameter Name="protectedItemName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.RecoveryServices.Backup.Models.BackupRequestResource" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="vaultName">
            Der Name des Recovery Services-Tresor.
            </param>
        <param name="resourceGroupName">
            Der Name der Ressourcengruppe, in dem die Recovery-Tresor Services, ist vorhanden.
            </param>
        <param name="fabricName">
            Name des Fabric, das Sichern des Elements zugeordnet.
            </param>
        <param name="containerName">
            Der Containername das Sichern des Elements zugeordnet.
            </param>
        <param name="protectedItemName">
            Sichern des Elements für die sicherungsanforderungen ausgelöst werden soll.
            </param>
        <param name="parameters">
            Anforderung für die Sicherung der Ressource
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Trigger-Sicherung für das angegebene Element gesichert werden. Das ist ein asynchroner Vorgang. Rufen Sie GetProtectedItemOperationResult-API auf, um den Status des Vorgangs zu kennen.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>