<Type Name="DocumentCollection" FullName="Microsoft.Azure.Documents.DocumentCollection">
  <TypeSignature Language="C#" Value="public class DocumentCollection : Microsoft.Azure.Documents.Resource" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit DocumentCollection extends Microsoft.Azure.Documents.Resource" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Documents.DocumentCollection" />
  <TypeSignature Language="VB.NET" Value="Public Class DocumentCollection&#xA;Inherits Resource" />
  <TypeSignature Language="F#" Value="type DocumentCollection = class&#xA;    inherit Resource" />
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
    <BaseTypeName>Microsoft.Azure.Documents.Resource</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="8a8eb-101">Stellt eine Auflistung Dokument im Azure-Cosmos-DB-Dienst.</span><span class="sxs-lookup"><span data-stu-id="8a8eb-101">Represents a document collection in the Azure Cosmos DB service.</span></span> <span data-ttu-id="8a8eb-102">Eine Auflistung ist ein benannter logischer Container für Dokumente.</span><span class="sxs-lookup"><span data-stu-id="8a8eb-102">A collection is a named logical container for documents.</span></span> 
            </summary>
    <remarks>
            <span data-ttu-id="8a8eb-103">Eine Datenbank kann NULL oder mehr benannte Sammlungen enthalten, und jede Sammlung besteht aus null oder mehr JSON-Dokumente.</span><span class="sxs-lookup"><span data-stu-id="8a8eb-103">A database may contain zero or more named collections and each collection consists of zero or more JSON documents.</span></span> <span data-ttu-id="8a8eb-104">Wird das Schema frei, die Dokumente in einer Auflistung müssen nicht die gleiche Struktur oder Felder freigeben.</span><span class="sxs-lookup"><span data-stu-id="8a8eb-104">Being schema-free, the documents in a collection do not need to share the same structure or fields.</span></span> <span data-ttu-id="8a8eb-105">Da Sammlungen Anwendungsressourcen sind, können sie mit dem Hauptschlüssel oder / / Ressourcenschlüssel autorisiert werden.</span><span class="sxs-lookup"><span data-stu-id="8a8eb-105">Since collections are application resources, they can be authorized using either the master key or resource keys.</span></span>
            <span data-ttu-id="8a8eb-106">Verweisen auf <see>http://azure.microsoft.com/documentation/articles/documentdb-resources/#collections</see> für Weitere Informationen zu Sammlungen.</span><span class="sxs-lookup"><span data-stu-id="8a8eb-106">Refer to <see>http://azure.microsoft.com/documentation/articles/documentdb-resources/#collections</see> for more details on collections.</span></span>
            </remarks>
    <altmember cref="T:Microsoft.Azure.Documents.IndexingPolicy" />
    <altmember cref="T:Microsoft.Azure.Documents.PartitionKeyDefinition" />
    <altmember cref="T:Microsoft.Azure.Documents.Document" />
    <altmember cref="T:Microsoft.Azure.Documents.Database" />
    <altmember cref="T:Microsoft.Azure.Documents.Offer" />
    <example>
            <span data-ttu-id="8a8eb-107">Das folgende Beispiel erstellt eine neue partitionierte Sammlung mit 50000 Anforderungseinheit pro Durchsatz.</span><span class="sxs-lookup"><span data-stu-id="8a8eb-107">The example below creates a new partitioned collection with 50000 Request-per-Unit throughput.</span></span>
            <span data-ttu-id="8a8eb-108">Der Partitionsschlüssel ist die erste Ebene "Land"-Eigenschaft in allen Dokumenten in dieser Auflistung.</span><span class="sxs-lookup"><span data-stu-id="8a8eb-108">The partition key is the first level 'country' property in all the documents within this collection.</span></span>
            <code language="c#"><![CDATA[
            DocumentCollection collection = await client.CreateDocumentCollectionAsync(
                databaseLink,
                new DocumentCollection 
                { 
                    Id = "MyCollection",
                    PartitionKey = new PartitionKeyDefinition
                    {
                        Paths = new Collection<string> { "/country" }
                    }
                }, 
                new RequestOptions { OfferThroughput = 50000} ).Result;
            ]]></code></example>
    <example>
            <span data-ttu-id="8a8eb-109">Das folgende Beispiel erstellt eine neue Sammlung mit OfferThroughput bis 10000 festgelegt.</span><span class="sxs-lookup"><span data-stu-id="8a8eb-109">The example below creates a new collection with OfferThroughput set to 10000.</span></span>
            <code language="c#"><![CDATA[
            DocumentCollection collection = await client.CreateDocumentCollectionAsync(
                databaseLink,
                new DocumentCollection { Id = "MyCollection" }, 
                new RequestOptions { OfferThroughput = 10000} ).Result;
            ]]></code></example>
    <example>
            <span data-ttu-id="8a8eb-110">Das folgende Beispiel erstellt eine neue Sammlung mit einem benutzerdefinierten indizierungsrichtlinie.</span><span class="sxs-lookup"><span data-stu-id="8a8eb-110">The example below creates a new collection with a custom indexing policy.</span></span>
            <code language="c#"><![CDATA[
            DocumentCollection collectionSpec = new DocumentCollection { Id ="MyCollection" };
            collectionSpec.IndexingPolicy.Automatic = true;
            collectionSpec.IndexingPolicy.IndexingMode = IndexingMode.Consistent;
            collection = await client.CreateDocumentCollectionAsync(database.SelfLink, collectionSpec);
            ]]></code></example>
    <example>
            <span data-ttu-id="8a8eb-111">Das folgende Beispiel erstellt ein Dokument vom Typ Book innerhalb dieser Auflistung.</span><span class="sxs-lookup"><span data-stu-id="8a8eb-111">The example below creates a document of type Book inside this collection.</span></span>
            <code language="c#"><![CDATA[
            Document doc = await client.CreateDocumentAsync(collection.SelfLink, new Book { Title = "War and Peace" });
            ]]></code></example>
    <example>
            <span data-ttu-id="8a8eb-112">Im Beispiel unten Abfragen für eine Datenbank-Id, die SelfLink abzurufen.</span><span class="sxs-lookup"><span data-stu-id="8a8eb-112">The example below queries for a Database by Id to retrieve the SelfLink.</span></span>
            <code language="c#"><![CDATA[
            using Microsoft.Azure.Documents.Linq;
            DocumentCollection collection = client.CreateDocumentCollectionQuery(databaseLink).Where(c => c.Id == "myColl").AsEnumerable().FirstOrDefault();
            string collectionLink = collection.SelfLink;
            ]]></code></example>
    <example>
            <span data-ttu-id="8a8eb-113">Im folgenden Beispiel wird diese Auflistung gelöscht.</span><span class="sxs-lookup"><span data-stu-id="8a8eb-113">The example below deletes this collection.</span></span>
            <code language="c#"><![CDATA[
            await client.DeleteDocumentCollectionAsync(collection.SelfLink);
            ]]></code></example>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public DocumentCollection ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.DocumentCollection.#ctor" />
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
            <span data-ttu-id="8a8eb-114">Initialisiert eine neue Instanz der dem <see cref="T:Microsoft.Azure.Documents.DocumentCollection" /> Klasse für den Azure-Cosmos-DB-Dienst.</span><span class="sxs-lookup"><span data-stu-id="8a8eb-114">Initializes a new instance of the <see cref="T:Microsoft.Azure.Documents.DocumentCollection" /> class for the Azure Cosmos DB service.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ConflictsLink">
      <MemberSignature Language="C#" Value="public string ConflictsLink { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ConflictsLink" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Documents.DocumentCollection.ConflictsLink" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ConflictsLink As String" />
      <MemberSignature Language="F#" Value="member this.ConflictsLink : string" Usage="Microsoft.Azure.Documents.DocumentCollection.ConflictsLink" />
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
            <span data-ttu-id="8a8eb-115">Ruft ab, der Self-link für Konflikte in einer Auflistung aus dem Azure-Cosmos-DB-Dienst.</span><span class="sxs-lookup"><span data-stu-id="8a8eb-115">Gets the self-link for conflicts in a collection from the Azure Cosmos DB service.</span></span>
            </summary>
        <value>
            <span data-ttu-id="8a8eb-116">Der Self-link für Konflikte in einer Auflistung.</span><span class="sxs-lookup"><span data-stu-id="8a8eb-116">The self-link for conflicts in a collection.</span></span>
            </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DefaultTimeToLive">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; DefaultTimeToLive { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; DefaultTimeToLive" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Documents.DocumentCollection.DefaultTimeToLive" />
      <MemberSignature Language="VB.NET" Value="Public Property DefaultTimeToLive As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.DefaultTimeToLive : Nullable&lt;int&gt; with get, set" Usage="Microsoft.Azure.Documents.DocumentCollection.DefaultTimeToLive" />
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
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(NullValueHandling=Newtonsoft.Json.NullValueHandling.Ignore, PropertyName="defaultTtl")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="8a8eb-117">Ruft die Standardzeit für die Gültigkeitsdauer in Sekunden für die Dokumente in einer Auflistung aus dem Azure-Cosmos-DB-Dienst ab.</span><span class="sxs-lookup"><span data-stu-id="8a8eb-117">Gets the default time to live in seconds for documents in a collection from the Azure Cosmos DB service.</span></span>
            </summary>
        <value>
            <span data-ttu-id="8a8eb-118">Es ist eine optionale Eigenschaft.</span><span class="sxs-lookup"><span data-stu-id="8a8eb-118">It is an optional property.</span></span>
            <span data-ttu-id="8a8eb-119">Ein gültiger Wert muss entweder eine positive ganze Zahl ungleich NULL, "1", oder <c>null</c>.</span><span class="sxs-lookup"><span data-stu-id="8a8eb-119">A valid value must be either a nonzero positive integer, '-1', or <c>null</c>.</span></span>
            <span data-ttu-id="8a8eb-120">Standardmäßig wird die DefaultTimeToLive auf null Bedeutung festgelegt, der die Zeit Gültigkeitsdauer für die Auflistung deaktiviert ist.</span><span class="sxs-lookup"><span data-stu-id="8a8eb-120">By default, DefaultTimeToLive is set to null meaning the time to live is turned off for the collection.</span></span>
            <span data-ttu-id="8a8eb-121">Die Maßeinheit ist Sekunden.</span><span class="sxs-lookup"><span data-stu-id="8a8eb-121">The unit of measurement is seconds.</span></span> <span data-ttu-id="8a8eb-122">Die zulässige Maximalwert ist 2147483647.</span><span class="sxs-lookup"><span data-stu-id="8a8eb-122">The maximum allowed value is 2147483647.</span></span>
            </value>
        <remarks>
          <para>
            <span data-ttu-id="8a8eb-123">Die <see cref="P:Microsoft.Azure.Documents.DocumentCollection.DefaultTimeToLive" /> gelten für alle Dokumente in der Auflistung als Standard Time-to-live-Richtlinie.</span><span class="sxs-lookup"><span data-stu-id="8a8eb-123">The <see cref="P:Microsoft.Azure.Documents.DocumentCollection.DefaultTimeToLive" /> will be applied to all the documents in the collection as the default time-to-live policy.</span></span>
            <span data-ttu-id="8a8eb-124">Das Dokument konnte die Time-to-live Standardrichtlinie überschreiben, indem seine <see cref="P:Microsoft.Azure.Documents.Document.TimeToLive" />.</span><span class="sxs-lookup"><span data-stu-id="8a8eb-124">The individual document could override the default time-to-live policy by setting its <see cref="P:Microsoft.Azure.Documents.Document.TimeToLive" />.</span></span>
            </para>
          <para>
            <span data-ttu-id="8a8eb-125">Wenn die <see cref="P:Microsoft.Azure.Documents.DocumentCollection.DefaultTimeToLive" /> ist <c>null</c>, die Time-to-live werden ausgeschaltet für die Auflistung.</span><span class="sxs-lookup"><span data-stu-id="8a8eb-125">When the <see cref="P:Microsoft.Azure.Documents.DocumentCollection.DefaultTimeToLive" /> is <c>null</c>, the time-to-live will be turned off for the collection.</span></span>
            <span data-ttu-id="8a8eb-126">Dies bedeutet, dass alle Dokumente nicht abläuft.</span><span class="sxs-lookup"><span data-stu-id="8a8eb-126">It means all the documents will never expire.</span></span> <span data-ttu-id="8a8eb-127">Des einzelne Dokuments <see cref="P:Microsoft.Azure.Documents.Document.TimeToLive" /> wird ignoriert.</span><span class="sxs-lookup"><span data-stu-id="8a8eb-127">The individual document's <see cref="P:Microsoft.Azure.Documents.Document.TimeToLive" /> will be disregarded.</span></span>
            </para>
          <para>
            <span data-ttu-id="8a8eb-128">Wenn die <see cref="P:Microsoft.Azure.Documents.DocumentCollection.DefaultTimeToLive" /> ist '1', die Time-to-live werden aktiviert, für die Auflistung.</span><span class="sxs-lookup"><span data-stu-id="8a8eb-128">When the <see cref="P:Microsoft.Azure.Documents.DocumentCollection.DefaultTimeToLive" /> is '-1', the time-to-live will be turned on for the collection.</span></span>
            <span data-ttu-id="8a8eb-129">Standardmäßig abläuft nie alle Dokumente.</span><span class="sxs-lookup"><span data-stu-id="8a8eb-129">By default, all the documents will never expire.</span></span> <span data-ttu-id="8a8eb-130">Das Dokument konnte einen bestimmten Time-to-live-Wert zugewiesen werden, durch Festlegen seiner <see cref="P:Microsoft.Azure.Documents.Document.TimeToLive" />.</span><span class="sxs-lookup"><span data-stu-id="8a8eb-130">The individual document could be given a specific time-to-live value by setting its <see cref="P:Microsoft.Azure.Documents.Document.TimeToLive" />.</span></span> <span data-ttu-id="8a8eb-131">Des Dokuments <see cref="P:Microsoft.Azure.Documents.Document.TimeToLive" /> wird berücksichtigt werden, und die abgelaufenen Dokumente im Hintergrund gelöscht werden.</span><span class="sxs-lookup"><span data-stu-id="8a8eb-131">The document's <see cref="P:Microsoft.Azure.Documents.Document.TimeToLive" /> will be honored, and the expired documents will be deleted in background.</span></span>
            </para>
          <para>
            <span data-ttu-id="8a8eb-132">Wenn die <see cref="P:Microsoft.Azure.Documents.DocumentCollection.DefaultTimeToLive" /> eine positive ganze Zahl ungleich NULL, wird die Time-to-live werden aktiviert, für die Auflistung.</span><span class="sxs-lookup"><span data-stu-id="8a8eb-132">When the <see cref="P:Microsoft.Azure.Documents.DocumentCollection.DefaultTimeToLive" /> is a nonzero positive integer, the time-to-live will be turned on for the collection.</span></span>
            <span data-ttu-id="8a8eb-133">Und ein Standard Gültigkeitsdauer in Sekunden werden auf alle Dokumente angewendet werden.</span><span class="sxs-lookup"><span data-stu-id="8a8eb-133">And a default time-to-live in seconds will be applied to all the documents.</span></span> <span data-ttu-id="8a8eb-134">Ein Dokument abgelaufen sein wird nach dem angegebenen <see cref="P:Microsoft.Azure.Documents.DocumentCollection.DefaultTimeToLive" /> Wert in Sekunden, die seit der letzten Schreibzugriffs.</span><span class="sxs-lookup"><span data-stu-id="8a8eb-134">A document will be expired after the specified <see cref="P:Microsoft.Azure.Documents.DocumentCollection.DefaultTimeToLive" /> value in seconds since its last write time.</span></span>
            <span data-ttu-id="8a8eb-135">Das Dokument konnte die Time-to-live Standardrichtlinie überschreiben, indem seine <see cref="P:Microsoft.Azure.Documents.Document.TimeToLive" />.</span><span class="sxs-lookup"><span data-stu-id="8a8eb-135">The individual document could override the default time-to-live policy by setting its <see cref="P:Microsoft.Azure.Documents.Document.TimeToLive" />.</span></span>
            <span data-ttu-id="8a8eb-136">Finden Sie in der <see cref="P:Microsoft.Azure.Documents.Document.TimeToLive" /> ausführliche Informationen zum Auswerten der endgültigen Time-to-live-Richtlinie eines Dokuments.</span><span class="sxs-lookup"><span data-stu-id="8a8eb-136">Please refer to the <see cref="P:Microsoft.Azure.Documents.Document.TimeToLive" /> for more details about evaluating the final time-to-live policy of a document.</span></span>
            </para>
        </remarks>
        <altmember cref="T:Microsoft.Azure.Documents.Document" />
        <example>
            <span data-ttu-id="8a8eb-137">Das folgende Beispiel deaktiviert Time-to-live, auf eine Auflistung.</span><span class="sxs-lookup"><span data-stu-id="8a8eb-137">The example below disables time-to-live on a collection.</span></span>
            <code language="c#"><![CDATA[
                collection.DefaultTimeToLive = null;
            ]]></code></example>
        <example>
            <span data-ttu-id="8a8eb-138">Das folgende Beispiel aktiviert Time-to-live, auf eine Auflistung.</span><span class="sxs-lookup"><span data-stu-id="8a8eb-138">The example below enables time-to-live on a collection.</span></span> <span data-ttu-id="8a8eb-139">Alle Dokumente sollen standardmäßig nie ablaufen.</span><span class="sxs-lookup"><span data-stu-id="8a8eb-139">By default, all the documents never expire.</span></span>
            <code language="c#"><![CDATA[
                collection.DefaultTimeToLive = -1;
            ]]></code></example>
        <example>
            <span data-ttu-id="8a8eb-140">Das folgende Beispiel aktiviert Time-to-live, auf eine Auflistung.</span><span class="sxs-lookup"><span data-stu-id="8a8eb-140">The example below enables time-to-live on a collection.</span></span> <span data-ttu-id="8a8eb-141">Standardmäßig wird das Dokument nach 1000 Sekunden ablaufen, seit der letzten Schreibzugriffs.</span><span class="sxs-lookup"><span data-stu-id="8a8eb-141">By default, the document will expire after 1000 seconds since its last write time.</span></span>
            <code language="c#"><![CDATA[
            collection.DefaultTimeToLive = 1000;
                ]]></code></example>
      </Docs>
    </Member>
    <Member MemberName="DocumentsLink">
      <MemberSignature Language="C#" Value="public string DocumentsLink { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string DocumentsLink" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Documents.DocumentCollection.DocumentsLink" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property DocumentsLink As String" />
      <MemberSignature Language="F#" Value="member this.DocumentsLink : string" Usage="Microsoft.Azure.Documents.DocumentCollection.DocumentsLink" />
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
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="_docs")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="8a8eb-142">Ruft ab, der Self-link für Dokumente in einer Auflistung aus dem Azure-Cosmos-DB-Dienst.</span><span class="sxs-lookup"><span data-stu-id="8a8eb-142">Gets the self-link for documents in a collection from the Azure Cosmos DB service.</span></span>
            </summary>
        <value>
            <span data-ttu-id="8a8eb-143">Der Self-link für Dokumente in einer Auflistung.</span><span class="sxs-lookup"><span data-stu-id="8a8eb-143">The self-link for documents in a collection.</span></span>
            </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IndexingPolicy">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Documents.IndexingPolicy IndexingPolicy { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Documents.IndexingPolicy IndexingPolicy" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Documents.DocumentCollection.IndexingPolicy" />
      <MemberSignature Language="VB.NET" Value="Public Property IndexingPolicy As IndexingPolicy" />
      <MemberSignature Language="F#" Value="member this.IndexingPolicy : Microsoft.Azure.Documents.IndexingPolicy with get, set" Usage="Microsoft.Azure.Documents.DocumentCollection.IndexingPolicy" />
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
        <ReturnType>Microsoft.Azure.Documents.IndexingPolicy</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="8a8eb-144">Ruft die <see cref="P:Microsoft.Azure.Documents.DocumentCollection.IndexingPolicy" /> der Auflistung aus dem Azure-Cosmos-DB-Dienst zugeordnet sind.</span><span class="sxs-lookup"><span data-stu-id="8a8eb-144">Gets the <see cref="P:Microsoft.Azure.Documents.DocumentCollection.IndexingPolicy" /> associated with the collection from the Azure Cosmos DB service.</span></span> 
            </summary>
        <value>
            <span data-ttu-id="8a8eb-145">Die indizierungsrichtlinie Sammlung zugeordnet wird.</span><span class="sxs-lookup"><span data-stu-id="8a8eb-145">The indexing policy associated with the collection.</span></span>
            </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PartitionKey">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Documents.PartitionKeyDefinition PartitionKey { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Documents.PartitionKeyDefinition PartitionKey" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Documents.DocumentCollection.PartitionKey" />
      <MemberSignature Language="VB.NET" Value="Public Property PartitionKey As PartitionKeyDefinition" />
      <MemberSignature Language="F#" Value="member this.PartitionKey : Microsoft.Azure.Documents.PartitionKeyDefinition with get, set" Usage="Microsoft.Azure.Documents.DocumentCollection.PartitionKey" />
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
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="partitionKey")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Documents.PartitionKeyDefinition</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="8a8eb-146">Ruft ab oder legt ihn fest <see cref="T:Microsoft.Azure.Documents.PartitionKeyDefinition" /> Objekt in der Azure-Cosmos-Datenbank.</span><span class="sxs-lookup"><span data-stu-id="8a8eb-146">Gets or sets <see cref="T:Microsoft.Azure.Documents.PartitionKeyDefinition" /> object in the Azure Cosmos DB service.</span></span>
            </summary>
        <value>
          <span data-ttu-id="8a8eb-147"><see cref="T:Microsoft.Azure.Documents.PartitionKeyDefinition" />-Objekt</span><span class="sxs-lookup"><span data-stu-id="8a8eb-147"><see cref="T:Microsoft.Azure.Documents.PartitionKeyDefinition" /> object.</span></span>
            </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="StoredProceduresLink">
      <MemberSignature Language="C#" Value="public string StoredProceduresLink { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string StoredProceduresLink" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Documents.DocumentCollection.StoredProceduresLink" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property StoredProceduresLink As String" />
      <MemberSignature Language="F#" Value="member this.StoredProceduresLink : string" Usage="Microsoft.Azure.Documents.DocumentCollection.StoredProceduresLink" />
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
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="_sprocs")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="8a8eb-148">Ruft ab, der Self-link für gespeicherte Prozeduren in einer Auflistung aus dem Azure-Cosmos-DB-Dienst.</span><span class="sxs-lookup"><span data-stu-id="8a8eb-148">Gets the self-link for stored procedures in a collection from the Azure Cosmos DB service.</span></span>
            </summary>
        <value>
            <span data-ttu-id="8a8eb-149">Der Self-link für gespeicherte Prozeduren in einer Auflistung.</span><span class="sxs-lookup"><span data-stu-id="8a8eb-149">The self-link for stored procedures in a collection.</span></span>
            </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TriggersLink">
      <MemberSignature Language="C#" Value="public string TriggersLink { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string TriggersLink" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Documents.DocumentCollection.TriggersLink" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property TriggersLink As String" />
      <MemberSignature Language="F#" Value="member this.TriggersLink : string" Usage="Microsoft.Azure.Documents.DocumentCollection.TriggersLink" />
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
            <span data-ttu-id="8a8eb-150">Ruft ab, der Self-link für Trigger in einer Auflistung aus dem Azure-Cosmos-DB-Dienst.</span><span class="sxs-lookup"><span data-stu-id="8a8eb-150">Gets the self-link for triggers in a collection from the Azure Cosmos DB service.</span></span>
            </summary>
        <value>
            <span data-ttu-id="8a8eb-151">Der Self-link für Trigger in einer Auflistung.</span><span class="sxs-lookup"><span data-stu-id="8a8eb-151">The self-link for triggers in a collection.</span></span>
            </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UniqueKeyPolicy">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Documents.UniqueKeyPolicy UniqueKeyPolicy { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Documents.UniqueKeyPolicy UniqueKeyPolicy" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Documents.DocumentCollection.UniqueKeyPolicy" />
      <MemberSignature Language="VB.NET" Value="Public Property UniqueKeyPolicy As UniqueKeyPolicy" />
      <MemberSignature Language="F#" Value="member this.UniqueKeyPolicy : Microsoft.Azure.Documents.UniqueKeyPolicy with get, set" Usage="Microsoft.Azure.Documents.DocumentCollection.UniqueKeyPolicy" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Documents.Client</AssemblyName>
        <AssemblyVersion>1.19.0.0</AssemblyVersion>
      </AssemblyInfo>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DocumentDB.Core</AssemblyName>
        <AssemblyVersion>1.7.1.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="uniqueKeyPolicy")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Documents.UniqueKeyPolicy</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="8a8eb-152">Ruft ab oder legt die <see cref="P:Microsoft.Azure.Documents.DocumentCollection.UniqueKeyPolicy" /> gewährleisten, dass die Eindeutigkeit der Dokumente in der Auflistung in der Azure-Cosmos-DB-Dienst.</span><span class="sxs-lookup"><span data-stu-id="8a8eb-152">Gets or sets the <see cref="P:Microsoft.Azure.Documents.DocumentCollection.UniqueKeyPolicy" /> that guarantee uniqueness of documents in collection in the Azure Cosmos DB service.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UserDefinedFunctionsLink">
      <MemberSignature Language="C#" Value="public string UserDefinedFunctionsLink { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string UserDefinedFunctionsLink" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Documents.DocumentCollection.UserDefinedFunctionsLink" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property UserDefinedFunctionsLink As String" />
      <MemberSignature Language="F#" Value="member this.UserDefinedFunctionsLink : string" Usage="Microsoft.Azure.Documents.DocumentCollection.UserDefinedFunctionsLink" />
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
            <span data-ttu-id="8a8eb-153">Ruft die Self-link für den Benutzer definierten Funktionen in einer Auflistung aus dem Azure-Cosmos-DB-Dienst.</span><span class="sxs-lookup"><span data-stu-id="8a8eb-153">Gets the self-link for user defined functions in a collection from the Azure Cosmos DB service.</span></span>
            </summary>
        <value>
            <span data-ttu-id="8a8eb-154">Der Self-link für den Benutzer definierten Funktionen in einer Auflistung.</span><span class="sxs-lookup"><span data-stu-id="8a8eb-154">The self-link for user defined functions in a collection.</span></span>
            </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>