<Type Name="IPartitionResolver" FullName="Microsoft.Azure.Documents.Client.IPartitionResolver">
  <TypeSignature Language="C#" Value="public interface IPartitionResolver" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IPartitionResolver" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Documents.Client.IPartitionResolver" />
  <TypeSignature Language="VB.NET" Value="Public Interface IPartitionResolver" />
  <TypeSignature Language="F#" Value="type IPartitionResolver = interface" />
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
  <Interfaces />
  <Attributes>
    <Attribute>
      <AttributeName>System.Obsolete("Support for IPartitionResolver is now obsolete. It's recommended that you use partitioned collections for higher storage and throughput.")</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            <span data-ttu-id="cb753-101">Dies stellt einen Partition-Konfliktlöser für eine Datenbank dar.</span><span class="sxs-lookup"><span data-stu-id="cb753-101">This represents a partition resolver for a database.</span></span> <span data-ttu-id="cb753-102">Partitionsschlüssel, zurück Auflistung einem Abgleich den Partitionsschlüssel im Azure-Cosmos-DB-Dienst.</span><span class="sxs-lookup"><span data-stu-id="cb753-102">Given a partition key, return the collection link(s) matching the partition key in the Azure Cosmos DB service.</span></span>
            </summary>
    <remarks>
      <para>
            <span data-ttu-id="cb753-103">Unterstützung für IPartitionResolver ist jetzt veraltet.</span><span class="sxs-lookup"><span data-stu-id="cb753-103">Support for IPartitionResolver is now obsolete.</span></span> <span data-ttu-id="cb753-104">Es wird empfohlen, die Verwendung von <a href="https://azure.microsoft.com/documentation/articles/documentdb-partition-data">partitionierte Sammlungen</a> für höhere Speicher und den Durchsatz.</span><span class="sxs-lookup"><span data-stu-id="cb753-104">It's recommended that you use <a href="https://azure.microsoft.com/documentation/articles/documentdb-partition-data">Partitioned Collections</a> for higher storage and throughput.</span></span>
            </para>
      <para>
            <span data-ttu-id="cb753-105">DocumentClient ermöglicht das Erstellen und registrieren Sie IPartitionResolvers Implementierungen für jede Datenbank.</span><span class="sxs-lookup"><span data-stu-id="cb753-105">DocumentClient allows you to create and register IPartitionResolvers implementations for each database.</span></span> <span data-ttu-id="cb753-106">Nach der Registrierung können Sie direkt an einer Datenbank statt einer Auflistung Dokumentenvorgänge ausführen.</span><span class="sxs-lookup"><span data-stu-id="cb753-106">Once registered, you can perform document operations directly against a database instead of a collection.</span></span> <span data-ttu-id="cb753-107">IPartitionResolvers verfügt über nur drei Methoden ExtractPartitionKey, ResolveForCreate und ResolveForRead.</span><span class="sxs-lookup"><span data-stu-id="cb753-107">IPartitionResolvers has just three methods ExtractPartitionKey, ResolveForCreate and ResolveForRead.</span></span>
            </para>
      <para>
            <span data-ttu-id="cb753-108">LINQ-Abfragen und ReadFeed Iteratoren mithilfe der ResolveForRead intern durchlaufen alle Sammlungen, die den Partitionsschlüssel für die Anforderung zu entsprechen.</span><span class="sxs-lookup"><span data-stu-id="cb753-108">LINQ queries and ReadFeed iterators use the ResolveForRead internally to iterate over all the collections that match the partition key for the request.</span></span> <span data-ttu-id="cb753-109">Erstellen Sie, verwenden Sie Vorgänge der ResolveForCreate zum Weiterleiten auf die richtige Partition erstellt.</span><span class="sxs-lookup"><span data-stu-id="cb753-109">Similarly, create operations use the ResolveForCreate to route creates to the right partition.</span></span> <span data-ttu-id="cb753-110">Es sind keine Änderungen erforderlich für ersetzen, löschen und lesen, da sie das Dokument verwenden, die bereits den Verweis auf die Auflistung enthält, die das Dokument enthält.</span><span class="sxs-lookup"><span data-stu-id="cb753-110">There are no changes required for Replace, Delete and Read since they use the Document, which already contains the reference to the collection that holds the document.</span></span>
            </para>
    </remarks>
  </Docs>
  <Members>
    <Member MemberName="GetPartitionKey">
      <MemberSignature Language="C#" Value="public object GetPartitionKey (object document);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance object GetPartitionKey(object document) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.Client.IPartitionResolver.GetPartitionKey(System.Object)" />
      <MemberSignature Language="VB.NET" Value="Public Function GetPartitionKey (document As Object) As Object" />
      <MemberSignature Language="F#" Value="abstract member GetPartitionKey : obj -&gt; obj" Usage="iPartitionResolver.GetPartitionKey document" />
      <MemberType>Method</MemberType>
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
        <ReturnType>System.Object</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="document" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="document"><span data-ttu-id="cb753-111">Ein Document-Objekt.</span><span class="sxs-lookup"><span data-stu-id="cb753-111">A document object.</span></span></param>
        <summary>
            <span data-ttu-id="cb753-112">Extrahiert den Partitionsschlüssel aus einem Dokument in der Azure-Cosmos-DB-Dienst an.</span><span class="sxs-lookup"><span data-stu-id="cb753-112">Extracts the partition key from a document in the Azure Cosmos DB service.</span></span>
            </summary>
        <returns><span data-ttu-id="cb753-113">Der Partitionsschlüssel für das Dokument.</span><span class="sxs-lookup"><span data-stu-id="cb753-113">The partition key for the document.</span></span></returns>
        <remarks>
            <span data-ttu-id="cb753-114">Typische Implementierungen rufen Sie den Wert einer einzelnen Eigenschaft aus dem Dokument (z. B. Benutzer-ID) oder eine zusammengesetzte Eigenschaft für z. B. Versions-ID extrahieren werden Gerät #) oder basierend auf dem Typ des Dokuments für z. B. Systemlogik implementieren, Wert der Id für Benutzer zu extrahieren, aber die UserId für UserMessages zu extrahieren.</span><span class="sxs-lookup"><span data-stu-id="cb753-114">Typical implementations will get the value of a single property from the document (e.g., user ID) or extract a compound property, for e.g., version ID, device #) or implement custom logic based on the type of the document, for e.g., extract value of id for users but extract userId for userMessages.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ResolveForCreate">
      <MemberSignature Language="C#" Value="public string ResolveForCreate (object partitionKey);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance string ResolveForCreate(object partitionKey) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.Client.IPartitionResolver.ResolveForCreate(System.Object)" />
      <MemberSignature Language="VB.NET" Value="Public Function ResolveForCreate (partitionKey As Object) As String" />
      <MemberSignature Language="F#" Value="abstract member ResolveForCreate : obj -&gt; string" Usage="iPartitionResolver.ResolveForCreate partitionKey" />
      <MemberType>Method</MemberType>
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
      <Parameters>
        <Parameter Name="partitionKey" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="partitionKey"><span data-ttu-id="cb753-115">Der Partitionsschlüssel verwendet werden, um zu bestimmen, das Ziel Auflistung für Vorgänge zu erstellen.</span><span class="sxs-lookup"><span data-stu-id="cb753-115">The partition key used to determine the target collection for create operations.</span></span></param>
        <summary>
            <span data-ttu-id="cb753-116">Erhält einen Partitionsschlüssel eingeben, gibt dies die Auflistung Self-link für das Erstellen eines Dokuments in der Azure-Cosmos-DB-Dienst.</span><span class="sxs-lookup"><span data-stu-id="cb753-116">Given a partition key, this returns the collection self-link for creating a document in the Azure Cosmos DB service.</span></span>
            </summary>
        <returns><span data-ttu-id="cb753-117">Eine Self-link für die Auflistung zum Erstellen von Dokumenten im für den angegebenen Partitionsschlüssel.</span><span class="sxs-lookup"><span data-stu-id="cb753-117">A self-link for the collection to create documents in for the specified partition key.</span></span></returns>
        <remarks>
            <span data-ttu-id="cb753-118">Der Rückgabewert muss eine gültige Sammlung Self-link-Zeichenfolge in das Format Dbs/Db_rid/colls/Col_rid.</span><span class="sxs-lookup"><span data-stu-id="cb753-118">The return value must be a valid collection self-link string in the format dbs/db_rid/colls/col_rid.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ResolveForRead">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IEnumerable&lt;string&gt; ResolveForRead (object partitionKey);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Collections.Generic.IEnumerable`1&lt;string&gt; ResolveForRead(object partitionKey) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.Client.IPartitionResolver.ResolveForRead(System.Object)" />
      <MemberSignature Language="VB.NET" Value="Public Function ResolveForRead (partitionKey As Object) As IEnumerable(Of String)" />
      <MemberSignature Language="F#" Value="abstract member ResolveForRead : obj -&gt; seq&lt;string&gt;" Usage="iPartitionResolver.ResolveForRead partitionKey" />
      <MemberType>Method</MemberType>
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
        <ReturnType>System.Collections.Generic.IEnumerable&lt;System.String&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="partitionKey" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="partitionKey"><span data-ttu-id="cb753-119">Der Partitionsschlüssel, bestimmen Sie die Zielsammlungen für Lesevorgänge, d. h., die Abfrage oder Read-Feed verwendet.</span><span class="sxs-lookup"><span data-stu-id="cb753-119">The partition key used to determine the target collections for reads, i.e., query or read-feed.</span></span></param>
        <summary>
            <span data-ttu-id="cb753-120">Erhält einen Partitionsschlüssel eingeben, gibt diese zurück, dass eine Liste der Sammlung Self-links, um gelesen werden.</span><span class="sxs-lookup"><span data-stu-id="cb753-120">Given a partition key, this returns a list of collection self-links to read from.</span></span>
            </summary>
        <returns><span data-ttu-id="cb753-121">Die Self-links für die Auflistungen leseanforderungen für den angegebenen Partitionsschlüssel ausführen.</span><span class="sxs-lookup"><span data-stu-id="cb753-121">The self-links for the collections to perform read requests for the specified partition key.</span></span></returns>
        <remarks>
            <span data-ttu-id="cb753-122">Der Rückgabewert muss ein IEnumerable von Self-link-Zeichenfolgen in die Format-Dbs/Db_rid/colls/Col_rid Auflistung sein.</span><span class="sxs-lookup"><span data-stu-id="cb753-122">The return value must be an IEnumerable of collection self-link strings in the format dbs/db_rid/colls/col_rid.</span></span>
            <span data-ttu-id="cb753-123">Im Gegensatz zu ResolveForCreate ist dies eine 1: n, wie ein einzelne Partitionsschlüssel in unterschiedlichen Sammlungen mit der Zeit erstellt werden kann, oder weil Sie die Datenmigration von Partitionsschlüssel zwischen Auflistungen in der Azure-Cosmos-DB-Dienst ausführen.</span><span class="sxs-lookup"><span data-stu-id="cb753-123">Unlike ResolveForCreate, this is a 1:N as a single partition key might be created in different collections over time or because you are performing data migration of partition key between collections in the Azure Cosmos DB service.</span></span>
            </remarks>
      </Docs>
    </Member>
  </Members>
</Type>