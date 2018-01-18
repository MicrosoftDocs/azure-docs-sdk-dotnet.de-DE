<Type Name="MetricTrigger" FullName="Microsoft.Azure.Management.Monitor.Management.Models.MetricTrigger">
  <TypeSignature Language="C#" Value="public class MetricTrigger" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit MetricTrigger extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Monitor.Management.Models.MetricTrigger" />
  <TypeSignature Language="VB.NET" Value="Public Class MetricTrigger" />
  <TypeSignature Language="F#" Value="type MetricTrigger = class" />
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
            <span data-ttu-id="1833d-101">Der Trigger, der zu einer skalierungsaktion führt.</span><span class="sxs-lookup"><span data-stu-id="1833d-101">The trigger that results in a scaling action.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public MetricTrigger ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Monitor.Management.Models.MetricTrigger.#ctor" />
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
            <span data-ttu-id="1833d-102">Initialisiert eine neue Instanz der MetricTrigger-Klasse.</span><span class="sxs-lookup"><span data-stu-id="1833d-102">Initializes a new instance of the MetricTrigger class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public MetricTrigger (string metricName, string metricResourceUri, TimeSpan timeGrain, Microsoft.Azure.Management.Monitor.Management.Models.MetricStatisticType statistic, TimeSpan timeWindow, Microsoft.Azure.Management.Monitor.Management.Models.TimeAggregationType timeAggregation, Microsoft.Azure.Management.Monitor.Management.Models.ComparisonOperationType operatorProperty, double threshold);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string metricName, string metricResourceUri, valuetype System.TimeSpan timeGrain, valuetype Microsoft.Azure.Management.Monitor.Management.Models.MetricStatisticType statistic, valuetype System.TimeSpan timeWindow, valuetype Microsoft.Azure.Management.Monitor.Management.Models.TimeAggregationType timeAggregation, valuetype Microsoft.Azure.Management.Monitor.Management.Models.ComparisonOperationType operatorProperty, float64 threshold) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Monitor.Management.Models.MetricTrigger.#ctor(System.String,System.String,System.TimeSpan,Microsoft.Azure.Management.Monitor.Management.Models.MetricStatisticType,System.TimeSpan,Microsoft.Azure.Management.Monitor.Management.Models.TimeAggregationType,Microsoft.Azure.Management.Monitor.Management.Models.ComparisonOperationType,System.Double)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (metricName As String, metricResourceUri As String, timeGrain As TimeSpan, statistic As MetricStatisticType, timeWindow As TimeSpan, timeAggregation As TimeAggregationType, operatorProperty As ComparisonOperationType, threshold As Double)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Monitor.Management.Models.MetricTrigger : string * string * TimeSpan * Microsoft.Azure.Management.Monitor.Management.Models.MetricStatisticType * TimeSpan * Microsoft.Azure.Management.Monitor.Management.Models.TimeAggregationType * Microsoft.Azure.Management.Monitor.Management.Models.ComparisonOperationType * double -&gt; Microsoft.Azure.Management.Monitor.Management.Models.MetricTrigger" Usage="new Microsoft.Azure.Management.Monitor.Management.Models.MetricTrigger (metricName, metricResourceUri, timeGrain, statistic, timeWindow, timeAggregation, operatorProperty, threshold)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Monitor</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
        <AssemblyVersion>0.18.1.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="metricName" Type="System.String" />
        <Parameter Name="metricResourceUri" Type="System.String" />
        <Parameter Name="timeGrain" Type="System.TimeSpan" />
        <Parameter Name="statistic" Type="Microsoft.Azure.Management.Monitor.Management.Models.MetricStatisticType" />
        <Parameter Name="timeWindow" Type="System.TimeSpan" />
        <Parameter Name="timeAggregation" Type="Microsoft.Azure.Management.Monitor.Management.Models.TimeAggregationType" />
        <Parameter Name="operatorProperty" Type="Microsoft.Azure.Management.Monitor.Management.Models.ComparisonOperationType" />
        <Parameter Name="threshold" Type="System.Double" />
      </Parameters>
      <Docs>
        <param name="metricName"><span data-ttu-id="1833d-103">Der Name der Metrik, die definiert, was die Regel überwacht.</span><span class="sxs-lookup"><span data-stu-id="1833d-103">the name of the metric that defines what the rule monitors.</span></span></param>
        <param name="metricResourceUri"><span data-ttu-id="1833d-104">Der Ressourcenbezeichner der Ressource die Regel überwacht.</span><span class="sxs-lookup"><span data-stu-id="1833d-104">the resource identifier of the resource the rule monitors.</span></span></param>
        <param name="timeGrain"><span data-ttu-id="1833d-105">die Granularität der Metriken, die Regel überwacht.</span><span class="sxs-lookup"><span data-stu-id="1833d-105">the granularity of metrics the rule monitors.</span></span> <span data-ttu-id="1833d-106">Einen der vordefinierten Werte muss von den metrikdefinitionen für die Metrik zurückgegeben werden.</span><span class="sxs-lookup"><span data-stu-id="1833d-106">Must be one of the predefined values returned from metric definitions for the metric.</span></span> <span data-ttu-id="1833d-107">Muss zwischen 12 Stunden und 1 Minute betragen.</span><span class="sxs-lookup"><span data-stu-id="1833d-107">Must be between 12 hours and 1 minute.</span></span></param>
        <param name="statistic"><span data-ttu-id="1833d-108">der Metrik Statistiktyp.</span><span class="sxs-lookup"><span data-stu-id="1833d-108">the metric statistic type.</span></span> <span data-ttu-id="1833d-109">Wie die Metriken aus mehreren Instanzen kombiniert werden.</span><span class="sxs-lookup"><span data-stu-id="1833d-109">How the metrics from multiple instances are combined.</span></span> <span data-ttu-id="1833d-110">Folgende Werte sind möglich: 'Average', 'Min', 'Max', 'Sum'</span><span class="sxs-lookup"><span data-stu-id="1833d-110">Possible values include: 'Average', 'Min', 'Max', 'Sum'</span></span></param>
        <param name="timeWindow"><span data-ttu-id="1833d-111">die Zeitspanne, in dem Instanzdaten gesammelt werden.</span><span class="sxs-lookup"><span data-stu-id="1833d-111">the range of time in which instance data is collected.</span></span> <span data-ttu-id="1833d-112">Dieser Wert muss größer als die Verzögerung bei der metrikerfassung, werden die von Ressource zu Ressource unterschiedlich sein können.</span><span class="sxs-lookup"><span data-stu-id="1833d-112">This value must be greater than the delay in metric collection, which can vary from resource-to-resource.</span></span> <span data-ttu-id="1833d-113">Muss zwischen 12 Stunden und 5 Minuten liegen.</span><span class="sxs-lookup"><span data-stu-id="1833d-113">Must be between 12 hours and 5 minutes.</span></span></param>
        <param name="timeAggregation"><span data-ttu-id="1833d-114">Zeit Aggregationstyp.</span><span class="sxs-lookup"><span data-stu-id="1833d-114">time aggregation type.</span></span> <span data-ttu-id="1833d-115">Legt fest, wie die erfassten Daten im Zeitverlauf kombiniert werden sollen.</span><span class="sxs-lookup"><span data-stu-id="1833d-115">How the data that is collected should be combined over time.</span></span> <span data-ttu-id="1833d-116">Der Standardwert ist "Average".</span><span class="sxs-lookup"><span data-stu-id="1833d-116">The default value is Average.</span></span> <span data-ttu-id="1833d-117">Folgende Werte sind möglich: "Durchschnitt", "Minimum", "Maximum", "Total", "Count"</span><span class="sxs-lookup"><span data-stu-id="1833d-117">Possible values include: 'Average', 'Minimum', 'Maximum', 'Total', 'Count'</span></span></param>
        <param name="operatorProperty"><span data-ttu-id="1833d-118">der Operator, mit dem die metrischen Daten und der Schwellenwert verglichen.</span><span class="sxs-lookup"><span data-stu-id="1833d-118">the operator that is used to compare the metric data and the threshold.</span></span> <span data-ttu-id="1833d-119">Folgende Werte sind möglich: "Equals", "Ungleich", "GreaterThan", "GreaterThanOrEqual", "LessThan", "LessThanOrEqual"</span><span class="sxs-lookup"><span data-stu-id="1833d-119">Possible values include: 'Equals', 'NotEquals', 'GreaterThan', 'GreaterThanOrEqual', 'LessThan', 'LessThanOrEqual'</span></span></param>
        <param name="threshold"><span data-ttu-id="1833d-120">der Schwellenwert der Metrik, die die skalierungsaktion auslöst.</span><span class="sxs-lookup"><span data-stu-id="1833d-120">the threshold of the metric that triggers the scale action.</span></span></param>
        <summary>
            <span data-ttu-id="1833d-121">Initialisiert eine neue Instanz der MetricTrigger-Klasse.</span><span class="sxs-lookup"><span data-stu-id="1833d-121">Initializes a new instance of the MetricTrigger class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MetricName">
      <MemberSignature Language="C#" Value="public string MetricName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string MetricName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Monitor.Management.Models.MetricTrigger.MetricName" />
      <MemberSignature Language="VB.NET" Value="Public Property MetricName As String" />
      <MemberSignature Language="F#" Value="member this.MetricName : string with get, set" Usage="Microsoft.Azure.Management.Monitor.Management.Models.MetricTrigger.MetricName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Monitor</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
        <AssemblyVersion>0.18.1.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="metricName")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="1833d-122">Ruft ab oder legt den Namen der Metrik, die definiert, was die Regel überwacht.</span><span class="sxs-lookup"><span data-stu-id="1833d-122">Gets or sets the name of the metric that defines what the rule monitors.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MetricResourceUri">
      <MemberSignature Language="C#" Value="public string MetricResourceUri { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string MetricResourceUri" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Monitor.Management.Models.MetricTrigger.MetricResourceUri" />
      <MemberSignature Language="VB.NET" Value="Public Property MetricResourceUri As String" />
      <MemberSignature Language="F#" Value="member this.MetricResourceUri : string with get, set" Usage="Microsoft.Azure.Management.Monitor.Management.Models.MetricTrigger.MetricResourceUri" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Monitor</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
        <AssemblyVersion>0.18.1.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="metricResourceUri")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="1833d-123">Ruft ab oder legt überwacht der Ressourcenbezeichner der Ressource die Regel.</span><span class="sxs-lookup"><span data-stu-id="1833d-123">Gets or sets the resource identifier of the resource the rule monitors.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OperatorProperty">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Monitor.Management.Models.ComparisonOperationType OperatorProperty { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype Microsoft.Azure.Management.Monitor.Management.Models.ComparisonOperationType OperatorProperty" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Monitor.Management.Models.MetricTrigger.OperatorProperty" />
      <MemberSignature Language="VB.NET" Value="Public Property OperatorProperty As ComparisonOperationType" />
      <MemberSignature Language="F#" Value="member this.OperatorProperty : Microsoft.Azure.Management.Monitor.Management.Models.ComparisonOperationType with get, set" Usage="Microsoft.Azure.Management.Monitor.Management.Models.MetricTrigger.OperatorProperty" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Monitor</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
        <AssemblyVersion>0.18.1.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="operator")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Monitor.Management.Models.ComparisonOperationType</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="1833d-124">Ruft ab oder legt den Operator, der verwendet wird, um die metrischen Daten und der Schwellenwert verglichen.</span><span class="sxs-lookup"><span data-stu-id="1833d-124">Gets or sets the operator that is used to compare the metric data and the threshold.</span></span> <span data-ttu-id="1833d-125">Folgende Werte sind möglich: "Equals", "Ungleich", "GreaterThan", "GreaterThanOrEqual", "LessThan", "LessThanOrEqual"</span><span class="sxs-lookup"><span data-stu-id="1833d-125">Possible values include: 'Equals', 'NotEquals', 'GreaterThan', 'GreaterThanOrEqual', 'LessThan', 'LessThanOrEqual'</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Statistic">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Monitor.Management.Models.MetricStatisticType Statistic { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype Microsoft.Azure.Management.Monitor.Management.Models.MetricStatisticType Statistic" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Monitor.Management.Models.MetricTrigger.Statistic" />
      <MemberSignature Language="VB.NET" Value="Public Property Statistic As MetricStatisticType" />
      <MemberSignature Language="F#" Value="member this.Statistic : Microsoft.Azure.Management.Monitor.Management.Models.MetricStatisticType with get, set" Usage="Microsoft.Azure.Management.Monitor.Management.Models.MetricTrigger.Statistic" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Monitor</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
        <AssemblyVersion>0.18.1.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="statistic")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Monitor.Management.Models.MetricStatisticType</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="1833d-126">Abrufen oder festlegen den Metrik Statistiktyp.</span><span class="sxs-lookup"><span data-stu-id="1833d-126">Gets or sets the metric statistic type.</span></span> <span data-ttu-id="1833d-127">Wie die Metriken aus mehreren Instanzen kombiniert werden.</span><span class="sxs-lookup"><span data-stu-id="1833d-127">How the metrics from multiple instances are combined.</span></span> <span data-ttu-id="1833d-128">Folgende Werte sind möglich: 'Average', 'Min', 'Max', 'Sum'</span><span class="sxs-lookup"><span data-stu-id="1833d-128">Possible values include: 'Average', 'Min', 'Max', 'Sum'</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Threshold">
      <MemberSignature Language="C#" Value="public double Threshold { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance float64 Threshold" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Monitor.Management.Models.MetricTrigger.Threshold" />
      <MemberSignature Language="VB.NET" Value="Public Property Threshold As Double" />
      <MemberSignature Language="F#" Value="member this.Threshold : double with get, set" Usage="Microsoft.Azure.Management.Monitor.Management.Models.MetricTrigger.Threshold" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Monitor</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
        <AssemblyVersion>0.18.1.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="threshold")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Double</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="1833d-129">Ruft ab oder legt den Schwellenwert der Metrik, die die skalierungsaktion auslöst.</span><span class="sxs-lookup"><span data-stu-id="1833d-129">Gets or sets the threshold of the metric that triggers the scale action.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TimeAggregation">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Monitor.Management.Models.TimeAggregationType TimeAggregation { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype Microsoft.Azure.Management.Monitor.Management.Models.TimeAggregationType TimeAggregation" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Monitor.Management.Models.MetricTrigger.TimeAggregation" />
      <MemberSignature Language="VB.NET" Value="Public Property TimeAggregation As TimeAggregationType" />
      <MemberSignature Language="F#" Value="member this.TimeAggregation : Microsoft.Azure.Management.Monitor.Management.Models.TimeAggregationType with get, set" Usage="Microsoft.Azure.Management.Monitor.Management.Models.MetricTrigger.TimeAggregation" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Monitor</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
        <AssemblyVersion>0.18.1.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="timeAggregation")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Monitor.Management.Models.TimeAggregationType</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="1833d-130">Ruft ab oder legt ihn fest Zeit Aggregation.</span><span class="sxs-lookup"><span data-stu-id="1833d-130">Gets or sets time aggregation type.</span></span> <span data-ttu-id="1833d-131">Legt fest, wie die erfassten Daten im Zeitverlauf kombiniert werden sollen.</span><span class="sxs-lookup"><span data-stu-id="1833d-131">How the data that is collected should be combined over time.</span></span> <span data-ttu-id="1833d-132">Der Standardwert ist "Average".</span><span class="sxs-lookup"><span data-stu-id="1833d-132">The default value is Average.</span></span>
            <span data-ttu-id="1833d-133">Folgende Werte sind möglich: "Durchschnitt", "Minimum", "Maximum", "Total", "Count"</span><span class="sxs-lookup"><span data-stu-id="1833d-133">Possible values include: 'Average', 'Minimum', 'Maximum', 'Total', 'Count'</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TimeGrain">
      <MemberSignature Language="C#" Value="public TimeSpan TimeGrain { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.TimeSpan TimeGrain" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Monitor.Management.Models.MetricTrigger.TimeGrain" />
      <MemberSignature Language="VB.NET" Value="Public Property TimeGrain As TimeSpan" />
      <MemberSignature Language="F#" Value="member this.TimeGrain : TimeSpan with get, set" Usage="Microsoft.Azure.Management.Monitor.Management.Models.MetricTrigger.TimeGrain" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Monitor</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
        <AssemblyVersion>0.18.1.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="timeGrain")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.TimeSpan</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="1833d-134">Ruft ab oder legt überwacht die Granularität der Metriken der Regel.</span><span class="sxs-lookup"><span data-stu-id="1833d-134">Gets or sets the granularity of metrics the rule monitors.</span></span> <span data-ttu-id="1833d-135">Einen der vordefinierten Werte muss von den metrikdefinitionen für die Metrik zurückgegeben werden.</span><span class="sxs-lookup"><span data-stu-id="1833d-135">Must be one of the predefined values returned from metric definitions for the metric.</span></span> <span data-ttu-id="1833d-136">Muss zwischen 12 Stunden und 1 Minute betragen.</span><span class="sxs-lookup"><span data-stu-id="1833d-136">Must be between 12 hours and 1 minute.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TimeWindow">
      <MemberSignature Language="C#" Value="public TimeSpan TimeWindow { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.TimeSpan TimeWindow" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Monitor.Management.Models.MetricTrigger.TimeWindow" />
      <MemberSignature Language="VB.NET" Value="Public Property TimeWindow As TimeSpan" />
      <MemberSignature Language="F#" Value="member this.TimeWindow : TimeSpan with get, set" Usage="Microsoft.Azure.Management.Monitor.Management.Models.MetricTrigger.TimeWindow" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Monitor</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
        <AssemblyVersion>0.18.1.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="timeWindow")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.TimeSpan</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="1833d-137">Ruft ab oder legt die Zeitspanne, in dem Instanzdaten gesammelt werden.</span><span class="sxs-lookup"><span data-stu-id="1833d-137">Gets or sets the range of time in which instance data is collected.</span></span>
            <span data-ttu-id="1833d-138">Dieser Wert muss größer als die Verzögerung bei der metrikerfassung, werden die von Ressource zu Ressource unterschiedlich sein können.</span><span class="sxs-lookup"><span data-stu-id="1833d-138">This value must be greater than the delay in metric collection, which can vary from resource-to-resource.</span></span> <span data-ttu-id="1833d-139">Muss zwischen 12 Stunden und 5 Minuten liegen.</span><span class="sxs-lookup"><span data-stu-id="1833d-139">Must be between 12 hours and 5 minutes.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Monitor.Management.Models.MetricTrigger.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="metricTrigger.Validate " />
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
            <span data-ttu-id="1833d-140">Überprüfen Sie das Objekt.</span><span class="sxs-lookup"><span data-stu-id="1833d-140">Validate the object.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="1833d-141">Wird ausgelöst, wenn die Validierung fehlschlägt</span><span class="sxs-lookup"><span data-stu-id="1833d-141">Thrown if validation fails</span></span>
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>