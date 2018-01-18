<Type Name="AzureTableSink" FullName="Microsoft.Azure.Management.DataFactory.Models.AzureTableSink">
  <TypeSignature Language="C#" Value="public class AzureTableSink : Microsoft.Azure.Management.DataFactory.Models.CopySink" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit AzureTableSink extends Microsoft.Azure.Management.DataFactory.Models.CopySink" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.DataFactory.Models.AzureTableSink" />
  <TypeSignature Language="VB.NET" Value="Public Class AzureTableSink&#xA;Inherits CopySink" />
  <TypeSignature Language="F#" Value="type AzureTableSink = class&#xA;    inherit CopySink" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
    <AssemblyVersion>0.2.0.0</AssemblyVersion>
    <AssemblyVersion>0.3.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.Management.DataFactory.Models.CopySink</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="1dc29-101">Eine Kopie Aktivität Azure Table-Senke.</span><span class="sxs-lookup"><span data-stu-id="1dc29-101">A copy activity Azure Table sink.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public AzureTableSink ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.Models.AzureTableSink.#ctor" />
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
            <span data-ttu-id="1dc29-102">Initialisiert eine neue Instanz der AzureTableSink-Klasse.</span><span class="sxs-lookup"><span data-stu-id="1dc29-102">Initializes a new instance of the AzureTableSink class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public AzureTableSink (System.Collections.Generic.IDictionary&lt;string,object&gt; additionalProperties = null, object writeBatchSize = null, object writeBatchTimeout = null, object sinkRetryCount = null, object sinkRetryWait = null, object azureTableDefaultPartitionKeyValue = null, object azureTablePartitionKeyName = null, object azureTableRowKeyName = null, object azureTableInsertType = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.Collections.Generic.IDictionary`2&lt;string, object&gt; additionalProperties, object writeBatchSize, object writeBatchTimeout, object sinkRetryCount, object sinkRetryWait, object azureTableDefaultPartitionKeyValue, object azureTablePartitionKeyName, object azureTableRowKeyName, object azureTableInsertType) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.Models.AzureTableSink.#ctor(System.Collections.Generic.IDictionary{System.String,System.Object},System.Object,System.Object,System.Object,System.Object,System.Object,System.Object,System.Object,System.Object)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional additionalProperties As IDictionary(Of String, Object) = null, Optional writeBatchSize As Object = null, Optional writeBatchTimeout As Object = null, Optional sinkRetryCount As Object = null, Optional sinkRetryWait As Object = null, Optional azureTableDefaultPartitionKeyValue As Object = null, Optional azureTablePartitionKeyName As Object = null, Optional azureTableRowKeyName As Object = null, Optional azureTableInsertType As Object = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.DataFactory.Models.AzureTableSink : System.Collections.Generic.IDictionary&lt;string, obj&gt; * obj * obj * obj * obj * obj * obj * obj * obj -&gt; Microsoft.Azure.Management.DataFactory.Models.AzureTableSink" Usage="new Microsoft.Azure.Management.DataFactory.Models.AzureTableSink (additionalProperties, writeBatchSize, writeBatchTimeout, sinkRetryCount, sinkRetryWait, azureTableDefaultPartitionKeyValue, azureTablePartitionKeyName, azureTableRowKeyName, azureTableInsertType)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="additionalProperties" Type="System.Collections.Generic.IDictionary&lt;System.String,System.Object&gt;" />
        <Parameter Name="writeBatchSize" Type="System.Object" />
        <Parameter Name="writeBatchTimeout" Type="System.Object" />
        <Parameter Name="sinkRetryCount" Type="System.Object" />
        <Parameter Name="sinkRetryWait" Type="System.Object" />
        <Parameter Name="azureTableDefaultPartitionKeyValue" Type="System.Object" />
        <Parameter Name="azureTablePartitionKeyName" Type="System.Object" />
        <Parameter Name="azureTableRowKeyName" Type="System.Object" />
        <Parameter Name="azureTableInsertType" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="additionalProperties"><span data-ttu-id="1dc29-103">Nicht übereinstimmende Eigenschaften aus der Nachricht deserialisiert werden diese Sammlung</span><span class="sxs-lookup"><span data-stu-id="1dc29-103">Unmatched properties from the message are deserialized this collection</span></span></param>
        <param name="writeBatchSize"><span data-ttu-id="1dc29-104">Schreiben Sie die Batchgröße.</span><span class="sxs-lookup"><span data-stu-id="1dc29-104">Write batch size.</span></span> <span data-ttu-id="1dc29-105">Typ: ganze Zahl (oder Ausdrücke mit ganzzahligen ResultType-Element), minimum: 0.</span><span class="sxs-lookup"><span data-stu-id="1dc29-105">Type: integer (or Expression with resultType integer), minimum: 0.</span></span></param>
        <param name="writeBatchTimeout"><span data-ttu-id="1dc29-106">BatchTimeout zu schreiben.</span><span class="sxs-lookup"><span data-stu-id="1dc29-106">Write batch timeout.</span></span> <span data-ttu-id="1dc29-107">Typ: Zeichenfolge (oder Ausdruck mit ResultType-Zeichenfolge), Muster: ((\d+)\.)? () :(60| \d\d) ([0-5][0-9])): () 60 | ([0-5][0-9])).</span><span class="sxs-lookup"><span data-stu-id="1dc29-107">Type: string (or Expression with resultType string), pattern: ((\d+)\.)?(\d\d):(60|([0-5][0-9])):(60|([0-5][0-9])).</span></span></param>
        <param name="sinkRetryCount"><span data-ttu-id="1dc29-108">Sink Wiederholungsanzahl.</span><span class="sxs-lookup"><span data-stu-id="1dc29-108">Sink retry count.</span></span> <span data-ttu-id="1dc29-109">Typ: ganze Zahl (oder Ausdrücke mit ganzzahligen ResultType-Element).</span><span class="sxs-lookup"><span data-stu-id="1dc29-109">Type: integer (or Expression with resultType integer).</span></span></param>
        <param name="sinkRetryWait"><span data-ttu-id="1dc29-110">Sink Wiederholung warten.</span><span class="sxs-lookup"><span data-stu-id="1dc29-110">Sink retry wait.</span></span> <span data-ttu-id="1dc29-111">Typ: Zeichenfolge (oder Ausdruck mit ResultType-Zeichenfolge), Muster: ((\d+)\.)? () :(60| \d\d) ([0-5][0-9])): () 60 | ([0-5][0-9])).</span><span class="sxs-lookup"><span data-stu-id="1dc29-111">Type: string (or Expression with resultType string), pattern: ((\d+)\.)?(\d\d):(60|([0-5][0-9])):(60|([0-5][0-9])).</span></span></param>
        <param name="azureTableDefaultPartitionKeyValue"><span data-ttu-id="1dc29-112">Azure Tabelle standardmäßiger partitionsschlüsselwert.</span><span class="sxs-lookup"><span data-stu-id="1dc29-112">Azure Table default partition key value.</span></span> <span data-ttu-id="1dc29-113">Typ: Zeichenfolge (oder Ausdruck mit ResultType-Zeichenfolge).</span><span class="sxs-lookup"><span data-stu-id="1dc29-113">Type: string (or Expression with resultType string).</span></span></param>
        <param name="azureTablePartitionKeyName"><span data-ttu-id="1dc29-114">Azure Tabelle Partition Schlüsselname.</span><span class="sxs-lookup"><span data-stu-id="1dc29-114">Azure Table partition key name.</span></span> <span data-ttu-id="1dc29-115">Typ: Zeichenfolge (oder Ausdruck mit ResultType-Zeichenfolge).</span><span class="sxs-lookup"><span data-stu-id="1dc29-115">Type: string (or Expression with resultType string).</span></span></param>
        <param name="azureTableRowKeyName"><span data-ttu-id="1dc29-116">Azure Tabelle Zeile Schlüsselname.</span><span class="sxs-lookup"><span data-stu-id="1dc29-116">Azure Table row key name.</span></span> <span data-ttu-id="1dc29-117">Typ: Zeichenfolge (oder Ausdruck mit ResultType-Zeichenfolge).</span><span class="sxs-lookup"><span data-stu-id="1dc29-117">Type: string (or Expression with resultType string).</span></span></param>
        <param name="azureTableInsertType"><span data-ttu-id="1dc29-118">Typ wird von Azure-Tabelle einfügen.</span><span class="sxs-lookup"><span data-stu-id="1dc29-118">Azure Table insert type.</span></span> <span data-ttu-id="1dc29-119">Typ: Zeichenfolge (oder Ausdruck mit ResultType-Zeichenfolge).</span><span class="sxs-lookup"><span data-stu-id="1dc29-119">Type: string (or Expression with resultType string).</span></span></param>
        <summary>
            <span data-ttu-id="1dc29-120">Initialisiert eine neue Instanz der AzureTableSink-Klasse.</span><span class="sxs-lookup"><span data-stu-id="1dc29-120">Initializes a new instance of the AzureTableSink class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AzureTableDefaultPartitionKeyValue">
      <MemberSignature Language="C#" Value="public object AzureTableDefaultPartitionKeyValue { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance object AzureTableDefaultPartitionKeyValue" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.AzureTableSink.AzureTableDefaultPartitionKeyValue" />
      <MemberSignature Language="VB.NET" Value="Public Property AzureTableDefaultPartitionKeyValue As Object" />
      <MemberSignature Language="F#" Value="member this.AzureTableDefaultPartitionKeyValue : obj with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.AzureTableSink.AzureTableDefaultPartitionKeyValue" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="azureTableDefaultPartitionKeyValue")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Object</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="1dc29-121">Ruft ab oder legt Azure Tabelle standardmäßiger partitionsschlüsselwert.</span><span class="sxs-lookup"><span data-stu-id="1dc29-121">Gets or sets azure Table default partition key value.</span></span> <span data-ttu-id="1dc29-122">Typ: Zeichenfolge (oder Ausdruck mit ResultType-Zeichenfolge).</span><span class="sxs-lookup"><span data-stu-id="1dc29-122">Type: string (or Expression with resultType string).</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AzureTableInsertType">
      <MemberSignature Language="C#" Value="public object AzureTableInsertType { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance object AzureTableInsertType" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.AzureTableSink.AzureTableInsertType" />
      <MemberSignature Language="VB.NET" Value="Public Property AzureTableInsertType As Object" />
      <MemberSignature Language="F#" Value="member this.AzureTableInsertType : obj with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.AzureTableSink.AzureTableInsertType" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="azureTableInsertType")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Object</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="1dc29-123">Ruft ab oder legt ihn fest Azure Tabelle einfügen.</span><span class="sxs-lookup"><span data-stu-id="1dc29-123">Gets or sets azure Table insert type.</span></span> <span data-ttu-id="1dc29-124">Typ: Zeichenfolge (oder Ausdruck mit ResultType-Zeichenfolge).</span><span class="sxs-lookup"><span data-stu-id="1dc29-124">Type: string (or Expression with resultType string).</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AzureTablePartitionKeyName">
      <MemberSignature Language="C#" Value="public object AzureTablePartitionKeyName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance object AzureTablePartitionKeyName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.AzureTableSink.AzureTablePartitionKeyName" />
      <MemberSignature Language="VB.NET" Value="Public Property AzureTablePartitionKeyName As Object" />
      <MemberSignature Language="F#" Value="member this.AzureTablePartitionKeyName : obj with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.AzureTableSink.AzureTablePartitionKeyName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="azureTablePartitionKeyName")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Object</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="1dc29-125">Ruft ab, oder legt ihn fest Azure Tabelle Partition Schlüsselnamen.</span><span class="sxs-lookup"><span data-stu-id="1dc29-125">Gets or sets azure Table partition key name.</span></span> <span data-ttu-id="1dc29-126">Typ: Zeichenfolge (oder Ausdruck mit ResultType-Zeichenfolge).</span><span class="sxs-lookup"><span data-stu-id="1dc29-126">Type: string (or Expression with resultType string).</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AzureTableRowKeyName">
      <MemberSignature Language="C#" Value="public object AzureTableRowKeyName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance object AzureTableRowKeyName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.AzureTableSink.AzureTableRowKeyName" />
      <MemberSignature Language="VB.NET" Value="Public Property AzureTableRowKeyName As Object" />
      <MemberSignature Language="F#" Value="member this.AzureTableRowKeyName : obj with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.AzureTableSink.AzureTableRowKeyName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="azureTableRowKeyName")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Object</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="1dc29-127">Ruft ab, oder legt ihn fest Azure Tabelle Zeile Schlüsselnamen.</span><span class="sxs-lookup"><span data-stu-id="1dc29-127">Gets or sets azure Table row key name.</span></span> <span data-ttu-id="1dc29-128">Typ: Zeichenfolge (oder Ausdruck mit ResultType-Zeichenfolge).</span><span class="sxs-lookup"><span data-stu-id="1dc29-128">Type: string (or Expression with resultType string).</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>