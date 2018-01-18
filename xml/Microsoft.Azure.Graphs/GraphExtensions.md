<Type Name="GraphExtensions" FullName="Microsoft.Azure.Graphs.GraphExtensions">
  <TypeSignature Language="C#" Value="public static class GraphExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed GraphExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Graphs.GraphExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module GraphExtensions" />
  <TypeSignature Language="F#" Value="type GraphExtensions = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Graphs</AssemblyName>
    <AssemblyVersion>0.3.0.0</AssemblyVersion>
    <AssemblyVersion>1.14.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="e0950-101">Diese Klasse stellt Erweiterungsmethoden für die Erstellung von Graph-Abfragen vom Typ <see cref="T:Microsoft.Azure.Documents.Linq.IDocumentQuery`1" />.</span><span class="sxs-lookup"><span data-stu-id="e0950-101">This class provides extension methods for creating Graph queries of type <see cref="T:Microsoft.Azure.Documents.Linq.IDocumentQuery`1" />.</span></span>
            <span data-ttu-id="e0950-102">Diese Abfragen werden für Azure DocumentDB-Auflistung ausgeführt.</span><span class="sxs-lookup"><span data-stu-id="e0950-102">These queries will execute against Azure DocumentDB collection.</span></span>
            </summary>
    <remarks>
            <span data-ttu-id="e0950-103">Die Klasse erweitert <see cref="T:Microsoft.Azure.Documents.Client.DocumentClient" /> Klasse ermöglicht schnelle Graph Durchlauf und CRUD-Vorgänge über Daten persistent in einer Azure DocumentDB-Auflistung.</span><span class="sxs-lookup"><span data-stu-id="e0950-103">The class extends <see cref="T:Microsoft.Azure.Documents.Client.DocumentClient" /> class to enable you to express graph traversal and CRUD operations over data persisted in a Azure DocumentDB collection.</span></span> <span data-ttu-id="e0950-104">Das zurückgegebene <see cref="T:Microsoft.Azure.Documents.Linq.IDocumentQuery`1" /> umschließen die Ausführung der eigentlichen Abfrage von Objekten und Auflisten von diesen Objekten erzwingt Azure DocumentDB-Abfragen ausgeführt werden.</span><span class="sxs-lookup"><span data-stu-id="e0950-104">The returned <see cref="T:Microsoft.Azure.Documents.Linq.IDocumentQuery`1" /> objects wrap the actual query execution, and enumerating these objects forces Azure DocumentDB queries to be executed.</span></span>
            </remarks>
  </Docs>
  <Members>
    <Member MemberName="CreateGremlinQuery">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Documents.Linq.IDocumentQuery&lt;dynamic&gt; CreateGremlinQuery (this Microsoft.Azure.Documents.Client.DocumentClient documentClient, Microsoft.Azure.Documents.DocumentCollection collection, string gremlinExpression, Microsoft.Azure.Documents.Client.FeedOptions feedOptions = null, Microsoft.Azure.Graphs.GraphSONMode graphSONMode = Microsoft.Azure.Graphs.GraphSONMode.Compact);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Documents.Linq.IDocumentQuery`1&lt;object&gt; CreateGremlinQuery(class Microsoft.Azure.Documents.Client.DocumentClient documentClient, class Microsoft.Azure.Documents.DocumentCollection collection, string gremlinExpression, class Microsoft.Azure.Documents.Client.FeedOptions feedOptions, valuetype Microsoft.Azure.Graphs.GraphSONMode graphSONMode) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Graphs.GraphExtensions.CreateGremlinQuery(Microsoft.Azure.Documents.Client.DocumentClient,Microsoft.Azure.Documents.DocumentCollection,System.String,Microsoft.Azure.Documents.Client.FeedOptions,Microsoft.Azure.Graphs.GraphSONMode)" />
      <MemberSignature Language="F#" Value="static member CreateGremlinQuery : Microsoft.Azure.Documents.Client.DocumentClient * Microsoft.Azure.Documents.DocumentCollection * string * Microsoft.Azure.Documents.Client.FeedOptions * Microsoft.Azure.Graphs.GraphSONMode -&gt; Microsoft.Azure.Documents.Linq.IDocumentQuery&lt;obj&gt;" Usage="Microsoft.Azure.Graphs.GraphExtensions.CreateGremlinQuery (documentClient, collection, gremlinExpression, feedOptions, graphSONMode)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Graphs</AssemblyName>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
        <AssemblyVersion>1.14.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Documents.Linq.IDocumentQuery&lt;System.Object&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="documentClient" Type="Microsoft.Azure.Documents.Client.DocumentClient" RefType="this" />
        <Parameter Name="collection" Type="Microsoft.Azure.Documents.DocumentCollection" />
        <Parameter Name="gremlinExpression" Type="System.String" />
        <Parameter Name="feedOptions" Type="Microsoft.Azure.Documents.Client.FeedOptions" />
        <Parameter Name="graphSONMode" Type="Microsoft.Azure.Graphs.GraphSONMode" />
      </Parameters>
      <Docs>
        <param name="documentClient"><span data-ttu-id="e0950-105">Die DocumentClient-Instanz, um die Abfrage auszuführen.</span><span class="sxs-lookup"><span data-stu-id="e0950-105">The DocumentClient instance to execute the query.</span></span></param>
        <param name="collection"><span data-ttu-id="e0950-106">Die DocumentCollection, die Diagramm, die Abfrage enthält.</span><span class="sxs-lookup"><span data-stu-id="e0950-106">The DocumentCollection that contains the graph to query.</span></span></param>
        <param name="gremlinExpression"><span data-ttu-id="e0950-107">Der Ausdruck Gremlin.</span><span class="sxs-lookup"><span data-stu-id="e0950-107">The Gremlin expression.</span></span></param>
        <param name="feedOptions"><span data-ttu-id="e0950-108">Die Optionen zum Verarbeiten des Abfrageergebnisses feed.</span><span class="sxs-lookup"><span data-stu-id="e0950-108">The options for processing the query result feed.</span></span> <span data-ttu-id="e0950-109">Weitere Informationen <see cref="T:Microsoft.Azure.Documents.Client.FeedOptions" />.</span><span class="sxs-lookup"><span data-stu-id="e0950-109">For details <see cref="T:Microsoft.Azure.Documents.Client.FeedOptions" />.</span></span></param>
        <param name="graphSONMode"><span data-ttu-id="e0950-110">Der GraphSON-Modus zu verwenden, wenn die Ergebnisse der Abfrage zurückgegeben werden soll.</span><span class="sxs-lookup"><span data-stu-id="e0950-110">The GraphSON mode to use when returning the results of the query.</span></span></param>
        <summary>
            <span data-ttu-id="e0950-111">Die Methode zum Erstellen eines Ausdrucks Gremlin zum Erstellen und Abfragen von Graph-Elemente, die unter einem Azure-CosmosDB Auflistung gespeichert.</span><span class="sxs-lookup"><span data-stu-id="e0950-111">Method to create a Gremlin expression to create/query graph elements stored under an Azure CosmosDB collection.</span></span>
            </summary>
        <returns><span data-ttu-id="e0950-112">Ein <see cref="T:Microsoft.Azure.Documents.Linq.IDocumentQuery`1" /> können, die die Abfrage ausgewertet.</span><span class="sxs-lookup"><span data-stu-id="e0950-112">An <see cref="T:Microsoft.Azure.Documents.Linq.IDocumentQuery`1" /> that can evaluate the query.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateGremlinQuery&lt;T&gt;">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Documents.Linq.IDocumentQuery&lt;T&gt; CreateGremlinQuery&lt;T&gt; (this Microsoft.Azure.Documents.Client.DocumentClient documentClient, Microsoft.Azure.Documents.DocumentCollection collection, string gremlinExpression, Microsoft.Azure.Documents.Client.FeedOptions feedOptions = null, Microsoft.Azure.Graphs.GraphSONMode graphSONMode = Microsoft.Azure.Graphs.GraphSONMode.Compact);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Documents.Linq.IDocumentQuery`1&lt;!!T&gt; CreateGremlinQuery&lt;T&gt;(class Microsoft.Azure.Documents.Client.DocumentClient documentClient, class Microsoft.Azure.Documents.DocumentCollection collection, string gremlinExpression, class Microsoft.Azure.Documents.Client.FeedOptions feedOptions, valuetype Microsoft.Azure.Graphs.GraphSONMode graphSONMode) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Graphs.GraphExtensions.CreateGremlinQuery``1(Microsoft.Azure.Documents.Client.DocumentClient,Microsoft.Azure.Documents.DocumentCollection,System.String,Microsoft.Azure.Documents.Client.FeedOptions,Microsoft.Azure.Graphs.GraphSONMode)" />
      <MemberSignature Language="F#" Value="static member CreateGremlinQuery : Microsoft.Azure.Documents.Client.DocumentClient * Microsoft.Azure.Documents.DocumentCollection * string * Microsoft.Azure.Documents.Client.FeedOptions * Microsoft.Azure.Graphs.GraphSONMode -&gt; Microsoft.Azure.Documents.Linq.IDocumentQuery&lt;'T&gt;" Usage="Microsoft.Azure.Graphs.GraphExtensions.CreateGremlinQuery (documentClient, collection, gremlinExpression, feedOptions, graphSONMode)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Graphs</AssemblyName>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
        <AssemblyVersion>1.14.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Documents.Linq.IDocumentQuery&lt;T&gt;</ReturnType>
      </ReturnValue>
      <TypeParameters>
        <TypeParameter Name="T" />
      </TypeParameters>
      <Parameters>
        <Parameter Name="documentClient" Type="Microsoft.Azure.Documents.Client.DocumentClient" RefType="this" />
        <Parameter Name="collection" Type="Microsoft.Azure.Documents.DocumentCollection" />
        <Parameter Name="gremlinExpression" Type="System.String" />
        <Parameter Name="feedOptions" Type="Microsoft.Azure.Documents.Client.FeedOptions" />
        <Parameter Name="graphSONMode" Type="Microsoft.Azure.Graphs.GraphSONMode" />
      </Parameters>
      <Docs>
        <typeparam name="T"><span data-ttu-id="e0950-113">Der Typ des Objekts, um die Abfrage.</span><span class="sxs-lookup"><span data-stu-id="e0950-113">Type of the object to query.</span></span></typeparam>
        <param name="documentClient"><span data-ttu-id="e0950-114">Die DocumentClient-Instanz, um die Abfrage auszuführen.</span><span class="sxs-lookup"><span data-stu-id="e0950-114">The DocumentClient instance to execute the query.</span></span></param>
        <param name="collection"><span data-ttu-id="e0950-115">Die DocumentCollection, die Diagramm, die Abfrage enthält.</span><span class="sxs-lookup"><span data-stu-id="e0950-115">The DocumentCollection that contains the graph to query.</span></span></param>
        <param name="gremlinExpression"><span data-ttu-id="e0950-116">Der Ausdruck Gremlin.</span><span class="sxs-lookup"><span data-stu-id="e0950-116">The Gremlin expression.</span></span></param>
        <param name="feedOptions"><span data-ttu-id="e0950-117">Die Optionen zum Verarbeiten des Abfrageergebnisses feed.</span><span class="sxs-lookup"><span data-stu-id="e0950-117">The options for processing the query result feed.</span></span> <span data-ttu-id="e0950-118">Weitere Informationen <see cref="T:Microsoft.Azure.Documents.Client.FeedOptions" />.</span><span class="sxs-lookup"><span data-stu-id="e0950-118">For details <see cref="T:Microsoft.Azure.Documents.Client.FeedOptions" />.</span></span></param>
        <param name="graphSONMode"><span data-ttu-id="e0950-119">Der GraphSON-Modus zu verwenden, wenn die Ergebnisse der Abfrage zurückgegeben werden soll.</span><span class="sxs-lookup"><span data-stu-id="e0950-119">The GraphSON mode to use when returning the results of the query.</span></span></param>
        <summary>
            <span data-ttu-id="e0950-120">Die Methode zum Erstellen eines Ausdrucks Gremlin zum Erstellen und Abfragen von Graph-Elemente, die unter einem Azure-CosmosDB Auflistung gespeichert.</span><span class="sxs-lookup"><span data-stu-id="e0950-120">Method to create a Gremlin expression to create/query graph elements stored under an Azure CosmosDB collection.</span></span>
            </summary>
        <returns><span data-ttu-id="e0950-121">Ein <see cref="T:Microsoft.Azure.Documents.Linq.IDocumentQuery`1" /> können, die die Abfrage ausgewertet.</span><span class="sxs-lookup"><span data-stu-id="e0950-121">An <see cref="T:Microsoft.Azure.Documents.Linq.IDocumentQuery`1" /> that can evaluate the query.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>