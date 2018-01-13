<Type Name="ProtectionContainersOperationsExtensions" FullName="Microsoft.Azure.Management.RecoveryServices.Backup.ProtectionContainersOperationsExtensions">
  <TypeSignature Language="C#" Value="public static class ProtectionContainersOperationsExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit ProtectionContainersOperationsExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.RecoveryServices.Backup.ProtectionContainersOperationsExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module ProtectionContainersOperationsExtensions" />
  <TypeSignature Language="F#" Value="type ProtectionContainersOperationsExtensions = class" />
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
            Erweiterungsmethoden für ProtectionContainersOperations.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="Get">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.RecoveryServices.Backup.Models.ProtectionContainerResource Get (this Microsoft.Azure.Management.RecoveryServices.Backup.IProtectionContainersOperations operations, string vaultName, string resourceGroupName, string fabricName, string containerName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.RecoveryServices.Backup.Models.ProtectionContainerResource Get(class Microsoft.Azure.Management.RecoveryServices.Backup.IProtectionContainersOperations operations, string vaultName, string resourceGroupName, string fabricName, string containerName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.RecoveryServices.Backup.ProtectionContainersOperationsExtensions.Get(Microsoft.Azure.Management.RecoveryServices.Backup.IProtectionContainersOperations,System.String,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function Get (operations As IProtectionContainersOperations, vaultName As String, resourceGroupName As String, fabricName As String, containerName As String) As ProtectionContainerResource" />
      <MemberSignature Language="F#" Value="static member Get : Microsoft.Azure.Management.RecoveryServices.Backup.IProtectionContainersOperations * string * string * string * string -&gt; Microsoft.Azure.Management.RecoveryServices.Backup.Models.ProtectionContainerResource" Usage="Microsoft.Azure.Management.RecoveryServices.Backup.ProtectionContainersOperationsExtensions.Get (operations, vaultName, resourceGroupName, fabricName, containerName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.RecoveryServices.Backup.Models.ProtectionContainerResource</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.RecoveryServices.Backup.IProtectionContainersOperations" RefType="this" />
        <Parameter Name="vaultName" Type="System.String" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="fabricName" Type="System.String" />
        <Parameter Name="containerName" Type="System.String" />
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
            Der Name des Fabrics, in dem der Container gehört.
            </param>
        <param name="containerName">
            Der Name des Containers, deren Details abgerufen werden müssen.
            </param>
        <summary>
            Ruft Details zu den bestimmten Container in Ihrem Recovery Services-Tresor registriert.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.RecoveryServices.Backup.Models.ProtectionContainerResource&gt; GetAsync (this Microsoft.Azure.Management.RecoveryServices.Backup.IProtectionContainersOperations operations, string vaultName, string resourceGroupName, string fabricName, string containerName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.RecoveryServices.Backup.Models.ProtectionContainerResource&gt; GetAsync(class Microsoft.Azure.Management.RecoveryServices.Backup.IProtectionContainersOperations operations, string vaultName, string resourceGroupName, string fabricName, string containerName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.RecoveryServices.Backup.ProtectionContainersOperationsExtensions.GetAsync(Microsoft.Azure.Management.RecoveryServices.Backup.IProtectionContainersOperations,System.String,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetAsync : Microsoft.Azure.Management.RecoveryServices.Backup.IProtectionContainersOperations * string * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.RecoveryServices.Backup.Models.ProtectionContainerResource&gt;" Usage="Microsoft.Azure.Management.RecoveryServices.Backup.ProtectionContainersOperationsExtensions.GetAsync (operations, vaultName, resourceGroupName, fabricName, containerName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.RecoveryServices.Backup.ProtectionContainersOperationsExtensions/&lt;GetAsync&gt;d__1))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.RecoveryServices.Backup.Models.ProtectionContainerResource&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.RecoveryServices.Backup.IProtectionContainersOperations" RefType="this" />
        <Parameter Name="vaultName" Type="System.String" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="fabricName" Type="System.String" />
        <Parameter Name="containerName" Type="System.String" />
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
            Der Name des Fabrics, in dem der Container gehört.
            </param>
        <param name="containerName">
            Der Name des Containers, deren Details abgerufen werden müssen.
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Ruft Details zu den bestimmten Container in Ihrem Recovery Services-Tresor registriert.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Refresh">
      <MemberSignature Language="C#" Value="public static void Refresh (this Microsoft.Azure.Management.RecoveryServices.Backup.IProtectionContainersOperations operations, string vaultName, string resourceGroupName, string fabricName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void Refresh(class Microsoft.Azure.Management.RecoveryServices.Backup.IProtectionContainersOperations operations, string vaultName, string resourceGroupName, string fabricName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.RecoveryServices.Backup.ProtectionContainersOperationsExtensions.Refresh(Microsoft.Azure.Management.RecoveryServices.Backup.IProtectionContainersOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Sub Refresh (operations As IProtectionContainersOperations, vaultName As String, resourceGroupName As String, fabricName As String)" />
      <MemberSignature Language="F#" Value="static member Refresh : Microsoft.Azure.Management.RecoveryServices.Backup.IProtectionContainersOperations * string * string * string -&gt; unit" Usage="Microsoft.Azure.Management.RecoveryServices.Backup.ProtectionContainersOperationsExtensions.Refresh (operations, vaultName, resourceGroupName, fabricName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.RecoveryServices.Backup.IProtectionContainersOperations" RefType="this" />
        <Parameter Name="vaultName" Type="System.String" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="fabricName" Type="System.String" />
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
            Name des Fabric zugeordnet ist, den Container.
            </param>
        <summary>
            Ermittelt alle Container in das Abonnement, das auf der Recovery Services-Tresor gesichert werden kann. Das ist ein asynchroner Vorgang. Rufen Sie GetRefreshOperationResult-API auf, um den Status des Vorgangs zu kennen.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RefreshAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task RefreshAsync (this Microsoft.Azure.Management.RecoveryServices.Backup.IProtectionContainersOperations operations, string vaultName, string resourceGroupName, string fabricName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task RefreshAsync(class Microsoft.Azure.Management.RecoveryServices.Backup.IProtectionContainersOperations operations, string vaultName, string resourceGroupName, string fabricName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.RecoveryServices.Backup.ProtectionContainersOperationsExtensions.RefreshAsync(Microsoft.Azure.Management.RecoveryServices.Backup.IProtectionContainersOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member RefreshAsync : Microsoft.Azure.Management.RecoveryServices.Backup.IProtectionContainersOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.RecoveryServices.Backup.ProtectionContainersOperationsExtensions.RefreshAsync (operations, vaultName, resourceGroupName, fabricName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.RecoveryServices.Backup.ProtectionContainersOperationsExtensions/&lt;RefreshAsync&gt;d__3))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.RecoveryServices.Backup.IProtectionContainersOperations" RefType="this" />
        <Parameter Name="vaultName" Type="System.String" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="fabricName" Type="System.String" />
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
            Name des Fabric zugeordnet ist, den Container.
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Ermittelt alle Container in das Abonnement, das auf der Recovery Services-Tresor gesichert werden kann. Das ist ein asynchroner Vorgang. Rufen Sie GetRefreshOperationResult-API auf, um den Status des Vorgangs zu kennen.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>