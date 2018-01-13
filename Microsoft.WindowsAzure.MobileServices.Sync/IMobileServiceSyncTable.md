<Type Name="IMobileServiceSyncTable" FullName="Microsoft.WindowsAzure.MobileServices.Sync.IMobileServiceSyncTable">
  <TypeSignature Language="C#" Value="public interface IMobileServiceSyncTable" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IMobileServiceSyncTable" />
  <TypeSignature Language="DocId" Value="T:Microsoft.WindowsAzure.MobileServices.Sync.IMobileServiceSyncTable" />
  <TypeSignature Language="VB.NET" Value="Public Interface IMobileServiceSyncTable" />
  <TypeSignature Language="F#" Value="type IMobileServiceSyncTable = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Mobile.Client</AssemblyName>
    <AssemblyVersion>4.0.0.0</AssemblyVersion>
    <AssemblyVersion>4.0.2.0</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            Stellt Vorgänge für lokale Tabelle bereit.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="DeleteAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task DeleteAsync (Newtonsoft.Json.Linq.JObject instance);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task DeleteAsync(class Newtonsoft.Json.Linq.JObject instance) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.MobileServices.Sync.IMobileServiceSyncTable.DeleteAsync(Newtonsoft.Json.Linq.JObject)" />
      <MemberSignature Language="VB.NET" Value="Public Function DeleteAsync (instance As JObject) As Task" />
      <MemberSignature Language="F#" Value="abstract member DeleteAsync : Newtonsoft.Json.Linq.JObject -&gt; System.Threading.Tasks.Task" Usage="iMobileServiceSyncTable.DeleteAsync instance" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Client</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.2.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="instance" Type="Newtonsoft.Json.Linq.JObject" />
      </Parameters>
      <Docs>
        <param name="instance">
            Die Instanz, aus der Tabelle löschen.
            </param>
        <summary>
            Löscht eine <paramref name="instance" /> aus der Tabelle.
            </summary>
        <returns>
            Eine Aufgabe, die abgeschlossen wird, wenn der Löschvorgang abgeschlossen ist.
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="InsertAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Newtonsoft.Json.Linq.JObject&gt; InsertAsync (Newtonsoft.Json.Linq.JObject instance);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Newtonsoft.Json.Linq.JObject&gt; InsertAsync(class Newtonsoft.Json.Linq.JObject instance) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.MobileServices.Sync.IMobileServiceSyncTable.InsertAsync(Newtonsoft.Json.Linq.JObject)" />
      <MemberSignature Language="VB.NET" Value="Public Function InsertAsync (instance As JObject) As Task(Of JObject)" />
      <MemberSignature Language="F#" Value="abstract member InsertAsync : Newtonsoft.Json.Linq.JObject -&gt; System.Threading.Tasks.Task&lt;Newtonsoft.Json.Linq.JObject&gt;" Usage="iMobileServiceSyncTable.InsertAsync instance" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Client</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.2.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Newtonsoft.Json.Linq.JObject&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="instance" Type="Newtonsoft.Json.Linq.JObject" />
      </Parameters>
      <Docs>
        <param name="instance">
            Die Instanz, in die Tabelle einzufügen.
            </param>
        <summary>
            Fügt eine <paramref name="instance" /> in die Tabelle.
            </summary>
        <returns>
            Eine Aufgabe, die abgeschlossen wird, wenn der Einfügevorgang abgeschlossen ist.
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="LookupAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Newtonsoft.Json.Linq.JObject&gt; LookupAsync (string id);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Newtonsoft.Json.Linq.JObject&gt; LookupAsync(string id) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.MobileServices.Sync.IMobileServiceSyncTable.LookupAsync(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function LookupAsync (id As String) As Task(Of JObject)" />
      <MemberSignature Language="F#" Value="abstract member LookupAsync : string -&gt; System.Threading.Tasks.Task&lt;Newtonsoft.Json.Linq.JObject&gt;" Usage="iMobileServiceSyncTable.LookupAsync id" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Client</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.2.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Newtonsoft.Json.Linq.JObject&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="id" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="id">
            Die Id des zu suchenden Instanz.
            </param>
        <summary>
            Führt eine Suche für eine Tabelle aus.
            </summary>
        <returns>
            Eine Aufgabe, die mit einem Ergebnis zurückgegeben wird, wenn die Suche abgeschlossen ist.
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MobileServiceClient">
      <MemberSignature Language="C#" Value="public Microsoft.WindowsAzure.MobileServices.MobileServiceClient MobileServiceClient { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.WindowsAzure.MobileServices.MobileServiceClient MobileServiceClient" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.MobileServices.Sync.IMobileServiceSyncTable.MobileServiceClient" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property MobileServiceClient As MobileServiceClient" />
      <MemberSignature Language="F#" Value="member this.MobileServiceClient : Microsoft.WindowsAzure.MobileServices.MobileServiceClient" Usage="Microsoft.WindowsAzure.MobileServices.Sync.IMobileServiceSyncTable.MobileServiceClient" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Client</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.2.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.MobileServices.MobileServiceClient</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft einen Verweis auf die <see cref="P:Microsoft.WindowsAzure.MobileServices.Sync.IMobileServiceSyncTable.MobileServiceClient" /> dieser Tabelle zugeordnet.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PullAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task PullAsync (string queryId, string query, System.Collections.Generic.IDictionary&lt;string,string&gt; parameters, bool pushOtherTables, System.Threading.CancellationToken cancellationToken, Microsoft.WindowsAzure.MobileServices.Sync.PullOptions pullOptions);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task PullAsync(string queryId, string query, class System.Collections.Generic.IDictionary`2&lt;string, string&gt; parameters, bool pushOtherTables, valuetype System.Threading.CancellationToken cancellationToken, class Microsoft.WindowsAzure.MobileServices.Sync.PullOptions pullOptions) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.MobileServices.Sync.IMobileServiceSyncTable.PullAsync(System.String,System.String,System.Collections.Generic.IDictionary{System.String,System.String},System.Boolean,System.Threading.CancellationToken,Microsoft.WindowsAzure.MobileServices.Sync.PullOptions)" />
      <MemberSignature Language="F#" Value="abstract member PullAsync : string * string * System.Collections.Generic.IDictionary&lt;string, string&gt; * bool * System.Threading.CancellationToken * Microsoft.WindowsAzure.MobileServices.Sync.PullOptions -&gt; System.Threading.Tasks.Task" Usage="iMobileServiceSyncTable.PullAsync (queryId, query, parameters, pushOtherTables, cancellationToken, pullOptions)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Client</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.2.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="queryId" Type="System.String" />
        <Parameter Name="query" Type="System.String" />
        <Parameter Name="parameters" Type="System.Collections.Generic.IDictionary&lt;System.String,System.String&gt;" />
        <Parameter Name="pushOtherTables" Type="System.Boolean" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
        <Parameter Name="pullOptions" Type="Microsoft.WindowsAzure.MobileServices.Sync.PullOptions" />
      </Parameters>
      <Docs>
        <param name="queryId">
            Eine Zeichenfolge, die diese Abfrage bezeichnet und dient zum Nachverfolgen der Synchronisierungsstatus des eindeutig. Angabe dieses Parameters kann inkrementelle Synchronisierung an der gleiche Schlüssel erneut verwendet wird.
            </param>
        <param name="query">
            Eine OData-Abfrage, die bestimmt, welche Elemente aus der Remotetabelle abrufen.
            </param>
        <param name="parameters">
            Ein Wörterbuch mit benutzerdefinierten Parametern und Werten, die im Anforderungs-URI-Abfragezeichenfolge enthalten.
            </param>
        <param name="pushOtherTables">
            Drücken Sie andere Tabellen, wenn diese Tabelle geändert wurde.
            </param>
        <param name="cancellationToken">Die <see cref="T:System.Threading.CancellationToken" /> Token beobachten
            </param>
        <param name="pullOptions">
            PullOptions, die bestimmen, wie Daten aus der Remotetabelle abrufen
            </param>
        <summary>
            Ruft alle Elemente, die mit die angegebene Abfrage aus der zugeordneten Remotetabelle übereinstimmen. Unterstützt inkrementelle Synchronisierung.
            </summary>
        <returns>
            Eine Aufgabe, die abgeschlossen wird, wenn der Pullvorgang abgeschlossen ist.
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PurgeAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task PurgeAsync (string queryId, string query, bool force, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task PurgeAsync(string queryId, string query, bool force, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.MobileServices.Sync.IMobileServiceSyncTable.PurgeAsync(System.String,System.String,System.Boolean,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member PurgeAsync : string * string * bool * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="iMobileServiceSyncTable.PurgeAsync (queryId, query, force, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Client</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.2.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="queryId" Type="System.String" />
        <Parameter Name="query" Type="System.String" />
        <Parameter Name="force" Type="System.Boolean" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="queryId">
            Eine Zeichenfolge, die diese Abfrage bezeichnet und dient zum Nachverfolgen der Synchronisierungsstatus des eindeutig. Dieser Parameter angeben, setzt den inkrementelle Synchronisierung-Zustand für die Abfrage.
            </param>
        <param name="query">Eine OData-Abfrage, die bestimmt, welche Elemente löschen.</param>
        <param name="force">Erzwingen Sie Löschvorgang durch das Verwerfen der ausstehenden Vorgänge.</param>
        <param name="cancellationToken">Die <see cref="T:System.Threading.CancellationToken" /> Token beobachten
            </param>
        <summary>
            Löscht alle Elemente in der lokalen Tabelle, die der Abfrage entsprechen.
            </summary>
        <returns>Eine Aufgabe, die beim Abschluss löschen Vorgang wurde beendet.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ReadAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Newtonsoft.Json.Linq.JToken&gt; ReadAsync (string query);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Newtonsoft.Json.Linq.JToken&gt; ReadAsync(string query) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.MobileServices.Sync.IMobileServiceSyncTable.ReadAsync(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function ReadAsync (query As String) As Task(Of JToken)" />
      <MemberSignature Language="F#" Value="abstract member ReadAsync : string -&gt; System.Threading.Tasks.Task&lt;Newtonsoft.Json.Linq.JToken&gt;" Usage="iMobileServiceSyncTable.ReadAsync query" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Client</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.2.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Newtonsoft.Json.Linq.JToken&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="query" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="query">
            Eine auszuführende Abfrage.
            </param>
        <summary>
            Führt eine Abfrage für die Tabelle.
            </summary>
        <returns>
            Eine Aufgabe, die mit Ergebnissen zurückgegeben wird, wenn die Abfrage abgeschlossen ist.
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SupportedOptions">
      <MemberSignature Language="C#" Value="public Microsoft.WindowsAzure.MobileServices.MobileServiceRemoteTableOptions SupportedOptions { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype Microsoft.WindowsAzure.MobileServices.MobileServiceRemoteTableOptions SupportedOptions" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.MobileServices.Sync.IMobileServiceSyncTable.SupportedOptions" />
      <MemberSignature Language="VB.NET" Value="Public Property SupportedOptions As MobileServiceRemoteTableOptions" />
      <MemberSignature Language="F#" Value="member this.SupportedOptions : Microsoft.WindowsAzure.MobileServices.MobileServiceRemoteTableOptions with get, set" Usage="Microsoft.WindowsAzure.MobileServices.Sync.IMobileServiceSyncTable.SupportedOptions" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Client</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.2.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.MobileServices.MobileServiceRemoteTableOptions</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Die unterstützten OData-Optionen für die Remotetabelle
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TableName">
      <MemberSignature Language="C#" Value="public string TableName { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string TableName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.MobileServices.Sync.IMobileServiceSyncTable.TableName" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property TableName As String" />
      <MemberSignature Language="F#" Value="member this.TableName : string" Usage="Microsoft.WindowsAzure.MobileServices.Sync.IMobileServiceSyncTable.TableName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Client</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.2.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft den Namen der Tabelle ab.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UpdateAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task UpdateAsync (Newtonsoft.Json.Linq.JObject instance);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task UpdateAsync(class Newtonsoft.Json.Linq.JObject instance) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.MobileServices.Sync.IMobileServiceSyncTable.UpdateAsync(Newtonsoft.Json.Linq.JObject)" />
      <MemberSignature Language="VB.NET" Value="Public Function UpdateAsync (instance As JObject) As Task" />
      <MemberSignature Language="F#" Value="abstract member UpdateAsync : Newtonsoft.Json.Linq.JObject -&gt; System.Threading.Tasks.Task" Usage="iMobileServiceSyncTable.UpdateAsync instance" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Client</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.2.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="instance" Type="Newtonsoft.Json.Linq.JObject" />
      </Parameters>
      <Docs>
        <param name="instance">
            In der Tabelle zu aktualisierende Instanz.
            </param>
        <summary>
            Updates ein <paramref name="instance" /> in der Tabelle.
            </summary>
        <returns>
            Eine Aufgabe, die abgeschlossen wird, wenn der Aktualisierungsvorgang abgeschlossen ist.
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>