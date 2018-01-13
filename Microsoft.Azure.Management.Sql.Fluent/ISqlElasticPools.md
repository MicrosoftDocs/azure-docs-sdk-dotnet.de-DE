<Type Name="ISqlElasticPools" FullName="Microsoft.Azure.Management.Sql.Fluent.ISqlElasticPools">
  <TypeSignature Language="C#" Value="public interface ISqlElasticPools : Microsoft.Azure.Management.ResourceManager.Fluent.Core.CollectionActions.ISupportsBatchCreation&lt;Microsoft.Azure.Management.Sql.Fluent.ISqlElasticPool&gt;, Microsoft.Azure.Management.ResourceManager.Fluent.Core.CollectionActions.ISupportsCreating&lt;Microsoft.Azure.Management.Sql.Fluent.SqlElasticPool.Definition.IBlank&gt;, Microsoft.Azure.Management.ResourceManager.Fluent.Core.CollectionActions.ISupportsDeletingById, Microsoft.Azure.Management.ResourceManager.Fluent.Core.CollectionActions.ISupportsDeletingByParent, Microsoft.Azure.Management.ResourceManager.Fluent.Core.CollectionActions.ISupportsGettingById&lt;Microsoft.Azure.Management.Sql.Fluent.ISqlElasticPool&gt;, Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasInner&lt;Microsoft.Azure.Management.Sql.Fluent.IElasticPoolsOperations&gt;, Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasManager&lt;Microsoft.Azure.Management.Sql.Fluent.ISqlManager&gt;" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract ISqlElasticPools implements class Microsoft.Azure.Management.ResourceManager.Fluent.Core.CollectionActions.ISupportsBatchCreation`1&lt;class Microsoft.Azure.Management.Sql.Fluent.ISqlElasticPool&gt;, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.CollectionActions.ISupportsCreating`1&lt;class Microsoft.Azure.Management.Sql.Fluent.SqlElasticPool.Definition.IBlank&gt;, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.CollectionActions.ISupportsDeletingById, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.CollectionActions.ISupportsDeletingByParent, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.CollectionActions.ISupportsGettingById`1&lt;class Microsoft.Azure.Management.Sql.Fluent.ISqlElasticPool&gt;, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasInner`1&lt;class Microsoft.Azure.Management.Sql.Fluent.IElasticPoolsOperations&gt;, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasManager`1&lt;class Microsoft.Azure.Management.Sql.Fluent.ISqlManager&gt;" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Sql.Fluent.ISqlElasticPools" />
  <TypeSignature Language="VB.NET" Value="Public Interface ISqlElasticPools&#xA;Implements IHasInner(Of IElasticPoolsOperations), IHasManager(Of ISqlManager), ISupportsBatchCreation(Of ISqlElasticPool), ISupportsCreating(Of IBlank), ISupportsDeletingById, ISupportsDeletingByParent, ISupportsGettingById(Of ISqlElasticPool)" />
  <TypeSignature Language="F#" Value="type ISqlElasticPools = interface&#xA;    interface ISupportsCreating&lt;IBlank&gt;&#xA;    interface ISupportsDeletingById&#xA;    interface ISupportsGettingById&lt;ISqlElasticPool&gt;&#xA;    interface ISupportsBatchCreation&lt;ISqlElasticPool&gt;&#xA;    interface ISupportsDeletingByParent&#xA;    interface IHasManager&lt;ISqlManager&gt;&#xA;    interface IHasInner&lt;IElasticPoolsOperations&gt;" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Sql.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.ResourceManager.Fluent.Core.CollectionActions.ISupportsBatchCreation&lt;Microsoft.Azure.Management.Sql.Fluent.ISqlElasticPool&gt;</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.ResourceManager.Fluent.Core.CollectionActions.ISupportsCreating&lt;Microsoft.Azure.Management.Sql.Fluent.SqlElasticPool.Definition.IBlank&gt;</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.ResourceManager.Fluent.Core.CollectionActions.ISupportsDeletingById</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.ResourceManager.Fluent.Core.CollectionActions.ISupportsDeletingByParent</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.ResourceManager.Fluent.Core.CollectionActions.ISupportsGettingById&lt;Microsoft.Azure.Management.Sql.Fluent.ISqlElasticPool&gt;</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasInner&lt;Microsoft.Azure.Management.Sql.Fluent.IElasticPoolsOperations&gt;</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasManager&lt;Microsoft.Azure.Management.Sql.Fluent.ISqlManager&gt;</InterfaceName>
    </Interface>
  </Interfaces>
  <Docs>
    <summary>
            Einstiegspunkt für einen elastischen Pool für SQL-Verwaltungs-API.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="GetBySqlServer">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Sql.Fluent.ISqlElasticPool GetBySqlServer (Microsoft.Azure.Management.Sql.Fluent.ISqlServer sqlServer, string name);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Sql.Fluent.ISqlElasticPool GetBySqlServer(class Microsoft.Azure.Management.Sql.Fluent.ISqlServer sqlServer, string name) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.Fluent.ISqlElasticPools.GetBySqlServer(Microsoft.Azure.Management.Sql.Fluent.ISqlServer,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function GetBySqlServer (sqlServer As ISqlServer, name As String) As ISqlElasticPool" />
      <MemberSignature Language="F#" Value="abstract member GetBySqlServer : Microsoft.Azure.Management.Sql.Fluent.ISqlServer * string -&gt; Microsoft.Azure.Management.Sql.Fluent.ISqlElasticPool" Usage="iSqlElasticPools.GetBySqlServer (sqlServer, name)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Sql.Fluent.ISqlElasticPool</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="sqlServer" Type="Microsoft.Azure.Management.Sql.Fluent.ISqlServer" />
        <Parameter Name="name" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="sqlServer">die Instanz von SQL Server.</param>
        <param name="name">der Name des SQLElasticPool.</param>
        <summary>
            Ruft die SQLElasticPool basierend auf den SQL Server-Instanz und den SQLElasticPool Namen ab.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>Eine unveränderliche Darstellung der SQLElasticPool.</return>
      </Docs>
    </Member>
    <Member MemberName="GetBySqlServer">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Sql.Fluent.ISqlElasticPool GetBySqlServer (string resourceGroup, string sqlServerName, string name);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Sql.Fluent.ISqlElasticPool GetBySqlServer(string resourceGroup, string sqlServerName, string name) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.Fluent.ISqlElasticPools.GetBySqlServer(System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function GetBySqlServer (resourceGroup As String, sqlServerName As String, name As String) As ISqlElasticPool" />
      <MemberSignature Language="F#" Value="abstract member GetBySqlServer : string * string * string -&gt; Microsoft.Azure.Management.Sql.Fluent.ISqlElasticPool" Usage="iSqlElasticPools.GetBySqlServer (resourceGroup, sqlServerName, name)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Sql.Fluent.ISqlElasticPool</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroup" Type="System.String" />
        <Parameter Name="sqlServerName" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="resourceGroup">der Name der Ressourcengruppe.</param>
        <param name="sqlServerName">der Name der SQL Server.</param>
        <param name="name">der Name des SQLElasticPool.</param>
        <summary>
            Ruft die SQLElasticPool basierend auf der Name der Ressourcengruppe, SQL Server-Name und SQLElasticPool Namen ab.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>Eine unveränderliche Darstellung der SQLElasticPool.</return>
      </Docs>
    </Member>
    <Member MemberName="ListBySqlServer">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IReadOnlyList&lt;Microsoft.Azure.Management.Sql.Fluent.ISqlElasticPool&gt; ListBySqlServer (Microsoft.Azure.Management.Sql.Fluent.ISqlServer sqlServer);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Collections.Generic.IReadOnlyList`1&lt;class Microsoft.Azure.Management.Sql.Fluent.ISqlElasticPool&gt; ListBySqlServer(class Microsoft.Azure.Management.Sql.Fluent.ISqlServer sqlServer) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.Fluent.ISqlElasticPools.ListBySqlServer(Microsoft.Azure.Management.Sql.Fluent.ISqlServer)" />
      <MemberSignature Language="VB.NET" Value="Public Function ListBySqlServer (sqlServer As ISqlServer) As IReadOnlyList(Of ISqlElasticPool)" />
      <MemberSignature Language="F#" Value="abstract member ListBySqlServer : Microsoft.Azure.Management.Sql.Fluent.ISqlServer -&gt; System.Collections.Generic.IReadOnlyList&lt;Microsoft.Azure.Management.Sql.Fluent.ISqlElasticPool&gt;" Usage="iSqlElasticPools.ListBySqlServer sqlServer" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IReadOnlyList&lt;Microsoft.Azure.Management.Sql.Fluent.ISqlElasticPool&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="sqlServer" Type="Microsoft.Azure.Management.Sql.Fluent.ISqlServer" />
      </Parameters>
      <Docs>
        <param name="sqlServer">die Instanz von SQL Server.</param>
        <summary>
            Ruft die SQLElasticPool basierend auf dem SQL Server ab.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>Die Liste der SQLElasticPools in einem SQLServer.</return>
      </Docs>
    </Member>
    <Member MemberName="ListBySqlServer">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IReadOnlyList&lt;Microsoft.Azure.Management.Sql.Fluent.ISqlElasticPool&gt; ListBySqlServer (string resourceGroupName, string sqlServerName);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Collections.Generic.IReadOnlyList`1&lt;class Microsoft.Azure.Management.Sql.Fluent.ISqlElasticPool&gt; ListBySqlServer(string resourceGroupName, string sqlServerName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.Fluent.ISqlElasticPools.ListBySqlServer(System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function ListBySqlServer (resourceGroupName As String, sqlServerName As String) As IReadOnlyList(Of ISqlElasticPool)" />
      <MemberSignature Language="F#" Value="abstract member ListBySqlServer : string * string -&gt; System.Collections.Generic.IReadOnlyList&lt;Microsoft.Azure.Management.Sql.Fluent.ISqlElasticPool&gt;" Usage="iSqlElasticPools.ListBySqlServer (resourceGroupName, sqlServerName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IReadOnlyList&lt;Microsoft.Azure.Management.Sql.Fluent.ISqlElasticPool&gt;</ReturnType>
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
        <return>Die Liste der SQLElasticPools in einem SQLServer.</return>
      </Docs>
    </Member>
  </Members>
</Type>