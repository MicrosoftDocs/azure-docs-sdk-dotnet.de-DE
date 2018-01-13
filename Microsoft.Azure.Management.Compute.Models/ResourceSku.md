<Type Name="ResourceSku" FullName="Microsoft.Azure.Management.Compute.Models.ResourceSku">
  <TypeSignature Language="C#" Value="public class ResourceSku" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit ResourceSku extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Compute.Models.ResourceSku" />
  <TypeSignature Language="VB.NET" Value="Public Class ResourceSku" />
  <TypeSignature Language="F#" Value="type ResourceSku = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
    <AssemblyVersion>16.0.0.0</AssemblyVersion>
    <AssemblyVersion>17.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="4d928-101">Beschreibt eine verfügbare Compute-SKU.</span><span class="sxs-lookup"><span data-stu-id="4d928-101">Describes an available Compute SKU.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ResourceSku ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Models.ResourceSku.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="4d928-102">Initialisiert eine neue Instanz der ResourceSku-Klasse.</span><span class="sxs-lookup"><span data-stu-id="4d928-102">Initializes a new instance of the ResourceSku class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ResourceSku (string resourceType = null, string name = null, string tier = null, string size = null, string family = null, string kind = null, Microsoft.Azure.Management.Compute.Models.ResourceSkuCapacity capacity = null, System.Collections.Generic.IList&lt;string&gt; locations = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Compute.Models.ResourceSkuLocationInfo&gt; locationInfo = null, System.Collections.Generic.IList&lt;string&gt; apiVersions = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Compute.Models.ResourceSkuCosts&gt; costs = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Compute.Models.ResourceSkuCapabilities&gt; capabilities = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Compute.Models.ResourceSkuRestrictions&gt; restrictions = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string resourceType, string name, string tier, string size, string family, string kind, class Microsoft.Azure.Management.Compute.Models.ResourceSkuCapacity capacity, class System.Collections.Generic.IList`1&lt;string&gt; locations, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Compute.Models.ResourceSkuLocationInfo&gt; locationInfo, class System.Collections.Generic.IList`1&lt;string&gt; apiVersions, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Compute.Models.ResourceSkuCosts&gt; costs, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Compute.Models.ResourceSkuCapabilities&gt; capabilities, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Compute.Models.ResourceSkuRestrictions&gt; restrictions) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Models.ResourceSku.#ctor(System.String,System.String,System.String,System.String,System.String,System.String,Microsoft.Azure.Management.Compute.Models.ResourceSkuCapacity,System.Collections.Generic.IList{System.String},System.Collections.Generic.IList{Microsoft.Azure.Management.Compute.Models.ResourceSkuLocationInfo},System.Collections.Generic.IList{System.String},System.Collections.Generic.IList{Microsoft.Azure.Management.Compute.Models.ResourceSkuCosts},System.Collections.Generic.IList{Microsoft.Azure.Management.Compute.Models.ResourceSkuCapabilities},System.Collections.Generic.IList{Microsoft.Azure.Management.Compute.Models.ResourceSkuRestrictions})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional resourceType As String = null, Optional name As String = null, Optional tier As String = null, Optional size As String = null, Optional family As String = null, Optional kind As String = null, Optional capacity As ResourceSkuCapacity = null, Optional locations As IList(Of String) = null, Optional locationInfo As IList(Of ResourceSkuLocationInfo) = null, Optional apiVersions As IList(Of String) = null, Optional costs As IList(Of ResourceSkuCosts) = null, Optional capabilities As IList(Of ResourceSkuCapabilities) = null, Optional restrictions As IList(Of ResourceSkuRestrictions) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Compute.Models.ResourceSku : string * string * string * string * string * string * Microsoft.Azure.Management.Compute.Models.ResourceSkuCapacity * System.Collections.Generic.IList&lt;string&gt; * System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Compute.Models.ResourceSkuLocationInfo&gt; * System.Collections.Generic.IList&lt;string&gt; * System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Compute.Models.ResourceSkuCosts&gt; * System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Compute.Models.ResourceSkuCapabilities&gt; * System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Compute.Models.ResourceSkuRestrictions&gt; -&gt; Microsoft.Azure.Management.Compute.Models.ResourceSku" Usage="new Microsoft.Azure.Management.Compute.Models.ResourceSku (resourceType, name, tier, size, family, kind, capacity, locations, locationInfo, apiVersions, costs, capabilities, restrictions)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="resourceType" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="tier" Type="System.String" />
        <Parameter Name="size" Type="System.String" />
        <Parameter Name="family" Type="System.String" />
        <Parameter Name="kind" Type="System.String" />
        <Parameter Name="capacity" Type="Microsoft.Azure.Management.Compute.Models.ResourceSkuCapacity" />
        <Parameter Name="locations" Type="System.Collections.Generic.IList&lt;System.String&gt;" />
        <Parameter Name="locationInfo" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Compute.Models.ResourceSkuLocationInfo&gt;" />
        <Parameter Name="apiVersions" Type="System.Collections.Generic.IList&lt;System.String&gt;" />
        <Parameter Name="costs" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Compute.Models.ResourceSkuCosts&gt;" />
        <Parameter Name="capabilities" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Compute.Models.ResourceSkuCapabilities&gt;" />
        <Parameter Name="restrictions" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Compute.Models.ResourceSkuRestrictions&gt;" />
      </Parameters>
      <Docs>
        <param name="resourceType"><span data-ttu-id="4d928-103">Der Typ der Ressource die SKU gilt.</span><span class="sxs-lookup"><span data-stu-id="4d928-103">The type of resource the SKU applies to.</span></span></param>
        <param name="name"><span data-ttu-id="4d928-104">Der Name der SKU.</span><span class="sxs-lookup"><span data-stu-id="4d928-104">The name of SKU.</span></span></param>
        <param name="tier"><span data-ttu-id="4d928-105">Gibt die Ebene der virtuellen Computer in einer Skala an. &lt;Br /&gt;&lt;Br /&gt; mögliche Werte:&lt;Br /&gt;&lt;Br /&gt; **Standard**&lt;Br /&gt; &lt;Br /&gt; **grundlegende**</span><span class="sxs-lookup"><span data-stu-id="4d928-105">Specifies the tier of virtual machines in a scale set.&lt;br /&gt;&lt;br /&gt; Possible Values:&lt;br /&gt;&lt;br /&gt; **Standard**&lt;br /&gt;&lt;br /&gt; **Basic**</span></span></param>
        <param name="size"><span data-ttu-id="4d928-106">Die Größe der SKU.</span><span class="sxs-lookup"><span data-stu-id="4d928-106">The Size of the SKU.</span></span></param>
        <param name="family"><span data-ttu-id="4d928-107">Der dieser bestimmten SKU-Familie.</span><span class="sxs-lookup"><span data-stu-id="4d928-107">The Family of this particular SKU.</span></span></param>
        <param name="kind"><span data-ttu-id="4d928-108">Die Art der Ressourcen, die in dieser SKU unterstützt werden.</span><span class="sxs-lookup"><span data-stu-id="4d928-108">The Kind of resources that are supported in this SKU.</span></span></param>
        <param name="capacity"><span data-ttu-id="4d928-109">Gibt die Anzahl von virtuellen Computern in der Menge der Skala an.</span><span class="sxs-lookup"><span data-stu-id="4d928-109">Specifies the number of virtual machines in the scale set.</span></span></param>
        <param name="locations"><span data-ttu-id="4d928-110">Der Satz von Speicherorten, dass die SKU verfügbar ist.</span><span class="sxs-lookup"><span data-stu-id="4d928-110">The set of locations that the SKU is available.</span></span></param>
        <param name="locationInfo"><span data-ttu-id="4d928-111">Eine Liste der Orte und Verfügbarkeit Zonen an diesen Standorten, in denen die SKU verfügbar ist.</span><span class="sxs-lookup"><span data-stu-id="4d928-111">A list of locations and availability zones in those locations where the SKU is available.</span></span></param>
        <param name="apiVersions"><span data-ttu-id="4d928-112">Die api-Versionen, die dieser SKU zu unterstützen.</span><span class="sxs-lookup"><span data-stu-id="4d928-112">The api versions that support this SKU.</span></span></param>
        <param name="costs"><span data-ttu-id="4d928-113">Metadaten für das Abrufen von Preisinformationen zu.</span><span class="sxs-lookup"><span data-stu-id="4d928-113">Metadata for retrieving price info.</span></span></param>
        <param name="capabilities"><span data-ttu-id="4d928-114">Ein Name-Wert-Paar um die Funktion zu beschreiben.</span><span class="sxs-lookup"><span data-stu-id="4d928-114">A name value pair to describe the capability.</span></span></param>
        <param name="restrictions"><span data-ttu-id="4d928-115">Die Einschränkungen aufgrund, die SKU verwendet werden kann.</span><span class="sxs-lookup"><span data-stu-id="4d928-115">The restrictions because of which SKU cannot be used.</span></span> <span data-ttu-id="4d928-116">Dies ist leer, wenn es keine Einschränkungen gibt.</span><span class="sxs-lookup"><span data-stu-id="4d928-116">This is empty if there are no restrictions.</span></span></param>
        <summary>
            <span data-ttu-id="4d928-117">Initialisiert eine neue Instanz der ResourceSku-Klasse.</span><span class="sxs-lookup"><span data-stu-id="4d928-117">Initializes a new instance of the ResourceSku class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ApiVersions">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;string&gt; ApiVersions { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;string&gt; ApiVersions" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Models.ResourceSku.ApiVersions" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ApiVersions As IList(Of String)" />
      <MemberSignature Language="F#" Value="member this.ApiVersions : System.Collections.Generic.IList&lt;string&gt;" Usage="Microsoft.Azure.Management.Compute.Models.ResourceSku.ApiVersions" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="apiVersions")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;System.String&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="4d928-118">Ruft die api-Versionen, die dieser SKU zu unterstützen.</span><span class="sxs-lookup"><span data-stu-id="4d928-118">Gets the api versions that support this SKU.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Capabilities">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Compute.Models.ResourceSkuCapabilities&gt; Capabilities { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Compute.Models.ResourceSkuCapabilities&gt; Capabilities" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Models.ResourceSku.Capabilities" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Capabilities As IList(Of ResourceSkuCapabilities)" />
      <MemberSignature Language="F#" Value="member this.Capabilities : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Compute.Models.ResourceSkuCapabilities&gt;" Usage="Microsoft.Azure.Management.Compute.Models.ResourceSku.Capabilities" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="capabilities")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Compute.Models.ResourceSkuCapabilities&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="4d928-119">Ruft ein Name-Wert-Paar, um die Funktion zu beschreiben.</span><span class="sxs-lookup"><span data-stu-id="4d928-119">Gets a name value pair to describe the capability.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Capacity">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Models.ResourceSkuCapacity Capacity { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Compute.Models.ResourceSkuCapacity Capacity" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Models.ResourceSku.Capacity" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Capacity As ResourceSkuCapacity" />
      <MemberSignature Language="F#" Value="member this.Capacity : Microsoft.Azure.Management.Compute.Models.ResourceSkuCapacity" Usage="Microsoft.Azure.Management.Compute.Models.ResourceSku.Capacity" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="capacity")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Models.ResourceSkuCapacity</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="4d928-120">Ruft gibt die Anzahl von virtuellen Computern in der Menge der Skala an.</span><span class="sxs-lookup"><span data-stu-id="4d928-120">Gets specifies the number of virtual machines in the scale set.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Costs">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Compute.Models.ResourceSkuCosts&gt; Costs { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Compute.Models.ResourceSkuCosts&gt; Costs" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Models.ResourceSku.Costs" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Costs As IList(Of ResourceSkuCosts)" />
      <MemberSignature Language="F#" Value="member this.Costs : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Compute.Models.ResourceSkuCosts&gt;" Usage="Microsoft.Azure.Management.Compute.Models.ResourceSku.Costs" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="costs")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Compute.Models.ResourceSkuCosts&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="4d928-121">Ruft Metadaten für das Abrufen von Preisinformationen zu ab.</span><span class="sxs-lookup"><span data-stu-id="4d928-121">Gets metadata for retrieving price info.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Family">
      <MemberSignature Language="C#" Value="public string Family { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Family" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Models.ResourceSku.Family" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Family As String" />
      <MemberSignature Language="F#" Value="member this.Family : string" Usage="Microsoft.Azure.Management.Compute.Models.ResourceSku.Family" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="family")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="4d928-122">Ruft ab, der dieser bestimmten SKU-Familie.</span><span class="sxs-lookup"><span data-stu-id="4d928-122">Gets the Family of this particular SKU.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Kind">
      <MemberSignature Language="C#" Value="public string Kind { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Kind" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Models.ResourceSku.Kind" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Kind As String" />
      <MemberSignature Language="F#" Value="member this.Kind : string" Usage="Microsoft.Azure.Management.Compute.Models.ResourceSku.Kind" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="kind")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="4d928-123">Ruft die Art von Ressourcen, die in dieser SKU unterstützt werden.</span><span class="sxs-lookup"><span data-stu-id="4d928-123">Gets the Kind of resources that are supported in this SKU.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="LocationInfo">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Compute.Models.ResourceSkuLocationInfo&gt; LocationInfo { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Compute.Models.ResourceSkuLocationInfo&gt; LocationInfo" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Models.ResourceSku.LocationInfo" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property LocationInfo As IList(Of ResourceSkuLocationInfo)" />
      <MemberSignature Language="F#" Value="member this.LocationInfo : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Compute.Models.ResourceSkuLocationInfo&gt;" Usage="Microsoft.Azure.Management.Compute.Models.ResourceSku.LocationInfo" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="locationInfo")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Compute.Models.ResourceSkuLocationInfo&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="4d928-124">Ruft eine Liste der Orte und Verfügbarkeit Zonen an diesen Standorten, in denen die SKU verfügbar ist.</span><span class="sxs-lookup"><span data-stu-id="4d928-124">Gets a list of locations and availability zones in those locations where the SKU is available.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Locations">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;string&gt; Locations { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;string&gt; Locations" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Models.ResourceSku.Locations" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Locations As IList(Of String)" />
      <MemberSignature Language="F#" Value="member this.Locations : System.Collections.Generic.IList&lt;string&gt;" Usage="Microsoft.Azure.Management.Compute.Models.ResourceSku.Locations" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="locations")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;System.String&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="4d928-125">Ruft die Gruppe von Standorten, dass die SKU verfügbar ist.</span><span class="sxs-lookup"><span data-stu-id="4d928-125">Gets the set of locations that the SKU is available.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Name">
      <MemberSignature Language="C#" Value="public string Name { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Name" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Models.ResourceSku.Name" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Name As String" />
      <MemberSignature Language="F#" Value="member this.Name : string" Usage="Microsoft.Azure.Management.Compute.Models.ResourceSku.Name" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
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
            <span data-ttu-id="4d928-126">Ruft den Namen der SKU.</span><span class="sxs-lookup"><span data-stu-id="4d928-126">Gets the name of SKU.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ResourceType">
      <MemberSignature Language="C#" Value="public string ResourceType { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ResourceType" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Models.ResourceSku.ResourceType" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ResourceType As String" />
      <MemberSignature Language="F#" Value="member this.ResourceType : string" Usage="Microsoft.Azure.Management.Compute.Models.ResourceSku.ResourceType" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="resourceType")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="4d928-127">Ruft den Typ der Ressource, für die SKU gilt.</span><span class="sxs-lookup"><span data-stu-id="4d928-127">Gets the type of resource the SKU applies to.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Restrictions">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Compute.Models.ResourceSkuRestrictions&gt; Restrictions { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Compute.Models.ResourceSkuRestrictions&gt; Restrictions" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Models.ResourceSku.Restrictions" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Restrictions As IList(Of ResourceSkuRestrictions)" />
      <MemberSignature Language="F#" Value="member this.Restrictions : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Compute.Models.ResourceSkuRestrictions&gt;" Usage="Microsoft.Azure.Management.Compute.Models.ResourceSku.Restrictions" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="restrictions")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Compute.Models.ResourceSkuRestrictions&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="4d928-128">Ruft die Einschränkungen, die aufgrund, die SKU verwendet werden kann.</span><span class="sxs-lookup"><span data-stu-id="4d928-128">Gets the restrictions because of which SKU cannot be used.</span></span> <span data-ttu-id="4d928-129">Dies ist leer, wenn es keine Einschränkungen gibt.</span><span class="sxs-lookup"><span data-stu-id="4d928-129">This is empty if there are no restrictions.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Size">
      <MemberSignature Language="C#" Value="public string Size { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Size" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Models.ResourceSku.Size" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Size As String" />
      <MemberSignature Language="F#" Value="member this.Size : string" Usage="Microsoft.Azure.Management.Compute.Models.ResourceSku.Size" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="size")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="4d928-130">Ruft die Größe der SKU.</span><span class="sxs-lookup"><span data-stu-id="4d928-130">Gets the Size of the SKU.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Tier">
      <MemberSignature Language="C#" Value="public string Tier { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Tier" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Models.ResourceSku.Tier" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Tier As String" />
      <MemberSignature Language="F#" Value="member this.Tier : string" Usage="Microsoft.Azure.Management.Compute.Models.ResourceSku.Tier" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="tier")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="4d928-131">Ruft gibt die Ebene der virtuellen Computer in einer Skala an. &amp;Lt; Br /&amp;Gt;&amp; Lt; Br /&amp;Gt; Mögliche Werte:&amp;Lt; Br /&amp;Gt;&amp; Lt; Br /&amp;Gt; **Standard**&amp;Lt; Br /&amp;Gt;&amp; Lt; Br /&amp;Gt; **Grundlegende**</span><span class="sxs-lookup"><span data-stu-id="4d928-131">Gets specifies the tier of virtual machines in a scale set.&amp;lt;br /&amp;gt;&amp;lt;br /&amp;gt; Possible Values:&amp;lt;br /&amp;gt;&amp;lt;br /&amp;gt; **Standard**&amp;lt;br /&amp;gt;&amp;lt;br /&amp;gt; **Basic**</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>