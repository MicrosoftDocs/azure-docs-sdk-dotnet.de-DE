<Type Name="BackupOperationResultsOperationsExtensions" FullName="Microsoft.Azure.Management.RecoveryServices.Backup.BackupOperationResultsOperationsExtensions">
  <TypeSignature Language="C#" Value="public static class BackupOperationResultsOperationsExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit BackupOperationResultsOperationsExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.RecoveryServices.Backup.BackupOperationResultsOperationsExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module BackupOperationResultsOperationsExtensions" />
  <TypeSignature Language="F#" Value="type BackupOperationResultsOperationsExtensions = class" />
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
            Erweiterungsmethoden für BackupOperationResultsOperations.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="Get">
      <MemberSignature Language="C#" Value="public static void Get (this Microsoft.Azure.Management.RecoveryServices.Backup.IBackupOperationResultsOperations operations, string vaultName, string resourceGroupName, string operationId);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void Get(class Microsoft.Azure.Management.RecoveryServices.Backup.IBackupOperationResultsOperations operations, string vaultName, string resourceGroupName, string operationId) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.RecoveryServices.Backup.BackupOperationResultsOperationsExtensions.Get(Microsoft.Azure.Management.RecoveryServices.Backup.IBackupOperationResultsOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Sub Get (operations As IBackupOperationResultsOperations, vaultName As String, resourceGroupName As String, operationId As String)" />
      <MemberSignature Language="F#" Value="static member Get : Microsoft.Azure.Management.RecoveryServices.Backup.IBackupOperationResultsOperations * string * string * string -&gt; unit" Usage="Microsoft.Azure.Management.RecoveryServices.Backup.BackupOperationResultsOperationsExtensions.Get (operations, vaultName, resourceGroupName, operationId)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.RecoveryServices.Backup.IBackupOperationResultsOperations" RefType="this" />
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
            Enthält der Status der Delete-Vorgänge wie etwa löschen Element gesichert. Nachdem der Vorgang gestartet wurde, wird der Statuscode der Antwort akzeptiert werden. Es wird weiterhin in diesem Status bis zum Abschluss erreicht. Bei erfolgreichem Abschluss wird der Statuscode OK sein. Diese Methode erwartet OperationID als Argument an. OperationID ist Teil des Location-Header der Antworten für den Vorgang.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task GetAsync (this Microsoft.Azure.Management.RecoveryServices.Backup.IBackupOperationResultsOperations operations, string vaultName, string resourceGroupName, string operationId, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task GetAsync(class Microsoft.Azure.Management.RecoveryServices.Backup.IBackupOperationResultsOperations operations, string vaultName, string resourceGroupName, string operationId, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.RecoveryServices.Backup.BackupOperationResultsOperationsExtensions.GetAsync(Microsoft.Azure.Management.RecoveryServices.Backup.IBackupOperationResultsOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetAsync : Microsoft.Azure.Management.RecoveryServices.Backup.IBackupOperationResultsOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.RecoveryServices.Backup.BackupOperationResultsOperationsExtensions.GetAsync (operations, vaultName, resourceGroupName, operationId, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.RecoveryServices.Backup.BackupOperationResultsOperationsExtensions/&lt;GetAsync&gt;d__1))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.RecoveryServices.Backup.IBackupOperationResultsOperations" RefType="this" />
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
            Enthält der Status der Delete-Vorgänge wie etwa löschen Element gesichert. Nachdem der Vorgang gestartet wurde, wird der Statuscode der Antwort akzeptiert werden. Es wird weiterhin in diesem Status bis zum Abschluss erreicht. Bei erfolgreichem Abschluss wird der Statuscode OK sein. Diese Methode erwartet OperationID als Argument an. OperationID ist Teil des Location-Header der Antworten für den Vorgang.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>