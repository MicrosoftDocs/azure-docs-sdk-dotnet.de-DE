<Type Name="EntityResolver&lt;T&gt;" FullName="Microsoft.WindowsAzure.Storage.Table.EntityResolver&lt;T&gt;">
  <TypeSignature Language="C#" Value="public delegate T EntityResolver&lt;T&gt;(string partitionKey, string rowKey, DateTimeOffset timestamp, IDictionary&lt;string,EntityProperty&gt; properties, string etag);" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed EntityResolver`1&lt;T&gt; extends System.MulticastDelegate" />
  <TypeSignature Language="DocId" Value="T:Microsoft.WindowsAzure.Storage.Table.EntityResolver`1" />
  <TypeSignature Language="VB.NET" Value="Public Delegate Function EntityResolver(Of T)(partitionKey As String, rowKey As String, timestamp As DateTimeOffset, properties As IDictionary(Of String, EntityProperty), etag As String) As T " />
  <TypeSignature Language="F#" Value="type EntityResolver&lt;'T&gt; = delegate of string * string * DateTimeOffset * IDictionary&lt;string, EntityProperty&gt; * string -&gt; 'T" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
    <AssemblyVersion>8.4.0.0</AssemblyVersion>
    <AssemblyVersion>8.7.0.0</AssemblyVersion>
  </AssemblyInfo>
  <TypeParameters>
    <TypeParameter Name="T" />
  </TypeParameters>
  <Base>
    <BaseTypeName>System.Delegate</BaseTypeName>
  </Base>
  <Parameters>
    <Parameter Name="partitionKey" Type="System.String" />
    <Parameter Name="rowKey" Type="System.String" />
    <Parameter Name="timestamp" Type="System.DateTimeOffset" />
    <Parameter Name="properties" Type="System.Collections.Generic.IDictionary&lt;System.String,Microsoft.WindowsAzure.Storage.Table.EntityProperty&gt;" />
    <Parameter Name="etag" Type="System.String" />
  </Parameters>
  <ReturnValue>
    <ReturnType>T</ReturnType>
  </ReturnValue>
  <Docs>
    <typeparam name="T"><span data-ttu-id="01b89-101">Der Typ, in dem die Abfrageergebnisse projiziert werden.</span><span class="sxs-lookup"><span data-stu-id="01b89-101">The type into which the query results are projected.</span></span></typeparam>
    <param name="partitionKey"><span data-ttu-id="01b89-102">Eine Zeichenfolge, die den Partitionsschlüssel der Entität enthält.</span><span class="sxs-lookup"><span data-stu-id="01b89-102">A string containing the partition key for the entity.</span></span></param>
    <param name="rowKey"><span data-ttu-id="01b89-103">Eine Zeichenfolge, die den Zeilenschlüssel der Entität enthält.</span><span class="sxs-lookup"><span data-stu-id="01b89-103">A string containing the row key for the entity.</span></span></param>
    <param name="timestamp"><span data-ttu-id="01b89-104">Ein <see cref="T:System.DateTimeOffset" /> mit dem Zeitstempel für die Entität.</span><span class="sxs-lookup"><span data-stu-id="01b89-104">A <see cref="T:System.DateTimeOffset" /> containing the timestamp for the entity.</span></span></param>
    <param name="properties"><span data-ttu-id="01b89-105">Ein <see cref="T:System.Collections.Generic.IDictionary`2" /> Objekt, das die Eigenschaften für die Entität enthält.</span><span class="sxs-lookup"><span data-stu-id="01b89-105">An <see cref="T:System.Collections.Generic.IDictionary`2" /> object containing the properties for the entity.</span></span></param>
    <param name="etag"><span data-ttu-id="01b89-106">Das ETag.</span><span class="sxs-lookup"><span data-stu-id="01b89-106">The ETag.</span></span></param>
    <summary>
            <span data-ttu-id="01b89-107">Gibt einen Delegaten zum Auflösen von Entitäten zurück.</span><span class="sxs-lookup"><span data-stu-id="01b89-107">Returns a delegate for resolving entities.</span></span>
            </summary>
    <returns />
    <remarks>To be added.</remarks>
  </Docs>
</Type>