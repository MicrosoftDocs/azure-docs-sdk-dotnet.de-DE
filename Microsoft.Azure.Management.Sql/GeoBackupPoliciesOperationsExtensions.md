<Type Name="GeoBackupPoliciesOperationsExtensions" FullName="Microsoft.Azure.Management.Sql.GeoBackupPoliciesOperationsExtensions">
  <TypeSignature Language="C#" Value="public static class GeoBackupPoliciesOperationsExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit GeoBackupPoliciesOperationsExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Sql.GeoBackupPoliciesOperationsExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module GeoBackupPoliciesOperationsExtensions" />
  <TypeSignature Language="F#" Value="type GeoBackupPoliciesOperationsExtensions = class" />
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
            Erweiterungsmethoden für GeoBackupPoliciesOperations.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="CreateOrUpdate">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Sql.Models.GeoBackupPolicy CreateOrUpdate (this Microsoft.Azure.Management.Sql.IGeoBackupPoliciesOperations operations, string resourceGroupName, string serverName, string databaseName, Microsoft.Azure.Management.Sql.Models.GeoBackupPolicy parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Sql.Models.GeoBackupPolicy CreateOrUpdate(class Microsoft.Azure.Management.Sql.IGeoBackupPoliciesOperations operations, string resourceGroupName, string serverName, string databaseName, class Microsoft.Azure.Management.Sql.Models.GeoBackupPolicy parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.GeoBackupPoliciesOperationsExtensions.CreateOrUpdate(Microsoft.Azure.Management.Sql.IGeoBackupPoliciesOperations,System.String,System.String,System.String,Microsoft.Azure.Management.Sql.Models.GeoBackupPolicy)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function CreateOrUpdate (operations As IGeoBackupPoliciesOperations, resourceGroupName As String, serverName As String, databaseName As String, parameters As GeoBackupPolicy) As GeoBackupPolicy" />
      <MemberSignature Language="F#" Value="static member CreateOrUpdate : Microsoft.Azure.Management.Sql.IGeoBackupPoliciesOperations * string * string * string * Microsoft.Azure.Management.Sql.Models.GeoBackupPolicy -&gt; Microsoft.Azure.Management.Sql.Models.GeoBackupPolicy" Usage="Microsoft.Azure.Management.Sql.GeoBackupPoliciesOperationsExtensions.CreateOrUpdate (operations, resourceGroupName, serverName, databaseName, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Sql.Models.GeoBackupPolicy</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Sql.IGeoBackupPoliciesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="serverName" Type="System.String" />
        <Parameter Name="databaseName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Sql.Models.GeoBackupPolicy" />
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
        <param name="parameters">
            Die erforderlichen Parameter zum Erstellen oder aktualisieren die geografische Sicherungsrichtlinie.
            </param>
        <summary>
            Aktualisiert eine Sicherungsrichtlinie für die Datenbank geografisch.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateOrUpdateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Sql.Models.GeoBackupPolicy&gt; CreateOrUpdateAsync (this Microsoft.Azure.Management.Sql.IGeoBackupPoliciesOperations operations, string resourceGroupName, string serverName, string databaseName, Microsoft.Azure.Management.Sql.Models.GeoBackupPolicy parameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Sql.Models.GeoBackupPolicy&gt; CreateOrUpdateAsync(class Microsoft.Azure.Management.Sql.IGeoBackupPoliciesOperations operations, string resourceGroupName, string serverName, string databaseName, class Microsoft.Azure.Management.Sql.Models.GeoBackupPolicy parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.GeoBackupPoliciesOperationsExtensions.CreateOrUpdateAsync(Microsoft.Azure.Management.Sql.IGeoBackupPoliciesOperations,System.String,System.String,System.String,Microsoft.Azure.Management.Sql.Models.GeoBackupPolicy,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member CreateOrUpdateAsync : Microsoft.Azure.Management.Sql.IGeoBackupPoliciesOperations * string * string * string * Microsoft.Azure.Management.Sql.Models.GeoBackupPolicy * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Sql.Models.GeoBackupPolicy&gt;" Usage="Microsoft.Azure.Management.Sql.GeoBackupPoliciesOperationsExtensions.CreateOrUpdateAsync (operations, resourceGroupName, serverName, databaseName, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Sql.GeoBackupPoliciesOperationsExtensions/&lt;CreateOrUpdateAsync&gt;d__1))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Sql.Models.GeoBackupPolicy&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Sql.IGeoBackupPoliciesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="serverName" Type="System.String" />
        <Parameter Name="databaseName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Sql.Models.GeoBackupPolicy" />
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
        <param name="parameters">
            Die erforderlichen Parameter zum Erstellen oder aktualisieren die geografische Sicherungsrichtlinie.
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Aktualisiert eine Sicherungsrichtlinie für die Datenbank geografisch.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Get">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Sql.Models.GeoBackupPolicy Get (this Microsoft.Azure.Management.Sql.IGeoBackupPoliciesOperations operations, string resourceGroupName, string serverName, string databaseName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Sql.Models.GeoBackupPolicy Get(class Microsoft.Azure.Management.Sql.IGeoBackupPoliciesOperations operations, string resourceGroupName, string serverName, string databaseName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.GeoBackupPoliciesOperationsExtensions.Get(Microsoft.Azure.Management.Sql.IGeoBackupPoliciesOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function Get (operations As IGeoBackupPoliciesOperations, resourceGroupName As String, serverName As String, databaseName As String) As GeoBackupPolicy" />
      <MemberSignature Language="F#" Value="static member Get : Microsoft.Azure.Management.Sql.IGeoBackupPoliciesOperations * string * string * string -&gt; Microsoft.Azure.Management.Sql.Models.GeoBackupPolicy" Usage="Microsoft.Azure.Management.Sql.GeoBackupPoliciesOperationsExtensions.Get (operations, resourceGroupName, serverName, databaseName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Sql.Models.GeoBackupPolicy</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Sql.IGeoBackupPoliciesOperations" RefType="this" />
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
            Ruft eine geografische Sicherungsrichtlinie ab.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Sql.Models.GeoBackupPolicy&gt; GetAsync (this Microsoft.Azure.Management.Sql.IGeoBackupPoliciesOperations operations, string resourceGroupName, string serverName, string databaseName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Sql.Models.GeoBackupPolicy&gt; GetAsync(class Microsoft.Azure.Management.Sql.IGeoBackupPoliciesOperations operations, string resourceGroupName, string serverName, string databaseName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.GeoBackupPoliciesOperationsExtensions.GetAsync(Microsoft.Azure.Management.Sql.IGeoBackupPoliciesOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetAsync : Microsoft.Azure.Management.Sql.IGeoBackupPoliciesOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Sql.Models.GeoBackupPolicy&gt;" Usage="Microsoft.Azure.Management.Sql.GeoBackupPoliciesOperationsExtensions.GetAsync (operations, resourceGroupName, serverName, databaseName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Sql.GeoBackupPoliciesOperationsExtensions/&lt;GetAsync&gt;d__3))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Sql.Models.GeoBackupPolicy&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Sql.IGeoBackupPoliciesOperations" RefType="this" />
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
            Ruft eine geografische Sicherungsrichtlinie ab.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByDatabase">
      <MemberSignature Language="C#" Value="public static System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.Sql.Models.GeoBackupPolicy&gt; ListByDatabase (this Microsoft.Azure.Management.Sql.IGeoBackupPoliciesOperations operations, string resourceGroupName, string serverName, string databaseName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Management.Sql.Models.GeoBackupPolicy&gt; ListByDatabase(class Microsoft.Azure.Management.Sql.IGeoBackupPoliciesOperations operations, string resourceGroupName, string serverName, string databaseName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.GeoBackupPoliciesOperationsExtensions.ListByDatabase(Microsoft.Azure.Management.Sql.IGeoBackupPoliciesOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListByDatabase (operations As IGeoBackupPoliciesOperations, resourceGroupName As String, serverName As String, databaseName As String) As IEnumerable(Of GeoBackupPolicy)" />
      <MemberSignature Language="F#" Value="static member ListByDatabase : Microsoft.Azure.Management.Sql.IGeoBackupPoliciesOperations * string * string * string -&gt; seq&lt;Microsoft.Azure.Management.Sql.Models.GeoBackupPolicy&gt;" Usage="Microsoft.Azure.Management.Sql.GeoBackupPoliciesOperationsExtensions.ListByDatabase (operations, resourceGroupName, serverName, databaseName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.Sql.Models.GeoBackupPolicy&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Sql.IGeoBackupPoliciesOperations" RefType="this" />
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
            Gibt eine Liste der geografischen Sicherungsrichtlinien zurück.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByDatabaseAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.Sql.Models.GeoBackupPolicy&gt;&gt; ListByDatabaseAsync (this Microsoft.Azure.Management.Sql.IGeoBackupPoliciesOperations operations, string resourceGroupName, string serverName, string databaseName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Management.Sql.Models.GeoBackupPolicy&gt;&gt; ListByDatabaseAsync(class Microsoft.Azure.Management.Sql.IGeoBackupPoliciesOperations operations, string resourceGroupName, string serverName, string databaseName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.GeoBackupPoliciesOperationsExtensions.ListByDatabaseAsync(Microsoft.Azure.Management.Sql.IGeoBackupPoliciesOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListByDatabaseAsync : Microsoft.Azure.Management.Sql.IGeoBackupPoliciesOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;seq&lt;Microsoft.Azure.Management.Sql.Models.GeoBackupPolicy&gt;&gt;" Usage="Microsoft.Azure.Management.Sql.GeoBackupPoliciesOperationsExtensions.ListByDatabaseAsync (operations, resourceGroupName, serverName, databaseName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Sql.GeoBackupPoliciesOperationsExtensions/&lt;ListByDatabaseAsync&gt;d__5))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.Sql.Models.GeoBackupPolicy&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Sql.IGeoBackupPoliciesOperations" RefType="this" />
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
            Gibt eine Liste der geografischen Sicherungsrichtlinien zurück.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>