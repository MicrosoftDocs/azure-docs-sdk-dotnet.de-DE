<Type Name="ResourceMetric" FullName="Microsoft.Azure.Management.AppService.Fluent.Models.ResourceMetric">
  <TypeSignature Language="C#" Value="public class ResourceMetric" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit ResourceMetric extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.AppService.Fluent.Models.ResourceMetric" />
  <TypeSignature Language="VB.NET" Value="Public Class ResourceMetric" />
  <TypeSignature Language="F#" Value="type ResourceMetric = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="afb29-101">Objekt, das eine Metrik für jede Ressource darstellt.</span><span class="sxs-lookup"><span data-stu-id="afb29-101">Object representing a metric for any resource .</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ResourceMetric ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.Models.ResourceMetric.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="afb29-102">Initialisiert eine neue Instanz der ResourceMetric-Klasse.</span><span class="sxs-lookup"><span data-stu-id="afb29-102">Initializes a new instance of the ResourceMetric class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ResourceMetric (Microsoft.Azure.Management.AppService.Fluent.Models.ResourceMetricName name = null, string unit = null, string timeGrain = null, Nullable&lt;DateTime&gt; startTime = null, Nullable&lt;DateTime&gt; endTime = null, string resourceId = null, string id = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Management.AppService.Fluent.Models.ResourceMetricValue&gt; metricValues = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Management.AppService.Fluent.Models.ResourceMetricProperty&gt; properties = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class Microsoft.Azure.Management.AppService.Fluent.Models.ResourceMetricName name, string unit, string timeGrain, valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; startTime, valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; endTime, string resourceId, string id, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.AppService.Fluent.Models.ResourceMetricValue&gt; metricValues, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.AppService.Fluent.Models.ResourceMetricProperty&gt; properties) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.Models.ResourceMetric.#ctor(Microsoft.Azure.Management.AppService.Fluent.Models.ResourceMetricName,System.String,System.String,System.Nullable{System.DateTime},System.Nullable{System.DateTime},System.String,System.String,System.Collections.Generic.IList{Microsoft.Azure.Management.AppService.Fluent.Models.ResourceMetricValue},System.Collections.Generic.IList{Microsoft.Azure.Management.AppService.Fluent.Models.ResourceMetricProperty})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional name As ResourceMetricName = null, Optional unit As String = null, Optional timeGrain As String = null, Optional startTime As Nullable(Of DateTime) = null, Optional endTime As Nullable(Of DateTime) = null, Optional resourceId As String = null, Optional id As String = null, Optional metricValues As IList(Of ResourceMetricValue) = null, Optional properties As IList(Of ResourceMetricProperty) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.AppService.Fluent.Models.ResourceMetric : Microsoft.Azure.Management.AppService.Fluent.Models.ResourceMetricName * string * string * Nullable&lt;DateTime&gt; * Nullable&lt;DateTime&gt; * string * string * System.Collections.Generic.IList&lt;Microsoft.Azure.Management.AppService.Fluent.Models.ResourceMetricValue&gt; * System.Collections.Generic.IList&lt;Microsoft.Azure.Management.AppService.Fluent.Models.ResourceMetricProperty&gt; -&gt; Microsoft.Azure.Management.AppService.Fluent.Models.ResourceMetric" Usage="new Microsoft.Azure.Management.AppService.Fluent.Models.ResourceMetric (name, unit, timeGrain, startTime, endTime, resourceId, id, metricValues, properties)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="name" Type="Microsoft.Azure.Management.AppService.Fluent.Models.ResourceMetricName" />
        <Parameter Name="unit" Type="System.String" />
        <Parameter Name="timeGrain" Type="System.String" />
        <Parameter Name="startTime" Type="System.Nullable&lt;System.DateTime&gt;" />
        <Parameter Name="endTime" Type="System.Nullable&lt;System.DateTime&gt;" />
        <Parameter Name="resourceId" Type="System.String" />
        <Parameter Name="id" Type="System.String" />
        <Parameter Name="metricValues" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Management.AppService.Fluent.Models.ResourceMetricValue&gt;" />
        <Parameter Name="properties" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Management.AppService.Fluent.Models.ResourceMetricProperty&gt;" />
      </Parameters>
      <Docs>
        <param name="name"><span data-ttu-id="afb29-103">Der Name der Metrik.</span><span class="sxs-lookup"><span data-stu-id="afb29-103">Name of metric.</span></span></param>
        <param name="unit"><span data-ttu-id="afb29-104">Metrik Einheit.</span><span class="sxs-lookup"><span data-stu-id="afb29-104">Metric unit.</span></span></param>
        <param name="timeGrain"><span data-ttu-id="afb29-105">Metrik Granularität.</span><span class="sxs-lookup"><span data-stu-id="afb29-105">Metric granularity.</span></span> <span data-ttu-id="afb29-106">Z. B. PT1H, PT5M, P1D</span><span class="sxs-lookup"><span data-stu-id="afb29-106">E.g PT1H, PT5M, P1D</span></span></param>
        <param name="startTime"><span data-ttu-id="afb29-107">Metrik Startzeit.</span><span class="sxs-lookup"><span data-stu-id="afb29-107">Metric start time.</span></span></param>
        <param name="endTime"><span data-ttu-id="afb29-108">Endzeit der Metrik.</span><span class="sxs-lookup"><span data-stu-id="afb29-108">Metric end time.</span></span></param>
        <param name="resourceId"><span data-ttu-id="afb29-109">Metrischen Ressourcen-ID</span><span class="sxs-lookup"><span data-stu-id="afb29-109">Metric resource Id.</span></span></param>
        <param name="id"><span data-ttu-id="afb29-110">Ressourcen-Id.</span><span class="sxs-lookup"><span data-stu-id="afb29-110">Resource Id.</span></span></param>
        <param name="metricValues"><span data-ttu-id="afb29-111">Metrikwerte.</span><span class="sxs-lookup"><span data-stu-id="afb29-111">Metric values.</span></span></param>
        <param name="properties"><span data-ttu-id="afb29-112">Eigenschaften.</span><span class="sxs-lookup"><span data-stu-id="afb29-112">Properties.</span></span></param>
        <summary>
            <span data-ttu-id="afb29-113">Initialisiert eine neue Instanz der ResourceMetric-Klasse.</span><span class="sxs-lookup"><span data-stu-id="afb29-113">Initializes a new instance of the ResourceMetric class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EndTime">
      <MemberSignature Language="C#" Value="public Nullable&lt;DateTime&gt; EndTime { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; EndTime" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.AppService.Fluent.Models.ResourceMetric.EndTime" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property EndTime As Nullable(Of DateTime)" />
      <MemberSignature Language="F#" Value="member this.EndTime : Nullable&lt;DateTime&gt;" Usage="Microsoft.Azure.Management.AppService.Fluent.Models.ResourceMetric.EndTime" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
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
            <span data-ttu-id="afb29-114">Ruft die Metrik Endzeit ab.</span><span class="sxs-lookup"><span data-stu-id="afb29-114">Gets metric end time.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Id">
      <MemberSignature Language="C#" Value="public string Id { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Id" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.AppService.Fluent.Models.ResourceMetric.Id" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Id As String" />
      <MemberSignature Language="F#" Value="member this.Id : string" Usage="Microsoft.Azure.Management.AppService.Fluent.Models.ResourceMetric.Id" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
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
            <span data-ttu-id="afb29-115">Ruft die Ressourcen-ID ab</span><span class="sxs-lookup"><span data-stu-id="afb29-115">Gets resource Id.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MetricValues">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Management.AppService.Fluent.Models.ResourceMetricValue&gt; MetricValues { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.AppService.Fluent.Models.ResourceMetricValue&gt; MetricValues" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.AppService.Fluent.Models.ResourceMetric.MetricValues" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property MetricValues As IList(Of ResourceMetricValue)" />
      <MemberSignature Language="F#" Value="member this.MetricValues : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.AppService.Fluent.Models.ResourceMetricValue&gt;" Usage="Microsoft.Azure.Management.AppService.Fluent.Models.ResourceMetric.MetricValues" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="metricValues")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Management.AppService.Fluent.Models.ResourceMetricValue&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="afb29-116">Ruft die Metrik Werte ab.</span><span class="sxs-lookup"><span data-stu-id="afb29-116">Gets metric values.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Name">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.AppService.Fluent.Models.ResourceMetricName Name { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.AppService.Fluent.Models.ResourceMetricName Name" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.AppService.Fluent.Models.ResourceMetric.Name" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Name As ResourceMetricName" />
      <MemberSignature Language="F#" Value="member this.Name : Microsoft.Azure.Management.AppService.Fluent.Models.ResourceMetricName" Usage="Microsoft.Azure.Management.AppService.Fluent.Models.ResourceMetric.Name" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="name")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.AppService.Fluent.Models.ResourceMetricName</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="afb29-117">Ruft den Namen der Metrik.</span><span class="sxs-lookup"><span data-stu-id="afb29-117">Gets name of metric.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Properties">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Management.AppService.Fluent.Models.ResourceMetricProperty&gt; Properties { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.AppService.Fluent.Models.ResourceMetricProperty&gt; Properties" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.AppService.Fluent.Models.ResourceMetric.Properties" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Properties As IList(Of ResourceMetricProperty)" />
      <MemberSignature Language="F#" Value="member this.Properties : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.AppService.Fluent.Models.ResourceMetricProperty&gt;" Usage="Microsoft.Azure.Management.AppService.Fluent.Models.ResourceMetric.Properties" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Management.AppService.Fluent.Models.ResourceMetricProperty&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="afb29-118">Ruft Eigenschaften ab.</span><span class="sxs-lookup"><span data-stu-id="afb29-118">Gets properties.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ResourceId">
      <MemberSignature Language="C#" Value="public string ResourceId { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ResourceId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.AppService.Fluent.Models.ResourceMetric.ResourceId" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ResourceId As String" />
      <MemberSignature Language="F#" Value="member this.ResourceId : string" Usage="Microsoft.Azure.Management.AppService.Fluent.Models.ResourceMetric.ResourceId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
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
            <span data-ttu-id="afb29-119">Ruft die Metrik-Ressourcen-ID ab</span><span class="sxs-lookup"><span data-stu-id="afb29-119">Gets metric resource Id.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="StartTime">
      <MemberSignature Language="C#" Value="public Nullable&lt;DateTime&gt; StartTime { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; StartTime" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.AppService.Fluent.Models.ResourceMetric.StartTime" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property StartTime As Nullable(Of DateTime)" />
      <MemberSignature Language="F#" Value="member this.StartTime : Nullable&lt;DateTime&gt;" Usage="Microsoft.Azure.Management.AppService.Fluent.Models.ResourceMetric.StartTime" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
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
            <span data-ttu-id="afb29-120">Ruft die Metrik Startzeit ab.</span><span class="sxs-lookup"><span data-stu-id="afb29-120">Gets metric start time.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TimeGrain">
      <MemberSignature Language="C#" Value="public string TimeGrain { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string TimeGrain" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.AppService.Fluent.Models.ResourceMetric.TimeGrain" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property TimeGrain As String" />
      <MemberSignature Language="F#" Value="member this.TimeGrain : string" Usage="Microsoft.Azure.Management.AppService.Fluent.Models.ResourceMetric.TimeGrain" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
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
            <span data-ttu-id="afb29-121">Ruft die Metrik Granularität ab.</span><span class="sxs-lookup"><span data-stu-id="afb29-121">Gets metric granularity.</span></span> <span data-ttu-id="afb29-122">Z. B. PT1H, PT5M, P1D</span><span class="sxs-lookup"><span data-stu-id="afb29-122">E.g PT1H, PT5M, P1D</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Unit">
      <MemberSignature Language="C#" Value="public string Unit { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Unit" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.AppService.Fluent.Models.ResourceMetric.Unit" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Unit As String" />
      <MemberSignature Language="F#" Value="member this.Unit : string" Usage="Microsoft.Azure.Management.AppService.Fluent.Models.ResourceMetric.Unit" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
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
            <span data-ttu-id="afb29-123">Ruft die Metrik Einheit ab.</span><span class="sxs-lookup"><span data-stu-id="afb29-123">Gets metric unit.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>