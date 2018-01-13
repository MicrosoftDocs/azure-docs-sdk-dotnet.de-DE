<Type Name="HashPartitionResolver" FullName="Microsoft.Azure.Documents.Partitioning.HashPartitionResolver">
  <TypeSignature Language="C#" Value="public class HashPartitionResolver : IDisposable, Microsoft.Azure.Documents.Client.IPartitionResolver" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit HashPartitionResolver extends System.Object implements class Microsoft.Azure.Documents.Client.IPartitionResolver, class System.IDisposable" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Documents.Partitioning.HashPartitionResolver" />
  <TypeSignature Language="VB.NET" Value="Public Class HashPartitionResolver&#xA;Implements IDisposable, IPartitionResolver" />
  <TypeSignature Language="F#" Value="type HashPartitionResolver = class&#xA;    interface IPartitionResolver&#xA;    interface IDisposable" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Documents.Client</AssemblyName>
    <AssemblyVersion>1.18.0.0</AssemblyVersion>
    <AssemblyVersion>1.19.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces>
    <Interface>
      <InterfaceName>Microsoft.Azure.Documents.Client.IPartitionResolver</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>System.IDisposable</InterfaceName>
    </Interface>
  </Interfaces>
  <Attributes>
    <Attribute>
      <AttributeName>System.Obsolete("Support for IPartitionResolver based classes is now obsolete. It's recommended that you use partitioned collections for higher storage and throughput.")</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            <span data-ttu-id="90844-101">HashPartitionResolver implementiert Partitionierung anhand des Werts einer Hashfunktion, sodass Sie Anforderungen und Daten über eine Anzahl von Partitionen in der Azure-Cosmos-DB-Dienst gleichmäßig zu verteilen.</span><span class="sxs-lookup"><span data-stu-id="90844-101">HashPartitionResolver implements partitioning based on the value of a hash function, allowing you to evenly distribute requests and data across a number of partitions in the Azure Cosmos DB service.</span></span> 
            </summary>
    <remarks>
      <para>
            <span data-ttu-id="90844-102">Unterstützung für IPartitionResolver-basierten Klassen ist mittlerweile veraltet.</span><span class="sxs-lookup"><span data-stu-id="90844-102">Support for IPartitionResolver based classes is now obsolete.</span></span> <span data-ttu-id="90844-103">Es wird empfohlen, die Verwendung von <a href="https://azure.microsoft.com/documentation/articles/documentdb-partition-data">partitionierte Sammlungen</a> für höhere Speicher und den Durchsatz.</span><span class="sxs-lookup"><span data-stu-id="90844-103">It's recommended that you use <a href="https://azure.microsoft.com/documentation/articles/documentdb-partition-data">Partitioned Collections</a> for higher storage and throughput.</span></span>
            </para>
      <para>
            <span data-ttu-id="90844-104">Die HashPartitionResolver-Klasse implementiert intern konsistent Hash Ring über der Hashfunktion, die im angegebenen die <see cref="T:Microsoft.Azure.Documents.Partitioning.IHashGenerator" /> Schnittstelle.</span><span class="sxs-lookup"><span data-stu-id="90844-104">The HashPartitionResolver class internally implements a consistent hash ring over the hash function specified in the <see cref="T:Microsoft.Azure.Documents.Partitioning.IHashGenerator" /> interface.</span></span> <span data-ttu-id="90844-105">Wird standardmäßig die HashPartitionResolver bietet eine MD5-Hash-Funktion, aber dies kann durch eine andere Implementierung für hashing ausgelagert werden.</span><span class="sxs-lookup"><span data-stu-id="90844-105">By default, the HashPartitionResolver provides an MD5 hash function, but this can be swapped out with a different hashing implementation.</span></span> <span data-ttu-id="90844-106">Die konsistente Hash Ring erstellt 16 Replikate für jede Sammlung um eine einheitlichere Verteilung von Dokumenten über Sammlungen zu erzielen.</span><span class="sxs-lookup"><span data-stu-id="90844-106">The consistent hash ring creates 16 replicas for each collection in order to achieve a more uniform distribution of documents across collections.</span></span>
            </para>
      <para>
            <span data-ttu-id="90844-107">Die Hashpartitionierung ist am besten geeigneten für die Partitionierung, wenn der Partitionsschlüssel eine hohe Kardinalität besitzt, da es die Daten gleichmäßig über Sammlungen verteilt wird.</span><span class="sxs-lookup"><span data-stu-id="90844-107">The hash partitioning is most suitable for partitioning when the partition key has a high cardinality because it will distribute the data evenly across collections.</span></span> <span data-ttu-id="90844-108">Hashpartitionierung verwendet normalerweise die Id-Eigenschaft.</span><span class="sxs-lookup"><span data-stu-id="90844-108">Typically hash partitioning uses the id property.</span></span> <span data-ttu-id="90844-109">Eine gängige Einsatzgebiete für die Hashpartitionierung ist Daten erzeugt oder verbraucht wurde von einer großen Anzahl von unterschiedlichen Clients oder zum Speichern von Benutzerprofilen und Katalogelemente Telemetriedaten.</span><span class="sxs-lookup"><span data-stu-id="90844-109">A common use cases for hash partitioning is data produced or consumed from a large number of distinct clients or for storing user profiles, catalog items, and telemetry data.</span></span>
            </para>
    </remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public HashPartitionResolver (Func&lt;object,string&gt; partitionKeyExtractor, System.Collections.Generic.IEnumerable&lt;string&gt; collectionLinks, int numberOfVirtualNodesPerCollection = 128, Microsoft.Azure.Documents.Partitioning.IHashGenerator hashGenerator = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.Func`2&lt;object, string&gt; partitionKeyExtractor, class System.Collections.Generic.IEnumerable`1&lt;string&gt; collectionLinks, int32 numberOfVirtualNodesPerCollection, class Microsoft.Azure.Documents.Partitioning.IHashGenerator hashGenerator) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.Partitioning.HashPartitionResolver.#ctor(System.Func{System.Object,System.String},System.Collections.Generic.IEnumerable{System.String},System.Int32,Microsoft.Azure.Documents.Partitioning.IHashGenerator)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (partitionKeyExtractor As Func(Of Object, String), collectionLinks As IEnumerable(Of String), Optional numberOfVirtualNodesPerCollection As Integer = 128, Optional hashGenerator As IHashGenerator = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Documents.Partitioning.HashPartitionResolver : Func&lt;obj, string&gt; * seq&lt;string&gt; * int * Microsoft.Azure.Documents.Partitioning.IHashGenerator -&gt; Microsoft.Azure.Documents.Partitioning.HashPartitionResolver" Usage="new Microsoft.Azure.Documents.Partitioning.HashPartitionResolver (partitionKeyExtractor, collectionLinks, numberOfVirtualNodesPerCollection, hashGenerator)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Documents.Client</AssemblyName>
        <AssemblyVersion>1.18.0.0</AssemblyVersion>
        <AssemblyVersion>1.19.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="partitionKeyExtractor" Type="System.Func&lt;System.Object,System.String&gt;" />
        <Parameter Name="collectionLinks" Type="System.Collections.Generic.IEnumerable&lt;System.String&gt;" />
        <Parameter Name="numberOfVirtualNodesPerCollection" Type="System.Int32" />
        <Parameter Name="hashGenerator" Type="Microsoft.Azure.Documents.Partitioning.IHashGenerator" />
      </Parameters>
      <Docs>
        <param name="partitionKeyExtractor"><span data-ttu-id="90844-110">Eine Funktion zum Extrahieren der partitionkey-Werte aus dem Dokument</span><span class="sxs-lookup"><span data-stu-id="90844-110">A function to extract the partitionKey from the document</span></span></param>
        <param name="collectionLinks"><span data-ttu-id="90844-111">Die Liste der Auflistung Links, die für das hashing verwendet werden soll.</span><span class="sxs-lookup"><span data-stu-id="90844-111">The list of collection links used for hashing.</span></span></param>
        <param name="numberOfVirtualNodesPerCollection"><span data-ttu-id="90844-112">Die Anzahl der virtuellen Knoten pro Sammlung im Ring Conisistent Hash.</span><span class="sxs-lookup"><span data-stu-id="90844-112">The number of virtual nodes per collection in the conisistent hash ring.</span></span></param>
        <param name="hashGenerator"><span data-ttu-id="90844-113">Die <see cref="T:Microsoft.Azure.Documents.Partitioning.IHashGenerator" /> für die Verwendung in Hashalgorithmen konsistent.</span><span class="sxs-lookup"><span data-stu-id="90844-113">The <see cref="T:Microsoft.Azure.Documents.Partitioning.IHashGenerator" /> to use in consistent hashing.</span></span> <span data-ttu-id="90844-114">Bei null wird der standardmäßige MD5-Hash-Generator verwendet.</span><span class="sxs-lookup"><span data-stu-id="90844-114">If null, the default MD5 hash generator is used.</span></span></param>
        <summary>
            <span data-ttu-id="90844-115">Initialisiert eine neue Instanz der dem <see cref="T:Microsoft.Azure.Documents.Partitioning.HashPartitionResolver" /> in der Azure-Cosmos-DB service unter Verwendung des angegebenen <paramref name="partitionKeyExtractor" /> Wert.</span><span class="sxs-lookup"><span data-stu-id="90844-115">Initializes a new instance of the <see cref="T:Microsoft.Azure.Documents.Partitioning.HashPartitionResolver" /> in the Azure Cosmos DB service using the specified <paramref name="partitionKeyExtractor" /> value.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public HashPartitionResolver (string partitionKeyPropertyName, System.Collections.Generic.IEnumerable&lt;string&gt; collectionLinks, int numberOfVirtualNodesPerCollection = 128, Microsoft.Azure.Documents.Partitioning.IHashGenerator hashGenerator = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string partitionKeyPropertyName, class System.Collections.Generic.IEnumerable`1&lt;string&gt; collectionLinks, int32 numberOfVirtualNodesPerCollection, class Microsoft.Azure.Documents.Partitioning.IHashGenerator hashGenerator) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.Partitioning.HashPartitionResolver.#ctor(System.String,System.Collections.Generic.IEnumerable{System.String},System.Int32,Microsoft.Azure.Documents.Partitioning.IHashGenerator)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (partitionKeyPropertyName As String, collectionLinks As IEnumerable(Of String), Optional numberOfVirtualNodesPerCollection As Integer = 128, Optional hashGenerator As IHashGenerator = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Documents.Partitioning.HashPartitionResolver : string * seq&lt;string&gt; * int * Microsoft.Azure.Documents.Partitioning.IHashGenerator -&gt; Microsoft.Azure.Documents.Partitioning.HashPartitionResolver" Usage="new Microsoft.Azure.Documents.Partitioning.HashPartitionResolver (partitionKeyPropertyName, collectionLinks, numberOfVirtualNodesPerCollection, hashGenerator)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Documents.Client</AssemblyName>
        <AssemblyVersion>1.18.0.0</AssemblyVersion>
        <AssemblyVersion>1.19.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="partitionKeyPropertyName" Type="System.String" />
        <Parameter Name="collectionLinks" Type="System.Collections.Generic.IEnumerable&lt;System.String&gt;" />
        <Parameter Name="numberOfVirtualNodesPerCollection" Type="System.Int32" />
        <Parameter Name="hashGenerator" Type="Microsoft.Azure.Documents.Partitioning.IHashGenerator" />
      </Parameters>
      <Docs>
        <param name="partitionKeyPropertyName"><span data-ttu-id="90844-116">Der Name der Eigenschaft in das Dokument das hashing auf ausführen.</span><span class="sxs-lookup"><span data-stu-id="90844-116">The name of the property in the document to execute the hashing on.</span></span></param>
        <param name="collectionLinks"><span data-ttu-id="90844-117">Die Liste der Auflistung Links, die für das hashing verwendet werden soll.</span><span class="sxs-lookup"><span data-stu-id="90844-117">The list of collection links used for hashing.</span></span></param>
        <param name="numberOfVirtualNodesPerCollection"><span data-ttu-id="90844-118">Die Anzahl der virtuellen Knoten pro Sammlung im Ring Conisistent Hash.</span><span class="sxs-lookup"><span data-stu-id="90844-118">The number of virtual nodes per collection in the conisistent hash ring.</span></span></param>
        <param name="hashGenerator"><span data-ttu-id="90844-119">Die <see cref="T:Microsoft.Azure.Documents.Partitioning.IHashGenerator" /> für die Verwendung in Hashalgorithmen konsistent.</span><span class="sxs-lookup"><span data-stu-id="90844-119">The <see cref="T:Microsoft.Azure.Documents.Partitioning.IHashGenerator" /> to use in consistent hashing.</span></span> <span data-ttu-id="90844-120">Bei null wird der standardmäßige MD5-Hash-Generator verwendet.</span><span class="sxs-lookup"><span data-stu-id="90844-120">If null, the default MD5 hash generator is used.</span></span></param>
        <summary>
            <span data-ttu-id="90844-121">Initialisiert eine neue Instanz der dem <see cref="T:Microsoft.Azure.Documents.Partitioning.HashPartitionResolver" /> in der Azure-Cosmos-DB service unter Verwendung des angegebenen <paramref name="partitionKeyPropertyName" /> Wert.</span><span class="sxs-lookup"><span data-stu-id="90844-121">Initializes a new instance of the <see cref="T:Microsoft.Azure.Documents.Partitioning.HashPartitionResolver" /> in the Azure Cosmos DB service using the specified <paramref name="partitionKeyPropertyName" /> value.</span></span>
            </summary>
        <remarks>
            <span data-ttu-id="90844-122">Wird verwendet, wenn Sie basierend auf einem einzelnen Eigenschaftennamen partitionieren möchten.</span><span class="sxs-lookup"><span data-stu-id="90844-122">Use when you want to partition based on a single property name.</span></span> <span data-ttu-id="90844-123">Verwenden Sie den Konstruktor für andere Partitionierungsschemas stattdessen mit PartitionKeyExtractor fest.</span><span class="sxs-lookup"><span data-stu-id="90844-123">For other partitioning schemes, use the constructor with partitionKeyExtractor instead.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="CollectionLinks">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IEnumerable&lt;string&gt; CollectionLinks { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IEnumerable`1&lt;string&gt; CollectionLinks" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Documents.Partitioning.HashPartitionResolver.CollectionLinks" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property CollectionLinks As IEnumerable(Of String)" />
      <MemberSignature Language="F#" Value="member this.CollectionLinks : seq&lt;string&gt;" Usage="Microsoft.Azure.Documents.Partitioning.HashPartitionResolver.CollectionLinks" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Documents.Client</AssemblyName>
        <AssemblyVersion>1.18.0.0</AssemblyVersion>
        <AssemblyVersion>1.19.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IEnumerable&lt;System.String&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="90844-124">Ruft die IEnumerable Auflistung Linktypen aus, die für das hashing im Azure-Cosmos-DB-Dienst verwendet.</span><span class="sxs-lookup"><span data-stu-id="90844-124">Gets the IEnumerable of collection links used for hashing in the Azure Cosmos DB service.</span></span>
            </summary>
        <value><span data-ttu-id="90844-125">Die IEnumerable Auflistung Linktypen aus, die für das hashing verwendet werden soll.</span><span class="sxs-lookup"><span data-stu-id="90844-125">The IEnumerable of collection links used for hashing.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Dispose">
      <MemberSignature Language="C#" Value="public void Dispose ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Dispose() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.Partitioning.HashPartitionResolver.Dispose" />
      <MemberSignature Language="VB.NET" Value="Public Sub Dispose ()" />
      <MemberSignature Language="F#" Value="abstract member Dispose : unit -&gt; unit&#xA;override this.Dispose : unit -&gt; unit" Usage="hashPartitionResolver.Dispose " />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:System.IDisposable.Dispose</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Documents.Client</AssemblyName>
        <AssemblyVersion>1.18.0.0</AssemblyVersion>
        <AssemblyVersion>1.19.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="90844-126">Verwirft den Konfliktlöser im Azure-Cosmos-DB-Dienst an.</span><span class="sxs-lookup"><span data-stu-id="90844-126">Disposes the resolver in the Azure Cosmos DB service.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Finalize">
      <MemberSignature Language="C#" Value="~HashPartitionResolver ();" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig virtual instance void Finalize() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.Partitioning.HashPartitionResolver.Finalize" />
      <MemberSignature Language="VB.NET" Value="Finalize ()" />
      <MemberSignature Language="F#" Value="override this.Finalize : unit -&gt; unit" Usage="hashPartitionResolver.Finalize " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Documents.Client</AssemblyName>
        <AssemblyVersion>1.18.0.0</AssemblyVersion>
        <AssemblyVersion>1.19.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="90844-127">Der Destruktor der Klasse.</span><span class="sxs-lookup"><span data-stu-id="90844-127">Class destructor.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetPartitionKey">
      <MemberSignature Language="C#" Value="public virtual object GetPartitionKey (object document);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance object GetPartitionKey(object document) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.Partitioning.HashPartitionResolver.GetPartitionKey(System.Object)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function GetPartitionKey (document As Object) As Object" />
      <MemberSignature Language="F#" Value="abstract member GetPartitionKey : obj -&gt; obj&#xA;override this.GetPartitionKey : obj -&gt; obj" Usage="hashPartitionResolver.GetPartitionKey document" />
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
        <param name="document"><span data-ttu-id="90844-128">Ein Document-Objekt</span><span class="sxs-lookup"><span data-stu-id="90844-128">A document object</span></span></param>
        <summary>
            <span data-ttu-id="90844-129">Extrahiert den Partitionsschlüssel aus dem angegebenen Dokument mit dem angegebenen <see cref="P:Microsoft.Azure.Documents.Partitioning.HashPartitionResolver.PartitionKeyPropertyName" /> Eigenschaft oder <see cref="P:Microsoft.Azure.Documents.Partitioning.HashPartitionResolver.PartitionKeyExtractor" /> Funktion Präferenz im Azure-Cosmos-DB-Dienst.</span><span class="sxs-lookup"><span data-stu-id="90844-129">Extracts the partition key from the specified document using the specified <see cref="P:Microsoft.Azure.Documents.Partitioning.HashPartitionResolver.PartitionKeyPropertyName" /> property or <see cref="P:Microsoft.Azure.Documents.Partitioning.HashPartitionResolver.PartitionKeyExtractor" /> function in order of preference in the Azure Cosmos DB service.</span></span>
            </summary>
        <returns><span data-ttu-id="90844-130">Objekt, das als Partitionsschlüssel verwendet.</span><span class="sxs-lookup"><span data-stu-id="90844-130">object used as the partition key.</span></span></returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.InvalidOperationException"><span data-ttu-id="90844-131">Wird ausgelöst, wenn dies nicht möglich, zum Extrahieren des Schlüssels für die Partition.</span><span class="sxs-lookup"><span data-stu-id="90844-131">Thrown if unable to extract the partition key.</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName="HashGenerator">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Documents.Partitioning.IHashGenerator HashGenerator { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Documents.Partitioning.IHashGenerator HashGenerator" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Documents.Partitioning.HashPartitionResolver.HashGenerator" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property HashGenerator As IHashGenerator" />
      <MemberSignature Language="F#" Value="member this.HashGenerator : Microsoft.Azure.Documents.Partitioning.IHashGenerator" Usage="Microsoft.Azure.Documents.Partitioning.HashPartitionResolver.HashGenerator" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Documents.Client</AssemblyName>
        <AssemblyVersion>1.18.0.0</AssemblyVersion>
        <AssemblyVersion>1.19.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonIgnore</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Documents.Partitioning.IHashGenerator</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="90844-132">Ruft die HashGenerator in konsistent Hashalgorithmen verwendet.</span><span class="sxs-lookup"><span data-stu-id="90844-132">Gets the HashGenerator used in consistent hashing.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="NumberOfVirtualNodesPerCollection">
      <MemberSignature Language="C#" Value="public int NumberOfVirtualNodesPerCollection { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 NumberOfVirtualNodesPerCollection" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Documents.Partitioning.HashPartitionResolver.NumberOfVirtualNodesPerCollection" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property NumberOfVirtualNodesPerCollection As Integer" />
      <MemberSignature Language="F#" Value="member this.NumberOfVirtualNodesPerCollection : int" Usage="Microsoft.Azure.Documents.Partitioning.HashPartitionResolver.NumberOfVirtualNodesPerCollection" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Documents.Client</AssemblyName>
        <AssemblyVersion>1.18.0.0</AssemblyVersion>
        <AssemblyVersion>1.19.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="90844-133">Die Anzahl der virtuellen Knoten pro Sammlung im HashSet Conisistent ring im Azure-Cosmos-DB-Dienst.</span><span class="sxs-lookup"><span data-stu-id="90844-133">The number of virtual nodes per collection in the conisistent hash ring in the Azure Cosmos DB service.</span></span> <span data-ttu-id="90844-134">Diese Steuerung der Gefährdung der Schiefe von Dokumenten über Sammlungen Vs die konsistente hashing Latenz.</span><span class="sxs-lookup"><span data-stu-id="90844-134">This controls the compromise of skewness of documents accross collections vs the consistent hashing latency.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PartitionKeyExtractor">
      <MemberSignature Language="C#" Value="public Func&lt;object,string&gt; PartitionKeyExtractor { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Func`2&lt;object, string&gt; PartitionKeyExtractor" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Documents.Partitioning.HashPartitionResolver.PartitionKeyExtractor" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property PartitionKeyExtractor As Func(Of Object, String)" />
      <MemberSignature Language="F#" Value="member this.PartitionKeyExtractor : Func&lt;obj, string&gt;" Usage="Microsoft.Azure.Documents.Partitioning.HashPartitionResolver.PartitionKeyExtractor" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Documents.Client</AssemblyName>
        <AssemblyVersion>1.18.0.0</AssemblyVersion>
        <AssemblyVersion>1.19.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Func&lt;System.Object,System.String&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="90844-135">Ruft die Funktion zum Extrahieren von Partitionsschlüssel aus einem Objekt in der Azure-Cosmos-Datenbank ab.</span><span class="sxs-lookup"><span data-stu-id="90844-135">Gets the function to extract the partition key from an object in the Azure Cosmos DB service.</span></span>
            </summary>
        <value><span data-ttu-id="90844-136">Die Funktion, die den Partitionsschlüssel aus einem Objekt zu extrahieren.</span><span class="sxs-lookup"><span data-stu-id="90844-136">The function to extract the partition key from an object.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PartitionKeyPropertyName">
      <MemberSignature Language="C#" Value="public string PartitionKeyPropertyName { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string PartitionKeyPropertyName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Documents.Partitioning.HashPartitionResolver.PartitionKeyPropertyName" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property PartitionKeyPropertyName As String" />
      <MemberSignature Language="F#" Value="member this.PartitionKeyPropertyName : string" Usage="Microsoft.Azure.Documents.Partitioning.HashPartitionResolver.PartitionKeyPropertyName" />
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
            <span data-ttu-id="90844-137">Ruft den Namen der Eigenschaft in das Dokument das hashing im Azure-Cosmos-DB-Dienst ausgeführt.</span><span class="sxs-lookup"><span data-stu-id="90844-137">Gets the name of the property in the document to execute the hashing on in the Azure Cosmos DB service.</span></span>
            </summary>
        <value><span data-ttu-id="90844-138">Der Name der Eigenschaft in das Dokument das hashing auf ausführen.</span><span class="sxs-lookup"><span data-stu-id="90844-138">The name of the property in the document to execute the hashing on.</span></span></value>
        <remarks>
            <span data-ttu-id="90844-139">HashPartitionResolver unterstützt zwei Modi - PartitionKeyPropertyName und der andere mit PartitionKeyExtractor verwenden.</span><span class="sxs-lookup"><span data-stu-id="90844-139">HashPartitionResolver supports two modes - one using PartitionKeyPropertyName and the other using PartitionKeyExtractor.</span></span>
            <span data-ttu-id="90844-140">Mithilfe der Reflektion, dies der Fall ist Name für die Verwendung der c#-Eigenschaft, die JSON-Darstellung PartitionKeyPropertyName extrahiert.</span><span class="sxs-lookup"><span data-stu-id="90844-140">PartitionKeyPropertyName is extracted using Reflection, so use the C# property name, not the JSON representation.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ResolveForCreate">
      <MemberSignature Language="C#" Value="public virtual string ResolveForCreate (object partitionKey);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance string ResolveForCreate(object partitionKey) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.Partitioning.HashPartitionResolver.ResolveForCreate(System.Object)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function ResolveForCreate (partitionKey As Object) As String" />
      <MemberSignature Language="F#" Value="abstract member ResolveForCreate : obj -&gt; string&#xA;override this.ResolveForCreate : obj -&gt; string" Usage="hashPartitionResolver.ResolveForCreate partitionKey" />
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
        <param name="partitionKey"><span data-ttu-id="90844-141">Der Partitionsschlüssel verwendet werden, um zu bestimmen, die Zielsammlung für erstellt.</span><span class="sxs-lookup"><span data-stu-id="90844-141">The partition key used to determine the target collection for creates.</span></span></param>
        <summary>
            <span data-ttu-id="90844-142">Erhält eine Partition drücken, gibt die Auflistung, die Self-link zum Erstellen eines Dokuments in der Azure-Cosmos-DB-Dienst.</span><span class="sxs-lookup"><span data-stu-id="90844-142">Given a partition key, returns the collection self-link for creating a document in the Azure Cosmos DB service.</span></span>
            </summary>
        <returns><span data-ttu-id="90844-143">Den Link der Ziel-Auflistung, der zum Erstellen von Dokumenten verwendet werden.</span><span class="sxs-lookup"><span data-stu-id="90844-143">The target collection link that will be used for document creation.</span></span></returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentNullException"><span data-ttu-id="90844-144">Wird ausgelöst, wenn das angegebene <paramref name="partitionKey" /> ist null.</span><span class="sxs-lookup"><span data-stu-id="90844-144">Thrown if the specified <paramref name="partitionKey" /> is null.</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName="ResolveForRead">
      <MemberSignature Language="C#" Value="public virtual System.Collections.Generic.IEnumerable&lt;string&gt; ResolveForRead (object partitionKey);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Collections.Generic.IEnumerable`1&lt;string&gt; ResolveForRead(object partitionKey) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.Partitioning.HashPartitionResolver.ResolveForRead(System.Object)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function ResolveForRead (partitionKey As Object) As IEnumerable(Of String)" />
      <MemberSignature Language="F#" Value="abstract member ResolveForRead : obj -&gt; seq&lt;string&gt;&#xA;override this.ResolveForRead : obj -&gt; seq&lt;string&gt;" Usage="hashPartitionResolver.ResolveForRead partitionKey" />
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
        <param name="partitionKey"><span data-ttu-id="90844-145">Der Partitionsschlüssel verwendet, um die Zielsammlungen für das Lesen zu bestimmen.</span><span class="sxs-lookup"><span data-stu-id="90844-145">The partition key used to determine the target collections for reading.</span></span> <span data-ttu-id="90844-146">Eine Zeichenfolge muss sein.</span><span class="sxs-lookup"><span data-stu-id="90844-146">Must be a string.</span></span></param>
        <summary>
            <span data-ttu-id="90844-147">Erhält eine Partition Schlüssel gibt eine Liste der Sammlung von Links mit dem Hash in der Azure-Cosmos-Datenbank gelesen.</span><span class="sxs-lookup"><span data-stu-id="90844-147">Given a partition key, returns a list of collection links to read from using its hash in the Azure Cosmos DB service.</span></span>
            </summary>
        <returns><span data-ttu-id="90844-148">Die Liste der zielverknüpfungen-Auflistung.</span><span class="sxs-lookup"><span data-stu-id="90844-148">The list of target collection links.</span></span></returns>
        <remarks>
            <span data-ttu-id="90844-149">Wenn PartitionKey null ist, werden alle Sammlungen zurückgegeben.</span><span class="sxs-lookup"><span data-stu-id="90844-149">If partitionKey is null, then all collections are returned.</span></span> <span data-ttu-id="90844-150">Die HashPartitionResolver unterstützt nur Zeichenfolgen als PartitionKeys.</span><span class="sxs-lookup"><span data-stu-id="90844-150">The HashPartitionResolver supports only strings as partitionKeys.</span></span>
            <span data-ttu-id="90844-151">Für andere Typen mit dem ToString()- oder JsonConvert.SerializeObject() in eine Zeichenfolge umgewandelt.</span><span class="sxs-lookup"><span data-stu-id="90844-151">For other types, use ToString() or JsonConvert.SerializeObject() to convert to string.</span></span>
            </remarks>
        <exception cref="T:System.InvalidOperationException"><span data-ttu-id="90844-152">Wird ausgelöst, wenn der Partitionsschlüssel keine Zeichenfolge ist.</span><span class="sxs-lookup"><span data-stu-id="90844-152">Thrown if the partition key is not a string.</span></span></exception>
      </Docs>
    </Member>
  </Members>
</Type>