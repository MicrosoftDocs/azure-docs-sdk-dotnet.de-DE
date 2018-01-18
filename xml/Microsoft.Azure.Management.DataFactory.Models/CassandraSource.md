<Type Name="CassandraSource" FullName="Microsoft.Azure.Management.DataFactory.Models.CassandraSource">
  <TypeSignature Language="C#" Value="public class CassandraSource : Microsoft.Azure.Management.DataFactory.Models.CopySource" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit CassandraSource extends Microsoft.Azure.Management.DataFactory.Models.CopySource" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.DataFactory.Models.CassandraSource" />
  <TypeSignature Language="VB.NET" Value="Public Class CassandraSource&#xA;Inherits CopySource" />
  <TypeSignature Language="F#" Value="type CassandraSource = class&#xA;    inherit CopySource" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
    <AssemblyVersion>0.2.0.0</AssemblyVersion>
    <AssemblyVersion>0.3.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.Management.DataFactory.Models.CopySource</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="ac510-101">Eine Aktivität Kopiequelle für eine Datenbank Cassandra.</span><span class="sxs-lookup"><span data-stu-id="ac510-101">A copy activity source for a Cassandra database.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public CassandraSource ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.Models.CassandraSource.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="ac510-102">Initialisiert eine neue Instanz der CassandraSource-Klasse.</span><span class="sxs-lookup"><span data-stu-id="ac510-102">Initializes a new instance of the CassandraSource class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public CassandraSource (System.Collections.Generic.IDictionary&lt;string,object&gt; additionalProperties = null, object sourceRetryCount = null, object sourceRetryWait = null, object query = null, string consistencyLevel = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.Collections.Generic.IDictionary`2&lt;string, object&gt; additionalProperties, object sourceRetryCount, object sourceRetryWait, object query, string consistencyLevel) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.Models.CassandraSource.#ctor(System.Collections.Generic.IDictionary{System.String,System.Object},System.Object,System.Object,System.Object,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional additionalProperties As IDictionary(Of String, Object) = null, Optional sourceRetryCount As Object = null, Optional sourceRetryWait As Object = null, Optional query As Object = null, Optional consistencyLevel As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.DataFactory.Models.CassandraSource : System.Collections.Generic.IDictionary&lt;string, obj&gt; * obj * obj * obj * string -&gt; Microsoft.Azure.Management.DataFactory.Models.CassandraSource" Usage="new Microsoft.Azure.Management.DataFactory.Models.CassandraSource (additionalProperties, sourceRetryCount, sourceRetryWait, query, consistencyLevel)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="additionalProperties" Type="System.Collections.Generic.IDictionary&lt;System.String,System.Object&gt;" />
        <Parameter Name="sourceRetryCount" Type="System.Object" />
        <Parameter Name="sourceRetryWait" Type="System.Object" />
        <Parameter Name="query" Type="System.Object" />
        <Parameter Name="consistencyLevel" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="additionalProperties"><span data-ttu-id="ac510-103">Nicht übereinstimmende Eigenschaften aus der Nachricht deserialisiert werden diese Sammlung</span><span class="sxs-lookup"><span data-stu-id="ac510-103">Unmatched properties from the message are deserialized this collection</span></span></param>
        <param name="sourceRetryCount"><span data-ttu-id="ac510-104">Anzahl von Wiederholungsversuchen Quelle.</span><span class="sxs-lookup"><span data-stu-id="ac510-104">Source retry count.</span></span> <span data-ttu-id="ac510-105">Typ: ganze Zahl (oder Ausdrücke mit ganzzahligen ResultType-Element).</span><span class="sxs-lookup"><span data-stu-id="ac510-105">Type: integer (or Expression with resultType integer).</span></span></param>
        <param name="sourceRetryWait"><span data-ttu-id="ac510-106">Warten Sie Quelle, versuchen Sie es erneut.</span><span class="sxs-lookup"><span data-stu-id="ac510-106">Source retry wait.</span></span> <span data-ttu-id="ac510-107">Typ: Zeichenfolge (oder Ausdruck mit ResultType-Zeichenfolge), Muster: ((\d+)\.)? () :(60| \d\d) ([0-5][0-9])): () 60 | ([0-5][0-9])).</span><span class="sxs-lookup"><span data-stu-id="ac510-107">Type: string (or Expression with resultType string), pattern: ((\d+)\.)?(\d\d):(60|([0-5][0-9])):(60|([0-5][0-9])).</span></span></param>
        <param name="query"><span data-ttu-id="ac510-108">Datenbankabfrage.</span><span class="sxs-lookup"><span data-stu-id="ac510-108">Database query.</span></span> <span data-ttu-id="ac510-109">Sollte es sich um eine SQL-92-Ausdruck oder einen Befehl für Cassandra Query Language (CQL) sein.</span><span class="sxs-lookup"><span data-stu-id="ac510-109">Should be a SQL-92 query expression or Cassandra Query Language (CQL) command.</span></span> <span data-ttu-id="ac510-110">Typ: Zeichenfolge (oder Ausdruck mit ResultType-Zeichenfolge).</span><span class="sxs-lookup"><span data-stu-id="ac510-110">Type: string (or Expression with resultType string).</span></span></param>
        <param name="consistencyLevel"><span data-ttu-id="ac510-111">Die konsistenzebene gibt an, wie viele Cassandra-Server auf eine leseanforderung reagieren müssen, bevor Daten an die Clientanwendung zurückgegeben.</span><span class="sxs-lookup"><span data-stu-id="ac510-111">The consistency level specifies how many Cassandra servers must respond to a read request before returning data to the client application.</span></span> <span data-ttu-id="ac510-112">Cassandra überprüft die angegebene Anzahl von Cassandra-Servern für Daten, die leseanforderung zu erfüllen.</span><span class="sxs-lookup"><span data-stu-id="ac510-112">Cassandra checks the specified number of Cassandra servers for data to satisfy the read request.</span></span> <span data-ttu-id="ac510-113">Dabei muss es sich um eine der CassandraSourceReadConsistencyLevels sein.</span><span class="sxs-lookup"><span data-stu-id="ac510-113">Must be one of cassandraSourceReadConsistencyLevels.</span></span> <span data-ttu-id="ac510-114">Der Standardwert ist "1".</span><span class="sxs-lookup"><span data-stu-id="ac510-114">The default value is 'ONE'.</span></span> <span data-ttu-id="ac510-115">Es wird die Groß-/Kleinschreibung.</span><span class="sxs-lookup"><span data-stu-id="ac510-115">It is case-insensitive.</span></span> <span data-ttu-id="ac510-116">Folgende Werte sind möglich: "Alle", "EACH_QUORUM", "QUORUM", 'LOCAL_QUORUM', 'ONE', "2", "Drei", "LOCAL_ONE", "Seriell", "LOCAL_SERIAL"</span><span class="sxs-lookup"><span data-stu-id="ac510-116">Possible values include: 'ALL', 'EACH_QUORUM', 'QUORUM', 'LOCAL_QUORUM', 'ONE', 'TWO', 'THREE', 'LOCAL_ONE', 'SERIAL', 'LOCAL_SERIAL'</span></span></param>
        <summary>
            <span data-ttu-id="ac510-117">Initialisiert eine neue Instanz der CassandraSource-Klasse.</span><span class="sxs-lookup"><span data-stu-id="ac510-117">Initializes a new instance of the CassandraSource class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ConsistencyLevel">
      <MemberSignature Language="C#" Value="public string ConsistencyLevel { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ConsistencyLevel" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.CassandraSource.ConsistencyLevel" />
      <MemberSignature Language="VB.NET" Value="Public Property ConsistencyLevel As String" />
      <MemberSignature Language="F#" Value="member this.ConsistencyLevel : string with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.CassandraSource.ConsistencyLevel" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="consistencyLevel")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="ac510-118">Ruft ab oder legt die konsistenzebene gibt an, wie viele Cassandra-Server auf eine leseanforderung reagieren müssen, bevor Daten an die Clientanwendung zurückgegeben.</span><span class="sxs-lookup"><span data-stu-id="ac510-118">Gets or sets the consistency level specifies how many Cassandra servers must respond to a read request before returning data to the client application.</span></span> <span data-ttu-id="ac510-119">Cassandra überprüft die angegebene Anzahl von Cassandra-Servern für Daten, die leseanforderung zu erfüllen.</span><span class="sxs-lookup"><span data-stu-id="ac510-119">Cassandra checks the specified number of Cassandra servers for data to satisfy the read request.</span></span> <span data-ttu-id="ac510-120">Dabei muss es sich um eine der CassandraSourceReadConsistencyLevels sein.</span><span class="sxs-lookup"><span data-stu-id="ac510-120">Must be one of cassandraSourceReadConsistencyLevels.</span></span> <span data-ttu-id="ac510-121">Der Standardwert ist "1".</span><span class="sxs-lookup"><span data-stu-id="ac510-121">The default value is 'ONE'.</span></span> <span data-ttu-id="ac510-122">Es wird die Groß-/Kleinschreibung.</span><span class="sxs-lookup"><span data-stu-id="ac510-122">It is case-insensitive.</span></span> <span data-ttu-id="ac510-123">Folgende Werte sind möglich: "Alle", "EACH_QUORUM", "QUORUM", 'LOCAL_QUORUM', 'ONE', "2", "Drei", "LOCAL_ONE", "Seriell", "LOCAL_SERIAL"</span><span class="sxs-lookup"><span data-stu-id="ac510-123">Possible values include: 'ALL', 'EACH_QUORUM', 'QUORUM', 'LOCAL_QUORUM', 'ONE', 'TWO', 'THREE', 'LOCAL_ONE', 'SERIAL', 'LOCAL_SERIAL'</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Query">
      <MemberSignature Language="C#" Value="public object Query { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance object Query" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.CassandraSource.Query" />
      <MemberSignature Language="VB.NET" Value="Public Property Query As Object" />
      <MemberSignature Language="F#" Value="member this.Query : obj with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.CassandraSource.Query" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="query")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Object</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="ac510-124">Ruft ab, oder legt die Datenbankabfrage fest.</span><span class="sxs-lookup"><span data-stu-id="ac510-124">Gets or sets database query.</span></span> <span data-ttu-id="ac510-125">Sollte es sich um eine SQL-92-Ausdruck oder einen Befehl für Cassandra Query Language (CQL) sein.</span><span class="sxs-lookup"><span data-stu-id="ac510-125">Should be a SQL-92 query expression or Cassandra Query Language (CQL) command.</span></span> <span data-ttu-id="ac510-126">Typ: Zeichenfolge (oder Ausdruck mit ResultType-Zeichenfolge).</span><span class="sxs-lookup"><span data-stu-id="ac510-126">Type: string (or Expression with resultType string).</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>