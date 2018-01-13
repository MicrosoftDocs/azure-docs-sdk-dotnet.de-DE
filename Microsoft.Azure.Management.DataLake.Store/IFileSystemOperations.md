<Type Name="IFileSystemOperations" FullName="Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations">
  <TypeSignature Language="C#" Value="public interface IFileSystemOperations" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IFileSystemOperations" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations" />
  <TypeSignature Language="VB.NET" Value="Public Interface IFileSystemOperations" />
  <TypeSignature Language="F#" Value="type IFileSystemOperations = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.DataLake.Store</AssemblyName>
    <AssemblyVersion>2.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            FileSystemOperations-Vorgänge.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="AppendWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt; AppendWithHttpMessagesAsync (string accountName, string path, System.IO.Stream streamContents, Nullable&lt;long&gt; offset = null, Nullable&lt;Microsoft.Azure.Management.DataLake.Store.Models.SyncFlag&gt; syncFlag = null, Nullable&lt;Guid&gt; leaseId = null, Nullable&lt;Guid&gt; fileSessionId = null, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse&gt; AppendWithHttpMessagesAsync(string accountName, string path, class System.IO.Stream streamContents, valuetype System.Nullable`1&lt;int64&gt; offset, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.DataLake.Store.Models.SyncFlag&gt; syncFlag, valuetype System.Nullable`1&lt;valuetype System.Guid&gt; leaseId, valuetype System.Nullable`1&lt;valuetype System.Guid&gt; fileSessionId, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations.AppendWithHttpMessagesAsync(System.String,System.String,System.IO.Stream,System.Nullable{System.Int64},System.Nullable{Microsoft.Azure.Management.DataLake.Store.Models.SyncFlag},System.Nullable{System.Guid},System.Nullable{System.Guid},System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member AppendWithHttpMessagesAsync : string * string * System.IO.Stream * Nullable&lt;int64&gt; * Nullable&lt;Microsoft.Azure.Management.DataLake.Store.Models.SyncFlag&gt; * Nullable&lt;Guid&gt; * Nullable&lt;Guid&gt; * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt;" Usage="iFileSystemOperations.AppendWithHttpMessagesAsync (accountName, path, streamContents, offset, syncFlag, leaseId, fileSessionId, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Store</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="path" Type="System.String" />
        <Parameter Name="streamContents" Type="System.IO.Stream" />
        <Parameter Name="offset" Type="System.Nullable&lt;System.Int64&gt;" />
        <Parameter Name="syncFlag" Type="System.Nullable&lt;Microsoft.Azure.Management.DataLake.Store.Models.SyncFlag&gt;" />
        <Parameter Name="leaseId" Type="System.Nullable&lt;System.Guid&gt;" />
        <Parameter Name="fileSessionId" Type="System.Nullable&lt;System.Guid&gt;" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
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
            Der optionale Offset in den Stream den Anfügevorgang zu beginnen.
            Standardmäßig werden am Ende des Streams angefügt werden soll.
            </param>
        <param name="syncFlag">
            Optional gibt an, was nach Abschluss der gleichzeitigen anfügen. Daten angeben, dass mehr Daten sofort vom Client gesendet werden werden, das Dateihandle, Open/gesperrt verbleiben sollte und Dateimetadaten (einschließlich Dateilänge, Uhrzeit der letzten Änderung) sollten nicht aktualisiert. Metadaten gibt an, dass mehr Daten sofort vom Client gesendet werden werden, das Dateihandle, Open/gesperrt verbleiben sollte und Dateimetadaten sollte aktualisiert. Schließen gibt an, dass der Client sendende von Daten erfolgt und das Dateihandle geschlossen/entsperrt muss Dateimetadaten sollte aktualisiert. Folgende Werte sind möglich: "Daten", "Metadaten", "Schließen"
            </param>
        <param name="leaseId">
            Optionale eindeutige GUID pro Datei an, um einzelne Writer-Semantik, was bedeutet, dass nur Clients, die an die Datei mit der gleichen LeaseId anfügen dazu berechtigt sein, sicherzustellen.
            </param>
        <param name="fileSessionId">
            Optionale eindeutige GUID pro Datei, die alle angibt, die mit dem gleichen fügt FileSessionId werden aus dem gleichen Client und der gleichen Sitzung. Dadurch erhalten einen Leistungsvorteil, wenn SyncFlag Daten oder Metadaten ist.
            </param>
        <param name="customHeaders">
            Die Header, die hinzugefügt werden auf Anforderung.
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Verwendet für Serial an die angegebene Datei angefügt. Hinweis: Das Ziel darf nicht von ConcurrentAppend hinzugefügte Daten. ConcurrentAppend und anfügen kann synonym verwendet werden. Sobald eine Zieldatei geändert wurde mit einer von beiden Optionen anfügen, die Append-Option kann nicht auf die Zieldatei nicht verwendet werden.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Azure.Management.DataLake.Store.Models.AdlsErrorException">
            Wird ausgelöst, wenn der Vorgang einen ungültigen Statuscode zurückgegeben hat.
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            Wird ausgelöst, wenn ein erforderlicher Parameter null ist.
            </exception>
      </Docs>
    </Member>
    <Member MemberName="CheckAccessWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt; CheckAccessWithHttpMessagesAsync (string accountName, string path, string fsaction, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse&gt; CheckAccessWithHttpMessagesAsync(string accountName, string path, string fsaction, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations.CheckAccessWithHttpMessagesAsync(System.String,System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member CheckAccessWithHttpMessagesAsync : string * string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt;" Usage="iFileSystemOperations.CheckAccessWithHttpMessagesAsync (accountName, path, fsaction, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Store</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="path" Type="System.String" />
        <Parameter Name="fsaction" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="accountName">
            Das Azure Data Lake-Speicher-Konto zum Ausführen der Filesystem-Vorgänge auf.
            </param>
        <param name="path">
            Der Pfad des Data Lake-Speicher (beginnend mit '/') der Datei oder des Verzeichnisses für den Zugriff zu überprüfen.
            </param>
        <param name="fsaction">
            In Form einer Zeichenfolge, übereinstimmende Regex-Muster System Vorgang Lese-/Schreib-/ausführungs-als Datei "[Rwx-] \ {3\}"
            </param>
        <param name="customHeaders">
            Die Header, die hinzugefügt werden auf Anforderung.
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Überprüft, ob der angegebene Zugriff im angegebenen Pfad verfügbar ist.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Azure.Management.DataLake.Store.Models.AdlsErrorException">
            Wird ausgelöst, wenn der Vorgang einen ungültigen Statuscode zurückgegeben hat.
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            Wird ausgelöst, wenn ein erforderlicher Parameter null ist.
            </exception>
      </Docs>
    </Member>
    <Member MemberName="ConcatWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt; ConcatWithHttpMessagesAsync (string accountName, string path, System.Collections.Generic.IList&lt;string&gt; sources, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse&gt; ConcatWithHttpMessagesAsync(string accountName, string path, class System.Collections.Generic.IList`1&lt;string&gt; sources, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations.ConcatWithHttpMessagesAsync(System.String,System.String,System.Collections.Generic.IList{System.String},System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ConcatWithHttpMessagesAsync : string * string * System.Collections.Generic.IList&lt;string&gt; * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt;" Usage="iFileSystemOperations.ConcatWithHttpMessagesAsync (accountName, path, sources, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Store</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="path" Type="System.String" />
        <Parameter Name="sources" Type="System.Collections.Generic.IList&lt;System.String&gt;" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="accountName">
            Das Azure Data Lake-Speicher-Konto zum Ausführen der Filesystem-Vorgänge auf.
            </param>
        <param name="path">
            Der Pfad des Data Lake-Speicher (beginnend mit '/') der Zieldatei, die sich aus der Verkettung ergibt.
            </param>
        <param name="sources">
            Eine Liste von durch Trennzeichen getrennt Data Lake-Speicher-Pfade (beginnend mit '/') der Dateien, die in der Reihenfolge verkettet, in dem sie verkettet werden soll.
            </param>
        <param name="customHeaders">
            Die Header, die hinzugefügt werden auf Anforderung.
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Verkettet die Liste der Quelldateien in der Zieldatei, die alle Quelldateien bei Erfolg wird entfernt.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Azure.Management.DataLake.Store.Models.AdlsErrorException">
            Wird ausgelöst, wenn der Vorgang einen ungültigen Statuscode zurückgegeben hat.
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            Wird ausgelöst, wenn ein erforderlicher Parameter null ist.
            </exception>
      </Docs>
    </Member>
    <Member MemberName="ConcurrentAppendWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt; ConcurrentAppendWithHttpMessagesAsync (string accountName, string path, System.IO.Stream streamContents, Nullable&lt;Microsoft.Azure.Management.DataLake.Store.Models.AppendModeType&gt; appendMode = null, Nullable&lt;Microsoft.Azure.Management.DataLake.Store.Models.SyncFlag&gt; syncFlag = null, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse&gt; ConcurrentAppendWithHttpMessagesAsync(string accountName, string path, class System.IO.Stream streamContents, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.DataLake.Store.Models.AppendModeType&gt; appendMode, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.DataLake.Store.Models.SyncFlag&gt; syncFlag, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations.ConcurrentAppendWithHttpMessagesAsync(System.String,System.String,System.IO.Stream,System.Nullable{Microsoft.Azure.Management.DataLake.Store.Models.AppendModeType},System.Nullable{Microsoft.Azure.Management.DataLake.Store.Models.SyncFlag},System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ConcurrentAppendWithHttpMessagesAsync : string * string * System.IO.Stream * Nullable&lt;Microsoft.Azure.Management.DataLake.Store.Models.AppendModeType&gt; * Nullable&lt;Microsoft.Azure.Management.DataLake.Store.Models.SyncFlag&gt; * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt;" Usage="iFileSystemOperations.ConcurrentAppendWithHttpMessagesAsync (accountName, path, streamContents, appendMode, syncFlag, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Store</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="path" Type="System.String" />
        <Parameter Name="streamContents" Type="System.IO.Stream" />
        <Parameter Name="appendMode" Type="System.Nullable&lt;Microsoft.Azure.Management.DataLake.Store.Models.AppendModeType&gt;" />
        <Parameter Name="syncFlag" Type="System.Nullable&lt;Microsoft.Azure.Management.DataLake.Store.Models.SyncFlag&gt;" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
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
            Optional gibt an, was nach Abschluss der gleichzeitigen anfügen. Daten angeben, dass mehr Daten sofort vom Client gesendet werden werden, das Dateihandle, Open/gesperrt verbleiben sollte und Dateimetadaten (einschließlich Dateilänge, Uhrzeit der letzten Änderung) sollten nicht aktualisiert. Metadaten gibt an, dass mehr Daten sofort vom Client gesendet werden werden, das Dateihandle, Open/gesperrt verbleiben sollte und Dateimetadaten sollte aktualisiert. Schließen gibt an, dass der Client sendende von Daten erfolgt und das Dateihandle geschlossen/entsperrt muss Dateimetadaten sollte aktualisiert. Folgende Werte sind möglich: "Daten", "Metadaten", "Schließen"
            </param>
        <param name="customHeaders">
            Die Header, die hinzugefügt werden auf Anforderung.
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Fügt an die angegebene Datei und optional die Datei erstmalig erstellen, wenn sie noch nicht vorhanden ist. Diese Methode unterstützt mehrere gleichzeitige an die Datei angefügt. Hinweis: Das Ziel darf nicht von CREATE- oder normale (seriell) anfügen hinzugefügte Daten. ConcurrentAppend und anfügen kann synonym verwendet werden. Sobald eine Zieldatei geändert wurde mit einer von beiden Optionen anfügen, die Append-Option kann nicht auf die Zieldatei nicht verwendet werden. ConcurrentAppend garantiert nicht die Reihenfolge und doppelt vorhandenen Daten in der Zieldatei landing zu kann.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Azure.Management.DataLake.Store.Models.AdlsErrorException">
            Wird ausgelöst, wenn der Vorgang einen ungültigen Statuscode zurückgegeben hat.
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            Wird ausgelöst, wenn ein erforderlicher Parameter null ist.
            </exception>
      </Docs>
    </Member>
    <Member MemberName="CreateWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt; CreateWithHttpMessagesAsync (string accountName, string path, System.IO.Stream streamContents = null, Nullable&lt;bool&gt; overwrite = null, Nullable&lt;Microsoft.Azure.Management.DataLake.Store.Models.SyncFlag&gt; syncFlag = null, Nullable&lt;Guid&gt; leaseId = null, Nullable&lt;int&gt; permission = null, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse&gt; CreateWithHttpMessagesAsync(string accountName, string path, class System.IO.Stream streamContents, valuetype System.Nullable`1&lt;bool&gt; overwrite, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.DataLake.Store.Models.SyncFlag&gt; syncFlag, valuetype System.Nullable`1&lt;valuetype System.Guid&gt; leaseId, valuetype System.Nullable`1&lt;int32&gt; permission, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations.CreateWithHttpMessagesAsync(System.String,System.String,System.IO.Stream,System.Nullable{System.Boolean},System.Nullable{Microsoft.Azure.Management.DataLake.Store.Models.SyncFlag},System.Nullable{System.Guid},System.Nullable{System.Int32},System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member CreateWithHttpMessagesAsync : string * string * System.IO.Stream * Nullable&lt;bool&gt; * Nullable&lt;Microsoft.Azure.Management.DataLake.Store.Models.SyncFlag&gt; * Nullable&lt;Guid&gt; * Nullable&lt;int&gt; * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt;" Usage="iFileSystemOperations.CreateWithHttpMessagesAsync (accountName, path, streamContents, overwrite, syncFlag, leaseId, permission, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Store</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="path" Type="System.String" />
        <Parameter Name="streamContents" Type="System.IO.Stream" />
        <Parameter Name="overwrite" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="syncFlag" Type="System.Nullable&lt;Microsoft.Azure.Management.DataLake.Store.Models.SyncFlag&gt;" />
        <Parameter Name="leaseId" Type="System.Nullable&lt;System.Guid&gt;" />
        <Parameter Name="permission" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
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
            Optional gibt an, was nach Abschluss des erstellen.
            Daten angeben, dass mehr Daten sofort vom Client gesendet werden werden, das Dateihandle, Open/gesperrt verbleiben sollte und Dateimetadaten (einschließlich Dateilänge, Uhrzeit der letzten Änderung) sollten nicht aktualisiert. Metadaten gibt an, dass mehr Daten sofort vom Client gesendet werden werden, das Dateihandle, Open/gesperrt verbleiben sollte und Dateimetadaten sollte aktualisiert. Schließen gibt an, dass der Client sendende von Daten erfolgt und das Dateihandle geschlossen/entsperrt muss Dateimetadaten sollte aktualisiert. Folgende Werte sind möglich: "Daten", "Metadaten", "Schließen"
            </param>
        <param name="leaseId">
            Optionale eindeutige GUID pro Datei an, um einzelne Writer-Semantik, was bedeutet, dass nur Clients, die an die Datei mit der gleichen LeaseId anfügen dazu berechtigt sein, sicherzustellen.
            </param>
        <param name="permission">
            Die oktale Darstellung der unbenannten Benutzer, Subnetzmaske und andere Berechtigungen, die für die Datei, die beim Erstellen festgelegt werden soll. Wenn nicht angegeben ist, erbt er diese aus dem Container.
            </param>
        <param name="customHeaders">
            Die Header, die hinzugefügt werden auf Anforderung.
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Erstellt eine Datei mit den optional angegebenen Inhalt. Hinweis: Wenn Inhalte bereitgestellt wird, kann die resultierende Datei geändert werden ConcurrentAppend verwenden.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Azure.Management.DataLake.Store.Models.AdlsErrorException">
            Wird ausgelöst, wenn der Vorgang einen ungültigen Statuscode zurückgegeben hat.
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            Wird ausgelöst, wenn ein erforderlicher Parameter null ist.
            </exception>
      </Docs>
    </Member>
    <Member MemberName="DeleteWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.DataLake.Store.Models.FileOperationResult&gt;&gt; DeleteWithHttpMessagesAsync (string accountName, string path, Nullable&lt;bool&gt; recursive = null, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Management.DataLake.Store.Models.FileOperationResult&gt;&gt; DeleteWithHttpMessagesAsync(string accountName, string path, valuetype System.Nullable`1&lt;bool&gt; recursive, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations.DeleteWithHttpMessagesAsync(System.String,System.String,System.Nullable{System.Boolean},System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member DeleteWithHttpMessagesAsync : string * string * Nullable&lt;bool&gt; * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.DataLake.Store.Models.FileOperationResult&gt;&gt;" Usage="iFileSystemOperations.DeleteWithHttpMessagesAsync (accountName, path, recursive, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Store</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.DataLake.Store.Models.FileOperationResult&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="path" Type="System.String" />
        <Parameter Name="recursive" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="accountName">
            Das Azure Data Lake-Speicher-Konto zum Ausführen der Filesystem-Vorgänge auf.
            </param>
        <param name="path">
            Der Pfad des Data Lake-Speicher (beginnend mit '/') der Datei oder eines Verzeichnisses gelöscht.
            </param>
        <param name="recursive">
            Der Optionaler Schalter, der angibt, ob der Löschvorgang rekursiv sein soll
            </param>
        <param name="customHeaders">
            Die Header, die hinzugefügt werden auf Anforderung.
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Die angeforderte Datei oder Verzeichnis und optional rekursiv gelöscht.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Azure.Management.DataLake.Store.Models.AdlsErrorException">
            Wird ausgelöst, wenn der Vorgang einen ungültigen Statuscode zurückgegeben hat.
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            Wird ausgelöst, wenn nicht die Antwort zu deserialisieren.
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            Wird ausgelöst, wenn ein erforderlicher Parameter null ist.
            </exception>
      </Docs>
    </Member>
    <Member MemberName="DownloadFile">
      <MemberSignature Language="C#" Value="public void DownloadFile (string accountName, string sourcePath, string destinationPath, int threadCount = -1, bool resume = false, bool overwrite = false, IProgress&lt;Microsoft.Azure.Management.DataLake.Store.TransferProgress&gt; progressTracker = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void DownloadFile(string accountName, string sourcePath, string destinationPath, int32 threadCount, bool resume, bool overwrite, class System.IProgress`1&lt;class Microsoft.Azure.Management.DataLake.Store.TransferProgress&gt; progressTracker, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations.DownloadFile(System.String,System.String,System.String,System.Int32,System.Boolean,System.Boolean,System.IProgress{Microsoft.Azure.Management.DataLake.Store.TransferProgress},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member DownloadFile : string * string * string * int * bool * bool * IProgress&lt;Microsoft.Azure.Management.DataLake.Store.TransferProgress&gt; * System.Threading.CancellationToken -&gt; unit" Usage="iFileSystemOperations.DownloadFile (accountName, sourcePath, destinationPath, threadCount, resume, overwrite, progressTracker, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Store</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="sourcePath" Type="System.String" />
        <Parameter Name="destinationPath" Type="System.String" />
        <Parameter Name="threadCount" Type="System.Int32" />
        <Parameter Name="resume" Type="System.Boolean" />
        <Parameter Name="overwrite" Type="System.Boolean" />
        <Parameter Name="progressTracker" Type="System.IProgress&lt;Microsoft.Azure.Management.DataLake.Store.TransferProgress&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="accountName">
            Das Azure Data Lake-Speicher-Konto zum Ausführen der Filesystem-Vorgänge auf.
            </param>
        <param name="sourcePath">
            Der Pfad des Data Lake-Speicher (beginnend mit '/') der herunterzuladenden Datei.
            </param>
        <param name="destinationPath">
            Der lokale Pfad zum Herunterladen der Datei an. Wenn ein Verzeichnis angegeben ist, wird der Dateiname der Name der Quelldatei identisch werden
            </param>
        <param name="threadCount">
            Die maximale Anzahl von Threads zur Verwendung während des Downloads. Standardmäßig wird diese Anzahl basierend auf der Größe berechnet werden.
            </param>
        <param name="resume">
            Einem Switch, der angibt, ob dieser Download eine Fortsetzung eines vorherigen, fehlgeschlagenen Downloads ist. Die Standardeinstellung ist "false".
            </param>
        <param name="overwrite">
            Ein Switch, der angibt, in diesem Download überschreiben soll, die die Zieldatei, falls vorhanden. Standardwert ist "false", und der Download schnelle Fehler aus, wenn die Zieldatei vorhanden ist.
            </param>
        <param name="progressTracker">
            Ein Optionaler Delegat, der verwendet werden kann, um den Status des Downloadvorgangs asynchron zu verfolgen.
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Lädt eine Datei aus dem angegebenen Data Lake-Speicher-Konto an.
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Azure.Management.DataLake.Store.Models.AdlsErrorException">
            Wird ausgelöst, wenn der Vorgang einen ungültigen Statuscode zurückgegeben hat.
            </exception>
        <exception cref="T:System.Threading.Tasks.TaskCanceledException">
            Wird ausgelöst, wenn der Vorgang zu lange dauert oder wenn der Benutzer explizit abbricht.
            </exception>
        <exception cref="T:Microsoft.Azure.Management.DataLake.Store.InvalidMetadataException">
            Wird ausgelöst, wenn Resume Metadaten beschädigt oder nicht dem aktuellen Vorgang zugeordnet ist.
            </exception>
        <exception cref="T:System.IO.FileNotFoundException">
            Wird ausgelöst, wenn der Quellpfad nicht gefunden werden kann.
            </exception>
        <exception cref="T:System.InvalidOperationException">
            Wird ausgelöst, wenn ein ungültiger Download ausgeführt wird oder eine Datei extern, während des Vorgangs geändert wird.
            </exception>
        <exception cref="T:Microsoft.Azure.Management.DataLake.Store.TransferFailedException">
            Wird ausgelöst, wenn die Übertragung fehl.
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            Wird ausgelöst, wenn nicht die Antwort zu deserialisieren.
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            Wird ausgelöst, wenn ein erforderlicher Parameter null ist.
            </exception>
      </Docs>
    </Member>
    <Member MemberName="DownloadFolder">
      <MemberSignature Language="C#" Value="public void DownloadFolder (string accountName, string sourcePath, string destinationPath, int perFileThreadCount = -1, int concurrentFileCount = -1, bool resume = false, bool overwrite = false, bool recurse = false, IProgress&lt;Microsoft.Azure.Management.DataLake.Store.TransferFolderProgress&gt; progressTracker = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void DownloadFolder(string accountName, string sourcePath, string destinationPath, int32 perFileThreadCount, int32 concurrentFileCount, bool resume, bool overwrite, bool recurse, class System.IProgress`1&lt;class Microsoft.Azure.Management.DataLake.Store.TransferFolderProgress&gt; progressTracker, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations.DownloadFolder(System.String,System.String,System.String,System.Int32,System.Int32,System.Boolean,System.Boolean,System.Boolean,System.IProgress{Microsoft.Azure.Management.DataLake.Store.TransferFolderProgress},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member DownloadFolder : string * string * string * int * int * bool * bool * bool * IProgress&lt;Microsoft.Azure.Management.DataLake.Store.TransferFolderProgress&gt; * System.Threading.CancellationToken -&gt; unit" Usage="iFileSystemOperations.DownloadFolder (accountName, sourcePath, destinationPath, perFileThreadCount, concurrentFileCount, resume, overwrite, recurse, progressTracker, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Store</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="sourcePath" Type="System.String" />
        <Parameter Name="destinationPath" Type="System.String" />
        <Parameter Name="perFileThreadCount" Type="System.Int32" />
        <Parameter Name="concurrentFileCount" Type="System.Int32" />
        <Parameter Name="resume" Type="System.Boolean" />
        <Parameter Name="overwrite" Type="System.Boolean" />
        <Parameter Name="recurse" Type="System.Boolean" />
        <Parameter Name="progressTracker" Type="System.IProgress&lt;Microsoft.Azure.Management.DataLake.Store.TransferFolderProgress&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="accountName">
            Das Azure Data Lake-Speicher-Konto zum Ausführen der Filesystem-Vorgänge auf.
            </param>
        <param name="sourcePath">
            Der Pfad des Data Lake-Speicher (beginnend mit "/") des Verzeichnisses, das herunterladen.
            </param>
        <param name="destinationPath">
            Der lokale Pfad auf den Ordner herunterladen.
            </param>
        <param name="perFileThreadCount">
            Die maximale Anzahl von Threads pro Datei während des Downloads zu verwenden. Standardmäßig wird diese Anzahl basierend auf den Ordner-Struktur und die durchschnittliche Größe berechnet werden.
            </param>
        <param name="concurrentFileCount">
            Die maximale Anzahl von gleichzeitig Herunterzuladende Dateien. Standardmäßig wird diese Anzahl basierend auf den Schritt die Ordnerstruktur und die Anzahl der Dateien berechnet werden.
            </param>
        <param name="resume">
            Einem Switch, der angibt, ob dieser Download eine Fortsetzung eines vorherigen, fehlgeschlagenen Downloads ist. Die Standardeinstellung ist "false".
            </param>
        <param name="overwrite">
            Ein Switch, der angibt, in diesem Download sollte den Inhalt des Zielverzeichnisses überschreiben, falls vorhanden. Standardwert ist "false", und der Download schneller Fehler aus, wenn am Zielspeicherort vorhanden ist.
            </param>
        <param name="recurse">
            Ein Switch, der angibt, in diesem Download sollte die Quelle Verzeichnis rekursiv oder nur die oberste Ebene heruntergeladen werden. Standardwert ist "false", nur die oberste Ebene heruntergeladen werden sollen.
            </param>
        <param name="progressTracker">
            Ein Optionaler Delegat, der verwendet werden kann, um den Status des Downloadvorgangs asynchron zu verfolgen.
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Lädt einen Ordner aus dem angegebenen Data Lake-Speicher-Konto an.
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Azure.Management.DataLake.Store.Models.AdlsErrorException">
            Wird ausgelöst, wenn der Vorgang einen ungültigen Statuscode zurückgegeben hat.
            </exception>
        <exception cref="T:System.Threading.Tasks.TaskCanceledException">
            Wird ausgelöst, wenn der Vorgang zu lange dauert oder wenn der Benutzer explizit abbricht.
            </exception>
        <exception cref="T:Microsoft.Azure.Management.DataLake.Store.InvalidMetadataException">
            Wird ausgelöst, wenn Resume Metadaten beschädigt oder nicht dem aktuellen Vorgang zugeordnet ist.
            </exception>
        <exception cref="T:System.IO.FileNotFoundException">
            Wird ausgelöst, wenn der Quellpfad nicht gefunden werden kann.
            </exception>
        <exception cref="T:System.InvalidOperationException">
            Wird ausgelöst, wenn ein ungültiger Download ausgeführt wird oder ein Datei bzw. der Ordner wird während des Vorgangs extern geändert.
            </exception>
        <exception cref="T:Microsoft.Azure.Management.DataLake.Store.TransferFailedException">
            Wird ausgelöst, wenn die Übertragung fehl.
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            Wird ausgelöst, wenn nicht die Antwort zu deserialisieren.
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            Wird ausgelöst, wenn ein erforderlicher Parameter null ist.
            </exception>
      </Docs>
    </Member>
    <Member MemberName="GetAclStatusWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.DataLake.Store.Models.AclStatusResult&gt;&gt; GetAclStatusWithHttpMessagesAsync (string accountName, string path, Nullable&lt;bool&gt; tooId = null, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Management.DataLake.Store.Models.AclStatusResult&gt;&gt; GetAclStatusWithHttpMessagesAsync(string accountName, string path, valuetype System.Nullable`1&lt;bool&gt; tooId, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations.GetAclStatusWithHttpMessagesAsync(System.String,System.String,System.Nullable{System.Boolean},System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetAclStatusWithHttpMessagesAsync : string * string * Nullable&lt;bool&gt; * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.DataLake.Store.Models.AclStatusResult&gt;&gt;" Usage="iFileSystemOperations.GetAclStatusWithHttpMessagesAsync (accountName, path, tooId, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Store</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.DataLake.Store.Models.AclStatusResult&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="path" Type="System.String" />
        <Parameter Name="tooId" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="accountName">
            Das Azure Data Lake-Speicher-Konto zum Ausführen der Filesystem-Vorgänge auf.
            </param>
        <param name="path">
            Der Pfad des Data Lake-Speicher (beginnend mit '/') der Datei oder des Verzeichnisses für den die ACL abgerufen.
            </param>
        <param name="tooId">
            Ein Optionaler Schalter benutzerfreundliche Namen anstelle von Objekt-ID für die ACL-Einträge zurückgegeben. Tooid = "false" gibt die Anzeigenamen statt die AAD-Objekt-ID. Standardwert ist "true" Zurückgeben von AAD-Objekt-IDs.
            </param>
        <param name="customHeaders">
            Die Header, die hinzugefügt werden auf Anforderung.
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Ruft die Einträge (Access Control List, ACL) für die angegebene Datei oder das Verzeichnis ab.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Azure.Management.DataLake.Store.Models.AdlsErrorException">
            Wird ausgelöst, wenn der Vorgang einen ungültigen Statuscode zurückgegeben hat.
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            Wird ausgelöst, wenn nicht die Antwort zu deserialisieren.
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            Wird ausgelöst, wenn ein erforderlicher Parameter null ist.
            </exception>
      </Docs>
    </Member>
    <Member MemberName="GetContentSummaryWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.DataLake.Store.Models.ContentSummaryResult&gt;&gt; GetContentSummaryWithHttpMessagesAsync (string accountName, string path, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Management.DataLake.Store.Models.ContentSummaryResult&gt;&gt; GetContentSummaryWithHttpMessagesAsync(string accountName, string path, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations.GetContentSummaryWithHttpMessagesAsync(System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetContentSummaryWithHttpMessagesAsync : string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.DataLake.Store.Models.ContentSummaryResult&gt;&gt;" Usage="iFileSystemOperations.GetContentSummaryWithHttpMessagesAsync (accountName, path, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Store</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.DataLake.Store.Models.ContentSummaryResult&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="path" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="accountName">
            Das Azure Data Lake-Speicher-Konto zum Ausführen der Filesystem-Vorgänge auf.
            </param>
        <param name="path">
            Der Pfad des Data Lake-Speicher (beginnend mit '/') der Datei für die Zusammenfassung des abzurufen.
            </param>
        <param name="customHeaders">
            Die Header, die hinzugefügt werden auf Anforderung.
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Ruft den Inhalt Zusammenfassung Objekt "Datei" angegeben werden, indem der Dateipfad ab.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Azure.Management.DataLake.Store.Models.AdlsErrorException">
            Wird ausgelöst, wenn der Vorgang einen ungültigen Statuscode zurückgegeben hat.
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            Wird ausgelöst, wenn nicht die Antwort zu deserialisieren.
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            Wird ausgelöst, wenn ein erforderlicher Parameter null ist.
            </exception>
      </Docs>
    </Member>
    <Member MemberName="GetFileStatusWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.DataLake.Store.Models.FileStatusResult&gt;&gt; GetFileStatusWithHttpMessagesAsync (string accountName, string path, Nullable&lt;bool&gt; tooId = null, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Management.DataLake.Store.Models.FileStatusResult&gt;&gt; GetFileStatusWithHttpMessagesAsync(string accountName, string path, valuetype System.Nullable`1&lt;bool&gt; tooId, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations.GetFileStatusWithHttpMessagesAsync(System.String,System.String,System.Nullable{System.Boolean},System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetFileStatusWithHttpMessagesAsync : string * string * Nullable&lt;bool&gt; * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.DataLake.Store.Models.FileStatusResult&gt;&gt;" Usage="iFileSystemOperations.GetFileStatusWithHttpMessagesAsync (accountName, path, tooId, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Store</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.DataLake.Store.Models.FileStatusResult&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="path" Type="System.String" />
        <Parameter Name="tooId" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="accountName">
            Das Azure Data Lake-Speicher-Konto zum Ausführen der Filesystem-Vorgänge auf.
            </param>
        <param name="path">
            Der Pfad des Data Lake-Speicher (beginnend mit '/') der Datei oder des Verzeichnisses für das Abrufen des Status.
            </param>
        <param name="tooId">
            Ein Optionaler Schalter zum Zurückgeben von Anzeigenamen anstelle der Besitzer und die Gruppe. Tooid = "false" gibt die Anzeigenamen statt die AAD-Objekt-ID. Standardwert ist "true" Zurückgeben von AAD-Objekt-IDs.
            </param>
        <param name="customHeaders">
            Die Header, die hinzugefügt werden auf Anforderung.
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Erhalten Sie das Objekt "Datei" Status durch den Dateipfad angegeben.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Azure.Management.DataLake.Store.Models.AdlsErrorException">
            Wird ausgelöst, wenn der Vorgang einen ungültigen Statuscode zurückgegeben hat.
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            Wird ausgelöst, wenn nicht die Antwort zu deserialisieren.
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            Wird ausgelöst, wenn ein erforderlicher Parameter null ist.
            </exception>
      </Docs>
    </Member>
    <Member MemberName="ListFileStatusWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.DataLake.Store.Models.FileStatusesResult&gt;&gt; ListFileStatusWithHttpMessagesAsync (string accountName, string path, Nullable&lt;int&gt; listSize = null, string listAfter = null, string listBefore = null, Nullable&lt;bool&gt; tooId = null, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Management.DataLake.Store.Models.FileStatusesResult&gt;&gt; ListFileStatusWithHttpMessagesAsync(string accountName, string path, valuetype System.Nullable`1&lt;int32&gt; listSize, string listAfter, string listBefore, valuetype System.Nullable`1&lt;bool&gt; tooId, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations.ListFileStatusWithHttpMessagesAsync(System.String,System.String,System.Nullable{System.Int32},System.String,System.String,System.Nullable{System.Boolean},System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListFileStatusWithHttpMessagesAsync : string * string * Nullable&lt;int&gt; * string * string * Nullable&lt;bool&gt; * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.DataLake.Store.Models.FileStatusesResult&gt;&gt;" Usage="iFileSystemOperations.ListFileStatusWithHttpMessagesAsync (accountName, path, listSize, listAfter, listBefore, tooId, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Store</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.DataLake.Store.Models.FileStatusesResult&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="path" Type="System.String" />
        <Parameter Name="listSize" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="listAfter" Type="System.String" />
        <Parameter Name="listBefore" Type="System.String" />
        <Parameter Name="tooId" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
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
            Ein Optionaler Schalter zum Zurückgeben von Anzeigenamen anstelle der Besitzer und die Gruppe. Tooid = "false" gibt die Anzeigenamen statt die AAD-Objekt-ID. Standardwert ist "true" Zurückgeben von AAD-Objekt-IDs.
            </param>
        <param name="customHeaders">
            Die Header, die hinzugefügt werden auf Anforderung.
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Rufen Sie die Liste von Objekten durch den Dateipfad, mit optionalen Paginierung-Parameter angegebene status
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Azure.Management.DataLake.Store.Models.AdlsErrorException">
            Wird ausgelöst, wenn der Vorgang einen ungültigen Statuscode zurückgegeben hat.
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            Wird ausgelöst, wenn nicht die Antwort zu deserialisieren.
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            Wird ausgelöst, wenn ein erforderlicher Parameter null ist.
            </exception>
      </Docs>
    </Member>
    <Member MemberName="MkdirsWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.DataLake.Store.Models.FileOperationResult&gt;&gt; MkdirsWithHttpMessagesAsync (string accountName, string path, Nullable&lt;int&gt; permission = null, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Management.DataLake.Store.Models.FileOperationResult&gt;&gt; MkdirsWithHttpMessagesAsync(string accountName, string path, valuetype System.Nullable`1&lt;int32&gt; permission, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations.MkdirsWithHttpMessagesAsync(System.String,System.String,System.Nullable{System.Int32},System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member MkdirsWithHttpMessagesAsync : string * string * Nullable&lt;int&gt; * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.DataLake.Store.Models.FileOperationResult&gt;&gt;" Usage="iFileSystemOperations.MkdirsWithHttpMessagesAsync (accountName, path, permission, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Store</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.DataLake.Store.Models.FileOperationResult&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="path" Type="System.String" />
        <Parameter Name="permission" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="accountName">
            Das Azure Data Lake-Speicher-Konto zum Ausführen der Filesystem-Vorgänge auf.
            </param>
        <param name="path">
            Der Pfad des Data Lake-Speicher (beginnend mit '/') der das zu erstellende Verzeichnis.
            </param>
        <param name="permission">
            Optionale oktale Berechtigung, die mit dem Verzeichnis erstellt werden soll.
            </param>
        <param name="customHeaders">
            Die Header, die hinzugefügt werden auf Anforderung.
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Erstellt ein Verzeichnis.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Azure.Management.DataLake.Store.Models.AdlsErrorException">
            Wird ausgelöst, wenn der Vorgang einen ungültigen Statuscode zurückgegeben hat.
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            Wird ausgelöst, wenn nicht die Antwort zu deserialisieren.
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            Wird ausgelöst, wenn ein erforderlicher Parameter null ist.
            </exception>
      </Docs>
    </Member>
    <Member MemberName="ModifyAclEntriesWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt; ModifyAclEntriesWithHttpMessagesAsync (string accountName, string path, string aclspec, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse&gt; ModifyAclEntriesWithHttpMessagesAsync(string accountName, string path, string aclspec, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations.ModifyAclEntriesWithHttpMessagesAsync(System.String,System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ModifyAclEntriesWithHttpMessagesAsync : string * string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt;" Usage="iFileSystemOperations.ModifyAclEntriesWithHttpMessagesAsync (accountName, path, aclspec, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Store</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="path" Type="System.String" />
        <Parameter Name="aclspec" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="accountName">
            Das Azure Data Lake-Speicher-Konto zum Ausführen der Filesystem-Vorgänge auf.
            </param>
        <param name="path">
            Der Pfad des Data Lake-Speicher (beginnend mit '/') der Datei oder des Verzeichnisses mit der ACL, die geändert wird.
            </param>
        <param name="aclspec">
            Die ACL-Spezifikation enthalten in der ACL Änderungsvorgänge im Format "[Standard:] Benutzer | Gruppe | andere:: R |-w |-X |-"
            </param>
        <param name="customHeaders">
            Die Header, die hinzugefügt werden auf Anforderung.
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Ändert vorhandene (Access Control List, ACL) Einträge in einer Datei oder eines Ordners an.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Azure.Management.DataLake.Store.Models.AdlsErrorException">
            Wird ausgelöst, wenn der Vorgang einen ungültigen Statuscode zurückgegeben hat.
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            Wird ausgelöst, wenn ein erforderlicher Parameter null ist.
            </exception>
      </Docs>
    </Member>
    <Member MemberName="MsConcatWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt; MsConcatWithHttpMessagesAsync (string accountName, string path, System.IO.Stream streamContents, Nullable&lt;bool&gt; deleteSourceDirectory = null, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse&gt; MsConcatWithHttpMessagesAsync(string accountName, string path, class System.IO.Stream streamContents, valuetype System.Nullable`1&lt;bool&gt; deleteSourceDirectory, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations.MsConcatWithHttpMessagesAsync(System.String,System.String,System.IO.Stream,System.Nullable{System.Boolean},System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member MsConcatWithHttpMessagesAsync : string * string * System.IO.Stream * Nullable&lt;bool&gt; * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt;" Usage="iFileSystemOperations.MsConcatWithHttpMessagesAsync (accountName, path, streamContents, deleteSourceDirectory, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Store</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="path" Type="System.String" />
        <Parameter Name="streamContents" Type="System.IO.Stream" />
        <Parameter Name="deleteSourceDirectory" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="accountName">
            Das Azure Data Lake-Speicher-Konto zum Ausführen der Filesystem-Vorgänge auf.
            </param>
        <param name="path">
            Der Pfad des Data Lake-Speicher (beginnend mit '/') der Zieldatei, die sich aus der Verkettung ergibt.
            </param>
        <param name="streamContents">
            Eine Liste der Data Lake-Speicher-Pfade (beginnend mit '/') der Quelldateien. Muss eine durch Trennzeichen getrennte Pfadliste im Format: sources=/file/path/1.txt,/file/path/2.txt,/file/path/lastfile.csv
            </param>
        <param name="deleteSourceDirectory">
            Gibt an, dass eine Optimierung stattdessen jede einzelne Quelldatenstrom zu löschen, löschen Stream Quellordner Wenn stattdessen alle Streams in demselben Ordner befinden. Dies führt zu eine erhebliche Leistungssteigerung, wenn die einzige Datenströme im Ordner "" Teil des verkettungsvorgangs sind. Warnung: Dies umfasst das Löschen von Dateien, die Quelldateien nicht sind.
            Legen Sie nur diese auf "true" wenn Quelldateien nur Dateien in das Quellverzeichnis sind.
            </param>
        <param name="customHeaders">
            Die Header, die hinzugefügt werden auf Anforderung.
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Verkettet die Liste der Quelldateien in der Zieldatei, die alle Quelldateien bei Erfolg wird gelöscht. Diese Methode akzeptiert Weitere quelldateipfaden als die Concat-Methode. Diese Methode und die Parameter, von denen, die er akzeptiert, werden kann zum Zweck der benutzerfreundlichkeit in einer zukünftigen Version geändert.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Azure.Management.DataLake.Store.Models.AdlsErrorException">
            Wird ausgelöst, wenn der Vorgang einen ungültigen Statuscode zurückgegeben hat.
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            Wird ausgelöst, wenn ein erforderlicher Parameter null ist.
            </exception>
      </Docs>
    </Member>
    <Member MemberName="OpenWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;System.IO.Stream&gt;&gt; OpenWithHttpMessagesAsync (string accountName, string path, Nullable&lt;long&gt; length = null, Nullable&lt;long&gt; offset = null, Nullable&lt;Guid&gt; fileSessionId = null, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class System.IO.Stream&gt;&gt; OpenWithHttpMessagesAsync(string accountName, string path, valuetype System.Nullable`1&lt;int64&gt; length, valuetype System.Nullable`1&lt;int64&gt; offset, valuetype System.Nullable`1&lt;valuetype System.Guid&gt; fileSessionId, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations.OpenWithHttpMessagesAsync(System.String,System.String,System.Nullable{System.Int64},System.Nullable{System.Int64},System.Nullable{System.Guid},System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member OpenWithHttpMessagesAsync : string * string * Nullable&lt;int64&gt; * Nullable&lt;int64&gt; * Nullable&lt;Guid&gt; * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;System.IO.Stream&gt;&gt;" Usage="iFileSystemOperations.OpenWithHttpMessagesAsync (accountName, path, length, offset, fileSessionId, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Store</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;System.IO.Stream&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="path" Type="System.String" />
        <Parameter Name="length" Type="System.Nullable&lt;System.Int64&gt;" />
        <Parameter Name="offset" Type="System.Nullable&lt;System.Int64&gt;" />
        <Parameter Name="fileSessionId" Type="System.Nullable&lt;System.Guid&gt;" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
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
        <param name="customHeaders">
            Die Header, die hinzugefügt werden auf Anforderung.
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Öffnet und liest aus der angegebenen Datei.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            Wird ausgelöst, wenn der Vorgang einen ungültigen Statuscode zurückgegeben hat.
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            Wird ausgelöst, wenn nicht die Antwort zu deserialisieren.
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            Wird ausgelöst, wenn ein erforderlicher Parameter null ist.
            </exception>
      </Docs>
    </Member>
    <Member MemberName="PathExistsWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;bool&gt;&gt; PathExistsWithHttpMessagesAsync (string accountName, string getFilePath, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;bool&gt;&gt; PathExistsWithHttpMessagesAsync(string accountName, string getFilePath, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations.PathExistsWithHttpMessagesAsync(System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member PathExistsWithHttpMessagesAsync : string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;bool&gt;&gt;" Usage="iFileSystemOperations.PathExistsWithHttpMessagesAsync (accountName, getFilePath, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Store</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;System.Boolean&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="getFilePath" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="accountName">
            Das Azure Data Lake-Speicher-Konto zum Ausführen der Filesystem-Vorgänge auf.
            </param>
        <param name="getFilePath">
            Der Pfad des Data Lake-Speicher (beginnend mit '/') der Datei oder des Verzeichnisses für das Testen.
            </param>
        <param name="customHeaders">
            Header, die hinzugefügt werden auf Anforderung.
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Testen Sie das Vorhandensein eines Objekts Datei oder das Verzeichnis, die durch den Dateipfad angegeben.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Azure.Management.DataLake.Store.Models.AdlsErrorException">
            Wird ausgelöst, wenn der Vorgang einen ungültigen Statuscode zurückgegeben hat.
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            Wird ausgelöst, wenn nicht die Antwort zu deserialisieren.
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            Wird ausgelöst, wenn ein erforderlicher Parameter null ist.
            </exception>
        <return>
            Ein Response-Objekt, das mit dem Antworttext und Antwortheadern.
            </return>
      </Docs>
    </Member>
    <Member MemberName="RemoveAclEntriesWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt; RemoveAclEntriesWithHttpMessagesAsync (string accountName, string path, string aclspec, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse&gt; RemoveAclEntriesWithHttpMessagesAsync(string accountName, string path, string aclspec, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations.RemoveAclEntriesWithHttpMessagesAsync(System.String,System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member RemoveAclEntriesWithHttpMessagesAsync : string * string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt;" Usage="iFileSystemOperations.RemoveAclEntriesWithHttpMessagesAsync (accountName, path, aclspec, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Store</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="path" Type="System.String" />
        <Parameter Name="aclspec" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="accountName">
            Das Azure Data Lake-Speicher-Konto zum Ausführen der Filesystem-Vorgänge auf.
            </param>
        <param name="path">
            Der Pfad des Data Lake-Speicher (beginnend mit '/') der Datei oder des Verzeichnisses mit der ACL entfernt wird.
            </param>
        <param name="aclspec">
            Die ACL-Spezifikation enthalten in der ACL entfernen Vorgänge im Format "[Standard:] Benutzer | Gruppe | andere"
            </param>
        <param name="customHeaders">
            Die Header, die hinzugefügt werden auf Anforderung.
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Entfernt einen vorhandenen Einträge in der Zugriffssteuerungsliste (ACL) für eine Datei oder einen Ordner.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Azure.Management.DataLake.Store.Models.AdlsErrorException">
            Wird ausgelöst, wenn der Vorgang einen ungültigen Statuscode zurückgegeben hat.
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            Wird ausgelöst, wenn ein erforderlicher Parameter null ist.
            </exception>
      </Docs>
    </Member>
    <Member MemberName="RemoveAclWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt; RemoveAclWithHttpMessagesAsync (string accountName, string path, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse&gt; RemoveAclWithHttpMessagesAsync(string accountName, string path, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations.RemoveAclWithHttpMessagesAsync(System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member RemoveAclWithHttpMessagesAsync : string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt;" Usage="iFileSystemOperations.RemoveAclWithHttpMessagesAsync (accountName, path, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Store</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="path" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="accountName">
            Das Azure Data Lake-Speicher-Konto zum Ausführen der Filesystem-Vorgänge auf.
            </param>
        <param name="path">
            Der Pfad des Data Lake-Speicher (beginnend mit '/') der Datei oder des Verzeichnisses mit der ACL entfernt wird.
            </param>
        <param name="customHeaders">
            Die Header, die hinzugefügt werden auf Anforderung.
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Entfernt die vorhandene Liste (ACL) der angegebenen Datei oder des Verzeichnisses.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Azure.Management.DataLake.Store.Models.AdlsErrorException">
            Wird ausgelöst, wenn der Vorgang einen ungültigen Statuscode zurückgegeben hat.
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            Wird ausgelöst, wenn ein erforderlicher Parameter null ist.
            </exception>
      </Docs>
    </Member>
    <Member MemberName="RemoveDefaultAclWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt; RemoveDefaultAclWithHttpMessagesAsync (string accountName, string path, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse&gt; RemoveDefaultAclWithHttpMessagesAsync(string accountName, string path, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations.RemoveDefaultAclWithHttpMessagesAsync(System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member RemoveDefaultAclWithHttpMessagesAsync : string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt;" Usage="iFileSystemOperations.RemoveDefaultAclWithHttpMessagesAsync (accountName, path, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Store</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="path" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="accountName">
            Das Azure Data Lake-Speicher-Konto zum Ausführen der Filesystem-Vorgänge auf.
            </param>
        <param name="path">
            Der Pfad des Data Lake-Speicher (beginnend mit "/") des Verzeichnisses mit den Standard-ACL entfernt wird.
            </param>
        <param name="customHeaders">
            Die Header, die hinzugefügt werden auf Anforderung.
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Entfernt die vorhandene Standard Zugriffssteuerungsliste (ACL) des angegebenen Verzeichnisses.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Azure.Management.DataLake.Store.Models.AdlsErrorException">
            Wird ausgelöst, wenn der Vorgang einen ungültigen Statuscode zurückgegeben hat.
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            Wird ausgelöst, wenn ein erforderlicher Parameter null ist.
            </exception>
      </Docs>
    </Member>
    <Member MemberName="RenameWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.DataLake.Store.Models.FileOperationResult&gt;&gt; RenameWithHttpMessagesAsync (string accountName, string path, string destination, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Management.DataLake.Store.Models.FileOperationResult&gt;&gt; RenameWithHttpMessagesAsync(string accountName, string path, string destination, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations.RenameWithHttpMessagesAsync(System.String,System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member RenameWithHttpMessagesAsync : string * string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.DataLake.Store.Models.FileOperationResult&gt;&gt;" Usage="iFileSystemOperations.RenameWithHttpMessagesAsync (accountName, path, destination, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Store</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.DataLake.Store.Models.FileOperationResult&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="path" Type="System.String" />
        <Parameter Name="destination" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="accountName">
            Das Azure Data Lake-Speicher-Konto zum Ausführen der Filesystem-Vorgänge auf.
            </param>
        <param name="path">
            Der Pfad des Data Lake-Speicher (beginnend mit '/') der Datei oder des Verzeichnisses zum Verschieben/umbenennen.
            </param>
        <param name="destination">
            Der Pfad zum Verschieben/Umbenennen der Datei oder einen Ordner an
            </param>
        <param name="customHeaders">
            Die Header, die hinzugefügt werden auf Anforderung.
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Benennt eine Datei oder ein Verzeichnis um.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Azure.Management.DataLake.Store.Models.AdlsErrorException">
            Wird ausgelöst, wenn der Vorgang einen ungültigen Statuscode zurückgegeben hat.
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            Wird ausgelöst, wenn nicht die Antwort zu deserialisieren.
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            Wird ausgelöst, wenn ein erforderlicher Parameter null ist.
            </exception>
      </Docs>
    </Member>
    <Member MemberName="SetAclWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt; SetAclWithHttpMessagesAsync (string accountName, string path, string aclspec, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse&gt; SetAclWithHttpMessagesAsync(string accountName, string path, string aclspec, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations.SetAclWithHttpMessagesAsync(System.String,System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member SetAclWithHttpMessagesAsync : string * string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt;" Usage="iFileSystemOperations.SetAclWithHttpMessagesAsync (accountName, path, aclspec, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Store</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="path" Type="System.String" />
        <Parameter Name="aclspec" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="accountName">
            Das Azure Data Lake-Speicher-Konto zum Ausführen der Filesystem-Vorgänge auf.
            </param>
        <param name="path">
            Der Pfad des Data Lake-Speicher (beginnend mit '/') der Datei oder des Verzeichnisses für das die ACL festgelegt.
            </param>
        <param name="aclspec">
            Die ACL-Spezifikation enthalten in der ACL-Erstellungsvorgänge im Format "[Standard:] Benutzer | Gruppe | andere:: R |-w |-X |-"
            </param>
        <param name="customHeaders">
            Die Header, die hinzugefügt werden auf Anforderung.
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Legt die Zugriffssteuerungsliste (ACL) für eine Datei oder Ordner fest.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Azure.Management.DataLake.Store.Models.AdlsErrorException">
            Wird ausgelöst, wenn der Vorgang einen ungültigen Statuscode zurückgegeben hat.
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            Wird ausgelöst, wenn ein erforderlicher Parameter null ist.
            </exception>
      </Docs>
    </Member>
    <Member MemberName="SetFileExpiryWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt; SetFileExpiryWithHttpMessagesAsync (string accountName, string path, Microsoft.Azure.Management.DataLake.Store.Models.ExpiryOptionType expiryOption, Nullable&lt;long&gt; expireTime = null, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse&gt; SetFileExpiryWithHttpMessagesAsync(string accountName, string path, valuetype Microsoft.Azure.Management.DataLake.Store.Models.ExpiryOptionType expiryOption, valuetype System.Nullable`1&lt;int64&gt; expireTime, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations.SetFileExpiryWithHttpMessagesAsync(System.String,System.String,Microsoft.Azure.Management.DataLake.Store.Models.ExpiryOptionType,System.Nullable{System.Int64},System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member SetFileExpiryWithHttpMessagesAsync : string * string * Microsoft.Azure.Management.DataLake.Store.Models.ExpiryOptionType * Nullable&lt;int64&gt; * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt;" Usage="iFileSystemOperations.SetFileExpiryWithHttpMessagesAsync (accountName, path, expiryOption, expireTime, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Store</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="path" Type="System.String" />
        <Parameter Name="expiryOption" Type="Microsoft.Azure.Management.DataLake.Store.Models.ExpiryOptionType" />
        <Parameter Name="expireTime" Type="System.Nullable&lt;System.Int64&gt;" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="accountName">
            Das Azure Data Lake-Speicher-Konto zum Ausführen der Filesystem-Vorgänge auf.
            </param>
        <param name="path">
            Der Pfad des Data Lake-Speicher (beginnend mit '/') der Datei für das Festlegen oder entfernen die Ablaufzeit.
            </param>
        <param name="expiryOption">
            Gibt den Typ der Ablauf für die Datei: 1.
            NeverExpire: ExpireTime wird ignoriert. 2. RelativeToNow: ExpireTime ist eine ganze Zahl in Millisekunden, die das Ablaufdatum relativ zum darstellt, wenn Dateiablauf aktualisiert wird. 3.
            RelativeToCreationDate: ExpireTime ist eine ganze Zahl in Millisekunden, die das Ablaufdatum relativ zur Erstellung der Datei darstellt. 4.
            Absolute: ExpireTime ist eine ganze Zahl in Millisekunden, die als Timestamp Unix relativ zum 1/1/1970 00:00:00. Folgende Werte sind möglich: "NeverExpire", "RelativeToNow", "RelativeToCreationDate", "Absolute"
            </param>
        <param name="expireTime">
            Die Zeit, die die Datei abläuft, entspricht die ExpiryOption, die festgelegt wurde.
            </param>
        <param name="customHeaders">
            Die Header, die hinzugefügt werden auf Anforderung.
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Entfernt die Ablaufzeit für die angegebene Datei ab oder legt sie fest. Dieser Vorgang kann nur für Dateien ausgeführt werden. Ordner werden nicht unterstützt.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Azure.Management.DataLake.Store.Models.AdlsErrorException">
            Wird ausgelöst, wenn der Vorgang einen ungültigen Statuscode zurückgegeben hat.
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            Wird ausgelöst, wenn ein erforderlicher Parameter null ist.
            </exception>
      </Docs>
    </Member>
    <Member MemberName="SetOwnerWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt; SetOwnerWithHttpMessagesAsync (string accountName, string path, string owner = null, string group = null, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse&gt; SetOwnerWithHttpMessagesAsync(string accountName, string path, string owner, string group, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations.SetOwnerWithHttpMessagesAsync(System.String,System.String,System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member SetOwnerWithHttpMessagesAsync : string * string * string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt;" Usage="iFileSystemOperations.SetOwnerWithHttpMessagesAsync (accountName, path, owner, group, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Store</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="path" Type="System.String" />
        <Parameter Name="owner" Type="System.String" />
        <Parameter Name="group" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
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
        <param name="customHeaders">
            Die Header, die hinzugefügt werden auf Anforderung.
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Legt den Besitzer einer Datei oder eines Verzeichnisses fest.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Azure.Management.DataLake.Store.Models.AdlsErrorException">
            Wird ausgelöst, wenn der Vorgang einen ungültigen Statuscode zurückgegeben hat.
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            Wird ausgelöst, wenn ein erforderlicher Parameter null ist.
            </exception>
      </Docs>
    </Member>
    <Member MemberName="SetPermissionWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt; SetPermissionWithHttpMessagesAsync (string accountName, string path, string permission = null, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse&gt; SetPermissionWithHttpMessagesAsync(string accountName, string path, string permission, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations.SetPermissionWithHttpMessagesAsync(System.String,System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member SetPermissionWithHttpMessagesAsync : string * string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt;" Usage="iFileSystemOperations.SetPermissionWithHttpMessagesAsync (accountName, path, permission, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Store</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="path" Type="System.String" />
        <Parameter Name="permission" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="accountName">
            Das Azure Data Lake-Speicher-Konto zum Ausführen der Filesystem-Vorgänge auf.
            </param>
        <param name="path">
            Der Pfad des Data Lake-Speicher (beginnend mit '/') der Datei oder des Verzeichnisses für die die Berechtigung festgelegt.
            </param>
        <param name="permission">
            Eine Zeichenfolgendarstellung der Berechtigung (d. h. "Rwx"). Wenn Sie leer ist, bleibt diese Eigenschaft unverändert.
            </param>
        <param name="customHeaders">
            Die Header, die hinzugefügt werden auf Anforderung.
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Legt den Berechtigungssatz einer Datei oder eines Ordners.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Azure.Management.DataLake.Store.Models.AdlsErrorException">
            Wird ausgelöst, wenn der Vorgang einen ungültigen Statuscode zurückgegeben hat.
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            Wird ausgelöst, wenn ein erforderlicher Parameter null ist.
            </exception>
      </Docs>
    </Member>
    <Member MemberName="UploadFile">
      <MemberSignature Language="C#" Value="public void UploadFile (string accountName, string sourcePath, string destinationPath, int threadCount = -1, bool resume = false, bool overwrite = false, bool uploadAsBinary = false, IProgress&lt;Microsoft.Azure.Management.DataLake.Store.TransferProgress&gt; progressTracker = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void UploadFile(string accountName, string sourcePath, string destinationPath, int32 threadCount, bool resume, bool overwrite, bool uploadAsBinary, class System.IProgress`1&lt;class Microsoft.Azure.Management.DataLake.Store.TransferProgress&gt; progressTracker, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations.UploadFile(System.String,System.String,System.String,System.Int32,System.Boolean,System.Boolean,System.Boolean,System.IProgress{Microsoft.Azure.Management.DataLake.Store.TransferProgress},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member UploadFile : string * string * string * int * bool * bool * bool * IProgress&lt;Microsoft.Azure.Management.DataLake.Store.TransferProgress&gt; * System.Threading.CancellationToken -&gt; unit" Usage="iFileSystemOperations.UploadFile (accountName, sourcePath, destinationPath, threadCount, resume, overwrite, uploadAsBinary, progressTracker, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Store</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="sourcePath" Type="System.String" />
        <Parameter Name="destinationPath" Type="System.String" />
        <Parameter Name="threadCount" Type="System.Int32" />
        <Parameter Name="resume" Type="System.Boolean" />
        <Parameter Name="overwrite" Type="System.Boolean" />
        <Parameter Name="uploadAsBinary" Type="System.Boolean" />
        <Parameter Name="progressTracker" Type="System.IProgress&lt;Microsoft.Azure.Management.DataLake.Store.TransferProgress&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="accountName">
            Das Azure Data Lake-Speicher-Konto zum Ausführen der Filesystem-Vorgänge auf.
            </param>
        <param name="sourcePath">
            Die lokalen Quelldatei in das Data Lake-Speicher-Konto hochladen.
            </param>
        <param name="destinationPath">
            Der Data Lake-Speicher-Pfad (beginnend mit "/") des Verzeichnisses oder Verzeichnis und der Dateiname in hochladen.
            </param>
        <param name="threadCount">
            Die maximale Anzahl von Threads zur Verwendung beim Hochladen. Standardmäßig wird diese Anzahl basierend auf der Größe berechnet werden.
            </param>
        <param name="resume">
            Einem Switch, der angibt, ob dieses Uploads eine Fortsetzung einer vorherigen, fehlgeschlagenen Uploads ist. Die Standardeinstellung ist "false".
            </param>
        <param name="overwrite">
            Ein Switch, der angibt, der dieses Uploads sollte die Zieldatei überschrieben werden soll, wenn er vorhanden ist. Standardwert ist "false", und der Upload schnelle Fehler aus, wenn die Zieldatei vorhanden ist.
            </param>
        <param name="uploadAsBinary">
            Ein Switch, der angibt, der dieses Uploads sollten die Datei als Binärdatei, Behandeln der leistungsfähiger als etwas aber Datensatz Grenze Integrität wird nicht sichergestellt.
            </param>
        <param name="progressTracker">
            Ein Optionaler Delegat, der verwendet werden kann, um den Status des Uploadvorgangs asynchron zu verfolgen.
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Lädt eine Datei in das angegebene Data Lake-Speicher-Konto hoch.
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Azure.Management.DataLake.Store.Models.AdlsErrorException">
            Wird ausgelöst, wenn der Vorgang einen ungültigen Statuscode zurückgegeben hat.
            </exception>
        <exception cref="T:System.Threading.Tasks.TaskCanceledException">
            Wird ausgelöst, wenn der Vorgang zu lange dauert oder wenn der Benutzer explizit abbricht.
            </exception>
        <exception cref="T:Microsoft.Azure.Management.DataLake.Store.InvalidMetadataException">
            Wird ausgelöst, wenn Resume Metadaten beschädigt oder nicht dem aktuellen Vorgang zugeordnet ist.
            </exception>
        <exception cref="T:System.IO.FileNotFoundException">
            Wird ausgelöst, wenn der Quellpfad nicht gefunden werden kann.
            </exception>
        <exception cref="T:System.InvalidOperationException">
            Wird ausgelöst, wenn ein ungültiger Upload versucht wird, oder die Datei extern, während des Vorgangs geändert wird.
            </exception>
        <exception cref="T:Microsoft.Azure.Management.DataLake.Store.TransferFailedException">
            Wird ausgelöst, wenn die Übertragung fehl.
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            Wird ausgelöst, wenn nicht die Antwort zu deserialisieren.
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            Wird ausgelöst, wenn ein erforderlicher Parameter null ist.
            </exception>
      </Docs>
    </Member>
    <Member MemberName="UploadFolder">
      <MemberSignature Language="C#" Value="public void UploadFolder (string accountName, string sourcePath, string destinationPath, int perFileThreadCount = -1, int concurrentFileCount = -1, bool resume = false, bool overwrite = false, bool uploadAsBinary = false, bool recurse = false, IProgress&lt;Microsoft.Azure.Management.DataLake.Store.TransferFolderProgress&gt; progressTracker = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void UploadFolder(string accountName, string sourcePath, string destinationPath, int32 perFileThreadCount, int32 concurrentFileCount, bool resume, bool overwrite, bool uploadAsBinary, bool recurse, class System.IProgress`1&lt;class Microsoft.Azure.Management.DataLake.Store.TransferFolderProgress&gt; progressTracker, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations.UploadFolder(System.String,System.String,System.String,System.Int32,System.Int32,System.Boolean,System.Boolean,System.Boolean,System.Boolean,System.IProgress{Microsoft.Azure.Management.DataLake.Store.TransferFolderProgress},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member UploadFolder : string * string * string * int * int * bool * bool * bool * bool * IProgress&lt;Microsoft.Azure.Management.DataLake.Store.TransferFolderProgress&gt; * System.Threading.CancellationToken -&gt; unit" Usage="iFileSystemOperations.UploadFolder (accountName, sourcePath, destinationPath, perFileThreadCount, concurrentFileCount, resume, overwrite, uploadAsBinary, recurse, progressTracker, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Store</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="sourcePath" Type="System.String" />
        <Parameter Name="destinationPath" Type="System.String" />
        <Parameter Name="perFileThreadCount" Type="System.Int32" />
        <Parameter Name="concurrentFileCount" Type="System.Int32" />
        <Parameter Name="resume" Type="System.Boolean" />
        <Parameter Name="overwrite" Type="System.Boolean" />
        <Parameter Name="uploadAsBinary" Type="System.Boolean" />
        <Parameter Name="recurse" Type="System.Boolean" />
        <Parameter Name="progressTracker" Type="System.IProgress&lt;Microsoft.Azure.Management.DataLake.Store.TransferFolderProgress&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="accountName">
            Das Azure Data Lake-Speicher-Konto zum Ausführen der Filesystem-Vorgänge auf.
            </param>
        <param name="sourcePath">
            Der lokale Quellordner in das Data Lake-Speicher-Konto hochladen.
            </param>
        <param name="destinationPath">
            Der Pfad des Data Lake-Speicher (beginnend mit "/") des Verzeichnisses, das zum Hochladen.
            </param>
        <param name="perFileThreadCount">
            Die maximale Anzahl von Threads pro Datei während des Uploads verwenden. Standardmäßig wird diese Anzahl basierend auf den Ordner-Struktur und die durchschnittliche Größe berechnet werden.
            </param>
        <param name="concurrentFileCount">
            Die maximale Anzahl von Dateien gleichzeitig hochladen. Standardmäßig wird diese Anzahl basierend auf den Schritt die Ordnerstruktur und die Anzahl der Dateien berechnet werden.
            </param>
        <param name="resume">
            Einem Switch, der angibt, ob dieses Uploads eine Fortsetzung einer vorherigen, fehlgeschlagenen Uploads ist. Die Standardeinstellung ist "false".
            </param>
        <param name="overwrite">
            Ein Switch, der angibt, der dieses Uploads sollte den Inhalt der Zielverzeichnis überschreiben, falls vorhanden. Standard ist "false", und der Upload schnelle Fehler aus, wenn am Zielspeicherort vorhanden ist.
            </param>
        <param name="uploadAsBinary">
            Ein Switch, der angibt, der dieses Uploads sollten alle Daten im Binärformat, behandeln die Vorgehensweise ist etwas leistungsfähiger aber Datensatz Grenze Integrität wird nicht sichergestellt. Dies wird für große Ordner der gemischten Binär- und Textmodus Dateien oder binäre nur Verzeichnisse empfohlen. Standardmäßig ist "false"
            </param>
        <param name="recurse">
            Ein Switch, der angibt, der dieses Uploads sollten die Quelle Verzeichnis rekursiv oder nur die oberste Ebene hochladen. Standardwert ist "false", nur die oberste Ebene hochgeladen wird.
            </param>
        <param name="progressTracker">
            Ein Optionaler Delegat, der verwendet werden kann, um den Status des Uploadvorgangs asynchron zu verfolgen.
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Einen Ordner hochgeladen auf das angegebene Data Lake-Speicher-Konto.
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Azure.Management.DataLake.Store.Models.AdlsErrorException">
            Wird ausgelöst, wenn der Vorgang einen ungültigen Statuscode zurückgegeben hat.
            </exception>
        <exception cref="T:System.Threading.Tasks.TaskCanceledException">
            Wird ausgelöst, wenn der Vorgang zu lange dauert oder wenn der Benutzer explizit abbricht.
            </exception>
        <exception cref="T:Microsoft.Azure.Management.DataLake.Store.InvalidMetadataException">
            Wird ausgelöst, wenn Resume Metadaten beschädigt oder nicht dem aktuellen Vorgang zugeordnet ist.
            </exception>
        <exception cref="T:System.IO.FileNotFoundException">
            Wird ausgelöst, wenn der Quellpfad nicht gefunden werden kann.
            </exception>
        <exception cref="T:System.InvalidOperationException">
            Wird ausgelöst, wenn ein ungültiger Upload versucht wird, oder ein Datei bzw. der Ordner wird während des Vorgangs extern geändert.
            </exception>
        <exception cref="T:Microsoft.Azure.Management.DataLake.Store.TransferFailedException">
            Wird ausgelöst, wenn die Übertragung fehl.
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            Wird ausgelöst, wenn nicht die Antwort zu deserialisieren.
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            Wird ausgelöst, wenn ein erforderlicher Parameter null ist.
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>