<Type Name="FileOperationsExtensions" FullName="Microsoft.Azure.Batch.Protocol.FileOperationsExtensions">
  <TypeSignature Language="C#" Value="public static class FileOperationsExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit FileOperationsExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Batch.Protocol.FileOperationsExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module FileOperationsExtensions" />
  <TypeSignature Language="F#" Value="type FileOperationsExtensions = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
    <AssemblyVersion>7.1.0.0</AssemblyVersion>
    <AssemblyVersion>8.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            Erweiterungsmethoden für FileOperations.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="DeleteFromComputeNode">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Batch.Protocol.Models.FileDeleteFromComputeNodeHeaders DeleteFromComputeNode (this Microsoft.Azure.Batch.Protocol.IFileOperations operations, string poolId, string nodeId, string filePath, Nullable&lt;bool&gt; recursive = null, Microsoft.Azure.Batch.Protocol.Models.FileDeleteFromComputeNodeOptions fileDeleteFromComputeNodeOptions = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Batch.Protocol.Models.FileDeleteFromComputeNodeHeaders DeleteFromComputeNode(class Microsoft.Azure.Batch.Protocol.IFileOperations operations, string poolId, string nodeId, string filePath, valuetype System.Nullable`1&lt;bool&gt; recursive, class Microsoft.Azure.Batch.Protocol.Models.FileDeleteFromComputeNodeOptions fileDeleteFromComputeNodeOptions) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.FileOperationsExtensions.DeleteFromComputeNode(Microsoft.Azure.Batch.Protocol.IFileOperations,System.String,System.String,System.String,System.Nullable{System.Boolean},Microsoft.Azure.Batch.Protocol.Models.FileDeleteFromComputeNodeOptions)" />
      <MemberSignature Language="F#" Value="static member DeleteFromComputeNode : Microsoft.Azure.Batch.Protocol.IFileOperations * string * string * string * Nullable&lt;bool&gt; * Microsoft.Azure.Batch.Protocol.Models.FileDeleteFromComputeNodeOptions -&gt; Microsoft.Azure.Batch.Protocol.Models.FileDeleteFromComputeNodeHeaders" Usage="Microsoft.Azure.Batch.Protocol.FileOperationsExtensions.DeleteFromComputeNode (operations, poolId, nodeId, filePath, recursive, fileDeleteFromComputeNodeOptions)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.Protocol.Models.FileDeleteFromComputeNodeHeaders</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Batch.Protocol.IFileOperations" RefType="this" />
        <Parameter Name="poolId" Type="System.String" />
        <Parameter Name="nodeId" Type="System.String" />
        <Parameter Name="filePath" Type="System.String" />
        <Parameter Name="recursive" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="fileDeleteFromComputeNodeOptions" Type="Microsoft.Azure.Batch.Protocol.Models.FileDeleteFromComputeNodeOptions" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="poolId">
            Die ID des Pools, den Compute-Knoten enthält.
            </param>
        <param name="nodeId">
            Die ID der Compute-Knoten, von dem Sie die Datei löschen möchten.
            </param>
        <param name="filePath">
            Der Pfad zur Datei oder zum Verzeichnis, das Sie löschen möchten.
            </param>
        <param name="recursive">
            Ob untergeordnete Elemente eines Verzeichnisses gelöscht. Wenn der Parameter "FilePath" ein Verzeichnis anstelle einer Datei darstellt, können Sie die rekursive auf "true" Löschen des Verzeichnisses und aller Dateien und Unterverzeichnisse darin festlegen. Wenn rekursiv "false" ist das Verzeichnis muss leer sein, oder Löschvorgang fehl.
            </param>
        <param name="fileDeleteFromComputeNodeOptions">
            Zusätzliche Parameter für den Vorgang
            </param>
        <summary>
            Löscht die angegebene Datei als der Serverknoten an.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteFromComputeNodeAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Batch.Protocol.Models.FileDeleteFromComputeNodeHeaders&gt; DeleteFromComputeNodeAsync (this Microsoft.Azure.Batch.Protocol.IFileOperations operations, string poolId, string nodeId, string filePath, Nullable&lt;bool&gt; recursive = null, Microsoft.Azure.Batch.Protocol.Models.FileDeleteFromComputeNodeOptions fileDeleteFromComputeNodeOptions = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Batch.Protocol.Models.FileDeleteFromComputeNodeHeaders&gt; DeleteFromComputeNodeAsync(class Microsoft.Azure.Batch.Protocol.IFileOperations operations, string poolId, string nodeId, string filePath, valuetype System.Nullable`1&lt;bool&gt; recursive, class Microsoft.Azure.Batch.Protocol.Models.FileDeleteFromComputeNodeOptions fileDeleteFromComputeNodeOptions, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.FileOperationsExtensions.DeleteFromComputeNodeAsync(Microsoft.Azure.Batch.Protocol.IFileOperations,System.String,System.String,System.String,System.Nullable{System.Boolean},Microsoft.Azure.Batch.Protocol.Models.FileDeleteFromComputeNodeOptions,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member DeleteFromComputeNodeAsync : Microsoft.Azure.Batch.Protocol.IFileOperations * string * string * string * Nullable&lt;bool&gt; * Microsoft.Azure.Batch.Protocol.Models.FileDeleteFromComputeNodeOptions * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Batch.Protocol.Models.FileDeleteFromComputeNodeHeaders&gt;" Usage="Microsoft.Azure.Batch.Protocol.FileOperationsExtensions.DeleteFromComputeNodeAsync (operations, poolId, nodeId, filePath, recursive, fileDeleteFromComputeNodeOptions, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Batch.Protocol.FileOperationsExtensions/&lt;DeleteFromComputeNodeAsync&gt;d__7))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Batch.Protocol.Models.FileDeleteFromComputeNodeHeaders&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Batch.Protocol.IFileOperations" RefType="this" />
        <Parameter Name="poolId" Type="System.String" />
        <Parameter Name="nodeId" Type="System.String" />
        <Parameter Name="filePath" Type="System.String" />
        <Parameter Name="recursive" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="fileDeleteFromComputeNodeOptions" Type="Microsoft.Azure.Batch.Protocol.Models.FileDeleteFromComputeNodeOptions" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="poolId">
            Die ID des Pools, den Compute-Knoten enthält.
            </param>
        <param name="nodeId">
            Die ID der Compute-Knoten, von dem Sie die Datei löschen möchten.
            </param>
        <param name="filePath">
            Der Pfad zur Datei oder zum Verzeichnis, das Sie löschen möchten.
            </param>
        <param name="recursive">
            Ob untergeordnete Elemente eines Verzeichnisses gelöscht. Wenn der Parameter "FilePath" ein Verzeichnis anstelle einer Datei darstellt, können Sie die rekursive auf "true" Löschen des Verzeichnisses und aller Dateien und Unterverzeichnisse darin festlegen. Wenn rekursiv "false" ist das Verzeichnis muss leer sein, oder Löschvorgang fehl.
            </param>
        <param name="fileDeleteFromComputeNodeOptions">
            Zusätzliche Parameter für den Vorgang
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Löscht die angegebene Datei als der Serverknoten an.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteFromTask">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Batch.Protocol.Models.FileDeleteFromTaskHeaders DeleteFromTask (this Microsoft.Azure.Batch.Protocol.IFileOperations operations, string jobId, string taskId, string filePath, Nullable&lt;bool&gt; recursive = null, Microsoft.Azure.Batch.Protocol.Models.FileDeleteFromTaskOptions fileDeleteFromTaskOptions = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Batch.Protocol.Models.FileDeleteFromTaskHeaders DeleteFromTask(class Microsoft.Azure.Batch.Protocol.IFileOperations operations, string jobId, string taskId, string filePath, valuetype System.Nullable`1&lt;bool&gt; recursive, class Microsoft.Azure.Batch.Protocol.Models.FileDeleteFromTaskOptions fileDeleteFromTaskOptions) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.FileOperationsExtensions.DeleteFromTask(Microsoft.Azure.Batch.Protocol.IFileOperations,System.String,System.String,System.String,System.Nullable{System.Boolean},Microsoft.Azure.Batch.Protocol.Models.FileDeleteFromTaskOptions)" />
      <MemberSignature Language="F#" Value="static member DeleteFromTask : Microsoft.Azure.Batch.Protocol.IFileOperations * string * string * string * Nullable&lt;bool&gt; * Microsoft.Azure.Batch.Protocol.Models.FileDeleteFromTaskOptions -&gt; Microsoft.Azure.Batch.Protocol.Models.FileDeleteFromTaskHeaders" Usage="Microsoft.Azure.Batch.Protocol.FileOperationsExtensions.DeleteFromTask (operations, jobId, taskId, filePath, recursive, fileDeleteFromTaskOptions)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.Protocol.Models.FileDeleteFromTaskHeaders</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Batch.Protocol.IFileOperations" RefType="this" />
        <Parameter Name="jobId" Type="System.String" />
        <Parameter Name="taskId" Type="System.String" />
        <Parameter Name="filePath" Type="System.String" />
        <Parameter Name="recursive" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="fileDeleteFromTaskOptions" Type="Microsoft.Azure.Batch.Protocol.Models.FileDeleteFromTaskOptions" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="jobId">
            Die ID des Auftrags, der den Task enthält.
            </param>
        <param name="taskId">
            Die ID der Aufgabe, deren Datei, die Sie löschen möchten.
            </param>
        <param name="filePath">
            Der Pfad zu der Aufgabendatei oder das Verzeichnis, das Sie löschen möchten.
            </param>
        <param name="recursive">
            Ob untergeordnete Elemente eines Verzeichnisses gelöscht. Wenn der Parameter "FilePath" ein Verzeichnis anstelle einer Datei darstellt, können Sie die rekursive auf "true" Löschen des Verzeichnisses und aller Dateien und Unterverzeichnisse darin festlegen. Wenn rekursiv "false" ist das Verzeichnis muss leer sein, oder Löschvorgang fehl.
            </param>
        <param name="fileDeleteFromTaskOptions">
            Zusätzliche Parameter für den Vorgang
            </param>
        <summary>
            Löscht der angegebenen Aufgabendatei aus den Compute-Knoten, in dem die Aufgabe ausgeführt wurde.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteFromTaskAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Batch.Protocol.Models.FileDeleteFromTaskHeaders&gt; DeleteFromTaskAsync (this Microsoft.Azure.Batch.Protocol.IFileOperations operations, string jobId, string taskId, string filePath, Nullable&lt;bool&gt; recursive = null, Microsoft.Azure.Batch.Protocol.Models.FileDeleteFromTaskOptions fileDeleteFromTaskOptions = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Batch.Protocol.Models.FileDeleteFromTaskHeaders&gt; DeleteFromTaskAsync(class Microsoft.Azure.Batch.Protocol.IFileOperations operations, string jobId, string taskId, string filePath, valuetype System.Nullable`1&lt;bool&gt; recursive, class Microsoft.Azure.Batch.Protocol.Models.FileDeleteFromTaskOptions fileDeleteFromTaskOptions, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.FileOperationsExtensions.DeleteFromTaskAsync(Microsoft.Azure.Batch.Protocol.IFileOperations,System.String,System.String,System.String,System.Nullable{System.Boolean},Microsoft.Azure.Batch.Protocol.Models.FileDeleteFromTaskOptions,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member DeleteFromTaskAsync : Microsoft.Azure.Batch.Protocol.IFileOperations * string * string * string * Nullable&lt;bool&gt; * Microsoft.Azure.Batch.Protocol.Models.FileDeleteFromTaskOptions * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Batch.Protocol.Models.FileDeleteFromTaskHeaders&gt;" Usage="Microsoft.Azure.Batch.Protocol.FileOperationsExtensions.DeleteFromTaskAsync (operations, jobId, taskId, filePath, recursive, fileDeleteFromTaskOptions, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Batch.Protocol.FileOperationsExtensions/&lt;DeleteFromTaskAsync&gt;d__1))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Batch.Protocol.Models.FileDeleteFromTaskHeaders&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Batch.Protocol.IFileOperations" RefType="this" />
        <Parameter Name="jobId" Type="System.String" />
        <Parameter Name="taskId" Type="System.String" />
        <Parameter Name="filePath" Type="System.String" />
        <Parameter Name="recursive" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="fileDeleteFromTaskOptions" Type="Microsoft.Azure.Batch.Protocol.Models.FileDeleteFromTaskOptions" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="jobId">
            Die ID des Auftrags, der den Task enthält.
            </param>
        <param name="taskId">
            Die ID der Aufgabe, deren Datei, die Sie löschen möchten.
            </param>
        <param name="filePath">
            Der Pfad zu der Aufgabendatei oder das Verzeichnis, das Sie löschen möchten.
            </param>
        <param name="recursive">
            Ob untergeordnete Elemente eines Verzeichnisses gelöscht. Wenn der Parameter "FilePath" ein Verzeichnis anstelle einer Datei darstellt, können Sie die rekursive auf "true" Löschen des Verzeichnisses und aller Dateien und Unterverzeichnisse darin festlegen. Wenn rekursiv "false" ist das Verzeichnis muss leer sein, oder Löschvorgang fehl.
            </param>
        <param name="fileDeleteFromTaskOptions">
            Zusätzliche Parameter für den Vorgang
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Löscht der angegebenen Aufgabendatei aus den Compute-Knoten, in dem die Aufgabe ausgeführt wurde.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetFromComputeNode">
      <MemberSignature Language="C#" Value="public static System.IO.Stream GetFromComputeNode (this Microsoft.Azure.Batch.Protocol.IFileOperations operations, string poolId, string nodeId, string filePath, Microsoft.Azure.Batch.Protocol.Models.FileGetFromComputeNodeOptions fileGetFromComputeNodeOptions = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.IO.Stream GetFromComputeNode(class Microsoft.Azure.Batch.Protocol.IFileOperations operations, string poolId, string nodeId, string filePath, class Microsoft.Azure.Batch.Protocol.Models.FileGetFromComputeNodeOptions fileGetFromComputeNodeOptions) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.FileOperationsExtensions.GetFromComputeNode(Microsoft.Azure.Batch.Protocol.IFileOperations,System.String,System.String,System.String,Microsoft.Azure.Batch.Protocol.Models.FileGetFromComputeNodeOptions)" />
      <MemberSignature Language="F#" Value="static member GetFromComputeNode : Microsoft.Azure.Batch.Protocol.IFileOperations * string * string * string * Microsoft.Azure.Batch.Protocol.Models.FileGetFromComputeNodeOptions -&gt; System.IO.Stream" Usage="Microsoft.Azure.Batch.Protocol.FileOperationsExtensions.GetFromComputeNode (operations, poolId, nodeId, filePath, fileGetFromComputeNodeOptions)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.IO.Stream</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Batch.Protocol.IFileOperations" RefType="this" />
        <Parameter Name="poolId" Type="System.String" />
        <Parameter Name="nodeId" Type="System.String" />
        <Parameter Name="filePath" Type="System.String" />
        <Parameter Name="fileGetFromComputeNodeOptions" Type="Microsoft.Azure.Batch.Protocol.Models.FileGetFromComputeNodeOptions" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="poolId">
            Die ID des Pools, den Compute-Knoten enthält.
            </param>
        <param name="nodeId">
            Die ID des Compute-Knotens, der die Datei enthält.
            </param>
        <param name="filePath">
            Der Pfad zu der Compute-Knoten-Datei, der den Inhalt abgerufen werden soll.
            </param>
        <param name="fileGetFromComputeNodeOptions">
            Zusätzliche Parameter für den Vorgang
            </param>
        <summary>
            Gibt den Inhalt der angegebenen Compute-Knoten-Datei zurück.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetFromComputeNodeAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;System.IO.Stream&gt; GetFromComputeNodeAsync (this Microsoft.Azure.Batch.Protocol.IFileOperations operations, string poolId, string nodeId, string filePath, Microsoft.Azure.Batch.Protocol.Models.FileGetFromComputeNodeOptions fileGetFromComputeNodeOptions = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class System.IO.Stream&gt; GetFromComputeNodeAsync(class Microsoft.Azure.Batch.Protocol.IFileOperations operations, string poolId, string nodeId, string filePath, class Microsoft.Azure.Batch.Protocol.Models.FileGetFromComputeNodeOptions fileGetFromComputeNodeOptions, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.FileOperationsExtensions.GetFromComputeNodeAsync(Microsoft.Azure.Batch.Protocol.IFileOperations,System.String,System.String,System.String,Microsoft.Azure.Batch.Protocol.Models.FileGetFromComputeNodeOptions,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetFromComputeNodeAsync : Microsoft.Azure.Batch.Protocol.IFileOperations * string * string * string * Microsoft.Azure.Batch.Protocol.Models.FileGetFromComputeNodeOptions * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.IO.Stream&gt;" Usage="Microsoft.Azure.Batch.Protocol.FileOperationsExtensions.GetFromComputeNodeAsync (operations, poolId, nodeId, filePath, fileGetFromComputeNodeOptions, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Batch.Protocol.FileOperationsExtensions/&lt;GetFromComputeNodeAsync&gt;d__9))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.IO.Stream&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Batch.Protocol.IFileOperations" RefType="this" />
        <Parameter Name="poolId" Type="System.String" />
        <Parameter Name="nodeId" Type="System.String" />
        <Parameter Name="filePath" Type="System.String" />
        <Parameter Name="fileGetFromComputeNodeOptions" Type="Microsoft.Azure.Batch.Protocol.Models.FileGetFromComputeNodeOptions" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="poolId">
            Die ID des Pools, den Compute-Knoten enthält.
            </param>
        <param name="nodeId">
            Die ID des Compute-Knotens, der die Datei enthält.
            </param>
        <param name="filePath">
            Der Pfad zu der Compute-Knoten-Datei, der den Inhalt abgerufen werden soll.
            </param>
        <param name="fileGetFromComputeNodeOptions">
            Zusätzliche Parameter für den Vorgang
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Gibt den Inhalt der angegebenen Compute-Knoten-Datei zurück.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetFromTask">
      <MemberSignature Language="C#" Value="public static System.IO.Stream GetFromTask (this Microsoft.Azure.Batch.Protocol.IFileOperations operations, string jobId, string taskId, string filePath, Microsoft.Azure.Batch.Protocol.Models.FileGetFromTaskOptions fileGetFromTaskOptions = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.IO.Stream GetFromTask(class Microsoft.Azure.Batch.Protocol.IFileOperations operations, string jobId, string taskId, string filePath, class Microsoft.Azure.Batch.Protocol.Models.FileGetFromTaskOptions fileGetFromTaskOptions) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.FileOperationsExtensions.GetFromTask(Microsoft.Azure.Batch.Protocol.IFileOperations,System.String,System.String,System.String,Microsoft.Azure.Batch.Protocol.Models.FileGetFromTaskOptions)" />
      <MemberSignature Language="F#" Value="static member GetFromTask : Microsoft.Azure.Batch.Protocol.IFileOperations * string * string * string * Microsoft.Azure.Batch.Protocol.Models.FileGetFromTaskOptions -&gt; System.IO.Stream" Usage="Microsoft.Azure.Batch.Protocol.FileOperationsExtensions.GetFromTask (operations, jobId, taskId, filePath, fileGetFromTaskOptions)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.IO.Stream</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Batch.Protocol.IFileOperations" RefType="this" />
        <Parameter Name="jobId" Type="System.String" />
        <Parameter Name="taskId" Type="System.String" />
        <Parameter Name="filePath" Type="System.String" />
        <Parameter Name="fileGetFromTaskOptions" Type="Microsoft.Azure.Batch.Protocol.Models.FileGetFromTaskOptions" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="jobId">
            Die ID des Auftrags, der den Task enthält.
            </param>
        <param name="taskId">
            Die ID der Aufgabe, deren Datei, die Sie abrufen möchten.
            </param>
        <param name="filePath">
            Der Pfad zu der Aufgabendatei, die den Inhalt abgerufen werden soll.
            </param>
        <param name="fileGetFromTaskOptions">
            Zusätzliche Parameter für den Vorgang
            </param>
        <summary>
            Gibt den Inhalt der angegebenen Aufgabendatei zurück.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetFromTaskAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;System.IO.Stream&gt; GetFromTaskAsync (this Microsoft.Azure.Batch.Protocol.IFileOperations operations, string jobId, string taskId, string filePath, Microsoft.Azure.Batch.Protocol.Models.FileGetFromTaskOptions fileGetFromTaskOptions = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class System.IO.Stream&gt; GetFromTaskAsync(class Microsoft.Azure.Batch.Protocol.IFileOperations operations, string jobId, string taskId, string filePath, class Microsoft.Azure.Batch.Protocol.Models.FileGetFromTaskOptions fileGetFromTaskOptions, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.FileOperationsExtensions.GetFromTaskAsync(Microsoft.Azure.Batch.Protocol.IFileOperations,System.String,System.String,System.String,Microsoft.Azure.Batch.Protocol.Models.FileGetFromTaskOptions,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetFromTaskAsync : Microsoft.Azure.Batch.Protocol.IFileOperations * string * string * string * Microsoft.Azure.Batch.Protocol.Models.FileGetFromTaskOptions * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.IO.Stream&gt;" Usage="Microsoft.Azure.Batch.Protocol.FileOperationsExtensions.GetFromTaskAsync (operations, jobId, taskId, filePath, fileGetFromTaskOptions, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Batch.Protocol.FileOperationsExtensions/&lt;GetFromTaskAsync&gt;d__3))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.IO.Stream&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Batch.Protocol.IFileOperations" RefType="this" />
        <Parameter Name="jobId" Type="System.String" />
        <Parameter Name="taskId" Type="System.String" />
        <Parameter Name="filePath" Type="System.String" />
        <Parameter Name="fileGetFromTaskOptions" Type="Microsoft.Azure.Batch.Protocol.Models.FileGetFromTaskOptions" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="jobId">
            Die ID des Auftrags, der den Task enthält.
            </param>
        <param name="taskId">
            Die ID der Aufgabe, deren Datei, die Sie abrufen möchten.
            </param>
        <param name="filePath">
            Der Pfad zu der Aufgabendatei, die den Inhalt abgerufen werden soll.
            </param>
        <param name="fileGetFromTaskOptions">
            Zusätzliche Parameter für den Vorgang
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Gibt den Inhalt der angegebenen Aufgabendatei zurück.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetPropertiesFromComputeNode">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Batch.Protocol.Models.FileGetPropertiesFromComputeNodeHeaders GetPropertiesFromComputeNode (this Microsoft.Azure.Batch.Protocol.IFileOperations operations, string poolId, string nodeId, string filePath, Microsoft.Azure.Batch.Protocol.Models.FileGetPropertiesFromComputeNodeOptions fileGetPropertiesFromComputeNodeOptions = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Batch.Protocol.Models.FileGetPropertiesFromComputeNodeHeaders GetPropertiesFromComputeNode(class Microsoft.Azure.Batch.Protocol.IFileOperations operations, string poolId, string nodeId, string filePath, class Microsoft.Azure.Batch.Protocol.Models.FileGetPropertiesFromComputeNodeOptions fileGetPropertiesFromComputeNodeOptions) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.FileOperationsExtensions.GetPropertiesFromComputeNode(Microsoft.Azure.Batch.Protocol.IFileOperations,System.String,System.String,System.String,Microsoft.Azure.Batch.Protocol.Models.FileGetPropertiesFromComputeNodeOptions)" />
      <MemberSignature Language="F#" Value="static member GetPropertiesFromComputeNode : Microsoft.Azure.Batch.Protocol.IFileOperations * string * string * string * Microsoft.Azure.Batch.Protocol.Models.FileGetPropertiesFromComputeNodeOptions -&gt; Microsoft.Azure.Batch.Protocol.Models.FileGetPropertiesFromComputeNodeHeaders" Usage="Microsoft.Azure.Batch.Protocol.FileOperationsExtensions.GetPropertiesFromComputeNode (operations, poolId, nodeId, filePath, fileGetPropertiesFromComputeNodeOptions)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.Protocol.Models.FileGetPropertiesFromComputeNodeHeaders</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Batch.Protocol.IFileOperations" RefType="this" />
        <Parameter Name="poolId" Type="System.String" />
        <Parameter Name="nodeId" Type="System.String" />
        <Parameter Name="filePath" Type="System.String" />
        <Parameter Name="fileGetPropertiesFromComputeNodeOptions" Type="Microsoft.Azure.Batch.Protocol.Models.FileGetPropertiesFromComputeNodeOptions" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="poolId">
            Die ID des Pools, den Compute-Knoten enthält.
            </param>
        <param name="nodeId">
            Die ID des Compute-Knotens, der die Datei enthält.
            </param>
        <param name="filePath">
            Der Pfad der Compute-Knoten-Datei, die die Eigenschaften abgerufen werden sollen.
            </param>
        <param name="fileGetPropertiesFromComputeNodeOptions">
            Zusätzliche Parameter für den Vorgang
            </param>
        <summary>
            Ruft die Eigenschaften der angegebenen Compute-Knoten-Datei ab.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetPropertiesFromComputeNodeAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Batch.Protocol.Models.FileGetPropertiesFromComputeNodeHeaders&gt; GetPropertiesFromComputeNodeAsync (this Microsoft.Azure.Batch.Protocol.IFileOperations operations, string poolId, string nodeId, string filePath, Microsoft.Azure.Batch.Protocol.Models.FileGetPropertiesFromComputeNodeOptions fileGetPropertiesFromComputeNodeOptions = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Batch.Protocol.Models.FileGetPropertiesFromComputeNodeHeaders&gt; GetPropertiesFromComputeNodeAsync(class Microsoft.Azure.Batch.Protocol.IFileOperations operations, string poolId, string nodeId, string filePath, class Microsoft.Azure.Batch.Protocol.Models.FileGetPropertiesFromComputeNodeOptions fileGetPropertiesFromComputeNodeOptions, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.FileOperationsExtensions.GetPropertiesFromComputeNodeAsync(Microsoft.Azure.Batch.Protocol.IFileOperations,System.String,System.String,System.String,Microsoft.Azure.Batch.Protocol.Models.FileGetPropertiesFromComputeNodeOptions,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetPropertiesFromComputeNodeAsync : Microsoft.Azure.Batch.Protocol.IFileOperations * string * string * string * Microsoft.Azure.Batch.Protocol.Models.FileGetPropertiesFromComputeNodeOptions * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Batch.Protocol.Models.FileGetPropertiesFromComputeNodeHeaders&gt;" Usage="Microsoft.Azure.Batch.Protocol.FileOperationsExtensions.GetPropertiesFromComputeNodeAsync (operations, poolId, nodeId, filePath, fileGetPropertiesFromComputeNodeOptions, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Batch.Protocol.FileOperationsExtensions/&lt;GetPropertiesFromComputeNodeAsync&gt;d__11))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Batch.Protocol.Models.FileGetPropertiesFromComputeNodeHeaders&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Batch.Protocol.IFileOperations" RefType="this" />
        <Parameter Name="poolId" Type="System.String" />
        <Parameter Name="nodeId" Type="System.String" />
        <Parameter Name="filePath" Type="System.String" />
        <Parameter Name="fileGetPropertiesFromComputeNodeOptions" Type="Microsoft.Azure.Batch.Protocol.Models.FileGetPropertiesFromComputeNodeOptions" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="poolId">
            Die ID des Pools, den Compute-Knoten enthält.
            </param>
        <param name="nodeId">
            Die ID des Compute-Knotens, der die Datei enthält.
            </param>
        <param name="filePath">
            Der Pfad der Compute-Knoten-Datei, die die Eigenschaften abgerufen werden sollen.
            </param>
        <param name="fileGetPropertiesFromComputeNodeOptions">
            Zusätzliche Parameter für den Vorgang
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Ruft die Eigenschaften der angegebenen Compute-Knoten-Datei ab.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetPropertiesFromTask">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Batch.Protocol.Models.FileGetPropertiesFromTaskHeaders GetPropertiesFromTask (this Microsoft.Azure.Batch.Protocol.IFileOperations operations, string jobId, string taskId, string filePath, Microsoft.Azure.Batch.Protocol.Models.FileGetPropertiesFromTaskOptions fileGetPropertiesFromTaskOptions = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Batch.Protocol.Models.FileGetPropertiesFromTaskHeaders GetPropertiesFromTask(class Microsoft.Azure.Batch.Protocol.IFileOperations operations, string jobId, string taskId, string filePath, class Microsoft.Azure.Batch.Protocol.Models.FileGetPropertiesFromTaskOptions fileGetPropertiesFromTaskOptions) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.FileOperationsExtensions.GetPropertiesFromTask(Microsoft.Azure.Batch.Protocol.IFileOperations,System.String,System.String,System.String,Microsoft.Azure.Batch.Protocol.Models.FileGetPropertiesFromTaskOptions)" />
      <MemberSignature Language="F#" Value="static member GetPropertiesFromTask : Microsoft.Azure.Batch.Protocol.IFileOperations * string * string * string * Microsoft.Azure.Batch.Protocol.Models.FileGetPropertiesFromTaskOptions -&gt; Microsoft.Azure.Batch.Protocol.Models.FileGetPropertiesFromTaskHeaders" Usage="Microsoft.Azure.Batch.Protocol.FileOperationsExtensions.GetPropertiesFromTask (operations, jobId, taskId, filePath, fileGetPropertiesFromTaskOptions)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.Protocol.Models.FileGetPropertiesFromTaskHeaders</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Batch.Protocol.IFileOperations" RefType="this" />
        <Parameter Name="jobId" Type="System.String" />
        <Parameter Name="taskId" Type="System.String" />
        <Parameter Name="filePath" Type="System.String" />
        <Parameter Name="fileGetPropertiesFromTaskOptions" Type="Microsoft.Azure.Batch.Protocol.Models.FileGetPropertiesFromTaskOptions" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="jobId">
            Die ID des Auftrags, der den Task enthält.
            </param>
        <param name="taskId">
            Die ID der Aufgabe, deren Datei, die die Eigenschaften abgerufen werden sollen.
            </param>
        <param name="filePath">
            Der Pfad zu der Aufgabendatei, die die Eigenschaften abgerufen werden sollen.
            </param>
        <param name="fileGetPropertiesFromTaskOptions">
            Zusätzliche Parameter für den Vorgang
            </param>
        <summary>
            Ruft die Eigenschaften der angegebenen Aufgabendatei ab.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetPropertiesFromTaskAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Batch.Protocol.Models.FileGetPropertiesFromTaskHeaders&gt; GetPropertiesFromTaskAsync (this Microsoft.Azure.Batch.Protocol.IFileOperations operations, string jobId, string taskId, string filePath, Microsoft.Azure.Batch.Protocol.Models.FileGetPropertiesFromTaskOptions fileGetPropertiesFromTaskOptions = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Batch.Protocol.Models.FileGetPropertiesFromTaskHeaders&gt; GetPropertiesFromTaskAsync(class Microsoft.Azure.Batch.Protocol.IFileOperations operations, string jobId, string taskId, string filePath, class Microsoft.Azure.Batch.Protocol.Models.FileGetPropertiesFromTaskOptions fileGetPropertiesFromTaskOptions, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.FileOperationsExtensions.GetPropertiesFromTaskAsync(Microsoft.Azure.Batch.Protocol.IFileOperations,System.String,System.String,System.String,Microsoft.Azure.Batch.Protocol.Models.FileGetPropertiesFromTaskOptions,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetPropertiesFromTaskAsync : Microsoft.Azure.Batch.Protocol.IFileOperations * string * string * string * Microsoft.Azure.Batch.Protocol.Models.FileGetPropertiesFromTaskOptions * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Batch.Protocol.Models.FileGetPropertiesFromTaskHeaders&gt;" Usage="Microsoft.Azure.Batch.Protocol.FileOperationsExtensions.GetPropertiesFromTaskAsync (operations, jobId, taskId, filePath, fileGetPropertiesFromTaskOptions, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Batch.Protocol.FileOperationsExtensions/&lt;GetPropertiesFromTaskAsync&gt;d__5))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Batch.Protocol.Models.FileGetPropertiesFromTaskHeaders&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Batch.Protocol.IFileOperations" RefType="this" />
        <Parameter Name="jobId" Type="System.String" />
        <Parameter Name="taskId" Type="System.String" />
        <Parameter Name="filePath" Type="System.String" />
        <Parameter Name="fileGetPropertiesFromTaskOptions" Type="Microsoft.Azure.Batch.Protocol.Models.FileGetPropertiesFromTaskOptions" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="jobId">
            Die ID des Auftrags, der den Task enthält.
            </param>
        <param name="taskId">
            Die ID der Aufgabe, deren Datei, die die Eigenschaften abgerufen werden sollen.
            </param>
        <param name="filePath">
            Der Pfad zu der Aufgabendatei, die die Eigenschaften abgerufen werden sollen.
            </param>
        <param name="fileGetPropertiesFromTaskOptions">
            Zusätzliche Parameter für den Vorgang
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Ruft die Eigenschaften der angegebenen Aufgabendatei ab.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListFromComputeNode">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Batch.Protocol.Models.NodeFile&gt; ListFromComputeNode (this Microsoft.Azure.Batch.Protocol.IFileOperations operations, string poolId, string nodeId, Nullable&lt;bool&gt; recursive = null, Microsoft.Azure.Batch.Protocol.Models.FileListFromComputeNodeOptions fileListFromComputeNodeOptions = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Batch.Protocol.Models.NodeFile&gt; ListFromComputeNode(class Microsoft.Azure.Batch.Protocol.IFileOperations operations, string poolId, string nodeId, valuetype System.Nullable`1&lt;bool&gt; recursive, class Microsoft.Azure.Batch.Protocol.Models.FileListFromComputeNodeOptions fileListFromComputeNodeOptions) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.FileOperationsExtensions.ListFromComputeNode(Microsoft.Azure.Batch.Protocol.IFileOperations,System.String,System.String,System.Nullable{System.Boolean},Microsoft.Azure.Batch.Protocol.Models.FileListFromComputeNodeOptions)" />
      <MemberSignature Language="F#" Value="static member ListFromComputeNode : Microsoft.Azure.Batch.Protocol.IFileOperations * string * string * Nullable&lt;bool&gt; * Microsoft.Azure.Batch.Protocol.Models.FileListFromComputeNodeOptions -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Batch.Protocol.Models.NodeFile&gt;" Usage="Microsoft.Azure.Batch.Protocol.FileOperationsExtensions.ListFromComputeNode (operations, poolId, nodeId, recursive, fileListFromComputeNodeOptions)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Batch.Protocol.Models.NodeFile&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Batch.Protocol.IFileOperations" RefType="this" />
        <Parameter Name="poolId" Type="System.String" />
        <Parameter Name="nodeId" Type="System.String" />
        <Parameter Name="recursive" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="fileListFromComputeNodeOptions" Type="Microsoft.Azure.Batch.Protocol.Models.FileListFromComputeNodeOptions" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="poolId">
            Die ID des Pools, den Compute-Knoten enthält.
            </param>
        <param name="nodeId">
            Die ID des Serverknotens, deren Dateien, die Sie auflisten möchten.
            </param>
        <param name="recursive">
            Ob untergeordnete Elemente auflisten eines Verzeichnisses.
            </param>
        <param name="fileListFromComputeNodeOptions">
            Zusätzliche Parameter für den Vorgang
            </param>
        <summary>
            Zeigt eine Liste aller Dateien im Task-Verzeichnisse im angegebenen Serverknoten.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListFromComputeNodeAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Batch.Protocol.Models.NodeFile&gt;&gt; ListFromComputeNodeAsync (this Microsoft.Azure.Batch.Protocol.IFileOperations operations, string poolId, string nodeId, Nullable&lt;bool&gt; recursive = null, Microsoft.Azure.Batch.Protocol.Models.FileListFromComputeNodeOptions fileListFromComputeNodeOptions = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Batch.Protocol.Models.NodeFile&gt;&gt; ListFromComputeNodeAsync(class Microsoft.Azure.Batch.Protocol.IFileOperations operations, string poolId, string nodeId, valuetype System.Nullable`1&lt;bool&gt; recursive, class Microsoft.Azure.Batch.Protocol.Models.FileListFromComputeNodeOptions fileListFromComputeNodeOptions, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.FileOperationsExtensions.ListFromComputeNodeAsync(Microsoft.Azure.Batch.Protocol.IFileOperations,System.String,System.String,System.Nullable{System.Boolean},Microsoft.Azure.Batch.Protocol.Models.FileListFromComputeNodeOptions,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListFromComputeNodeAsync : Microsoft.Azure.Batch.Protocol.IFileOperations * string * string * Nullable&lt;bool&gt; * Microsoft.Azure.Batch.Protocol.Models.FileListFromComputeNodeOptions * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Batch.Protocol.Models.NodeFile&gt;&gt;" Usage="Microsoft.Azure.Batch.Protocol.FileOperationsExtensions.ListFromComputeNodeAsync (operations, poolId, nodeId, recursive, fileListFromComputeNodeOptions, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Batch.Protocol.FileOperationsExtensions/&lt;ListFromComputeNodeAsync&gt;d__15))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Batch.Protocol.Models.NodeFile&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Batch.Protocol.IFileOperations" RefType="this" />
        <Parameter Name="poolId" Type="System.String" />
        <Parameter Name="nodeId" Type="System.String" />
        <Parameter Name="recursive" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="fileListFromComputeNodeOptions" Type="Microsoft.Azure.Batch.Protocol.Models.FileListFromComputeNodeOptions" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="poolId">
            Die ID des Pools, den Compute-Knoten enthält.
            </param>
        <param name="nodeId">
            Die ID des Serverknotens, deren Dateien, die Sie auflisten möchten.
            </param>
        <param name="recursive">
            Ob untergeordnete Elemente auflisten eines Verzeichnisses.
            </param>
        <param name="fileListFromComputeNodeOptions">
            Zusätzliche Parameter für den Vorgang
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Zeigt eine Liste aller Dateien im Task-Verzeichnisse im angegebenen Serverknoten.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListFromComputeNodeNext">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Batch.Protocol.Models.NodeFile&gt; ListFromComputeNodeNext (this Microsoft.Azure.Batch.Protocol.IFileOperations operations, string nextPageLink, Microsoft.Azure.Batch.Protocol.Models.FileListFromComputeNodeNextOptions fileListFromComputeNodeNextOptions = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Batch.Protocol.Models.NodeFile&gt; ListFromComputeNodeNext(class Microsoft.Azure.Batch.Protocol.IFileOperations operations, string nextPageLink, class Microsoft.Azure.Batch.Protocol.Models.FileListFromComputeNodeNextOptions fileListFromComputeNodeNextOptions) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.FileOperationsExtensions.ListFromComputeNodeNext(Microsoft.Azure.Batch.Protocol.IFileOperations,System.String,Microsoft.Azure.Batch.Protocol.Models.FileListFromComputeNodeNextOptions)" />
      <MemberSignature Language="F#" Value="static member ListFromComputeNodeNext : Microsoft.Azure.Batch.Protocol.IFileOperations * string * Microsoft.Azure.Batch.Protocol.Models.FileListFromComputeNodeNextOptions -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Batch.Protocol.Models.NodeFile&gt;" Usage="Microsoft.Azure.Batch.Protocol.FileOperationsExtensions.ListFromComputeNodeNext (operations, nextPageLink, fileListFromComputeNodeNextOptions)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Batch.Protocol.Models.NodeFile&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Batch.Protocol.IFileOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="fileListFromComputeNodeNextOptions" Type="Microsoft.Azure.Batch.Protocol.Models.FileListFromComputeNodeNextOptions" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="nextPageLink">
            Die "NextLink" aus dem vorherigen erfolgreichen Aufruf List-Vorgangs.
            </param>
        <param name="fileListFromComputeNodeNextOptions">
            Zusätzliche Parameter für den Vorgang
            </param>
        <summary>
            Zeigt eine Liste aller Dateien im Task-Verzeichnisse im angegebenen Serverknoten.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListFromComputeNodeNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Batch.Protocol.Models.NodeFile&gt;&gt; ListFromComputeNodeNextAsync (this Microsoft.Azure.Batch.Protocol.IFileOperations operations, string nextPageLink, Microsoft.Azure.Batch.Protocol.Models.FileListFromComputeNodeNextOptions fileListFromComputeNodeNextOptions = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Batch.Protocol.Models.NodeFile&gt;&gt; ListFromComputeNodeNextAsync(class Microsoft.Azure.Batch.Protocol.IFileOperations operations, string nextPageLink, class Microsoft.Azure.Batch.Protocol.Models.FileListFromComputeNodeNextOptions fileListFromComputeNodeNextOptions, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.FileOperationsExtensions.ListFromComputeNodeNextAsync(Microsoft.Azure.Batch.Protocol.IFileOperations,System.String,Microsoft.Azure.Batch.Protocol.Models.FileListFromComputeNodeNextOptions,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListFromComputeNodeNextAsync : Microsoft.Azure.Batch.Protocol.IFileOperations * string * Microsoft.Azure.Batch.Protocol.Models.FileListFromComputeNodeNextOptions * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Batch.Protocol.Models.NodeFile&gt;&gt;" Usage="Microsoft.Azure.Batch.Protocol.FileOperationsExtensions.ListFromComputeNodeNextAsync (operations, nextPageLink, fileListFromComputeNodeNextOptions, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Batch.Protocol.FileOperationsExtensions/&lt;ListFromComputeNodeNextAsync&gt;d__19))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Batch.Protocol.Models.NodeFile&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Batch.Protocol.IFileOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="fileListFromComputeNodeNextOptions" Type="Microsoft.Azure.Batch.Protocol.Models.FileListFromComputeNodeNextOptions" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="nextPageLink">
            Die "NextLink" aus dem vorherigen erfolgreichen Aufruf List-Vorgangs.
            </param>
        <param name="fileListFromComputeNodeNextOptions">
            Zusätzliche Parameter für den Vorgang
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Zeigt eine Liste aller Dateien im Task-Verzeichnisse im angegebenen Serverknoten.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListFromTask">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Batch.Protocol.Models.NodeFile&gt; ListFromTask (this Microsoft.Azure.Batch.Protocol.IFileOperations operations, string jobId, string taskId, Nullable&lt;bool&gt; recursive = null, Microsoft.Azure.Batch.Protocol.Models.FileListFromTaskOptions fileListFromTaskOptions = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Batch.Protocol.Models.NodeFile&gt; ListFromTask(class Microsoft.Azure.Batch.Protocol.IFileOperations operations, string jobId, string taskId, valuetype System.Nullable`1&lt;bool&gt; recursive, class Microsoft.Azure.Batch.Protocol.Models.FileListFromTaskOptions fileListFromTaskOptions) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.FileOperationsExtensions.ListFromTask(Microsoft.Azure.Batch.Protocol.IFileOperations,System.String,System.String,System.Nullable{System.Boolean},Microsoft.Azure.Batch.Protocol.Models.FileListFromTaskOptions)" />
      <MemberSignature Language="F#" Value="static member ListFromTask : Microsoft.Azure.Batch.Protocol.IFileOperations * string * string * Nullable&lt;bool&gt; * Microsoft.Azure.Batch.Protocol.Models.FileListFromTaskOptions -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Batch.Protocol.Models.NodeFile&gt;" Usage="Microsoft.Azure.Batch.Protocol.FileOperationsExtensions.ListFromTask (operations, jobId, taskId, recursive, fileListFromTaskOptions)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Batch.Protocol.Models.NodeFile&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Batch.Protocol.IFileOperations" RefType="this" />
        <Parameter Name="jobId" Type="System.String" />
        <Parameter Name="taskId" Type="System.String" />
        <Parameter Name="recursive" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="fileListFromTaskOptions" Type="Microsoft.Azure.Batch.Protocol.Models.FileListFromTaskOptions" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="jobId">
            Die ID des Auftrags, der den Task enthält.
            </param>
        <param name="taskId">
            Die ID der Aufgabe, deren Dateien, die Sie auflisten möchten.
            </param>
        <param name="recursive">
            Ob untergeordnete Elemente auflisten des Verzeichnisses Aufgabe. Dieser Parameter kann in Kombination mit dem Filterparameter, um die Liste bestimmte Typen von Dateien verwendet werden.
            </param>
        <param name="fileListFromTaskOptions">
            Zusätzliche Parameter für den Vorgang
            </param>
        <summary>
            Listet die Dateien im Verzeichnis für eine Aufgabe auf seine Computeknoten.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListFromTaskAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Batch.Protocol.Models.NodeFile&gt;&gt; ListFromTaskAsync (this Microsoft.Azure.Batch.Protocol.IFileOperations operations, string jobId, string taskId, Nullable&lt;bool&gt; recursive = null, Microsoft.Azure.Batch.Protocol.Models.FileListFromTaskOptions fileListFromTaskOptions = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Batch.Protocol.Models.NodeFile&gt;&gt; ListFromTaskAsync(class Microsoft.Azure.Batch.Protocol.IFileOperations operations, string jobId, string taskId, valuetype System.Nullable`1&lt;bool&gt; recursive, class Microsoft.Azure.Batch.Protocol.Models.FileListFromTaskOptions fileListFromTaskOptions, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.FileOperationsExtensions.ListFromTaskAsync(Microsoft.Azure.Batch.Protocol.IFileOperations,System.String,System.String,System.Nullable{System.Boolean},Microsoft.Azure.Batch.Protocol.Models.FileListFromTaskOptions,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListFromTaskAsync : Microsoft.Azure.Batch.Protocol.IFileOperations * string * string * Nullable&lt;bool&gt; * Microsoft.Azure.Batch.Protocol.Models.FileListFromTaskOptions * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Batch.Protocol.Models.NodeFile&gt;&gt;" Usage="Microsoft.Azure.Batch.Protocol.FileOperationsExtensions.ListFromTaskAsync (operations, jobId, taskId, recursive, fileListFromTaskOptions, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Batch.Protocol.FileOperationsExtensions/&lt;ListFromTaskAsync&gt;d__13))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Batch.Protocol.Models.NodeFile&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Batch.Protocol.IFileOperations" RefType="this" />
        <Parameter Name="jobId" Type="System.String" />
        <Parameter Name="taskId" Type="System.String" />
        <Parameter Name="recursive" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="fileListFromTaskOptions" Type="Microsoft.Azure.Batch.Protocol.Models.FileListFromTaskOptions" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="jobId">
            Die ID des Auftrags, der den Task enthält.
            </param>
        <param name="taskId">
            Die ID der Aufgabe, deren Dateien, die Sie auflisten möchten.
            </param>
        <param name="recursive">
            Ob untergeordnete Elemente auflisten des Verzeichnisses Aufgabe. Dieser Parameter kann in Kombination mit dem Filterparameter, um die Liste bestimmte Typen von Dateien verwendet werden.
            </param>
        <param name="fileListFromTaskOptions">
            Zusätzliche Parameter für den Vorgang
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Listet die Dateien im Verzeichnis für eine Aufgabe auf seine Computeknoten.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListFromTaskNext">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Batch.Protocol.Models.NodeFile&gt; ListFromTaskNext (this Microsoft.Azure.Batch.Protocol.IFileOperations operations, string nextPageLink, Microsoft.Azure.Batch.Protocol.Models.FileListFromTaskNextOptions fileListFromTaskNextOptions = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Batch.Protocol.Models.NodeFile&gt; ListFromTaskNext(class Microsoft.Azure.Batch.Protocol.IFileOperations operations, string nextPageLink, class Microsoft.Azure.Batch.Protocol.Models.FileListFromTaskNextOptions fileListFromTaskNextOptions) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.FileOperationsExtensions.ListFromTaskNext(Microsoft.Azure.Batch.Protocol.IFileOperations,System.String,Microsoft.Azure.Batch.Protocol.Models.FileListFromTaskNextOptions)" />
      <MemberSignature Language="F#" Value="static member ListFromTaskNext : Microsoft.Azure.Batch.Protocol.IFileOperations * string * Microsoft.Azure.Batch.Protocol.Models.FileListFromTaskNextOptions -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Batch.Protocol.Models.NodeFile&gt;" Usage="Microsoft.Azure.Batch.Protocol.FileOperationsExtensions.ListFromTaskNext (operations, nextPageLink, fileListFromTaskNextOptions)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Batch.Protocol.Models.NodeFile&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Batch.Protocol.IFileOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="fileListFromTaskNextOptions" Type="Microsoft.Azure.Batch.Protocol.Models.FileListFromTaskNextOptions" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="nextPageLink">
            Die "NextLink" aus dem vorherigen erfolgreichen Aufruf List-Vorgangs.
            </param>
        <param name="fileListFromTaskNextOptions">
            Zusätzliche Parameter für den Vorgang
            </param>
        <summary>
            Listet die Dateien im Verzeichnis für eine Aufgabe auf seine Computeknoten.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListFromTaskNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Batch.Protocol.Models.NodeFile&gt;&gt; ListFromTaskNextAsync (this Microsoft.Azure.Batch.Protocol.IFileOperations operations, string nextPageLink, Microsoft.Azure.Batch.Protocol.Models.FileListFromTaskNextOptions fileListFromTaskNextOptions = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Batch.Protocol.Models.NodeFile&gt;&gt; ListFromTaskNextAsync(class Microsoft.Azure.Batch.Protocol.IFileOperations operations, string nextPageLink, class Microsoft.Azure.Batch.Protocol.Models.FileListFromTaskNextOptions fileListFromTaskNextOptions, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.FileOperationsExtensions.ListFromTaskNextAsync(Microsoft.Azure.Batch.Protocol.IFileOperations,System.String,Microsoft.Azure.Batch.Protocol.Models.FileListFromTaskNextOptions,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListFromTaskNextAsync : Microsoft.Azure.Batch.Protocol.IFileOperations * string * Microsoft.Azure.Batch.Protocol.Models.FileListFromTaskNextOptions * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Batch.Protocol.Models.NodeFile&gt;&gt;" Usage="Microsoft.Azure.Batch.Protocol.FileOperationsExtensions.ListFromTaskNextAsync (operations, nextPageLink, fileListFromTaskNextOptions, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Batch.Protocol.FileOperationsExtensions/&lt;ListFromTaskNextAsync&gt;d__17))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Batch.Protocol.Models.NodeFile&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Batch.Protocol.IFileOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="fileListFromTaskNextOptions" Type="Microsoft.Azure.Batch.Protocol.Models.FileListFromTaskNextOptions" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="nextPageLink">
            Die "NextLink" aus dem vorherigen erfolgreichen Aufruf List-Vorgangs.
            </param>
        <param name="fileListFromTaskNextOptions">
            Zusätzliche Parameter für den Vorgang
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Listet die Dateien im Verzeichnis für eine Aufgabe auf seine Computeknoten.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>