<Type Name="MobileServiceSyncTableExtensions" FullName="Microsoft.WindowsAzure.MobileServices.MobileServiceSyncTableExtensions">
  <TypeSignature Language="C#" Value="public static class MobileServiceSyncTableExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit MobileServiceSyncTableExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.WindowsAzure.MobileServices.MobileServiceSyncTableExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module MobileServiceSyncTableExtensions" />
  <TypeSignature Language="F#" Value="type MobileServiceSyncTableExtensions = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Mobile.Client</AssemblyName>
    <AssemblyVersion>4.0.0.0</AssemblyVersion>
    <AssemblyVersion>4.0.2.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            Enthält Erweiterungsmethoden [c#]<see cref="T:Microsoft.WindowsAzure.MobileServices.Sync.IMobileServiceSyncTable" /></summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="PullAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task PullAsync (this Microsoft.WindowsAzure.MobileServices.Sync.IMobileServiceSyncTable table, string queryId, string query);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task PullAsync(class Microsoft.WindowsAzure.MobileServices.Sync.IMobileServiceSyncTable table, string queryId, string query) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.MobileServices.MobileServiceSyncTableExtensions.PullAsync(Microsoft.WindowsAzure.MobileServices.Sync.IMobileServiceSyncTable,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function PullAsync (table As IMobileServiceSyncTable, queryId As String, query As String) As Task" />
      <MemberSignature Language="F#" Value="static member PullAsync : Microsoft.WindowsAzure.MobileServices.Sync.IMobileServiceSyncTable * string * string -&gt; System.Threading.Tasks.Task" Usage="Microsoft.WindowsAzure.MobileServices.MobileServiceSyncTableExtensions.PullAsync (table, queryId, query)" />
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
        <Parameter Name="table" Type="Microsoft.WindowsAzure.MobileServices.Sync.IMobileServiceSyncTable" RefType="this" />
        <Parameter Name="queryId" Type="System.String" />
        <Parameter Name="query" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="table">Die Instanz der Tabelle zum Ausführen von Pull auf.</param>
        <param name="queryId">
            Eine Zeichenfolge, die diese Abfrage bezeichnet und dient zum Nachverfolgen der Synchronisierungsstatus des eindeutig. Angabe dieses Parameters kann inkrementelle Synchronisierung an der gleiche Schlüssel erneut verwendet wird. 255 Zeichen oder weniger und nur alphanumerische Zeichen, Bindestriche und Unterstriche enthalten.
            </param>
        <param name="query">
            Eine OData-Abfrage, die bestimmt, welche Elemente aus der Remotetabelle abrufen.
            </param>
        <summary>
            Ruft alle Elemente, die mit die angegebene Abfrage aus der zugeordneten Remotetabelle übereinstimmen. Unterstützt inkrementelle Synchronisierung.
            </summary>
        <returns>
            Eine Aufgabe, die abgeschlossen wird, wenn der Pullvorgang abgeschlossen ist.
            </returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentException">
            Wird ausgelöst, wenn <paramref name="queryId" />entspricht nicht den regulären Ausdruck <value>[a-zA-Z][a-zA-Z0-9_-]{1,255}</value>.
            </exception>
      </Docs>
    </Member>
    <Member MemberName="PullAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task PullAsync (this Microsoft.WindowsAzure.MobileServices.Sync.IMobileServiceSyncTable table, string queryId, string query, Microsoft.WindowsAzure.MobileServices.Sync.PullOptions pullOptions);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task PullAsync(class Microsoft.WindowsAzure.MobileServices.Sync.IMobileServiceSyncTable table, string queryId, string query, class Microsoft.WindowsAzure.MobileServices.Sync.PullOptions pullOptions) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.MobileServices.MobileServiceSyncTableExtensions.PullAsync(Microsoft.WindowsAzure.MobileServices.Sync.IMobileServiceSyncTable,System.String,System.String,Microsoft.WindowsAzure.MobileServices.Sync.PullOptions)" />
      <MemberSignature Language="F#" Value="static member PullAsync : Microsoft.WindowsAzure.MobileServices.Sync.IMobileServiceSyncTable * string * string * Microsoft.WindowsAzure.MobileServices.Sync.PullOptions -&gt; System.Threading.Tasks.Task" Usage="Microsoft.WindowsAzure.MobileServices.MobileServiceSyncTableExtensions.PullAsync (table, queryId, query, pullOptions)" />
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
        <Parameter Name="table" Type="Microsoft.WindowsAzure.MobileServices.Sync.IMobileServiceSyncTable" RefType="this" />
        <Parameter Name="queryId" Type="System.String" />
        <Parameter Name="query" Type="System.String" />
        <Parameter Name="pullOptions" Type="Microsoft.WindowsAzure.MobileServices.Sync.PullOptions" />
      </Parameters>
      <Docs>
        <param name="table">Die Instanz der Tabelle zum Ausführen von Pull auf.</param>
        <param name="queryId">
            Eine Zeichenfolge, die diese Abfrage bezeichnet und dient zum Nachverfolgen der Synchronisierungsstatus des eindeutig. Angabe dieses Parameters kann inkrementelle Synchronisierung an der gleiche Schlüssel erneut verwendet wird. 255 Zeichen oder weniger und nur alphanumerische Zeichen, Bindestriche und Unterstriche enthalten.
            </param>
        <param name="query">
            Eine OData-Abfrage, die bestimmt, welche Elemente aus der Remotetabelle abrufen.
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
        <exception cref="T:System.ArgumentException">
            Wird ausgelöst, wenn <paramref name="queryId" /> entspricht nicht den regulären Ausdruck <value>[a-zA-Z][a-zA-Z0-9_-]{1,255}</value>.
            </exception>
      </Docs>
    </Member>
    <Member MemberName="PullAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task PullAsync (this Microsoft.WindowsAzure.MobileServices.Sync.IMobileServiceSyncTable table, string queryId, string query, System.Collections.Generic.IDictionary&lt;string,string&gt; parameters, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task PullAsync(class Microsoft.WindowsAzure.MobileServices.Sync.IMobileServiceSyncTable table, string queryId, string query, class System.Collections.Generic.IDictionary`2&lt;string, string&gt; parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.MobileServices.MobileServiceSyncTableExtensions.PullAsync(Microsoft.WindowsAzure.MobileServices.Sync.IMobileServiceSyncTable,System.String,System.String,System.Collections.Generic.IDictionary{System.String,System.String},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member PullAsync : Microsoft.WindowsAzure.MobileServices.Sync.IMobileServiceSyncTable * string * string * System.Collections.Generic.IDictionary&lt;string, string&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.WindowsAzure.MobileServices.MobileServiceSyncTableExtensions.PullAsync (table, queryId, query, parameters, cancellationToken)" />
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
        <Parameter Name="table" Type="Microsoft.WindowsAzure.MobileServices.Sync.IMobileServiceSyncTable" RefType="this" />
        <Parameter Name="queryId" Type="System.String" />
        <Parameter Name="query" Type="System.String" />
        <Parameter Name="parameters" Type="System.Collections.Generic.IDictionary&lt;System.String,System.String&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="table">Die Instanz der Tabelle zum Ausführen von Pull auf.</param>
        <param name="queryId">
            Eine Zeichenfolge, die diese Abfrage bezeichnet und dient zum Nachverfolgen der Synchronisierungsstatus des eindeutig. Angabe dieses Parameters kann inkrementelle Synchronisierung an der gleiche Schlüssel erneut verwendet wird. 255 Zeichen oder weniger und nur alphanumerische Zeichen, Bindestriche und Unterstriche enthalten.
            </param>
        <param name="query">
            Eine OData-Abfrage, die bestimmt, welche Elemente aus der Remotetabelle abrufen.
            </param>
        <param name="parameters">
            Ein Wörterbuch mit benutzerdefinierten Parametern und Werten, die im Anforderungs-URI-Abfragezeichenfolge enthalten.
            </param>
        <param name="cancellationToken">Die <see cref="T:System.Threading.CancellationToken" />Token beobachten</param>
        <summary>
            Ruft alle Elemente, die mit die angegebene Abfrage aus der zugeordneten Remotetabelle übereinstimmen. Unterstützt inkrementelle Synchronisierung.
            </summary>
        <returns>
            Eine Aufgabe, die abgeschlossen wird, wenn der Pullvorgang abgeschlossen ist.
            </returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentException">
            Wird ausgelöst, wenn <paramref name="queryId" /> entspricht nicht den regulären Ausdruck <value>[a-zA-Z][a-zA-Z0-9_-]{1,255}</value>.
            </exception>
      </Docs>
    </Member>
    <Member MemberName="PullAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task PullAsync (this Microsoft.WindowsAzure.MobileServices.Sync.IMobileServiceSyncTable table, string queryId, string query, System.Collections.Generic.IDictionary&lt;string,string&gt; parameters, bool pushOtherTables, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task PullAsync(class Microsoft.WindowsAzure.MobileServices.Sync.IMobileServiceSyncTable table, string queryId, string query, class System.Collections.Generic.IDictionary`2&lt;string, string&gt; parameters, bool pushOtherTables, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.MobileServices.MobileServiceSyncTableExtensions.PullAsync(Microsoft.WindowsAzure.MobileServices.Sync.IMobileServiceSyncTable,System.String,System.String,System.Collections.Generic.IDictionary{System.String,System.String},System.Boolean,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member PullAsync : Microsoft.WindowsAzure.MobileServices.Sync.IMobileServiceSyncTable * string * string * System.Collections.Generic.IDictionary&lt;string, string&gt; * bool * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.WindowsAzure.MobileServices.MobileServiceSyncTableExtensions.PullAsync (table, queryId, query, parameters, pushOtherTables, cancellationToken)" />
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
        <Parameter Name="table" Type="Microsoft.WindowsAzure.MobileServices.Sync.IMobileServiceSyncTable" RefType="this" />
        <Parameter Name="queryId" Type="System.String" />
        <Parameter Name="query" Type="System.String" />
        <Parameter Name="parameters" Type="System.Collections.Generic.IDictionary&lt;System.String,System.String&gt;" />
        <Parameter Name="pushOtherTables" Type="System.Boolean" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="table">To be added.</param>
        <param name="queryId">
            Eine Zeichenfolge, die diese Abfrage bezeichnet und dient zum Nachverfolgen der Synchronisierungsstatus des eindeutig. Angabe dieses Parameters kann inkrementelle Synchronisierung an der gleiche Schlüssel erneut verwendet wird. 255 Zeichen oder weniger und nur alphanumerische Zeichen, Bindestriche und Unterstriche enthalten
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
        <summary>
            Ruft alle Elemente, die mit die angegebene Abfrage aus der zugeordneten Remotetabelle übereinstimmen. Unterstützt inkrementelle Synchronisierung.
            </summary>
        <returns>
            Eine Aufgabe, die abgeschlossen wird, wenn der Pullvorgang abgeschlossen ist.
            </returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentException">
            Wird ausgelöst, wenn <paramref name="queryId" /> entspricht nicht den regulären Ausdruck <value>[a-zA-Z][a-zA-Z0-9_-]{1,255}</value>.
            </exception>
      </Docs>
    </Member>
    <Member MemberName="PullAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task PullAsync (this Microsoft.WindowsAzure.MobileServices.Sync.IMobileServiceSyncTable table, string queryId, string query, System.Collections.Generic.IDictionary&lt;string,string&gt; parameters, System.Threading.CancellationToken cancellationToken, Microsoft.WindowsAzure.MobileServices.Sync.PullOptions pullOptions);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task PullAsync(class Microsoft.WindowsAzure.MobileServices.Sync.IMobileServiceSyncTable table, string queryId, string query, class System.Collections.Generic.IDictionary`2&lt;string, string&gt; parameters, valuetype System.Threading.CancellationToken cancellationToken, class Microsoft.WindowsAzure.MobileServices.Sync.PullOptions pullOptions) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.MobileServices.MobileServiceSyncTableExtensions.PullAsync(Microsoft.WindowsAzure.MobileServices.Sync.IMobileServiceSyncTable,System.String,System.String,System.Collections.Generic.IDictionary{System.String,System.String},System.Threading.CancellationToken,Microsoft.WindowsAzure.MobileServices.Sync.PullOptions)" />
      <MemberSignature Language="F#" Value="static member PullAsync : Microsoft.WindowsAzure.MobileServices.Sync.IMobileServiceSyncTable * string * string * System.Collections.Generic.IDictionary&lt;string, string&gt; * System.Threading.CancellationToken * Microsoft.WindowsAzure.MobileServices.Sync.PullOptions -&gt; System.Threading.Tasks.Task" Usage="Microsoft.WindowsAzure.MobileServices.MobileServiceSyncTableExtensions.PullAsync (table, queryId, query, parameters, cancellationToken, pullOptions)" />
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
        <Parameter Name="table" Type="Microsoft.WindowsAzure.MobileServices.Sync.IMobileServiceSyncTable" RefType="this" />
        <Parameter Name="queryId" Type="System.String" />
        <Parameter Name="query" Type="System.String" />
        <Parameter Name="parameters" Type="System.Collections.Generic.IDictionary&lt;System.String,System.String&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
        <Parameter Name="pullOptions" Type="Microsoft.WindowsAzure.MobileServices.Sync.PullOptions" />
      </Parameters>
      <Docs>
        <param name="table">Die Instanz der Tabelle zum Ausführen von Pull auf.</param>
        <param name="queryId">
            Eine Zeichenfolge, die diese Abfrage bezeichnet und dient zum Nachverfolgen der Synchronisierungsstatus des eindeutig. Angabe dieses Parameters kann inkrementelle Synchronisierung an der gleiche Schlüssel erneut verwendet wird. 255 Zeichen oder weniger und nur alphanumerische Zeichen, Bindestriche und Unterstriche enthalten.
            </param>
        <param name="query">
            Eine OData-Abfrage, die bestimmt, welche Elemente aus der Remotetabelle abrufen.
            </param>
        <param name="parameters">
            Ein Wörterbuch mit benutzerdefinierten Parametern und Werten, die im Anforderungs-URI-Abfragezeichenfolge enthalten.
            </param>
        <param name="cancellationToken">Die <see cref="T:System.Threading.CancellationToken" />Token beobachten</param>
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
        <exception cref="T:System.ArgumentException">
            Wird ausgelöst, wenn <paramref name="queryId" /> entspricht nicht den regulären Ausdruck <value>[a-zA-Z][a-zA-Z0-9_-]{1,255}</value>.
            </exception>
      </Docs>
    </Member>
    <Member MemberName="PullAsync&lt;T,U&gt;">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task PullAsync&lt;T,U&gt; (this Microsoft.WindowsAzure.MobileServices.Sync.IMobileServiceSyncTable&lt;T&gt; table, string queryId, Microsoft.WindowsAzure.MobileServices.IMobileServiceTableQuery&lt;U&gt; query);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task PullAsync&lt;T, U&gt;(class Microsoft.WindowsAzure.MobileServices.Sync.IMobileServiceSyncTable`1&lt;!!T&gt; table, string queryId, class Microsoft.WindowsAzure.MobileServices.IMobileServiceTableQuery`1&lt;!!U&gt; query) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.MobileServices.MobileServiceSyncTableExtensions.PullAsync``2(Microsoft.WindowsAzure.MobileServices.Sync.IMobileServiceSyncTable{``0},System.String,Microsoft.WindowsAzure.MobileServices.IMobileServiceTableQuery{``1})" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function PullAsync(Of T, U) (table As IMobileServiceSyncTable(Of T), queryId As String, query As IMobileServiceTableQuery(Of U)) As Task" />
      <MemberSignature Language="F#" Value="static member PullAsync : Microsoft.WindowsAzure.MobileServices.Sync.IMobileServiceSyncTable&lt;'T&gt; * string * Microsoft.WindowsAzure.MobileServices.IMobileServiceTableQuery&lt;'U&gt; -&gt; System.Threading.Tasks.Task" Usage="Microsoft.WindowsAzure.MobileServices.MobileServiceSyncTableExtensions.PullAsync (table, queryId, query)" />
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
        <TypeParameter Name="T" />
        <TypeParameter Name="U" />
      </TypeParameters>
      <Parameters>
        <Parameter Name="table" Type="Microsoft.WindowsAzure.MobileServices.Sync.IMobileServiceSyncTable&lt;T&gt;" RefType="this" />
        <Parameter Name="queryId" Type="System.String" />
        <Parameter Name="query" Type="Microsoft.WindowsAzure.MobileServices.IMobileServiceTableQuery&lt;U&gt;" />
      </Parameters>
      <Docs>
        <typeparam name="T">To be added.</typeparam>
        <typeparam name="U">To be added.</typeparam>
        <param name="table">Die Instanz der Tabelle zum Ausführen von Pull auf.</param>
        <param name="queryId">
            Eine Zeichenfolge, die diese Abfrage bezeichnet und dient zum Nachverfolgen der Synchronisierungsstatus des eindeutig. Angabe dieses Parameters kann inkrementelle Synchronisierung an der gleiche Schlüssel erneut verwendet wird. 255 Zeichen oder weniger und nur alphanumerische Zeichen, Bindestriche und Unterstriche enthalten
            </param>
        <param name="query">
            Eine OData-Abfrage, die bestimmt, welche Elemente aus der Remotetabelle abrufen.
            </param>
        <summary>
            Ruft alle Elemente, die mit die angegebene Abfrage aus der zugeordneten Remotetabelle übereinstimmen.
            </summary>
        <returns>
            Eine Aufgabe, die abgeschlossen wird, wenn der Pullvorgang abgeschlossen ist.
            </returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentException">
            Wird ausgelöst, wenn <paramref name="queryId" /> entspricht nicht den regulären Ausdruck <value>[a-zA-Z][a-zA-Z0-9_-]{1,255}</value>.
            </exception>
      </Docs>
    </Member>
    <Member MemberName="PullAsync&lt;T,U&gt;">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task PullAsync&lt;T,U&gt; (this Microsoft.WindowsAzure.MobileServices.Sync.IMobileServiceSyncTable&lt;T&gt; table, string queryId, Microsoft.WindowsAzure.MobileServices.IMobileServiceTableQuery&lt;U&gt; query, Microsoft.WindowsAzure.MobileServices.Sync.PullOptions pullOptions);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task PullAsync&lt;T, U&gt;(class Microsoft.WindowsAzure.MobileServices.Sync.IMobileServiceSyncTable`1&lt;!!T&gt; table, string queryId, class Microsoft.WindowsAzure.MobileServices.IMobileServiceTableQuery`1&lt;!!U&gt; query, class Microsoft.WindowsAzure.MobileServices.Sync.PullOptions pullOptions) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.MobileServices.MobileServiceSyncTableExtensions.PullAsync``2(Microsoft.WindowsAzure.MobileServices.Sync.IMobileServiceSyncTable{``0},System.String,Microsoft.WindowsAzure.MobileServices.IMobileServiceTableQuery{``1},Microsoft.WindowsAzure.MobileServices.Sync.PullOptions)" />
      <MemberSignature Language="F#" Value="static member PullAsync : Microsoft.WindowsAzure.MobileServices.Sync.IMobileServiceSyncTable&lt;'T&gt; * string * Microsoft.WindowsAzure.MobileServices.IMobileServiceTableQuery&lt;'U&gt; * Microsoft.WindowsAzure.MobileServices.Sync.PullOptions -&gt; System.Threading.Tasks.Task" Usage="Microsoft.WindowsAzure.MobileServices.MobileServiceSyncTableExtensions.PullAsync (table, queryId, query, pullOptions)" />
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
        <TypeParameter Name="T" />
        <TypeParameter Name="U" />
      </TypeParameters>
      <Parameters>
        <Parameter Name="table" Type="Microsoft.WindowsAzure.MobileServices.Sync.IMobileServiceSyncTable&lt;T&gt;" RefType="this" />
        <Parameter Name="queryId" Type="System.String" />
        <Parameter Name="query" Type="Microsoft.WindowsAzure.MobileServices.IMobileServiceTableQuery&lt;U&gt;" />
        <Parameter Name="pullOptions" Type="Microsoft.WindowsAzure.MobileServices.Sync.PullOptions" />
      </Parameters>
      <Docs>
        <typeparam name="T">To be added.</typeparam>
        <typeparam name="U">To be added.</typeparam>
        <param name="table">Die Instanz der Tabelle zum Ausführen von Pull auf.</param>
        <param name="queryId">
            Eine Zeichenfolge, die diese Abfrage bezeichnet und dient zum Nachverfolgen der Synchronisierungsstatus des eindeutig. Angabe dieses Parameters kann inkrementelle Synchronisierung an der gleiche Schlüssel erneut verwendet wird. 255 Zeichen oder weniger und nur alphanumerische Zeichen, Bindestriche und Unterstriche enthalten
            </param>
        <param name="query">
            Eine OData-Abfrage, die bestimmt, welche Elemente aus der Remotetabelle abrufen.
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
        <exception cref="T:System.ArgumentException">
            Wird ausgelöst, wenn <paramref name="queryId" /> entspricht nicht den regulären Ausdruck <value>[a-zA-Z][a-zA-Z0-9_-]{1,255}</value>.
            </exception>
      </Docs>
    </Member>
    <Member MemberName="PullAsync&lt;T,U&gt;">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task PullAsync&lt;T,U&gt; (this Microsoft.WindowsAzure.MobileServices.Sync.IMobileServiceSyncTable&lt;T&gt; table, string queryId, Microsoft.WindowsAzure.MobileServices.IMobileServiceTableQuery&lt;U&gt; query, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task PullAsync&lt;T, U&gt;(class Microsoft.WindowsAzure.MobileServices.Sync.IMobileServiceSyncTable`1&lt;!!T&gt; table, string queryId, class Microsoft.WindowsAzure.MobileServices.IMobileServiceTableQuery`1&lt;!!U&gt; query, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.MobileServices.MobileServiceSyncTableExtensions.PullAsync``2(Microsoft.WindowsAzure.MobileServices.Sync.IMobileServiceSyncTable{``0},System.String,Microsoft.WindowsAzure.MobileServices.IMobileServiceTableQuery{``1},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member PullAsync : Microsoft.WindowsAzure.MobileServices.Sync.IMobileServiceSyncTable&lt;'T&gt; * string * Microsoft.WindowsAzure.MobileServices.IMobileServiceTableQuery&lt;'U&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.WindowsAzure.MobileServices.MobileServiceSyncTableExtensions.PullAsync (table, queryId, query, cancellationToken)" />
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
        <TypeParameter Name="T" />
        <TypeParameter Name="U" />
      </TypeParameters>
      <Parameters>
        <Parameter Name="table" Type="Microsoft.WindowsAzure.MobileServices.Sync.IMobileServiceSyncTable&lt;T&gt;" RefType="this" />
        <Parameter Name="queryId" Type="System.String" />
        <Parameter Name="query" Type="Microsoft.WindowsAzure.MobileServices.IMobileServiceTableQuery&lt;U&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <typeparam name="T">To be added.</typeparam>
        <typeparam name="U">To be added.</typeparam>
        <param name="table">Die Instanz der Tabelle zum Ausführen von Pull auf.</param>
        <param name="queryId">
            Eine Zeichenfolge, die diese Abfrage bezeichnet und dient zum Nachverfolgen der Synchronisierungsstatus des eindeutig. Angabe dieses Parameters kann inkrementelle Synchronisierung an der gleiche Schlüssel erneut verwendet wird. 255 Zeichen oder weniger und nur alphanumerische Zeichen, Bindestriche und Unterstriche enthalten
            </param>
        <param name="query">
            Eine OData-Abfrage, die bestimmt, welche Elemente aus der Remotetabelle abrufen.
            </param>
        <param name="cancellationToken">Die <see cref="T:System.Threading.CancellationToken" /> Token beobachten
            </param>
        <summary>
            Ruft alle Elemente, die mit die angegebene Abfrage aus der zugeordneten Remotetabelle übereinstimmen.
            </summary>
        <returns>
            Eine Aufgabe, die abgeschlossen wird, wenn der Pullvorgang abgeschlossen ist.
            </returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentException">
            Wird ausgelöst, wenn <paramref name="queryId" /> entspricht nicht den regulären Ausdruck <value>[a-zA-Z][a-zA-Z0-9_-]{1,255}</value>.
            </exception>
      </Docs>
    </Member>
    <Member MemberName="PullAsync&lt;T,U&gt;">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task PullAsync&lt;T,U&gt; (this Microsoft.WindowsAzure.MobileServices.Sync.IMobileServiceSyncTable&lt;T&gt; table, string queryId, Microsoft.WindowsAzure.MobileServices.IMobileServiceTableQuery&lt;U&gt; query, bool pushOtherTables, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task PullAsync&lt;T, U&gt;(class Microsoft.WindowsAzure.MobileServices.Sync.IMobileServiceSyncTable`1&lt;!!T&gt; table, string queryId, class Microsoft.WindowsAzure.MobileServices.IMobileServiceTableQuery`1&lt;!!U&gt; query, bool pushOtherTables, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.MobileServices.MobileServiceSyncTableExtensions.PullAsync``2(Microsoft.WindowsAzure.MobileServices.Sync.IMobileServiceSyncTable{``0},System.String,Microsoft.WindowsAzure.MobileServices.IMobileServiceTableQuery{``1},System.Boolean,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member PullAsync : Microsoft.WindowsAzure.MobileServices.Sync.IMobileServiceSyncTable&lt;'T&gt; * string * Microsoft.WindowsAzure.MobileServices.IMobileServiceTableQuery&lt;'U&gt; * bool * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.WindowsAzure.MobileServices.MobileServiceSyncTableExtensions.PullAsync (table, queryId, query, pushOtherTables, cancellationToken)" />
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
        <TypeParameter Name="T" />
        <TypeParameter Name="U" />
      </TypeParameters>
      <Parameters>
        <Parameter Name="table" Type="Microsoft.WindowsAzure.MobileServices.Sync.IMobileServiceSyncTable&lt;T&gt;" RefType="this" />
        <Parameter Name="queryId" Type="System.String" />
        <Parameter Name="query" Type="Microsoft.WindowsAzure.MobileServices.IMobileServiceTableQuery&lt;U&gt;" />
        <Parameter Name="pushOtherTables" Type="System.Boolean" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <typeparam name="T">To be added.</typeparam>
        <typeparam name="U">To be added.</typeparam>
        <param name="table">To be added.</param>
        <param name="queryId">
            Eine Zeichenfolge, die diese Abfrage bezeichnet und dient zum Nachverfolgen der Synchronisierungsstatus des eindeutig. Angabe dieses Parameters kann inkrementelle Synchronisierung an der gleiche Schlüssel erneut verwendet wird. 255 Zeichen oder weniger und nur alphanumerische Zeichen, Bindestriche und Unterstriche enthalten
            </param>
        <param name="query">
            Eine OData-Abfrage, die bestimmt, welche Elemente aus der Remotetabelle abrufen.
            </param>
        <param name="pushOtherTables">
            Push andere Tabellen, wenn diese Tabelle geändert wurde.
            </param>
        <param name="cancellationToken">Die <see cref="T:System.Threading.CancellationToken" /> Token beobachten
            </param>
        <summary>
            Ruft alle Elemente, die mit die angegebene Abfrage aus der zugeordneten Remotetabelle übereinstimmen.
            </summary>
        <returns>
            Eine Aufgabe, die abgeschlossen wird, wenn der Pullvorgang abgeschlossen ist.
            </returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentException">
            Wird ausgelöst, wenn <paramref name="queryId" /> entspricht nicht den regulären Ausdruck <value>[a-zA-Z][a-zA-Z0-9_-]{1,255}</value>.
            </exception>
      </Docs>
    </Member>
    <Member MemberName="PullAsync&lt;T,U&gt;">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task PullAsync&lt;T,U&gt; (this Microsoft.WindowsAzure.MobileServices.Sync.IMobileServiceSyncTable&lt;T&gt; table, string queryId, Microsoft.WindowsAzure.MobileServices.IMobileServiceTableQuery&lt;U&gt; query, System.Threading.CancellationToken cancellationToken, Microsoft.WindowsAzure.MobileServices.Sync.PullOptions pullOptions);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task PullAsync&lt;T, U&gt;(class Microsoft.WindowsAzure.MobileServices.Sync.IMobileServiceSyncTable`1&lt;!!T&gt; table, string queryId, class Microsoft.WindowsAzure.MobileServices.IMobileServiceTableQuery`1&lt;!!U&gt; query, valuetype System.Threading.CancellationToken cancellationToken, class Microsoft.WindowsAzure.MobileServices.Sync.PullOptions pullOptions) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.MobileServices.MobileServiceSyncTableExtensions.PullAsync``2(Microsoft.WindowsAzure.MobileServices.Sync.IMobileServiceSyncTable{``0},System.String,Microsoft.WindowsAzure.MobileServices.IMobileServiceTableQuery{``1},System.Threading.CancellationToken,Microsoft.WindowsAzure.MobileServices.Sync.PullOptions)" />
      <MemberSignature Language="F#" Value="static member PullAsync : Microsoft.WindowsAzure.MobileServices.Sync.IMobileServiceSyncTable&lt;'T&gt; * string * Microsoft.WindowsAzure.MobileServices.IMobileServiceTableQuery&lt;'U&gt; * System.Threading.CancellationToken * Microsoft.WindowsAzure.MobileServices.Sync.PullOptions -&gt; System.Threading.Tasks.Task" Usage="Microsoft.WindowsAzure.MobileServices.MobileServiceSyncTableExtensions.PullAsync (table, queryId, query, cancellationToken, pullOptions)" />
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
        <TypeParameter Name="T" />
        <TypeParameter Name="U" />
      </TypeParameters>
      <Parameters>
        <Parameter Name="table" Type="Microsoft.WindowsAzure.MobileServices.Sync.IMobileServiceSyncTable&lt;T&gt;" RefType="this" />
        <Parameter Name="queryId" Type="System.String" />
        <Parameter Name="query" Type="Microsoft.WindowsAzure.MobileServices.IMobileServiceTableQuery&lt;U&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
        <Parameter Name="pullOptions" Type="Microsoft.WindowsAzure.MobileServices.Sync.PullOptions" />
      </Parameters>
      <Docs>
        <typeparam name="T">To be added.</typeparam>
        <typeparam name="U">To be added.</typeparam>
        <param name="table">Die Instanz der Tabelle zum Ausführen von Pull auf.</param>
        <param name="queryId">
            Eine Zeichenfolge, die diese Abfrage bezeichnet und dient zum Nachverfolgen der Synchronisierungsstatus des eindeutig. Angabe dieses Parameters kann inkrementelle Synchronisierung an der gleiche Schlüssel erneut verwendet wird. 255 Zeichen oder weniger und nur alphanumerische Zeichen, Bindestriche und Unterstriche enthalten
            </param>
        <param name="query">
            Eine OData-Abfrage, die bestimmt, welche Elemente aus der Remotetabelle abrufen.
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
        <exception cref="T:System.ArgumentException">
            Wird ausgelöst, wenn <paramref name="queryId" /> entspricht nicht den regulären Ausdruck <value>[a-zA-Z][a-zA-Z0-9_-]{1,255}</value>.
            </exception>
      </Docs>
    </Member>
    <Member MemberName="PurgeAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task PurgeAsync (this Microsoft.WindowsAzure.MobileServices.Sync.IMobileServiceSyncTable table);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task PurgeAsync(class Microsoft.WindowsAzure.MobileServices.Sync.IMobileServiceSyncTable table) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.MobileServices.MobileServiceSyncTableExtensions.PurgeAsync(Microsoft.WindowsAzure.MobileServices.Sync.IMobileServiceSyncTable)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function PurgeAsync (table As IMobileServiceSyncTable) As Task" />
      <MemberSignature Language="F#" Value="static member PurgeAsync : Microsoft.WindowsAzure.MobileServices.Sync.IMobileServiceSyncTable -&gt; System.Threading.Tasks.Task" Usage="Microsoft.WindowsAzure.MobileServices.MobileServiceSyncTableExtensions.PurgeAsync table" />
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
        <Parameter Name="table" Type="Microsoft.WindowsAzure.MobileServices.Sync.IMobileServiceSyncTable" RefType="this" />
      </Parameters>
      <Docs>
        <param name="table">Die Instanz der Tabelle auszuführende löschen auf.</param>
        <summary>
            Löscht alle Elemente im lokalen Tabelle
            </summary>
        <returns>Eine Aufgabe, die beim Abschluss löschen Vorgang wurde beendet.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PurgeAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task PurgeAsync (this Microsoft.WindowsAzure.MobileServices.Sync.IMobileServiceSyncTable table, bool force);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task PurgeAsync(class Microsoft.WindowsAzure.MobileServices.Sync.IMobileServiceSyncTable table, bool force) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.MobileServices.MobileServiceSyncTableExtensions.PurgeAsync(Microsoft.WindowsAzure.MobileServices.Sync.IMobileServiceSyncTable,System.Boolean)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function PurgeAsync (table As IMobileServiceSyncTable, force As Boolean) As Task" />
      <MemberSignature Language="F#" Value="static member PurgeAsync : Microsoft.WindowsAzure.MobileServices.Sync.IMobileServiceSyncTable * bool -&gt; System.Threading.Tasks.Task" Usage="Microsoft.WindowsAzure.MobileServices.MobileServiceSyncTableExtensions.PurgeAsync (table, force)" />
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
        <Parameter Name="table" Type="Microsoft.WindowsAzure.MobileServices.Sync.IMobileServiceSyncTable" RefType="this" />
        <Parameter Name="force" Type="System.Boolean" />
      </Parameters>
      <Docs>
        <param name="table">Die Instanz der Tabelle auszuführende löschen auf.</param>
        <param name="force">Erzwingen Sie Löschvorgang durch das Verwerfen der ausstehenden Vorgänge.</param>
        <summary>
            Löscht alle Elemente im lokalen Tabelle
            </summary>
        <returns>Eine Aufgabe, die beim Abschluss löschen Vorgang wurde beendet.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PurgeAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task PurgeAsync (this Microsoft.WindowsAzure.MobileServices.Sync.IMobileServiceSyncTable table, string query);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task PurgeAsync(class Microsoft.WindowsAzure.MobileServices.Sync.IMobileServiceSyncTable table, string query) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.MobileServices.MobileServiceSyncTableExtensions.PurgeAsync(Microsoft.WindowsAzure.MobileServices.Sync.IMobileServiceSyncTable,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function PurgeAsync (table As IMobileServiceSyncTable, query As String) As Task" />
      <MemberSignature Language="F#" Value="static member PurgeAsync : Microsoft.WindowsAzure.MobileServices.Sync.IMobileServiceSyncTable * string -&gt; System.Threading.Tasks.Task" Usage="Microsoft.WindowsAzure.MobileServices.MobileServiceSyncTableExtensions.PurgeAsync (table, query)" />
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
        <Parameter Name="table" Type="Microsoft.WindowsAzure.MobileServices.Sync.IMobileServiceSyncTable" RefType="this" />
        <Parameter Name="query" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="table">Die Instanz der Tabelle auszuführende löschen auf.</param>
        <param name="query">Eine OData-Abfrage, die bestimmt, welche Elemente löschen.</param>
        <summary>
            Löscht alle Elemente in der lokalen Tabelle, die der Abfrage entsprechen.
            </summary>
        <returns>Eine Aufgabe, die beim Abschluss löschen Vorgang wurde beendet.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PurgeAsync&lt;T,U&gt;">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task PurgeAsync&lt;T,U&gt; (this Microsoft.WindowsAzure.MobileServices.Sync.IMobileServiceSyncTable&lt;T&gt; table, Microsoft.WindowsAzure.MobileServices.IMobileServiceTableQuery&lt;U&gt; query);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task PurgeAsync&lt;T, U&gt;(class Microsoft.WindowsAzure.MobileServices.Sync.IMobileServiceSyncTable`1&lt;!!T&gt; table, class Microsoft.WindowsAzure.MobileServices.IMobileServiceTableQuery`1&lt;!!U&gt; query) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.MobileServices.MobileServiceSyncTableExtensions.PurgeAsync``2(Microsoft.WindowsAzure.MobileServices.Sync.IMobileServiceSyncTable{``0},Microsoft.WindowsAzure.MobileServices.IMobileServiceTableQuery{``1})" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function PurgeAsync(Of T, U) (table As IMobileServiceSyncTable(Of T), query As IMobileServiceTableQuery(Of U)) As Task" />
      <MemberSignature Language="F#" Value="static member PurgeAsync : Microsoft.WindowsAzure.MobileServices.Sync.IMobileServiceSyncTable&lt;'T&gt; * Microsoft.WindowsAzure.MobileServices.IMobileServiceTableQuery&lt;'U&gt; -&gt; System.Threading.Tasks.Task" Usage="Microsoft.WindowsAzure.MobileServices.MobileServiceSyncTableExtensions.PurgeAsync (table, query)" />
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
        <TypeParameter Name="T" />
        <TypeParameter Name="U" />
      </TypeParameters>
      <Parameters>
        <Parameter Name="table" Type="Microsoft.WindowsAzure.MobileServices.Sync.IMobileServiceSyncTable&lt;T&gt;" RefType="this" />
        <Parameter Name="query" Type="Microsoft.WindowsAzure.MobileServices.IMobileServiceTableQuery&lt;U&gt;" />
      </Parameters>
      <Docs>
        <typeparam name="T">To be added.</typeparam>
        <typeparam name="U">To be added.</typeparam>
        <param name="table">Die Instanz der Tabelle auszuführende löschen auf.</param>
        <param name="query">Eine OData-Abfrage, die bestimmt, welche Elemente löschen.</param>
        <summary>
            Löscht alle Elemente in der lokalen Tabelle, die der Abfrage entsprechen.
            </summary>
        <returns>Eine Aufgabe, die beim Abschluss löschen Vorgang wurde beendet.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>