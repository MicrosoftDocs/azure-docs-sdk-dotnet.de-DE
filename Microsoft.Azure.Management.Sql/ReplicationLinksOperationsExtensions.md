<Type Name="ReplicationLinksOperationsExtensions" FullName="Microsoft.Azure.Management.Sql.ReplicationLinksOperationsExtensions">
  <TypeSignature Language="C#" Value="public static class ReplicationLinksOperationsExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit ReplicationLinksOperationsExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Sql.ReplicationLinksOperationsExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module ReplicationLinksOperationsExtensions" />
  <TypeSignature Language="F#" Value="type ReplicationLinksOperationsExtensions = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            Erweiterungsmethoden für ReplicationLinksOperations.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="BeginFailover">
      <MemberSignature Language="C#" Value="public static void BeginFailover (this Microsoft.Azure.Management.Sql.IReplicationLinksOperations operations, string resourceGroupName, string serverName, string databaseName, string linkId);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void BeginFailover(class Microsoft.Azure.Management.Sql.IReplicationLinksOperations operations, string resourceGroupName, string serverName, string databaseName, string linkId) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.ReplicationLinksOperationsExtensions.BeginFailover(Microsoft.Azure.Management.Sql.IReplicationLinksOperations,System.String,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Sub BeginFailover (operations As IReplicationLinksOperations, resourceGroupName As String, serverName As String, databaseName As String, linkId As String)" />
      <MemberSignature Language="F#" Value="static member BeginFailover : Microsoft.Azure.Management.Sql.IReplicationLinksOperations * string * string * string * string -&gt; unit" Usage="Microsoft.Azure.Management.Sql.ReplicationLinksOperationsExtensions.BeginFailover (operations, resourceGroupName, serverName, databaseName, linkId)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Sql.IReplicationLinksOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="serverName" Type="System.String" />
        <Parameter Name="databaseName" Type="System.String" />
        <Parameter Name="linkId" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="resourceGroupName">
            Der Name der Ressourcengruppe, die die Ressource enthält. Dieser Wert kann über die Azure-Ressourcen-Manager-API oder das Portal abgerufen werden.
            </param>
        <param name="serverName">
            Der Name des Servers.
            </param>
        <param name="databaseName">
            Der Name der Datenbank, die über den Replikationslink Failover ausgeführt werden kann.
            </param>
        <param name="linkId">
            Die ID des Replikationslinks Failover ausgeführt werden kann.
            </param>
        <summary>
            Legt fest, welche Replikatdatenbank als primäre Replikatdatenbank verwendet wird, indem ein Failover von der aktuellen primären Replikatdatenbank durchgeführt wird.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginFailoverAllowDataLoss">
      <MemberSignature Language="C#" Value="public static void BeginFailoverAllowDataLoss (this Microsoft.Azure.Management.Sql.IReplicationLinksOperations operations, string resourceGroupName, string serverName, string databaseName, string linkId);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void BeginFailoverAllowDataLoss(class Microsoft.Azure.Management.Sql.IReplicationLinksOperations operations, string resourceGroupName, string serverName, string databaseName, string linkId) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.ReplicationLinksOperationsExtensions.BeginFailoverAllowDataLoss(Microsoft.Azure.Management.Sql.IReplicationLinksOperations,System.String,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Sub BeginFailoverAllowDataLoss (operations As IReplicationLinksOperations, resourceGroupName As String, serverName As String, databaseName As String, linkId As String)" />
      <MemberSignature Language="F#" Value="static member BeginFailoverAllowDataLoss : Microsoft.Azure.Management.Sql.IReplicationLinksOperations * string * string * string * string -&gt; unit" Usage="Microsoft.Azure.Management.Sql.ReplicationLinksOperationsExtensions.BeginFailoverAllowDataLoss (operations, resourceGroupName, serverName, databaseName, linkId)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Sql.IReplicationLinksOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="serverName" Type="System.String" />
        <Parameter Name="databaseName" Type="System.String" />
        <Parameter Name="linkId" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="resourceGroupName">
            Der Name der Ressourcengruppe, die die Ressource enthält. Dieser Wert kann über die Azure-Ressourcen-Manager-API oder das Portal abgerufen werden.
            </param>
        <param name="serverName">
            Der Name des Servers.
            </param>
        <param name="databaseName">
            Der Name der Datenbank, die über den Replikationslink Failover ausgeführt werden kann.
            </param>
        <param name="linkId">
            Die ID des Replikationslinks Failover ausgeführt werden kann.
            </param>
        <summary>
            Legt fest, welche Replikatdatenbank als primäre Replikatdatenbank verwendet wird, indem ein Failover von der aktuellen primären Replikatdatenbank durchgeführt wird. Bei diesem Vorgang können Daten verloren gehen.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginFailoverAllowDataLossAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task BeginFailoverAllowDataLossAsync (this Microsoft.Azure.Management.Sql.IReplicationLinksOperations operations, string resourceGroupName, string serverName, string databaseName, string linkId, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task BeginFailoverAllowDataLossAsync(class Microsoft.Azure.Management.Sql.IReplicationLinksOperations operations, string resourceGroupName, string serverName, string databaseName, string linkId, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.ReplicationLinksOperationsExtensions.BeginFailoverAllowDataLossAsync(Microsoft.Azure.Management.Sql.IReplicationLinksOperations,System.String,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginFailoverAllowDataLossAsync : Microsoft.Azure.Management.Sql.IReplicationLinksOperations * string * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.Sql.ReplicationLinksOperationsExtensions.BeginFailoverAllowDataLossAsync (operations, resourceGroupName, serverName, databaseName, linkId, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Sql.ReplicationLinksOperationsExtensions/&lt;BeginFailoverAllowDataLossAsync&gt;d__13))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Sql.IReplicationLinksOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="serverName" Type="System.String" />
        <Parameter Name="databaseName" Type="System.String" />
        <Parameter Name="linkId" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="resourceGroupName">
            Der Name der Ressourcengruppe, die die Ressource enthält. Dieser Wert kann über die Azure-Ressourcen-Manager-API oder das Portal abgerufen werden.
            </param>
        <param name="serverName">
            Der Name des Servers.
            </param>
        <param name="databaseName">
            Der Name der Datenbank, die über den Replikationslink Failover ausgeführt werden kann.
            </param>
        <param name="linkId">
            Die ID des Replikationslinks Failover ausgeführt werden kann.
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Legt fest, welche Replikatdatenbank als primäre Replikatdatenbank verwendet wird, indem ein Failover von der aktuellen primären Replikatdatenbank durchgeführt wird. Bei diesem Vorgang können Daten verloren gehen.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginFailoverAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task BeginFailoverAsync (this Microsoft.Azure.Management.Sql.IReplicationLinksOperations operations, string resourceGroupName, string serverName, string databaseName, string linkId, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task BeginFailoverAsync(class Microsoft.Azure.Management.Sql.IReplicationLinksOperations operations, string resourceGroupName, string serverName, string databaseName, string linkId, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.ReplicationLinksOperationsExtensions.BeginFailoverAsync(Microsoft.Azure.Management.Sql.IReplicationLinksOperations,System.String,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginFailoverAsync : Microsoft.Azure.Management.Sql.IReplicationLinksOperations * string * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.Sql.ReplicationLinksOperationsExtensions.BeginFailoverAsync (operations, resourceGroupName, serverName, databaseName, linkId, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Sql.ReplicationLinksOperationsExtensions/&lt;BeginFailoverAsync&gt;d__11))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Sql.IReplicationLinksOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="serverName" Type="System.String" />
        <Parameter Name="databaseName" Type="System.String" />
        <Parameter Name="linkId" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="resourceGroupName">
            Der Name der Ressourcengruppe, die die Ressource enthält. Dieser Wert kann über die Azure-Ressourcen-Manager-API oder das Portal abgerufen werden.
            </param>
        <param name="serverName">
            Der Name des Servers.
            </param>
        <param name="databaseName">
            Der Name der Datenbank, die über den Replikationslink Failover ausgeführt werden kann.
            </param>
        <param name="linkId">
            Die ID des Replikationslinks Failover ausgeführt werden kann.
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Legt fest, welche Replikatdatenbank als primäre Replikatdatenbank verwendet wird, indem ein Failover von der aktuellen primären Replikatdatenbank durchgeführt wird.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Delete">
      <MemberSignature Language="C#" Value="public static void Delete (this Microsoft.Azure.Management.Sql.IReplicationLinksOperations operations, string resourceGroupName, string serverName, string databaseName, string linkId);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void Delete(class Microsoft.Azure.Management.Sql.IReplicationLinksOperations operations, string resourceGroupName, string serverName, string databaseName, string linkId) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.ReplicationLinksOperationsExtensions.Delete(Microsoft.Azure.Management.Sql.IReplicationLinksOperations,System.String,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Sub Delete (operations As IReplicationLinksOperations, resourceGroupName As String, serverName As String, databaseName As String, linkId As String)" />
      <MemberSignature Language="F#" Value="static member Delete : Microsoft.Azure.Management.Sql.IReplicationLinksOperations * string * string * string * string -&gt; unit" Usage="Microsoft.Azure.Management.Sql.ReplicationLinksOperationsExtensions.Delete (operations, resourceGroupName, serverName, databaseName, linkId)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Sql.IReplicationLinksOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="serverName" Type="System.String" />
        <Parameter Name="databaseName" Type="System.String" />
        <Parameter Name="linkId" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="resourceGroupName">
            Der Name der Ressourcengruppe, die die Ressource enthält. Dieser Wert kann über die Azure-Ressourcen-Manager-API oder das Portal abgerufen werden.
            </param>
        <param name="serverName">
            Der Name des Servers.
            </param>
        <param name="databaseName">
            Der Name der Datenbank, die über den Replikationslink gelöscht werden sollen.
            </param>
        <param name="linkId">
            Die ID des Replikationslinks gelöscht werden soll.
            </param>
        <summary>
            Löscht einen Datenbankreplikationslink. Kann nicht während eines Failovers verwendet werden.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task DeleteAsync (this Microsoft.Azure.Management.Sql.IReplicationLinksOperations operations, string resourceGroupName, string serverName, string databaseName, string linkId, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task DeleteAsync(class Microsoft.Azure.Management.Sql.IReplicationLinksOperations operations, string resourceGroupName, string serverName, string databaseName, string linkId, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.ReplicationLinksOperationsExtensions.DeleteAsync(Microsoft.Azure.Management.Sql.IReplicationLinksOperations,System.String,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member DeleteAsync : Microsoft.Azure.Management.Sql.IReplicationLinksOperations * string * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.Sql.ReplicationLinksOperationsExtensions.DeleteAsync (operations, resourceGroupName, serverName, databaseName, linkId, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Sql.ReplicationLinksOperationsExtensions/&lt;DeleteAsync&gt;d__1))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Sql.IReplicationLinksOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="serverName" Type="System.String" />
        <Parameter Name="databaseName" Type="System.String" />
        <Parameter Name="linkId" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="resourceGroupName">
            Der Name der Ressourcengruppe, die die Ressource enthält. Dieser Wert kann über die Azure-Ressourcen-Manager-API oder das Portal abgerufen werden.
            </param>
        <param name="serverName">
            Der Name des Servers.
            </param>
        <param name="databaseName">
            Der Name der Datenbank, die über den Replikationslink gelöscht werden sollen.
            </param>
        <param name="linkId">
            Die ID des Replikationslinks gelöscht werden soll.
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Löscht einen Datenbankreplikationslink. Kann nicht während eines Failovers verwendet werden.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Failover">
      <MemberSignature Language="C#" Value="public static void Failover (this Microsoft.Azure.Management.Sql.IReplicationLinksOperations operations, string resourceGroupName, string serverName, string databaseName, string linkId);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void Failover(class Microsoft.Azure.Management.Sql.IReplicationLinksOperations operations, string resourceGroupName, string serverName, string databaseName, string linkId) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.ReplicationLinksOperationsExtensions.Failover(Microsoft.Azure.Management.Sql.IReplicationLinksOperations,System.String,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Sub Failover (operations As IReplicationLinksOperations, resourceGroupName As String, serverName As String, databaseName As String, linkId As String)" />
      <MemberSignature Language="F#" Value="static member Failover : Microsoft.Azure.Management.Sql.IReplicationLinksOperations * string * string * string * string -&gt; unit" Usage="Microsoft.Azure.Management.Sql.ReplicationLinksOperationsExtensions.Failover (operations, resourceGroupName, serverName, databaseName, linkId)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Sql.IReplicationLinksOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="serverName" Type="System.String" />
        <Parameter Name="databaseName" Type="System.String" />
        <Parameter Name="linkId" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="resourceGroupName">
            Der Name der Ressourcengruppe, die die Ressource enthält. Dieser Wert kann über die Azure-Ressourcen-Manager-API oder das Portal abgerufen werden.
            </param>
        <param name="serverName">
            Der Name des Servers.
            </param>
        <param name="databaseName">
            Der Name der Datenbank, die über den Replikationslink Failover ausgeführt werden kann.
            </param>
        <param name="linkId">
            Die ID des Replikationslinks Failover ausgeführt werden kann.
            </param>
        <summary>
            Legt fest, welche Replikatdatenbank als primäre Replikatdatenbank verwendet wird, indem ein Failover von der aktuellen primären Replikatdatenbank durchgeführt wird.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="FailoverAllowDataLoss">
      <MemberSignature Language="C#" Value="public static void FailoverAllowDataLoss (this Microsoft.Azure.Management.Sql.IReplicationLinksOperations operations, string resourceGroupName, string serverName, string databaseName, string linkId);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void FailoverAllowDataLoss(class Microsoft.Azure.Management.Sql.IReplicationLinksOperations operations, string resourceGroupName, string serverName, string databaseName, string linkId) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.ReplicationLinksOperationsExtensions.FailoverAllowDataLoss(Microsoft.Azure.Management.Sql.IReplicationLinksOperations,System.String,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Sub FailoverAllowDataLoss (operations As IReplicationLinksOperations, resourceGroupName As String, serverName As String, databaseName As String, linkId As String)" />
      <MemberSignature Language="F#" Value="static member FailoverAllowDataLoss : Microsoft.Azure.Management.Sql.IReplicationLinksOperations * string * string * string * string -&gt; unit" Usage="Microsoft.Azure.Management.Sql.ReplicationLinksOperationsExtensions.FailoverAllowDataLoss (operations, resourceGroupName, serverName, databaseName, linkId)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Sql.IReplicationLinksOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="serverName" Type="System.String" />
        <Parameter Name="databaseName" Type="System.String" />
        <Parameter Name="linkId" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="resourceGroupName">
            Der Name der Ressourcengruppe, die die Ressource enthält. Dieser Wert kann über die Azure-Ressourcen-Manager-API oder das Portal abgerufen werden.
            </param>
        <param name="serverName">
            Der Name des Servers.
            </param>
        <param name="databaseName">
            Der Name der Datenbank, die über den Replikationslink Failover ausgeführt werden kann.
            </param>
        <param name="linkId">
            Die ID des Replikationslinks Failover ausgeführt werden kann.
            </param>
        <summary>
            Legt fest, welche Replikatdatenbank als primäre Replikatdatenbank verwendet wird, indem ein Failover von der aktuellen primären Replikatdatenbank durchgeführt wird. Bei diesem Vorgang können Daten verloren gehen.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="FailoverAllowDataLossAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task FailoverAllowDataLossAsync (this Microsoft.Azure.Management.Sql.IReplicationLinksOperations operations, string resourceGroupName, string serverName, string databaseName, string linkId, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task FailoverAllowDataLossAsync(class Microsoft.Azure.Management.Sql.IReplicationLinksOperations operations, string resourceGroupName, string serverName, string databaseName, string linkId, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.ReplicationLinksOperationsExtensions.FailoverAllowDataLossAsync(Microsoft.Azure.Management.Sql.IReplicationLinksOperations,System.String,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member FailoverAllowDataLossAsync : Microsoft.Azure.Management.Sql.IReplicationLinksOperations * string * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.Sql.ReplicationLinksOperationsExtensions.FailoverAllowDataLossAsync (operations, resourceGroupName, serverName, databaseName, linkId, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Sql.ReplicationLinksOperationsExtensions/&lt;FailoverAllowDataLossAsync&gt;d__7))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Sql.IReplicationLinksOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="serverName" Type="System.String" />
        <Parameter Name="databaseName" Type="System.String" />
        <Parameter Name="linkId" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="resourceGroupName">
            Der Name der Ressourcengruppe, die die Ressource enthält. Dieser Wert kann über die Azure-Ressourcen-Manager-API oder das Portal abgerufen werden.
            </param>
        <param name="serverName">
            Der Name des Servers.
            </param>
        <param name="databaseName">
            Der Name der Datenbank, die über den Replikationslink Failover ausgeführt werden kann.
            </param>
        <param name="linkId">
            Die ID des Replikationslinks Failover ausgeführt werden kann.
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Legt fest, welche Replikatdatenbank als primäre Replikatdatenbank verwendet wird, indem ein Failover von der aktuellen primären Replikatdatenbank durchgeführt wird. Bei diesem Vorgang können Daten verloren gehen.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="FailoverAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task FailoverAsync (this Microsoft.Azure.Management.Sql.IReplicationLinksOperations operations, string resourceGroupName, string serverName, string databaseName, string linkId, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task FailoverAsync(class Microsoft.Azure.Management.Sql.IReplicationLinksOperations operations, string resourceGroupName, string serverName, string databaseName, string linkId, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.ReplicationLinksOperationsExtensions.FailoverAsync(Microsoft.Azure.Management.Sql.IReplicationLinksOperations,System.String,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member FailoverAsync : Microsoft.Azure.Management.Sql.IReplicationLinksOperations * string * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.Sql.ReplicationLinksOperationsExtensions.FailoverAsync (operations, resourceGroupName, serverName, databaseName, linkId, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Sql.ReplicationLinksOperationsExtensions/&lt;FailoverAsync&gt;d__5))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Sql.IReplicationLinksOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="serverName" Type="System.String" />
        <Parameter Name="databaseName" Type="System.String" />
        <Parameter Name="linkId" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="resourceGroupName">
            Der Name der Ressourcengruppe, die die Ressource enthält. Dieser Wert kann über die Azure-Ressourcen-Manager-API oder das Portal abgerufen werden.
            </param>
        <param name="serverName">
            Der Name des Servers.
            </param>
        <param name="databaseName">
            Der Name der Datenbank, die über den Replikationslink Failover ausgeführt werden kann.
            </param>
        <param name="linkId">
            Die ID des Replikationslinks Failover ausgeführt werden kann.
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Legt fest, welche Replikatdatenbank als primäre Replikatdatenbank verwendet wird, indem ein Failover von der aktuellen primären Replikatdatenbank durchgeführt wird.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Get">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Sql.Models.ReplicationLink Get (this Microsoft.Azure.Management.Sql.IReplicationLinksOperations operations, string resourceGroupName, string serverName, string databaseName, string linkId);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Sql.Models.ReplicationLink Get(class Microsoft.Azure.Management.Sql.IReplicationLinksOperations operations, string resourceGroupName, string serverName, string databaseName, string linkId) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.ReplicationLinksOperationsExtensions.Get(Microsoft.Azure.Management.Sql.IReplicationLinksOperations,System.String,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function Get (operations As IReplicationLinksOperations, resourceGroupName As String, serverName As String, databaseName As String, linkId As String) As ReplicationLink" />
      <MemberSignature Language="F#" Value="static member Get : Microsoft.Azure.Management.Sql.IReplicationLinksOperations * string * string * string * string -&gt; Microsoft.Azure.Management.Sql.Models.ReplicationLink" Usage="Microsoft.Azure.Management.Sql.ReplicationLinksOperationsExtensions.Get (operations, resourceGroupName, serverName, databaseName, linkId)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Sql.Models.ReplicationLink</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Sql.IReplicationLinksOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="serverName" Type="System.String" />
        <Parameter Name="databaseName" Type="System.String" />
        <Parameter Name="linkId" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="resourceGroupName">
            Der Name der Ressourcengruppe, die die Ressource enthält. Dieser Wert kann über die Azure-Ressourcen-Manager-API oder das Portal abgerufen werden.
            </param>
        <param name="serverName">
            Der Name des Servers.
            </param>
        <param name="databaseName">
            Der Name der Datenbank auf den Link, um zu erhalten.
            </param>
        <param name="linkId">
            Die Replikation-Link-ID abgerufen werden sollen.
            </param>
        <summary>
            Ruft ein datenbankreplikationslink ab.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Sql.Models.ReplicationLink&gt; GetAsync (this Microsoft.Azure.Management.Sql.IReplicationLinksOperations operations, string resourceGroupName, string serverName, string databaseName, string linkId, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Sql.Models.ReplicationLink&gt; GetAsync(class Microsoft.Azure.Management.Sql.IReplicationLinksOperations operations, string resourceGroupName, string serverName, string databaseName, string linkId, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.ReplicationLinksOperationsExtensions.GetAsync(Microsoft.Azure.Management.Sql.IReplicationLinksOperations,System.String,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetAsync : Microsoft.Azure.Management.Sql.IReplicationLinksOperations * string * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Sql.Models.ReplicationLink&gt;" Usage="Microsoft.Azure.Management.Sql.ReplicationLinksOperationsExtensions.GetAsync (operations, resourceGroupName, serverName, databaseName, linkId, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Sql.ReplicationLinksOperationsExtensions/&lt;GetAsync&gt;d__3))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Sql.Models.ReplicationLink&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Sql.IReplicationLinksOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="serverName" Type="System.String" />
        <Parameter Name="databaseName" Type="System.String" />
        <Parameter Name="linkId" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="resourceGroupName">
            Der Name der Ressourcengruppe, die die Ressource enthält. Dieser Wert kann über die Azure-Ressourcen-Manager-API oder das Portal abgerufen werden.
            </param>
        <param name="serverName">
            Der Name des Servers.
            </param>
        <param name="databaseName">
            Der Name der Datenbank auf den Link, um zu erhalten.
            </param>
        <param name="linkId">
            Die Replikation-Link-ID abgerufen werden sollen.
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Ruft ein datenbankreplikationslink ab.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByDatabase">
      <MemberSignature Language="C#" Value="public static System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.Sql.Models.ReplicationLink&gt; ListByDatabase (this Microsoft.Azure.Management.Sql.IReplicationLinksOperations operations, string resourceGroupName, string serverName, string databaseName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Management.Sql.Models.ReplicationLink&gt; ListByDatabase(class Microsoft.Azure.Management.Sql.IReplicationLinksOperations operations, string resourceGroupName, string serverName, string databaseName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.ReplicationLinksOperationsExtensions.ListByDatabase(Microsoft.Azure.Management.Sql.IReplicationLinksOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListByDatabase (operations As IReplicationLinksOperations, resourceGroupName As String, serverName As String, databaseName As String) As IEnumerable(Of ReplicationLink)" />
      <MemberSignature Language="F#" Value="static member ListByDatabase : Microsoft.Azure.Management.Sql.IReplicationLinksOperations * string * string * string -&gt; seq&lt;Microsoft.Azure.Management.Sql.Models.ReplicationLink&gt;" Usage="Microsoft.Azure.Management.Sql.ReplicationLinksOperationsExtensions.ListByDatabase (operations, resourceGroupName, serverName, databaseName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.Sql.Models.ReplicationLink&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Sql.IReplicationLinksOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="serverName" Type="System.String" />
        <Parameter Name="databaseName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="resourceGroupName">
            Der Name der Ressourcengruppe, die die Ressource enthält. Dieser Wert kann über die Azure-Ressourcen-Manager-API oder das Portal abgerufen werden.
            </param>
        <param name="serverName">
            Der Name des Servers.
            </param>
        <param name="databaseName">
            Der Name des abzurufenden Links für die Datenbank.
            </param>
        <summary>
            Listet eine datenbankreplikationslinks.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByDatabaseAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.Sql.Models.ReplicationLink&gt;&gt; ListByDatabaseAsync (this Microsoft.Azure.Management.Sql.IReplicationLinksOperations operations, string resourceGroupName, string serverName, string databaseName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Management.Sql.Models.ReplicationLink&gt;&gt; ListByDatabaseAsync(class Microsoft.Azure.Management.Sql.IReplicationLinksOperations operations, string resourceGroupName, string serverName, string databaseName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.ReplicationLinksOperationsExtensions.ListByDatabaseAsync(Microsoft.Azure.Management.Sql.IReplicationLinksOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListByDatabaseAsync : Microsoft.Azure.Management.Sql.IReplicationLinksOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;seq&lt;Microsoft.Azure.Management.Sql.Models.ReplicationLink&gt;&gt;" Usage="Microsoft.Azure.Management.Sql.ReplicationLinksOperationsExtensions.ListByDatabaseAsync (operations, resourceGroupName, serverName, databaseName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Sql.ReplicationLinksOperationsExtensions/&lt;ListByDatabaseAsync&gt;d__9))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.Sql.Models.ReplicationLink&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Sql.IReplicationLinksOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="serverName" Type="System.String" />
        <Parameter Name="databaseName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="resourceGroupName">
            Der Name der Ressourcengruppe, die die Ressource enthält. Dieser Wert kann über die Azure-Ressourcen-Manager-API oder das Portal abgerufen werden.
            </param>
        <param name="serverName">
            Der Name des Servers.
            </param>
        <param name="databaseName">
            Der Name des abzurufenden Links für die Datenbank.
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Listet eine datenbankreplikationslinks.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>