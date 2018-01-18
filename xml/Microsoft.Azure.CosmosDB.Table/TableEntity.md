<Type Name="TableEntity" FullName="Microsoft.Azure.CosmosDB.Table.TableEntity">
  <TypeSignature Language="C#" Value="public class TableEntity : Microsoft.Azure.CosmosDB.Table.ITableEntity" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi TableEntity extends System.Object implements class Microsoft.Azure.CosmosDB.Table.ITableEntity" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.CosmosDB.Table.TableEntity" />
  <TypeSignature Language="VB.NET" Value="Public Class TableEntity&#xA;Implements ITableEntity" />
  <TypeSignature Language="F#" Value="type TableEntity = class&#xA;    interface ITableEntity" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.CosmosDB.Table</AssemblyName>
    <AssemblyVersion>0.9.0.0</AssemblyVersion>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces>
    <Interface>
      <InterfaceName>Microsoft.Azure.CosmosDB.Table.ITableEntity</InterfaceName>
    </Interface>
  </Interfaces>
  <Docs>
    <summary>
            <span data-ttu-id="1942c-101">Stellt den Basisobjekttyp für eine Tabellenentität im Tabellendienst dar.</span><span class="sxs-lookup"><span data-stu-id="1942c-101">Represents the base object type for a table entity in the Table service.</span></span>
            </summary>
    <remarks>
      <span data-ttu-id="1942c-102"><see cref="T:Microsoft.Azure.CosmosDB.Table.TableEntity" />Stellt eine basisimplementierung für die <see cref="T:Microsoft.Azure.CosmosDB.Table.ITableEntity" /> Schnittstelle, bietet <see cref="M:Microsoft.Azure.CosmosDB.Table.TableEntity.ReadEntity(System.Collections.Generic.IDictionary{System.String,Microsoft.Azure.CosmosDB.Table.EntityProperty},Microsoft.Azure.Storage.OperationContext)" /> und <see cref="M:Microsoft.Azure.CosmosDB.Table.TableEntity.WriteEntity(Microsoft.Azure.Storage.OperationContext)" /> Methoden, die standardmäßig serialisieren und Deserialisieren alle Eigenschaften über Reflektion ermöglicht.</span><span class="sxs-lookup"><span data-stu-id="1942c-102"><see cref="T:Microsoft.Azure.CosmosDB.Table.TableEntity" /> provides a base implementation for the <see cref="T:Microsoft.Azure.CosmosDB.Table.ITableEntity" /> interface that provides <see cref="M:Microsoft.Azure.CosmosDB.Table.TableEntity.ReadEntity(System.Collections.Generic.IDictionary{System.String,Microsoft.Azure.CosmosDB.Table.EntityProperty},Microsoft.Azure.Storage.OperationContext)" /> and <see cref="M:Microsoft.Azure.CosmosDB.Table.TableEntity.WriteEntity(Microsoft.Azure.Storage.OperationContext)" /> methods that by default serialize and deserialize all properties via reflection.</span></span> <span data-ttu-id="1942c-103">Eine tabellenentitätsklasse kann diese Klasse erweitert und überschreiben die <see cref="M:Microsoft.Azure.CosmosDB.Table.ITableEntity.ReadEntity(System.Collections.Generic.IDictionary{System.String,Microsoft.Azure.CosmosDB.Table.EntityProperty},Microsoft.Azure.Storage.OperationContext)" /> und <see cref="M:Microsoft.Azure.CosmosDB.Table.ITableEntity.WriteEntity(Microsoft.Azure.Storage.OperationContext)" /> Methoden bieten angepasste oder leistungsstärkere Serialisierungslogik.</span><span class="sxs-lookup"><span data-stu-id="1942c-103">A table entity class may extend this class and override the <see cref="M:Microsoft.Azure.CosmosDB.Table.ITableEntity.ReadEntity(System.Collections.Generic.IDictionary{System.String,Microsoft.Azure.CosmosDB.Table.EntityProperty},Microsoft.Azure.Storage.OperationContext)" /> and <see cref="M:Microsoft.Azure.CosmosDB.Table.ITableEntity.WriteEntity(Microsoft.Azure.Storage.OperationContext)" /> methods to provide customized or better performing serialization logic.</span></span></remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public TableEntity ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.CosmosDB.Table.TableEntity.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.CosmosDB.Table</AssemblyName>
        <AssemblyVersion>0.9.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="1942c-104">Initialisiert eine neue Instanz der <see cref="T:Microsoft.Azure.CosmosDB.Table.TableEntity" />-Klasse.</span><span class="sxs-lookup"><span data-stu-id="1942c-104">Initializes a new instance of the <see cref="T:Microsoft.Azure.CosmosDB.Table.TableEntity" /> class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public TableEntity (string partitionKey, string rowKey);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string partitionKey, string rowKey) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.CosmosDB.Table.TableEntity.#ctor(System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (partitionKey As String, rowKey As String)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.CosmosDB.Table.TableEntity : string * string -&gt; Microsoft.Azure.CosmosDB.Table.TableEntity" Usage="new Microsoft.Azure.CosmosDB.Table.TableEntity (partitionKey, rowKey)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.CosmosDB.Table</AssemblyName>
        <AssemblyVersion>0.9.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="partitionKey" Type="System.String" />
        <Parameter Name="rowKey" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="partitionKey"><span data-ttu-id="1942c-105">Eine Zeichenfolge, die den Partitionsschlüssel der enthält die <see cref="T:Microsoft.Azure.CosmosDB.Table.TableEntity" /> initialisiert werden.</span><span class="sxs-lookup"><span data-stu-id="1942c-105">A string containing the partition key of the <see cref="T:Microsoft.Azure.CosmosDB.Table.TableEntity" /> to be initialized.</span></span></param>
        <param name="rowKey"><span data-ttu-id="1942c-106">Eine Zeichenfolge, die den Zeilenschlüssel der enthält die <see cref="T:Microsoft.Azure.CosmosDB.Table.TableEntity" /> initialisiert werden.</span><span class="sxs-lookup"><span data-stu-id="1942c-106">A string containing the row key of the <see cref="T:Microsoft.Azure.CosmosDB.Table.TableEntity" /> to be initialized.</span></span></param>
        <summary>
            <span data-ttu-id="1942c-107">Initialisiert eine neue Instanz der dem <see cref="T:Microsoft.Azure.CosmosDB.Table.TableEntity" /> Klasse mit dem angegebenen Partitionsschlüssel und Zeilenschlüssel.</span><span class="sxs-lookup"><span data-stu-id="1942c-107">Initializes a new instance of the <see cref="T:Microsoft.Azure.CosmosDB.Table.TableEntity" /> class with the specified partition key and row key.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ConvertBack&lt;TResult&gt;">
      <MemberSignature Language="C#" Value="public static TResult ConvertBack&lt;TResult&gt; (System.Collections.Generic.IDictionary&lt;string,Microsoft.Azure.CosmosDB.Table.EntityProperty&gt; properties, Microsoft.Azure.Storage.OperationContext operationContext);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig !!TResult ConvertBack&lt;TResult&gt;(class System.Collections.Generic.IDictionary`2&lt;string, class Microsoft.Azure.CosmosDB.Table.EntityProperty&gt; properties, class Microsoft.Azure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.CosmosDB.Table.TableEntity.ConvertBack``1(System.Collections.Generic.IDictionary{System.String,Microsoft.Azure.CosmosDB.Table.EntityProperty},Microsoft.Azure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="static member ConvertBack : System.Collections.Generic.IDictionary&lt;string, Microsoft.Azure.CosmosDB.Table.EntityProperty&gt; * Microsoft.Azure.Storage.OperationContext -&gt; 'Result" Usage="Microsoft.Azure.CosmosDB.Table.TableEntity.ConvertBack (properties, operationContext)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.CosmosDB.Table</AssemblyName>
        <AssemblyVersion>0.9.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>TResult</ReturnType>
      </ReturnValue>
      <TypeParameters>
        <TypeParameter Name="TResult" />
      </TypeParameters>
      <Parameters>
        <Parameter Name="properties" Type="System.Collections.Generic.IDictionary&lt;System.String,Microsoft.Azure.CosmosDB.Table.EntityProperty&gt;" />
        <Parameter Name="operationContext" Type="Microsoft.Azure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <typeparam name="TResult"><span data-ttu-id="1942c-108">Der Typ des recomposed-Objekts.</span><span class="sxs-lookup"><span data-stu-id="1942c-108">The type of the recomposed object.</span></span> <span data-ttu-id="1942c-109">Dies kann ein einfaches Objekt mit einer flachen Struktur oder ein komplexes Objekt komplexe Eigenschaften, die mit mehreren Ebenen der Objekthierarchie sein.</span><span class="sxs-lookup"><span data-stu-id="1942c-109">This can be a simple object with a flat structure or a complex object with complex properties and multiple levels of object hierarchy.</span></span></typeparam>
        <param name="properties"><span data-ttu-id="1942c-110">Ein <see cref="T:System.Collections.Generic.IDictionary`2" /> zuordnet, die zu verwendenden Objektnamen <see cref="T:Microsoft.Azure.CosmosDB.Table.EntityProperty" /> Datenwerte deserialisiert und gespeichert, die in dieser tabellenentitätsinstanz.</span><span class="sxs-lookup"><span data-stu-id="1942c-110">An <see cref="T:System.Collections.Generic.IDictionary`2" /> object that maps string property names to <see cref="T:Microsoft.Azure.CosmosDB.Table.EntityProperty" /> data values to deserialize and store in this table entity instance.</span></span></param>
        <param name="operationContext"><span data-ttu-id="1942c-111">Ein <see cref="T:Microsoft.Azure.Storage.OperationContext" /> -Objekt, das den Kontext für den aktuellen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="1942c-111">An <see cref="T:Microsoft.Azure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <summary>
            <span data-ttu-id="1942c-112">Gibt eine benutzerdefinierte Entitätsinstanz, die neu aufgebaut wird unter Verwendung des angegebenen <see cref="T:System.Collections.Generic.IDictionary`2" /> von Eigenschaftsnamen für <see cref="T:Microsoft.Azure.CosmosDB.Table.EntityProperty" /> -Datentypwerte.</span><span class="sxs-lookup"><span data-stu-id="1942c-112">Returns a custom entity instance which is recomposed using the specified <see cref="T:System.Collections.Generic.IDictionary`2" /> of property names to <see cref="T:Microsoft.Azure.CosmosDB.Table.EntityProperty" /> data typed values.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ConvertBack&lt;TResult&gt;">
      <MemberSignature Language="C#" Value="public static TResult ConvertBack&lt;TResult&gt; (System.Collections.Generic.IDictionary&lt;string,Microsoft.Azure.CosmosDB.Table.EntityProperty&gt; properties, Microsoft.Azure.CosmosDB.Table.EntityPropertyConverterOptions entityPropertyConverterOptions, Microsoft.Azure.Storage.OperationContext operationContext);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig !!TResult ConvertBack&lt;TResult&gt;(class System.Collections.Generic.IDictionary`2&lt;string, class Microsoft.Azure.CosmosDB.Table.EntityProperty&gt; properties, class Microsoft.Azure.CosmosDB.Table.EntityPropertyConverterOptions entityPropertyConverterOptions, class Microsoft.Azure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.CosmosDB.Table.TableEntity.ConvertBack``1(System.Collections.Generic.IDictionary{System.String,Microsoft.Azure.CosmosDB.Table.EntityProperty},Microsoft.Azure.CosmosDB.Table.EntityPropertyConverterOptions,Microsoft.Azure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="static member ConvertBack : System.Collections.Generic.IDictionary&lt;string, Microsoft.Azure.CosmosDB.Table.EntityProperty&gt; * Microsoft.Azure.CosmosDB.Table.EntityPropertyConverterOptions * Microsoft.Azure.Storage.OperationContext -&gt; 'Result" Usage="Microsoft.Azure.CosmosDB.Table.TableEntity.ConvertBack (properties, entityPropertyConverterOptions, operationContext)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.CosmosDB.Table</AssemblyName>
        <AssemblyVersion>0.9.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>TResult</ReturnType>
      </ReturnValue>
      <TypeParameters>
        <TypeParameter Name="TResult" />
      </TypeParameters>
      <Parameters>
        <Parameter Name="properties" Type="System.Collections.Generic.IDictionary&lt;System.String,Microsoft.Azure.CosmosDB.Table.EntityProperty&gt;" />
        <Parameter Name="entityPropertyConverterOptions" Type="Microsoft.Azure.CosmosDB.Table.EntityPropertyConverterOptions" />
        <Parameter Name="operationContext" Type="Microsoft.Azure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <typeparam name="TResult"><span data-ttu-id="1942c-113">Der Typ des recomposed-Objekts.</span><span class="sxs-lookup"><span data-stu-id="1942c-113">The type of the recomposed object.</span></span> <span data-ttu-id="1942c-114">Dies kann ein einfaches Objekt mit einer flachen Struktur oder ein komplexes Objekt komplexe Eigenschaften, die mit mehreren Ebenen der Objekthierarchie sein.</span><span class="sxs-lookup"><span data-stu-id="1942c-114">This can be a simple object with a flat structure or a complex object with complex properties and multiple levels of object hierarchy.</span></span></typeparam>
        <param name="properties"><span data-ttu-id="1942c-115">Ein <see cref="T:System.Collections.Generic.IDictionary`2" /> zuordnet, die zu verwendenden Objektnamen <see cref="T:Microsoft.Azure.CosmosDB.Table.EntityProperty" /> Datenwerte deserialisiert und gespeichert, die in dieser tabellenentitätsinstanz.</span><span class="sxs-lookup"><span data-stu-id="1942c-115">An <see cref="T:System.Collections.Generic.IDictionary`2" /> object that maps string property names to <see cref="T:Microsoft.Azure.CosmosDB.Table.EntityProperty" /> data values to deserialize and store in this table entity instance.</span></span></param>
        <param name="entityPropertyConverterOptions"><span data-ttu-id="1942c-116">Ein <see cref="T:Microsoft.Azure.CosmosDB.Table.EntityPropertyConverterOptions" /> -Objekt, das Optionen für die Konvertierung der Entität-Eigenschaft angibt.</span><span class="sxs-lookup"><span data-stu-id="1942c-116">A <see cref="T:Microsoft.Azure.CosmosDB.Table.EntityPropertyConverterOptions" /> object that specifies options for the entity property conversion.</span></span></param>
        <param name="operationContext"><span data-ttu-id="1942c-117">Ein <see cref="T:Microsoft.Azure.Storage.OperationContext" /> -Objekt, das den Kontext für den aktuellen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="1942c-117">An <see cref="T:Microsoft.Azure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <summary>
            <span data-ttu-id="1942c-118">Gibt eine benutzerdefinierte Entitätsinstanz, die neu aufgebaut wird unter Verwendung des angegebenen <see cref="T:System.Collections.Generic.IDictionary`2" /> von Eigenschaftsnamen für <see cref="T:Microsoft.Azure.CosmosDB.Table.EntityProperty" /> -Datentypwerte.</span><span class="sxs-lookup"><span data-stu-id="1942c-118">Returns a custom entity instance which is recomposed using the specified <see cref="T:System.Collections.Generic.IDictionary`2" /> of property names to <see cref="T:Microsoft.Azure.CosmosDB.Table.EntityProperty" /> data typed values.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DisableCompiledSerializers">
      <MemberSignature Language="C#" Value="public static bool DisableCompiledSerializers { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property bool DisableCompiledSerializers" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.CosmosDB.Table.TableEntity.DisableCompiledSerializers" />
      <MemberSignature Language="VB.NET" Value="Public Shared Property DisableCompiledSerializers As Boolean" />
      <MemberSignature Language="F#" Value="member this.DisableCompiledSerializers : bool with get, set" Usage="Microsoft.Azure.CosmosDB.Table.TableEntity.DisableCompiledSerializers" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.CosmosDB.Table</AssemblyName>
        <AssemblyVersion>0.9.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="1942c-119">Deaktiviert die Fähigkeit zum dynamischen Generieren von lesen und Schreiben von Lambdas zur Laufzeit.</span><span class="sxs-lookup"><span data-stu-id="1942c-119">Disables the ability to dynamically generate read and write lambdas at runtime.</span></span> <span data-ttu-id="1942c-120">Diese Einstellung auf "false" festgelegt wird, allen Typinstanzen, die von TableEntity abgeleitet werden gemeinsam genutzte statischen Cache gelöscht.</span><span class="sxs-lookup"><span data-stu-id="1942c-120">Setting this to false will clear out the static cache shared across all type instances that derive from TableEntity.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DisablePropertyResolverCache">
      <MemberSignature Language="C#" Value="public static bool DisablePropertyResolverCache { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property bool DisablePropertyResolverCache" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.CosmosDB.Table.TableEntity.DisablePropertyResolverCache" />
      <MemberSignature Language="VB.NET" Value="Public Shared Property DisablePropertyResolverCache As Boolean" />
      <MemberSignature Language="F#" Value="member this.DisablePropertyResolverCache : bool with get, set" Usage="Microsoft.Azure.CosmosDB.Table.TableEntity.DisablePropertyResolverCache" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.CosmosDB.Table</AssemblyName>
        <AssemblyVersion>0.9.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="1942c-121">Ruft ab oder legt den Status der Eigenschaftencache Konfliktlöser für die <see cref="T:Microsoft.Azure.CosmosDB.Table.TableEntity" />.</span><span class="sxs-lookup"><span data-stu-id="1942c-121">Gets or sets the status of the property resolver cache for the <see cref="T:Microsoft.Azure.CosmosDB.Table.TableEntity" />.</span></span> 
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="1942c-122">Der Konfliktlöser Eigenschaftencache zwischenspeichert bekannte Entitätstypen und ihre jeweiligen Konfliktlöser Wörterbücher, wenn Entitäten deserialisiert werden, und die Nutzlast enthält keine JSON-Metadaten.</span><span class="sxs-lookup"><span data-stu-id="1942c-122">The property resolver cache caches known entity types and their respective property resolver dictionaries when entities are deserialized and the payload does not include JSON metadata.</span></span> <span data-ttu-id="1942c-123">In den meisten Szenarien wird das Deaktivieren der Konfliktlöser Eigenschaftencache aufgrund seiner Effekte auf die Leistung nicht empfohlen.</span><span class="sxs-lookup"><span data-stu-id="1942c-123">For most scenarios, disabling the property resolver cache is not recommended due to its effect on performance.</span></span> 
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ETag">
      <MemberSignature Language="C#" Value="public string ETag { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ETag" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.CosmosDB.Table.TableEntity.ETag" />
      <MemberSignature Language="VB.NET" Value="Public Property ETag As String" />
      <MemberSignature Language="F#" Value="member this.ETag : string with get, set" Usage="Microsoft.Azure.CosmosDB.Table.TableEntity.ETag" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:Microsoft.Azure.CosmosDB.Table.ITableEntity.ETag</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.CosmosDB.Table</AssemblyName>
        <AssemblyVersion>0.9.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="1942c-124">Ruft ab oder legt das ETag der Entität.</span><span class="sxs-lookup"><span data-stu-id="1942c-124">Gets or sets the entity's ETag.</span></span> <span data-ttu-id="1942c-125">Legen Sie diesen Wert auf "\*" zum Überschreiben einer Entität als Teil eines Updatevorgangs zu erzwingen.</span><span class="sxs-lookup"><span data-stu-id="1942c-125">Set this value to '\*' in order to force an overwrite to an entity as part of an update operation.</span></span>
            </summary>
        <value><span data-ttu-id="1942c-126">Eine Zeichenfolge mit dem ETag-Wert für die Entität.</span><span class="sxs-lookup"><span data-stu-id="1942c-126">A string containing the ETag value for the entity.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Flatten">
      <MemberSignature Language="C#" Value="public static System.Collections.Generic.IDictionary&lt;string,Microsoft.Azure.CosmosDB.Table.EntityProperty&gt; Flatten (object entity, Microsoft.Azure.Storage.OperationContext operationContext);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Collections.Generic.IDictionary`2&lt;string, class Microsoft.Azure.CosmosDB.Table.EntityProperty&gt; Flatten(object entity, class Microsoft.Azure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.CosmosDB.Table.TableEntity.Flatten(System.Object,Microsoft.Azure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="static member Flatten : obj * Microsoft.Azure.Storage.OperationContext -&gt; System.Collections.Generic.IDictionary&lt;string, Microsoft.Azure.CosmosDB.Table.EntityProperty&gt;" Usage="Microsoft.Azure.CosmosDB.Table.TableEntity.Flatten (entity, operationContext)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.CosmosDB.Table</AssemblyName>
        <AssemblyVersion>0.9.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IDictionary&lt;System.String,Microsoft.Azure.CosmosDB.Table.EntityProperty&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="entity" Type="System.Object" />
        <Parameter Name="operationContext" Type="Microsoft.Azure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="entity"><span data-ttu-id="1942c-127">Das zu serialisierende Entitätsobjekt.</span><span class="sxs-lookup"><span data-stu-id="1942c-127">The entity object to serialize.</span></span></param>
        <param name="operationContext"><span data-ttu-id="1942c-128">Ein <see cref="T:Microsoft.Azure.Storage.OperationContext" /> -Objekt, das den Kontext für den aktuellen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="1942c-128">An <see cref="T:Microsoft.Azure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <summary>
            <span data-ttu-id="1942c-129">Fasst die Entität und erstellt eine <see cref="T:System.Collections.Generic.IDictionary`2" /> von <see cref="T:Microsoft.Azure.CosmosDB.Table.EntityProperty" /> Objekte für alle Eigenschaften des angegebenen Entitätsobjekts.</span><span class="sxs-lookup"><span data-stu-id="1942c-129">Flattens the entity and creates a <see cref="T:System.Collections.Generic.IDictionary`2" /> of <see cref="T:Microsoft.Azure.CosmosDB.Table.EntityProperty" /> objects for all properties of the specified entity object.</span></span>
            </summary>
        <returns><span data-ttu-id="1942c-130">Ein <see cref="T:System.Collections.Generic.IDictionary`2" /> von <see cref="T:Microsoft.Azure.CosmosDB.Table.EntityProperty" /> Objekte für alle Eigenschaften des angegebenen Entitätsobjekts.</span><span class="sxs-lookup"><span data-stu-id="1942c-130">An <see cref="T:System.Collections.Generic.IDictionary`2" /> of <see cref="T:Microsoft.Azure.CosmosDB.Table.EntityProperty" /> objects for all the properties of the specified entity object.</span></span></returns>
        <remarks><span data-ttu-id="1942c-131">Der Entitätstyp kann ein einfaches Objekt mit einer flachen Struktur oder ein komplexes Objekt komplexe Eigenschaften, die mit mehreren Ebenen der Objekthierarchie.</span><span class="sxs-lookup"><span data-stu-id="1942c-131">The entity type can be a simple object with a flat structure or a complex object with complex properties and multiple levels of object hierarchy.</span></span>
            <span data-ttu-id="1942c-132">Generische ConvertBack-Methode kann die ursprüngliche Entität mithilfe den Rückgabewert dieser Methode neu aufzubauen.</span><span class="sxs-lookup"><span data-stu-id="1942c-132">Generic ConvertBack method can recompose the original entity using the return value of this method.</span></span></remarks>
      </Docs>
    </Member>
    <Member MemberName="Flatten">
      <MemberSignature Language="C#" Value="public static System.Collections.Generic.IDictionary&lt;string,Microsoft.Azure.CosmosDB.Table.EntityProperty&gt; Flatten (object entity, Microsoft.Azure.CosmosDB.Table.EntityPropertyConverterOptions entityPropertyConverterOptions, Microsoft.Azure.Storage.OperationContext operationContext);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Collections.Generic.IDictionary`2&lt;string, class Microsoft.Azure.CosmosDB.Table.EntityProperty&gt; Flatten(object entity, class Microsoft.Azure.CosmosDB.Table.EntityPropertyConverterOptions entityPropertyConverterOptions, class Microsoft.Azure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.CosmosDB.Table.TableEntity.Flatten(System.Object,Microsoft.Azure.CosmosDB.Table.EntityPropertyConverterOptions,Microsoft.Azure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="static member Flatten : obj * Microsoft.Azure.CosmosDB.Table.EntityPropertyConverterOptions * Microsoft.Azure.Storage.OperationContext -&gt; System.Collections.Generic.IDictionary&lt;string, Microsoft.Azure.CosmosDB.Table.EntityProperty&gt;" Usage="Microsoft.Azure.CosmosDB.Table.TableEntity.Flatten (entity, entityPropertyConverterOptions, operationContext)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.CosmosDB.Table</AssemblyName>
        <AssemblyVersion>0.9.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IDictionary&lt;System.String,Microsoft.Azure.CosmosDB.Table.EntityProperty&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="entity" Type="System.Object" />
        <Parameter Name="entityPropertyConverterOptions" Type="Microsoft.Azure.CosmosDB.Table.EntityPropertyConverterOptions" />
        <Parameter Name="operationContext" Type="Microsoft.Azure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="entity"><span data-ttu-id="1942c-133">Das zu serialisierende Entitätsobjekt.</span><span class="sxs-lookup"><span data-stu-id="1942c-133">The entity object to serialize.</span></span></param>
        <param name="entityPropertyConverterOptions"><span data-ttu-id="1942c-134">Ein <see cref="T:Microsoft.Azure.CosmosDB.Table.EntityPropertyConverterOptions" /> -Objekt, das Optionen für die Konvertierung der Entität-Eigenschaft angibt.</span><span class="sxs-lookup"><span data-stu-id="1942c-134">A <see cref="T:Microsoft.Azure.CosmosDB.Table.EntityPropertyConverterOptions" /> object that specifies options for the entity property conversion.</span></span></param>
        <param name="operationContext"><span data-ttu-id="1942c-135">Ein <see cref="T:Microsoft.Azure.Storage.OperationContext" /> -Objekt, das den Kontext für den aktuellen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="1942c-135">An <see cref="T:Microsoft.Azure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <summary>
            <span data-ttu-id="1942c-136">Fasst die Entität und erstellt eine <see cref="T:System.Collections.Generic.IDictionary`2" /> von <see cref="T:Microsoft.Azure.CosmosDB.Table.EntityProperty" /> Objekte für alle Eigenschaften des angegebenen Entitätsobjekts.</span><span class="sxs-lookup"><span data-stu-id="1942c-136">Flattens the entity and creates a <see cref="T:System.Collections.Generic.IDictionary`2" /> of <see cref="T:Microsoft.Azure.CosmosDB.Table.EntityProperty" /> objects for all properties of the specified entity object.</span></span>
            </summary>
        <returns><span data-ttu-id="1942c-137">Ein <see cref="T:System.Collections.Generic.IDictionary`2" /> von <see cref="T:Microsoft.Azure.CosmosDB.Table.EntityProperty" /> Objekte für alle Eigenschaften des angegebenen Entitätsobjekts.</span><span class="sxs-lookup"><span data-stu-id="1942c-137">An <see cref="T:System.Collections.Generic.IDictionary`2" /> of <see cref="T:Microsoft.Azure.CosmosDB.Table.EntityProperty" /> objects for all the properties of the specified entity object.</span></span></returns>
        <remarks><span data-ttu-id="1942c-138">Der Entitätstyp kann ein einfaches Objekt mit einer flachen Struktur oder ein komplexes Objekt komplexe Eigenschaften, die mit mehreren Ebenen der Objekthierarchie.</span><span class="sxs-lookup"><span data-stu-id="1942c-138">The entity type can be a simple object with a flat structure or a complex object with complex properties and multiple levels of object hierarchy.</span></span>
            <span data-ttu-id="1942c-139">Generische ConvertBack-Methode kann die ursprüngliche Entität mithilfe den Rückgabewert dieser Methode neu aufzubauen.</span><span class="sxs-lookup"><span data-stu-id="1942c-139">Generic ConvertBack method can recompose the original entity using the return value of this method.</span></span></remarks>
      </Docs>
    </Member>
    <Member MemberName="PartitionKey">
      <MemberSignature Language="C#" Value="public string PartitionKey { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string PartitionKey" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.CosmosDB.Table.TableEntity.PartitionKey" />
      <MemberSignature Language="VB.NET" Value="Public Property PartitionKey As String" />
      <MemberSignature Language="F#" Value="member this.PartitionKey : string with get, set" Usage="Microsoft.Azure.CosmosDB.Table.TableEntity.PartitionKey" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:Microsoft.Azure.CosmosDB.Table.ITableEntity.PartitionKey</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.CosmosDB.Table</AssemblyName>
        <AssemblyVersion>0.9.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="1942c-140">Ruft ab, oder legt ihn fest Partitionsschlüssel der Entität.</span><span class="sxs-lookup"><span data-stu-id="1942c-140">Gets or sets the entity's partition key.</span></span>
            </summary>
        <value><span data-ttu-id="1942c-141">Eine Zeichenfolge, die den Partitionsschlüssel der Entität enthält.</span><span class="sxs-lookup"><span data-stu-id="1942c-141">A string containing the partition key for the entity.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ReadEntity">
      <MemberSignature Language="C#" Value="public virtual void ReadEntity (System.Collections.Generic.IDictionary&lt;string,Microsoft.Azure.CosmosDB.Table.EntityProperty&gt; properties, Microsoft.Azure.Storage.OperationContext operationContext);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void ReadEntity(class System.Collections.Generic.IDictionary`2&lt;string, class Microsoft.Azure.CosmosDB.Table.EntityProperty&gt; properties, class Microsoft.Azure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.CosmosDB.Table.TableEntity.ReadEntity(System.Collections.Generic.IDictionary{System.String,Microsoft.Azure.CosmosDB.Table.EntityProperty},Microsoft.Azure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="abstract member ReadEntity : System.Collections.Generic.IDictionary&lt;string, Microsoft.Azure.CosmosDB.Table.EntityProperty&gt; * Microsoft.Azure.Storage.OperationContext -&gt; unit&#xA;override this.ReadEntity : System.Collections.Generic.IDictionary&lt;string, Microsoft.Azure.CosmosDB.Table.EntityProperty&gt; * Microsoft.Azure.Storage.OperationContext -&gt; unit" Usage="tableEntity.ReadEntity (properties, operationContext)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.Azure.CosmosDB.Table.ITableEntity.ReadEntity(System.Collections.Generic.IDictionary{System.String,Microsoft.Azure.CosmosDB.Table.EntityProperty},Microsoft.Azure.Storage.OperationContext)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.CosmosDB.Table</AssemblyName>
        <AssemblyVersion>0.9.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="properties" Type="System.Collections.Generic.IDictionary&lt;System.String,Microsoft.Azure.CosmosDB.Table.EntityProperty&gt;" />
        <Parameter Name="operationContext" Type="Microsoft.Azure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="properties"><span data-ttu-id="1942c-142">Ein <see cref="T:System.Collections.Generic.IDictionary`2" /> -Objekt, das eigenschaftenzuordnungen benennt typisierten <see cref="T:Microsoft.Azure.CosmosDB.Table.EntityProperty" /> Werte.</span><span class="sxs-lookup"><span data-stu-id="1942c-142">An <see cref="T:System.Collections.Generic.IDictionary`2" /> object that maps property names to typed <see cref="T:Microsoft.Azure.CosmosDB.Table.EntityProperty" /> values.</span></span></param>
        <param name="operationContext"><span data-ttu-id="1942c-143">Ein <see cref="T:Microsoft.Azure.Storage.OperationContext" /> -Objekt, das den Kontext für den aktuellen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="1942c-143">An <see cref="T:Microsoft.Azure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <summary>
            <span data-ttu-id="1942c-144">Deserialisiert die Entität mit dem angegebenen <see cref="T:System.Collections.Generic.IDictionary`2" /> ordnet Eigenschaftsnamen typisierten <see cref="T:Microsoft.Azure.CosmosDB.Table.EntityProperty" /> Werte.</span><span class="sxs-lookup"><span data-stu-id="1942c-144">Deserializes the entity using the specified <see cref="T:System.Collections.Generic.IDictionary`2" /> that maps property names to typed <see cref="T:Microsoft.Azure.CosmosDB.Table.EntityProperty" /> values.</span></span> 
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ReadUserObject">
      <MemberSignature Language="C#" Value="public static void ReadUserObject (object entity, System.Collections.Generic.IDictionary&lt;string,Microsoft.Azure.CosmosDB.Table.EntityProperty&gt; properties, Microsoft.Azure.Storage.OperationContext operationContext);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void ReadUserObject(object entity, class System.Collections.Generic.IDictionary`2&lt;string, class Microsoft.Azure.CosmosDB.Table.EntityProperty&gt; properties, class Microsoft.Azure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.CosmosDB.Table.TableEntity.ReadUserObject(System.Object,System.Collections.Generic.IDictionary{System.String,Microsoft.Azure.CosmosDB.Table.EntityProperty},Microsoft.Azure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="static member ReadUserObject : obj * System.Collections.Generic.IDictionary&lt;string, Microsoft.Azure.CosmosDB.Table.EntityProperty&gt; * Microsoft.Azure.Storage.OperationContext -&gt; unit" Usage="Microsoft.Azure.CosmosDB.Table.TableEntity.ReadUserObject (entity, properties, operationContext)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.CosmosDB.Table</AssemblyName>
        <AssemblyVersion>0.9.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="entity" Type="System.Object" />
        <Parameter Name="properties" Type="System.Collections.Generic.IDictionary&lt;System.String,Microsoft.Azure.CosmosDB.Table.EntityProperty&gt;" />
        <Parameter Name="operationContext" Type="Microsoft.Azure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="entity"><span data-ttu-id="1942c-145">Die benutzerdefinierte Entitätsinstanz, die deserialisiert wird.</span><span class="sxs-lookup"><span data-stu-id="1942c-145">The custom entity instance being deserialized.</span></span></param>
        <param name="properties"><span data-ttu-id="1942c-146">Ein <see cref="T:System.Collections.Generic.IDictionary`2" /> zuordnet, die zu verwendenden Objektnamen <see cref="T:Microsoft.Azure.CosmosDB.Table.EntityProperty" /> Datenwerte deserialisiert und gespeichert, die in dieser tabellenentitätsinstanz.</span><span class="sxs-lookup"><span data-stu-id="1942c-146">An <see cref="T:System.Collections.Generic.IDictionary`2" /> object that maps string property names to <see cref="T:Microsoft.Azure.CosmosDB.Table.EntityProperty" /> data values to deserialize and store in this table entity instance.</span></span></param>
        <param name="operationContext"><span data-ttu-id="1942c-147">Ein <see cref="T:Microsoft.Azure.Storage.OperationContext" /> -Objekt, das den Kontext für den aktuellen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="1942c-147">An <see cref="T:Microsoft.Azure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <summary>
            <span data-ttu-id="1942c-148">Deserialisiert eine benutzerdefinierte Entitätsinstanz unter Verwendung des angegebenen <see cref="T:System.Collections.Generic.IDictionary`2" /> von Eigenschaftsnamen für <see cref="T:Microsoft.Azure.CosmosDB.Table.EntityProperty" /> -Datentypwerte.</span><span class="sxs-lookup"><span data-stu-id="1942c-148">Deserializes a custom entity instance using the specified <see cref="T:System.Collections.Generic.IDictionary`2" /> of property names to <see cref="T:Microsoft.Azure.CosmosDB.Table.EntityProperty" /> data typed values.</span></span> 
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RowKey">
      <MemberSignature Language="C#" Value="public string RowKey { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string RowKey" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.CosmosDB.Table.TableEntity.RowKey" />
      <MemberSignature Language="VB.NET" Value="Public Property RowKey As String" />
      <MemberSignature Language="F#" Value="member this.RowKey : string with get, set" Usage="Microsoft.Azure.CosmosDB.Table.TableEntity.RowKey" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:Microsoft.Azure.CosmosDB.Table.ITableEntity.RowKey</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.CosmosDB.Table</AssemblyName>
        <AssemblyVersion>0.9.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="1942c-149">Ruft ab, oder legt ihn fest Zeilenschlüssel der Entität.</span><span class="sxs-lookup"><span data-stu-id="1942c-149">Gets or sets the entity's row key.</span></span>
            </summary>
        <value><span data-ttu-id="1942c-150">Eine Zeichenfolge, die den Zeilenschlüssel der Entität enthält.</span><span class="sxs-lookup"><span data-stu-id="1942c-150">A string containing the row key for the entity.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Timestamp">
      <MemberSignature Language="C#" Value="public DateTimeOffset Timestamp { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.DateTimeOffset Timestamp" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.CosmosDB.Table.TableEntity.Timestamp" />
      <MemberSignature Language="VB.NET" Value="Public Property Timestamp As DateTimeOffset" />
      <MemberSignature Language="F#" Value="member this.Timestamp : DateTimeOffset with get, set" Usage="Microsoft.Azure.CosmosDB.Table.TableEntity.Timestamp" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:Microsoft.Azure.CosmosDB.Table.ITableEntity.Timestamp</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.CosmosDB.Table</AssemblyName>
        <AssemblyVersion>0.9.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.DateTimeOffset</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="1942c-151">Ruft ab oder legt den Zeitstempel der Entität.</span><span class="sxs-lookup"><span data-stu-id="1942c-151">Gets or sets the entity's timestamp.</span></span>
            </summary>
        <value><span data-ttu-id="1942c-152">Ein <see cref="T:System.DateTimeOffset" /> mit dem Zeitstempel der Entität.</span><span class="sxs-lookup"><span data-stu-id="1942c-152">A <see cref="T:System.DateTimeOffset" /> containing the timestamp of the entity.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="WriteEntity">
      <MemberSignature Language="C#" Value="public virtual System.Collections.Generic.IDictionary&lt;string,Microsoft.Azure.CosmosDB.Table.EntityProperty&gt; WriteEntity (Microsoft.Azure.Storage.OperationContext operationContext);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Collections.Generic.IDictionary`2&lt;string, class Microsoft.Azure.CosmosDB.Table.EntityProperty&gt; WriteEntity(class Microsoft.Azure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.CosmosDB.Table.TableEntity.WriteEntity(Microsoft.Azure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="abstract member WriteEntity : Microsoft.Azure.Storage.OperationContext -&gt; System.Collections.Generic.IDictionary&lt;string, Microsoft.Azure.CosmosDB.Table.EntityProperty&gt;&#xA;override this.WriteEntity : Microsoft.Azure.Storage.OperationContext -&gt; System.Collections.Generic.IDictionary&lt;string, Microsoft.Azure.CosmosDB.Table.EntityProperty&gt;" Usage="tableEntity.WriteEntity operationContext" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.Azure.CosmosDB.Table.ITableEntity.WriteEntity(Microsoft.Azure.Storage.OperationContext)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.CosmosDB.Table</AssemblyName>
        <AssemblyVersion>0.9.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IDictionary&lt;System.String,Microsoft.Azure.CosmosDB.Table.EntityProperty&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operationContext" Type="Microsoft.Azure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="operationContext"><span data-ttu-id="1942c-153">Ein <see cref="T:Microsoft.Azure.Storage.OperationContext" /> -Objekt, das den Kontext für den aktuellen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="1942c-153">An <see cref="T:Microsoft.Azure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <summary>
            <span data-ttu-id="1942c-154">Serialisiert die <see cref="T:System.Collections.Generic.IDictionary`2" /> von Eigenschaftennamen zugeordnet <see cref="T:Microsoft.Azure.CosmosDB.Table.EntityProperty" /> -Datenwerten aus dieser <see cref="T:Microsoft.Azure.CosmosDB.Table.TableEntity" /> Instanz.</span><span class="sxs-lookup"><span data-stu-id="1942c-154">Serializes the <see cref="T:System.Collections.Generic.IDictionary`2" /> of property names mapped to <see cref="T:Microsoft.Azure.CosmosDB.Table.EntityProperty" /> data values from this <see cref="T:Microsoft.Azure.CosmosDB.Table.TableEntity" /> instance.</span></span>
            </summary>
        <returns><span data-ttu-id="1942c-155">Ein <see cref="T:System.Collections.Generic.IDictionary`2" /> zuordnet, die zu verwendenden Objektnamen <see cref="T:Microsoft.Azure.CosmosDB.Table.EntityProperty" /> Datentypwerte, die durch Serialisieren dieser tabellenentitätsinstanz erstellt.</span><span class="sxs-lookup"><span data-stu-id="1942c-155">An <see cref="T:System.Collections.Generic.IDictionary`2" /> object that maps string property names to <see cref="T:Microsoft.Azure.CosmosDB.Table.EntityProperty" /> typed values created by serializing this table entity instance.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="WriteUserObject">
      <MemberSignature Language="C#" Value="public static System.Collections.Generic.IDictionary&lt;string,Microsoft.Azure.CosmosDB.Table.EntityProperty&gt; WriteUserObject (object entity, Microsoft.Azure.Storage.OperationContext operationContext);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Collections.Generic.IDictionary`2&lt;string, class Microsoft.Azure.CosmosDB.Table.EntityProperty&gt; WriteUserObject(object entity, class Microsoft.Azure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.CosmosDB.Table.TableEntity.WriteUserObject(System.Object,Microsoft.Azure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="static member WriteUserObject : obj * Microsoft.Azure.Storage.OperationContext -&gt; System.Collections.Generic.IDictionary&lt;string, Microsoft.Azure.CosmosDB.Table.EntityProperty&gt;" Usage="Microsoft.Azure.CosmosDB.Table.TableEntity.WriteUserObject (entity, operationContext)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.CosmosDB.Table</AssemblyName>
        <AssemblyVersion>0.9.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IDictionary&lt;System.String,Microsoft.Azure.CosmosDB.Table.EntityProperty&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="entity" Type="System.Object" />
        <Parameter Name="operationContext" Type="Microsoft.Azure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="entity"><span data-ttu-id="1942c-156">Das zu serialisierende Entitätsobjekt.</span><span class="sxs-lookup"><span data-stu-id="1942c-156">The entity object to serialize.</span></span></param>
        <param name="operationContext"><span data-ttu-id="1942c-157">Ein <see cref="T:Microsoft.Azure.Storage.OperationContext" /> -Objekt, das den Kontext für den aktuellen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="1942c-157">An <see cref="T:Microsoft.Azure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <summary>
            <span data-ttu-id="1942c-158">Erstellen einer <see cref="T:System.Collections.Generic.IDictionary`2" /> von <see cref="T:Microsoft.Azure.CosmosDB.Table.EntityProperty" /> Objekte für alle Eigenschaften des angegebenen Entitätsobjekts.</span><span class="sxs-lookup"><span data-stu-id="1942c-158">Create a <see cref="T:System.Collections.Generic.IDictionary`2" /> of <see cref="T:Microsoft.Azure.CosmosDB.Table.EntityProperty" /> objects for all the properties of the specified entity object.</span></span>
            </summary>
        <returns><span data-ttu-id="1942c-159">Ein <see cref="T:System.Collections.Generic.IDictionary`2" /> von <see cref="T:Microsoft.Azure.CosmosDB.Table.EntityProperty" /> Objekte für alle Eigenschaften des angegebenen Entitätsobjekts.</span><span class="sxs-lookup"><span data-stu-id="1942c-159">An <see cref="T:System.Collections.Generic.IDictionary`2" /> of <see cref="T:Microsoft.Azure.CosmosDB.Table.EntityProperty" /> objects for all the properties of the specified entity object.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>