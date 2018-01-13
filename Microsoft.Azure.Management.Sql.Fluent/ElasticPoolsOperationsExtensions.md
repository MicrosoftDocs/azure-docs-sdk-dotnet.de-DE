<Type Name="ElasticPoolsOperationsExtensions" FullName="Microsoft.Azure.Management.Sql.Fluent.ElasticPoolsOperationsExtensions">
  <TypeSignature Language="C#" Value="public static class ElasticPoolsOperationsExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit ElasticPoolsOperationsExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Sql.Fluent.ElasticPoolsOperationsExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module ElasticPoolsOperationsExtensions" />
  <TypeSignature Language="F#" Value="type ElasticPoolsOperationsExtensions = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Sql.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            Erweiterungsmethoden für ElasticPoolsOperations.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="BeginCreateOrUpdateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Sql.Fluent.Models.ElasticPoolInner&gt; BeginCreateOrUpdateAsync (this Microsoft.Azure.Management.Sql.Fluent.IElasticPoolsOperations operations, string resourceGroupName, string serverName, string elasticPoolName, Microsoft.Azure.Management.Sql.Fluent.Models.ElasticPoolInner parameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Sql.Fluent.Models.ElasticPoolInner&gt; BeginCreateOrUpdateAsync(class Microsoft.Azure.Management.Sql.Fluent.IElasticPoolsOperations operations, string resourceGroupName, string serverName, string elasticPoolName, class Microsoft.Azure.Management.Sql.Fluent.Models.ElasticPoolInner parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.Fluent.ElasticPoolsOperationsExtensions.BeginCreateOrUpdateAsync(Microsoft.Azure.Management.Sql.Fluent.IElasticPoolsOperations,System.String,System.String,System.String,Microsoft.Azure.Management.Sql.Fluent.Models.ElasticPoolInner,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginCreateOrUpdateAsync : Microsoft.Azure.Management.Sql.Fluent.IElasticPoolsOperations * string * string * string * Microsoft.Azure.Management.Sql.Fluent.Models.ElasticPoolInner * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Sql.Fluent.Models.ElasticPoolInner&gt;" Usage="Microsoft.Azure.Management.Sql.Fluent.ElasticPoolsOperationsExtensions.BeginCreateOrUpdateAsync (operations, resourceGroupName, serverName, elasticPoolName, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Sql.Fluent.ElasticPoolsOperationsExtensions/&lt;BeginCreateOrUpdateAsync&gt;d__8))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Sql.Fluent.Models.ElasticPoolInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Sql.Fluent.IElasticPoolsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="serverName" Type="System.String" />
        <Parameter Name="elasticPoolName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Sql.Fluent.Models.ElasticPoolInner" />
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
            Der Name des Azure SQL-Servers.
            </param>
        <param name="elasticPoolName">
            Der Name der SQL Azure elastischen Pool verarbeitet werden sollen (aktualisiert oder erstellt wurde).
            </param>
        <param name="parameters">
            Die erforderlichen Parameter zum Erstellen oder Aktualisieren von einem elastischen Pool.
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Erstellt einen neuen elastischen Pool für SQL Azure oder aktualisiert einen vorhandenen elastischen Pool für SQL Azure.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateOrUpdateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Sql.Fluent.Models.ElasticPoolInner&gt; CreateOrUpdateAsync (this Microsoft.Azure.Management.Sql.Fluent.IElasticPoolsOperations operations, string resourceGroupName, string serverName, string elasticPoolName, Microsoft.Azure.Management.Sql.Fluent.Models.ElasticPoolInner parameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Sql.Fluent.Models.ElasticPoolInner&gt; CreateOrUpdateAsync(class Microsoft.Azure.Management.Sql.Fluent.IElasticPoolsOperations operations, string resourceGroupName, string serverName, string elasticPoolName, class Microsoft.Azure.Management.Sql.Fluent.Models.ElasticPoolInner parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.Fluent.ElasticPoolsOperationsExtensions.CreateOrUpdateAsync(Microsoft.Azure.Management.Sql.Fluent.IElasticPoolsOperations,System.String,System.String,System.String,Microsoft.Azure.Management.Sql.Fluent.Models.ElasticPoolInner,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member CreateOrUpdateAsync : Microsoft.Azure.Management.Sql.Fluent.IElasticPoolsOperations * string * string * string * Microsoft.Azure.Management.Sql.Fluent.Models.ElasticPoolInner * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Sql.Fluent.Models.ElasticPoolInner&gt;" Usage="Microsoft.Azure.Management.Sql.Fluent.ElasticPoolsOperationsExtensions.CreateOrUpdateAsync (operations, resourceGroupName, serverName, elasticPoolName, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Sql.Fluent.ElasticPoolsOperationsExtensions/&lt;CreateOrUpdateAsync&gt;d__0))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Sql.Fluent.Models.ElasticPoolInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Sql.Fluent.IElasticPoolsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="serverName" Type="System.String" />
        <Parameter Name="elasticPoolName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Sql.Fluent.Models.ElasticPoolInner" />
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
            Der Name des Azure SQL-Servers.
            </param>
        <param name="elasticPoolName">
            Der Name der SQL Azure elastischen Pool verarbeitet werden sollen (aktualisiert oder erstellt wurde).
            </param>
        <param name="parameters">
            Die erforderlichen Parameter zum Erstellen oder Aktualisieren von einem elastischen Pool.
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Erstellt einen neuen elastischen Pool für SQL Azure oder aktualisiert einen vorhandenen elastischen Pool für SQL Azure.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task DeleteAsync (this Microsoft.Azure.Management.Sql.Fluent.IElasticPoolsOperations operations, string resourceGroupName, string serverName, string elasticPoolName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task DeleteAsync(class Microsoft.Azure.Management.Sql.Fluent.IElasticPoolsOperations operations, string resourceGroupName, string serverName, string elasticPoolName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.Fluent.ElasticPoolsOperationsExtensions.DeleteAsync(Microsoft.Azure.Management.Sql.Fluent.IElasticPoolsOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member DeleteAsync : Microsoft.Azure.Management.Sql.Fluent.IElasticPoolsOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.Sql.Fluent.ElasticPoolsOperationsExtensions.DeleteAsync (operations, resourceGroupName, serverName, elasticPoolName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Sql.Fluent.ElasticPoolsOperationsExtensions/&lt;DeleteAsync&gt;d__1))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Sql.Fluent.IElasticPoolsOperations" RefType="this" />
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
            Der Name des Azure SQL-Servers.
            </param>
        <param name="elasticPoolName">
            Der Name des SQL Azure elastischen Pools gelöscht werden soll.
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Löscht den elastischen Pool für SQL Azure.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Sql.Fluent.Models.ElasticPoolInner&gt; GetAsync (this Microsoft.Azure.Management.Sql.Fluent.IElasticPoolsOperations operations, string resourceGroupName, string serverName, string elasticPoolName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Sql.Fluent.Models.ElasticPoolInner&gt; GetAsync(class Microsoft.Azure.Management.Sql.Fluent.IElasticPoolsOperations operations, string resourceGroupName, string serverName, string elasticPoolName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.Fluent.ElasticPoolsOperationsExtensions.GetAsync(Microsoft.Azure.Management.Sql.Fluent.IElasticPoolsOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetAsync : Microsoft.Azure.Management.Sql.Fluent.IElasticPoolsOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Sql.Fluent.Models.ElasticPoolInner&gt;" Usage="Microsoft.Azure.Management.Sql.Fluent.ElasticPoolsOperationsExtensions.GetAsync (operations, resourceGroupName, serverName, elasticPoolName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Sql.Fluent.ElasticPoolsOperationsExtensions/&lt;GetAsync&gt;d__2))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Sql.Fluent.Models.ElasticPoolInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Sql.Fluent.IElasticPoolsOperations" RefType="this" />
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
            Der Name des Azure SQL-Servers.
            </param>
        <param name="elasticPoolName">
            Der Name des SQL Azure elastischen Pools abgerufen werden sollen.
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Ruft Informationen zu einem elastischen Pool für SQL Azure ab.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetDatabaseAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Sql.Fluent.Models.DatabaseInner&gt; GetDatabaseAsync (this Microsoft.Azure.Management.Sql.Fluent.IElasticPoolsOperations operations, string resourceGroupName, string serverName, string elasticPoolName, string databaseName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Sql.Fluent.Models.DatabaseInner&gt; GetDatabaseAsync(class Microsoft.Azure.Management.Sql.Fluent.IElasticPoolsOperations operations, string resourceGroupName, string serverName, string elasticPoolName, string databaseName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.Fluent.ElasticPoolsOperationsExtensions.GetDatabaseAsync(Microsoft.Azure.Management.Sql.Fluent.IElasticPoolsOperations,System.String,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetDatabaseAsync : Microsoft.Azure.Management.Sql.Fluent.IElasticPoolsOperations * string * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Sql.Fluent.Models.DatabaseInner&gt;" Usage="Microsoft.Azure.Management.Sql.Fluent.ElasticPoolsOperationsExtensions.GetDatabaseAsync (operations, resourceGroupName, serverName, elasticPoolName, databaseName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Sql.Fluent.ElasticPoolsOperationsExtensions/&lt;GetDatabaseAsync&gt;d__6))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Sql.Fluent.Models.DatabaseInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Sql.Fluent.IElasticPoolsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="serverName" Type="System.String" />
        <Parameter Name="elasticPoolName" Type="System.String" />
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
            Der Name des Azure SQL-Servers.
            </param>
        <param name="elasticPoolName">
            Der Name des SQL Azure elastischen Pools abgerufen werden sollen.
            </param>
        <param name="databaseName">
            Der Name der Azure SQL-Datenbank abgerufen werden sollen.
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Ruft Informationen zu einer Azure SQL-Datenbank in einem elastischen Pool für SQL Azure ab.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListActivityAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.Sql.Fluent.Models.ElasticPoolActivityInner&gt;&gt; ListActivityAsync (this Microsoft.Azure.Management.Sql.Fluent.IElasticPoolsOperations operations, string resourceGroupName, string serverName, string elasticPoolName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Management.Sql.Fluent.Models.ElasticPoolActivityInner&gt;&gt; ListActivityAsync(class Microsoft.Azure.Management.Sql.Fluent.IElasticPoolsOperations operations, string resourceGroupName, string serverName, string elasticPoolName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.Fluent.ElasticPoolsOperationsExtensions.ListActivityAsync(Microsoft.Azure.Management.Sql.Fluent.IElasticPoolsOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListActivityAsync : Microsoft.Azure.Management.Sql.Fluent.IElasticPoolsOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;seq&lt;Microsoft.Azure.Management.Sql.Fluent.Models.ElasticPoolActivityInner&gt;&gt;" Usage="Microsoft.Azure.Management.Sql.Fluent.ElasticPoolsOperationsExtensions.ListActivityAsync (operations, resourceGroupName, serverName, elasticPoolName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Sql.Fluent.ElasticPoolsOperationsExtensions/&lt;ListActivityAsync&gt;d__4))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.Sql.Fluent.Models.ElasticPoolActivityInner&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Sql.Fluent.IElasticPoolsOperations" RefType="this" />
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
            Der Name des Azure SQL-Servers.
            </param>
        <param name="elasticPoolName">
            Der Name der SQL Azure elastischen Pool für das Abrufen der aktuellen Aktivität.
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Gibt Informationen zu SQL Azure elastischen Pool Aktivitäten zurück.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByServerAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.Sql.Fluent.Models.ElasticPoolInner&gt;&gt; ListByServerAsync (this Microsoft.Azure.Management.Sql.Fluent.IElasticPoolsOperations operations, string resourceGroupName, string serverName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Management.Sql.Fluent.Models.ElasticPoolInner&gt;&gt; ListByServerAsync(class Microsoft.Azure.Management.Sql.Fluent.IElasticPoolsOperations operations, string resourceGroupName, string serverName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.Fluent.ElasticPoolsOperationsExtensions.ListByServerAsync(Microsoft.Azure.Management.Sql.Fluent.IElasticPoolsOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListByServerAsync : Microsoft.Azure.Management.Sql.Fluent.IElasticPoolsOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;seq&lt;Microsoft.Azure.Management.Sql.Fluent.Models.ElasticPoolInner&gt;&gt;" Usage="Microsoft.Azure.Management.Sql.Fluent.ElasticPoolsOperationsExtensions.ListByServerAsync (operations, resourceGroupName, serverName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Sql.Fluent.ElasticPoolsOperationsExtensions/&lt;ListByServerAsync&gt;d__3))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.Sql.Fluent.Models.ElasticPoolInner&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Sql.Fluent.IElasticPoolsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="serverName" Type="System.String" />
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
            Der Name des Azure SQL-Servers.
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Gibt Informationen zu Azure SQL-elastische Pools.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListDatabaseActivityAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.Sql.Fluent.Models.ElasticPoolDatabaseActivityInner&gt;&gt; ListDatabaseActivityAsync (this Microsoft.Azure.Management.Sql.Fluent.IElasticPoolsOperations operations, string resourceGroupName, string serverName, string elasticPoolName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Management.Sql.Fluent.Models.ElasticPoolDatabaseActivityInner&gt;&gt; ListDatabaseActivityAsync(class Microsoft.Azure.Management.Sql.Fluent.IElasticPoolsOperations operations, string resourceGroupName, string serverName, string elasticPoolName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.Fluent.ElasticPoolsOperationsExtensions.ListDatabaseActivityAsync(Microsoft.Azure.Management.Sql.Fluent.IElasticPoolsOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListDatabaseActivityAsync : Microsoft.Azure.Management.Sql.Fluent.IElasticPoolsOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;seq&lt;Microsoft.Azure.Management.Sql.Fluent.Models.ElasticPoolDatabaseActivityInner&gt;&gt;" Usage="Microsoft.Azure.Management.Sql.Fluent.ElasticPoolsOperationsExtensions.ListDatabaseActivityAsync (operations, resourceGroupName, serverName, elasticPoolName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Sql.Fluent.ElasticPoolsOperationsExtensions/&lt;ListDatabaseActivityAsync&gt;d__5))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.Sql.Fluent.Models.ElasticPoolDatabaseActivityInner&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Sql.Fluent.IElasticPoolsOperations" RefType="this" />
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
            Der Name des Azure SQL-Servers.
            </param>
        <param name="elasticPoolName">
            Der Name des Azure SQL elastischen Pools.
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Informationen zur Aktivität zurückgegeben in Azure SQL-Datenbanken in einem elastischen Pool für SQL Azure.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListDatabasesAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.Sql.Fluent.Models.DatabaseInner&gt;&gt; ListDatabasesAsync (this Microsoft.Azure.Management.Sql.Fluent.IElasticPoolsOperations operations, string resourceGroupName, string serverName, string elasticPoolName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Management.Sql.Fluent.Models.DatabaseInner&gt;&gt; ListDatabasesAsync(class Microsoft.Azure.Management.Sql.Fluent.IElasticPoolsOperations operations, string resourceGroupName, string serverName, string elasticPoolName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.Fluent.ElasticPoolsOperationsExtensions.ListDatabasesAsync(Microsoft.Azure.Management.Sql.Fluent.IElasticPoolsOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListDatabasesAsync : Microsoft.Azure.Management.Sql.Fluent.IElasticPoolsOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;seq&lt;Microsoft.Azure.Management.Sql.Fluent.Models.DatabaseInner&gt;&gt;" Usage="Microsoft.Azure.Management.Sql.Fluent.ElasticPoolsOperationsExtensions.ListDatabasesAsync (operations, resourceGroupName, serverName, elasticPoolName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Sql.Fluent.ElasticPoolsOperationsExtensions/&lt;ListDatabasesAsync&gt;d__7))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.Sql.Fluent.Models.DatabaseInner&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Sql.Fluent.IElasticPoolsOperations" RefType="this" />
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
            Der Name des Azure SQL-Servers.
            </param>
        <param name="elasticPoolName">
            Der Name des SQL Azure elastischen Pools abgerufen werden sollen.
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Gibt Informationen zu einer Azure SQL-Datenbank in einem elastischen Pool für SQL Azure.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>