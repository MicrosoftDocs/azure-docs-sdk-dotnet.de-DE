<Type Name="ExportJobsOperationResultsOperationsExtensions" FullName="Microsoft.Azure.Management.RecoveryServices.Backup.ExportJobsOperationResultsOperationsExtensions">
  <TypeSignature Language="C#" Value="public static class ExportJobsOperationResultsOperationsExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit ExportJobsOperationResultsOperationsExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.RecoveryServices.Backup.ExportJobsOperationResultsOperationsExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module ExportJobsOperationResultsOperationsExtensions" />
  <TypeSignature Language="F#" Value="type ExportJobsOperationResultsOperationsExtensions = class" />
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
            Erweiterungsmethoden für ExportJobsOperationResultsOperations.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="Get">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.RecoveryServices.Backup.Models.OperationResultInfoBaseResource Get (this Microsoft.Azure.Management.RecoveryServices.Backup.IExportJobsOperationResultsOperations operations, string vaultName, string resourceGroupName, string operationId);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.RecoveryServices.Backup.Models.OperationResultInfoBaseResource Get(class Microsoft.Azure.Management.RecoveryServices.Backup.IExportJobsOperationResultsOperations operations, string vaultName, string resourceGroupName, string operationId) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.RecoveryServices.Backup.ExportJobsOperationResultsOperationsExtensions.Get(Microsoft.Azure.Management.RecoveryServices.Backup.IExportJobsOperationResultsOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function Get (operations As IExportJobsOperationResultsOperations, vaultName As String, resourceGroupName As String, operationId As String) As OperationResultInfoBaseResource" />
      <MemberSignature Language="F#" Value="static member Get : Microsoft.Azure.Management.RecoveryServices.Backup.IExportJobsOperationResultsOperations * string * string * string -&gt; Microsoft.Azure.Management.RecoveryServices.Backup.Models.OperationResultInfoBaseResource" Usage="Microsoft.Azure.Management.RecoveryServices.Backup.ExportJobsOperationResultsOperationsExtensions.Get (operations, vaultName, resourceGroupName, operationId)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.RecoveryServices.Backup.Models.OperationResultInfoBaseResource</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.RecoveryServices.Backup.IExportJobsOperationResultsOperations" RefType="this" />
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
            OperationID des exportauftrags dar.
            </param>
        <summary>
            Ruft das Ergebnis des Vorgangs des Vorgangs durch Exportieren Aufträge API ausgelöst. Wenn der Vorgang erfolgreich ist, enthält er auch URL des Blob und einen SAS-Schlüssel, auf die gleiche. Das Blob enthält, in die serialisierte JSON-Format exportierte Aufträgen.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.RecoveryServices.Backup.Models.OperationResultInfoBaseResource&gt; GetAsync (this Microsoft.Azure.Management.RecoveryServices.Backup.IExportJobsOperationResultsOperations operations, string vaultName, string resourceGroupName, string operationId, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.RecoveryServices.Backup.Models.OperationResultInfoBaseResource&gt; GetAsync(class Microsoft.Azure.Management.RecoveryServices.Backup.IExportJobsOperationResultsOperations operations, string vaultName, string resourceGroupName, string operationId, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.RecoveryServices.Backup.ExportJobsOperationResultsOperationsExtensions.GetAsync(Microsoft.Azure.Management.RecoveryServices.Backup.IExportJobsOperationResultsOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetAsync : Microsoft.Azure.Management.RecoveryServices.Backup.IExportJobsOperationResultsOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.RecoveryServices.Backup.Models.OperationResultInfoBaseResource&gt;" Usage="Microsoft.Azure.Management.RecoveryServices.Backup.ExportJobsOperationResultsOperationsExtensions.GetAsync (operations, vaultName, resourceGroupName, operationId, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.RecoveryServices.Backup.ExportJobsOperationResultsOperationsExtensions/&lt;GetAsync&gt;d__1))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.RecoveryServices.Backup.Models.OperationResultInfoBaseResource&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.RecoveryServices.Backup.IExportJobsOperationResultsOperations" RefType="this" />
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
            OperationID des exportauftrags dar.
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Ruft das Ergebnis des Vorgangs des Vorgangs durch Exportieren Aufträge API ausgelöst. Wenn der Vorgang erfolgreich ist, enthält er auch URL des Blob und einen SAS-Schlüssel, auf die gleiche. Das Blob enthält, in die serialisierte JSON-Format exportierte Aufträgen.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>