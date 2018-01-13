<Type Name="EntityResolver&lt;T&gt;" FullName="Microsoft.Azure.CosmosDB.Table.EntityResolver&lt;T&gt;">
  <TypeSignature Language="C#" Value="public delegate T EntityResolver&lt;T&gt;(string partitionKey, string rowKey, DateTimeOffset timestamp, IDictionary&lt;string,EntityProperty&gt; properties, string etag);" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed EntityResolver`1&lt;T&gt; extends System.MulticastDelegate" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.CosmosDB.Table.EntityResolver`1" />
  <TypeSignature Language="VB.NET" Value="Public Delegate Function EntityResolver(Of T)(partitionKey As String, rowKey As String, timestamp As DateTimeOffset, properties As IDictionary(Of String, EntityProperty), etag As String) As T " />
  <TypeSignature Language="F#" Value="type EntityResolver&lt;'T&gt; = delegate of string * string * DateTimeOffset * IDictionary&lt;string, EntityProperty&gt; * string -&gt; 'T" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.CosmosDB.Table</AssemblyName>
    <AssemblyVersion>0.9.0.0</AssemblyVersion>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
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
    <Parameter Name="properties" Type="System.Collections.Generic.IDictionary&lt;System.String,Microsoft.Azure.CosmosDB.Table.EntityProperty&gt;" />
    <Parameter Name="etag" Type="System.String" />
  </Parameters>
  <ReturnValue>
    <ReturnType>T</ReturnType>
  </ReturnValue>
  <Docs>
    <typeparam name="T">Der Typ, in dem die Abfrageergebnisse projiziert werden.</typeparam>
    <param name="partitionKey">Eine Zeichenfolge, die den Partitionsschlüssel der Entität enthält.</param>
    <param name="rowKey">Eine Zeichenfolge, die den Zeilenschlüssel der Entität enthält.</param>
    <param name="timestamp">Ein <see cref="T:System.DateTimeOffset" /> mit dem Zeitstempel für die Entität.</param>
    <param name="properties">Ein <see cref="T:System.Collections.Generic.IDictionary`2" /> Objekt, das die Eigenschaften für die Entität enthält.</param>
    <param name="etag">Das ETag.</param>
    <summary>
            Gibt einen Delegaten zum Auflösen von Entitäten zurück.
            </summary>
    <returns />
    <remarks>To be added.</remarks>
  </Docs>
</Type>