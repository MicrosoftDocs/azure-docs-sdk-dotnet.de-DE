<Type Name="ISqlDatabases" FullName="Microsoft.Azure.Management.Sql.Fluent.ISqlDatabases">
  <TypeSignature Language="C#" Value="public interface ISqlDatabases : Microsoft.Azure.Management.ResourceManager.Fluent.Core.CollectionActions.ISupportsBatchCreation&lt;Microsoft.Azure.Management.Sql.Fluent.ISqlDatabase&gt;, Microsoft.Azure.Management.ResourceManager.Fluent.Core.CollectionActions.ISupportsCreating&lt;Microsoft.Azure.Management.Sql.Fluent.SqlDatabase.Definition.IBlank&gt;, Microsoft.Azure.Management.ResourceManager.Fluent.Core.CollectionActions.ISupportsDeletingById, Microsoft.Azure.Management.ResourceManager.Fluent.Core.CollectionActions.ISupportsDeletingByParent, Microsoft.Azure.Management.ResourceManager.Fluent.Core.CollectionActions.ISupportsGettingById&lt;Microsoft.Azure.Management.Sql.Fluent.ISqlDatabase&gt;, Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasInner&lt;Microsoft.Azure.Management.Sql.Fluent.IDatabasesOperations&gt;, Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasManager&lt;Microsoft.Azure.Management.Sql.Fluent.ISqlManager&gt;" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract ISqlDatabases implements class Microsoft.Azure.Management.ResourceManager.Fluent.Core.CollectionActions.ISupportsBatchCreation`1&lt;class Microsoft.Azure.Management.Sql.Fluent.ISqlDatabase&gt;, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.CollectionActions.ISupportsCreating`1&lt;class Microsoft.Azure.Management.Sql.Fluent.SqlDatabase.Definition.IBlank&gt;, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.CollectionActions.ISupportsDeletingById, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.CollectionActions.ISupportsDeletingByParent, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.CollectionActions.ISupportsGettingById`1&lt;class Microsoft.Azure.Management.Sql.Fluent.ISqlDatabase&gt;, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasInner`1&lt;class Microsoft.Azure.Management.Sql.Fluent.IDatabasesOperations&gt;, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasManager`1&lt;class Microsoft.Azure.Management.Sql.Fluent.ISqlManager&gt;" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Sql.Fluent.ISqlDatabases" />
  <TypeSignature Language="VB.NET" Value="Public Interface ISqlDatabases&#xA;Implements IHasInner(Of IDatabasesOperations), IHasManager(Of ISqlManager), ISupportsBatchCreation(Of ISqlDatabase), ISupportsCreating(Of IBlank), ISupportsDeletingById, ISupportsDeletingByParent, ISupportsGettingById(Of ISqlDatabase)" />
  <TypeSignature Language="F#" Value="type ISqlDatabases = interface&#xA;    interface ISupportsCreating&lt;IBlank&gt;&#xA;    interface ISupportsDeletingById&#xA;    interface ISupportsGettingById&lt;ISqlDatabase&gt;&#xA;    interface ISupportsBatchCreation&lt;ISqlDatabase&gt;&#xA;    interface ISupportsDeletingByParent&#xA;    interface IHasManager&lt;ISqlManager&gt;&#xA;    interface IHasInner&lt;IDatabasesOperations&gt;" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Sql.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.ResourceManager.Fluent.Core.CollectionActions.ISupportsBatchCreation&lt;Microsoft.Azure.Management.Sql.Fluent.ISqlDatabase&gt;</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.ResourceManager.Fluent.Core.CollectionActions.ISupportsCreating&lt;Microsoft.Azure.Management.Sql.Fluent.SqlDatabase.Definition.IBlank&gt;</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.ResourceManager.Fluent.Core.CollectionActions.ISupportsDeletingById</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.ResourceManager.Fluent.Core.CollectionActions.ISupportsDeletingByParent</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.ResourceManager.Fluent.Core.CollectionActions.ISupportsGettingById&lt;Microsoft.Azure.Management.Sql.Fluent.ISqlDatabase&gt;</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasInner&lt;Microsoft.Azure.Management.Sql.Fluent.IDatabasesOperations&gt;</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasManager&lt;Microsoft.Azure.Management.Sql.Fluent.ISqlManager&gt;</InterfaceName>
    </Interface>
  </Interfaces>
  <Docs>
    <summary>
            Einstiegspunkt für einen SQL-datenbankverwaltungs-API.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="GetBySqlServer">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Sql.Fluent.ISqlDatabase GetBySqlServer (Microsoft.Azure.Management.Sql.Fluent.ISqlServer sqlServer, string name);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Sql.Fluent.ISqlDatabase GetBySqlServer(class Microsoft.Azure.Management.Sql.Fluent.ISqlServer sqlServer, string name) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.Fluent.ISqlDatabases.GetBySqlServer(Microsoft.Azure.Management.Sql.Fluent.ISqlServer,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function GetBySqlServer (sqlServer As ISqlServer, name As String) As ISqlDatabase" />
      <MemberSignature Language="F#" Value="abstract member GetBySqlServer : Microsoft.Azure.Management.Sql.Fluent.ISqlServer * string -&gt; Microsoft.Azure.Management.Sql.Fluent.ISqlDatabase" Usage="iSqlDatabases.GetBySqlServer (sqlServer, name)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Sql.Fluent.ISqlDatabase</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="sqlServer" Type="Microsoft.Azure.Management.Sql.Fluent.ISqlServer" />
        <Parameter Name="name" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="sqlServer">die Instanz von SQL Server.</param>
        <param name="name">der Name der SQL-Datenbank.</param>
        <summary>
            Ruft die SQL-Datenbank basierend auf den SQL Server-Instanz und den Namen der SQL-Datenbank ab.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>Eine unveränderliche Darstellung der SQL-Datenbank.</return>
      </Docs>
    </Member>
    <Member MemberName="GetBySqlServer">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Sql.Fluent.ISqlDatabase GetBySqlServer (string resourceGroup, string sqlServerName, string name);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Sql.Fluent.ISqlDatabase GetBySqlServer(string resourceGroup, string sqlServerName, string name) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.Fluent.ISqlDatabases.GetBySqlServer(System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function GetBySqlServer (resourceGroup As String, sqlServerName As String, name As String) As ISqlDatabase" />
      <MemberSignature Language="F#" Value="abstract member GetBySqlServer : string * string * string -&gt; Microsoft.Azure.Management.Sql.Fluent.ISqlDatabase" Usage="iSqlDatabases.GetBySqlServer (resourceGroup, sqlServerName, name)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Sql.Fluent.ISqlDatabase</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroup" Type="System.String" />
        <Parameter Name="sqlServerName" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="resourceGroup">der Name der Ressourcengruppe.</param>
        <param name="sqlServerName">der Name der SQL Server.</param>
        <param name="name">der Name der SQL-Datenbank.</param>
        <summary>
            Ruft die SQL-Datenbank basierend auf der Name der Ressourcengruppe, SQL Server-Name und Name der SQL-Datenbank ab.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>Eine unveränderliche Darstellung der SQL-Datenbank.</return>
      </Docs>
    </Member>
    <Member MemberName="ListBySqlServer">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IReadOnlyList&lt;Microsoft.Azure.Management.Sql.Fluent.ISqlDatabase&gt; ListBySqlServer (Microsoft.Azure.Management.Sql.Fluent.ISqlServer sqlServer);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Collections.Generic.IReadOnlyList`1&lt;class Microsoft.Azure.Management.Sql.Fluent.ISqlDatabase&gt; ListBySqlServer(class Microsoft.Azure.Management.Sql.Fluent.ISqlServer sqlServer) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.Fluent.ISqlDatabases.ListBySqlServer(Microsoft.Azure.Management.Sql.Fluent.ISqlServer)" />
      <MemberSignature Language="VB.NET" Value="Public Function ListBySqlServer (sqlServer As ISqlServer) As IReadOnlyList(Of ISqlDatabase)" />
      <MemberSignature Language="F#" Value="abstract member ListBySqlServer : Microsoft.Azure.Management.Sql.Fluent.ISqlServer -&gt; System.Collections.Generic.IReadOnlyList&lt;Microsoft.Azure.Management.Sql.Fluent.ISqlDatabase&gt;" Usage="iSqlDatabases.ListBySqlServer sqlServer" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IReadOnlyList&lt;Microsoft.Azure.Management.Sql.Fluent.ISqlDatabase&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="sqlServer" Type="Microsoft.Azure.Management.Sql.Fluent.ISqlServer" />
      </Parameters>
      <Docs>
        <param name="sqlServer">die Instanz von SQL Server.</param>
        <summary>
            Ruft die SQL-Datenbank basierend auf dem SQL Server ab.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>Die Liste der SQLDatabases in einem SQLServer.</return>
      </Docs>
    </Member>
    <Member MemberName="ListBySqlServer">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IReadOnlyList&lt;Microsoft.Azure.Management.Sql.Fluent.ISqlDatabase&gt; ListBySqlServer (string resourceGroupName, string sqlServerName);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Collections.Generic.IReadOnlyList`1&lt;class Microsoft.Azure.Management.Sql.Fluent.ISqlDatabase&gt; ListBySqlServer(string resourceGroupName, string sqlServerName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.Fluent.ISqlDatabases.ListBySqlServer(System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function ListBySqlServer (resourceGroupName As String, sqlServerName As String) As IReadOnlyList(Of ISqlDatabase)" />
      <MemberSignature Language="F#" Value="abstract member ListBySqlServer : string * string -&gt; System.Collections.Generic.IReadOnlyList&lt;Microsoft.Azure.Management.Sql.Fluent.ISqlDatabase&gt;" Usage="iSqlDatabases.ListBySqlServer (resourceGroupName, sqlServerName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IReadOnlyList&lt;Microsoft.Azure.Management.Sql.Fluent.ISqlDatabase&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="sqlServerName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">Der Name der Ressourcengruppe zum Auflisten der Ressourcen aus.</param>
        <param name="sqlServerName">der Name der SQL Server.</param>
        <summary>
            Listet die Ressourcen des angegebenen Typs in der angegebenen Ressourcengruppe und SQLServer.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>Die Liste der SQLDatabases in einem SQLServer.</return>
      </Docs>
    </Member>
  </Members>
</Type>