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
            <span data-ttu-id="710c5-101">Stellt Vorgänge für lokale Tabelle bereit.</span><span class="sxs-lookup"><span data-stu-id="710c5-101">Provides operations on local table.</span></span>
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
            <span data-ttu-id="710c5-102">Die Instanz, aus der Tabelle löschen.</span><span class="sxs-lookup"><span data-stu-id="710c5-102">The instance to delete from the table.</span></span>
            </param>
        <summary>
            <span data-ttu-id="710c5-103">Löscht eine <paramref name="instance" /> aus der Tabelle.</span><span class="sxs-lookup"><span data-stu-id="710c5-103">Deletes an <paramref name="instance" /> from the table.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="710c5-104">Eine Aufgabe, die abgeschlossen wird, wenn der Löschvorgang abgeschlossen ist.</span><span class="sxs-lookup"><span data-stu-id="710c5-104">A task that will complete when the delete finishes.</span></span>
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
            <span data-ttu-id="710c5-105">Die Instanz, in die Tabelle einzufügen.</span><span class="sxs-lookup"><span data-stu-id="710c5-105">The instance to insert into the table.</span></span>
            </param>
        <summary>
            <span data-ttu-id="710c5-106">Fügt eine <paramref name="instance" /> in die Tabelle.</span><span class="sxs-lookup"><span data-stu-id="710c5-106">Inserts an <paramref name="instance" /> into the table.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="710c5-107">Eine Aufgabe, die abgeschlossen wird, wenn der Einfügevorgang abgeschlossen ist.</span><span class="sxs-lookup"><span data-stu-id="710c5-107">A task that will complete when the insert finishes.</span></span>
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
            <span data-ttu-id="710c5-108">Die Id des zu suchenden Instanz.</span><span class="sxs-lookup"><span data-stu-id="710c5-108">The id of the instance to lookup.</span></span>
            </param>
        <summary>
            <span data-ttu-id="710c5-109">Führt eine Suche für eine Tabelle aus.</span><span class="sxs-lookup"><span data-stu-id="710c5-109">Executes a lookup against a table.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="710c5-110">Eine Aufgabe, die mit einem Ergebnis zurückgegeben wird, wenn die Suche abgeschlossen ist.</span><span class="sxs-lookup"><span data-stu-id="710c5-110">A task that will return with a result when the lookup finishes.</span></span>
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
            <span data-ttu-id="710c5-111">Ruft einen Verweis auf die <see cref="P:Microsoft.WindowsAzure.MobileServices.Sync.IMobileServiceSyncTable.MobileServiceClient" /> dieser Tabelle zugeordnet.</span><span class="sxs-lookup"><span data-stu-id="710c5-111">Gets a reference to the <see cref="P:Microsoft.WindowsAzure.MobileServices.Sync.IMobileServiceSyncTable.MobileServiceClient" /> associated with this table.</span></span>
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
            <span data-ttu-id="710c5-112">Eine Zeichenfolge, die diese Abfrage bezeichnet und dient zum Nachverfolgen der Synchronisierungsstatus des eindeutig.</span><span class="sxs-lookup"><span data-stu-id="710c5-112">A string that uniquely identifies this query and is used to keep track of its sync state.</span></span> <span data-ttu-id="710c5-113">Angabe dieses Parameters kann inkrementelle Synchronisierung an der gleiche Schlüssel erneut verwendet wird.</span><span class="sxs-lookup"><span data-stu-id="710c5-113">Supplying this parameter enables incremental sync whenever the same key is used again.</span></span>
            </param>
        <param name="query">
            <span data-ttu-id="710c5-114">Eine OData-Abfrage, die bestimmt, welche Elemente aus der Remotetabelle abrufen.</span><span class="sxs-lookup"><span data-stu-id="710c5-114">An OData query that determines which items to pull from the remote table.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="710c5-115">Ein Wörterbuch mit benutzerdefinierten Parametern und Werten, die im Anforderungs-URI-Abfragezeichenfolge enthalten.</span><span class="sxs-lookup"><span data-stu-id="710c5-115">A dictionary of user-defined parameters and values to include in the request URI query string.</span></span>
            </param>
        <param name="pushOtherTables">
            <span data-ttu-id="710c5-116">Drücken Sie andere Tabellen, wenn diese Tabelle geändert wurde.</span><span class="sxs-lookup"><span data-stu-id="710c5-116">Push other tables if this table is dirty.</span></span>
            </param>
        <param name="cancellationToken"><span data-ttu-id="710c5-117">Die <see cref="T:System.Threading.CancellationToken" /> Token beobachten</span><span class="sxs-lookup"><span data-stu-id="710c5-117">The <see cref="T:System.Threading.CancellationToken" /> token to observe</span></span>
            </param>
        <param name="pullOptions">
            <span data-ttu-id="710c5-118">PullOptions, die bestimmen, wie Daten aus der Remotetabelle abrufen</span><span class="sxs-lookup"><span data-stu-id="710c5-118">PullOptions that determine how to pull data from the remote table</span></span>
            </param>
        <summary>
            <span data-ttu-id="710c5-119">Ruft alle Elemente, die mit die angegebene Abfrage aus der zugeordneten Remotetabelle übereinstimmen.</span><span class="sxs-lookup"><span data-stu-id="710c5-119">Pulls all items that match the given query from the associated remote table.</span></span> <span data-ttu-id="710c5-120">Unterstützt inkrementelle Synchronisierung.</span><span class="sxs-lookup"><span data-stu-id="710c5-120">Supports incremental sync.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="710c5-121">Eine Aufgabe, die abgeschlossen wird, wenn der Pullvorgang abgeschlossen ist.</span><span class="sxs-lookup"><span data-stu-id="710c5-121">A task that completes when pull operation has finished.</span></span>
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
            <span data-ttu-id="710c5-122">Eine Zeichenfolge, die diese Abfrage bezeichnet und dient zum Nachverfolgen der Synchronisierungsstatus des eindeutig.</span><span class="sxs-lookup"><span data-stu-id="710c5-122">A string that uniquely identifies this query and is used to keep track of its sync state.</span></span> <span data-ttu-id="710c5-123">Dieser Parameter angeben, setzt den inkrementelle Synchronisierung-Zustand für die Abfrage.</span><span class="sxs-lookup"><span data-stu-id="710c5-123">Supplying this parameter resets the incremental sync state for the query.</span></span>
            </param>
        <param name="query"><span data-ttu-id="710c5-124">Eine OData-Abfrage, die bestimmt, welche Elemente löschen.</span><span class="sxs-lookup"><span data-stu-id="710c5-124">An OData query that determines which items to delete.</span></span></param>
        <param name="force"><span data-ttu-id="710c5-125">Erzwingen Sie Löschvorgang durch das Verwerfen der ausstehenden Vorgänge.</span><span class="sxs-lookup"><span data-stu-id="710c5-125">Force the purge by discarding the pending operations.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="710c5-126">Die <see cref="T:System.Threading.CancellationToken" /> Token beobachten</span><span class="sxs-lookup"><span data-stu-id="710c5-126">The <see cref="T:System.Threading.CancellationToken" /> token to observe</span></span>
            </param>
        <summary>
            <span data-ttu-id="710c5-127">Löscht alle Elemente in der lokalen Tabelle, die der Abfrage entsprechen.</span><span class="sxs-lookup"><span data-stu-id="710c5-127">Deletes all the items in local table that match the query.</span></span>
            </summary>
        <returns><span data-ttu-id="710c5-128">Eine Aufgabe, die beim Abschluss löschen Vorgang wurde beendet.</span><span class="sxs-lookup"><span data-stu-id="710c5-128">A task that completes when purge operation has finished.</span></span></returns>
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
            <span data-ttu-id="710c5-129">Eine auszuführende Abfrage.</span><span class="sxs-lookup"><span data-stu-id="710c5-129">A query to execute.</span></span>
            </param>
        <summary>
            <span data-ttu-id="710c5-130">Führt eine Abfrage für die Tabelle.</span><span class="sxs-lookup"><span data-stu-id="710c5-130">Executes a query against the table.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="710c5-131">Eine Aufgabe, die mit Ergebnissen zurückgegeben wird, wenn die Abfrage abgeschlossen ist.</span><span class="sxs-lookup"><span data-stu-id="710c5-131">A task that will return with results when the query finishes.</span></span>
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
            <span data-ttu-id="710c5-132">Die unterstützten OData-Optionen für die Remotetabelle</span><span class="sxs-lookup"><span data-stu-id="710c5-132">The supported odata options on the remote table</span></span>
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
            <span data-ttu-id="710c5-133">Ruft den Namen der Tabelle ab.</span><span class="sxs-lookup"><span data-stu-id="710c5-133">Gets the name of the table.</span></span>
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
            <span data-ttu-id="710c5-134">In der Tabelle zu aktualisierende Instanz.</span><span class="sxs-lookup"><span data-stu-id="710c5-134">The instance to update in the table.</span></span>
            </param>
        <summary>
            <span data-ttu-id="710c5-135">Updates ein <paramref name="instance" /> in der Tabelle.</span><span class="sxs-lookup"><span data-stu-id="710c5-135">Updates an <paramref name="instance" /> in the table.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="710c5-136">Eine Aufgabe, die abgeschlossen wird, wenn der Aktualisierungsvorgang abgeschlossen ist.</span><span class="sxs-lookup"><span data-stu-id="710c5-136">A task that will complete when the update finishes.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>