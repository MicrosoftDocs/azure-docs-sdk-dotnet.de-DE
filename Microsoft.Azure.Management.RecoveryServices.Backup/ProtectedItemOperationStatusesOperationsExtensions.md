<Type Name="ProtectedItemOperationStatusesOperationsExtensions" FullName="Microsoft.Azure.Management.RecoveryServices.Backup.ProtectedItemOperationStatusesOperationsExtensions">
  <TypeSignature Language="C#" Value="public static class ProtectedItemOperationStatusesOperationsExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit ProtectedItemOperationStatusesOperationsExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.RecoveryServices.Backup.ProtectedItemOperationStatusesOperationsExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module ProtectedItemOperationStatusesOperationsExtensions" />
  <TypeSignature Language="F#" Value="type ProtectedItemOperationStatusesOperationsExtensions = class" />
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
            Erweiterungsmethoden für ProtectedItemOperationStatusesOperations.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="Get">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.RecoveryServices.Backup.Models.OperationStatus Get (this Microsoft.Azure.Management.RecoveryServices.Backup.IProtectedItemOperationStatusesOperations operations, string vaultName, string resourceGroupName, string fabricName, string containerName, string protectedItemName, string operationId);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.RecoveryServices.Backup.Models.OperationStatus Get(class Microsoft.Azure.Management.RecoveryServices.Backup.IProtectedItemOperationStatusesOperations operations, string vaultName, string resourceGroupName, string fabricName, string containerName, string protectedItemName, string operationId) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.RecoveryServices.Backup.ProtectedItemOperationStatusesOperationsExtensions.Get(Microsoft.Azure.Management.RecoveryServices.Backup.IProtectedItemOperationStatusesOperations,System.String,System.String,System.String,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function Get (operations As IProtectedItemOperationStatusesOperations, vaultName As String, resourceGroupName As String, fabricName As String, containerName As String, protectedItemName As String, operationId As String) As OperationStatus" />
      <MemberSignature Language="F#" Value="static member Get : Microsoft.Azure.Management.RecoveryServices.Backup.IProtectedItemOperationStatusesOperations * string * string * string * string * string * string -&gt; Microsoft.Azure.Management.RecoveryServices.Backup.Models.OperationStatus" Usage="Microsoft.Azure.Management.RecoveryServices.Backup.ProtectedItemOperationStatusesOperationsExtensions.Get (operations, vaultName, resourceGroupName, fabricName, containerName, protectedItemName, operationId)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.RecoveryServices.Backup.Models.OperationStatus</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.RecoveryServices.Backup.IProtectedItemOperationStatusesOperations" RefType="this" />
        <Parameter Name="vaultName" Type="System.String" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="fabricName" Type="System.String" />
        <Parameter Name="containerName" Type="System.String" />
        <Parameter Name="protectedItemName" Type="System.String" />
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
        <param name="fabricName">
            Name des Fabric, das Sichern des Elements zugeordnet.
            </param>
        <param name="containerName">
            Der Containername das Sichern des Elements zugeordnet.
            </param>
        <param name="protectedItemName">
            Sichern des Elementname, deren Details werden abgerufen werden sollen.
            </param>
        <param name="operationId">
            OperationID darstellt, den Vorgang, deren Status abgerufen werden muss.
            </param>
        <summary>
            Ruft den Status eines Vorgangs wie z. B. das Auslösen einer sicherungs wiederherstellen.
            Der Status kann in Bearbeitung, abgeschlossen oder fehlerhaft sein. Sie können die OperationStatus-Enumeration für alle möglichen Status des Vorgangs verweisen. Einige Vorgänge Aufträge erstellt werden. Diese Methode gibt die Liste der Aufträge, die dem Vorgang zugeordnet.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.RecoveryServices.Backup.Models.OperationStatus&gt; GetAsync (this Microsoft.Azure.Management.RecoveryServices.Backup.IProtectedItemOperationStatusesOperations operations, string vaultName, string resourceGroupName, string fabricName, string containerName, string protectedItemName, string operationId, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.RecoveryServices.Backup.Models.OperationStatus&gt; GetAsync(class Microsoft.Azure.Management.RecoveryServices.Backup.IProtectedItemOperationStatusesOperations operations, string vaultName, string resourceGroupName, string fabricName, string containerName, string protectedItemName, string operationId, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.RecoveryServices.Backup.ProtectedItemOperationStatusesOperationsExtensions.GetAsync(Microsoft.Azure.Management.RecoveryServices.Backup.IProtectedItemOperationStatusesOperations,System.String,System.String,System.String,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetAsync : Microsoft.Azure.Management.RecoveryServices.Backup.IProtectedItemOperationStatusesOperations * string * string * string * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.RecoveryServices.Backup.Models.OperationStatus&gt;" Usage="Microsoft.Azure.Management.RecoveryServices.Backup.ProtectedItemOperationStatusesOperationsExtensions.GetAsync (operations, vaultName, resourceGroupName, fabricName, containerName, protectedItemName, operationId, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.RecoveryServices.Backup.ProtectedItemOperationStatusesOperationsExtensions/&lt;GetAsync&gt;d__1))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.RecoveryServices.Backup.Models.OperationStatus&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.RecoveryServices.Backup.IProtectedItemOperationStatusesOperations" RefType="this" />
        <Parameter Name="vaultName" Type="System.String" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="fabricName" Type="System.String" />
        <Parameter Name="containerName" Type="System.String" />
        <Parameter Name="protectedItemName" Type="System.String" />
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
        <param name="fabricName">
            Name des Fabric, das Sichern des Elements zugeordnet.
            </param>
        <param name="containerName">
            Der Containername das Sichern des Elements zugeordnet.
            </param>
        <param name="protectedItemName">
            Sichern des Elementname, deren Details werden abgerufen werden sollen.
            </param>
        <param name="operationId">
            OperationID darstellt, den Vorgang, deren Status abgerufen werden muss.
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Ruft den Status eines Vorgangs wie z. B. das Auslösen einer sicherungs wiederherstellen.
            Der Status kann in Bearbeitung, abgeschlossen oder fehlerhaft sein. Sie können die OperationStatus-Enumeration für alle möglichen Status des Vorgangs verweisen. Einige Vorgänge Aufträge erstellt werden. Diese Methode gibt die Liste der Aufträge, die dem Vorgang zugeordnet.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>