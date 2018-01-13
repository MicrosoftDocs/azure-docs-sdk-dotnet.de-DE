<Type Name="ResourceMetricValue" FullName="Microsoft.Azure.Management.AppService.Fluent.Models.ResourceMetricValue">
  <TypeSignature Language="C#" Value="public class ResourceMetricValue" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit ResourceMetricValue extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.AppService.Fluent.Models.ResourceMetricValue" />
  <TypeSignature Language="VB.NET" Value="Public Class ResourceMetricValue" />
  <TypeSignature Language="F#" Value="type ResourceMetricValue = class" />
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
            <span data-ttu-id="e2c5f-101">Der Wert der ressourcenmetriken.</span><span class="sxs-lookup"><span data-stu-id="e2c5f-101">Value of resource metric.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ResourceMetricValue ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.Models.ResourceMetricValue.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="e2c5f-102">Initialisiert eine neue Instanz der ResourceMetricValue-Klasse.</span><span class="sxs-lookup"><span data-stu-id="e2c5f-102">Initializes a new instance of the ResourceMetricValue class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ResourceMetricValue (string timestamp = null, Nullable&lt;double&gt; average = null, Nullable&lt;double&gt; minimum = null, Nullable&lt;double&gt; maximum = null, Nullable&lt;double&gt; total = null, Nullable&lt;double&gt; count = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Management.AppService.Fluent.Models.ResourceMetricProperty&gt; properties = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string timestamp, valuetype System.Nullable`1&lt;float64&gt; average, valuetype System.Nullable`1&lt;float64&gt; minimum, valuetype System.Nullable`1&lt;float64&gt; maximum, valuetype System.Nullable`1&lt;float64&gt; total, valuetype System.Nullable`1&lt;float64&gt; count, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.AppService.Fluent.Models.ResourceMetricProperty&gt; properties) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.Models.ResourceMetricValue.#ctor(System.String,System.Nullable{System.Double},System.Nullable{System.Double},System.Nullable{System.Double},System.Nullable{System.Double},System.Nullable{System.Double},System.Collections.Generic.IList{Microsoft.Azure.Management.AppService.Fluent.Models.ResourceMetricProperty})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional timestamp As String = null, Optional average As Nullable(Of Double) = null, Optional minimum As Nullable(Of Double) = null, Optional maximum As Nullable(Of Double) = null, Optional total As Nullable(Of Double) = null, Optional count As Nullable(Of Double) = null, Optional properties As IList(Of ResourceMetricProperty) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.AppService.Fluent.Models.ResourceMetricValue : string * Nullable&lt;double&gt; * Nullable&lt;double&gt; * Nullable&lt;double&gt; * Nullable&lt;double&gt; * Nullable&lt;double&gt; * System.Collections.Generic.IList&lt;Microsoft.Azure.Management.AppService.Fluent.Models.ResourceMetricProperty&gt; -&gt; Microsoft.Azure.Management.AppService.Fluent.Models.ResourceMetricValue" Usage="new Microsoft.Azure.Management.AppService.Fluent.Models.ResourceMetricValue (timestamp, average, minimum, maximum, total, count, properties)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="timestamp" Type="System.String" />
        <Parameter Name="average" Type="System.Nullable&lt;System.Double&gt;" />
        <Parameter Name="minimum" Type="System.Nullable&lt;System.Double&gt;" />
        <Parameter Name="maximum" Type="System.Nullable&lt;System.Double&gt;" />
        <Parameter Name="total" Type="System.Nullable&lt;System.Double&gt;" />
        <Parameter Name="count" Type="System.Nullable&lt;System.Double&gt;" />
        <Parameter Name="properties" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Management.AppService.Fluent.Models.ResourceMetricProperty&gt;" />
      </Parameters>
      <Docs>
        <param name="timestamp"><span data-ttu-id="e2c5f-103">Timestamp-Wert.</span><span class="sxs-lookup"><span data-stu-id="e2c5f-103">Value timestamp.</span></span></param>
        <param name="average"><span data-ttu-id="e2c5f-104">Wert Durchschnitt.</span><span class="sxs-lookup"><span data-stu-id="e2c5f-104">Value average.</span></span></param>
        <param name="minimum"><span data-ttu-id="e2c5f-105">Wert von Minimum.</span><span class="sxs-lookup"><span data-stu-id="e2c5f-105">Value minimum.</span></span></param>
        <param name="maximum"><span data-ttu-id="e2c5f-106">Wert maximal.</span><span class="sxs-lookup"><span data-stu-id="e2c5f-106">Value maximum.</span></span></param>
        <param name="total"><span data-ttu-id="e2c5f-107">Gesamtwert.</span><span class="sxs-lookup"><span data-stu-id="e2c5f-107">Value total.</span></span></param>
        <param name="count"><span data-ttu-id="e2c5f-108">Count-Wert.</span><span class="sxs-lookup"><span data-stu-id="e2c5f-108">Value count.</span></span></param>
        <param name="properties"><span data-ttu-id="e2c5f-109">Eigenschaften.</span><span class="sxs-lookup"><span data-stu-id="e2c5f-109">Properties.</span></span></param>
        <summary>
            <span data-ttu-id="e2c5f-110">Initialisiert eine neue Instanz der ResourceMetricValue-Klasse.</span><span class="sxs-lookup"><span data-stu-id="e2c5f-110">Initializes a new instance of the ResourceMetricValue class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Average">
      <MemberSignature Language="C#" Value="public Nullable&lt;double&gt; Average { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;float64&gt; Average" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.AppService.Fluent.Models.ResourceMetricValue.Average" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Average As Nullable(Of Double)" />
      <MemberSignature Language="F#" Value="member this.Average : Nullable&lt;double&gt;" Usage="Microsoft.Azure.Management.AppService.Fluent.Models.ResourceMetricValue.Average" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
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
            <span data-ttu-id="e2c5f-111">Ruft die durchschnittlichen Wert.</span><span class="sxs-lookup"><span data-stu-id="e2c5f-111">Gets value average.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Count">
      <MemberSignature Language="C#" Value="public Nullable&lt;double&gt; Count { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;float64&gt; Count" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.AppService.Fluent.Models.ResourceMetricValue.Count" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Count As Nullable(Of Double)" />
      <MemberSignature Language="F#" Value="member this.Count : Nullable&lt;double&gt;" Usage="Microsoft.Azure.Management.AppService.Fluent.Models.ResourceMetricValue.Count" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
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
            <span data-ttu-id="e2c5f-112">Ruft die Anzahl an.</span><span class="sxs-lookup"><span data-stu-id="e2c5f-112">Gets value count.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Maximum">
      <MemberSignature Language="C#" Value="public Nullable&lt;double&gt; Maximum { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;float64&gt; Maximum" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.AppService.Fluent.Models.ResourceMetricValue.Maximum" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Maximum As Nullable(Of Double)" />
      <MemberSignature Language="F#" Value="member this.Maximum : Nullable&lt;double&gt;" Usage="Microsoft.Azure.Management.AppService.Fluent.Models.ResourceMetricValue.Maximum" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
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
            <span data-ttu-id="e2c5f-113">Ruft den Wert maximale ab.</span><span class="sxs-lookup"><span data-stu-id="e2c5f-113">Gets value maximum.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Minimum">
      <MemberSignature Language="C#" Value="public Nullable&lt;double&gt; Minimum { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;float64&gt; Minimum" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.AppService.Fluent.Models.ResourceMetricValue.Minimum" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Minimum As Nullable(Of Double)" />
      <MemberSignature Language="F#" Value="member this.Minimum : Nullable&lt;double&gt;" Usage="Microsoft.Azure.Management.AppService.Fluent.Models.ResourceMetricValue.Minimum" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
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
            <span data-ttu-id="e2c5f-114">Ruft den Wert minimale ab.</span><span class="sxs-lookup"><span data-stu-id="e2c5f-114">Gets value minimum.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Properties">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Management.AppService.Fluent.Models.ResourceMetricProperty&gt; Properties { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.AppService.Fluent.Models.ResourceMetricProperty&gt; Properties" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.AppService.Fluent.Models.ResourceMetricValue.Properties" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Properties As IList(Of ResourceMetricProperty)" />
      <MemberSignature Language="F#" Value="member this.Properties : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.AppService.Fluent.Models.ResourceMetricProperty&gt;" Usage="Microsoft.Azure.Management.AppService.Fluent.Models.ResourceMetricValue.Properties" />
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
            <span data-ttu-id="e2c5f-115">Ruft Eigenschaften ab.</span><span class="sxs-lookup"><span data-stu-id="e2c5f-115">Gets properties.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Timestamp">
      <MemberSignature Language="C#" Value="public string Timestamp { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Timestamp" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.AppService.Fluent.Models.ResourceMetricValue.Timestamp" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Timestamp As String" />
      <MemberSignature Language="F#" Value="member this.Timestamp : string" Usage="Microsoft.Azure.Management.AppService.Fluent.Models.ResourceMetricValue.Timestamp" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="timestamp")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="e2c5f-116">Ruft Timestamp-Wert.</span><span class="sxs-lookup"><span data-stu-id="e2c5f-116">Gets value timestamp.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Total">
      <MemberSignature Language="C#" Value="public Nullable&lt;double&gt; Total { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;float64&gt; Total" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.AppService.Fluent.Models.ResourceMetricValue.Total" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Total As Nullable(Of Double)" />
      <MemberSignature Language="F#" Value="member this.Total : Nullable&lt;double&gt;" Usage="Microsoft.Azure.Management.AppService.Fluent.Models.ResourceMetricValue.Total" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
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
            <span data-ttu-id="e2c5f-117">Ruft den Wert insgesamt ab.</span><span class="sxs-lookup"><span data-stu-id="e2c5f-117">Gets value total.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>