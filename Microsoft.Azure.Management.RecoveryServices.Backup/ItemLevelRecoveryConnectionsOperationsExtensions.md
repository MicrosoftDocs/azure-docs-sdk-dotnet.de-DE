<Type Name="ItemLevelRecoveryConnectionsOperationsExtensions" FullName="Microsoft.Azure.Management.RecoveryServices.Backup.ItemLevelRecoveryConnectionsOperationsExtensions">
  <TypeSignature Language="C#" Value="public static class ItemLevelRecoveryConnectionsOperationsExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit ItemLevelRecoveryConnectionsOperationsExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.RecoveryServices.Backup.ItemLevelRecoveryConnectionsOperationsExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module ItemLevelRecoveryConnectionsOperationsExtensions" />
  <TypeSignature Language="F#" Value="type ItemLevelRecoveryConnectionsOperationsExtensions = class" />
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
            Erweiterungsmethoden für ItemLevelRecoveryConnectionsOperations.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="Provision">
      <MemberSignature Language="C#" Value="public static void Provision (this Microsoft.Azure.Management.RecoveryServices.Backup.IItemLevelRecoveryConnectionsOperations operations, string vaultName, string resourceGroupName, string fabricName, string containerName, string protectedItemName, string recoveryPointId, Microsoft.Azure.Management.RecoveryServices.Backup.Models.ILRRequestResource parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void Provision(class Microsoft.Azure.Management.RecoveryServices.Backup.IItemLevelRecoveryConnectionsOperations operations, string vaultName, string resourceGroupName, string fabricName, string containerName, string protectedItemName, string recoveryPointId, class Microsoft.Azure.Management.RecoveryServices.Backup.Models.ILRRequestResource parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.RecoveryServices.Backup.ItemLevelRecoveryConnectionsOperationsExtensions.Provision(Microsoft.Azure.Management.RecoveryServices.Backup.IItemLevelRecoveryConnectionsOperations,System.String,System.String,System.String,System.String,System.String,System.String,Microsoft.Azure.Management.RecoveryServices.Backup.Models.ILRRequestResource)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Sub Provision (operations As IItemLevelRecoveryConnectionsOperations, vaultName As String, resourceGroupName As String, fabricName As String, containerName As String, protectedItemName As String, recoveryPointId As String, parameters As ILRRequestResource)" />
      <MemberSignature Language="F#" Value="static member Provision : Microsoft.Azure.Management.RecoveryServices.Backup.IItemLevelRecoveryConnectionsOperations * string * string * string * string * string * string * Microsoft.Azure.Management.RecoveryServices.Backup.Models.ILRRequestResource -&gt; unit" Usage="Microsoft.Azure.Management.RecoveryServices.Backup.ItemLevelRecoveryConnectionsOperationsExtensions.Provision (operations, vaultName, resourceGroupName, fabricName, containerName, protectedItemName, recoveryPointId, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.RecoveryServices.Backup.IItemLevelRecoveryConnectionsOperations" RefType="this" />
        <Parameter Name="vaultName" Type="System.String" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="fabricName" Type="System.String" />
        <Parameter Name="containerName" Type="System.String" />
        <Parameter Name="protectedItemName" Type="System.String" />
        <Parameter Name="recoveryPointId" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.RecoveryServices.Backup.Models.ILRRequestResource" />
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
            Gesichert Elementname, deren Dateien bzw. Ordner wiederhergestellt werden sollen.
            </param>
        <param name="recoveryPointId">
            Die ID des Wiederherstellungspunkts die gesicherte Daten darstellt. iSCSI-Verbindung wird für diese gesicherten Daten bereitgestellt werden.
            </param>
        <param name="parameters">
            Wiederherstellung auf Elementebene ressourcenanforderung
            </param>
        <summary>
            Stellt ein Skript, das eine iSCSI-Verbindung die zu sichernden Daten aufruft.
            Dieses Skript ausgeführt, wird einen Datei-Explorer Anzeigen der wiederherstellbaren Dateien und Ordner geöffnet. Das ist ein asynchroner Vorgang. Rufen Sie GetProtectedItemOperationResult-API auf, um den Status der Bereitstellung zu kennen.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ProvisionAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task ProvisionAsync (this Microsoft.Azure.Management.RecoveryServices.Backup.IItemLevelRecoveryConnectionsOperations operations, string vaultName, string resourceGroupName, string fabricName, string containerName, string protectedItemName, string recoveryPointId, Microsoft.Azure.Management.RecoveryServices.Backup.Models.ILRRequestResource parameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task ProvisionAsync(class Microsoft.Azure.Management.RecoveryServices.Backup.IItemLevelRecoveryConnectionsOperations operations, string vaultName, string resourceGroupName, string fabricName, string containerName, string protectedItemName, string recoveryPointId, class Microsoft.Azure.Management.RecoveryServices.Backup.Models.ILRRequestResource parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.RecoveryServices.Backup.ItemLevelRecoveryConnectionsOperationsExtensions.ProvisionAsync(Microsoft.Azure.Management.RecoveryServices.Backup.IItemLevelRecoveryConnectionsOperations,System.String,System.String,System.String,System.String,System.String,System.String,Microsoft.Azure.Management.RecoveryServices.Backup.Models.ILRRequestResource,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ProvisionAsync : Microsoft.Azure.Management.RecoveryServices.Backup.IItemLevelRecoveryConnectionsOperations * string * string * string * string * string * string * Microsoft.Azure.Management.RecoveryServices.Backup.Models.ILRRequestResource * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.RecoveryServices.Backup.ItemLevelRecoveryConnectionsOperationsExtensions.ProvisionAsync (operations, vaultName, resourceGroupName, fabricName, containerName, protectedItemName, recoveryPointId, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.RecoveryServices.Backup.ItemLevelRecoveryConnectionsOperationsExtensions/&lt;ProvisionAsync&gt;d__1))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.RecoveryServices.Backup.IItemLevelRecoveryConnectionsOperations" RefType="this" />
        <Parameter Name="vaultName" Type="System.String" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="fabricName" Type="System.String" />
        <Parameter Name="containerName" Type="System.String" />
        <Parameter Name="protectedItemName" Type="System.String" />
        <Parameter Name="recoveryPointId" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.RecoveryServices.Backup.Models.ILRRequestResource" />
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
            Gesichert Elementname, deren Dateien bzw. Ordner wiederhergestellt werden sollen.
            </param>
        <param name="recoveryPointId">
            Die ID des Wiederherstellungspunkts die gesicherte Daten darstellt. iSCSI-Verbindung wird für diese gesicherten Daten bereitgestellt werden.
            </param>
        <param name="parameters">
            Wiederherstellung auf Elementebene ressourcenanforderung
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Stellt ein Skript, das eine iSCSI-Verbindung die zu sichernden Daten aufruft.
            Dieses Skript ausgeführt, wird einen Datei-Explorer Anzeigen der wiederherstellbaren Dateien und Ordner geöffnet. Das ist ein asynchroner Vorgang. Rufen Sie GetProtectedItemOperationResult-API auf, um den Status der Bereitstellung zu kennen.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Revoke">
      <MemberSignature Language="C#" Value="public static void Revoke (this Microsoft.Azure.Management.RecoveryServices.Backup.IItemLevelRecoveryConnectionsOperations operations, string vaultName, string resourceGroupName, string fabricName, string containerName, string protectedItemName, string recoveryPointId);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void Revoke(class Microsoft.Azure.Management.RecoveryServices.Backup.IItemLevelRecoveryConnectionsOperations operations, string vaultName, string resourceGroupName, string fabricName, string containerName, string protectedItemName, string recoveryPointId) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.RecoveryServices.Backup.ItemLevelRecoveryConnectionsOperationsExtensions.Revoke(Microsoft.Azure.Management.RecoveryServices.Backup.IItemLevelRecoveryConnectionsOperations,System.String,System.String,System.String,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Sub Revoke (operations As IItemLevelRecoveryConnectionsOperations, vaultName As String, resourceGroupName As String, fabricName As String, containerName As String, protectedItemName As String, recoveryPointId As String)" />
      <MemberSignature Language="F#" Value="static member Revoke : Microsoft.Azure.Management.RecoveryServices.Backup.IItemLevelRecoveryConnectionsOperations * string * string * string * string * string * string -&gt; unit" Usage="Microsoft.Azure.Management.RecoveryServices.Backup.ItemLevelRecoveryConnectionsOperationsExtensions.Revoke (operations, vaultName, resourceGroupName, fabricName, containerName, protectedItemName, recoveryPointId)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.RecoveryServices.Backup.IItemLevelRecoveryConnectionsOperations" RefType="this" />
        <Parameter Name="vaultName" Type="System.String" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="fabricName" Type="System.String" />
        <Parameter Name="containerName" Type="System.String" />
        <Parameter Name="protectedItemName" Type="System.String" />
        <Parameter Name="recoveryPointId" Type="System.String" />
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
            Gesichert Elementname, deren Dateien bzw. Ordner wiederhergestellt werden sollen.
            </param>
        <param name="recoveryPointId">
            Die ID des Wiederherstellungspunkts die gesicherte Daten darstellt. iSCSI-Verbindung wird für diese gesicherten Daten aufgehoben.
            </param>
        <summary>
            Widerruft eine iSCSI-Verbindung die verwendet werden kann, um ein Skript herunterladen.
            Dieses Skript ausgeführt, öffnet einen Datei-Explorer alle wiederherstellbaren Dateien und Ordner anzeigen. Das ist ein asynchroner Vorgang.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RevokeAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task RevokeAsync (this Microsoft.Azure.Management.RecoveryServices.Backup.IItemLevelRecoveryConnectionsOperations operations, string vaultName, string resourceGroupName, string fabricName, string containerName, string protectedItemName, string recoveryPointId, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task RevokeAsync(class Microsoft.Azure.Management.RecoveryServices.Backup.IItemLevelRecoveryConnectionsOperations operations, string vaultName, string resourceGroupName, string fabricName, string containerName, string protectedItemName, string recoveryPointId, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.RecoveryServices.Backup.ItemLevelRecoveryConnectionsOperationsExtensions.RevokeAsync(Microsoft.Azure.Management.RecoveryServices.Backup.IItemLevelRecoveryConnectionsOperations,System.String,System.String,System.String,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member RevokeAsync : Microsoft.Azure.Management.RecoveryServices.Backup.IItemLevelRecoveryConnectionsOperations * string * string * string * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.RecoveryServices.Backup.ItemLevelRecoveryConnectionsOperationsExtensions.RevokeAsync (operations, vaultName, resourceGroupName, fabricName, containerName, protectedItemName, recoveryPointId, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.RecoveryServices.Backup.ItemLevelRecoveryConnectionsOperationsExtensions/&lt;RevokeAsync&gt;d__3))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.RecoveryServices.Backup.IItemLevelRecoveryConnectionsOperations" RefType="this" />
        <Parameter Name="vaultName" Type="System.String" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="fabricName" Type="System.String" />
        <Parameter Name="containerName" Type="System.String" />
        <Parameter Name="protectedItemName" Type="System.String" />
        <Parameter Name="recoveryPointId" Type="System.String" />
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
            Gesichert Elementname, deren Dateien bzw. Ordner wiederhergestellt werden sollen.
            </param>
        <param name="recoveryPointId">
            Die ID des Wiederherstellungspunkts die gesicherte Daten darstellt. iSCSI-Verbindung wird für diese gesicherten Daten aufgehoben.
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Widerruft eine iSCSI-Verbindung die verwendet werden kann, um ein Skript herunterladen.
            Dieses Skript ausgeführt, öffnet einen Datei-Explorer alle wiederherstellbaren Dateien und Ordner anzeigen. Das ist ein asynchroner Vorgang.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>