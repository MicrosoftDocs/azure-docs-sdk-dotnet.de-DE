<Type Name="BackupLongTermRetentionPoliciesOperationsExtensions" FullName="Microsoft.Azure.Management.Sql.BackupLongTermRetentionPoliciesOperationsExtensions">
  <TypeSignature Language="C#" Value="public static class BackupLongTermRetentionPoliciesOperationsExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit BackupLongTermRetentionPoliciesOperationsExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Sql.BackupLongTermRetentionPoliciesOperationsExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module BackupLongTermRetentionPoliciesOperationsExtensions" />
  <TypeSignature Language="F#" Value="type BackupLongTermRetentionPoliciesOperationsExtensions = class" />
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
            Erweiterungsmethoden für BackupLongTermRetentionPoliciesOperations.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="BeginCreateOrUpdate">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Sql.Models.BackupLongTermRetentionPolicy BeginCreateOrUpdate (this Microsoft.Azure.Management.Sql.IBackupLongTermRetentionPoliciesOperations operations, string resourceGroupName, string serverName, string databaseName, Microsoft.Azure.Management.Sql.Models.BackupLongTermRetentionPolicy parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Sql.Models.BackupLongTermRetentionPolicy BeginCreateOrUpdate(class Microsoft.Azure.Management.Sql.IBackupLongTermRetentionPoliciesOperations operations, string resourceGroupName, string serverName, string databaseName, class Microsoft.Azure.Management.Sql.Models.BackupLongTermRetentionPolicy parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.BackupLongTermRetentionPoliciesOperationsExtensions.BeginCreateOrUpdate(Microsoft.Azure.Management.Sql.IBackupLongTermRetentionPoliciesOperations,System.String,System.String,System.String,Microsoft.Azure.Management.Sql.Models.BackupLongTermRetentionPolicy)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function BeginCreateOrUpdate (operations As IBackupLongTermRetentionPoliciesOperations, resourceGroupName As String, serverName As String, databaseName As String, parameters As BackupLongTermRetentionPolicy) As BackupLongTermRetentionPolicy" />
      <MemberSignature Language="F#" Value="static member BeginCreateOrUpdate : Microsoft.Azure.Management.Sql.IBackupLongTermRetentionPoliciesOperations * string * string * string * Microsoft.Azure.Management.Sql.Models.BackupLongTermRetentionPolicy -&gt; Microsoft.Azure.Management.Sql.Models.BackupLongTermRetentionPolicy" Usage="Microsoft.Azure.Management.Sql.BackupLongTermRetentionPoliciesOperationsExtensions.BeginCreateOrUpdate (operations, resourceGroupName, serverName, databaseName, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Sql.Models.BackupLongTermRetentionPolicy</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Sql.IBackupLongTermRetentionPoliciesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="serverName" Type="System.String" />
        <Parameter Name="databaseName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Sql.Models.BackupLongTermRetentionPolicy" />
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
            der Name der Datenbank
            </param>
        <param name="parameters">
            Die erforderlichen Parameter, um eine Aufbewahrungsrichtlinie für Sicherungen langfristig zu aktualisieren.
            </param>
        <summary>
            Erstellt oder aktualisiert eine langfristige Sicherung Aufbewahrungsrichtlinie für die Datenbank
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginCreateOrUpdateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Sql.Models.BackupLongTermRetentionPolicy&gt; BeginCreateOrUpdateAsync (this Microsoft.Azure.Management.Sql.IBackupLongTermRetentionPoliciesOperations operations, string resourceGroupName, string serverName, string databaseName, Microsoft.Azure.Management.Sql.Models.BackupLongTermRetentionPolicy parameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Sql.Models.BackupLongTermRetentionPolicy&gt; BeginCreateOrUpdateAsync(class Microsoft.Azure.Management.Sql.IBackupLongTermRetentionPoliciesOperations operations, string resourceGroupName, string serverName, string databaseName, class Microsoft.Azure.Management.Sql.Models.BackupLongTermRetentionPolicy parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.BackupLongTermRetentionPoliciesOperationsExtensions.BeginCreateOrUpdateAsync(Microsoft.Azure.Management.Sql.IBackupLongTermRetentionPoliciesOperations,System.String,System.String,System.String,Microsoft.Azure.Management.Sql.Models.BackupLongTermRetentionPolicy,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginCreateOrUpdateAsync : Microsoft.Azure.Management.Sql.IBackupLongTermRetentionPoliciesOperations * string * string * string * Microsoft.Azure.Management.Sql.Models.BackupLongTermRetentionPolicy * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Sql.Models.BackupLongTermRetentionPolicy&gt;" Usage="Microsoft.Azure.Management.Sql.BackupLongTermRetentionPoliciesOperationsExtensions.BeginCreateOrUpdateAsync (operations, resourceGroupName, serverName, databaseName, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Sql.BackupLongTermRetentionPoliciesOperationsExtensions/&lt;BeginCreateOrUpdateAsync&gt;d__5))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Sql.Models.BackupLongTermRetentionPolicy&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Sql.IBackupLongTermRetentionPoliciesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="serverName" Type="System.String" />
        <Parameter Name="databaseName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Sql.Models.BackupLongTermRetentionPolicy" />
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
            der Name der Datenbank
            </param>
        <param name="parameters">
            Die erforderlichen Parameter, um eine Aufbewahrungsrichtlinie für Sicherungen langfristig zu aktualisieren.
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Erstellt oder aktualisiert eine langfristige Sicherung Aufbewahrungsrichtlinie für die Datenbank
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateOrUpdate">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Sql.Models.BackupLongTermRetentionPolicy CreateOrUpdate (this Microsoft.Azure.Management.Sql.IBackupLongTermRetentionPoliciesOperations operations, string resourceGroupName, string serverName, string databaseName, Microsoft.Azure.Management.Sql.Models.BackupLongTermRetentionPolicy parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Sql.Models.BackupLongTermRetentionPolicy CreateOrUpdate(class Microsoft.Azure.Management.Sql.IBackupLongTermRetentionPoliciesOperations operations, string resourceGroupName, string serverName, string databaseName, class Microsoft.Azure.Management.Sql.Models.BackupLongTermRetentionPolicy parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.BackupLongTermRetentionPoliciesOperationsExtensions.CreateOrUpdate(Microsoft.Azure.Management.Sql.IBackupLongTermRetentionPoliciesOperations,System.String,System.String,System.String,Microsoft.Azure.Management.Sql.Models.BackupLongTermRetentionPolicy)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function CreateOrUpdate (operations As IBackupLongTermRetentionPoliciesOperations, resourceGroupName As String, serverName As String, databaseName As String, parameters As BackupLongTermRetentionPolicy) As BackupLongTermRetentionPolicy" />
      <MemberSignature Language="F#" Value="static member CreateOrUpdate : Microsoft.Azure.Management.Sql.IBackupLongTermRetentionPoliciesOperations * string * string * string * Microsoft.Azure.Management.Sql.Models.BackupLongTermRetentionPolicy -&gt; Microsoft.Azure.Management.Sql.Models.BackupLongTermRetentionPolicy" Usage="Microsoft.Azure.Management.Sql.BackupLongTermRetentionPoliciesOperationsExtensions.CreateOrUpdate (operations, resourceGroupName, serverName, databaseName, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Sql.Models.BackupLongTermRetentionPolicy</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Sql.IBackupLongTermRetentionPoliciesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="serverName" Type="System.String" />
        <Parameter Name="databaseName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Sql.Models.BackupLongTermRetentionPolicy" />
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
            der Name der Datenbank
            </param>
        <param name="parameters">
            Die erforderlichen Parameter, um eine Aufbewahrungsrichtlinie für Sicherungen langfristig zu aktualisieren.
            </param>
        <summary>
            Erstellt oder aktualisiert eine langfristige Sicherung Aufbewahrungsrichtlinie für die Datenbank
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateOrUpdateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Sql.Models.BackupLongTermRetentionPolicy&gt; CreateOrUpdateAsync (this Microsoft.Azure.Management.Sql.IBackupLongTermRetentionPoliciesOperations operations, string resourceGroupName, string serverName, string databaseName, Microsoft.Azure.Management.Sql.Models.BackupLongTermRetentionPolicy parameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Sql.Models.BackupLongTermRetentionPolicy&gt; CreateOrUpdateAsync(class Microsoft.Azure.Management.Sql.IBackupLongTermRetentionPoliciesOperations operations, string resourceGroupName, string serverName, string databaseName, class Microsoft.Azure.Management.Sql.Models.BackupLongTermRetentionPolicy parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.BackupLongTermRetentionPoliciesOperationsExtensions.CreateOrUpdateAsync(Microsoft.Azure.Management.Sql.IBackupLongTermRetentionPoliciesOperations,System.String,System.String,System.String,Microsoft.Azure.Management.Sql.Models.BackupLongTermRetentionPolicy,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member CreateOrUpdateAsync : Microsoft.Azure.Management.Sql.IBackupLongTermRetentionPoliciesOperations * string * string * string * Microsoft.Azure.Management.Sql.Models.BackupLongTermRetentionPolicy * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Sql.Models.BackupLongTermRetentionPolicy&gt;" Usage="Microsoft.Azure.Management.Sql.BackupLongTermRetentionPoliciesOperationsExtensions.CreateOrUpdateAsync (operations, resourceGroupName, serverName, databaseName, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Sql.BackupLongTermRetentionPoliciesOperationsExtensions/&lt;CreateOrUpdateAsync&gt;d__3))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Sql.Models.BackupLongTermRetentionPolicy&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Sql.IBackupLongTermRetentionPoliciesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="serverName" Type="System.String" />
        <Parameter Name="databaseName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Sql.Models.BackupLongTermRetentionPolicy" />
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
            der Name der Datenbank
            </param>
        <param name="parameters">
            Die erforderlichen Parameter, um eine Aufbewahrungsrichtlinie für Sicherungen langfristig zu aktualisieren.
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Erstellt oder aktualisiert eine langfristige Sicherung Aufbewahrungsrichtlinie für die Datenbank
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Get">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Sql.Models.BackupLongTermRetentionPolicy Get (this Microsoft.Azure.Management.Sql.IBackupLongTermRetentionPoliciesOperations operations, string resourceGroupName, string serverName, string databaseName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Sql.Models.BackupLongTermRetentionPolicy Get(class Microsoft.Azure.Management.Sql.IBackupLongTermRetentionPoliciesOperations operations, string resourceGroupName, string serverName, string databaseName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.BackupLongTermRetentionPoliciesOperationsExtensions.Get(Microsoft.Azure.Management.Sql.IBackupLongTermRetentionPoliciesOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function Get (operations As IBackupLongTermRetentionPoliciesOperations, resourceGroupName As String, serverName As String, databaseName As String) As BackupLongTermRetentionPolicy" />
      <MemberSignature Language="F#" Value="static member Get : Microsoft.Azure.Management.Sql.IBackupLongTermRetentionPoliciesOperations * string * string * string -&gt; Microsoft.Azure.Management.Sql.Models.BackupLongTermRetentionPolicy" Usage="Microsoft.Azure.Management.Sql.BackupLongTermRetentionPoliciesOperationsExtensions.Get (operations, resourceGroupName, serverName, databaseName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Sql.Models.BackupLongTermRetentionPolicy</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Sql.IBackupLongTermRetentionPoliciesOperations" RefType="this" />
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
            Gibt eine langfristige Sicherung Aufbewahrungsrichtlinie für die Datenbank
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Sql.Models.BackupLongTermRetentionPolicy&gt; GetAsync (this Microsoft.Azure.Management.Sql.IBackupLongTermRetentionPoliciesOperations operations, string resourceGroupName, string serverName, string databaseName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Sql.Models.BackupLongTermRetentionPolicy&gt; GetAsync(class Microsoft.Azure.Management.Sql.IBackupLongTermRetentionPoliciesOperations operations, string resourceGroupName, string serverName, string databaseName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.BackupLongTermRetentionPoliciesOperationsExtensions.GetAsync(Microsoft.Azure.Management.Sql.IBackupLongTermRetentionPoliciesOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetAsync : Microsoft.Azure.Management.Sql.IBackupLongTermRetentionPoliciesOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Sql.Models.BackupLongTermRetentionPolicy&gt;" Usage="Microsoft.Azure.Management.Sql.BackupLongTermRetentionPoliciesOperationsExtensions.GetAsync (operations, resourceGroupName, serverName, databaseName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Sql.BackupLongTermRetentionPoliciesOperationsExtensions/&lt;GetAsync&gt;d__1))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Sql.Models.BackupLongTermRetentionPolicy&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Sql.IBackupLongTermRetentionPoliciesOperations" RefType="this" />
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
            Gibt eine langfristige Sicherung Aufbewahrungsrichtlinie für die Datenbank
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>