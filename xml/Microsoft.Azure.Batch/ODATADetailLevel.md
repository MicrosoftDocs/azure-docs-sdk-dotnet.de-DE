<Type Name="ODATADetailLevel" FullName="Microsoft.Azure.Batch.ODATADetailLevel">
  <TypeSignature Language="C#" Value="public class ODATADetailLevel : Microsoft.Azure.Batch.DetailLevel" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit ODATADetailLevel extends Microsoft.Azure.Batch.DetailLevel" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Batch.ODATADetailLevel" />
  <TypeSignature Language="VB.NET" Value="Public Class ODATADetailLevel&#xA;Inherits DetailLevel" />
  <TypeSignature Language="F#" Value="type ODATADetailLevel = class&#xA;    inherit DetailLevel" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
    <AssemblyVersion>7.1.0.0</AssemblyVersion>
    <AssemblyVersion>8.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.Batch.DetailLevel</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
             <span data-ttu-id="dca2a-101">Steuert die Anzahl der Details aus dem Azure Batch-Dienst beim Auflisten oder Abrufen von Ressourcen, die mithilfe von OData-Abfrageklauseln angefordert.</span><span class="sxs-lookup"><span data-stu-id="dca2a-101">Controls the amount of detail requested from the Azure Batch service when listing or retrieving resources, using OData query clauses.</span></span>
             </summary>
    <remarks>
      <para><span data-ttu-id="dca2a-102">Azure Batch unterstützt OData-Abfragen, die dem Client erlauben, erhalten eine präzisere Steuerung der Leistung von Abfragen, indem Sie steuern, welche Ressourcen in Auflistungsvorgänge zurückgegeben werden (<see cref="P:Microsoft.Azure.Batch.ODATADetailLevel.FilterClause" />), und welche Eigenschaften jeder Ressource zurückgegeben werden, in der Liste "," Get "oder" Aktualisieren Vorgänge (<see cref="P:Microsoft.Azure.Batch.ODATADetailLevel.SelectClause" /> und <see cref="P:Microsoft.Azure.Batch.ODATADetailLevel.ExpandClause" />).</span><span class="sxs-lookup"><span data-stu-id="dca2a-102">Azure Batch supports OData queries, which allow the client to gain finer control over query performance by controlling which resources are returned in List operations (<see cref="P:Microsoft.Azure.Batch.ODATADetailLevel.FilterClause" />), and which properties of each resource are returned in List, Get or Refresh operations (<see cref="P:Microsoft.Azure.Batch.ODATADetailLevel.SelectClause" /> and <see cref="P:Microsoft.Azure.Batch.ODATADetailLevel.ExpandClause" />).</span></span></para>
      <para><span data-ttu-id="dca2a-103">Standardmäßig, wenn Sie nicht bestehen, eine <see cref="T:Microsoft.Azure.Batch.DetailLevel" /> auf eine Liste abrufen oder Aktualisieren der Batch-Client gibt kein Filter (alle Datensätze zurückgegeben werden), keine select-Klausel (alle einfache Eigenschaften werden zurückgegeben) und keine expand-Klausel (zugehörigen Entitäten werden nicht zurückgegeben).</span><span class="sxs-lookup"><span data-stu-id="dca2a-103">By default, if you do not pass a <see cref="T:Microsoft.Azure.Batch.DetailLevel" /> to a List, Get or Refresh operation, the Batch client specifies no filter (all records are returned), no select clause (all simple properties are returned) and no expand clause (associated entities are not returned).</span></span>  <span data-ttu-id="dca2a-104">Daher sind Eigenschaften der zugeordneten Entität standardmäßig Null, anstatt wie andere Eigenschaften aufgefüllt wird.</span><span class="sxs-lookup"><span data-stu-id="dca2a-104">Consequently, by default, associated entity properties are null, rather than being populated like other properties.</span></span>  <span data-ttu-id="dca2a-105">Finden Sie in der Dokumentation der einzelnen um herauszufinden, welche Eigenschaften gelten als zugehörigen Entitäten und erweitert werden, um die aufgefüllt werden müssen.</span><span class="sxs-lookup"><span data-stu-id="dca2a-105">Refer to individual class documentation to find out which properties are considered associated entities and need to be expanded to be populated.</span></span></para>
      <para><span data-ttu-id="dca2a-106">Da die OData-Abfragen direkt an die REST-API übergeben werden, müssen Klausel Zeichenfolgen die JSON-Attributnamen aus der REST-API verwenden, die nicht immer den Eigenschaftennamen .NET entsprechen.</span><span class="sxs-lookup"><span data-stu-id="dca2a-106">Because the OData queries are passed directly to the REST API, clause strings must use the JSON attribute names from the REST API, which are not always the same as .NET property names.</span></span>  <span data-ttu-id="dca2a-107">Beispielsweise .NET <see cref="P:Microsoft.Azure.Batch.CloudPool.VirtualMachineSize">CloudPool.VirtualMachineSize</see> Eigenschaft entspricht dem VmSize-Attribut in der REST-API; deshalb einen Pool Auflisten von Vorgängen nach Größe des virtuellen Computers filtern möchten, müssen Sie VmSize statt VirtualMachineSize schreiben in der Filterzeichenfolge.</span><span class="sxs-lookup"><span data-stu-id="dca2a-107">For example, the .NET <see cref="P:Microsoft.Azure.Batch.CloudPool.VirtualMachineSize">CloudPool.VirtualMachineSize</see> property corresponds to the vmSize attribute in the REST API; therefore, to filter a pool list operations by VM size, you would need to write vmSize rather than VirtualMachineSize in your filter string.</span></span>  <span data-ttu-id="dca2a-108">Finden Sie in der REST-API-Dokumentation so ermitteln Sie den Namen des JSON-Attributs entspricht einer Eigenschaft .NET.</span><span class="sxs-lookup"><span data-stu-id="dca2a-108">Refer to the REST API documentation to find out the JSON attribute name corresponding to a .NET property.</span></span></para>
      <para><span data-ttu-id="dca2a-109">Weitere Informationen zur Verwendung von OData zum effizienten Abfragen der Azure Batch-Dienst finden Sie unter <a href="https://azure.microsoft.com/en-us/documentation/articles/batch-efficient-list-queries/">effiziente Listenabfragen</a> auf MSDN.</span><span class="sxs-lookup"><span data-stu-id="dca2a-109">For additional information about using OData to efficiently query the Azure Batch service, see <a href="https://azure.microsoft.com/en-us/documentation/articles/batch-efficient-list-queries/">Efficient List Queries</a> on MSDN.</span></span></para>
    </remarks>
    <example>
             <span data-ttu-id="dca2a-110">In diesem Beispiel wird gezeigt, wie ein ODataDetailLevel angeben, die nur aktiv listet <see cref="T:Microsoft.Azure.Batch.CloudPool">CloudPools</see>, und ruft nur die <see cref="P:Microsoft.Azure.Batch.CloudPool.Id" />, <see cref="P:Microsoft.Azure.Batch.CloudPool.DisplayName" /> und <see cref="P:Microsoft.Azure.Batch.CloudPool.Statistics" /> für jeden Pool (z. B. für die Anzeige in einem reporting-Benutzer -Schnittstelle).</span><span class="sxs-lookup"><span data-stu-id="dca2a-110">This sample shows how to specify an ODataDetailLevel that lists only active <see cref="T:Microsoft.Azure.Batch.CloudPool">CloudPools</see>, and retrieves only the <see cref="P:Microsoft.Azure.Batch.CloudPool.Id" />, <see cref="P:Microsoft.Azure.Batch.CloudPool.DisplayName" /> and <see cref="P:Microsoft.Azure.Batch.CloudPool.Statistics" /> for each pool (for example, for display in a reporting user interface).</span></span>
             <code>
             var detailLevel = new ODATADetailLevel(
             filterClause: "state eq 'active'",
             selectClause: "id,displayName,stats",
                 expandClause: "stats"
                 );
                 
             var pools = batchClient.PoolOperations.ListPools(detailLevel);
            </code></example>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ODATADetailLevel ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.ODATADetailLevel.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="dca2a-111">Initialisiert eine neue Instanz der dem <see cref="T:Microsoft.Azure.Batch.ODATADetailLevel" /> Klasse mit leeren-Klauseln.</span><span class="sxs-lookup"><span data-stu-id="dca2a-111">Initializes a new instance of the <see cref="T:Microsoft.Azure.Batch.ODATADetailLevel" /> class with empty clauses.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ODATADetailLevel (string filterClause = null, string selectClause = null, string expandClause = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string filterClause, string selectClause, string expandClause) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.ODATADetailLevel.#ctor(System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional filterClause As String = null, Optional selectClause As String = null, Optional expandClause As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Batch.ODATADetailLevel : string * string * string -&gt; Microsoft.Azure.Batch.ODATADetailLevel" Usage="new Microsoft.Azure.Batch.ODATADetailLevel (filterClause, selectClause, expandClause)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="filterClause" Type="System.String" />
        <Parameter Name="selectClause" Type="System.String" />
        <Parameter Name="expandClause" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="filterClause"><span data-ttu-id="dca2a-112">Die Filterklausel.</span><span class="sxs-lookup"><span data-stu-id="dca2a-112">The filter clause.</span></span></param>
        <param name="selectClause"><span data-ttu-id="dca2a-113">Die SELECT-Klausel.</span><span class="sxs-lookup"><span data-stu-id="dca2a-113">The select clause.</span></span></param>
        <param name="expandClause"><span data-ttu-id="dca2a-114">Der Expand-Klausel.</span><span class="sxs-lookup"><span data-stu-id="dca2a-114">The expand clause.</span></span></param>
        <summary>
            <span data-ttu-id="dca2a-115">Initialisiert eine neue Instanz der dem <see cref="T:Microsoft.Azure.Batch.ODATADetailLevel" /> Klasse mit der angegebenen Klausel.</span><span class="sxs-lookup"><span data-stu-id="dca2a-115">Initializes a new instance of the <see cref="T:Microsoft.Azure.Batch.ODATADetailLevel" /> class with the specified clauses.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ExpandClause">
      <MemberSignature Language="C#" Value="public string ExpandClause { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ExpandClause" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.ODATADetailLevel.ExpandClause" />
      <MemberSignature Language="VB.NET" Value="Public Property ExpandClause As String" />
      <MemberSignature Language="F#" Value="member this.ExpandClause : string with get, set" Usage="Microsoft.Azure.Batch.ODATADetailLevel.ExpandClause" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="dca2a-116">Ruft ab oder legt die OData expand-Klausel.</span><span class="sxs-lookup"><span data-stu-id="dca2a-116">Gets or sets the OData expand clause.</span></span> <span data-ttu-id="dca2a-117">Verwendet zum Abrufen der zugehörigen Entitäten der Hauptentität abgerufen wird.</span><span class="sxs-lookup"><span data-stu-id="dca2a-117">Used to retrieve associated entities of the main entity being retrieved.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
          <para><span data-ttu-id="dca2a-118">Dies ist ein optionaler OData $expand-Ausdruckszeichenfolge <a href="http://docs.oasis-open.org/odata/odata/v4.0/errata02/os/complete/part2-url-conventions/odata-v4.0-errata02-os-part2-url-conventions-complete.html#_Toc406398162">(siehe die OData-Spezifikation)</a>.</span><span class="sxs-lookup"><span data-stu-id="dca2a-118">This is an optional OData $expand expression string <a href="http://docs.oasis-open.org/odata/odata/v4.0/errata02/os/complete/part2-url-conventions/odata-v4.0-errata02-os-part2-url-conventions-complete.html#_Toc406398162">(see the OData specification)</a>.</span></span>
            <span data-ttu-id="dca2a-119">Eigenschaften, die zugehörigen Entitäten enthält werden null, wenn in einer ExpandClause eingeschlossen.</span><span class="sxs-lookup"><span data-stu-id="dca2a-119">Properties containing associated entities will be null unless included in an ExpandClause.</span></span>
            <span data-ttu-id="dca2a-120">Insbesondere wenn Sie eine Liste durchführen, abzurufen Sie oder zu aktualisieren Sie und geben Sie eine ExpandClause nicht an, und klicken Sie dann alle Eigenschaften der zugeordneten Entität auf null werden.</span><span class="sxs-lookup"><span data-stu-id="dca2a-120">Specifically, if you perform a List, Get or Refresh and do not specify an ExpandClause, then all associated entity properties will be null.</span></span>  <span data-ttu-id="dca2a-121">Angenommen, Sie führen eine <see cref="M:Microsoft.Azure.Batch.PoolOperations.ListPools(Microsoft.Azure.Batch.DetailLevel,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior})" /> Vorgang ohne eine ExpandClause die <see cref="P:Microsoft.Azure.Batch.CloudPool.Statistics" /> -Eigenschaft wird null sein.</span><span class="sxs-lookup"><span data-stu-id="dca2a-121">For example, if you perform a <see cref="M:Microsoft.Azure.Batch.PoolOperations.ListPools(Microsoft.Azure.Batch.DetailLevel,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior})" /> operation without an ExpandClause then the <see cref="P:Microsoft.Azure.Batch.CloudPool.Statistics" /> property will be null.</span></span>  <span data-ttu-id="dca2a-122">Zum Auffüllen der Eigenschaft Statistics müssen Sie angeben, ein ExpandClause von <c>Stats</c>.  Finden Sie in einzelne Klassendokumentation, um herauszufinden, welche Eigenschaften zugeordneten Entitäten berücksichtigt werden.</span><span class="sxs-lookup"><span data-stu-id="dca2a-122">To populate the Statistics property you must supply an ExpandClause of <c>stats</c>.  Refer to individual class documentation to find out which properties are considered associated entities.</span></span></para>
          <para><span data-ttu-id="dca2a-123">Wenn Sie sowohl eine ExpandClause angeben und eine <see cref="P:Microsoft.Azure.Batch.ODATADetailLevel.SelectClause" />, und klicken Sie dann in der ExpandClause aufgeführten Eigenschaften in der SelectClause wiederholt werden müssen (da nur die in der SelectClause aufgeführten Eigenschaften in der Antwort des Diensts enthalten sind).</span><span class="sxs-lookup"><span data-stu-id="dca2a-123">If you specify both an ExpandClause and a <see cref="P:Microsoft.Azure.Batch.ODATADetailLevel.SelectClause" />, then properties listed in the ExpandClause must be repeated in the SelectClause (because only properties listed in the SelectClause are included in the service response).</span></span>  <span data-ttu-id="dca2a-124">(Diese Anforderung nicht auftreten können, wenn Sie eine SelectClause nicht angeben, bedeutet dies, dass "umfassen alle Eigenschaften in der Antwort.")</span><span class="sxs-lookup"><span data-stu-id="dca2a-124">(This requirement does not arise if you do not specify a SelectClause, because that means 'include all properties in the response.')</span></span></para>
          <para><span data-ttu-id="dca2a-125">Erweiterungen müssen mithilfe von REST-API-Attributnamen, nicht .NET Eigenschaftennamen angegeben werden.</span><span class="sxs-lookup"><span data-stu-id="dca2a-125">Expansions must be specified using REST API attribute names, not .NET property names.</span></span></para>
          <para><span data-ttu-id="dca2a-126">Die Standardeinstellung ist keine erweitern Ausdruck, d. h. keine zugewiesenen Objekte zurückgegeben werden (und die entsprechenden Eigenschaften sind null).</span><span class="sxs-lookup"><span data-stu-id="dca2a-126">The default is no expand expression, which means no associated objects are returned (and the corresponding properties are null).</span></span></para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="FilterClause">
      <MemberSignature Language="C#" Value="public string FilterClause { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string FilterClause" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.ODATADetailLevel.FilterClause" />
      <MemberSignature Language="VB.NET" Value="Public Property FilterClause As String" />
      <MemberSignature Language="F#" Value="member this.FilterClause : string with get, set" Usage="Microsoft.Azure.Batch.ODATADetailLevel.FilterClause" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="dca2a-127">Ruft ab oder legt die OData-Filter-Klausel.</span><span class="sxs-lookup"><span data-stu-id="dca2a-127">Gets or sets the OData filter clause.</span></span> <span data-ttu-id="dca2a-128">Verwendet, um ein listenvorgang, um Elemente zu beschränken, die angegebenen Kriterien entsprechen.</span><span class="sxs-lookup"><span data-stu-id="dca2a-128">Used to restrict a list operation to items that match specified criteria.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
          <para><span data-ttu-id="dca2a-129">Dies ist eine optionale OData $filter Ausdruckszeichenfolge <a href="http://docs.oasis-open.org/odata/odata/v4.0/errata02/os/complete/part2-url-conventions/odata-v4.0-errata02-os-part2-url-conventions-complete.html#_Toc406398094">(siehe die OData-Spezifikation)</a>.</span><span class="sxs-lookup"><span data-stu-id="dca2a-129">This is an optional OData $filter expression string <a href="http://docs.oasis-open.org/odata/odata/v4.0/errata02/os/complete/part2-url-conventions/odata-v4.0-errata02-os-part2-url-conventions-complete.html#_Toc406398094">(see the OData specification)</a>.</span></span>
            <span data-ttu-id="dca2a-130">Sie können z. B. Einschränken einer <see cref="M:Microsoft.Azure.Batch.PoolOperations.ListPools(Microsoft.Azure.Batch.DetailLevel,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior})" /> Vorgang nur die aktiven Pools mit dem Ausdruck zurückgeben <c>State Eq 'aktiv'</c>.</span><span class="sxs-lookup"><span data-stu-id="dca2a-130">For example, you can restrict a <see cref="M:Microsoft.Azure.Batch.PoolOperations.ListPools(Microsoft.Azure.Batch.DetailLevel,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior})" /> operation to return only active pools with the expression <c>state eq 'active'</c>.</span></span></para>
          <para><span data-ttu-id="dca2a-131">Verwenden von REST-API-Attributnamen, nicht .NET Eigenschaftennamen müssen Filter angegeben werden.</span><span class="sxs-lookup"><span data-stu-id="dca2a-131">Filters must be specified using REST API attribute names, not .NET property names.</span></span></para>
          <para><span data-ttu-id="dca2a-132">Der Standardwert ist kein Filterausdruck, was bedeutet, dass alle Ressourcen zurückgegeben werden.</span><span class="sxs-lookup"><span data-stu-id="dca2a-132">The default is no filter expression, which means all resources are returned.</span></span></para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="SelectClause">
      <MemberSignature Language="C#" Value="public string SelectClause { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string SelectClause" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.ODATADetailLevel.SelectClause" />
      <MemberSignature Language="VB.NET" Value="Public Property SelectClause As String" />
      <MemberSignature Language="F#" Value="member this.SelectClause : string with get, set" Usage="Microsoft.Azure.Batch.ODATADetailLevel.SelectClause" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="dca2a-133">Ruft ab oder legt die OData-select-Klausel.</span><span class="sxs-lookup"><span data-stu-id="dca2a-133">Gets or sets the OData select clause.</span></span> <span data-ttu-id="dca2a-134">Verwendet, um nur bestimmte Eigenschaften alle Eigenschaften des Objekts abzurufen.</span><span class="sxs-lookup"><span data-stu-id="dca2a-134">Used to retrieve only specific properties instead of all object properties.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
          <para><span data-ttu-id="dca2a-135">Dies ist eine optionale OData $select Ausdruckszeichenfolge <a href="http://docs.oasis-open.org/odata/odata/v4.0/errata02/os/complete/part2-url-conventions/odata-v4.0-errata02-os-part2-url-conventions-complete.html#_Toc406398163">(siehe die OData-Spezifikation)</a>.</span><span class="sxs-lookup"><span data-stu-id="dca2a-135">This is an optional OData $select expression string <a href="http://docs.oasis-open.org/odata/odata/v4.0/errata02/os/complete/part2-url-conventions/odata-v4.0-errata02-os-part2-url-conventions-complete.html#_Toc406398163">(see the OData specification)</a>.</span></span>
            <span data-ttu-id="dca2a-136">Wenn Sie eine SelectClause dann bereitstellen <b>nur</b> werden die Eigenschaften aufgeführt, die in dieser Klausel aufgefüllt; andere Eigenschaften verfügen über die Standardwerte (in der Regel null).</span><span class="sxs-lookup"><span data-stu-id="dca2a-136">If you provide a SelectClause, then <b>only</b> the properties listed in that clause are populated; other properties have their default values (typically null).</span></span>  <span data-ttu-id="dca2a-137">Angenommen, Sie führen eine <see cref="M:Microsoft.Azure.Batch.PoolOperations.ListPools(Microsoft.Azure.Batch.DetailLevel,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior})" /> Vorgang mit einem SelectClause von <c>-Id, DisplayName</c>, klicken Sie dann jede <see cref="T:Microsoft.Azure.Batch.CloudPool" /> müssen die <see cref="P:Microsoft.Azure.Batch.CloudPool.Id" /> und <see cref="P:Microsoft.Azure.Batch.CloudPool.DisplayName" /> Eigenschaften aufgefüllt, jedoch andere Eigenschaften wie z. B. <see cref="P:Microsoft.Azure.Batch.CloudPool.State" /> nicht abgerufen werden soll, und aus diesem Grund müssen die Standardwerte (in der Regel null).</span><span class="sxs-lookup"><span data-stu-id="dca2a-137">For example, if you perform a <see cref="M:Microsoft.Azure.Batch.PoolOperations.ListPools(Microsoft.Azure.Batch.DetailLevel,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior})" /> operation with a SelectClause of <c>id,displayName</c>, then each <see cref="T:Microsoft.Azure.Batch.CloudPool" /> will have its <see cref="P:Microsoft.Azure.Batch.CloudPool.Id" /> and <see cref="P:Microsoft.Azure.Batch.CloudPool.DisplayName" /> properties populated, but other properties such as <see cref="P:Microsoft.Azure.Batch.CloudPool.State" /> will not be retrieved and therefore will have their default values (typically null).</span></span></para>
          <para><span data-ttu-id="dca2a-138">Wenn bei eine Entität (über eine Liste abrufen oder aktualisieren) abgerufen wurde, identifizieren angegebene eine SelectClause, die nicht die Eigenschaft bzw. Eigenschaften eindeutig, enthält das Objekt (normalerweise die Id-Eigenschaft, aber für <see cref="T:Microsoft.Azure.Batch.Certificate" /> den Fingerabdruck und ThumbprintAlgorithm Eigenschaften, und klicken Sie dann auf alle Methoden, die Zugriff auf die Batch-Dienst zum Abrufen von Daten oder Vorgänge ausführen, schlägt fehl.</span><span class="sxs-lookup"><span data-stu-id="dca2a-138">If, when an entity was retrieved (via a List, Get or Refresh), you specifed a SelectClause which did not include the property or properties that uniquely identify the object (usually the Id property, but for <see cref="T:Microsoft.Azure.Batch.Certificate" /> the Thumbprint and ThumbprintAlgorithm properties, then any methods that access the Batch service to retrieve data or perform operations will fail.</span></span>
            <span data-ttu-id="dca2a-139">Dazu gehören die meisten Methoden für das Objekt, einschließlich <see cref="M:Microsoft.Azure.Batch.IRefreshable.Refresh(Microsoft.Azure.Batch.DetailLevel,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior})" /> und <see cref="M:Microsoft.Azure.Batch.IRefreshable.RefreshAsync(Microsoft.Azure.Batch.DetailLevel,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior},System.Threading.CancellationToken)" />.</span><span class="sxs-lookup"><span data-stu-id="dca2a-139">This includes most methods on the object, including <see cref="M:Microsoft.Azure.Batch.IRefreshable.Refresh(Microsoft.Azure.Batch.DetailLevel,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior})" /> and <see cref="M:Microsoft.Azure.Batch.IRefreshable.RefreshAsync(Microsoft.Azure.Batch.DetailLevel,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior},System.Threading.CancellationToken)" />.</span></span>
            <span data-ttu-id="dca2a-140">Sie können Eigenschaften weiterhin zugegriffen werden (obwohl nur in der SelectClause enthaltenen Eigenschaften aufgefüllt werden).</span><span class="sxs-lookup"><span data-stu-id="dca2a-140">You can still access properties (though only properties included in the SelectClause will be populated).</span></span></para>
          <para><span data-ttu-id="dca2a-141">Verwenden von REST-API-Attributnamen, die Eigenschaftennamen nicht .NET müssen die Auswahl angegeben werden.</span><span class="sxs-lookup"><span data-stu-id="dca2a-141">Selections must be specified using REST API attribute names, not .NET property names.</span></span></para>
          <para><span data-ttu-id="dca2a-142">Der Standardwert ist keine select-Ausdruck, was bedeutet, dass alle Eigenschaften zurückgegeben werden.</span><span class="sxs-lookup"><span data-stu-id="dca2a-142">The default is no select expression, which means all properties are returned.</span></span></para>
        </remarks>
      </Docs>
    </Member>
  </Members>
</Type>