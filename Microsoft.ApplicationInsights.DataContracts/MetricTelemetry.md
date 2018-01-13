<Type Name="MetricTelemetry" FullName="Microsoft.ApplicationInsights.DataContracts.MetricTelemetry">
  <TypeSignature Language="C#" Value="public sealed class MetricTelemetry : Microsoft.ApplicationInsights.Channel.ITelemetry, Microsoft.ApplicationInsights.DataContracts.ISupportProperties" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit MetricTelemetry extends System.Object implements class Microsoft.ApplicationInsights.Channel.ITelemetry, class Microsoft.ApplicationInsights.DataContracts.ISupportProperties" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ApplicationInsights.DataContracts.MetricTelemetry" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class MetricTelemetry&#xA;Implements ISupportProperties, ITelemetry" />
  <TypeSignature Language="F#" Value="type MetricTelemetry = class&#xA;    interface ITelemetry&#xA;    interface ISupportProperties" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.ApplicationInsights</AssemblyName>
    <AssemblyVersion>2.3.0.0</AssemblyVersion>
    <AssemblyVersion>2.5.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces>
    <Interface>
      <InterfaceName>Microsoft.ApplicationInsights.Channel.ITelemetry</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.ApplicationInsights.DataContracts.ISupportProperties</InterfaceName>
    </Interface>
  </Interfaces>
  <Docs>
    <summary>
            <span data-ttu-id="8af0b-101">Telemetrie-Typ verwendet, um Metriken zu verfolgen.</span><span class="sxs-lookup"><span data-stu-id="8af0b-101">Telemetry type used to track metrics.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public MetricTelemetry ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ApplicationInsights.DataContracts.MetricTelemetry.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ApplicationInsights</AssemblyName>
        <AssemblyVersion>2.3.0.0</AssemblyVersion>
        <AssemblyVersion>2.5.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="8af0b-102">Initialisiert eine neue Instanz der dem <see cref="T:Microsoft.ApplicationInsights.DataContracts.MetricTelemetry" /> Klasse mit leeren Eigenschaften.</span><span class="sxs-lookup"><span data-stu-id="8af0b-102">Initializes a new instance of the <see cref="T:Microsoft.ApplicationInsights.DataContracts.MetricTelemetry" /> class with empty properties.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public MetricTelemetry (string metricName, double metricValue);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string metricName, float64 metricValue) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ApplicationInsights.DataContracts.MetricTelemetry.#ctor(System.String,System.Double)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (metricName As String, metricValue As Double)" />
      <MemberSignature Language="F#" Value="new Microsoft.ApplicationInsights.DataContracts.MetricTelemetry : string * double -&gt; Microsoft.ApplicationInsights.DataContracts.MetricTelemetry" Usage="new Microsoft.ApplicationInsights.DataContracts.MetricTelemetry (metricName, metricValue)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ApplicationInsights</AssemblyName>
        <AssemblyVersion>2.3.0.0</AssemblyVersion>
        <AssemblyVersion>2.5.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="metricName" Type="System.String" />
        <Parameter Name="metricValue" Type="System.Double" />
      </Parameters>
      <Docs>
        <param name="metricName">To be added.</param>
        <param name="metricValue">To be added.</param>
        <summary>
            <span data-ttu-id="8af0b-103">Initialisiert eine neue Instanz der <see cref="T:Microsoft.ApplicationInsights.DataContracts.MetricTelemetry" />-Klasse mit den angegebenen <paramref name="metricName" /> und dem angegebenen <paramref name="metricValue" />.</span><span class="sxs-lookup"><span data-stu-id="8af0b-103">Initializes a new instance of the <see cref="T:Microsoft.ApplicationInsights.DataContracts.MetricTelemetry" /> class with the specified <paramref name="metricName" /> and <paramref name="metricValue" />.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentException"><span data-ttu-id="8af0b-104">Die <paramref name="metricName" /> ist null oder eine leere Zeichenfolge.</span><span class="sxs-lookup"><span data-stu-id="8af0b-104">The <paramref name="metricName" /> is null or empty string.</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public MetricTelemetry (string name, int count, double sum, double min, double max, double standardDeviation);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string name, int32 count, float64 sum, float64 min, float64 max, float64 standardDeviation) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ApplicationInsights.DataContracts.MetricTelemetry.#ctor(System.String,System.Int32,System.Double,System.Double,System.Double,System.Double)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (name As String, count As Integer, sum As Double, min As Double, max As Double, standardDeviation As Double)" />
      <MemberSignature Language="F#" Value="new Microsoft.ApplicationInsights.DataContracts.MetricTelemetry : string * int * double * double * double * double -&gt; Microsoft.ApplicationInsights.DataContracts.MetricTelemetry" Usage="new Microsoft.ApplicationInsights.DataContracts.MetricTelemetry (name, count, sum, min, max, standardDeviation)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ApplicationInsights</AssemblyName>
        <AssemblyVersion>2.3.0.0</AssemblyVersion>
        <AssemblyVersion>2.5.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="count" Type="System.Int32" />
        <Parameter Name="sum" Type="System.Double" />
        <Parameter Name="min" Type="System.Double" />
        <Parameter Name="max" Type="System.Double" />
        <Parameter Name="standardDeviation" Type="System.Double" />
      </Parameters>
      <Docs>
        <param name="name"><span data-ttu-id="8af0b-105">Der metrikname.</span><span class="sxs-lookup"><span data-stu-id="8af0b-105">Metric name.</span></span></param>
        <param name="count"><span data-ttu-id="8af0b-106">Anzahl der Werte, die während des aggregationsintervalls.</span><span class="sxs-lookup"><span data-stu-id="8af0b-106">Count of values taken during aggregation interval.</span></span></param>
        <param name="sum"><span data-ttu-id="8af0b-107">Summe der Werte, die während des aggregationsintervalls.</span><span class="sxs-lookup"><span data-stu-id="8af0b-107">Sum of values taken during aggregation interval.</span></span></param>
        <param name="min"><span data-ttu-id="8af0b-108">Minimalwert, die während des aggregationsintervalls.</span><span class="sxs-lookup"><span data-stu-id="8af0b-108">Minimum value taken during aggregation interval.</span></span></param>
        <param name="max"><span data-ttu-id="8af0b-109">Maximum der Werte, die während des aggregationsintervalls.</span><span class="sxs-lookup"><span data-stu-id="8af0b-109">Maximum of values taken during aggregation interval.</span></span></param>
        <param name="standardDeviation"><span data-ttu-id="8af0b-110">Standardabweichung der Werte, die während des aggregationsintervalls.</span><span class="sxs-lookup"><span data-stu-id="8af0b-110">Standard deviation of values taken during aggregation interval.</span></span></param>
        <summary>
            <span data-ttu-id="8af0b-111">Initialisiert eine neue Instanz der dem <see cref="T:Microsoft.ApplicationInsights.DataContracts.MetricTelemetry" /> Klasse mit Eigenschaften bereitgestellt.</span><span class="sxs-lookup"><span data-stu-id="8af0b-111">Initializes a new instance of the <see cref="T:Microsoft.ApplicationInsights.DataContracts.MetricTelemetry" /> class with properties provided.</span></span>
            </summary>
        <remarks>
            <span data-ttu-id="8af0b-112">Es wird angenommen, dass bereitgestellte metrische Statistiken über eine Zeitspanne, die gleich 1 Minute berechnet werden.</span><span class="sxs-lookup"><span data-stu-id="8af0b-112">Metric statistics provided are assumed to be calculated over a period of time equaling 1 minute.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="Context">
      <MemberSignature Language="C#" Value="public Microsoft.ApplicationInsights.DataContracts.TelemetryContext Context { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.ApplicationInsights.DataContracts.TelemetryContext Context" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ApplicationInsights.DataContracts.MetricTelemetry.Context" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Context As TelemetryContext" />
      <MemberSignature Language="F#" Value="member this.Context : Microsoft.ApplicationInsights.DataContracts.TelemetryContext" Usage="Microsoft.ApplicationInsights.DataContracts.MetricTelemetry.Context" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:Microsoft.ApplicationInsights.Channel.ITelemetry.Context</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ApplicationInsights</AssemblyName>
        <AssemblyVersion>2.3.0.0</AssemblyVersion>
        <AssemblyVersion>2.5.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ApplicationInsights.DataContracts.TelemetryContext</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="8af0b-113">Ruft das aktuelle Element der Telemetrie zugeordneten Kontext.</span><span class="sxs-lookup"><span data-stu-id="8af0b-113">Gets the context associated with the current telemetry item.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Count">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; Count { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; Count" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ApplicationInsights.DataContracts.MetricTelemetry.Count" />
      <MemberSignature Language="VB.NET" Value="Public Property Count As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.Count : Nullable&lt;int&gt; with get, set" Usage="Microsoft.ApplicationInsights.DataContracts.MetricTelemetry.Count" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ApplicationInsights</AssemblyName>
        <AssemblyVersion>2.3.0.0</AssemblyVersion>
        <AssemblyVersion>2.5.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="8af0b-114">Ruft ab oder legt die Anzahl der Beispiele für die Metrik.</span><span class="sxs-lookup"><span data-stu-id="8af0b-114">Gets or sets the number of samples for this metric.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeepClone">
      <MemberSignature Language="C#" Value="public Microsoft.ApplicationInsights.Channel.ITelemetry DeepClone ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.ApplicationInsights.Channel.ITelemetry DeepClone() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ApplicationInsights.DataContracts.MetricTelemetry.DeepClone" />
      <MemberSignature Language="VB.NET" Value="Public Function DeepClone () As ITelemetry" />
      <MemberSignature Language="F#" Value="abstract member DeepClone : unit -&gt; Microsoft.ApplicationInsights.Channel.ITelemetry&#xA;override this.DeepClone : unit -&gt; Microsoft.ApplicationInsights.Channel.ITelemetry" Usage="metricTelemetry.DeepClone " />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.ApplicationInsights.Channel.ITelemetry.DeepClone</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ApplicationInsights</AssemblyName>
        <AssemblyVersion>2.5.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ApplicationInsights.Channel.ITelemetry</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Max">
      <MemberSignature Language="C#" Value="public Nullable&lt;double&gt; Max { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;float64&gt; Max" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ApplicationInsights.DataContracts.MetricTelemetry.Max" />
      <MemberSignature Language="VB.NET" Value="Public Property Max As Nullable(Of Double)" />
      <MemberSignature Language="F#" Value="member this.Max : Nullable&lt;double&gt; with get, set" Usage="Microsoft.ApplicationInsights.DataContracts.MetricTelemetry.Max" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ApplicationInsights</AssemblyName>
        <AssemblyVersion>2.3.0.0</AssemblyVersion>
        <AssemblyVersion>2.5.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Double&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="8af0b-115">Ruft ab oder legt den maximalen Wert dieser Metrik.</span><span class="sxs-lookup"><span data-stu-id="8af0b-115">Gets or sets the max value of this metric.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Microsoft.ApplicationInsights.Channel.ITelemetry.Sanitize">
      <MemberSignature Language="C#" Value="void ITelemetry.Sanitize ();" />
      <MemberSignature Language="ILAsm" Value=".method hidebysig newslot virtual instance void Microsoft.ApplicationInsights.Channel.ITelemetry.Sanitize() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ApplicationInsights.DataContracts.MetricTelemetry.Microsoft#ApplicationInsights#Channel#ITelemetry#Sanitize" />
      <MemberSignature Language="VB.NET" Value="Sub Sanitize () Implements ITelemetry.Sanitize" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.ApplicationInsights.Channel.ITelemetry.Sanitize</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ApplicationInsights</AssemblyName>
        <AssemblyVersion>2.3.0.0</AssemblyVersion>
        <AssemblyVersion>2.5.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="8af0b-116">Bereinigt die Eigenschaften, die auf Einschränkungen basieren.</span><span class="sxs-lookup"><span data-stu-id="8af0b-116">Sanitizes the properties based on constraints.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Min">
      <MemberSignature Language="C#" Value="public Nullable&lt;double&gt; Min { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;float64&gt; Min" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ApplicationInsights.DataContracts.MetricTelemetry.Min" />
      <MemberSignature Language="VB.NET" Value="Public Property Min As Nullable(Of Double)" />
      <MemberSignature Language="F#" Value="member this.Min : Nullable&lt;double&gt; with get, set" Usage="Microsoft.ApplicationInsights.DataContracts.MetricTelemetry.Min" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ApplicationInsights</AssemblyName>
        <AssemblyVersion>2.3.0.0</AssemblyVersion>
        <AssemblyVersion>2.5.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Double&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="8af0b-117">Ruft ab oder legt die Minimalwert, der diese Metrik.</span><span class="sxs-lookup"><span data-stu-id="8af0b-117">Gets or sets the min value of this metric.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Name">
      <MemberSignature Language="C#" Value="public string Name { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Name" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ApplicationInsights.DataContracts.MetricTelemetry.Name" />
      <MemberSignature Language="VB.NET" Value="Public Property Name As String" />
      <MemberSignature Language="F#" Value="member this.Name : string with get, set" Usage="Microsoft.ApplicationInsights.DataContracts.MetricTelemetry.Name" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ApplicationInsights</AssemblyName>
        <AssemblyVersion>2.3.0.0</AssemblyVersion>
        <AssemblyVersion>2.5.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="8af0b-118">Ruft ab oder legt den Namen der Metrik.</span><span class="sxs-lookup"><span data-stu-id="8af0b-118">Gets or sets the name of the metric.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Properties">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IDictionary&lt;string,string&gt; Properties { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IDictionary`2&lt;string, string&gt; Properties" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ApplicationInsights.DataContracts.MetricTelemetry.Properties" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Properties As IDictionary(Of String, String)" />
      <MemberSignature Language="F#" Value="member this.Properties : System.Collections.Generic.IDictionary&lt;string, string&gt;" Usage="Microsoft.ApplicationInsights.DataContracts.MetricTelemetry.Properties" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:Microsoft.ApplicationInsights.DataContracts.ISupportProperties.Properties</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ApplicationInsights</AssemblyName>
        <AssemblyVersion>2.3.0.0</AssemblyVersion>
        <AssemblyVersion>2.5.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IDictionary&lt;System.String,System.String&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="8af0b-119">Ruft ein Wörterbuch von anwendungsdefinierten Eigenschaftennamen und Werte, die zusätzliche Informationen über diese Metrik.</span><span class="sxs-lookup"><span data-stu-id="8af0b-119">Gets a dictionary of application-defined property names and values providing additional information about this metric.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Sequence">
      <MemberSignature Language="C#" Value="public string Sequence { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Sequence" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ApplicationInsights.DataContracts.MetricTelemetry.Sequence" />
      <MemberSignature Language="VB.NET" Value="Public Property Sequence As String" />
      <MemberSignature Language="F#" Value="member this.Sequence : string with get, set" Usage="Microsoft.ApplicationInsights.DataContracts.MetricTelemetry.Sequence" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:Microsoft.ApplicationInsights.Channel.ITelemetry.Sequence</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ApplicationInsights</AssemblyName>
        <AssemblyVersion>2.3.0.0</AssemblyVersion>
        <AssemblyVersion>2.5.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="8af0b-120">Ruft ab oder legt den Wert an, der absolute Reihenfolge der Telemetrie-Elements definiert.</span><span class="sxs-lookup"><span data-stu-id="8af0b-120">Gets or sets the value that defines absolute order of the telemetry item.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="StandardDeviation">
      <MemberSignature Language="C#" Value="public Nullable&lt;double&gt; StandardDeviation { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;float64&gt; StandardDeviation" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ApplicationInsights.DataContracts.MetricTelemetry.StandardDeviation" />
      <MemberSignature Language="VB.NET" Value="Public Property StandardDeviation As Nullable(Of Double)" />
      <MemberSignature Language="F#" Value="member this.StandardDeviation : Nullable&lt;double&gt; with get, set" Usage="Microsoft.ApplicationInsights.DataContracts.MetricTelemetry.StandardDeviation" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ApplicationInsights</AssemblyName>
        <AssemblyVersion>2.3.0.0</AssemblyVersion>
        <AssemblyVersion>2.5.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Double&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="8af0b-121">Abrufen oder Festlegen der standardmäßigen Abweichung bei der diese Metrik.</span><span class="sxs-lookup"><span data-stu-id="8af0b-121">Gets or sets the standard deviation of this metric.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Sum">
      <MemberSignature Language="C#" Value="public double Sum { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance float64 Sum" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ApplicationInsights.DataContracts.MetricTelemetry.Sum" />
      <MemberSignature Language="VB.NET" Value="Public Property Sum As Double" />
      <MemberSignature Language="F#" Value="member this.Sum : double with get, set" Usage="Microsoft.ApplicationInsights.DataContracts.MetricTelemetry.Sum" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ApplicationInsights</AssemblyName>
        <AssemblyVersion>2.3.0.0</AssemblyVersion>
        <AssemblyVersion>2.5.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Double</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="8af0b-122">Abrufen oder Festlegen der Summe der Werte der Metrik Beispiele.</span><span class="sxs-lookup"><span data-stu-id="8af0b-122">Gets or sets sum of the values of the metric samples.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Timestamp">
      <MemberSignature Language="C#" Value="public DateTimeOffset Timestamp { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.DateTimeOffset Timestamp" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ApplicationInsights.DataContracts.MetricTelemetry.Timestamp" />
      <MemberSignature Language="VB.NET" Value="Public Property Timestamp As DateTimeOffset" />
      <MemberSignature Language="F#" Value="member this.Timestamp : DateTimeOffset with get, set" Usage="Microsoft.ApplicationInsights.DataContracts.MetricTelemetry.Timestamp" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:Microsoft.ApplicationInsights.Channel.ITelemetry.Timestamp</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ApplicationInsights</AssemblyName>
        <AssemblyVersion>2.3.0.0</AssemblyVersion>
        <AssemblyVersion>2.5.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.DateTimeOffset</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="8af0b-123">Ruft ab oder legt Datum und Uhrzeit, wann das Ereignis aufgezeichnet wurde.</span><span class="sxs-lookup"><span data-stu-id="8af0b-123">Gets or sets date and time when event was recorded.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Value">
      <MemberSignature Language="C#" Value="public double Value { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance float64 Value" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ApplicationInsights.DataContracts.MetricTelemetry.Value" />
      <MemberSignature Language="VB.NET" Value="Public Property Value As Double" />
      <MemberSignature Language="F#" Value="member this.Value : double with get, set" Usage="Microsoft.ApplicationInsights.DataContracts.MetricTelemetry.Value" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ApplicationInsights</AssemblyName>
        <AssemblyVersion>2.3.0.0</AssemblyVersion>
        <AssemblyVersion>2.5.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Obsolete("This property is obsolete. Use Sum property instead.")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Double</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="8af0b-124">Ruft ab oder legt den Wert für diese Metrik.</span><span class="sxs-lookup"><span data-stu-id="8af0b-124">Gets or sets the value of this metric.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>