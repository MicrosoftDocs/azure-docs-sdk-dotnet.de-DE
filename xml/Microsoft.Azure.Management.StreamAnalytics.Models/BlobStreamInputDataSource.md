<Type Name="BlobStreamInputDataSource" FullName="Microsoft.Azure.Management.StreamAnalytics.Models.BlobStreamInputDataSource">
  <TypeSignature Language="C#" Value="public class BlobStreamInputDataSource : Microsoft.Azure.Management.StreamAnalytics.Models.StreamInputDataSource" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit BlobStreamInputDataSource extends Microsoft.Azure.Management.StreamAnalytics.Models.StreamInputDataSource" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.StreamAnalytics.Models.BlobStreamInputDataSource" />
  <TypeSignature Language="VB.NET" Value="Public Class BlobStreamInputDataSource&#xA;Inherits StreamInputDataSource" />
  <TypeSignature Language="F#" Value="type BlobStreamInputDataSource = class&#xA;    inherit StreamInputDataSource" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
    <AssemblyVersion>2.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.Management.StreamAnalytics.Models.StreamInputDataSource</BaseTypeName>
  </Base>
  <Interfaces />
  <Attributes>
    <Attribute>
      <AttributeName>Microsoft.Rest.Serialization.JsonTransformation</AttributeName>
    </Attribute>
    <Attribute>
      <AttributeName>Newtonsoft.Json.JsonObject("Microsoft.Storage/Blob")</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            <span data-ttu-id="4c679-101">Beschreibt eine Eingabe Blob-Datenquelle, die datenstromdaten enthält.</span><span class="sxs-lookup"><span data-stu-id="4c679-101">Describes a blob input data source that contains stream data.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public BlobStreamInputDataSource ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StreamAnalytics.Models.BlobStreamInputDataSource.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="4c679-102">Initialisiert eine neue Instanz der BlobStreamInputDataSource-Klasse.</span><span class="sxs-lookup"><span data-stu-id="4c679-102">Initializes a new instance of the BlobStreamInputDataSource class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public BlobStreamInputDataSource (System.Collections.Generic.IList&lt;Microsoft.Azure.Management.StreamAnalytics.Models.StorageAccount&gt; storageAccounts = null, string container = null, string pathPattern = null, string dateFormat = null, string timeFormat = null, Nullable&lt;int&gt; sourcePartitionCount = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.StreamAnalytics.Models.StorageAccount&gt; storageAccounts, string container, string pathPattern, string dateFormat, string timeFormat, valuetype System.Nullable`1&lt;int32&gt; sourcePartitionCount) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StreamAnalytics.Models.BlobStreamInputDataSource.#ctor(System.Collections.Generic.IList{Microsoft.Azure.Management.StreamAnalytics.Models.StorageAccount},System.String,System.String,System.String,System.String,System.Nullable{System.Int32})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional storageAccounts As IList(Of StorageAccount) = null, Optional container As String = null, Optional pathPattern As String = null, Optional dateFormat As String = null, Optional timeFormat As String = null, Optional sourcePartitionCount As Nullable(Of Integer) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.StreamAnalytics.Models.BlobStreamInputDataSource : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.StreamAnalytics.Models.StorageAccount&gt; * string * string * string * string * Nullable&lt;int&gt; -&gt; Microsoft.Azure.Management.StreamAnalytics.Models.BlobStreamInputDataSource" Usage="new Microsoft.Azure.Management.StreamAnalytics.Models.BlobStreamInputDataSource (storageAccounts, container, pathPattern, dateFormat, timeFormat, sourcePartitionCount)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="storageAccounts" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Management.StreamAnalytics.Models.StorageAccount&gt;" />
        <Parameter Name="container" Type="System.String" />
        <Parameter Name="pathPattern" Type="System.String" />
        <Parameter Name="dateFormat" Type="System.String" />
        <Parameter Name="timeFormat" Type="System.String" />
        <Parameter Name="sourcePartitionCount" Type="System.Nullable&lt;System.Int32&gt;" />
      </Parameters>
      <Docs>
        <param name="storageAccounts"><span data-ttu-id="4c679-103">Eine Liste mit mindestens ein Azure-Speicherkonten.</span><span class="sxs-lookup"><span data-stu-id="4c679-103">A list of one or more Azure Storage accounts.</span></span> <span data-ttu-id="4c679-104">Auf (CreateOrReplace)-PUT-Anforderungen erforderlich.</span><span class="sxs-lookup"><span data-stu-id="4c679-104">Required on PUT (CreateOrReplace) requests.</span></span></param>
        <param name="container"><span data-ttu-id="4c679-105">Der Name eines Containers im zugeordneten Speicherkonto an.</span><span class="sxs-lookup"><span data-stu-id="4c679-105">The name of a container within the associated Storage account.</span></span> <span data-ttu-id="4c679-106">Dieser Container enthält entweder die gehörte aus gelesen oder geschrieben werden sollen.</span><span class="sxs-lookup"><span data-stu-id="4c679-106">This container contains either the blob(s) to be read from or written to.</span></span> <span data-ttu-id="4c679-107">Auf (CreateOrReplace)-PUT-Anforderungen erforderlich.</span><span class="sxs-lookup"><span data-stu-id="4c679-107">Required on PUT (CreateOrReplace) requests.</span></span></param>
        <param name="pathPattern"><span data-ttu-id="4c679-108">Das Muster für den Blob-Pfad.</span><span class="sxs-lookup"><span data-stu-id="4c679-108">The blob path pattern.</span></span> <span data-ttu-id="4c679-109">Regulärer Ausdruck.</span><span class="sxs-lookup"><span data-stu-id="4c679-109">Not a regular expression.</span></span> <span data-ttu-id="4c679-110">Er stellt ein Muster mit dem Blob Namen gesucht werden soll, um zu bestimmen, und zwar unabhängig davon, ob sie als Eingabe oder Ausgabe für den Auftrag eingeschlossen werden sollen.</span><span class="sxs-lookup"><span data-stu-id="4c679-110">It represents a pattern against which blob names will be matched to determine whether or not they should be included as input or output to the job.</span></span> <span data-ttu-id="4c679-111">Finden Sie unter https://docs.microsoft.com/en-us/rest/api/streamanalytics/stream-analytics-input oder https://docs.microsoft.com/en-us/rest/api/streamanalytics/stream-analytics-output für eine ausführlichere Erläuterung und ein Beispiel.</span><span class="sxs-lookup"><span data-stu-id="4c679-111">See https://docs.microsoft.com/en-us/rest/api/streamanalytics/stream-analytics-input or https://docs.microsoft.com/en-us/rest/api/streamanalytics/stream-analytics-output for a more detailed explanation and example.</span></span></param>
        <param name="dateFormat"><span data-ttu-id="4c679-112">Das Datumsformat.</span><span class="sxs-lookup"><span data-stu-id="4c679-112">The date format.</span></span> <span data-ttu-id="4c679-113">Wenn {Date} in der PathPattern angezeigt wird, ist der Wert dieser Eigenschaft als Datumsformat verwendet.</span><span class="sxs-lookup"><span data-stu-id="4c679-113">Wherever {date} appears in pathPattern, the value of this property is used as the date format instead.</span></span></param>
        <param name="timeFormat"><span data-ttu-id="4c679-114">Das Zeitformat.</span><span class="sxs-lookup"><span data-stu-id="4c679-114">The time format.</span></span> <span data-ttu-id="4c679-115">Wenn {Time} in der PathPattern angezeigt wird, ist der Wert dieser Eigenschaft als Uhrzeitformat verwendet.</span><span class="sxs-lookup"><span data-stu-id="4c679-115">Wherever {time} appears in pathPattern, the value of this property is used as the time format instead.</span></span></param>
        <param name="sourcePartitionCount"><span data-ttu-id="4c679-116">Die Anzahl der Partitionen von der Eingabedatenquelle Blob.</span><span class="sxs-lookup"><span data-stu-id="4c679-116">The partition count of the blob input data source.</span></span> <span data-ttu-id="4c679-117">Im Bereich 1-256.</span><span class="sxs-lookup"><span data-stu-id="4c679-117">Range 1 - 256.</span></span></param>
        <summary>
            <span data-ttu-id="4c679-118">Initialisiert eine neue Instanz der BlobStreamInputDataSource-Klasse.</span><span class="sxs-lookup"><span data-stu-id="4c679-118">Initializes a new instance of the BlobStreamInputDataSource class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Container">
      <MemberSignature Language="C#" Value="public string Container { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Container" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StreamAnalytics.Models.BlobStreamInputDataSource.Container" />
      <MemberSignature Language="VB.NET" Value="Public Property Container As String" />
      <MemberSignature Language="F#" Value="member this.Container : string with get, set" Usage="Microsoft.Azure.Management.StreamAnalytics.Models.BlobStreamInputDataSource.Container" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.container")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="4c679-119">Ruft ab oder legt den Namen eines Containers im zugeordneten Speicherkonto an.</span><span class="sxs-lookup"><span data-stu-id="4c679-119">Gets or sets the name of a container within the associated Storage account.</span></span> <span data-ttu-id="4c679-120">Dieser Container enthält entweder die gehörte aus gelesen oder geschrieben werden sollen.</span><span class="sxs-lookup"><span data-stu-id="4c679-120">This container contains either the blob(s) to be read from or written to.</span></span> <span data-ttu-id="4c679-121">Auf (CreateOrReplace)-PUT-Anforderungen erforderlich.</span><span class="sxs-lookup"><span data-stu-id="4c679-121">Required on PUT (CreateOrReplace) requests.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DateFormat">
      <MemberSignature Language="C#" Value="public string DateFormat { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string DateFormat" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StreamAnalytics.Models.BlobStreamInputDataSource.DateFormat" />
      <MemberSignature Language="VB.NET" Value="Public Property DateFormat As String" />
      <MemberSignature Language="F#" Value="member this.DateFormat : string with get, set" Usage="Microsoft.Azure.Management.StreamAnalytics.Models.BlobStreamInputDataSource.DateFormat" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.dateFormat")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="4c679-122">Ruft ab oder legt das Datumsformat.</span><span class="sxs-lookup"><span data-stu-id="4c679-122">Gets or sets the date format.</span></span> <span data-ttu-id="4c679-123">Wenn {Date} in der PathPattern angezeigt wird, ist der Wert dieser Eigenschaft als Datumsformat verwendet.</span><span class="sxs-lookup"><span data-stu-id="4c679-123">Wherever {date} appears in pathPattern, the value of this property is used as the date format instead.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PathPattern">
      <MemberSignature Language="C#" Value="public string PathPattern { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string PathPattern" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StreamAnalytics.Models.BlobStreamInputDataSource.PathPattern" />
      <MemberSignature Language="VB.NET" Value="Public Property PathPattern As String" />
      <MemberSignature Language="F#" Value="member this.PathPattern : string with get, set" Usage="Microsoft.Azure.Management.StreamAnalytics.Models.BlobStreamInputDataSource.PathPattern" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.pathPattern")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="4c679-124">Abrufen oder Festlegen der Blob-Pfad-Muster.</span><span class="sxs-lookup"><span data-stu-id="4c679-124">Gets or sets the blob path pattern.</span></span> <span data-ttu-id="4c679-125">Regulärer Ausdruck.</span><span class="sxs-lookup"><span data-stu-id="4c679-125">Not a regular expression.</span></span> <span data-ttu-id="4c679-126">Er stellt ein Muster mit dem Blob Namen gesucht werden soll, um zu bestimmen, und zwar unabhängig davon, ob sie als Eingabe oder Ausgabe für den Auftrag eingeschlossen werden sollen.</span><span class="sxs-lookup"><span data-stu-id="4c679-126">It represents a pattern against which blob names will be matched to determine whether or not they should be included as input or output to the job.</span></span> <span data-ttu-id="4c679-127">Finden Sie unter https://docs.microsoft.com/en-us/rest/api/streamanalytics/stream-analytics-input oder https://docs.microsoft.com/en-us/rest/api/streamanalytics/stream-analytics-output für eine ausführlichere Erläuterung und ein Beispiel.</span><span class="sxs-lookup"><span data-stu-id="4c679-127">See https://docs.microsoft.com/en-us/rest/api/streamanalytics/stream-analytics-input or https://docs.microsoft.com/en-us/rest/api/streamanalytics/stream-analytics-output for a more detailed explanation and example.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SourcePartitionCount">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; SourcePartitionCount { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; SourcePartitionCount" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StreamAnalytics.Models.BlobStreamInputDataSource.SourcePartitionCount" />
      <MemberSignature Language="VB.NET" Value="Public Property SourcePartitionCount As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.SourcePartitionCount : Nullable&lt;int&gt; with get, set" Usage="Microsoft.Azure.Management.StreamAnalytics.Models.BlobStreamInputDataSource.SourcePartitionCount" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.sourcePartitionCount")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="4c679-128">Ruft ab oder legt die Anzahl der Partitionen von der Eingabedatenquelle Blob.</span><span class="sxs-lookup"><span data-stu-id="4c679-128">Gets or sets the partition count of the blob input data source.</span></span>
            <span data-ttu-id="4c679-129">Im Bereich 1-256.</span><span class="sxs-lookup"><span data-stu-id="4c679-129">Range 1 - 256.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="StorageAccounts">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Management.StreamAnalytics.Models.StorageAccount&gt; StorageAccounts { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.StreamAnalytics.Models.StorageAccount&gt; StorageAccounts" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StreamAnalytics.Models.BlobStreamInputDataSource.StorageAccounts" />
      <MemberSignature Language="VB.NET" Value="Public Property StorageAccounts As IList(Of StorageAccount)" />
      <MemberSignature Language="F#" Value="member this.StorageAccounts : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.StreamAnalytics.Models.StorageAccount&gt; with get, set" Usage="Microsoft.Azure.Management.StreamAnalytics.Models.BlobStreamInputDataSource.StorageAccounts" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.storageAccounts")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Management.StreamAnalytics.Models.StorageAccount&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="4c679-130">Ruft ab oder legt eine Liste von einem oder mehreren Azure-Speicher-Konten.</span><span class="sxs-lookup"><span data-stu-id="4c679-130">Gets or sets a list of one or more Azure Storage accounts.</span></span> <span data-ttu-id="4c679-131">Auf (CreateOrReplace)-PUT-Anforderungen erforderlich.</span><span class="sxs-lookup"><span data-stu-id="4c679-131">Required on PUT (CreateOrReplace) requests.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TimeFormat">
      <MemberSignature Language="C#" Value="public string TimeFormat { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string TimeFormat" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StreamAnalytics.Models.BlobStreamInputDataSource.TimeFormat" />
      <MemberSignature Language="VB.NET" Value="Public Property TimeFormat As String" />
      <MemberSignature Language="F#" Value="member this.TimeFormat : string with get, set" Usage="Microsoft.Azure.Management.StreamAnalytics.Models.BlobStreamInputDataSource.TimeFormat" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.timeFormat")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="4c679-132">Ruft ab oder legt das Zeitformat.</span><span class="sxs-lookup"><span data-stu-id="4c679-132">Gets or sets the time format.</span></span> <span data-ttu-id="4c679-133">Wenn {Time} in der PathPattern angezeigt wird, ist der Wert dieser Eigenschaft als Uhrzeitformat verwendet.</span><span class="sxs-lookup"><span data-stu-id="4c679-133">Wherever {time} appears in pathPattern, the value of this property is used as the time format instead.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>