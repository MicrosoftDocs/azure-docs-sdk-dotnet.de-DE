<Type Name="JobOperationResultsOperationsExtensions" FullName="Microsoft.Azure.Management.RecoveryServices.Backup.JobOperationResultsOperationsExtensions">
  <TypeSignature Language="C#" Value="public static class JobOperationResultsOperationsExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit JobOperationResultsOperationsExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.RecoveryServices.Backup.JobOperationResultsOperationsExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module JobOperationResultsOperationsExtensions" />
  <TypeSignature Language="F#" Value="type JobOperationResultsOperationsExtensions = class" />
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
            Erweiterungsmethoden für JobOperationResultsOperations.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="Get">
      <MemberSignature Language="C#" Value="public static void Get (this Microsoft.Azure.Management.RecoveryServices.Backup.IJobOperationResultsOperations operations, string vaultName, string resourceGroupName, string jobName, string operationId);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void Get(class Microsoft.Azure.Management.RecoveryServices.Backup.IJobOperationResultsOperations operations, string vaultName, string resourceGroupName, string jobName, string operationId) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.RecoveryServices.Backup.JobOperationResultsOperationsExtensions.Get(Microsoft.Azure.Management.RecoveryServices.Backup.IJobOperationResultsOperations,System.String,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Sub Get (operations As IJobOperationResultsOperations, vaultName As String, resourceGroupName As String, jobName As String, operationId As String)" />
      <MemberSignature Language="F#" Value="static member Get : Microsoft.Azure.Management.RecoveryServices.Backup.IJobOperationResultsOperations * string * string * string * string -&gt; unit" Usage="Microsoft.Azure.Management.RecoveryServices.Backup.JobOperationResultsOperationsExtensions.Get (operations, vaultName, resourceGroupName, jobName, operationId)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.RecoveryServices.Backup.IJobOperationResultsOperations" RefType="this" />
        <Parameter Name="vaultName" Type="System.String" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="jobName" Type="System.String" />
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
        <param name="jobName">
            Name des Auftrags, deren Ergebnis des Vorgangs wurde abgerufen werden sollen.
            </param>
        <param name="operationId">
            OperationID, der den Vorgang darstellt, dessen Ergebnis beinhaltet einen abgerufen werden sollen.
            </param>
        <summary>
            Dadurch wird das Ergebnis der Vorgänge.
            der Vorgang.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task GetAsync (this Microsoft.Azure.Management.RecoveryServices.Backup.IJobOperationResultsOperations operations, string vaultName, string resourceGroupName, string jobName, string operationId, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task GetAsync(class Microsoft.Azure.Management.RecoveryServices.Backup.IJobOperationResultsOperations operations, string vaultName, string resourceGroupName, string jobName, string operationId, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.RecoveryServices.Backup.JobOperationResultsOperationsExtensions.GetAsync(Microsoft.Azure.Management.RecoveryServices.Backup.IJobOperationResultsOperations,System.String,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetAsync : Microsoft.Azure.Management.RecoveryServices.Backup.IJobOperationResultsOperations * string * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.RecoveryServices.Backup.JobOperationResultsOperationsExtensions.GetAsync (operations, vaultName, resourceGroupName, jobName, operationId, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.RecoveryServices.Backup.JobOperationResultsOperationsExtensions/&lt;GetAsync&gt;d__1))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.RecoveryServices.Backup.IJobOperationResultsOperations" RefType="this" />
        <Parameter Name="vaultName" Type="System.String" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="jobName" Type="System.String" />
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
        <param name="jobName">
            Name des Auftrags, deren Ergebnis des Vorgangs wurde abgerufen werden sollen.
            </param>
        <param name="operationId">
            OperationID, der den Vorgang darstellt, dessen Ergebnis beinhaltet einen abgerufen werden sollen.
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Dadurch wird das Ergebnis der Vorgänge.
            der Vorgang.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>