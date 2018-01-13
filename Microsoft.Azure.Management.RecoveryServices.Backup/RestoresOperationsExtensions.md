<Type Name="RestoresOperationsExtensions" FullName="Microsoft.Azure.Management.RecoveryServices.Backup.RestoresOperationsExtensions">
  <TypeSignature Language="C#" Value="public static class RestoresOperationsExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit RestoresOperationsExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.RecoveryServices.Backup.RestoresOperationsExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module RestoresOperationsExtensions" />
  <TypeSignature Language="F#" Value="type RestoresOperationsExtensions = class" />
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
            Erweiterungsmethoden für RestoresOperations.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="Trigger">
      <MemberSignature Language="C#" Value="public static void Trigger (this Microsoft.Azure.Management.RecoveryServices.Backup.IRestoresOperations operations, string vaultName, string resourceGroupName, string fabricName, string containerName, string protectedItemName, string recoveryPointId, Microsoft.Azure.Management.RecoveryServices.Backup.Models.RestoreRequestResource parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void Trigger(class Microsoft.Azure.Management.RecoveryServices.Backup.IRestoresOperations operations, string vaultName, string resourceGroupName, string fabricName, string containerName, string protectedItemName, string recoveryPointId, class Microsoft.Azure.Management.RecoveryServices.Backup.Models.RestoreRequestResource parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.RecoveryServices.Backup.RestoresOperationsExtensions.Trigger(Microsoft.Azure.Management.RecoveryServices.Backup.IRestoresOperations,System.String,System.String,System.String,System.String,System.String,System.String,Microsoft.Azure.Management.RecoveryServices.Backup.Models.RestoreRequestResource)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Sub Trigger (operations As IRestoresOperations, vaultName As String, resourceGroupName As String, fabricName As String, containerName As String, protectedItemName As String, recoveryPointId As String, parameters As RestoreRequestResource)" />
      <MemberSignature Language="F#" Value="static member Trigger : Microsoft.Azure.Management.RecoveryServices.Backup.IRestoresOperations * string * string * string * string * string * string * Microsoft.Azure.Management.RecoveryServices.Backup.Models.RestoreRequestResource -&gt; unit" Usage="Microsoft.Azure.Management.RecoveryServices.Backup.RestoresOperationsExtensions.Trigger (operations, vaultName, resourceGroupName, fabricName, containerName, protectedItemName, recoveryPointId, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.RecoveryServices.Backup.IRestoresOperations" RefType="this" />
        <Parameter Name="vaultName" Type="System.String" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="fabricName" Type="System.String" />
        <Parameter Name="containerName" Type="System.String" />
        <Parameter Name="protectedItemName" Type="System.String" />
        <Parameter Name="recoveryPointId" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.RecoveryServices.Backup.Models.RestoreRequestResource" />
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
            Name des Fabric gesicherten Elementen zugeordnet.
            </param>
        <param name="containerName">
            Der Containername gesicherten Elementen zugeordnet.
            </param>
        <param name="protectedItemName">
            Gesichert Element wiederhergestellt werden.
            </param>
        <param name="recoveryPointId">
            Die ID des Wiederherstellungspunkts dar die gesicherten Daten wiederhergestellt werden.
            </param>
        <param name="parameters">
            Anforderung zum Wiederherstellen von Ressourcen
            </param>
        <summary>
            Stellt das angegebene gesicherte Daten. Das ist ein asynchroner Vorgang.
            Um den Status dieser API-Aufruf zu kennen, verwenden Sie GetProtectedItemOperationResult-API.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TriggerAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task TriggerAsync (this Microsoft.Azure.Management.RecoveryServices.Backup.IRestoresOperations operations, string vaultName, string resourceGroupName, string fabricName, string containerName, string protectedItemName, string recoveryPointId, Microsoft.Azure.Management.RecoveryServices.Backup.Models.RestoreRequestResource parameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task TriggerAsync(class Microsoft.Azure.Management.RecoveryServices.Backup.IRestoresOperations operations, string vaultName, string resourceGroupName, string fabricName, string containerName, string protectedItemName, string recoveryPointId, class Microsoft.Azure.Management.RecoveryServices.Backup.Models.RestoreRequestResource parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.RecoveryServices.Backup.RestoresOperationsExtensions.TriggerAsync(Microsoft.Azure.Management.RecoveryServices.Backup.IRestoresOperations,System.String,System.String,System.String,System.String,System.String,System.String,Microsoft.Azure.Management.RecoveryServices.Backup.Models.RestoreRequestResource,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member TriggerAsync : Microsoft.Azure.Management.RecoveryServices.Backup.IRestoresOperations * string * string * string * string * string * string * Microsoft.Azure.Management.RecoveryServices.Backup.Models.RestoreRequestResource * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.RecoveryServices.Backup.RestoresOperationsExtensions.TriggerAsync (operations, vaultName, resourceGroupName, fabricName, containerName, protectedItemName, recoveryPointId, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.RecoveryServices.Backup.RestoresOperationsExtensions/&lt;TriggerAsync&gt;d__1))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.RecoveryServices.Backup.IRestoresOperations" RefType="this" />
        <Parameter Name="vaultName" Type="System.String" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="fabricName" Type="System.String" />
        <Parameter Name="containerName" Type="System.String" />
        <Parameter Name="protectedItemName" Type="System.String" />
        <Parameter Name="recoveryPointId" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.RecoveryServices.Backup.Models.RestoreRequestResource" />
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
            Name des Fabric gesicherten Elementen zugeordnet.
            </param>
        <param name="containerName">
            Der Containername gesicherten Elementen zugeordnet.
            </param>
        <param name="protectedItemName">
            Gesichert Element wiederhergestellt werden.
            </param>
        <param name="recoveryPointId">
            Die ID des Wiederherstellungspunkts dar die gesicherten Daten wiederhergestellt werden.
            </param>
        <param name="parameters">
            Anforderung zum Wiederherstellen von Ressourcen
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Stellt das angegebene gesicherte Daten. Das ist ein asynchroner Vorgang.
            Um den Status dieser API-Aufruf zu kennen, verwenden Sie GetProtectedItemOperationResult-API.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>