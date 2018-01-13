<Type Name="DataMaskingRulesOperationsExtensions" FullName="Microsoft.Azure.Management.Sql.DataMaskingRulesOperationsExtensions">
  <TypeSignature Language="C#" Value="public static class DataMaskingRulesOperationsExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit DataMaskingRulesOperationsExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Sql.DataMaskingRulesOperationsExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module DataMaskingRulesOperationsExtensions" />
  <TypeSignature Language="F#" Value="type DataMaskingRulesOperationsExtensions = class" />
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
            Erweiterungsmethoden für DataMaskingRulesOperations.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="CreateOrUpdate">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Sql.Models.DataMaskingRule CreateOrUpdate (this Microsoft.Azure.Management.Sql.IDataMaskingRulesOperations operations, string resourceGroupName, string serverName, string databaseName, string dataMaskingRuleName, Microsoft.Azure.Management.Sql.Models.DataMaskingRule parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Sql.Models.DataMaskingRule CreateOrUpdate(class Microsoft.Azure.Management.Sql.IDataMaskingRulesOperations operations, string resourceGroupName, string serverName, string databaseName, string dataMaskingRuleName, class Microsoft.Azure.Management.Sql.Models.DataMaskingRule parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.DataMaskingRulesOperationsExtensions.CreateOrUpdate(Microsoft.Azure.Management.Sql.IDataMaskingRulesOperations,System.String,System.String,System.String,System.String,Microsoft.Azure.Management.Sql.Models.DataMaskingRule)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function CreateOrUpdate (operations As IDataMaskingRulesOperations, resourceGroupName As String, serverName As String, databaseName As String, dataMaskingRuleName As String, parameters As DataMaskingRule) As DataMaskingRule" />
      <MemberSignature Language="F#" Value="static member CreateOrUpdate : Microsoft.Azure.Management.Sql.IDataMaskingRulesOperations * string * string * string * string * Microsoft.Azure.Management.Sql.Models.DataMaskingRule -&gt; Microsoft.Azure.Management.Sql.Models.DataMaskingRule" Usage="Microsoft.Azure.Management.Sql.DataMaskingRulesOperationsExtensions.CreateOrUpdate (operations, resourceGroupName, serverName, databaseName, dataMaskingRuleName, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Sql.Models.DataMaskingRule</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Sql.IDataMaskingRulesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="serverName" Type="System.String" />
        <Parameter Name="databaseName" Type="System.String" />
        <Parameter Name="dataMaskingRuleName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Sql.Models.DataMaskingRule" />
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
            Der Name der Datenbank.
            </param>
        <param name="dataMaskingRuleName">
            Der Name der datenmaskierungsregel.
            </param>
        <param name="parameters">
            Die erforderlichen Parameter zum Erstellen oder Aktualisieren einer datenmaskierungsregel.
            </param>
        <summary>
            Erstellt oder aktualisiert eine datenmaskierungsregel Datenbank.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateOrUpdateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Sql.Models.DataMaskingRule&gt; CreateOrUpdateAsync (this Microsoft.Azure.Management.Sql.IDataMaskingRulesOperations operations, string resourceGroupName, string serverName, string databaseName, string dataMaskingRuleName, Microsoft.Azure.Management.Sql.Models.DataMaskingRule parameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Sql.Models.DataMaskingRule&gt; CreateOrUpdateAsync(class Microsoft.Azure.Management.Sql.IDataMaskingRulesOperations operations, string resourceGroupName, string serverName, string databaseName, string dataMaskingRuleName, class Microsoft.Azure.Management.Sql.Models.DataMaskingRule parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.DataMaskingRulesOperationsExtensions.CreateOrUpdateAsync(Microsoft.Azure.Management.Sql.IDataMaskingRulesOperations,System.String,System.String,System.String,System.String,Microsoft.Azure.Management.Sql.Models.DataMaskingRule,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member CreateOrUpdateAsync : Microsoft.Azure.Management.Sql.IDataMaskingRulesOperations * string * string * string * string * Microsoft.Azure.Management.Sql.Models.DataMaskingRule * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Sql.Models.DataMaskingRule&gt;" Usage="Microsoft.Azure.Management.Sql.DataMaskingRulesOperationsExtensions.CreateOrUpdateAsync (operations, resourceGroupName, serverName, databaseName, dataMaskingRuleName, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Sql.DataMaskingRulesOperationsExtensions/&lt;CreateOrUpdateAsync&gt;d__1))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Sql.Models.DataMaskingRule&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Sql.IDataMaskingRulesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="serverName" Type="System.String" />
        <Parameter Name="databaseName" Type="System.String" />
        <Parameter Name="dataMaskingRuleName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Sql.Models.DataMaskingRule" />
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
            Der Name der Datenbank.
            </param>
        <param name="dataMaskingRuleName">
            Der Name der datenmaskierungsregel.
            </param>
        <param name="parameters">
            Die erforderlichen Parameter zum Erstellen oder Aktualisieren einer datenmaskierungsregel.
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Erstellt oder aktualisiert eine datenmaskierungsregel Datenbank.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByDatabase">
      <MemberSignature Language="C#" Value="public static System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.Sql.Models.DataMaskingRule&gt; ListByDatabase (this Microsoft.Azure.Management.Sql.IDataMaskingRulesOperations operations, string resourceGroupName, string serverName, string databaseName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Management.Sql.Models.DataMaskingRule&gt; ListByDatabase(class Microsoft.Azure.Management.Sql.IDataMaskingRulesOperations operations, string resourceGroupName, string serverName, string databaseName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.DataMaskingRulesOperationsExtensions.ListByDatabase(Microsoft.Azure.Management.Sql.IDataMaskingRulesOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListByDatabase (operations As IDataMaskingRulesOperations, resourceGroupName As String, serverName As String, databaseName As String) As IEnumerable(Of DataMaskingRule)" />
      <MemberSignature Language="F#" Value="static member ListByDatabase : Microsoft.Azure.Management.Sql.IDataMaskingRulesOperations * string * string * string -&gt; seq&lt;Microsoft.Azure.Management.Sql.Models.DataMaskingRule&gt;" Usage="Microsoft.Azure.Management.Sql.DataMaskingRulesOperationsExtensions.ListByDatabase (operations, resourceGroupName, serverName, databaseName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.Sql.Models.DataMaskingRule&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Sql.IDataMaskingRulesOperations" RefType="this" />
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
            Der Name der Datenbank.
            </param>
        <summary>
            Ruft eine Liste von datenmaskierungsregeln Datenbank ab.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByDatabaseAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.Sql.Models.DataMaskingRule&gt;&gt; ListByDatabaseAsync (this Microsoft.Azure.Management.Sql.IDataMaskingRulesOperations operations, string resourceGroupName, string serverName, string databaseName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Management.Sql.Models.DataMaskingRule&gt;&gt; ListByDatabaseAsync(class Microsoft.Azure.Management.Sql.IDataMaskingRulesOperations operations, string resourceGroupName, string serverName, string databaseName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.DataMaskingRulesOperationsExtensions.ListByDatabaseAsync(Microsoft.Azure.Management.Sql.IDataMaskingRulesOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListByDatabaseAsync : Microsoft.Azure.Management.Sql.IDataMaskingRulesOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;seq&lt;Microsoft.Azure.Management.Sql.Models.DataMaskingRule&gt;&gt;" Usage="Microsoft.Azure.Management.Sql.DataMaskingRulesOperationsExtensions.ListByDatabaseAsync (operations, resourceGroupName, serverName, databaseName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Sql.DataMaskingRulesOperationsExtensions/&lt;ListByDatabaseAsync&gt;d__3))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.Sql.Models.DataMaskingRule&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Sql.IDataMaskingRulesOperations" RefType="this" />
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
            Der Name der Datenbank.
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Ruft eine Liste von datenmaskierungsregeln Datenbank ab.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>