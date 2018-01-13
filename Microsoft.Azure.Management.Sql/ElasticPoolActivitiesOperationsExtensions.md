<Type Name="ElasticPoolActivitiesOperationsExtensions" FullName="Microsoft.Azure.Management.Sql.ElasticPoolActivitiesOperationsExtensions">
  <TypeSignature Language="C#" Value="public static class ElasticPoolActivitiesOperationsExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit ElasticPoolActivitiesOperationsExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Sql.ElasticPoolActivitiesOperationsExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module ElasticPoolActivitiesOperationsExtensions" />
  <TypeSignature Language="F#" Value="type ElasticPoolActivitiesOperationsExtensions = class" />
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
            Erweiterungsmethoden für ElasticPoolActivitiesOperations.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="ListByElasticPool">
      <MemberSignature Language="C#" Value="public static System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.Sql.Models.ElasticPoolActivity&gt; ListByElasticPool (this Microsoft.Azure.Management.Sql.IElasticPoolActivitiesOperations operations, string resourceGroupName, string serverName, string elasticPoolName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Management.Sql.Models.ElasticPoolActivity&gt; ListByElasticPool(class Microsoft.Azure.Management.Sql.IElasticPoolActivitiesOperations operations, string resourceGroupName, string serverName, string elasticPoolName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.ElasticPoolActivitiesOperationsExtensions.ListByElasticPool(Microsoft.Azure.Management.Sql.IElasticPoolActivitiesOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListByElasticPool (operations As IElasticPoolActivitiesOperations, resourceGroupName As String, serverName As String, elasticPoolName As String) As IEnumerable(Of ElasticPoolActivity)" />
      <MemberSignature Language="F#" Value="static member ListByElasticPool : Microsoft.Azure.Management.Sql.IElasticPoolActivitiesOperations * string * string * string -&gt; seq&lt;Microsoft.Azure.Management.Sql.Models.ElasticPoolActivity&gt;" Usage="Microsoft.Azure.Management.Sql.ElasticPoolActivitiesOperationsExtensions.ListByElasticPool (operations, resourceGroupName, serverName, elasticPoolName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.Sql.Models.ElasticPoolActivity&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Sql.IElasticPoolActivitiesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="serverName" Type="System.String" />
        <Parameter Name="elasticPoolName" Type="System.String" />
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
        <param name="elasticPoolName">
            Der Name des elastischen Pools für das Abrufen der aktuellen Aktivität.
            </param>
        <summary>
            Gibt Aktivitäten des Pools für elastische Datenbanken zurück
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByElasticPoolAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.Sql.Models.ElasticPoolActivity&gt;&gt; ListByElasticPoolAsync (this Microsoft.Azure.Management.Sql.IElasticPoolActivitiesOperations operations, string resourceGroupName, string serverName, string elasticPoolName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Management.Sql.Models.ElasticPoolActivity&gt;&gt; ListByElasticPoolAsync(class Microsoft.Azure.Management.Sql.IElasticPoolActivitiesOperations operations, string resourceGroupName, string serverName, string elasticPoolName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.ElasticPoolActivitiesOperationsExtensions.ListByElasticPoolAsync(Microsoft.Azure.Management.Sql.IElasticPoolActivitiesOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListByElasticPoolAsync : Microsoft.Azure.Management.Sql.IElasticPoolActivitiesOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;seq&lt;Microsoft.Azure.Management.Sql.Models.ElasticPoolActivity&gt;&gt;" Usage="Microsoft.Azure.Management.Sql.ElasticPoolActivitiesOperationsExtensions.ListByElasticPoolAsync (operations, resourceGroupName, serverName, elasticPoolName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Sql.ElasticPoolActivitiesOperationsExtensions/&lt;ListByElasticPoolAsync&gt;d__1))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.Sql.Models.ElasticPoolActivity&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Sql.IElasticPoolActivitiesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="serverName" Type="System.String" />
        <Parameter Name="elasticPoolName" Type="System.String" />
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
        <param name="elasticPoolName">
            Der Name des elastischen Pools für das Abrufen der aktuellen Aktivität.
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Gibt Aktivitäten des Pools für elastische Datenbanken zurück
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>