<Type Name="IndexingParameters" FullName="Microsoft.Azure.Search.Models.IndexingParameters">
  <TypeSignature Language="C#" Value="public class IndexingParameters" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit IndexingParameters extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Search.Models.IndexingParameters" />
  <TypeSignature Language="VB.NET" Value="Public Class IndexingParameters" />
  <TypeSignature Language="F#" Value="type IndexingParameters = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Search</AssemblyName>
    <AssemblyVersion>3.0.0.0</AssemblyVersion>
    <AssemblyVersion>4.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="300f1-101">Stellt Parameter für die indexerausführung dar.</span><span class="sxs-lookup"><span data-stu-id="300f1-101">Represents parameters for indexer execution.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public IndexingParameters ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.Models.IndexingParameters.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="300f1-102">Initialisiert eine neue Instanz der "indexingparameters"-Klasse.</span><span class="sxs-lookup"><span data-stu-id="300f1-102">Initializes a new instance of the IndexingParameters class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public IndexingParameters (Nullable&lt;int&gt; batchSize = null, Nullable&lt;int&gt; maxFailedItems = null, Nullable&lt;int&gt; maxFailedItemsPerBatch = null, System.Collections.Generic.IDictionary&lt;string,object&gt; configuration = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(valuetype System.Nullable`1&lt;int32&gt; batchSize, valuetype System.Nullable`1&lt;int32&gt; maxFailedItems, valuetype System.Nullable`1&lt;int32&gt; maxFailedItemsPerBatch, class System.Collections.Generic.IDictionary`2&lt;string, object&gt; configuration) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.Models.IndexingParameters.#ctor(System.Nullable{System.Int32},System.Nullable{System.Int32},System.Nullable{System.Int32},System.Collections.Generic.IDictionary{System.String,System.Object})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional batchSize As Nullable(Of Integer) = null, Optional maxFailedItems As Nullable(Of Integer) = null, Optional maxFailedItemsPerBatch As Nullable(Of Integer) = null, Optional configuration As IDictionary(Of String, Object) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Search.Models.IndexingParameters : Nullable&lt;int&gt; * Nullable&lt;int&gt; * Nullable&lt;int&gt; * System.Collections.Generic.IDictionary&lt;string, obj&gt; -&gt; Microsoft.Azure.Search.Models.IndexingParameters" Usage="new Microsoft.Azure.Search.Models.IndexingParameters (batchSize, maxFailedItems, maxFailedItemsPerBatch, configuration)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="batchSize" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="maxFailedItems" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="maxFailedItemsPerBatch" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="configuration" Type="System.Collections.Generic.IDictionary&lt;System.String,System.Object&gt;" />
      </Parameters>
      <Docs>
        <param name="batchSize">To be added.</param>
        <param name="maxFailedItems">To be added.</param>
        <param name="maxFailedItemsPerBatch">To be added.</param>
        <param name="configuration">To be added.</param>
        <summary>
            <span data-ttu-id="300f1-103">Initialisiert eine neue Instanz der "indexingparameters"-Klasse.</span><span class="sxs-lookup"><span data-stu-id="300f1-103">Initializes a new instance of the IndexingParameters class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Base64EncodeKeys">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; Base64EncodeKeys { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; Base64EncodeKeys" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Search.Models.IndexingParameters.Base64EncodeKeys" />
      <MemberSignature Language="VB.NET" Value="Public Property Base64EncodeKeys As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.Base64EncodeKeys : Nullable&lt;bool&gt; with get, set" Usage="Microsoft.Azure.Search.Models.IndexingParameters.Base64EncodeKeys" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="base64EncodeKeys")</AttributeName>
        </Attribute>
        <Attribute>
          <AttributeName>System.Obsolete("This property is obsolete. Please create a field mapping using 'FieldMapping.Base64Encode' instead.")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="300f1-104">Ruft ab oder legt sie fest, ob der Indexer base64-codiert alle Werte, die in das Schlüsselfeld des zielindexes eingefügt werden.</span><span class="sxs-lookup"><span data-stu-id="300f1-104">Gets or sets whether indexer will base64-encode all values that are inserted into key field of the target index.</span></span> <span data-ttu-id="300f1-105">Dies ist erforderlich, wenn Schlüssel Zeichen enthalten können, die in Schlüsseln ungültig sind (z. B. einen Punkt ".").</span><span class="sxs-lookup"><span data-stu-id="300f1-105">This is needed if keys can contain characters that are invalid in keys (such as dot '.').</span></span> <span data-ttu-id="300f1-106">Die Standardeinstellung ist "false".</span><span class="sxs-lookup"><span data-stu-id="300f1-106">Default is false.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BatchSize">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; BatchSize { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; BatchSize" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Search.Models.IndexingParameters.BatchSize" />
      <MemberSignature Language="VB.NET" Value="Public Property BatchSize As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.BatchSize : Nullable&lt;int&gt; with get, set" Usage="Microsoft.Azure.Search.Models.IndexingParameters.BatchSize" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="batchSize")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="300f1-107">Ruft ab oder legt die Anzahl der Elemente, die aus der Datenquelle gelesen und indiziert werden als einzelner Batch, um die Leistung zu verbessern.</span><span class="sxs-lookup"><span data-stu-id="300f1-107">Gets or sets the number of items that are read from the data source and indexed as a single batch in order to improve performance.</span></span> <span data-ttu-id="300f1-108">Der Standardwert hängt vom Typ der Datenquelle ab.</span><span class="sxs-lookup"><span data-stu-id="300f1-108">The default depends on the data source type.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Configuration">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IDictionary&lt;string,object&gt; Configuration { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IDictionary`2&lt;string, object&gt; Configuration" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Search.Models.IndexingParameters.Configuration" />
      <MemberSignature Language="VB.NET" Value="Public Property Configuration As IDictionary(Of String, Object)" />
      <MemberSignature Language="F#" Value="member this.Configuration : System.Collections.Generic.IDictionary&lt;string, obj&gt; with get, set" Usage="Microsoft.Azure.Search.Models.IndexingParameters.Configuration" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="configuration")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IDictionary&lt;System.String,System.Object&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="300f1-109">Ermittelt oder definiert ein Wörterbuch von Indexer-spezifische Konfigurationseigenschaften.</span><span class="sxs-lookup"><span data-stu-id="300f1-109">Gets or sets a dictionary of indexer-specific configuration properties.</span></span> <span data-ttu-id="300f1-110">Jeder Name ist der Name einer bestimmten Eigenschaft.</span><span class="sxs-lookup"><span data-stu-id="300f1-110">Each name is the name of a specific property.</span></span> <span data-ttu-id="300f1-111">Jeder Wert muss ein primitiver Typ sein.</span><span class="sxs-lookup"><span data-stu-id="300f1-111">Each value must be of a primitive type.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MaxFailedItems">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; MaxFailedItems { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; MaxFailedItems" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Search.Models.IndexingParameters.MaxFailedItems" />
      <MemberSignature Language="VB.NET" Value="Public Property MaxFailedItems As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.MaxFailedItems : Nullable&lt;int&gt; with get, set" Usage="Microsoft.Azure.Search.Models.IndexingParameters.MaxFailedItems" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="maxFailedItems")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="300f1-112">Ruft ab oder legt die maximale Anzahl von Elementen, die für die indexerausführung weiterhin als erfolgreich betrachtet werden die Indizierung fehlschlagen kann.</span><span class="sxs-lookup"><span data-stu-id="300f1-112">Gets or sets the maximum number of items that can fail indexing for indexer execution to still be considered successful.</span></span> <span data-ttu-id="300f1-113">-1 bedeutet keine Beschränkung.</span><span class="sxs-lookup"><span data-stu-id="300f1-113">-1 means no limit.</span></span> <span data-ttu-id="300f1-114">Der Standardwert ist 0.</span><span class="sxs-lookup"><span data-stu-id="300f1-114">Default is 0.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MaxFailedItemsPerBatch">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; MaxFailedItemsPerBatch { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; MaxFailedItemsPerBatch" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Search.Models.IndexingParameters.MaxFailedItemsPerBatch" />
      <MemberSignature Language="VB.NET" Value="Public Property MaxFailedItemsPerBatch As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.MaxFailedItemsPerBatch : Nullable&lt;int&gt; with get, set" Usage="Microsoft.Azure.Search.Models.IndexingParameters.MaxFailedItemsPerBatch" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="maxFailedItemsPerBatch")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="300f1-115">Ruft ab oder legt die maximale Anzahl von Elementen in einem einzigen Batch, der Indizierung fehlschlagen darf die Indizierung für den Batch weiterhin als erfolgreich betrachtet werden.</span><span class="sxs-lookup"><span data-stu-id="300f1-115">Gets or sets the maximum number of items in a single batch that can fail indexing for the batch to still be considered successful.</span></span> <span data-ttu-id="300f1-116">-1 bedeutet keine Beschränkung.</span><span class="sxs-lookup"><span data-stu-id="300f1-116">-1 means no limit.</span></span> <span data-ttu-id="300f1-117">Der Standardwert ist 0.</span><span class="sxs-lookup"><span data-stu-id="300f1-117">Default is 0.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>