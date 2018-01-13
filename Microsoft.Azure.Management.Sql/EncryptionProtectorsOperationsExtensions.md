<Type Name="EncryptionProtectorsOperationsExtensions" FullName="Microsoft.Azure.Management.Sql.EncryptionProtectorsOperationsExtensions">
  <TypeSignature Language="C#" Value="public static class EncryptionProtectorsOperationsExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit EncryptionProtectorsOperationsExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Sql.EncryptionProtectorsOperationsExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module EncryptionProtectorsOperationsExtensions" />
  <TypeSignature Language="F#" Value="type EncryptionProtectorsOperationsExtensions = class" />
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
            Erweiterungsmethoden für EncryptionProtectorsOperations.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="BeginCreateOrUpdate">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Sql.Models.EncryptionProtector BeginCreateOrUpdate (this Microsoft.Azure.Management.Sql.IEncryptionProtectorsOperations operations, string resourceGroupName, string serverName, Microsoft.Azure.Management.Sql.Models.EncryptionProtector parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Sql.Models.EncryptionProtector BeginCreateOrUpdate(class Microsoft.Azure.Management.Sql.IEncryptionProtectorsOperations operations, string resourceGroupName, string serverName, class Microsoft.Azure.Management.Sql.Models.EncryptionProtector parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.EncryptionProtectorsOperationsExtensions.BeginCreateOrUpdate(Microsoft.Azure.Management.Sql.IEncryptionProtectorsOperations,System.String,System.String,Microsoft.Azure.Management.Sql.Models.EncryptionProtector)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function BeginCreateOrUpdate (operations As IEncryptionProtectorsOperations, resourceGroupName As String, serverName As String, parameters As EncryptionProtector) As EncryptionProtector" />
      <MemberSignature Language="F#" Value="static member BeginCreateOrUpdate : Microsoft.Azure.Management.Sql.IEncryptionProtectorsOperations * string * string * Microsoft.Azure.Management.Sql.Models.EncryptionProtector -&gt; Microsoft.Azure.Management.Sql.Models.EncryptionProtector" Usage="Microsoft.Azure.Management.Sql.EncryptionProtectorsOperationsExtensions.BeginCreateOrUpdate (operations, resourceGroupName, serverName, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Sql.Models.EncryptionProtector</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Sql.IEncryptionProtectorsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="serverName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Sql.Models.EncryptionProtector" />
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
        <param name="parameters">
            Der angeforderte Schutzvorrichtung Ressource Verschlüsselungsstatus.
            </param>
        <summary>
            Aktualisiert eine vorhandene Verschlüsselung Schutzvorrichtung.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginCreateOrUpdateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Sql.Models.EncryptionProtector&gt; BeginCreateOrUpdateAsync (this Microsoft.Azure.Management.Sql.IEncryptionProtectorsOperations operations, string resourceGroupName, string serverName, Microsoft.Azure.Management.Sql.Models.EncryptionProtector parameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Sql.Models.EncryptionProtector&gt; BeginCreateOrUpdateAsync(class Microsoft.Azure.Management.Sql.IEncryptionProtectorsOperations operations, string resourceGroupName, string serverName, class Microsoft.Azure.Management.Sql.Models.EncryptionProtector parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.EncryptionProtectorsOperationsExtensions.BeginCreateOrUpdateAsync(Microsoft.Azure.Management.Sql.IEncryptionProtectorsOperations,System.String,System.String,Microsoft.Azure.Management.Sql.Models.EncryptionProtector,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginCreateOrUpdateAsync : Microsoft.Azure.Management.Sql.IEncryptionProtectorsOperations * string * string * Microsoft.Azure.Management.Sql.Models.EncryptionProtector * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Sql.Models.EncryptionProtector&gt;" Usage="Microsoft.Azure.Management.Sql.EncryptionProtectorsOperationsExtensions.BeginCreateOrUpdateAsync (operations, resourceGroupName, serverName, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Sql.EncryptionProtectorsOperationsExtensions/&lt;BeginCreateOrUpdateAsync&gt;d__7))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Sql.Models.EncryptionProtector&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Sql.IEncryptionProtectorsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="serverName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Sql.Models.EncryptionProtector" />
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
        <param name="parameters">
            Der angeforderte Schutzvorrichtung Ressource Verschlüsselungsstatus.
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Aktualisiert eine vorhandene Verschlüsselung Schutzvorrichtung.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateOrUpdate">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Sql.Models.EncryptionProtector CreateOrUpdate (this Microsoft.Azure.Management.Sql.IEncryptionProtectorsOperations operations, string resourceGroupName, string serverName, Microsoft.Azure.Management.Sql.Models.EncryptionProtector parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Sql.Models.EncryptionProtector CreateOrUpdate(class Microsoft.Azure.Management.Sql.IEncryptionProtectorsOperations operations, string resourceGroupName, string serverName, class Microsoft.Azure.Management.Sql.Models.EncryptionProtector parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.EncryptionProtectorsOperationsExtensions.CreateOrUpdate(Microsoft.Azure.Management.Sql.IEncryptionProtectorsOperations,System.String,System.String,Microsoft.Azure.Management.Sql.Models.EncryptionProtector)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function CreateOrUpdate (operations As IEncryptionProtectorsOperations, resourceGroupName As String, serverName As String, parameters As EncryptionProtector) As EncryptionProtector" />
      <MemberSignature Language="F#" Value="static member CreateOrUpdate : Microsoft.Azure.Management.Sql.IEncryptionProtectorsOperations * string * string * Microsoft.Azure.Management.Sql.Models.EncryptionProtector -&gt; Microsoft.Azure.Management.Sql.Models.EncryptionProtector" Usage="Microsoft.Azure.Management.Sql.EncryptionProtectorsOperationsExtensions.CreateOrUpdate (operations, resourceGroupName, serverName, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Sql.Models.EncryptionProtector</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Sql.IEncryptionProtectorsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="serverName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Sql.Models.EncryptionProtector" />
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
        <param name="parameters">
            Der angeforderte Schutzvorrichtung Ressource Verschlüsselungsstatus.
            </param>
        <summary>
            Aktualisiert eine vorhandene Verschlüsselung Schutzvorrichtung.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateOrUpdateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Sql.Models.EncryptionProtector&gt; CreateOrUpdateAsync (this Microsoft.Azure.Management.Sql.IEncryptionProtectorsOperations operations, string resourceGroupName, string serverName, Microsoft.Azure.Management.Sql.Models.EncryptionProtector parameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Sql.Models.EncryptionProtector&gt; CreateOrUpdateAsync(class Microsoft.Azure.Management.Sql.IEncryptionProtectorsOperations operations, string resourceGroupName, string serverName, class Microsoft.Azure.Management.Sql.Models.EncryptionProtector parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.EncryptionProtectorsOperationsExtensions.CreateOrUpdateAsync(Microsoft.Azure.Management.Sql.IEncryptionProtectorsOperations,System.String,System.String,Microsoft.Azure.Management.Sql.Models.EncryptionProtector,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member CreateOrUpdateAsync : Microsoft.Azure.Management.Sql.IEncryptionProtectorsOperations * string * string * Microsoft.Azure.Management.Sql.Models.EncryptionProtector * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Sql.Models.EncryptionProtector&gt;" Usage="Microsoft.Azure.Management.Sql.EncryptionProtectorsOperationsExtensions.CreateOrUpdateAsync (operations, resourceGroupName, serverName, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Sql.EncryptionProtectorsOperationsExtensions/&lt;CreateOrUpdateAsync&gt;d__5))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Sql.Models.EncryptionProtector&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Sql.IEncryptionProtectorsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="serverName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Sql.Models.EncryptionProtector" />
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
        <param name="parameters">
            Der angeforderte Schutzvorrichtung Ressource Verschlüsselungsstatus.
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Aktualisiert eine vorhandene Verschlüsselung Schutzvorrichtung.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Get">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Sql.Models.EncryptionProtector Get (this Microsoft.Azure.Management.Sql.IEncryptionProtectorsOperations operations, string resourceGroupName, string serverName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Sql.Models.EncryptionProtector Get(class Microsoft.Azure.Management.Sql.IEncryptionProtectorsOperations operations, string resourceGroupName, string serverName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.EncryptionProtectorsOperationsExtensions.Get(Microsoft.Azure.Management.Sql.IEncryptionProtectorsOperations,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function Get (operations As IEncryptionProtectorsOperations, resourceGroupName As String, serverName As String) As EncryptionProtector" />
      <MemberSignature Language="F#" Value="static member Get : Microsoft.Azure.Management.Sql.IEncryptionProtectorsOperations * string * string -&gt; Microsoft.Azure.Management.Sql.Models.EncryptionProtector" Usage="Microsoft.Azure.Management.Sql.EncryptionProtectorsOperationsExtensions.Get (operations, resourceGroupName, serverName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Sql.Models.EncryptionProtector</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Sql.IEncryptionProtectorsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="serverName" Type="System.String" />
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
        <summary>
            Ruft eine Verschlüsselung Schutzvorrichtung ab.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Sql.Models.EncryptionProtector&gt; GetAsync (this Microsoft.Azure.Management.Sql.IEncryptionProtectorsOperations operations, string resourceGroupName, string serverName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Sql.Models.EncryptionProtector&gt; GetAsync(class Microsoft.Azure.Management.Sql.IEncryptionProtectorsOperations operations, string resourceGroupName, string serverName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.EncryptionProtectorsOperationsExtensions.GetAsync(Microsoft.Azure.Management.Sql.IEncryptionProtectorsOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetAsync : Microsoft.Azure.Management.Sql.IEncryptionProtectorsOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Sql.Models.EncryptionProtector&gt;" Usage="Microsoft.Azure.Management.Sql.EncryptionProtectorsOperationsExtensions.GetAsync (operations, resourceGroupName, serverName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Sql.EncryptionProtectorsOperationsExtensions/&lt;GetAsync&gt;d__3))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Sql.Models.EncryptionProtector&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Sql.IEncryptionProtectorsOperations" RefType="this" />
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
            Der Name des Servers.
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Ruft eine Verschlüsselung Schutzvorrichtung ab.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByServer">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Sql.Models.EncryptionProtector&gt; ListByServer (this Microsoft.Azure.Management.Sql.IEncryptionProtectorsOperations operations, string resourceGroupName, string serverName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Sql.Models.EncryptionProtector&gt; ListByServer(class Microsoft.Azure.Management.Sql.IEncryptionProtectorsOperations operations, string resourceGroupName, string serverName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.EncryptionProtectorsOperationsExtensions.ListByServer(Microsoft.Azure.Management.Sql.IEncryptionProtectorsOperations,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListByServer (operations As IEncryptionProtectorsOperations, resourceGroupName As String, serverName As String) As IPage(Of EncryptionProtector)" />
      <MemberSignature Language="F#" Value="static member ListByServer : Microsoft.Azure.Management.Sql.IEncryptionProtectorsOperations * string * string -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Sql.Models.EncryptionProtector&gt;" Usage="Microsoft.Azure.Management.Sql.EncryptionProtectorsOperationsExtensions.ListByServer (operations, resourceGroupName, serverName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Sql.Models.EncryptionProtector&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Sql.IEncryptionProtectorsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="serverName" Type="System.String" />
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
        <summary>
            Ruft eine Liste der Server-Verschlüsselung Schutzvorrichtungen
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByServerAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Sql.Models.EncryptionProtector&gt;&gt; ListByServerAsync (this Microsoft.Azure.Management.Sql.IEncryptionProtectorsOperations operations, string resourceGroupName, string serverName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Sql.Models.EncryptionProtector&gt;&gt; ListByServerAsync(class Microsoft.Azure.Management.Sql.IEncryptionProtectorsOperations operations, string resourceGroupName, string serverName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.EncryptionProtectorsOperationsExtensions.ListByServerAsync(Microsoft.Azure.Management.Sql.IEncryptionProtectorsOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListByServerAsync : Microsoft.Azure.Management.Sql.IEncryptionProtectorsOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Sql.Models.EncryptionProtector&gt;&gt;" Usage="Microsoft.Azure.Management.Sql.EncryptionProtectorsOperationsExtensions.ListByServerAsync (operations, resourceGroupName, serverName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Sql.EncryptionProtectorsOperationsExtensions/&lt;ListByServerAsync&gt;d__1))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Sql.Models.EncryptionProtector&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Sql.IEncryptionProtectorsOperations" RefType="this" />
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
            Der Name des Servers.
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Ruft eine Liste der Server-Verschlüsselung Schutzvorrichtungen
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByServerNext">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Sql.Models.EncryptionProtector&gt; ListByServerNext (this Microsoft.Azure.Management.Sql.IEncryptionProtectorsOperations operations, string nextPageLink);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Sql.Models.EncryptionProtector&gt; ListByServerNext(class Microsoft.Azure.Management.Sql.IEncryptionProtectorsOperations operations, string nextPageLink) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.EncryptionProtectorsOperationsExtensions.ListByServerNext(Microsoft.Azure.Management.Sql.IEncryptionProtectorsOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListByServerNext (operations As IEncryptionProtectorsOperations, nextPageLink As String) As IPage(Of EncryptionProtector)" />
      <MemberSignature Language="F#" Value="static member ListByServerNext : Microsoft.Azure.Management.Sql.IEncryptionProtectorsOperations * string -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Sql.Models.EncryptionProtector&gt;" Usage="Microsoft.Azure.Management.Sql.EncryptionProtectorsOperationsExtensions.ListByServerNext (operations, nextPageLink)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Sql.Models.EncryptionProtector&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Sql.IEncryptionProtectorsOperations" RefType="this" />
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
            Ruft eine Liste der Server-Verschlüsselung Schutzvorrichtungen
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByServerNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Sql.Models.EncryptionProtector&gt;&gt; ListByServerNextAsync (this Microsoft.Azure.Management.Sql.IEncryptionProtectorsOperations operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Sql.Models.EncryptionProtector&gt;&gt; ListByServerNextAsync(class Microsoft.Azure.Management.Sql.IEncryptionProtectorsOperations operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.EncryptionProtectorsOperationsExtensions.ListByServerNextAsync(Microsoft.Azure.Management.Sql.IEncryptionProtectorsOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListByServerNextAsync : Microsoft.Azure.Management.Sql.IEncryptionProtectorsOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Sql.Models.EncryptionProtector&gt;&gt;" Usage="Microsoft.Azure.Management.Sql.EncryptionProtectorsOperationsExtensions.ListByServerNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Sql.EncryptionProtectorsOperationsExtensions/&lt;ListByServerNextAsync&gt;d__9))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Sql.Models.EncryptionProtector&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Sql.IEncryptionProtectorsOperations" RefType="this" />
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
            Ruft eine Liste der Server-Verschlüsselung Schutzvorrichtungen
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>