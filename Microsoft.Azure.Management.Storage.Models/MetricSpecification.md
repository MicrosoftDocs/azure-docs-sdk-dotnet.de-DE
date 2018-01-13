<Type Name="MetricSpecification" FullName="Microsoft.Azure.Management.Storage.Models.MetricSpecification">
  <TypeSignature Language="C#" Value="public class MetricSpecification" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit MetricSpecification extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Storage.Models.MetricSpecification" />
  <TypeSignature Language="VB.NET" Value="Public Class MetricSpecification" />
  <TypeSignature Language="F#" Value="type MetricSpecification = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Storage</AssemblyName>
    <AssemblyVersion>7.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="99a34-101">Metrik Spezifikation des Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="99a34-101">Metric specification of operation.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public MetricSpecification ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Storage.Models.MetricSpecification.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Storage</AssemblyName>
        <AssemblyVersion>7.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="99a34-102">Initialisiert eine neue Instanz der MetricSpecification-Klasse.</span><span class="sxs-lookup"><span data-stu-id="99a34-102">Initializes a new instance of the MetricSpecification class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public MetricSpecification (string name = null, string displayName = null, string displayDescription = null, string unit = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Storage.Models.Dimension&gt; dimensions = null, string aggregationType = null, Nullable&lt;bool&gt; fillGapWithZero = null, string category = null, string resourceIdDimensionNameOverride = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string name, string displayName, string displayDescription, string unit, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Storage.Models.Dimension&gt; dimensions, string aggregationType, valuetype System.Nullable`1&lt;bool&gt; fillGapWithZero, string category, string resourceIdDimensionNameOverride) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Storage.Models.MetricSpecification.#ctor(System.String,System.String,System.String,System.String,System.Collections.Generic.IList{Microsoft.Azure.Management.Storage.Models.Dimension},System.String,System.Nullable{System.Boolean},System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional name As String = null, Optional displayName As String = null, Optional displayDescription As String = null, Optional unit As String = null, Optional dimensions As IList(Of Dimension) = null, Optional aggregationType As String = null, Optional fillGapWithZero As Nullable(Of Boolean) = null, Optional category As String = null, Optional resourceIdDimensionNameOverride As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Storage.Models.MetricSpecification : string * string * string * string * System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Storage.Models.Dimension&gt; * string * Nullable&lt;bool&gt; * string * string -&gt; Microsoft.Azure.Management.Storage.Models.MetricSpecification" Usage="new Microsoft.Azure.Management.Storage.Models.MetricSpecification (name, displayName, displayDescription, unit, dimensions, aggregationType, fillGapWithZero, category, resourceIdDimensionNameOverride)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Storage</AssemblyName>
        <AssemblyVersion>7.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="displayName" Type="System.String" />
        <Parameter Name="displayDescription" Type="System.String" />
        <Parameter Name="unit" Type="System.String" />
        <Parameter Name="dimensions" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Storage.Models.Dimension&gt;" />
        <Parameter Name="aggregationType" Type="System.String" />
        <Parameter Name="fillGapWithZero" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="category" Type="System.String" />
        <Parameter Name="resourceIdDimensionNameOverride" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="name"><span data-ttu-id="99a34-103">Der Name der Metrik-Spezifikation.</span><span class="sxs-lookup"><span data-stu-id="99a34-103">Name of metric specification.</span></span></param>
        <param name="displayName"><span data-ttu-id="99a34-104">Der Anzeigename der Metrik-Spezifikation.</span><span class="sxs-lookup"><span data-stu-id="99a34-104">Display name of metric specification.</span></span></param>
        <param name="displayDescription"><span data-ttu-id="99a34-105">Zeigen Sie die Beschreibung der Metrik-Spezifikation.</span><span class="sxs-lookup"><span data-stu-id="99a34-105">Display description of metric specification.</span></span></param>
        <param name="unit"><span data-ttu-id="99a34-106">Einheit möglicherweise Bytes oder Count.</span><span class="sxs-lookup"><span data-stu-id="99a34-106">Unit could be Bytes or Count.</span></span></param>
        <param name="dimensions"><span data-ttu-id="99a34-107">Dimensionen des Blobs, einschließlich Blob-Typ und Access-Ebene.</span><span class="sxs-lookup"><span data-stu-id="99a34-107">Dimensions of blobs, including blob type and access tier.</span></span></param>
        <param name="aggregationType"><span data-ttu-id="99a34-108">Ist möglicherweise durchschnittlichen Aggregationstyp.</span><span class="sxs-lookup"><span data-stu-id="99a34-108">Aggregation type could be Average.</span></span></param>
        <param name="fillGapWithZero"><span data-ttu-id="99a34-109">Die Eigenschaft entscheiden, füllen Lücken mit 0 (null) oder nicht.</span><span class="sxs-lookup"><span data-stu-id="99a34-109">The property to decide fill gap with zero or not.</span></span></param>
        <param name="category"><span data-ttu-id="99a34-110">Die Kategorie dieser Metrik Spezifikation angehören, ist möglicherweise Kapazität.</span><span class="sxs-lookup"><span data-stu-id="99a34-110">The category this metric specification belong to, could be Capacity.</span></span></param>
        <param name="resourceIdDimensionNameOverride"><span data-ttu-id="99a34-111">Konto-Ressourcen-Id.</span><span class="sxs-lookup"><span data-stu-id="99a34-111">Account Resource Id.</span></span></param>
        <summary>
            <span data-ttu-id="99a34-112">Initialisiert eine neue Instanz der MetricSpecification-Klasse.</span><span class="sxs-lookup"><span data-stu-id="99a34-112">Initializes a new instance of the MetricSpecification class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AggregationType">
      <MemberSignature Language="C#" Value="public string AggregationType { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string AggregationType" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Storage.Models.MetricSpecification.AggregationType" />
      <MemberSignature Language="VB.NET" Value="Public Property AggregationType As String" />
      <MemberSignature Language="F#" Value="member this.AggregationType : string with get, set" Usage="Microsoft.Azure.Management.Storage.Models.MetricSpecification.AggregationType" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Storage</AssemblyName>
        <AssemblyVersion>7.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="aggregationType")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="99a34-113">Ruft ab oder legt ihn fest Aggregation Typ Durchschnitt werden konnte.</span><span class="sxs-lookup"><span data-stu-id="99a34-113">Gets or sets aggregation type could be Average.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Category">
      <MemberSignature Language="C#" Value="public string Category { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Category" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Storage.Models.MetricSpecification.Category" />
      <MemberSignature Language="VB.NET" Value="Public Property Category As String" />
      <MemberSignature Language="F#" Value="member this.Category : string with get, set" Usage="Microsoft.Azure.Management.Storage.Models.MetricSpecification.Category" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Storage</AssemblyName>
        <AssemblyVersion>7.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="category")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="99a34-114">Ruft ab oder legt die Kategorie dieser Metrik Spezifikation angehören, Kapazität werden konnte.</span><span class="sxs-lookup"><span data-stu-id="99a34-114">Gets or sets the category this metric specification belong to, could be Capacity.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Dimensions">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Storage.Models.Dimension&gt; Dimensions { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Storage.Models.Dimension&gt; Dimensions" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Storage.Models.MetricSpecification.Dimensions" />
      <MemberSignature Language="VB.NET" Value="Public Property Dimensions As IList(Of Dimension)" />
      <MemberSignature Language="F#" Value="member this.Dimensions : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Storage.Models.Dimension&gt; with get, set" Usage="Microsoft.Azure.Management.Storage.Models.MetricSpecification.Dimensions" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Storage</AssemblyName>
        <AssemblyVersion>7.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="dimensions")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Storage.Models.Dimension&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="99a34-115">Ruft ab, oder legt ihn fest Dimensionen von Blobs, einschließlich Blob-Typ und Access-Ebene.</span><span class="sxs-lookup"><span data-stu-id="99a34-115">Gets or sets dimensions of blobs, including blob type and access tier.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DisplayDescription">
      <MemberSignature Language="C#" Value="public string DisplayDescription { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string DisplayDescription" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Storage.Models.MetricSpecification.DisplayDescription" />
      <MemberSignature Language="VB.NET" Value="Public Property DisplayDescription As String" />
      <MemberSignature Language="F#" Value="member this.DisplayDescription : string with get, set" Usage="Microsoft.Azure.Management.Storage.Models.MetricSpecification.DisplayDescription" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Storage</AssemblyName>
        <AssemblyVersion>7.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="displayDescription")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="99a34-116">Abrufen oder Festlegen der Beschreibung der Anzeige der Metrik-Spezifikation.</span><span class="sxs-lookup"><span data-stu-id="99a34-116">Gets or sets display description of metric specification.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DisplayName">
      <MemberSignature Language="C#" Value="public string DisplayName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string DisplayName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Storage.Models.MetricSpecification.DisplayName" />
      <MemberSignature Language="VB.NET" Value="Public Property DisplayName As String" />
      <MemberSignature Language="F#" Value="member this.DisplayName : string with get, set" Usage="Microsoft.Azure.Management.Storage.Models.MetricSpecification.DisplayName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Storage</AssemblyName>
        <AssemblyVersion>7.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="displayName")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="99a34-117">Ruft ab oder legt der Anzeigename der Metrik-Spezifikation.</span><span class="sxs-lookup"><span data-stu-id="99a34-117">Gets or sets display name of metric specification.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="FillGapWithZero">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; FillGapWithZero { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; FillGapWithZero" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Storage.Models.MetricSpecification.FillGapWithZero" />
      <MemberSignature Language="VB.NET" Value="Public Property FillGapWithZero As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.FillGapWithZero : Nullable&lt;bool&gt; with get, set" Usage="Microsoft.Azure.Management.Storage.Models.MetricSpecification.FillGapWithZero" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Storage</AssemblyName>
        <AssemblyVersion>7.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="fillGapWithZero")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="99a34-118">Ruft ab, oder Festlegen der Eigenschaft um zu entscheiden, füllen Lücken mit 0 (null) oder nicht.</span><span class="sxs-lookup"><span data-stu-id="99a34-118">Gets or sets the property to decide fill gap with zero or not.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Name">
      <MemberSignature Language="C#" Value="public string Name { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Name" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Storage.Models.MetricSpecification.Name" />
      <MemberSignature Language="VB.NET" Value="Public Property Name As String" />
      <MemberSignature Language="F#" Value="member this.Name : string with get, set" Usage="Microsoft.Azure.Management.Storage.Models.MetricSpecification.Name" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Storage</AssemblyName>
        <AssemblyVersion>7.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="name")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="99a34-119">Ruft ab oder legt den Namen der Metrik-Spezifikation fest.</span><span class="sxs-lookup"><span data-stu-id="99a34-119">Gets or sets name of metric specification.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ResourceIdDimensionNameOverride">
      <MemberSignature Language="C#" Value="public string ResourceIdDimensionNameOverride { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ResourceIdDimensionNameOverride" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Storage.Models.MetricSpecification.ResourceIdDimensionNameOverride" />
      <MemberSignature Language="VB.NET" Value="Public Property ResourceIdDimensionNameOverride As String" />
      <MemberSignature Language="F#" Value="member this.ResourceIdDimensionNameOverride : string with get, set" Usage="Microsoft.Azure.Management.Storage.Models.MetricSpecification.ResourceIdDimensionNameOverride" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Storage</AssemblyName>
        <AssemblyVersion>7.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="resourceIdDimensionNameOverride")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="99a34-120">Ruft ab oder legt ihn fest Konto-Ressourcen-Id.</span><span class="sxs-lookup"><span data-stu-id="99a34-120">Gets or sets account Resource Id.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Unit">
      <MemberSignature Language="C#" Value="public string Unit { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Unit" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Storage.Models.MetricSpecification.Unit" />
      <MemberSignature Language="VB.NET" Value="Public Property Unit As String" />
      <MemberSignature Language="F#" Value="member this.Unit : string with get, set" Usage="Microsoft.Azure.Management.Storage.Models.MetricSpecification.Unit" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Storage</AssemblyName>
        <AssemblyVersion>7.0.0.0</AssemblyVersion>
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
            <span data-ttu-id="99a34-121">Ruft ab oder legt ihn fest Einheit möglicherweise Bytes oder Count.</span><span class="sxs-lookup"><span data-stu-id="99a34-121">Gets or sets unit could be Bytes or Count.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>