<Type Name="IMobileServiceSyncTable&lt;T&gt;" FullName="Microsoft.WindowsAzure.MobileServices.Sync.IMobileServiceSyncTable&lt;T&gt;">
  <TypeSignature Language="C#" Value="public interface IMobileServiceSyncTable&lt;T&gt; : Microsoft.WindowsAzure.MobileServices.Sync.IMobileServiceSyncTable" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IMobileServiceSyncTable`1&lt;T&gt; implements class Microsoft.WindowsAzure.MobileServices.Sync.IMobileServiceSyncTable" />
  <TypeSignature Language="DocId" Value="T:Microsoft.WindowsAzure.MobileServices.Sync.IMobileServiceSyncTable`1" />
  <TypeSignature Language="VB.NET" Value="Public Interface IMobileServiceSyncTable(Of T)&#xA;Implements IMobileServiceSyncTable" />
  <TypeSignature Language="F#" Value="type IMobileServiceSyncTable&lt;'T&gt; = interface&#xA;    interface IMobileServiceSyncTable" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Mobile.Client</AssemblyName>
    <AssemblyVersion>4.0.0.0</AssemblyVersion>
    <AssemblyVersion>4.0.2.0</AssemblyVersion>
  </AssemblyInfo>
  <TypeParameters>
    <TypeParameter Name="T" />
  </TypeParameters>
  <Interfaces>
    <Interface>
      <InterfaceName>Microsoft.WindowsAzure.MobileServices.Sync.IMobileServiceSyncTable</InterfaceName>
    </Interface>
  </Interfaces>
  <Docs>
    <typeparam name="T">To be added.</typeparam>
    <summary>
            Stellt Vorgänge für lokale Tabelle bereit.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="CreateQuery">
      <MemberSignature Language="C#" Value="public Microsoft.WindowsAzure.MobileServices.IMobileServiceTableQuery&lt;T&gt; CreateQuery ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.WindowsAzure.MobileServices.IMobileServiceTableQuery`1&lt;!T&gt; CreateQuery() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.MobileServices.Sync.IMobileServiceSyncTable`1.CreateQuery" />
      <MemberSignature Language="VB.NET" Value="Public Function CreateQuery () As IMobileServiceTableQuery(Of T)" />
      <MemberSignature Language="F#" Value="abstract member CreateQuery : unit -&gt; Microsoft.WindowsAzure.MobileServices.IMobileServiceTableQuery&lt;'T&gt;" Usage="iMobileServiceSyncTable.CreateQuery " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Client</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.2.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.MobileServices.IMobileServiceTableQuery&lt;T&gt;</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            Erstellt eine Abfrage für die aktuelle Tabelle.
            </summary>
        <returns>
            Eine Abfrage für die Tabelle.
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task DeleteAsync (T instance);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task DeleteAsync(!T instance) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.MobileServices.Sync.IMobileServiceSyncTable`1.DeleteAsync(`0)" />
      <MemberSignature Language="VB.NET" Value="Public Function DeleteAsync (instance As T) As Task" />
      <MemberSignature Language="F#" Value="abstract member DeleteAsync : 'T -&gt; System.Threading.Tasks.Task" Usage="iMobileServiceSyncTable.DeleteAsync instance" />
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
        <Parameter Name="instance" Type="T" />
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
    <Member MemberName="IncludeTotalCount">
      <MemberSignature Language="C#" Value="public Microsoft.WindowsAzure.MobileServices.IMobileServiceTableQuery&lt;T&gt; IncludeTotalCount ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.WindowsAzure.MobileServices.IMobileServiceTableQuery`1&lt;!T&gt; IncludeTotalCount() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.MobileServices.Sync.IMobileServiceSyncTable`1.IncludeTotalCount" />
      <MemberSignature Language="VB.NET" Value="Public Function IncludeTotalCount () As IMobileServiceTableQuery(Of T)" />
      <MemberSignature Language="F#" Value="abstract member IncludeTotalCount : unit -&gt; Microsoft.WindowsAzure.MobileServices.IMobileServiceTableQuery&lt;'T&gt;" Usage="iMobileServiceSyncTable.IncludeTotalCount " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Client</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.2.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.MobileServices.IMobileServiceTableQuery&lt;T&gt;</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            Erstellt eine Abfrage, mit die sichergestellt wird, dass die Gesamtanzahl für alle Datensätze, die zurückgegeben worden wären ignorieren Paging dauern /-Klausel, die vom Client oder Server angegebenen Limit herankommt.
            </summary>
        <returns>
            Eine Abfrage für die Tabelle.
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="InsertAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task InsertAsync (T instance);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task InsertAsync(!T instance) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.MobileServices.Sync.IMobileServiceSyncTable`1.InsertAsync(`0)" />
      <MemberSignature Language="VB.NET" Value="Public Function InsertAsync (instance As T) As Task" />
      <MemberSignature Language="F#" Value="abstract member InsertAsync : 'T -&gt; System.Threading.Tasks.Task" Usage="iMobileServiceSyncTable.InsertAsync instance" />
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
        <Parameter Name="instance" Type="T" />
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
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;T&gt; LookupAsync (string id);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;!T&gt; LookupAsync(string id) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.MobileServices.Sync.IMobileServiceSyncTable`1.LookupAsync(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function LookupAsync (id As String) As Task(Of T)" />
      <MemberSignature Language="F#" Value="abstract member LookupAsync : string -&gt; System.Threading.Tasks.Task&lt;'T&gt;" Usage="iMobileServiceSyncTable.LookupAsync id" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Client</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.2.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;T&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="id" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="id">
            Die Id der Instanz.
            </param>
        <summary>
            Suchen einer Instanz in einer Tabelle nach seiner Id.
            </summary>
        <returns>
            Die gewünschte Instanz.
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OrderBy&lt;TKey&gt;">
      <MemberSignature Language="C#" Value="public Microsoft.WindowsAzure.MobileServices.IMobileServiceTableQuery&lt;T&gt; OrderBy&lt;TKey&gt; (System.Linq.Expressions.Expression&lt;Func&lt;T,TKey&gt;&gt; keySelector);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.WindowsAzure.MobileServices.IMobileServiceTableQuery`1&lt;!T&gt; OrderBy&lt;TKey&gt;(class System.Linq.Expressions.Expression`1&lt;class System.Func`2&lt;!T, !!TKey&gt;&gt; keySelector) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.MobileServices.Sync.IMobileServiceSyncTable`1.OrderBy``1(System.Linq.Expressions.Expression{System.Func{`0,``0}})" />
      <MemberSignature Language="VB.NET" Value="Public Function OrderBy(Of TKey) (keySelector As Expression(Of Func(Of T, TKey))) As IMobileServiceTableQuery(Of T)" />
      <MemberSignature Language="F#" Value="abstract member OrderBy : System.Linq.Expressions.Expression&lt;Func&lt;'T, 'Key&gt;&gt; -&gt; Microsoft.WindowsAzure.MobileServices.IMobileServiceTableQuery&lt;'T&gt;" Usage="iMobileServiceSyncTable.OrderBy keySelector" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Client</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.2.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.MobileServices.IMobileServiceTableQuery&lt;T&gt;</ReturnType>
      </ReturnValue>
      <TypeParameters>
        <TypeParameter Name="TKey" />
      </TypeParameters>
      <Parameters>
        <Parameter Name="keySelector" Type="System.Linq.Expressions.Expression&lt;System.Func&lt;T,TKey&gt;&gt;" />
      </Parameters>
      <Docs>
        <typeparam name="TKey">
            Der Typ des Members, nach dem sortiert wird.
            </typeparam>
        <param name="keySelector">
            Der Ausdruck, der den Member auswählt, nach dem sortiert wird.
            </param>
        <summary>
            Erstellt eine Abfrage durch Anwenden der angegebenen ascending Order-Klausel an.
            </summary>
        <returns>
            Eine Abfrage für die Tabelle.
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OrderByDescending&lt;TKey&gt;">
      <MemberSignature Language="C#" Value="public Microsoft.WindowsAzure.MobileServices.IMobileServiceTableQuery&lt;T&gt; OrderByDescending&lt;TKey&gt; (System.Linq.Expressions.Expression&lt;Func&lt;T,TKey&gt;&gt; keySelector);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.WindowsAzure.MobileServices.IMobileServiceTableQuery`1&lt;!T&gt; OrderByDescending&lt;TKey&gt;(class System.Linq.Expressions.Expression`1&lt;class System.Func`2&lt;!T, !!TKey&gt;&gt; keySelector) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.MobileServices.Sync.IMobileServiceSyncTable`1.OrderByDescending``1(System.Linq.Expressions.Expression{System.Func{`0,``0}})" />
      <MemberSignature Language="VB.NET" Value="Public Function OrderByDescending(Of TKey) (keySelector As Expression(Of Func(Of T, TKey))) As IMobileServiceTableQuery(Of T)" />
      <MemberSignature Language="F#" Value="abstract member OrderByDescending : System.Linq.Expressions.Expression&lt;Func&lt;'T, 'Key&gt;&gt; -&gt; Microsoft.WindowsAzure.MobileServices.IMobileServiceTableQuery&lt;'T&gt;" Usage="iMobileServiceSyncTable.OrderByDescending keySelector" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Client</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.2.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.MobileServices.IMobileServiceTableQuery&lt;T&gt;</ReturnType>
      </ReturnValue>
      <TypeParameters>
        <TypeParameter Name="TKey" />
      </TypeParameters>
      <Parameters>
        <Parameter Name="keySelector" Type="System.Linq.Expressions.Expression&lt;System.Func&lt;T,TKey&gt;&gt;" />
      </Parameters>
      <Docs>
        <typeparam name="TKey">
            Der Typ des Members, nach dem sortiert wird.
            </typeparam>
        <param name="keySelector">
            Der Ausdruck, der den Member auswählt, nach dem sortiert wird.
            </param>
        <summary>
            Erstellt eine Abfrage durch Anwenden der angegebenen descending Order-Klausel an.
            </summary>
        <returns>
            Eine Abfrage für die Tabelle.
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PullAsync&lt;U&gt;">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task PullAsync&lt;U&gt; (string queryId, Microsoft.WindowsAzure.MobileServices.IMobileServiceTableQuery&lt;U&gt; query, bool pushOtherTables, System.Threading.CancellationToken cancellationToken, Microsoft.WindowsAzure.MobileServices.Sync.PullOptions pullOptions);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task PullAsync&lt;U&gt;(string queryId, class Microsoft.WindowsAzure.MobileServices.IMobileServiceTableQuery`1&lt;!!U&gt; query, bool pushOtherTables, valuetype System.Threading.CancellationToken cancellationToken, class Microsoft.WindowsAzure.MobileServices.Sync.PullOptions pullOptions) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.MobileServices.Sync.IMobileServiceSyncTable`1.PullAsync``1(System.String,Microsoft.WindowsAzure.MobileServices.IMobileServiceTableQuery{``0},System.Boolean,System.Threading.CancellationToken,Microsoft.WindowsAzure.MobileServices.Sync.PullOptions)" />
      <MemberSignature Language="F#" Value="abstract member PullAsync : string * Microsoft.WindowsAzure.MobileServices.IMobileServiceTableQuery&lt;'U&gt; * bool * System.Threading.CancellationToken * Microsoft.WindowsAzure.MobileServices.Sync.PullOptions -&gt; System.Threading.Tasks.Task" Usage="iMobileServiceSyncTable.PullAsync (queryId, query, pushOtherTables, cancellationToken, pullOptions)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Client</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.2.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <TypeParameters>
        <TypeParameter Name="U" />
      </TypeParameters>
      <Parameters>
        <Parameter Name="queryId" Type="System.String" />
        <Parameter Name="query" Type="Microsoft.WindowsAzure.MobileServices.IMobileServiceTableQuery&lt;U&gt;" />
        <Parameter Name="pushOtherTables" Type="System.Boolean" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
        <Parameter Name="pullOptions" Type="Microsoft.WindowsAzure.MobileServices.Sync.PullOptions" />
      </Parameters>
      <Docs>
        <typeparam name="U">To be added.</typeparam>
        <param name="queryId">
            Eine Zeichenfolge, die diese Abfrage bezeichnet und dient zum Nachverfolgen der Synchronisierungsstatus des eindeutig. Angabe dieses Parameters kann inkrementelle Synchronisierung an der gleiche Schlüssel erneut verwendet wird.
            </param>
        <param name="query">
            Eine OData-Abfrage, die bestimmt, welche Elemente aus der Remotetabelle abrufen.
            </param>
        <param name="pushOtherTables">
            Push andere Tabellen, wenn diese Tabelle geändert wurde.
            </param>
        <param name="cancellationToken">Die <see cref="T:System.Threading.CancellationToken" /> Token beobachten
            </param>
        <param name="pullOptions">
            PullOptions, die bestimmen, wie Daten aus der Remotetabelle abrufen
            </param>
        <summary>
            Ruft alle Elemente, die mit die angegebene Abfrage aus der zugeordneten Remotetabelle übereinstimmen.
            </summary>
        <returns>
            Eine Aufgabe, die abgeschlossen wird, wenn der Pullvorgang abgeschlossen ist.
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PurgeAsync&lt;U&gt;">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task PurgeAsync&lt;U&gt; (string queryId, Microsoft.WindowsAzure.MobileServices.IMobileServiceTableQuery&lt;U&gt; query, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task PurgeAsync&lt;U&gt;(string queryId, class Microsoft.WindowsAzure.MobileServices.IMobileServiceTableQuery`1&lt;!!U&gt; query, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.MobileServices.Sync.IMobileServiceSyncTable`1.PurgeAsync``1(System.String,Microsoft.WindowsAzure.MobileServices.IMobileServiceTableQuery{``0},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member PurgeAsync : string * Microsoft.WindowsAzure.MobileServices.IMobileServiceTableQuery&lt;'U&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="iMobileServiceSyncTable.PurgeAsync (queryId, query, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Client</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.2.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <TypeParameters>
        <TypeParameter Name="U" />
      </TypeParameters>
      <Parameters>
        <Parameter Name="queryId" Type="System.String" />
        <Parameter Name="query" Type="Microsoft.WindowsAzure.MobileServices.IMobileServiceTableQuery&lt;U&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <typeparam name="U">To be added.</typeparam>
        <param name="queryId">
            Eine Zeichenfolge, die diese Abfrage bezeichnet und dient zum Nachverfolgen der Synchronisierungsstatus des eindeutig. Dieser Parameter angeben, setzt den inkrementelle Synchronisierung-Zustand für die Abfrage.
            </param>
        <param name="query">Eine OData-Abfrage, die bestimmt, welche Elemente löschen.</param>
        <param name="cancellationToken">Die <see cref="T:System.Threading.CancellationToken" /> Token beobachten
            </param>
        <summary>
            Löscht alle Elemente in der lokalen Tabelle, die der Abfrage entsprechen.
            </summary>
        <returns>Eine Aufgabe, die beim Abschluss löschen Vorgang wurde beendet.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PurgeAsync&lt;U&gt;">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task PurgeAsync&lt;U&gt; (string queryId, Microsoft.WindowsAzure.MobileServices.IMobileServiceTableQuery&lt;U&gt; query, bool force, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task PurgeAsync&lt;U&gt;(string queryId, class Microsoft.WindowsAzure.MobileServices.IMobileServiceTableQuery`1&lt;!!U&gt; query, bool force, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.MobileServices.Sync.IMobileServiceSyncTable`1.PurgeAsync``1(System.String,Microsoft.WindowsAzure.MobileServices.IMobileServiceTableQuery{``0},System.Boolean,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member PurgeAsync : string * Microsoft.WindowsAzure.MobileServices.IMobileServiceTableQuery&lt;'U&gt; * bool * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="iMobileServiceSyncTable.PurgeAsync (queryId, query, force, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Client</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.2.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <TypeParameters>
        <TypeParameter Name="U" />
      </TypeParameters>
      <Parameters>
        <Parameter Name="queryId" Type="System.String" />
        <Parameter Name="query" Type="Microsoft.WindowsAzure.MobileServices.IMobileServiceTableQuery&lt;U&gt;" />
        <Parameter Name="force" Type="System.Boolean" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <typeparam name="U">To be added.</typeparam>
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
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;T&gt;&gt; ReadAsync ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class System.Collections.Generic.IEnumerable`1&lt;!T&gt;&gt; ReadAsync() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.MobileServices.Sync.IMobileServiceSyncTable`1.ReadAsync" />
      <MemberSignature Language="VB.NET" Value="Public Function ReadAsync () As Task(Of IEnumerable(Of T))" />
      <MemberSignature Language="F#" Value="abstract member ReadAsync : unit -&gt; System.Threading.Tasks.Task&lt;seq&lt;'T&gt;&gt;" Usage="iMobileServiceSyncTable.ReadAsync " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Client</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.2.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;T&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            Instanzen zurückgegeben aus einer Tabelle.
            </summary>
        <returns>
            Instanzen aus der Tabelle.
            </returns>
        <remarks>
            Dieser Aufruf wird Paging usw. ist für Sie nicht verarbeiten.
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ReadAsync&lt;U&gt;">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;U&gt;&gt; ReadAsync&lt;U&gt; (Microsoft.WindowsAzure.MobileServices.IMobileServiceTableQuery&lt;U&gt; query);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class System.Collections.Generic.IEnumerable`1&lt;!!U&gt;&gt; ReadAsync&lt;U&gt;(class Microsoft.WindowsAzure.MobileServices.IMobileServiceTableQuery`1&lt;!!U&gt; query) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.MobileServices.Sync.IMobileServiceSyncTable`1.ReadAsync``1(Microsoft.WindowsAzure.MobileServices.IMobileServiceTableQuery{``0})" />
      <MemberSignature Language="VB.NET" Value="Public Function ReadAsync(Of U) (query As IMobileServiceTableQuery(Of U)) As Task(Of IEnumerable(Of U))" />
      <MemberSignature Language="F#" Value="abstract member ReadAsync : Microsoft.WindowsAzure.MobileServices.IMobileServiceTableQuery&lt;'U&gt; -&gt; System.Threading.Tasks.Task&lt;seq&lt;'U&gt;&gt;" Usage="iMobileServiceSyncTable.ReadAsync query" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Client</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.2.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;U&gt;&gt;</ReturnType>
      </ReturnValue>
      <TypeParameters>
        <TypeParameter Name="U" />
      </TypeParameters>
      <Parameters>
        <Parameter Name="query" Type="Microsoft.WindowsAzure.MobileServices.IMobileServiceTableQuery&lt;U&gt;" />
      </Parameters>
      <Docs>
        <typeparam name="U">
            Der Typ der Instanz, die von der Abfrage zurückgegeben.
            </typeparam>
        <param name="query">
            Die auszuführende Abfrage.
            </param>
        <summary>
            Gibt Instanzen aus einer Tabelle basierend auf einer Abfrage zurück.
            </summary>
        <returns>
            Instanzen aus der Tabelle.
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RefreshAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task RefreshAsync (T instance);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task RefreshAsync(!T instance) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.MobileServices.Sync.IMobileServiceSyncTable`1.RefreshAsync(`0)" />
      <MemberSignature Language="VB.NET" Value="Public Function RefreshAsync (instance As T) As Task" />
      <MemberSignature Language="F#" Value="abstract member RefreshAsync : 'T -&gt; System.Threading.Tasks.Task" Usage="iMobileServiceSyncTable.RefreshAsync instance" />
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
        <Parameter Name="instance" Type="T" />
      </Parameters>
      <Docs>
        <param name="instance">
            Die Instanz zu aktualisieren.
            </param>
        <summary>
            Aktualisieren Sie die aktuelle Instanz mit der aktuellen Werte aus der lokalen Tabelle.
            </summary>
        <returns>
            Eine Aufgabe, die abgeschlossen wird, wenn der Aktualisierungsvorgang abgeschlossen ist.
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Select&lt;U&gt;">
      <MemberSignature Language="C#" Value="public Microsoft.WindowsAzure.MobileServices.IMobileServiceTableQuery&lt;U&gt; Select&lt;U&gt; (System.Linq.Expressions.Expression&lt;Func&lt;T,U&gt;&gt; selector);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.WindowsAzure.MobileServices.IMobileServiceTableQuery`1&lt;!!U&gt; Select&lt;U&gt;(class System.Linq.Expressions.Expression`1&lt;class System.Func`2&lt;!T, !!U&gt;&gt; selector) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.MobileServices.Sync.IMobileServiceSyncTable`1.Select``1(System.Linq.Expressions.Expression{System.Func{`0,``0}})" />
      <MemberSignature Language="VB.NET" Value="Public Function Select(Of U) (selector As Expression(Of Func(Of T, U))) As IMobileServiceTableQuery(Of U)" />
      <MemberSignature Language="F#" Value="abstract member Select : System.Linq.Expressions.Expression&lt;Func&lt;'T, 'U&gt;&gt; -&gt; Microsoft.WindowsAzure.MobileServices.IMobileServiceTableQuery&lt;'U&gt;" Usage="iMobileServiceSyncTable.Select selector" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Client</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.2.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.MobileServices.IMobileServiceTableQuery&lt;U&gt;</ReturnType>
      </ReturnValue>
      <TypeParameters>
        <TypeParameter Name="U" />
      </TypeParameters>
      <Parameters>
        <Parameter Name="selector" Type="System.Linq.Expressions.Expression&lt;System.Func&lt;T,U&gt;&gt;" />
      </Parameters>
      <Docs>
        <typeparam name="U">
            Der Typ, der das projizierte Ergebnis der Abfrage darstellt.
            </typeparam>
        <param name="selector">
            Die Auswahlfunktion.
            </param>
        <summary>
            Erstellt eine Abfrage durch Anwenden der angegebenen Auswahl.
            </summary>
        <returns>
            Eine Abfrage für die Tabelle.
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Skip">
      <MemberSignature Language="C#" Value="public Microsoft.WindowsAzure.MobileServices.IMobileServiceTableQuery&lt;T&gt; Skip (int count);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.WindowsAzure.MobileServices.IMobileServiceTableQuery`1&lt;!T&gt; Skip(int32 count) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.MobileServices.Sync.IMobileServiceSyncTable`1.Skip(System.Int32)" />
      <MemberSignature Language="VB.NET" Value="Public Function Skip (count As Integer) As IMobileServiceTableQuery(Of T)" />
      <MemberSignature Language="F#" Value="abstract member Skip : int -&gt; Microsoft.WindowsAzure.MobileServices.IMobileServiceTableQuery&lt;'T&gt;" Usage="iMobileServiceSyncTable.Skip count" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Client</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.2.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.MobileServices.IMobileServiceTableQuery&lt;T&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="count" Type="System.Int32" />
      </Parameters>
      <Docs>
        <param name="count">
            Die zu überspringende Zahl.
            </param>
        <summary>
            Erstellt eine Abfrage durch Anwenden der angegebenen Skip-Klausel.
            </summary>
        <returns>
            Eine Abfrage für die Tabelle.
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Take">
      <MemberSignature Language="C#" Value="public Microsoft.WindowsAzure.MobileServices.IMobileServiceTableQuery&lt;T&gt; Take (int count);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.WindowsAzure.MobileServices.IMobileServiceTableQuery`1&lt;!T&gt; Take(int32 count) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.MobileServices.Sync.IMobileServiceSyncTable`1.Take(System.Int32)" />
      <MemberSignature Language="VB.NET" Value="Public Function Take (count As Integer) As IMobileServiceTableQuery(Of T)" />
      <MemberSignature Language="F#" Value="abstract member Take : int -&gt; Microsoft.WindowsAzure.MobileServices.IMobileServiceTableQuery&lt;'T&gt;" Usage="iMobileServiceSyncTable.Take count" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Client</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.2.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.MobileServices.IMobileServiceTableQuery&lt;T&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="count" Type="System.Int32" />
      </Parameters>
      <Docs>
        <param name="count">
            Die zu erfassende Zahl.
            </param>
        <summary>
            Erstellt eine Abfrage durch Anwenden der angegebenen Take-Klausel.
            </summary>
        <returns>
            Eine Abfrage für die Tabelle.
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ThenBy&lt;TKey&gt;">
      <MemberSignature Language="C#" Value="public Microsoft.WindowsAzure.MobileServices.IMobileServiceTableQuery&lt;T&gt; ThenBy&lt;TKey&gt; (System.Linq.Expressions.Expression&lt;Func&lt;T,TKey&gt;&gt; keySelector);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.WindowsAzure.MobileServices.IMobileServiceTableQuery`1&lt;!T&gt; ThenBy&lt;TKey&gt;(class System.Linq.Expressions.Expression`1&lt;class System.Func`2&lt;!T, !!TKey&gt;&gt; keySelector) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.MobileServices.Sync.IMobileServiceSyncTable`1.ThenBy``1(System.Linq.Expressions.Expression{System.Func{`0,``0}})" />
      <MemberSignature Language="VB.NET" Value="Public Function ThenBy(Of TKey) (keySelector As Expression(Of Func(Of T, TKey))) As IMobileServiceTableQuery(Of T)" />
      <MemberSignature Language="F#" Value="abstract member ThenBy : System.Linq.Expressions.Expression&lt;Func&lt;'T, 'Key&gt;&gt; -&gt; Microsoft.WindowsAzure.MobileServices.IMobileServiceTableQuery&lt;'T&gt;" Usage="iMobileServiceSyncTable.ThenBy keySelector" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Client</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.2.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.MobileServices.IMobileServiceTableQuery&lt;T&gt;</ReturnType>
      </ReturnValue>
      <TypeParameters>
        <TypeParameter Name="TKey" />
      </TypeParameters>
      <Parameters>
        <Parameter Name="keySelector" Type="System.Linq.Expressions.Expression&lt;System.Func&lt;T,TKey&gt;&gt;" />
      </Parameters>
      <Docs>
        <typeparam name="TKey">
            Der Typ des Members, nach dem sortiert wird.
            </typeparam>
        <param name="keySelector">
            Der Ausdruck, der den Member auswählt, nach dem sortiert wird.
            </param>
        <summary>
            Erstellt eine Abfrage durch Anwenden der angegebenen ascending Order-Klausel an.
            </summary>
        <returns>
            Eine Abfrage für die Tabelle.
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ThenByDescending&lt;TKey&gt;">
      <MemberSignature Language="C#" Value="public Microsoft.WindowsAzure.MobileServices.IMobileServiceTableQuery&lt;T&gt; ThenByDescending&lt;TKey&gt; (System.Linq.Expressions.Expression&lt;Func&lt;T,TKey&gt;&gt; keySelector);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.WindowsAzure.MobileServices.IMobileServiceTableQuery`1&lt;!T&gt; ThenByDescending&lt;TKey&gt;(class System.Linq.Expressions.Expression`1&lt;class System.Func`2&lt;!T, !!TKey&gt;&gt; keySelector) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.MobileServices.Sync.IMobileServiceSyncTable`1.ThenByDescending``1(System.Linq.Expressions.Expression{System.Func{`0,``0}})" />
      <MemberSignature Language="VB.NET" Value="Public Function ThenByDescending(Of TKey) (keySelector As Expression(Of Func(Of T, TKey))) As IMobileServiceTableQuery(Of T)" />
      <MemberSignature Language="F#" Value="abstract member ThenByDescending : System.Linq.Expressions.Expression&lt;Func&lt;'T, 'Key&gt;&gt; -&gt; Microsoft.WindowsAzure.MobileServices.IMobileServiceTableQuery&lt;'T&gt;" Usage="iMobileServiceSyncTable.ThenByDescending keySelector" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Client</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.2.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.MobileServices.IMobileServiceTableQuery&lt;T&gt;</ReturnType>
      </ReturnValue>
      <TypeParameters>
        <TypeParameter Name="TKey" />
      </TypeParameters>
      <Parameters>
        <Parameter Name="keySelector" Type="System.Linq.Expressions.Expression&lt;System.Func&lt;T,TKey&gt;&gt;" />
      </Parameters>
      <Docs>
        <typeparam name="TKey">
            Der Typ des Members, nach dem sortiert wird.
            </typeparam>
        <param name="keySelector">
            Der Ausdruck, der den Member auswählt, nach dem sortiert wird.
            </param>
        <summary>
            Erstellt eine Abfrage durch Anwenden der angegebenen descending Order-Klausel an.
            </summary>
        <returns>
            Eine Abfrage für die Tabelle.
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ToEnumerableAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;T&gt;&gt; ToEnumerableAsync ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class System.Collections.Generic.IEnumerable`1&lt;!T&gt;&gt; ToEnumerableAsync() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.MobileServices.Sync.IMobileServiceSyncTable`1.ToEnumerableAsync" />
      <MemberSignature Language="VB.NET" Value="Public Function ToEnumerableAsync () As Task(Of IEnumerable(Of T))" />
      <MemberSignature Language="F#" Value="abstract member ToEnumerableAsync : unit -&gt; System.Threading.Tasks.Task&lt;seq&lt;'T&gt;&gt;" Usage="iMobileServiceSyncTable.ToEnumerableAsync " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Client</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.2.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;T&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            Ruft die Elemente der Tabelle asynchron ab.
            </summary>
        <returns>
            Die tabellenelementergebnisse als Sequenz.
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ToListAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Collections.Generic.List&lt;T&gt;&gt; ToListAsync ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class System.Collections.Generic.List`1&lt;!T&gt;&gt; ToListAsync() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.MobileServices.Sync.IMobileServiceSyncTable`1.ToListAsync" />
      <MemberSignature Language="VB.NET" Value="Public Function ToListAsync () As Task(Of List(Of T))" />
      <MemberSignature Language="F#" Value="abstract member ToListAsync : unit -&gt; System.Threading.Tasks.Task&lt;System.Collections.Generic.List&lt;'T&gt;&gt;" Usage="iMobileServiceSyncTable.ToListAsync " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Client</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.2.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Collections.Generic.List&lt;T&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            Ruft die Elemente der Tabelle asynchron ab, und geben Sie die Ergebnisse in eine neue Liste zurück.
            </summary>
        <returns>
            Die tabellenelementergebnisse als Liste.
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UpdateAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task UpdateAsync (T instance);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task UpdateAsync(!T instance) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.MobileServices.Sync.IMobileServiceSyncTable`1.UpdateAsync(`0)" />
      <MemberSignature Language="VB.NET" Value="Public Function UpdateAsync (instance As T) As Task" />
      <MemberSignature Language="F#" Value="abstract member UpdateAsync : 'T -&gt; System.Threading.Tasks.Task" Usage="iMobileServiceSyncTable.UpdateAsync instance" />
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
        <Parameter Name="instance" Type="T" />
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
    <Member MemberName="Where">
      <MemberSignature Language="C#" Value="public Microsoft.WindowsAzure.MobileServices.IMobileServiceTableQuery&lt;T&gt; Where (System.Linq.Expressions.Expression&lt;Func&lt;T,bool&gt;&gt; predicate);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.WindowsAzure.MobileServices.IMobileServiceTableQuery`1&lt;!T&gt; Where(class System.Linq.Expressions.Expression`1&lt;class System.Func`2&lt;!T, bool&gt;&gt; predicate) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.MobileServices.Sync.IMobileServiceSyncTable`1.Where(System.Linq.Expressions.Expression{System.Func{`0,System.Boolean}})" />
      <MemberSignature Language="VB.NET" Value="Public Function Where (predicate As Expression(Of Func(Of T, Boolean))) As IMobileServiceTableQuery(Of T)" />
      <MemberSignature Language="F#" Value="abstract member Where : System.Linq.Expressions.Expression&lt;Func&lt;'T, bool&gt;&gt; -&gt; Microsoft.WindowsAzure.MobileServices.IMobileServiceTableQuery&lt;'T&gt;" Usage="iMobileServiceSyncTable.Where predicate" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Client</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.2.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.MobileServices.IMobileServiceTableQuery&lt;T&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="predicate" Type="System.Linq.Expressions.Expression&lt;System.Func&lt;T,System.Boolean&gt;&gt;" />
      </Parameters>
      <Docs>
        <param name="predicate">
            Das Filterprädikat.
            </param>
        <summary>
            Erstellt eine Abfrage durch Anwenden des angegebenen filterprädikats.
            </summary>
        <returns>
            Eine Abfrage für die Tabelle.
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>