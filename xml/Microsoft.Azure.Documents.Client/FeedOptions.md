<Type Name="FeedOptions" FullName="Microsoft.Azure.Documents.Client.FeedOptions">
  <TypeSignature Language="C#" Value="public sealed class FeedOptions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit FeedOptions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Documents.Client.FeedOptions" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class FeedOptions" />
  <TypeSignature Language="F#" Value="type FeedOptions = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.DocumentDB.Core</AssemblyName>
    <AssemblyVersion>1.6.0.0</AssemblyVersion>
    <AssemblyVersion>1.7.0.0</AssemblyVersion>
    <AssemblyVersion>1.7.1.0</AssemblyVersion>
  </AssemblyInfo>
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Documents.Client</AssemblyName>
    <AssemblyVersion>1.18.0.0</AssemblyVersion>
    <AssemblyVersion>1.19.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="a6255-101">Gibt die Optionen, die feed-Methoden (enumerationsvorgängen) im Azure-Cosmos-DB-Dienst zugeordnet.</span><span class="sxs-lookup"><span data-stu-id="a6255-101">Specifies the options associated with feed methods (enumeration operations) in the Azure Cosmos DB service.</span></span>
            </summary>
    <remarks>
            <span data-ttu-id="a6255-102">Zum Verwalten von Abfrage- und ReadFeed Ausführung verwendet.</span><span class="sxs-lookup"><span data-stu-id="a6255-102">Used to manage query and ReadFeed execution.</span></span> <span data-ttu-id="a6255-103">Können FeedOptions Seitengröße (MaxItemCount) festlegen.</span><span class="sxs-lookup"><span data-stu-id="a6255-103">Can use FeedOptions to set page size (MaxItemCount)</span></span>
            </remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public FeedOptions ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.Client.FeedOptions.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DocumentDB.Core</AssemblyName>
        <AssemblyVersion>1.6.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.1.0</AssemblyVersion>
      </AssemblyInfo>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Documents.Client</AssemblyName>
        <AssemblyVersion>1.18.0.0</AssemblyVersion>
        <AssemblyVersion>1.19.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="a6255-104">Initialisiert eine neue Instanz der dem <see cref="T:Microsoft.Azure.Documents.Client.FeedOptions" /> Klasse für den Azure-Cosmos-DB-Dienst.</span><span class="sxs-lookup"><span data-stu-id="a6255-104">Initializes a new instance of the <see cref="T:Microsoft.Azure.Documents.Client.FeedOptions" /> class for the Azure Cosmos DB service.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DisableRUPerMinuteUsage">
      <MemberSignature Language="C#" Value="public bool DisableRUPerMinuteUsage { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool DisableRUPerMinuteUsage" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Documents.Client.FeedOptions.DisableRUPerMinuteUsage" />
      <MemberSignature Language="VB.NET" Value="Public Property DisableRUPerMinuteUsage As Boolean" />
      <MemberSignature Language="F#" Value="member this.DisableRUPerMinuteUsage : bool with get, set" Usage="Microsoft.Azure.Documents.Client.FeedOptions.DisableRUPerMinuteUsage" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DocumentDB.Core</AssemblyName>
        <AssemblyVersion>1.6.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.1.0</AssemblyVersion>
      </AssemblyInfo>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Documents.Client</AssemblyName>
        <AssemblyVersion>1.18.0.0</AssemblyVersion>
        <AssemblyVersion>1.19.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="a6255-105">Ruft ab oder legt die <see cref="P:Microsoft.Azure.Documents.Client.FeedOptions.DisableRUPerMinuteUsage" /> Option für die aktuelle Abfrage im Azure-Cosmos-DB-Dienst.</span><span class="sxs-lookup"><span data-stu-id="a6255-105">Gets or sets the <see cref="P:Microsoft.Azure.Documents.Client.FeedOptions.DisableRUPerMinuteUsage" /> option for the current query in the Azure Cosmos DB service.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
          <para> 
            <span data-ttu-id="a6255-106">DisableRUPerMinuteUsage dient zum Aktivieren/Deaktivieren von anfordern Einheiten (RUs) / Minute Kapazität für die Abfrage dienen, wenn reguläre RUs/Sekunde bereitgestellt erschöpft ist.</span><span class="sxs-lookup"><span data-stu-id="a6255-106">DisableRUPerMinuteUsage is used to enable/disable Request Units(RUs)/minute capacity to serve the query if regular provisioned RUs/second is exhausted.</span></span>
            </para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="EnableCrossPartitionQuery">
      <MemberSignature Language="C#" Value="public bool EnableCrossPartitionQuery { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool EnableCrossPartitionQuery" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Documents.Client.FeedOptions.EnableCrossPartitionQuery" />
      <MemberSignature Language="VB.NET" Value="Public Property EnableCrossPartitionQuery As Boolean" />
      <MemberSignature Language="F#" Value="member this.EnableCrossPartitionQuery : bool with get, set" Usage="Microsoft.Azure.Documents.Client.FeedOptions.EnableCrossPartitionQuery" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DocumentDB.Core</AssemblyName>
        <AssemblyVersion>1.6.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.1.0</AssemblyVersion>
      </AssemblyInfo>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Documents.Client</AssemblyName>
        <AssemblyVersion>1.18.0.0</AssemblyVersion>
        <AssemblyVersion>1.19.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="a6255-107">Ruft ab oder legt einen Wert, der angibt, ob Benutzer aktiviert sind, um mehr als eine Anforderung zum Ausführen der Abfrage im Azure-Cosmos-DB-Dienst zu senden.</span><span class="sxs-lookup"><span data-stu-id="a6255-107">Gets or sets a value indicating whether users are enabled to send more than one request to execute the query in the Azure Cosmos DB service.</span></span> <span data-ttu-id="a6255-108">Mehr als eine Anforderung ist erforderlich, wenn die Abfrage nicht auf einzelne partitionsschlüsselwert begrenzt ist.</span><span class="sxs-lookup"><span data-stu-id="a6255-108">More than one request is necessary if the query is not scoped to single partition key value.</span></span>
            </summary>
        <value>
            <span data-ttu-id="a6255-109">Option ist "true", wenn die Ausführung von partitionsübergreifenden Abfragen aktiviert ist. andernfalls "false".</span><span class="sxs-lookup"><span data-stu-id="a6255-109">Option is true if cross-partition query execution is enabled; otherwise, false.</span></span>
            </value>
        <remarks>
          <para>
            <span data-ttu-id="a6255-110">Diese Option gilt nur für Abfragen für Dokumente und Dokumentanlagen.</span><span class="sxs-lookup"><span data-stu-id="a6255-110">This option only applies to queries on documents and document attachments.</span></span>
            </para>
        </remarks>
        <example>
          <code language="c#"><![CDATA[
            // Enable cross partition query.
            var queryable = client.CreateDocumentQuery<Book>(
                collectionLink, new FeedOptions { EnableCrossPartitionQuery = true }).Where(b => b.Price > 1000);
            ]]></code>
        </example>
      </Docs>
    </Member>
    <Member MemberName="EnableLowPrecisionOrderBy">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; EnableLowPrecisionOrderBy { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; EnableLowPrecisionOrderBy" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Documents.Client.FeedOptions.EnableLowPrecisionOrderBy" />
      <MemberSignature Language="VB.NET" Value="Public Property EnableLowPrecisionOrderBy As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.EnableLowPrecisionOrderBy : Nullable&lt;bool&gt; with get, set" Usage="Microsoft.Azure.Documents.Client.FeedOptions.EnableLowPrecisionOrderBy" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DocumentDB.Core</AssemblyName>
        <AssemblyVersion>1.6.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.1.0</AssemblyVersion>
      </AssemblyInfo>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Documents.Client</AssemblyName>
        <AssemblyVersion>1.18.0.0</AssemblyVersion>
        <AssemblyVersion>1.19.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="a6255-111">Ermittelt oder definiert die Möglichkeit, niedrige Genauigkeit Reihenfolge von im Azure-Cosmos-DB-Dienst zu aktivieren.</span><span class="sxs-lookup"><span data-stu-id="a6255-111">Gets or sets the option to enable low precision order by in the Azure Cosmos DB service.</span></span>
            </summary>
        <value>
            <span data-ttu-id="a6255-112">Die Option aus, um mit einfacher Genauigkeit mit Order by-aktivieren.</span><span class="sxs-lookup"><span data-stu-id="a6255-112">The option to enable low-precision order by.</span></span>
            </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EnableScanInQuery">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; EnableScanInQuery { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; EnableScanInQuery" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Documents.Client.FeedOptions.EnableScanInQuery" />
      <MemberSignature Language="VB.NET" Value="Public Property EnableScanInQuery As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.EnableScanInQuery : Nullable&lt;bool&gt; with get, set" Usage="Microsoft.Azure.Documents.Client.FeedOptions.EnableScanInQuery" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DocumentDB.Core</AssemblyName>
        <AssemblyVersion>1.6.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.1.0</AssemblyVersion>
      </AssemblyInfo>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Documents.Client</AssemblyName>
        <AssemblyVersion>1.18.0.0</AssemblyVersion>
        <AssemblyVersion>1.19.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="a6255-113">Ruft ab oder legt sie fest, war die Option zum Aktivieren von Scans für die Abfragen als Indizierung zustellbaren konnte nicht, abgewählt auf die angeforderte Pfade in der Azure-Cosmos-DB-Dienst.</span><span class="sxs-lookup"><span data-stu-id="a6255-113">Gets or sets the option to enable scans on the queries which couldn't be served as indexing was opted out on the requested paths in the Azure Cosmos DB service.</span></span>
            </summary>
        <value>
            <span data-ttu-id="a6255-114">Option ist "true", wenn die Überprüfung auf Abfragen aktiviert ist. andernfalls "false".</span><span class="sxs-lookup"><span data-stu-id="a6255-114">Option is true if scan on queries is enabled; otherwise, false.</span></span>
            </value>
        <remarks>To be added.</remarks>
        <example>
          <code language="c#"><![CDATA[
            // Enable scan when Range index is not specified.
            var queryable = client.CreateDocumentQuery<Book>(
                collectionLink, new FeedOptions { EnableScanInQuery = true }).Where(b => b.Price > 1000);
            ]]></code>
        </example>
      </Docs>
    </Member>
    <Member MemberName="MaxBufferedItemCount">
      <MemberSignature Language="C#" Value="public int MaxBufferedItemCount { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 MaxBufferedItemCount" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Documents.Client.FeedOptions.MaxBufferedItemCount" />
      <MemberSignature Language="VB.NET" Value="Public Property MaxBufferedItemCount As Integer" />
      <MemberSignature Language="F#" Value="member this.MaxBufferedItemCount : int with get, set" Usage="Microsoft.Azure.Documents.Client.FeedOptions.MaxBufferedItemCount" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DocumentDB.Core</AssemblyName>
        <AssemblyVersion>1.6.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.1.0</AssemblyVersion>
      </AssemblyInfo>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Documents.Client</AssemblyName>
        <AssemblyVersion>1.18.0.0</AssemblyVersion>
        <AssemblyVersion>1.19.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="a6255-115">Ruft ab oder legt ihn fest, die die maximale Anzahl von Elementen, die möglich Clientseite während gepuffert parallele Ausführung von Abfragen in der Azure-Cosmos-DB-Dienst.</span><span class="sxs-lookup"><span data-stu-id="a6255-115">Gets or sets the maximum number of items that can be buffered client side during parallel query execution in the Azure Cosmos DB service.</span></span> <span data-ttu-id="a6255-116">Ein positive Eigenschaftswert schränkt die Anzahl der gepufferten Elemente, die den festgelegten Wert.</span><span class="sxs-lookup"><span data-stu-id="a6255-116">A positive property value limits the number of buffered items to the set value.</span></span> <span data-ttu-id="a6255-117">Wenn sie auf kleiner als 0 festgelegt ist, entscheidet das System automatisch die Anzahl der Elemente in Puffer.</span><span class="sxs-lookup"><span data-stu-id="a6255-117">If it is set to less than 0, the system automatically decides the number of items to buffer.</span></span>
            </summary>
        <value>
            <span data-ttu-id="a6255-118">Die maximale Anzahl von Elementen, die während der parallelen abfrageausführung gepuffert werden können.</span><span class="sxs-lookup"><span data-stu-id="a6255-118">The maximum count of items that can be buffered during parallel query execution.</span></span>
            </value>
        <remarks>
            <span data-ttu-id="a6255-119">Dies ist nur sinnvolle und kann nicht in bestimmten Fällen von abided sein.</span><span class="sxs-lookup"><span data-stu-id="a6255-119">This is only suggestive and cannot be abided by in certain cases.</span></span>
            </remarks>
        <example>
          <code language="c#"><![CDATA[
            var queryable = client.CreateDocumentQuery<Book>(collectionLink, new FeedOptions { 
            MaximumBufferSize = 10, MaxDegreeOfParallelism = 2 });
            ]]></code>
        </example>
      </Docs>
    </Member>
    <Member MemberName="MaxDegreeOfParallelism">
      <MemberSignature Language="C#" Value="public int MaxDegreeOfParallelism { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 MaxDegreeOfParallelism" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Documents.Client.FeedOptions.MaxDegreeOfParallelism" />
      <MemberSignature Language="VB.NET" Value="Public Property MaxDegreeOfParallelism As Integer" />
      <MemberSignature Language="F#" Value="member this.MaxDegreeOfParallelism : int with get, set" Usage="Microsoft.Azure.Documents.Client.FeedOptions.MaxDegreeOfParallelism" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DocumentDB.Core</AssemblyName>
        <AssemblyVersion>1.6.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.1.0</AssemblyVersion>
      </AssemblyInfo>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Documents.Client</AssemblyName>
        <AssemblyVersion>1.18.0.0</AssemblyVersion>
        <AssemblyVersion>1.19.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="a6255-120">Ruft ab oder legt die Anzahl der gleichzeitigen Vorgänge, die Clientseite werden während der parallelen abfrageausführung im Azure-Cosmos-DB-Dienst ausgeführt.</span><span class="sxs-lookup"><span data-stu-id="a6255-120">Gets or sets the number of concurrent operations run client side during parallel query execution in the Azure Cosmos DB service.</span></span> <span data-ttu-id="a6255-121">Ein positiver Eigenschaftswert beschränkt die Anzahl der gleichzeitigen Vorgänge auf den festgelegten Wert.</span><span class="sxs-lookup"><span data-stu-id="a6255-121">A positive property value limits the number of concurrent operations to the set value.</span></span> <span data-ttu-id="a6255-122">Wenn ein kleinerer Wert als 0 festgelegt wird, wird die Anzahl der gleichzeitig auszuführenden Vorgänge automatisch vom System festgelegt.</span><span class="sxs-lookup"><span data-stu-id="a6255-122">If it is set to less than 0, the system automatically decides the number of concurrent operations to run.</span></span>
            </summary>
        <value>
            <span data-ttu-id="a6255-123">Die maximale Anzahl gleichzeitiger Vorgänge während der parallelen Ausführung.</span><span class="sxs-lookup"><span data-stu-id="a6255-123">The maximum number of concurrent operations during parallel execution.</span></span> <span data-ttu-id="a6255-124">Der Standardwert ist 0.</span><span class="sxs-lookup"><span data-stu-id="a6255-124">Defaults to 0.</span></span>
            </value>
        <remarks>To be added.</remarks>
        <example>
          <code language="c#"><![CDATA[
            var queryable = client.CreateDocumentQuery<Book>(collectionLink, new FeedOptions { 
            MaxDegreeOfParallelism = 5});
            ]]></code>
        </example>
      </Docs>
    </Member>
    <Member MemberName="MaxItemCount">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; MaxItemCount { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; MaxItemCount" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Documents.Client.FeedOptions.MaxItemCount" />
      <MemberSignature Language="VB.NET" Value="Public Property MaxItemCount As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.MaxItemCount : Nullable&lt;int&gt; with get, set" Usage="Microsoft.Azure.Documents.Client.FeedOptions.MaxItemCount" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DocumentDB.Core</AssemblyName>
        <AssemblyVersion>1.6.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.1.0</AssemblyVersion>
      </AssemblyInfo>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Documents.Client</AssemblyName>
        <AssemblyVersion>1.18.0.0</AssemblyVersion>
        <AssemblyVersion>1.19.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="a6255-125">Ruft ab oder legt die maximale Anzahl von Elementen, die in der Enumerationsvorgang im Azure-Cosmos-DB-Dienst zurückgegeben werden.</span><span class="sxs-lookup"><span data-stu-id="a6255-125">Gets or sets the maximum number of items to be returned in the enumeration operation in the Azure Cosmos DB service.</span></span>
            </summary>
        <value>
            <span data-ttu-id="a6255-126">Die maximale Anzahl von Elementen, die in der Enumerationsvorgang zurückgegeben werden.</span><span class="sxs-lookup"><span data-stu-id="a6255-126">The maximum number of items to be returned in the enumeration operation.</span></span>
            </value>
        <remarks>
            <span data-ttu-id="a6255-127">Für die abfragenpaginierung verwendet.</span><span class="sxs-lookup"><span data-stu-id="a6255-127">Used for query pagination.</span></span>
            <span data-ttu-id="a6255-128">"-1" wird für dynamische Seitengröße verwendet.</span><span class="sxs-lookup"><span data-stu-id="a6255-128">'-1' Used for dynamic page size.</span></span>
            </remarks>
        <example>
          <code language="c#"><![CDATA[
            // Fetch query results 10 at a time.
            using (var queryable = client.CreateDocumentQuery<Book>(collectionLink, new FeedOptions { MaxItemCount = 10 }))
            {
                while (queryable.HasResults)
                {
                    FeedResponse<Book> response = await queryable.ExecuteNext<Book>();
                }
            }
            ]]></code>
        </example>
      </Docs>
    </Member>
    <Member MemberName="PartitionKey">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Documents.PartitionKey PartitionKey { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Documents.PartitionKey PartitionKey" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Documents.Client.FeedOptions.PartitionKey" />
      <MemberSignature Language="VB.NET" Value="Public Property PartitionKey As PartitionKey" />
      <MemberSignature Language="F#" Value="member this.PartitionKey : Microsoft.Azure.Documents.PartitionKey with get, set" Usage="Microsoft.Azure.Documents.Client.FeedOptions.PartitionKey" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DocumentDB.Core</AssemblyName>
        <AssemblyVersion>1.6.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.1.0</AssemblyVersion>
      </AssemblyInfo>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Documents.Client</AssemblyName>
        <AssemblyVersion>1.18.0.0</AssemblyVersion>
        <AssemblyVersion>1.19.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Documents.PartitionKey</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="a6255-129">Ruft ab oder legt die <see cref="P:Microsoft.Azure.Documents.Client.FeedOptions.PartitionKey" /> für die aktuelle Anforderung im Azure-Cosmos-DB-Dienst.</span><span class="sxs-lookup"><span data-stu-id="a6255-129">Gets or sets the <see cref="P:Microsoft.Azure.Documents.Client.FeedOptions.PartitionKey" /> for the current request in the Azure Cosmos DB service.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
          <para>
            <span data-ttu-id="a6255-130">Partitionsschlüssel ist erforderlich, wenn Sie Dokumente oder Anlagen in eine partitionierte Sammlung feed gelesen.</span><span class="sxs-lookup"><span data-stu-id="a6255-130">Partition key is required when read documents or attachments feed in a partitioned collection.</span></span> <span data-ttu-id="a6255-131">Insbesondere Partitionsschlüssel ist erforderlich für: <see cref="M:Microsoft.Azure.Documents.Client.DocumentClient.ReadDocumentFeedAsync(System.String,Microsoft.Azure.Documents.Client.FeedOptions)" />, <see cref="M:Microsoft.Azure.Documents.Client.DocumentClient.ReadAttachmentFeedAsync(System.String,Microsoft.Azure.Documents.Client.FeedOptions)" /> und <see cref="M:Microsoft.Azure.Documents.Client.DocumentClient.ReadConflictFeedAsync(System.String,Microsoft.Azure.Documents.Client.FeedOptions)" />.</span><span class="sxs-lookup"><span data-stu-id="a6255-131">Specifically Partition key is required for : <see cref="M:Microsoft.Azure.Documents.Client.DocumentClient.ReadDocumentFeedAsync(System.String,Microsoft.Azure.Documents.Client.FeedOptions)" />, <see cref="M:Microsoft.Azure.Documents.Client.DocumentClient.ReadAttachmentFeedAsync(System.String,Microsoft.Azure.Documents.Client.FeedOptions)" /> and <see cref="M:Microsoft.Azure.Documents.Client.DocumentClient.ReadConflictFeedAsync(System.String,Microsoft.Azure.Documents.Client.FeedOptions)" />.</span></span>  
            <span data-ttu-id="a6255-132">Nur Dokumente zurück in Partitionen, die die <see cref="P:Microsoft.Azure.Documents.Client.FeedOptions.PartitionKey" /> wird im Resultset zurückgegeben.</span><span class="sxs-lookup"><span data-stu-id="a6255-132">Only documents in partitions containing the <see cref="P:Microsoft.Azure.Documents.Client.FeedOptions.PartitionKey" /> is returned in the result.</span></span>
                </para>
        </remarks>
        <altmember cref="T:Microsoft.Azure.Documents.DocumentCollection" />
        <altmember cref="T:Microsoft.Azure.Documents.PartitionKeyDefinition" />
        <example>
            <span data-ttu-id="a6255-133">Das folgende Beispiel zeigt, wie ein Dokument in einem partitionierten Auflistung von feed gelesen <see cref="P:Microsoft.Azure.Documents.Client.FeedOptions.PartitionKey" />.</span><span class="sxs-lookup"><span data-stu-id="a6255-133">The following example shows how to read a document feed in a partitioned collection using <see cref="P:Microsoft.Azure.Documents.Client.FeedOptions.PartitionKey" />.</span></span>
            <span data-ttu-id="a6255-134">Das Beispiel setzt voraus, Erstellen der Auflistung mit einem <see cref="T:Microsoft.Azure.Documents.PartitionKeyDefinition" /> für die Eigenschaft "Country" in allen Dokumenten.</span><span class="sxs-lookup"><span data-stu-id="a6255-134">The example assumes the collection is created with a <see cref="T:Microsoft.Azure.Documents.PartitionKeyDefinition" /> on the 'country' property in all the documents.</span></span>
            <code language="c#"><![CDATA[
            await client.ReadDocumentFeedAsync(
                collection.SelfLink, 
                new RequestOptions { PartitionKey = new PartitionKey("USA") } );
            ]]></code></example>
      </Docs>
    </Member>
    <Member MemberName="PartitionKeyRangeId">
      <MemberSignature Language="C#" Value="public string PartitionKeyRangeId { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string PartitionKeyRangeId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Documents.Client.FeedOptions.PartitionKeyRangeId" />
      <MemberSignature Language="VB.NET" Value="Public Property PartitionKeyRangeId As String" />
      <MemberSignature Language="F#" Value="member this.PartitionKeyRangeId : string with get, set" Usage="Microsoft.Azure.Documents.Client.FeedOptions.PartitionKeyRangeId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DocumentDB.Core</AssemblyName>
        <AssemblyVersion>1.6.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.1.0</AssemblyVersion>
      </AssemblyInfo>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Documents.Client</AssemblyName>
        <AssemblyVersion>1.18.0.0</AssemblyVersion>
        <AssemblyVersion>1.19.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="a6255-135">Ruft ab oder legt den Schlüsselbereich Partitions-Id für die aktuelle Anforderung.</span><span class="sxs-lookup"><span data-stu-id="a6255-135">Gets or sets the partition key range id for the current request.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
          <para>
            <span data-ttu-id="a6255-136">ReadFeed Anforderungen können diese Anforderung auf bestimmten Bereich weiterzuleiten.</span><span class="sxs-lookup"><span data-stu-id="a6255-136">ReadFeed requests can use this to forward request to specific range.</span></span>
            <span data-ttu-id="a6255-137">Hierbei handelt es sich um Hilfsprogramms bei Bulk-Export-Szenarien.</span><span class="sxs-lookup"><span data-stu-id="a6255-137">This is usefull in case of bulk export scenarios.</span></span>
            </para>
        </remarks>
        <altmember cref="T:Microsoft.Azure.Documents.DocumentCollection" />
        <example>
            <span data-ttu-id="a6255-138">Im folgende Beispiel wird gezeigt, wie ein Dokument in eine partitionierte Sammlung von partitionsschlüsselbereichs "20" feed gelesen werden.</span><span class="sxs-lookup"><span data-stu-id="a6255-138">The following example shows how to read a document feed in a partitioned collection from partition key range "20".</span></span>
            <code language="c#"><![CDATA[
            await client.ReadDocumentFeedAsync(
                collection.SelfLink, 
                new RequestOptions { PartitionKeyRangeId = "20" } );
            ]]></code></example>
      </Docs>
    </Member>
    <Member MemberName="PopulateQueryMetrics">
      <MemberSignature Language="C#" Value="public bool PopulateQueryMetrics { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool PopulateQueryMetrics" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Documents.Client.FeedOptions.PopulateQueryMetrics" />
      <MemberSignature Language="VB.NET" Value="Public Property PopulateQueryMetrics As Boolean" />
      <MemberSignature Language="F#" Value="member this.PopulateQueryMetrics : bool with get, set" Usage="Microsoft.Azure.Documents.Client.FeedOptions.PopulateQueryMetrics" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DocumentDB.Core</AssemblyName>
        <AssemblyVersion>1.6.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.1.0</AssemblyVersion>
      </AssemblyInfo>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Documents.Client</AssemblyName>
        <AssemblyVersion>1.18.0.0</AssemblyVersion>
        <AssemblyVersion>1.19.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
             <span data-ttu-id="a6255-139">Ruft ab oder legt die <see cref="P:Microsoft.Azure.Documents.Client.FeedOptions.PopulateQueryMetrics" /> Option für die Abfrage dokumentanforderungen im Azure-Cosmos-DB-Dienst anfordern.</span><span class="sxs-lookup"><span data-stu-id="a6255-139">Gets or sets the <see cref="P:Microsoft.Azure.Documents.Client.FeedOptions.PopulateQueryMetrics" /> request option for document query requests in the Azure Cosmos DB service.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
          <para> 
            <span data-ttu-id="a6255-140">PopulateQueryMetrics dient zum Aktivieren/Deaktivieren von abrufen Metriken, die im Zusammenhang mit der Ausführung von Abfragen auf Dokument abfrageanforderungen.</span><span class="sxs-lookup"><span data-stu-id="a6255-140">PopulateQueryMetrics is used to enable/disable getting metrics relating to query execution on document query requests.</span></span>
            </para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="RequestContinuation">
      <MemberSignature Language="C#" Value="public string RequestContinuation { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string RequestContinuation" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Documents.Client.FeedOptions.RequestContinuation" />
      <MemberSignature Language="VB.NET" Value="Public Property RequestContinuation As String" />
      <MemberSignature Language="F#" Value="member this.RequestContinuation : string with get, set" Usage="Microsoft.Azure.Documents.Client.FeedOptions.RequestContinuation" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DocumentDB.Core</AssemblyName>
        <AssemblyVersion>1.6.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.1.0</AssemblyVersion>
      </AssemblyInfo>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Documents.Client</AssemblyName>
        <AssemblyVersion>1.18.0.0</AssemblyVersion>
        <AssemblyVersion>1.19.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="a6255-141">Ruft ab oder legt das Fortsetzungstoken für die Anforderung im Azure-Cosmos-DB-Dienst.</span><span class="sxs-lookup"><span data-stu-id="a6255-141">Gets or sets the request continuation token in the Azure Cosmos DB service.</span></span>
            </summary>
        <value>
            <span data-ttu-id="a6255-142">Das Fortsetzungstoken für die Anforderung.</span><span class="sxs-lookup"><span data-stu-id="a6255-142">The request continuation token.</span></span>
            </value>
        <remarks>To be added.</remarks>
        <example>
          <code language="c#"><![CDATA[
            // Resume query execution using the continuation from the previous query
            var queryable = client.CreateDocumentQuery<Book>(collectionLink, new FeedOptions { RequestContinuation = prevQuery.ResponseContinuation });
            ]]></code>
        </example>
      </Docs>
    </Member>
    <Member MemberName="ResponseContinuationTokenLimitInKb">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; ResponseContinuationTokenLimitInKb { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; ResponseContinuationTokenLimitInKb" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Documents.Client.FeedOptions.ResponseContinuationTokenLimitInKb" />
      <MemberSignature Language="VB.NET" Value="Public Property ResponseContinuationTokenLimitInKb As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.ResponseContinuationTokenLimitInKb : Nullable&lt;int&gt; with get, set" Usage="Microsoft.Azure.Documents.Client.FeedOptions.ResponseContinuationTokenLimitInKb" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DocumentDB.Core</AssemblyName>
        <AssemblyVersion>1.6.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.1.0</AssemblyVersion>
      </AssemblyInfo>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Documents.Client</AssemblyName>
        <AssemblyVersion>1.18.0.0</AssemblyVersion>
        <AssemblyVersion>1.19.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
             <span data-ttu-id="a6255-143">Ruft ab oder legt die <see cref="P:Microsoft.Azure.Documents.Client.FeedOptions.ResponseContinuationTokenLimitInKb" /> Option für die Abfrage dokumentanforderungen im Azure-Cosmos-DB-Dienst anfordern.</span><span class="sxs-lookup"><span data-stu-id="a6255-143">Gets or sets the <see cref="P:Microsoft.Azure.Documents.Client.FeedOptions.ResponseContinuationTokenLimitInKb" /> request option for document query requests in the Azure Cosmos DB service.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
          <para> 
            <span data-ttu-id="a6255-144">ResponseContinuationTokenLimitInKb wird verwendet, um die Länge des Fortsetzungstokens in der Abfrageantwort zu beschränken.</span><span class="sxs-lookup"><span data-stu-id="a6255-144">ResponseContinuationTokenLimitInKb is used to limit the length of continuation token in the query response.</span></span> <span data-ttu-id="a6255-145">Gültige Werte sind &gt;= 0.</span><span class="sxs-lookup"><span data-stu-id="a6255-145">Valid values are &gt;= 0.</span></span>
            </para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="SessionToken">
      <MemberSignature Language="C#" Value="public string SessionToken { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string SessionToken" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Documents.Client.FeedOptions.SessionToken" />
      <MemberSignature Language="VB.NET" Value="Public Property SessionToken As String" />
      <MemberSignature Language="F#" Value="member this.SessionToken : string with get, set" Usage="Microsoft.Azure.Documents.Client.FeedOptions.SessionToken" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DocumentDB.Core</AssemblyName>
        <AssemblyVersion>1.6.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.1.0</AssemblyVersion>
      </AssemblyInfo>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Documents.Client</AssemblyName>
        <AssemblyVersion>1.18.0.0</AssemblyVersion>
        <AssemblyVersion>1.19.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="a6255-146">Ruft ab oder legt das Sitzungstoken für die Verwendung mit sitzungskonsistenz im Azure-Cosmos-DB-Dienst.</span><span class="sxs-lookup"><span data-stu-id="a6255-146">Gets or sets the session token for use with session consistency in the Azure Cosmos DB service.</span></span>
            </summary>
        <value>
            <span data-ttu-id="a6255-147">Das Sitzungstoken für die Verwendung mit sitzungskonsistenz.</span><span class="sxs-lookup"><span data-stu-id="a6255-147">The session token for use with session consistency.</span></span>
            </value>
        <remarks>
            <span data-ttu-id="a6255-148">Bei Anwendungen nützlich, die einen Lastenausgleich über mehrere Microsoft.Azure.Documents.Client.DocumentClient-Instanzen sind.</span><span class="sxs-lookup"><span data-stu-id="a6255-148">Useful for applications that are load balanced across multiple Microsoft.Azure.Documents.Client.DocumentClient instances.</span></span> <span data-ttu-id="a6255-149">In diesem Fall Roundtrip des Tokens aus Endbenutzer die Anwendung, und dann zurück zum Azure-Cosmos-Datenbank, damit eine Sitzung über Server hinweg beibehalten werden kann.</span><span class="sxs-lookup"><span data-stu-id="a6255-149">In this case, round-trip the token from end user to the application and then back to Azure Cosmos DB so that a session can be preserved across servers.</span></span>
            </remarks>
        <example>
          <code language="c#"><![CDATA[
            var queryable = client.CreateDocumentQuery<Book>(
                collectionLink, new FeedOptions { SessionToken = lastSessionToken });
            ]]></code>
        </example>
      </Docs>
    </Member>
  </Members>
</Type>