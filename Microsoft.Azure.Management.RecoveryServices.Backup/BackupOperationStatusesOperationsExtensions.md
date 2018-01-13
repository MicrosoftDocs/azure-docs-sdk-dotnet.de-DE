<Type Name="BackupOperationStatusesOperationsExtensions" FullName="Microsoft.Azure.Management.RecoveryServices.Backup.BackupOperationStatusesOperationsExtensions">
  <TypeSignature Language="C#" Value="public static class BackupOperationStatusesOperationsExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit BackupOperationStatusesOperationsExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.RecoveryServices.Backup.BackupOperationStatusesOperationsExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module BackupOperationStatusesOperationsExtensions" />
  <TypeSignature Language="F#" Value="type BackupOperationStatusesOperationsExtensions = class" />
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
            Erweiterungsmethoden für BackupOperationStatusesOperations.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="Get">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.RecoveryServices.Backup.Models.OperationStatus Get (this Microsoft.Azure.Management.RecoveryServices.Backup.IBackupOperationStatusesOperations operations, string vaultName, string resourceGroupName, string operationId);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.RecoveryServices.Backup.Models.OperationStatus Get(class Microsoft.Azure.Management.RecoveryServices.Backup.IBackupOperationStatusesOperations operations, string vaultName, string resourceGroupName, string operationId) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.RecoveryServices.Backup.BackupOperationStatusesOperationsExtensions.Get(Microsoft.Azure.Management.RecoveryServices.Backup.IBackupOperationStatusesOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function Get (operations As IBackupOperationStatusesOperations, vaultName As String, resourceGroupName As String, operationId As String) As OperationStatus" />
      <MemberSignature Language="F#" Value="static member Get : Microsoft.Azure.Management.RecoveryServices.Backup.IBackupOperationStatusesOperations * string * string * string -&gt; Microsoft.Azure.Management.RecoveryServices.Backup.Models.OperationStatus" Usage="Microsoft.Azure.Management.RecoveryServices.Backup.BackupOperationStatusesOperationsExtensions.Get (operations, vaultName, resourceGroupName, operationId)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.RecoveryServices.Backup.Models.OperationStatus</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.RecoveryServices.Backup.IBackupOperationStatusesOperations" RefType="this" />
        <Parameter Name="vaultName" Type="System.String" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="operationId" Type="System.String" />
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
        <param name="operationId">
            OperationID, der den Vorgang darstellt.
            </param>
        <summary>
            Ruft den Status eines Vorgangs wie z. B. das Auslösen einer sicherungs wiederherstellen.
            Der Status kann in Bearbeitung, abgeschlossen oder fehlerhaft sein. Sie können die OperationStatus-Enumeration für alle möglichen Status eines Vorgangs verweisen. Einige Vorgänge Aufträge erstellt werden. Diese Methode gibt die Liste der Aufträge auf, wenn der Vorgang abgeschlossen ist.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.RecoveryServices.Backup.Models.OperationStatus&gt; GetAsync (this Microsoft.Azure.Management.RecoveryServices.Backup.IBackupOperationStatusesOperations operations, string vaultName, string resourceGroupName, string operationId, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.RecoveryServices.Backup.Models.OperationStatus&gt; GetAsync(class Microsoft.Azure.Management.RecoveryServices.Backup.IBackupOperationStatusesOperations operations, string vaultName, string resourceGroupName, string operationId, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.RecoveryServices.Backup.BackupOperationStatusesOperationsExtensions.GetAsync(Microsoft.Azure.Management.RecoveryServices.Backup.IBackupOperationStatusesOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetAsync : Microsoft.Azure.Management.RecoveryServices.Backup.IBackupOperationStatusesOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.RecoveryServices.Backup.Models.OperationStatus&gt;" Usage="Microsoft.Azure.Management.RecoveryServices.Backup.BackupOperationStatusesOperationsExtensions.GetAsync (operations, vaultName, resourceGroupName, operationId, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.RecoveryServices.Backup.BackupOperationStatusesOperationsExtensions/&lt;GetAsync&gt;d__1))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.RecoveryServices.Backup.Models.OperationStatus&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.RecoveryServices.Backup.IBackupOperationStatusesOperations" RefType="this" />
        <Parameter Name="vaultName" Type="System.String" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="operationId" Type="System.String" />
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
        <param name="operationId">
            OperationID, der den Vorgang darstellt.
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Ruft den Status eines Vorgangs wie z. B. das Auslösen einer sicherungs wiederherstellen.
            Der Status kann in Bearbeitung, abgeschlossen oder fehlerhaft sein. Sie können die OperationStatus-Enumeration für alle möglichen Status eines Vorgangs verweisen. Einige Vorgänge Aufträge erstellt werden. Diese Methode gibt die Liste der Aufträge auf, wenn der Vorgang abgeschlossen ist.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>