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
            Diese Klasse stellt Erweiterungsmethoden für die Erstellung von Graph-Abfragen vom Typ <see cref="T:Microsoft.Azure.Documents.Linq.IDocumentQuery`1" />.
            Diese Abfragen werden für Azure DocumentDB-Auflistung ausgeführt.
            </summary>
    <remarks>
            Die Klasse erweitert <see cref="T:Microsoft.Azure.Documents.Client.DocumentClient" /> Klasse ermöglicht schnelle Graph Durchlauf und CRUD-Vorgänge über Daten persistent in einer Azure DocumentDB-Auflistung. Das zurückgegebene <see cref="T:Microsoft.Azure.Documents.Linq.IDocumentQuery`1" /> umschließen die Ausführung der eigentlichen Abfrage von Objekten und Auflisten von diesen Objekten erzwingt Azure DocumentDB-Abfragen ausgeführt werden.
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
        <param name="documentClient">Die DocumentClient-Instanz, um die Abfrage auszuführen.</param>
        <param name="collection">Die DocumentCollection, die Diagramm, die Abfrage enthält.</param>
        <param name="gremlinExpression">Der Ausdruck Gremlin.</param>
        <param name="feedOptions">Die Optionen zum Verarbeiten des Abfrageergebnisses feed. Weitere Informationen <see cref="T:Microsoft.Azure.Documents.Client.FeedOptions" />.</param>
        <param name="graphSONMode">Der GraphSON-Modus zu verwenden, wenn die Ergebnisse der Abfrage zurückgegeben werden soll.</param>
        <summary>
            Die Methode zum Erstellen eines Ausdrucks Gremlin zum Erstellen und Abfragen von Graph-Elemente, die unter einem Azure-CosmosDB Auflistung gespeichert.
            </summary>
        <returns>Ein <see cref="T:Microsoft.Azure.Documents.Linq.IDocumentQuery`1" /> können, die die Abfrage ausgewertet.</returns>
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
        <typeparam name="T">Der Typ des Objekts, um die Abfrage.</typeparam>
        <param name="documentClient">Die DocumentClient-Instanz, um die Abfrage auszuführen.</param>
        <param name="collection">Die DocumentCollection, die Diagramm, die Abfrage enthält.</param>
        <param name="gremlinExpression">Der Ausdruck Gremlin.</param>
        <param name="feedOptions">Die Optionen zum Verarbeiten des Abfrageergebnisses feed. Weitere Informationen <see cref="T:Microsoft.Azure.Documents.Client.FeedOptions" />.</param>
        <param name="graphSONMode">Der GraphSON-Modus zu verwenden, wenn die Ergebnisse der Abfrage zurückgegeben werden soll.</param>
        <summary>
            Die Methode zum Erstellen eines Ausdrucks Gremlin zum Erstellen und Abfragen von Graph-Elemente, die unter einem Azure-CosmosDB Auflistung gespeichert.
            </summary>
        <returns>Ein <see cref="T:Microsoft.Azure.Documents.Linq.IDocumentQuery`1" /> können, die die Abfrage ausgewertet.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>