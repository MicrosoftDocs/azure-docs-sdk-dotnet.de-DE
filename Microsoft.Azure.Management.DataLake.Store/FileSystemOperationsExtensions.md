<Type Name="FileSystemOperationsExtensions" FullName="Microsoft.Azure.Management.DataLake.Store.FileSystemOperationsExtensions">
  <TypeSignature Language="C#" Value="public static class FileSystemOperationsExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit FileSystemOperationsExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.DataLake.Store.FileSystemOperationsExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module FileSystemOperationsExtensions" />
  <TypeSignature Language="F#" Value="type FileSystemOperationsExtensions = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.DataLake.Store</AssemblyName>
    <AssemblyVersion>2.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            Erweiterungsmethoden für FileSystemOperations.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="Append">
      <MemberSignature Language="C#" Value="public static void Append (this Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations operations, string accountName, string path, System.IO.Stream streamContents, Nullable&lt;long&gt; offset = null, Nullable&lt;Microsoft.Azure.Management.DataLake.Store.Models.SyncFlag&gt; syncFlag = null, Nullable&lt;Guid&gt; leaseId = null, Nullable&lt;Guid&gt; fileSessionId = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void Append(class Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations operations, string accountName, string path, class System.IO.Stream streamContents, valuetype System.Nullable`1&lt;int64&gt; offset, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.DataLake.Store.Models.SyncFlag&gt; syncFlag, valuetype System.Nullable`1&lt;valuetype System.Guid&gt; leaseId, valuetype System.Nullable`1&lt;valuetype System.Guid&gt; fileSessionId) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Store.FileSystemOperationsExtensions.Append(Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations,System.String,System.String,System.IO.Stream,System.Nullable{System.Int64},System.Nullable{Microsoft.Azure.Management.DataLake.Store.Models.SyncFlag},System.Nullable{System.Guid},System.Nullable{System.Guid})" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Sub Append (operations As IFileSystemOperations, accountName As String, path As String, streamContents As Stream, Optional offset As Nullable(Of Long) = null, Optional syncFlag As Nullable(Of SyncFlag) = null, Optional leaseId As Nullable(Of Guid) = null, Optional fileSessionId As Nullable(Of Guid) = null)" />
      <MemberSignature Language="F#" Value="static member Append : Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations * string * string * System.IO.Stream * Nullable&lt;int64&gt; * Nullable&lt;Microsoft.Azure.Management.DataLake.Store.Models.SyncFlag&gt; * Nullable&lt;Guid&gt; * Nullable&lt;Guid&gt; -&gt; unit" Usage="Microsoft.Azure.Management.DataLake.Store.FileSystemOperationsExtensions.Append (operations, accountName, path, streamContents, offset, syncFlag, leaseId, fileSessionId)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Store</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations" RefType="this" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="path" Type="System.String" />
        <Parameter Name="streamContents" Type="System.IO.Stream" />
        <Parameter Name="offset" Type="System.Nullable&lt;System.Int64&gt;" />
        <Parameter Name="syncFlag" Type="System.Nullable&lt;Microsoft.Azure.Management.DataLake.Store.Models.SyncFlag&gt;" />
        <Parameter Name="leaseId" Type="System.Nullable&lt;System.Guid&gt;" />
        <Parameter Name="fileSessionId" Type="System.Nullable&lt;System.Guid&gt;" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="accountName">
            Das Azure Data Lake-Speicher-Konto zum Ausführen der Filesystem-Vorgänge auf.
            </param>
        <param name="path">
            Der Pfad des Data Lake-Speicher (beginnend mit '/') der Datei, die angefügt werden soll.
            </param>
        <param name="streamContents">
            Der Inhalt der Datei einschließen, wenn Sie auf die Datei anfügen.
            </param>
        <param name="offset">
            Der optionale Offset in den Stream den Anfügevorgang zu beginnen. Standardmäßig werden am Ende des Streams angefügt werden soll.
            </param>
        <param name="syncFlag">
            Optional gibt an, was nach Abschluss der gleichzeitigen anfügen.
            Daten angeben, dass mehr Daten sofort vom Client gesendet werden werden, das Dateihandle, Open/gesperrt verbleiben sollte und Dateimetadaten (einschließlich Dateilänge, Uhrzeit der letzten Änderung) sollten nicht aktualisiert. Metadaten gibt an, dass mehr Daten sofort vom Client gesendet werden werden, das Dateihandle, Open/gesperrt verbleiben sollte und Dateimetadaten sollte aktualisiert. Schließen gibt an, dass der Client sendende von Daten erfolgt und das Dateihandle geschlossen/entsperrt muss Dateimetadaten sollte aktualisiert. Folgende Werte sind möglich: "Daten", "Metadaten", "Schließen"
            </param>
        <param name="leaseId">
            Optionale eindeutige GUID pro Datei an, um einzelne Writer-Semantik, was bedeutet, dass nur Clients, die an die Datei mit der gleichen LeaseId anfügen dazu berechtigt sein, sicherzustellen.
            </param>
        <param name="fileSessionId">
            Optionale eindeutige GUID pro Datei, die alle angibt, die mit dem gleichen fügt FileSessionId werden aus dem gleichen Client und der gleichen Sitzung. Dadurch erhalten einen Leistungsvorteil, wenn SyncFlag Daten oder Metadaten ist.
            </param>
        <summary>
            Verwendet für Serial an die angegebene Datei angefügt. Hinweis: Das Ziel darf nicht von ConcurrentAppend hinzugefügte Daten. ConcurrentAppend und anfügen kann synonym verwendet werden. Sobald eine Zieldatei geändert wurde mit einer von beiden Optionen anfügen, die Append-Option kann nicht auf die Zieldatei nicht verwendet werden.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AppendAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task AppendAsync (this Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations operations, string accountName, string path, System.IO.Stream streamContents, Nullable&lt;long&gt; offset = null, Nullable&lt;Microsoft.Azure.Management.DataLake.Store.Models.SyncFlag&gt; syncFlag = null, Nullable&lt;Guid&gt; leaseId = null, Nullable&lt;Guid&gt; fileSessionId = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task AppendAsync(class Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations operations, string accountName, string path, class System.IO.Stream streamContents, valuetype System.Nullable`1&lt;int64&gt; offset, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.DataLake.Store.Models.SyncFlag&gt; syncFlag, valuetype System.Nullable`1&lt;valuetype System.Guid&gt; leaseId, valuetype System.Nullable`1&lt;valuetype System.Guid&gt; fileSessionId, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Store.FileSystemOperationsExtensions.AppendAsync(Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations,System.String,System.String,System.IO.Stream,System.Nullable{System.Int64},System.Nullable{Microsoft.Azure.Management.DataLake.Store.Models.SyncFlag},System.Nullable{System.Guid},System.Nullable{System.Guid},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member AppendAsync : Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations * string * string * System.IO.Stream * Nullable&lt;int64&gt; * Nullable&lt;Microsoft.Azure.Management.DataLake.Store.Models.SyncFlag&gt; * Nullable&lt;Guid&gt; * Nullable&lt;Guid&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.DataLake.Store.FileSystemOperationsExtensions.AppendAsync (operations, accountName, path, streamContents, offset, syncFlag, leaseId, fileSessionId, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Store</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.DataLake.Store.FileSystemOperationsExtensions/&lt;AppendAsync&gt;d__23))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations" RefType="this" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="path" Type="System.String" />
        <Parameter Name="streamContents" Type="System.IO.Stream" />
        <Parameter Name="offset" Type="System.Nullable&lt;System.Int64&gt;" />
        <Parameter Name="syncFlag" Type="System.Nullable&lt;Microsoft.Azure.Management.DataLake.Store.Models.SyncFlag&gt;" />
        <Parameter Name="leaseId" Type="System.Nullable&lt;System.Guid&gt;" />
        <Parameter Name="fileSessionId" Type="System.Nullable&lt;System.Guid&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="accountName">
            Das Azure Data Lake-Speicher-Konto zum Ausführen der Filesystem-Vorgänge auf.
            </param>
        <param name="path">
            Der Pfad des Data Lake-Speicher (beginnend mit '/') der Datei, die angefügt werden soll.
            </param>
        <param name="streamContents">
            Der Inhalt der Datei einschließen, wenn Sie auf die Datei anfügen.
            </param>
        <param name="offset">
            Der optionale Offset in den Stream den Anfügevorgang zu beginnen. Standardmäßig werden am Ende des Streams angefügt werden soll.
            </param>
        <param name="syncFlag">
            Optional gibt an, was nach Abschluss der gleichzeitigen anfügen.
            Daten angeben, dass mehr Daten sofort vom Client gesendet werden werden, das Dateihandle, Open/gesperrt verbleiben sollte und Dateimetadaten (einschließlich Dateilänge, Uhrzeit der letzten Änderung) sollten nicht aktualisiert. Metadaten gibt an, dass mehr Daten sofort vom Client gesendet werden werden, das Dateihandle, Open/gesperrt verbleiben sollte und Dateimetadaten sollte aktualisiert. Schließen gibt an, dass der Client sendende von Daten erfolgt und das Dateihandle geschlossen/entsperrt muss Dateimetadaten sollte aktualisiert. Folgende Werte sind möglich: "Daten", "Metadaten", "Schließen"
            </param>
        <param name="leaseId">
            Optionale eindeutige GUID pro Datei an, um einzelne Writer-Semantik, was bedeutet, dass nur Clients, die an die Datei mit der gleichen LeaseId anfügen dazu berechtigt sein, sicherzustellen.
            </param>
        <param name="fileSessionId">
            Optionale eindeutige GUID pro Datei, die alle angibt, die mit dem gleichen fügt FileSessionId werden aus dem gleichen Client und der gleichen Sitzung. Dadurch erhalten einen Leistungsvorteil, wenn SyncFlag Daten oder Metadaten ist.
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Verwendet für Serial an die angegebene Datei angefügt. Hinweis: Das Ziel darf nicht von ConcurrentAppend hinzugefügte Daten. ConcurrentAppend und anfügen kann synonym verwendet werden. Sobald eine Zieldatei geändert wurde mit einer von beiden Optionen anfügen, die Append-Option kann nicht auf die Zieldatei nicht verwendet werden.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CheckAccess">
      <MemberSignature Language="C#" Value="public static void CheckAccess (this Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations operations, string accountName, string path, string fsaction);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void CheckAccess(class Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations operations, string accountName, string path, string fsaction) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Store.FileSystemOperationsExtensions.CheckAccess(Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Sub CheckAccess (operations As IFileSystemOperations, accountName As String, path As String, fsaction As String)" />
      <MemberSignature Language="F#" Value="static member CheckAccess : Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations * string * string * string -&gt; unit" Usage="Microsoft.Azure.Management.DataLake.Store.FileSystemOperationsExtensions.CheckAccess (operations, accountName, path, fsaction)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Store</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations" RefType="this" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="path" Type="System.String" />
        <Parameter Name="fsaction" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="accountName">
            Das Azure Data Lake-Speicher-Konto zum Ausführen der Filesystem-Vorgänge auf.
            </param>
        <param name="path">
            Der Pfad des Data Lake-Speicher (beginnend mit '/') der Datei oder des Verzeichnisses für den Zugriff zu überprüfen.
            </param>
        <param name="fsaction">
            In Form einer Zeichenfolge, übereinstimmende Regex-Muster System Vorgang Lese-/Schreib-/ausführungs-als Datei "[Rwx-] \ {3\}"
            </param>
        <summary>
            Überprüft, ob der angegebene Zugriff im angegebenen Pfad verfügbar ist.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CheckAccessAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task CheckAccessAsync (this Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations operations, string accountName, string path, string fsaction, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task CheckAccessAsync(class Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations operations, string accountName, string path, string fsaction, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Store.FileSystemOperationsExtensions.CheckAccessAsync(Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member CheckAccessAsync : Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.DataLake.Store.FileSystemOperationsExtensions.CheckAccessAsync (operations, accountName, path, fsaction, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Store</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.DataLake.Store.FileSystemOperationsExtensions/&lt;CheckAccessAsync&gt;d__7))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations" RefType="this" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="path" Type="System.String" />
        <Parameter Name="fsaction" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="accountName">
            Das Azure Data Lake-Speicher-Konto zum Ausführen der Filesystem-Vorgänge auf.
            </param>
        <param name="path">
            Der Pfad des Data Lake-Speicher (beginnend mit '/') der Datei oder des Verzeichnisses für den Zugriff zu überprüfen.
            </param>
        <param name="fsaction">
            In Form einer Zeichenfolge, übereinstimmende Regex-Muster System Vorgang Lese-/Schreib-/ausführungs-als Datei "[Rwx-] \ {3\}"
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Überprüft, ob der angegebene Zugriff im angegebenen Pfad verfügbar ist.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Concat">
      <MemberSignature Language="C#" Value="public static void Concat (this Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations operations, string accountName, string path, System.Collections.Generic.IList&lt;string&gt; sources);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void Concat(class Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations operations, string accountName, string path, class System.Collections.Generic.IList`1&lt;string&gt; sources) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Store.FileSystemOperationsExtensions.Concat(Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations,System.String,System.String,System.Collections.Generic.IList{System.String})" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Sub Concat (operations As IFileSystemOperations, accountName As String, path As String, sources As IList(Of String))" />
      <MemberSignature Language="F#" Value="static member Concat : Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations * string * string * System.Collections.Generic.IList&lt;string&gt; -&gt; unit" Usage="Microsoft.Azure.Management.DataLake.Store.FileSystemOperationsExtensions.Concat (operations, accountName, path, sources)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Store</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations" RefType="this" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="path" Type="System.String" />
        <Parameter Name="sources" Type="System.Collections.Generic.IList&lt;System.String&gt;" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="accountName">
            Das Azure Data Lake-Speicher-Konto zum Ausführen der Filesystem-Vorgänge auf.
            </param>
        <param name="path">
            Der Pfad des Data Lake-Speicher (beginnend mit '/') der Zieldatei, die sich aus der Verkettung ergibt.
            </param>
        <param name="sources">
            Eine Liste von durch Trennzeichen getrennt Data Lake-Speicher-Pfade (beginnend mit '/') der Dateien, die in der Reihenfolge verkettet, in dem sie verkettet werden soll.
            </param>
        <summary>
            Verkettet die Liste der Quelldateien in der Zieldatei, die alle Quelldateien bei Erfolg wird entfernt.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ConcatAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task ConcatAsync (this Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations operations, string accountName, string path, System.Collections.Generic.IList&lt;string&gt; sources, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task ConcatAsync(class Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations operations, string accountName, string path, class System.Collections.Generic.IList`1&lt;string&gt; sources, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Store.FileSystemOperationsExtensions.ConcatAsync(Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations,System.String,System.String,System.Collections.Generic.IList{System.String},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ConcatAsync : Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations * string * string * System.Collections.Generic.IList&lt;string&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.DataLake.Store.FileSystemOperationsExtensions.ConcatAsync (operations, accountName, path, sources, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Store</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.DataLake.Store.FileSystemOperationsExtensions/&lt;ConcatAsync&gt;d__11))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations" RefType="this" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="path" Type="System.String" />
        <Parameter Name="sources" Type="System.Collections.Generic.IList&lt;System.String&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="accountName">
            Das Azure Data Lake-Speicher-Konto zum Ausführen der Filesystem-Vorgänge auf.
            </param>
        <param name="path">
            Der Pfad des Data Lake-Speicher (beginnend mit '/') der Zieldatei, die sich aus der Verkettung ergibt.
            </param>
        <param name="sources">
            Eine Liste von durch Trennzeichen getrennt Data Lake-Speicher-Pfade (beginnend mit '/') der Dateien, die in der Reihenfolge verkettet, in dem sie verkettet werden soll.
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Verkettet die Liste der Quelldateien in der Zieldatei, die alle Quelldateien bei Erfolg wird entfernt.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ConcurrentAppend">
      <MemberSignature Language="C#" Value="public static void ConcurrentAppend (this Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations operations, string accountName, string path, System.IO.Stream streamContents, Nullable&lt;Microsoft.Azure.Management.DataLake.Store.Models.AppendModeType&gt; appendMode = null, Nullable&lt;Microsoft.Azure.Management.DataLake.Store.Models.SyncFlag&gt; syncFlag = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void ConcurrentAppend(class Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations operations, string accountName, string path, class System.IO.Stream streamContents, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.DataLake.Store.Models.AppendModeType&gt; appendMode, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.DataLake.Store.Models.SyncFlag&gt; syncFlag) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Store.FileSystemOperationsExtensions.ConcurrentAppend(Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations,System.String,System.String,System.IO.Stream,System.Nullable{Microsoft.Azure.Management.DataLake.Store.Models.AppendModeType},System.Nullable{Microsoft.Azure.Management.DataLake.Store.Models.SyncFlag})" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Sub ConcurrentAppend (operations As IFileSystemOperations, accountName As String, path As String, streamContents As Stream, Optional appendMode As Nullable(Of AppendModeType) = null, Optional syncFlag As Nullable(Of SyncFlag) = null)" />
      <MemberSignature Language="F#" Value="static member ConcurrentAppend : Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations * string * string * System.IO.Stream * Nullable&lt;Microsoft.Azure.Management.DataLake.Store.Models.AppendModeType&gt; * Nullable&lt;Microsoft.Azure.Management.DataLake.Store.Models.SyncFlag&gt; -&gt; unit" Usage="Microsoft.Azure.Management.DataLake.Store.FileSystemOperationsExtensions.ConcurrentAppend (operations, accountName, path, streamContents, appendMode, syncFlag)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Store</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations" RefType="this" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="path" Type="System.String" />
        <Parameter Name="streamContents" Type="System.IO.Stream" />
        <Parameter Name="appendMode" Type="System.Nullable&lt;Microsoft.Azure.Management.DataLake.Store.Models.AppendModeType&gt;" />
        <Parameter Name="syncFlag" Type="System.Nullable&lt;Microsoft.Azure.Management.DataLake.Store.Models.SyncFlag&gt;" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="accountName">
            Das Azure Data Lake-Speicher-Konto zum Ausführen der Filesystem-Vorgänge auf.
            </param>
        <param name="path">
            Der Pfad des Data Lake-Speicher (beginnend mit '/') der Datei an die anzufügende mithilfe von gleichzeitiger angefügt werden soll.
            </param>
        <param name="streamContents">
            Der Inhalt der Datei einschließen, wenn Sie auf die Datei anfügen.
            </param>
        <param name="appendMode">
            Gibt an, dass der Aufruf gleichzeitige anfügen die Datei erstellen soll, wenn sie nicht vorhanden, oder öffnen Sie einfach die vorhandene Datei zum Anhängen. Folgende Werte sind möglich: "automatisch erstellen"
            </param>
        <param name="syncFlag">
            Optional gibt an, was nach Abschluss der gleichzeitigen anfügen.
            Daten angeben, dass mehr Daten sofort vom Client gesendet werden werden, das Dateihandle, Open/gesperrt verbleiben sollte und Dateimetadaten (einschließlich Dateilänge, Uhrzeit der letzten Änderung) sollten nicht aktualisiert. Metadaten gibt an, dass mehr Daten sofort vom Client gesendet werden werden, das Dateihandle, Open/gesperrt verbleiben sollte und Dateimetadaten sollte aktualisiert. Schließen gibt an, dass der Client sendende von Daten erfolgt und das Dateihandle geschlossen/entsperrt muss Dateimetadaten sollte aktualisiert. Folgende Werte sind möglich: "Daten", "Metadaten", "Schließen"
            </param>
        <summary>
            Fügt an die angegebene Datei und optional die Datei erstmalig erstellen, wenn sie noch nicht vorhanden ist. Diese Methode unterstützt mehrere gleichzeitige an die Datei angefügt. Hinweis: Das Ziel darf nicht von CREATE- oder normale (seriell) anfügen hinzugefügte Daten. ConcurrentAppend und anfügen kann synonym verwendet werden. Sobald eine Zieldatei geändert wurde mit einer von beiden Optionen anfügen, die Append-Option kann nicht auf die Zieldatei nicht verwendet werden.
            ConcurrentAppend garantiert nicht die Reihenfolge und doppelt vorhandenen Daten in der Zieldatei landing zu kann.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ConcurrentAppendAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task ConcurrentAppendAsync (this Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations operations, string accountName, string path, System.IO.Stream streamContents, Nullable&lt;Microsoft.Azure.Management.DataLake.Store.Models.AppendModeType&gt; appendMode = null, Nullable&lt;Microsoft.Azure.Management.DataLake.Store.Models.SyncFlag&gt; syncFlag = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task ConcurrentAppendAsync(class Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations operations, string accountName, string path, class System.IO.Stream streamContents, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.DataLake.Store.Models.AppendModeType&gt; appendMode, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.DataLake.Store.Models.SyncFlag&gt; syncFlag, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Store.FileSystemOperationsExtensions.ConcurrentAppendAsync(Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations,System.String,System.String,System.IO.Stream,System.Nullable{Microsoft.Azure.Management.DataLake.Store.Models.AppendModeType},System.Nullable{Microsoft.Azure.Management.DataLake.Store.Models.SyncFlag},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ConcurrentAppendAsync : Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations * string * string * System.IO.Stream * Nullable&lt;Microsoft.Azure.Management.DataLake.Store.Models.AppendModeType&gt; * Nullable&lt;Microsoft.Azure.Management.DataLake.Store.Models.SyncFlag&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.DataLake.Store.FileSystemOperationsExtensions.ConcurrentAppendAsync (operations, accountName, path, streamContents, appendMode, syncFlag, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Store</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.DataLake.Store.FileSystemOperationsExtensions/&lt;ConcurrentAppendAsync&gt;d__5))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations" RefType="this" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="path" Type="System.String" />
        <Parameter Name="streamContents" Type="System.IO.Stream" />
        <Parameter Name="appendMode" Type="System.Nullable&lt;Microsoft.Azure.Management.DataLake.Store.Models.AppendModeType&gt;" />
        <Parameter Name="syncFlag" Type="System.Nullable&lt;Microsoft.Azure.Management.DataLake.Store.Models.SyncFlag&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="accountName">
            Das Azure Data Lake-Speicher-Konto zum Ausführen der Filesystem-Vorgänge auf.
            </param>
        <param name="path">
            Der Pfad des Data Lake-Speicher (beginnend mit '/') der Datei an die anzufügende mithilfe von gleichzeitiger angefügt werden soll.
            </param>
        <param name="streamContents">
            Der Inhalt der Datei einschließen, wenn Sie auf die Datei anfügen.
            </param>
        <param name="appendMode">
            Gibt an, dass der Aufruf gleichzeitige anfügen die Datei erstellen soll, wenn sie nicht vorhanden, oder öffnen Sie einfach die vorhandene Datei zum Anhängen. Folgende Werte sind möglich: "automatisch erstellen"
            </param>
        <param name="syncFlag">
            Optional gibt an, was nach Abschluss der gleichzeitigen anfügen.
            Daten angeben, dass mehr Daten sofort vom Client gesendet werden werden, das Dateihandle, Open/gesperrt verbleiben sollte und Dateimetadaten (einschließlich Dateilänge, Uhrzeit der letzten Änderung) sollten nicht aktualisiert. Metadaten gibt an, dass mehr Daten sofort vom Client gesendet werden werden, das Dateihandle, Open/gesperrt verbleiben sollte und Dateimetadaten sollte aktualisiert. Schließen gibt an, dass der Client sendende von Daten erfolgt und das Dateihandle geschlossen/entsperrt muss Dateimetadaten sollte aktualisiert. Folgende Werte sind möglich: "Daten", "Metadaten", "Schließen"
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Fügt an die angegebene Datei und optional die Datei erstmalig erstellen, wenn sie noch nicht vorhanden ist. Diese Methode unterstützt mehrere gleichzeitige an die Datei angefügt. Hinweis: Das Ziel darf nicht von CREATE- oder normale (seriell) anfügen hinzugefügte Daten. ConcurrentAppend und anfügen kann synonym verwendet werden. Sobald eine Zieldatei geändert wurde mit einer von beiden Optionen anfügen, die Append-Option kann nicht auf die Zieldatei nicht verwendet werden.
            ConcurrentAppend garantiert nicht die Reihenfolge und doppelt vorhandenen Daten in der Zieldatei landing zu kann.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Create">
      <MemberSignature Language="C#" Value="public static void Create (this Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations operations, string accountName, string path, System.IO.Stream streamContents = null, Nullable&lt;bool&gt; overwrite = null, Nullable&lt;Microsoft.Azure.Management.DataLake.Store.Models.SyncFlag&gt; syncFlag = null, Nullable&lt;Guid&gt; leaseId = null, Nullable&lt;int&gt; permission = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void Create(class Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations operations, string accountName, string path, class System.IO.Stream streamContents, valuetype System.Nullable`1&lt;bool&gt; overwrite, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.DataLake.Store.Models.SyncFlag&gt; syncFlag, valuetype System.Nullable`1&lt;valuetype System.Guid&gt; leaseId, valuetype System.Nullable`1&lt;int32&gt; permission) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Store.FileSystemOperationsExtensions.Create(Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations,System.String,System.String,System.IO.Stream,System.Nullable{System.Boolean},System.Nullable{Microsoft.Azure.Management.DataLake.Store.Models.SyncFlag},System.Nullable{System.Guid},System.Nullable{System.Int32})" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Sub Create (operations As IFileSystemOperations, accountName As String, path As String, Optional streamContents As Stream = null, Optional overwrite As Nullable(Of Boolean) = null, Optional syncFlag As Nullable(Of SyncFlag) = null, Optional leaseId As Nullable(Of Guid) = null, Optional permission As Nullable(Of Integer) = null)" />
      <MemberSignature Language="F#" Value="static member Create : Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations * string * string * System.IO.Stream * Nullable&lt;bool&gt; * Nullable&lt;Microsoft.Azure.Management.DataLake.Store.Models.SyncFlag&gt; * Nullable&lt;Guid&gt; * Nullable&lt;int&gt; -&gt; unit" Usage="Microsoft.Azure.Management.DataLake.Store.FileSystemOperationsExtensions.Create (operations, accountName, path, streamContents, overwrite, syncFlag, leaseId, permission)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Store</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations" RefType="this" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="path" Type="System.String" />
        <Parameter Name="streamContents" Type="System.IO.Stream" />
        <Parameter Name="overwrite" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="syncFlag" Type="System.Nullable&lt;Microsoft.Azure.Management.DataLake.Store.Models.SyncFlag&gt;" />
        <Parameter Name="leaseId" Type="System.Nullable&lt;System.Guid&gt;" />
        <Parameter Name="permission" Type="System.Nullable&lt;System.Int32&gt;" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="accountName">
            Das Azure Data Lake-Speicher-Konto zum Ausführen der Filesystem-Vorgänge auf.
            </param>
        <param name="path">
            Der Pfad des Data Lake-Speicher (beginnend mit '/') der zu erstellenden Datei.
            </param>
        <param name="streamContents">
            Der Inhalt der Datei beim Erstellen der Datei werden sollen. Dieser Parameter ist optional, was in eine leere Datei, wenn nicht angegeben.
            </param>
        <param name="overwrite">
            Angabe darüber zurück, wenn die Datei überschrieben werden sollte.
            </param>
        <param name="syncFlag">
            Optional gibt an, was nach Abschluss des erstellen. Daten angeben, dass mehr Daten sofort vom Client gesendet werden werden, das Dateihandle, Open/gesperrt verbleiben sollte und Dateimetadaten (einschließlich Dateilänge, Uhrzeit der letzten Änderung) sollten nicht aktualisiert. Metadaten gibt an, dass mehr Daten sofort vom Client gesendet werden werden, das Dateihandle, Open/gesperrt verbleiben sollte und Dateimetadaten sollte aktualisiert. Schließen gibt an, dass der Client sendende von Daten erfolgt und das Dateihandle geschlossen/entsperrt muss Dateimetadaten sollte aktualisiert. Folgende Werte sind möglich: "Daten", "Metadaten", "Schließen"
            </param>
        <param name="leaseId">
            Optionale eindeutige GUID pro Datei an, um einzelne Writer-Semantik, was bedeutet, dass nur Clients, die an die Datei mit der gleichen LeaseId anfügen dazu berechtigt sein, sicherzustellen.
            </param>
        <param name="permission">
            Die oktale Darstellung der unbenannten Benutzer, Subnetzmaske und andere Berechtigungen, die für die Datei, die beim Erstellen festgelegt werden soll. Wenn nicht angegeben ist, erbt er diese aus dem Container.
            </param>
        <summary>
            Erstellt eine Datei mit den optional angegebenen Inhalt. Hinweis: Wenn Inhalte bereitgestellt wird, kann die resultierende Datei geändert werden ConcurrentAppend verwenden.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task CreateAsync (this Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations operations, string accountName, string path, System.IO.Stream streamContents = null, Nullable&lt;bool&gt; overwrite = null, Nullable&lt;Microsoft.Azure.Management.DataLake.Store.Models.SyncFlag&gt; syncFlag = null, Nullable&lt;Guid&gt; leaseId = null, Nullable&lt;int&gt; permission = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task CreateAsync(class Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations operations, string accountName, string path, class System.IO.Stream streamContents, valuetype System.Nullable`1&lt;bool&gt; overwrite, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.DataLake.Store.Models.SyncFlag&gt; syncFlag, valuetype System.Nullable`1&lt;valuetype System.Guid&gt; leaseId, valuetype System.Nullable`1&lt;int32&gt; permission, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Store.FileSystemOperationsExtensions.CreateAsync(Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations,System.String,System.String,System.IO.Stream,System.Nullable{System.Boolean},System.Nullable{Microsoft.Azure.Management.DataLake.Store.Models.SyncFlag},System.Nullable{System.Guid},System.Nullable{System.Int32},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member CreateAsync : Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations * string * string * System.IO.Stream * Nullable&lt;bool&gt; * Nullable&lt;Microsoft.Azure.Management.DataLake.Store.Models.SyncFlag&gt; * Nullable&lt;Guid&gt; * Nullable&lt;int&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.DataLake.Store.FileSystemOperationsExtensions.CreateAsync (operations, accountName, path, streamContents, overwrite, syncFlag, leaseId, permission, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Store</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.DataLake.Store.FileSystemOperationsExtensions/&lt;CreateAsync&gt;d__25))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations" RefType="this" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="path" Type="System.String" />
        <Parameter Name="streamContents" Type="System.IO.Stream" />
        <Parameter Name="overwrite" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="syncFlag" Type="System.Nullable&lt;Microsoft.Azure.Management.DataLake.Store.Models.SyncFlag&gt;" />
        <Parameter Name="leaseId" Type="System.Nullable&lt;System.Guid&gt;" />
        <Parameter Name="permission" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="accountName">
            Das Azure Data Lake-Speicher-Konto zum Ausführen der Filesystem-Vorgänge auf.
            </param>
        <param name="path">
            Der Pfad des Data Lake-Speicher (beginnend mit '/') der zu erstellenden Datei.
            </param>
        <param name="streamContents">
            Der Inhalt der Datei beim Erstellen der Datei werden sollen. Dieser Parameter ist optional, was in eine leere Datei, wenn nicht angegeben.
            </param>
        <param name="overwrite">
            Angabe darüber zurück, wenn die Datei überschrieben werden sollte.
            </param>
        <param name="syncFlag">
            Optional gibt an, was nach Abschluss des erstellen. Daten angeben, dass mehr Daten sofort vom Client gesendet werden werden, das Dateihandle, Open/gesperrt verbleiben sollte und Dateimetadaten (einschließlich Dateilänge, Uhrzeit der letzten Änderung) sollten nicht aktualisiert. Metadaten gibt an, dass mehr Daten sofort vom Client gesendet werden werden, das Dateihandle, Open/gesperrt verbleiben sollte und Dateimetadaten sollte aktualisiert. Schließen gibt an, dass der Client sendende von Daten erfolgt und das Dateihandle geschlossen/entsperrt muss Dateimetadaten sollte aktualisiert. Folgende Werte sind möglich: "Daten", "Metadaten", "Schließen"
            </param>
        <param name="leaseId">
            Optionale eindeutige GUID pro Datei an, um einzelne Writer-Semantik, was bedeutet, dass nur Clients, die an die Datei mit der gleichen LeaseId anfügen dazu berechtigt sein, sicherzustellen.
            </param>
        <param name="permission">
            Die oktale Darstellung der unbenannten Benutzer, Subnetzmaske und andere Berechtigungen, die für die Datei, die beim Erstellen festgelegt werden soll. Wenn nicht angegeben ist, erbt er diese aus dem Container.
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Erstellt eine Datei mit den optional angegebenen Inhalt. Hinweis: Wenn Inhalte bereitgestellt wird, kann die resultierende Datei geändert werden ConcurrentAppend verwenden.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Delete">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.DataLake.Store.Models.FileOperationResult Delete (this Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations operations, string accountName, string path, Nullable&lt;bool&gt; recursive = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.DataLake.Store.Models.FileOperationResult Delete(class Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations operations, string accountName, string path, valuetype System.Nullable`1&lt;bool&gt; recursive) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Store.FileSystemOperationsExtensions.Delete(Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations,System.String,System.String,System.Nullable{System.Boolean})" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function Delete (operations As IFileSystemOperations, accountName As String, path As String, Optional recursive As Nullable(Of Boolean) = null) As FileOperationResult" />
      <MemberSignature Language="F#" Value="static member Delete : Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations * string * string * Nullable&lt;bool&gt; -&gt; Microsoft.Azure.Management.DataLake.Store.Models.FileOperationResult" Usage="Microsoft.Azure.Management.DataLake.Store.FileSystemOperationsExtensions.Delete (operations, accountName, path, recursive)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Store</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.DataLake.Store.Models.FileOperationResult</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations" RefType="this" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="path" Type="System.String" />
        <Parameter Name="recursive" Type="System.Nullable&lt;System.Boolean&gt;" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="accountName">
            Das Azure Data Lake-Speicher-Konto zum Ausführen der Filesystem-Vorgänge auf.
            </param>
        <param name="path">
            Der Pfad des Data Lake-Speicher (beginnend mit '/') der Datei oder eines Verzeichnisses gelöscht.
            </param>
        <param name="recursive">
            Der Optionaler Schalter, der angibt, ob der Löschvorgang rekursiv sein soll
            </param>
        <summary>
            Die angeforderte Datei oder Verzeichnis und optional rekursiv gelöscht.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataLake.Store.Models.FileOperationResult&gt; DeleteAsync (this Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations operations, string accountName, string path, Nullable&lt;bool&gt; recursive = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.DataLake.Store.Models.FileOperationResult&gt; DeleteAsync(class Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations operations, string accountName, string path, valuetype System.Nullable`1&lt;bool&gt; recursive, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Store.FileSystemOperationsExtensions.DeleteAsync(Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations,System.String,System.String,System.Nullable{System.Boolean},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member DeleteAsync : Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations * string * string * Nullable&lt;bool&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataLake.Store.Models.FileOperationResult&gt;" Usage="Microsoft.Azure.Management.DataLake.Store.FileSystemOperationsExtensions.DeleteAsync (operations, accountName, path, recursive, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Store</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.DataLake.Store.FileSystemOperationsExtensions/&lt;DeleteAsync&gt;d__39))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataLake.Store.Models.FileOperationResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations" RefType="this" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="path" Type="System.String" />
        <Parameter Name="recursive" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="accountName">
            Das Azure Data Lake-Speicher-Konto zum Ausführen der Filesystem-Vorgänge auf.
            </param>
        <param name="path">
            Der Pfad des Data Lake-Speicher (beginnend mit '/') der Datei oder eines Verzeichnisses gelöscht.
            </param>
        <param name="recursive">
            Der Optionaler Schalter, der angibt, ob der Löschvorgang rekursiv sein soll
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Die angeforderte Datei oder Verzeichnis und optional rekursiv gelöscht.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAclStatus">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.DataLake.Store.Models.AclStatusResult GetAclStatus (this Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations operations, string accountName, string path, Nullable&lt;bool&gt; tooId = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.DataLake.Store.Models.AclStatusResult GetAclStatus(class Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations operations, string accountName, string path, valuetype System.Nullable`1&lt;bool&gt; tooId) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Store.FileSystemOperationsExtensions.GetAclStatus(Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations,System.String,System.String,System.Nullable{System.Boolean})" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function GetAclStatus (operations As IFileSystemOperations, accountName As String, path As String, Optional tooId As Nullable(Of Boolean) = null) As AclStatusResult" />
      <MemberSignature Language="F#" Value="static member GetAclStatus : Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations * string * string * Nullable&lt;bool&gt; -&gt; Microsoft.Azure.Management.DataLake.Store.Models.AclStatusResult" Usage="Microsoft.Azure.Management.DataLake.Store.FileSystemOperationsExtensions.GetAclStatus (operations, accountName, path, tooId)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Store</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.DataLake.Store.Models.AclStatusResult</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations" RefType="this" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="path" Type="System.String" />
        <Parameter Name="tooId" Type="System.Nullable&lt;System.Boolean&gt;" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="accountName">
            Das Azure Data Lake-Speicher-Konto zum Ausführen der Filesystem-Vorgänge auf.
            </param>
        <param name="path">
            Der Pfad des Data Lake-Speicher (beginnend mit '/') der Datei oder des Verzeichnisses für den die ACL abgerufen.
            </param>
        <param name="tooId">
            Ein Optionaler Schalter benutzerfreundliche Namen anstelle von Objekt-ID für die ACL-Einträge zurückgegeben. Tooid = "false" gibt die Anzeigenamen statt die AAD-Objekt-ID.
            Standardwert ist "true" Zurückgeben von AAD-Objekt-IDs.
            </param>
        <summary>
            Ruft die Einträge (Access Control List, ACL) für die angegebene Datei oder das Verzeichnis ab.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAclStatusAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataLake.Store.Models.AclStatusResult&gt; GetAclStatusAsync (this Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations operations, string accountName, string path, Nullable&lt;bool&gt; tooId = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.DataLake.Store.Models.AclStatusResult&gt; GetAclStatusAsync(class Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations operations, string accountName, string path, valuetype System.Nullable`1&lt;bool&gt; tooId, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Store.FileSystemOperationsExtensions.GetAclStatusAsync(Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations,System.String,System.String,System.Nullable{System.Boolean},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetAclStatusAsync : Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations * string * string * Nullable&lt;bool&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataLake.Store.Models.AclStatusResult&gt;" Usage="Microsoft.Azure.Management.DataLake.Store.FileSystemOperationsExtensions.GetAclStatusAsync (operations, accountName, path, tooId, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Store</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.DataLake.Store.FileSystemOperationsExtensions/&lt;GetAclStatusAsync&gt;d__37))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataLake.Store.Models.AclStatusResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations" RefType="this" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="path" Type="System.String" />
        <Parameter Name="tooId" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="accountName">
            Das Azure Data Lake-Speicher-Konto zum Ausführen der Filesystem-Vorgänge auf.
            </param>
        <param name="path">
            Der Pfad des Data Lake-Speicher (beginnend mit '/') der Datei oder des Verzeichnisses für den die ACL abgerufen.
            </param>
        <param name="tooId">
            Ein Optionaler Schalter benutzerfreundliche Namen anstelle von Objekt-ID für die ACL-Einträge zurückgegeben. Tooid = "false" gibt die Anzeigenamen statt die AAD-Objekt-ID.
            Standardwert ist "true" Zurückgeben von AAD-Objekt-IDs.
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Ruft die Einträge (Access Control List, ACL) für die angegebene Datei oder das Verzeichnis ab.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetContentSummary">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.DataLake.Store.Models.ContentSummaryResult GetContentSummary (this Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations operations, string accountName, string path);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.DataLake.Store.Models.ContentSummaryResult GetContentSummary(class Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations operations, string accountName, string path) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Store.FileSystemOperationsExtensions.GetContentSummary(Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function GetContentSummary (operations As IFileSystemOperations, accountName As String, path As String) As ContentSummaryResult" />
      <MemberSignature Language="F#" Value="static member GetContentSummary : Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations * string * string -&gt; Microsoft.Azure.Management.DataLake.Store.Models.ContentSummaryResult" Usage="Microsoft.Azure.Management.DataLake.Store.FileSystemOperationsExtensions.GetContentSummary (operations, accountName, path)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Store</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.DataLake.Store.Models.ContentSummaryResult</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations" RefType="this" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="path" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="accountName">
            Das Azure Data Lake-Speicher-Konto zum Ausführen der Filesystem-Vorgänge auf.
            </param>
        <param name="path">
            Der Pfad des Data Lake-Speicher (beginnend mit '/') der Datei für die Zusammenfassung des abzurufen.
            </param>
        <summary>
            Ruft den Inhalt Zusammenfassung Objekt "Datei" angegeben werden, indem der Dateipfad ab.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetContentSummaryAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataLake.Store.Models.ContentSummaryResult&gt; GetContentSummaryAsync (this Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations operations, string accountName, string path, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.DataLake.Store.Models.ContentSummaryResult&gt; GetContentSummaryAsync(class Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations operations, string accountName, string path, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Store.FileSystemOperationsExtensions.GetContentSummaryAsync(Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetContentSummaryAsync : Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataLake.Store.Models.ContentSummaryResult&gt;" Usage="Microsoft.Azure.Management.DataLake.Store.FileSystemOperationsExtensions.GetContentSummaryAsync (operations, accountName, path, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Store</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.DataLake.Store.FileSystemOperationsExtensions/&lt;GetContentSummaryAsync&gt;d__17))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataLake.Store.Models.ContentSummaryResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations" RefType="this" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="path" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="accountName">
            Das Azure Data Lake-Speicher-Konto zum Ausführen der Filesystem-Vorgänge auf.
            </param>
        <param name="path">
            Der Pfad des Data Lake-Speicher (beginnend mit '/') der Datei für die Zusammenfassung des abzurufen.
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Ruft den Inhalt Zusammenfassung Objekt "Datei" angegeben werden, indem der Dateipfad ab.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetFileStatus">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.DataLake.Store.Models.FileStatusResult GetFileStatus (this Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations operations, string accountName, string path, Nullable&lt;bool&gt; tooId = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.DataLake.Store.Models.FileStatusResult GetFileStatus(class Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations operations, string accountName, string path, valuetype System.Nullable`1&lt;bool&gt; tooId) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Store.FileSystemOperationsExtensions.GetFileStatus(Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations,System.String,System.String,System.Nullable{System.Boolean})" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function GetFileStatus (operations As IFileSystemOperations, accountName As String, path As String, Optional tooId As Nullable(Of Boolean) = null) As FileStatusResult" />
      <MemberSignature Language="F#" Value="static member GetFileStatus : Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations * string * string * Nullable&lt;bool&gt; -&gt; Microsoft.Azure.Management.DataLake.Store.Models.FileStatusResult" Usage="Microsoft.Azure.Management.DataLake.Store.FileSystemOperationsExtensions.GetFileStatus (operations, accountName, path, tooId)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Store</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.DataLake.Store.Models.FileStatusResult</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations" RefType="this" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="path" Type="System.String" />
        <Parameter Name="tooId" Type="System.Nullable&lt;System.Boolean&gt;" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="accountName">
            Das Azure Data Lake-Speicher-Konto zum Ausführen der Filesystem-Vorgänge auf.
            </param>
        <param name="path">
            Der Pfad des Data Lake-Speicher (beginnend mit '/') der Datei oder des Verzeichnisses für das Abrufen des Status.
            </param>
        <param name="tooId">
            Ein Optionaler Schalter zum Zurückgeben von Anzeigenamen anstelle der Besitzer und die Gruppe.
            Tooid = "false" gibt die Anzeigenamen statt die AAD-Objekt-ID. Standardwert ist "true" Zurückgeben von AAD-Objekt-IDs.
            </param>
        <summary>
            Erhalten Sie das Objekt "Datei" Status durch den Dateipfad angegeben.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetFileStatusAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataLake.Store.Models.FileStatusResult&gt; GetFileStatusAsync (this Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations operations, string accountName, string path, Nullable&lt;bool&gt; tooId = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.DataLake.Store.Models.FileStatusResult&gt; GetFileStatusAsync(class Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations operations, string accountName, string path, valuetype System.Nullable`1&lt;bool&gt; tooId, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Store.FileSystemOperationsExtensions.GetFileStatusAsync(Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations,System.String,System.String,System.Nullable{System.Boolean},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetFileStatusAsync : Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations * string * string * Nullable&lt;bool&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataLake.Store.Models.FileStatusResult&gt;" Usage="Microsoft.Azure.Management.DataLake.Store.FileSystemOperationsExtensions.GetFileStatusAsync (operations, accountName, path, tooId, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Store</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.DataLake.Store.FileSystemOperationsExtensions/&lt;GetFileStatusAsync&gt;d__19))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataLake.Store.Models.FileStatusResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations" RefType="this" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="path" Type="System.String" />
        <Parameter Name="tooId" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="accountName">
            Das Azure Data Lake-Speicher-Konto zum Ausführen der Filesystem-Vorgänge auf.
            </param>
        <param name="path">
            Der Pfad des Data Lake-Speicher (beginnend mit '/') der Datei oder des Verzeichnisses für das Abrufen des Status.
            </param>
        <param name="tooId">
            Ein Optionaler Schalter zum Zurückgeben von Anzeigenamen anstelle der Besitzer und die Gruppe.
            Tooid = "false" gibt die Anzeigenamen statt die AAD-Objekt-ID. Standardwert ist "true" Zurückgeben von AAD-Objekt-IDs.
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Erhalten Sie das Objekt "Datei" Status durch den Dateipfad angegeben.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListFileStatus">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.DataLake.Store.Models.FileStatusesResult ListFileStatus (this Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations operations, string accountName, string path, Nullable&lt;int&gt; listSize = null, string listAfter = null, string listBefore = null, Nullable&lt;bool&gt; tooId = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.DataLake.Store.Models.FileStatusesResult ListFileStatus(class Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations operations, string accountName, string path, valuetype System.Nullable`1&lt;int32&gt; listSize, string listAfter, string listBefore, valuetype System.Nullable`1&lt;bool&gt; tooId) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Store.FileSystemOperationsExtensions.ListFileStatus(Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations,System.String,System.String,System.Nullable{System.Int32},System.String,System.String,System.Nullable{System.Boolean})" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListFileStatus (operations As IFileSystemOperations, accountName As String, path As String, Optional listSize As Nullable(Of Integer) = null, Optional listAfter As String = null, Optional listBefore As String = null, Optional tooId As Nullable(Of Boolean) = null) As FileStatusesResult" />
      <MemberSignature Language="F#" Value="static member ListFileStatus : Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations * string * string * Nullable&lt;int&gt; * string * string * Nullable&lt;bool&gt; -&gt; Microsoft.Azure.Management.DataLake.Store.Models.FileStatusesResult" Usage="Microsoft.Azure.Management.DataLake.Store.FileSystemOperationsExtensions.ListFileStatus (operations, accountName, path, listSize, listAfter, listBefore, tooId)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Store</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.DataLake.Store.Models.FileStatusesResult</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations" RefType="this" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="path" Type="System.String" />
        <Parameter Name="listSize" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="listAfter" Type="System.String" />
        <Parameter Name="listBefore" Type="System.String" />
        <Parameter Name="tooId" Type="System.Nullable&lt;System.Boolean&gt;" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="accountName">
            Das Azure Data Lake-Speicher-Konto zum Ausführen der Filesystem-Vorgänge auf.
            </param>
        <param name="path">
            Der Pfad des Data Lake-Speicher (beginnend mit "/") des Verzeichnisses, das Liste.
            </param>
        <param name="listSize">
            Ruft ab oder legt die Anzahl der zurückzugebenden Elemente an. Optional.
            </param>
        <param name="listAfter">
            Ruft ab oder legt das Element oder Lexographical Index nach dem Ergebnisse zurückgegeben werden soll. Eine Liste der Dateien von "a","b", z. B. verdächtigem "und ListAfter ="b"wird zurückgeben würde", und eine ListAfter = "C" wird auch zurückgeben würde ". Optional.
            </param>
        <param name="listBefore">
            Ruft ab oder legt das Element oder Lexographical Index vor dem Zurückgeben von Ergebnissen werden soll. Eine Dateiliste des "a","b", z. B. verdächtigem "und ListBefore = hatte" wird zurückgegeben, "a", "b" und eine ListBefore = "c", "a","b" wird ebenfalls zurückgegeben. Optional.
            </param>
        <param name="tooId">
            Ein Optionaler Schalter zum Zurückgeben von Anzeigenamen anstelle der Besitzer und die Gruppe.
            Tooid = "false" gibt die Anzeigenamen statt die AAD-Objekt-ID. Standardwert ist "true" Zurückgeben von AAD-Objekt-IDs.
            </param>
        <summary>
            Rufen Sie die Liste von Objekten durch den Dateipfad, mit optionalen Paginierung-Parameter angegebene status
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListFileStatusAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataLake.Store.Models.FileStatusesResult&gt; ListFileStatusAsync (this Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations operations, string accountName, string path, Nullable&lt;int&gt; listSize = null, string listAfter = null, string listBefore = null, Nullable&lt;bool&gt; tooId = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.DataLake.Store.Models.FileStatusesResult&gt; ListFileStatusAsync(class Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations operations, string accountName, string path, valuetype System.Nullable`1&lt;int32&gt; listSize, string listAfter, string listBefore, valuetype System.Nullable`1&lt;bool&gt; tooId, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Store.FileSystemOperationsExtensions.ListFileStatusAsync(Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations,System.String,System.String,System.Nullable{System.Int32},System.String,System.String,System.Nullable{System.Boolean},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListFileStatusAsync : Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations * string * string * Nullable&lt;int&gt; * string * string * Nullable&lt;bool&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataLake.Store.Models.FileStatusesResult&gt;" Usage="Microsoft.Azure.Management.DataLake.Store.FileSystemOperationsExtensions.ListFileStatusAsync (operations, accountName, path, listSize, listAfter, listBefore, tooId, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Store</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.DataLake.Store.FileSystemOperationsExtensions/&lt;ListFileStatusAsync&gt;d__15))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataLake.Store.Models.FileStatusesResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations" RefType="this" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="path" Type="System.String" />
        <Parameter Name="listSize" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="listAfter" Type="System.String" />
        <Parameter Name="listBefore" Type="System.String" />
        <Parameter Name="tooId" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="accountName">
            Das Azure Data Lake-Speicher-Konto zum Ausführen der Filesystem-Vorgänge auf.
            </param>
        <param name="path">
            Der Pfad des Data Lake-Speicher (beginnend mit "/") des Verzeichnisses, das Liste.
            </param>
        <param name="listSize">
            Ruft ab oder legt die Anzahl der zurückzugebenden Elemente an. Optional.
            </param>
        <param name="listAfter">
            Ruft ab oder legt das Element oder Lexographical Index nach dem Ergebnisse zurückgegeben werden soll. Eine Liste der Dateien von "a","b", z. B. verdächtigem "und ListAfter ="b"wird zurückgeben würde", und eine ListAfter = "C" wird auch zurückgeben würde ". Optional.
            </param>
        <param name="listBefore">
            Ruft ab oder legt das Element oder Lexographical Index vor dem Zurückgeben von Ergebnissen werden soll. Eine Dateiliste des "a","b", z. B. verdächtigem "und ListBefore = hatte" wird zurückgegeben, "a", "b" und eine ListBefore = "c", "a","b" wird ebenfalls zurückgegeben. Optional.
            </param>
        <param name="tooId">
            Ein Optionaler Schalter zum Zurückgeben von Anzeigenamen anstelle der Besitzer und die Gruppe.
            Tooid = "false" gibt die Anzeigenamen statt die AAD-Objekt-ID. Standardwert ist "true" Zurückgeben von AAD-Objekt-IDs.
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Rufen Sie die Liste von Objekten durch den Dateipfad, mit optionalen Paginierung-Parameter angegebene status
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Mkdirs">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.DataLake.Store.Models.FileOperationResult Mkdirs (this Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations operations, string accountName, string path, Nullable&lt;int&gt; permission = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.DataLake.Store.Models.FileOperationResult Mkdirs(class Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations operations, string accountName, string path, valuetype System.Nullable`1&lt;int32&gt; permission) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Store.FileSystemOperationsExtensions.Mkdirs(Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations,System.String,System.String,System.Nullable{System.Int32})" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function Mkdirs (operations As IFileSystemOperations, accountName As String, path As String, Optional permission As Nullable(Of Integer) = null) As FileOperationResult" />
      <MemberSignature Language="F#" Value="static member Mkdirs : Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations * string * string * Nullable&lt;int&gt; -&gt; Microsoft.Azure.Management.DataLake.Store.Models.FileOperationResult" Usage="Microsoft.Azure.Management.DataLake.Store.FileSystemOperationsExtensions.Mkdirs (operations, accountName, path, permission)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Store</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.DataLake.Store.Models.FileOperationResult</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations" RefType="this" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="path" Type="System.String" />
        <Parameter Name="permission" Type="System.Nullable&lt;System.Int32&gt;" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="accountName">
            Das Azure Data Lake-Speicher-Konto zum Ausführen der Filesystem-Vorgänge auf.
            </param>
        <param name="path">
            Der Pfad des Data Lake-Speicher (beginnend mit '/') der das zu erstellende Verzeichnis.
            </param>
        <param name="permission">
            Optionale oktale Berechtigung, die mit dem Verzeichnis erstellt werden soll.
            </param>
        <summary>
            Erstellt ein Verzeichnis.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MkdirsAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataLake.Store.Models.FileOperationResult&gt; MkdirsAsync (this Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations operations, string accountName, string path, Nullable&lt;int&gt; permission = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.DataLake.Store.Models.FileOperationResult&gt; MkdirsAsync(class Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations operations, string accountName, string path, valuetype System.Nullable`1&lt;int32&gt; permission, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Store.FileSystemOperationsExtensions.MkdirsAsync(Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations,System.String,System.String,System.Nullable{System.Int32},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member MkdirsAsync : Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations * string * string * Nullable&lt;int&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataLake.Store.Models.FileOperationResult&gt;" Usage="Microsoft.Azure.Management.DataLake.Store.FileSystemOperationsExtensions.MkdirsAsync (operations, accountName, path, permission, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Store</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.DataLake.Store.FileSystemOperationsExtensions/&lt;MkdirsAsync&gt;d__9))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataLake.Store.Models.FileOperationResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations" RefType="this" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="path" Type="System.String" />
        <Parameter Name="permission" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="accountName">
            Das Azure Data Lake-Speicher-Konto zum Ausführen der Filesystem-Vorgänge auf.
            </param>
        <param name="path">
            Der Pfad des Data Lake-Speicher (beginnend mit '/') der das zu erstellende Verzeichnis.
            </param>
        <param name="permission">
            Optionale oktale Berechtigung, die mit dem Verzeichnis erstellt werden soll.
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Erstellt ein Verzeichnis.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ModifyAclEntries">
      <MemberSignature Language="C#" Value="public static void ModifyAclEntries (this Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations operations, string accountName, string path, string aclspec);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void ModifyAclEntries(class Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations operations, string accountName, string path, string aclspec) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Store.FileSystemOperationsExtensions.ModifyAclEntries(Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Sub ModifyAclEntries (operations As IFileSystemOperations, accountName As String, path As String, aclspec As String)" />
      <MemberSignature Language="F#" Value="static member ModifyAclEntries : Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations * string * string * string -&gt; unit" Usage="Microsoft.Azure.Management.DataLake.Store.FileSystemOperationsExtensions.ModifyAclEntries (operations, accountName, path, aclspec)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Store</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations" RefType="this" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="path" Type="System.String" />
        <Parameter Name="aclspec" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="accountName">
            Das Azure Data Lake-Speicher-Konto zum Ausführen der Filesystem-Vorgänge auf.
            </param>
        <param name="path">
            Der Pfad des Data Lake-Speicher (beginnend mit '/') der Datei oder des Verzeichnisses mit der ACL, die geändert wird.
            </param>
        <param name="aclspec">
            Die ACL-Spezifikation enthalten in der ACL Änderungsvorgänge im Format "[Standard:] Benutzer | Gruppe | andere:: R |-w |-X |-"
            </param>
        <summary>
            Ändert vorhandene (Access Control List, ACL) Einträge in einer Datei oder eines Ordners an.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ModifyAclEntriesAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task ModifyAclEntriesAsync (this Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations operations, string accountName, string path, string aclspec, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task ModifyAclEntriesAsync(class Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations operations, string accountName, string path, string aclspec, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Store.FileSystemOperationsExtensions.ModifyAclEntriesAsync(Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ModifyAclEntriesAsync : Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.DataLake.Store.FileSystemOperationsExtensions.ModifyAclEntriesAsync (operations, accountName, path, aclspec, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Store</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.DataLake.Store.FileSystemOperationsExtensions/&lt;ModifyAclEntriesAsync&gt;d__29))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations" RefType="this" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="path" Type="System.String" />
        <Parameter Name="aclspec" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="accountName">
            Das Azure Data Lake-Speicher-Konto zum Ausführen der Filesystem-Vorgänge auf.
            </param>
        <param name="path">
            Der Pfad des Data Lake-Speicher (beginnend mit '/') der Datei oder des Verzeichnisses mit der ACL, die geändert wird.
            </param>
        <param name="aclspec">
            Die ACL-Spezifikation enthalten in der ACL Änderungsvorgänge im Format "[Standard:] Benutzer | Gruppe | andere:: R |-w |-X |-"
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Ändert vorhandene (Access Control List, ACL) Einträge in einer Datei oder eines Ordners an.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MsConcat">
      <MemberSignature Language="C#" Value="public static void MsConcat (this Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations operations, string accountName, string path, System.IO.Stream streamContents, Nullable&lt;bool&gt; deleteSourceDirectory = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void MsConcat(class Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations operations, string accountName, string path, class System.IO.Stream streamContents, valuetype System.Nullable`1&lt;bool&gt; deleteSourceDirectory) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Store.FileSystemOperationsExtensions.MsConcat(Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations,System.String,System.String,System.IO.Stream,System.Nullable{System.Boolean})" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Sub MsConcat (operations As IFileSystemOperations, accountName As String, path As String, streamContents As Stream, Optional deleteSourceDirectory As Nullable(Of Boolean) = null)" />
      <MemberSignature Language="F#" Value="static member MsConcat : Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations * string * string * System.IO.Stream * Nullable&lt;bool&gt; -&gt; unit" Usage="Microsoft.Azure.Management.DataLake.Store.FileSystemOperationsExtensions.MsConcat (operations, accountName, path, streamContents, deleteSourceDirectory)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Store</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations" RefType="this" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="path" Type="System.String" />
        <Parameter Name="streamContents" Type="System.IO.Stream" />
        <Parameter Name="deleteSourceDirectory" Type="System.Nullable&lt;System.Boolean&gt;" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="accountName">
            Das Azure Data Lake-Speicher-Konto zum Ausführen der Filesystem-Vorgänge auf.
            </param>
        <param name="path">
            Der Pfad des Data Lake-Speicher (beginnend mit '/') der Zieldatei, die sich aus der Verkettung ergibt.
            </param>
        <param name="streamContents">
            Eine Liste der Data Lake-Speicher-Pfade (beginnend mit '/') der Quelldateien.
            Muss eine durch Trennzeichen getrennte Pfadliste im Format: sources=/file/path/1.txt,/file/path/2.txt,/file/path/lastfile.csv
            </param>
        <param name="deleteSourceDirectory">
            Gibt an, dass eine Optimierung stattdessen jede einzelne Quelldatenstrom zu löschen, löschen Stream Quellordner Wenn stattdessen alle Streams in demselben Ordner befinden. Dies führt zu eine erhebliche Leistungssteigerung, wenn die einzige Datenströme im Ordner "" Teil des verkettungsvorgangs sind. Warnung: Dies umfasst das Löschen von Dateien, die Quelldateien nicht sind. Legen Sie nur diese auf "true" wenn Quelldateien nur Dateien in das Quellverzeichnis sind.
            </param>
        <summary>
            Verkettet die Liste der Quelldateien in der Zieldatei, die alle Quelldateien bei Erfolg wird gelöscht. Diese Methode akzeptiert Weitere quelldateipfaden als die Concat-Methode. Diese Methode und die Parameter, von denen, die er akzeptiert, werden kann zum Zweck der benutzerfreundlichkeit in einer zukünftigen Version geändert.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MsConcatAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task MsConcatAsync (this Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations operations, string accountName, string path, System.IO.Stream streamContents, Nullable&lt;bool&gt; deleteSourceDirectory = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task MsConcatAsync(class Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations operations, string accountName, string path, class System.IO.Stream streamContents, valuetype System.Nullable`1&lt;bool&gt; deleteSourceDirectory, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Store.FileSystemOperationsExtensions.MsConcatAsync(Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations,System.String,System.String,System.IO.Stream,System.Nullable{System.Boolean},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member MsConcatAsync : Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations * string * string * System.IO.Stream * Nullable&lt;bool&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.DataLake.Store.FileSystemOperationsExtensions.MsConcatAsync (operations, accountName, path, streamContents, deleteSourceDirectory, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Store</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.DataLake.Store.FileSystemOperationsExtensions/&lt;MsConcatAsync&gt;d__13))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations" RefType="this" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="path" Type="System.String" />
        <Parameter Name="streamContents" Type="System.IO.Stream" />
        <Parameter Name="deleteSourceDirectory" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="accountName">
            Das Azure Data Lake-Speicher-Konto zum Ausführen der Filesystem-Vorgänge auf.
            </param>
        <param name="path">
            Der Pfad des Data Lake-Speicher (beginnend mit '/') der Zieldatei, die sich aus der Verkettung ergibt.
            </param>
        <param name="streamContents">
            Eine Liste der Data Lake-Speicher-Pfade (beginnend mit '/') der Quelldateien.
            Muss eine durch Trennzeichen getrennte Pfadliste im Format: sources=/file/path/1.txt,/file/path/2.txt,/file/path/lastfile.csv
            </param>
        <param name="deleteSourceDirectory">
            Gibt an, dass eine Optimierung stattdessen jede einzelne Quelldatenstrom zu löschen, löschen Stream Quellordner Wenn stattdessen alle Streams in demselben Ordner befinden. Dies führt zu eine erhebliche Leistungssteigerung, wenn die einzige Datenströme im Ordner "" Teil des verkettungsvorgangs sind. Warnung: Dies umfasst das Löschen von Dateien, die Quelldateien nicht sind. Legen Sie nur diese auf "true" wenn Quelldateien nur Dateien in das Quellverzeichnis sind.
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Verkettet die Liste der Quelldateien in der Zieldatei, die alle Quelldateien bei Erfolg wird gelöscht. Diese Methode akzeptiert Weitere quelldateipfaden als die Concat-Methode. Diese Methode und die Parameter, von denen, die er akzeptiert, werden kann zum Zweck der benutzerfreundlichkeit in einer zukünftigen Version geändert.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Open">
      <MemberSignature Language="C#" Value="public static System.IO.Stream Open (this Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations operations, string accountName, string path, Nullable&lt;long&gt; length = null, Nullable&lt;long&gt; offset = null, Nullable&lt;Guid&gt; fileSessionId = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.IO.Stream Open(class Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations operations, string accountName, string path, valuetype System.Nullable`1&lt;int64&gt; length, valuetype System.Nullable`1&lt;int64&gt; offset, valuetype System.Nullable`1&lt;valuetype System.Guid&gt; fileSessionId) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Store.FileSystemOperationsExtensions.Open(Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations,System.String,System.String,System.Nullable{System.Int64},System.Nullable{System.Int64},System.Nullable{System.Guid})" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function Open (operations As IFileSystemOperations, accountName As String, path As String, Optional length As Nullable(Of Long) = null, Optional offset As Nullable(Of Long) = null, Optional fileSessionId As Nullable(Of Guid) = null) As Stream" />
      <MemberSignature Language="F#" Value="static member Open : Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations * string * string * Nullable&lt;int64&gt; * Nullable&lt;int64&gt; * Nullable&lt;Guid&gt; -&gt; System.IO.Stream" Usage="Microsoft.Azure.Management.DataLake.Store.FileSystemOperationsExtensions.Open (operations, accountName, path, length, offset, fileSessionId)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Store</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.IO.Stream</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations" RefType="this" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="path" Type="System.String" />
        <Parameter Name="length" Type="System.Nullable&lt;System.Int64&gt;" />
        <Parameter Name="offset" Type="System.Nullable&lt;System.Int64&gt;" />
        <Parameter Name="fileSessionId" Type="System.Nullable&lt;System.Guid&gt;" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="accountName">
            Das Azure Data Lake-Speicher-Konto zum Ausführen der Filesystem-Vorgänge auf.
            </param>
        <param name="path">
            Der Pfad des Data Lake-Speicher (beginnend mit '/') der Datei zu öffnen.
            </param>
        <param name="length">
            Die Anzahl der Bytes, die zum Abrufen der Server versucht. Es werden abgerufen &lt;= Längenbytes.
            </param>
        <param name="offset">
            Der Byteoffset zum Lesen von Daten aus starten.
            </param>
        <param name="fileSessionId">
            Optionale eindeutige GUID pro Datei, der angibt, mit der gleichen FileSessionId alle Lesevorgänge werden von der gleichen Client und der gleichen Sitzung. Dadurch erhalten einen Leistungsvorteil.
            </param>
        <summary>
            Öffnet und liest aus der angegebenen Datei.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OpenAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;System.IO.Stream&gt; OpenAsync (this Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations operations, string accountName, string path, Nullable&lt;long&gt; length = null, Nullable&lt;long&gt; offset = null, Nullable&lt;Guid&gt; fileSessionId = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class System.IO.Stream&gt; OpenAsync(class Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations operations, string accountName, string path, valuetype System.Nullable`1&lt;int64&gt; length, valuetype System.Nullable`1&lt;int64&gt; offset, valuetype System.Nullable`1&lt;valuetype System.Guid&gt; fileSessionId, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Store.FileSystemOperationsExtensions.OpenAsync(Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations,System.String,System.String,System.Nullable{System.Int64},System.Nullable{System.Int64},System.Nullable{System.Guid},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member OpenAsync : Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations * string * string * Nullable&lt;int64&gt; * Nullable&lt;int64&gt; * Nullable&lt;Guid&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.IO.Stream&gt;" Usage="Microsoft.Azure.Management.DataLake.Store.FileSystemOperationsExtensions.OpenAsync (operations, accountName, path, length, offset, fileSessionId, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Store</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.DataLake.Store.FileSystemOperationsExtensions/&lt;OpenAsync&gt;d__21))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.IO.Stream&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations" RefType="this" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="path" Type="System.String" />
        <Parameter Name="length" Type="System.Nullable&lt;System.Int64&gt;" />
        <Parameter Name="offset" Type="System.Nullable&lt;System.Int64&gt;" />
        <Parameter Name="fileSessionId" Type="System.Nullable&lt;System.Guid&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="accountName">
            Das Azure Data Lake-Speicher-Konto zum Ausführen der Filesystem-Vorgänge auf.
            </param>
        <param name="path">
            Der Pfad des Data Lake-Speicher (beginnend mit '/') der Datei zu öffnen.
            </param>
        <param name="length">
            Die Anzahl der Bytes, die zum Abrufen der Server versucht. Es werden abgerufen &lt;= Längenbytes.
            </param>
        <param name="offset">
            Der Byteoffset zum Lesen von Daten aus starten.
            </param>
        <param name="fileSessionId">
            Optionale eindeutige GUID pro Datei, der angibt, mit der gleichen FileSessionId alle Lesevorgänge werden von der gleichen Client und der gleichen Sitzung. Dadurch erhalten einen Leistungsvorteil.
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Öffnet und liest aus der angegebenen Datei.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PathExists">
      <MemberSignature Language="C#" Value="public static bool PathExists (this Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations operations, string accountName, string getFilePath);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig bool PathExists(class Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations operations, string accountName, string getFilePath) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Store.FileSystemOperationsExtensions.PathExists(Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function PathExists (operations As IFileSystemOperations, accountName As String, getFilePath As String) As Boolean" />
      <MemberSignature Language="F#" Value="static member PathExists : Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations * string * string -&gt; bool" Usage="Microsoft.Azure.Management.DataLake.Store.FileSystemOperationsExtensions.PathExists (operations, accountName, getFilePath)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Store</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations" RefType="this" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="getFilePath" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="accountName">
            Das Azure Data Lake-Speicher-Konto zum Ausführen der Filesystem-Vorgänge auf.
            </param>
        <param name="getFilePath">
            Der Pfad des Data Lake-Speicher (beginnend mit '/') der Datei oder des Verzeichnisses für die das Vorhandensein testen.
            </param>
        <summary>
            Testen Sie das Vorhandensein eines Objekts Datei oder das Verzeichnis, die durch den Dateipfad angegeben.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PathExistsAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;bool&gt; PathExistsAsync (this Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations operations, string accountName, string getFilePath, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;bool&gt; PathExistsAsync(class Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations operations, string accountName, string getFilePath, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Store.FileSystemOperationsExtensions.PathExistsAsync(Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member PathExistsAsync : Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;bool&gt;" Usage="Microsoft.Azure.Management.DataLake.Store.FileSystemOperationsExtensions.PathExistsAsync (operations, accountName, getFilePath, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Store</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.DataLake.Store.FileSystemOperationsExtensions/&lt;PathExistsAsync&gt;d__1))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations" RefType="this" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="getFilePath" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="accountName">
            Das Azure Data Lake-Speicher-Konto zum Ausführen der Filesystem-Vorgänge auf.
            </param>
        <param name="getFilePath">
            Der Pfad des Data Lake-Speicher (beginnend mit '/') der Datei oder des Verzeichnisses für die das Vorhandensein testen.
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Testen Sie das Vorhandensein eines Objekts Datei oder das Verzeichnis, die durch den Dateipfad angegeben.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RemoveAcl">
      <MemberSignature Language="C#" Value="public static void RemoveAcl (this Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations operations, string accountName, string path);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void RemoveAcl(class Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations operations, string accountName, string path) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Store.FileSystemOperationsExtensions.RemoveAcl(Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Sub RemoveAcl (operations As IFileSystemOperations, accountName As String, path As String)" />
      <MemberSignature Language="F#" Value="static member RemoveAcl : Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations * string * string -&gt; unit" Usage="Microsoft.Azure.Management.DataLake.Store.FileSystemOperationsExtensions.RemoveAcl (operations, accountName, path)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Store</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations" RefType="this" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="path" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="accountName">
            Das Azure Data Lake-Speicher-Konto zum Ausführen der Filesystem-Vorgänge auf.
            </param>
        <param name="path">
            Der Pfad des Data Lake-Speicher (beginnend mit '/') der Datei oder des Verzeichnisses mit der ACL entfernt wird.
            </param>
        <summary>
            Entfernt die vorhandene Liste (ACL) der angegebenen Datei oder des Verzeichnisses.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RemoveAclAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task RemoveAclAsync (this Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations operations, string accountName, string path, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task RemoveAclAsync(class Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations operations, string accountName, string path, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Store.FileSystemOperationsExtensions.RemoveAclAsync(Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member RemoveAclAsync : Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.DataLake.Store.FileSystemOperationsExtensions.RemoveAclAsync (operations, accountName, path, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Store</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.DataLake.Store.FileSystemOperationsExtensions/&lt;RemoveAclAsync&gt;d__35))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations" RefType="this" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="path" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="accountName">
            Das Azure Data Lake-Speicher-Konto zum Ausführen der Filesystem-Vorgänge auf.
            </param>
        <param name="path">
            Der Pfad des Data Lake-Speicher (beginnend mit '/') der Datei oder des Verzeichnisses mit der ACL entfernt wird.
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Entfernt die vorhandene Liste (ACL) der angegebenen Datei oder des Verzeichnisses.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RemoveAclEntries">
      <MemberSignature Language="C#" Value="public static void RemoveAclEntries (this Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations operations, string accountName, string path, string aclspec);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void RemoveAclEntries(class Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations operations, string accountName, string path, string aclspec) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Store.FileSystemOperationsExtensions.RemoveAclEntries(Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Sub RemoveAclEntries (operations As IFileSystemOperations, accountName As String, path As String, aclspec As String)" />
      <MemberSignature Language="F#" Value="static member RemoveAclEntries : Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations * string * string * string -&gt; unit" Usage="Microsoft.Azure.Management.DataLake.Store.FileSystemOperationsExtensions.RemoveAclEntries (operations, accountName, path, aclspec)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Store</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations" RefType="this" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="path" Type="System.String" />
        <Parameter Name="aclspec" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="accountName">
            Das Azure Data Lake-Speicher-Konto zum Ausführen der Filesystem-Vorgänge auf.
            </param>
        <param name="path">
            Der Pfad des Data Lake-Speicher (beginnend mit '/') der Datei oder des Verzeichnisses mit der ACL entfernt wird.
            </param>
        <param name="aclspec">
            Die ACL-Spezifikation enthalten in der ACL entfernen Vorgänge im Format "[Standard:] Benutzer | Gruppe | andere"
            </param>
        <summary>
            Entfernt einen vorhandenen Einträge in der Zugriffssteuerungsliste (ACL) für eine Datei oder einen Ordner.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RemoveAclEntriesAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task RemoveAclEntriesAsync (this Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations operations, string accountName, string path, string aclspec, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task RemoveAclEntriesAsync(class Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations operations, string accountName, string path, string aclspec, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Store.FileSystemOperationsExtensions.RemoveAclEntriesAsync(Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member RemoveAclEntriesAsync : Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.DataLake.Store.FileSystemOperationsExtensions.RemoveAclEntriesAsync (operations, accountName, path, aclspec, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Store</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.DataLake.Store.FileSystemOperationsExtensions/&lt;RemoveAclEntriesAsync&gt;d__31))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations" RefType="this" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="path" Type="System.String" />
        <Parameter Name="aclspec" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="accountName">
            Das Azure Data Lake-Speicher-Konto zum Ausführen der Filesystem-Vorgänge auf.
            </param>
        <param name="path">
            Der Pfad des Data Lake-Speicher (beginnend mit '/') der Datei oder des Verzeichnisses mit der ACL entfernt wird.
            </param>
        <param name="aclspec">
            Die ACL-Spezifikation enthalten in der ACL entfernen Vorgänge im Format "[Standard:] Benutzer | Gruppe | andere"
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Entfernt einen vorhandenen Einträge in der Zugriffssteuerungsliste (ACL) für eine Datei oder einen Ordner.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RemoveDefaultAcl">
      <MemberSignature Language="C#" Value="public static void RemoveDefaultAcl (this Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations operations, string accountName, string path);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void RemoveDefaultAcl(class Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations operations, string accountName, string path) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Store.FileSystemOperationsExtensions.RemoveDefaultAcl(Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Sub RemoveDefaultAcl (operations As IFileSystemOperations, accountName As String, path As String)" />
      <MemberSignature Language="F#" Value="static member RemoveDefaultAcl : Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations * string * string -&gt; unit" Usage="Microsoft.Azure.Management.DataLake.Store.FileSystemOperationsExtensions.RemoveDefaultAcl (operations, accountName, path)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Store</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations" RefType="this" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="path" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="accountName">
            Das Azure Data Lake-Speicher-Konto zum Ausführen der Filesystem-Vorgänge auf.
            </param>
        <param name="path">
            Der Pfad des Data Lake-Speicher (beginnend mit "/") des Verzeichnisses mit den Standard-ACL entfernt wird.
            </param>
        <summary>
            Entfernt die vorhandene Standard Zugriffssteuerungsliste (ACL) des angegebenen Verzeichnisses.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RemoveDefaultAclAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task RemoveDefaultAclAsync (this Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations operations, string accountName, string path, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task RemoveDefaultAclAsync(class Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations operations, string accountName, string path, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Store.FileSystemOperationsExtensions.RemoveDefaultAclAsync(Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member RemoveDefaultAclAsync : Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.DataLake.Store.FileSystemOperationsExtensions.RemoveDefaultAclAsync (operations, accountName, path, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Store</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.DataLake.Store.FileSystemOperationsExtensions/&lt;RemoveDefaultAclAsync&gt;d__33))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations" RefType="this" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="path" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="accountName">
            Das Azure Data Lake-Speicher-Konto zum Ausführen der Filesystem-Vorgänge auf.
            </param>
        <param name="path">
            Der Pfad des Data Lake-Speicher (beginnend mit "/") des Verzeichnisses mit den Standard-ACL entfernt wird.
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Entfernt die vorhandene Standard Zugriffssteuerungsliste (ACL) des angegebenen Verzeichnisses.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Rename">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.DataLake.Store.Models.FileOperationResult Rename (this Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations operations, string accountName, string path, string destination);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.DataLake.Store.Models.FileOperationResult Rename(class Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations operations, string accountName, string path, string destination) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Store.FileSystemOperationsExtensions.Rename(Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function Rename (operations As IFileSystemOperations, accountName As String, path As String, destination As String) As FileOperationResult" />
      <MemberSignature Language="F#" Value="static member Rename : Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations * string * string * string -&gt; Microsoft.Azure.Management.DataLake.Store.Models.FileOperationResult" Usage="Microsoft.Azure.Management.DataLake.Store.FileSystemOperationsExtensions.Rename (operations, accountName, path, destination)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Store</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.DataLake.Store.Models.FileOperationResult</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations" RefType="this" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="path" Type="System.String" />
        <Parameter Name="destination" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="accountName">
            Das Azure Data Lake-Speicher-Konto zum Ausführen der Filesystem-Vorgänge auf.
            </param>
        <param name="path">
            Der Pfad des Data Lake-Speicher (beginnend mit '/') der Datei oder des Verzeichnisses zum Verschieben/umbenennen.
            </param>
        <param name="destination">
            Der Pfad zum Verschieben/Umbenennen der Datei oder einen Ordner an
            </param>
        <summary>
            Benennt eine Datei oder ein Verzeichnis um.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RenameAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataLake.Store.Models.FileOperationResult&gt; RenameAsync (this Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations operations, string accountName, string path, string destination, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.DataLake.Store.Models.FileOperationResult&gt; RenameAsync(class Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations operations, string accountName, string path, string destination, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Store.FileSystemOperationsExtensions.RenameAsync(Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member RenameAsync : Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataLake.Store.Models.FileOperationResult&gt;" Usage="Microsoft.Azure.Management.DataLake.Store.FileSystemOperationsExtensions.RenameAsync (operations, accountName, path, destination, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Store</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.DataLake.Store.FileSystemOperationsExtensions/&lt;RenameAsync&gt;d__41))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataLake.Store.Models.FileOperationResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations" RefType="this" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="path" Type="System.String" />
        <Parameter Name="destination" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="accountName">
            Das Azure Data Lake-Speicher-Konto zum Ausführen der Filesystem-Vorgänge auf.
            </param>
        <param name="path">
            Der Pfad des Data Lake-Speicher (beginnend mit '/') der Datei oder des Verzeichnisses zum Verschieben/umbenennen.
            </param>
        <param name="destination">
            Der Pfad zum Verschieben/Umbenennen der Datei oder einen Ordner an
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Benennt eine Datei oder ein Verzeichnis um.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SetAcl">
      <MemberSignature Language="C#" Value="public static void SetAcl (this Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations operations, string accountName, string path, string aclspec);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void SetAcl(class Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations operations, string accountName, string path, string aclspec) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Store.FileSystemOperationsExtensions.SetAcl(Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Sub SetAcl (operations As IFileSystemOperations, accountName As String, path As String, aclspec As String)" />
      <MemberSignature Language="F#" Value="static member SetAcl : Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations * string * string * string -&gt; unit" Usage="Microsoft.Azure.Management.DataLake.Store.FileSystemOperationsExtensions.SetAcl (operations, accountName, path, aclspec)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Store</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations" RefType="this" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="path" Type="System.String" />
        <Parameter Name="aclspec" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="accountName">
            Das Azure Data Lake-Speicher-Konto zum Ausführen der Filesystem-Vorgänge auf.
            </param>
        <param name="path">
            Der Pfad des Data Lake-Speicher (beginnend mit '/') der Datei oder des Verzeichnisses für das die ACL festgelegt.
            </param>
        <param name="aclspec">
            Die ACL-Spezifikation enthalten in der ACL-Erstellungsvorgänge im Format "[Standard:] Benutzer | Gruppe | andere:: R |-w |-X |-"
            </param>
        <summary>
            Legt die Zugriffssteuerungsliste (ACL) für eine Datei oder Ordner fest.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SetAclAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task SetAclAsync (this Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations operations, string accountName, string path, string aclspec, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task SetAclAsync(class Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations operations, string accountName, string path, string aclspec, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Store.FileSystemOperationsExtensions.SetAclAsync(Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member SetAclAsync : Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.DataLake.Store.FileSystemOperationsExtensions.SetAclAsync (operations, accountName, path, aclspec, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Store</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.DataLake.Store.FileSystemOperationsExtensions/&lt;SetAclAsync&gt;d__27))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations" RefType="this" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="path" Type="System.String" />
        <Parameter Name="aclspec" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="accountName">
            Das Azure Data Lake-Speicher-Konto zum Ausführen der Filesystem-Vorgänge auf.
            </param>
        <param name="path">
            Der Pfad des Data Lake-Speicher (beginnend mit '/') der Datei oder des Verzeichnisses für das die ACL festgelegt.
            </param>
        <param name="aclspec">
            Die ACL-Spezifikation enthalten in der ACL-Erstellungsvorgänge im Format "[Standard:] Benutzer | Gruppe | andere:: R |-w |-X |-"
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Legt die Zugriffssteuerungsliste (ACL) für eine Datei oder Ordner fest.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SetFileExpiry">
      <MemberSignature Language="C#" Value="public static void SetFileExpiry (this Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations operations, string accountName, string path, Microsoft.Azure.Management.DataLake.Store.Models.ExpiryOptionType expiryOption, Nullable&lt;long&gt; expireTime = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void SetFileExpiry(class Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations operations, string accountName, string path, valuetype Microsoft.Azure.Management.DataLake.Store.Models.ExpiryOptionType expiryOption, valuetype System.Nullable`1&lt;int64&gt; expireTime) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Store.FileSystemOperationsExtensions.SetFileExpiry(Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations,System.String,System.String,Microsoft.Azure.Management.DataLake.Store.Models.ExpiryOptionType,System.Nullable{System.Int64})" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Sub SetFileExpiry (operations As IFileSystemOperations, accountName As String, path As String, expiryOption As ExpiryOptionType, Optional expireTime As Nullable(Of Long) = null)" />
      <MemberSignature Language="F#" Value="static member SetFileExpiry : Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations * string * string * Microsoft.Azure.Management.DataLake.Store.Models.ExpiryOptionType * Nullable&lt;int64&gt; -&gt; unit" Usage="Microsoft.Azure.Management.DataLake.Store.FileSystemOperationsExtensions.SetFileExpiry (operations, accountName, path, expiryOption, expireTime)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Store</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations" RefType="this" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="path" Type="System.String" />
        <Parameter Name="expiryOption" Type="Microsoft.Azure.Management.DataLake.Store.Models.ExpiryOptionType" />
        <Parameter Name="expireTime" Type="System.Nullable&lt;System.Int64&gt;" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="accountName">
            Das Azure Data Lake-Speicher-Konto zum Ausführen der Filesystem-Vorgänge auf.
            </param>
        <param name="path">
            Der Pfad des Data Lake-Speicher (beginnend mit '/') der Datei für das Festlegen oder entfernen die Ablaufzeit.
            </param>
        <param name="expiryOption">
            Gibt den Typ der Ablauf für die Datei: 1. NeverExpire: ExpireTime wird ignoriert. 2. RelativeToNow: ExpireTime ist eine ganze Zahl in Millisekunden, die das Ablaufdatum relativ zum darstellt, wenn Dateiablauf aktualisiert wird. 3. RelativeToCreationDate: ExpireTime ist eine ganze Zahl in Millisekunden, die das Ablaufdatum relativ zur Erstellung der Datei darstellt.
            4. Absolute: ExpireTime ist eine ganze Zahl in Millisekunden, die als Timestamp Unix relativ zum 1/1/1970 00:00:00. Folgende Werte sind möglich: "NeverExpire", "RelativeToNow", "RelativeToCreationDate", "Absolute"
            </param>
        <param name="expireTime">
            Die Zeit, die die Datei abläuft, entspricht die ExpiryOption, die festgelegt wurde.
            </param>
        <summary>
            Entfernt die Ablaufzeit für die angegebene Datei ab oder legt sie fest. Dieser Vorgang kann nur für Dateien ausgeführt werden. Ordner werden nicht unterstützt.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SetFileExpiryAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task SetFileExpiryAsync (this Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations operations, string accountName, string path, Microsoft.Azure.Management.DataLake.Store.Models.ExpiryOptionType expiryOption, Nullable&lt;long&gt; expireTime = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task SetFileExpiryAsync(class Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations operations, string accountName, string path, valuetype Microsoft.Azure.Management.DataLake.Store.Models.ExpiryOptionType expiryOption, valuetype System.Nullable`1&lt;int64&gt; expireTime, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Store.FileSystemOperationsExtensions.SetFileExpiryAsync(Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations,System.String,System.String,Microsoft.Azure.Management.DataLake.Store.Models.ExpiryOptionType,System.Nullable{System.Int64},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member SetFileExpiryAsync : Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations * string * string * Microsoft.Azure.Management.DataLake.Store.Models.ExpiryOptionType * Nullable&lt;int64&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.DataLake.Store.FileSystemOperationsExtensions.SetFileExpiryAsync (operations, accountName, path, expiryOption, expireTime, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Store</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.DataLake.Store.FileSystemOperationsExtensions/&lt;SetFileExpiryAsync&gt;d__3))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations" RefType="this" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="path" Type="System.String" />
        <Parameter Name="expiryOption" Type="Microsoft.Azure.Management.DataLake.Store.Models.ExpiryOptionType" />
        <Parameter Name="expireTime" Type="System.Nullable&lt;System.Int64&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="accountName">
            Das Azure Data Lake-Speicher-Konto zum Ausführen der Filesystem-Vorgänge auf.
            </param>
        <param name="path">
            Der Pfad des Data Lake-Speicher (beginnend mit '/') der Datei für das Festlegen oder entfernen die Ablaufzeit.
            </param>
        <param name="expiryOption">
            Gibt den Typ der Ablauf für die Datei: 1. NeverExpire: ExpireTime wird ignoriert. 2. RelativeToNow: ExpireTime ist eine ganze Zahl in Millisekunden, die das Ablaufdatum relativ zum darstellt, wenn Dateiablauf aktualisiert wird. 3. RelativeToCreationDate: ExpireTime ist eine ganze Zahl in Millisekunden, die das Ablaufdatum relativ zur Erstellung der Datei darstellt.
            4. Absolute: ExpireTime ist eine ganze Zahl in Millisekunden, die als Timestamp Unix relativ zum 1/1/1970 00:00:00. Folgende Werte sind möglich: "NeverExpire", "RelativeToNow", "RelativeToCreationDate", "Absolute"
            </param>
        <param name="expireTime">
            Die Zeit, die die Datei abläuft, entspricht die ExpiryOption, die festgelegt wurde.
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Entfernt die Ablaufzeit für die angegebene Datei ab oder legt sie fest. Dieser Vorgang kann nur für Dateien ausgeführt werden. Ordner werden nicht unterstützt.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SetOwner">
      <MemberSignature Language="C#" Value="public static void SetOwner (this Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations operations, string accountName, string path, string owner = null, string group = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void SetOwner(class Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations operations, string accountName, string path, string owner, string group) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Store.FileSystemOperationsExtensions.SetOwner(Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations,System.String,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Sub SetOwner (operations As IFileSystemOperations, accountName As String, path As String, Optional owner As String = null, Optional group As String = null)" />
      <MemberSignature Language="F#" Value="static member SetOwner : Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations * string * string * string * string -&gt; unit" Usage="Microsoft.Azure.Management.DataLake.Store.FileSystemOperationsExtensions.SetOwner (operations, accountName, path, owner, group)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Store</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations" RefType="this" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="path" Type="System.String" />
        <Parameter Name="owner" Type="System.String" />
        <Parameter Name="group" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="accountName">
            Das Azure Data Lake-Speicher-Konto zum Ausführen der Filesystem-Vorgänge auf.
            </param>
        <param name="path">
            Der Pfad des Data Lake-Speicher (beginnend mit '/') der Datei oder des Verzeichnisses für die zum Festlegen des Besitzers.
            </param>
        <param name="owner">
            Die AAD-Objekt-ID des Benutzers Besitzers der Datei oder des Verzeichnisses. Falls leer, wird die Eigenschaft bleibt unverändert.
            </param>
        <param name="group">
            Die AAD-Objekt-ID der Besitzer der Gruppe der Datei oder des Verzeichnisses. Falls leer, wird die Eigenschaft bleibt unverändert.
            </param>
        <summary>
            Legt den Besitzer einer Datei oder eines Verzeichnisses fest.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SetOwnerAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task SetOwnerAsync (this Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations operations, string accountName, string path, string owner = null, string group = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task SetOwnerAsync(class Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations operations, string accountName, string path, string owner, string group, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Store.FileSystemOperationsExtensions.SetOwnerAsync(Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations,System.String,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member SetOwnerAsync : Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations * string * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.DataLake.Store.FileSystemOperationsExtensions.SetOwnerAsync (operations, accountName, path, owner, group, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Store</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.DataLake.Store.FileSystemOperationsExtensions/&lt;SetOwnerAsync&gt;d__43))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations" RefType="this" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="path" Type="System.String" />
        <Parameter Name="owner" Type="System.String" />
        <Parameter Name="group" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="accountName">
            Das Azure Data Lake-Speicher-Konto zum Ausführen der Filesystem-Vorgänge auf.
            </param>
        <param name="path">
            Der Pfad des Data Lake-Speicher (beginnend mit '/') der Datei oder des Verzeichnisses für die zum Festlegen des Besitzers.
            </param>
        <param name="owner">
            Die AAD-Objekt-ID des Benutzers Besitzers der Datei oder des Verzeichnisses. Falls leer, wird die Eigenschaft bleibt unverändert.
            </param>
        <param name="group">
            Die AAD-Objekt-ID der Besitzer der Gruppe der Datei oder des Verzeichnisses. Falls leer, wird die Eigenschaft bleibt unverändert.
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Legt den Besitzer einer Datei oder eines Verzeichnisses fest.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SetPermission">
      <MemberSignature Language="C#" Value="public static void SetPermission (this Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations operations, string accountName, string path, string permission = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void SetPermission(class Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations operations, string accountName, string path, string permission) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Store.FileSystemOperationsExtensions.SetPermission(Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Sub SetPermission (operations As IFileSystemOperations, accountName As String, path As String, Optional permission As String = null)" />
      <MemberSignature Language="F#" Value="static member SetPermission : Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations * string * string * string -&gt; unit" Usage="Microsoft.Azure.Management.DataLake.Store.FileSystemOperationsExtensions.SetPermission (operations, accountName, path, permission)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Store</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations" RefType="this" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="path" Type="System.String" />
        <Parameter Name="permission" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="accountName">
            Das Azure Data Lake-Speicher-Konto zum Ausführen der Filesystem-Vorgänge auf.
            </param>
        <param name="path">
            Der Pfad des Data Lake-Speicher (beginnend mit '/') der Datei oder des Verzeichnisses für die die Berechtigung festgelegt.
            </param>
        <param name="permission">
            Eine Zeichenfolgendarstellung der Berechtigung (d. h. "Rwx"). Wenn Sie leer ist, bleibt diese Eigenschaft unverändert.
            </param>
        <summary>
            Legt den Berechtigungssatz einer Datei oder eines Ordners.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SetPermissionAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task SetPermissionAsync (this Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations operations, string accountName, string path, string permission = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task SetPermissionAsync(class Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations operations, string accountName, string path, string permission, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Store.FileSystemOperationsExtensions.SetPermissionAsync(Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member SetPermissionAsync : Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.DataLake.Store.FileSystemOperationsExtensions.SetPermissionAsync (operations, accountName, path, permission, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Store</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.DataLake.Store.FileSystemOperationsExtensions/&lt;SetPermissionAsync&gt;d__45))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations" RefType="this" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="path" Type="System.String" />
        <Parameter Name="permission" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="accountName">
            Das Azure Data Lake-Speicher-Konto zum Ausführen der Filesystem-Vorgänge auf.
            </param>
        <param name="path">
            Der Pfad des Data Lake-Speicher (beginnend mit '/') der Datei oder des Verzeichnisses für die die Berechtigung festgelegt.
            </param>
        <param name="permission">
            Eine Zeichenfolgendarstellung der Berechtigung (d. h. "Rwx"). Wenn Sie leer ist, bleibt diese Eigenschaft unverändert.
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Legt den Berechtigungssatz einer Datei oder eines Ordners.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>