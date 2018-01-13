<Type Name="SyncMembersOperationsExtensions" FullName="Microsoft.Azure.Management.Sql.SyncMembersOperationsExtensions">
  <TypeSignature Language="C#" Value="public static class SyncMembersOperationsExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit SyncMembersOperationsExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Sql.SyncMembersOperationsExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module SyncMembersOperationsExtensions" />
  <TypeSignature Language="F#" Value="type SyncMembersOperationsExtensions = class" />
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
            Erweiterungsmethoden für SyncMembersOperations.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="BeginCreateOrUpdate">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Sql.Models.SyncMember BeginCreateOrUpdate (this Microsoft.Azure.Management.Sql.ISyncMembersOperations operations, string resourceGroupName, string serverName, string databaseName, string syncGroupName, string syncMemberName, Microsoft.Azure.Management.Sql.Models.SyncMember parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Sql.Models.SyncMember BeginCreateOrUpdate(class Microsoft.Azure.Management.Sql.ISyncMembersOperations operations, string resourceGroupName, string serverName, string databaseName, string syncGroupName, string syncMemberName, class Microsoft.Azure.Management.Sql.Models.SyncMember parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.SyncMembersOperationsExtensions.BeginCreateOrUpdate(Microsoft.Azure.Management.Sql.ISyncMembersOperations,System.String,System.String,System.String,System.String,System.String,Microsoft.Azure.Management.Sql.Models.SyncMember)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function BeginCreateOrUpdate (operations As ISyncMembersOperations, resourceGroupName As String, serverName As String, databaseName As String, syncGroupName As String, syncMemberName As String, parameters As SyncMember) As SyncMember" />
      <MemberSignature Language="F#" Value="static member BeginCreateOrUpdate : Microsoft.Azure.Management.Sql.ISyncMembersOperations * string * string * string * string * string * Microsoft.Azure.Management.Sql.Models.SyncMember -&gt; Microsoft.Azure.Management.Sql.Models.SyncMember" Usage="Microsoft.Azure.Management.Sql.SyncMembersOperationsExtensions.BeginCreateOrUpdate (operations, resourceGroupName, serverName, databaseName, syncGroupName, syncMemberName, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Sql.Models.SyncMember</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Sql.ISyncMembersOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="serverName" Type="System.String" />
        <Parameter Name="databaseName" Type="System.String" />
        <Parameter Name="syncGroupName" Type="System.String" />
        <Parameter Name="syncMemberName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Sql.Models.SyncMember" />
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
            Der Name der Synchronisierungsgruppe auf der das Sync-Element gehostet wird.
            </param>
        <param name="syncMemberName">
            Der Name des Sync-Elements.
            </param>
        <param name="parameters">
            Der angeforderte Sync Ressourcenstatus des Elements.
            </param>
        <summary>
            Erstellt oder aktualisiert ein Sync-Element.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginCreateOrUpdateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Sql.Models.SyncMember&gt; BeginCreateOrUpdateAsync (this Microsoft.Azure.Management.Sql.ISyncMembersOperations operations, string resourceGroupName, string serverName, string databaseName, string syncGroupName, string syncMemberName, Microsoft.Azure.Management.Sql.Models.SyncMember parameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Sql.Models.SyncMember&gt; BeginCreateOrUpdateAsync(class Microsoft.Azure.Management.Sql.ISyncMembersOperations operations, string resourceGroupName, string serverName, string databaseName, string syncGroupName, string syncMemberName, class Microsoft.Azure.Management.Sql.Models.SyncMember parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.SyncMembersOperationsExtensions.BeginCreateOrUpdateAsync(Microsoft.Azure.Management.Sql.ISyncMembersOperations,System.String,System.String,System.String,System.String,System.String,Microsoft.Azure.Management.Sql.Models.SyncMember,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginCreateOrUpdateAsync : Microsoft.Azure.Management.Sql.ISyncMembersOperations * string * string * string * string * string * Microsoft.Azure.Management.Sql.Models.SyncMember * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Sql.Models.SyncMember&gt;" Usage="Microsoft.Azure.Management.Sql.SyncMembersOperationsExtensions.BeginCreateOrUpdateAsync (operations, resourceGroupName, serverName, databaseName, syncGroupName, syncMemberName, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Sql.SyncMembersOperationsExtensions/&lt;BeginCreateOrUpdateAsync&gt;d__15))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Sql.Models.SyncMember&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Sql.ISyncMembersOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="serverName" Type="System.String" />
        <Parameter Name="databaseName" Type="System.String" />
        <Parameter Name="syncGroupName" Type="System.String" />
        <Parameter Name="syncMemberName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Sql.Models.SyncMember" />
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
            Der Name der Synchronisierungsgruppe auf der das Sync-Element gehostet wird.
            </param>
        <param name="syncMemberName">
            Der Name des Sync-Elements.
            </param>
        <param name="parameters">
            Der angeforderte Sync Ressourcenstatus des Elements.
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Erstellt oder aktualisiert ein Sync-Element.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginDelete">
      <MemberSignature Language="C#" Value="public static void BeginDelete (this Microsoft.Azure.Management.Sql.ISyncMembersOperations operations, string resourceGroupName, string serverName, string databaseName, string syncGroupName, string syncMemberName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void BeginDelete(class Microsoft.Azure.Management.Sql.ISyncMembersOperations operations, string resourceGroupName, string serverName, string databaseName, string syncGroupName, string syncMemberName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.SyncMembersOperationsExtensions.BeginDelete(Microsoft.Azure.Management.Sql.ISyncMembersOperations,System.String,System.String,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Sub BeginDelete (operations As ISyncMembersOperations, resourceGroupName As String, serverName As String, databaseName As String, syncGroupName As String, syncMemberName As String)" />
      <MemberSignature Language="F#" Value="static member BeginDelete : Microsoft.Azure.Management.Sql.ISyncMembersOperations * string * string * string * string * string -&gt; unit" Usage="Microsoft.Azure.Management.Sql.SyncMembersOperationsExtensions.BeginDelete (operations, resourceGroupName, serverName, databaseName, syncGroupName, syncMemberName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Sql.ISyncMembersOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="serverName" Type="System.String" />
        <Parameter Name="databaseName" Type="System.String" />
        <Parameter Name="syncGroupName" Type="System.String" />
        <Parameter Name="syncMemberName" Type="System.String" />
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
            Der Name der Synchronisierungsgruppe auf der das Sync-Element gehostet wird.
            </param>
        <param name="syncMemberName">
            Der Name des Sync-Elements.
            </param>
        <summary>
            Löscht ein Sync-Element.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginDeleteAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task BeginDeleteAsync (this Microsoft.Azure.Management.Sql.ISyncMembersOperations operations, string resourceGroupName, string serverName, string databaseName, string syncGroupName, string syncMemberName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task BeginDeleteAsync(class Microsoft.Azure.Management.Sql.ISyncMembersOperations operations, string resourceGroupName, string serverName, string databaseName, string syncGroupName, string syncMemberName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.SyncMembersOperationsExtensions.BeginDeleteAsync(Microsoft.Azure.Management.Sql.ISyncMembersOperations,System.String,System.String,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginDeleteAsync : Microsoft.Azure.Management.Sql.ISyncMembersOperations * string * string * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.Sql.SyncMembersOperationsExtensions.BeginDeleteAsync (operations, resourceGroupName, serverName, databaseName, syncGroupName, syncMemberName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Sql.SyncMembersOperationsExtensions/&lt;BeginDeleteAsync&gt;d__17))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Sql.ISyncMembersOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="serverName" Type="System.String" />
        <Parameter Name="databaseName" Type="System.String" />
        <Parameter Name="syncGroupName" Type="System.String" />
        <Parameter Name="syncMemberName" Type="System.String" />
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
            Der Name der Synchronisierungsgruppe auf der das Sync-Element gehostet wird.
            </param>
        <param name="syncMemberName">
            Der Name des Sync-Elements.
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Löscht ein Sync-Element.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginRefreshMemberSchema">
      <MemberSignature Language="C#" Value="public static void BeginRefreshMemberSchema (this Microsoft.Azure.Management.Sql.ISyncMembersOperations operations, string resourceGroupName, string serverName, string databaseName, string syncGroupName, string syncMemberName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void BeginRefreshMemberSchema(class Microsoft.Azure.Management.Sql.ISyncMembersOperations operations, string resourceGroupName, string serverName, string databaseName, string syncGroupName, string syncMemberName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.SyncMembersOperationsExtensions.BeginRefreshMemberSchema(Microsoft.Azure.Management.Sql.ISyncMembersOperations,System.String,System.String,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Sub BeginRefreshMemberSchema (operations As ISyncMembersOperations, resourceGroupName As String, serverName As String, databaseName As String, syncGroupName As String, syncMemberName As String)" />
      <MemberSignature Language="F#" Value="static member BeginRefreshMemberSchema : Microsoft.Azure.Management.Sql.ISyncMembersOperations * string * string * string * string * string -&gt; unit" Usage="Microsoft.Azure.Management.Sql.SyncMembersOperationsExtensions.BeginRefreshMemberSchema (operations, resourceGroupName, serverName, databaseName, syncGroupName, syncMemberName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Sql.ISyncMembersOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="serverName" Type="System.String" />
        <Parameter Name="databaseName" Type="System.String" />
        <Parameter Name="syncGroupName" Type="System.String" />
        <Parameter Name="syncMemberName" Type="System.String" />
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
            Der Name der Synchronisierungsgruppe auf der das Sync-Element gehostet wird.
            </param>
        <param name="syncMemberName">
            Der Name des Sync-Elements.
            </param>
        <summary>
            Aktualisiert ein Datenbankschema der Sync-Element.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginRefreshMemberSchemaAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task BeginRefreshMemberSchemaAsync (this Microsoft.Azure.Management.Sql.ISyncMembersOperations operations, string resourceGroupName, string serverName, string databaseName, string syncGroupName, string syncMemberName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task BeginRefreshMemberSchemaAsync(class Microsoft.Azure.Management.Sql.ISyncMembersOperations operations, string resourceGroupName, string serverName, string databaseName, string syncGroupName, string syncMemberName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.SyncMembersOperationsExtensions.BeginRefreshMemberSchemaAsync(Microsoft.Azure.Management.Sql.ISyncMembersOperations,System.String,System.String,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginRefreshMemberSchemaAsync : Microsoft.Azure.Management.Sql.ISyncMembersOperations * string * string * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.Sql.SyncMembersOperationsExtensions.BeginRefreshMemberSchemaAsync (operations, resourceGroupName, serverName, databaseName, syncGroupName, syncMemberName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Sql.SyncMembersOperationsExtensions/&lt;BeginRefreshMemberSchemaAsync&gt;d__21))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Sql.ISyncMembersOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="serverName" Type="System.String" />
        <Parameter Name="databaseName" Type="System.String" />
        <Parameter Name="syncGroupName" Type="System.String" />
        <Parameter Name="syncMemberName" Type="System.String" />
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
            Der Name der Synchronisierungsgruppe auf der das Sync-Element gehostet wird.
            </param>
        <param name="syncMemberName">
            Der Name des Sync-Elements.
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Aktualisiert ein Datenbankschema der Sync-Element.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginUpdate">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Sql.Models.SyncMember BeginUpdate (this Microsoft.Azure.Management.Sql.ISyncMembersOperations operations, string resourceGroupName, string serverName, string databaseName, string syncGroupName, string syncMemberName, Microsoft.Azure.Management.Sql.Models.SyncMember parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Sql.Models.SyncMember BeginUpdate(class Microsoft.Azure.Management.Sql.ISyncMembersOperations operations, string resourceGroupName, string serverName, string databaseName, string syncGroupName, string syncMemberName, class Microsoft.Azure.Management.Sql.Models.SyncMember parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.SyncMembersOperationsExtensions.BeginUpdate(Microsoft.Azure.Management.Sql.ISyncMembersOperations,System.String,System.String,System.String,System.String,System.String,Microsoft.Azure.Management.Sql.Models.SyncMember)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function BeginUpdate (operations As ISyncMembersOperations, resourceGroupName As String, serverName As String, databaseName As String, syncGroupName As String, syncMemberName As String, parameters As SyncMember) As SyncMember" />
      <MemberSignature Language="F#" Value="static member BeginUpdate : Microsoft.Azure.Management.Sql.ISyncMembersOperations * string * string * string * string * string * Microsoft.Azure.Management.Sql.Models.SyncMember -&gt; Microsoft.Azure.Management.Sql.Models.SyncMember" Usage="Microsoft.Azure.Management.Sql.SyncMembersOperationsExtensions.BeginUpdate (operations, resourceGroupName, serverName, databaseName, syncGroupName, syncMemberName, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Sql.Models.SyncMember</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Sql.ISyncMembersOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="serverName" Type="System.String" />
        <Parameter Name="databaseName" Type="System.String" />
        <Parameter Name="syncGroupName" Type="System.String" />
        <Parameter Name="syncMemberName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Sql.Models.SyncMember" />
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
            Der Name der Synchronisierungsgruppe auf der das Sync-Element gehostet wird.
            </param>
        <param name="syncMemberName">
            Der Name des Sync-Elements.
            </param>
        <param name="parameters">
            Der angeforderte Sync Ressourcenstatus des Elements.
            </param>
        <summary>
            Aktualisiert ein vorhandenes Sync-Element.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginUpdateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Sql.Models.SyncMember&gt; BeginUpdateAsync (this Microsoft.Azure.Management.Sql.ISyncMembersOperations operations, string resourceGroupName, string serverName, string databaseName, string syncGroupName, string syncMemberName, Microsoft.Azure.Management.Sql.Models.SyncMember parameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Sql.Models.SyncMember&gt; BeginUpdateAsync(class Microsoft.Azure.Management.Sql.ISyncMembersOperations operations, string resourceGroupName, string serverName, string databaseName, string syncGroupName, string syncMemberName, class Microsoft.Azure.Management.Sql.Models.SyncMember parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.SyncMembersOperationsExtensions.BeginUpdateAsync(Microsoft.Azure.Management.Sql.ISyncMembersOperations,System.String,System.String,System.String,System.String,System.String,Microsoft.Azure.Management.Sql.Models.SyncMember,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginUpdateAsync : Microsoft.Azure.Management.Sql.ISyncMembersOperations * string * string * string * string * string * Microsoft.Azure.Management.Sql.Models.SyncMember * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Sql.Models.SyncMember&gt;" Usage="Microsoft.Azure.Management.Sql.SyncMembersOperationsExtensions.BeginUpdateAsync (operations, resourceGroupName, serverName, databaseName, syncGroupName, syncMemberName, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Sql.SyncMembersOperationsExtensions/&lt;BeginUpdateAsync&gt;d__19))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Sql.Models.SyncMember&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Sql.ISyncMembersOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="serverName" Type="System.String" />
        <Parameter Name="databaseName" Type="System.String" />
        <Parameter Name="syncGroupName" Type="System.String" />
        <Parameter Name="syncMemberName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Sql.Models.SyncMember" />
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
            Der Name der Synchronisierungsgruppe auf der das Sync-Element gehostet wird.
            </param>
        <param name="syncMemberName">
            Der Name des Sync-Elements.
            </param>
        <param name="parameters">
            Der angeforderte Sync Ressourcenstatus des Elements.
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Aktualisiert ein vorhandenes Sync-Element.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateOrUpdate">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Sql.Models.SyncMember CreateOrUpdate (this Microsoft.Azure.Management.Sql.ISyncMembersOperations operations, string resourceGroupName, string serverName, string databaseName, string syncGroupName, string syncMemberName, Microsoft.Azure.Management.Sql.Models.SyncMember parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Sql.Models.SyncMember CreateOrUpdate(class Microsoft.Azure.Management.Sql.ISyncMembersOperations operations, string resourceGroupName, string serverName, string databaseName, string syncGroupName, string syncMemberName, class Microsoft.Azure.Management.Sql.Models.SyncMember parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.SyncMembersOperationsExtensions.CreateOrUpdate(Microsoft.Azure.Management.Sql.ISyncMembersOperations,System.String,System.String,System.String,System.String,System.String,Microsoft.Azure.Management.Sql.Models.SyncMember)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function CreateOrUpdate (operations As ISyncMembersOperations, resourceGroupName As String, serverName As String, databaseName As String, syncGroupName As String, syncMemberName As String, parameters As SyncMember) As SyncMember" />
      <MemberSignature Language="F#" Value="static member CreateOrUpdate : Microsoft.Azure.Management.Sql.ISyncMembersOperations * string * string * string * string * string * Microsoft.Azure.Management.Sql.Models.SyncMember -&gt; Microsoft.Azure.Management.Sql.Models.SyncMember" Usage="Microsoft.Azure.Management.Sql.SyncMembersOperationsExtensions.CreateOrUpdate (operations, resourceGroupName, serverName, databaseName, syncGroupName, syncMemberName, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Sql.Models.SyncMember</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Sql.ISyncMembersOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="serverName" Type="System.String" />
        <Parameter Name="databaseName" Type="System.String" />
        <Parameter Name="syncGroupName" Type="System.String" />
        <Parameter Name="syncMemberName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Sql.Models.SyncMember" />
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
            Der Name der Synchronisierungsgruppe auf der das Sync-Element gehostet wird.
            </param>
        <param name="syncMemberName">
            Der Name des Sync-Elements.
            </param>
        <param name="parameters">
            Der angeforderte Sync Ressourcenstatus des Elements.
            </param>
        <summary>
            Erstellt oder aktualisiert ein Sync-Element.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateOrUpdateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Sql.Models.SyncMember&gt; CreateOrUpdateAsync (this Microsoft.Azure.Management.Sql.ISyncMembersOperations operations, string resourceGroupName, string serverName, string databaseName, string syncGroupName, string syncMemberName, Microsoft.Azure.Management.Sql.Models.SyncMember parameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Sql.Models.SyncMember&gt; CreateOrUpdateAsync(class Microsoft.Azure.Management.Sql.ISyncMembersOperations operations, string resourceGroupName, string serverName, string databaseName, string syncGroupName, string syncMemberName, class Microsoft.Azure.Management.Sql.Models.SyncMember parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.SyncMembersOperationsExtensions.CreateOrUpdateAsync(Microsoft.Azure.Management.Sql.ISyncMembersOperations,System.String,System.String,System.String,System.String,System.String,Microsoft.Azure.Management.Sql.Models.SyncMember,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member CreateOrUpdateAsync : Microsoft.Azure.Management.Sql.ISyncMembersOperations * string * string * string * string * string * Microsoft.Azure.Management.Sql.Models.SyncMember * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Sql.Models.SyncMember&gt;" Usage="Microsoft.Azure.Management.Sql.SyncMembersOperationsExtensions.CreateOrUpdateAsync (operations, resourceGroupName, serverName, databaseName, syncGroupName, syncMemberName, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Sql.SyncMembersOperationsExtensions/&lt;CreateOrUpdateAsync&gt;d__3))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Sql.Models.SyncMember&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Sql.ISyncMembersOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="serverName" Type="System.String" />
        <Parameter Name="databaseName" Type="System.String" />
        <Parameter Name="syncGroupName" Type="System.String" />
        <Parameter Name="syncMemberName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Sql.Models.SyncMember" />
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
            Der Name der Synchronisierungsgruppe auf der das Sync-Element gehostet wird.
            </param>
        <param name="syncMemberName">
            Der Name des Sync-Elements.
            </param>
        <param name="parameters">
            Der angeforderte Sync Ressourcenstatus des Elements.
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Erstellt oder aktualisiert ein Sync-Element.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Delete">
      <MemberSignature Language="C#" Value="public static void Delete (this Microsoft.Azure.Management.Sql.ISyncMembersOperations operations, string resourceGroupName, string serverName, string databaseName, string syncGroupName, string syncMemberName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void Delete(class Microsoft.Azure.Management.Sql.ISyncMembersOperations operations, string resourceGroupName, string serverName, string databaseName, string syncGroupName, string syncMemberName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.SyncMembersOperationsExtensions.Delete(Microsoft.Azure.Management.Sql.ISyncMembersOperations,System.String,System.String,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Sub Delete (operations As ISyncMembersOperations, resourceGroupName As String, serverName As String, databaseName As String, syncGroupName As String, syncMemberName As String)" />
      <MemberSignature Language="F#" Value="static member Delete : Microsoft.Azure.Management.Sql.ISyncMembersOperations * string * string * string * string * string -&gt; unit" Usage="Microsoft.Azure.Management.Sql.SyncMembersOperationsExtensions.Delete (operations, resourceGroupName, serverName, databaseName, syncGroupName, syncMemberName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Sql.ISyncMembersOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="serverName" Type="System.String" />
        <Parameter Name="databaseName" Type="System.String" />
        <Parameter Name="syncGroupName" Type="System.String" />
        <Parameter Name="syncMemberName" Type="System.String" />
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
            Der Name der Synchronisierungsgruppe auf der das Sync-Element gehostet wird.
            </param>
        <param name="syncMemberName">
            Der Name des Sync-Elements.
            </param>
        <summary>
            Löscht ein Sync-Element.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task DeleteAsync (this Microsoft.Azure.Management.Sql.ISyncMembersOperations operations, string resourceGroupName, string serverName, string databaseName, string syncGroupName, string syncMemberName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task DeleteAsync(class Microsoft.Azure.Management.Sql.ISyncMembersOperations operations, string resourceGroupName, string serverName, string databaseName, string syncGroupName, string syncMemberName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.SyncMembersOperationsExtensions.DeleteAsync(Microsoft.Azure.Management.Sql.ISyncMembersOperations,System.String,System.String,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member DeleteAsync : Microsoft.Azure.Management.Sql.ISyncMembersOperations * string * string * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.Sql.SyncMembersOperationsExtensions.DeleteAsync (operations, resourceGroupName, serverName, databaseName, syncGroupName, syncMemberName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Sql.SyncMembersOperationsExtensions/&lt;DeleteAsync&gt;d__5))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Sql.ISyncMembersOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="serverName" Type="System.String" />
        <Parameter Name="databaseName" Type="System.String" />
        <Parameter Name="syncGroupName" Type="System.String" />
        <Parameter Name="syncMemberName" Type="System.String" />
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
            Der Name der Synchronisierungsgruppe auf der das Sync-Element gehostet wird.
            </param>
        <param name="syncMemberName">
            Der Name des Sync-Elements.
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Löscht ein Sync-Element.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Get">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Sql.Models.SyncMember Get (this Microsoft.Azure.Management.Sql.ISyncMembersOperations operations, string resourceGroupName, string serverName, string databaseName, string syncGroupName, string syncMemberName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Sql.Models.SyncMember Get(class Microsoft.Azure.Management.Sql.ISyncMembersOperations operations, string resourceGroupName, string serverName, string databaseName, string syncGroupName, string syncMemberName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.SyncMembersOperationsExtensions.Get(Microsoft.Azure.Management.Sql.ISyncMembersOperations,System.String,System.String,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function Get (operations As ISyncMembersOperations, resourceGroupName As String, serverName As String, databaseName As String, syncGroupName As String, syncMemberName As String) As SyncMember" />
      <MemberSignature Language="F#" Value="static member Get : Microsoft.Azure.Management.Sql.ISyncMembersOperations * string * string * string * string * string -&gt; Microsoft.Azure.Management.Sql.Models.SyncMember" Usage="Microsoft.Azure.Management.Sql.SyncMembersOperationsExtensions.Get (operations, resourceGroupName, serverName, databaseName, syncGroupName, syncMemberName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Sql.Models.SyncMember</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Sql.ISyncMembersOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="serverName" Type="System.String" />
        <Parameter Name="databaseName" Type="System.String" />
        <Parameter Name="syncGroupName" Type="System.String" />
        <Parameter Name="syncMemberName" Type="System.String" />
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
            Der Name der Synchronisierungsgruppe auf der das Sync-Element gehostet wird.
            </param>
        <param name="syncMemberName">
            Der Name des Sync-Elements.
            </param>
        <summary>
            Ruft ein Element für die Synchronisierung ab.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Sql.Models.SyncMember&gt; GetAsync (this Microsoft.Azure.Management.Sql.ISyncMembersOperations operations, string resourceGroupName, string serverName, string databaseName, string syncGroupName, string syncMemberName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Sql.Models.SyncMember&gt; GetAsync(class Microsoft.Azure.Management.Sql.ISyncMembersOperations operations, string resourceGroupName, string serverName, string databaseName, string syncGroupName, string syncMemberName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.SyncMembersOperationsExtensions.GetAsync(Microsoft.Azure.Management.Sql.ISyncMembersOperations,System.String,System.String,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetAsync : Microsoft.Azure.Management.Sql.ISyncMembersOperations * string * string * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Sql.Models.SyncMember&gt;" Usage="Microsoft.Azure.Management.Sql.SyncMembersOperationsExtensions.GetAsync (operations, resourceGroupName, serverName, databaseName, syncGroupName, syncMemberName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Sql.SyncMembersOperationsExtensions/&lt;GetAsync&gt;d__1))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Sql.Models.SyncMember&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Sql.ISyncMembersOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="serverName" Type="System.String" />
        <Parameter Name="databaseName" Type="System.String" />
        <Parameter Name="syncGroupName" Type="System.String" />
        <Parameter Name="syncMemberName" Type="System.String" />
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
            Der Name der Synchronisierungsgruppe auf der das Sync-Element gehostet wird.
            </param>
        <param name="syncMemberName">
            Der Name des Sync-Elements.
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Ruft ein Element für die Synchronisierung ab.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListBySyncGroup">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Sql.Models.SyncMember&gt; ListBySyncGroup (this Microsoft.Azure.Management.Sql.ISyncMembersOperations operations, string resourceGroupName, string serverName, string databaseName, string syncGroupName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Sql.Models.SyncMember&gt; ListBySyncGroup(class Microsoft.Azure.Management.Sql.ISyncMembersOperations operations, string resourceGroupName, string serverName, string databaseName, string syncGroupName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.SyncMembersOperationsExtensions.ListBySyncGroup(Microsoft.Azure.Management.Sql.ISyncMembersOperations,System.String,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListBySyncGroup (operations As ISyncMembersOperations, resourceGroupName As String, serverName As String, databaseName As String, syncGroupName As String) As IPage(Of SyncMember)" />
      <MemberSignature Language="F#" Value="static member ListBySyncGroup : Microsoft.Azure.Management.Sql.ISyncMembersOperations * string * string * string * string -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Sql.Models.SyncMember&gt;" Usage="Microsoft.Azure.Management.Sql.SyncMembersOperationsExtensions.ListBySyncGroup (operations, resourceGroupName, serverName, databaseName, syncGroupName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Sql.Models.SyncMember&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Sql.ISyncMembersOperations" RefType="this" />
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
            Listen Elemente in der angegebenen Synchronisierungsgruppe zu synchronisieren.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListBySyncGroupAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Sql.Models.SyncMember&gt;&gt; ListBySyncGroupAsync (this Microsoft.Azure.Management.Sql.ISyncMembersOperations operations, string resourceGroupName, string serverName, string databaseName, string syncGroupName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Sql.Models.SyncMember&gt;&gt; ListBySyncGroupAsync(class Microsoft.Azure.Management.Sql.ISyncMembersOperations operations, string resourceGroupName, string serverName, string databaseName, string syncGroupName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.SyncMembersOperationsExtensions.ListBySyncGroupAsync(Microsoft.Azure.Management.Sql.ISyncMembersOperations,System.String,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListBySyncGroupAsync : Microsoft.Azure.Management.Sql.ISyncMembersOperations * string * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Sql.Models.SyncMember&gt;&gt;" Usage="Microsoft.Azure.Management.Sql.SyncMembersOperationsExtensions.ListBySyncGroupAsync (operations, resourceGroupName, serverName, databaseName, syncGroupName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Sql.SyncMembersOperationsExtensions/&lt;ListBySyncGroupAsync&gt;d__9))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Sql.Models.SyncMember&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Sql.ISyncMembersOperations" RefType="this" />
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
            Listen Elemente in der angegebenen Synchronisierungsgruppe zu synchronisieren.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListBySyncGroupNext">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Sql.Models.SyncMember&gt; ListBySyncGroupNext (this Microsoft.Azure.Management.Sql.ISyncMembersOperations operations, string nextPageLink);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Sql.Models.SyncMember&gt; ListBySyncGroupNext(class Microsoft.Azure.Management.Sql.ISyncMembersOperations operations, string nextPageLink) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.SyncMembersOperationsExtensions.ListBySyncGroupNext(Microsoft.Azure.Management.Sql.ISyncMembersOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListBySyncGroupNext (operations As ISyncMembersOperations, nextPageLink As String) As IPage(Of SyncMember)" />
      <MemberSignature Language="F#" Value="static member ListBySyncGroupNext : Microsoft.Azure.Management.Sql.ISyncMembersOperations * string -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Sql.Models.SyncMember&gt;" Usage="Microsoft.Azure.Management.Sql.SyncMembersOperationsExtensions.ListBySyncGroupNext (operations, nextPageLink)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Sql.Models.SyncMember&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Sql.ISyncMembersOperations" RefType="this" />
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
            Listen Elemente in der angegebenen Synchronisierungsgruppe zu synchronisieren.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListBySyncGroupNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Sql.Models.SyncMember&gt;&gt; ListBySyncGroupNextAsync (this Microsoft.Azure.Management.Sql.ISyncMembersOperations operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Sql.Models.SyncMember&gt;&gt; ListBySyncGroupNextAsync(class Microsoft.Azure.Management.Sql.ISyncMembersOperations operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.SyncMembersOperationsExtensions.ListBySyncGroupNextAsync(Microsoft.Azure.Management.Sql.ISyncMembersOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListBySyncGroupNextAsync : Microsoft.Azure.Management.Sql.ISyncMembersOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Sql.Models.SyncMember&gt;&gt;" Usage="Microsoft.Azure.Management.Sql.SyncMembersOperationsExtensions.ListBySyncGroupNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Sql.SyncMembersOperationsExtensions/&lt;ListBySyncGroupNextAsync&gt;d__23))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Sql.Models.SyncMember&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Sql.ISyncMembersOperations" RefType="this" />
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
            Listen Elemente in der angegebenen Synchronisierungsgruppe zu synchronisieren.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListMemberSchemas">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Sql.Models.SyncFullSchemaProperties&gt; ListMemberSchemas (this Microsoft.Azure.Management.Sql.ISyncMembersOperations operations, string resourceGroupName, string serverName, string databaseName, string syncGroupName, string syncMemberName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Sql.Models.SyncFullSchemaProperties&gt; ListMemberSchemas(class Microsoft.Azure.Management.Sql.ISyncMembersOperations operations, string resourceGroupName, string serverName, string databaseName, string syncGroupName, string syncMemberName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.SyncMembersOperationsExtensions.ListMemberSchemas(Microsoft.Azure.Management.Sql.ISyncMembersOperations,System.String,System.String,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListMemberSchemas (operations As ISyncMembersOperations, resourceGroupName As String, serverName As String, databaseName As String, syncGroupName As String, syncMemberName As String) As IPage(Of SyncFullSchemaProperties)" />
      <MemberSignature Language="F#" Value="static member ListMemberSchemas : Microsoft.Azure.Management.Sql.ISyncMembersOperations * string * string * string * string * string -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Sql.Models.SyncFullSchemaProperties&gt;" Usage="Microsoft.Azure.Management.Sql.SyncMembersOperationsExtensions.ListMemberSchemas (operations, resourceGroupName, serverName, databaseName, syncGroupName, syncMemberName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Sql.Models.SyncFullSchemaProperties&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Sql.ISyncMembersOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="serverName" Type="System.String" />
        <Parameter Name="databaseName" Type="System.String" />
        <Parameter Name="syncGroupName" Type="System.String" />
        <Parameter Name="syncMemberName" Type="System.String" />
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
            Der Name der Synchronisierungsgruppe auf der das Sync-Element gehostet wird.
            </param>
        <param name="syncMemberName">
            Der Name des Sync-Elements.
            </param>
        <summary>
            Ruft ein Element Sync Datenbankschema ab.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListMemberSchemasAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Sql.Models.SyncFullSchemaProperties&gt;&gt; ListMemberSchemasAsync (this Microsoft.Azure.Management.Sql.ISyncMembersOperations operations, string resourceGroupName, string serverName, string databaseName, string syncGroupName, string syncMemberName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Sql.Models.SyncFullSchemaProperties&gt;&gt; ListMemberSchemasAsync(class Microsoft.Azure.Management.Sql.ISyncMembersOperations operations, string resourceGroupName, string serverName, string databaseName, string syncGroupName, string syncMemberName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.SyncMembersOperationsExtensions.ListMemberSchemasAsync(Microsoft.Azure.Management.Sql.ISyncMembersOperations,System.String,System.String,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListMemberSchemasAsync : Microsoft.Azure.Management.Sql.ISyncMembersOperations * string * string * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Sql.Models.SyncFullSchemaProperties&gt;&gt;" Usage="Microsoft.Azure.Management.Sql.SyncMembersOperationsExtensions.ListMemberSchemasAsync (operations, resourceGroupName, serverName, databaseName, syncGroupName, syncMemberName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Sql.SyncMembersOperationsExtensions/&lt;ListMemberSchemasAsync&gt;d__11))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Sql.Models.SyncFullSchemaProperties&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Sql.ISyncMembersOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="serverName" Type="System.String" />
        <Parameter Name="databaseName" Type="System.String" />
        <Parameter Name="syncGroupName" Type="System.String" />
        <Parameter Name="syncMemberName" Type="System.String" />
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
            Der Name der Synchronisierungsgruppe auf der das Sync-Element gehostet wird.
            </param>
        <param name="syncMemberName">
            Der Name des Sync-Elements.
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Ruft ein Element Sync Datenbankschema ab.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListMemberSchemasNext">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Sql.Models.SyncFullSchemaProperties&gt; ListMemberSchemasNext (this Microsoft.Azure.Management.Sql.ISyncMembersOperations operations, string nextPageLink);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Sql.Models.SyncFullSchemaProperties&gt; ListMemberSchemasNext(class Microsoft.Azure.Management.Sql.ISyncMembersOperations operations, string nextPageLink) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.SyncMembersOperationsExtensions.ListMemberSchemasNext(Microsoft.Azure.Management.Sql.ISyncMembersOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListMemberSchemasNext (operations As ISyncMembersOperations, nextPageLink As String) As IPage(Of SyncFullSchemaProperties)" />
      <MemberSignature Language="F#" Value="static member ListMemberSchemasNext : Microsoft.Azure.Management.Sql.ISyncMembersOperations * string -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Sql.Models.SyncFullSchemaProperties&gt;" Usage="Microsoft.Azure.Management.Sql.SyncMembersOperationsExtensions.ListMemberSchemasNext (operations, nextPageLink)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Sql.Models.SyncFullSchemaProperties&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Sql.ISyncMembersOperations" RefType="this" />
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
            Ruft ein Element Sync Datenbankschema ab.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListMemberSchemasNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Sql.Models.SyncFullSchemaProperties&gt;&gt; ListMemberSchemasNextAsync (this Microsoft.Azure.Management.Sql.ISyncMembersOperations operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Sql.Models.SyncFullSchemaProperties&gt;&gt; ListMemberSchemasNextAsync(class Microsoft.Azure.Management.Sql.ISyncMembersOperations operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.SyncMembersOperationsExtensions.ListMemberSchemasNextAsync(Microsoft.Azure.Management.Sql.ISyncMembersOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListMemberSchemasNextAsync : Microsoft.Azure.Management.Sql.ISyncMembersOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Sql.Models.SyncFullSchemaProperties&gt;&gt;" Usage="Microsoft.Azure.Management.Sql.SyncMembersOperationsExtensions.ListMemberSchemasNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Sql.SyncMembersOperationsExtensions/&lt;ListMemberSchemasNextAsync&gt;d__25))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Sql.Models.SyncFullSchemaProperties&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Sql.ISyncMembersOperations" RefType="this" />
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
            Ruft ein Element Sync Datenbankschema ab.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RefreshMemberSchema">
      <MemberSignature Language="C#" Value="public static void RefreshMemberSchema (this Microsoft.Azure.Management.Sql.ISyncMembersOperations operations, string resourceGroupName, string serverName, string databaseName, string syncGroupName, string syncMemberName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void RefreshMemberSchema(class Microsoft.Azure.Management.Sql.ISyncMembersOperations operations, string resourceGroupName, string serverName, string databaseName, string syncGroupName, string syncMemberName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.SyncMembersOperationsExtensions.RefreshMemberSchema(Microsoft.Azure.Management.Sql.ISyncMembersOperations,System.String,System.String,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Sub RefreshMemberSchema (operations As ISyncMembersOperations, resourceGroupName As String, serverName As String, databaseName As String, syncGroupName As String, syncMemberName As String)" />
      <MemberSignature Language="F#" Value="static member RefreshMemberSchema : Microsoft.Azure.Management.Sql.ISyncMembersOperations * string * string * string * string * string -&gt; unit" Usage="Microsoft.Azure.Management.Sql.SyncMembersOperationsExtensions.RefreshMemberSchema (operations, resourceGroupName, serverName, databaseName, syncGroupName, syncMemberName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Sql.ISyncMembersOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="serverName" Type="System.String" />
        <Parameter Name="databaseName" Type="System.String" />
        <Parameter Name="syncGroupName" Type="System.String" />
        <Parameter Name="syncMemberName" Type="System.String" />
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
            Der Name der Synchronisierungsgruppe auf der das Sync-Element gehostet wird.
            </param>
        <param name="syncMemberName">
            Der Name des Sync-Elements.
            </param>
        <summary>
            Aktualisiert ein Datenbankschema der Sync-Element.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RefreshMemberSchemaAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task RefreshMemberSchemaAsync (this Microsoft.Azure.Management.Sql.ISyncMembersOperations operations, string resourceGroupName, string serverName, string databaseName, string syncGroupName, string syncMemberName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task RefreshMemberSchemaAsync(class Microsoft.Azure.Management.Sql.ISyncMembersOperations operations, string resourceGroupName, string serverName, string databaseName, string syncGroupName, string syncMemberName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.SyncMembersOperationsExtensions.RefreshMemberSchemaAsync(Microsoft.Azure.Management.Sql.ISyncMembersOperations,System.String,System.String,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member RefreshMemberSchemaAsync : Microsoft.Azure.Management.Sql.ISyncMembersOperations * string * string * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.Sql.SyncMembersOperationsExtensions.RefreshMemberSchemaAsync (operations, resourceGroupName, serverName, databaseName, syncGroupName, syncMemberName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Sql.SyncMembersOperationsExtensions/&lt;RefreshMemberSchemaAsync&gt;d__13))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Sql.ISyncMembersOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="serverName" Type="System.String" />
        <Parameter Name="databaseName" Type="System.String" />
        <Parameter Name="syncGroupName" Type="System.String" />
        <Parameter Name="syncMemberName" Type="System.String" />
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
            Der Name der Synchronisierungsgruppe auf der das Sync-Element gehostet wird.
            </param>
        <param name="syncMemberName">
            Der Name des Sync-Elements.
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Aktualisiert ein Datenbankschema der Sync-Element.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Update">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Sql.Models.SyncMember Update (this Microsoft.Azure.Management.Sql.ISyncMembersOperations operations, string resourceGroupName, string serverName, string databaseName, string syncGroupName, string syncMemberName, Microsoft.Azure.Management.Sql.Models.SyncMember parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Sql.Models.SyncMember Update(class Microsoft.Azure.Management.Sql.ISyncMembersOperations operations, string resourceGroupName, string serverName, string databaseName, string syncGroupName, string syncMemberName, class Microsoft.Azure.Management.Sql.Models.SyncMember parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.SyncMembersOperationsExtensions.Update(Microsoft.Azure.Management.Sql.ISyncMembersOperations,System.String,System.String,System.String,System.String,System.String,Microsoft.Azure.Management.Sql.Models.SyncMember)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function Update (operations As ISyncMembersOperations, resourceGroupName As String, serverName As String, databaseName As String, syncGroupName As String, syncMemberName As String, parameters As SyncMember) As SyncMember" />
      <MemberSignature Language="F#" Value="static member Update : Microsoft.Azure.Management.Sql.ISyncMembersOperations * string * string * string * string * string * Microsoft.Azure.Management.Sql.Models.SyncMember -&gt; Microsoft.Azure.Management.Sql.Models.SyncMember" Usage="Microsoft.Azure.Management.Sql.SyncMembersOperationsExtensions.Update (operations, resourceGroupName, serverName, databaseName, syncGroupName, syncMemberName, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Sql.Models.SyncMember</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Sql.ISyncMembersOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="serverName" Type="System.String" />
        <Parameter Name="databaseName" Type="System.String" />
        <Parameter Name="syncGroupName" Type="System.String" />
        <Parameter Name="syncMemberName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Sql.Models.SyncMember" />
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
            Der Name der Synchronisierungsgruppe auf der das Sync-Element gehostet wird.
            </param>
        <param name="syncMemberName">
            Der Name des Sync-Elements.
            </param>
        <param name="parameters">
            Der angeforderte Sync Ressourcenstatus des Elements.
            </param>
        <summary>
            Aktualisiert ein vorhandenes Sync-Element.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UpdateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Sql.Models.SyncMember&gt; UpdateAsync (this Microsoft.Azure.Management.Sql.ISyncMembersOperations operations, string resourceGroupName, string serverName, string databaseName, string syncGroupName, string syncMemberName, Microsoft.Azure.Management.Sql.Models.SyncMember parameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Sql.Models.SyncMember&gt; UpdateAsync(class Microsoft.Azure.Management.Sql.ISyncMembersOperations operations, string resourceGroupName, string serverName, string databaseName, string syncGroupName, string syncMemberName, class Microsoft.Azure.Management.Sql.Models.SyncMember parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.SyncMembersOperationsExtensions.UpdateAsync(Microsoft.Azure.Management.Sql.ISyncMembersOperations,System.String,System.String,System.String,System.String,System.String,Microsoft.Azure.Management.Sql.Models.SyncMember,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member UpdateAsync : Microsoft.Azure.Management.Sql.ISyncMembersOperations * string * string * string * string * string * Microsoft.Azure.Management.Sql.Models.SyncMember * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Sql.Models.SyncMember&gt;" Usage="Microsoft.Azure.Management.Sql.SyncMembersOperationsExtensions.UpdateAsync (operations, resourceGroupName, serverName, databaseName, syncGroupName, syncMemberName, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Sql.SyncMembersOperationsExtensions/&lt;UpdateAsync&gt;d__7))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Sql.Models.SyncMember&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Sql.ISyncMembersOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="serverName" Type="System.String" />
        <Parameter Name="databaseName" Type="System.String" />
        <Parameter Name="syncGroupName" Type="System.String" />
        <Parameter Name="syncMemberName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Sql.Models.SyncMember" />
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
            Der Name der Synchronisierungsgruppe auf der das Sync-Element gehostet wird.
            </param>
        <param name="syncMemberName">
            Der Name des Sync-Elements.
            </param>
        <param name="parameters">
            Der angeforderte Sync Ressourcenstatus des Elements.
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Aktualisiert ein vorhandenes Sync-Element.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>