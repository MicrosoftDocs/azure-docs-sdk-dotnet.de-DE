<Type Name="Resource" FullName="Microsoft.Azure.Documents.Resource">
  <TypeSignature Language="C#" Value="public abstract class Resource : Microsoft.Azure.Documents.JsonSerializable" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract beforefieldinit Resource extends Microsoft.Azure.Documents.JsonSerializable" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Documents.Resource" />
  <TypeSignature Language="VB.NET" Value="Public MustInherit Class Resource&#xA;Inherits JsonSerializable" />
  <TypeSignature Language="F#" Value="type Resource = class&#xA;    inherit JsonSerializable" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.DocumentDB.Core</AssemblyName>
    <AssemblyVersion>1.6.0.0</AssemblyVersion>
    <AssemblyVersion>1.7.0.0</AssemblyVersion>
    <AssemblyVersion>1.7.1.0</AssemblyVersion>
  </AssemblyInfo>
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Documents.Client</AssemblyName>
    <AssemblyVersion>1.18.0.0</AssemblyVersion>
    <AssemblyVersion>1.19.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.Documents.JsonSerializable</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary> 
             <span data-ttu-id="f782a-101">Stellt einen abstrakte Ressourcentyp im Azure-Cosmos-DB-Dienst dar.</span><span class="sxs-lookup"><span data-stu-id="f782a-101">Represents an abstract resource type in the Azure Cosmos DB service.</span></span>
             <span data-ttu-id="f782a-102">Alle Azure-Cosmos-DB-Ressourcen, wie z. B. <see cref="T:Microsoft.Azure.Documents.Database" />, <see cref="T:Microsoft.Azure.Documents.DocumentCollection" />, und <see cref="T:Microsoft.Azure.Documents.Document" /> dieser abstrakten Typ erweitern.</span><span class="sxs-lookup"><span data-stu-id="f782a-102">All Azure Cosmos DB resources, such as <see cref="T:Microsoft.Azure.Documents.Database" />, <see cref="T:Microsoft.Azure.Documents.DocumentCollection" />, and <see cref="T:Microsoft.Azure.Documents.Document" /> extend this abstract type.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="protected Resource ();" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.Resource.#ctor" />
      <MemberSignature Language="VB.NET" Value="Protected Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DocumentDB.Core</AssemblyName>
        <AssemblyVersion>1.6.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.1.0</AssemblyVersion>
      </AssemblyInfo>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Documents.Client</AssemblyName>
        <AssemblyVersion>1.18.0.0</AssemblyVersion>
        <AssemblyVersion>1.19.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="f782a-103">Initialisiert eine neue Instanz der dem <see cref="T:Microsoft.Azure.Documents.Resource" /> Klasse für den Azure-Cosmos-DB-Dienst.</span><span class="sxs-lookup"><span data-stu-id="f782a-103">Initializes a new instance of the <see cref="T:Microsoft.Azure.Documents.Resource" /> class for the Azure Cosmos DB service.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="protected Resource (Microsoft.Azure.Documents.Resource resource);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig specialname rtspecialname instance void .ctor(class Microsoft.Azure.Documents.Resource resource) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.Resource.#ctor(Microsoft.Azure.Documents.Resource)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Documents.Resource : Microsoft.Azure.Documents.Resource -&gt; Microsoft.Azure.Documents.Resource" Usage="new Microsoft.Azure.Documents.Resource resource" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DocumentDB.Core</AssemblyName>
        <AssemblyVersion>1.6.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.1.0</AssemblyVersion>
      </AssemblyInfo>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Documents.Client</AssemblyName>
        <AssemblyVersion>1.18.0.0</AssemblyVersion>
        <AssemblyVersion>1.19.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="resource" Type="Microsoft.Azure.Documents.Resource" />
      </Parameters>
      <Docs>
        <param name="resource">To be added.</param>
        <summary>
            <span data-ttu-id="f782a-104">Kopierkonstruktor für eine <see cref="T:Microsoft.Azure.Documents.Resource" /> im Azure-Cosmos-DB-Dienst verwendet.</span><span class="sxs-lookup"><span data-stu-id="f782a-104">Copy constructor for a <see cref="T:Microsoft.Azure.Documents.Resource" /> used in the Azure Cosmos DB service.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AltLink">
      <MemberSignature Language="C#" Value="public string AltLink { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string AltLink" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Documents.Resource.AltLink" />
      <MemberSignature Language="VB.NET" Value="Public Property AltLink As String" />
      <MemberSignature Language="F#" Value="member this.AltLink : string with get, set" Usage="Microsoft.Azure.Documents.Resource.AltLink" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DocumentDB.Core</AssemblyName>
        <AssemblyVersion>1.6.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.1.0</AssemblyVersion>
      </AssemblyInfo>
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
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="f782a-105">Ruft die Alt-Verknüpfung der Ressource aus dem Azure-Cosmos-DB-Dienst zugeordnet.</span><span class="sxs-lookup"><span data-stu-id="f782a-105">Gets the alt-link associated with the resource from the Azure Cosmos DB service.</span></span>
            </summary>
        <value><span data-ttu-id="f782a-106">Die Alt-Verknüpfung der Ressource zugeordnet.</span><span class="sxs-lookup"><span data-stu-id="f782a-106">The alt-link associated with the resource.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ETag">
      <MemberSignature Language="C#" Value="public string ETag { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ETag" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Documents.Resource.ETag" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ETag As String" />
      <MemberSignature Language="F#" Value="member this.ETag : string" Usage="Microsoft.Azure.Documents.Resource.ETag" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DocumentDB.Core</AssemblyName>
        <AssemblyVersion>1.6.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.1.0</AssemblyVersion>
      </AssemblyInfo>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Documents.Client</AssemblyName>
        <AssemblyVersion>1.18.0.0</AssemblyVersion>
        <AssemblyVersion>1.19.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="_etag")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="f782a-107">Ruft das Entitätstag aus dem Azure-Cosmos-DB-Dienst zur Ressource zugeordnete ab.</span><span class="sxs-lookup"><span data-stu-id="f782a-107">Gets the entity tag associated with the resource from the Azure Cosmos DB service.</span></span>
            </summary>
        <value>
            <span data-ttu-id="f782a-108">Die Entitäts-Tag, das der Ressource zugeordnet ist.</span><span class="sxs-lookup"><span data-stu-id="f782a-108">The entity tag associated with the resource.</span></span>
            </value>
        <remarks>
            <span data-ttu-id="f782a-109">Etags mit werden für parallelitätsprüfung beim Aktualisieren von Ressourcen verwendet.</span><span class="sxs-lookup"><span data-stu-id="f782a-109">ETags are used for concurrency checking when updating resources.</span></span> 
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="GetPropertyValue&lt;T&gt;">
      <MemberSignature Language="C#" Value="public T GetPropertyValue&lt;T&gt; (string propertyName);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance !!T GetPropertyValue&lt;T&gt;(string propertyName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.Resource.GetPropertyValue``1(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function GetPropertyValue(Of T) (propertyName As String) As T" />
      <MemberSignature Language="F#" Value="member this.GetPropertyValue : string -&gt; 'T" Usage="resource.GetPropertyValue propertyName" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DocumentDB.Core</AssemblyName>
        <AssemblyVersion>1.6.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.1.0</AssemblyVersion>
      </AssemblyInfo>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Documents.Client</AssemblyName>
        <AssemblyVersion>1.18.0.0</AssemblyVersion>
        <AssemblyVersion>1.19.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>T</ReturnType>
      </ReturnValue>
      <TypeParameters>
        <TypeParameter Name="T" />
      </TypeParameters>
      <Parameters>
        <Parameter Name="propertyName" Type="System.String" />
      </Parameters>
      <Docs>
        <typeparam name="T"><span data-ttu-id="f782a-110">Der Typ der Eigenschaft.</span><span class="sxs-lookup"><span data-stu-id="f782a-110">The type of the property.</span></span></typeparam>
        <param name="propertyName"><span data-ttu-id="f782a-111">Der Name der Eigenschaft.</span><span class="sxs-lookup"><span data-stu-id="f782a-111">The name of the property.</span></span></param>
        <summary>
            <span data-ttu-id="f782a-112">Ruft den angegebenen Eigenschaftennamen aus dem Azure-Cosmos-DB-Dienst zugeordneten Eigenschaftswert ab.</span><span class="sxs-lookup"><span data-stu-id="f782a-112">Gets property value associated with the specified property name from the Azure Cosmos DB service.</span></span>
            </summary>
        <returns><span data-ttu-id="f782a-113">Der Eigenschaftswert.</span><span class="sxs-lookup"><span data-stu-id="f782a-113">The property value.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Id">
      <MemberSignature Language="C#" Value="public virtual string Id { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Id" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Documents.Resource.Id" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Property Id As String" />
      <MemberSignature Language="F#" Value="member this.Id : string with get, set" Usage="Microsoft.Azure.Documents.Resource.Id" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DocumentDB.Core</AssemblyName>
        <AssemblyVersion>1.6.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.1.0</AssemblyVersion>
      </AssemblyInfo>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Documents.Client</AssemblyName>
        <AssemblyVersion>1.18.0.0</AssemblyVersion>
        <AssemblyVersion>1.19.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="id")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="f782a-114">Ruft ab oder legt die Id der Ressource in der Azure-Cosmos-DB-Dienst fest.</span><span class="sxs-lookup"><span data-stu-id="f782a-114">Gets or sets the Id of the resource in the Azure Cosmos DB service.</span></span>
            </summary>
        <value><span data-ttu-id="f782a-115">Die Id der Ressource zugeordnet ist.</span><span class="sxs-lookup"><span data-stu-id="f782a-115">The Id associated with the resource.</span></span></value>
        <remarks>
          <para>
            <span data-ttu-id="f782a-116">Jede Ressource in einem Azure-Cosmos-DB-Datenbank-Konto muss über einen eindeutigen Bezeichner verfügen.</span><span class="sxs-lookup"><span data-stu-id="f782a-116">Every resource within an Azure Cosmos DB database account needs to have a unique identifier.</span></span> <span data-ttu-id="f782a-117">Im Gegensatz zu <see cref="P:Microsoft.Azure.Documents.Resource.ResourceId" />, die intern festgelegt ist, wird diese Id wird vom Benutzer festlegbaren und unveränderlich ist.</span><span class="sxs-lookup"><span data-stu-id="f782a-117">Unlike <see cref="P:Microsoft.Azure.Documents.Resource.ResourceId" />, which is set internally, this Id is settable by the user and is not immutable.</span></span>
            </para>
          <para>
            <span data-ttu-id="f782a-118">Bei der Arbeit mit Dokumentressourcen bieten sie ebenfalls diese Id-Eigenschaft festgelegt werden.</span><span class="sxs-lookup"><span data-stu-id="f782a-118">When working with document resources, they too have this settable Id property.</span></span> <span data-ttu-id="f782a-119">Wenn eine Id nicht vom Benutzer bereitgestellt wird das SDK automatisch eine neue GUID generiert und weisen den Wert dieser Eigenschaft vor dem das Dokument in der Datenbank beibehalten.</span><span class="sxs-lookup"><span data-stu-id="f782a-119">If an Id is not supplied by the user the SDK will automatically generate a new GUID and assign its value to this property before persisting the document in the database.</span></span> <span data-ttu-id="f782a-120">Sie können diese Id der automatischen Generierung überschreiben, indem Sie den DisableAutomaticIdGeneration-Parameter festlegen, auf die <see cref="T:Microsoft.Azure.Documents.Client.DocumentClient" /> Instanz auf "true".</span><span class="sxs-lookup"><span data-stu-id="f782a-120">You can override this auto Id generation by setting the disableAutomaticIdGeneration parameter on the <see cref="T:Microsoft.Azure.Documents.Client.DocumentClient" /> instance to true.</span></span>
            <span data-ttu-id="f782a-121">Dadurch wird verhindert, dass das SDK generieren neue Ids.</span><span class="sxs-lookup"><span data-stu-id="f782a-121">This will prevent the SDK from generating new Ids.</span></span> 
            </para>
          <para>
            <span data-ttu-id="f782a-122">Die folgenden Zeichen sind beschränkt und kann nicht in die Id-Eigenschaft verwendet werden: '/', '\\','?', '#'</span><span class="sxs-lookup"><span data-stu-id="f782a-122">The following characters are restricted and cannot be used in the Id property: '/', '\\', '?', '#'</span></span>
             </para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="ResourceId">
      <MemberSignature Language="C#" Value="public virtual string ResourceId { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ResourceId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Documents.Resource.ResourceId" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Property ResourceId As String" />
      <MemberSignature Language="F#" Value="member this.ResourceId : string with get, set" Usage="Microsoft.Azure.Documents.Resource.ResourceId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DocumentDB.Core</AssemblyName>
        <AssemblyVersion>1.6.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.1.0</AssemblyVersion>
      </AssemblyInfo>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Documents.Client</AssemblyName>
        <AssemblyVersion>1.18.0.0</AssemblyVersion>
        <AssemblyVersion>1.19.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="_rid")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="f782a-123">Ruft ab oder legt die Ressourcen-Id der Ressource in der Azure-Cosmos-Datenbank zugeordnet.</span><span class="sxs-lookup"><span data-stu-id="f782a-123">Gets or sets the Resource Id associated with the resource in the Azure Cosmos DB service.</span></span>
            </summary>
        <value>
            <span data-ttu-id="f782a-124">Die Ressourcen-Id der Ressource zugeordnet.</span><span class="sxs-lookup"><span data-stu-id="f782a-124">The Resource Id associated with the resource.</span></span>
            </value>
        <remarks>
            <span data-ttu-id="f782a-125">Eine Ressourcen-Id ist der eindeutige, unveränderliche-Bezeichner, die jeder Azure-Cosmos-DB-Ressource zugewiesen ist, ob eine Datenbank, eine Auflistung oder ein Dokument ist.</span><span class="sxs-lookup"><span data-stu-id="f782a-125">A Resource Id is the unique, immutable, identifier assigned to each Azure Cosmos DB resource whether that is a database, a collection or a document.</span></span>
            <span data-ttu-id="f782a-126">Diese Ressourcen-Ids werden verwendet, wenn Sie SelfLinks, eine statische adressierbaren Uri für jede Ressource innerhalb eines Kontos für Datenbank erstellen.</span><span class="sxs-lookup"><span data-stu-id="f782a-126">These resource ids are used when building up SelfLinks, a static addressable Uri for each resource within a database account.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="SelfLink">
      <MemberSignature Language="C#" Value="public string SelfLink { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string SelfLink" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Documents.Resource.SelfLink" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property SelfLink As String" />
      <MemberSignature Language="F#" Value="member this.SelfLink : string" Usage="Microsoft.Azure.Documents.Resource.SelfLink" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DocumentDB.Core</AssemblyName>
        <AssemblyVersion>1.6.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.1.0</AssemblyVersion>
      </AssemblyInfo>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Documents.Client</AssemblyName>
        <AssemblyVersion>1.18.0.0</AssemblyVersion>
        <AssemblyVersion>1.19.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="_self")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="f782a-127">Ruft ab, der Self-link der Ressource mit dem der Dienst Azure-Cosmos-Datenbank zugeordnet.</span><span class="sxs-lookup"><span data-stu-id="f782a-127">Gets the self-link associated with the resource from the Azure Cosmos DB service.</span></span>
            </summary>
        <value><span data-ttu-id="f782a-128">Der Self-link der Ressource zugeordnet.</span><span class="sxs-lookup"><span data-stu-id="f782a-128">The self-link associated with the resource.</span></span></value>
        <remarks>
            <span data-ttu-id="f782a-129">Self-link ist eine statische adressierbaren Uri für jede Ressource innerhalb eines Kontos für Datenbank und das Azure-Cosmos-DB-Ressourcenmodell folgt.</span><span class="sxs-lookup"><span data-stu-id="f782a-129">A self-link is a static addressable Uri for each resource within a database account and follows the Azure Cosmos DB resource model.</span></span>
            <span data-ttu-id="f782a-130">Beispiel:</span><span class="sxs-lookup"><span data-stu-id="f782a-130">E.g.</span></span> <span data-ttu-id="f782a-131">Self-link für ein Dokument kann Dbs/Db_resourceid/colls/Coll_resourceid/Dokumente/Doc_resourceid sein.</span><span class="sxs-lookup"><span data-stu-id="f782a-131">a self-link for a document could be dbs/db_resourceid/colls/coll_resourceid/documents/doc_resourceid</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="SetPropertyValue">
      <MemberSignature Language="C#" Value="public void SetPropertyValue (string propertyName, object propertyValue);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance void SetPropertyValue(string propertyName, object propertyValue) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.Resource.SetPropertyValue(System.String,System.Object)" />
      <MemberSignature Language="VB.NET" Value="Public Sub SetPropertyValue (propertyName As String, propertyValue As Object)" />
      <MemberSignature Language="F#" Value="member this.SetPropertyValue : string * obj -&gt; unit" Usage="resource.SetPropertyValue (propertyName, propertyValue)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DocumentDB.Core</AssemblyName>
        <AssemblyVersion>1.6.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.1.0</AssemblyVersion>
      </AssemblyInfo>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Documents.Client</AssemblyName>
        <AssemblyVersion>1.18.0.0</AssemblyVersion>
        <AssemblyVersion>1.19.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="propertyName" Type="System.String" />
        <Parameter Name="propertyValue" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="propertyName"><span data-ttu-id="f782a-132">Der Name der Eigenschaft.</span><span class="sxs-lookup"><span data-stu-id="f782a-132">The name of the property.</span></span></param>
        <param name="propertyValue"><span data-ttu-id="f782a-133">Der Eigenschaftswert.</span><span class="sxs-lookup"><span data-stu-id="f782a-133">The property value.</span></span></param>
        <summary>
            <span data-ttu-id="f782a-134">Legt den angegebenen Eigenschaftennamen im Azure-Cosmos-DB-Dienst zugeordneten Eigenschaftswert fest.</span><span class="sxs-lookup"><span data-stu-id="f782a-134">Sets property value associated with the specified property name in the Azure Cosmos DB service.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Timestamp">
      <MemberSignature Language="C#" Value="public virtual DateTime Timestamp { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.DateTime Timestamp" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Documents.Resource.Timestamp" />
      <MemberSignature Language="VB.NET" Value="Public Overridable ReadOnly Property Timestamp As DateTime" />
      <MemberSignature Language="F#" Value="member this.Timestamp : DateTime" Usage="Microsoft.Azure.Documents.Resource.Timestamp" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DocumentDB.Core</AssemblyName>
        <AssemblyVersion>1.6.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.1.0</AssemblyVersion>
      </AssemblyInfo>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Documents.Client</AssemblyName>
        <AssemblyVersion>1.18.0.0</AssemblyVersion>
        <AssemblyVersion>1.19.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonConverter(typeof(Microsoft.Azure.Documents.UnixDateTimeConverter))</AttributeName>
        </Attribute>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="_ts")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.DateTime</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="f782a-135">Ruft den Zeitstempel der letzten Änderung der Ressource mit dem der Dienst Azure-Cosmos-Datenbank zugeordnet.</span><span class="sxs-lookup"><span data-stu-id="f782a-135">Gets the last modified timestamp associated with the resource from the Azure Cosmos DB service.</span></span>
            </summary>
        <value><span data-ttu-id="f782a-136">Der Zeitstempel der letzten Änderung der Ressource zugeordnet.</span><span class="sxs-lookup"><span data-stu-id="f782a-136">The last modified timestamp associated with the resource.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ToByteArray">
      <MemberSignature Language="C#" Value="public byte[] ToByteArray ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance unsigned int8[] ToByteArray() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.Resource.ToByteArray" />
      <MemberSignature Language="VB.NET" Value="Public Function ToByteArray () As Byte()" />
      <MemberSignature Language="F#" Value="member this.ToByteArray : unit -&gt; byte[]" Usage="resource.ToByteArray " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DocumentDB.Core</AssemblyName>
        <AssemblyVersion>1.6.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.1.0</AssemblyVersion>
      </AssemblyInfo>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Documents.Client</AssemblyName>
        <AssemblyVersion>1.18.0.0</AssemblyVersion>
        <AssemblyVersion>1.19.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Byte[]</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="f782a-137">Serialisieren Sie in ein Bytearray über SaveTo für den Azure-Cosmos-DB-Dienst.</span><span class="sxs-lookup"><span data-stu-id="f782a-137">Serialize to a byte array via SaveTo for the Azure Cosmos DB service.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>