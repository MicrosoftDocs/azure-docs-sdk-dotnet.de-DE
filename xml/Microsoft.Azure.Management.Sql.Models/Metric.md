<Type Name="Metric" FullName="Microsoft.Azure.Management.Sql.Models.Metric">
  <TypeSignature Language="C#" Value="public class Metric" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit Metric extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Sql.Models.Metric" />
  <TypeSignature Language="VB.NET" Value="Public Class Metric" />
  <TypeSignature Language="F#" Value="type Metric = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="f5276-101">Datenbank-Metriken.</span><span class="sxs-lookup"><span data-stu-id="f5276-101">Database metrics.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public Metric ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.Models.Metric.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="f5276-102">Initialisiert eine neue Instanz der Metrik-Klasse.</span><span class="sxs-lookup"><span data-stu-id="f5276-102">Initializes a new instance of the Metric class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public Metric (Nullable&lt;DateTime&gt; startTime = null, Nullable&lt;DateTime&gt; endTime = null, string timeGrain = null, string unit = null, Microsoft.Azure.Management.Sql.Models.MetricName name = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Sql.Models.MetricValue&gt; metricValues = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; startTime, valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; endTime, string timeGrain, string unit, class Microsoft.Azure.Management.Sql.Models.MetricName name, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Sql.Models.MetricValue&gt; metricValues) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.Models.Metric.#ctor(System.Nullable{System.DateTime},System.Nullable{System.DateTime},System.String,System.String,Microsoft.Azure.Management.Sql.Models.MetricName,System.Collections.Generic.IList{Microsoft.Azure.Management.Sql.Models.MetricValue})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional startTime As Nullable(Of DateTime) = null, Optional endTime As Nullable(Of DateTime) = null, Optional timeGrain As String = null, Optional unit As String = null, Optional name As MetricName = null, Optional metricValues As IList(Of MetricValue) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Sql.Models.Metric : Nullable&lt;DateTime&gt; * Nullable&lt;DateTime&gt; * string * string * Microsoft.Azure.Management.Sql.Models.MetricName * System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Sql.Models.MetricValue&gt; -&gt; Microsoft.Azure.Management.Sql.Models.Metric" Usage="new Microsoft.Azure.Management.Sql.Models.Metric (startTime, endTime, timeGrain, unit, name, metricValues)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="startTime" Type="System.Nullable&lt;System.DateTime&gt;" />
        <Parameter Name="endTime" Type="System.Nullable&lt;System.DateTime&gt;" />
        <Parameter Name="timeGrain" Type="System.String" />
        <Parameter Name="unit" Type="System.String" />
        <Parameter Name="name" Type="Microsoft.Azure.Management.Sql.Models.MetricName" />
        <Parameter Name="metricValues" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Sql.Models.MetricValue&gt;" />
      </Parameters>
      <Docs>
        <param name="startTime"><span data-ttu-id="f5276-103">Die Startzeit für die Metrik (ISO-8601-Format).</span><span class="sxs-lookup"><span data-stu-id="f5276-103">The start time for the metric (ISO-8601 format).</span></span></param>
        <param name="endTime"><span data-ttu-id="f5276-104">Die Endzeit für die Metrik (ISO-8601-Format).</span><span class="sxs-lookup"><span data-stu-id="f5276-104">The end time for the metric (ISO-8601 format).</span></span></param>
        <param name="timeGrain"><span data-ttu-id="f5276-105">Der Zeitschritt verwendet werden, um die Metrikwerte zusammenzufassen.</span><span class="sxs-lookup"><span data-stu-id="f5276-105">The time step to be used to summarize the metric values.</span></span></param>
        <param name="unit"><span data-ttu-id="f5276-106">Die Einheit der Metrik.</span><span class="sxs-lookup"><span data-stu-id="f5276-106">The unit of the metric.</span></span> <span data-ttu-id="f5276-107">Folgende Werte sind möglich: "Count", "Byte", "Sekunden", "Prozent", "CountPerSecond", "BytesPerSecond"</span><span class="sxs-lookup"><span data-stu-id="f5276-107">Possible values include: 'count', 'bytes', 'seconds', 'percent', 'countPerSecond', 'bytesPerSecond'</span></span></param>
        <param name="name"><span data-ttu-id="f5276-108">Die Informationen für die Metrik.</span><span class="sxs-lookup"><span data-stu-id="f5276-108">The name information for the metric.</span></span></param>
        <param name="metricValues"><span data-ttu-id="f5276-109">Die Metrik Werte für das angegebene Zeitfenster und Timestep.</span><span class="sxs-lookup"><span data-stu-id="f5276-109">The metric values for the specified time window and timestep.</span></span></param>
        <summary>
            <span data-ttu-id="f5276-110">Initialisiert eine neue Instanz der Metrik-Klasse.</span><span class="sxs-lookup"><span data-stu-id="f5276-110">Initializes a new instance of the Metric class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EndTime">
      <MemberSignature Language="C#" Value="public Nullable&lt;DateTime&gt; EndTime { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; EndTime" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Models.Metric.EndTime" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property EndTime As Nullable(Of DateTime)" />
      <MemberSignature Language="F#" Value="member this.EndTime : Nullable&lt;DateTime&gt;" Usage="Microsoft.Azure.Management.Sql.Models.Metric.EndTime" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="endTime")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.DateTime&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="f5276-111">Ruft die Endzeit für die Metrik (ISO-8601-Format) ab.</span><span class="sxs-lookup"><span data-stu-id="f5276-111">Gets the end time for the metric (ISO-8601 format).</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MetricValues">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Sql.Models.MetricValue&gt; MetricValues { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Sql.Models.MetricValue&gt; MetricValues" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Models.Metric.MetricValues" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property MetricValues As IList(Of MetricValue)" />
      <MemberSignature Language="F#" Value="member this.MetricValues : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Sql.Models.MetricValue&gt;" Usage="Microsoft.Azure.Management.Sql.Models.Metric.MetricValues" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="metricValues")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Sql.Models.MetricValue&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="f5276-112">Ruft die Metrik Werte für das angegebene Zeitfenster und Timestep ab.</span><span class="sxs-lookup"><span data-stu-id="f5276-112">Gets the metric values for the specified time window and timestep.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Name">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Sql.Models.MetricName Name { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Sql.Models.MetricName Name" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Models.Metric.Name" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Name As MetricName" />
      <MemberSignature Language="F#" Value="member this.Name : Microsoft.Azure.Management.Sql.Models.MetricName" Usage="Microsoft.Azure.Management.Sql.Models.Metric.Name" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="name")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Sql.Models.MetricName</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="f5276-113">Ruft die Informationen für die Metrik ab.</span><span class="sxs-lookup"><span data-stu-id="f5276-113">Gets the name information for the metric.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="StartTime">
      <MemberSignature Language="C#" Value="public Nullable&lt;DateTime&gt; StartTime { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; StartTime" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Models.Metric.StartTime" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property StartTime As Nullable(Of DateTime)" />
      <MemberSignature Language="F#" Value="member this.StartTime : Nullable&lt;DateTime&gt;" Usage="Microsoft.Azure.Management.Sql.Models.Metric.StartTime" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="startTime")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.DateTime&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="f5276-114">Ruft die Startzeit für die Metrik (ISO-8601-Format) ab.</span><span class="sxs-lookup"><span data-stu-id="f5276-114">Gets the start time for the metric (ISO-8601 format).</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TimeGrain">
      <MemberSignature Language="C#" Value="public string TimeGrain { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string TimeGrain" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Models.Metric.TimeGrain" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property TimeGrain As String" />
      <MemberSignature Language="F#" Value="member this.TimeGrain : string" Usage="Microsoft.Azure.Management.Sql.Models.Metric.TimeGrain" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="timeGrain")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="f5276-115">Ruft den Zeitschritt verwendet werden, um die Metrikwerte zusammenzufassen.</span><span class="sxs-lookup"><span data-stu-id="f5276-115">Gets the time step to be used to summarize the metric values.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Unit">
      <MemberSignature Language="C#" Value="public string Unit { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Unit" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Models.Metric.Unit" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Unit As String" />
      <MemberSignature Language="F#" Value="member this.Unit : string" Usage="Microsoft.Azure.Management.Sql.Models.Metric.Unit" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="unit")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="f5276-116">Ruft die Maßeinheit der Metrik an.</span><span class="sxs-lookup"><span data-stu-id="f5276-116">Gets the unit of the metric.</span></span> <span data-ttu-id="f5276-117">Folgende Werte sind möglich: "Count", "Byte", "Sekunden", "Prozent", "CountPerSecond", "BytesPerSecond"</span><span class="sxs-lookup"><span data-stu-id="f5276-117">Possible values include: 'count', 'bytes', 'seconds', 'percent', 'countPerSecond', 'bytesPerSecond'</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>