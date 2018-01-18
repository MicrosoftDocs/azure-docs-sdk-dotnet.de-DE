<Type Name="IDomainManager&lt;TData&gt;" FullName="Microsoft.Azure.Mobile.Server.Tables.IDomainManager&lt;TData&gt;">
  <TypeSignature Language="C#" Value="public interface IDomainManager&lt;TData&gt; where TData : class, ITableData" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IDomainManager`1&lt;class (class Microsoft.Azure.Mobile.Server.Tables.ITableData) TData&gt;" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Mobile.Server.Tables.IDomainManager`1" />
  <TypeSignature Language="VB.NET" Value="Public Interface IDomainManager(Of TData)" />
  <TypeSignature Language="F#" Value="type IDomainManager&lt;'Data (requires 'Data : null and 'Data :&gt; ITableData)&gt; = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Mobile.Server.Tables</AssemblyName>
    <AssemblyVersion>2.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <TypeParameters>
    <TypeParameter Name="TData">
      <Constraints>
        <ParameterAttribute>ReferenceTypeConstraint</ParameterAttribute>
        <InterfaceName>Microsoft.Azure.Mobile.Server.Tables.ITableData</InterfaceName>
      </Constraints>
    </TypeParameter>
  </TypeParameters>
  <Interfaces />
  <Docs>
    <typeparam name="TData"></typeparam>
    <summary>
            <span data-ttu-id="e72ab-101">Stellt eine Abstraktion für den Zugriff auf einen Back-End-Speicher für eine <see cref="T:Microsoft.Azure.Mobile.Server.TableController`1" />.</span><span class="sxs-lookup"><span data-stu-id="e72ab-101">Provides an abstraction for accessing a backend store for a <see cref="T:Microsoft.Azure.Mobile.Server.TableController`1" />.</span></span>
            <span data-ttu-id="e72ab-102">Die Abstraktion kann auf zwei Arten abhängig von den Funktionen des Back-End-Speichers implementiert werden.</span><span class="sxs-lookup"><span data-stu-id="e72ab-102">The abstraction can be implemented in one of two ways depending on the capabilities of the backend store.</span></span> <span data-ttu-id="e72ab-103">Speichert, unterstützen einen <see cref="T:System.Linq.IQueryable`1" />-basierendes Modell kann Implementieren der <see cref="M:Query" /> und <see cref="M:Lookup" /> Methoden während speichert, die nicht unterstützen <see cref="T:System.Linq.IQueryable" /> direkt und wo es ist nicht die bevorzugte Methode für den Zugriff auf die sie implementieren kann die <see cref="M:QueryAsync" /> und <see cref="M:LookupAsync" /> Methoden.</span><span class="sxs-lookup"><span data-stu-id="e72ab-103">Stores that support a <see cref="T:System.Linq.IQueryable`1" />-based model can implement the <see cref="M:Query" /> and <see cref="M:Lookup" /> methods whereas stores that don't support <see cref="T:System.Linq.IQueryable" /> directly or where it is not the preferred way of accessing them can implement the <see cref="M:QueryAsync" /> and <see cref="M:LookupAsync" /> methods.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="DeleteAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;bool&gt; DeleteAsync (string id);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;bool&gt; DeleteAsync(string id) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Mobile.Server.Tables.IDomainManager`1.DeleteAsync(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function DeleteAsync (id As String) As Task(Of Boolean)" />
      <MemberSignature Language="F#" Value="abstract member DeleteAsync : string -&gt; System.Threading.Tasks.Task&lt;bool&gt;" Usage="iDomainManager.DeleteAsync id" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Server.Tables</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="id" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="id"><span data-ttu-id="e72ab-104">Die Id des Elements, das gelöscht werden soll.</span><span class="sxs-lookup"><span data-stu-id="e72ab-104">The id of the item to delete.</span></span></param>
        <summary>
            <span data-ttu-id="e72ab-105">Löscht ein vorhandenes Element</span><span class="sxs-lookup"><span data-stu-id="e72ab-105">Deletes an existing item</span></span>
            </summary>
        <returns>
          <span data-ttu-id="e72ab-106"><c>"true"</c> Wenn Element gelöscht; andernfalls wurde <c>"false"</c></span><span class="sxs-lookup"><span data-stu-id="e72ab-106"><c>true</c> if item was deleted; otherwise <c>false</c></span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="InsertAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;TData&gt; InsertAsync (TData data);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;!TData&gt; InsertAsync(!TData data) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Mobile.Server.Tables.IDomainManager`1.InsertAsync(`0)" />
      <MemberSignature Language="VB.NET" Value="Public Function InsertAsync (data As TData) As Task(Of TData)" />
      <MemberSignature Language="F#" Value="abstract member InsertAsync : 'Data -&gt; System.Threading.Tasks.Task&lt;'Data (requires 'Data : null and 'Data :&gt; Microsoft.Azure.Mobile.Server.Tables.ITableData)&gt;" Usage="iDomainManager.InsertAsync data" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Server.Tables</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;TData&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="data" Type="TData" />
      </Parameters>
      <Docs>
        <param name="data"><span data-ttu-id="e72ab-107">Die Daten eingefügt werden</span><span class="sxs-lookup"><span data-stu-id="e72ab-107">The data to be inserted</span></span></param>
        <summary>
            <span data-ttu-id="e72ab-108">Fügt ein Element in den Back-End-Speicher.</span><span class="sxs-lookup"><span data-stu-id="e72ab-108">Inserts an item to the backend store.</span></span>
            </summary>
        <returns><span data-ttu-id="e72ab-109">Das eingefügte Element.</span><span class="sxs-lookup"><span data-stu-id="e72ab-109">The inserted item.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Lookup">
      <MemberSignature Language="C#" Value="public System.Web.Http.SingleResult&lt;TData&gt; Lookup (string id);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Web.Http.SingleResult`1&lt;!TData&gt; Lookup(string id) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Mobile.Server.Tables.IDomainManager`1.Lookup(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function Lookup (id As String) As SingleResult(Of TData)" />
      <MemberSignature Language="F#" Value="abstract member Lookup : string -&gt; System.Web.Http.SingleResult&lt;'Data (requires 'Data : null and 'Data :&gt; Microsoft.Azure.Mobile.Server.Tables.ITableData)&gt;" Usage="iDomainManager.Lookup id" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Server.Tables</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Web.Http.SingleResult&lt;TData&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="id" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="id"><span data-ttu-id="e72ab-110">Die Id, die das Element darstellt.</span><span class="sxs-lookup"><span data-stu-id="e72ab-110">The id representing the item.</span></span> <span data-ttu-id="e72ab-111">Die Id dient als Teil der <see cref="T:Microsoft.Azure.Mobile.Server.Tables.ITableData" /> und an den Client sichtbar ist.</span><span class="sxs-lookup"><span data-stu-id="e72ab-111">The id is provided as part of the <see cref="T:Microsoft.Azure.Mobile.Server.Tables.ITableData" /> and is visible to the client.</span></span> <span data-ttu-id="e72ab-112">Jedoch kann die jeweiligen Implementierung abhängig von den Back-End-Speicher und das Domänenmodell, die Id in eine andere Form der eindeutige Bezeichner zuordnen.</span><span class="sxs-lookup"><span data-stu-id="e72ab-112">However, depending on the backend store and the domain model, the particular implementation may map the id to some other form of unique identifier.</span></span></param>
        <summary>
            <span data-ttu-id="e72ab-113">Erstellt ein <see cref="T:System.Linq.IQueryable`1" /> gegen ein Store unterstützender auszuführenden <see cref="T:System.Linq.IQueryable`1" /> für ein einzelnes Element nachschlagen.</span><span class="sxs-lookup"><span data-stu-id="e72ab-113">Builds an <see cref="T:System.Linq.IQueryable`1" /> to be executed against a store supporting <see cref="T:System.Linq.IQueryable`1" /> for looking up a single item.</span></span>
            </summary>
        <returns><span data-ttu-id="e72ab-114">Ein <see cref="T:System.Web.Http.SingleResult`1" /> , enthält die <see cref="T:System.Linq.IQueryable`1" /> der wurde noch nicht ausgeführt wurde.</span><span class="sxs-lookup"><span data-stu-id="e72ab-114">A <see cref="T:System.Web.Http.SingleResult`1" /> containing the <see cref="T:System.Linq.IQueryable`1" /> which has not yet been executed.</span></span></returns>
        <remarks>
            <span data-ttu-id="e72ab-115">Siehe auch <see cref="M:Query" /> also die Begleitmethode zum Erstellen einer <see cref="T:System.Linq.IQueryable`1" /> , die mehrere Elemente darstellt.</span><span class="sxs-lookup"><span data-stu-id="e72ab-115">See also <see cref="M:Query" /> which is the companion method for creating an <see cref="T:System.Linq.IQueryable`1" /> representing multiple items.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="LookupAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Web.Http.SingleResult&lt;TData&gt;&gt; LookupAsync (string id);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class System.Web.Http.SingleResult`1&lt;!TData&gt;&gt; LookupAsync(string id) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Mobile.Server.Tables.IDomainManager`1.LookupAsync(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function LookupAsync (id As String) As Task(Of SingleResult(Of TData))" />
      <MemberSignature Language="F#" Value="abstract member LookupAsync : string -&gt; System.Threading.Tasks.Task&lt;System.Web.Http.SingleResult&lt;'Data&gt;&gt;" Usage="iDomainManager.LookupAsync id" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Server.Tables</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Web.Http.SingleResult&lt;TData&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="id" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="id"><span data-ttu-id="e72ab-116">Die Id, die das Element darstellt.</span><span class="sxs-lookup"><span data-stu-id="e72ab-116">The id representing the item.</span></span> <span data-ttu-id="e72ab-117">Die Id dient als Teil der <see cref="T:Microsoft.Azure.Mobile.Server.Tables.ITableData" /> und an den Client sichtbar ist.</span><span class="sxs-lookup"><span data-stu-id="e72ab-117">The id is provided as part of the <see cref="T:Microsoft.Azure.Mobile.Server.Tables.ITableData" /> and is visible to the client.</span></span> <span data-ttu-id="e72ab-118">Jedoch kann die jeweiligen Implementierung abhängig von den Back-End-Speicher und das Domänenmodell, die Id in eine andere Form der eindeutige Bezeichner zuordnen.</span><span class="sxs-lookup"><span data-stu-id="e72ab-118">However, depending on the backend store and the domain model, the particular implementation may map the id to some other form of unique identifier.</span></span></param>
        <summary>
            <span data-ttu-id="e72ab-119">Sucht ein einzelnes Element im Back-End-Speicher.</span><span class="sxs-lookup"><span data-stu-id="e72ab-119">Looks up a single item in the backend store.</span></span> 
            </summary>
        <returns><span data-ttu-id="e72ab-120">Ein <see cref="T:System.Web.Http.SingleResult`1" /> , das dem Ergebnis der Suche.</span><span class="sxs-lookup"><span data-stu-id="e72ab-120">A <see cref="T:System.Web.Http.SingleResult`1" /> representing the result of the lookup.</span></span> <span data-ttu-id="e72ab-121">Ein <see cref="T:System.Web.Http.SingleResult`1" /> stellt eine <see cref="T:System.Linq.IQueryable" /> mit keinem oder einem Entitäten.</span><span class="sxs-lookup"><span data-stu-id="e72ab-121">A <see cref="T:System.Web.Http.SingleResult`1" /> represents an <see cref="T:System.Linq.IQueryable" /> containing zero or one entities.</span></span> <span data-ttu-id="e72ab-122">Dadurch kann er mit einer weiteren Abfrage z. B. gebildet werden <c>$select</c>.</span><span class="sxs-lookup"><span data-stu-id="e72ab-122">This allows it to be composed with further querying such as <c>$select</c>.</span></span></returns>
        <remarks>
            <span data-ttu-id="e72ab-123">Siehe auch <see cref="M:QueryAsync" /> die Begleitmethode zum Ausführen einer Abfrage für mehrere Elemente ist.</span><span class="sxs-lookup"><span data-stu-id="e72ab-123">See also <see cref="M:QueryAsync" /> which is the companion method for executing a query for multiple items.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="Query">
      <MemberSignature Language="C#" Value="public System.Linq.IQueryable&lt;TData&gt; Query ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Linq.IQueryable`1&lt;!TData&gt; Query() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Mobile.Server.Tables.IDomainManager`1.Query" />
      <MemberSignature Language="VB.NET" Value="Public Function Query () As IQueryable(Of TData)" />
      <MemberSignature Language="F#" Value="abstract member Query : unit -&gt; System.Linq.IQueryable&lt;'Data (requires 'Data : null and 'Data :&gt; Microsoft.Azure.Mobile.Server.Tables.ITableData)&gt;" Usage="iDomainManager.Query " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Server.Tables</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Linq.IQueryable&lt;TData&gt;</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="e72ab-124">Erstellt ein <see cref="T:System.Linq.IQueryable`1" /> gegen ein Store unterstützender auszuführenden <see cref="T:System.Linq.IQueryable`1" /> zum Abfragen von Daten.</span><span class="sxs-lookup"><span data-stu-id="e72ab-124">Builds an <see cref="T:System.Linq.IQueryable`1" /> to be executed against a store supporting <see cref="T:System.Linq.IQueryable`1" /> for querying data.</span></span> 
            </summary>
        <returns><span data-ttu-id="e72ab-125">Ein <see cref="T:System.Linq.IQueryable`1" /> der wurde noch nicht ausgeführt wurde.</span><span class="sxs-lookup"><span data-stu-id="e72ab-125">An <see cref="T:System.Linq.IQueryable`1" /> which has not yet been executed.</span></span></returns>
        <remarks>
            <span data-ttu-id="e72ab-126">Siehe auch <see cref="M:Lookup" /> also die Begleitmethode zum Erstellen einer <see cref="T:System.Linq.IQueryable`1" /> , die ein einzelnes Element darstellt.</span><span class="sxs-lookup"><span data-stu-id="e72ab-126">See also <see cref="M:Lookup" /> which is the companion method for creating an <see cref="T:System.Linq.IQueryable`1" /> representing a single item.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="QueryAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;TData&gt;&gt; QueryAsync (System.Web.Http.OData.Query.ODataQueryOptions query);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class System.Collections.Generic.IEnumerable`1&lt;!TData&gt;&gt; QueryAsync(class System.Web.Http.OData.Query.ODataQueryOptions query) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Mobile.Server.Tables.IDomainManager`1.QueryAsync(System.Web.Http.OData.Query.ODataQueryOptions)" />
      <MemberSignature Language="VB.NET" Value="Public Function QueryAsync (query As ODataQueryOptions) As Task(Of IEnumerable(Of TData))" />
      <MemberSignature Language="F#" Value="abstract member QueryAsync : System.Web.Http.OData.Query.ODataQueryOptions -&gt; System.Threading.Tasks.Task&lt;seq&lt;'Data&gt;&gt;" Usage="iDomainManager.QueryAsync query" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Server.Tables</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;TData&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="query" Type="System.Web.Http.OData.Query.ODataQueryOptions" />
      </Parameters>
      <Docs>
        <param name="query"><span data-ttu-id="e72ab-127">Die <see cref="T:System.Web.Http.OData.Query.ODataQueryOptions" /> auszuführende Abfrage.</span><span class="sxs-lookup"><span data-stu-id="e72ab-127">The <see cref="T:System.Web.Http.OData.Query.ODataQueryOptions" /> query to execute.</span></span></param>
        <summary>
            <span data-ttu-id="e72ab-128">Führt die bereitgestellte <paramref name="query" /> für einen Speicher.</span><span class="sxs-lookup"><span data-stu-id="e72ab-128">Executes the provided <paramref name="query" /> against a store.</span></span>
            </summary>
        <returns><span data-ttu-id="e72ab-129">Ein <see cref="T:System.Collections.Generic.IEnumerable`1" /> , das dem Ergebnis der Abfrage.</span><span class="sxs-lookup"><span data-stu-id="e72ab-129">An <see cref="T:System.Collections.Generic.IEnumerable`1" /> representing the result of the query.</span></span></returns>
        <remarks>
            <span data-ttu-id="e72ab-130">Siehe auch <see cref="M:LookupAsync" /> also die Begleitmethode für das Ausführen einer Suche für ein einzelnes Element.</span><span class="sxs-lookup"><span data-stu-id="e72ab-130">See also <see cref="M:LookupAsync" /> which is the companion method for executing a lookup for a single item.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ReplaceAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;TData&gt; ReplaceAsync (string id, TData data);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;!TData&gt; ReplaceAsync(string id, !TData data) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Mobile.Server.Tables.IDomainManager`1.ReplaceAsync(System.String,`0)" />
      <MemberSignature Language="VB.NET" Value="Public Function ReplaceAsync (id As String, data As TData) As Task(Of TData)" />
      <MemberSignature Language="F#" Value="abstract member ReplaceAsync : string * 'Data -&gt; System.Threading.Tasks.Task&lt;'Data (requires 'Data : null and 'Data :&gt; Microsoft.Azure.Mobile.Server.Tables.ITableData)&gt;" Usage="iDomainManager.ReplaceAsync (id, data)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Server.Tables</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;TData&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="id" Type="System.String" />
        <Parameter Name="data" Type="TData" />
      </Parameters>
      <Docs>
        <param name="id"><span data-ttu-id="e72ab-131">Die Id des zu ersetzenden Elements.</span><span class="sxs-lookup"><span data-stu-id="e72ab-131">The id of the item to replace.</span></span></param>
        <param name="data"><span data-ttu-id="e72ab-132">Die Ersetzung</span><span class="sxs-lookup"><span data-stu-id="e72ab-132">The replacement</span></span></param>
        <summary>
            <span data-ttu-id="e72ab-133">Vollständig ersetzt ein vorhandenes Element aus.</span><span class="sxs-lookup"><span data-stu-id="e72ab-133">Completely replaces an existing item.</span></span>
            </summary>
        <returns><span data-ttu-id="e72ab-134">Das ersetzte Element</span><span class="sxs-lookup"><span data-stu-id="e72ab-134">The replaced item</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UpdateAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;TData&gt; UpdateAsync (string id, System.Web.Http.OData.Delta&lt;TData&gt; patch);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;!TData&gt; UpdateAsync(string id, class System.Web.Http.OData.Delta`1&lt;!TData&gt; patch) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Mobile.Server.Tables.IDomainManager`1.UpdateAsync(System.String,System.Web.Http.OData.Delta{`0})" />
      <MemberSignature Language="VB.NET" Value="Public Function UpdateAsync (id As String, patch As Delta(Of TData)) As Task(Of TData)" />
      <MemberSignature Language="F#" Value="abstract member UpdateAsync : string * System.Web.Http.OData.Delta&lt;'Data (requires 'Data : null and 'Data :&gt; Microsoft.Azure.Mobile.Server.Tables.ITableData)&gt; -&gt; System.Threading.Tasks.Task&lt;'Data (requires 'Data : null and 'Data :&gt; Microsoft.Azure.Mobile.Server.Tables.ITableData)&gt;" Usage="iDomainManager.UpdateAsync (id, patch)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Server.Tables</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;TData&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="id" Type="System.String" />
        <Parameter Name="patch" Type="System.Web.Http.OData.Delta&lt;TData&gt;" />
      </Parameters>
      <Docs>
        <param name="id"><span data-ttu-id="e72ab-135">Die Id des Elements, das Patch.</span><span class="sxs-lookup"><span data-stu-id="e72ab-135">The id of the item to patch.</span></span></param>
        <param name="patch"><span data-ttu-id="e72ab-136">Der Patch angewendet werden soll.</span><span class="sxs-lookup"><span data-stu-id="e72ab-136">The patch to apply.</span></span></param>
        <summary>
            <span data-ttu-id="e72ab-137">Aktualisiert ein vorhandenes Element durch Anwenden einer <see cref="T:System.Web.Http.OData.Delta`1" /> Patch darauf.</span><span class="sxs-lookup"><span data-stu-id="e72ab-137">Updates an existing item by applying a <see cref="T:System.Web.Http.OData.Delta`1" /> patch to it.</span></span> <span data-ttu-id="e72ab-138">Die <see cref="T:System.Web.Http.OData.Delta`1" /> Abstraktion der nachverfolgt welche Eigenschaften geändert haben, die Probleme mit Standardwerten und wie vermeidet.</span><span class="sxs-lookup"><span data-stu-id="e72ab-138">The <see cref="T:System.Web.Http.OData.Delta`1" /> abstraction keeps track of which properties have changed which avoids problems with default values and the like.</span></span>
            </summary>
        <returns><span data-ttu-id="e72ab-139">Das Patch-Element.</span><span class="sxs-lookup"><span data-stu-id="e72ab-139">The patched item.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>