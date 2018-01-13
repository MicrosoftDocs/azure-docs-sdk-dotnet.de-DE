<Type Name="RedisOperationsExtensions" FullName="Microsoft.Azure.Management.Redis.Fluent.RedisOperationsExtensions">
  <TypeSignature Language="C#" Value="public static class RedisOperationsExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit RedisOperationsExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Redis.Fluent.RedisOperationsExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module RedisOperationsExtensions" />
  <TypeSignature Language="F#" Value="type RedisOperationsExtensions = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Redis.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            Erweiterungsmethoden für RedisOperations.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="BeginCreateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Redis.Fluent.Models.RedisResourceInner&gt; BeginCreateAsync (this Microsoft.Azure.Management.Redis.Fluent.IRedisOperations operations, string resourceGroupName, string name, Microsoft.Azure.Management.Redis.Fluent.Models.RedisCreateParametersInner parameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Redis.Fluent.Models.RedisResourceInner&gt; BeginCreateAsync(class Microsoft.Azure.Management.Redis.Fluent.IRedisOperations operations, string resourceGroupName, string name, class Microsoft.Azure.Management.Redis.Fluent.Models.RedisCreateParametersInner parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Redis.Fluent.RedisOperationsExtensions.BeginCreateAsync(Microsoft.Azure.Management.Redis.Fluent.IRedisOperations,System.String,System.String,Microsoft.Azure.Management.Redis.Fluent.Models.RedisCreateParametersInner,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginCreateAsync : Microsoft.Azure.Management.Redis.Fluent.IRedisOperations * string * string * Microsoft.Azure.Management.Redis.Fluent.Models.RedisCreateParametersInner * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Redis.Fluent.Models.RedisResourceInner&gt;" Usage="Microsoft.Azure.Management.Redis.Fluent.RedisOperationsExtensions.BeginCreateAsync (operations, resourceGroupName, name, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Redis.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Redis.Fluent.RedisOperationsExtensions/&lt;BeginCreateAsync&gt;d__11))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Redis.Fluent.Models.RedisResourceInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Redis.Fluent.IRedisOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Redis.Fluent.Models.RedisCreateParametersInner" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="resourceGroupName">
            Der Name der Ressourcengruppe.
            </param>
        <param name="name">
            Der Name des Redis-Caches.
            </param>
        <param name="parameters">
            Parameter für das Erstellen des Redis-zur Verfügung gestellt.
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Erstellen Sie oder Ersetzen Sie (überschreiben/neu erstellen, mit potenziellen Ausfallzeiten) einen vorhandenen Redis-Cache.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginDeleteAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task BeginDeleteAsync (this Microsoft.Azure.Management.Redis.Fluent.IRedisOperations operations, string resourceGroupName, string name, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task BeginDeleteAsync(class Microsoft.Azure.Management.Redis.Fluent.IRedisOperations operations, string resourceGroupName, string name, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Redis.Fluent.RedisOperationsExtensions.BeginDeleteAsync(Microsoft.Azure.Management.Redis.Fluent.IRedisOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginDeleteAsync : Microsoft.Azure.Management.Redis.Fluent.IRedisOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.Redis.Fluent.RedisOperationsExtensions.BeginDeleteAsync (operations, resourceGroupName, name, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Redis.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Redis.Fluent.RedisOperationsExtensions/&lt;BeginDeleteAsync&gt;d__12))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Redis.Fluent.IRedisOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="resourceGroupName">
            Der Name der Ressourcengruppe.
            </param>
        <param name="name">
            Der Name des Redis-Caches.
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Löscht einen Redis Cache.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginExportDataAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task BeginExportDataAsync (this Microsoft.Azure.Management.Redis.Fluent.IRedisOperations operations, string resourceGroupName, string name, Microsoft.Azure.Management.Redis.Fluent.Models.ExportRDBParametersInner parameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task BeginExportDataAsync(class Microsoft.Azure.Management.Redis.Fluent.IRedisOperations operations, string resourceGroupName, string name, class Microsoft.Azure.Management.Redis.Fluent.Models.ExportRDBParametersInner parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Redis.Fluent.RedisOperationsExtensions.BeginExportDataAsync(Microsoft.Azure.Management.Redis.Fluent.IRedisOperations,System.String,System.String,Microsoft.Azure.Management.Redis.Fluent.Models.ExportRDBParametersInner,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginExportDataAsync : Microsoft.Azure.Management.Redis.Fluent.IRedisOperations * string * string * Microsoft.Azure.Management.Redis.Fluent.Models.ExportRDBParametersInner * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.Redis.Fluent.RedisOperationsExtensions.BeginExportDataAsync (operations, resourceGroupName, name, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Redis.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Redis.Fluent.RedisOperationsExtensions/&lt;BeginExportDataAsync&gt;d__14))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Redis.Fluent.IRedisOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Redis.Fluent.Models.ExportRDBParametersInner" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="resourceGroupName">
            Der Name der Ressourcengruppe.
            </param>
        <param name="name">
            Der Name des Redis-Caches.
            </param>
        <param name="parameters">
            Parameter für Redis-Exportvorgang.
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Exportieren von Daten aus dem Redis-Cache auf Blobs in einem Container.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginImportDataAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task BeginImportDataAsync (this Microsoft.Azure.Management.Redis.Fluent.IRedisOperations operations, string resourceGroupName, string name, Microsoft.Azure.Management.Redis.Fluent.Models.ImportRDBParametersInner parameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task BeginImportDataAsync(class Microsoft.Azure.Management.Redis.Fluent.IRedisOperations operations, string resourceGroupName, string name, class Microsoft.Azure.Management.Redis.Fluent.Models.ImportRDBParametersInner parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Redis.Fluent.RedisOperationsExtensions.BeginImportDataAsync(Microsoft.Azure.Management.Redis.Fluent.IRedisOperations,System.String,System.String,Microsoft.Azure.Management.Redis.Fluent.Models.ImportRDBParametersInner,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginImportDataAsync : Microsoft.Azure.Management.Redis.Fluent.IRedisOperations * string * string * Microsoft.Azure.Management.Redis.Fluent.Models.ImportRDBParametersInner * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.Redis.Fluent.RedisOperationsExtensions.BeginImportDataAsync (operations, resourceGroupName, name, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Redis.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Redis.Fluent.RedisOperationsExtensions/&lt;BeginImportDataAsync&gt;d__13))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Redis.Fluent.IRedisOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Redis.Fluent.Models.ImportRDBParametersInner" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="resourceGroupName">
            Der Name der Ressourcengruppe.
            </param>
        <param name="name">
            Der Name des Redis-Caches.
            </param>
        <param name="parameters">
            Parameter für Redis Datenimportvorgang an.
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Importieren Sie Daten in den Redis-Cache.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Redis.Fluent.Models.RedisResourceInner&gt; CreateAsync (this Microsoft.Azure.Management.Redis.Fluent.IRedisOperations operations, string resourceGroupName, string name, Microsoft.Azure.Management.Redis.Fluent.Models.RedisCreateParametersInner parameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Redis.Fluent.Models.RedisResourceInner&gt; CreateAsync(class Microsoft.Azure.Management.Redis.Fluent.IRedisOperations operations, string resourceGroupName, string name, class Microsoft.Azure.Management.Redis.Fluent.Models.RedisCreateParametersInner parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Redis.Fluent.RedisOperationsExtensions.CreateAsync(Microsoft.Azure.Management.Redis.Fluent.IRedisOperations,System.String,System.String,Microsoft.Azure.Management.Redis.Fluent.Models.RedisCreateParametersInner,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member CreateAsync : Microsoft.Azure.Management.Redis.Fluent.IRedisOperations * string * string * Microsoft.Azure.Management.Redis.Fluent.Models.RedisCreateParametersInner * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Redis.Fluent.Models.RedisResourceInner&gt;" Usage="Microsoft.Azure.Management.Redis.Fluent.RedisOperationsExtensions.CreateAsync (operations, resourceGroupName, name, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Redis.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Redis.Fluent.RedisOperationsExtensions/&lt;CreateAsync&gt;d__0))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Redis.Fluent.Models.RedisResourceInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Redis.Fluent.IRedisOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Redis.Fluent.Models.RedisCreateParametersInner" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="resourceGroupName">
            Der Name der Ressourcengruppe.
            </param>
        <param name="name">
            Der Name des Redis-Caches.
            </param>
        <param name="parameters">
            Parameter für das Erstellen des Redis-zur Verfügung gestellt.
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Erstellen Sie oder Ersetzen Sie (überschreiben/neu erstellen, mit potenziellen Ausfallzeiten) einen vorhandenen Redis-Cache.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task DeleteAsync (this Microsoft.Azure.Management.Redis.Fluent.IRedisOperations operations, string resourceGroupName, string name, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task DeleteAsync(class Microsoft.Azure.Management.Redis.Fluent.IRedisOperations operations, string resourceGroupName, string name, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Redis.Fluent.RedisOperationsExtensions.DeleteAsync(Microsoft.Azure.Management.Redis.Fluent.IRedisOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member DeleteAsync : Microsoft.Azure.Management.Redis.Fluent.IRedisOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.Redis.Fluent.RedisOperationsExtensions.DeleteAsync (operations, resourceGroupName, name, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Redis.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Redis.Fluent.RedisOperationsExtensions/&lt;DeleteAsync&gt;d__2))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Redis.Fluent.IRedisOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="resourceGroupName">
            Der Name der Ressourcengruppe.
            </param>
        <param name="name">
            Der Name des Redis-Caches.
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Löscht einen Redis Cache.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ExportDataAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task ExportDataAsync (this Microsoft.Azure.Management.Redis.Fluent.IRedisOperations operations, string resourceGroupName, string name, Microsoft.Azure.Management.Redis.Fluent.Models.ExportRDBParametersInner parameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task ExportDataAsync(class Microsoft.Azure.Management.Redis.Fluent.IRedisOperations operations, string resourceGroupName, string name, class Microsoft.Azure.Management.Redis.Fluent.Models.ExportRDBParametersInner parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Redis.Fluent.RedisOperationsExtensions.ExportDataAsync(Microsoft.Azure.Management.Redis.Fluent.IRedisOperations,System.String,System.String,Microsoft.Azure.Management.Redis.Fluent.Models.ExportRDBParametersInner,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ExportDataAsync : Microsoft.Azure.Management.Redis.Fluent.IRedisOperations * string * string * Microsoft.Azure.Management.Redis.Fluent.Models.ExportRDBParametersInner * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.Redis.Fluent.RedisOperationsExtensions.ExportDataAsync (operations, resourceGroupName, name, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Redis.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Redis.Fluent.RedisOperationsExtensions/&lt;ExportDataAsync&gt;d__10))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Redis.Fluent.IRedisOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Redis.Fluent.Models.ExportRDBParametersInner" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="resourceGroupName">
            Der Name der Ressourcengruppe.
            </param>
        <param name="name">
            Der Name des Redis-Caches.
            </param>
        <param name="parameters">
            Parameter für Redis-Exportvorgang.
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Exportieren von Daten aus dem Redis-Cache auf Blobs in einem Container.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ForceRebootAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Redis.Fluent.Models.RedisForceRebootResponseInner&gt; ForceRebootAsync (this Microsoft.Azure.Management.Redis.Fluent.IRedisOperations operations, string resourceGroupName, string name, Microsoft.Azure.Management.Redis.Fluent.Models.RedisRebootParametersInner parameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Redis.Fluent.Models.RedisForceRebootResponseInner&gt; ForceRebootAsync(class Microsoft.Azure.Management.Redis.Fluent.IRedisOperations operations, string resourceGroupName, string name, class Microsoft.Azure.Management.Redis.Fluent.Models.RedisRebootParametersInner parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Redis.Fluent.RedisOperationsExtensions.ForceRebootAsync(Microsoft.Azure.Management.Redis.Fluent.IRedisOperations,System.String,System.String,Microsoft.Azure.Management.Redis.Fluent.Models.RedisRebootParametersInner,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ForceRebootAsync : Microsoft.Azure.Management.Redis.Fluent.IRedisOperations * string * string * Microsoft.Azure.Management.Redis.Fluent.Models.RedisRebootParametersInner * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Redis.Fluent.Models.RedisForceRebootResponseInner&gt;" Usage="Microsoft.Azure.Management.Redis.Fluent.RedisOperationsExtensions.ForceRebootAsync (operations, resourceGroupName, name, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Redis.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Redis.Fluent.RedisOperationsExtensions/&lt;ForceRebootAsync&gt;d__8))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Redis.Fluent.Models.RedisForceRebootResponseInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Redis.Fluent.IRedisOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Redis.Fluent.Models.RedisRebootParametersInner" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="resourceGroupName">
            Der Name der Ressourcengruppe.
            </param>
        <param name="name">
            Der Name des Redis-Caches.
            </param>
        <param name="parameters">
            Gibt an, der Redis-Knoten neu starten.
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Neustart angegeben Redis-Knoten. Dieser Vorgang erfordert, über die Schreibberechtigung für die Cache-Ressource. Datenverlust möglich.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Redis.Fluent.Models.RedisResourceInner&gt; GetAsync (this Microsoft.Azure.Management.Redis.Fluent.IRedisOperations operations, string resourceGroupName, string name, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Redis.Fluent.Models.RedisResourceInner&gt; GetAsync(class Microsoft.Azure.Management.Redis.Fluent.IRedisOperations operations, string resourceGroupName, string name, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Redis.Fluent.RedisOperationsExtensions.GetAsync(Microsoft.Azure.Management.Redis.Fluent.IRedisOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetAsync : Microsoft.Azure.Management.Redis.Fluent.IRedisOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Redis.Fluent.Models.RedisResourceInner&gt;" Usage="Microsoft.Azure.Management.Redis.Fluent.RedisOperationsExtensions.GetAsync (operations, resourceGroupName, name, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Redis.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Redis.Fluent.RedisOperationsExtensions/&lt;GetAsync&gt;d__3))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Redis.Fluent.Models.RedisResourceInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Redis.Fluent.IRedisOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="resourceGroupName">
            Der Name der Ressourcengruppe.
            </param>
        <param name="name">
            Der Name des Redis-Caches.
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Ruft einen Redis Cache (ressourcenbeschreibung) ab.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ImportDataAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task ImportDataAsync (this Microsoft.Azure.Management.Redis.Fluent.IRedisOperations operations, string resourceGroupName, string name, Microsoft.Azure.Management.Redis.Fluent.Models.ImportRDBParametersInner parameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task ImportDataAsync(class Microsoft.Azure.Management.Redis.Fluent.IRedisOperations operations, string resourceGroupName, string name, class Microsoft.Azure.Management.Redis.Fluent.Models.ImportRDBParametersInner parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Redis.Fluent.RedisOperationsExtensions.ImportDataAsync(Microsoft.Azure.Management.Redis.Fluent.IRedisOperations,System.String,System.String,Microsoft.Azure.Management.Redis.Fluent.Models.ImportRDBParametersInner,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ImportDataAsync : Microsoft.Azure.Management.Redis.Fluent.IRedisOperations * string * string * Microsoft.Azure.Management.Redis.Fluent.Models.ImportRDBParametersInner * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.Redis.Fluent.RedisOperationsExtensions.ImportDataAsync (operations, resourceGroupName, name, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Redis.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Redis.Fluent.RedisOperationsExtensions/&lt;ImportDataAsync&gt;d__9))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Redis.Fluent.IRedisOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Redis.Fluent.Models.ImportRDBParametersInner" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="resourceGroupName">
            Der Name der Ressourcengruppe.
            </param>
        <param name="name">
            Der Name des Redis-Caches.
            </param>
        <param name="parameters">
            Parameter für Redis Datenimportvorgang an.
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Importieren Sie Daten in den Redis-Cache.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Redis.Fluent.Models.RedisResourceInner&gt;&gt; ListAsync (this Microsoft.Azure.Management.Redis.Fluent.IRedisOperations operations, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Redis.Fluent.Models.RedisResourceInner&gt;&gt; ListAsync(class Microsoft.Azure.Management.Redis.Fluent.IRedisOperations operations, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Redis.Fluent.RedisOperationsExtensions.ListAsync(Microsoft.Azure.Management.Redis.Fluent.IRedisOperations,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListAsync : Microsoft.Azure.Management.Redis.Fluent.IRedisOperations * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Redis.Fluent.Models.RedisResourceInner&gt;&gt;" Usage="Microsoft.Azure.Management.Redis.Fluent.RedisOperationsExtensions.ListAsync (operations, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Redis.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Redis.Fluent.RedisOperationsExtensions/&lt;ListAsync&gt;d__5))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Redis.Fluent.Models.RedisResourceInner&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Redis.Fluent.IRedisOperations" RefType="this" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Ruft alle Redis-Caches in das angegebene Abonnement ab.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByResourceGroupAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Redis.Fluent.Models.RedisResourceInner&gt;&gt; ListByResourceGroupAsync (this Microsoft.Azure.Management.Redis.Fluent.IRedisOperations operations, string resourceGroupName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Redis.Fluent.Models.RedisResourceInner&gt;&gt; ListByResourceGroupAsync(class Microsoft.Azure.Management.Redis.Fluent.IRedisOperations operations, string resourceGroupName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Redis.Fluent.RedisOperationsExtensions.ListByResourceGroupAsync(Microsoft.Azure.Management.Redis.Fluent.IRedisOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListByResourceGroupAsync : Microsoft.Azure.Management.Redis.Fluent.IRedisOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Redis.Fluent.Models.RedisResourceInner&gt;&gt;" Usage="Microsoft.Azure.Management.Redis.Fluent.RedisOperationsExtensions.ListByResourceGroupAsync (operations, resourceGroupName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Redis.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Redis.Fluent.RedisOperationsExtensions/&lt;ListByResourceGroupAsync&gt;d__4))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Redis.Fluent.Models.RedisResourceInner&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Redis.Fluent.IRedisOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="resourceGroupName">
            Der Name der Ressourcengruppe.
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Listet alle Redis-Caches in einer Ressourcengruppe.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByResourceGroupNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Redis.Fluent.Models.RedisResourceInner&gt;&gt; ListByResourceGroupNextAsync (this Microsoft.Azure.Management.Redis.Fluent.IRedisOperations operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Redis.Fluent.Models.RedisResourceInner&gt;&gt; ListByResourceGroupNextAsync(class Microsoft.Azure.Management.Redis.Fluent.IRedisOperations operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Redis.Fluent.RedisOperationsExtensions.ListByResourceGroupNextAsync(Microsoft.Azure.Management.Redis.Fluent.IRedisOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListByResourceGroupNextAsync : Microsoft.Azure.Management.Redis.Fluent.IRedisOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Redis.Fluent.Models.RedisResourceInner&gt;&gt;" Usage="Microsoft.Azure.Management.Redis.Fluent.RedisOperationsExtensions.ListByResourceGroupNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Redis.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Redis.Fluent.RedisOperationsExtensions/&lt;ListByResourceGroupNextAsync&gt;d__15))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Redis.Fluent.Models.RedisResourceInner&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Redis.Fluent.IRedisOperations" RefType="this" />
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
            Listet alle Redis-Caches in einer Ressourcengruppe.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListKeysAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Redis.Fluent.Models.RedisAccessKeysInner&gt; ListKeysAsync (this Microsoft.Azure.Management.Redis.Fluent.IRedisOperations operations, string resourceGroupName, string name, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Redis.Fluent.Models.RedisAccessKeysInner&gt; ListKeysAsync(class Microsoft.Azure.Management.Redis.Fluent.IRedisOperations operations, string resourceGroupName, string name, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Redis.Fluent.RedisOperationsExtensions.ListKeysAsync(Microsoft.Azure.Management.Redis.Fluent.IRedisOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListKeysAsync : Microsoft.Azure.Management.Redis.Fluent.IRedisOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Redis.Fluent.Models.RedisAccessKeysInner&gt;" Usage="Microsoft.Azure.Management.Redis.Fluent.RedisOperationsExtensions.ListKeysAsync (operations, resourceGroupName, name, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Redis.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Redis.Fluent.RedisOperationsExtensions/&lt;ListKeysAsync&gt;d__6))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Redis.Fluent.Models.RedisAccessKeysInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Redis.Fluent.IRedisOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="resourceGroupName">
            Der Name der Ressourcengruppe.
            </param>
        <param name="name">
            Der Name des Redis-Caches.
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Abgerufen Sie ein Redis-Cache-Zugriffsschlüsseln werden. Dieser Vorgang erfordert, über die Schreibberechtigung für die Cache-Ressource.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Redis.Fluent.Models.RedisResourceInner&gt;&gt; ListNextAsync (this Microsoft.Azure.Management.Redis.Fluent.IRedisOperations operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Redis.Fluent.Models.RedisResourceInner&gt;&gt; ListNextAsync(class Microsoft.Azure.Management.Redis.Fluent.IRedisOperations operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Redis.Fluent.RedisOperationsExtensions.ListNextAsync(Microsoft.Azure.Management.Redis.Fluent.IRedisOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListNextAsync : Microsoft.Azure.Management.Redis.Fluent.IRedisOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Redis.Fluent.Models.RedisResourceInner&gt;&gt;" Usage="Microsoft.Azure.Management.Redis.Fluent.RedisOperationsExtensions.ListNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Redis.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Redis.Fluent.RedisOperationsExtensions/&lt;ListNextAsync&gt;d__16))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Redis.Fluent.Models.RedisResourceInner&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Redis.Fluent.IRedisOperations" RefType="this" />
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
            Ruft alle Redis-Caches in das angegebene Abonnement ab.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RegenerateKeyAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Redis.Fluent.Models.RedisAccessKeysInner&gt; RegenerateKeyAsync (this Microsoft.Azure.Management.Redis.Fluent.IRedisOperations operations, string resourceGroupName, string name, Microsoft.Azure.Management.Redis.Fluent.Models.RedisKeyType keyType, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Redis.Fluent.Models.RedisAccessKeysInner&gt; RegenerateKeyAsync(class Microsoft.Azure.Management.Redis.Fluent.IRedisOperations operations, string resourceGroupName, string name, valuetype Microsoft.Azure.Management.Redis.Fluent.Models.RedisKeyType keyType, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Redis.Fluent.RedisOperationsExtensions.RegenerateKeyAsync(Microsoft.Azure.Management.Redis.Fluent.IRedisOperations,System.String,System.String,Microsoft.Azure.Management.Redis.Fluent.Models.RedisKeyType,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member RegenerateKeyAsync : Microsoft.Azure.Management.Redis.Fluent.IRedisOperations * string * string * Microsoft.Azure.Management.Redis.Fluent.Models.RedisKeyType * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Redis.Fluent.Models.RedisAccessKeysInner&gt;" Usage="Microsoft.Azure.Management.Redis.Fluent.RedisOperationsExtensions.RegenerateKeyAsync (operations, resourceGroupName, name, keyType, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Redis.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Redis.Fluent.RedisOperationsExtensions/&lt;RegenerateKeyAsync&gt;d__7))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Redis.Fluent.Models.RedisAccessKeysInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Redis.Fluent.IRedisOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="keyType" Type="Microsoft.Azure.Management.Redis.Fluent.Models.RedisKeyType" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="resourceGroupName">
            Der Name der Ressourcengruppe.
            </param>
        <param name="name">
            Der Name des Redis-Caches.
            </param>
        <param name="keyType">
            Der Redis-Zugriffsschlüssel erneut generieren. Folgende Werte sind möglich: 'Primary', 'Sekundären'
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Neugenerieren von Zugriffsschlüsseln für Redis-Cache. Dieser Vorgang erfordert, über die Schreibberechtigung für die Cache-Ressource.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UpdateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Redis.Fluent.Models.RedisResourceInner&gt; UpdateAsync (this Microsoft.Azure.Management.Redis.Fluent.IRedisOperations operations, string resourceGroupName, string name, Microsoft.Azure.Management.Redis.Fluent.Models.RedisUpdateParametersInner parameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Redis.Fluent.Models.RedisResourceInner&gt; UpdateAsync(class Microsoft.Azure.Management.Redis.Fluent.IRedisOperations operations, string resourceGroupName, string name, class Microsoft.Azure.Management.Redis.Fluent.Models.RedisUpdateParametersInner parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Redis.Fluent.RedisOperationsExtensions.UpdateAsync(Microsoft.Azure.Management.Redis.Fluent.IRedisOperations,System.String,System.String,Microsoft.Azure.Management.Redis.Fluent.Models.RedisUpdateParametersInner,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member UpdateAsync : Microsoft.Azure.Management.Redis.Fluent.IRedisOperations * string * string * Microsoft.Azure.Management.Redis.Fluent.Models.RedisUpdateParametersInner * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Redis.Fluent.Models.RedisResourceInner&gt;" Usage="Microsoft.Azure.Management.Redis.Fluent.RedisOperationsExtensions.UpdateAsync (operations, resourceGroupName, name, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Redis.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Redis.Fluent.RedisOperationsExtensions/&lt;UpdateAsync&gt;d__1))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Redis.Fluent.Models.RedisResourceInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Redis.Fluent.IRedisOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Redis.Fluent.Models.RedisUpdateParametersInner" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="resourceGroupName">
            Der Name der Ressourcengruppe.
            </param>
        <param name="name">
            Der Name des Redis-Caches.
            </param>
        <param name="parameters">
            Parameter für den Redis-Update zur Verfügung gestellt.
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Aktualisieren Sie einen vorhandenen Redis-Cache.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>