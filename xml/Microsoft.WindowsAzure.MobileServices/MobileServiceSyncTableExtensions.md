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
            <span data-ttu-id="5694c-101">Enthält Erweiterungsmethoden [c#]<see cref="T:Microsoft.WindowsAzure.MobileServices.Sync.IMobileServiceSyncTable" /></span><span class="sxs-lookup"><span data-stu-id="5694c-101">Provides extension methods on <see cref="T:Microsoft.WindowsAzure.MobileServices.Sync.IMobileServiceSyncTable" /></span></span></summary>
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
        <param name="table"><span data-ttu-id="5694c-102">Die Instanz der Tabelle zum Ausführen von Pull auf.</span><span class="sxs-lookup"><span data-stu-id="5694c-102">The instance of table to execute pull on.</span></span></param>
        <param name="queryId">
            <span data-ttu-id="5694c-103">Eine Zeichenfolge, die diese Abfrage bezeichnet und dient zum Nachverfolgen der Synchronisierungsstatus des eindeutig.</span><span class="sxs-lookup"><span data-stu-id="5694c-103">A string that uniquely identifies this query and is used to keep track of its sync state.</span></span> <span data-ttu-id="5694c-104">Angabe dieses Parameters kann inkrementelle Synchronisierung an der gleiche Schlüssel erneut verwendet wird.</span><span class="sxs-lookup"><span data-stu-id="5694c-104">Supplying this parameter enables incremental sync whenever the same key is used again.</span></span> <span data-ttu-id="5694c-105">255 Zeichen oder weniger und nur alphanumerische Zeichen, Bindestriche und Unterstriche enthalten.</span><span class="sxs-lookup"><span data-stu-id="5694c-105">Must be 255 characters or less and contain only alphanumeric characters, dash, and underscore.</span></span>
            </param>
        <param name="query">
            <span data-ttu-id="5694c-106">Eine OData-Abfrage, die bestimmt, welche Elemente aus der Remotetabelle abrufen.</span><span class="sxs-lookup"><span data-stu-id="5694c-106">An OData query that determines which items to pull from the remote table.</span></span>
            </param>
        <summary>
            <span data-ttu-id="5694c-107">Ruft alle Elemente, die mit die angegebene Abfrage aus der zugeordneten Remotetabelle übereinstimmen.</span><span class="sxs-lookup"><span data-stu-id="5694c-107">Pulls all items that match the given query from the associated remote table.</span></span> <span data-ttu-id="5694c-108">Unterstützt inkrementelle Synchronisierung.</span><span class="sxs-lookup"><span data-stu-id="5694c-108">Supports incremental sync.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="5694c-109">Eine Aufgabe, die abgeschlossen wird, wenn der Pullvorgang abgeschlossen ist.</span><span class="sxs-lookup"><span data-stu-id="5694c-109">A task that completes when pull operation has finished.</span></span>
            </returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentException">
            <span data-ttu-id="5694c-110">Wird ausgelöst, wenn <paramref name="queryId" />entspricht nicht den regulären Ausdruck <value>[a-zA-Z][a-zA-Z0-9_-]{1,255}</value>.</span><span class="sxs-lookup"><span data-stu-id="5694c-110">Thrown when <paramref name="queryId" />does not match the regular expression <value>[a-zA-Z][a-zA-Z0-9_-]{1,255}</value>.</span></span>
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
        <param name="table"><span data-ttu-id="5694c-111">Die Instanz der Tabelle zum Ausführen von Pull auf.</span><span class="sxs-lookup"><span data-stu-id="5694c-111">The instance of table to execute pull on.</span></span></param>
        <param name="queryId">
            <span data-ttu-id="5694c-112">Eine Zeichenfolge, die diese Abfrage bezeichnet und dient zum Nachverfolgen der Synchronisierungsstatus des eindeutig.</span><span class="sxs-lookup"><span data-stu-id="5694c-112">A string that uniquely identifies this query and is used to keep track of its sync state.</span></span> <span data-ttu-id="5694c-113">Angabe dieses Parameters kann inkrementelle Synchronisierung an der gleiche Schlüssel erneut verwendet wird.</span><span class="sxs-lookup"><span data-stu-id="5694c-113">Supplying this parameter enables incremental sync whenever the same key is used again.</span></span> <span data-ttu-id="5694c-114">255 Zeichen oder weniger und nur alphanumerische Zeichen, Bindestriche und Unterstriche enthalten.</span><span class="sxs-lookup"><span data-stu-id="5694c-114">Must be 255 characters or less and contain only alphanumeric characters, dash, and underscore.</span></span>
            </param>
        <param name="query">
            <span data-ttu-id="5694c-115">Eine OData-Abfrage, die bestimmt, welche Elemente aus der Remotetabelle abrufen.</span><span class="sxs-lookup"><span data-stu-id="5694c-115">An OData query that determines which items to pull from the remote table.</span></span>
            </param>
        <param name="pullOptions">
            <span data-ttu-id="5694c-116">PullOptions, die bestimmen, wie Daten aus der Remotetabelle abrufen</span><span class="sxs-lookup"><span data-stu-id="5694c-116">PullOptions that determine how to pull data from the remote table</span></span>
            </param>
        <summary>
            <span data-ttu-id="5694c-117">Ruft alle Elemente, die mit die angegebene Abfrage aus der zugeordneten Remotetabelle übereinstimmen.</span><span class="sxs-lookup"><span data-stu-id="5694c-117">Pulls all items that match the given query from the associated remote table.</span></span> <span data-ttu-id="5694c-118">Unterstützt inkrementelle Synchronisierung.</span><span class="sxs-lookup"><span data-stu-id="5694c-118">Supports incremental sync.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="5694c-119">Eine Aufgabe, die abgeschlossen wird, wenn der Pullvorgang abgeschlossen ist.</span><span class="sxs-lookup"><span data-stu-id="5694c-119">A task that completes when pull operation has finished.</span></span>
            </returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentException">
            <span data-ttu-id="5694c-120">Wird ausgelöst, wenn <paramref name="queryId" /> entspricht nicht den regulären Ausdruck <value>[a-zA-Z][a-zA-Z0-9_-]{1,255}</value>.</span><span class="sxs-lookup"><span data-stu-id="5694c-120">Thrown when <paramref name="queryId" /> does not match the regular expression <value>[a-zA-Z][a-zA-Z0-9_-]{1,255}</value>.</span></span>
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
        <param name="table"><span data-ttu-id="5694c-121">Die Instanz der Tabelle zum Ausführen von Pull auf.</span><span class="sxs-lookup"><span data-stu-id="5694c-121">The instance of table to execute pull on.</span></span></param>
        <param name="queryId">
            <span data-ttu-id="5694c-122">Eine Zeichenfolge, die diese Abfrage bezeichnet und dient zum Nachverfolgen der Synchronisierungsstatus des eindeutig.</span><span class="sxs-lookup"><span data-stu-id="5694c-122">A string that uniquely identifies this query and is used to keep track of its sync state.</span></span> <span data-ttu-id="5694c-123">Angabe dieses Parameters kann inkrementelle Synchronisierung an der gleiche Schlüssel erneut verwendet wird.</span><span class="sxs-lookup"><span data-stu-id="5694c-123">Supplying this parameter enables incremental sync whenever the same key is used again.</span></span> <span data-ttu-id="5694c-124">255 Zeichen oder weniger und nur alphanumerische Zeichen, Bindestriche und Unterstriche enthalten.</span><span class="sxs-lookup"><span data-stu-id="5694c-124">Must be 255 characters or less and contain only alphanumeric characters, dash, and underscore.</span></span>
            </param>
        <param name="query">
            <span data-ttu-id="5694c-125">Eine OData-Abfrage, die bestimmt, welche Elemente aus der Remotetabelle abrufen.</span><span class="sxs-lookup"><span data-stu-id="5694c-125">An OData query that determines which items to pull from the remote table.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="5694c-126">Ein Wörterbuch mit benutzerdefinierten Parametern und Werten, die im Anforderungs-URI-Abfragezeichenfolge enthalten.</span><span class="sxs-lookup"><span data-stu-id="5694c-126">A dictionary of user-defined parameters and values to include in the request URI query string.</span></span>
            </param>
        <param name="cancellationToken"><span data-ttu-id="5694c-127">Die <see cref="T:System.Threading.CancellationToken" />Token beobachten</span><span class="sxs-lookup"><span data-stu-id="5694c-127">The <see cref="T:System.Threading.CancellationToken" />token to observe</span></span></param>
        <summary>
            <span data-ttu-id="5694c-128">Ruft alle Elemente, die mit die angegebene Abfrage aus der zugeordneten Remotetabelle übereinstimmen.</span><span class="sxs-lookup"><span data-stu-id="5694c-128">Pulls all items that match the given query from the associated remote table.</span></span> <span data-ttu-id="5694c-129">Unterstützt inkrementelle Synchronisierung.</span><span class="sxs-lookup"><span data-stu-id="5694c-129">Supports incremental sync.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="5694c-130">Eine Aufgabe, die abgeschlossen wird, wenn der Pullvorgang abgeschlossen ist.</span><span class="sxs-lookup"><span data-stu-id="5694c-130">A task that completes when pull operation has finished.</span></span>
            </returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentException">
            <span data-ttu-id="5694c-131">Wird ausgelöst, wenn <paramref name="queryId" /> entspricht nicht den regulären Ausdruck <value>[a-zA-Z][a-zA-Z0-9_-]{1,255}</value>.</span><span class="sxs-lookup"><span data-stu-id="5694c-131">Thrown when <paramref name="queryId" /> does not match the regular expression <value>[a-zA-Z][a-zA-Z0-9_-]{1,255}</value>.</span></span>
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
            <span data-ttu-id="5694c-132">Eine Zeichenfolge, die diese Abfrage bezeichnet und dient zum Nachverfolgen der Synchronisierungsstatus des eindeutig.</span><span class="sxs-lookup"><span data-stu-id="5694c-132">A string that uniquely identifies this query and is used to keep track of its sync state.</span></span> <span data-ttu-id="5694c-133">Angabe dieses Parameters kann inkrementelle Synchronisierung an der gleiche Schlüssel erneut verwendet wird.</span><span class="sxs-lookup"><span data-stu-id="5694c-133">Supplying this parameter enables incremental sync whenever the same key is used again.</span></span> <span data-ttu-id="5694c-134">255 Zeichen oder weniger und nur alphanumerische Zeichen, Bindestriche und Unterstriche enthalten</span><span class="sxs-lookup"><span data-stu-id="5694c-134">Must be 255 characters or less and contain only alphanumeric characters, dash, and underscore</span></span>
            </param>
        <param name="query">
            <span data-ttu-id="5694c-135">Eine OData-Abfrage, die bestimmt, welche Elemente aus der Remotetabelle abrufen.</span><span class="sxs-lookup"><span data-stu-id="5694c-135">An OData query that determines which items to pull from the remote table.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="5694c-136">Ein Wörterbuch mit benutzerdefinierten Parametern und Werten, die im Anforderungs-URI-Abfragezeichenfolge enthalten.</span><span class="sxs-lookup"><span data-stu-id="5694c-136">A dictionary of user-defined parameters and values to include in the request URI query string.</span></span>
            </param>
        <param name="pushOtherTables">
            <span data-ttu-id="5694c-137">Drücken Sie andere Tabellen, wenn diese Tabelle geändert wurde.</span><span class="sxs-lookup"><span data-stu-id="5694c-137">Push other tables if this table is dirty.</span></span>
            </param>
        <param name="cancellationToken"><span data-ttu-id="5694c-138">Die <see cref="T:System.Threading.CancellationToken" /> Token beobachten</span><span class="sxs-lookup"><span data-stu-id="5694c-138">The <see cref="T:System.Threading.CancellationToken" /> token to observe</span></span>
            </param>
        <summary>
            <span data-ttu-id="5694c-139">Ruft alle Elemente, die mit die angegebene Abfrage aus der zugeordneten Remotetabelle übereinstimmen.</span><span class="sxs-lookup"><span data-stu-id="5694c-139">Pulls all items that match the given query from the associated remote table.</span></span> <span data-ttu-id="5694c-140">Unterstützt inkrementelle Synchronisierung.</span><span class="sxs-lookup"><span data-stu-id="5694c-140">Supports incremental sync.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="5694c-141">Eine Aufgabe, die abgeschlossen wird, wenn der Pullvorgang abgeschlossen ist.</span><span class="sxs-lookup"><span data-stu-id="5694c-141">A task that completes when pull operation has finished.</span></span>
            </returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentException">
            <span data-ttu-id="5694c-142">Wird ausgelöst, wenn <paramref name="queryId" /> entspricht nicht den regulären Ausdruck <value>[a-zA-Z][a-zA-Z0-9_-]{1,255}</value>.</span><span class="sxs-lookup"><span data-stu-id="5694c-142">Thrown when <paramref name="queryId" /> does not match the regular expression <value>[a-zA-Z][a-zA-Z0-9_-]{1,255}</value>.</span></span>
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
        <param name="table"><span data-ttu-id="5694c-143">Die Instanz der Tabelle zum Ausführen von Pull auf.</span><span class="sxs-lookup"><span data-stu-id="5694c-143">The instance of table to execute pull on.</span></span></param>
        <param name="queryId">
            <span data-ttu-id="5694c-144">Eine Zeichenfolge, die diese Abfrage bezeichnet und dient zum Nachverfolgen der Synchronisierungsstatus des eindeutig.</span><span class="sxs-lookup"><span data-stu-id="5694c-144">A string that uniquely identifies this query and is used to keep track of its sync state.</span></span> <span data-ttu-id="5694c-145">Angabe dieses Parameters kann inkrementelle Synchronisierung an der gleiche Schlüssel erneut verwendet wird.</span><span class="sxs-lookup"><span data-stu-id="5694c-145">Supplying this parameter enables incremental sync whenever the same key is used again.</span></span> <span data-ttu-id="5694c-146">255 Zeichen oder weniger und nur alphanumerische Zeichen, Bindestriche und Unterstriche enthalten.</span><span class="sxs-lookup"><span data-stu-id="5694c-146">Must be 255 characters or less and contain only alphanumeric characters, dash, and underscore.</span></span>
            </param>
        <param name="query">
            <span data-ttu-id="5694c-147">Eine OData-Abfrage, die bestimmt, welche Elemente aus der Remotetabelle abrufen.</span><span class="sxs-lookup"><span data-stu-id="5694c-147">An OData query that determines which items to pull from the remote table.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="5694c-148">Ein Wörterbuch mit benutzerdefinierten Parametern und Werten, die im Anforderungs-URI-Abfragezeichenfolge enthalten.</span><span class="sxs-lookup"><span data-stu-id="5694c-148">A dictionary of user-defined parameters and values to include in the request URI query string.</span></span>
            </param>
        <param name="cancellationToken"><span data-ttu-id="5694c-149">Die <see cref="T:System.Threading.CancellationToken" />Token beobachten</span><span class="sxs-lookup"><span data-stu-id="5694c-149">The <see cref="T:System.Threading.CancellationToken" />token to observe</span></span></param>
        <param name="pullOptions">
            <span data-ttu-id="5694c-150">PullOptions, die bestimmen, wie Daten aus der Remotetabelle abrufen</span><span class="sxs-lookup"><span data-stu-id="5694c-150">PullOptions that determine how to pull data from the remote table</span></span>
            </param>
        <summary>
            <span data-ttu-id="5694c-151">Ruft alle Elemente, die mit die angegebene Abfrage aus der zugeordneten Remotetabelle übereinstimmen.</span><span class="sxs-lookup"><span data-stu-id="5694c-151">Pulls all items that match the given query from the associated remote table.</span></span> <span data-ttu-id="5694c-152">Unterstützt inkrementelle Synchronisierung.</span><span class="sxs-lookup"><span data-stu-id="5694c-152">Supports incremental sync.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="5694c-153">Eine Aufgabe, die abgeschlossen wird, wenn der Pullvorgang abgeschlossen ist.</span><span class="sxs-lookup"><span data-stu-id="5694c-153">A task that completes when pull operation has finished.</span></span>
            </returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentException">
            <span data-ttu-id="5694c-154">Wird ausgelöst, wenn <paramref name="queryId" /> entspricht nicht den regulären Ausdruck <value>[a-zA-Z][a-zA-Z0-9_-]{1,255}</value>.</span><span class="sxs-lookup"><span data-stu-id="5694c-154">Thrown when <paramref name="queryId" /> does not match the regular expression <value>[a-zA-Z][a-zA-Z0-9_-]{1,255}</value>.</span></span>
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
        <param name="table"><span data-ttu-id="5694c-155">Die Instanz der Tabelle zum Ausführen von Pull auf.</span><span class="sxs-lookup"><span data-stu-id="5694c-155">The instance of table to execute pull on.</span></span></param>
        <param name="queryId">
            <span data-ttu-id="5694c-156">Eine Zeichenfolge, die diese Abfrage bezeichnet und dient zum Nachverfolgen der Synchronisierungsstatus des eindeutig.</span><span class="sxs-lookup"><span data-stu-id="5694c-156">A string that uniquely identifies this query and is used to keep track of its sync state.</span></span> <span data-ttu-id="5694c-157">Angabe dieses Parameters kann inkrementelle Synchronisierung an der gleiche Schlüssel erneut verwendet wird.</span><span class="sxs-lookup"><span data-stu-id="5694c-157">Supplying this parameter enables incremental sync whenever the same key is used again.</span></span> <span data-ttu-id="5694c-158">255 Zeichen oder weniger und nur alphanumerische Zeichen, Bindestriche und Unterstriche enthalten</span><span class="sxs-lookup"><span data-stu-id="5694c-158">Must be 255 characters or less and contain only alphanumeric characters, dash, and underscore</span></span>
            </param>
        <param name="query">
            <span data-ttu-id="5694c-159">Eine OData-Abfrage, die bestimmt, welche Elemente aus der Remotetabelle abrufen.</span><span class="sxs-lookup"><span data-stu-id="5694c-159">An OData query that determines which items to pull from the remote table.</span></span>
            </param>
        <summary>
            <span data-ttu-id="5694c-160">Ruft alle Elemente, die mit die angegebene Abfrage aus der zugeordneten Remotetabelle übereinstimmen.</span><span class="sxs-lookup"><span data-stu-id="5694c-160">Pulls all items that match the given query from the associated remote table.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="5694c-161">Eine Aufgabe, die abgeschlossen wird, wenn der Pullvorgang abgeschlossen ist.</span><span class="sxs-lookup"><span data-stu-id="5694c-161">A task that completes when pull operation has finished.</span></span>
            </returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentException">
            <span data-ttu-id="5694c-162">Wird ausgelöst, wenn <paramref name="queryId" /> entspricht nicht den regulären Ausdruck <value>[a-zA-Z][a-zA-Z0-9_-]{1,255}</value>.</span><span class="sxs-lookup"><span data-stu-id="5694c-162">Thrown when <paramref name="queryId" /> does not match the regular expression <value>[a-zA-Z][a-zA-Z0-9_-]{1,255}</value>.</span></span>
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
        <param name="table"><span data-ttu-id="5694c-163">Die Instanz der Tabelle zum Ausführen von Pull auf.</span><span class="sxs-lookup"><span data-stu-id="5694c-163">The instance of table to execute pull on.</span></span></param>
        <param name="queryId">
            <span data-ttu-id="5694c-164">Eine Zeichenfolge, die diese Abfrage bezeichnet und dient zum Nachverfolgen der Synchronisierungsstatus des eindeutig.</span><span class="sxs-lookup"><span data-stu-id="5694c-164">A string that uniquely identifies this query and is used to keep track of its sync state.</span></span> <span data-ttu-id="5694c-165">Angabe dieses Parameters kann inkrementelle Synchronisierung an der gleiche Schlüssel erneut verwendet wird.</span><span class="sxs-lookup"><span data-stu-id="5694c-165">Supplying this parameter enables incremental sync whenever the same key is used again.</span></span> <span data-ttu-id="5694c-166">255 Zeichen oder weniger und nur alphanumerische Zeichen, Bindestriche und Unterstriche enthalten</span><span class="sxs-lookup"><span data-stu-id="5694c-166">Must be 255 characters or less and contain only alphanumeric characters, dash, and underscore</span></span>
            </param>
        <param name="query">
            <span data-ttu-id="5694c-167">Eine OData-Abfrage, die bestimmt, welche Elemente aus der Remotetabelle abrufen.</span><span class="sxs-lookup"><span data-stu-id="5694c-167">An OData query that determines which items to pull from the remote table.</span></span>
            </param>
        <param name="pullOptions">
            <span data-ttu-id="5694c-168">PullOptions, die bestimmen, wie Daten aus der Remotetabelle abrufen</span><span class="sxs-lookup"><span data-stu-id="5694c-168">PullOptions that determine how to pull data from the remote table</span></span>
            </param>
        <summary>
            <span data-ttu-id="5694c-169">Ruft alle Elemente, die mit die angegebene Abfrage aus der zugeordneten Remotetabelle übereinstimmen.</span><span class="sxs-lookup"><span data-stu-id="5694c-169">Pulls all items that match the given query from the associated remote table.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="5694c-170">Eine Aufgabe, die abgeschlossen wird, wenn der Pullvorgang abgeschlossen ist.</span><span class="sxs-lookup"><span data-stu-id="5694c-170">A task that completes when pull operation has finished.</span></span>
            </returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentException">
            <span data-ttu-id="5694c-171">Wird ausgelöst, wenn <paramref name="queryId" /> entspricht nicht den regulären Ausdruck <value>[a-zA-Z][a-zA-Z0-9_-]{1,255}</value>.</span><span class="sxs-lookup"><span data-stu-id="5694c-171">Thrown when <paramref name="queryId" /> does not match the regular expression <value>[a-zA-Z][a-zA-Z0-9_-]{1,255}</value>.</span></span>
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
        <param name="table"><span data-ttu-id="5694c-172">Die Instanz der Tabelle zum Ausführen von Pull auf.</span><span class="sxs-lookup"><span data-stu-id="5694c-172">The instance of table to execute pull on.</span></span></param>
        <param name="queryId">
            <span data-ttu-id="5694c-173">Eine Zeichenfolge, die diese Abfrage bezeichnet und dient zum Nachverfolgen der Synchronisierungsstatus des eindeutig.</span><span class="sxs-lookup"><span data-stu-id="5694c-173">A string that uniquely identifies this query and is used to keep track of its sync state.</span></span> <span data-ttu-id="5694c-174">Angabe dieses Parameters kann inkrementelle Synchronisierung an der gleiche Schlüssel erneut verwendet wird.</span><span class="sxs-lookup"><span data-stu-id="5694c-174">Supplying this parameter enables incremental sync whenever the same key is used again.</span></span> <span data-ttu-id="5694c-175">255 Zeichen oder weniger und nur alphanumerische Zeichen, Bindestriche und Unterstriche enthalten</span><span class="sxs-lookup"><span data-stu-id="5694c-175">Must be 255 characters or less and contain only alphanumeric characters, dash, and underscore</span></span>
            </param>
        <param name="query">
            <span data-ttu-id="5694c-176">Eine OData-Abfrage, die bestimmt, welche Elemente aus der Remotetabelle abrufen.</span><span class="sxs-lookup"><span data-stu-id="5694c-176">An OData query that determines which items to pull from the remote table.</span></span>
            </param>
        <param name="cancellationToken"><span data-ttu-id="5694c-177">Die <see cref="T:System.Threading.CancellationToken" /> Token beobachten</span><span class="sxs-lookup"><span data-stu-id="5694c-177">The <see cref="T:System.Threading.CancellationToken" /> token to observe</span></span>
            </param>
        <summary>
            <span data-ttu-id="5694c-178">Ruft alle Elemente, die mit die angegebene Abfrage aus der zugeordneten Remotetabelle übereinstimmen.</span><span class="sxs-lookup"><span data-stu-id="5694c-178">Pulls all items that match the given query from the associated remote table.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="5694c-179">Eine Aufgabe, die abgeschlossen wird, wenn der Pullvorgang abgeschlossen ist.</span><span class="sxs-lookup"><span data-stu-id="5694c-179">A task that completes when pull operation has finished.</span></span>
            </returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentException">
            <span data-ttu-id="5694c-180">Wird ausgelöst, wenn <paramref name="queryId" /> entspricht nicht den regulären Ausdruck <value>[a-zA-Z][a-zA-Z0-9_-]{1,255}</value>.</span><span class="sxs-lookup"><span data-stu-id="5694c-180">Thrown when <paramref name="queryId" /> does not match the regular expression <value>[a-zA-Z][a-zA-Z0-9_-]{1,255}</value>.</span></span>
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
            <span data-ttu-id="5694c-181">Eine Zeichenfolge, die diese Abfrage bezeichnet und dient zum Nachverfolgen der Synchronisierungsstatus des eindeutig.</span><span class="sxs-lookup"><span data-stu-id="5694c-181">A string that uniquely identifies this query and is used to keep track of its sync state.</span></span> <span data-ttu-id="5694c-182">Angabe dieses Parameters kann inkrementelle Synchronisierung an der gleiche Schlüssel erneut verwendet wird.</span><span class="sxs-lookup"><span data-stu-id="5694c-182">Supplying this parameter enables incremental sync whenever the same key is used again.</span></span> <span data-ttu-id="5694c-183">255 Zeichen oder weniger und nur alphanumerische Zeichen, Bindestriche und Unterstriche enthalten</span><span class="sxs-lookup"><span data-stu-id="5694c-183">Must be 255 characters or less and contain only alphanumeric characters, dash, and underscore</span></span>
            </param>
        <param name="query">
            <span data-ttu-id="5694c-184">Eine OData-Abfrage, die bestimmt, welche Elemente aus der Remotetabelle abrufen.</span><span class="sxs-lookup"><span data-stu-id="5694c-184">An OData query that determines which items to pull from the remote table.</span></span>
            </param>
        <param name="pushOtherTables">
            <span data-ttu-id="5694c-185">Push andere Tabellen, wenn diese Tabelle geändert wurde.</span><span class="sxs-lookup"><span data-stu-id="5694c-185">Push other tables if this table is dirty</span></span>
            </param>
        <param name="cancellationToken"><span data-ttu-id="5694c-186">Die <see cref="T:System.Threading.CancellationToken" /> Token beobachten</span><span class="sxs-lookup"><span data-stu-id="5694c-186">The <see cref="T:System.Threading.CancellationToken" /> token to observe</span></span>
            </param>
        <summary>
            <span data-ttu-id="5694c-187">Ruft alle Elemente, die mit die angegebene Abfrage aus der zugeordneten Remotetabelle übereinstimmen.</span><span class="sxs-lookup"><span data-stu-id="5694c-187">Pulls all items that match the given query from the associated remote table.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="5694c-188">Eine Aufgabe, die abgeschlossen wird, wenn der Pullvorgang abgeschlossen ist.</span><span class="sxs-lookup"><span data-stu-id="5694c-188">A task that completes when pull operation has finished.</span></span>
            </returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentException">
            <span data-ttu-id="5694c-189">Wird ausgelöst, wenn <paramref name="queryId" /> entspricht nicht den regulären Ausdruck <value>[a-zA-Z][a-zA-Z0-9_-]{1,255}</value>.</span><span class="sxs-lookup"><span data-stu-id="5694c-189">Thrown when <paramref name="queryId" /> does not match the regular expression <value>[a-zA-Z][a-zA-Z0-9_-]{1,255}</value>.</span></span>
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
        <param name="table"><span data-ttu-id="5694c-190">Die Instanz der Tabelle zum Ausführen von Pull auf.</span><span class="sxs-lookup"><span data-stu-id="5694c-190">The instance of table to execute pull on.</span></span></param>
        <param name="queryId">
            <span data-ttu-id="5694c-191">Eine Zeichenfolge, die diese Abfrage bezeichnet und dient zum Nachverfolgen der Synchronisierungsstatus des eindeutig.</span><span class="sxs-lookup"><span data-stu-id="5694c-191">A string that uniquely identifies this query and is used to keep track of its sync state.</span></span> <span data-ttu-id="5694c-192">Angabe dieses Parameters kann inkrementelle Synchronisierung an der gleiche Schlüssel erneut verwendet wird.</span><span class="sxs-lookup"><span data-stu-id="5694c-192">Supplying this parameter enables incremental sync whenever the same key is used again.</span></span> <span data-ttu-id="5694c-193">255 Zeichen oder weniger und nur alphanumerische Zeichen, Bindestriche und Unterstriche enthalten</span><span class="sxs-lookup"><span data-stu-id="5694c-193">Must be 255 characters or less and contain only alphanumeric characters, dash, and underscore</span></span>
            </param>
        <param name="query">
            <span data-ttu-id="5694c-194">Eine OData-Abfrage, die bestimmt, welche Elemente aus der Remotetabelle abrufen.</span><span class="sxs-lookup"><span data-stu-id="5694c-194">An OData query that determines which items to pull from the remote table.</span></span>
            </param>
        <param name="cancellationToken"><span data-ttu-id="5694c-195">Die <see cref="T:System.Threading.CancellationToken" /> Token beobachten</span><span class="sxs-lookup"><span data-stu-id="5694c-195">The <see cref="T:System.Threading.CancellationToken" /> token to observe</span></span>
            </param>
        <param name="pullOptions">
            <span data-ttu-id="5694c-196">PullOptions, die bestimmen, wie Daten aus der Remotetabelle abrufen</span><span class="sxs-lookup"><span data-stu-id="5694c-196">PullOptions that determine how to pull data from the remote table</span></span>
            </param>
        <summary>
            <span data-ttu-id="5694c-197">Ruft alle Elemente, die mit die angegebene Abfrage aus der zugeordneten Remotetabelle übereinstimmen.</span><span class="sxs-lookup"><span data-stu-id="5694c-197">Pulls all items that match the given query from the associated remote table.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="5694c-198">Eine Aufgabe, die abgeschlossen wird, wenn der Pullvorgang abgeschlossen ist.</span><span class="sxs-lookup"><span data-stu-id="5694c-198">A task that completes when pull operation has finished.</span></span>
            </returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentException">
            <span data-ttu-id="5694c-199">Wird ausgelöst, wenn <paramref name="queryId" /> entspricht nicht den regulären Ausdruck <value>[a-zA-Z][a-zA-Z0-9_-]{1,255}</value>.</span><span class="sxs-lookup"><span data-stu-id="5694c-199">Thrown when <paramref name="queryId" /> does not match the regular expression <value>[a-zA-Z][a-zA-Z0-9_-]{1,255}</value>.</span></span>
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
        <param name="table"><span data-ttu-id="5694c-200">Die Instanz der Tabelle auszuführende löschen auf.</span><span class="sxs-lookup"><span data-stu-id="5694c-200">The instance of table to execute purge on.</span></span></param>
        <summary>
            <span data-ttu-id="5694c-201">Löscht alle Elemente im lokalen Tabelle</span><span class="sxs-lookup"><span data-stu-id="5694c-201">Deletes all the items in local table</span></span>
            </summary>
        <returns><span data-ttu-id="5694c-202">Eine Aufgabe, die beim Abschluss löschen Vorgang wurde beendet.</span><span class="sxs-lookup"><span data-stu-id="5694c-202">A task that completes when purge operation has finished.</span></span></returns>
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
        <param name="table"><span data-ttu-id="5694c-203">Die Instanz der Tabelle auszuführende löschen auf.</span><span class="sxs-lookup"><span data-stu-id="5694c-203">The instance of table to execute purge on.</span></span></param>
        <param name="force"><span data-ttu-id="5694c-204">Erzwingen Sie Löschvorgang durch das Verwerfen der ausstehenden Vorgänge.</span><span class="sxs-lookup"><span data-stu-id="5694c-204">Force the purge by discarding the pending operations.</span></span></param>
        <summary>
            <span data-ttu-id="5694c-205">Löscht alle Elemente im lokalen Tabelle</span><span class="sxs-lookup"><span data-stu-id="5694c-205">Deletes all the items in local table</span></span>
            </summary>
        <returns><span data-ttu-id="5694c-206">Eine Aufgabe, die beim Abschluss löschen Vorgang wurde beendet.</span><span class="sxs-lookup"><span data-stu-id="5694c-206">A task that completes when purge operation has finished.</span></span></returns>
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
        <param name="table"><span data-ttu-id="5694c-207">Die Instanz der Tabelle auszuführende löschen auf.</span><span class="sxs-lookup"><span data-stu-id="5694c-207">The instance of table to execute purge on.</span></span></param>
        <param name="query"><span data-ttu-id="5694c-208">Eine OData-Abfrage, die bestimmt, welche Elemente löschen.</span><span class="sxs-lookup"><span data-stu-id="5694c-208">An OData query that determines which items to delete.</span></span></param>
        <summary>
            <span data-ttu-id="5694c-209">Löscht alle Elemente in der lokalen Tabelle, die der Abfrage entsprechen.</span><span class="sxs-lookup"><span data-stu-id="5694c-209">Deletes all the items in local table that match the query.</span></span>
            </summary>
        <returns><span data-ttu-id="5694c-210">Eine Aufgabe, die beim Abschluss löschen Vorgang wurde beendet.</span><span class="sxs-lookup"><span data-stu-id="5694c-210">A task that completes when purge operation has finished.</span></span></returns>
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
        <param name="table"><span data-ttu-id="5694c-211">Die Instanz der Tabelle auszuführende löschen auf.</span><span class="sxs-lookup"><span data-stu-id="5694c-211">The instance of table to execute purge on.</span></span></param>
        <param name="query"><span data-ttu-id="5694c-212">Eine OData-Abfrage, die bestimmt, welche Elemente löschen.</span><span class="sxs-lookup"><span data-stu-id="5694c-212">An OData query that determines which items to delete.</span></span></param>
        <summary>
            <span data-ttu-id="5694c-213">Löscht alle Elemente in der lokalen Tabelle, die der Abfrage entsprechen.</span><span class="sxs-lookup"><span data-stu-id="5694c-213">Deletes all the items in local table that match the query.</span></span>
            </summary>
        <returns><span data-ttu-id="5694c-214">Eine Aufgabe, die beim Abschluss löschen Vorgang wurde beendet.</span><span class="sxs-lookup"><span data-stu-id="5694c-214">A task that completes when purge operation has finished.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>