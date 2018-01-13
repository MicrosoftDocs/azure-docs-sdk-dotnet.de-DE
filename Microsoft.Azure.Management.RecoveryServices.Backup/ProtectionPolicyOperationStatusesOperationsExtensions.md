<Type Name="ProtectionPolicyOperationStatusesOperationsExtensions" FullName="Microsoft.Azure.Management.RecoveryServices.Backup.ProtectionPolicyOperationStatusesOperationsExtensions">
  <TypeSignature Language="C#" Value="public static class ProtectionPolicyOperationStatusesOperationsExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit ProtectionPolicyOperationStatusesOperationsExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.RecoveryServices.Backup.ProtectionPolicyOperationStatusesOperationsExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module ProtectionPolicyOperationStatusesOperationsExtensions" />
  <TypeSignature Language="F#" Value="type ProtectionPolicyOperationStatusesOperationsExtensions = class" />
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
            Erweiterungsmethoden für ProtectionPolicyOperationStatusesOperations.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="Get">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.RecoveryServices.Backup.Models.OperationStatus Get (this Microsoft.Azure.Management.RecoveryServices.Backup.IProtectionPolicyOperationStatusesOperations operations, string vaultName, string resourceGroupName, string policyName, string operationId);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.RecoveryServices.Backup.Models.OperationStatus Get(class Microsoft.Azure.Management.RecoveryServices.Backup.IProtectionPolicyOperationStatusesOperations operations, string vaultName, string resourceGroupName, string policyName, string operationId) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.RecoveryServices.Backup.ProtectionPolicyOperationStatusesOperationsExtensions.Get(Microsoft.Azure.Management.RecoveryServices.Backup.IProtectionPolicyOperationStatusesOperations,System.String,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function Get (operations As IProtectionPolicyOperationStatusesOperations, vaultName As String, resourceGroupName As String, policyName As String, operationId As String) As OperationStatus" />
      <MemberSignature Language="F#" Value="static member Get : Microsoft.Azure.Management.RecoveryServices.Backup.IProtectionPolicyOperationStatusesOperations * string * string * string * string -&gt; Microsoft.Azure.Management.RecoveryServices.Backup.Models.OperationStatus" Usage="Microsoft.Azure.Management.RecoveryServices.Backup.ProtectionPolicyOperationStatusesOperationsExtensions.Get (operations, vaultName, resourceGroupName, policyName, operationId)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.RecoveryServices.Backup.Models.OperationStatus</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.RecoveryServices.Backup.IProtectionPolicyOperationStatusesOperations" RefType="this" />
        <Parameter Name="vaultName" Type="System.String" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="policyName" Type="System.String" />
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
        <param name="policyName">
            Name der Sicherungsrichtlinie des Vorgangs, deren Status abgerufen werden muss.
            </param>
        <param name="operationId">
            Vorgangs-ID einen Vorgang dar, deren Status abgerufen werden muss.
            </param>
        <summary>
            Stellt den Status der asynchronen Vorgänge, z. B. Sicherung, Wiederherstellung bereit.
            Der Status kann in Bearbeitung, abgeschlossen oder fehlerhaft sein. Sie können der Vorgangsstatus-Enumeration für alle möglichen Status eines Vorgangs verweisen. Einige Vorgänge Aufträge erstellt werden. Diese Methode gibt die Liste der Aufträge Vorgang zugeordnet.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.RecoveryServices.Backup.Models.OperationStatus&gt; GetAsync (this Microsoft.Azure.Management.RecoveryServices.Backup.IProtectionPolicyOperationStatusesOperations operations, string vaultName, string resourceGroupName, string policyName, string operationId, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.RecoveryServices.Backup.Models.OperationStatus&gt; GetAsync(class Microsoft.Azure.Management.RecoveryServices.Backup.IProtectionPolicyOperationStatusesOperations operations, string vaultName, string resourceGroupName, string policyName, string operationId, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.RecoveryServices.Backup.ProtectionPolicyOperationStatusesOperationsExtensions.GetAsync(Microsoft.Azure.Management.RecoveryServices.Backup.IProtectionPolicyOperationStatusesOperations,System.String,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetAsync : Microsoft.Azure.Management.RecoveryServices.Backup.IProtectionPolicyOperationStatusesOperations * string * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.RecoveryServices.Backup.Models.OperationStatus&gt;" Usage="Microsoft.Azure.Management.RecoveryServices.Backup.ProtectionPolicyOperationStatusesOperationsExtensions.GetAsync (operations, vaultName, resourceGroupName, policyName, operationId, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.RecoveryServices.Backup.ProtectionPolicyOperationStatusesOperationsExtensions/&lt;GetAsync&gt;d__1))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.RecoveryServices.Backup.Models.OperationStatus&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.RecoveryServices.Backup.IProtectionPolicyOperationStatusesOperations" RefType="this" />
        <Parameter Name="vaultName" Type="System.String" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="policyName" Type="System.String" />
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
        <param name="policyName">
            Name der Sicherungsrichtlinie des Vorgangs, deren Status abgerufen werden muss.
            </param>
        <param name="operationId">
            Vorgangs-ID einen Vorgang dar, deren Status abgerufen werden muss.
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Stellt den Status der asynchronen Vorgänge, z. B. Sicherung, Wiederherstellung bereit.
            Der Status kann in Bearbeitung, abgeschlossen oder fehlerhaft sein. Sie können der Vorgangsstatus-Enumeration für alle möglichen Status eines Vorgangs verweisen. Einige Vorgänge Aufträge erstellt werden. Diese Methode gibt die Liste der Aufträge Vorgang zugeordnet.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>