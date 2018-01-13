<Type Name="RangePartitionResolver&lt;T&gt;" FullName="Microsoft.Azure.Documents.Partitioning.RangePartitionResolver&lt;T&gt;">
  <TypeSignature Language="C#" Value="public class RangePartitionResolver&lt;T&gt; : Microsoft.Azure.Documents.Client.IPartitionResolver where T : IComparable&lt;T&gt;, IEquatable&lt;T&gt;" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit RangePartitionResolver`1&lt;(class System.IComparable`1&lt;!T&gt;, class System.IEquatable`1&lt;!T&gt;) T&gt; extends System.Object implements class Microsoft.Azure.Documents.Client.IPartitionResolver" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Documents.Partitioning.RangePartitionResolver`1" />
  <TypeSignature Language="VB.NET" Value="Public Class RangePartitionResolver(Of T)&#xA;Implements IPartitionResolver" />
  <TypeSignature Language="F#" Value="type RangePartitionResolver&lt;'T (requires 'T :&gt; IComparable&lt;'T&gt; and 'T :&gt; IEquatable&lt;'T&gt;)&gt; = class&#xA;    interface IPartitionResolver" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Documents.Client</AssemblyName>
    <AssemblyVersion>1.18.0.0</AssemblyVersion>
    <AssemblyVersion>1.19.0.0</AssemblyVersion>
  </AssemblyInfo>
  <TypeParameters>
    <TypeParameter Name="T">
      <Constraints>
        <InterfaceName>System.IComparable&lt;T&gt;</InterfaceName>
        <InterfaceName>System.IEquatable&lt;T&gt;</InterfaceName>
      </Constraints>
    </TypeParameter>
  </TypeParameters>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces>
    <Interface>
      <InterfaceName>Microsoft.Azure.Documents.Client.IPartitionResolver</InterfaceName>
    </Interface>
  </Interfaces>
  <Attributes>
    <Attribute>
      <AttributeName>System.Obsolete("Support for IPartitionResolver based classes is now obsolete. It's recommended that you use partitioned collections for higher storage and throughput.")</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <typeparam name="T"><span data-ttu-id="ba964-101">Der Typ des Werts für die Bereichspartitionierung verwendet werden soll.</span><span class="sxs-lookup"><span data-stu-id="ba964-101">The type of value to use for range partitioning.</span></span></typeparam>
    <summary>
            <span data-ttu-id="ba964-102">RangePartitionResolver implementiert Partitionierung im Azure-Cosmos-DB-Dienst mithilfe einer partitionszuordnung von Wertebereichen für eine Sammlung, die Self-link.</span><span class="sxs-lookup"><span data-stu-id="ba964-102">RangePartitionResolver implements partitioning in Azure Cosmos DB service by using a partition map of ranges of values to a collection self-link.</span></span>
            <span data-ttu-id="ba964-103">Dies funktioniert gut, wenn die Daten natürlich geordnete und häufig abgefragt ab Wertebereiche, z. B. für zeitreihendaten oder alphabetische Bereiche von Zeichenfolgen verwenden.</span><span class="sxs-lookup"><span data-stu-id="ba964-103">This works well when the data is naturally ordered and commonly queried upon using ranges of values, e.g., for time series data or alphabetical ranges of strings.</span></span>
            </summary>
    <remarks>
      <para>
            <span data-ttu-id="ba964-104">Unterstützung für IPartitionResolver-basierten Klassen ist mittlerweile veraltet.</span><span class="sxs-lookup"><span data-stu-id="ba964-104">Support for IPartitionResolver based classes is now obsolete.</span></span> <span data-ttu-id="ba964-105">Es wird empfohlen, die Verwendung von <a href="https://azure.microsoft.com/documentation/articles/documentdb-partition-data">partitionierte Sammlungen</a> für höhere Speicher und den Durchsatz.</span><span class="sxs-lookup"><span data-stu-id="ba964-105">It's recommended that you use <a href="https://azure.microsoft.com/documentation/articles/documentdb-partition-data">Partitioned Collections</a> for higher storage and throughput.</span></span>
            </para>
      <para>
            <span data-ttu-id="ba964-106">In einer Bereichspartitionierung werden Partitionen basierend darauf zugewiesen, ob der Partitionsschlüssel in einem bestimmten Bereich liegt.</span><span class="sxs-lookup"><span data-stu-id="ba964-106">In range partitioning, partitions are assigned based on whether the partition key is within a certain range.</span></span> <span data-ttu-id="ba964-107">Die RangePartitionResolver-Klasse können Sie die Verwalten einer Zuordnung zwischen einer <see cref="T:Microsoft.Azure.Documents.Partitioning.Range`1" /> und Self-link-Auflistung.</span><span class="sxs-lookup"><span data-stu-id="ba964-107">The RangePartitionResolver class helps you maintain a mapping between a <see cref="T:Microsoft.Azure.Documents.Partitioning.Range`1" /> and collection self-link.</span></span>
            </para>
      <para>
        <span data-ttu-id="ba964-108"><see cref="T:Microsoft.Azure.Documents.Partitioning.Range`1" />ist eine einfache Klasse zum Angeben von Bereichen von Typen, die implementieren <see cref="T:System.IComparable`1" /> und <see cref="T:System.IEquatable`1" /> wie Zeichenfolgen oder Zahlen.</span><span class="sxs-lookup"><span data-stu-id="ba964-108"><see cref="T:Microsoft.Azure.Documents.Partitioning.Range`1" /> is a simple class for specifying ranges of any types that implement <see cref="T:System.IComparable`1" /> and <see cref="T:System.IEquatable`1" /> like strings or numbers.</span></span> <span data-ttu-id="ba964-109">Für liest und erstellt, Sie können in jeder beliebigen Bereich übergeben, und der Konfliktlöser identifiziert alle möglichen Sammlungen durch Identifizieren der Bereiche der Partitionen, die Twith angeforderten Bereich überschneidet.</span><span class="sxs-lookup"><span data-stu-id="ba964-109">For reads and creates, you can pass in any arbitrary range, and the resolver identifies all the candidate collections by identifying the ranges of the partitions that intersect twith the requested range.</span></span>
            </para>
      <para>
            <span data-ttu-id="ba964-110">Ein spezieller Fall der Bereichspartitionierung ist, wenn der Bereich nur einen einzelnen diskreten Wert bezeichnet Suche Partitionierung ist.</span><span class="sxs-lookup"><span data-stu-id="ba964-110">A special case of range partitioning is when the range is just a single discrete value, sometimes called Lookup Partitioning.</span></span> <span data-ttu-id="ba964-111">Dies wird häufig für die Partitionierung von diskreten Werten wie Region oder Typ oder zur Partitionierung von Mandanten in einer mehrinstanzenfähigen Anwendung verwendet.</span><span class="sxs-lookup"><span data-stu-id="ba964-111">This is commonly used for partitioning by discrete values like Region or Type or for partitioning tenants in a multi-tenant application.</span></span>
            </para>
    </remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public RangePartitionResolver (Func&lt;object,object&gt; partitionKeyExtractor, System.Collections.Generic.IDictionary&lt;Microsoft.Azure.Documents.Partitioning.Range&lt;T&gt;,string&gt; partitionMap);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.Func`2&lt;object, object&gt; partitionKeyExtractor, class System.Collections.Generic.IDictionary`2&lt;class Microsoft.Azure.Documents.Partitioning.Range`1&lt;!T&gt;, string&gt; partitionMap) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.Partitioning.RangePartitionResolver`1.#ctor(System.Func{System.Object,System.Object},System.Collections.Generic.IDictionary{Microsoft.Azure.Documents.Partitioning.Range{`0},System.String})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (partitionKeyExtractor As Func(Of Object, Object), partitionMap As IDictionary(Of Range(Of T), String))" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Documents.Partitioning.RangePartitionResolver&lt;'T (requires 'T :&gt; IComparable&lt;'T&gt; and 'T :&gt; IEquatable&lt;'T&gt;)&gt; : Func&lt;obj, obj&gt; * System.Collections.Generic.IDictionary&lt;Microsoft.Azure.Documents.Partitioning.Range&lt;'T&gt;, string&gt; -&gt; Microsoft.Azure.Documents.Partitioning.RangePartitionResolver&lt;'T (requires 'T :&gt; IComparable&lt;'T&gt; and 'T :&gt; IEquatable&lt;'T&gt;)&gt;" Usage="new Microsoft.Azure.Documents.Partitioning.RangePartitionResolver&lt;'T (requires 'T :&gt; System.IComparable&lt;'T&gt; and 'T :&gt; System.IEquatable&lt;'T&gt;)&gt; (partitionKeyExtractor, partitionMap)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Documents.Client</AssemblyName>
        <AssemblyVersion>1.18.0.0</AssemblyVersion>
        <AssemblyVersion>1.19.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="partitionKeyExtractor" Type="System.Func&lt;System.Object,System.Object&gt;" />
        <Parameter Name="partitionMap" Type="System.Collections.Generic.IDictionary&lt;Microsoft.Azure.Documents.Partitioning.Range&lt;T&gt;,System.String&gt;" />
      </Parameters>
      <Docs>
        <param name="partitionKeyExtractor"><span data-ttu-id="ba964-112">Der Name der Eigenschaft in das Dokument das hashing auf ausführen.</span><span class="sxs-lookup"><span data-stu-id="ba964-112">The name of the property in the document to execute the hashing on.</span></span></param>
        <param name="partitionMap"><span data-ttu-id="ba964-113">Eine Karte aus dem Bereich Sammlung verknüpfen, die für die Partitionierung von Anforderungen verwendet wird.</span><span class="sxs-lookup"><span data-stu-id="ba964-113">A map from range to collection-link that is used for partitioning requests.</span></span></param>
        <summary>
            <span data-ttu-id="ba964-114">Initialisiert eine neue Instanz der dem <see cref="T:Microsoft.Azure.Documents.Partitioning.HashPartitionResolver" /> in der Azure-Cosmos-DB service unter Verwendung des angegebenen <paramref name="partitionKeyExtractor" /> Wert.</span><span class="sxs-lookup"><span data-stu-id="ba964-114">Initializes a new instance of the <see cref="T:Microsoft.Azure.Documents.Partitioning.HashPartitionResolver" /> in the Azure Cosmos DB service using the specified <paramref name="partitionKeyExtractor" /> value.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentNullException"><span data-ttu-id="ba964-115">Wird ausgelöst, wenn einer der Parameter null ist.</span><span class="sxs-lookup"><span data-stu-id="ba964-115">Thrown if one of the parameters is null.</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public RangePartitionResolver (string partitionKeyPropertyName, System.Collections.Generic.IDictionary&lt;Microsoft.Azure.Documents.Partitioning.Range&lt;T&gt;,string&gt; partitionMap);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string partitionKeyPropertyName, class System.Collections.Generic.IDictionary`2&lt;class Microsoft.Azure.Documents.Partitioning.Range`1&lt;!T&gt;, string&gt; partitionMap) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.Partitioning.RangePartitionResolver`1.#ctor(System.String,System.Collections.Generic.IDictionary{Microsoft.Azure.Documents.Partitioning.Range{`0},System.String})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (partitionKeyPropertyName As String, partitionMap As IDictionary(Of Range(Of T), String))" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Documents.Partitioning.RangePartitionResolver&lt;'T (requires 'T :&gt; IComparable&lt;'T&gt; and 'T :&gt; IEquatable&lt;'T&gt;)&gt; : string * System.Collections.Generic.IDictionary&lt;Microsoft.Azure.Documents.Partitioning.Range&lt;'T&gt;, string&gt; -&gt; Microsoft.Azure.Documents.Partitioning.RangePartitionResolver&lt;'T (requires 'T :&gt; IComparable&lt;'T&gt; and 'T :&gt; IEquatable&lt;'T&gt;)&gt;" Usage="new Microsoft.Azure.Documents.Partitioning.RangePartitionResolver&lt;'T (requires 'T :&gt; System.IComparable&lt;'T&gt; and 'T :&gt; System.IEquatable&lt;'T&gt;)&gt; (partitionKeyPropertyName, partitionMap)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Documents.Client</AssemblyName>
        <AssemblyVersion>1.18.0.0</AssemblyVersion>
        <AssemblyVersion>1.19.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="partitionKeyPropertyName" Type="System.String" />
        <Parameter Name="partitionMap" Type="System.Collections.Generic.IDictionary&lt;Microsoft.Azure.Documents.Partitioning.Range&lt;T&gt;,System.String&gt;" />
      </Parameters>
      <Docs>
        <param name="partitionKeyPropertyName"><span data-ttu-id="ba964-116">Der Name der Eigenschaft in das Dokument das hashing auf ausführen.</span><span class="sxs-lookup"><span data-stu-id="ba964-116">The name of the property in the document to execute the hashing on.</span></span></param>
        <param name="partitionMap"><span data-ttu-id="ba964-117">Eine Karte aus dem Bereich Sammlung verknüpfen, die für die Partitionierung von Anforderungen verwendet wird.</span><span class="sxs-lookup"><span data-stu-id="ba964-117">A map from range to collection-link that is used for partitioning requests.</span></span></param>
        <summary>
            <span data-ttu-id="ba964-118">Initialisiert eine neue Instanz der dem <see cref="T:Microsoft.Azure.Documents.Partitioning.RangePartitionResolver`1" /> Klasse in der Azure-Cosmos-DB-Dienst unter Verwendung des angegebenen <paramref name="partitionKeyPropertyName" /> Wert.</span><span class="sxs-lookup"><span data-stu-id="ba964-118">Initializes a new instance of the <see cref="T:Microsoft.Azure.Documents.Partitioning.RangePartitionResolver`1" /> class in the Azure Cosmos DB service using the specified <paramref name="partitionKeyPropertyName" /> value.</span></span>
            </summary>
        <remarks>
            <span data-ttu-id="ba964-119">Wird verwendet, wenn Sie basierend auf einem einzelnen Eigenschaftennamen partitionieren möchten.</span><span class="sxs-lookup"><span data-stu-id="ba964-119">Use when you want to partition based on a single property name.</span></span> <span data-ttu-id="ba964-120">Verwenden Sie den Konstruktor für andere Partitionierungsschemas stattdessen mit PartitionKeyExtractor fest.</span><span class="sxs-lookup"><span data-stu-id="ba964-120">For other partitioning schemes, use the constructor with partitionKeyExtractor instead.</span></span>
            </remarks>
        <exception cref="T:System.ArgumentNullException"><span data-ttu-id="ba964-121">Wird ausgelöst, wenn einer der Parameter null ist.</span><span class="sxs-lookup"><span data-stu-id="ba964-121">Thrown if one of the parameters is null.</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName="GetPartitionKey">
      <MemberSignature Language="C#" Value="public virtual object GetPartitionKey (object document);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance object GetPartitionKey(object document) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.Partitioning.RangePartitionResolver`1.GetPartitionKey(System.Object)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function GetPartitionKey (document As Object) As Object" />
      <MemberSignature Language="F#" Value="abstract member GetPartitionKey : obj -&gt; obj&#xA;override this.GetPartitionKey : obj -&gt; obj" Usage="rangePartitionResolver.GetPartitionKey document" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.Azure.Documents.Client.IPartitionResolver.GetPartitionKey(System.Object)</InterfaceMember>
      </Implements>
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
        <param name="document"><span data-ttu-id="ba964-122">Ein Document-Objekt</span><span class="sxs-lookup"><span data-stu-id="ba964-122">A document object</span></span></param>
        <summary>
            <span data-ttu-id="ba964-123">Extrahiert den Partitionsschlüssel aus dem angegebenen Dokument mit dem angegebenen <see cref="P:Microsoft.Azure.Documents.Partitioning.HashPartitionResolver.PartitionKeyPropertyName" /> Eigenschaft oder <see cref="P:Microsoft.Azure.Documents.Partitioning.HashPartitionResolver.PartitionKeyExtractor" /> Funktion Präferenz im Azure-Cosmos-DB-Dienst.</span><span class="sxs-lookup"><span data-stu-id="ba964-123">Extracts the partition key from the specified document using the specified <see cref="P:Microsoft.Azure.Documents.Partitioning.HashPartitionResolver.PartitionKeyPropertyName" /> property or <see cref="P:Microsoft.Azure.Documents.Partitioning.HashPartitionResolver.PartitionKeyExtractor" /> function in order of preference in the Azure Cosmos DB service.</span></span>
            </summary>
        <returns><span data-ttu-id="ba964-124">Objekt, das als Partitionsschlüssel verwendet.</span><span class="sxs-lookup"><span data-stu-id="ba964-124">object used as the partition key.</span></span></returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.InvalidOperationException"><span data-ttu-id="ba964-125">Wird ausgelöst, wenn dies nicht möglich, zum Extrahieren des Schlüssels für die Partition.</span><span class="sxs-lookup"><span data-stu-id="ba964-125">Thrown if unable to extract the partition key.</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName="PartitionKeyExtractor">
      <MemberSignature Language="C#" Value="public Func&lt;object,object&gt; PartitionKeyExtractor { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Func`2&lt;object, object&gt; PartitionKeyExtractor" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Documents.Partitioning.RangePartitionResolver`1.PartitionKeyExtractor" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property PartitionKeyExtractor As Func(Of Object, Object)" />
      <MemberSignature Language="F#" Value="member this.PartitionKeyExtractor : Func&lt;obj, obj&gt;" Usage="Microsoft.Azure.Documents.Partitioning.RangePartitionResolver&lt;'T (requires 'T :&gt; System.IComparable&lt;'T&gt; and 'T :&gt; System.IEquatable&lt;'T&gt;)&gt;.PartitionKeyExtractor" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Documents.Client</AssemblyName>
        <AssemblyVersion>1.18.0.0</AssemblyVersion>
        <AssemblyVersion>1.19.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Func&lt;System.Object,System.Object&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="ba964-126">Ruft die Funktion zum Extrahieren des partitionsschlüssels aller Objekte in der Azure-Cosmos-DB-Dienst ab.</span><span class="sxs-lookup"><span data-stu-id="ba964-126">Gets the function to extract the partition key from any object in the Azure Cosmos DB service.</span></span>
            </summary>
        <value>
            <span data-ttu-id="ba964-127">Die Funktion, die den Partitionsschlüssel aller Objekte zu extrahieren.</span><span class="sxs-lookup"><span data-stu-id="ba964-127">The function to extract the partition key from any object.</span></span>
            </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PartitionKeyPropertyName">
      <MemberSignature Language="C#" Value="public string PartitionKeyPropertyName { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string PartitionKeyPropertyName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Documents.Partitioning.RangePartitionResolver`1.PartitionKeyPropertyName" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property PartitionKeyPropertyName As String" />
      <MemberSignature Language="F#" Value="member this.PartitionKeyPropertyName : string" Usage="Microsoft.Azure.Documents.Partitioning.RangePartitionResolver&lt;'T (requires 'T :&gt; System.IComparable&lt;'T&gt; and 'T :&gt; System.IEquatable&lt;'T&gt;)&gt;.PartitionKeyPropertyName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Documents.Client</AssemblyName>
        <AssemblyVersion>1.18.0.0</AssemblyVersion>
        <AssemblyVersion>1.19.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="ba964-128">Der Name der Eigenschaft in das Dokument das hashing im Azure-Cosmos-DB-Dienst ausgeführt wird.</span><span class="sxs-lookup"><span data-stu-id="ba964-128">The name of the property in the document to execute the hashing on in the Azure Cosmos DB service.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PartitionMap">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IDictionary&lt;Microsoft.Azure.Documents.Partitioning.Range&lt;T&gt;,string&gt; PartitionMap { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IDictionary`2&lt;class Microsoft.Azure.Documents.Partitioning.Range`1&lt;!T&gt;, string&gt; PartitionMap" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Documents.Partitioning.RangePartitionResolver`1.PartitionMap" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property PartitionMap As IDictionary(Of Range(Of T), String)" />
      <MemberSignature Language="F#" Value="member this.PartitionMap : System.Collections.Generic.IDictionary&lt;Microsoft.Azure.Documents.Partitioning.Range&lt;'T&gt;, string&gt;" Usage="Microsoft.Azure.Documents.Partitioning.RangePartitionResolver&lt;'T (requires 'T :&gt; System.IComparable&lt;'T&gt; and 'T :&gt; System.IEquatable&lt;'T&gt;)&gt;.PartitionMap" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Documents.Client</AssemblyName>
        <AssemblyVersion>1.18.0.0</AssemblyVersion>
        <AssemblyVersion>1.19.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IDictionary&lt;Microsoft.Azure.Documents.Partitioning.Range&lt;T&gt;,System.String&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="ba964-129">Ruft die Zuordnung von Bereich Auflistung-Link, der für die Partitionierung Anforderungen in der Azure-Cosmos-DB-Dienst verwendet wird.</span><span class="sxs-lookup"><span data-stu-id="ba964-129">Gets the map from range to collection-link that is used for partitioning requests in the Azure Cosmos DB service.</span></span>
            </summary>
        <value>
            <span data-ttu-id="ba964-130">Die Zuordnung von Bereich Sammlung verknüpfen, die für die Partitionierung von Anforderungen verwendet wird.</span><span class="sxs-lookup"><span data-stu-id="ba964-130">The map from range to collection-link that is used for partitioning requests.</span></span>
            </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ResolveForCreate">
      <MemberSignature Language="C#" Value="public virtual string ResolveForCreate (object partitionKey);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance string ResolveForCreate(object partitionKey) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.Partitioning.RangePartitionResolver`1.ResolveForCreate(System.Object)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function ResolveForCreate (partitionKey As Object) As String" />
      <MemberSignature Language="F#" Value="abstract member ResolveForCreate : obj -&gt; string&#xA;override this.ResolveForCreate : obj -&gt; string" Usage="rangePartitionResolver.ResolveForCreate partitionKey" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.Azure.Documents.Client.IPartitionResolver.ResolveForCreate(System.Object)</InterfaceMember>
      </Implements>
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
        <param name="partitionKey"><span data-ttu-id="ba964-131">Der Partitionsschlüssel verwendet werden, um zu bestimmen, die Zielsammlung für erstellen</span><span class="sxs-lookup"><span data-stu-id="ba964-131">The partition key used to determine the target collection for create</span></span></param>
        <summary>
            <span data-ttu-id="ba964-132">Erhält eine Partition drücken, gibt die richtigen Auflistung Self-link für das Erstellen eines Dokuments mithilfe der partitionszuordnung Bereich im Azure-Cosmos-DB-Dienst.</span><span class="sxs-lookup"><span data-stu-id="ba964-132">Given a partition key, returns the correct collection self-link for creating a document using the range partition map in the Azure Cosmos DB service.</span></span>
            </summary>
        <returns><span data-ttu-id="ba964-133">Den Link der Ziel-Auflistung, der zum Erstellen von Dokumenten verwendet werden.</span><span class="sxs-lookup"><span data-stu-id="ba964-133">The target collection link that will be used for document creation.</span></span></returns>
        <remarks>
            <span data-ttu-id="ba964-134">Wenn mehrere Bereiche der angegebenen partitionkey-Werte übereinstimmen, gibt der Konfliktlöser der übereinstimmenden Bereiche zurück.</span><span class="sxs-lookup"><span data-stu-id="ba964-134">If multiple ranges match the specified partitionKey, then the resolver returns one of the matching ranges.</span></span> <span data-ttu-id="ba964-135">Wenn keiner der Bereiche entspricht, löst die Methode eine <see cref="T:System.InvalidOperationException" />.</span><span class="sxs-lookup"><span data-stu-id="ba964-135">If none of the ranges match, then the method throws a <see cref="T:System.InvalidOperationException" />.</span></span> <span data-ttu-id="ba964-136">Wenn PartitionKey null ist, werden alle Sammlungen zurückgegeben.</span><span class="sxs-lookup"><span data-stu-id="ba964-136">If partitionKey is null, then all collections are returned.</span></span>
            </remarks>
        <exception cref="T:System.ArgumentNullException"><span data-ttu-id="ba964-137">Wird ausgelöst, wenn <paramref name="partitionKey" /> ist null.</span><span class="sxs-lookup"><span data-stu-id="ba964-137">Thrown if <paramref name="partitionKey" /> is null.</span></span></exception>
        <exception cref="T:System.InvalidOperationException">
            <span data-ttu-id="ba964-138">Wird ausgelöst, wenn die <paramref name="partitionKey" /> ist ein ungültiger Typ oder keiner der Bereiche auf den angegebenen Partitionsschlüssel entspricht.</span><span class="sxs-lookup"><span data-stu-id="ba964-138">Thrown if the <paramref name="partitionKey" /> is an invalid type or if none of the ranges match the specified partition key.</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="ResolveForRead">
      <MemberSignature Language="C#" Value="public virtual System.Collections.Generic.IEnumerable&lt;string&gt; ResolveForRead (object partitionKey);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Collections.Generic.IEnumerable`1&lt;string&gt; ResolveForRead(object partitionKey) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.Partitioning.RangePartitionResolver`1.ResolveForRead(System.Object)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function ResolveForRead (partitionKey As Object) As IEnumerable(Of String)" />
      <MemberSignature Language="F#" Value="abstract member ResolveForRead : obj -&gt; seq&lt;string&gt;&#xA;override this.ResolveForRead : obj -&gt; seq&lt;string&gt;" Usage="rangePartitionResolver.ResolveForRead partitionKey" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.Azure.Documents.Client.IPartitionResolver.ResolveForRead(System.Object)</InterfaceMember>
      </Implements>
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
        <param name="partitionKey"><span data-ttu-id="ba964-139">Der Partitionsschlüssel verwendet, um die Zielsammlungen für die Abfrage zu ermitteln.</span><span class="sxs-lookup"><span data-stu-id="ba964-139">The partition key used to determine the target collections for query</span></span></param>
        <summary>
            <span data-ttu-id="ba964-140">Erhält eine Partition drücken, gibt eine Liste der Sammlung von Links zum Lesen aus der Verwendung der partitionszuordnung Bereich im Azure-Cosmos-DB-Dienst.</span><span class="sxs-lookup"><span data-stu-id="ba964-140">Given a partition key, returns a list of collection links to read from using the range partition map in the Azure Cosmos DB service.</span></span>
            </summary>
        <returns><span data-ttu-id="ba964-141">Die Liste der zielverknüpfungen-Auflistung.</span><span class="sxs-lookup"><span data-stu-id="ba964-141">The list of target collection links.</span></span></returns>
        <remarks>
            <span data-ttu-id="ba964-142">Die <paramref name="partitionKey" /> muss eine Instanz von <typeparamref name="T" />, <see cref="T:Microsoft.Azure.Documents.Partitioning.Range`1" /> oder ein <see cref="T:System.Collections.Generic.IEnumerable`1" />. " /&gt;.</span><span class="sxs-lookup"><span data-stu-id="ba964-142">The <paramref name="partitionKey" /> must be an instance of <typeparamref name="T" />, <see cref="T:Microsoft.Azure.Documents.Partitioning.Range`1" /> or an <see cref="T:System.Collections.Generic.IEnumerable`1" />."/&gt;.</span></span> <span data-ttu-id="ba964-143">Diese Methode gibt alle Sammlungen, die Bereiche, die mit dem angegebenen intersect entspricht <paramref name="partitionKey" />.</span><span class="sxs-lookup"><span data-stu-id="ba964-143">This method returns all the collections corresponding to the ranges that intersect with the specified <paramref name="partitionKey" />.</span></span>
            </remarks>
        <exception cref="T:System.InvalidOperationException">
            <span data-ttu-id="ba964-144">Wird ausgelöst, wenn die <paramref name="partitionKey" /> ist ein ungültiger Typ.</span><span class="sxs-lookup"><span data-stu-id="ba964-144">Thrown if the <paramref name="partitionKey" /> is an invalid type.</span></span>
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>