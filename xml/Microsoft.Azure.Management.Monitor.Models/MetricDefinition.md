<Type Name="MetricDefinition" FullName="Microsoft.Azure.Management.Monitor.Models.MetricDefinition">
  <TypeSignature Language="C#" Value="public class MetricDefinition" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit MetricDefinition extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Monitor.Models.MetricDefinition" />
  <TypeSignature Language="VB.NET" Value="Public Class MetricDefinition" />
  <TypeSignature Language="F#" Value="type MetricDefinition = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Monitor</AssemblyName>
    <AssemblyVersion>0.18.0.0</AssemblyVersion>
    <AssemblyVersion>0.18.1.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="c6292-101">Anhand der metrischen definitionsklasse gibt die Metadaten für eine Metrik an.</span><span class="sxs-lookup"><span data-stu-id="c6292-101">Metric definition class specifies the metadata for a metric.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public MetricDefinition ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Monitor.Models.MetricDefinition.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Monitor</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
        <AssemblyVersion>0.18.1.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="c6292-102">Initialisiert eine neue Instanz der MetricDefinition-Klasse.</span><span class="sxs-lookup"><span data-stu-id="c6292-102">Initializes a new instance of the MetricDefinition class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public MetricDefinition (Nullable&lt;bool&gt; isDimensionRequired = null, string resourceId = null, Microsoft.Azure.Management.Monitor.Models.LocalizableString name = null, Nullable&lt;Microsoft.Azure.Management.Monitor.Models.Unit&gt; unit = null, Nullable&lt;Microsoft.Azure.Management.Monitor.Models.AggregationType&gt; primaryAggregationType = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Monitor.Models.MetricAvailability&gt; metricAvailabilities = null, string id = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Monitor.Models.LocalizableString&gt; dimensions = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(valuetype System.Nullable`1&lt;bool&gt; isDimensionRequired, string resourceId, class Microsoft.Azure.Management.Monitor.Models.LocalizableString name, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.Monitor.Models.Unit&gt; unit, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.Monitor.Models.AggregationType&gt; primaryAggregationType, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Monitor.Models.MetricAvailability&gt; metricAvailabilities, string id, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Monitor.Models.LocalizableString&gt; dimensions) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Monitor.Models.MetricDefinition.#ctor(System.Nullable{System.Boolean},System.String,Microsoft.Azure.Management.Monitor.Models.LocalizableString,System.Nullable{Microsoft.Azure.Management.Monitor.Models.Unit},System.Nullable{Microsoft.Azure.Management.Monitor.Models.AggregationType},System.Collections.Generic.IList{Microsoft.Azure.Management.Monitor.Models.MetricAvailability},System.String,System.Collections.Generic.IList{Microsoft.Azure.Management.Monitor.Models.LocalizableString})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional isDimensionRequired As Nullable(Of Boolean) = null, Optional resourceId As String = null, Optional name As LocalizableString = null, Optional unit As Nullable(Of Unit) = null, Optional primaryAggregationType As Nullable(Of AggregationType) = null, Optional metricAvailabilities As IList(Of MetricAvailability) = null, Optional id As String = null, Optional dimensions As IList(Of LocalizableString) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Monitor.Models.MetricDefinition : Nullable&lt;bool&gt; * string * Microsoft.Azure.Management.Monitor.Models.LocalizableString * Nullable&lt;Microsoft.Azure.Management.Monitor.Models.Unit&gt; * Nullable&lt;Microsoft.Azure.Management.Monitor.Models.AggregationType&gt; * System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Monitor.Models.MetricAvailability&gt; * string * System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Monitor.Models.LocalizableString&gt; -&gt; Microsoft.Azure.Management.Monitor.Models.MetricDefinition" Usage="new Microsoft.Azure.Management.Monitor.Models.MetricDefinition (isDimensionRequired, resourceId, name, unit, primaryAggregationType, metricAvailabilities, id, dimensions)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Monitor</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
        <AssemblyVersion>0.18.1.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="isDimensionRequired" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="resourceId" Type="System.String" />
        <Parameter Name="name" Type="Microsoft.Azure.Management.Monitor.Models.LocalizableString" />
        <Parameter Name="unit" Type="System.Nullable&lt;Microsoft.Azure.Management.Monitor.Models.Unit&gt;" />
        <Parameter Name="primaryAggregationType" Type="System.Nullable&lt;Microsoft.Azure.Management.Monitor.Models.AggregationType&gt;" />
        <Parameter Name="metricAvailabilities" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Monitor.Models.MetricAvailability&gt;" />
        <Parameter Name="id" Type="System.String" />
        <Parameter Name="dimensions" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Monitor.Models.LocalizableString&gt;" />
      </Parameters>
      <Docs>
        <param name="isDimensionRequired"><span data-ttu-id="c6292-103">Kennzeichen Sie, um anzugeben, ob die Dimension erforderlich ist.</span><span class="sxs-lookup"><span data-stu-id="c6292-103">Flag to indicate whether the dimension is required.</span></span></param>
        <param name="resourceId"><span data-ttu-id="c6292-104">Der Ressourcenbezeichner der Ressource, die die Metrik ausgegeben.</span><span class="sxs-lookup"><span data-stu-id="c6292-104">the resource identifier of the resource that emitted the metric.</span></span></param>
        <param name="name"><span data-ttu-id="c6292-105">der Name und der Anzeigename der Metrik, d. h. es ist eine lokalisierbare Zeichenfolge.</span><span class="sxs-lookup"><span data-stu-id="c6292-105">the name and the display name of the metric, i.e. it is a localizable string.</span></span></param>
        <param name="unit"><span data-ttu-id="c6292-106">Die Einheit der Metrik.</span><span class="sxs-lookup"><span data-stu-id="c6292-106">the unit of the metric.</span></span> <span data-ttu-id="c6292-107">Folgende Werte sind möglich: 'Count', 'Bytes', "Sekunden", "CountPerSecond", "BytesPerSecond", "Prozent", "Millisekunden", "ByteSeconds", "Unspecified"</span><span class="sxs-lookup"><span data-stu-id="c6292-107">Possible values include: 'Count', 'Bytes', 'Seconds', 'CountPerSecond', 'BytesPerSecond', 'Percent', 'MilliSeconds', 'ByteSeconds', 'Unspecified'</span></span></param>
        <param name="primaryAggregationType"><span data-ttu-id="c6292-108">der primäre Aggregation Typwert, der definiert, wie Sie die Werte für die Anzeige zu verwenden.</span><span class="sxs-lookup"><span data-stu-id="c6292-108">the primary aggregation type value defining how to use the values for display.</span></span> <span data-ttu-id="c6292-109">Folgende Werte sind möglich: 'None', 'Average', 'Count', "Minimum", "Maximum", "Total"</span><span class="sxs-lookup"><span data-stu-id="c6292-109">Possible values include: 'None', 'Average', 'Count', 'Minimum', 'Maximum', 'Total'</span></span></param>
        <param name="metricAvailabilities"><span data-ttu-id="c6292-110">die Auflistung von welchen Intervallen Aggregation abzufragenden verfügbar sind.</span><span class="sxs-lookup"><span data-stu-id="c6292-110">the collection of what aggregation intervals are available to be queried.</span></span></param>
        <param name="id"><span data-ttu-id="c6292-111">Der Ressourcenbezeichner der metrischen Definition.</span><span class="sxs-lookup"><span data-stu-id="c6292-111">the resource identifier of the metric definition.</span></span></param>
        <param name="dimensions"><span data-ttu-id="c6292-112">der Name und der Anzeigename der Dimension, d. h. es ist eine lokalisierbare Zeichenfolge.</span><span class="sxs-lookup"><span data-stu-id="c6292-112">the name and the display name of the dimension, i.e. it is a localizable string.</span></span></param>
        <summary>
            <span data-ttu-id="c6292-113">Initialisiert eine neue Instanz der MetricDefinition-Klasse.</span><span class="sxs-lookup"><span data-stu-id="c6292-113">Initializes a new instance of the MetricDefinition class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Dimensions">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Monitor.Models.LocalizableString&gt; Dimensions { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Monitor.Models.LocalizableString&gt; Dimensions" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Monitor.Models.MetricDefinition.Dimensions" />
      <MemberSignature Language="VB.NET" Value="Public Property Dimensions As IList(Of LocalizableString)" />
      <MemberSignature Language="F#" Value="member this.Dimensions : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Monitor.Models.LocalizableString&gt; with get, set" Usage="Microsoft.Azure.Management.Monitor.Models.MetricDefinition.Dimensions" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Monitor</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
        <AssemblyVersion>0.18.1.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="dimensions")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Monitor.Models.LocalizableString&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="c6292-114">Ruft ab oder legt sie fest, den Namen und den Anzeigenamen der Dimension, d. h. es ist eine lokalisierbare Zeichenfolge.</span><span class="sxs-lookup"><span data-stu-id="c6292-114">Gets or sets the name and the display name of the dimension, i.e. it is a localizable string.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Id">
      <MemberSignature Language="C#" Value="public string Id { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Id" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Monitor.Models.MetricDefinition.Id" />
      <MemberSignature Language="VB.NET" Value="Public Property Id As String" />
      <MemberSignature Language="F#" Value="member this.Id : string with get, set" Usage="Microsoft.Azure.Management.Monitor.Models.MetricDefinition.Id" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Monitor</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
        <AssemblyVersion>0.18.1.0</AssemblyVersion>
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
            <span data-ttu-id="c6292-115">Ruft ab oder legt den Ressourcenbezeichner des anhand der metrischen Definition.</span><span class="sxs-lookup"><span data-stu-id="c6292-115">Gets or sets the resource identifier of the metric definition.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IsDimensionRequired">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; IsDimensionRequired { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; IsDimensionRequired" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Monitor.Models.MetricDefinition.IsDimensionRequired" />
      <MemberSignature Language="VB.NET" Value="Public Property IsDimensionRequired As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.IsDimensionRequired : Nullable&lt;bool&gt; with get, set" Usage="Microsoft.Azure.Management.Monitor.Models.MetricDefinition.IsDimensionRequired" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Monitor</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
        <AssemblyVersion>0.18.1.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="isDimensionRequired")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="c6292-116">Ruft ab, oder legt ihn fest Kennzeichen, das angibt, ob die Dimension erforderlich ist.</span><span class="sxs-lookup"><span data-stu-id="c6292-116">Gets or sets flag to indicate whether the dimension is required.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MetricAvailabilities">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Monitor.Models.MetricAvailability&gt; MetricAvailabilities { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Monitor.Models.MetricAvailability&gt; MetricAvailabilities" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Monitor.Models.MetricDefinition.MetricAvailabilities" />
      <MemberSignature Language="VB.NET" Value="Public Property MetricAvailabilities As IList(Of MetricAvailability)" />
      <MemberSignature Language="F#" Value="member this.MetricAvailabilities : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Monitor.Models.MetricAvailability&gt; with get, set" Usage="Microsoft.Azure.Management.Monitor.Models.MetricDefinition.MetricAvailabilities" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Monitor</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
        <AssemblyVersion>0.18.1.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="metricAvailabilities")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Monitor.Models.MetricAvailability&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="c6292-117">Ruft ab oder legt die Auflistung der welche Aggregation Intervalle verfügbar sind.</span><span class="sxs-lookup"><span data-stu-id="c6292-117">Gets or sets the collection of what aggregation intervals are available to be queried.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Name">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Monitor.Models.LocalizableString Name { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Monitor.Models.LocalizableString Name" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Monitor.Models.MetricDefinition.Name" />
      <MemberSignature Language="VB.NET" Value="Public Property Name As LocalizableString" />
      <MemberSignature Language="F#" Value="member this.Name : Microsoft.Azure.Management.Monitor.Models.LocalizableString with get, set" Usage="Microsoft.Azure.Management.Monitor.Models.MetricDefinition.Name" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Monitor</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
        <AssemblyVersion>0.18.1.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="name")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Monitor.Models.LocalizableString</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="c6292-118">Ruft ab oder legt sie fest, der Name und der Anzeigename der Metrik, d. h. es ist eine lokalisierbare Zeichenfolge.</span><span class="sxs-lookup"><span data-stu-id="c6292-118">Gets or sets the name and the display name of the metric, i.e. it is a localizable string.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PrimaryAggregationType">
      <MemberSignature Language="C#" Value="public Nullable&lt;Microsoft.Azure.Management.Monitor.Models.AggregationType&gt; PrimaryAggregationType { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.Monitor.Models.AggregationType&gt; PrimaryAggregationType" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Monitor.Models.MetricDefinition.PrimaryAggregationType" />
      <MemberSignature Language="VB.NET" Value="Public Property PrimaryAggregationType As Nullable(Of AggregationType)" />
      <MemberSignature Language="F#" Value="member this.PrimaryAggregationType : Nullable&lt;Microsoft.Azure.Management.Monitor.Models.AggregationType&gt; with get, set" Usage="Microsoft.Azure.Management.Monitor.Models.MetricDefinition.PrimaryAggregationType" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Monitor</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
        <AssemblyVersion>0.18.1.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="primaryAggregationType")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;Microsoft.Azure.Management.Monitor.Models.AggregationType&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="c6292-119">Ruft ab, oder legt ihn fest den primären Aggregation Typwert, der definiert, wie Sie die Werte für die Anzeige zu verwenden.</span><span class="sxs-lookup"><span data-stu-id="c6292-119">Gets or sets the primary aggregation type value defining how to use the values for display.</span></span> <span data-ttu-id="c6292-120">Folgende Werte sind möglich: 'None', 'Average', 'Count', "Minimum", "Maximum", "Total"</span><span class="sxs-lookup"><span data-stu-id="c6292-120">Possible values include: 'None', 'Average', 'Count', 'Minimum', 'Maximum', 'Total'</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ResourceId">
      <MemberSignature Language="C#" Value="public string ResourceId { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ResourceId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Monitor.Models.MetricDefinition.ResourceId" />
      <MemberSignature Language="VB.NET" Value="Public Property ResourceId As String" />
      <MemberSignature Language="F#" Value="member this.ResourceId : string with get, set" Usage="Microsoft.Azure.Management.Monitor.Models.MetricDefinition.ResourceId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Monitor</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
        <AssemblyVersion>0.18.1.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="resourceId")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="c6292-121">Abrufen oder festlegen den Ressourcenbezeichner der Ressource, die die Metrik ausgegeben.</span><span class="sxs-lookup"><span data-stu-id="c6292-121">Gets or sets the resource identifier of the resource that emitted the metric.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Unit">
      <MemberSignature Language="C#" Value="public Nullable&lt;Microsoft.Azure.Management.Monitor.Models.Unit&gt; Unit { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.Monitor.Models.Unit&gt; Unit" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Monitor.Models.MetricDefinition.Unit" />
      <MemberSignature Language="VB.NET" Value="Public Property Unit As Nullable(Of Unit)" />
      <MemberSignature Language="F#" Value="member this.Unit : Nullable&lt;Microsoft.Azure.Management.Monitor.Models.Unit&gt; with get, set" Usage="Microsoft.Azure.Management.Monitor.Models.MetricDefinition.Unit" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Monitor</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
        <AssemblyVersion>0.18.1.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="unit")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;Microsoft.Azure.Management.Monitor.Models.Unit&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="c6292-122">Ruft ab oder legt fest, der Metrik.</span><span class="sxs-lookup"><span data-stu-id="c6292-122">Gets or sets the unit of the metric.</span></span> <span data-ttu-id="c6292-123">Folgende Werte sind möglich: 'Count', 'Bytes', "Sekunden", "CountPerSecond", "BytesPerSecond", "Prozent", "Millisekunden", "ByteSeconds", "Unspecified"</span><span class="sxs-lookup"><span data-stu-id="c6292-123">Possible values include: 'Count', 'Bytes', 'Seconds', 'CountPerSecond', 'BytesPerSecond', 'Percent', 'MilliSeconds', 'ByteSeconds', 'Unspecified'</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Monitor.Models.MetricDefinition.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="metricDefinition.Validate " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Monitor</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
        <AssemblyVersion>0.18.1.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="c6292-124">Überprüfen Sie das Objekt.</span><span class="sxs-lookup"><span data-stu-id="c6292-124">Validate the object.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="c6292-125">Wird ausgelöst, wenn die Validierung fehlschlägt</span><span class="sxs-lookup"><span data-stu-id="c6292-125">Thrown if validation fails</span></span>
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>