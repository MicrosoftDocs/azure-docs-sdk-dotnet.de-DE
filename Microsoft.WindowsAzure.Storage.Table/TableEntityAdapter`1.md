<Type Name="TableEntityAdapter&lt;T&gt;" FullName="Microsoft.WindowsAzure.Storage.Table.TableEntityAdapter&lt;T&gt;">
  <TypeSignature Language="C#" Value="public class TableEntityAdapter&lt;T&gt; : Microsoft.WindowsAzure.Storage.Table.TableEntity" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit TableEntityAdapter`1&lt;T&gt; extends Microsoft.WindowsAzure.Storage.Table.TableEntity" />
  <TypeSignature Language="DocId" Value="T:Microsoft.WindowsAzure.Storage.Table.TableEntityAdapter`1" />
  <TypeSignature Language="VB.NET" Value="Public Class TableEntityAdapter(Of T)&#xA;Inherits TableEntity" />
  <TypeSignature Language="F#" Value="type TableEntityAdapter&lt;'T&gt; = class&#xA;    inherit TableEntity" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
    <AssemblyVersion>8.4.0.0</AssemblyVersion>
    <AssemblyVersion>8.7.0.0</AssemblyVersion>
  </AssemblyInfo>
  <TypeParameters>
    <TypeParameter Name="T" />
  </TypeParameters>
  <Base>
    <BaseTypeName>Microsoft.WindowsAzure.Storage.Table.TableEntity</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <typeparam name="T"><span data-ttu-id="d5d49-101">Der Typ des Objekts, das Lese- und Schreibberechtigungen für Azure-Tabellenspeicher, es einer Klasse oder Struktur sein kann.</span><span class="sxs-lookup"><span data-stu-id="d5d49-101">The type of object to read and write to Azure Table Storage, it can be a class or a struct.</span></span></typeparam>
    <summary>
            <span data-ttu-id="d5d49-102">Adapterklasse ermöglicht lesen und Schreiben von Objekten mit Azure Table Storage ohne erben von <see cref="T:Microsoft.WindowsAzure.Storage.Table.TableEntity" /> Klasse oder durch Implementierung <see cref="T:Microsoft.WindowsAzure.Storage.Table.ITableEntity" /> Schnittstelle.</span><span class="sxs-lookup"><span data-stu-id="d5d49-102">Adapter class to allow reading and writing objects to Azure Table Storage without inheriting from <see cref="T:Microsoft.WindowsAzure.Storage.Table.TableEntity" /> class or implementing <see cref="T:Microsoft.WindowsAzure.Storage.Table.ITableEntity" /> interface.</span></span> <span data-ttu-id="d5d49-103">Die Objekte möglich POCO-Objekte, die einfache oder komplexe Objekte mit verschachtelte komplexe Eigenschaften.</span><span class="sxs-lookup"><span data-stu-id="d5d49-103">The objects can be simple POCO objects or complex objects with nested complex properties.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public TableEntityAdapter ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Table.TableEntityAdapter`1.#ctor" />
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
            <span data-ttu-id="d5d49-104">Initialisiert eine neue Instanz der <see cref="T:Microsoft.WindowsAzure.Storage.Table.TableEntityAdapter`1" />-Klasse.</span><span class="sxs-lookup"><span data-stu-id="d5d49-104">Initializes a new instance of the <see cref="T:Microsoft.WindowsAzure.Storage.Table.TableEntityAdapter`1" /> class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public TableEntityAdapter (T originalEntity);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(!T originalEntity) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Table.TableEntityAdapter`1.#ctor(`0)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (originalEntity As T)" />
      <MemberSignature Language="F#" Value="new Microsoft.WindowsAzure.Storage.Table.TableEntityAdapter&lt;'T&gt; : 'T -&gt; Microsoft.WindowsAzure.Storage.Table.TableEntityAdapter&lt;'T&gt;" Usage="new Microsoft.WindowsAzure.Storage.Table.TableEntityAdapter&lt;'T&gt; originalEntity" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="originalEntity" Type="T" />
      </Parameters>
      <Docs>
        <param name="originalEntity"><span data-ttu-id="d5d49-105">Das Objekt, mit Azure Table Storage geschrieben werden soll.</span><span class="sxs-lookup"><span data-stu-id="d5d49-105">The object to write to Azure Table Storage.</span></span></param>
        <summary>
            <span data-ttu-id="d5d49-106">Initialisiert eine neue Instanz der <see cref="T:Microsoft.WindowsAzure.Storage.Table.TableEntityAdapter`1" />-Klasse mit dem angegebenen Objekt.</span><span class="sxs-lookup"><span data-stu-id="d5d49-106">Initializes a new instance of the <see cref="T:Microsoft.WindowsAzure.Storage.Table.TableEntityAdapter`1" /> class with the specified object.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public TableEntityAdapter (T originalEntity, string partitionKey, string rowKey);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(!T originalEntity, string partitionKey, string rowKey) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Table.TableEntityAdapter`1.#ctor(`0,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (originalEntity As T, partitionKey As String, rowKey As String)" />
      <MemberSignature Language="F#" Value="new Microsoft.WindowsAzure.Storage.Table.TableEntityAdapter&lt;'T&gt; : 'T * string * string -&gt; Microsoft.WindowsAzure.Storage.Table.TableEntityAdapter&lt;'T&gt;" Usage="new Microsoft.WindowsAzure.Storage.Table.TableEntityAdapter&lt;'T&gt; (originalEntity, partitionKey, rowKey)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="originalEntity" Type="T" />
        <Parameter Name="partitionKey" Type="System.String" />
        <Parameter Name="rowKey" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="originalEntity"><span data-ttu-id="d5d49-107">Das Objekt, mit Azure Table Storage geschrieben werden soll.</span><span class="sxs-lookup"><span data-stu-id="d5d49-107">The object to write to Azure Table Storage.</span></span></param>
        <param name="partitionKey"><span data-ttu-id="d5d49-108">Eine Zeichenfolge mit dem partitionsschlüsselwert für die Entität.</span><span class="sxs-lookup"><span data-stu-id="d5d49-108">A string containing the partition key value for the entity.</span></span></param>
        <param name="rowKey"><span data-ttu-id="d5d49-109">Eine Zeichenfolge mit dem zeilenschlüsselwert für die Entität.</span><span class="sxs-lookup"><span data-stu-id="d5d49-109">A string containing the row key value for the entity.</span></span></param>
        <summary>
            <span data-ttu-id="d5d49-110">Initialisiert eine neue Instanz der dem <see cref="T:Microsoft.WindowsAzure.Storage.Table.TableEntityAdapter`1" /> Klasse mit dem angegebenen Objekt, Partitionsschlüssel und Zeilenschlüssel.</span><span class="sxs-lookup"><span data-stu-id="d5d49-110">Initializes a new instance of the <see cref="T:Microsoft.WindowsAzure.Storage.Table.TableEntityAdapter`1" /> class with the specified object, partition key and row key.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OriginalEntity">
      <MemberSignature Language="C#" Value="public T OriginalEntity { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance !T OriginalEntity" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.Table.TableEntityAdapter`1.OriginalEntity" />
      <MemberSignature Language="VB.NET" Value="Public Property OriginalEntity As T" />
      <MemberSignature Language="F#" Value="member this.OriginalEntity : 'T with get, set" Usage="Microsoft.WindowsAzure.Storage.Table.TableEntityAdapter&lt;'T&gt;.OriginalEntity" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>T</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="d5d49-111">Die ursprüngliche Entität, die gelesen und in Azure-Tabellenspeicher geschrieben.</span><span class="sxs-lookup"><span data-stu-id="d5d49-111">The original entity that is read and written to azure table storage.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ReadEntity">
      <MemberSignature Language="C#" Value="public override void ReadEntity (System.Collections.Generic.IDictionary&lt;string,Microsoft.WindowsAzure.Storage.Table.EntityProperty&gt; properties, Microsoft.WindowsAzure.Storage.OperationContext operationContext);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance void ReadEntity(class System.Collections.Generic.IDictionary`2&lt;string, class Microsoft.WindowsAzure.Storage.Table.EntityProperty&gt; properties, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Table.TableEntityAdapter`1.ReadEntity(System.Collections.Generic.IDictionary{System.String,Microsoft.WindowsAzure.Storage.Table.EntityProperty},Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="override this.ReadEntity : System.Collections.Generic.IDictionary&lt;string, Microsoft.WindowsAzure.Storage.Table.EntityProperty&gt; * Microsoft.WindowsAzure.Storage.OperationContext -&gt; unit" Usage="tableEntityAdapter.ReadEntity (properties, operationContext)" />
      <MemberType>Method</MemberType>
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
        <param name="properties"><span data-ttu-id="d5d49-112">Ein <see cref="T:System.Collections.Generic.IDictionary`2" /> -Objekt, das eigenschaftenzuordnungen benennt typisierten <see cref="T:Microsoft.WindowsAzure.Storage.Table.EntityProperty" /> Werte.</span><span class="sxs-lookup"><span data-stu-id="d5d49-112">An <see cref="T:System.Collections.Generic.IDictionary`2" /> object that maps property names to typed <see cref="T:Microsoft.WindowsAzure.Storage.Table.EntityProperty" /> values.</span></span></param>
        <param name="operationContext"><span data-ttu-id="d5d49-113">Ein <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> -Objekt, das den Kontext für den aktuellen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="d5d49-113">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <summary>
            <span data-ttu-id="d5d49-114">Deserialisiert <see cref="T:Microsoft.WindowsAzure.Storage.Table.TableEntityAdapter`1" /> -Instanz mit dem angegebenen <see cref="T:System.Collections.Generic.IDictionary`2" /> Eigenschaftsnamen der ordnet die <see cref="P:Microsoft.WindowsAzure.Storage.Table.TableEntityAdapter`1.OriginalEntity" /> zu typisierten <see cref="T:Microsoft.WindowsAzure.Storage.Table.EntityProperty" /> Werte und speichert ihn in die <see cref="P:Microsoft.WindowsAzure.Storage.Table.TableEntityAdapter`1.OriginalEntity" /> Eigenschaft.</span><span class="sxs-lookup"><span data-stu-id="d5d49-114">Deserializes <see cref="T:Microsoft.WindowsAzure.Storage.Table.TableEntityAdapter`1" /> instance using the specified <see cref="T:System.Collections.Generic.IDictionary`2" /> that maps property names of the <see cref="P:Microsoft.WindowsAzure.Storage.Table.TableEntityAdapter`1.OriginalEntity" /> to typed <see cref="T:Microsoft.WindowsAzure.Storage.Table.EntityProperty" /> values and stores it in the <see cref="P:Microsoft.WindowsAzure.Storage.Table.TableEntityAdapter`1.OriginalEntity" /> property.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="WriteEntity">
      <MemberSignature Language="C#" Value="public override System.Collections.Generic.IDictionary&lt;string,Microsoft.WindowsAzure.Storage.Table.EntityProperty&gt; WriteEntity (Microsoft.WindowsAzure.Storage.OperationContext operationContext);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance class System.Collections.Generic.IDictionary`2&lt;string, class Microsoft.WindowsAzure.Storage.Table.EntityProperty&gt; WriteEntity(class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Table.TableEntityAdapter`1.WriteEntity(Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="override this.WriteEntity : Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Collections.Generic.IDictionary&lt;string, Microsoft.WindowsAzure.Storage.Table.EntityProperty&gt;" Usage="tableEntityAdapter.WriteEntity operationContext" />
      <MemberType>Method</MemberType>
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
        <param name="operationContext"><span data-ttu-id="d5d49-115">Ein <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> -Objekt, das den Kontext für den aktuellen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="d5d49-115">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <summary>
            <span data-ttu-id="d5d49-116">Serialisiert die <see cref="T:System.Collections.Generic.IDictionary`2" /> von Eigenschaftennamen zugeordnet <see cref="T:Microsoft.WindowsAzure.Storage.Table.EntityProperty" /> Datenwerte aus der <see cref="P:Microsoft.WindowsAzure.Storage.Table.TableEntityAdapter`1.OriginalEntity" /> Eigenschaft.</span><span class="sxs-lookup"><span data-stu-id="d5d49-116">Serializes the <see cref="T:System.Collections.Generic.IDictionary`2" /> of property names mapped to <see cref="T:Microsoft.WindowsAzure.Storage.Table.EntityProperty" /> data values from the <see cref="P:Microsoft.WindowsAzure.Storage.Table.TableEntityAdapter`1.OriginalEntity" /> property.</span></span>
            </summary>
        <returns><span data-ttu-id="d5d49-117">Ein <see cref="T:System.Collections.Generic.IDictionary`2" /> zuordnet, die zu verwendenden Objektnamen <see cref="T:Microsoft.WindowsAzure.Storage.Table.EntityProperty" /> Datentypwerte, die durch Serialisieren dieser tabellenentitätsinstanz erstellt.</span><span class="sxs-lookup"><span data-stu-id="d5d49-117">An <see cref="T:System.Collections.Generic.IDictionary`2" /> object that maps string property names to <see cref="T:Microsoft.WindowsAzure.Storage.Table.EntityProperty" /> typed values created by serializing this table entity instance.</span></span></returns>
        <remarks><span data-ttu-id="d5d49-118">Wenn <see cref="P:Microsoft.WindowsAzure.Storage.Table.TableEntityAdapter`1.OriginalEntity" /> ist ein einfaches POCO-Objekt mit einfachen Eigenschaften (Grundtypen, String, Byte [],...), <see cref="M:Microsoft.WindowsAzure.Storage.Table.TableEntityAdapter`1.WriteEntity(Microsoft.WindowsAzure.Storage.OperationContext)" /> Methode erstellt <see cref="T:Microsoft.WindowsAzure.Storage.Table.EntityProperty" /> Objekten die Verwendung dieser Eigenschaften.</span><span class="sxs-lookup"><span data-stu-id="d5d49-118">If <see cref="P:Microsoft.WindowsAzure.Storage.Table.TableEntityAdapter`1.OriginalEntity" /> is a simple POCO object with simple properties (primitive types, string, byte[], ...), <see cref="M:Microsoft.WindowsAzure.Storage.Table.TableEntityAdapter`1.WriteEntity(Microsoft.WindowsAzure.Storage.OperationContext)" /> method will create <see cref="T:Microsoft.WindowsAzure.Storage.Table.EntityProperty" /> objects using these properties.</span></span><br />
             <span data-ttu-id="d5d49-119">D. h.</span><span class="sxs-lookup"><span data-stu-id="d5d49-119">Ie.</span></span> <span data-ttu-id="d5d49-120">Eine einfache POCO Objekt A mit Eigenschaften von B und C mit dieser Struktur A -&gt;B, A -&gt;C wird konvertiert werden, um Schlüssel-Wert-Paare von {"B", EntityProperty(B)}, {"C", EntityProperty(C)}.</span><span class="sxs-lookup"><span data-stu-id="d5d49-120">A simple POCO object A with properties of B and C with this structure A-&gt;B, A-&gt;C, will be converted to key value pairs of {"B", EntityProperty(B)}, {"C", EntityProperty(C)}.</span></span><br />
            <span data-ttu-id="d5d49-121">Wenn <see cref="P:Microsoft.WindowsAzure.Storage.Table.TableEntityAdapter`1.OriginalEntity" /> verfügt über komplexe Eigenschaften (und möglicherweise diese Eigenschaften mit Ihren eigenen komplexe Eigenschaften) <see cref="M:Microsoft.WindowsAzure.Storage.Table.TableEntityAdapter`1.WriteEntity(Microsoft.WindowsAzure.Storage.OperationContext)" /> Methode wird vereinfachen <see cref="P:Microsoft.WindowsAzure.Storage.Table.TableEntityAdapter`1.OriginalEntity" /> erste.</span><span class="sxs-lookup"><span data-stu-id="d5d49-121">If <see cref="P:Microsoft.WindowsAzure.Storage.Table.TableEntityAdapter`1.OriginalEntity" /> has complex properties (and potentially these properties having complex properties of their own), <see cref="M:Microsoft.WindowsAzure.Storage.Table.TableEntityAdapter`1.WriteEntity(Microsoft.WindowsAzure.Storage.OperationContext)" /> method will flatten <see cref="P:Microsoft.WindowsAzure.Storage.Table.TableEntityAdapter`1.OriginalEntity" /> first.</span></span><br />
            <span data-ttu-id="d5d49-122">D. h.</span><span class="sxs-lookup"><span data-stu-id="d5d49-122">Ie.</span></span> <span data-ttu-id="d5d49-123">Mit einer einfachen Eigenschaft von B und komplexe Eigenschaften von C und D die haben eigene Eigenschaften E und F mit dieser Struktur ein - Objekt A&gt;B, A -&gt;C -&gt;E "und" A -&gt;d-&gt;F wird Schlüsselwert vereinfacht werden die Paare von:</span><span class="sxs-lookup"><span data-stu-id="d5d49-123">An object A with a simple property of B and complex properties of C and D which have their own properties of E and F with this structure A-&gt;B, A-&gt;C-&gt;E and A-&gt;D-&gt;F, will be flattened to key value pairs of:</span></span><br />
            <span data-ttu-id="d5d49-124">{"B", EntityProperty(B)}, {"C_E", EntityProperty(E)} und {"D_F", EntityProperty(F)}.</span><span class="sxs-lookup"><span data-stu-id="d5d49-124">{"B", EntityProperty(B)}, {"C_E", EntityProperty(E)} and {"D_F", EntityProperty(F)}.</span></span><br />
            <span data-ttu-id="d5d49-125">Für jedes Schlüssel-Wert-Paar:</span><span class="sxs-lookup"><span data-stu-id="d5d49-125">For each key value pair:</span></span><br />
            1. <span data-ttu-id="d5d49-126">Der Schlüssel wird durch den Namen der Eigenschaften, die vom Stamm (A) zum Ende Knoteneigenschaft ("E" oder "F"), die durch "_" getrennten besucht anfügen zusammengesetzt.</span><span class="sxs-lookup"><span data-stu-id="d5d49-126">The key is composed by appending the names of the properties visited from root (A) to end node property (E or F) delimited by "_".</span></span><br />
            2. <span data-ttu-id="d5d49-127">Der Wert ist die <see cref="T:Microsoft.WindowsAzure.Storage.Table.EntityProperty" /> Objekt instanziiert, indem der Wert der Eigenschaft der End-Knoten.</span><span class="sxs-lookup"><span data-stu-id="d5d49-127">The value is the <see cref="T:Microsoft.WindowsAzure.Storage.Table.EntityProperty" /> object, instantiated by the value of the end node property.</span></span><br />
            <span data-ttu-id="d5d49-128">Alle Schlüssel-Wert-Paare gespeichert werden im zurückgegebenen <see cref="T:System.Collections.Generic.IDictionary`2" />.</span><span class="sxs-lookup"><span data-stu-id="d5d49-128">All key value pairs will be stored in the returned <see cref="T:System.Collections.Generic.IDictionary`2" />.</span></span><br /><span data-ttu-id="d5d49-129"><see cref="M:Microsoft.WindowsAzure.Storage.Table.TableEntityAdapter`1.ReadEntity(System.Collections.Generic.IDictionary{System.String,Microsoft.WindowsAzure.Storage.Table.EntityProperty},Microsoft.WindowsAzure.Storage.OperationContext)" />Methode recomposes der ursprünglichen Objekte (POCO oder komplexe) mithilfe der <see cref="T:System.Collections.Generic.IDictionary`2" /> von dieser Methode zurückgegebene und speichert diese im <see cref="P:Microsoft.WindowsAzure.Storage.Table.TableEntityAdapter`1.OriginalEntity" /> Eigenschaft.</span><span class="sxs-lookup"><span data-stu-id="d5d49-129"><see cref="M:Microsoft.WindowsAzure.Storage.Table.TableEntityAdapter`1.ReadEntity(System.Collections.Generic.IDictionary{System.String,Microsoft.WindowsAzure.Storage.Table.EntityProperty},Microsoft.WindowsAzure.Storage.OperationContext)" /> method recomposes the original object (POCO or complex) using the <see cref="T:System.Collections.Generic.IDictionary`2" /> returned by this method and store it in <see cref="P:Microsoft.WindowsAzure.Storage.Table.TableEntityAdapter`1.OriginalEntity" /> property.</span></span><br />
            <span data-ttu-id="d5d49-130">Eigenschaften, die mit markiert sind <see cref="T:Microsoft.WindowsAzure.Storage.Table.IgnorePropertyAttribute" /> in die <see cref="P:Microsoft.WindowsAzure.Storage.Table.TableEntityAdapter`1.OriginalEntity" /> -Objekt ignoriert und nicht von dieser Methode verarbeitet werden.</span><span class="sxs-lookup"><span data-stu-id="d5d49-130">Properties that are marked with <see cref="T:Microsoft.WindowsAzure.Storage.Table.IgnorePropertyAttribute" /> in the <see cref="P:Microsoft.WindowsAzure.Storage.Table.TableEntityAdapter`1.OriginalEntity" /> object will be ignored and not processed by this method.</span></span></remarks>
      </Docs>
    </Member>
  </Members>
</Type>