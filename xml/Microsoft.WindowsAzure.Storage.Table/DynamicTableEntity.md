<Type Name="DynamicTableEntity" FullName="Microsoft.WindowsAzure.Storage.Table.DynamicTableEntity">
  <TypeSignature Language="C#" Value="public sealed class DynamicTableEntity : Microsoft.WindowsAzure.Storage.Table.ITableEntity" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit DynamicTableEntity extends System.Object implements class Microsoft.WindowsAzure.Storage.Table.ITableEntity" />
  <TypeSignature Language="DocId" Value="T:Microsoft.WindowsAzure.Storage.Table.DynamicTableEntity" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class DynamicTableEntity&#xA;Implements ITableEntity" />
  <TypeSignature Language="F#" Value="type DynamicTableEntity = class&#xA;    interface ITableEntity" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
    <AssemblyVersion>8.4.0.0</AssemblyVersion>
    <AssemblyVersion>8.7.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces>
    <Interface>
      <InterfaceName>Microsoft.WindowsAzure.Storage.Table.ITableEntity</InterfaceName>
    </Interface>
  </Interfaces>
  <Docs>
    <summary>
            <span data-ttu-id="82a3a-101">Ein <see cref="T:Microsoft.WindowsAzure.Storage.Table.ITableEntity" /> Typ, der Aufrufern den direkten Zugriff auf die eigenschaftszuordnung der Entität ermöglicht.</span><span class="sxs-lookup"><span data-stu-id="82a3a-101">A <see cref="T:Microsoft.WindowsAzure.Storage.Table.ITableEntity" /> type which allows callers direct access to the property map of the entity.</span></span> <span data-ttu-id="82a3a-102">Diese Klasse erübrigt die Verwendung von Reflektion für die Serialisierung und Deserialisierung.</span><span class="sxs-lookup"><span data-stu-id="82a3a-102">This class eliminates the use of reflection for serialization and deserialization.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public DynamicTableEntity ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Table.DynamicTableEntity.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="82a3a-103">Initialisiert eine neue Instanz der <see cref="T:Microsoft.WindowsAzure.Storage.Table.DynamicTableEntity" />-Klasse.</span><span class="sxs-lookup"><span data-stu-id="82a3a-103">Initializes a new instance of the <see cref="T:Microsoft.WindowsAzure.Storage.Table.DynamicTableEntity" /> class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public DynamicTableEntity (string partitionKey, string rowKey);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string partitionKey, string rowKey) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Table.DynamicTableEntity.#ctor(System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (partitionKey As String, rowKey As String)" />
      <MemberSignature Language="F#" Value="new Microsoft.WindowsAzure.Storage.Table.DynamicTableEntity : string * string -&gt; Microsoft.WindowsAzure.Storage.Table.DynamicTableEntity" Usage="new Microsoft.WindowsAzure.Storage.Table.DynamicTableEntity (partitionKey, rowKey)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="partitionKey" Type="System.String" />
        <Parameter Name="rowKey" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="partitionKey"><span data-ttu-id="82a3a-104">Eine Zeichenfolge mit dem partitionsschlüsselwert für die Entität.</span><span class="sxs-lookup"><span data-stu-id="82a3a-104">A string containing the partition key value for the entity.</span></span></param>
        <param name="rowKey"><span data-ttu-id="82a3a-105">Eine Zeichenfolge mit dem zeilenschlüsselwert für die Entität.</span><span class="sxs-lookup"><span data-stu-id="82a3a-105">A string containing the row key value for the entity.</span></span></param>
        <summary>
            <span data-ttu-id="82a3a-106">Initialisiert eine neue Instanz der dem <see cref="T:Microsoft.WindowsAzure.Storage.Table.DynamicTableEntity" /> Klasse mit dem angegebenen Partitionsschlüssel und Zeilenschlüssel.</span><span class="sxs-lookup"><span data-stu-id="82a3a-106">Initializes a new instance of the <see cref="T:Microsoft.WindowsAzure.Storage.Table.DynamicTableEntity" /> class with the specified partition key and row key.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public DynamicTableEntity (string partitionKey, string rowKey, string etag, System.Collections.Generic.IDictionary&lt;string,Microsoft.WindowsAzure.Storage.Table.EntityProperty&gt; properties);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string partitionKey, string rowKey, string etag, class System.Collections.Generic.IDictionary`2&lt;string, class Microsoft.WindowsAzure.Storage.Table.EntityProperty&gt; properties) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Table.DynamicTableEntity.#ctor(System.String,System.String,System.String,System.Collections.Generic.IDictionary{System.String,Microsoft.WindowsAzure.Storage.Table.EntityProperty})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (partitionKey As String, rowKey As String, etag As String, properties As IDictionary(Of String, EntityProperty))" />
      <MemberSignature Language="F#" Value="new Microsoft.WindowsAzure.Storage.Table.DynamicTableEntity : string * string * string * System.Collections.Generic.IDictionary&lt;string, Microsoft.WindowsAzure.Storage.Table.EntityProperty&gt; -&gt; Microsoft.WindowsAzure.Storage.Table.DynamicTableEntity" Usage="new Microsoft.WindowsAzure.Storage.Table.DynamicTableEntity (partitionKey, rowKey, etag, properties)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="partitionKey" Type="System.String" />
        <Parameter Name="rowKey" Type="System.String" />
        <Parameter Name="etag" Type="System.String" />
        <Parameter Name="properties" Type="System.Collections.Generic.IDictionary&lt;System.String,Microsoft.WindowsAzure.Storage.Table.EntityProperty&gt;" />
      </Parameters>
      <Docs>
        <param name="partitionKey"><span data-ttu-id="82a3a-107">Eine Zeichenfolge mit dem partitionsschlüsselwert für die Entität.</span><span class="sxs-lookup"><span data-stu-id="82a3a-107">A string containing the partition key value for the entity.</span></span></param>
        <param name="rowKey"><span data-ttu-id="82a3a-108">Eine Zeichenfolge mit dem zeilenschlüsselwert für die Entität.</span><span class="sxs-lookup"><span data-stu-id="82a3a-108">A string containing the row key value for the entity.</span></span></param>
        <param name="etag"><span data-ttu-id="82a3a-109">Eine Zeichenfolge, die das ETag für die Entität enthält.</span><span class="sxs-lookup"><span data-stu-id="82a3a-109">A string containing the ETag for the entity.</span></span></param>
        <param name="properties"><span data-ttu-id="82a3a-110">Ein <see cref="T:System.Collections.Generic.IDictionary`2" /> Objekt mit Eigenschaften der Entität nach Eigenschaftsnamen indiziert.</span><span class="sxs-lookup"><span data-stu-id="82a3a-110">An <see cref="T:System.Collections.Generic.IDictionary`2" /> object containing the entity's properties, indexed by property name.</span></span></param>
        <summary>
            <span data-ttu-id="82a3a-111">Initialisiert eine neue Instanz der dem <see cref="T:Microsoft.WindowsAzure.Storage.Table.DynamicTableEntity" /> Klasse mit dem Partitionsschlüssel, Zeilenschlüssel, ETag (wenn verfügbar, erforderlich) und Eigenschaften der Entität.</span><span class="sxs-lookup"><span data-stu-id="82a3a-111">Initializes a new instance of the <see cref="T:Microsoft.WindowsAzure.Storage.Table.DynamicTableEntity" /> class with the entity's partition key, row key, ETag (if available/required), and properties.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ETag">
      <MemberSignature Language="C#" Value="public string ETag { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ETag" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.Table.DynamicTableEntity.ETag" />
      <MemberSignature Language="VB.NET" Value="Public Property ETag As String" />
      <MemberSignature Language="F#" Value="member this.ETag : string with get, set" Usage="Microsoft.WindowsAzure.Storage.Table.DynamicTableEntity.ETag" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:Microsoft.WindowsAzure.Storage.Table.ITableEntity.ETag</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="82a3a-112">Ruft ab oder legt das aktuelle ETag der Entität.</span><span class="sxs-lookup"><span data-stu-id="82a3a-112">Gets or sets the entity's current ETag.</span></span>
            </summary>
        <value><span data-ttu-id="82a3a-113">Eine Zeichenfolge, die das ETag für die Entität enthält.</span><span class="sxs-lookup"><span data-stu-id="82a3a-113">A string containing the ETag for the entity.</span></span></value>
        <remarks><span data-ttu-id="82a3a-114">Legen Sie diesen Wert auf "\*" auf eine Entität als Teil eines Updatevorgangs Blind zu überschreiben.</span><span class="sxs-lookup"><span data-stu-id="82a3a-114">Set this value to '\*' to blindly overwrite an entity as part of an update operation.</span></span></remarks>
      </Docs>
    </Member>
    <Member MemberName="Item">
      <MemberSignature Language="C#" Value="public Microsoft.WindowsAzure.Storage.Table.EntityProperty this[string key] { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.WindowsAzure.Storage.Table.EntityProperty Item(string)" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.Table.DynamicTableEntity.Item(System.String)" />
      <MemberSignature Language="VB.NET" Value="Default Public Property Item(key As String) As EntityProperty" />
      <MemberSignature Language="F#" Value="member this.Item(string) : Microsoft.WindowsAzure.Storage.Table.EntityProperty with get, set" Usage="Microsoft.WindowsAzure.Storage.Table.DynamicTableEntity.Item" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Storage.Table.EntityProperty</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="key" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="key"><span data-ttu-id="82a3a-115">Eine Zeichenfolge, die mit dem Namen der Eigenschaft.</span><span class="sxs-lookup"><span data-stu-id="82a3a-115">A string containing the name of the property.</span></span></param>
        <summary>
            <span data-ttu-id="82a3a-116">Ruft ab oder legt die Entitätseigenschaft erhält den Namen der Eigenschaft.</span><span class="sxs-lookup"><span data-stu-id="82a3a-116">Gets or sets the entity's property, given the name of the property.</span></span>
            </summary>
        <value><span data-ttu-id="82a3a-117">Ein <see cref="T:Microsoft.WindowsAzure.Storage.Table.EntityProperty" />-Objekt.</span><span class="sxs-lookup"><span data-stu-id="82a3a-117">An <see cref="T:Microsoft.WindowsAzure.Storage.Table.EntityProperty" /> object.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PartitionKey">
      <MemberSignature Language="C#" Value="public string PartitionKey { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string PartitionKey" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.Table.DynamicTableEntity.PartitionKey" />
      <MemberSignature Language="VB.NET" Value="Public Property PartitionKey As String" />
      <MemberSignature Language="F#" Value="member this.PartitionKey : string with get, set" Usage="Microsoft.WindowsAzure.Storage.Table.DynamicTableEntity.PartitionKey" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:Microsoft.WindowsAzure.Storage.Table.ITableEntity.PartitionKey</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="82a3a-118">Ruft ab, oder legt ihn fest Partitionsschlüssel der Entität.</span><span class="sxs-lookup"><span data-stu-id="82a3a-118">Gets or sets the entity's partition key.</span></span>
            </summary>
        <value><span data-ttu-id="82a3a-119">Eine Zeichenfolge mit dem partitionsschlüsselwert für die Entität.</span><span class="sxs-lookup"><span data-stu-id="82a3a-119">A string containing the partition key value for the entity.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Properties">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IDictionary&lt;string,Microsoft.WindowsAzure.Storage.Table.EntityProperty&gt; Properties { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IDictionary`2&lt;string, class Microsoft.WindowsAzure.Storage.Table.EntityProperty&gt; Properties" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.Table.DynamicTableEntity.Properties" />
      <MemberSignature Language="VB.NET" Value="Public Property Properties As IDictionary(Of String, EntityProperty)" />
      <MemberSignature Language="F#" Value="member this.Properties : System.Collections.Generic.IDictionary&lt;string, Microsoft.WindowsAzure.Storage.Table.EntityProperty&gt; with get, set" Usage="Microsoft.WindowsAzure.Storage.Table.DynamicTableEntity.Properties" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IDictionary&lt;System.String,Microsoft.WindowsAzure.Storage.Table.EntityProperty&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="82a3a-120">Ruft ab oder legt die Eigenschaften in der Tabellenentität nach Eigenschaftsname indiziert.</span><span class="sxs-lookup"><span data-stu-id="82a3a-120">Gets or sets the properties in the table entity, indexed by property name.</span></span>
            </summary>
        <value><span data-ttu-id="82a3a-121">Ein <see cref="T:System.Collections.Generic.IDictionary`2" /> Objekt, das die Eigenschaften der Entität enthält.</span><span class="sxs-lookup"><span data-stu-id="82a3a-121">An <see cref="T:System.Collections.Generic.IDictionary`2" /> object containing the entity's properties.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ReadEntity">
      <MemberSignature Language="C#" Value="public void ReadEntity (System.Collections.Generic.IDictionary&lt;string,Microsoft.WindowsAzure.Storage.Table.EntityProperty&gt; properties, Microsoft.WindowsAzure.Storage.OperationContext operationContext);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void ReadEntity(class System.Collections.Generic.IDictionary`2&lt;string, class Microsoft.WindowsAzure.Storage.Table.EntityProperty&gt; properties, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Table.DynamicTableEntity.ReadEntity(System.Collections.Generic.IDictionary{System.String,Microsoft.WindowsAzure.Storage.Table.EntityProperty},Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="abstract member ReadEntity : System.Collections.Generic.IDictionary&lt;string, Microsoft.WindowsAzure.Storage.Table.EntityProperty&gt; * Microsoft.WindowsAzure.Storage.OperationContext -&gt; unit&#xA;override this.ReadEntity : System.Collections.Generic.IDictionary&lt;string, Microsoft.WindowsAzure.Storage.Table.EntityProperty&gt; * Microsoft.WindowsAzure.Storage.OperationContext -&gt; unit" Usage="dynamicTableEntity.ReadEntity (properties, operationContext)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.WindowsAzure.Storage.Table.ITableEntity.ReadEntity(System.Collections.Generic.IDictionary{System.String,Microsoft.WindowsAzure.Storage.Table.EntityProperty},Microsoft.WindowsAzure.Storage.OperationContext)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="properties" Type="System.Collections.Generic.IDictionary&lt;System.String,Microsoft.WindowsAzure.Storage.Table.EntityProperty&gt;" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="properties"><span data-ttu-id="82a3a-122">Eine Auflistung mit den <see cref="T:System.Collections.Generic.IDictionary`2" /> der zeichenfolgeneigenschaftsnamen zu Werten vom Typ zugeordnet <see cref="T:Microsoft.WindowsAzure.Storage.Table.EntityProperty" /> zum Speichern von in diesem <see cref="T:Microsoft.WindowsAzure.Storage.Table.DynamicTableEntity" /> Instanz.</span><span class="sxs-lookup"><span data-stu-id="82a3a-122">A collection containing the <see cref="T:System.Collections.Generic.IDictionary`2" /> of string property names mapped to values of type <see cref="T:Microsoft.WindowsAzure.Storage.Table.EntityProperty" /> to store in this <see cref="T:Microsoft.WindowsAzure.Storage.Table.DynamicTableEntity" /> instance.</span></span></param>
        <param name="operationContext"><span data-ttu-id="82a3a-123">Ein <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> -Objekt, das den Kontext für den aktuellen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="82a3a-123">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <summary>
            <span data-ttu-id="82a3a-124">Deserialisiert diese <see cref="T:Microsoft.WindowsAzure.Storage.Table.DynamicTableEntity" /> -Instanz mit dem angegebenen <see cref="T:System.Collections.Generic.IDictionary`2" /> von Eigenschaftsnamen zu Werten vom Typ <see cref="T:Microsoft.WindowsAzure.Storage.Table.EntityProperty" />.</span><span class="sxs-lookup"><span data-stu-id="82a3a-124">Deserializes this <see cref="T:Microsoft.WindowsAzure.Storage.Table.DynamicTableEntity" /> instance using the specified <see cref="T:System.Collections.Generic.IDictionary`2" /> of property names to values of type <see cref="T:Microsoft.WindowsAzure.Storage.Table.EntityProperty" />.</span></span>
            </summary>
        <remarks><span data-ttu-id="82a3a-125">Im Eigenschaftenwörterbuch an die API übergeben werden intern als Verweis, keine Kopie gespeichert.</span><span class="sxs-lookup"><span data-stu-id="82a3a-125">The properties dictionary passed to this API is stored internally as a reference, not a copy.</span></span></remarks>
      </Docs>
    </Member>
    <Member MemberName="RowKey">
      <MemberSignature Language="C#" Value="public string RowKey { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string RowKey" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.Table.DynamicTableEntity.RowKey" />
      <MemberSignature Language="VB.NET" Value="Public Property RowKey As String" />
      <MemberSignature Language="F#" Value="member this.RowKey : string with get, set" Usage="Microsoft.WindowsAzure.Storage.Table.DynamicTableEntity.RowKey" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:Microsoft.WindowsAzure.Storage.Table.ITableEntity.RowKey</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="82a3a-126">Ruft ab, oder legt ihn fest Zeilenschlüssel der Entität.</span><span class="sxs-lookup"><span data-stu-id="82a3a-126">Gets or sets the entity's row key.</span></span>
            </summary>
        <value><span data-ttu-id="82a3a-127">Eine Zeichenfolge mit dem zeilenschlüsselwert für die Entität.</span><span class="sxs-lookup"><span data-stu-id="82a3a-127">A string containing the row key value for the entity.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Timestamp">
      <MemberSignature Language="C#" Value="public DateTimeOffset Timestamp { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.DateTimeOffset Timestamp" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.Table.DynamicTableEntity.Timestamp" />
      <MemberSignature Language="VB.NET" Value="Public Property Timestamp As DateTimeOffset" />
      <MemberSignature Language="F#" Value="member this.Timestamp : DateTimeOffset with get, set" Usage="Microsoft.WindowsAzure.Storage.Table.DynamicTableEntity.Timestamp" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:Microsoft.WindowsAzure.Storage.Table.ITableEntity.Timestamp</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.DateTimeOffset</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="82a3a-128">Ruft ab oder legt den Zeitstempel der Entität.</span><span class="sxs-lookup"><span data-stu-id="82a3a-128">Gets or sets the entity's timestamp.</span></span>
            </summary>
        <value><span data-ttu-id="82a3a-129">Ein <see cref="T:System.DateTimeOffset" /> mit dem Zeitstempel für die Entität.</span><span class="sxs-lookup"><span data-stu-id="82a3a-129">A <see cref="T:System.DateTimeOffset" /> containing the timestamp for the entity.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="WriteEntity">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IDictionary&lt;string,Microsoft.WindowsAzure.Storage.Table.EntityProperty&gt; WriteEntity (Microsoft.WindowsAzure.Storage.OperationContext operationContext);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Collections.Generic.IDictionary`2&lt;string, class Microsoft.WindowsAzure.Storage.Table.EntityProperty&gt; WriteEntity(class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Table.DynamicTableEntity.WriteEntity(Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="abstract member WriteEntity : Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Collections.Generic.IDictionary&lt;string, Microsoft.WindowsAzure.Storage.Table.EntityProperty&gt;&#xA;override this.WriteEntity : Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Collections.Generic.IDictionary&lt;string, Microsoft.WindowsAzure.Storage.Table.EntityProperty&gt;" Usage="dynamicTableEntity.WriteEntity operationContext" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.WindowsAzure.Storage.Table.ITableEntity.WriteEntity(Microsoft.WindowsAzure.Storage.OperationContext)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IDictionary&lt;System.String,Microsoft.WindowsAzure.Storage.Table.EntityProperty&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="operationContext"><span data-ttu-id="82a3a-130">Ein <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> -Objekt, das den Kontext für den aktuellen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="82a3a-130">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <summary>
            <span data-ttu-id="82a3a-131">Serialisiert die <see cref="T:System.Collections.Generic.IDictionary`2" /> von Eigenschaftsnamen zu Werten vom Typ zugeordnet <see cref="T:Microsoft.WindowsAzure.Storage.Table.EntityProperty" /> aus diesem <see cref="T:Microsoft.WindowsAzure.Storage.Table.DynamicTableEntity" /> Instanz.</span><span class="sxs-lookup"><span data-stu-id="82a3a-131">Serializes the <see cref="T:System.Collections.Generic.IDictionary`2" /> of property names mapped to values of type <see cref="T:Microsoft.WindowsAzure.Storage.Table.EntityProperty" /> from this <see cref="T:Microsoft.WindowsAzure.Storage.Table.DynamicTableEntity" /> instance.</span></span>
            </summary>
        <returns><span data-ttu-id="82a3a-132">Ein <see cref="T:System.Collections.Generic.IDictionary`2" /> Objekt mit der Zuordnung der zeichenfolgeneigenschaftsnamen zu Werten vom Typ <see cref="T:Microsoft.WindowsAzure.Storage.Table.EntityProperty" /> gespeichert, die in diesem <see cref="T:Microsoft.WindowsAzure.Storage.Table.DynamicTableEntity" /> Instanz.</span><span class="sxs-lookup"><span data-stu-id="82a3a-132">An <see cref="T:System.Collections.Generic.IDictionary`2" /> object containing the map of string property names to values of type <see cref="T:Microsoft.WindowsAzure.Storage.Table.EntityProperty" /> stored in this <see cref="T:Microsoft.WindowsAzure.Storage.Table.DynamicTableEntity" /> instance.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>