<Type Name="SchemaInfoCollection" FullName="Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Schema.SchemaInfoCollection">
  <TypeSignature Language="C#" Value="public class SchemaInfoCollection : System.Collections.Generic.IEnumerable&lt;System.Collections.Generic.KeyValuePair&lt;string,Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Schema.SchemaInfo&gt;&gt;" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit SchemaInfoCollection extends System.Object implements class System.Collections.Generic.IEnumerable`1&lt;valuetype System.Collections.Generic.KeyValuePair`2&lt;string, class Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Schema.SchemaInfo&gt;&gt;, class System.Collections.IEnumerable" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Schema.SchemaInfoCollection" />
  <TypeSignature Language="VB.NET" Value="Public Class SchemaInfoCollection&#xA;Implements IEnumerable(Of KeyValuePair(Of String, SchemaInfo))" />
  <TypeSignature Language="F#" Value="type SchemaInfoCollection = class&#xA;    interface seq&lt;KeyValuePair&lt;string, SchemaInfo&gt;&gt;&#xA;    interface IEnumerable" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.SqlDatabase.ElasticScale.Client</AssemblyName>
    <AssemblyVersion>1.3.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces>
    <Interface>
      <InterfaceName>System.Collections.Generic.IEnumerable&lt;System.Collections.Generic.KeyValuePair&lt;System.String,Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Schema.SchemaInfo&gt;&gt;</InterfaceName>
    </Interface>
  </Interfaces>
  <Docs>
    <summary>
            <span data-ttu-id="286b9-101">Bietet Speicherdienste an einen Client für Storing\updating\retrieving Schemainformationen ein shardingschema zugeordnet sind und einzelne Buckets Informationen Namen zuweisen.</span><span class="sxs-lookup"><span data-stu-id="286b9-101">Provides storage services to a client for storing\updating\retrieving schema information associated with a sharding scheme and assigning names to individual buckets of information.</span></span> <span data-ttu-id="286b9-102">Die Klasse speichert nicht die Zuordnung zwischen einem shardingschema und die Metadaten-Einheit.</span><span class="sxs-lookup"><span data-stu-id="286b9-102">The class doesn't store the association between a sharding scheme and the metadata unit.</span></span> <span data-ttu-id="286b9-103">Es ist die Zuordnung verwalten in der Verantwortung des Aufrufers.</span><span class="sxs-lookup"><span data-stu-id="286b9-103">It's the caller's responsibility to maintain the mapping.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="Add">
      <MemberSignature Language="C#" Value="public void Add (string shardMapName, Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Schema.SchemaInfo schemaInfo);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance void Add(string shardMapName, class Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Schema.SchemaInfo schemaInfo) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Schema.SchemaInfoCollection.Add(System.String,Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Schema.SchemaInfo)" />
      <MemberSignature Language="F#" Value="member this.Add : string * Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Schema.SchemaInfo -&gt; unit" Usage="schemaInfoCollection.Add (shardMapName, schemaInfo)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.SqlDatabase.ElasticScale.Client</AssemblyName>
        <AssemblyVersion>1.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="shardMapName" Type="System.String" />
        <Parameter Name="schemaInfo" Type="Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Schema.SchemaInfo" />
      </Parameters>
      <Docs>
        <param name="shardMapName"><span data-ttu-id="286b9-104">Der Name des der <see cref="T:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardMap" /> , die <see cref="T:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Schema.SchemaInfo" /> zugeordnet wird</span><span class="sxs-lookup"><span data-stu-id="286b9-104">The name of the <see cref="T:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardMap" /> that the <see cref="T:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Schema.SchemaInfo" /> will be associated with</span></span></param>
        <param name="schemaInfo"><span data-ttu-id="286b9-105">Sharding-Schemainformationen.</span><span class="sxs-lookup"><span data-stu-id="286b9-105">Sharding schema information.</span></span></param>
        <summary>
            <span data-ttu-id="286b9-106">Fügt eine <see cref="T:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Schema.SchemaInfo" /> zugeordneten der angegebenen <see cref="T:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardMap" /> Name.</span><span class="sxs-lookup"><span data-stu-id="286b9-106">Adds a <see cref="T:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Schema.SchemaInfo" /> that is associated with the given <see cref="T:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardMap" /> name.</span></span> <span data-ttu-id="286b9-107">Die zugeordneten Daten enthält Informationen über Sharding-Tabellen und Verweistabellen.</span><span class="sxs-lookup"><span data-stu-id="286b9-107">The associated data contains information concerning sharded tables and reference tables.</span></span> <span data-ttu-id="286b9-108">Wenn Sie versuchen, Sie fügen eine <see cref="T:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Schema.SchemaInfo" /> mit einem vorhandenen Namen, eine Namenskonflikt Ausnahme ausgelöst</span><span class="sxs-lookup"><span data-stu-id="286b9-108">If you try to add a <see cref="T:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Schema.SchemaInfo" /> with an existing name, a name-conflict exception will be thrown</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Get">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Schema.SchemaInfo Get (string shardMapName);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Schema.SchemaInfo Get(string shardMapName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Schema.SchemaInfoCollection.Get(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function Get (shardMapName As String) As SchemaInfo" />
      <MemberSignature Language="F#" Value="member this.Get : string -&gt; Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Schema.SchemaInfo" Usage="schemaInfoCollection.Get shardMapName" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.SqlDatabase.ElasticScale.Client</AssemblyName>
        <AssemblyVersion>1.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Schema.SchemaInfo</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="shardMapName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="shardMapName"><span data-ttu-id="286b9-109">Der Name des der <see cref="T:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardMap" /> abgerufen.</span><span class="sxs-lookup"><span data-stu-id="286b9-109">The name of the <see cref="T:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardMap" /> to get.</span></span></param>
        <summary>
            <span data-ttu-id="286b9-110">Ruft die <see cref="T:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Schema.SchemaInfo" /> gespeichert, die mit dem angegebenen <see cref="T:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardMap" /> Name.</span><span class="sxs-lookup"><span data-stu-id="286b9-110">Fetches the <see cref="T:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Schema.SchemaInfo" /> stored with the supplied <see cref="T:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardMap" /> name.</span></span>
            </summary>
        <returns><span data-ttu-id="286b9-111">SchemaInfo-Objekt.</span><span class="sxs-lookup"><span data-stu-id="286b9-111">SchemaInfo object.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetEnumerator">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IEnumerator&lt;System.Collections.Generic.KeyValuePair&lt;string,Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Schema.SchemaInfo&gt;&gt; GetEnumerator ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Collections.Generic.IEnumerator`1&lt;valuetype System.Collections.Generic.KeyValuePair`2&lt;string, class Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Schema.SchemaInfo&gt;&gt; GetEnumerator() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Schema.SchemaInfoCollection.GetEnumerator" />
      <MemberSignature Language="VB.NET" Value="Public Function GetEnumerator () As IEnumerator(Of KeyValuePair(Of String, SchemaInfo))" />
      <MemberSignature Language="F#" Value="abstract member GetEnumerator : unit -&gt; System.Collections.Generic.IEnumerator&lt;System.Collections.Generic.KeyValuePair&lt;string, Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Schema.SchemaInfo&gt;&gt;&#xA;override this.GetEnumerator : unit -&gt; System.Collections.Generic.IEnumerator&lt;System.Collections.Generic.KeyValuePair&lt;string, Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Schema.SchemaInfo&gt;&gt;" Usage="schemaInfoCollection.GetEnumerator " />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:System.Collections.Generic.IEnumerable`1.GetEnumerator</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.SqlDatabase.ElasticScale.Client</AssemblyName>
        <AssemblyVersion>1.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IEnumerator&lt;System.Collections.Generic.KeyValuePair&lt;System.String,Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Schema.SchemaInfo&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="286b9-112">Gibt einen Enumerator zurück, der die <see cref="T:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Schema.SchemaInfoCollection" /> durchläuft.</span><span class="sxs-lookup"><span data-stu-id="286b9-112">Returns an enumerator that iterates through the <see cref="T:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Schema.SchemaInfoCollection" />.</span></span>
            </summary>
        <returns><span data-ttu-id="286b9-113">Enumerator von Schlüssel-Wert-Paaren mit Namen und <see cref="T:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Schema.SchemaInfo" /> Objekte.</span><span class="sxs-lookup"><span data-stu-id="286b9-113">Enumerator of key-value pairs of name and <see cref="T:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Schema.SchemaInfo" /> objects.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Remove">
      <MemberSignature Language="C#" Value="public void Remove (string shardMapName);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance void Remove(string shardMapName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Schema.SchemaInfoCollection.Remove(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub Remove (shardMapName As String)" />
      <MemberSignature Language="F#" Value="member this.Remove : string -&gt; unit" Usage="schemaInfoCollection.Remove shardMapName" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.SqlDatabase.ElasticScale.Client</AssemblyName>
        <AssemblyVersion>1.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="shardMapName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="shardMapName"><span data-ttu-id="286b9-114">Der Name des der <see cref="T:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardMap" /> , deren <see cref="T:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Schema.SchemaInfo" /> wird entfernt</span><span class="sxs-lookup"><span data-stu-id="286b9-114">The name of the <see cref="T:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardMap" /> whose <see cref="T:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Schema.SchemaInfo" /> will be removed</span></span></param>
        <summary>
            <span data-ttu-id="286b9-115">Entfernt die <see cref="T:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Schema.SchemaInfo" /> mit der angegebenen <see cref="T:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardMap" /> Name.</span><span class="sxs-lookup"><span data-stu-id="286b9-115">Removes the <see cref="T:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Schema.SchemaInfo" /> with the given <see cref="T:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardMap" /> name.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Replace">
      <MemberSignature Language="C#" Value="public void Replace (string shardMapName, Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Schema.SchemaInfo schemaInfo);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance void Replace(string shardMapName, class Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Schema.SchemaInfo schemaInfo) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Schema.SchemaInfoCollection.Replace(System.String,Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Schema.SchemaInfo)" />
      <MemberSignature Language="F#" Value="member this.Replace : string * Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Schema.SchemaInfo -&gt; unit" Usage="schemaInfoCollection.Replace (shardMapName, schemaInfo)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.SqlDatabase.ElasticScale.Client</AssemblyName>
        <AssemblyVersion>1.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="shardMapName" Type="System.String" />
        <Parameter Name="schemaInfo" Type="Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Schema.SchemaInfo" />
      </Parameters>
      <Docs>
        <param name="shardMapName"><span data-ttu-id="286b9-116">Der Name des der <see cref="T:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardMap" /> , deren <see cref="T:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Schema.SchemaInfo" /> ersetzt werden.</span><span class="sxs-lookup"><span data-stu-id="286b9-116">The name of the <see cref="T:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardMap" /> whose <see cref="T:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Schema.SchemaInfo" /> will be replaced.</span></span></param>
        <param name="schemaInfo"><span data-ttu-id="286b9-117">Sharding-Schemainformationen.</span><span class="sxs-lookup"><span data-stu-id="286b9-117">Sharding schema information.</span></span></param>
        <summary>
            <span data-ttu-id="286b9-118">Ersetzt die <see cref="T:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Schema.SchemaInfo" /> mit der angegebenen <see cref="T:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardMap" /> Name.</span><span class="sxs-lookup"><span data-stu-id="286b9-118">Replaces the <see cref="T:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Schema.SchemaInfo" /> with the given <see cref="T:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardMap" /> name.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="System.Collections.IEnumerable.GetEnumerator">
      <MemberSignature Language="C#" Value="System.Collections.IEnumerator IEnumerable.GetEnumerator ();" />
      <MemberSignature Language="ILAsm" Value=".method hidebysig newslot virtual instance class System.Collections.IEnumerator System.Collections.IEnumerable.GetEnumerator() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Schema.SchemaInfoCollection.System#Collections#IEnumerable#GetEnumerator" />
      <MemberSignature Language="VB.NET" Value="Function GetEnumerator () As IEnumerator Implements IEnumerable.GetEnumerator" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:System.Collections.IEnumerable.GetEnumerator</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.SqlDatabase.ElasticScale.Client</AssemblyName>
        <AssemblyVersion>1.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.IEnumerator</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="286b9-119">Gibt einen Enumerator, der dies durchläuft <see cref="T:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Schema.SchemaInfoCollection" />.</span><span class="sxs-lookup"><span data-stu-id="286b9-119">Returns an enumerator that iterates through this <see cref="T:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Schema.SchemaInfoCollection" />.</span></span>
            </summary>
        <returns><span data-ttu-id="286b9-120">Enumerator von Schlüssel-Wert-Paaren mit Namen und <see cref="T:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Schema.SchemaInfo" /> Objekte.</span><span class="sxs-lookup"><span data-stu-id="286b9-120">Enumerator of key-value pairs of name and <see cref="T:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Schema.SchemaInfo" /> objects.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TryGet">
      <MemberSignature Language="C#" Value="public bool TryGet (string shardMapName, out Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Schema.SchemaInfo schemaInfo);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance bool TryGet(string shardMapName, [out] class Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Schema.SchemaInfo&amp; schemaInfo) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Schema.SchemaInfoCollection.TryGet(System.String,Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Schema.SchemaInfo@)" />
      <MemberSignature Language="VB.NET" Value="Public Function TryGet (shardMapName As String, ByRef schemaInfo As SchemaInfo) As Boolean" />
      <MemberSignature Language="F#" Value="member this.TryGet : string *  -&gt; bool" Usage="schemaInfoCollection.TryGet (shardMapName, schemaInfo)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.SqlDatabase.ElasticScale.Client</AssemblyName>
        <AssemblyVersion>1.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="shardMapName" Type="System.String" />
        <Parameter Name="schemaInfo" Type="Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Schema.SchemaInfo&amp;" RefType="out" />
      </Parameters>
      <Docs>
        <param name="shardMapName"><span data-ttu-id="286b9-121">Der Name des der <see cref="T:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardMap" /> , deren <see cref="T:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Schema.SchemaInfo" /> wird abgerufen</span><span class="sxs-lookup"><span data-stu-id="286b9-121">The name of the <see cref="T:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardMap" /> whose <see cref="T:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Schema.SchemaInfo" /> will be fetched</span></span></param>
        <param name="schemaInfo"><span data-ttu-id="286b9-122">Die <see cref="T:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Schema.SchemaInfo" /> abgerufenen oder null, wenn Fehler beim Abrufen des wurde</span><span class="sxs-lookup"><span data-stu-id="286b9-122">The <see cref="T:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Schema.SchemaInfo" /> that was fetched or null if retrieval failed</span></span></param>
        <summary>
            <span data-ttu-id="286b9-123">Versucht, Abrufen der <see cref="T:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Schema.SchemaInfo" /> mit der angegebenen <see cref="T:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardMap" /> Namen ohne eine Ausnahme auslösen, wenn Daten nicht vorhanden ist.</span><span class="sxs-lookup"><span data-stu-id="286b9-123">Tries to fetch the <see cref="T:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Schema.SchemaInfo" /> with the given <see cref="T:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardMap" /> name without raising any exception if data doesn't exist.</span></span>
            </summary>
        <returns><span data-ttu-id="286b9-124">"true", wenn Schemainformationen andernfalls mit dem angegebenen Namen, "false" vorhanden ist.</span><span class="sxs-lookup"><span data-stu-id="286b9-124">true if schema info exists with given name, false otherwise.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>