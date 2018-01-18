<Type Name="MetricValue" FullName="Microsoft.Azure.Management.Sql.Models.MetricValue">
  <TypeSignature Language="C#" Value="public class MetricValue" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit MetricValue extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Sql.Models.MetricValue" />
  <TypeSignature Language="VB.NET" Value="Public Class MetricValue" />
  <TypeSignature Language="F#" Value="type MetricValue = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.Management.Sql.Models.SubResource</BaseTypeName>
    <BaseTypeName FrameworkAlternate="azure-dotnet">System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="29d57-101">Stellt Metriken-Datenbank.</span><span class="sxs-lookup"><span data-stu-id="29d57-101">Represents database metrics.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public MetricValue ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.Models.MetricValue.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="29d57-102">Initialisiert eine neue Instanz der MetricValue-Klasse.</span><span class="sxs-lookup"><span data-stu-id="29d57-102">Initializes a new instance of the MetricValue class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public MetricValue (Nullable&lt;double&gt; count = null, Nullable&lt;double&gt; average = null, Nullable&lt;double&gt; maximum = null, Nullable&lt;double&gt; minimum = null, Nullable&lt;DateTime&gt; timestamp = null, Nullable&lt;double&gt; total = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(valuetype System.Nullable`1&lt;float64&gt; count, valuetype System.Nullable`1&lt;float64&gt; average, valuetype System.Nullable`1&lt;float64&gt; maximum, valuetype System.Nullable`1&lt;float64&gt; minimum, valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; timestamp, valuetype System.Nullable`1&lt;float64&gt; total) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.Models.MetricValue.#ctor(System.Nullable{System.Double},System.Nullable{System.Double},System.Nullable{System.Double},System.Nullable{System.Double},System.Nullable{System.DateTime},System.Nullable{System.Double})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional count As Nullable(Of Double) = null, Optional average As Nullable(Of Double) = null, Optional maximum As Nullable(Of Double) = null, Optional minimum As Nullable(Of Double) = null, Optional timestamp As Nullable(Of DateTime) = null, Optional total As Nullable(Of Double) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Sql.Models.MetricValue : Nullable&lt;double&gt; * Nullable&lt;double&gt; * Nullable&lt;double&gt; * Nullable&lt;double&gt; * Nullable&lt;DateTime&gt; * Nullable&lt;double&gt; -&gt; Microsoft.Azure.Management.Sql.Models.MetricValue" Usage="new Microsoft.Azure.Management.Sql.Models.MetricValue (count, average, maximum, minimum, timestamp, total)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="count" Type="System.Nullable&lt;System.Double&gt;" />
        <Parameter Name="average" Type="System.Nullable&lt;System.Double&gt;" />
        <Parameter Name="maximum" Type="System.Nullable&lt;System.Double&gt;" />
        <Parameter Name="minimum" Type="System.Nullable&lt;System.Double&gt;" />
        <Parameter Name="timestamp" Type="System.Nullable&lt;System.DateTime&gt;" />
        <Parameter Name="total" Type="System.Nullable&lt;System.Double&gt;" />
      </Parameters>
      <Docs>
        <param name="count"><span data-ttu-id="29d57-103">Die Anzahl der Werte für die Metrik.</span><span class="sxs-lookup"><span data-stu-id="29d57-103">The number of values for the metric.</span></span></param>
        <param name="average"><span data-ttu-id="29d57-104">Der Durchschnittswert der Metrik.</span><span class="sxs-lookup"><span data-stu-id="29d57-104">The average value of the metric.</span></span></param>
        <param name="maximum"><span data-ttu-id="29d57-105">Der maximale Wert der Metrik.</span><span class="sxs-lookup"><span data-stu-id="29d57-105">The max value of the metric.</span></span></param>
        <param name="minimum"><span data-ttu-id="29d57-106">Der Minimalwert der Metrik.</span><span class="sxs-lookup"><span data-stu-id="29d57-106">The min value of the metric.</span></span></param>
        <param name="timestamp"><span data-ttu-id="29d57-107">Der Metrik Zeitstempel (ISO-8601-Format).</span><span class="sxs-lookup"><span data-stu-id="29d57-107">The metric timestamp (ISO-8601 format).</span></span></param>
        <param name="total"><span data-ttu-id="29d57-108">Der Gesamtwert der Metrik.</span><span class="sxs-lookup"><span data-stu-id="29d57-108">The total value of the metric.</span></span></param>
        <summary>
            <span data-ttu-id="29d57-109">Initialisiert eine neue Instanz der MetricValue-Klasse.</span><span class="sxs-lookup"><span data-stu-id="29d57-109">Initializes a new instance of the MetricValue class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Average">
      <MemberSignature Language="C#" Value="public Nullable&lt;double&gt; Average { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;float64&gt; Average" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Models.MetricValue.Average" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Average As Nullable(Of Double)" />
      <MemberSignature Language="F#" Value="member this.Average : Nullable&lt;double&gt;" Usage="Microsoft.Azure.Management.Sql.Models.MetricValue.Average" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="average")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Double&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="29d57-110">Ruft den Durchschnittswert der Metrik an.</span><span class="sxs-lookup"><span data-stu-id="29d57-110">Gets the average value of the metric.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Count">
      <MemberSignature Language="C#" Value="public Nullable&lt;double&gt; Count { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;float64&gt; Count" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Models.MetricValue.Count" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Count As Nullable(Of Double)" />
      <MemberSignature Language="F#" Value="member this.Count : Nullable&lt;double&gt;" Usage="Microsoft.Azure.Management.Sql.Models.MetricValue.Count" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="count")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Double&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="29d57-111">Ruft die Anzahl der Werte für die Metrik an.</span><span class="sxs-lookup"><span data-stu-id="29d57-111">Gets the number of values for the metric.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Maximum">
      <MemberSignature Language="C#" Value="public Nullable&lt;double&gt; Maximum { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;float64&gt; Maximum" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Models.MetricValue.Maximum" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Maximum As Nullable(Of Double)" />
      <MemberSignature Language="F#" Value="member this.Maximum : Nullable&lt;double&gt;" Usage="Microsoft.Azure.Management.Sql.Models.MetricValue.Maximum" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="maximum")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Double&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="29d57-112">Ruft den maximalen Wert der Metrik an.</span><span class="sxs-lookup"><span data-stu-id="29d57-112">Gets the max value of the metric.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Minimum">
      <MemberSignature Language="C#" Value="public Nullable&lt;double&gt; Minimum { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;float64&gt; Minimum" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Models.MetricValue.Minimum" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Minimum As Nullable(Of Double)" />
      <MemberSignature Language="F#" Value="member this.Minimum : Nullable&lt;double&gt;" Usage="Microsoft.Azure.Management.Sql.Models.MetricValue.Minimum" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="minimum")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Double&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="29d57-113">Ruft den Minimalwert der Metrik an.</span><span class="sxs-lookup"><span data-stu-id="29d57-113">Gets the min value of the metric.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Timestamp">
      <MemberSignature Language="C#" Value="public Nullable&lt;DateTime&gt; Timestamp { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; Timestamp" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Models.MetricValue.Timestamp" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Timestamp As Nullable(Of DateTime)" />
      <MemberSignature Language="F#" Value="member this.Timestamp : Nullable&lt;DateTime&gt;" Usage="Microsoft.Azure.Management.Sql.Models.MetricValue.Timestamp" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="timestamp")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.DateTime&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="29d57-114">Ruft die Metrik Zeitstempel (ISO-8601-Format) ab.</span><span class="sxs-lookup"><span data-stu-id="29d57-114">Gets the metric timestamp (ISO-8601 format).</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Total">
      <MemberSignature Language="C#" Value="public Nullable&lt;double&gt; Total { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;float64&gt; Total" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Models.MetricValue.Total" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Total As Nullable(Of Double)" />
      <MemberSignature Language="F#" Value="member this.Total : Nullable&lt;double&gt;" Usage="Microsoft.Azure.Management.Sql.Models.MetricValue.Total" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="total")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Double&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="29d57-115">Ruft den Gesamtwert der Metrik an.</span><span class="sxs-lookup"><span data-stu-id="29d57-115">Gets the total value of the metric.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>