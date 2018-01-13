<Type Name="SyncGroupsOperationsExtensions" FullName="Microsoft.Azure.Management.Sql.SyncGroupsOperationsExtensions">
  <TypeSignature Language="C#" Value="public static class SyncGroupsOperationsExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit SyncGroupsOperationsExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Sql.SyncGroupsOperationsExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module SyncGroupsOperationsExtensions" />
  <TypeSignature Language="F#" Value="type SyncGroupsOperationsExtensions = class" />
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
            Erweiterungsmethoden für SyncGroupsOperations.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="BeginCreateOrUpdate">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Sql.Models.SyncGroup BeginCreateOrUpdate (this Microsoft.Azure.Management.Sql.ISyncGroupsOperations operations, string resourceGroupName, string serverName, string databaseName, string syncGroupName, Microsoft.Azure.Management.Sql.Models.SyncGroup parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Sql.Models.SyncGroup BeginCreateOrUpdate(class Microsoft.Azure.Management.Sql.ISyncGroupsOperations operations, string resourceGroupName, string serverName, string databaseName, string syncGroupName, class Microsoft.Azure.Management.Sql.Models.SyncGroup parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.SyncGroupsOperationsExtensions.BeginCreateOrUpdate(Microsoft.Azure.Management.Sql.ISyncGroupsOperations,System.String,System.String,System.String,System.String,Microsoft.Azure.Management.Sql.Models.SyncGroup)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function BeginCreateOrUpdate (operations As ISyncGroupsOperations, resourceGroupName As String, serverName As String, databaseName As String, syncGroupName As String, parameters As SyncGroup) As SyncGroup" />
      <MemberSignature Language="F#" Value="static member BeginCreateOrUpdate : Microsoft.Azure.Management.Sql.ISyncGroupsOperations * string * string * string * string * Microsoft.Azure.Management.Sql.Models.SyncGroup -&gt; Microsoft.Azure.Management.Sql.Models.SyncGroup" Usage="Microsoft.Azure.Management.Sql.SyncGroupsOperationsExtensions.BeginCreateOrUpdate (operations, resourceGroupName, serverName, databaseName, syncGroupName, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Sql.Models.SyncGroup</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Sql.ISyncGroupsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="serverName" Type="System.String" />
        <Parameter Name="databaseName" Type="System.String" />
        <Parameter Name="syncGroupName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Sql.Models.SyncGroup" />
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
            Der Name der Datenbank auf der die Synchronisierungsgruppe gehostet wird.
            </param>
        <param name="syncGroupName">
            Der Name der Synchronisierungsgruppe.
            </param>
        <param name="parameters">
            Die angeforderte Gruppe Ressource Synchronisierungsstatus.
            </param>
        <summary>
            Erstellt oder aktualisiert eine Synchronisierungsgruppe.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginCreateOrUpdateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Sql.Models.SyncGroup&gt; BeginCreateOrUpdateAsync (this Microsoft.Azure.Management.Sql.ISyncGroupsOperations operations, string resourceGroupName, string serverName, string databaseName, string syncGroupName, Microsoft.Azure.Management.Sql.Models.SyncGroup parameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Sql.Models.SyncGroup&gt; BeginCreateOrUpdateAsync(class Microsoft.Azure.Management.Sql.ISyncGroupsOperations operations, string resourceGroupName, string serverName, string databaseName, string syncGroupName, class Microsoft.Azure.Management.Sql.Models.SyncGroup parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.SyncGroupsOperationsExtensions.BeginCreateOrUpdateAsync(Microsoft.Azure.Management.Sql.ISyncGroupsOperations,System.String,System.String,System.String,System.String,Microsoft.Azure.Management.Sql.Models.SyncGroup,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginCreateOrUpdateAsync : Microsoft.Azure.Management.Sql.ISyncGroupsOperations * string * string * string * string * Microsoft.Azure.Management.Sql.Models.SyncGroup * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Sql.Models.SyncGroup&gt;" Usage="Microsoft.Azure.Management.Sql.SyncGroupsOperationsExtensions.BeginCreateOrUpdateAsync (operations, resourceGroupName, serverName, databaseName, syncGroupName, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Sql.SyncGroupsOperationsExtensions/&lt;BeginCreateOrUpdateAsync&gt;d__25))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Sql.Models.SyncGroup&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Sql.ISyncGroupsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="serverName" Type="System.String" />
        <Parameter Name="databaseName" Type="System.String" />
        <Parameter Name="syncGroupName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Sql.Models.SyncGroup" />
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
            Der Name der Datenbank auf der die Synchronisierungsgruppe gehostet wird.
            </param>
        <param name="syncGroupName">
            Der Name der Synchronisierungsgruppe.
            </param>
        <param name="parameters">
            Die angeforderte Gruppe Ressource Synchronisierungsstatus.
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Erstellt oder aktualisiert eine Synchronisierungsgruppe.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginDelete">
      <MemberSignature Language="C#" Value="public static void BeginDelete (this Microsoft.Azure.Management.Sql.ISyncGroupsOperations operations, string resourceGroupName, string serverName, string databaseName, string syncGroupName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void BeginDelete(class Microsoft.Azure.Management.Sql.ISyncGroupsOperations operations, string resourceGroupName, string serverName, string databaseName, string syncGroupName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.SyncGroupsOperationsExtensions.BeginDelete(Microsoft.Azure.Management.Sql.ISyncGroupsOperations,System.String,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Sub BeginDelete (operations As ISyncGroupsOperations, resourceGroupName As String, serverName As String, databaseName As String, syncGroupName As String)" />
      <MemberSignature Language="F#" Value="static member BeginDelete : Microsoft.Azure.Management.Sql.ISyncGroupsOperations * string * string * string * string -&gt; unit" Usage="Microsoft.Azure.Management.Sql.SyncGroupsOperationsExtensions.BeginDelete (operations, resourceGroupName, serverName, databaseName, syncGroupName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Sql.ISyncGroupsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="serverName" Type="System.String" />
        <Parameter Name="databaseName" Type="System.String" />
        <Parameter Name="syncGroupName" Type="System.String" />
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
            Der Name der Datenbank auf der die Synchronisierungsgruppe gehostet wird.
            </param>
        <param name="syncGroupName">
            Der Name der Synchronisierungsgruppe.
            </param>
        <summary>
            Löscht eine Synchronisierungsgruppe an.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginDeleteAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task BeginDeleteAsync (this Microsoft.Azure.Management.Sql.ISyncGroupsOperations operations, string resourceGroupName, string serverName, string databaseName, string syncGroupName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task BeginDeleteAsync(class Microsoft.Azure.Management.Sql.ISyncGroupsOperations operations, string resourceGroupName, string serverName, string databaseName, string syncGroupName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.SyncGroupsOperationsExtensions.BeginDeleteAsync(Microsoft.Azure.Management.Sql.ISyncGroupsOperations,System.String,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginDeleteAsync : Microsoft.Azure.Management.Sql.ISyncGroupsOperations * string * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.Sql.SyncGroupsOperationsExtensions.BeginDeleteAsync (operations, resourceGroupName, serverName, databaseName, syncGroupName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Sql.SyncGroupsOperationsExtensions/&lt;BeginDeleteAsync&gt;d__27))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Sql.ISyncGroupsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="serverName" Type="System.String" />
        <Parameter Name="databaseName" Type="System.String" />
        <Parameter Name="syncGroupName" Type="System.String" />
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
            Der Name der Datenbank auf der die Synchronisierungsgruppe gehostet wird.
            </param>
        <param name="syncGroupName">
            Der Name der Synchronisierungsgruppe.
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Löscht eine Synchronisierungsgruppe an.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginRefreshHubSchema">
      <MemberSignature Language="C#" Value="public static void BeginRefreshHubSchema (this Microsoft.Azure.Management.Sql.ISyncGroupsOperations operations, string resourceGroupName, string serverName, string databaseName, string syncGroupName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void BeginRefreshHubSchema(class Microsoft.Azure.Management.Sql.ISyncGroupsOperations operations, string resourceGroupName, string serverName, string databaseName, string syncGroupName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.SyncGroupsOperationsExtensions.BeginRefreshHubSchema(Microsoft.Azure.Management.Sql.ISyncGroupsOperations,System.String,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Sub BeginRefreshHubSchema (operations As ISyncGroupsOperations, resourceGroupName As String, serverName As String, databaseName As String, syncGroupName As String)" />
      <MemberSignature Language="F#" Value="static member BeginRefreshHubSchema : Microsoft.Azure.Management.Sql.ISyncGroupsOperations * string * string * string * string -&gt; unit" Usage="Microsoft.Azure.Management.Sql.SyncGroupsOperationsExtensions.BeginRefreshHubSchema (operations, resourceGroupName, serverName, databaseName, syncGroupName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Sql.ISyncGroupsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="serverName" Type="System.String" />
        <Parameter Name="databaseName" Type="System.String" />
        <Parameter Name="syncGroupName" Type="System.String" />
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
            Der Name der Datenbank auf der die Synchronisierungsgruppe gehostet wird.
            </param>
        <param name="syncGroupName">
            Der Name der Synchronisierungsgruppe.
            </param>
        <summary>
            Aktualisiert ein Datenbankschema Hub.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginRefreshHubSchemaAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task BeginRefreshHubSchemaAsync (this Microsoft.Azure.Management.Sql.ISyncGroupsOperations operations, string resourceGroupName, string serverName, string databaseName, string syncGroupName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task BeginRefreshHubSchemaAsync(class Microsoft.Azure.Management.Sql.ISyncGroupsOperations operations, string resourceGroupName, string serverName, string databaseName, string syncGroupName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.SyncGroupsOperationsExtensions.BeginRefreshHubSchemaAsync(Microsoft.Azure.Management.Sql.ISyncGroupsOperations,System.String,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginRefreshHubSchemaAsync : Microsoft.Azure.Management.Sql.ISyncGroupsOperations * string * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.Sql.SyncGroupsOperationsExtensions.BeginRefreshHubSchemaAsync (operations, resourceGroupName, serverName, databaseName, syncGroupName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Sql.SyncGroupsOperationsExtensions/&lt;BeginRefreshHubSchemaAsync&gt;d__23))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Sql.ISyncGroupsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="serverName" Type="System.String" />
        <Parameter Name="databaseName" Type="System.String" />
        <Parameter Name="syncGroupName" Type="System.String" />
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
            Der Name der Datenbank auf der die Synchronisierungsgruppe gehostet wird.
            </param>
        <param name="syncGroupName">
            Der Name der Synchronisierungsgruppe.
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Aktualisiert ein Datenbankschema Hub.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginUpdate">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Sql.Models.SyncGroup BeginUpdate (this Microsoft.Azure.Management.Sql.ISyncGroupsOperations operations, string resourceGroupName, string serverName, string databaseName, string syncGroupName, Microsoft.Azure.Management.Sql.Models.SyncGroup parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Sql.Models.SyncGroup BeginUpdate(class Microsoft.Azure.Management.Sql.ISyncGroupsOperations operations, string resourceGroupName, string serverName, string databaseName, string syncGroupName, class Microsoft.Azure.Management.Sql.Models.SyncGroup parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.SyncGroupsOperationsExtensions.BeginUpdate(Microsoft.Azure.Management.Sql.ISyncGroupsOperations,System.String,System.String,System.String,System.String,Microsoft.Azure.Management.Sql.Models.SyncGroup)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function BeginUpdate (operations As ISyncGroupsOperations, resourceGroupName As String, serverName As String, databaseName As String, syncGroupName As String, parameters As SyncGroup) As SyncGroup" />
      <MemberSignature Language="F#" Value="static member BeginUpdate : Microsoft.Azure.Management.Sql.ISyncGroupsOperations * string * string * string * string * Microsoft.Azure.Management.Sql.Models.SyncGroup -&gt; Microsoft.Azure.Management.Sql.Models.SyncGroup" Usage="Microsoft.Azure.Management.Sql.SyncGroupsOperationsExtensions.BeginUpdate (operations, resourceGroupName, serverName, databaseName, syncGroupName, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Sql.Models.SyncGroup</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Sql.ISyncGroupsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="serverName" Type="System.String" />
        <Parameter Name="databaseName" Type="System.String" />
        <Parameter Name="syncGroupName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Sql.Models.SyncGroup" />
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
            Der Name der Datenbank auf der die Synchronisierungsgruppe gehostet wird.
            </param>
        <param name="syncGroupName">
            Der Name der Synchronisierungsgruppe.
            </param>
        <param name="parameters">
            Die angeforderte Gruppe Ressource Synchronisierungsstatus.
            </param>
        <summary>
            Aktualisiert eine Synchronisierungsgruppe an.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginUpdateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Sql.Models.SyncGroup&gt; BeginUpdateAsync (this Microsoft.Azure.Management.Sql.ISyncGroupsOperations operations, string resourceGroupName, string serverName, string databaseName, string syncGroupName, Microsoft.Azure.Management.Sql.Models.SyncGroup parameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Sql.Models.SyncGroup&gt; BeginUpdateAsync(class Microsoft.Azure.Management.Sql.ISyncGroupsOperations operations, string resourceGroupName, string serverName, string databaseName, string syncGroupName, class Microsoft.Azure.Management.Sql.Models.SyncGroup parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.SyncGroupsOperationsExtensions.BeginUpdateAsync(Microsoft.Azure.Management.Sql.ISyncGroupsOperations,System.String,System.String,System.String,System.String,Microsoft.Azure.Management.Sql.Models.SyncGroup,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginUpdateAsync : Microsoft.Azure.Management.Sql.ISyncGroupsOperations * string * string * string * string * Microsoft.Azure.Management.Sql.Models.SyncGroup * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Sql.Models.SyncGroup&gt;" Usage="Microsoft.Azure.Management.Sql.SyncGroupsOperationsExtensions.BeginUpdateAsync (operations, resourceGroupName, serverName, databaseName, syncGroupName, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Sql.SyncGroupsOperationsExtensions/&lt;BeginUpdateAsync&gt;d__29))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Sql.Models.SyncGroup&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Sql.ISyncGroupsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="serverName" Type="System.String" />
        <Parameter Name="databaseName" Type="System.String" />
        <Parameter Name="syncGroupName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Sql.Models.SyncGroup" />
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
            Der Name der Datenbank auf der die Synchronisierungsgruppe gehostet wird.
            </param>
        <param name="syncGroupName">
            Der Name der Synchronisierungsgruppe.
            </param>
        <param name="parameters">
            Die angeforderte Gruppe Ressource Synchronisierungsstatus.
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Aktualisiert eine Synchronisierungsgruppe an.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CancelSync">
      <MemberSignature Language="C#" Value="public static void CancelSync (this Microsoft.Azure.Management.Sql.ISyncGroupsOperations operations, string resourceGroupName, string serverName, string databaseName, string syncGroupName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void CancelSync(class Microsoft.Azure.Management.Sql.ISyncGroupsOperations operations, string resourceGroupName, string serverName, string databaseName, string syncGroupName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.SyncGroupsOperationsExtensions.CancelSync(Microsoft.Azure.Management.Sql.ISyncGroupsOperations,System.String,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Sub CancelSync (operations As ISyncGroupsOperations, resourceGroupName As String, serverName As String, databaseName As String, syncGroupName As String)" />
      <MemberSignature Language="F#" Value="static member CancelSync : Microsoft.Azure.Management.Sql.ISyncGroupsOperations * string * string * string * string -&gt; unit" Usage="Microsoft.Azure.Management.Sql.SyncGroupsOperationsExtensions.CancelSync (operations, resourceGroupName, serverName, databaseName, syncGroupName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Sql.ISyncGroupsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="serverName" Type="System.String" />
        <Parameter Name="databaseName" Type="System.String" />
        <Parameter Name="syncGroupName" Type="System.String" />
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
            Der Name der Datenbank auf der die Synchronisierungsgruppe gehostet wird.
            </param>
        <param name="syncGroupName">
            Der Name der Synchronisierungsgruppe.
            </param>
        <summary>
            Bricht eine Synchronisierung der Sync-Gruppe ab.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CancelSyncAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task CancelSyncAsync (this Microsoft.Azure.Management.Sql.ISyncGroupsOperations operations, string resourceGroupName, string serverName, string databaseName, string syncGroupName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task CancelSyncAsync(class Microsoft.Azure.Management.Sql.ISyncGroupsOperations operations, string resourceGroupName, string serverName, string databaseName, string syncGroupName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.SyncGroupsOperationsExtensions.CancelSyncAsync(Microsoft.Azure.Management.Sql.ISyncGroupsOperations,System.String,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member CancelSyncAsync : Microsoft.Azure.Management.Sql.ISyncGroupsOperations * string * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.Sql.SyncGroupsOperationsExtensions.CancelSyncAsync (operations, resourceGroupName, serverName, databaseName, syncGroupName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Sql.SyncGroupsOperationsExtensions/&lt;CancelSyncAsync&gt;d__9))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Sql.ISyncGroupsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="serverName" Type="System.String" />
        <Parameter Name="databaseName" Type="System.String" />
        <Parameter Name="syncGroupName" Type="System.String" />
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
            Der Name der Datenbank auf der die Synchronisierungsgruppe gehostet wird.
            </param>
        <param name="syncGroupName">
            Der Name der Synchronisierungsgruppe.
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Bricht eine Synchronisierung der Sync-Gruppe ab.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateOrUpdate">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Sql.Models.SyncGroup CreateOrUpdate (this Microsoft.Azure.Management.Sql.ISyncGroupsOperations operations, string resourceGroupName, string serverName, string databaseName, string syncGroupName, Microsoft.Azure.Management.Sql.Models.SyncGroup parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Sql.Models.SyncGroup CreateOrUpdate(class Microsoft.Azure.Management.Sql.ISyncGroupsOperations operations, string resourceGroupName, string serverName, string databaseName, string syncGroupName, class Microsoft.Azure.Management.Sql.Models.SyncGroup parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.SyncGroupsOperationsExtensions.CreateOrUpdate(Microsoft.Azure.Management.Sql.ISyncGroupsOperations,System.String,System.String,System.String,System.String,Microsoft.Azure.Management.Sql.Models.SyncGroup)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function CreateOrUpdate (operations As ISyncGroupsOperations, resourceGroupName As String, serverName As String, databaseName As String, syncGroupName As String, parameters As SyncGroup) As SyncGroup" />
      <MemberSignature Language="F#" Value="static member CreateOrUpdate : Microsoft.Azure.Management.Sql.ISyncGroupsOperations * string * string * string * string * Microsoft.Azure.Management.Sql.Models.SyncGroup -&gt; Microsoft.Azure.Management.Sql.Models.SyncGroup" Usage="Microsoft.Azure.Management.Sql.SyncGroupsOperationsExtensions.CreateOrUpdate (operations, resourceGroupName, serverName, databaseName, syncGroupName, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Sql.Models.SyncGroup</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Sql.ISyncGroupsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="serverName" Type="System.String" />
        <Parameter Name="databaseName" Type="System.String" />
        <Parameter Name="syncGroupName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Sql.Models.SyncGroup" />
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
            Der Name der Datenbank auf der die Synchronisierungsgruppe gehostet wird.
            </param>
        <param name="syncGroupName">
            Der Name der Synchronisierungsgruppe.
            </param>
        <param name="parameters">
            Die angeforderte Gruppe Ressource Synchronisierungsstatus.
            </param>
        <summary>
            Erstellt oder aktualisiert eine Synchronisierungsgruppe.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateOrUpdateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Sql.Models.SyncGroup&gt; CreateOrUpdateAsync (this Microsoft.Azure.Management.Sql.ISyncGroupsOperations operations, string resourceGroupName, string serverName, string databaseName, string syncGroupName, Microsoft.Azure.Management.Sql.Models.SyncGroup parameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Sql.Models.SyncGroup&gt; CreateOrUpdateAsync(class Microsoft.Azure.Management.Sql.ISyncGroupsOperations operations, string resourceGroupName, string serverName, string databaseName, string syncGroupName, class Microsoft.Azure.Management.Sql.Models.SyncGroup parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.SyncGroupsOperationsExtensions.CreateOrUpdateAsync(Microsoft.Azure.Management.Sql.ISyncGroupsOperations,System.String,System.String,System.String,System.String,Microsoft.Azure.Management.Sql.Models.SyncGroup,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member CreateOrUpdateAsync : Microsoft.Azure.Management.Sql.ISyncGroupsOperations * string * string * string * string * Microsoft.Azure.Management.Sql.Models.SyncGroup * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Sql.Models.SyncGroup&gt;" Usage="Microsoft.Azure.Management.Sql.SyncGroupsOperationsExtensions.CreateOrUpdateAsync (operations, resourceGroupName, serverName, databaseName, syncGroupName, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Sql.SyncGroupsOperationsExtensions/&lt;CreateOrUpdateAsync&gt;d__15))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Sql.Models.SyncGroup&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Sql.ISyncGroupsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="serverName" Type="System.String" />
        <Parameter Name="databaseName" Type="System.String" />
        <Parameter Name="syncGroupName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Sql.Models.SyncGroup" />
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
            Der Name der Datenbank auf der die Synchronisierungsgruppe gehostet wird.
            </param>
        <param name="syncGroupName">
            Der Name der Synchronisierungsgruppe.
            </param>
        <param name="parameters">
            Die angeforderte Gruppe Ressource Synchronisierungsstatus.
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Erstellt oder aktualisiert eine Synchronisierungsgruppe.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Delete">
      <MemberSignature Language="C#" Value="public static void Delete (this Microsoft.Azure.Management.Sql.ISyncGroupsOperations operations, string resourceGroupName, string serverName, string databaseName, string syncGroupName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void Delete(class Microsoft.Azure.Management.Sql.ISyncGroupsOperations operations, string resourceGroupName, string serverName, string databaseName, string syncGroupName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.SyncGroupsOperationsExtensions.Delete(Microsoft.Azure.Management.Sql.ISyncGroupsOperations,System.String,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Sub Delete (operations As ISyncGroupsOperations, resourceGroupName As String, serverName As String, databaseName As String, syncGroupName As String)" />
      <MemberSignature Language="F#" Value="static member Delete : Microsoft.Azure.Management.Sql.ISyncGroupsOperations * string * string * string * string -&gt; unit" Usage="Microsoft.Azure.Management.Sql.SyncGroupsOperationsExtensions.Delete (operations, resourceGroupName, serverName, databaseName, syncGroupName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Sql.ISyncGroupsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="serverName" Type="System.String" />
        <Parameter Name="databaseName" Type="System.String" />
        <Parameter Name="syncGroupName" Type="System.String" />
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
            Der Name der Datenbank auf der die Synchronisierungsgruppe gehostet wird.
            </param>
        <param name="syncGroupName">
            Der Name der Synchronisierungsgruppe.
            </param>
        <summary>
            Löscht eine Synchronisierungsgruppe an.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task DeleteAsync (this Microsoft.Azure.Management.Sql.ISyncGroupsOperations operations, string resourceGroupName, string serverName, string databaseName, string syncGroupName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task DeleteAsync(class Microsoft.Azure.Management.Sql.ISyncGroupsOperations operations, string resourceGroupName, string serverName, string databaseName, string syncGroupName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.SyncGroupsOperationsExtensions.DeleteAsync(Microsoft.Azure.Management.Sql.ISyncGroupsOperations,System.String,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member DeleteAsync : Microsoft.Azure.Management.Sql.ISyncGroupsOperations * string * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.Sql.SyncGroupsOperationsExtensions.DeleteAsync (operations, resourceGroupName, serverName, databaseName, syncGroupName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Sql.SyncGroupsOperationsExtensions/&lt;DeleteAsync&gt;d__17))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Sql.ISyncGroupsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="serverName" Type="System.String" />
        <Parameter Name="databaseName" Type="System.String" />
        <Parameter Name="syncGroupName" Type="System.String" />
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
            Der Name der Datenbank auf der die Synchronisierungsgruppe gehostet wird.
            </param>
        <param name="syncGroupName">
            Der Name der Synchronisierungsgruppe.
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Löscht eine Synchronisierungsgruppe an.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Get">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Sql.Models.SyncGroup Get (this Microsoft.Azure.Management.Sql.ISyncGroupsOperations operations, string resourceGroupName, string serverName, string databaseName, string syncGroupName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Sql.Models.SyncGroup Get(class Microsoft.Azure.Management.Sql.ISyncGroupsOperations operations, string resourceGroupName, string serverName, string databaseName, string syncGroupName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.SyncGroupsOperationsExtensions.Get(Microsoft.Azure.Management.Sql.ISyncGroupsOperations,System.String,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function Get (operations As ISyncGroupsOperations, resourceGroupName As String, serverName As String, databaseName As String, syncGroupName As String) As SyncGroup" />
      <MemberSignature Language="F#" Value="static member Get : Microsoft.Azure.Management.Sql.ISyncGroupsOperations * string * string * string * string -&gt; Microsoft.Azure.Management.Sql.Models.SyncGroup" Usage="Microsoft.Azure.Management.Sql.SyncGroupsOperationsExtensions.Get (operations, resourceGroupName, serverName, databaseName, syncGroupName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Sql.Models.SyncGroup</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Sql.ISyncGroupsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="serverName" Type="System.String" />
        <Parameter Name="databaseName" Type="System.String" />
        <Parameter Name="syncGroupName" Type="System.String" />
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
            Der Name der Datenbank auf der die Synchronisierungsgruppe gehostet wird.
            </param>
        <param name="syncGroupName">
            Der Name der Synchronisierungsgruppe.
            </param>
        <summary>
            Ruft eine Synchronisierungsgruppe ab.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Sql.Models.SyncGroup&gt; GetAsync (this Microsoft.Azure.Management.Sql.ISyncGroupsOperations operations, string resourceGroupName, string serverName, string databaseName, string syncGroupName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Sql.Models.SyncGroup&gt; GetAsync(class Microsoft.Azure.Management.Sql.ISyncGroupsOperations operations, string resourceGroupName, string serverName, string databaseName, string syncGroupName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.SyncGroupsOperationsExtensions.GetAsync(Microsoft.Azure.Management.Sql.ISyncGroupsOperations,System.String,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetAsync : Microsoft.Azure.Management.Sql.ISyncGroupsOperations * string * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Sql.Models.SyncGroup&gt;" Usage="Microsoft.Azure.Management.Sql.SyncGroupsOperationsExtensions.GetAsync (operations, resourceGroupName, serverName, databaseName, syncGroupName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Sql.SyncGroupsOperationsExtensions/&lt;GetAsync&gt;d__13))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Sql.Models.SyncGroup&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Sql.ISyncGroupsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="serverName" Type="System.String" />
        <Parameter Name="databaseName" Type="System.String" />
        <Parameter Name="syncGroupName" Type="System.String" />
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
            Der Name der Datenbank auf der die Synchronisierungsgruppe gehostet wird.
            </param>
        <param name="syncGroupName">
            Der Name der Synchronisierungsgruppe.
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Ruft eine Synchronisierungsgruppe ab.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByDatabase">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Sql.Models.SyncGroup&gt; ListByDatabase (this Microsoft.Azure.Management.Sql.ISyncGroupsOperations operations, string resourceGroupName, string serverName, string databaseName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Sql.Models.SyncGroup&gt; ListByDatabase(class Microsoft.Azure.Management.Sql.ISyncGroupsOperations operations, string resourceGroupName, string serverName, string databaseName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.SyncGroupsOperationsExtensions.ListByDatabase(Microsoft.Azure.Management.Sql.ISyncGroupsOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListByDatabase (operations As ISyncGroupsOperations, resourceGroupName As String, serverName As String, databaseName As String) As IPage(Of SyncGroup)" />
      <MemberSignature Language="F#" Value="static member ListByDatabase : Microsoft.Azure.Management.Sql.ISyncGroupsOperations * string * string * string -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Sql.Models.SyncGroup&gt;" Usage="Microsoft.Azure.Management.Sql.SyncGroupsOperationsExtensions.ListByDatabase (operations, resourceGroupName, serverName, databaseName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Sql.Models.SyncGroup&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Sql.ISyncGroupsOperations" RefType="this" />
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
            Der Name der Datenbank auf der die Synchronisierungsgruppe gehostet wird.
            </param>
        <summary>
            Listen Synchronisierungsgruppen, die in einer hubdatenbank.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByDatabaseAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Sql.Models.SyncGroup&gt;&gt; ListByDatabaseAsync (this Microsoft.Azure.Management.Sql.ISyncGroupsOperations operations, string resourceGroupName, string serverName, string databaseName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Sql.Models.SyncGroup&gt;&gt; ListByDatabaseAsync(class Microsoft.Azure.Management.Sql.ISyncGroupsOperations operations, string resourceGroupName, string serverName, string databaseName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.SyncGroupsOperationsExtensions.ListByDatabaseAsync(Microsoft.Azure.Management.Sql.ISyncGroupsOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListByDatabaseAsync : Microsoft.Azure.Management.Sql.ISyncGroupsOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Sql.Models.SyncGroup&gt;&gt;" Usage="Microsoft.Azure.Management.Sql.SyncGroupsOperationsExtensions.ListByDatabaseAsync (operations, resourceGroupName, serverName, databaseName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Sql.SyncGroupsOperationsExtensions/&lt;ListByDatabaseAsync&gt;d__21))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Sql.Models.SyncGroup&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Sql.ISyncGroupsOperations" RefType="this" />
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
            Der Name der Datenbank auf der die Synchronisierungsgruppe gehostet wird.
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Listen Synchronisierungsgruppen, die in einer hubdatenbank.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByDatabaseNext">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Sql.Models.SyncGroup&gt; ListByDatabaseNext (this Microsoft.Azure.Management.Sql.ISyncGroupsOperations operations, string nextPageLink);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Sql.Models.SyncGroup&gt; ListByDatabaseNext(class Microsoft.Azure.Management.Sql.ISyncGroupsOperations operations, string nextPageLink) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.SyncGroupsOperationsExtensions.ListByDatabaseNext(Microsoft.Azure.Management.Sql.ISyncGroupsOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListByDatabaseNext (operations As ISyncGroupsOperations, nextPageLink As String) As IPage(Of SyncGroup)" />
      <MemberSignature Language="F#" Value="static member ListByDatabaseNext : Microsoft.Azure.Management.Sql.ISyncGroupsOperations * string -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Sql.Models.SyncGroup&gt;" Usage="Microsoft.Azure.Management.Sql.SyncGroupsOperationsExtensions.ListByDatabaseNext (operations, nextPageLink)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Sql.Models.SyncGroup&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Sql.ISyncGroupsOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="nextPageLink">
            Die "NextLink" aus dem vorherigen erfolgreichen Aufruf List-Vorgangs.
            </param>
        <summary>
            Listen Synchronisierungsgruppen, die in einer hubdatenbank.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByDatabaseNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Sql.Models.SyncGroup&gt;&gt; ListByDatabaseNextAsync (this Microsoft.Azure.Management.Sql.ISyncGroupsOperations operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Sql.Models.SyncGroup&gt;&gt; ListByDatabaseNextAsync(class Microsoft.Azure.Management.Sql.ISyncGroupsOperations operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.SyncGroupsOperationsExtensions.ListByDatabaseNextAsync(Microsoft.Azure.Management.Sql.ISyncGroupsOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListByDatabaseNextAsync : Microsoft.Azure.Management.Sql.ISyncGroupsOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Sql.Models.SyncGroup&gt;&gt;" Usage="Microsoft.Azure.Management.Sql.SyncGroupsOperationsExtensions.ListByDatabaseNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Sql.SyncGroupsOperationsExtensions/&lt;ListByDatabaseNextAsync&gt;d__37))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Sql.Models.SyncGroup&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Sql.ISyncGroupsOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="nextPageLink">
            Die "NextLink" aus dem vorherigen erfolgreichen Aufruf List-Vorgangs.
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Listen Synchronisierungsgruppen, die in einer hubdatenbank.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListHubSchemas">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Sql.Models.SyncFullSchemaProperties&gt; ListHubSchemas (this Microsoft.Azure.Management.Sql.ISyncGroupsOperations operations, string resourceGroupName, string serverName, string databaseName, string syncGroupName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Sql.Models.SyncFullSchemaProperties&gt; ListHubSchemas(class Microsoft.Azure.Management.Sql.ISyncGroupsOperations operations, string resourceGroupName, string serverName, string databaseName, string syncGroupName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.SyncGroupsOperationsExtensions.ListHubSchemas(Microsoft.Azure.Management.Sql.ISyncGroupsOperations,System.String,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListHubSchemas (operations As ISyncGroupsOperations, resourceGroupName As String, serverName As String, databaseName As String, syncGroupName As String) As IPage(Of SyncFullSchemaProperties)" />
      <MemberSignature Language="F#" Value="static member ListHubSchemas : Microsoft.Azure.Management.Sql.ISyncGroupsOperations * string * string * string * string -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Sql.Models.SyncFullSchemaProperties&gt;" Usage="Microsoft.Azure.Management.Sql.SyncGroupsOperationsExtensions.ListHubSchemas (operations, resourceGroupName, serverName, databaseName, syncGroupName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Sql.Models.SyncFullSchemaProperties&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Sql.ISyncGroupsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="serverName" Type="System.String" />
        <Parameter Name="databaseName" Type="System.String" />
        <Parameter Name="syncGroupName" Type="System.String" />
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
            Der Name der Datenbank auf der die Synchronisierungsgruppe gehostet wird.
            </param>
        <param name="syncGroupName">
            Der Name der Synchronisierungsgruppe.
            </param>
        <summary>
            Ruft eine Auflistung von Hub-Datenbankschemas.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListHubSchemasAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Sql.Models.SyncFullSchemaProperties&gt;&gt; ListHubSchemasAsync (this Microsoft.Azure.Management.Sql.ISyncGroupsOperations operations, string resourceGroupName, string serverName, string databaseName, string syncGroupName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Sql.Models.SyncFullSchemaProperties&gt;&gt; ListHubSchemasAsync(class Microsoft.Azure.Management.Sql.ISyncGroupsOperations operations, string resourceGroupName, string serverName, string databaseName, string syncGroupName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.SyncGroupsOperationsExtensions.ListHubSchemasAsync(Microsoft.Azure.Management.Sql.ISyncGroupsOperations,System.String,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListHubSchemasAsync : Microsoft.Azure.Management.Sql.ISyncGroupsOperations * string * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Sql.Models.SyncFullSchemaProperties&gt;&gt;" Usage="Microsoft.Azure.Management.Sql.SyncGroupsOperationsExtensions.ListHubSchemasAsync (operations, resourceGroupName, serverName, databaseName, syncGroupName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Sql.SyncGroupsOperationsExtensions/&lt;ListHubSchemasAsync&gt;d__5))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Sql.Models.SyncFullSchemaProperties&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Sql.ISyncGroupsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="serverName" Type="System.String" />
        <Parameter Name="databaseName" Type="System.String" />
        <Parameter Name="syncGroupName" Type="System.String" />
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
            Der Name der Datenbank auf der die Synchronisierungsgruppe gehostet wird.
            </param>
        <param name="syncGroupName">
            Der Name der Synchronisierungsgruppe.
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Ruft eine Auflistung von Hub-Datenbankschemas.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListHubSchemasNext">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Sql.Models.SyncFullSchemaProperties&gt; ListHubSchemasNext (this Microsoft.Azure.Management.Sql.ISyncGroupsOperations operations, string nextPageLink);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Sql.Models.SyncFullSchemaProperties&gt; ListHubSchemasNext(class Microsoft.Azure.Management.Sql.ISyncGroupsOperations operations, string nextPageLink) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.SyncGroupsOperationsExtensions.ListHubSchemasNext(Microsoft.Azure.Management.Sql.ISyncGroupsOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListHubSchemasNext (operations As ISyncGroupsOperations, nextPageLink As String) As IPage(Of SyncFullSchemaProperties)" />
      <MemberSignature Language="F#" Value="static member ListHubSchemasNext : Microsoft.Azure.Management.Sql.ISyncGroupsOperations * string -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Sql.Models.SyncFullSchemaProperties&gt;" Usage="Microsoft.Azure.Management.Sql.SyncGroupsOperationsExtensions.ListHubSchemasNext (operations, nextPageLink)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Sql.Models.SyncFullSchemaProperties&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Sql.ISyncGroupsOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="nextPageLink">
            Die "NextLink" aus dem vorherigen erfolgreichen Aufruf List-Vorgangs.
            </param>
        <summary>
            Ruft eine Auflistung von Hub-Datenbankschemas.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListHubSchemasNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Sql.Models.SyncFullSchemaProperties&gt;&gt; ListHubSchemasNextAsync (this Microsoft.Azure.Management.Sql.ISyncGroupsOperations operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Sql.Models.SyncFullSchemaProperties&gt;&gt; ListHubSchemasNextAsync(class Microsoft.Azure.Management.Sql.ISyncGroupsOperations operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.SyncGroupsOperationsExtensions.ListHubSchemasNextAsync(Microsoft.Azure.Management.Sql.ISyncGroupsOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListHubSchemasNextAsync : Microsoft.Azure.Management.Sql.ISyncGroupsOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Sql.Models.SyncFullSchemaProperties&gt;&gt;" Usage="Microsoft.Azure.Management.Sql.SyncGroupsOperationsExtensions.ListHubSchemasNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Sql.SyncGroupsOperationsExtensions/&lt;ListHubSchemasNextAsync&gt;d__33))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Sql.Models.SyncFullSchemaProperties&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Sql.ISyncGroupsOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="nextPageLink">
            Die "NextLink" aus dem vorherigen erfolgreichen Aufruf List-Vorgangs.
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Ruft eine Auflistung von Hub-Datenbankschemas.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListLogs">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Sql.Models.SyncGroupLogProperties&gt; ListLogs (this Microsoft.Azure.Management.Sql.ISyncGroupsOperations operations, string resourceGroupName, string serverName, string databaseName, string syncGroupName, string startTime, string endTime, string type, string continuationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Sql.Models.SyncGroupLogProperties&gt; ListLogs(class Microsoft.Azure.Management.Sql.ISyncGroupsOperations operations, string resourceGroupName, string serverName, string databaseName, string syncGroupName, string startTime, string endTime, string type, string continuationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.SyncGroupsOperationsExtensions.ListLogs(Microsoft.Azure.Management.Sql.ISyncGroupsOperations,System.String,System.String,System.String,System.String,System.String,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListLogs (operations As ISyncGroupsOperations, resourceGroupName As String, serverName As String, databaseName As String, syncGroupName As String, startTime As String, endTime As String, type As String, Optional continuationToken As String = null) As IPage(Of SyncGroupLogProperties)" />
      <MemberSignature Language="F#" Value="static member ListLogs : Microsoft.Azure.Management.Sql.ISyncGroupsOperations * string * string * string * string * string * string * string * string -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Sql.Models.SyncGroupLogProperties&gt;" Usage="Microsoft.Azure.Management.Sql.SyncGroupsOperationsExtensions.ListLogs (operations, resourceGroupName, serverName, databaseName, syncGroupName, startTime, endTime, type, continuationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Sql.Models.SyncGroupLogProperties&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Sql.ISyncGroupsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="serverName" Type="System.String" />
        <Parameter Name="databaseName" Type="System.String" />
        <Parameter Name="syncGroupName" Type="System.String" />
        <Parameter Name="startTime" Type="System.String" />
        <Parameter Name="endTime" Type="System.String" />
        <Parameter Name="type" Type="System.String" />
        <Parameter Name="continuationToken" Type="System.String" />
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
            Der Name der Datenbank auf der die Synchronisierungsgruppe gehostet wird.
            </param>
        <param name="syncGroupName">
            Der Name der Synchronisierungsgruppe.
            </param>
        <param name="startTime">
            Abzurufen Sie Protokolle, die nach diesem Zeitpunkt generierten.
            </param>
        <param name="endTime">
            Rufen Sie die Protokolle, die vor diesem Zeitpunkt generiert.
            </param>
        <param name="type">
            Die Typen von Protokollen abgerufen werden soll. Folgende Werte sind möglich: "Alle", "Fehler", "Warnung", "Success"
            </param>
        <param name="continuationToken">
            Das Fortsetzungstoken für diesen Vorgang.
            </param>
        <summary>
            Ruft eine Auflistung von Synchronisierungsprotokollen für die Gruppe ab.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListLogsAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Sql.Models.SyncGroupLogProperties&gt;&gt; ListLogsAsync (this Microsoft.Azure.Management.Sql.ISyncGroupsOperations operations, string resourceGroupName, string serverName, string databaseName, string syncGroupName, string startTime, string endTime, string type, string continuationToken = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Sql.Models.SyncGroupLogProperties&gt;&gt; ListLogsAsync(class Microsoft.Azure.Management.Sql.ISyncGroupsOperations operations, string resourceGroupName, string serverName, string databaseName, string syncGroupName, string startTime, string endTime, string type, string continuationToken, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.SyncGroupsOperationsExtensions.ListLogsAsync(Microsoft.Azure.Management.Sql.ISyncGroupsOperations,System.String,System.String,System.String,System.String,System.String,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListLogsAsync : Microsoft.Azure.Management.Sql.ISyncGroupsOperations * string * string * string * string * string * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Sql.Models.SyncGroupLogProperties&gt;&gt;" Usage="Microsoft.Azure.Management.Sql.SyncGroupsOperationsExtensions.ListLogsAsync (operations, resourceGroupName, serverName, databaseName, syncGroupName, startTime, endTime, type, continuationToken, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Sql.SyncGroupsOperationsExtensions/&lt;ListLogsAsync&gt;d__7))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Sql.Models.SyncGroupLogProperties&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Sql.ISyncGroupsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="serverName" Type="System.String" />
        <Parameter Name="databaseName" Type="System.String" />
        <Parameter Name="syncGroupName" Type="System.String" />
        <Parameter Name="startTime" Type="System.String" />
        <Parameter Name="endTime" Type="System.String" />
        <Parameter Name="type" Type="System.String" />
        <Parameter Name="continuationToken" Type="System.String" />
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
            Der Name der Datenbank auf der die Synchronisierungsgruppe gehostet wird.
            </param>
        <param name="syncGroupName">
            Der Name der Synchronisierungsgruppe.
            </param>
        <param name="startTime">
            Abzurufen Sie Protokolle, die nach diesem Zeitpunkt generierten.
            </param>
        <param name="endTime">
            Rufen Sie die Protokolle, die vor diesem Zeitpunkt generiert.
            </param>
        <param name="type">
            Die Typen von Protokollen abgerufen werden soll. Folgende Werte sind möglich: "Alle", "Fehler", "Warnung", "Success"
            </param>
        <param name="continuationToken">
            Das Fortsetzungstoken für diesen Vorgang.
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Ruft eine Auflistung von Synchronisierungsprotokollen für die Gruppe ab.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListLogsNext">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Sql.Models.SyncGroupLogProperties&gt; ListLogsNext (this Microsoft.Azure.Management.Sql.ISyncGroupsOperations operations, string nextPageLink);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Sql.Models.SyncGroupLogProperties&gt; ListLogsNext(class Microsoft.Azure.Management.Sql.ISyncGroupsOperations operations, string nextPageLink) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.SyncGroupsOperationsExtensions.ListLogsNext(Microsoft.Azure.Management.Sql.ISyncGroupsOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListLogsNext (operations As ISyncGroupsOperations, nextPageLink As String) As IPage(Of SyncGroupLogProperties)" />
      <MemberSignature Language="F#" Value="static member ListLogsNext : Microsoft.Azure.Management.Sql.ISyncGroupsOperations * string -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Sql.Models.SyncGroupLogProperties&gt;" Usage="Microsoft.Azure.Management.Sql.SyncGroupsOperationsExtensions.ListLogsNext (operations, nextPageLink)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Sql.Models.SyncGroupLogProperties&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Sql.ISyncGroupsOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="nextPageLink">
            Die "NextLink" aus dem vorherigen erfolgreichen Aufruf List-Vorgangs.
            </param>
        <summary>
            Ruft eine Auflistung von Synchronisierungsprotokollen für die Gruppe ab.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListLogsNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Sql.Models.SyncGroupLogProperties&gt;&gt; ListLogsNextAsync (this Microsoft.Azure.Management.Sql.ISyncGroupsOperations operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Sql.Models.SyncGroupLogProperties&gt;&gt; ListLogsNextAsync(class Microsoft.Azure.Management.Sql.ISyncGroupsOperations operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.SyncGroupsOperationsExtensions.ListLogsNextAsync(Microsoft.Azure.Management.Sql.ISyncGroupsOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListLogsNextAsync : Microsoft.Azure.Management.Sql.ISyncGroupsOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Sql.Models.SyncGroupLogProperties&gt;&gt;" Usage="Microsoft.Azure.Management.Sql.SyncGroupsOperationsExtensions.ListLogsNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Sql.SyncGroupsOperationsExtensions/&lt;ListLogsNextAsync&gt;d__35))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Sql.Models.SyncGroupLogProperties&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Sql.ISyncGroupsOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="nextPageLink">
            Die "NextLink" aus dem vorherigen erfolgreichen Aufruf List-Vorgangs.
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Ruft eine Auflistung von Synchronisierungsprotokollen für die Gruppe ab.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListSyncDatabaseIds">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Sql.Models.SyncDatabaseIdProperties&gt; ListSyncDatabaseIds (this Microsoft.Azure.Management.Sql.ISyncGroupsOperations operations, string locationName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Sql.Models.SyncDatabaseIdProperties&gt; ListSyncDatabaseIds(class Microsoft.Azure.Management.Sql.ISyncGroupsOperations operations, string locationName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.SyncGroupsOperationsExtensions.ListSyncDatabaseIds(Microsoft.Azure.Management.Sql.ISyncGroupsOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListSyncDatabaseIds (operations As ISyncGroupsOperations, locationName As String) As IPage(Of SyncDatabaseIdProperties)" />
      <MemberSignature Language="F#" Value="static member ListSyncDatabaseIds : Microsoft.Azure.Management.Sql.ISyncGroupsOperations * string -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Sql.Models.SyncDatabaseIdProperties&gt;" Usage="Microsoft.Azure.Management.Sql.SyncGroupsOperationsExtensions.ListSyncDatabaseIds (operations, locationName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Sql.Models.SyncDatabaseIdProperties&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Sql.ISyncGroupsOperations" RefType="this" />
        <Parameter Name="locationName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="locationName">
            Der Name der Region, in dem die Ressource befindet.
            </param>
        <summary>
            Ruft eine Auflistung von Sync-Datenbank-Ids ab.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListSyncDatabaseIdsAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Sql.Models.SyncDatabaseIdProperties&gt;&gt; ListSyncDatabaseIdsAsync (this Microsoft.Azure.Management.Sql.ISyncGroupsOperations operations, string locationName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Sql.Models.SyncDatabaseIdProperties&gt;&gt; ListSyncDatabaseIdsAsync(class Microsoft.Azure.Management.Sql.ISyncGroupsOperations operations, string locationName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.SyncGroupsOperationsExtensions.ListSyncDatabaseIdsAsync(Microsoft.Azure.Management.Sql.ISyncGroupsOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListSyncDatabaseIdsAsync : Microsoft.Azure.Management.Sql.ISyncGroupsOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Sql.Models.SyncDatabaseIdProperties&gt;&gt;" Usage="Microsoft.Azure.Management.Sql.SyncGroupsOperationsExtensions.ListSyncDatabaseIdsAsync (operations, locationName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Sql.SyncGroupsOperationsExtensions/&lt;ListSyncDatabaseIdsAsync&gt;d__1))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Sql.Models.SyncDatabaseIdProperties&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Sql.ISyncGroupsOperations" RefType="this" />
        <Parameter Name="locationName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="locationName">
            Der Name der Region, in dem die Ressource befindet.
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Ruft eine Auflistung von Sync-Datenbank-Ids ab.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListSyncDatabaseIdsNext">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Sql.Models.SyncDatabaseIdProperties&gt; ListSyncDatabaseIdsNext (this Microsoft.Azure.Management.Sql.ISyncGroupsOperations operations, string nextPageLink);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Sql.Models.SyncDatabaseIdProperties&gt; ListSyncDatabaseIdsNext(class Microsoft.Azure.Management.Sql.ISyncGroupsOperations operations, string nextPageLink) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.SyncGroupsOperationsExtensions.ListSyncDatabaseIdsNext(Microsoft.Azure.Management.Sql.ISyncGroupsOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListSyncDatabaseIdsNext (operations As ISyncGroupsOperations, nextPageLink As String) As IPage(Of SyncDatabaseIdProperties)" />
      <MemberSignature Language="F#" Value="static member ListSyncDatabaseIdsNext : Microsoft.Azure.Management.Sql.ISyncGroupsOperations * string -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Sql.Models.SyncDatabaseIdProperties&gt;" Usage="Microsoft.Azure.Management.Sql.SyncGroupsOperationsExtensions.ListSyncDatabaseIdsNext (operations, nextPageLink)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Sql.Models.SyncDatabaseIdProperties&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Sql.ISyncGroupsOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="nextPageLink">
            Die "NextLink" aus dem vorherigen erfolgreichen Aufruf List-Vorgangs.
            </param>
        <summary>
            Ruft eine Auflistung von Sync-Datenbank-Ids ab.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListSyncDatabaseIdsNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Sql.Models.SyncDatabaseIdProperties&gt;&gt; ListSyncDatabaseIdsNextAsync (this Microsoft.Azure.Management.Sql.ISyncGroupsOperations operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Sql.Models.SyncDatabaseIdProperties&gt;&gt; ListSyncDatabaseIdsNextAsync(class Microsoft.Azure.Management.Sql.ISyncGroupsOperations operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.SyncGroupsOperationsExtensions.ListSyncDatabaseIdsNextAsync(Microsoft.Azure.Management.Sql.ISyncGroupsOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListSyncDatabaseIdsNextAsync : Microsoft.Azure.Management.Sql.ISyncGroupsOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Sql.Models.SyncDatabaseIdProperties&gt;&gt;" Usage="Microsoft.Azure.Management.Sql.SyncGroupsOperationsExtensions.ListSyncDatabaseIdsNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Sql.SyncGroupsOperationsExtensions/&lt;ListSyncDatabaseIdsNextAsync&gt;d__31))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Sql.Models.SyncDatabaseIdProperties&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Sql.ISyncGroupsOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="nextPageLink">
            Die "NextLink" aus dem vorherigen erfolgreichen Aufruf List-Vorgangs.
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Ruft eine Auflistung von Sync-Datenbank-Ids ab.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RefreshHubSchema">
      <MemberSignature Language="C#" Value="public static void RefreshHubSchema (this Microsoft.Azure.Management.Sql.ISyncGroupsOperations operations, string resourceGroupName, string serverName, string databaseName, string syncGroupName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void RefreshHubSchema(class Microsoft.Azure.Management.Sql.ISyncGroupsOperations operations, string resourceGroupName, string serverName, string databaseName, string syncGroupName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.SyncGroupsOperationsExtensions.RefreshHubSchema(Microsoft.Azure.Management.Sql.ISyncGroupsOperations,System.String,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Sub RefreshHubSchema (operations As ISyncGroupsOperations, resourceGroupName As String, serverName As String, databaseName As String, syncGroupName As String)" />
      <MemberSignature Language="F#" Value="static member RefreshHubSchema : Microsoft.Azure.Management.Sql.ISyncGroupsOperations * string * string * string * string -&gt; unit" Usage="Microsoft.Azure.Management.Sql.SyncGroupsOperationsExtensions.RefreshHubSchema (operations, resourceGroupName, serverName, databaseName, syncGroupName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Sql.ISyncGroupsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="serverName" Type="System.String" />
        <Parameter Name="databaseName" Type="System.String" />
        <Parameter Name="syncGroupName" Type="System.String" />
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
            Der Name der Datenbank auf der die Synchronisierungsgruppe gehostet wird.
            </param>
        <param name="syncGroupName">
            Der Name der Synchronisierungsgruppe.
            </param>
        <summary>
            Aktualisiert ein Datenbankschema Hub.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RefreshHubSchemaAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task RefreshHubSchemaAsync (this Microsoft.Azure.Management.Sql.ISyncGroupsOperations operations, string resourceGroupName, string serverName, string databaseName, string syncGroupName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task RefreshHubSchemaAsync(class Microsoft.Azure.Management.Sql.ISyncGroupsOperations operations, string resourceGroupName, string serverName, string databaseName, string syncGroupName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.SyncGroupsOperationsExtensions.RefreshHubSchemaAsync(Microsoft.Azure.Management.Sql.ISyncGroupsOperations,System.String,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member RefreshHubSchemaAsync : Microsoft.Azure.Management.Sql.ISyncGroupsOperations * string * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.Sql.SyncGroupsOperationsExtensions.RefreshHubSchemaAsync (operations, resourceGroupName, serverName, databaseName, syncGroupName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Sql.SyncGroupsOperationsExtensions/&lt;RefreshHubSchemaAsync&gt;d__3))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Sql.ISyncGroupsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="serverName" Type="System.String" />
        <Parameter Name="databaseName" Type="System.String" />
        <Parameter Name="syncGroupName" Type="System.String" />
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
            Der Name der Datenbank auf der die Synchronisierungsgruppe gehostet wird.
            </param>
        <param name="syncGroupName">
            Der Name der Synchronisierungsgruppe.
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Aktualisiert ein Datenbankschema Hub.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TriggerSync">
      <MemberSignature Language="C#" Value="public static void TriggerSync (this Microsoft.Azure.Management.Sql.ISyncGroupsOperations operations, string resourceGroupName, string serverName, string databaseName, string syncGroupName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void TriggerSync(class Microsoft.Azure.Management.Sql.ISyncGroupsOperations operations, string resourceGroupName, string serverName, string databaseName, string syncGroupName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.SyncGroupsOperationsExtensions.TriggerSync(Microsoft.Azure.Management.Sql.ISyncGroupsOperations,System.String,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Sub TriggerSync (operations As ISyncGroupsOperations, resourceGroupName As String, serverName As String, databaseName As String, syncGroupName As String)" />
      <MemberSignature Language="F#" Value="static member TriggerSync : Microsoft.Azure.Management.Sql.ISyncGroupsOperations * string * string * string * string -&gt; unit" Usage="Microsoft.Azure.Management.Sql.SyncGroupsOperationsExtensions.TriggerSync (operations, resourceGroupName, serverName, databaseName, syncGroupName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Sql.ISyncGroupsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="serverName" Type="System.String" />
        <Parameter Name="databaseName" Type="System.String" />
        <Parameter Name="syncGroupName" Type="System.String" />
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
            Der Name der Datenbank auf der die Synchronisierungsgruppe gehostet wird.
            </param>
        <param name="syncGroupName">
            Der Name der Synchronisierungsgruppe.
            </param>
        <summary>
            Löst eine Synchronisierung der Sync-Gruppe.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TriggerSyncAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task TriggerSyncAsync (this Microsoft.Azure.Management.Sql.ISyncGroupsOperations operations, string resourceGroupName, string serverName, string databaseName, string syncGroupName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task TriggerSyncAsync(class Microsoft.Azure.Management.Sql.ISyncGroupsOperations operations, string resourceGroupName, string serverName, string databaseName, string syncGroupName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.SyncGroupsOperationsExtensions.TriggerSyncAsync(Microsoft.Azure.Management.Sql.ISyncGroupsOperations,System.String,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member TriggerSyncAsync : Microsoft.Azure.Management.Sql.ISyncGroupsOperations * string * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.Sql.SyncGroupsOperationsExtensions.TriggerSyncAsync (operations, resourceGroupName, serverName, databaseName, syncGroupName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Sql.SyncGroupsOperationsExtensions/&lt;TriggerSyncAsync&gt;d__11))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Sql.ISyncGroupsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="serverName" Type="System.String" />
        <Parameter Name="databaseName" Type="System.String" />
        <Parameter Name="syncGroupName" Type="System.String" />
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
            Der Name der Datenbank auf der die Synchronisierungsgruppe gehostet wird.
            </param>
        <param name="syncGroupName">
            Der Name der Synchronisierungsgruppe.
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Löst eine Synchronisierung der Sync-Gruppe.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Update">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Sql.Models.SyncGroup Update (this Microsoft.Azure.Management.Sql.ISyncGroupsOperations operations, string resourceGroupName, string serverName, string databaseName, string syncGroupName, Microsoft.Azure.Management.Sql.Models.SyncGroup parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Sql.Models.SyncGroup Update(class Microsoft.Azure.Management.Sql.ISyncGroupsOperations operations, string resourceGroupName, string serverName, string databaseName, string syncGroupName, class Microsoft.Azure.Management.Sql.Models.SyncGroup parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.SyncGroupsOperationsExtensions.Update(Microsoft.Azure.Management.Sql.ISyncGroupsOperations,System.String,System.String,System.String,System.String,Microsoft.Azure.Management.Sql.Models.SyncGroup)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function Update (operations As ISyncGroupsOperations, resourceGroupName As String, serverName As String, databaseName As String, syncGroupName As String, parameters As SyncGroup) As SyncGroup" />
      <MemberSignature Language="F#" Value="static member Update : Microsoft.Azure.Management.Sql.ISyncGroupsOperations * string * string * string * string * Microsoft.Azure.Management.Sql.Models.SyncGroup -&gt; Microsoft.Azure.Management.Sql.Models.SyncGroup" Usage="Microsoft.Azure.Management.Sql.SyncGroupsOperationsExtensions.Update (operations, resourceGroupName, serverName, databaseName, syncGroupName, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Sql.Models.SyncGroup</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Sql.ISyncGroupsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="serverName" Type="System.String" />
        <Parameter Name="databaseName" Type="System.String" />
        <Parameter Name="syncGroupName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Sql.Models.SyncGroup" />
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
            Der Name der Datenbank auf der die Synchronisierungsgruppe gehostet wird.
            </param>
        <param name="syncGroupName">
            Der Name der Synchronisierungsgruppe.
            </param>
        <param name="parameters">
            Die angeforderte Gruppe Ressource Synchronisierungsstatus.
            </param>
        <summary>
            Aktualisiert eine Synchronisierungsgruppe an.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UpdateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Sql.Models.SyncGroup&gt; UpdateAsync (this Microsoft.Azure.Management.Sql.ISyncGroupsOperations operations, string resourceGroupName, string serverName, string databaseName, string syncGroupName, Microsoft.Azure.Management.Sql.Models.SyncGroup parameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Sql.Models.SyncGroup&gt; UpdateAsync(class Microsoft.Azure.Management.Sql.ISyncGroupsOperations operations, string resourceGroupName, string serverName, string databaseName, string syncGroupName, class Microsoft.Azure.Management.Sql.Models.SyncGroup parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.SyncGroupsOperationsExtensions.UpdateAsync(Microsoft.Azure.Management.Sql.ISyncGroupsOperations,System.String,System.String,System.String,System.String,Microsoft.Azure.Management.Sql.Models.SyncGroup,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member UpdateAsync : Microsoft.Azure.Management.Sql.ISyncGroupsOperations * string * string * string * string * Microsoft.Azure.Management.Sql.Models.SyncGroup * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Sql.Models.SyncGroup&gt;" Usage="Microsoft.Azure.Management.Sql.SyncGroupsOperationsExtensions.UpdateAsync (operations, resourceGroupName, serverName, databaseName, syncGroupName, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Sql.SyncGroupsOperationsExtensions/&lt;UpdateAsync&gt;d__19))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Sql.Models.SyncGroup&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Sql.ISyncGroupsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="serverName" Type="System.String" />
        <Parameter Name="databaseName" Type="System.String" />
        <Parameter Name="syncGroupName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Sql.Models.SyncGroup" />
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
            Der Name der Datenbank auf der die Synchronisierungsgruppe gehostet wird.
            </param>
        <param name="syncGroupName">
            Der Name der Synchronisierungsgruppe.
            </param>
        <param name="parameters">
            Die angeforderte Gruppe Ressource Synchronisierungsstatus.
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Aktualisiert eine Synchronisierungsgruppe an.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>