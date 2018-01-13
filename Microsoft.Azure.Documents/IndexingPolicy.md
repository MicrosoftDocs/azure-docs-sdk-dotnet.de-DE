<Type Name="IndexingPolicy" FullName="Microsoft.Azure.Documents.IndexingPolicy">
  <TypeSignature Language="C#" Value="public sealed class IndexingPolicy : Microsoft.Azure.Documents.JsonSerializable, ICloneable" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit IndexingPolicy extends Microsoft.Azure.Documents.JsonSerializable implements class System.ICloneable" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Documents.IndexingPolicy" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class IndexingPolicy&#xA;Inherits JsonSerializable&#xA;Implements ICloneable" />
  <TypeSignature Language="F#" Value="type IndexingPolicy = class&#xA;    inherit JsonSerializable&#xA;    interface ICloneable" />
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
  <Interfaces>
    <Interface>
      <InterfaceName>System.ICloneable</InterfaceName>
    </Interface>
  </Interfaces>
  <Docs>
    <summary>
            <span data-ttu-id="e0d49-101">Stellt die Indizierung Richtlinienkonfiguration für eine Sammlung in der Azure-Cosmos-DB-Dienst dar.</span><span class="sxs-lookup"><span data-stu-id="e0d49-101">Represents the indexing policy configuration for a collection in the Azure Cosmos DB service.</span></span>
            </summary>
    <remarks>
            <span data-ttu-id="e0d49-102">Richtlinien können Indizierung welche Eigenschaften (JSON-Pfade) eingeschlossen/ausgeschlossen werden, konfigurieren Sie, ob der Index ständig aktualisierte oder offline (lazy), die automatische im Vergleich zu opt-in pro-Dokument, als auch die Genauigkeit und den Typ des Indexes pro Pfad ist.</span><span class="sxs-lookup"><span data-stu-id="e0d49-102">Indexing policies can used to configure which properties (JSON paths) are included/excluded, whether the index is updated consistently or offline (lazy), automatic vs. opt-in per-document, as well as the precision and type of index per path.</span></span>
            <span data-ttu-id="e0d49-103"><para>Verweisen auf <see>http://azure.microsoft.com/documentation/articles/documentdb-indexing-policies/</see> zusätzliche Informationen zum indizierungsrichtlinien angeben.</para></span><span class="sxs-lookup"><span data-stu-id="e0d49-103"><para> Refer to <see>http://azure.microsoft.com/documentation/articles/documentdb-indexing-policies/</see> for additional information on how to specify indexing policies. </para></span></span></remarks>
    <altmember cref="T:Microsoft.Azure.Documents.DocumentCollection" />
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public IndexingPolicy ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.IndexingPolicy.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
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
            <span data-ttu-id="e0d49-104">Initialisiert eine neue Instanz der dem <see cref="T:Microsoft.Azure.Documents.IndexingPolicy" /> Klasse für den Azure-Cosmos-DB-Dienst.</span><span class="sxs-lookup"><span data-stu-id="e0d49-104">Initializes a new instance of the <see cref="T:Microsoft.Azure.Documents.IndexingPolicy" /> class for the Azure Cosmos DB service.</span></span>
            </summary>
        <remarks>
            <span data-ttu-id="e0d49-105">Indizierungsmodus ist konsistent auf festgelegt.</span><span class="sxs-lookup"><span data-stu-id="e0d49-105">Indexing mode is set to consistent.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public IndexingPolicy (params Microsoft.Azure.Documents.Index[] defaultIndexOverrides);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class Microsoft.Azure.Documents.Index[] defaultIndexOverrides) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.IndexingPolicy.#ctor(Microsoft.Azure.Documents.Index[])" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (ParamArray defaultIndexOverrides As Index())" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Documents.IndexingPolicy : Microsoft.Azure.Documents.Index[] -&gt; Microsoft.Azure.Documents.IndexingPolicy" Usage="new Microsoft.Azure.Documents.IndexingPolicy defaultIndexOverrides" />
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
        <Parameter Name="defaultIndexOverrides" Type="Microsoft.Azure.Documents.Index[]">
          <Attributes>
            <Attribute>
              <AttributeName>System.ParamArray</AttributeName>
            </Attribute>
          </Attributes>
        </Parameter>
      </Parameters>
      <Docs>
        <param name="defaultIndexOverrides"><span data-ttu-id="e0d49-106">Durch Trennzeichen getrennt Satz von Indizes, die als Index Standardspezifikationen für den Stammpfad dienen.</span><span class="sxs-lookup"><span data-stu-id="e0d49-106">Comma seperated set of indexes that serve as default index specifications for the root path.</span></span></param>
        <summary>
            <span data-ttu-id="e0d49-107">Initialisiert eine neue Instanz der dem <see cref="T:Microsoft.Azure.Documents.IndexingPolicy" /> Klasse mit dem angegebenen Satz von Indizes als Index Standardspezifikationen für den Root-Pfad für den Azure-Cosmos-DB-Dienst.</span><span class="sxs-lookup"><span data-stu-id="e0d49-107">Initializes a new instance of the <see cref="T:Microsoft.Azure.Documents.IndexingPolicy" /> class with the specified set of indexes as default index specifications for the root path for the Azure Cosmos DB service.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <altmember cref="T:Microsoft.Azure.Documents.Index" />
        <example>
            <span data-ttu-id="e0d49-108">Im folgende Beispiel veranschaulicht das Überschreiben der Standardeinstellung IndexingPolicy für Root-Pfad:</span><span class="sxs-lookup"><span data-stu-id="e0d49-108">The following example shows how to override the default indexingPolicy for root path:</span></span>
            <code language="c#"><![CDATA[
            HashIndex hashIndexOverride = Index.Hash(DataType.String, 5);
            RangeIndex rangeIndexOverride = Index.Range(DataType.Number, 2);
            SpatialIndex spatialIndexOverride = Index.Spatial(DataType.Point);
            
            IndexingPolicy indexingPolicy = new IndexingPolicy(hashIndexOverride, rangeIndexOverride, spatialIndexOverride);
            ]]></code></example>
        <example>
            <span data-ttu-id="e0d49-109">Wenn Sie nur die IndexingPolicy für Zahlen außer Kraft setzen möchten, können Sie genau angeben:</span><span class="sxs-lookup"><span data-stu-id="e0d49-109">If you would like to just override the indexingPolicy for Numbers you can specify just that:</span></span>
            <code language="c#"><![CDATA[
            RangeIndex rangeIndexOverride = Index.Range(DataType.Number, 2);
            
            IndexingPolicy indexingPolicy = new IndexingPolicy(rangeIndexOverride);
            ]]></code></example>
      </Docs>
    </Member>
    <Member MemberName="Automatic">
      <MemberSignature Language="C#" Value="public bool Automatic { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool Automatic" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Documents.IndexingPolicy.Automatic" />
      <MemberSignature Language="VB.NET" Value="Public Property Automatic As Boolean" />
      <MemberSignature Language="F#" Value="member this.Automatic : bool with get, set" Usage="Microsoft.Azure.Documents.IndexingPolicy.Automatic" />
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
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="automatic")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="e0d49-110">Ruft ab oder legt einen Wert, der angibt, ob die automatische Indizierung für eine Sammlung in der Azure-Cosmos-DB-Dienst aktiviert ist.</span><span class="sxs-lookup"><span data-stu-id="e0d49-110">Gets or sets a value that indicates whether automatic indexing is enabled for a collection in the Azure Cosmos DB service.</span></span>
            </summary>
        <value>
            <span data-ttu-id="e0d49-111">"True", wenn die automatische Indizierung aktiviert ist; andernfalls "false".</span><span class="sxs-lookup"><span data-stu-id="e0d49-111">True, if automatic indexing is enabled; otherwise, false.</span></span>
            </value>
        <remarks>
            <span data-ttu-id="e0d49-112">In die automatische Indizierung Dokumente können explizit ausgeschlossen werden von der Volltextindizierung Verwendung <see cref="T:Microsoft.Azure.Documents.Client.RequestOptions" />.</span><span class="sxs-lookup"><span data-stu-id="e0d49-112">In automatic indexing, documents can be explicitly excluded from indexing using <see cref="T:Microsoft.Azure.Documents.Client.RequestOptions" />.</span></span>  
            <span data-ttu-id="e0d49-113">Im manuellen Indizierung können Dokumente explizit eingefügt werden.</span><span class="sxs-lookup"><span data-stu-id="e0d49-113">In manual indexing, documents can be explicitly included.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="Clone">
      <MemberSignature Language="C#" Value="public object Clone ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance object Clone() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.IndexingPolicy.Clone" />
      <MemberSignature Language="VB.NET" Value="Public Function Clone () As Object" />
      <MemberSignature Language="F#" Value="abstract member Clone : unit -&gt; obj&#xA;override this.Clone : unit -&gt; obj" Usage="indexingPolicy.Clone " />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:System.ICloneable.Clone</InterfaceMember>
      </Implements>
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
        <ReturnType>System.Object</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="e0d49-114">Führt eine tiefe Kopie der indizierungsrichtlinie für den Azure-Cosmos-DB-Dienst an.</span><span class="sxs-lookup"><span data-stu-id="e0d49-114">Performs a deep copy of the indexing policy for the Azure Cosmos DB service.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="e0d49-115">Ein Klon der indizierungsrichtlinie.</span><span class="sxs-lookup"><span data-stu-id="e0d49-115">A clone of the indexing policy.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ExcludedPaths">
      <MemberSignature Language="C#" Value="public System.Collections.ObjectModel.Collection&lt;Microsoft.Azure.Documents.ExcludedPath&gt; ExcludedPaths { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.ObjectModel.Collection`1&lt;class Microsoft.Azure.Documents.ExcludedPath&gt; ExcludedPaths" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Documents.IndexingPolicy.ExcludedPaths" />
      <MemberSignature Language="VB.NET" Value="Public Property ExcludedPaths As Collection(Of ExcludedPath)" />
      <MemberSignature Language="F#" Value="member this.ExcludedPaths : System.Collections.ObjectModel.Collection&lt;Microsoft.Azure.Documents.ExcludedPath&gt; with get, set" Usage="Microsoft.Azure.Documents.IndexingPolicy.ExcludedPaths" />
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
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="excludedPaths")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.ObjectModel.Collection&lt;Microsoft.Azure.Documents.ExcludedPath&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="e0d49-116">Ruft ab oder legt sie fest, die Auflistung mit <see cref="T:Microsoft.Azure.Documents.ExcludedPath" /> Objekte in der Azure-Cosmos-DB-Dienst.</span><span class="sxs-lookup"><span data-stu-id="e0d49-116">Gets or sets the collection containing <see cref="T:Microsoft.Azure.Documents.ExcludedPath" /> objects in the Azure Cosmos DB service.</span></span>
            </summary>
        <value>
            <span data-ttu-id="e0d49-117">Die Auflistung mit <see cref="T:Microsoft.Azure.Documents.ExcludedPath" /> Objekte.</span><span class="sxs-lookup"><span data-stu-id="e0d49-117">The collection containing <see cref="T:Microsoft.Azure.Documents.ExcludedPath" /> objects.</span></span>
            </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IncludedPaths">
      <MemberSignature Language="C#" Value="public System.Collections.ObjectModel.Collection&lt;Microsoft.Azure.Documents.IncludedPath&gt; IncludedPaths { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.ObjectModel.Collection`1&lt;class Microsoft.Azure.Documents.IncludedPath&gt; IncludedPaths" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Documents.IndexingPolicy.IncludedPaths" />
      <MemberSignature Language="VB.NET" Value="Public Property IncludedPaths As Collection(Of IncludedPath)" />
      <MemberSignature Language="F#" Value="member this.IncludedPaths : System.Collections.ObjectModel.Collection&lt;Microsoft.Azure.Documents.IncludedPath&gt; with get, set" Usage="Microsoft.Azure.Documents.IndexingPolicy.IncludedPaths" />
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
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="includedPaths")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.ObjectModel.Collection&lt;Microsoft.Azure.Documents.IncludedPath&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="e0d49-118">Ruft ab oder legt sie fest, die Auflistung mit <see cref="T:Microsoft.Azure.Documents.IncludedPath" /> Objekte in der Azure-Cosmos-DB-Dienst.</span><span class="sxs-lookup"><span data-stu-id="e0d49-118">Gets or sets the collection containing <see cref="T:Microsoft.Azure.Documents.IncludedPath" /> objects in the Azure Cosmos DB service.</span></span>
            </summary>
        <value>
            <span data-ttu-id="e0d49-119">Die Auflistung mit <see cref="T:Microsoft.Azure.Documents.IncludedPath" /> Objekte.</span><span class="sxs-lookup"><span data-stu-id="e0d49-119">The collection containing <see cref="T:Microsoft.Azure.Documents.IncludedPath" /> objects.</span></span>
            </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IndexingMode">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Documents.IndexingMode IndexingMode { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype Microsoft.Azure.Documents.IndexingMode IndexingMode" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Documents.IndexingPolicy.IndexingMode" />
      <MemberSignature Language="VB.NET" Value="Public Property IndexingMode As IndexingMode" />
      <MemberSignature Language="F#" Value="member this.IndexingMode : Microsoft.Azure.Documents.IndexingMode with get, set" Usage="Microsoft.Azure.Documents.IndexingPolicy.IndexingMode" />
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
          <AttributeName>Newtonsoft.Json.JsonConverter(typeof(Newtonsoft.Json.Converters.StringEnumConverter))</AttributeName>
        </Attribute>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="indexingMode")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Documents.IndexingMode</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="e0d49-120">Ruft ab oder legt den indizierungsmodus ("consistent" und "lazy") im Azure-Cosmos-DB-Dienst.</span><span class="sxs-lookup"><span data-stu-id="e0d49-120">Gets or sets the indexing mode (consistent or lazy) in the Azure Cosmos DB service.</span></span>
            </summary>
        <value>
            <span data-ttu-id="e0d49-121">Einer der Werte von der <see cref="T:Microsoft.Azure.Documents.IndexingMode" /> Enumeration.</span><span class="sxs-lookup"><span data-stu-id="e0d49-121">One of the values of the <see cref="T:Microsoft.Azure.Documents.IndexingMode" /> enumeration.</span></span>
            </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>