<Type Name="ServerConnectionPoliciesOperationsExtensions" FullName="Microsoft.Azure.Management.Sql.ServerConnectionPoliciesOperationsExtensions">
  <TypeSignature Language="C#" Value="public static class ServerConnectionPoliciesOperationsExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit ServerConnectionPoliciesOperationsExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Sql.ServerConnectionPoliciesOperationsExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module ServerConnectionPoliciesOperationsExtensions" />
  <TypeSignature Language="F#" Value="type ServerConnectionPoliciesOperationsExtensions = class" />
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
            Erweiterungsmethoden für ServerConnectionPoliciesOperations.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="CreateOrUpdate">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Sql.Models.ServerConnectionPolicy CreateOrUpdate (this Microsoft.Azure.Management.Sql.IServerConnectionPoliciesOperations operations, string resourceGroupName, string serverName, Microsoft.Azure.Management.Sql.Models.ServerConnectionPolicy parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Sql.Models.ServerConnectionPolicy CreateOrUpdate(class Microsoft.Azure.Management.Sql.IServerConnectionPoliciesOperations operations, string resourceGroupName, string serverName, class Microsoft.Azure.Management.Sql.Models.ServerConnectionPolicy parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.ServerConnectionPoliciesOperationsExtensions.CreateOrUpdate(Microsoft.Azure.Management.Sql.IServerConnectionPoliciesOperations,System.String,System.String,Microsoft.Azure.Management.Sql.Models.ServerConnectionPolicy)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function CreateOrUpdate (operations As IServerConnectionPoliciesOperations, resourceGroupName As String, serverName As String, parameters As ServerConnectionPolicy) As ServerConnectionPolicy" />
      <MemberSignature Language="F#" Value="static member CreateOrUpdate : Microsoft.Azure.Management.Sql.IServerConnectionPoliciesOperations * string * string * Microsoft.Azure.Management.Sql.Models.ServerConnectionPolicy -&gt; Microsoft.Azure.Management.Sql.Models.ServerConnectionPolicy" Usage="Microsoft.Azure.Management.Sql.ServerConnectionPoliciesOperationsExtensions.CreateOrUpdate (operations, resourceGroupName, serverName, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Sql.Models.ServerConnectionPolicy</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Sql.IServerConnectionPoliciesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="serverName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Sql.Models.ServerConnectionPolicy" />
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
            Die erforderlichen Parameter für eine sichere Verbindungsrichtlinie aktualisieren.
            </param>
        <summary>
            Erstellt oder aktualisiert die Serverrichtlinie Verbindung.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateOrUpdateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Sql.Models.ServerConnectionPolicy&gt; CreateOrUpdateAsync (this Microsoft.Azure.Management.Sql.IServerConnectionPoliciesOperations operations, string resourceGroupName, string serverName, Microsoft.Azure.Management.Sql.Models.ServerConnectionPolicy parameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Sql.Models.ServerConnectionPolicy&gt; CreateOrUpdateAsync(class Microsoft.Azure.Management.Sql.IServerConnectionPoliciesOperations operations, string resourceGroupName, string serverName, class Microsoft.Azure.Management.Sql.Models.ServerConnectionPolicy parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.ServerConnectionPoliciesOperationsExtensions.CreateOrUpdateAsync(Microsoft.Azure.Management.Sql.IServerConnectionPoliciesOperations,System.String,System.String,Microsoft.Azure.Management.Sql.Models.ServerConnectionPolicy,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member CreateOrUpdateAsync : Microsoft.Azure.Management.Sql.IServerConnectionPoliciesOperations * string * string * Microsoft.Azure.Management.Sql.Models.ServerConnectionPolicy * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Sql.Models.ServerConnectionPolicy&gt;" Usage="Microsoft.Azure.Management.Sql.ServerConnectionPoliciesOperationsExtensions.CreateOrUpdateAsync (operations, resourceGroupName, serverName, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Sql.ServerConnectionPoliciesOperationsExtensions/&lt;CreateOrUpdateAsync&gt;d__1))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Sql.Models.ServerConnectionPolicy&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Sql.IServerConnectionPoliciesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="serverName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Sql.Models.ServerConnectionPolicy" />
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
            Die erforderlichen Parameter für eine sichere Verbindungsrichtlinie aktualisieren.
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Erstellt oder aktualisiert die Serverrichtlinie Verbindung.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Get">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Sql.Models.ServerConnectionPolicy Get (this Microsoft.Azure.Management.Sql.IServerConnectionPoliciesOperations operations, string resourceGroupName, string serverName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Sql.Models.ServerConnectionPolicy Get(class Microsoft.Azure.Management.Sql.IServerConnectionPoliciesOperations operations, string resourceGroupName, string serverName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.ServerConnectionPoliciesOperationsExtensions.Get(Microsoft.Azure.Management.Sql.IServerConnectionPoliciesOperations,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function Get (operations As IServerConnectionPoliciesOperations, resourceGroupName As String, serverName As String) As ServerConnectionPolicy" />
      <MemberSignature Language="F#" Value="static member Get : Microsoft.Azure.Management.Sql.IServerConnectionPoliciesOperations * string * string -&gt; Microsoft.Azure.Management.Sql.Models.ServerConnectionPolicy" Usage="Microsoft.Azure.Management.Sql.ServerConnectionPoliciesOperationsExtensions.Get (operations, resourceGroupName, serverName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Sql.Models.ServerConnectionPolicy</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Sql.IServerConnectionPoliciesOperations" RefType="this" />
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
            Ruft die Richtlinie für sichere Verbindung des Servers ab.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Sql.Models.ServerConnectionPolicy&gt; GetAsync (this Microsoft.Azure.Management.Sql.IServerConnectionPoliciesOperations operations, string resourceGroupName, string serverName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Sql.Models.ServerConnectionPolicy&gt; GetAsync(class Microsoft.Azure.Management.Sql.IServerConnectionPoliciesOperations operations, string resourceGroupName, string serverName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.ServerConnectionPoliciesOperationsExtensions.GetAsync(Microsoft.Azure.Management.Sql.IServerConnectionPoliciesOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetAsync : Microsoft.Azure.Management.Sql.IServerConnectionPoliciesOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Sql.Models.ServerConnectionPolicy&gt;" Usage="Microsoft.Azure.Management.Sql.ServerConnectionPoliciesOperationsExtensions.GetAsync (operations, resourceGroupName, serverName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Sql.ServerConnectionPoliciesOperationsExtensions/&lt;GetAsync&gt;d__3))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Sql.Models.ServerConnectionPolicy&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Sql.IServerConnectionPoliciesOperations" RefType="this" />
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
            Ruft die Richtlinie für sichere Verbindung des Servers ab.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>